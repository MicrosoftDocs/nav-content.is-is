---
title: "Hönnunarupplýsingar - sléttun"
description: "Sléttunar leifar geta átt sér stað þegar þú metur kostnað af birgðaminnkun sem mælt er í öðru magni en samsvarandi birgðaaukning. Sléttunarleifar eru reiknaðar fyrir allar kostnaðarútreikninga þegar **Kostnaðarleiðrétting Birgðafærsla** runuvinnsla er keyrð."
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
ms.openlocfilehash: 2a5187811051ee2bd32ec44b22876f0a468225e2
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-rounding"></a><span data-ttu-id="49741-104">Hönnunarupplýsingar: sléttun</span><span class="sxs-lookup"><span data-stu-id="49741-104">Design Details: Rounding</span></span>
<span data-ttu-id="49741-105">Sléttunar leifar geta átt sér stað þegar þú metur kostnað af birgðaminnkun sem mælt er í öðru magni en samsvarandi birgðaaukning.</span><span class="sxs-lookup"><span data-stu-id="49741-105">Rounding residuals can occur when you value the cost of an inventory decrease that is measured in a different quantity than the corresponding inventory increase.</span></span> <span data-ttu-id="49741-106">Sléttunarleifar eru reiknaðar fyrir allar kostnaðarútreikninga þegar **Kostnaðarleiðrétting - Birgðafærsla** runuvinnsla er keyrð.</span><span class="sxs-lookup"><span data-stu-id="49741-106">Rounding residuals are calculated for all costing methods when you run the **Adjust Cost - Item Entries** batch job.</span></span>  

 <span data-ttu-id="49741-107">Þegar þú notar meðaltal sem aðferð kostnaðarútreiknings er sléttunarafgangurinn reiknaður út og skráður stighækkandi, færslu fyrir færslu.</span><span class="sxs-lookup"><span data-stu-id="49741-107">When you use the average costing method, the rounding residual is calculated and recorded on a cumulative, entry-by-entry basis.</span></span>  

 <span data-ttu-id="49741-108">Þegar þú notar aðferð kostnaðarútreiknings annan en Meðaltal er sléttunarafgangur reiknaður út þegar birgðaaukningunni hefur verið jafnað að fullu, það er þegar eftirstandandi magn fyrir birgðaaukningu er jafnt og núll.</span><span class="sxs-lookup"><span data-stu-id="49741-108">When you use a costing method other than Average, the rounding residual is calculated when the inventory increase has been fully applied, that is when the remaining quantity for the inventory increase is equal to zero.</span></span> <span data-ttu-id="49741-109">Sérstök færsla er því næst stofnuð fyrir sléttunarafganginn og bókunardagsetning sléttunarfærslunnar er bókunardagsetning síðustu reikningsfærðu virðisfærslu birgðaaukningarinnar.</span><span class="sxs-lookup"><span data-stu-id="49741-109">A separate entry is then created for the rounding residual, and the posting date on this rounding entry is the posting date of the last invoiced value entry of the inventory increase.</span></span>  

## <a name="example"></a><span data-ttu-id="49741-110">Dæmi</span><span class="sxs-lookup"><span data-stu-id="49741-110">Example</span></span>  
 <span data-ttu-id="49741-111">Eftirfarandi dæmi sýnir hvernig mismunandi sléttunarafgangar eru meðhöndlaðir fyrir meðaltalkostnaðaraðferð og aðrar aðferðir.</span><span class="sxs-lookup"><span data-stu-id="49741-111">The following example illustrates how different rounding residuals are handled for the average costing method and non-Average costing method, respectively.</span></span> <span data-ttu-id="49741-112">Í báðum tilvikum er **Kostnaðarleiðrétting - Birgðafærsla** runuvinnsla verið keyrð.</span><span class="sxs-lookup"><span data-stu-id="49741-112">In both cases, the **Adjust Cost - Item Entries** batch job has been run.</span></span>  

 <span data-ttu-id="49741-113">Eftirfarandi tafla sýnir birgðahöfuðbókarfærslur sem dæmin eru byggð á.</span><span class="sxs-lookup"><span data-stu-id="49741-113">The following table shows the item ledger entries that the example is based on.</span></span>  

