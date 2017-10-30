---
title: "Hvernig á að setja upp uppruna og markhópa úthlutanna"
description: "Hver úthlutun samanstendur af úthlutunaruppruna og einu eða fleiri úthlutunarmörkum. Úthlutunaruppruninn skilgreinir hvaða kostnaði skal úthlutað. Úthlutunarmörkin ákvarða hvert kostnaði verður úthlutað."
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
ms.openlocfilehash: 91adabefc3e0b4a69b24b34a084f89c17711d573
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-allocation-source-and-targets"></a><span data-ttu-id="fc80b-105">Hvernig á að setja upp uppruna og markhópa úthlutanna</span><span class="sxs-lookup"><span data-stu-id="fc80b-105">How to: Set Up Allocation Source and Targets</span></span>
<span data-ttu-id="fc80b-106">Hver úthlutun samanstendur af úthlutunaruppruna og einu eða fleiri úthlutunarmörkum.</span><span class="sxs-lookup"><span data-stu-id="fc80b-106">Each allocation consists of an allocation source and one or more allocation targets.</span></span> <span data-ttu-id="fc80b-107">Úthlutunaruppruninn skilgreinir hvaða kostnaði skal úthlutað.</span><span class="sxs-lookup"><span data-stu-id="fc80b-107">The allocation source defines which costs will be allocated.</span></span> <span data-ttu-id="fc80b-108">Úthlutunarmörkin ákvarða hvert kostnaði verður úthlutað.</span><span class="sxs-lookup"><span data-stu-id="fc80b-108">The allocation targets determine where the costs will be allocated.</span></span>  

## <a name="to-set-up-cost-allocations"></a><span data-ttu-id="fc80b-109">Til að setja upp kostnaðarúthlutanir</span><span class="sxs-lookup"><span data-stu-id="fc80b-109">To set up cost allocations</span></span>  
1.  <span data-ttu-id="fc80b-110">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Kostnaðarúthlutun** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="fc80b-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cost Allocation**, and then chose the related link.</span></span>  
2.  <span data-ttu-id="fc80b-111">Í glugganum **Kostnaðarúthlutun** skal velja reitinn **Breyta**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-111">In the **Cost Allocation** window, choose the **Edit** action.</span></span>  
3.  <span data-ttu-id="fc80b-112">Færið inn kenni fyrir úthlutunaruppsprettu í reitnum **Kenni**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-112">Enter an ID for the allocation source in the **ID** field.</span></span>  
4.  <span data-ttu-id="fc80b-113">Skilgreina stig sem tölu á bilinu 1 til 99 í reitnum **Stig**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-113">Define a level as a number between 1 and 99 in the **Level** field.</span></span> <span data-ttu-id="fc80b-114">Úthlutunarbókunin mun fylgja röð stiganna.</span><span class="sxs-lookup"><span data-stu-id="fc80b-114">The allocation posting will follow the order of the levels.</span></span>  
5.  <span data-ttu-id="fc80b-115">Færa inn kostnaðartegund til að skilgreina hvaða kostnaðartegundum verður úthlutað í reitinn **Svið kostnaðartegundar**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-115">Enter a cost type to define which cost types will be allocated in the **Cost Type Range** field.</span></span> <span data-ttu-id="fc80b-116">Ef öllum kostnaði kostnaðartegundar hefur verið úthlutað er ekkert svið skilgreint.</span><span class="sxs-lookup"><span data-stu-id="fc80b-116">If all costs for a cost type are allocated, no range is defined.</span></span>  
6.  <span data-ttu-id="fc80b-117">Færa inn kostnaðarstað ásamt kostnaði sem á að úthluta í reitinn **Kostnaðarstaðarkóði**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-117">Enter a cost center together with costs to be allocated in the **Cost Center Code** field.</span></span>  
7.  <span data-ttu-id="fc80b-118">Færa inn kostnaðarhlut ásamt kostnaði sem á að úthluta í reitinn **Kostnaðarhlutakóði**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-118">Enter a cost object together with costs to be allocated in the **Cost Object Code** field.</span></span> <span data-ttu-id="fc80b-119">Reiturinn er oftast áfram auður vegna þess að kostnaðarhlutir eru sjaldnast úthlutaðir á aðra kostnaðarhluti.</span><span class="sxs-lookup"><span data-stu-id="fc80b-119">Most often, this field stays empty, because cost objects are rarely allocated to other cost objects.</span></span>  
8.  <span data-ttu-id="fc80b-120">Færa inn kostnaðargerð í reitinn **Kreditfært í kostnaðartegund**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-120">Enter a cost type in the **Credit to Cost Type** field.</span></span> <span data-ttu-id="fc80b-121">Kostnaður sem er úthlutað verður kreditfærður í upprunakostnaðartegund.</span><span class="sxs-lookup"><span data-stu-id="fc80b-121">The costs that are allocated will be credited to the source cost type.</span></span> <span data-ttu-id="fc80b-122">Kreditbókunin verður bókuð á þá kostnaðartegund sem uppgefin er hér.</span><span class="sxs-lookup"><span data-stu-id="fc80b-122">The credit posting will be posted to the cost type given here.</span></span>  
9. <span data-ttu-id="fc80b-123">Á flýtiflipanum **Línur** skal skilgreina úthlutunarmörk.</span><span class="sxs-lookup"><span data-stu-id="fc80b-123">On the **Lines** FastTab, define the allocation targets.</span></span> <span data-ttu-id="fc80b-124">Í fyrstu línunni skal færa inn kostnaðartegund í reitinn **Markkostnaðartegund**.</span><span class="sxs-lookup"><span data-stu-id="fc80b-124">On the first line, enter a cost type in the **Target Cost Type** field.</span></span> <span data-ttu-id="fc80b-125">Skilgreinir hvaða kostnaðartegund úthlutunin er skuldfærð á.</span><span class="sxs-lookup"><span data-stu-id="fc80b-125">It defines which cost type the allocation is debited to.</span></span>  
10. <span data-ttu-id="fc80b-126">Í fyrstu línunni skal færa inn fyrsta úthlutunar markið í reitinn **Markkostnaðarstaður** eða reitinn **Markkostnaðarhlutur** .</span><span class="sxs-lookup"><span data-stu-id="fc80b-126">On the first line, enter the first allocation target in the **Target Cost Center** field or **Target Cost Object** the field.</span></span> <span data-ttu-id="fc80b-127">Þessir tveir reitir skilgreina hvaða kostnaðarstað eða kostnaðarhlut úthlutunin er skuldfærð á.</span><span class="sxs-lookup"><span data-stu-id="fc80b-127">These two fields define which cost center or cost object the allocation is debited to.</span></span> <span data-ttu-id="fc80b-128">Aðeins er hægt að færa inn í gildi annars hvors þessara reita, en ekki bæði.</span><span class="sxs-lookup"><span data-stu-id="fc80b-128">You can only fill in one of these fields, but not both.</span></span>  
11. <span data-ttu-id="fc80b-129">Endurtaka skal sömu skref í annarri línu til að setja upp fleiri úthlutunarmörk.</span><span class="sxs-lookup"><span data-stu-id="fc80b-129">Repeat the same steps on the second line to set up additional allocation targets.</span></span>  
12. <span data-ttu-id="fc80b-130">Þegar búið er að setja upp úthlutunarmarkmið og -uppruna, skal velja aðgerðina **Reikna úthlutunarlykil** til að reikna samtölu hlutdeildargilda.</span><span class="sxs-lookup"><span data-stu-id="fc80b-130">After you have set up the allocation target and sources, choose the **Calculate Allocation Key** action to calculate the total share values.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="fc80b-131">Veljið gátreitinn **Útilokað** til að gera úthlutunaruppsetningu óvirka.</span><span class="sxs-lookup"><span data-stu-id="fc80b-131">Select the **Blocked** check box to deactivate the allocation setup.</span></span>  

