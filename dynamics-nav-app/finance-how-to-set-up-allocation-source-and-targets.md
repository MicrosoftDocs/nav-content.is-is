---
title: "Hvernig á að setja upp uppruna og markhópa úthlutanna"
description: "Hver úthlutun samanstendur af úthlutunaruppruna og einu eða fleiri úthlutunarmörkum. Úthlutunaruppruninn skilgreinir hvaða kostnaði skal úthlutað. Úthlutunarmörkin ákvarða hvert kostnaði verður úthlutað."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 91adabefc3e0b4a69b24b34a084f89c17711d573
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-allocation-source-and-targets"></a>Hvernig á að setja upp uppruna og markhópa úthlutanna
Hver úthlutun samanstendur af úthlutunaruppruna og einu eða fleiri úthlutunarmörkum. Úthlutunaruppruninn skilgreinir hvaða kostnaði skal úthlutað. Úthlutunarmörkin ákvarða hvert kostnaði verður úthlutað.  

## <a name="to-set-up-cost-allocations"></a>Til að setja upp kostnaðarúthlutanir  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Kostnaðarúthlutun** og velja svo viðeigandi tengil.  
2.  Í glugganum **Kostnaðarúthlutun** skal velja reitinn **Breyta**.  
3.  Færið inn kenni fyrir úthlutunaruppsprettu í reitnum **Kenni**.  
4.  Skilgreina stig sem tölu á bilinu 1 til 99 í reitnum **Stig**. Úthlutunarbókunin mun fylgja röð stiganna.  
5.  Færa inn kostnaðartegund til að skilgreina hvaða kostnaðartegundum verður úthlutað í reitinn **Svið kostnaðartegundar**. Ef öllum kostnaði kostnaðartegundar hefur verið úthlutað er ekkert svið skilgreint.  
6.  Færa inn kostnaðarstað ásamt kostnaði sem á að úthluta í reitinn **Kostnaðarstaðarkóði**.  
7.  Færa inn kostnaðarhlut ásamt kostnaði sem á að úthluta í reitinn **Kostnaðarhlutakóði**. Reiturinn er oftast áfram auður vegna þess að kostnaðarhlutir eru sjaldnast úthlutaðir á aðra kostnaðarhluti.  
8.  Færa inn kostnaðargerð í reitinn **Kreditfært í kostnaðartegund**. Kostnaður sem er úthlutað verður kreditfærður í upprunakostnaðartegund. Kreditbókunin verður bókuð á þá kostnaðartegund sem uppgefin er hér.  
9. Á flýtiflipanum **Línur** skal skilgreina úthlutunarmörk. Í fyrstu línunni skal færa inn kostnaðartegund í reitinn **Markkostnaðartegund**. Skilgreinir hvaða kostnaðartegund úthlutunin er skuldfærð á.  
10. Í fyrstu línunni skal færa inn fyrsta úthlutunar markið í reitinn **Markkostnaðarstaður** eða reitinn **Markkostnaðarhlutur** . Þessir tveir reitir skilgreina hvaða kostnaðarstað eða kostnaðarhlut úthlutunin er skuldfærð á. Aðeins er hægt að færa inn í gildi annars hvors þessara reita, en ekki bæði.  
11. Endurtaka skal sömu skref í annarri línu til að setja upp fleiri úthlutunarmörk.  
12. Þegar búið er að setja upp úthlutunarmarkmið og -uppruna, skal velja aðgerðina **Reikna úthlutunarlykil** til að reikna samtölu hlutdeildargilda.  

> [!NOTE]  
>  Veljið gátreitinn **Útilokað** til að gera úthlutunaruppsetningu óvirka.  

## <a name="see-also"></a>Sjá einnig  
[Kostnaðarreikningur](finance-manage-cost-accounting.md)  
 [Uppsetning afmarkanir fyrir Kvik úthlutunargrunnar.](finance-setting-filters-for-dynamic-allocation-bases.md)   
 [Dæmi: Skilgreining fastrar úthlutunar á grundvelli úthlutunarhlutfalls](finance-scenario-example-defining-static-allocations-based-on-allocation-ratio.md)   
 [Dæmi: Skilgreining kvikrar úthlutunar á grundvelli seldra vara](finance-scenario-example-defining-dynamic-allocations-based-on-items-sold.md)   
 [Skilgreina og úthluta kostnaði](finance-define-and-allocate-costs.md)   
 [Orðalisti í kostnaðarbókhaldi](finance-terminology-in-cost-accounting.md)  
 [Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

