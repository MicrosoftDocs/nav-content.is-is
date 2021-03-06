---
title: "Hvernig á að nota vörusamsafn í framleiðslu"
description: "Þegar grunndagatal er sérsniðið fyrir fyrirtækið eða einhvern viðskiptafélaga eru breytingar á frídögum og virkum dögum færðar inn."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/05/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4ad54585baef119db06bf69476739174af1209bb
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-production-families"></a>Hvernig á að: vinna með framleiðslusamsafn
Framleiðslusamsafn er hópur einstakra vara sem byggðar eru á líku framleiðsluferli. Með því að mynda framleiðslusamsöfn er hægt að framleiða sumar vörur tvisvar eða oftar í einni vinnslu, en þetta fínstillir efnisnotkun.

Í reit **Magn** í glugganum **Samsafn** er fært inn magnið sem framleitt hefur verið þegar allt samsafnið hefur verið framleitt einu sinni.

## <a name="example"></a>Dæmi
Við stönsun er hægt að framleiða fjögur stykki af sömu vörunni úr einni plötu og 10 stykki af annarri, ólíkri vöru, á sama tíma. Stansvélin mótar öll 14 stykkin í einu þrepi.

Stofnun framleiðslusamsafna dregur úr úrkastsmagninu vegna þess að það sem myndi venjulega vera afgangsúrkast, við framleiðslu stærri stykkja, er í staðinn notað til að framleiða minni hluti.

## <a name="to-set-up-a-production-family"></a>Uppsetning framleiðslusamsafns
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Samsafn** og velja svo viðeigandi tengil.
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-produce-based-on-a-production-familily"></a>Framleiða byggir á framleiðslusamsafni
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Fastáætluð framleiðslupöntun** og velja svo viðeigandi tengil.
2. Stofna nýja framleiðslupöntun Frekari upplýsingar, sjá [Hvernig skal: Stofna framleiðslupantanir](production-how-to-create-production-orders.md).
3. Í reitnum **Gerð uppruna**, veljið **Samsafn**.  
4. Í reitnum **Forðanr.** er viðeigandi framleiðslusamsafn valið.

## <a name="see-also"></a>Sjá einnig
[Hvernig á að stofna nýjar framl.uppskriftir](production-how-to-create-production-boms.md)  
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Framleiðsla](production-manage-manufacturing.md)    
[Áætlun](production-planning.md)   
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

