---
title: "Hönnunarupplýsingar - Leitað að víddarsamsetningum"
description: "Þegar þú lokar glugga eftir að hafa breytt víddasamstæðu metur [!INCLUDE[d365fin](includes/d365fin_md.md)] hvort þessi breytta víddasamstæða er til. Ef samstæðan er ekki til er ný samstæða búin til og víddarsamsetningarkenninu er skilað."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1e3bbad5d5f809068b88f6bbf5d0deaa22b38427
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-searching-for-dimension-combinations"></a>Hönnunarupplýsingar Leitað að víddarsamsetningum
Þegar þú lokar glugga eftir að hafa breytt víddsamstæðu metur [!INCLUDE[d365fin](includes/d365fin_md.md)] hvort þessi breytta víddasamstæða er til. Ef samstæðan er ekki til er ný samstæða búin til og víddarsamsetningarkenninu er skilað.  

## <a name="building-search-tree"></a>Byggir leitartré  
 Tafla 481 **Víddasamstæðutrjáhnútu** er notað þegar [!INCLUDE[d365fin](includes/d365fin_md.md)] metur hvort víddasamstæðamál er þegar til í töflu 480 **Víddasamstæðufærsla**. Matið er framkvæmt með því fara yfir leitartré frá efsta stig 0. Efsta stig 0 táknar víddasamstæðu án víddasamstæðufærslna. Undireiningar þessarar víddasamstæðu tákna víddasamstæður með einni víddasamstæðufærslu. Undireiningar þessara víddasamstæða standa fyrir tvær undireiningar og svo framvegis.  

### <a name="example-1"></a>Dæmi 1  
 Eftirfarandi skýringarmynd leitartré með sex víddasamstæðum. Aðeins eru einkennandi víddasamstæðufærslur sýndar á myndinni.  

 ![Víddartjástrúktur](media/nav2013_dimension_tree.png "NAV2013_Vídd_Tré")  

 Eftirfarandi tafla lýsir a fullgerðum lista víddasamstæðufærsla sem mynda hverja víddasamstæðu.  

|Víddasamstæður|Víddasamstæðufærslur|  
|--------------------|---------------------------|  
|Sett 0|Ekkert|  
|Sett 1|AREA 30|  
|Sett 2|AREA 30, DEPT ADM|  
|Sett 3|AREA 30, DEPT PROD|  
|Sett 4|AREA 30, DEPT ADM, PROJ VW|  
|Sett 5|AREA 40|  
|Sett 6|AREA 40, PROJ VW|  

### <a name="example-2"></a>Dæmi 2  
 Þetta dæmi sýnir hvernig [!INCLUDE[d365fin](includes/d365fin_md.md)] metur hvort víddarsamstæða sem samanstendur af færslum AREA 40, DEPT PROD sé til.  

 Fyrst mun [!INCLUDE[d365fin](includes/d365fin_md.md)] einnig uppfæra töfluna **Trjáhnútur víddasamstæðu** til að tryggja að leitartréð líti eins út og eftirfarandi teikning. Því verður víddasamstæða 7 undireining víddasamstæðu 5.  

 ![NAV2013&#95;Vídd&#95;Tré&#95;Dæmi 2](media/nav2013_dimension_tree_example2.png "NAV2013_Vídd_Tré_Dæmi2")  

### <a name="finding-dimension-set-id"></a>Finna auðkenni víddasamstæðu  
 Á hugmyndastigi eru **Yfireining**, **Vídd og** **Víddargildi** í leitartrénu sameinuð og notuð sem aðallykill vegna þess að [!INCLUDE[d365fin](includes/d365fin_md.md)] fer yfir tréð á sama hátt og víddarfærslurnar. GET-eiginleikinn (skrá) er notaður til að leita að auðkenni víddasamstæðu. Eftirfarandi kóðadæmi sýnir hvernig á að finna auðkenni víddasamstæðu þegar það eru víddagildi eru þrjú.  

```  
DimSet."Parent ID" := 0;  // 'root'  
IF UserDim.FINDSET THEN  
  REPEAT  
      DimSet.GET(DimSet."Parent ID",UserDim.DimCode,UserDim.DimValueCode);  
  UNTIL UserDim.NEXT = 0;  
EXIT(DimSet.ID);  

```  

 Hins vegar, til að varðveita getu [!INCLUDE[d365fin](includes/d365fin_md.md)] til að endurnefna vídd og víddargildi, er aukið við töflu 348 **Víddargildi** með heiltölureitnum **Víddargildiskenni**. Taflan breytir reitaparinu **Vídd** og **Víddargildi** í heiltölu gildi. Þegar þú endurnefnir víddir og víddargildi er gilum í heilum tölum ekki breytt.  

```  
DimSet."Parent ID" := 0;  // 'root'  
IF UserDim.FINDSET THEN  
  REPEAT  
      DimSet.GET(DimSet.ParentID,UserDim."Dimension Value ID");  
  UNTIL UserDim.NEXT = 0;  
EXIT(DimSet.ID);  

```  

## <a name="see-also"></a>Sjá einnig  
 [GET Eiginleiki (Skrá)](https://msdn.microsoft.com/en-us/library/dd301056.aspx)    
 [Hönnunarupplýsingarn: Færslur víddarsamstæða](design-details-dimension-set-entries.md)   
 [Yfirlit yfir víddasamstæðufærslur](design-details-dimension-set-entries-overview.md)   
 [Hönnunarupplýsingar töfluuppbygging](design-details-table-structure.md)   
 [Hönnunarupplýsingar: Codeunit 408 víddarstjórnun](design-details-codeunit-408-dimension-management.md)   
 [Hönnunarupplýsingar: Kóðadæmi um breytt mynstur í Breytingar](design-details-code-examples-of-changed-patterns-in-modifications.md)

