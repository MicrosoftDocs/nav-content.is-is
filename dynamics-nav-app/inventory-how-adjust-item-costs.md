---
title: "Leiðrétta birgðakostnað handvirkt"
description: "Þú getur leiðrétt birgðaverðmat vöru með því að nota FIFO eða Meðalkostnaðaraðferð, til dæmis þegar vöruverð breytist ekki vegna viðskiptalegra ástæðna, heldur einhvers annars."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cost adjustment, cost forwarding, costing method, inventory valuation, costing
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 40647e0263b7c21c1f085cd6dde449f8210ede10
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-adjust-item-costs"></a>Hvernig á að: Leiðrétta birgðakostnað
Kostnaðarverð vöru (birgðavirði) sem er keypt og seld síðar getur breyst á líftímanum, til dæmis vegna þess að kostnað við frakt er bætt við innkaupakostnaðinn þegar varan hefur verið seld. Kostnaðaraðlögun er sérstaklega viðeigandi í aðstæðum þar sem þú selur vörur áður en þú reiknar kaupin á þeim vörum. Til þess að vita alltaf rétt birgðavirði verður því að leiðrétta kostnaðarverð vöru reglubundið. Þetta tryggir að sölu- og hagnaðartölur séu réttar og afkastavísar (KPI) fjárhags séu réttir. Nánari upplýsingar, sjá [Upplýsingar um hönnun: Kostnaðarleiðrétting](design-details-cost-adjustment.md)

Sem regla er gildið í reitnum **Unit Cost** á birgðaspjaldinu byggt á stöðluðu kostnaðarverði vöru og staðlaðri aðferð við kostnaðarútreikning. Fyrir vörur með öllum öðrum aðferðum við kostnaðarútreikning er þetta byggt á útreikningi á fáanlegum birgðum (reikningsfærður kostnaður og væntanlegur kostnaður) deilt með tiltæku magni. Sjá „Skilja útreikning kostnaðarverðs“ fyrir frekari upplýsingar.

Í [!INCLUDE[d365fin](includes/d365fin_md.md)] eru kostnaðarkostnaður sjálfkrafa leiðrétt í hvert skipti sem viðskiptin eiga sér stað, svo sem þegar þú sendir inn innkaupareikning fyrir hlut.

Þú getur einnig notað aðgerð til að breyta kostnaði við einn eða fleiri hluti handvirkt. Þetta er gagnlegt, til dæmis þegar þú veist að kostnaður hlutar hefur breyst af öðrum ástæðum en vörufærslu.

Kostnaðarverð er leiðrétt með FIFO eða Meðalkostnaðaraðferð, það fer eftir vali þínu í **Uppsetning fyrirtækis** í uppsetning með aðstoð eða í reitnum **Aðferð kostnaðarútreiknings** á vöruspjaldinu. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-items.md).  

Ef þú notar FIFO kostnaðaraðferð, þá er einingarverð vöru raunvirði sérhverrar innhreyfingar vörunnar. Fyrir verðmat birgða, er gert ráð fyrir að vörur sem settar voru fyrst í birgðir seljist fyrst.

Ef þú notar Meðalkostnaðaraðferð, er einingaverð vara reiknað út sem meðaleiningaverð á hverjum tímapunkti eftir innkaup. Fyrir verðmat birgða, er gert ráð fyrir að allar birgðir verði seldar á sama tíma. Fyrir vörur sem nota þessa aðferð kostnaðarútreiknings geturðu valið **kostnaðarverð** reitinn á vöruspjaldinu til að skoða færslusöguna sem meðalkostnaður er reiknaður út frá

Kostnaðarleiðréttingin vinnur aðeins virðisfærslur sem hafa ekki verið lagfærðar. Ef keyrslan þarf að flytja kostnaðarbreytingar á innleið í tengdar færslur á útleið gerir hún það með því að stofna nýjar virðisleiðréttingarfærslur sem byggja á upplýsingum um upphaflegar virðisfærslur en innihalda leiðréttingarupphæðina. Kostnaðarleiðréttingin notar dagsetningu bókunar upphaflegu virðisfærslunnar í leiðréttingarfærslunni nema hún sé í lokuðu birgðatímabili. Í því tilfelli notar kerfið upphafsdagsetningu næsta birgðatímabils. Ef birgðatímabil eru ekki notuð munu gögnin í reitnum **Bókun leyfð frá** í glugganum **Fjárhagsgrunnur** skilgreina hvenær leiðréttingarfærslan er bókuð.

## <a name="to-adjust-item-costs-manually"></a>Til að uppfæra birgðakostnað verks handvirkt
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Leiðrétta kostnað - Birgðafærslur** og velja svo viðeigandi tengil.
2. Í glugganum **Leiðr. Kostnað - Birgðafærslur** skal tilgreina hvaða vörur á að leiðrétta kostnað fyrir.
3. Velja hnappinn **Í lagi**.

