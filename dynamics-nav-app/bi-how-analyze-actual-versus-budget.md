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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: da2cdce3ada29fff98ceb875414f750a8af51855
ms.contentlocale: is-is
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-analyze-actual-amounts-versus-budgeted-amounts"></a><span data-ttu-id="3873f-103">Hvernig skal: Greina raunverulegar og áætlaðar upphæðir</span><span class="sxs-lookup"><span data-stu-id="3873f-103">How to: Analyze Actual Amounts Versus Budgeted Amounts</span></span>
<span data-ttu-id="3873f-104">Hluti af því að safna saman, greina og deila upplýsingum fyrirtækis, er að skoða raunverulegar upphæðir í samanburði við áætlaðar upphæðir fyrir alla reikninga og nokkur tímabil.</span><span class="sxs-lookup"><span data-stu-id="3873f-104">As a part of gathering, analyzing, and sharing your company data, you view actual amounts compared to budgeted amounts for all accounts and for several periods.</span></span>

<span data-ttu-id="3873f-105">Til að greina áætlaðar upphæðir, verður fyrst að búa til fjárhagsáætlun.</span><span class="sxs-lookup"><span data-stu-id="3873f-105">To analyze budgeted amounts, you must first create budgets.</span></span> <span data-ttu-id="3873f-106">Nánari upplýsingar eru í [Hvernig á að: Búa til fjárhagsáætlanir](finance-how-create-budgets.md).</span><span class="sxs-lookup"><span data-stu-id="3873f-106">For more information, see [How to: Create Budgets](finance-how-create-budgets.md).</span></span>

## <a name="to-view-a-budget"></a><span data-ttu-id="3873f-107">Að skoða áætlun</span><span class="sxs-lookup"><span data-stu-id="3873f-107">To view a budget</span></span>
<span data-ttu-id="3873f-108">Í áætlun með víddum er hægt að setja afmarkanir á færslurnar og sjá tilteknar áætlanir.</span><span class="sxs-lookup"><span data-stu-id="3873f-108">In a budget with dimensions, you can filter the entries and see specific budgets.</span></span>

1. <span data-ttu-id="3873f-109">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsáætlanir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="3873f-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **G/L Budgets**, and then choose the related link.</span></span>
2. <span data-ttu-id="3873f-110">Í glugganum **Fjárhagsáætlanir** skal velja þá áætlun sem á að skoða.</span><span class="sxs-lookup"><span data-stu-id="3873f-110">In the **G/L Budgets** window, open the budget that you want to view.</span></span>  
3. <span data-ttu-id="3873f-111">Efst í glugganum skal fylla inn í reitina eins og þörf krefur, til að skilgreina hvað birtist.</span><span class="sxs-lookup"><span data-stu-id="3873f-111">At the top of the window, fill in the fields as necessary to define what is shown.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   <span data-ttu-id="3873f-112">Ef valið var **Tímabil** annað hvort í reitnum **Sýna sem línur** eða **Sýna sem dálka** þarf að fylla út reitinn **Skoða eftir**.</span><span class="sxs-lookup"><span data-stu-id="3873f-112">If you have selected **Period** in either the **Show as Lines** or the **Show as Columns** field, then you must fill in the **View by** field.</span></span> <span data-ttu-id="3873f-113">Ef ekki hefur verið valið **Tímabil**, hvorki í reitnum **Sýna sem línur** né **Sýna sem dálka**, skal slá inn viðeigandi tímabil í reitnum **Dags.afmörkun**.</span><span class="sxs-lookup"><span data-stu-id="3873f-113">If you have not selected **Period** in either the **Show as Lines** or **Show as Columns** field, then enter the appropriate period in **Date Filter** field.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="3873f-114">Aðeins færslur úr fjárhagsáætlun með afmörkunarkótum sem færðir eru inn á flýtiflipanum **Afmarkanir** eru teknar með í útreikninginn.</span><span class="sxs-lookup"><span data-stu-id="3873f-114">Only entries from the general ledger budget with the filter codes that you enter on the **Filters** FastTab are included in the calculation.</span></span> <span data-ttu-id="3873f-115">Áætlunarfærslur með aðra afmörkunarkóta eða án nokkurra afmörkunarkóta teljast ekki með.</span><span class="sxs-lookup"><span data-stu-id="3873f-115">Budget entries with other filter codes or without any filter codes are not included.</span></span> <span data-ttu-id="3873f-116">Á meðan afmörkunin er stillt á gluggann sýnir áætlunin aðeins áætlunarfærslur með þessum afmörkunarkótum.</span><span class="sxs-lookup"><span data-stu-id="3873f-116">As long as the filter remains on the window, the budget only displays the budget entries with these filter codes.</span></span>  

