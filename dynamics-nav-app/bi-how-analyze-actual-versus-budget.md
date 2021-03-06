---
title: "Greina raunverulegar og áætlaðar upphæðir"
description: "Lýsir því hvernig greina skal raunverulegar upphæðir annars vegar og áætlaðar upphæðir hins vegar."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bi, power BI, analysis, KPI
ms.date: 06/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a39f213e7e96423efe25bb715f4a1b4bb3c0258b
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-analyze-actual-amounts-versus-budgeted-amounts"></a>Hvernig skal: Greina raunverulegar og áætlaðar upphæðir
Hluti af því að safna saman, greina og deila upplýsingum fyrirtækis, er að skoða raunverulegar upphæðir í samanburði við áætlaðar upphæðir fyrir alla reikninga og nokkur tímabil.

Til að greina áætlaðar upphæðir, verður fyrst að búa til fjárhagsáætlun. Nánari upplýsingar eru í [Hvernig á að: Búa til fjárhagsáætlanir](finance-how-create-budgets.md).

## <a name="to-view-a-budget"></a>Að skoða áætlun
Í áætlun með víddum er hægt að setja afmarkanir á færslurnar og sjá tilteknar áætlanir.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsáætlanir** og velja svo viðeigandi tengil.
2. Í glugganum **Fjárhagsáætlanir** skal velja þá áætlun sem á að skoða.  
3. Efst í glugganum skal fylla inn í reitina eins og þörf krefur, til að skilgreina hvað birtist. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   Ef valið var **Tímabil** annað hvort í reitnum **Sýna sem línur** eða **Sýna sem dálka** þarf að fylla út reitinn **Skoða eftir**. Ef ekki hefur verið valið **Tímabil**, hvorki í reitnum **Sýna sem línur** né **Sýna sem dálka**, skal slá inn viðeigandi tímabil í reitnum **Dags.afmörkun**.  

> [!NOTE]  
>   Aðeins færslur úr fjárhagsáætlun með afmörkunarkótum sem færðir eru inn á flýtiflipanum **Afmarkanir** eru teknar með í útreikninginn. Áætlunarfærslur með aðra afmörkunarkóta eða án nokkurra afmörkunarkóta teljast ekki með. Á meðan afmörkunin er stillt á gluggann sýnir áætlunin aðeins áætlunarfærslur með þessum afmörkunarkótum.  

> [!TIP]  
>   Ef þörf er á að breyta áætlun, er hægt að breyta áætlunarfærslunum. Velja upphæð til að skoða undirliggjandi fjárhagsáætlunarfærslur.

## <a name="to-view-actual-and-budgeted-amounts-for-all-accounts"></a>Að skoða raunverulegar og áætlaðar upphæðir fyrir alla reikninga  
Hægt er að skoða fjárhagsáætlanir og bera þær saman við raunverulegar upphæðir í mörgum svæðum í [!INCLUDE[d365fin](includes/d365fin_md.md)].

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókhaldslykill** og velja svo viðeigandi tengil.  
2. Í glugganum **Bókhaldslykill**, skal velja aðgerðina **Fjárhagur staða/áætlun**.
3. Efst í glugganum skal fylla inn í reitina eins og þörf krefur, til að skilgreina hvað birtist.  
4. Til að sjá tilgreininguna sem birt upphæð samanstendur af skal velja reitinn.  

> [!NOTE]  
>   Afmarkanir sem settar eru í gluggahausinn verða notaðar í fjárhagsfærslum og áætlunarfærslum.

Bókhaldslykillinn er í dálkunum til vinstri. Af dálkunum fimm lengst til hægri sýna fjórir þeir fyrstu raunverulegar og áætlaðar debet- og kreditfærslur á hverjum reikningi. Fimmti dálkurinn sýnir hlutfallsleg tengsl raunverulegra og áætlaðra upphæða á fjárhagsreikningnum.  

> [!TIP]  
>   Reiturinn **Skoða eftir** í glugganum **Fjárhagur - Staða/áætlun** er notaður til að velja lengd tímabils. Smellt er á reitinn  **Skoða sem** til að velja hvernig upphæðir eru reiknaðar (**Hreyfing** eða **Staða til dags**). Veljið aðgerðina **Fyrra tímabil** eða **Næsta tímabil** til að breyta tímabilinu.  

## <a name="to-view-actual-and-budgeted-amounts-for-several-periods"></a>Að skoða raunverulegar og áætlaðar upphæðir fyrir nokkur tímabil  
Í stað þess að skoða raunverulegar og áætlaðar upphæðir á öllum reikningum innan ákveðins tímabils er hægt að skoða fjölda tímabila á stökum reikningi.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókhaldslykill** og velja svo viðeigandi tengil.  
2. Í glugganum **Bókhaldslykill** veljið viðeigandi fjárhagsreikning, og veljið síðan aðgerðina **Fjárhagsreikningur staða/áætlun**.  
3. Efst í glugganum skal fylla inn í reitina eins og þörf krefur, til að skilgreina hvað birtist.   
4. Til að sjá tilgreiningu á birtri upphæð skal velja reitinn.  

## <a name="see-also"></a>Sjá einnig
[Viðskiptaupplýsingar](bi.md)
[Hvernig skal: Vinna með fjárhagsskemu](bi-how-work-account-schedule.md)  
[Fjármál](finance.md)  
[Uppsetning Fjármála](finance-setup-finance.md)  
[Fjárhagur og bókhaldslyklar](finance-general-ledger.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

