---
title: "Hvernig á að skrá notkun og frálag fyrir eina framleiðslupöntun"
description: "Þessi aðgerð er framkvæmd í glugganum **Framleiðslubók**. Bókin sameinar aðgerðir notkunarbókar og afkastabókar í eina bók sem hægt er komast í beint úr framleiðslupöntun. Hún er notuð í handvirka bókun íhlutanotkunar, lokamagns framleiddra vara og tíma sem fer í aðgerðir. Megintilgangur hennar er að bóka handvirkt notkun íhluta, magn framleiddra endanlegra vara og stundir sem búið er að eyða í aðgerðir."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e912412475c8b62404d7c417b9ae3ebbddeb9a17
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-register-consumption-and-output-for-one-released-production-order-line"></a>Hvernig á að: skrá notkun og frálag fyrir eina útgefna framleiðslupöntunarlínu | Microsoft Docs
Þessi aðgerð er framkvæmd í glugganum **Framleiðslubók**. Bókin sameinar aðgerðir notkunarbókar og afkastabókar í eina bók sem hægt er komast í beint úr framleiðslupöntun. Hún er notuð í handvirka bókun íhlutanotkunar, lokamagns framleiddra vara og tíma sem fer í aðgerðir. Megintilgangur hennar er að bóka handvirkt notkun íhluta, magn framleiddra endanlegra vara og stundir sem búið er að eyða í aðgerðir. Gildin eru bókuð í fjárhagsfærslur undir útgefnu framleiðslupöntuninni. Notkunarmagn bókað sem neikvæðar Færslur í birgðafærslum, Frálagsmagn er bókað sem jákvæðar birgðafærslur og tími sem varið er er bókaður sem afkastagetufærslur. Þessi bókuðu gildi er einnig hægt að skoða neðst í bókinni sem raunverulegt magn.  

> [!NOTE]  
>  Þar sem gögn um notkun eru unnin með gögnum um afköst bíður þessi bók uppá að birta tengda íhluti og aðgerðir í rökrænni uppbyggingu framvindu. Íhlutir eru inndregnir undir viðeigandi aðgerð. Þetta kallar á notkun leiðartengilskóða.  

> [!NOTE]  
>  Íhlutir án leiðartengilskóta er skráðir fyrst í bókina.  

## <a name="to-register-consumption-and-output"></a>Notkun og frálag skráð  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Útgefnar framleiðslupantanir** og velja svo viðeigandi tengil.  
2.  Opna skal útgefna framleiðslupöntunarlínu sem er tilbúin til skráningar, og svo á flýtiflipanum **Línur** skal velja **Lína**, aðgerðina og svo **Framleiðslubók** aðgerðina.  

    Þegar glugginn **Framleiðslubók** er opnaður birtast bókarlínur fyrir framleiðslupöntunarlínu í samræmi við gluggana **Framl.pöntunaríhlutur** og **Leið framl.pöntunar**. Þessar línur koma úr framleiðsluuppskriftinni og leiðum sem úthlutað er á vöruna sem verið er að framleiða. Frekari upplýsingar, sjá [Hvernig skal: Stofna framleiðsluuppskriftir](production-how-to-create-routings.md).  

3.  Í reitnum **Bókunardags.** efst í bókinni er hægt að bóka dagsetningu sem gildir fyrir allar línur. Vinnudagsetningin er sjálfgefin. Reiturinn er notaður til að samstilla bókunardagsetningar allra lína á fljótlegan hátt, ef þörf er á.  

    > [!NOTE]  
    >  Bókunardagsetningar í einstökum línum hafa forgang yfir þessum reit.  

4.  Í afmörkunarreitnum **Birgðaskráningaraðferð** efst í bókinni er hægt að velja að skoða notkun og afköst sem eru bókuð sjálfvirkt (skráð) samkvæmt birgðaskráningaraðferðum sem tilgreindar eru fyrir vöruna og forðann.  

    Í öllum tegundum lína í færslubókinni, eru einungis viðkomandi reitir sýndir. Aðrir eru auðir og ritvarðir.  

    Þegar bókin er opnuð er magn sem á að bóka forskráð. Ef ekkert hefur verið bókað fyrir eru allir magnreitir sjálfgefið útfylltir með áætluðu magni sem tekið er úr framleiðslupöntuninni. Ef bókað hefur verið að hluta sýna magnreitirnir það magn sem eftir er. Það magn og sá tími sem þegar er búið að bóka er birt neðst í bókinni sem raunverulegar færslur.  

    Þegar kemur að magni í reitnum **Afkastað magn** er hægt að velja hvaða gildi eru forstillt þegar bókin er fyrst opnuð. Þetta er gert í glugganum **Uppsetning framleiðslu** í flipanum **Almennt**, nánar tiltekið reitnum **Forstillt frálagsmagn**. 

5.  Því næst eru viðeigandi notkun og frálagsmagn færð inn í skrifanlega reiti.  

    > [!NOTE]  
    >  Aðeins frálagsmagn í síðustu bókarlínunni með færslutegundina **Frálag** leiðréttir birgðastigið þegar bókin er bókuð. Því ætti ekki að bóka bókina með áætlað afkastamagn forstillt á síðustu afkastalínunni fyrr en allar lokavörur hafa verið framleiddar.  

6.  Gátmerki er sett í reitinn  **Lokið** í afkastlínum til að gefa til kynna að aðgerðinni sé lokið. Þessi reitur tengist reitnum **Staða leiðar** á leiðarlínu framleiðslupöntunar.  
7.  Smellt á aðgerðina **Bóka** til að skrá magn sem slegið hefur verið inn og svo er bókinni lokað.  

Færslubókin mun innihalda gildi sem enn á eftir að bóka, ef einhver eru, næst þegar hún er opnuð. Bókuð gildi birtast sem raunveruleg gildi neðst í færslubókinni.  

> [!NOTE]  
>   Ef vara sem verið er að nota er lokuð bókar bókin ekki notkunarmagn fyrir hana. Ef vél eða vinnustöð er lokuð bókar bókin ekki afkastað magn eða vinnslutíma í þá afkastalínu.  

> [!NOTE]  
>  Ef bókinni er lokað án bókana glatast breytingarnar.  

> [!WARNING]  
>  Tveir notendur geta ekki notað gluggann **Framleiðslubók** á sama tíma. Þetta merkir að ef notandi 2 opnar gluggann og færir inn gögn þegar notandi 1 er þegar að vinna í glugganum gæti notandi 2 tapað gögnum þegar notandi 1 lokar glugganum.  

## <a name="see-also"></a>Sjá einnig  
[Framleiðsla](production-manage-manufacturing.md)    
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Áætlun](production-planning.md)      
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

