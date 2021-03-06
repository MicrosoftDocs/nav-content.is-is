---
title: "Hvernig á að stofna nýjar framl.uppskriftir"
description: "Framleiðsluuppskrift geymir aðalgögn sem lýsa íhlutum og millivörum sem notuð er í framleiðslu yfirvörunnar. Þegar framleiðslupöntun er búin til fyrir yfirvörunni stjórnar framleiðsluuppskriftin útreikningum á efniþörf, eins og sýnt er í glugganum **Íhlutir framl.pöntunar**."
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
ms.openlocfilehash: 122bc1fa0b259e4d80ad134b94abcdc4d2d96640
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-production-boms"></a>Hvernig á að stofna nýjar framl.uppskriftir
Framleiðsluuppskrift geymir aðalgögn sem lýsa íhlutum og millivörum sem notuð er í framleiðslu yfirvörunnar. Þegar framleiðslupöntun er búin til fyrir yfirvörunni stjórnar framleiðsluuppskriftin útreikningum á efniþörf, eins og sýnt er í glugganum **Íhlutir framl.pöntunar**.

[!INCLUDE[d365fin](includes/d365fin_md.md)] styður einnig samsetningaruppskriftir. Samsetningarpantanir eru notaðar til að gera lokaafurð úr íhlutum með einföldu ferli sem hægt er að vinna með einu eða fleiri tilföngum, sem ekki eru vélar eða vinnustöðvar, eða án nokkurra tilfanga. Til dæmis gæti samsetningarferli falið í sér að velja tvær vínflöskur og einn kaffipoka og pakka þeim sem gjafavöru. Nánari upplýsingar er að finna í „Samsetningaruppskriftir eða framleiðsluuppskriftir“ hlutanum í [Hvernig á að: Vinna með uppskrift.](inventory-how-work-BOMs.md)  

Áður en þú getur sett upp leið verður eftirfarandi að vera á réttum stað:  

- Birgðaspjöld er búin til fyrir yfirvörur sem taka þátt í framleiðslu. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-items.md).
- Framleiðsluforði eru uppsettur. Nánari upplýsingar er að finna í [Hvernig á að setja upp vinnustöðvar og vélastöðvar](production-how-to-set-up-work-and-machine-centers.md).

## <a name="to-create-a-production-bom"></a>Búa til framleiðsluuppskrift  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Framleiðsluuppskrift** og velja svo viðeigandi tengil.  
2. Valið er **Nýtt** aðgerð.  
3. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Til að hægt sé að breyta uppskriftinni verður reiturinn **Staða** að vera stilltur á **Ný** eða **Í þróun**. Til að ræsa hana þarf að stilla **Staða** á **Vottað**.  

    Haldið áfram til að fylla út í framleiðsluuppskriftarlínurnar
5. Í reitnum **Tegund** er valið hvort vara á þessari uppskriftarlínu er venjuleg vara eða framleiðsluuppskrift. Ef varan á línunni er framleiðsluuppskrift þá verður hún þegar að vera til staðar sem vottuð framleiðsluuppskrift.  
6.  Í reitnum **númer** er umræddri vöru eða framleiðsluuppskrift flett upp og hún valin eða hún slegin handvirkt í reitinn.  
7.  Í reitnum **Magn á** er fært inn hversu margar einingar vörunnar fara í yfirvöruna, t.d. 4 dekk á 1 bifreið.  
8.  Í reitnum **Úrkast %** er hægt að slá inn fast hlutfall íhluta sem er fleygt meðan á framleiðslu stendur. Þegar íhlutirnir eru tilbúnir til notkunar í útgefinni framleiðslupöntun er hlutfallinu bætt við áætlað magn (í reitnum  **Notkunarmagn**) í framleiðslubók. Nánari upplýsingar er að finna í [Hvernig á að Skrá Notkun og frálag](production-how-to-register-consumption-and-output.md)  

    > [!NOTE]  
    >  Þetta úrkastshlutfall stendur fyrir íhluti sem er fleygt á meðan á framleiðslu stendur (þegar tekið er úr birgðum) á meðan úrkastshlutfall á leiðarlínum stendur fyrir frálagi sem er fleygt (áður en það verður birgðir).  

9.  Í reitnum **Leiðartengilskóti** er hægt að slá inn kóta til að tengja íhlut við ákveðna aðgerð. Frekari upplýsingar, sjá hlutann „Stofna leiðartengla“ í [Hvernig skal: Stofna leiðir](production-how-to-create-routings.md).
10. Framleiðsluuppskriftarlínur eru afritaðar með því að smella á **Afrita uppskr.** aðgerðina til að velja línur sem eru til.  
11.  Framleiðsluuppskriftin vottuð  
12.  Nú er hægt að hengja nýju framleiðsluuppskriftina við spjald viðkomandi yfirvöru. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-items.md).  

