---
title: "Hvernig á að: Tryggja eignir"
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
ms.openlocfilehash: a3a59bc091042f72775b56fdd5bbe37ffa1a6d80
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-insure-fixed-assets"></a>Hvernig á að: Tryggja eignir
Vátryggingarskírteini fyrir eign er sýnt með vátryggingarspjaldi. Hægt er að úthluta einni eign á eina vátryggingarskírteini eða margar eignir á eitt vátryggingarskírteini.

Þú úthlutar eign á vátryggingarskírteini með því að bóka í vátryggingasviðsbók úr glugganum **Vátryggingabók** .

Þar að auki er hægt að úthluta eign á vátryggingarskírteini og stofna vátryggingasviðsfærslur þegar þú bókar kaupverð hennar. Þú gerir þetta með því að bóka kaupverð úr eignabók með reitnum **vátryggingarnúmer** útfylltan. **Sjálfvirk Vátryggingarbókun** gátreiturinn á **uppsetning eigna** glugganum þarf að vera valinn. Nánari upplýsingar eru í Bókun eignakaupa handvirkt með fjárhagsbók eigna í [hvernig á að komast yfir eignir](fa-how-acquire.md).

Ef **Sjálfvirk Vátryggingarbókun** gátreiturinn á **uppsetning eigna** glugganum er ekki valinn, þá mun bókun eignakaupa úr eignabók stofna línur í glugganum **Vátryggingabók** sem síðan verður að bóka handvirkt.

**Viðvörun**: Ef ekki er valinn gátreiturinn **Sjálfvirk Vátryggingarbókun** á **uppsetning eigna** glugganum, þá ætti vátryggingabók að vera byggð á færslubókarsniðmát án númeraröð. Þetta er af því að innsett fylgiskjalsnúmerum úr eignabókarlínum munu annars skarast við númeraröðina í vátryggingabók. Nánari upplýsingar um sniðmát færslubókar og keyrsla sjá [Hvernig: setja upp almennar upplýsingar um eignir](fa-how-setup-general.md).

Þegar eign hefur verið úthlutað á vátryggingarskírteini, er valinn gátreitur **Tryggt** á eignaspjaldi. Þegar þú selur eignina, er sjálfkrafa hakað úr gátreitnum.

## <a name="to-create-or-modify-an-insurance-card"></a>Stofna eða Breyting á vátryggingaspjöldum:
Vátryggingarskírteini fyrir eign verður að vera sýnt með vátryggingarspjaldi.

Þegar upplýsingar um breytingar á tryggingarupphæð berast verður að breyta þeim á **vátryggingarspjald** glugganum til að tryggja að greining vátryggingasviðs sé rétt.  

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**,slá inn **tryggingar**, og velja síðan viðeigandi tengil.
2. Veljið aðgerðina **Nýtt** til að Búa til nýtt kort fyrir vátryggingarskírteini. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Einnig geturðu valið vátryggingarskírteini sem þú vilt breyta og veldu svo aðgerðina **Breyta**.

## <a name="to-assign-a-fixed-asset-to-an-insurance-policy-by-posting-from-the-insurance-journal"></a>Til að Tengja eign við vátryggingarskírteini með því að bóka úr vátryggingabók.
Þú úthlutar eign á vátryggingarskírteini með því að bóka í vátryggingasviðsbók.

Eftirfarandi ferli útskýrir hvernig stofna vátryggingarbókarlínu handvirkt. Ef **Sjálfvirk Vátryggingarbókun** gátreitinn er valinn í **uppsetning eigna** glugganum, þá eru línur í vátryggingabók sjálfkrafa stofnaðar þegar kaupverð er bókað. Í því tilfelli er allt sem þarf að gera er að bóka færslubókina.

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **vátryggingarækur**, og velja síðan viðeigandi tengil.
2. Opna skal viðeigandi færslubók og fylla færslubókarlínurnar út eftir þörfum.
3. Til að úthluta mörgum eignum á eina vátryggingarskírteini, skal stofna færslubókarlínur með sömu gildum og í **Vátryggingarnr.** reitnum og mismunandi gildin í reitnum **Eignanr.** .
4. Valið er **bóka** aðgerð.

**Athugasemd**: Færslurnar í vátryggingabók eru aðeins bókaðar í vátryggingasviðshöfuðbókina.  

## <a name="to-update-the-insurance-value-of-a-fixed-asset"></a>Uppfæra tryggingarvirði eignar
Í eftirfarandi dæmi er sýnt hvernig hægt er að nota keyrsluna **Endurmat vátrygginga** til að uppfæra verðmæti eigna sem eru tryggðar.

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**,slá inn **endurmat vátrygginga**, og velja síðan viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum.

    **Athugasemd**: í reitnum **endurmatstala** er Lækkun uppá 5%, til dæmis, færð inn sem 95, en þú færir inn aukningu uppá 2% sem 102.  
