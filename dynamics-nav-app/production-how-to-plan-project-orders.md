---
title: "Hvernig á að áætla verkefnispantanir"
description: "Þessi áætlanagerð byrjar í sölupöntun og nýtir gluggann **Áætlun sölupöntunar**. Þegar framleiðslupöntun verkefnis er stofnuð er hægt að skipuleggja hana frekar með því að nota gluggann **Pantanaáætlun**."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a03cdaf16b25cbcf030e9a33c538ea3df96a1fe9
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-plan-project-orders"></a>Hvernig á að áætla verkefnispantanir
Þessi áætlanagerð byrjar í sölupöntun og nýtir gluggann  **Áætlun sölupöntunar**. Þegar framleiðslupöntun verkefnis er stofnuð er hægt að skipuleggja hana frekar með því að nota gluggann **Pantanaáætlun**.  

## <a name="to-create-a-project-production-order"></a>Framleiðslupöntun verkefnis stofnuð  

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Sölupantanir** og velja svo viðeigandi tengil.  
2.  Veljið sölupöntunina sem sýnir framleiðsluverkefnið, og veljið síðan aðgerðina **Áætla**.  
4.  Í glugganum **Áætlun sölupöntunar** er smellt á aðgerðina **Stofna framl.pöntun**.  
5.  Í glugganum **Stofna pöntun úr sölu** í reitnum **Tegund pöntunar** er **Verkefnispöntun** valin.  
6.  Velja hnappinn **Já**.  
7.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **framleiðslupantanir** og velja svo viðeigandi tengil.
8. Opna skal nýstofnaða framleiðslupöntun.  

    Athugið að reiturinn **Tegund uppruna** í framleiðslupöntuninni inniheldur **Söluhaus** og hún hefur margar línur, eina fyrir hverja vöru sölulínu sem þarf að framleiða.  
9. Veldu aðgerðina **Áætlun**.
10. Í glugganum **Pantanaáætlun** er smellt á **Uppfæra** aðgerðina til reikna nýja eftirspurn.  

Pöntunarhausslínan fyrir verkefnispöntunina birtist með allar óuppfylltar eftirspurnarlínur stækkaðar neðan hennar. Þótt framleiðslupöntunin innihaldi línur fyrir nokkrar framleiddar vörur er heildareftirspurnin fyrir allar framleiðslupöntunarlínur skráð undir einni pöntunarhausslínu í glugganum **Pantanaáætlun**, auk þess sem nafn upprunalega viðskiptamannsins er birt. Nú er hægt að áætla eftirspurn eins og lýst er í [Hvernig á að: Áætla nýja eftirspurn pöntun fyrir pöntun](production-how-to-plan-for-new-demand.md).  

> [!NOTE]  
>  Eftirspurnarlínur í framleiðslupöntun verkefnisins sem hafa **Framl.pöntun** í reitnum **Áfyllingarkerfi** tákna undirliggjandi framleiðslupantanir. Eftir að hafa myndað þessar framleiðslupantanir, þarf að reikna aftur út áætlun í glugganum **Pantanaáætlun** til að auðkenna alla óuppfyllta eftirspurn eftir íhlutum fyrir þær. Í því tilviki er birtist eftirspurnin í eftirspurnarlínum undir línu í haus venjulegrar framleiðslupöntunar sem þýðir að verkefnistengslin sjást ekki lengur í glugganum. Ef á hinn bóginn notast er við eiginleikann Rekja pöntun er hægt að fara fram og aftur í allar framboðspantanir undir upphaflegu sölupöntuninni.  

## <a name="see-also"></a>Sjá einnig
[Áætlun](production-planning.md)   
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Framleiðsla](production-manage-manufacturing.md)    
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Hönnunarupplýsingar: framboðsáætlun](design-details-supply-planning.md)   
[Uppsetning bestu venja: Framboðsáætlun](setup-best-practices-supply-planning.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

