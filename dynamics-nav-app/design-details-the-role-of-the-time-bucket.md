---
title: "Hönnunarupplýsingar - Hlutverk tímaramma"
description: "Tilgangurinn með tímarammanum er að safna saman eftirspurnartilvikum innan tímagluggans til að útbúa sameiginlega birgðapöntun."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c05bb3ca1913b1f5d0abe0bfa26248d08e080ad6
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-the-role-of-the-time-bucket"></a>Hönnunarupplýsingar: Hlutverk tímaramma
Tilgangurinn með tímarammanum er að safna saman eftirspurnartilvikum innan tímagluggans til að útbúa sameiginlega birgðapöntun.  
  
 Fyrir endurpöntunarstefnur sem nota endurpöntunarmark er hægt að skilgreina tímaramma. Þetta tryggir að eftirspurn innan sama tímabils sé safnað upp áður en áhrifin á áætlaðar birgðir eru könnuð, og hvort endurpöntunarmarki hafi verið náð. Ef farið er yfir endurpöntunarmarkið er ný birgðapöntun áætluð framvirkt frá lokum tímabilsins sem skilgreint er í tímarammanum. Tímaramminn hefst á upphafsdagsetningu áætlunar.  
  
 Tímaramminn endurspeglar það handvirka ferli að kanna birgðastigið oft fremur en fyrir hverja færslu. Notandinn verður að tilgreina tíðnina (tímarammann). Til dæmis safnar notandinn saman öllum vöruþörfum frá einum lánardrottni til að leggja inn vikulega pöntun.  
  
 ![](media/nav_app_supply_planning_2_reorder_cycle.png "NAV_APP_supply_planning_2_reorder_cycle")  
  
 Tímaramminn er vanalega notaður til að forðast keðjuverkun. Til dæmis jöfn lína framboðs og eftirspurnar þar sem fyrri eftirspurn er afturkölluð eða ný búin til. Niðurstaðan ætti að vera sú að framboðspöntunin (nema sú síðasta) er enduráætluð.  
  
## <a name="see-also"></a>Sjá einnig  
 [Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reordering-policies.md)   
 [Hönnunarupplýsingar: áætlunarfæribreyta](design-details-planning-parameters.md)   
 [Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md)   
 [Hönnunarupplýsingar: framboðsáætlun](design-details-supply-planning.md)