|<span data-ttu-id="49741-114">Bókunardags.</span><span class="sxs-lookup"><span data-stu-id="49741-114">Posting Date</span></span>|<span data-ttu-id="49741-115">Magn</span><span class="sxs-lookup"><span data-stu-id="49741-115">Quantity</span></span>|<span data-ttu-id="49741-116">Færslunr.</span><span class="sxs-lookup"><span data-stu-id="49741-116">Entry No.</span></span>|  
|------------------|--------------|---------------|  
|<span data-ttu-id="49741-117">01-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-117">01-01-20</span></span>|<span data-ttu-id="49741-118">3</span><span class="sxs-lookup"><span data-stu-id="49741-118">3</span></span>|<span data-ttu-id="49741-119">1</span><span class="sxs-lookup"><span data-stu-id="49741-119">1</span></span>|  
|<span data-ttu-id="49741-120">02-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-120">02-01-20</span></span>|<span data-ttu-id="49741-121">-1</span><span class="sxs-lookup"><span data-stu-id="49741-121">-1</span></span>|<span data-ttu-id="49741-122">2</span><span class="sxs-lookup"><span data-stu-id="49741-122">2</span></span>|  
|<span data-ttu-id="49741-123">03-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-123">03-01-20</span></span>|<span data-ttu-id="49741-124">-1</span><span class="sxs-lookup"><span data-stu-id="49741-124">-1</span></span>|<span data-ttu-id="49741-125">3</span><span class="sxs-lookup"><span data-stu-id="49741-125">3</span></span>|  
|<span data-ttu-id="49741-126">04-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-126">04-01-20</span></span>|<span data-ttu-id="49741-127">-1</span><span class="sxs-lookup"><span data-stu-id="49741-127">-1</span></span>|<span data-ttu-id="49741-128">4</span><span class="sxs-lookup"><span data-stu-id="49741-128">4</span></span>|  

 <span data-ttu-id="49741-129">Fyrir vöru sem notar kostnaðarútreikninginn Meðaltal er sléttunarafgangurinn (1/300) reiknaður með fyrstu minnkun (færsla nr. 2) og er fluttur áfram í færslu nr. 3.</span><span class="sxs-lookup"><span data-stu-id="49741-129">For an item using the Average costing method, the rounding residual (1/300) is calculated with the first decrease (entry number 2) and is carried forward to entry number 3.</span></span> <span data-ttu-id="49741-130">Þannig er færsla nr. 3 með gildið - 3.34.</span><span class="sxs-lookup"><span data-stu-id="49741-130">Therefore, entry number 3 is valued at –3.34.</span></span>  

 <span data-ttu-id="49741-131">Eftirfarandi tafla sýnir afleiddar virðisfærslur.</span><span class="sxs-lookup"><span data-stu-id="49741-131">The following table shows the resulting value entries.</span></span>  

