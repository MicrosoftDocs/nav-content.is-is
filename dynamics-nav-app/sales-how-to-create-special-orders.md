---
title: "Hvernig á að stofna sérpantanir"
description: "Hægt er að stofna sérpöntun um að vara sem ekki er tiltæk sé send tilteknum viðskiptamanni. Birgir sendir vöruna í vöruhús og þá má senda hana áfram til viðskiptamanns, annaðhvort sérstaklega eða með annarri pöntun."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6460c643a07f92e478aafb84044c90ff3ed3a236
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-special-orders"></a><span data-ttu-id="36610-104">Hvernig á að stofna sérpöntun</span><span class="sxs-lookup"><span data-stu-id="36610-104">How to: Create Special Orders</span></span>
<span data-ttu-id="36610-105">Hægt er að stofna sérpöntun um að vara sem ekki er tiltæk sé send tilteknum viðskiptamanni.</span><span class="sxs-lookup"><span data-stu-id="36610-105">You can create a special order for a specific nonstock item to be shipped to a specific customer.</span></span> <span data-ttu-id="36610-106">Birgir sendir vöruna í vöruhús og þá má senda hana áfram til viðskiptamanns, annaðhvort sérstaklega eða með annarri pöntun.</span><span class="sxs-lookup"><span data-stu-id="36610-106">Your vendor ships the item to your warehouse and you can then ship the item on to your customer either independently or together with other items on another order.</span></span>  

<span data-ttu-id="36610-107">Sérpantanir gefa til kynna að innkaupa- og sölupöntun séu tengdar til að tryggja að sértæk vara utan birgða sé tínd og afhent viðskiptamanni.</span><span class="sxs-lookup"><span data-stu-id="36610-107">Special orders imply that the purchase and sales order are linked to ensure that the specific nonstock item is picked and delivered to the customer.</span></span>  

<span data-ttu-id="36610-108">Þessa aðgerð er ekki hægt að nota nema búið sé að setja upp spjald fyrir viðskiptamann, lánardrottin og vöru svo hægt sé að vinna pöntunina.</span><span class="sxs-lookup"><span data-stu-id="36610-108">Before you can use this feature, you must first set up the customer, vendor, and item cards necessary for the order.</span></span>  

## <a name="to-create-a-special-order"></a><span data-ttu-id="36610-109">Stofnuð sérpöntun:</span><span class="sxs-lookup"><span data-stu-id="36610-109">To create a special order</span></span>  
1.  <span data-ttu-id="36610-110">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Sölupöntun** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="36610-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Order**, and then choose the related link.</span></span>  
2. <span data-ttu-id="36610-111">Valið er **Nýtt** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="36610-111">Choose the **New** action.</span></span> <span data-ttu-id="36610-112">Búin er til ný  sölupöntun fyrir vöruna.</span><span class="sxs-lookup"><span data-stu-id="36610-112">Create and fill in a  sales order for the item.</span></span> <span data-ttu-id="36610-113">Nánari upplýsingar eru í [Hvernig á að: selja vörur.](sales-how-sell-products.md)</span><span class="sxs-lookup"><span data-stu-id="36610-113">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
3.  <span data-ttu-id="36610-114">Á flýtiflipanum **Línur** er fyllt út í sölulínuna.</span><span class="sxs-lookup"><span data-stu-id="36610-114">On the **Lines** FastTab, fill in the sales line.</span></span> <span data-ttu-id="36610-115">Í reitnum **Innkaupakóti** veljið innkaupakóta sem er með reitinn **Sérpöntun** valinn.</span><span class="sxs-lookup"><span data-stu-id="36610-115">In the **Purchasing Code** field, select a purchasing code that has the **Special Order** field selected.</span></span>

    <span data-ttu-id="36610-116">Nú þarf að stofna innkaupapöntun út frá innkaupatillögu.</span><span class="sxs-lookup"><span data-stu-id="36610-116">You must now create a purchase order from a requisition worksheet.</span></span>  
