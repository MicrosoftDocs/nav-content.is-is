---
title: "Hvernig á að birgðaskrá íhluti samkvæmt frálagi aðgerða"
description: "Fyrir vörur sem hafa verið settar upp með afturvirkri birgðaskráningu er sjálfgefin virkni að reikna út og bóka notkun íhluta þegar stöðu útgefinnar framleiðslupöntunar er breytt í **Lokið**. Frekari upplýsingar eru í Birgðaskráningaraðferð."
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
ms.openlocfilehash: 48645ff5d943b2f7093224289ff3cad6cfa6537e
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-flush-components-according-to-operation-output"></a>Hvernig á að birgðaskrá íhluti samkvæmt frálagi aðgerða
Fyrir vörur sem hafa verið settar upp með afturvirkri birgðaskráningu er sjálfgefin virkni að reikna út og bóka notkun íhluta þegar stöðu útgefinnar framleiðslupöntunar er breytt í **Lokið**.  

Ef leiðartengilskótar eru einnig skilgreindir verður reiknað og bókað eftir hverja aðgerð og magnið sem var raunverulega notað í aðgerðinni bókað. Frekari upplýsingar, sjá [Hvernig skal: Stofna leiðir](production-how-to-create-routings.md).  

Til dæmis ef framleiðslupöntun um að framleiða 800 metra krefst 8 kg af íhlut, og ef 200 metrar eru bókaðir sem frálag, bókast 2 kg sjálfkrafa sem notkun.  

Þessi aðgerð er gagnleg af eftirfarandi ástæðum:  

-   **Birgðir - Verðmæti** - Virðisfærslur fyrir frálag og notkun eru stofnaðar samhliða framleiðslupöntun í vinnslu. Án leiðartengilskóða munu birgðagildi hækka þar sem afköst eru bókuð og svo minnka síðar meir þegar gildi íhlutanotkunar er bókuð ásamt lokinni framleiðslupöntun.  
-   **Birgðir til ráðstöfunar** - með stöðugri notkunarbókun er betur uppfært hvort íhlutir eru til ráðstöfunar, sem er mikilvægt til að viðhalda innra jafnvægi á milli eftirspurnar og framboðs. Án leiðartengilskóta kunna aðrar eftirspurnir eftir íhlutnum að líta svo á að hann sé laus, svo framarlega sem hann bíður seinkaðrar notkunarbókunar.  
-   **Tímanleg** – þegar hægt er að sérstilla afurðir eftir beiðni viðskiptamanna er hægt að draga úr rýrnun með því að tryggja að breytingar á verkum og kerfisbreytingar eigi sér aðeins stað þegar þess þarf.  

Eftirfarandi ferli sýnir hvernig eigi að sameina afturvirka birgðaskráningu og kóta leiðartengils þannig að magnið sem er skráð fyrir hverja aðgerð sé í samræmi við raunverulegan frálag lokinna aðgerða.  

## <a name="to-flush-components-according-to-operation-output"></a>Til að birgðaskrá íhluti samkvæmt frálagi aðgerðar  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.  
2.  Veldu aðgerðina **Breyta**.  
3.  Á flýtiflipanum **Áfylling**, í reitnum **Birgðaskráningaraðferð**, skal velja **Framsenda**.  

    > [!NOTE]  
    >  Veljið **Tínsla + Áfram** ef íhluturinn er notaður í birgðageymslu sem er sett upp fyrir beinan frágang og tínslu.  

4.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **leiðir** og velja svo viðeigandi tengil.  
5.  Skilgreina leiðartengilskóða fyrir hverja aðgerð sem notar íhlutinn. Frekari upplýsingar, sjá [Hvernig skal: Stofna leiðir](production-how-to-create-routings.md).  
6.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Framleiðsluuppskrift** og velja svo viðeigandi tengil.  
7.  Skilgreina leiðartengilskóta úr hverju íhlutstilviki við aðgerðina þar sem hann er notaður.

    > [!IMPORTANT]  
    >  Íhluturinn verður að hafa leiðartengil við síðustu aðgerð leiðarinnar.  

## <a name="see-also"></a>Sjá einnig  
[Hvernig á að stofna nýjar framl.uppskriftir](production-how-to-create-production-boms.md)  
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Framleiðsla](production-manage-manufacturing.md)    
[Áætlun](production-planning.md)   
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