|<span data-ttu-id="49741-132">Bókunardags.</span><span class="sxs-lookup"><span data-stu-id="49741-132">Posting Date</span></span>|<span data-ttu-id="49741-133">Magn</span><span class="sxs-lookup"><span data-stu-id="49741-133">Quantity</span></span>|<span data-ttu-id="49741-134">Kostnaðarupphæð (raunverul.)</span><span class="sxs-lookup"><span data-stu-id="49741-134">Cost Amount (Actual)</span></span>|<span data-ttu-id="49741-135">Birgðafærslunr.</span><span class="sxs-lookup"><span data-stu-id="49741-135">Item Ledger Entry No.</span></span>|<span data-ttu-id="49741-136">Færslunr.</span><span class="sxs-lookup"><span data-stu-id="49741-136">Entry No.</span></span>|  
|------------------|--------------|----------------------------|---------------------------|---------------|  
|<span data-ttu-id="49741-137">01-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-137">01-01-20</span></span>|<span data-ttu-id="49741-138">3</span><span class="sxs-lookup"><span data-stu-id="49741-138">3</span></span>|<span data-ttu-id="49741-139">10</span><span class="sxs-lookup"><span data-stu-id="49741-139">10</span></span>|<span data-ttu-id="49741-140">1</span><span class="sxs-lookup"><span data-stu-id="49741-140">1</span></span>|<span data-ttu-id="49741-141">1</span><span class="sxs-lookup"><span data-stu-id="49741-141">1</span></span>|  
|<span data-ttu-id="49741-142">02-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-142">02-01-20</span></span>|<span data-ttu-id="49741-143">-1</span><span class="sxs-lookup"><span data-stu-id="49741-143">-1</span></span>|<span data-ttu-id="49741-144">-3,33</span><span class="sxs-lookup"><span data-stu-id="49741-144">-3.33</span></span>|<span data-ttu-id="49741-145">2</span><span class="sxs-lookup"><span data-stu-id="49741-145">2</span></span>|<span data-ttu-id="49741-146">2</span><span class="sxs-lookup"><span data-stu-id="49741-146">2</span></span>|  
|<span data-ttu-id="49741-147">03-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-147">03-01-20</span></span>|<span data-ttu-id="49741-148">-1</span><span class="sxs-lookup"><span data-stu-id="49741-148">-1</span></span>|<span data-ttu-id="49741-149">-3,34</span><span class="sxs-lookup"><span data-stu-id="49741-149">-3.34</span></span>|<span data-ttu-id="49741-150">3</span><span class="sxs-lookup"><span data-stu-id="49741-150">3</span></span>|<span data-ttu-id="49741-151">3</span><span class="sxs-lookup"><span data-stu-id="49741-151">3</span></span>|  
|<span data-ttu-id="49741-152">04-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-152">04-01-20</span></span>|<span data-ttu-id="49741-153">-1</span><span class="sxs-lookup"><span data-stu-id="49741-153">-1</span></span>|<span data-ttu-id="49741-154">-3,33</span><span class="sxs-lookup"><span data-stu-id="49741-154">-3.33</span></span>|<span data-ttu-id="49741-155">4</span><span class="sxs-lookup"><span data-stu-id="49741-155">4</span></span>|<span data-ttu-id="49741-156">4</span><span class="sxs-lookup"><span data-stu-id="49741-156">4</span></span>|  

 <span data-ttu-id="49741-157">Fyrir vöru sem notar kostnaðarútreikning annan en Meðaltal er sléttunarafgangurinn (0.01) reiknaður þegar eftirstandandi magn fyrir birgðaaukninguna er núll.</span><span class="sxs-lookup"><span data-stu-id="49741-157">For an item using a costing method other than Average, the rounding residual (0.01) is calculated when the remaining quantity for the inventory increase is zero.</span></span> <span data-ttu-id="49741-158">Sléttunarafgangur er með aðra færslu (númer 5).</span><span class="sxs-lookup"><span data-stu-id="49741-158">The rounding residual has a separate entry (number 5).</span></span>  

 <span data-ttu-id="49741-159">Eftirfarandi tafla sýnir afleiddar virðisfærslur.</span><span class="sxs-lookup"><span data-stu-id="49741-159">The following table shows the resulting value entries.</span></span>  

