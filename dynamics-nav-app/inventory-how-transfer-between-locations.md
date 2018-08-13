---
title: "Flytja vörur á milli birgðageymslna"
description: "Lýsir hvernig á að flytja birgðir frá einum stað eða vörugeymslu til annars, annaðhvort með endurflokkunarfærslubók eða með flutningsfyrirmæli."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: move, warehouse
ms.date: 06/02/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 2f7b7db12069fd9f93a616077ea2b61393c1e9a3
ms.openlocfilehash: bfa377de06a42c47e0bb76a2659de28ddb581e90
ms.contentlocale: is-is
ms.lasthandoff: 08/13/2018

---
# <a name="how-to-transfer-inventory-between-locations"></a><span data-ttu-id="76404-103">Hvernig á að: Flytja birgðir milli staða</span><span class="sxs-lookup"><span data-stu-id="76404-103">How to: Transfer Inventory Between Locations</span></span>
<span data-ttu-id="76404-104">Það er hægt að flytja birgðavörur milli tveggja staða með því að búa til flutningspantanir.</span><span class="sxs-lookup"><span data-stu-id="76404-104">You can transfer inventory items between locations by creating transfer orders.</span></span> <span data-ttu-id="76404-105">Einnig er hægt að nota vöruendurflokkunarbók.</span><span class="sxs-lookup"><span data-stu-id="76404-105">Alternatively, you can use the item reclassification journal.</span></span>

<span data-ttu-id="76404-106">Með flutningspöntun eru flutningar á útleið fluttir frá einum stað og tekið á móti flutningum á innleið á hinum staðnum.</span><span class="sxs-lookup"><span data-stu-id="76404-106">With transfer orders, you ship the outbound transfer from one location and receive the inbound transfer at the other location.</span></span> <span data-ttu-id="76404-107">Þannig er hægt að stjórna vöruhúsaaðgerðunum og meira öryggi er fyrir því að birgðamagn sé rétt uppfært.</span><span class="sxs-lookup"><span data-stu-id="76404-107">This allows you to manage the involved warehouse activities and provides more certainty that inventory quantities are updated correctly.</span></span>

<span data-ttu-id="76404-108">Með vöruendurflokkunarbók þarf einfaldlega að fylla inn í reitina **Staðsetningarkóði** og **Nýr staðsetningarkóði**.</span><span class="sxs-lookup"><span data-stu-id="76404-108">With the reclassification journal, you simply fill in the **Location Code** and the **New Location Code** fields.</span></span> <span data-ttu-id="76404-109">Þegar bókin er bókuð eru færslur birgðahöfuðbókar aðlagaðar þeirri staðsetningu sem um ræðir.</span><span class="sxs-lookup"><span data-stu-id="76404-109">When you post the journal, the item ledger entries are adjusted at the locations in question.</span></span> <span data-ttu-id="76404-110">Vöruhúsaaðgerðum er ekki stjórnað með þessari aðferð.</span><span class="sxs-lookup"><span data-stu-id="76404-110">With this method, warehouse activities are not managed.</span></span>

> [!NOTE]  
>   <span data-ttu-id="76404-111">Ef þú hefur hluti skráð í birgðum þínum án staðsetningar kóða, t.d. frá því að þú átt aðeins eitt vörugeymsla, þá getur þú ekki flutt þau vörur með því að nota flutningsfyrirmæli.</span><span class="sxs-lookup"><span data-stu-id="76404-111">If you have items recorded in your inventory without a location code, for example from a time when you only had one warehouse, then you cannot transfer those items using transfer orders.</span></span> <span data-ttu-id="76404-112">Þess í stað verður þú að nota endurflokkunarskýrsluna til að endurflokka atriði úr autt staðarnúmeri í raunverulegan staðarnúmer.</span><span class="sxs-lookup"><span data-stu-id="76404-112">Instead, you must use the reclassification journal to reclassify the items from a blank location code to an actual location code.</span></span>  <span data-ttu-id="76404-113">Nánari upplýsingar er að finna í skrefi 3 í "Til að flytja hluti með hlutanum um endurflokkunarskýrslu" hluta.</span><span class="sxs-lookup"><span data-stu-id="76404-113">For more information, see step 3 in the "To transfer items with the item reclassification journal" section.</span></span>

<span data-ttu-id="76404-114">Staðsetning og flutningsleiðir þurfa að vera uppsett til að flytja vörur.</span><span class="sxs-lookup"><span data-stu-id="76404-114">To transfer items, locations and transfer routes must be set up.</span></span> <span data-ttu-id="76404-115">Nánari upplýsingar er að finna í [Hvernig á að: Setja upp staðsetningar](inventory-how-setup-locations.md).</span><span class="sxs-lookup"><span data-stu-id="76404-115">For more information, see [How to: Set Up Locations](inventory-how-setup-locations.md).</span></span>

