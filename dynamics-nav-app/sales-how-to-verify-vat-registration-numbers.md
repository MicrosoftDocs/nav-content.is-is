---
title: "Hvernig á að staðfesta VSK-númer"
description: "Hægt er að nota EB vefþjónustu til að staðfesta að VSK-númer sem þú slærð inn í viðskiptamann, lánardrottinn eða tengiliðaspjöld séu gild."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/10/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8ed345e346ba32a38ebb2738afbe6c12749842ff
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-verify-vat-registration-numbers"></a>Hvernig á að staðfesta VSK-númer
Hægt er að nota EB vefþjónustu til að staðfesta að VSK-númer sem þú slærð inn í viðskiptamann, lánardrottinn eða tengiliðaspjöld séu gild.  

 Þegar þú breytir **VSK númer** reitnum á korti þar sem gildið í **land/svæði kóði** reitnum er innan Land/svæði Evrópusambandsins, eru nýja VSK-númerið þitt og notandakenni skráð í **VSK Skráningarkladdi** gluggann. Þú sannprófar VSK-númer með því að velja **Staðfesta skráningarnúmer** hnappinn í **VSK Skráningarkladdi** gluggann. Ný lína er stofnuð í hvert skipti sem staðfestingaraðgerðin er notuð. Ef hægt var að sannprófa tölurnar inniheldur **Staða** reiturinn **Gilt**. Ef ekki er hægt að sannprófa töluna inniheldur **Staða** reiturinn **Ógilt** og þú verður að breyta tölunni í **VSK Númer** reitnum á kortinu og hefja sannprófunina aftur.  

 Vefslóð sjálfgefinnar vefþjónustu er sett upp í **VSK skráningarnúmer sannprófun vefslóð** reitnum í **Uppsetning fjárhags** glugganum.  

 Í **VSK Skráningarnúmerasnið** töflunni er hægt að breyta fyrir hvert landsvæði mismunandi snið VSK-skráningarnúmera sem notendur hafa leyfi til að slá inn í **VSK skráningarnúmer** reitinn  

> [!WARNING]  
>  Þessi vefþjónusta notar http-reglur, sem táknar að gagnaflutningur um þjónustuna er ekki dulritaður.  

> [!NOTE]  
>  Þú getur upplifað niðurtíma fyrir þessa þjónustu sem Microsoft er ekki ábyrgt fyrir, þar sem þjónustan er hluti af breiðu EB neti landsbundinna VSK-skráa.  

## <a name="to-verify-a-vat-registration-number-from-a-customer-card"></a>Til að staðfesta VSK-númer af viðskiptamannaspjaldi  
Eftirfarandi lýsir því hvernig skal sannprófa VSK númer fyrir viðskiptamann. Skrefin eru svipuð fyrir lánardrottinn og tengilið.   
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **viðskiptamenn** og velja svo viðeigandi tengil.  

2.  Opnaðu spjald viðskiptamannsins þar sem þú vilt staðfesta NVS-númerið.  

    > [!NOTE]  
    >  **Land/svæði kóði** Reiturinn á viðskiptamannaspjaldinu þarf að innhalda land/svæði innan Evrópusambandsins.  
3.  Á flýtiflipanum **Reikningsfæra** velurðu hnappinn KafaNiður við hlið **VSK skráningarnúmer** reitarins.  

    **VSK skráningarkladdi** glugginn opnast með einni línu þar sem **Staða** reiturinn inniheldur **Ekki sannvottað**.  
4.  Velja **Staðfestið skráningarnúmer** aðgerðina.  

     Ný lína er stofnuð þar sem **Staða** reiturinn inniheldur annað hvort **Gilt** eða **Ógilt**.  
5.  Ef **Staða** reiturinn inniheldur **Ógilt** skaltu breyta númerinu í **VSK númer** reitnum á spjaldinu og endurtaka svo skref 3 og 4.  

## <a name="see-also"></a>Sjá einnig  
[Fjármál](finance.md)  
[Hvernig á að: Skrá nýja viðskiptamenn](sales-how-register-new-customers.md)  
[Hvernig á að Skrá nýja lánardrottna](purchasing-how-register-new-vendors.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

