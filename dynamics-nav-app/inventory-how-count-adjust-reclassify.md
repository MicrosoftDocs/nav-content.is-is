---
title: "Talning, breytingar og endurflokkun birgða"
description: "Lýsir því hvernig skal framkvæma rauntalningu, gera neikvæðar eða jákvæðar leiðréttingar, og hvernig skal breyta upplýsingum, eins og t.d. staðsetningu eða lotunúmer, á birgðahöfuðbókafærslum eða vöruhúsafærslum. "
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: adjustment, negative, positive, increase, decrease
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4d53e6e9b64e0f5c790abb0f62f66a2b28c12c50
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-count-adjust-and-reclassify-inventory"></a>Hvernig skal: Telja, breyta og endurflokka birgðir.
Minnst einu sinni á hverju fjárhagsári þarf að telja raunbirgðir (það er, telja allar vörur á lager) til að athuga hvort magnið sem skráð er í kerfinu sé það sama og raunbirgðir á lager. Þegar búið er að finna út úr raunbirgðum þarf að bóka þær í fjárhag þegar fram fer mat á birgðum við lok tímabils.

Þó að allar vörur í birgðum séu taldar minnst einu sinni á ári gæti þurft að telja sumar vörur oftar, kannski vegna þess hve verðmætar þær eru eða vegna þess að mikil hreyfing er á þeim og þær eru stór hluti af rekstrinum. Í þessum tilgangi geturðu úthlutað sérstökum talningatímabilum á þessar vörur. Sjá frekari upplýsingar í „Að framkvæma reglulega talningu" liðnum.

Ef nauðsynlegt er að leiðrétta skráð birgðamagn í tengslum við talningu eða í öðrum tilgangi er hægt að nota birgðabók til þess að breyta færslum í birgðum beint án þess að bóka viðskipti. Að öðrum kosti er hægt að leiðrétta einstaka vöru á birgðaspjaldinu.

Ef nauðsynlegt er að breyta eigindum fyrir birgðafærslur auk magns er hægt að nota endurflokkunarbók vöru. Dæmigerðar eigindir til að endurflokka eru til dæmis rað/lotu númer, gildistími og víddir.

> [!NOTE]
> Í grunngerðum í ítarlegu vöruhúsi eru vörur skráðar í hólf sem vöruhúsafærslur, en ekki sem birgðabókafærslur. Þar af leiðandi framkvæmir þú talningu, leiðréttingu og endurflokkun í sérstökum vöruhúsabókum sem styðja hólf. Síðan notarðu sérstakar aðgerðir til að samstilla nýju eða breyttu vöruhúsafærslurnar við tengdar birgðabókafærslur til að endurspegla breytingarnar í birgðamagni og virði. Þessu er lýst í sérstöku ferli hér að neðan, þar sem við á.

## <a name="to-perform-a-physical-inventory"></a>Að framkvæma Raunbirgðatalningu
Gera verður úttekt á raunbirgðum, það er að telja hvað mikið er til í raun og veru af hverri vöru, til að sjá hvort magnið sem er skráð í kerfinu er í samræmi við vörutalningu í lok hvers reikningsárs, eða oftar. Ef munur er á þessu tvennu verður að bóka hann á birgðareikninginn áður en birgðir eru verðmetnar.

Að frátöldum efnislegu talningarverki felur heildarferlið í sér eftirfarandi þrjú verkefni:

- Reikna væntanlegar birgðir.
- Prenta skýrsluna sem verður notuð við talningu.
- Færa inn og bóka raunveruleg taldar birgðir.

Hægt er að framkvæma raunbirgðatalningu á aðra af eftirfarandi vegu eftir því hvernig uppsetningu vöruhússins er háttað: Nánari upplýsingar er að finna í [Uppsetning vöruhúsastjórnunar](warehouse-setup-warehouse.md).  

-   Ef ekki er í birgðageymslunni notaður beinn frágangur og tínsla (skilgreiningar grunnvöruhúss) er **raunbirgðabókin** notuð í valmyndinni **Birgðir** og ferlið er mikið til það sama og þegar raunbirgðir eru teknar án reglubundinnar talningar.  
-   Ef birgðageymslan notar beinan frágang og tínslu (skilgreiningar ítarlegs vöruhúss) þarf fyrst að nota gluggann **Vöruh.- Raunbirgðabók** og síðan gluggann **Birgðabók** til að keyra **Reikna vöruhúsaleiðréttingu** aðgerðina.

