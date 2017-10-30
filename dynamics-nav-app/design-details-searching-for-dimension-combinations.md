---
title: "Hönnunarupplýsingar - Leitað að víddarsamsetningum"
description: "Þegar þú lokar glugga eftir að hafa breytt víddasamstæðu metur [!INCLUDE[d365fin](includes/d365fin_md.md)] hvort þessi breytta víddasamstæða er til. Ef samstæðan er ekki til er ný samstæða búin til og víddarsamsetningarkenninu er skilað."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
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
# <a name="design-details-searching-for-dimension-combinations"></a><span data-ttu-id="32c5f-104">Hönnunarupplýsingar Leitað að víddarsamsetningum</span><span class="sxs-lookup"><span data-stu-id="32c5f-104">Design Details: Searching for Dimension Combinations</span></span>
<span data-ttu-id="32c5f-105">Þegar þú lokar glugga eftir að hafa breytt víddsamstæðu metur [!INCLUDE[d365fin](includes/d365fin_md.md)] hvort þessi breytta víddasamstæða er til.</span><span class="sxs-lookup"><span data-stu-id="32c5f-105">When you close a window after you edit a set of dimensions, [!INCLUDE[d365fin](includes/d365fin_md.md)] evaluates whether the edited set of dimensions exists.</span></span> <span data-ttu-id="32c5f-106">Ef samstæðan er ekki til er ný samstæða búin til og víddarsamsetningarkenninu er skilað.</span><span class="sxs-lookup"><span data-stu-id="32c5f-106">If the set does not exist, a new set is created and the dimension combination ID is returned.</span></span>  

## <a name="building-search-tree"></a><span data-ttu-id="32c5f-107">Byggir leitartré</span><span class="sxs-lookup"><span data-stu-id="32c5f-107">Building Search Tree</span></span>  
 <span data-ttu-id="32c5f-108">Tafla 481 **Víddasamstæðutrjáhnútu** er notað þegar [!INCLUDE[d365fin](includes/d365fin_md.md)] metur hvort víddasamstæðamál er þegar til í töflu 480 **Víddasamstæðufærsla**.</span><span class="sxs-lookup"><span data-stu-id="32c5f-108">Table 481 **Dimension Set Tree Node** is used when [!INCLUDE[d365fin](includes/d365fin_md.md)] evaluates whether a set of dimensions already exists in table 480 **Dimension Set Entry** table.</span></span> <span data-ttu-id="32c5f-109">Matið er framkvæmt með því fara yfir leitartré frá efsta stig 0.</span><span class="sxs-lookup"><span data-stu-id="32c5f-109">The evaluation is performed by recursively traversing the search tree starting at the top level numbered 0.</span></span> <span data-ttu-id="32c5f-110">Efsta stig 0 táknar víddasamstæðu án víddasamstæðufærslna.</span><span class="sxs-lookup"><span data-stu-id="32c5f-110">The top level 0 represents a dimension set with no dimension set entries.</span></span> <span data-ttu-id="32c5f-111">Undireiningar þessarar víddasamstæðu tákna víddasamstæður með einni víddasamstæðufærslu.</span><span class="sxs-lookup"><span data-stu-id="32c5f-111">The children of this dimension set represent dimension sets with only one dimension set entry.</span></span> <span data-ttu-id="32c5f-112">Undireiningar þessara víddasamstæða standa fyrir tvær undireiningar og svo framvegis.</span><span class="sxs-lookup"><span data-stu-id="32c5f-112">The children of these dimension sets represent dimension sets with two children, and so on.</span></span>  

### <a name="example-1"></a><span data-ttu-id="32c5f-113">Dæmi 1</span><span class="sxs-lookup"><span data-stu-id="32c5f-113">Example 1</span></span>  
 <span data-ttu-id="32c5f-114">Eftirfarandi skýringarmynd leitartré með sex víddasamstæðum.</span><span class="sxs-lookup"><span data-stu-id="32c5f-114">The following diagram represents a search tree with six dimension sets.</span></span> <span data-ttu-id="32c5f-115">Aðeins eru einkennandi víddasamstæðufærslur sýndar á myndinni.</span><span class="sxs-lookup"><span data-stu-id="32c5f-115">Only the distinguishing dimension set entry is displayed in the diagram.</span></span>  

 <span data-ttu-id="32c5f-116">![Víddartjástrúktur](media/nav2013_dimension_tree.png "NAV2013_Vídd_Tré")</span><span class="sxs-lookup"><span data-stu-id="32c5f-116">![Dimension tree structure](media/nav2013_dimension_tree.png "NAV2013_Dimension_Tree")</span></span>  

 <span data-ttu-id="32c5f-117">Eftirfarandi tafla lýsir a fullgerðum lista víddasamstæðufærsla sem mynda hverja víddasamstæðu.</span><span class="sxs-lookup"><span data-stu-id="32c5f-117">The following table describes a complete list of dimension set entries that make up each dimension set.</span></span>  

