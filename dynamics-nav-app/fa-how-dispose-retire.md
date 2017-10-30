---
title: "Afskráning eða innköllun eignar"
description: "Nauðsynlegt er að bóka afskráningarvirði þegar þú rýrir, selur eða innkallar eignir."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: scrap
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f6e90150a2fd14be13746dcbc91a6fca82d39738
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-dispose-of-or-retire-fixed-assets"></a><span data-ttu-id="9420b-103">Hvernig á að: afskrá eða innkalla eignir</span><span class="sxs-lookup"><span data-stu-id="9420b-103">How to: Dispose of or Retire Fixed Assets</span></span>
<span data-ttu-id="9420b-104">Þegar eign er seld eða afskráð með öðrum hætti verður að bóka afskráningarverðmæti hennar til að reikna út og skrá hagnað eða tap.</span><span class="sxs-lookup"><span data-stu-id="9420b-104">When you sell or otherwise dispose of a fixed asset, the disposal value must be posted to calculate and record the gain or loss.</span></span> <span data-ttu-id="9420b-105">Afskráningarfærsla verður að vera síðasta færslan sem bókuð er vegna eignar.</span><span class="sxs-lookup"><span data-stu-id="9420b-105">A disposal entry must be the last entry posted for a fixed asset.</span></span> <span data-ttu-id="9420b-106">Vegna eigna sem eru að hluta afskráðar er hægt að bóka eina eða fleiri afskráningarfærslur.</span><span class="sxs-lookup"><span data-stu-id="9420b-106">For partially disposed fixed assets, you can post more than one disposal entry.</span></span> <span data-ttu-id="9420b-107">Samtala allra bókaðra afskráningarupphæða verður að vera kreditupphæð.</span><span class="sxs-lookup"><span data-stu-id="9420b-107">The total of all posted disposal amounts must be a credit amount.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="9420b-108">Ef ný eign kemur í stað annarrar verður að skrá bæði söluna á gömlu eigninni (afskráning) og innkaupin á þeirri nýju (kaup).</span><span class="sxs-lookup"><span data-stu-id="9420b-108">If you trade-in a fixed asset for another one, you must record both the sale of the old asset (disposal) and the purchase of the new one (acquisition).</span></span> <span data-ttu-id="9420b-109">Nánari upplýsingar eru í [Hvernig á að: komast ufir eignir](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="9420b-109">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>  

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a><span data-ttu-id="9420b-110">Bóka afskráningu úr fjárhagsbók eigna</span><span class="sxs-lookup"><span data-stu-id="9420b-110">To post a disposal from the fixed asset G/L journal</span></span>
1. <span data-ttu-id="9420b-111">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsbók eigna** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="9420b-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9420b-112">Stofnaður er upprunaleg Færslubókarlína og reitirnir fylltir út eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="9420b-112">Create an initial journal line and fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. <span data-ttu-id="9420b-113">Í reitnum **Eignabókunartegund** er valinn **afskráning**.</span><span class="sxs-lookup"><span data-stu-id="9420b-113">In the **FA Posting Type** field, select **Disposal**.</span></span>  
4. <span data-ttu-id="9420b-114">Valið er **Setja inn mótreikn. eigna** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="9420b-114">Choose the **Insert FA Bal. Account** action.</span></span> <span data-ttu-id="9420b-115">Seinni færslubókarlína er búin til fyrir mótreiknings sem er sett upp fyrir bókun afskráningar.</span><span class="sxs-lookup"><span data-stu-id="9420b-115">A second journal line is created for the balancing account that is set up for disposal posting.</span></span>  

    > [!NOTE]  
>   <span data-ttu-id="9420b-116">Skref 4 virkar eingöngu ef búið er að setja upp eftirfarandi: Í **Eignabókunarflokksspjald** glugganum fyrir bókunarflokkur eigna, inniheldur reiturinn **afskráningarreikningur** debetreikning fjárhags og reiturinn **Mótreikningur afskráningar** inniheldur fjárhagsreikninginn sem á að bóka mótfærslur í fyrir styrkingu.</span><span class="sxs-lookup"><span data-stu-id="9420b-116">Step 4 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Disposal Account** field contains the general ledger debit account and the **Disposal Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation.</span></span> <span data-ttu-id="9420b-117">Nánari upplýsingar eru í "setja upp bókunarflokka eigna" hlutanum í [Hvernig: Setja Upp almennar upplýsingar um eignir](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="9420b-117">For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).</span></span>  
5. <span data-ttu-id="9420b-118">Valið er **bóka** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="9420b-118">Choose the **Post** action.</span></span>  

    <span data-ttu-id="9420b-119">Ef hluti eignar er seldur eða afskráður verður að skipta eigninni upp í hluta áður en hægt er að afskrá.</span><span class="sxs-lookup"><span data-stu-id="9420b-119">If you sell or dispose of part of a fixed asset, you must split up the asset before you can record the disposal transaction.</span></span> <span data-ttu-id="9420b-120">Nánari upplýsingar eru í [Hvernig á að: skipta upp, eða sameina eignir](fa-how-trans-split-combine.md).</span><span class="sxs-lookup"><span data-stu-id="9420b-120">For more information, see [How to: Transfer, Split, or Combine Fixed Assets](fa-how-trans-split-combine.md).</span></span>  

## <a name="to-view-disposal-ledger-entries"></a><span data-ttu-id="9420b-121">Skoðun afskráningarfærslna:</span><span class="sxs-lookup"><span data-stu-id="9420b-121">To view disposal ledger entries</span></span>
<span data-ttu-id="9420b-122">Þegar eign er seld eða afskráð með öðrum hætti er afskráningarverðmæti hennar bókað í fjárhags þar sem má sjá niðurstöðurnar.</span><span class="sxs-lookup"><span data-stu-id="9420b-122">When you sell or dispose of a fixed asset, the disposal value is posted to the general ledger where you can view the result.</span></span>  

1. <span data-ttu-id="9420b-123">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **eignir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="9420b-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9420b-124">Valin er eignin sem á að skoða færslur fyrir og veldu síðan aðgerðina **afskriftabækur**.</span><span class="sxs-lookup"><span data-stu-id="9420b-124">Select the fixed asset that you want to view entries for, and then choose the **Depreciation Books** action.</span></span>  
3. <span data-ttu-id="9420b-125">Valin er afskriftabók sem á að skoða færslur fyrir og veldu síðan aðgerðina **fjárhagsfærslur**.</span><span class="sxs-lookup"><span data-stu-id="9420b-125">Select the depreciation book that you want to view entries for, and then choose the **Ledger Entries** action.</span></span>  
4. <span data-ttu-id="9420b-126">Í reitnum **Eignabókunarflokkur** er valin línan þar sem stendur **Afskráning** og síðan smellt á aðgerðina **Skoða**.</span><span class="sxs-lookup"><span data-stu-id="9420b-126">Select a line with **Disposal** in the **FA Posting Category** field, and then choose the **Navigate** action.</span></span>  
5. <span data-ttu-id="9420b-127">Í glugganum **skoða** er valin línan Fjárhagsfærsla og síðan smellt á aðgerina **Sýna**.</span><span class="sxs-lookup"><span data-stu-id="9420b-127">In the **Navigate** window, select the general ledger entry line, and then choose the **Show** action.</span></span>  

<span data-ttu-id="9420b-128">Glugginn **Fjárhagsfærslur** opnastþa sem sjást færslurnar sem afskráningarfærslan hefur myndað.</span><span class="sxs-lookup"><span data-stu-id="9420b-128">The **General Ledger Entries** window opens where you can see the entries that the disposal posting resulted in.</span></span>  

## <a name="see-also"></a><span data-ttu-id="9420b-129">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="9420b-129">See Also</span></span>
[<span data-ttu-id="9420b-130">Eignir</span><span class="sxs-lookup"><span data-stu-id="9420b-130">Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="9420b-131">Uppsetning eigna</span><span class="sxs-lookup"><span data-stu-id="9420b-131">Setting Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="9420b-132">Fjármál</span><span class="sxs-lookup"><span data-stu-id="9420b-132">Finance</span></span>](finance.md)  
<span data-ttu-id="9420b-133">[Velkomin(n) í [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="9420b-133">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span></span>  
<span data-ttu-id="9420b-134">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9420b-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