### <a name="to-calculate-the-expected-inventory-in-basic-warehouse-configurations"></a>Til að reikna væntanlegar birgðir
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Raunbirgðabók** og velja svo viðeigandi tengil.
2. Veljið aðgerðina **Reikna Birgðir**.
3. Í glugganum **Reikna birgðir** tilgreinið skilyrði sem nota á til að stofna færslubókarlínur, t.d. hvort þær eigi að innihalda vörur sem hafa engar birgðir skráðar.
4. Stilla afmarkanir ef aðeins á að reikna birgðir fyrir ákveðnar vörur, hólf, birgðageymslur eða víddir.
5. Velja hnappinn **Í lagi**.

> [!NOTE]  
>   Birgðafærslurnar eru unnar í samræmi við þær upplýsingar sem tilgreindar voru, og línur eru stofnaðar í raunbirgðabókinni. Takið eftir að reiturinn **Magn (raunbirgðir)** færir sjálfkrafa inn sama magn og reiturinn **Magn (reiknað)**. Með þessum eiginleika er ekki nauðsynlegt að færa inn taldar lagerbirgðir fyrir vörur sem er hafa sama magn og reiknað magn. Ef talið magn er annað en það sem skráð er í reitnum **Magn (reiknað)** þarf að skrifa yfir það með magninu sem talið var.

### <a name="to-calculate-the-expected-inventory-in-advanced-warehouse-configurations"></a>Til að reikna væntanlegar birgðir í grunngerð ítarlegs vöruhúss
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Birgðabók** og velja svo viðeigandi tengil.  
2.  Velja aðgerðina **Reikna vöruhúsaleiðréttingu**  
3.  Númer varanna sem á að telja eru færð inn í beiðniglugga keyrslunnar ásamt birgðageymslunni.
4. Velja hnappinn **Í lagi** hnappinn og bóka leiðréttingarnar ef einhverjar eru.

    Ef þetta er ekki gert áður en talning raunbirgða fer fram verða niðurstöðurnar sem bókaðar eru í raunbirgðabók og birgðabók í öðru þrepi ferlisins, niðurstöður raunbirgðatalningarinnar ásamt öðrum vöruhúsaleiðréttingum á vörunum sem taldar eru.  
5.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vöruhús raunbirgðabók** og velja svo viðeigandi tengil.  
6. Veljið aðgerðina **Reikna Birgðir**. Beiðnigluggi keyrslunnar **Reikna vöruhúsabirgðir** opnast.  
7.  Afmarkanirnar eru stillta til að takmarka vörurnar sem telja á í færslubókinni og síðan er smellt á **Í lagi**.

    Stofnuð er sérstök lína í kerfinu fyrir hvert hólf sem uppfyllir skilyrði afmörkunarinnar. Á þessu stigi er enn hægt að eyða einhverjum línum en ef bóka á niðurstöðurnar sem raunbirgðir þarf að telja vöruna í öllum hólfum þar sem hún er geymd.    

     Ef aðeins er tími til að telja vöruna í sumum hólfum en ekki öllum er hægt að uppgötva ósamræmi, skrá það og bóka það síðar í birgðabókina með því að nota aðgerðina **Reikna vöruhúsaleiðréttingu**.  
8.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vöruhús raunbirgðalisti** og velja svo viðeigandi tengil.  
9.  Skýrslubeiðnisíðan er opnuð og listarnir sem starfsmennirnir eiga að nota til að skrá magn vörunnar sem talið er í hverju hólfi prentaðir út.  
10. Þegar talningu er lokið er talið magn ritað í reitinn **Magn (raunbirgðir)** í raunbirgðabók vöruhússins.  

    > [!NOTE]  
    >  Í raunbirgðabók vöruhússins er reiturinn **Magn (reiknað)** sjálfkrafa fylltur út samkvæmt hólfafærslum vöruhúss og það magn afritað í reitinn **Magn (raunbirgðir)** á hverri línu. Ef magnið sem talið er af starfsmanni vöruhússins samsvarar ekki magninu sem fært er sjálfkrafa í reitinn Magn (raunbirgðir) þarf að rita magnið sem talið var.  