|<span data-ttu-id="32c5f-118">Víddasamstæður</span><span class="sxs-lookup"><span data-stu-id="32c5f-118">Dimension Sets</span></span>|<span data-ttu-id="32c5f-119">Víddasamstæðufærslur</span><span class="sxs-lookup"><span data-stu-id="32c5f-119">Dimension Set Entries</span></span>|  
|--------------------|---------------------------|  
|<span data-ttu-id="32c5f-120">Sett 0</span><span class="sxs-lookup"><span data-stu-id="32c5f-120">Set 0</span></span>|<span data-ttu-id="32c5f-121">Ekkert</span><span class="sxs-lookup"><span data-stu-id="32c5f-121">None</span></span>|  
|<span data-ttu-id="32c5f-122">Sett 1</span><span class="sxs-lookup"><span data-stu-id="32c5f-122">Set 1</span></span>|<span data-ttu-id="32c5f-123">AREA 30</span><span class="sxs-lookup"><span data-stu-id="32c5f-123">AREA 30</span></span>|  
|<span data-ttu-id="32c5f-124">Sett 2</span><span class="sxs-lookup"><span data-stu-id="32c5f-124">Set 2</span></span>|<span data-ttu-id="32c5f-125">AREA 30, DEPT ADM</span><span class="sxs-lookup"><span data-stu-id="32c5f-125">AREA 30, DEPT ADM</span></span>|  
|<span data-ttu-id="32c5f-126">Sett 3</span><span class="sxs-lookup"><span data-stu-id="32c5f-126">Set 3</span></span>|<span data-ttu-id="32c5f-127">AREA 30, DEPT PROD</span><span class="sxs-lookup"><span data-stu-id="32c5f-127">AREA 30, DEPT PROD</span></span>|  
|<span data-ttu-id="32c5f-128">Sett 4</span><span class="sxs-lookup"><span data-stu-id="32c5f-128">Set 4</span></span>|<span data-ttu-id="32c5f-129">AREA 30, DEPT ADM, PROJ VW</span><span class="sxs-lookup"><span data-stu-id="32c5f-129">AREA 30, DEPT ADM, PROJ VW</span></span>|  
|<span data-ttu-id="32c5f-130">Sett 5</span><span class="sxs-lookup"><span data-stu-id="32c5f-130">Set 5</span></span>|<span data-ttu-id="32c5f-131">AREA 40</span><span class="sxs-lookup"><span data-stu-id="32c5f-131">AREA 40</span></span>|  
|<span data-ttu-id="32c5f-132">Sett 6</span><span class="sxs-lookup"><span data-stu-id="32c5f-132">Set 6</span></span>|<span data-ttu-id="32c5f-133">AREA 40, PROJ VW</span><span class="sxs-lookup"><span data-stu-id="32c5f-133">AREA 40, PROJ VW</span></span>|  

