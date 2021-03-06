---
title: "Yfirlit yfir uppsetningar fyrir þjónustuvörur og þjónustuvörueiningar"
description: "Lærðu um hluti sem þú verður að setja upp áður en þú getur notað þjónustuvörur, eins og sjálfgefin gildi á borð við svartíma, samningsafslátt í prósentum og þjónustuverðflokk."
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
ms.openlocfilehash: 0632bdc3b12e60c9b49893df748e8ca165c5b9d4
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-service-items-and-service-item-components"></a>Hvernig á að: setja upp þjónustuvörur og þjónustuvörueiningar
Áður en þú vinnur með þjónustuvörur verður þú að setja upp eftirfarandi:

* Þjónustuvöruflokkar 
* Valfrjálst

## <a name="to-set-up-service-item-groups"></a>Setja upp þjónustuvöruflokka
Þú getur setja upp þjónustuvöruflokka sem tengjast hvað varðar viðgerð og viðhaldi. Skilgreina má sjálfgefin gildi vegna þjónustuvöru í þjónustuvöruflokki, t.d. svartíma, samningsafslátt í prósentum og þjónustuverðflokk. Hægt er að ráða því hvort vara í þjónustuvöruflokki sé sjálfkrafa skráð sem þjónustuvara þegar hún er seld.  
  
Þjónustuvöruflokkum er úthlutað til vöru á **birgða** spjaldi og þjónustuvöru á **þjónustuvöru** spjaldi.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuvöruflokkar** og velja svo viðeigandi tengil.  
2. Nýr þjónustuvöruflokkur er stofnaður.  
3. Fyllt er í reitina **Kóti** og **Lýsing**.  
4. Í reitinn **Sjálfg. samningsafsláttar %** er færð inn sjálfgefin prósenta samningsafsláttar sem á að eiga við þjónustuvöruna í flokknum.  
5. Í reitinn **Kóti sjálfg. Þjónustuverðfl.** er færður inn kóti sjálfgefins þjónustuverðflokks sem á að eiga við þjónustuvöruna í flokknum.  
6. Í reitinn **Sjálfgefinn svartími (klst.)** er færður inn sjálfgefinn svartími í klukkustundum sem á að gilda um þjónustuvöruna í flokknum.  
7. Ef skrá á vöru í flokknum sem þjónustuvöru þegar hún er seld þarf að velja reitinn **Stofna þjónustuvöru**.  

## <a name="to-set-up-service-item-components"></a>Uppsetning þjónustuvöruíhluta
Í þjónustuvöru geta verið margir íhlutir sem skipta má út með varahlutum þegar varan er í þjónustu. Þessir íhlutir eru uppsettir í síðunni **Þjónustuvara íhlutalisti**. Ef setja á upp íhluta vegna þjónustuvöru sem er uppskrift er hægt að afrita uppskriftarvöruna og stofna hana sem íhluti þjónustuvöru. 
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuvörur** og velja svo viðeigandi tengil. 
2. Opna skal þjónustuvöruna sem á að setja upp íhluti fyrir.  
3. Velja aðgerðina **Íhlutir**. Glugginn **Þjónustuvöruíhlutalisti** opnast.  
4. Bæta við nýjum íhlut.  
5. Í reitnum **Tegund** skal velja **Þjónustuvara** ef íhluturinn sjálfur er skráð þjónustuvara. Að öðrum kosti skal velja **Vara**.  
6. Í reitnum **númer** skal velja vöruna eða þjónustuvöruna sem er íhlutur þjónustuvörunnar.  

## <a name="to-set-up-service-item-components-from-a-bom"></a>Uppsetning þjónustuvöruíhluta út frá uppskriftum
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuvörur** og velja svo viðeigandi tengil.  
2. Opna skal þjónustuvöruna sem setja á upp íhluti út frá uppskrift fyrir.  
3. Velja aðgerðina **Íhlutir**. Glugginn **Þjónustuvöruíhlutalisti** opnast.  
4. Valið er **Afrita úr uppskrift** aðgerð.  
  
    Ef varan sem þjónustuvaran tengist er uppskrift stofnuð sjálfkrafa fyrir íhluti fyrir alla vöru í uppskriftinni.  

## <a name="to-set-up-a-service-shelf"></a>Uppsetning þjónustuhillu
Þú getur sett upp þjónustuhillur sem tilgreina hvar þú geymir þjónustuvörur þínar. Þjónustuhillum er úthlutað til þjónustuvöru í síðunum **Þjónustupöntun** og **Þjónustuvörublað**.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuhillur** og velja svo viðeigandi tengil.
2. Fyllið inn í reitina eftir þörfum.

## <a name="see-also"></a>Sjá einnig
[Hvernig á að setja upp Kóta fyrir Staðlaða þjónustu](service-how-setup-service-coding.md)   
[Hvernig á að setja upp úrræðaleit](service-how-setup-troubleshooting.md)