4. <span data-ttu-id="36610-117">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **innkaupatillaga** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="36610-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Requisition Worksheet**, and then choose the related link.</span></span>  
5. <span data-ttu-id="36610-118">Veljið aðgerðina **Sérpöntun** og veljið síðan aðgerðina **sækja sölupöntun**.</span><span class="sxs-lookup"><span data-stu-id="36610-118">Choose the **Special Order** action, and then choose the **Get Sales Orders** action.</span></span>  
6.  <span data-ttu-id="36610-119">Í glugganum **Sækja sölupantanir** sýna niðurstöður þar sem **Númer fylgiskjals** er sölupöntunarnúmeri.</span><span class="sxs-lookup"><span data-stu-id="36610-119">In the **Get Sales Orders** window, show results where the **Document No.** is the sales order number.</span></span> <span data-ttu-id="36610-120">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="36610-120">Choose the **OK** button.</span></span> <span data-ttu-id="36610-121">Kerfið stofnar innkaupatillögulínu vegna vörunnar.</span><span class="sxs-lookup"><span data-stu-id="36610-121">A requisition worksheet line is created for the item.</span></span>  
7.  <span data-ttu-id="36610-122">Í innkaupatillögulínunni skal velja **Nýtt** í reitnum **Aðgerðarboð**.</span><span class="sxs-lookup"><span data-stu-id="36610-122">On the requisition worksheet line, in the **Action Message** field, select **New**.</span></span>  
8.  <span data-ttu-id="36610-123">Í glugganum **Innkaupatillaga** veljið aðgerðina **Framkvæma aðgerðaboð**.</span><span class="sxs-lookup"><span data-stu-id="36610-123">In the **Req. Worksheet** window, choose the **Carry Out Action Message** action.</span></span> <span data-ttu-id="36610-124">Glugginn **Framkvæma aðgerðaboð - Tillaga** opnast.</span><span class="sxs-lookup"><span data-stu-id="36610-124">The **Carry Out Action Msg. - Req.** window opens.</span></span> <span data-ttu-id="36610-125">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="36610-125">Choose the **OK** button.</span></span>  

    <span data-ttu-id="36610-126">Þá birtast boð þess efnis að innkaupapantanir hafi verið stofnaðar.</span><span class="sxs-lookup"><span data-stu-id="36610-126">A message appears telling you that the purchase orders have been created.</span></span> <span data-ttu-id="36610-127">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="36610-127">Choost the **OK** button.</span></span>  

<span data-ttu-id="36610-128">Tekið er tillit til stofnaðrar innkaupapöntunar fyrir sérpöntun af kerfinu þar sem hún jafnar framboð og eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="36610-128">A purchase order created as a special order for a sales order is respected by the planning system as it balances demand and supply.</span></span> <span data-ttu-id="36610-129">Það er, innkaupapöntun (framboð) helst tengd við sölupöntun (eftirspurn) jafnvel þó innkaupapöntunin gæti lagt til fyrri eftirspurnar.</span><span class="sxs-lookup"><span data-stu-id="36610-129">That is, the purchase order (supply) remains linked to the sales order (demand), even if that purchase order could supply another earlier demand.</span></span> <span data-ttu-id="36610-130">Nánari upplýsingar eru í [Upplýsingar um hönnun: Endurpöntunarstefnur](design-details-reservation-order-tracking-and-action-messaging.md).</span><span class="sxs-lookup"><span data-stu-id="36610-130">For more information, see [Design Details: Reordering Policies](design-details-reservation-order-tracking-and-action-messaging.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="36610-131">Ekki er hægt að nota sérpöntunarkostinn ef varan er þegar frátekin.</span><span class="sxs-lookup"><span data-stu-id="36610-131">You cannot use the special order functionality if the item is already reserved.</span></span> <span data-ttu-id="36610-132">Þess vegna, fyrir vörur sem eru seldar með sérpöntunum, gakktu úr skugga um að **Frátekning** reiturinn á birgðaspjaldinu sé ekki stilltur á **Alltaf**.</span><span class="sxs-lookup"><span data-stu-id="36610-132">Therefore, for items that are sold on special orders, make sure the **Reserve** field on the item card is not set to **Always**.</span></span>  

## <a name="see-also"></a><span data-ttu-id="36610-133">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="36610-133">See Also</span></span>  
[<span data-ttu-id="36610-134">Hvernig á að: Vinna með Utanbirgðavörur</span><span class="sxs-lookup"><span data-stu-id="36610-134">How to: Work with Nonstock Items</span></span>](inventory-how-work-nonstock-items.md)  
[<span data-ttu-id="36610-135">Sala</span><span class="sxs-lookup"><span data-stu-id="36610-135">Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="36610-136">[Hvernig á að: Gera beinar afhendingar](sales-how-drop-shipment.md) </span><span class="sxs-lookup"><span data-stu-id="36610-136">[How to: Make Drop Shipments](sales-how-drop-shipment.md) </span></span>  
[<span data-ttu-id="36610-137">Hönnunarupplýsingar: Endurpöntunarstefnur</span><span class="sxs-lookup"><span data-stu-id="36610-137">Design Details: Reordering Policies</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
<span data-ttu-id="36610-138">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="36610-138">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