### <a name="example-2"></a><span data-ttu-id="32c5f-134">Dæmi 2</span><span class="sxs-lookup"><span data-stu-id="32c5f-134">Example 2</span></span>  
 <span data-ttu-id="32c5f-135">Þetta dæmi sýnir hvernig [!INCLUDE[d365fin](includes/d365fin_md.md)] metur hvort víddarsamstæða sem samanstendur af færslum AREA 40, DEPT PROD sé til.</span><span class="sxs-lookup"><span data-stu-id="32c5f-135">This example shows how [!INCLUDE[d365fin](includes/d365fin_md.md)] evaluates whether a dimension set that consists of the dimension set entries AREA 40, DEPT PROD exists.</span></span>  

 <span data-ttu-id="32c5f-136">Fyrst mun [!INCLUDE[d365fin](includes/d365fin_md.md)] einnig uppfæra töfluna **Trjáhnútur víddasamstæðu** til að tryggja að leitartréð líti eins út og eftirfarandi teikning.</span><span class="sxs-lookup"><span data-stu-id="32c5f-136">First, [!INCLUDE[d365fin](includes/d365fin_md.md)] also updates the **Dimension Set Tree Node** table to make sure that the search tree looks like the following diagram.</span></span> <span data-ttu-id="32c5f-137">Því verður víddasamstæða 7 undireining víddasamstæðu 5.</span><span class="sxs-lookup"><span data-stu-id="32c5f-137">Thus dimension set 7 becomes a child of the dimension set 5.</span></span>  

 <span data-ttu-id="32c5f-138">![NAV2013&#95;Vídd&#95;Tré&#95;Dæmi 2](media/nav2013_dimension_tree_example2.png "NAV2013_Vídd_Tré_Dæmi2")</span><span class="sxs-lookup"><span data-stu-id="32c5f-138">![NAV2013&#95;Dimension&#95;Tree&#95;Example 2](media/nav2013_dimension_tree_example2.png "NAV2013_Dimension_Tree_Example2")</span></span>  

### <a name="finding-dimension-set-id"></a><span data-ttu-id="32c5f-139">Finna auðkenni víddasamstæðu</span><span class="sxs-lookup"><span data-stu-id="32c5f-139">Finding Dimension Set ID</span></span>  
 <span data-ttu-id="32c5f-140">Á hugmyndastigi eru **Yfireining**, **Vídd og** **Víddargildi** í leitartrénu sameinuð og notuð sem aðallykill vegna þess að [!INCLUDE[d365fin](includes/d365fin_md.md)] fer yfir tréð á sama hátt og víddarfærslurnar.</span><span class="sxs-lookup"><span data-stu-id="32c5f-140">At a conceptual level, **Parent ID**, **Dimension**, and **Dimension Value**, in the search tree, are combined and used as the primary key because [!INCLUDE[d365fin](includes/d365fin_md.md)] traverses the tree in the same order as the dimension entries.</span></span> <span data-ttu-id="32c5f-141">GET-eiginleikinn (skrá) er notaður til að leita að auðkenni víddasamstæðu.</span><span class="sxs-lookup"><span data-stu-id="32c5f-141">The GET function (record) is used to search for dimension set ID.</span></span> <span data-ttu-id="32c5f-142">Eftirfarandi kóðadæmi sýnir hvernig á að finna auðkenni víddasamstæðu þegar það eru víddagildi eru þrjú.</span><span class="sxs-lookup"><span data-stu-id="32c5f-142">The following code example shows how to find the dimension set ID when there are three dimension values.</span></span>  

```  
DimSet."Parent ID" := 0;  // 'root'  
IF UserDim.FINDSET THEN  
  REPEAT  
      DimSet.GET(DimSet."Parent ID",UserDim.DimCode,UserDim.DimValueCode);  
  UNTIL UserDim.NEXT = 0;  
EXIT(DimSet.ID);  

```  

 <span data-ttu-id="32c5f-143">Hins vegar, til að varðveita getu [!INCLUDE[d365fin](includes/d365fin_md.md)] til að endurnefna vídd og víddargildi, er aukið við töflu 348 **Víddargildi** með heiltölureitnum **Víddargildiskenni**.</span><span class="sxs-lookup"><span data-stu-id="32c5f-143">However, to preserve the ability of [!INCLUDE[d365fin](includes/d365fin_md.md)] to rename a dimension and dimension value, table 348 **Dimension Value** is extended with an integer field of **Dimension Value ID**.</span></span> <span data-ttu-id="32c5f-144">Taflan breytir reitaparinu **Vídd** og **Víddargildi** í heiltölu gildi.</span><span class="sxs-lookup"><span data-stu-id="32c5f-144">This table converts the field pair **Dimension** and **Dimension Value** to an integer value.</span></span> <span data-ttu-id="32c5f-145">Þegar þú endurnefnir víddir og víddargildi er gilum í heilum tölum ekki breytt.</span><span class="sxs-lookup"><span data-stu-id="32c5f-145">When you rename the dimension and dimension value, the integer value is not changed.</span></span>  

```  
DimSet."Parent ID" := 0;  // 'root'  
IF UserDim.FINDSET THEN  
  REPEAT  
      DimSet.GET(DimSet.ParentID,UserDim."Dimension Value ID");  
  UNTIL UserDim.NEXT = 0;  
EXIT(DimSet.ID);  

```  

## <a name="see-also"></a><span data-ttu-id="32c5f-146">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="32c5f-146">See Also</span></span>  
 <span data-ttu-id="32c5f-147">[GET Eiginleiki (Skrá)](https://msdn.microsoft.com/en-us/library/dd301056.aspx)  </span><span class="sxs-lookup"><span data-stu-id="32c5f-147">[GET Function (Record)](https://msdn.microsoft.com/en-us/library/dd301056.aspx)  </span></span>  
 <span data-ttu-id="32c5f-148">[Hönnunarupplýsingarn: Færslur víddarsamstæða](design-details-dimension-set-entries.md) </span><span class="sxs-lookup"><span data-stu-id="32c5f-148">[Design Details: Dimension Set Entries](design-details-dimension-set-entries.md) </span></span>  
 <span data-ttu-id="32c5f-149">[Yfirlit yfir víddasamstæðufærslur](design-details-dimension-set-entries-overview.md) </span><span class="sxs-lookup"><span data-stu-id="32c5f-149">[Dimension Set Entries Overview](design-details-dimension-set-entries-overview.md) </span></span>  
 <span data-ttu-id="32c5f-150">[Hönnunarupplýsingar töfluuppbygging](design-details-table-structure.md) </span><span class="sxs-lookup"><span data-stu-id="32c5f-150">[Design Details: Table Structure](design-details-table-structure.md) </span></span>  
 <span data-ttu-id="32c5f-151">[Hönnunarupplýsingar: Codeunit 408 víddarstjórnun](design-details-codeunit-408-dimension-management.md) </span><span class="sxs-lookup"><span data-stu-id="32c5f-151">[Design Details: Codeunit 408 Dimension Management](design-details-codeunit-408-dimension-management.md) </span></span>  
 [<span data-ttu-id="32c5f-152">Hönnunarupplýsingar: Kóðadæmi um breytt mynstur í Breytingar</span><span class="sxs-lookup"><span data-stu-id="32c5f-152">Design Details: Code Examples of Changed Patterns in Modifications</span></span>](design-details-code-examples-of-changed-patterns-in-modifications.md)