## <a name="see-also"></a><span data-ttu-id="fc80b-132">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="fc80b-132">See Also</span></span>  
[<span data-ttu-id="fc80b-133">Kostnaðarreikningur</span><span class="sxs-lookup"><span data-stu-id="fc80b-133">Accounting for Costs</span></span>](finance-manage-cost-accounting.md)  
 <span data-ttu-id="fc80b-134">[Uppsetning afmarkanir fyrir Kvik úthlutunargrunnar.](finance-setting-filters-for-dynamic-allocation-bases.md) </span><span class="sxs-lookup"><span data-stu-id="fc80b-134">[Setting Filters for Dynamic Allocation Bases](finance-setting-filters-for-dynamic-allocation-bases.md) </span></span>  
 <span data-ttu-id="fc80b-135">[Dæmi: Skilgreining fastrar úthlutunar á grundvelli úthlutunarhlutfalls](finance-scenario-example-defining-static-allocations-based-on-allocation-ratio.md) </span><span class="sxs-lookup"><span data-stu-id="fc80b-135">[Scenario Example: Defining Static Allocations Based on Allocation Ratio](finance-scenario-example-defining-static-allocations-based-on-allocation-ratio.md) </span></span>  
 <span data-ttu-id="fc80b-136">[Dæmi: Skilgreining kvikrar úthlutunar á grundvelli seldra vara](finance-scenario-example-defining-dynamic-allocations-based-on-items-sold.md) </span><span class="sxs-lookup"><span data-stu-id="fc80b-136">[Scenario Example: Defining Dynamic Allocations Based on Items Sold](finance-scenario-example-defining-dynamic-allocations-based-on-items-sold.md) </span></span>  
 <span data-ttu-id="fc80b-137">[Skilgreina og úthluta kostnaði](finance-define-and-allocate-costs.md) </span><span class="sxs-lookup"><span data-stu-id="fc80b-137">[Defining and Allocating Costs](finance-define-and-allocate-costs.md) </span></span>  
 [<span data-ttu-id="fc80b-138">Orðalisti í kostnaðarbókhaldi</span><span class="sxs-lookup"><span data-stu-id="fc80b-138">Terminology in Cost Accounting</span></span>](finance-terminology-in-cost-accounting.md)  
 <span data-ttu-id="fc80b-139">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="fc80b-139">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
