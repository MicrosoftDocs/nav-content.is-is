---
title: "Hvernig á að: Skrá söluverð og afslætti"
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
ms.openlocfilehash: f99bb0aeef2c25048b0da3e0476ae2d612bff562
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-record-purchase-prices-and-discounts"></a>Hvernig á að: Skrá söluverð og afslætti
Skilgreina verður mismunandi verð- og afsláttarsamninga sem gilda þegar vörur eru keyptar frá mismunandi lánardrottnum svo að þeim reglum og gildum sem samkomulag hefur náðst um sé beitt á innkaupaskjöl sem gerð eru fyrir lánardrottininn.

Hvað varðar verð, er hægt að hafa sérstakt söluverð í sölulínunum ef tiltekin samsetning á viðskiptamanni, vöru, lágmarksmagni, mælieiningu, eða upphafs-/ lokadagsetningu er til staðar.

Hvað varðar afslátt, er hægt að setja upp og nota tvær tegundir innkaupaafsláttar:

|Afsláttargerð |Lýsing |
|--------------|------------|
|**Innkaupalínuafsláttur**|Afsláttarupphæð sem er sett inn í sölulínur ef tiltekin samsetning á lánardrottni, vöru, lágmarksmagni, mælieiningu, eða upphafs-/ lokadagsetningu er til staðar. Þetta virkar á sama háttog fyrir innkaupsverð.|
|**Reikningsafsláttur**|Hlutfallsafsláttur sem er dreginn frá heildarupphæð skjalsins ef upphæðin í öllum línum í söluskjali fer fram yfir ákveðið lágmark.|

Vegna þess að innkaupalínuafslættir og innkaupaverð byggjast á samsetningu vöru og lánardrottins er einnig hægt að færa þessa grunnstillingu inn af birgðaspjaldinu, þar sem reglurnar og gildin eru skilgreind. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md).

## <a name="to-set-up-a-special-purchase-price-for-a-vendor"></a>Að setja upp sérstakt innkaupsverð fyrir lánardrottin
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **lánardrottnar** og velja síðan viðkomandi tengil.
2. Opna skal viðeigandi lánardrottnaspjald og velja síðan aðgerðina **Verð**.

    Reiturinn **Tegund innkaupa** er fylltur út fyrirfram með **Lánardrottinn**og í reitnum **Innkaupakóði**er númer lánardrottins.
3. Fyllið út reitina í línunni eins og þörf er á. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
4. Fyllt er út lína fyrir hverja samsetningu sem lánardrottinn veitir innkaupalínuafsláttur fyrir.

## <a name="to-set-up-a-line-discount-for-a-vendor"></a>Að setja upp línuafslátt fyrir lánardrottin
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **lánardrottnar** og velja síðan viðkomandi tengil.
2. Opna skal viðeigandi lánardrottinsspjald og veljið síðan aðgerðina **Línuafslættir**.

    Reiturinn **Tegund innkaupa** er fylltur út fyrirfram með **Lánardrottinn**og í reitnum **Innkaupakóði**er númer lánardrottins.
3. Fyllið út reitina í línunni eins og þörf er á. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
4. Fyllt er út lína fyrir hverja samsetningu sem lánardrottinn veitir innkaupalínuafsláttur fyrir.

## <a name="to-set-up-an-invoice-discount-for-a-vendor"></a>Að setja upp reikningsafslátt fyrir lánardrottin
Þegar lánardrottnar þínir hafa veitt þér upplýsingar um hvaða reikningsafslætti þeir veita eru færðir inn reikningsafsláttarkóðar á lánardrottnaspjöldin og sett upp skilyrði fyrir hvern kóða.

1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **lánardrottnar** og velja síðan viðkomandi tengil.
2. Opna skal spjald lánardrottins sem getur veitt reikningsafslátt.
3. Í reitnum **Reikningsafsláttarkóði** er valinn kóði fyrir viðeigandi reikningsafsláttarskilmála sem forritið notar til að reikna reikningsafslátt fyrir lánardrottin.

    **Athugasemd**: Fyrirliggjandi lánardrottnaspjöld standa fyrir reikningsafsláttarkóða. Þetta gerir kleift að úthluta reikningsafsláttarskilmálum hratt og örugglega til lánardrottna með því að velja nafn annars lánardrottins sem hefur sömu skilmála.

    Næsta skref er að setja upp nýja skilmála fyrir reikningsafslátt.
4. Í glugganum **Lánardrottnaspjald** er aðgerðin **Reikningsafslættir** valin. Glugginn **Reikningsafsláttur lánardr.** opnast.
5. Í reitnum **Gjaldmiðilskóði** er færður inn kóðinn fyrir gjaldmiðilinn sem reikningsafsláttarskilyrði í línunni eiga við um. Reiturinn er skilinn eftir auður ef setja á upp reikningsafsláttarskilyrði í USD.
6. Í reitinn **Lágmarksupphæð** er færð inn lágmarksupphæð sem reikningur þarf að hafa til að hægt sé að fá afslátt.
7. Í reitnum **Afsláttar %** skal slá inn reikningsafslátt sem prósentu af reikningsupphæð.
8. Endurtakið skref 5 til 7 fyrir alla gjaldmiðla sem lánardrottinn mun fá mismunandi reikningsafslátt í.

Reikningsafsláttur er nú settur upp og úthlutað á umræddan lánardrottin. Þegar valinn er lánardrottinskóði í reitnum **Kóði reikningsafsláttar** á öðrum lánardrottnaspjöldum er sama reikningsafslætti úthlutað þeim lánardrottini.

## <a name="see-also"></a>Sjá einnig  
[Setja upp innkaup](purchasing-setup-purchasing.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)

