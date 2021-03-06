---
title: "Setja upp og stjórna fjárhagsáætlun fyrir verk"
description: "Lýsir því hvernig skal áætla tilföng og spá fyrir um og stjórna kostnaði verks með því að setja upp fjárhagsáætlun fyrir hvert verk."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project budget, forecast
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 69ac2811e90985f49739ef3e5df020f136112654
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-job-budgets"></a>Hvernig á að: Vinna með verkáætlanir
Hægt er að setja upp áætlun fyrir hvert verk. Áætlunin er notuð til að áætla forðann sem hægt er að úthluta verki. Áætlunin getur verið almenns eðlis með fáeinum færslum eða með mörgum færslum sem skiptast í aðgerðastig. Svo er hægt að bera áætlaðar upphæðir saman við raunverulega notkun eins og hún birtist í verkbókinni. Með því að fylgjast með mismuni á milli raunnotkun og áætlaðri notkun er hægt að stýra yfirstandandi verkefni og auka gæði síðari verka með því að draga úr hættu á að kostnaður sé vanmetinn.

Eftirfarandi aðferð lýsir því hvernig á að meta áætlaðan kostnað við áætlun. Upplýsingar um skráningu áætlunar samanborið við raunverulegt verð og kostnað verks má sjá í [Hvernig á að: Skrá notkun vegna verka](projects-how-record-job-usage.md).  

## <a name="JobBudgetCosts"></a> Til að áætlað kostnað verks
Þegar viðskiptavinur vill vita verð verks sem verður reikningsfært samkvæmt notkun þarf að ákvarða áætlaðan kostnað verksins. Glugginn **Verkhlutalínur** er notaður til þess.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Verk** og velja svo viðeigandi tengil.  
2. Opnið viðeigandi verk.
3. Veljið verkhlutalínu af gerðinni Bókun og veljið svo aðgerðina **Verkáætlunarlínur**.
4. Fyllið í reitina eftir þörfum í nýrri línu. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]   

Fyrir reitinn **Línugerð** skal vísa til eftirfarandi upplýsinga.  

| Tegund línu | Lýsing |
| --- | --- |
| **Bæði fjárhagsáætlun og reikningshæft** |Upphæðir kostnaðar og verðs sem færðar eru í áætlunarlínuna eru áætlaður kostnaður þeirrar áætlunarlínu. Verðupphæðin verður reikningsfærð. |
| **Fjárhagsáætlun** |Viðskiptavinurinn er ekki rukkaður um notkun. notkunina er aldrei hægt að flytja á reikning en hún verður samt notuð í útreikningum VÍV. |
| **Reikningshæft** |Viðskiptavinurinn er rukkaður um notkun. Notkun er færð á reikninginn samkvæmt magninu sem tilgreint er í reitnum Magn til flutnings á reikning. |

> [!NOTE]  
>   Reiturinn **Áætlunardagsetning** fyrir áætlunarlínuna inniheldur dagsetninguna þegar áætlað er að notkun tengd áætlunarlínunni verði lokið. Það er líka dagsetningin þegar hægt er að flytja áætlunarlínuna á sölureikning og bóka hana.  

> [!NOTE]  
>   Þegar þú fyllir í reitinn **Magn**, verða allar upplýsingar um heildarverð og heildarkostnað reiknaðar út og settar í áætlunarlínuna. Hægt er að breyta þeim hvenær sem er.

Í glugganum **Verkspjald** er nú hægt að sjá yfirlit yfir samanlagðan áætlaðan kostnað, áætlað verð, reikningshæfan kostnað og reikningshæft verð fyrir hvert verk.

Upplýsingar um skráningu áætlunar samanborið við raunverulegt verð og kostnað verks má sjá í [Hvernig á að: Skrá notkun vegna verka](projects-how-record-job-usage.md).

## <a name="see-also"></a>Sjá einnig
[Verkefnastjórnun](projects-manage-projects.md)  
[Fjármál](finance.md)  
[Innkaup](purchasing-manage-purchasing.md)         
[Sala](sales-manage-sales.md)      
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

