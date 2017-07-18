---
title: "Hvernig á að setja upp upplýsingar fyrir almennar eignir"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8c0e33a78d47ccfbe39a78f81e31b69f61fd4f80
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-general-fixed-assets-information"></a>Hvernig á að setja upp upplýsingar fyrir almennar eignir
Áður en hægt er að vinna með eignir, þarf að setja upp sjálfgefna fjárhagsreikninga, úthlutunarlykla, færslubókarsniðmát og keyrslur fyrir bókun á eign og endurflokkun og hægt er að flokka eignir í eignaflokka, til dæmis Áþreifanlegar og Óáþreifanlegar.

## <a name="to-set-up-general-default-values-for-fixed-assets"></a>Uppsetning almennra sjálfgilda fyrir eignir
Skilgreina almenna virkni eða aðgerðina eign og setja upp númeraröð skjala í **Uppsetning Eigna** glugganum.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning eigna**, og velja síðan viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

## <a name="to-set-up-fixed-asset-posting-groups"></a>Setja upp bókunarflokka eigna  
Bókunarflokkar eru notaðir til að skilgreina flokka eigna. Færslur í þessum bókunarflokkum eru bókaðar á sömu fjárhagsreikninga.  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignabókunarflokkar**, og velja síðan viðeigandi tengil.  
2. Valið er **Nýtt** aðgerð.
3. Í glugganum **eignabókunarflokkaspjald** þarf að fylla reitina út eftir þörfum.

    **Athugasemd**: til Að ganga úr skugga um að mótreikningar fyrir mismunandi eignabókanir eru sjálfkrafa settir inn þegar þú velur **Setja einn mótreikning eigna** aðgerð í færslubókarlínum, fylgja skal næsta skref, í samræmi við uppfærslubókun.
4. Á flýtiflipi **Mótreikningur** í reitnum **mótreikningur uppfærslu** er valinn fjárhagsreikningurinn sem þú vilt bóka mótfærslur í fyrir uppfærslu.

Nánari upplýsingar um notkun **Setja inn mótreikning eigna** aðgerð á eignafjárhagslínur skal skoða, til dæmis, [Hvernigá að: Endurmeta Eignir](fa-how-revalue.md).

## <a name="to-set-up-fixed-asset-allocation-keys"></a>Úthlutunarlyklar eigna eru settir þannig upp:  
Hægt er að úthluta færslum á ýmsar deildir og/eða verkefni samkvæmt úthlutunarlyklum sem notandi skilgreinir. Setja má upp úthlutunarlykil sem skiptir til dæmis hlutdeild í afskriftakostnaði af bílum í 35 prósent á stjórnunardeild og 65 prósent á söludeild. Nánari upplýsingar eru [Hvernig: Nota Úthlutunarlykla í Færslubækur](ui-how-use-allocation-keys-general-journals.md).

Úthlutunarlyklar gilda um eignaflokka en ekki um stakar eignir.  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignabókunarflokkar**, og velja síðan viðeigandi tengil.  
2. Í glugganum **Eignabókunarflokkar** skal velja aðgerðina **úthlutanir** og velja síðan bókunarflokk.
3. Í glugganum **eignaúthlutanir** þarf að fylla reitina út eftir þörfum.
4. Endurtaktu skref 2 og 3 fyrir hverja bókunargerð sem ætlunin er að skilgreina úthlutunarlykla fyrir.

## <a name="to-set-up-fixed-asset-journal-templates"></a>Setja upp sniðmát eignabóka  
Sniðmát er fyrirfram skilgreind uppsetning á færslubók. Í sniðmáti eru upplýsingar um ferilskóta, skýrslur og númeraraðir. Frekari upplýsingar eru í [vinna með almenn færslubók](ui-work-general-journals.md).

Dynamics NAV býr sjálfkrafa til sniðmát eignar í fyrsta sinn sem glugginn **eignabók** er opnaður en hægt er að setja upp önnur bókarsniðmát.  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sniðmát eignabóka**, og velja síðan viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum.

## <a name="to-set-up-fixed-asset-journal-batches"></a>Setja upp keyrslur eignabóka
Hægt er að setja upp margar bókarkeyrslur sem eru sérstakar færslubækur fyrir hvert færslubókarsniðmát. Starfsmenn geta til dæmis verið með eigin bókarkeyrslur sem nota upphafsstafi starfsmannsins sem heiti bókarkeyrslu. Frekari upplýsingar eru í [vinna með almenn færslubók](ui-work-general-journals.md).  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sniðmát eignabóka**, og velja síðan viðeigandi tengil.  
2. Valin er viðeigandi sniðmát færslubókar og veldu svo **keyrslur** aðgerðina.
3. Í glugganum **eignabókarkeyrslur** þarf að fylla reitina út eftir þörfum.

