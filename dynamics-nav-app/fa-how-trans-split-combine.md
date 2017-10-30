---
title: Endurflokka eignir
description: "Eign er endurflokkuð til að flytja hana yfir í aðra deild, skipta henni upp eða sameina hana öðrum eignum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 43b24201037de228faf4f58cc46bd92f796d72e3
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-split-or-combine-fixed-assets"></a><span data-ttu-id="e1c9f-103">Hvernig á að: flytja, skipta upp, eða sameina eignir</span><span class="sxs-lookup"><span data-stu-id="e1c9f-103">How to: Transfer, Split, or Combine Fixed Assets</span></span>
<span data-ttu-id="e1c9f-104">Þú notar eignaendurflokkunarbókina til að flytja til eignir, skipta þeim upp og sameina þær.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-104">You use the fixed asset reclassification journal to transfer, split up, and combine fixed assets.</span></span> <span data-ttu-id="e1c9f-105">Skoða eða prenta útkomu eignaendurflokkunar með skýrslunni **Bókfært Virði eignar 02** skýrslu.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-105">You view or print the results of fixed asset reclassification with the **Fixed Asset-Book Value 02** report.</span></span>

## <a name="to-transfer-a-fixed-asset-to-a-different-department"></a><span data-ttu-id="e1c9f-106">Að færa eign í aðra deild</span><span class="sxs-lookup"><span data-stu-id="e1c9f-106">To transfer a fixed asset to a different department</span></span>
<span data-ttu-id="e1c9f-107">Þú gætir þurft að flytja eignir í aðra deild þegar t.d. þú setja eign í framleiðsludeildina meðan verið er að búa hana til og flytja hana svo í stjórnunardeildina þegar lokið er við hana.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-107">You may need to transfer a fixed asset to a different department when, for example, you place an asset in the production department while it is under construction and then move it to the administration department when it is finished.</span></span>  

1. <span data-ttu-id="e1c9f-108">Uppsetning nýrrar eignar.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-108">Set up a new fixed asset.</span></span> <span data-ttu-id="e1c9f-109">Nýr deild er færður inn í reitinn **Deildarkóði**.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-109">Enter the new department in the **Department Code** field.</span></span>
2. <span data-ttu-id="e1c9f-110">Úthluta eigna-/afskriftabók á nýju eignina.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-110">Assign a fixed asset depreciation book to the new fixed asset.</span></span> <span data-ttu-id="e1c9f-111">Nánari upplýsingar eru í [Hvernig á að: komast ufir eignir](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="e1c9f-111">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>
3. <span data-ttu-id="e1c9f-112">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Endurflokkunarbækur eignar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Reclass. Journals**, and then choose the related link.</span></span>
4. <span data-ttu-id="e1c9f-113">Stofna endurflokkunarbók þar sem **Eignanr.** reiturinn inniheldur upphaflega eign og **Nýtt Eignanr.** reiturinn inniheldur nýju eignina sem á að færa.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-113">Create a reclassification journal where the **FA No.** field contains the original fixed asset, and the **New FA No.** field contains the new fixed asset to be moved.</span></span>  
5. <span data-ttu-id="e1c9f-114">Valið er **endurflokka** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-114">Choose the **Reclassify** action.</span></span>

    <span data-ttu-id="e1c9f-115">Línurnar tvær eru nú stofnaðar í eignafjárhagsbókinni með því að nota sniðmátið og keyrsluna sem tilgreind voru í glugganum **uppsetning eignabókar** fyrir tilgreinda afskriftabók.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-115">Two lines are now created in the fixed asset G/L journal using the template and batch that you have specified in the **FA Journal Setup** window for the specified depreciation book.</span></span> <span data-ttu-id="e1c9f-116">Nánari upplýsingar er að finna í [Hvernig á að setja upp afskriftir eigna](fa-how-setup-depreciation.md).</span><span class="sxs-lookup"><span data-stu-id="e1c9f-116">For more information, see [How to: Set Up Fixed Asset Depreciation](fa-how-setup-depreciation.md).</span></span>
6. <span data-ttu-id="e1c9f-117">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsbók eigna** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span></span>    
7. <span data-ttu-id="e1c9f-118">Í **fjárhagsbók eigna** glugga er valið **Bóka** aðgerð til að bóka endurflokkun sem framkvæmd var í skrefi 4 til 5.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-118">In the **Fixed Asset G/L Journal** window, choose the **Post** action to post the reclassification that you performed in steps 4 and 5.</span></span>

<span data-ttu-id="e1c9f-119">Ef bókaður hefur verið stofnkostnaður fyrir eina eign er hægt að nota eignaendurflokkunarbókina til að skipta stofnkostnaðinum á nokkrar eignir.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-119">If you have posted an acquisition cost for one asset, you can use the fixed asset reclassification journal to split the acquisition cost among several assets.</span></span>  

