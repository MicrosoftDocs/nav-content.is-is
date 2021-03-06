---
title: "Skilgreining fastrar úthlutunar á grundvelli úthlutunarhlutfalls"
description: "Föst úthlutunaraðferð er byggð á tilteknu gildi, s.s. fermetrum í notkun eða skilgreindu úthlutunarhlutfalli, s.s. 5:2:4."
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
ms.openlocfilehash: 5f7b627a415a39775dc49726cc655f47383abd17
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="scenario-example-defining-static-allocations-based-on-allocation-ratio"></a>Dæmi: Skilgreining fastrar úthlutunar á grundvelli úthlutunarhlutfalls
Föst úthlutunaraðferð er byggð á tilteknu gildi, s.s. fermetrum í notkun eða skilgreindu úthlutunarhlutfalli, s.s. 5:2:4.  

Í þessu efnisatriði er lýst hvernig á að skilgreina þrjá nýja kostnaðarhluti úthlutunarmarks fyrir kostnaðarstað úthlutunarupprunans FRAML með fyrirliggjandi úthlutunarhlutfallinu 5:2:4. Kostnaðarhlutirnir þrír eru ACCESSO, PAINT og FITTINGS.  

> [!NOTE]  
>  Í dæminu er notast við sýnigögnin í [!INCLUDE[d365fin](includes/d365fin_md.md)].  

## <a name="to-define-the-allocation-source-prod-cost-center-on-the-general-fasttab"></a>Til að skilgreina PROD kostnaðarstað úthlutunarveitu á flýtiflipanum Almennt  

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Kostnaðarúthlutun** og velja svo viðeigandi tengil.  
2.  Í glugganum **Kostnaðarúthlutun** skal velja aðgerðina **Nýtt**.  
3.  Í reitnum **Kenni** smellið á færslulykilinn eða sláið inn auðkenni.  
4.  Í reitinn **Stig**, sláið inn **1**.  
5.  Í reitnum **Gildir frá** og **Gildir til** eru viðeigandi dagsetningar færðar inn.  
6.  Í reitinn **Kóði kostnaðarstaðar** er slegið inn **SALA**.  
7.  Í **Kreditfært í kostnaðartegund** reitinn er slegin inn kostnaðargerðin **9903**.  

## <a name="to-define-the-allocation-target-cost-objects-on-the-lines-fasttab"></a>Til að skilgreina kostnaðarhluti úthlutunarmarks á flýtiflipanum Línur  

1.  Í fyrstu línunni í reitnum **Markkostnaðartegund** sláið inn **9903**.  
2.  Í fyrstu línunni í reitnum **Markkostnaðarhlutur** veljið **ACCESSO**.  
3.  Í fyrstu línunni í reitnum **„Gerð úthlutunarmarka** veljið **Allur kostnaður** til að tilgreina hvernig öllum uppsöfnuðum kostnaði er úthlutað.  
4.  Í fyrstu línunni í reitnum **Grunnur** veljið **Fast** til að nota fasta úthlutunaraðferð.  
5.  Í fyrstu línuna í reitnum **Deila** setjið inn úthlutunarhlutfallið **5**.  
6.  Í aðra línuna í reitnum **Markkostnaðartegund** sláið inn **9903**.  
7.  Í annarri línunni, í reitnum **Markkostnaðarhlutur** er valið **MÁLNING**.  
8.  Í annarri línunni í reitnum **„Gerð úthlutunarmarka** veljið **Allur kostnaður** til að tilgreina hvernig öllum uppsöfnuðum kostnaði er úthlutað.  
9. Í annarri línunni, í reitnum **Grunnur**, er valið **Föst** til að nota fasta úthlutunaraðferð.  
10. Í annarri línunni, í reitnum **Deila**, er sett inn úthlutunarhlutfallið **2**.  
11. Í þriðju línuna í reitnum **Markkostnaðartegund** sláið inn **9903**.  
12. Í þriðju línunni í reitnum **Markkostnaðarhlutur**, er slegið inn **TENGIHLUTIR**.  
13. Í þriðju línunni í reitnum **„Gerð úthlutunarmarka** veljið **Allur kostnaður** til að tilgreina hvernig öllum uppsöfnuðum kostnaði er úthlutað.  
14. Í þriðju línunni í reitnum **Grunnur**, er valið **Föst** til að nota fasta úthlutunaraðferð.  
15. Í þriðju línunni, í reitnum **Deila**, er sett inn úthlutunarhlutfallið **4**.  

> [!IMPORTANT]  
>  [!INCLUDE[d365fin](includes/d365fin_md.md)] reiknar sjálfkrafa reitinn **Prósenta** með því að nota prósentuhlutfall sem er háð öllum þremur úthlutunarhlutföllum sem færð eru inn í reitinn **Deila** í öllum þremur línunum.  

## <a name="see-also"></a>Sjá einnig  
[Hvernig á að setja upp uppruna og markhópa úthlutanna](finance-how-to-set-up-allocation-source-and-targets.md)   
[Skilgreina og úthluta kostnaði](finance-define-and-allocate-costs.md)   
[Dæmi: Skilgreining kvikrar úthlutunar á grundvelli seldra vara](finance-scenario-example-defining-dynamic-allocations-based-on-items-sold.md)   
[Skilgreina og úthluta kostnaði](finance-define-and-allocate-costs.md)