## <a name="to-make-general-changes-in-the-direct-unit-cost"></a>Almennar breytingar gerðar í Innk.verð:
Ef breyta þarf innkaupaverðinu fyrir marga hluti er hægt að nota **Leiðrétta vörukostnað/verð** keyrsluna.  

 Keyrslan breytir innihaldi reitsins **Einingarverð** á birgðaspjaldinu. Keyrslan breytir efni reitsins á sama hátt fyrir allar vörur eða valdar vörur. Keyrslan margfaldar gildið í reitnum með leiðréttingarstuðli sem notandi tilgreinir.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Leiðrétta vörukostnað/verð** og velja svo viðeigandi tengil.  
2. Í reitnum **Leiðr. reit**, skal tilgreina hvaða vöru eða birgðahaldseiningarspjald reit á að leiðrétta.  
3. Í reitnum **Leiðréttingarstuðull** skal tilgreina stuðulinn sem gildinu verður breytt eftir. Til dæmis færa inn **1,5** til að hækka gildið um 50%.  
4. Á flýtiflipanum **Vara** skal setja upp afmarkanir til að tilgreina, til dæmis, hvaða vörur á að vinna með runuvinnslunni.  
5. Velja hnappinn **Í lagi**.  

## <a name="understanding-unit-cost-calculation"></a>Skilja útreikning kostnaðarverðs
Sem regla er gildið í reitnum **kostnaðarverð** á birgðaspjaldinu byggt á stöðluðu kostnaðarverði vöru og staðlaðri aðferð við kostnaðarútreikning. Fyrir vörur með öllum öðrum aðferðum við kostnaðarútreikning er þetta byggt á útreikningi á fáanlegum birgðum (reikningsfærður kostnaður og væntanlegur kostnaður) deilt með tiltæku magni.  

 Í eftirfarandi köflum er lýst nánar hvernig reiturinn **Aðferð kostn.útreiknings** hefur áhrif á útreikning innkaupaverðs fyrir innkaup og sölu:  

## <a name="unit-cost-calculation-for-purchases"></a>Útreikningur kostnaðarverðs fyrir innkaup  
 Þegar vörur eru keyptar afritar kerfið alltaf gildið í reitnum **Síðasta innk.verð** á birgðaspjaldinu yfir í reitinn **Innk.verð** í innkaupalínu eða í línuna Einingarkostnaður í birgðabókarlínu.  

 Það sem valið er í reitnum **Aðferð kostnaðarútreiknings** hefur áhrif á hvernig [!INCLUDE[d365fin](includes/d365fin_md.md)] reiknar innihald reitarins **Einingarkostnaður** á línunum.  

### <a name="costing-method-fifo-lifo-specific-or-average"></a>Aðferð kostn.útreiknings FIFO, LIFO, Innslegið eða Meðal  
 [!INCLUDE[d365fin](includes/d365fin_md.md)] reiknar út í reitinn **Einingarkostnaður SGM** í innkaupalínunni eða í reitinn **Einingarkostnaður** í birgðabókarlínunni eftir þessari reiknireglu:  

 “Kostn.verð (SGM) = (Beinn kostnaður – (Afsláttarupphæð / Magn)) x (1 + “Óbein kostnaðar % / 100) + Hlutf. sameiginl. Kostn  

### <a name="costing-method-standard"></a>Stöðluð aðferð kostn.útreiknings  
 Reiturinn **Kostn.verð (ISK)** á innkaupalínunni eða reiturinn **Kostnaðarverð** hefur verið fylltur út í birgðabókarlínunni með gildinu í reitnum **Kostnaðarverð** á birgðaspjaldinu. Þegar aðferð kostnaðarútreiknings er stöðluð byggist þetta alltaf á stöðluðum kostnaði.  

 Þegar innkaup eru bókuð er kostnaðarverð úr innkaupalínunni eða bókarlínunni afritað yfir í vörufærslu innkaupareiknings; þetta er hægt að skoða á færslulista vörunnar.  

### <a name="all-costing-methods"></a>Allar aðferðir kostn.útreiknings  
 Kostnaðarverðið í upprunaskjalslínunni er notað til að reikna út efni reitsins **Kostnaðarupphæð raunveruleg** eða, ef við á reitinn **Kostnaðarupphæð (væntanleg)** sem tengist þessari birgðafærslu, sama hvaða kostnaðaraðferð er notuð á vöruna.  

## <a name="unit-cost-calculation-for-sales"></a>Útreikningur kostnaðarverðs fyrir sölu  
 Þegar vörur eru seldar er kostnaðarverðið afritað úr reitnum Einingarkostnaður á birgðaspjaldinu yfir í sölulínu eða birgðabókarlínu.  

 Við bókun er kostnaðarverðið afritað yfir á birgðafærslu sölureiknings og má skoða það á færslulista vörunnar. [!INCLUDE[d365fin](includes/d365fin_md.md)] notar kostnaðarverðið í upprunaskjalslínunni til að reikna út efni reitsins **Kostnaðarupphæð (raunveruleg)** eða, ef við á **Kostnaðarupphæð (væntanleg)** reitinn í gildisfærslunni sem tengist þessar vörufærslu.  

## <a name="see-also"></a>Sjá einnig
[Birgðakostnaði stjórnað](finance-manage-inventory-costs.md)  
[Birgðir](inventory-manage-inventory.md)  
[Sala](sales-manage-sales.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

