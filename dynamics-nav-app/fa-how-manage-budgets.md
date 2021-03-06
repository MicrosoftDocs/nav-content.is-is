---
title: "Umsjón fjárhagsáætlana fyrir eignir"
description: "Til að hjálpa til við undirbúning fjárhagsáætlana og forspáa, eru settar upp upplýsingar um fjárfestingar, afskráningar og afskriftir eigna í framtíðinni."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: forecast
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 52b5e72d4d0a3e2c914894c58c10f44cb42d9c9d
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-budgets-for-fixed-assets"></a>Hvernig á að: Umsjón fjárhagsáætlana fyrir eignir
Hægt er að setja upp áætlaðar eignir. Til dæmis leyfir þetta þér að taka með áætluð kaup og sölu í skýrslum.  

Við gerð áætlaðs rekstrarreiknings, efnahagsreiknings og sjóðstreymis þarf upplýsingar um fjárfestingar, afskráningar og afskriftir eigna í framtíðinni. Hægt er að fá þessar upplýsingar í skýrslunni **Eignir - Áætlað virði**. Áður en skýrslan er prentuð þarf að taka saman fjárhagsáætlunina.  

## <a name="to-budget-the-acquisition-cost-of-a-fixed-asset"></a>Setja kaupverð eignar í fjárhagsáætlun
Til undirbúnings fjárhagsáætlunar verður að stofna eignaspjöld fyrir þær eignir sem ætlunin er að kaupa í framtíðinni. Eignir á fjárhagsáætlun eru settar upp eins og venjulegar eignir, en það verður að setja þær upp þannig að þær bókist ekki í fjárhag.

Þegar kaupverð er bókað er færður inn fjöldi áætlaðra eigna í reitnum **Áætlað eignanr.**. Þetta veldur því að forritið bókar stofnkostnað með gagnstæðu formerki á áætluðu eigninni. Heildarstofnkostnaður áætluðu eignarinnar er þá mismunurinn milli áætlaðs og raunverulegs stofnkostnaðar.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **eignir** og velja svo viðeigandi tengil.
2. Veldu aðgerðina **Nýtt** til að stofna nýtt eignaspjald fyrir áætluðu eignina.
3. Velja reitnum **Áætluð Eign** gátreitinn til að hindra bókun í fjárhag.
4. Hinir reitirnir eru fylltir út, úthluta afskriftabók og bóka síðan fyrsta kaupverð með áætluðu eigninni sem er færð inn í reitinn **Áætlað Eignanr.** á færslubókarlínunni. Nánari upplýsingar eru í [Hvernig á að: komast ufir eignir](fa-how-acquire.md).

## <a name="to-budget-the-disposal-of-a-fixed-asset"></a>Setja afskráningu eignar í fjárhagsáætlun
Eigi að selja eignir á áætlunartímabilinu er hægt að færa inn upplýsingar um söluverð og söludagsetningu.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **eignir** og velja svo viðeigandi tengil.
2. Valin er eignin sem á að afskrá, og velja síðan **Afskriftabækur** aðgerð.
3. Í glugganum **Eignaafskriftabækur** er fært inn í reitina **Áætluð afskráningardags.** og **Áætlaður afrakstur undir reitnum Afskráning**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-view-projected-disposal-values"></a>Skoðun á áætluðu virði afskráninga:
Keyra má skýrsluna **Eignir - Áætlað virði** til að skoða áætlað afskráningarvirði og reikna hagnað/tap.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Áætlað virði eigna** og velja svo viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum.
3. Veljið hnappinn **Prenta** eða **Forskoðun**.

## <a name="to-budget-depreciation"></a>Áætlun afskrifta:
Þú getur notað **Eignir – Áætlað virði** skýrsluna til að reikna afskrift í framtíðinni. Í skýrslunni er hægt að skoða bókfært virði og uppsafnaðar afskriftir við upphaf valins tímabils, breytingar sem á tímabilinu og bókfært virði og uppsafnaðar afskriftir i lok tímabilsins.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Áætlað virði eigna** og velja svo viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum.
3. Til að skoða heildarvirði allra eigna skal hreinsa gátreitinn **Prenta á Eign**.
4. Flýtiflipinn **Eignir** er hafður auður ef taka á allar eignir með. Ritaðu **Nei** í reitinn **Áætluð eign** til að undanskilja áætlaðar eignir eða **Já** til að skoða einungis áætlaðar eignir.
5. Veljið hnappinn **Prenta** eða **Forskoðun**.

## <a name="see-also"></a>Sjá einnig
[Eignir](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance.md)  
[Velkomin(n) í [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

