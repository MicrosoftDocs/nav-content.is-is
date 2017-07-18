---
title: "Hvernig á að: Endurmeta eignir"
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
ms.openlocfilehash: ce4176db221d309df63ad8e2bc89263b2464021b
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-revalue-fixed-assets"></a>Hvernig á að: Endurmeta eignir
Endurmat eigna getur samanstaðið af uppfærslu, niðurfærslu, og leiðréttingum á almennu virði.

Þegar virði eignar hefur hækkað, er bókuð færslubókarlínu með hærri upphæð, uppfærslu í afskriftabókina. Nýtt verð er skráð sem uppfærslu samkvæmt bókunargrunni eigna.

Þegar virði eignar hefur lækkað, bókarðu færslubókarlínu með lægri upphæð, niðurfærslu, í afskriftabók. Nýtt verð er skráð sem niðurfærslu samkvæmt bókunargrunni eigna.

Endurmat er notað til að laga virði margra eigna, til dæmis, að almennum verðbreytingum. Hægt er að nota keyrsluna **Endurmat eigna** til að breyta ýmsum upphæðum, svo sem upphæðum niðurfærslna og uppfærslna.

## <a name="to-post-an-appreciation-from-the-fixed-asset-gl-journal"></a>Bóka uppfærslu úr fjárhagsbók eigna  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.  
2. Stofnaður er upprunaleg Færslubókarlína og reitirnir fylltir út eftir þörfum.
3. Í reitnum **Eignabókunartegund** er valinn **uppfærsla**.
4. Valið er **Setja inn mótreikn. eigna** aðgerð. Seinni færslubókarlína er búin til fyrir mótreiknings sem er sett upp fyrir bókun uppfærslu.

    **Athugasemd**: skref 4 virkar eingöngu ef búið er að setja upp eftirfarandi: Í **Eignabókunarflokksspjald** glugganum fyrir bókunarflokkur eigna, inniheldur reiturinn **uppfærslureikningur** debetreikning fjárhags og reikningurinn **Mótreikning uppfærslu** inniheldur fjárhagsreikninginn sem á að bóka mótfærslur í fyrir uppfærslu. Nánari upplýsingar eru í "setja upp bókunarflokka eigna" hlutanum í [Hvernig: Setja Upp almennar upplýsingar um eignir](fa-how-setup-general.md).
5. Valið er **bóka** aðgerð.

## <a name="to-post-a-write-down-from-the-fixed-asset-gl-journal"></a>Bóka niðurfærsla úr fjárhagsbók eigna  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.  
2. Stofnaður er upprunaleg Færslubókarlína og reitirnir fylltir út eftir þörfum.
3. Í reitnum **Eignabókunartegund** er valinn **niðurfærsla**.
4. Valið er **Setja inn mótreikn. eigna** aðgerð. Seinni færslubókarlína er búin til fyrir mótreiknings sem er sett upp fyrir bókun niðurfærslu.

    **Athugasemd**: skref 4 virkar eingöngu ef búið er að setja upp eftirfarandi: Í **Eignabókunarflokksspjald** glugganum fyrir bókunarflokkur eigna, inniheldur reiturinn **niðurfærslureikningur** kreditreikning fjárhags og reikningurinn **Mótreikning niðurfærslu** inniheldur fjárhagsreikninginn sem á að bóka mótfærslur í fyrir niðurfærslur. Nánari upplýsingar eru í "setja upp bókunarflokka eigna" hlutanum í [Hvernig: Setja Upp almennar upplýsingar um eignir](fa-how-setup-general.md).
5. Valið er **bóka** aðgerð.

## <a name="to-perform-general-revaluation-of-fixed-assets"></a>Framkvæma almennt endurmat eigna  
Endurmat er notað til að laga virði margra eigna, til dæmis, að almennum verðbreytingum. Hægt er að nota keyrsluna **Endurmat eigna** til að breyta ýmsum upphæðum, svo sem upphæðum niðurfærslna og uppfærslna. **Leyfa Endurmat** gátreiturinn á **Afskriftabók** glugganum verður að vera valinn.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **endurmeta eignir**, og velja síðan viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum.
3. Velja hnappinn **Í lagi**.  

    Endurmatslínur eru búnar til samkvæmt stillingu í skref 2. Línur eru búnar til annaðhvort í færslubók eigna, allt eftir sniðmáti þínu og uppsetningu keyrslu í glugganum **Eignabókargrunnur**. Nánari upplýsingar sjá [Hvernig: setja upp almennar upplýsingar um eignir](fa-how-setup-general.md).

4. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.  
5. Velja bókina með eignir sem á að endurmeta og síðan valið aðgerðin **Færslur**.  
6. Athugaðu Stofnaðar færslur, og síðan valið **Bóka** aðgerð til að bóka bókina.

**Ábending**: Ef endurmatstölurnar eru aðeins til sýnis er hægt að búa til sérstaka afskriftabók til að geyma þær í. Þá hafa þessar færslur ekki áhrif á aðrar afskriftabækur.

## <a name="to-post-additional-acquisition-costs"></a>Bókun Viðbótarkaupverðs
Annar stofnkostnaður eignar er bókaður eins og upphaflegi stofnkostnaðurinn: úr innkaupareikningi eða úr eignabók. Nánari upplýsingar eru í [Hvernig á að: komast ufir eignir](fa-how-acquire.md).  

Ef afskriftir hafa þegar verið reiknaðar fyrir eignina er sett gátmerki í reitinn **Afskr. kaupverðs** til að annar stofnkostnaður að frádregnu hrakvirði verði afskrifaður í hlutfalli við upphæðina sem áður keypt eign hefur þegar verið afskrifuð um. Þetta tryggir að afskriftatímabilið breytist ekki.  

Afskriftaprósentan er reiknuð sem:  

*P = (heildarafskriftir x 100) / afskriftagrunnur*

*Afskriftaupphæð = (P/100) x (viðbótarstofnkostnaður - hrakvirði)*  

Muna þarf að setja gátmerkið í reitinn **Afskr. til eignabókunardags.** í reikningi, eignafjárhagsbókar- eða eignabókarlínurnar til að tryggja að afskrift sé reiknuð frá síðasta eignabókunardegi til bókunardags annars kaupverðs.

### <a name="example---posting-additional-acquisition-costs"></a>Dæmi - bókun viðbótar stofnkostnaðar
Vél er keypt 1. ágúst, 2000. Stofnkostnaðurinn er 4.800. Afskriftaaðferðin er línuleg til fjögurra ára.

31. ágúst, 2000, er keyrslan **Reikna afskrift** keyrð. Afskriftir eru reiknaðar sem:

*bókfært virði x fjöldi afskriftadaga / heildarfjöldi afskriftadaga = 4800 x 30 / 1440 = 100*  

september, 2000, er sölureikningur bókaður vegna málningar á vélinni. Upphæðin á reikningnum er 480.

Ef valið var **Afskr. til eignabókunardags.** gátreiturinn á reikningnum fyrir bókun, fara fram eftirfarandi útreikningar:  

15 daga afskriftir (frá 01/09/00 til 15/09/00) eru reiknaðar sem:

*bókfært virði x fjöldi afskriftadaga / eftirstandandi fjöldi afskriftadaga = (4800 - 100) x 15 / 1410 = 50*

Ef valið var **Afskr. kaupverðs.** gátreiturinn á reikningnum fyrir bókun, fara fram eftirfarandi útreikningar:  

*Annar stofnkostnaður er afskrifaður um ((150 x 100) / 4800) / 100 x 480 = 15*

Afskriftagrunnurinn er núna *5280 = (4800 + 480)* og uppsafnaðar afskriftir eru *165 = (100 + 50 +15) * sem samsvarar 45 daga afskriftum á heildarkaupverði. Það merkir að eignin verði að fullu afskrifuð innan áætlaðs fjögurra ára líftíma.  

Þegar keyrslan **Reikna afskriftir** er keyrð 30/09/00 eru útreikningar með eftirfarandi hætti:  

*Eftirstöðvar afskriftartíma eru 3 ár, 10 mánuðir og 15 dagar = 1395 dagar*  

*Bókfært virði er (5280 -165) = 5115*  

*Afskriftaupphæð fyrir september 2000: 5115 x 15 / 1395 = 55,00*  

*Heildarafskriftir = 165 + 55 = 220*  

Ef þú valdir ekki gátreitinn **Afskr. til eignabókunardags.** glatar eignin 15 daga afskriftum vegna þess að keyrslan **Reikna afskriftir** sem keyrð er 30/09/00 reiknar afskriftir frá 15/09/00 til 30/09/00. Það merkir að þegar keyrslan **Reikna afskriftir** er keyrð 30/09/00 eru útreikningarnir sem hér segir:  

*Eftirstöðvar líftíma eru 3 ár, 10 mánuðir og 15 dagar = 1395 dagar*  

*Bókfært virði er (4800 + 480 - 100 - 15) = 5165*

*Afskriftaupphæð fyrir september 2000: 5165 x 15 / 1395 = 55,54*  

*Heildarafskriftir = 100 + 15 + 55,54 = 170,54*

## <a name="see-also"></a>Sjá einnig
[Eignastjórnun](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

