---
title: "Setja upp fjárhagseignir"
description: "Áður en þú getur byrjað að stjórna eignum, verður þú að setja upp sjálfgefna fjárhagsreikninga, bókunarflokka, úthlutunarlykla, færslubókasniðmát og keyrslur, og flokkskóða."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ecdb1c85526bf9c2583ed5936c2fcc55a27bcb5d
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-general-fixed-assets-information"></a>Hvernig á að setja upp upplýsingar fyrir almennar eignir
Áður en hægt er að vinna með eignir, þarf að setja upp sjálfgefna fjárhagsreikninga, úthlutunarlykla, færslubókarsniðmát og keyrslur fyrir bókun á eign og endurflokkun og hægt er að flokka eignir í eignaflokka, til dæmis Áþreifanlegar og Óáþreifanlegar.

## <a name="to-set-up-general-default-values-for-fixed-assets"></a>Uppsetning almennra sjálfgilda fyrir eignir
Skilgreina almenna virkni eða aðgerðina eign og setja upp númeraröð skjala í **Uppsetning Eigna** glugganum.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning eigna** og velja svo viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-fixed-asset-posting-groups"></a>Setja upp bókunarflokka eigna
Bókunarflokkar eru notaðir til að skilgreina flokka eigna. Færslur í þessum bókunarflokkum eru bókaðar á sömu fjárhagsreikninga.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **FA bókunarflokkar** og velja svo viðeigandi tengil.  
2. Valið er **Nýtt** aðgerð.
3. Í glugganum **eignabókunarflokkaspjald** þarf að fylla reitina út eftir þörfum.

    > [!NOTE]  
   >   Til að ganga úr skugga um að mótreikningar fyrir mismunandi eignabókanir eru sjálfkrafa settir inn þegar þú velur **Setja inn mótreikning eigna** aðgerð í færslubókarlínum, fylgja skal næsta skref, í samræmi við uppfærslubókun.
4. Á flýtiflipi **Mótreikningur** í reitnum **mótreikningur uppfærslu** er valinn fjárhagsreikningurinn sem þú vilt bóka mótfærslur í fyrir uppfærslu.

Nánari upplýsingar um notkun **Setja inn mótreikning eigna** aðgerð á eignafjárhagslínur skal skoða, til dæmis, [Hvernigá að: Endurmeta Eignir](fa-how-revalue.md).

## <a name="to-set-up-fixed-asset-allocation-keys"></a>Úthlutunarlyklar eigna eru settir þannig upp:
Hægt er að úthluta færslum á ýmsar deildir og/eða verkefni samkvæmt úthlutunarlyklum sem notandi skilgreinir. Setja má upp úthlutunarlykil sem skiptir til dæmis hlutdeild í afskriftakostnaði af bílum í 35 prósent á stjórnunardeild og 65 prósent á söludeild. Frekari upplýsingar, sjá [Hvernig á að: Úthluta kostnaði og tekjum](year-allocate-costs-income.md).

Úthlutunarlyklar gilda um eignaflokka en ekki um stakar eignir.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **FA bókunarflokkar** og velja svo viðeigandi tengil.  
2. Í glugganum **Eignabókunarflokkar** skal velja aðgerðina **úthlutanir** og velja síðan bókunarflokk.
3. Í glugganum **eignaúthlutanir** þarf að fylla reitina út eftir þörfum.
4. Endurtaktu skref 2 og 3 fyrir hverja bókunargerð sem ætlunin er að skilgreina úthlutunarlykla fyrir.

## <a name="to-set-up-fixed-asset-journal-templates"></a>Setja upp sniðmát eignabóka
Sniðmát er fyrirfram skilgreind uppsetning á færslubók. Í sniðmáti eru upplýsingar um ferilskóta, skýrslur og númeraraðir. Frekari upplýsingar, sjá [Vinna með almennar færslubækur](ui-work-general-journals.md).

[!INCLUDE[d365fin](includes/d365fin_md.md)] býr sjálfkrafa til sniðmát færslubókar eignar í fyrsta sinn sem glugginn**Færslubók eignar** er opnaður, en hægt er að setja upp önnur sniðmát færslubókar.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **sniðmát færslubókar eignar** og velja svo viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum.

## <a name="to-set-up-fixed-asset-journal-batches"></a>Setja upp keyrslur eignabóka
Hægt er að setja upp margar bókarkeyrslur sem eru sérstakar færslubækur fyrir hvert færslubókarsniðmát. Starfsmenn geta til dæmis verið með eigin bókarkeyrslur sem nota upphafsstafi starfsmannsins sem heiti bókarkeyrslu. Frekari upplýsingar eru í [vinna með almenn færslubók](ui-work-general-journals.md).  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **sniðmát færslubókar eignar** og velja svo viðeigandi tengil.  
2. Valin er viðeigandi sniðmát færslubókar og veldu svo **keyrslur** aðgerðina.
3. Í glugganum **eignabókarkeyrslur** þarf að fylla reitina út eftir þörfum.