11. Þegar allt talið magn hefur verið fært inn er valin aðgerðin **Skrá**.  

    Þegar færslubókin er skráð eru tvær vöruhúsafærslur stofnaðar í vöruhúsadagbók fyrir hverja línu sem var talin og skráð:  

    -   Ef misræmi er milli reiknaðs magn og raunmagns er neikvætt eða jákvætt magn skráð fyrir hólfið og jöfnunarmagn bókað í leiðréttingarhólf birgðageymslunnar.  
    -   Ef reiknað magn er jafnt raunmagni er færslan 0 skráð bæði fyrir hólfið og leiðréttingarhólfið. Færslurnar eru skráning á því að á skráningardegi hafi talning raunbirgða í vöruhúsi farið fram og ekkert misræmi hafi verið í birgðum fyrir vöruna.  

Þegar raunbirgðir vöruhússins eru skráðar er ekki bókað í birgðahöfuðbók, raunbirgðabók eða virðisbók heldur eru færslurnar til reiðu fyrir afstemmingu þegar þess þarf. Eigi hins vegar að halda nákvæmar tölur um hvað fer fram í vöruhúsin og öll hólf þar sem varan er skráð hafa verið talin skal strax bóka vöruhúsaniðurstöðurnar sem raunbirgðir. Frekari upplýsingar, sjá „Færa inn og bóka rauntaldar birgðir í grunngerð ítarlegs vöruhúss“.

### <a name="to-print-the-report-to-be-used-when-counting"></a>Prenta skýrsluna sem verður notuð við talningu.
1. Í glugganum **Raunbirgðabók** sem inniheldur útreikning áætlaðra birgða skal velja **Prenta** aðgerðina.
2. Í glugganum **Raunbirgðalisti** tilgreinið hvort skýrslan skuli sýna reiknað magn og hvort skýrslan eigi að birta birgðavörur eftir rað-/lotunúmerum.
3. Setjið upp afmarkanir ef aðeins á að prenta skýrsluna fyrir ákveðnar vörur, hólf, birgðageymslur eða víddir.
4. Velja hnappinn **Prenta**.

Starfsmenn geta nú haldið áfram að telja birgðir og skrá hugsanlegt misræmi þegar skýrslan er prentuð.

### <a name="to-enter-and-post-the-actual-counted-inventory-in-basic-warehouse-configurations"></a>Til að færa inn og bóka raunverulegar taldar birgðir í grunngerð vöruhúss.
1. Í hverri línu í **Raunbirgðabók** glugganum, þar sem tiltækt raunbirgðamagn, samkvæmt rauntalningu, er annað en reiknað magn, er fært inn raunbirgðamagn í reitinn **Magn raunbirgðir**.

    Viðeigandi reitir eru uppfærðir í samræmi við það.

    > [!NOTE]  
   >   Ef við raunbirgðatalningu kemur í ljós munur vegna vara hafi verið bókaðar með röngum birgðageymslukótum er munurinn ekki færður inn í raunbirgðabókina. Í staðinn skal nota endurflokkunarbók eða millifærslupöntun til að beina vörunum á rétta staði. Frekari upplýsingar, sjá Birgðafærslubók enduflokkunar eða Hvernig á að stofna Millifærslupantanir.

2. Til að leiðrétta reiknað magn í raunverulegt talið magn skal velja aðgerðina **Bóka**.

    Bæði birgðafærslur og raunbirgðabókarfærslur eru stofnaðar. Opna birgðaspjaldið til að skoða raunbirgðafærslur sem leiða af því.

3. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.
4. Til að staðfesta birgðatalningu skal opna það birgðaspjald sem um ræðir, og veljið síðan aðgerðina **Raunbirgðafjárhagsfærslur**.

