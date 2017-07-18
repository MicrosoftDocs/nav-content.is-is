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
ms.openlocfilehash: 2d6438108fb2c36bb6f0d44efddc053bd628d068
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a>Hvernig á að: Skrá söluverð og afslætti
Skilgreina þarf ólíka verð- og greiðsluskilmála sem gilda þegar ólíkum viðskiptamönnum er selt þannig að umsamin gildi og reglur séu notuð í söluskjölum sem stofnuð eru fyrir viðskiptamennina.

Hvað varðar verð er hægt að hafa sérstakt söluverð sett í sölulínur ef tiltekin samsetning á viðskiptamanni, vöru, lágmarksmagni, mælieiningu, eða tupphafs-/ lokadagsetningu er til staðar.

Hvað varðar afslætti er hægt að setja upp og nota tvær tegundir söluafsláttar:

|Afsláttargerð |Lýsing |
|--------------|------------|
|**Sölulínuafsláttur**|Afsláttarupphæð sem er sett inn í sölulínu ef tiltekin samsetning á viðskiptamanni, vöru, lágmarksmagni, mælieiningu, eða upphafs-/ lokadagsetningu er til staðar. Þetta virkar á sama hátt og fyrir söluverð.|
|**Reikningsafsláttur**|Hlutfallsafsláttur sem er dreginn frá heildarupphæð skjalsins ef upphæðin í öllum línum í söluskjali fer fram yfir ákveðið lágmark.|

Af því að söluverð og afsláttur á sölulínur byggist á samsetningu vöru og viðskiptamanns þá má einnig framkvæma þessa grunnstillingu í birgðaspjaldi vörunnar þar sem reglurnar og gildin eiga við.

## <a name="to-set-up-a-sales-price-for-a-customer"></a>Að setja upp söluverð fyrir viðskiptamann
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **viðskiptamenn** og velja síðan viðkomandi tengil.
2. Opna skal viðeigandi viðskiptamannaspjald og veljið síðan aðgerðina **Verð**.

    Í reitnum **Tegund sölu** er búið að fylla út **Viðskiptamaður** og í reitnum **Sölukóði** er búið að fylla út númer viðskiptamannsins.
3. Fyllið út reitina í línunni eins og þörf er á. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
4. Fyllt er út lína fyrir hverja samsetningu sem veitir sérstakt söluverð fyrir viðskiptamanninn.

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a>Sölulínuafsláttur stofnaður fyrir viðskiptamann
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **viðskiptamenn** og velja síðan viðkomandi tengil.
2. Opna skal viðeigandi viðskiptamannaspjald og veljið svo aðgerðina **Línuafslættir**.

    Í reitnum **Tegund sölu** er búið að fylla út **Viðskiptamaður** og í reitnum **Sölukóði** er búið að fylla út númer viðskiptamannsins.
3.  Fyllið út reitina í línunni eins og þörf er á. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
4. Fyllt er út lína fyrir hverja samsetningu sem veitir sérstakan sölulínuafslátt fyrir viðskiptamanninn.

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a>Að setja upp reikningsafslátt fyrir viðskiptamann
Eftir að ákveðið hefur verið hvaða viðskiptamenn geti fengið reikningsafslátt eru færðir inn reikningsafsláttarkóðar á viðskiptamannaspjöldin og sett upp skilyrði fyrir hvern kóða.

1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **viðskiptamenn** og velja síðan viðkomandi tengil.
2. Opna skal spjald viðskiptamanns sem getur fengið reikningsafslátt.
3. Í reitinn **Reikningsafsláttarkóði** er færður inn kóði fyrir viðeigandi reikningsafsláttarskilmála sem forritið notar til að reikna reikningsafslátt fyrir viðskiptamanninn.

    **Athugasemd**: Fyrirliggjandi viðskiptamannaspjöld standa fyrir reikningsafsláttarkóða. Þetta gerir kleift að úthluta reikningsafsláttarskilmálum hratt og örugglega til viðskiptamanna með því að velja nafn annars viðskiptamanns sem hefur sömu skilmála.

    Næsta skref er að setja upp nýja skilmála fyrir sölureikningsafslætti.
4. Í glugganum **Viðskiptamannaspjald** er aðgerðin **Reikningsafsláttur** valin. Glugginn **Reikningsafsláttur viðskm.** opnast.
5. Í reitnum **Gjaldmiðilskóði** er færður inn kóðinn fyrir gjaldmiðilinn sem reikningsafsláttarskilyrði í línunni eiga við um. Reiturinn er skilinn eftir auður ef setja á upp reikningsafsláttarskilyrði í USD.
6. Í reitinn **Lágmarksupphæð** er færð inn lágmarksupphæð sem reikningur þarf að hafa til að hægt sé að fá afslátt.
7. Í reitnum **Afsláttar %** skal slá inn reikningsafslátt sem prósentu af reikningsupphæð.
8. Endurtakið skref 5 til 7 fyrir alla gjaldmiðla sem viðskiptamaðurinn mun fá mismunandi reikningsafslátt í.

Reikningsafsláttur er nú settur upp og úthlutað á umræddan viðskiptamann. Þegar valinn er kóði viðskiptamannsins í reitnum **Reikningsafsl.kóði** á öðrum viðskiptamannaspjöldum er sama reikningsafslætti úthlutað þeim viðskiptamönnum.

## <a name="see-also"></a>Sjá einnig  
[Uppsetning sölu](sales-setup-sales.md)  
[Stjórna sölu](sales-manage-sales.md)

