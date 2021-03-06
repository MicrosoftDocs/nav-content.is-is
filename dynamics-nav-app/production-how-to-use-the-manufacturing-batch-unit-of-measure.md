---
title: "Hvernig á að nota mælieiningu framleiðslukeyrslu"
description: "Ef vara er sett á lager eftir einni mælieiningu en framleidd eftir annarri, verður framleiðslupöntunin að notar mælieiningu framleiðslukeyrslu til að reikna út rétt magn íhluta. Dæmi um útreikning með mælieiningu framleiðslukeyrslu er þegar framleiddur hlutur er merktur á lager í stykkjum en framleiddur í tonnum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cf0c91b076f473c12e61ce82d870a66e352c1920
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-manufacturing-batch-units-of-measure"></a>Hvernig á að: Vinna með mælieiningu framleiðslukeyrslu
Ef vara er sett á lager eftir einni mælieiningu en framleidd eftir annarri er framleiðslupöntun stofnuð sem notar mælieiningu framleiðslukeyrslu til að reikna út rétt magn íhluta meðan á keyrslunni **Endurnýjun framleiðslupöntunar** stendur. Dæmi um útreikning með mælieiningu framleiðslukeyrslu er þegar framleiddur hlutur er merktur á lager í stykkjum en framleiddur í tonnum.  

## <a name="to-create-a-production-bom-using-a-batch-unit-of-measure"></a>Til að stofna framleiðsluuppskrift með því að nota keyrslumælieininguna:  
1.  Mælieining framleiðslukeyrslu er sett upp sem mælieiningarvalkostur í glugganum **Mælieiningar vöru** á vörunni sem á að framleiða. Keyrslumælieiningin kemur ekki í staðinn fyrir Grunnmælieininguna á vörunni.  
2.  Stofnuð er framleiðsluuppskrift fyrir vöruna sem er sett upp með mælieiningu framleiðslukeyrslu. Frekari upplýsingar, sjá [Hvernig skal: Stofna framleiðsluuppskriftir](production-how-to-create-production-boms.md).  
3.  Í reitnum **Mælieiningarkóti** er mælieining framleiðslukeyrslu valin.  
4.  Fyrir hverja framleiðsluuppskriftarlínu í reitnum **Magn á** er slegið inn magnið af þessum vöruíhlut sem þarf til að stofna þessa keyrslumælieiningu.  
5.  Opna **Birgðaspjald** fyrir vöruna sem á í hlut.  

    Á flýtiflipanum **Áfyllingu**, í reitnum **Framleiðsluuppskriftarnr.**, er framleiðsluuppskriftin valin sem stofnuð var fyrir ofan.  
6.  Stofnaður er framleiðslupöntunarhaus með því að nota vöruna sem er sett upp með mælieiningu framleiðslukeyrslu. Frekari upplýsingar, sjá [Hvernig skal: Stofna framleiðslupantanir](production-how-to-create-production-orders.md).  
7.  Veldu aðgerðina **Uppfæra** og veldu síðan **Í lagi** hnappinn.  

Á flýtiflipanum **Línur** skal velja aðgerðina **Lína**, og velja svo aðgerðina **Íhlutir** til að skoða niðurstöðurnar. Kerfið reiknar út rétt magn íhluta sem þarf til að fullnægja framleiðsluuppskriftinni á grundvelli mælieiningu framleiðslukeyrslu.  

## <a name="to-calculate-a-manufacturing-batch-unit-of-measure-on-a-production-order"></a>Til að reikna út Mælieiningu framleiðslukeyrslu á Framleiðslupöntun:  
1.  Stofnaður er framleiðslupöntunarhaus með því að nota vöruna sem er sett upp með mælieiningu framleiðslukeyrslu.  
2.  Í reitnum **Vörunr.** í Framleiðslupöntunarlínunni er slegið inn sama vörunúmer og notað er í hausnum.  
3.  Í reitnum **Magn** er slegið inn sama magn og er notað í hausnum.  
4.  Í reitnum **Mælieiningarkóti** er mælieiningarkóti framleiðslukeyrslu valinn.  
5.  Velja aðgerðina **Uppfæra**.
6.  Á flýtiflipanum **Reikna** skal hreinsa gátreitinn **Línur**.  
7.  Velja hnappinn **Í lagi**.  
8.  Á flýtiflipanum **Línur** skal velja aðgerðina **Lína**, og velja svo aðgerðina **Íhlutir** til að skoða niðurstöðurnar. Rétt magn íhluta sem þarf til að fullnægja framleiðsluuppskriftinni er reiknað út á grundvelli mælieiningu framleiðslukeyrslu.  

## <a name="see-also"></a>Sjá einnig  
[Hvernig á að stofna Nýjar leiðir](production-how-to-create-routings.md)  
[Hvernig á að stofna nýjar framl.uppskriftir](production-how-to-create-production-boms.md)     
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Framleiðsla](production-manage-manufacturing.md)    
[Áætlun](production-planning.md)   
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

