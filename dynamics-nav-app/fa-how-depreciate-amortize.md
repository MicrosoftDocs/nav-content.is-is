---
title: "Hvernig á að: afskrifa eða greiða af eignum"
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
ms.openlocfilehash: af71f30681d436ed5da1cd6cb3c2e13f86558631
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-depreciate-or-amortize-fixed-assets"></a>Hvernig á að: afskrifa eða greiða af eignum
Afskriftir eru notaðar til að dreifa kostnaði við eignir eins og tæki og búnað á afskriftartíma þeirra. Tilgreina verður afskriftaraðferð fyrir hverja eign.  

 Hægt er að bóka afskriftir með tvennum hætti:
- Sjálfvirkt með því að keyra keyrsluna **Reikna afskriftir**.
- Handvirkt með því að nota fjárhagsbók eigna.  

Dynamics NAV getur reiknað daglegar afskriftir og er því unnt að reikna afskriftir fyrir hvaða tímabil sem er. Þess vegna er til dæmis hægt að greina rekstrarafkomu hverju sinni miðað við mánuð, ársfjórðung eða ár. Útreikningurinn notar 360 daga staðalár og 30 daga staðalmánuð. Frekari upplýsingar eru í [afskriftaaðferðir](fa-depreciation-methods.md)

Ef margar deildir nota eign er hægt að dreifa tímabilsafskriftum sjálfvirkt á deildirnar samkvæmt úthlutunartöflu sem notandi skilgreinir.  

Hægt er að hætta við rangar færslur í afskriftabók með því að nota keyrsluna **Hætta við eignabókarfærslur**. Að því loknu er hægt að bóka rétta afskriftarupphæð með því að keyra keyrsluna **Reikna afskriftir** aftur. Þegar villur eru leiðréttar eru þær bókaðar sem rangar eignafærslur.  

Endurmat er notað til að laga virði að almennum verðbreytingum. Hægt er að nota keyrsluna **Endurmat eigna** til að endurreikna upphæðir afskrifta.  

## <a name="to-calculate-a-depreciation-automatically"></a>Afskriftir reiknaðar sjálfvirkt:
Hægt er að keyra keyrsluna **Reikna afskriftir** mánaðarlega eða hvenær sem óskað er. Seldar eignir, eignir sem eru lokaðar eða óvirkar og eignir sem afskrifaðar eru handvirkt eru hunsaðar.    

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu** , slá inn **reikna afskrift**, og velja síðan viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Velja hnappinn **Í lagi**.  

    Keyrslan reiknar afskriftirnar og býr til línur í eignafjárhagsbók.  
4. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.

    Í glugganum **eignafjárhagsbók** í reitnum **Fjöldi afskriftadaga** má sjá hve margir afskriftadagar hafa verið reiknaðir.  
5. Valið er **bóka** aðgerð.

## <a name="to-post-a-depreciation-manually-from-the-fixed-asset-gl-journal"></a>Bóka afskrift handvirkt úr fjárhagsbók eigna
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.  
2. Stofnaður er upprunaleg Færslubókarlína og reitirnir fylltir út eftir þörfum.
3. Í reitnum **Eignabókunartegund** er valinn **afskrift**.
4. Valið er **Setja inn mótreikn. eigna** aðgerð. Seinni færslubókarlína er búin til fyrir mótreiknings sem er sett upp fyrir bókun afskriftar. Nánari upplýsingar eru í "setja upp bókunarflokka eigna" hlutanum í [Hvernig: Setja Upp almennar upplýsingar um eignir](fa-how-setup-general.md).
5. Á flipanum **Heim** veljið **Bóka** til að bóka færslubókina.

Ef settir hafa verið eignaúthlutunarlyklar til að úthluta upphæðum á mismunandi deildir eða verkefni, þá verða upphæðirnar úthlutað á meðan á bókun stendur. Nánari upplýsingar sjá [Hvernig: setja upp almennar upplýsingar um eignir](fa-how-setup-general.md).

## <a name="to-calculate-allocations-in-the-fixed-asset-gl-journal"></a>Reikna út úthlutanir í eignafjárhagsbókum:
Ef margar deildir nota eign er hægt að dreifa tímabilsafskriftum sjálfvirkt á deildirnar samkvæmt úthlutunartöflu sem notandi skilgreinir.  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.   
Stofnaður er Færslubókarlína og reitirnir fylltir út eftir þörfum.
3. Í reitnum **Eignabókunartegund** er valinn **úthlutun**.
4. Valið er **Setja inn mótreikn. eigna** aðgerð. Seinni færslubókarlína er búin til fyrir mótreiknings sem er sett upp fyrir bókun úthlutunar.
5. Á flipanum **Heim** veljið **Bóka** til að bóka færslubókina.

## <a name="use-duplication-lists-to-prepare-to-post-to-multiple-depreciation-books"></a>Nota Afritunarlista nota til undirbúa að bóka margar afskriftabækur  
Þegar fylltar eru út færslubókarlínur sem á að bóka í afskriftabók er hægt að afrita línurnar í aðra bók, hvaðan hægt er að bóka þær í aðra afskriftabók. Nánari upplýsingar eru í "bóka færslur í mismunandi afskriftabækur" hlutanum.

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **afskriftarbækur**, og velja síðan viðeigandi tengil.  
2. Viðeigandi afskriftabók er valin, smellt á gátreitinn **hluti afritunarlista**.  

**Mikilvægt**: Ef reiturinn **Nota afritalista** hefur verið valinn skal ekki nota númeraraðir í færslubókinni. Ástæðan fyrir þessu er að númeraraðir fyrir fjárhagsbók eigna tekur ekki númeraröðinni fyrir færslubók eigna.

## <a name="to-post-entries-to-different-depreciation-books"></a>Færslur bókaðar í mismunandi afskriftabækur  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.
2. Í bókinni sem á að bóka afskriftir með, skal velja **Nota Afritalista** gátreitinn.
3. Fyllið inn í eftirstandandi reiti eftir þörfum.
4. Valið er **bóka** aðgerð.
5. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignabækur**, og velja síðan viðeigandi tengil.

    Glugginn **Eignabók** inniheldur nýjar línur fyrir mismunandi afskriftabækur samkvæmt afritunarlista.   

6. Skoða eða breyta línunum og síðan valið **Bóka** aðgerð.

**Athugasemd**: Einnig er hægt að afrita færslu í aðra bók með því að rita afskriftabókarkóta í reitinn **Afrit í afskriftabók** þegar bókarlína er fyllt út.

Hægt er að nota keyrsluna **Afrita afskriftabók** til að afrita færslur úr einni afskriftabók í aðra. Við keyrsluna verða til bókarlínur í bókarkeyrslunni sem tilgreind var í glugganum **Eignabókaruppsetning** fyrir afskriftabókina sem á að afrita í. Nánari upplýsingar má finna hér á eftir.

## <a name="to-copy-fixed-asset-ledger-entries-between-depreciation-books"></a>Til að afrita eignafærslur milli afskriftabækur  
1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **afskriftarbækur**, og velja síðan viðeigandi tengil.
2. Opna skal viðeigandi kort afskriftabókar og veljið síðan aðgerðina **afrita afskriftabók**.  
3. Í glugganum **afrita afskriftabók** þarf að fylla reitina út eftir þörfum.  
4. Velja hnappinn **Í lagi**.  

Afrituðu línurnar eru annaðhvort búnar til í fjárhagsbók eigna eða eignabókinni eftir því hvort afskriftabókin sem þú ert að afrita er með samþættingu við fjárhag.

## <a name="see-also"></a>Sjá einnig
[Eignastjórnun](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