> [!NOTE]  
>  Til að endurreikna staðlað kostnaðarverð vörunnar úr birgðaspjaldinu skal velja **Framleiðsla** og síðan smellt á **Reikna staðlað kostn.verð** aðgerðina.  

## <a name="to-create-a-new-versions-of-a-production-bom"></a>Gerð nýrra útgáfa af framleiðsluuppskriftum
Nýjar útgáfur af framl.uppskriftum eru t.d. notaðar þegar vöru er skipt út með annarri vöru, eða þegar viðskiptamaður krefst sérstakrar útgáfu af vörunni. Útgáfureglan gerir kleift að stjórna ólíkum útgáfum af framleiðsluuppskrift. Uppbygging framleiðsluuppskriftarútgáfunnar samsvarar uppbyggingu framleiðsluuppskriftanna. Grundvallarmunurinn er gildistími á útgáfunum. Gildistíminn er skilgreindur af upphafsdagsetningu.  

Upphafsdagsetningin sýnir upphaf tímabilsins sem útgáfan er í gildi. Upphafsdagsetningin er alltaf afmörkunarviðmiðun fyrir útreikninga og mat. Uppskriftarútgáfan er gild þar til næsta útgáfa tekur gildi samkvæmt upphafsdagsetningu hennar.  

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Framleiðsluuppskrift** og velja svo viðeigandi tengil.  
2.  Framleiðsluuppskriftin sem á að afrita er valin og svo er aðgerðin **Útgáfur** valin.  
3.  Á flipanum **Heim** í flokknum **Nýtt** skal velja **Nýtt**.  
4. Fyllið inn í reitina eftir þörfum.
5. Einstakt auðkenni útgáfunnar er fært inn í reitinn **Útgáfukóti**. Hvaða samsetning af tölum og bókstöfum er leyfileg.  

    Nýja útgáfan sem búin var til fær sjálfkrafa stöðuna **Ný.**
6. Þegar uppskriftarútgáfunni er lokið, setja **Staða** reitinn á **Vottað**.  

Gildistími útgáfunnar er tilgreindur í reitnum **Upphafsdagsetning**.  

> [!NOTE]  
>  Veljið valkostinn **Vara** í reitnum **Tegund** til að nota vöru úr aðalvörugögnum í framleiðsluuppskriftinni. Ef vörunni fylgir einnig framleiðsluuppskrift þar sem reiturinn **Nr. framleiðsluuppskriftar** er fylltur út á birgðaspjaldinu er einnig tekið tillit til hennar.  
>   
>  Velja skal valkostinn **Framl.uppskr.** ef nota á annan skuggaframleiðsluuppskrift í línunni.  
>   
>  Skuggauppskriftir eru notaðar til að skipuleggja vörur./ Þessi fram.uppskriftartegund leiðir aldrei af sér fullunna vöru, en er notuð sérstaklega til að ákvarða háða eftirspurn. Skuggauppskriftir hafa ekki eigin aðalgögn.

## <a name="quantity-calculation-formula-on-production-boms"></a>Magnreikniformúla á framleiðsluuppskriftir  
Magnið er reiknað samkvæmt mismunandi víddum sem einnig eru færðar í framleiðsluuppskriftarlínurnar línurnar. Víddirnar vísa til pöntunareiningar á viðkomandi vöru. Hægt er að færa inn lengd, breidd, dýpt og þyngd sem víddir.  

Dálkarnir Tegund útreiknings, Lengd, Breidd, Dýpt og Þyngd birtast ekki þar sem aðeins fáeinir notendur nota þá. Ef notandi vill nota magnreikninga þarf fyrst að birta þessa dálka.  

Tengsl ólíkra íhluta eru skilgreind af reiknireglunni. Hægt er að nota eftirfarandi valkosti sem reiknireglu:  

-  **Tómt** - Víddir ekki teknar með. (Magn = Magn á.)  
-  **Lengd** - Magn = Magn á * Lengd  
-  **Lengd x Breidd** - Magn = Magn á * Lengd x Breidd  
-  **Lengd x Breidd x Dýpt** - Magn = Magn á Lengd x Breidd x Dýpt  
-  **Þyngd** -Magn = Magn á x Þyngd  

### <a name="example"></a>Dæmi  
Framleiðsluuppskrift hljóðar upp á sjötíu málmhluti með víddina lengd = 0.20 m og breidd = 0.15 m. Gildin eru færð inn á eftirfarandi hátt: Reikniregla = Lengd x Breidd, Lengd = 20, Breidd = 15, Magn á = 70. Magnið fæst með Magn á x Lengd * Breidd, þ.e., Magn = 70 x 0.20 m x 0.15 m = 2.1 m2.  

## <a name="see-also"></a>Sjá einnig  
[Hvernig á að stofna Nýjar leiðir](production-how-to-create-routings.md)   
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Framleiðsla](production-manage-manufacturing.md)    
[Áætlun](production-planning.md)   
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

