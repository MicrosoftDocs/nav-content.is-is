---
title: "Valfrjálsar aðgerðir fyrir lokun tímabila"
description: "Þetta efnisatriði útskýrir valfrjáls ferli og aðgerðir fyrir lokun fjárhagstímabila í Dynamics NAV."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, aging, creditor payments, vendor payments
ms.date: 08/10/2018
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ca22e72552c69d3bcb0b85101b586796ff026896
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="overview-of-tasks-to-close-accounting-periods"></a>Yfirlit yfir verkhluta sem felur í sér lokun fjárhagstímabila
[!INCLUDE[d365fin](includes/d365fin_md.md)] þvingar þig ekki til að loka tímabilum, en það eru margar aðgerðir í lokunartíma (lok mánaðar) sem þú getur gert. Þetta efni gefur yfirlit yfir valfrjáls ferli og starfsemi fyrir lokunartímabil.  

## <a name="general-ledger"></a>Fjárhagur
* Tilgreindu kerfisbundið og notendasértækt bókunartímabil.  

    Þetta tilgreinir dagsetningar þar sem hægt er að bóka. Þú gætir viljað leyfa bókun í byrjun tímabilsins eða í lok tímabilsins, allt eftir fyrirtækinu. Nánari upplýsingar eru í [Hvernig á að tilgreina bókunartímabil](finance-how-specify-posting-periods.md).  
* Allar nauðsynlegar fjárhagsleiðréttingar eru framkvæmdar.  
* Ítrekunarbækur eru uppfærðar og bókaðar.  
  <!--* Process Consolidations-->
* Fjárhagsskema keyrt sem hér segir:  
  * Glugginn **Fjárhagsskema** er opnaður og smellt á aðgerðina **Prenta**.  

## <a name="sales-and-receivables"></a>Sala and útistandandi
* Allar sölupantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.  
* Inngreiðslubókin er bókuð.  
* Uppfæra og birta bækur tímarit sem tengjast sölu og útistandandi.  
* Afstemma viðskiptakröfur við færslubók.  
* Runuvinnslan **Eyða reikningsf. sölupöntunum** er keyrð.  

## <a name="purchases-and-payables"></a>Innkaup og viðskiptaskuldir
* Allar pantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.  
* Allar greiðslubækur eru bókaðar.  
* Ítrekunarfærslubækur tengdar innkaupum og viðskiptaskuldum eru uppfærðar og bókaðar.  
* Skýrslan **Aldursgreindar skuldir** er keyrð og skuldir stemmdar af við fjárhaginn.  
* Runuvinnslan **Eyða reikningsf. innk.pöntunum** er keyrð.  

## <a name="fixed-assets"></a>Eignir
* Allur viðhaldskostnaður hefur verið bókaður í gegnum Eignabók eða Reikningar
* Leiðréttingar eru bókaðar
* Uppfærsla er bókuð
* Afskriftir eru bókaðar
* Ítrekunarbók eigna er uppfærð og bókuð.

## <a name="intercompany"></a>Milli fyrirtækja
* Vinna úr færslum á milli fyrirtækja

## <a name="calculate-and-process-sales-tax"></a>VSK er reiknaður og unninn
* Lokið er við skattyfirlit.  

## <a name="see-also"></a>Sjá einnig
[Lokaár og Tímabil](year-close-years-periods.md)  
[Bókum lokað](year-close-books.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