### <a name="to-enter-and-post-the-actual-counted-inventory-in-advanced-warehouse-configurations"></a>Til að færa inn og bóka raunverulegar taldar birgðir í grunngerð ítarlegs vöruhúss.

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Birgðabók** og velja svo viðeigandi tengil.  
2.  Velja aðgerðina **Reikna vöruhúsaleiðréttingu**  
3.  Velja skal sömu vörur og taldar voru í reglubundinni talningu raunbirgða auk allra annarra vara sem krefjast leiðréttinga og því næst hnappinn **Í lagi**.  

     Glugginn **Birgðabók** opnast og línur eru stofnaðar fyrir þessar vörur. Athugið að nettómagn sem var talin og skráð hólf fyrir hólf e nú hægt að sameina og samstilla sem birgðafærsla.  

4.  Bóka skal færslubók án þess að magni sé breytt.  

Magnið í birgðabókinni (birgðafærslur) og magnið í vöruhúsinu (vöruhúsafærslur) er nú á ný það sama fyrir þessar vörur og kerfið hefur uppfært dagsetningu síðustu talningar á vörunni eða birgðahaldseiningu.  

## <a name="to-perform-cycle-counting"></a>Að framkvæma reglulega talningu
Þó að allar vörur í birgðum séu taldar minnst einu sinni á ári gæti þurft að telja sumar vörur oftar, kannski vegna þess hve verðmætar þær eru eða vegna þess að mikil hreyfing er á þeim og þær eru stór hluti af rekstrinum. Í þessum tilgangi geturðu úthlutað sérstökum talningatímabilum á þessar vörur.

Hægt er að framkvæma reglubundna talningu á aðra af eftirfarandi vegur eftir uppsetningu vöruhússins Nánari upplýsingar er að finna í [Uppsetning vöruhúsastjórnunar](warehouse-setup-warehouse.md).  

-   Ef ekki er í birgðageymslunni notaður beinn frágangur og tínsla (skilgreiningar grunnvöruhúss) er **raunbirgðabókin** notuð í valmyndinni **Birgðir** og ferlið er mikið til það sama og þegar raunbirgðir eru teknar án reglubundinnar talningar.  
-   Ef birgðageymslan notar beinan frágang og tínslu (skilgreiningar ítarlegs vöruhúss) þarf fyrst að nota gluggann **Vöruh.- Raunbirgðabók** og síðan gluggann **Birgðabók** til að keyra **Reikna vöruhúsaleiðréttingu** aðgerðina.  

### <a name="to-set-up-counting-periods"></a>Talningatímabil sett upp
Raunbirgðir eru vanalega taldar með jöfnu millibili, til dæmis mánaðarlega, ársfjórðungslega eða árlega. Hægt er að setja upp þau talningatímabil sem þarf.

Birgðatalningatímabilin sem á að nota eru sett upp og síðan er einu slíku úthlutað á hverja vöru. Þegar raunbirgðir eru taldar og aðgerðin **Reikna talningatímabil** er notuð í raunbirgðabók eru línur fyrir vörurnar búnar til sjálfkrafa.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Talningartímabil raunbirgða** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

### <a name="to-assign-a-counting-period-to-an-item"></a>Talningatímabili úthlutað á vöru  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.  
2. Varan sem úthluta á talningartímabili er valin.  
3. Á reitnum **Kóti talningartímabils raunbirgða** skal velja viðkomandi talningartímabil.  
4. Velja **Já** til að breyta kótanum og reikna út fyrsta talningartímabilið fyrir vöruna. Næst þegar valið er að reikna út talningatímabil í raunbirgðabók vöruhúss, birtist varan sem lína í glugganum **Vöruval raunbirgða**. Nú er hægt að byrja telja vöruna með reglulegu millibili.

### <a name="to-initiate-a-count-based-on-counting-periods-in-basic-warehouse-configurations"></a>Að hefja talningu byggða á talningartímabilum í grunngerð vöruhúss.
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Raunbirgðabók** og velja svo viðeigandi tengil.
2. Veljið **Reikna talningartímabil** aðgerðina.

    Glugginn **Vöruval raunbirgða** opnast þar sem vörurnar sem talningatímabil hafa verið sett upp fyrir sem þarf að telja eru samkvæmt talningartímabilum þeirra.
3. Framkvæma raunbirgðatalningu. Frekari upplýsingar, sjá „Framkvæma raunbirgðatalningu“ hlutann.