## <a name="to-transfer-items-with-a-transfer-order"></a><span data-ttu-id="76404-116">Vörur fluttar með flutningspöntun</span><span class="sxs-lookup"><span data-stu-id="76404-116">To transfer items with a transfer order</span></span>
1. <span data-ttu-id="76404-117">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Flutningspantanir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="76404-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Transfer orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="76404-118">Í glugganum **Flutningspöntun** skal fylla út reitina eins og þörf krefur.</span><span class="sxs-lookup"><span data-stu-id="76404-118">In the **Transfer Order** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    > [!NOTE]  
   >   <span data-ttu-id="76404-119">Ef búið er að fylla út reitina **Millifærslukóði**, **Flutningsaðilakóði** og **Flutningsþjónusta** í glugganum **Lýsing millifærsluleiðar** þegar flutningsleið var sett upp, fyllir kerfið sjálfkrafa út samsvarandi reiti á millifærslupöntuninni.</span><span class="sxs-lookup"><span data-stu-id="76404-119">If you have filled in the **In-Transit Code**, **Shipping Agent Code**, and **Shipping Agent Service** fields in the **Trans. Route Spec.** window when you set up the transfer route, then the corresponding fields on the transfer order are filled in automatically.</span></span>

    <span data-ttu-id="76404-120">Þegar fyllt er út í reitinn **Flutningsþjónusta** reiknar kerfið út móttökudagsetningu fyrir flutt-til birgðageymslu með því að bæta flutningstíma flutningsþjónustunnar við afhendingardagsetninguna.</span><span class="sxs-lookup"><span data-stu-id="76404-120">When you fill in the **Shipping Agent Service** field, the receipt date at the transfer-to location is calculated by adding the shipping time of the shipping agent service to the shipment date.</span></span>

    <span data-ttu-id="76404-121">Sem starfsmaður vörugeymslu við flutninginn frá staðsetninginni skaltu halda áfram að senda vörurnar.</span><span class="sxs-lookup"><span data-stu-id="76404-121">As a warehouse worker at the transfer-from location, proceed to ship the items.</span></span>
3. <span data-ttu-id="76404-122">Veldu aðgerðina **Bóka** veldu **Senda** valkostinn og veldu síðan **Í lagi** hnappinn.</span><span class="sxs-lookup"><span data-stu-id="76404-122">Choose the **Post** action, choose the **Ship** option, and then choose the **OK** button.</span></span>

    <span data-ttu-id="76404-123">Atriðin eru nú í flutningi milli tilgreindra staða, í samræmi við tilgreint flutningsleið.</span><span class="sxs-lookup"><span data-stu-id="76404-123">The items are now in transit between the specified locations, according to the specifies transfer route.</span></span>

    <span data-ttu-id="76404-124">Sem starfsmaður vörugeymslu við flutninginn frá staðsetninginni skaltu halda áfram að fá vörurnar.</span><span class="sxs-lookup"><span data-stu-id="76404-124">As a warehouse worker at the transfer-from location, proceed to receive the items.</span></span>
4. <span data-ttu-id="76404-125">Veldu aðgerðina **Bóka**, veldu **Móttaka** valkostinn og veldu síðan **Í lagi** hnappinn.</span><span class="sxs-lookup"><span data-stu-id="76404-125">Choose the **Post** action, choose the **Receive** option, and then choose the **OK** button.</span></span>

## <a name="to-transfer-items-with-the-item-reclassification-journal"></a><span data-ttu-id="76404-126">Til að flytja vörur með vöruendurflokkunarbók</span><span class="sxs-lookup"><span data-stu-id="76404-126">To transfer items with the item reclassification journal</span></span>
1. <span data-ttu-id="76404-127">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Birgðaendurflokkunarbækur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="76404-127">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Reclass. Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="76404-128">Í glugganum **Birgðaendurflokkunarbók** skal fylla út reitina eins og þörf krefur.</span><span class="sxs-lookup"><span data-stu-id="76404-128">In the **Item Reclass. Journal** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. <span data-ttu-id="76404-129">Í reitnum **Kóði birgðageymslu** er færð inn birgðageymslan þar sem vörurnar eru nú geymdar.</span><span class="sxs-lookup"><span data-stu-id="76404-129">In the **Location Code** field, enter the location where the items are currently stored.</span></span>

    > [!NOTE]  
   >   <span data-ttu-id="76404-130">Til að flytja hluti sem ekki hafa staðsetningarkóða skal skilja reitinn **Staðsetningarkóða** eftir auðan.</span><span class="sxs-lookup"><span data-stu-id="76404-130">To transfer items that have no location code, leave the **Location Code** field blank.</span></span>
4. <span data-ttu-id="76404-131">Í reitnum **Nýr staðsetningarkóði**, sláðu inn staðinn sem þú vilt flytja hlutina í.</span><span class="sxs-lookup"><span data-stu-id="76404-131">In the **New Location Code** field, enter the location that you want to transfer the items to.</span></span>
5. <span data-ttu-id="76404-132">Valið er **Bóka** aðgerðin.</span><span class="sxs-lookup"><span data-stu-id="76404-132">Choose the **Post** action.</span></span>

## <a name="see-also"></a><span data-ttu-id="76404-133">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="76404-133">See Also</span></span>
[<span data-ttu-id="76404-134">Stjórna birgðum</span><span class="sxs-lookup"><span data-stu-id="76404-134">Manage Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="76404-135">Hvernig á að: Setja upp birgðageymslur</span><span class="sxs-lookup"><span data-stu-id="76404-135">How to: Set Up Locations</span></span>](inventory-how-setup-locations.md)  

<span data-ttu-id="76404-136">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="76404-136">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
<span data-ttu-id="76404-137">[Sérstillir [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-customizing-overview.md)</span><span class="sxs-lookup"><span data-stu-id="76404-137">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-customizing-overview.md)</span></span>  
[<span data-ttu-id="76404-138">Almenn viðskiptavirkni</span><span class="sxs-lookup"><span data-stu-id="76404-138">General Business Functionality</span></span>](ui-across-business-areas.md)

# #