3.  Velja hnappinn **Í lagi**.  

    Keyrslan reiknar þessa nýju tölu sem hlutfall af vátryggðu heildarvirði eins og kemur fram í glugganum **Vátryggingaupplýsingar** og býr til línu í vátryggingabókinni.  
4. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **vátryggingarækur**, og velja síðan viðeigandi tengil.
5. Opnaðu viðeigandi Vátryggingabók, endurskoðaðu stofnuð gildi og bókaðu þau síðan í vátryggingasviðshöfuðbókina.

## <a name="to-monitor-insurance-coverage"></a>Eftirlit með vátryggingasviði
Dynamics NAV veitir sérhæfðar skýrslu- og tölfræðiglugga til að greina vátryggingarskírteini, og hvort eignir þínar eru oftryggðar eða vantryggðar.

### <a name="overview-of-insurance-policies"></a>Yfirlit yfir vátryggingaskírteini  
Yfirlit yfir vátryggingarskírteini fæst með því að prenta eða forskoða skýrsluna **Vátrygging – Listi** þar sem sýndar eru allar vátryggingar og helstu reitir á vátryggingarspjöldunum.  

### <a name="insurance-coverage"></a>Vátryggingasvið
Ef skoða á hvaða eignir eru vátryggðar eða hvaða vátryggingar gilda fyrir hverja eign er hægt að prenta eða forskoða skýrsluna **Vátrygging - Tryggt heildarv.**.

### <a name="overunder-coverage"></a>Of-/Vantrygging
Hægt er að athuga hvort eignir eru oftryggðar eða vantryggðar á eftirfarandi hátt:
- Glugginn **Vátryggingaupplýsingar**. Plústala í reitnum **Yfir-/undirtryggt** merkir að eignin sé yfirtryggð. Mínustala merkir að hún sé undirtryggð.
- Glugginn **Eignaupplýsingar** . Veldu reitinn **Vátryggt Heildarvirði** til að skoða **Vátryggingasviðsfærslur** glugginn.  
- **Yfir-/undir Vátryggingasvið** skýrslu.  
- **Tryggingagreining** skýrslan

### <a name="uninsured-fixed-assets"></a>Ótryggðar eignir
Ef ganga á úr skugga um hvort gleymst hafi að tengja eign við vátryggingu er hægt að prenta eða forskoða skýrsluna **Vátrygging - Ótryggðar eignir**. Þessi skýrsla sýnir eignir með upphæðir sem hafa ekki verið bókaðar á vátryggingasviðsbókina.

## <a name="to-view-insurance-coverage-ledger-entries"></a>Skoðun vátryggingasviðsfærslna:
Hægt er að skoða færslurnar sem færðar hafa verið í vátryggingasviðsbókina.  

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**,slá inn **tryggingar**, og velja síðan viðeigandi tengil.  
2. Valin er viðeigandi vátryggingarskírteini og veldu svo **vátryggingasviðsfærslur** aðgerðina.

## <a name="to-view-the-total-insurance-value-of-fixed-assets"></a>Skoðun á vátryggðu heildarvirði eigna:
Sérhæfðu fylkisgluggi sýnir upphæð skráðrar tryggingar við hverja tryggingarstefnu fyrir hverja eign. Þetta eru vátryggingatengdar upphæðir sem bókaðar voru.

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**,slá inn **tryggingar**, og velja síðan viðeigandi tengil.  
2. Valin er viðeigandi vátryggingarskírteini og veldu svo **heildarvirði tryggingar á eign** aðgerðina.
3. Fyllið inn í svæðin eftir þörfum.  
4. Veldu aðgerðina **sýna fylki**.  
5. Til að skoða undirliggjandi vátryggingasviðsfærslur, velja gildi í fylkinu.

## <a name="to-correct-insurance-coverage-entries"></a>Leiðrétting á vátryggingarsviðsfærslum  
Ef eign hefur verið tengd við rangt vátryggingarskírteini er hægt að leiðrétta það með því stofna tvær endurflokkunarfærslur úr vátryggingabókinni.  

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **vátryggingarækur**, og velja síðan viðeigandi tengil.
2. Stofna eina færslubókarlínu fyrir hverja eign og rétt vátryggingarskírteini þar sem gildið í reitnum **Upphæð** er jákvæð.
3. Stofna aðra færslubókarlínu fyrir hverja eign og rangt vátryggingarskírteini þar sem gildið í reitnum **Upphæð** er neikvæð.  
4. Valið er **bóka** aðgerð.

Eignin er losuð frá ranga vátryggingarskírteininu, á annarri línunni, og hengt við rétta vátryggingarskírteinið, á fyrstu línunni.

## <a name="see-also"></a>Sjá einnig
[Eignastjórnun](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