### <a name="to-initiate-a-count-based-on-counting-periods-in-advanced-warehouse-configurations"></a>Að hefja talningu byggða á talningartímabilum í grunngerð ítarlegs vöruhúss.
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vöruhús raunbirgðabók** og velja svo viðeigandi tengil.  
2. Veljið **Reikna talningartímabil** aðgerðina.

    Glugginn **Vöruval raunbirgða** opnast þar sem vörurnar sem talningatímabil hafa verið sett upp fyrir sem þarf að telja eru samkvæmt talningartímabilum þeirra.
3. Framkvæma raunbirgðatalningu. Frekari upplýsingar, sjá „Framkvæma raunbirgðatalningu“ hlutann.  

    > [!NOTE]  
    >  Telja þarf vörurnar í öllum hólfunum sem innihalda þær vörur. Ef sumum af hólfalínunum sem kerfið sækir fyrir talningu í glugganum **Raunbirgðir vöruhúss** er eytt verða ekki taldar allar vörur í vöruhúsinu. Ef þess háttar ófullkomnar niðurstöður eru seinna bókaðar í Raunbirgðabók verður magnið sem bókað er rangt.  

## <a name="to-adjust-the-inventory-of-one-item"></a>Leiðrétta birgðastöðu einnar vöru
Eftir að búið er að telja vöru á birgðasvæði er hægt að nota eiginleikann **Leiðrétta birgðir** til að skrá raunverulegt magn í birgðum.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.
2. Veljið þá vöru sem leiðrétta birgðir fyrir og veldu svo **leiðrétta birgðir** aðgerðina.
3. Í reitnum **nýjar birgðir** skaltu slá inn birgðamagn sem þú vilt skrá fyrir vöruna.
4. Velja hnappinn **Í lagi**.

Birgðir vörunnar hafa nú verið leiðréttar. Nýja magni er birt í reitnum **Núverandi birgðir** í glugganum **leiðrétta birgðir** og í reitnum **birgðir** í glugganum **vöruspjald**.

Einnig er hægt að nota aðgerðina **Leiðrétta birgðir** sem einfalda leið til að staðsetja keypta vöru í birgðum ef þú ætlar ekki að nota gluggann innkaupareikningur til að skrá innkaupin. Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).

> [!NOTE]  
>   Eftir að þú hefur leiðrétt birgðir þarftu að uppfæra þær með núverandi útreiknuðu virði. Frekari upplýsingar eru í [Hvernig á að: Endurmeta birgðir](inventory-how-revalue-inventory.md).

### <a name="to-adjust-the-inventory-quantity-of-multiple-items-in-basic-warehouse-configurations"></a>Leiðrétta birgðamagn margra vara í grunngerð vöruhúss
Í glugganum **Birgðabók** er hægt að bóka birgðafærslu beint til að leiðrétta birgðaskrá í tengslum við innkaup, sölu og jákvæða eða neikvæða leiðréttingu án þess að nota fylgiskjöl.

Ef birgðabókin er oft notuð til að bóka sömu eða svipaðar færslubókarlínur, til dæmis í tengslum við efnisnotkun, er hægt að nota **Stöðluðu birgðabókina** til að auðvelda þessa endurteknu vinnu. Frekari upplýsingar, sjá hlutann „Staðlaðar færslubækur“ [Unnið með almennar færslubækur](ui-work-general-journals.md).

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Birgðafærslubækur** og velja svo viðeigandi tengil.
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Veljið aðgerðina **bóka** til að gera birgðaleiðréttingarnar.

> [!NOTE]  
>   Eftir að þú hefur leiðrétt birgðir þarftu að uppfæra þær með núverandi útreiknuðu virði. Frekari upplýsingar eru í [Hvernig á að: Endurmeta birgðir](inventory-how-revalue-inventory.md).

### <a name="to-adjust-bin-quantities-in-advanced-warehouse-configurations"></a>Leiðrétta hólfamagn í grunngerð ítarlegs vöruhúss  
Ef staðsetningin notar beinan frágang og tínsla er **Birgðabók vöruhúss** notuð, án samhengis við raunbirgðir, til að bóka allar jákvæðar og neikvæðar leiðréttingar á vörumagni sem vitað er að eru raunverulega viðbót, til dæmis vörur sem áður hafa verið bókaðar sem týndar en finnast óvænt, eða raunverulegur missir, t.d. ef viðkvæmar vörur brotna.  