> [!TIP]  
>   <span data-ttu-id="3873f-117">Ef þörf er á að breyta áætlun, er hægt að breyta áætlunarfærslunum.</span><span class="sxs-lookup"><span data-stu-id="3873f-117">If you want to modify the budget, you can modify the budget entries.</span></span> <span data-ttu-id="3873f-118">Velja upphæð til að skoða undirliggjandi fjárhagsáætlunarfærslur.</span><span class="sxs-lookup"><span data-stu-id="3873f-118">Choose an amount to view the underlying general ledger budget entries.</span></span>

## <a name="to-view-actual-and-budgeted-amounts-for-all-accounts"></a><span data-ttu-id="3873f-119">Að skoða raunverulegar og áætlaðar upphæðir fyrir alla reikninga</span><span class="sxs-lookup"><span data-stu-id="3873f-119">To view actual and budgeted amounts for all accounts</span></span>  
<span data-ttu-id="3873f-120">Hægt er að skoða fjárhagsáætlanir og bera þær saman við raunverulegar upphæðir í mörgum svæðum í [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="3873f-120">You can view general ledger budgets and compare them with actual figures in several areas of [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

1. <span data-ttu-id="3873f-121">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókhaldslykill** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="3873f-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="3873f-122">Í glugganum **Bókhaldslykill**, skal velja aðgerðina **Fjárhagur staða/áætlun**.</span><span class="sxs-lookup"><span data-stu-id="3873f-122">In the **Chart of Accounts** window, choose the **G/L Balance/Budget** action.</span></span>
3. <span data-ttu-id="3873f-123">Efst í glugganum skal fylla inn í reitina eins og þörf krefur, til að skilgreina hvað birtist.</span><span class="sxs-lookup"><span data-stu-id="3873f-123">At the top of the window, fill in the fields as necessary to define what is shown.</span></span>  
4. <span data-ttu-id="3873f-124">Til að sjá tilgreininguna sem birt upphæð samanstendur af skal velja reitinn.</span><span class="sxs-lookup"><span data-stu-id="3873f-124">To see a specification that makes up the amount shown, choose the field.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="3873f-125">Afmarkanir sem settar eru í gluggahausinn verða notaðar í fjárhagsfærslum og áætlunarfærslum.</span><span class="sxs-lookup"><span data-stu-id="3873f-125">The filters you set in the window header will be applied to general ledger entries and also budget entries.</span></span>

<span data-ttu-id="3873f-126">Bókhaldslykillinn er í dálkunum til vinstri.</span><span class="sxs-lookup"><span data-stu-id="3873f-126">The leftmost columns contain the chart of accounts.</span></span> <span data-ttu-id="3873f-127">Af dálkunum fimm lengst til hægri sýna fjórir þeir fyrstu raunverulegar og áætlaðar debet- og kreditfærslur á hverjum reikningi.</span><span class="sxs-lookup"><span data-stu-id="3873f-127">Of the five columns on the rightmost side, the first four columns show actual and budgeted debit and credit amounts for each account.</span></span> <span data-ttu-id="3873f-128">Fimmti dálkurinn sýnir hlutfallsleg tengsl raunverulegra og áætlaðra upphæða á fjárhagsreikningnum.</span><span class="sxs-lookup"><span data-stu-id="3873f-128">The fifth column shows the proportional relationship between the actual and the budgeted amounts on the general ledger account.</span></span>  

> [!TIP]  
>   <span data-ttu-id="3873f-129">Reiturinn **Skoða eftir** í glugganum **Fjárhagur - Staða/áætlun** er notaður til að velja lengd tímabils.</span><span class="sxs-lookup"><span data-stu-id="3873f-129">Use the **View by** field in the **G/L Balance/Budget** window to select the period length.</span></span> <span data-ttu-id="3873f-130">Smellt er á reitinn  **Skoða sem** til að velja hvernig upphæðir eru reiknaðar (**Hreyfing** eða **Staða til dags**).</span><span class="sxs-lookup"><span data-stu-id="3873f-130">Use the **View as** field to select the way the amounts will be calculated, **Net Change** or **Balance at Date**.</span></span> <span data-ttu-id="3873f-131">Veljið aðgerðina **Fyrra tímabil** eða **Næsta tímabil** til að breyta tímabilinu.</span><span class="sxs-lookup"><span data-stu-id="3873f-131">Choose the **Previous Period** or **Next Period** action to change the period.</span></span>  

## <a name="to-view-actual-and-budgeted-amounts-for-several-periods"></a><span data-ttu-id="3873f-132">Að skoða raunverulegar og áætlaðar upphæðir fyrir nokkur tímabil</span><span class="sxs-lookup"><span data-stu-id="3873f-132">To view actual and budgeted amounts for several periods</span></span>  
<span data-ttu-id="3873f-133">Í stað þess að skoða raunverulegar og áætlaðar upphæðir á öllum reikningum innan ákveðins tímabils er hægt að skoða fjölda tímabila á stökum reikningi.</span><span class="sxs-lookup"><span data-stu-id="3873f-133">Instead of viewing the actual and budgeted amounts for all accounts within a single period, you can view a number of periods for a single account.</span></span>  

1. <span data-ttu-id="3873f-134">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókhaldslykill** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="3873f-134">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="3873f-135">Í glugganum **Bókhaldslykill** veljið viðeigandi fjárhagsreikning, og veljið síðan aðgerðina **Fjárhagsreikningur staða/áætlun**.</span><span class="sxs-lookup"><span data-stu-id="3873f-135">In the **Chart of Accounts** window, select the relevant general ledger account, and then choose the **G/L Account Balance/Budget** action.</span></span>  
3. <span data-ttu-id="3873f-136">Efst í glugganum skal fylla inn í reitina eins og þörf krefur, til að skilgreina hvað birtist.</span><span class="sxs-lookup"><span data-stu-id="3873f-136">At the top of the window, fill in the fields as necessary to define what is shown.</span></span>   
4. <span data-ttu-id="3873f-137">Til að sjá tilgreiningu á birtri upphæð skal velja reitinn.</span><span class="sxs-lookup"><span data-stu-id="3873f-137">To see a specification of an amount shown, choose the field.</span></span>  

## <a name="see-also"></a><span data-ttu-id="3873f-138">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="3873f-138">See Also</span></span>
<span data-ttu-id="3873f-139">[Viðskiptaupplýsingar](bi.md)
[Hvernig skal: Vinna með fjárhagsskemu](bi-how-work-account-schedule.md)</span><span class="sxs-lookup"><span data-stu-id="3873f-139">[Business Intelligence](bi.md)
[How to: Work with Account Schedules](bi-how-work-account-schedule.md)</span></span>  
[<span data-ttu-id="3873f-140">Fjármál</span><span class="sxs-lookup"><span data-stu-id="3873f-140">Finance</span></span>](finance.md)  
[<span data-ttu-id="3873f-141">Uppsetning Fjármála</span><span class="sxs-lookup"><span data-stu-id="3873f-141">Setting Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="3873f-142">Fjárhagur og bókhaldslyklar</span><span class="sxs-lookup"><span data-stu-id="3873f-142">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
<span data-ttu-id="3873f-143">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="3873f-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

