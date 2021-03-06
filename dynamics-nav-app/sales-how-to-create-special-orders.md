---
title: "Hvernig á að stofna sérpantanir"
description: "Hægt er að stofna sérpöntun um að vara sem ekki er tiltæk sé send tilteknum viðskiptamanni. Birgir sendir vöruna í vöruhús og þá má senda hana áfram til viðskiptamanns, annaðhvort sérstaklega eða með annarri pöntun."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6460c643a07f92e478aafb84044c90ff3ed3a236
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-special-orders"></a>Hvernig á að stofna sérpöntun
Hægt er að stofna sérpöntun um að vara sem ekki er tiltæk sé send tilteknum viðskiptamanni. Birgir sendir vöruna í vöruhús og þá má senda hana áfram til viðskiptamanns, annaðhvort sérstaklega eða með annarri pöntun.  

Sérpantanir gefa til kynna að innkaupa- og sölupöntun séu tengdar til að tryggja að sértæk vara utan birgða sé tínd og afhent viðskiptamanni.  

Þessa aðgerð er ekki hægt að nota nema búið sé að setja upp spjald fyrir viðskiptamann, lánardrottin og vöru svo hægt sé að vinna pöntunina.  

## <a name="to-create-a-special-order"></a>Stofnuð sérpöntun:  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Sölupöntun** og velja svo viðeigandi tengil.  
2. Valið er **Nýtt** aðgerð. Búin er til ný  sölupöntun fyrir vöruna. Nánari upplýsingar eru í [Hvernig á að: selja vörur.](sales-how-sell-products.md)
3.  Á flýtiflipanum **Línur** er fyllt út í sölulínuna. Í reitnum **Innkaupakóti** veljið innkaupakóta sem er með reitinn **Sérpöntun** valinn.

    Nú þarf að stofna innkaupapöntun út frá innkaupatillögu.  
4. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **innkaupatillaga** og velja svo viðeigandi tengil.  
5. Veljið aðgerðina **Sérpöntun** og veljið síðan aðgerðina **sækja sölupöntun**.  
6.  Í glugganum **Sækja sölupantanir** sýna niðurstöður þar sem **Númer fylgiskjals** er sölupöntunarnúmeri. Velja hnappinn **Í lagi**. Kerfið stofnar innkaupatillögulínu vegna vörunnar.  
7.  Í innkaupatillögulínunni skal velja **Nýtt** í reitnum **Aðgerðarboð**.  
8.  Í glugganum **Innkaupatillaga** veljið aðgerðina **Framkvæma aðgerðaboð**. Glugginn **Framkvæma aðgerðaboð - Tillaga** opnast. Velja hnappinn **Í lagi**.  

    Þá birtast boð þess efnis að innkaupapantanir hafi verið stofnaðar. Velja hnappinn **Í lagi**.  

Tekið er tillit til stofnaðrar innkaupapöntunar fyrir sérpöntun af kerfinu þar sem hún jafnar framboð og eftirspurn. Það er, innkaupapöntun (framboð) helst tengd við sölupöntun (eftirspurn) jafnvel þó innkaupapöntunin gæti lagt til fyrri eftirspurnar. Nánari upplýsingar eru í [Upplýsingar um hönnun: Endurpöntunarstefnur](design-details-reservation-order-tracking-and-action-messaging.md).  

> [!NOTE]  
>  Ekki er hægt að nota sérpöntunarkostinn ef varan er þegar frátekin. Þess vegna, fyrir vörur sem eru seldar með sérpöntunum, gakktu úr skugga um að **Frátekning** reiturinn á birgðaspjaldinu sé ekki stilltur á **Alltaf**.  

## <a name="see-also"></a>Sjá einnig  
[Hvernig á að: Vinna með Utanbirgðavörur](inventory-how-work-nonstock-items.md)  
[Sala](sales-manage-sales.md)  
[Hvernig á að: Gera beinar afhendingar](sales-how-drop-shipment.md)   
[Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reservation-order-tracking-and-action-messaging.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