Þegar leiðréttingar eru bókaðar í birgðabók vöruhúss en ekki í birgðabókinni verða magnfærslur ætíð nákvæmari. Þannig eru alltaf til upplýsingar í vöruhúsinu um það hve mikið af vörum er til reiðu og hvar þær eru geymdar, en hver leiðréttingarfærsla er ekki bókuð jafnóðum í birgðahöfuðbók. Í skráningarferlinu er bætt við eða dregið frá raunverulega hólfinu með magnleiðréttingunni og búin til mótjöfnunarfærsla í leiðréttingarhólfi vöruhúss, sýndarhólfi með engum raunverulegum vörum. Þetta hólf er skilgreint í **hólfakóða birgðaleiðréttingar** á birgðageymsluspjaldi.

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Birgðabók vöruhúss** og velja svo viðeigandi tengil.  
2.  Upplýsingar fyrir hausinn eru færðar inn.  
3.  Reiturinn **Vörunr.** er fylltur út á línunni.  
4.  Hólfið þar sem viðbótarvörurnar eru settar eða þar sem vörur vantar er fært inn.  
5.  Magnið sem munar er fært í reitinn **Magn**. Hafi viðbótarvörur fundist er ritað jákvætt magn. Vanti vörur er ritað neikvætt magn.  
6.  Velja aðgerðina **Skrá**.

## <a name="to-synchronize-the-adjusted-warehouse-entries-with-the-related-item-ledger-entries"></a>Samstilla leiðréttar vöruhúsafærslur við tengdar birgðabókafærslur
Með vissu millibili, sem ræðst af reglum fyrirtækisins, þarf að bóka færslur í leiðréttingarhólfi vöruhússins í birgðahöfuðbók. Sumum finnst við hæfi að bóka leiðréttingar á birgðahöfuðbókinni daglega en öðrum þykir nóg að gera það sjaldnar.

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Birgðabók** og velja svo viðeigandi tengil.  
2.  Reitirnir eru fylltir út fyrir hverja línu.  
3.  Velja aðgerðina **Reikna vöruhúsaleiðréttingu** og fyllið út afmarkanir eins og við á í beiðniglugga keyrslunnar. Leiðréttingar eru eingöngu reiknaðar fyrir færslurnar í leiðréttingarhólfinu sem uppfylla afmörkunarkröfurnar.  
4.  Á flýtiflipanum **Valkostir** er tala færð handvirkt inn í reitinn **Númer fylgiskjals**. Þar sem engar númeraraðir hafa verið settar upp fyrir þessa keyrslu skal nota númeraskema sem sett er upp í vöruhúsinu eða færa inn dagsetninguna og upphafsstafi notanda á eftir.  
5.  Velja hnappinn **Í lagi**. Lagðar eru saman jákvæðar og neikvæðar leiðréttingar fyrir hverja vöru og stofnaðar línur í birgðabókinni fyrir allar vörur þar sem samtalan er jákvætt eða neikvætt magn.  
6.  Bóka skal línurnar til þess að færa mismun á magni inn í birgðahöfuðbók. Birgðirnar í vöruhúsahólfunum samsvara nú nákvæmlega birgðunum í birgðahöfuðbókinni.  

## <a name="to-reclassify-an-items-lot-number"></a>Að endurflokka lotunúmer vöru
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Birgðaendurflokkunarbækur** og velja svo viðeigandi tengil.
2. Í glugganum **Birgðaendurflokkunarbók** skal fylla út reitina eins og þörf krefur.
3. Í reitinn **Lotunr.**, færið inn núverandi lotunúmer vörunnar.
4. Í reitinn **Nýtt Lotunr.**, færið inn nýtt lotunúmer vörunnar.
5. Valið er **Bóka** aðgerðin.

Sérstök skref eiga við þegar þú vilt endurflokka rað- eða lotunúmer. Frekari upplýsingar, sjá [Hvernig á að: vinna með rað- og lotunúmer](inventory-how-work-item-tracking.md).

## <a name="see-also"></a>Sjá einnig
[Birgða](inventory-manage-inventory.md)
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)    
[Sala](sales-manage-sales.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

