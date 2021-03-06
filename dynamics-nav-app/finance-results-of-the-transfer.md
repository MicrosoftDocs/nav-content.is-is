---
title: "Niðurstöður millifærslu"
description: "Þetta efnisatriði lýsir því hvað gerist eftir að þú milkliffærir fjárhagsfærslur yfir í kostnaðarfærslur."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: general ledger, transfer, cost entries
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 05da79520b5568a8b8e63f10efce9c8b3c5395b8
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="results-of-transferring-general-ledger-entries-to-cost-entries"></a>Niðurstöður millifærslu fjárhagsfærslna yfir í kostnaðarfærslur
Meðan á millifærslu á fjárhagsfærslum í kostnaðarfærslur stendur, stofnar [!INCLUDE[d365fin](includes/d365fin_md.md)] tengingar í færslurnar í töflunni **Fjárhagsfærslur**, töflunni **Kostnaðarfærsla** og töflunni **Kostnaðarskráning** svo hægt sé að rekja tengingar milli kostnaðar- og fjárhagsfærslna.  

## <a name="general-ledger-entries"></a>Fjárhagsfærslur  
Fyrir hverja fjárhagsfærslu sem er flutt í kostnaðarbókhald, fyllir [!INCLUDE[d365fin](includes/d365fin_md.md)] út kostnaðinn í reitnum **Færslunr.**  

## <a name="cost-entries"></a>Kostnaðarfærslur  
Fyrir sérhverja kostnaðarfærslu, vistar [!INCLUDE[d365fin](includes/d365fin_md.md)] færslunúmer samsvarandi fjárhagsfærslu í reitnum **Fjárhagsfærsla númer** í töflunni **Kostnaðarfærsla**.  

Fyrir sameinaðar kostnaðarfærslur, vistar [!INCLUDE[d365fin](includes/d365fin_md.md)] færslunúmer síðustu fjárhagsfærslu, sem er færslan með hæsta færslunúmerið.  

Svæðið **Fjárhagsreikningur** í töflunni **Kostnaðarfærsla** hefur að geyma númer þess almenna fjárhagsreiknings sem kostnaðarfærslan kom frá.  

Fyrir stakar kostnaðarfærslur flytur [!INCLUDE[d365fin](includes/d365fin_md.md)] bókunartextann úr fjárhagsfærslunni í textareitinn **Lýsing**. Fyrir sameinaðar færslur, sýnir textareiturinn að þessar færslur eru fluttar sem sameinaðar færslur. Ef til dæmis um er að ræða sameinaða færslu vegna októbermánaðar 2012 gæti textinn verið **Sameinaðar færslur, október 2012**.  

## <a name="cost-register"></a>Kostnaðarskráning  
Í töflunni **Kostnaðarskráning**, [!INCLUDE[d365fin](includes/d365fin_md.md)] stofnar færslu með upprunaflutningnum frá fjárhag. Færslan skráir fyrstu og síðustu færslunúmer fjárhagsfærslna sem eru fluttar, til viðbótar við fyrstu og síðustu færslunúmer kostnaðarfærslnanna sem eru stofnaðar.  

## <a name="see-also"></a>Sjá einnig  
[Hvernig á að flytja fjárhagsfærslur í kostnaðarfærslur](finance-how-to-transfer-general-ledger-entries-to-cost-entries.md)   
[Skilyrði til að millifærslu fjárhagsfærslna í kostnaðarfærslur](finance-criteria-for-transferring-general-ledger-entries-to-cost-entries.md)   
[Sjálfvirkur flutningur og færslur sameinaðar](finance-automatic-transfer-combined-entries.md)   
[Flytja og bóka kostnaðarfærslur](finance-transfer-and-post-cost-entries.md)  

