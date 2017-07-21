---
title: "Hvernig á að setja upp sjóðstreymisspár"
author: bholtorf
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f657509fc2195674db81f47bc5ae31b7ba1aa40e
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-predictive-cash-flow-forecasts"></a>Hvernig á að setja upp sjóðstreymisspár
Spár sjóður flæði hægðarauka er hægt að tryggja að fyrirtækinu hefur nægt sjóður tiltækar til að uppfylla obligations hennar ársreikninga og gagnast til að auðkenna leiðréttingar. Til dæmis ef inngreiðslubók ofáfyllingar gæti borgað óvirka sumum skuldum og sem greitt er fljótt viðvörun hefur hækkunar ef oft tight fletta. 

Cortana Intelligence notar þjónustunni Azure Vélastöðvar Learning gera reliable, predictive spár. Til dæmis spár úr Cortana Intelligence getur hjálpað við að predict, og að forðast, inngreiðslum deficits. Þjónusta sameinar eldri upplýsingar með gildandi bókanir vegna innkaupa og dates sala, þar á meðal bókanir með gjalddaga sem er í framtíðinni. Þar á meðal eru:
* Innkaupapantanir
* Sölupantanir
* Innkaupa- og sölureikningar
* Kreditreikningar

## <a name="before-you-start"></a>Verður að byrja fyrir  
Til eru nokkur atriði til að gera áður en hægt er að nota Cortana Intelligence fyrir staðgreiðslu flæði spár: 
* Ef þegar aren't með staðgreiðslu flæði spár, þarf að setja upp:
    * Eina eða fleiri bókagrunna í **Staðgreiðslu Flæði Bókagrunna**. 
    * Reikningar vegna innkaupa, sala, sölupantanir og innkaupapantanir. Cortana Intelligence notar bókanir þessum reikningum.
    * Eina eða fleiri sjóður flæði spár í **Sjóður Flæði Spá**. Ganga úr skugga um að taka með innkaupapantanir, sölupantanir, útistandandi og gjaldfallið sem veftengingar.  
    Frekari upplýsingar er að leita _staðgreiðslu flæði spár_ í kerfinu Hjálp. 
* Vita API URL og lykillinn API fyrir predictive vefþjónustan sem á að nota.  
    Hægt er að nota Learning Azure Véla- eða aðra þjónustu ef slíkt. Einnig er almennt líkan sem kallast _spálíkanið fyrir Microsoft Dynamics NAV_ tiltækt á netinu í Cortana Intelligence Gallery. Fylgið eftirfarandi skrefum til að fá aðgang að reitunum:

    1. Í inn, farið er í [Cortana Intelligence Gallery](https://go.microsoft.com/fwlink/?linkid=828352)
    2. Leita að _líkaninu Spá fyrir Microsoft Dynamics NAV_, og opna svo líkanið í Azure Machine Learning Studio.
    3. Nota á reikninginn í Microsoft að undirrita fyrir workspace er og afrita síðan líkaninu sem.
    4. Keyrslan líkaninu og út og þjónustu veftengingar.
    5. Gera API URL og API lykillinn athugasemd. Verður að nota þessar skilríki þegar sett er upp Cortana Intelligence í Microsoft Dynamics NAV.  

* Að íhuga hvernig oft til að reikna spá. Þjónusta Azure Vélastöðvar Learning hefur takmarkanir varðandi notkun. Til dæmis, ef lotu vörur er það gæti verið betur til að reikna út minna eru notaðar. 
* Úthlutað Accountant mitt hlutverk. 

## <a name="set-up-cortana-intelligence"></a>Cortana Intelligence
Hægt er að nota er leiðbeiningum assisted grunnur til að setja upp spár vöruflæðinu sjóður. Um hjálpar til við að tilgreina atriði krefur hversu oft eigi að uppfæra spá, til að byggja á, upplýsingar um þegar greiða skattaumhverfi og hvort nota Cortana Intelligence.  

Ef notuð þegar spár vöruflæðinu sjóður og aðeins á að slökkva á Cortana Intelligence er einnig hægt að nota handvirkt ferli. Þegar formerki í tilkynning birtir er blátt strikamerking efst á workspace. Til að setja upp Cortana Intelligence þannig, velja **Já hafa**. Skilaboðin birtir aðeins einu sinni. Ef það er lokað nota handvirkt ferli til að setja upp Cortana Intelligence.  

**Tip:** Lítur lengd tímabila sem þjónustan er notaður í útreikningum hennar. Frekari gögn sem veita verður því nákvæmari á predictions. Líka watch út fyrir mikið frávik í tímabil. Þeir eru einnig hefur predictions. Ef Cortana Intelligence finnur ekki nægt gögnum eða gögnin breytist við lotu, gera á ekki við prediction. 

Uppsetning assisted leiðbeiningum nota til:
1. Í hlutverki Accountant undir á **Spá Sjóður Vöruflæði** myndritið er valið á **Opnar Assisted Uppsetning** aðgerð.
2. Reitirnir fylltir út eftir þörfum hvert skref um í.

Nota handvirkt ferli:
1. Í reitnum **Leit** skal færa inn Sjóðstreymisuppsetningu og velja síðan viðkomandi tengil.
2. Stækka á **Cortana Intelligence** Flýtiflipanum og síðan fyllt út í reitina og þörf krefur.

## <a name="turn-on-cortana-intelligence-for-cash-flow-forecasts"></a>Skila á Cortana Intelligence fyrir spár vöruflæðinu staðgreiðslu
1. Í reitnum **Leit** skal færa inn Sjóðstreymisuppsetningu og velja síðan viðkomandi tengil.
2. Valið er **Sjóður Vöruflæðinu Vinnublað** aðgerð.
3. Í á **Sjóður Flæði Vinnublað** síðunni, velja sem **Vinnublað Tillögulínur** aðgerð.  
4. Undir **Upprunategundir að taka Með**, velja sem **Cortana Intelligence Spá** gátreitinn.

## <a name="investigate-a-cash-flow-forecast"></a>Sett er upp sjóðstreymisspá.
Taka með góð skoða gögn bak spá, þar á meðal frávik, velja sem **Cortana Intelligence** dálk. Fyrsta línan í töflunni birtist frávik. Í öðrum línum henni er raðað eftir upprunaskjalsins.  

Til dæmis er hægt að sjá hvernig spá:    
* Með staðfest sölu og innkaup 
* Dregur gjaldfallið og bætir sala
* Skips afritun sölupantanir og innkaupapantanir

## <a name="see-also"></a>Sjá einnig  
[Unnið með Dynamics NAV](ui-work-product.md)

