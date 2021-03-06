---
title: "Hönnunarupplýsingar - birgðahaldstími"
description: "Bakfærð færsla eða kostnaðarleiðréttingar hafa oft áhrif á stöðu og birgðaverðmat fyrri reikningstímabil sem teljast lokjuð. Þetta getur haft öfug áhrif á nákvæma skýrslugerð, sérstaklega hjá alþjóðlegum fyrirtækjum. Búnaður birgðahaldstíma má nota til að forðast slíka vandamál, með því að opna eða loka birgðahaldstímum til að takmarka bókanir á tilteknu tímabili."
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
ms.openlocfilehash: 1dd508ee887b28b1696746444145eff6f2bd7ebe
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-inventory-periods"></a>Hönnunarupplýsingar: birgðahaldstími
Bakfærð færsla eða kostnaðarleiðréttingar hafa oft áhrif á stöðu og birgðaverðmat fyrri reikningstímabil sem teljast lokjuð. Þetta getur haft öfug áhrif á nákvæma skýrslugerð, sérstaklega hjá alþjóðlegum fyrirtækjum. Búnaður birgðahaldstíma má nota til að forðast slíka vandamál, með því að opna eða loka birgðahaldstímum til að takmarka bókanir á tilteknu tímabili.  

 Birgðatímabil er tímabil, skilgreint með lokadagsetningu, sem birgðafærslur eru bókaðar innan. Þegar þú lokar birgðahaldstíma er ekki hægt að bóka neinar gildisbreytingar á lokaða tímabilinu. Þetta inniheldur nýjar gildisbókanir, væntanlegar eða reikningsfærðar færslur, breytingar á núverandi gildi og kostnaðarleiðréttingu. Hins vegar getur þú samt notað það á opna birgðafærslu sem lendir á lokaða tímabilinu. Nánari upplýsingar eru í [Upplýsingar um hönnun: Vörujöfnun](design-details-item-application.md).  

 Til að ganga úr skugga um að allar viðskiptifærslur í lokuðu tímabili eru endanlegar, skulu eftirfarandi skilyrði vera uppfyllt áður en birgðahaldstími getur lokað:  

- Allar birgðahöfuðbókarfærslur á útleið á tímabilinu þurfa að vera lokaðar (ekki neikvæð birgðastaða).  
- Leiðrétta þarf allan vörukostnað á tímabilinu.  
- Allar losaðar og loknar framleiðslupantanir á tímabilinu þurfa að vera kostnaðarjafnaðar.  

  Þegar þú lokar birgðahaldstíma er stofnuð birgðahaldstímafærsla með þv´að nota númer síðustu vöruskráningar sem fellur undir birgðahaldstímann. Að auki, er tími, dagsetning, og notandakóði notandans sem lokar tímabilinu eru færðar í birgðahaldstímifærslu. Með því að nota þessar upplýsingar með síðasta skráðri vöru fyrra tímabili, getur þú séð hvaða birgðafærslur voru bókaðar á birgðahaldstími. Það er líka hægt að enduropna birgðahaldstíma ef þú þarft að bóka í lokuðum tímabili. Þegar þú enduropnar birgðahaldstíma er stofnuð birgðahaldstímafærsla.  

## <a name="see-also"></a>Sjá einnig  
 [Hönnunarupplýsingar: Birgðakostnaður](design-details-inventory-costing.md) [Stjórna birgðakostnaði](finance-manage-inventory-costs.md) [Fjármál](finance.md)  
 [Unnið með Dynamics NAV](ui-work-product.md)

