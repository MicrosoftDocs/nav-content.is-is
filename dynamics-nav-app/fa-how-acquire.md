---
title: "Hvernig á að: komast Yfir Eignir"
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
ms.openlocfilehash: 5b58a6cf0a0c22c8076082328f92725cb7dbc4d1
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-acquire-fixed-assets"></a>Hvernig á að: komast Yfir Eignir
Setja verður upp spjald fyrir hverja eign með upplýsingum um eignina. Hægt er að setja byggingar eða framleiðslubúnað sem aðaleign með íhlutalista upp og hægt er að flokka þær á ýmsa vegu, eins og eftir flokki, deild eða staðsetningu. Afskriftabók þarf að setja upp og tengja hverri eign áður en hægt er að komast yfir hana.

Þegar eign er sett upp og Afskriftabók tengd henni, verðurðu að komast yfir eignina. Til að komast yfir eign, skráirðu kaupferð hennar í viðeigandi Fjárhagsreikning, bankareikning, eða lánardrottin með því að bóka kaupfærslu úr gluganum **Fjárhagsbók eigna** . Þú getur notað gluggann **aðstoð við eignakaup** til að stofna og bóka nauðsynlegar færslubókarlínur sjálfvirkt.

Hrakvirði er afgangsvirði eignar þegar ekki er lengur hægt að nota hana. Hægt er að bóka hrakvirðið um leið og stofnkostnaður er bókaður. Nánari upplýsingar sjá [Hvernig á að: afskrifa eða greiða af eignum](fa-how-depreciate-amortize.md)

Endurmat er notað til að laga virði að almennum verðbreytingum. Hægt er að nota keyrsluna **Endurmat eigna** til að reikna kaupferð á endurnýjunarverði.

## <a name="to-create-a-fixed-asset-and-acquire-it-automatically"></a>Stofna eign og komast yfir hana sjálfkrafa
Eftirfarandi ferli sýnir hvernig á að stofna eign og komast svo yfir hana með því að nota **aðstoð við eignakaup** glugganum til að stofna og bóka nauðsynlegar eignafjárhagslínur Hægt er að einnig að stofna og bóka færslubókarlínurnar handvirkt. Nánari upplýsingar eru í "Bókun eignakaupa handvirkt með fjárhagsbók eigna" hlutanum.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.  
2. Velja sem **Nýtt** aðgerð og síðan fyllt út í reitina á **Almenna** Flýtiflipanum eins og þörf krefur. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Fyllt er út í reiti eftir því sem við á í flýtiflipanum **afskriftabók**. Þetta skref úthlutar afskriftabók á eigninni.  
4. Ef það þarf að úthluta fleiri en einni afskriftabók á eign skal velja **bæta Við Fleiri Afskriftabækur** aðgerð. Nánari upplýsingar eru í "úthluta eign á afskriftabók" hlutanum í [Hvernig á að setja upp afskriftabækur eigna](fa-how-setup-depreciation.md).

    Þegar allir reitir sem þarf til að komast yfir eign eru fylltir út, birtist **hægt er að komast yfir eignina. Komast yfir** tilkynning efst á síðunni.
5. Valið er **Komast yfir** aðgerð í tilkynningunni.
6. Fylgja leiðbeiningunum í glugganum **aðstoð við eignakaup** til að ljúka sjálfvirka kaup eignarinnar.

**Athuga**: einnig má bóka kaupverð sem lán. Í því tilfelli skal muna að gildið í reitnum **kaupverð með VSK** á að vera með mínusmerki til að tilgreina lánið.

Þegar valið er **Ljúka**, er **Bókfært Virði** í reitnum **Eignaspjald** útfyllt, og gefur til kynna að eignin var keypt á tilgreint kaupverð.  

## <a name="to-set-up-a-component-list-for-a-main-asset"></a>Uppsetning íhlutalista fyrir aðaleignir:  
Hægt er að flokka eignir í aðaleignir og íhluti þeirra. Í framleiðslutæki gætu til dæmis verið margir hlutir sem þarf að flokka á þennan hátt.  