## <a name="to-set-up-fixed-asset-reclassification-journal-templates"></a>Setja upp keyrslur endurflokkunarsniðmáta  
Hægt er að nota eignaendurflokkunarbókina til að flytja eignir, skipta þeim upp eða sameina þær. Dynamics NAV býr sjálfkrafa til endurflokkunarsniðmát eignar í fyrsta sinn sem glugginn **eignaendurflokkunarbók** er opnaður en hægt er að setja upp önnur bókarsniðmát endurflokkunar. Frekari upplýsingar eru í [vinna með almenn færslubók](ui-work-general-journals.md).  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sniðmát eignaendurflokkunarbókar**, og velja síðan viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum.

## <a name="to-set-up-fixed-asset-reclassification-journal-batches"></a>Setja upp endurflokkunarkeyrslur eignabóka  
Hægt er að setja upp margar bókarkeyrslur sem eru sérstakar færslubækur fyrir hvert sniðmát endurflokkunarbókar. Starfsmenn geta til dæmis verið með eigin endurflokkunarbókarkeyrslur sem nota upphafsstafi starfsmannsins sem heiti bókarkeyrslu. Frekari upplýsingar eru í [vinna með almenn færslubók](ui-work-general-journals.md).
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sniðmát eignaendurflokkunarbókar**, og velja síðan viðeigandi tengil.  
2. Valin er viðeigandi sniðmát færslubókar og veldu svo **keyrslur** aðgerðina.
3. Í glugganum **keyrslur eignaendurflokkunarbókar** þarf að fylla reitina út eftir þörfum.

## <a name="to-set-up-fixed-asset-class-codes"></a>Uppsetning eignaflokkskóða  
Flokkskóðana er hægt að nota við aðalflokkun eigna, eins og til dæmis í áþreifanlegar og óáþreifanlegar eignir.
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignaflokka**, og velja síðan viðeigandi tengil.
2. Færðir eru inn kótar og heiti á flokkunum sem búa á til.

## <a name="to-set-up-fixed-asset-subclass-codes"></a>Uppsetning eignaundirflokkskóða
Kóðar eignaundirflokks eru notaðir til að flokka eignir, s.s. í byggingar, ökutæki, húsbúnað eða vélbúnað.  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignaundirflokka**, og velja síðan viðeigandi tengil.
2. Færðir eru inn kótar og heiti á flokkunum sem búa á til.

## <a name="to-set-up-fixed-asset-location-codes"></a>Staðsetningarkóðar eigna eru settir þannig upp:
Eignastaðsetningarkóta eru notaðir til að skrá staðsetningu eignarinnar, s.s. í söludeild, móttöku, stjórnunardeild, framleiðsludeild eða vöruhúsi. Þessar upplýsingar koma að gagni við vátryggingar og birgðir.
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **staðsetningar eigna**, og velja síðan viðeigandi tengil.
2. Færðir eru inn kóðar og heiti á staðsetningum eigna sem búa á til.

## <a name="to-register-opening-entries"></a>Skráning opnunarfærslna  
Áður en Eignir eru notaðar í fyrsta sinn í Dynamics NAV verður að setja upp fjárhagskerfishlutann áður en eignir eru settar upp. Hvernig þetta er gert fer eftir því hvort eignir séu hluti af fjárhag.  

 Eftirfarandi aðferð er notuð ef bóka á eignafærslur í fjárhag.  

1. Gæta skal þess að lokið sé við grunnuppsetningu eigna.  
2. Búið er til eignaspjald fyrir hverja eign sem til er.  
3. Uppsetning afskriftabóka eigna.  
4. Virkja fjárhagssamþættingu með því að fylgja næstu skrefum.
5. Í reitnum **Leit** skal færa inn **Afskriftabækur** og velja síðan viðkomandi tengil.  
6. Velja skal viðeigandi afskriftabók. Á flipanum **Heim** í flokknum **Stjórna** veljið **Breyta lista** til að opna gluggann **Afskriftabókarspjald**.
7. Ganga skal úr skugga um að á flýtiflipanum **Heildun** séu allir reitir auðir með því að hreinsa öll gátmerki. Ef um er að ræða fleiri en eina afskriftabók skal virkja fjárhagssamþættingu fyrir hverja þeirra.  
8. Í eignabókinni eru færðar eftirfarandi línur fyrir hverja eign:
    - Færð er inn lína með stofnkostnaðinum.
    - Lína með uppsafnaðar afskriftir til loka fyrra fjárhagsárs.
    - Lína með uppsafnaðar afskriftir frá upphafi yfirstandandi reikningsárs til dagsetningarinnar þegar áætlað er að Dynamics NAV hefji útreikning á afskriftum.

Ef þú ert með aðrar opnunarstöður geturðu einnig fært þær inn núna, eins og niður\-færsla og uppfærsla.  

Ef eignirnar eru ekki samþættar fjárhag er sleppt skrefum 4 til og með 7.

## <a name="see-also"></a>Sjá einnig
[Uppsetning eigna](fa-setup.md)  
[Eignastjórnun](fa-manage.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

