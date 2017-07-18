---
title: "Að skila VÍV aðferðir"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f21357897dd730d96db7abab469d5958c6fe117c
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="understanding-wip-methods"></a>Að skila VÍV aðferðir

Dynamics NAV styður eftirfarandi aðferðir við útreikning og skráningu um virði verka í vinnslu.

|VÍV-aðferð |Tegund útreiknings |Lýsing útreiknings|
|-----------|--------------------|-----------------------|
|Kostnaðarvirði|Samþykktar tekjur = Reikningshæft reikningsfært verð<br /><br /> Áætlaður heildarkostnaður = Reikningshæft heildarverð x Kostnaðarhlutfall áætlunar<br /><br /> VÍV-kostnaður = \(Prósentum lokið - Reikningsfærð %\) x Áætlaður heildarkostnaður<br /><br /> Prósentum lokið = Notkun (heildarkostnaður) / Heildarkostnaður á fjárhagsáætlun<br /> Reikningsfærð % = Reikningshæft reikningsfært verð<br /><br /> Reikningshæft heildarverð (samþykktur kostnaður) = Notkun (heildarkostnaður) VÍV|Útreikningar á kostnaðarvirði hefjast á því að reiknað er virði þess sem hefur verið innt af hendi með því að taka hluta áætlaðs heildarkostnaðar byggt á loknum prósentum. Reikningsfærður kostnaður er dreginn frá með því að taka hluta áætlaðs heildarkostnaðar byggt á reikningsfærðu prósentunni.<br /><br /> Skilyrði fyrir útreikningnum eru að reikningshæft heildarverð, heildarverð á fjárhagsáætlun og heildarkostnaður á fjárhagsáætlun sé rétt færður inn fyrir verkið í heild.|
|Sölukostnaður|Samþykktar tekjur = Reikningshæft reikningsfært verð<br /><br /> Samþykktur kostnaður = Heildarkostnaður á fjárhagsáætlun x Reikningsfærð prósenta<br /><br /> Reikningsfærð %= Reikningshæft reikningsfært verð / Reikningshæft heildarverð<br /><br /> \(Reikningsfærð % er dálkur í verkhlutalínum\)<br /><br /> VÍV - kostnaður = Notkun (heildarkostnaður) – Samþykktur kostnaður|Útreikningar á sölukostnaði hefjast á því að reiknaður er út samþykktur kostnaður. Kostnaður er samþykktur í hlutfalli byggt á heildarkostnaði á fjárhagsáætlun.<br /><br /> Skilyrði fyrir útreikningnum eru að reikningshæft heildarverð og heildarkostnaður á fjárhagsáætlun séu færð inn á réttan hátt fyrir allt verkið.|
|Söluvirði|Samþykktur kostnaður = Notkun (heildarkostnaður)<br /><br /> Samþykktar tekjur = Notkun (heildarverð) x Áætlað hlutfall reikningsfærslu<br /><br /> Endurheimt kostnaðar % = Reikningshæft heildarverð / Heildarverð á fjárhagsáætlun<br /><br /> VÍV-sala = Samþykkt sala - Reikningshæft reikningsfært verð|Útreikningar á söluvirði samþykkja tekjur í hlutfalli byggt á notkun (heildarkostnaði) og áætluðu hlutfalli kostnaðarendurheimtar.<br /><br /> Skilyrði fyrir útreikningnum eru að reikningshæft heildarverð og heildarverð á fjárhagsáætlun séu færð inn á réttan hátt fyrir allt verkið.|
|Áfangaaðferð|Samþykktur kostnaður = Notkun (heildarkostnaður)<br /><br /> Samþykktar tekjur = Reikningshæft heildarverð x Prósentum lokið<br /><br /> Prósentum lokið = Notkun (heildarkostnaður) / Heildarkostnaður á fjárhagsáætlun<br /><br /> \(Kallað „Kostnaður loka %“ í verkhlutalínum\)<br /> VÍV-sala = Samþykkt sala - Reikningshæft reikningsfært verð|Útreikningar á loknum prósentum samþykkja tekjur í hlutfalli byggt á loknum prósentum, þ.e. notkun (heildarkostnaði) á móti áætlunarkostnaði.<br /><br /> Skilyrði fyrir útreikningnum eru að reikningshæft heildarverð og heildarkostnaður á fjárhagsáætlun séu færð inn á réttan hátt fyrir allt verkið.|
|Samn. sem er lokið|WIP Upphæð = WIP Kostnaður upphæð = Notkun \(Heildarkostnaður\)<br /><br /> VÍV-söluupphæð = Reikningshæft \(Reikningsfært verð\)|Með valkostinum Samningi lokið eru tekjur og kostnaður ekki samþykkt fyrr en verkinu er lokið. Þetta getur verið æskilegt þegar mikil óvissa ríkir um áætlun kostnaðar og tekna verksins.<br /><br /> Öll notkun bókast á reikninginn Verk í vinnslu, kostnaður \(eign\) og öll reikningsfærð sala bókast á reikninginn VÍV Reikningsfærð sala \(skuld\) þar til verkinu er lokið.|

## <a name="see-also"></a>Sjá einnig
[Unnið með verkefni](projects-manage-projects.md)  
[Fjármál](finance-setup.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)         
[Stjórna sölu](sales-manage-sales.md)      
[Unnið með Dynamics NAV](ui-work-product.md)  