## <a name="to-set-up-fixed-asset-reclassification-journal-templates"></a>Setja upp keyrslur endurflokkunarsniðmáta
Hægt er að nota eignaendurflokkunarbókina til að flytja eignir, skipta þeim upp eða sameina þær. [!INCLUDE[d365fin](includes/d365fin_md.md)] býr sjálfkrafa til sniðmát endurflokkunarbókar eignar í fyrsta sinn sem glugginn **Endurflokkunarbók eignar** er opnaður, en hægt er að setja upp önnur sniðmát endurflokkunarbókar. Frekari upplýsingar eru í [vinna með almenn færslubók](ui-work-general-journals.md).  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **sniðmát endurflokkunarbókar eignar** og velja svo viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum.

## <a name="to-set-up-fixed-asset-reclassification-journal-batches"></a>Setja upp endurflokkunarkeyrslur eignabóka
Hægt er að setja upp margar bókarkeyrslur sem eru sérstakar færslubækur fyrir hvert sniðmát endurflokkunarbókar. Starfsmenn geta til dæmis verið með eigin endurflokkunarbókarkeyrslur sem nota upphafsstafi starfsmannsins sem heiti bókarkeyrslu. Frekari upplýsingar eru í [vinna með almenn færslubók](ui-work-general-journals.md).

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **sniðmát endurflokkunarbókar eignar** og velja svo viðeigandi tengil.  
2. Valin er viðeigandi sniðmát færslubókar og veldu svo **keyrslur** aðgerðina.
3. Í glugganum **keyrslur eignaendurflokkunarbókar** þarf að fylla reitina út eftir þörfum.

## <a name="to-set-up-fixed-asset-class-codes"></a>Uppsetning eignaflokkskóða
Flokkskóðana er hægt að nota við aðalflokkun eigna, eins og til dæmis í áþreifanlegar og óáþreifanlegar eignir.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Eignaflokkar** og velja svo viðeigandi tengil.
2. Færðir eru inn kótar og heiti á flokkunum sem búa á til.

## <a name="to-set-up-fixed-asset-subclass-codes"></a>Uppsetning eignaundirflokkskóða
Kóðar eignaundirflokks eru notaðir til að flokka eignir, s.s. í byggingar, ökutæki, húsbúnað eða vélbúnað.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Eignaundirflokkar** og velja svo viðeigandi tengil.
2. Færðir eru inn kótar og heiti á flokkunum sem búa á til.

## <a name="to-set-up-fixed-asset-location-codes"></a>Staðsetningarkóðar eigna eru settir þannig upp:
Eignastaðsetningarkóta eru notaðir til að skrá staðsetningu eignarinnar, s.s. í söludeild, móttöku, stjórnunardeild, framleiðsludeild eða vöruhúsi. Þessar upplýsingar koma að gagni við vátryggingar og birgðir.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Staðsetning eigna** og velja svo viðeigandi tengil.
2. Færðir eru inn kóðar og heiti á staðsetningum eigna sem búa á til.

## <a name="to-register-opening-entries"></a>Skráning opnunarfærslna
Ef verið er að nota eignirnar í [!INCLUDE[d365fin](includes/d365fin_md.md)] í fyrsta sinn, verður að setja upp fjárhagskerfishlutann áður en eignir eru settar upp. Hvernig þetta er gert fer eftir því hvort eignir séu hluti af fjárhag.  

 Eftirfarandi aðferð er notuð ef bóka á eignafærslur í fjárhag.  

1. Gæta skal þess að lokið sé við grunnuppsetningu eigna.  
2. Búið er til eignaspjald fyrir hverja eign sem til er.  
3. Uppsetning afskriftabóka eigna.  
4. Virkja fjárhagssamþættingu með því að fylgja næstu skrefum.
5. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Afskriftabækur** og velja svo viðeigandi tengil.  
6. Velja skal viðeigandi afskriftabók. Á flipanum **Heim** í flokknum **Stjórna** veljið **Breyta lista** til að opna gluggann **Afskriftabókarspjald**.
7. Ganga skal úr skugga um að á flýtiflipanum **Heildun** séu allir reitir auðir með því að hreinsa öll gátmerki. Ef um er að ræða fleiri en eina afskriftabók skal virkja fjárhagssamþættingu fyrir hverja þeirra.  
8. Í eignabókinni eru færðar eftirfarandi línur fyrir hverja eign:
   * Færð er inn lína með stofnkostnaðinum.
   * Lína með uppsafnaðar afskriftir til loka fyrra fjárhagsárs.
   * Lína með uppsafnaðar afskriftir frá upphafi yfirstandandi reikningsárs til dagsetningarinnar sem [!INCLUDE[d365fin](includes/d365fin_md.md)] er stillt á og setur af stað útreikning á afskriftunum.

Ef aðrar mótfærslur eru opnar eru einnig hægt að færa þær inn núna, til dæmis niðurfærsla og uppfærsla.  

Ef eignirnar eru ekki samþættar fjárhag er sleppt skrefum 4 til og með 7.

## <a name="see-also"></a>Sjá einnig
[Uppsetning eigna](fa-setup.md)  
[Eignir](fa-manage.md)  
[Fjármál](finance.md)  
[Velkomin(n) í [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