|<span data-ttu-id="49741-160">Bókunardags.</span><span class="sxs-lookup"><span data-stu-id="49741-160">Posting Date</span></span>|<span data-ttu-id="49741-161">Magn</span><span class="sxs-lookup"><span data-stu-id="49741-161">Quantity</span></span>|<span data-ttu-id="49741-162">Kostnaðarupphæð (raunverul.)</span><span class="sxs-lookup"><span data-stu-id="49741-162">Cost Amount (Actual)</span></span>|<span data-ttu-id="49741-163">Birgðafærslunr.</span><span class="sxs-lookup"><span data-stu-id="49741-163">Item Ledger Entry No.</span></span>|<span data-ttu-id="49741-164">Færslunr.</span><span class="sxs-lookup"><span data-stu-id="49741-164">Entry No.</span></span>|  
|------------------|--------------|----------------------------|---------------------------|---------------|  
|<span data-ttu-id="49741-165">01-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-165">01-01-20</span></span>|<span data-ttu-id="49741-166">3</span><span class="sxs-lookup"><span data-stu-id="49741-166">3</span></span>|<span data-ttu-id="49741-167">10</span><span class="sxs-lookup"><span data-stu-id="49741-167">10</span></span>|<span data-ttu-id="49741-168">1</span><span class="sxs-lookup"><span data-stu-id="49741-168">1</span></span>|<span data-ttu-id="49741-169">1</span><span class="sxs-lookup"><span data-stu-id="49741-169">1</span></span>|  
|<span data-ttu-id="49741-170">02-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-170">02-01-20</span></span>|<span data-ttu-id="49741-171">-1</span><span class="sxs-lookup"><span data-stu-id="49741-171">-1</span></span>|<span data-ttu-id="49741-172">-3,33</span><span class="sxs-lookup"><span data-stu-id="49741-172">-3.33</span></span>|<span data-ttu-id="49741-173">2</span><span class="sxs-lookup"><span data-stu-id="49741-173">2</span></span>|<span data-ttu-id="49741-174">2</span><span class="sxs-lookup"><span data-stu-id="49741-174">2</span></span>|  
|<span data-ttu-id="49741-175">03-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-175">03-01-20</span></span>|<span data-ttu-id="49741-176">-1</span><span class="sxs-lookup"><span data-stu-id="49741-176">-1</span></span>|<span data-ttu-id="49741-177">-3,33</span><span class="sxs-lookup"><span data-stu-id="49741-177">-3.33</span></span>|<span data-ttu-id="49741-178">3</span><span class="sxs-lookup"><span data-stu-id="49741-178">3</span></span>|<span data-ttu-id="49741-179">3</span><span class="sxs-lookup"><span data-stu-id="49741-179">3</span></span>|  
|<span data-ttu-id="49741-180">04-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-180">04-01-20</span></span>|<span data-ttu-id="49741-181">-1</span><span class="sxs-lookup"><span data-stu-id="49741-181">-1</span></span>|<span data-ttu-id="49741-182">-3,33</span><span class="sxs-lookup"><span data-stu-id="49741-182">-3.33</span></span>|<span data-ttu-id="49741-183">4</span><span class="sxs-lookup"><span data-stu-id="49741-183">4</span></span>|<span data-ttu-id="49741-184">4</span><span class="sxs-lookup"><span data-stu-id="49741-184">4</span></span>|  
|<span data-ttu-id="49741-185">01-01-20</span><span class="sxs-lookup"><span data-stu-id="49741-185">01-01-20</span></span>|<span data-ttu-id="49741-186">0</span><span class="sxs-lookup"><span data-stu-id="49741-186">0</span></span>|<span data-ttu-id="49741-187">-0,01</span><span class="sxs-lookup"><span data-stu-id="49741-187">-0.01</span></span>|<span data-ttu-id="49741-188">0</span><span class="sxs-lookup"><span data-stu-id="49741-188">1</span></span>|<span data-ttu-id="49741-189">5</span><span class="sxs-lookup"><span data-stu-id="49741-189">5</span></span>|  

## <a name="see-also"></a><span data-ttu-id="49741-190">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="49741-190">See Also</span></span>  
 <span data-ttu-id="49741-191">[Hönnunarupplýsingar: Birgðakostnaður](design-details-inventory-costing.md) </span><span class="sxs-lookup"><span data-stu-id="49741-191">[Design Details: Inventory Costing](design-details-inventory-costing.md) </span></span>  
 <span data-ttu-id="49741-192">[Hönnunarupplýsingar: Kostnaðarleiðrétting](design-details-cost-adjustment.md) </span><span class="sxs-lookup"><span data-stu-id="49741-192">[Design Details: Cost Adjustment](design-details-cost-adjustment.md) </span></span>  
 <span data-ttu-id="49741-193">[Hönnunarupplýsingar: Aðferð kostn.útreiknings](design-details-costing-methods.md) [Stjórna birgðakostnaði](finance-manage-inventory-costs.md)</span><span class="sxs-lookup"><span data-stu-id="49741-193">[Design Details: Costing Methods](design-details-costing-methods.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)</span></span>  
 [<span data-ttu-id="49741-194">Fjármál</span><span class="sxs-lookup"><span data-stu-id="49741-194">Finance</span></span>](finance.md)  
 <span data-ttu-id="49741-195">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="49741-195">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