## <a name="to-split-a-fixed-asset-into-three-fixed-assets"></a><span data-ttu-id="e1c9f-120">Til að skipta eign í þremur eignir</span><span class="sxs-lookup"><span data-stu-id="e1c9f-120">To split a fixed asset into three fixed assets</span></span>
<span data-ttu-id="e1c9f-121">Hægt er að skipta einni eign í margar eignir, til dæmis þegar þörf er á að skipta eign á þrjú mismunandi deildum.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-121">You can split one fixed asset into multiple fixed assets, for example when you need to distribute a fixed asset onto three different departments.</span></span> <span data-ttu-id="e1c9f-122">Í því tilfelli geturðu til dæmis að flytja 25 prósent af kaupverði og afskriftum upprunalegrar eignar yfir á aðra eign og 45 prósent yfir á þriðju eignina.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-122">In that case, you can move, for example, 25 percent of the acquisition cost and depreciation for the original fixed asset to the second fixed asset and 45 percent to the third asset.</span></span> <span data-ttu-id="e1c9f-123">Prósenturnar 30 sem eftir eru verða áfram á upphaflegu eigninni.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-123">The remaining 30 percent will remain on the original fixed asset.</span></span>

1. <span data-ttu-id="e1c9f-124">Uppsetning tveggja nýrra eigna.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-124">Set up two new fixed assets.</span></span> <span data-ttu-id="e1c9f-125">Nýr deild er færður inn í reitinn **Deildarkóði**.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-125">Enter the new department in the **Department Code** field.</span></span>
2. <span data-ttu-id="e1c9f-126">Úthluta eigna-/afskriftabók á nýju eignirnar.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-126">Assign fixed asset depreciation books to the new fixed assets.</span></span> <span data-ttu-id="e1c9f-127">Nánari upplýsingar eru í [Hvernig á að: komast ufir eignir](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="e1c9f-127">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>
3. <span data-ttu-id="e1c9f-128">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Endurflokkunarbækur eignar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Reclass. Journals**, and then choose the related link.</span></span>
4. <span data-ttu-id="e1c9f-129">Búa til tvö endurflokkunarbókarlínur, ein fyrir hverja nýja eign.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-129">Create two reclassification journal lines, one for each new fixed asset.</span></span>
5. <span data-ttu-id="e1c9f-130">Í fyrstu línunni er færð inn önnur eignin í reitinn **Nýtt Eignanr.** og 25 í **Endurflokka kaupverð %** reitinn.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-130">On the first line, enter the second fixed asset in the **New FA No.** field and 25 in the **Reclassify Acq. Cost %** field.</span></span>
6. <span data-ttu-id="e1c9f-131">Í annarri línunni er færð inn þriðja eignin í reitinn **Nýtt Eignanr.** og 40 í **Endurflokka kaupverð %** reitinn.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-131">On the second line, enter the third fixed asset in the **New FA No.** field and 40 in the **Reclassify Acq. Cost %** field.</span></span>
7. <span data-ttu-id="e1c9f-132">Í báðum línum velja **Endurflokka kaupverð** og **Endurflokka Afskriftir** gátreiti.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-132">On both lines, select the **Reclassify Acquisition Cost** and **Reclassify Depreciation** check boxes.</span></span>   
8. <span data-ttu-id="e1c9f-133">Valið er **endurflokka** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-133">Choose the **Reclassify** action.</span></span>

    <span data-ttu-id="e1c9f-134">Línurnar tvær eru nú stofnaðar í eignafjárhagsbókinni með því að nota sniðmátið og keyrsluna sem tilgreind voru í glugganum **uppsetning eignabókar** fyrir tilgreinda afskriftabók.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-134">Two lines are now created in the fixed asset G/L journal using the template and batch that you have specified in the **FA Journal Setup** window for the specified depreciation book.</span></span> <span data-ttu-id="e1c9f-135">Nánari upplýsingar er að finna í [Hvernig á að setja upp afskriftir eigna](fa-how-setup-depreciation.md).</span><span class="sxs-lookup"><span data-stu-id="e1c9f-135">For more information, see [How to: Set Up Fixed Asset Depreciation](fa-how-setup-depreciation.md).</span></span>    
9. <span data-ttu-id="e1c9f-136">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsbók eigna** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span></span>
10. <span data-ttu-id="e1c9f-137">Í **fjárhagsbók eigna** glugga er valið **Bóka** aðgerð til að bóka endurflokkun sem framkvæmd var í skrefi 4 til og með 8.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-137">In the **Fixed Asset G/L Journal** window, choose the **Post** action to post the reclassification that you performed in steps 4 through 8.</span></span>