Setja verður bæði aðaleignina og íhluti hennar upp sem einstök eignaspjöld. Þegar íhlutalistinn hefur verið settur upp fyllir Dynamics NAV sjálfkrafa í reitina **Aðaleign/Íhlutur** og **Íhlutir aðaleignar** á eignaspjöldunum.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.
2. Valin er eignin sem er aðaleignin er valin síðan **íhlutir aðaleignar** aðgerð.
3. Í reitnum **íhlutir aðaleignar** er valið **Eignanr.**. reiturinn og síðan valið eignin sem á að bæta við sem íhlut aðaleignar.
4. Glugganum er lokað.
5. Endurtaktu þrep 3 og 4 fyrir hverja íhlut eignar sem ætlunin er að bæta við.
6. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning eigna**, og velja síðan viðeigandi tengil.
7. Valinn er **Leyfa Bókun á Aðaleignir** gátreitinn.

## <a name="to-post-a-fixed-asset-acquisition-manually-with-the-fixed-asset-gl-journal"></a>Bókun eignakaupa handvirkt með fjárhagsbók eigna.
Eftirfarandi ferli sýnir hvernig á að komast yfir eign handvirkt með því að stofna og bóka línur í glugganum **Fjárhagsbók eigna**. Einnig má komast yfir eign sjálfkrafa með því að nota **aðstoð við eignakaup** gluggann. Nánari upplýsingar sjá skref 5 í "Stofna eign og komast yfir hana sjálfkrafa" hlutanum.

**Athuga**: einnig má bóka kaupverð sem lán. Í því tilfelli muna sem gildið í reitnum **upphæð** að vera með mínusmerki til að tilgreina kredit.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.
2. Í **fjárhagsbók eigna** glugga í á **Eignabókunartegund** reitnum er valinn **kaupverð**.
3. Fyllið inn í eftirstandandi reiti eftir þörfum.
4. Valið er **bóka** aðgerð.  

**Ábending**: Ef fyllt er í reitina **vátryggingarnúmer** reit fjárhagsbók eigna þegar kaupverð er bókað, þá bókar Dynamics NAV einnig kaupverð eignarinnar í vátryggingasviðsbókina. Nánari upplýsingar sjá [Hvernig á að: tryggja eignir](fa-how-insure.md)

## <a name="to-cancel-an-acquisition-cost-posting-for-one-fixed-asset"></a>Ógilding bókunar kaupverðs fyrir eina eign
Ef villa á sér stað við bókun stofnkostnaðar er hægt að fjarlægja færsluna með keyrslunni **Afturkalla eignafærslur** og bóka síðan rétta stofnkostnaðarfærslu. Röngu færslurnar eru fluttar í gluggann **Rangar eignafærslur.**

Ef stofnkostnaður er til dæmis bókaður með rangri dagsetningu þarf að leiðrétta það eins fljótt og unnt er þar sem bókunardagsetningu eigna er notuð í margar mikilvæga útreikninga.

**Mikilvægt**: Er ekki hægt að nota **bakfæra** aðgerð fyrir eignafærslur.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **Hætta við eignafærslur**, og velja síðan viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Veldu hnappinn **Í lagi** til að ræsa keyrsluna.
4. Þegar röng færsla eða færslur eru ógiltir, skal halda áfram og bóka rétt kaupverð.

Til að hætta við færslur fyrir margar eignir á sama tíma skal nota **hætta Við Eignafærslur** keyrsluna.

## <a name="to-post-the-salvage-value-together-with-the-acquisition-cost"></a>Bóka hrakvirði með kaupverði.  
Hægt er að bóka hrakvirði með stofnkostnaði af fjárhagsbók eigna.    

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **Hætta við eignafærslur**, og velja síðan viðeigandi tengil.
2. Stofna færslubókarlínunni kaupa. Nánari upplýsingar eru í "Bókun eignakaupa handvirkt með fjárhagsbók eigna" hlutanum.
3. **Hrakvirðið** er fært sem kreditupphæð (með mínusmerki) í reitinn Hrakvirði í reikningslínunni.
4. Valið er **bóka** aðgerð.

**Athugasemd**: Bókunartegundin **hrakvirði** er aðeins valkostur í **eignabókinni**. Hún er Ekki tiltæk í **Eignabók Fjárhags** glugganum vegna þess að hrakvirði er aldrei bókað á fjárhag.

## <a name="see-also"></a>Sjá einnig
[Eignastjórnun](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