## <a name="to-combine-two-fixed-assets-into-one"></a><span data-ttu-id="e1c9f-138">Sameina tvær eignir í eina</span><span class="sxs-lookup"><span data-stu-id="e1c9f-138">To combine two fixed assets into one</span></span>
<span data-ttu-id="e1c9f-139">Hægt er að sameina margar eignir í eina eign, til dæmis þegar þú færir skiptum eignum í eina deild.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-139">You can combine multiple fixed assets into one fixed asset, for example when you move distributed fixed assets into one department.</span></span> <span data-ttu-id="e1c9f-140">Ef búið er að bóka kaupverð og afskriftir fyrir eignina sem á að færa, verða þessi gildi sameinuð í eina staka eign.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-140">If you have posted acquisition costs and depreciation for the fixed asset to be moved, those values will be combined in the single fixed asset.</span></span>

1. <span data-ttu-id="e1c9f-141">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Endurflokkunarbækur eignar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-141">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Reclass. Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="e1c9f-142">Stofna endurflokkunarbók þar sem **Eignanr.** reiturinn inniheldur eignina sem á að færa/sameina og **Nýtt Eignanr.** reiturinn inniheldur eignina sem hún verður sameinuð við.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-142">Create a reclassification journal where the **FA No.** field contains the fixed asset to be moved/combined, and the **New FA No.** field contains the fixed asset that it will be combined with.</span></span>
3. <span data-ttu-id="e1c9f-143">Láttu Reiturinn **Endurflokka kaupverðs %** auðan til að flytja/sameina allt kaupverð.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-143">Leave the **Reclassify Acq. Cost %** field empty to move/combine the entire acquisition cost.</span></span>    
4. <span data-ttu-id="e1c9f-144">Veldu **Endurflokka kaupverð** og **Endurflokka Afskriftir** gátreiti.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-144">Select the **Reclassify Acquisition Cost** and **Reclassify Depreciation** check boxes.</span></span>
5. <span data-ttu-id="e1c9f-145">Í flipanum **Aðgerðir** veljið **Endurflokka**.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-145">On the **Actions** tab, choose **Reclassify**.</span></span>

    <span data-ttu-id="e1c9f-146">Línurnar tvær eru nú stofnaðar í eignafjárhagsbókinni með því að nota sniðmátið og keyrsluna sem tilgreind voru í glugganum **uppsetning eignabókar** fyrir tilgreinda afskriftabók.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-146">Two lines are now created in the fixed asset G/L journal using the template and batch that you have specified in the **FA Journal Setup** window for the specified depreciation book.</span></span> <span data-ttu-id="e1c9f-147">Nánari upplýsingar er að finna í [Hvernig á að setja upp afskriftir eigna](fa-how-setup-depreciation.md).</span><span class="sxs-lookup"><span data-stu-id="e1c9f-147">For more information, see [How to: Set Up Fixed Asset Depreciation](fa-how-setup-depreciation.md).</span></span>   
6. <span data-ttu-id="e1c9f-148">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsbók eigna** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-148">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span></span>
7. <span data-ttu-id="e1c9f-149">Í **fjárhagsbók eigna** glugga er valið **Bóka** aðgerð til að bóka endurflokkun sem framkvæmd var í skrefi 2 til og með 5.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-149">In the **Fixed Asset G/L Journal** window, choose the **Post** action to post the reclassification that you performed in steps 2 through 5.</span></span>

## <a name="to-view-changed-depreciation-book-values-due-to-fixed-asset-reclassification"></a><span data-ttu-id="e1c9f-150">Skoða breytt bókfært afskriftarvirði vegna endurflokkunar eigna.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-150">To view changed depreciation book values due to fixed asset reclassification</span></span>
1. <span data-ttu-id="e1c9f-151">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Eignabók virði 02** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-151">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Book Value 02**, and then choose the related link.</span></span>
2. <span data-ttu-id="e1c9f-152">Fyllið inn í svæðin eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-152">Fill in the fields as necessary.</span></span>
3. <span data-ttu-id="e1c9f-153">Veljið hnappinn **Prenta** eða **Forskoðun**.</span><span class="sxs-lookup"><span data-stu-id="e1c9f-153">Choose the **Print** or **Preview** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="e1c9f-154">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="e1c9f-154">See Also</span></span>
[<span data-ttu-id="e1c9f-155">Eignir</span><span class="sxs-lookup"><span data-stu-id="e1c9f-155">Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="e1c9f-156">Uppsetning eigna</span><span class="sxs-lookup"><span data-stu-id="e1c9f-156">Setting Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="e1c9f-157">Fjármál</span><span class="sxs-lookup"><span data-stu-id="e1c9f-157">Finance</span></span>](finance.md)  
<span data-ttu-id="e1c9f-158">[Velkomin(n) í [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="e1c9f-158">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span></span>  
<span data-ttu-id="e1c9f-159">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="e1c9f-159">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
