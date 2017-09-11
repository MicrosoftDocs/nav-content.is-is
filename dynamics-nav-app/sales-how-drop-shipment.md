---
title: "Hvernig á að: Gera beinar afhendingar"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: a726c8c24d8f843b33b4df4d85ad2b5eab3790e7
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="a896e-102">Hvernig á að: Gera beinar afhendingar</span><span class="sxs-lookup"><span data-stu-id="a896e-102">How to: Make Drop Shipments</span></span>
<span data-ttu-id="a896e-103">Bein afhending er afhending frá einum af lánardrottnum fyrirtækisins beint til einhvers af viðskiptamönnum fyrirtækisins.</span><span class="sxs-lookup"><span data-stu-id="a896e-103">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="a896e-104">Þegar sölupöntun er merkt fyrir bein sending og þú býrð til innkaupapöntun sem tilgreinir viðskiptamaður í reitnum **Selt-til-Viðskm.nr.**</span><span class="sxs-lookup"><span data-stu-id="a896e-104">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="a896e-105"> þá má tengja skjölin tvö og þannig segja lánardrottninum að senda beint til viðskiptamanns.</span><span class="sxs-lookup"><span data-stu-id="a896e-105">field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="a896e-106">Sölupöntun fyrir beina afhendingu búin til</span><span class="sxs-lookup"><span data-stu-id="a896e-106">To create a sales order for drop shipment</span></span>
<span data-ttu-id="a896e-107">Til að Undirbúa bein afhending, er stofnuð sölupöntun fyrir vöru sem venjulega, nema þarf tilgreina í sölulínunni að salan krefst beinnar sendingar.</span><span class="sxs-lookup"><span data-stu-id="a896e-107">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="a896e-108">Stofnið sölupöntun fyrir vöru.</span><span class="sxs-lookup"><span data-stu-id="a896e-108">Create a sales order for an item.</span></span> <span data-ttu-id="a896e-109">Nánari upplýsingar eru í [Hvernig á að: selja vörur.](sales-how-sell-products.md)</span><span class="sxs-lookup"><span data-stu-id="a896e-109">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="a896e-110">Á sölupöntunarlínu fyrir vöru í beinni sendingu, er valinn **Bein sending** gátreitinn.</span><span class="sxs-lookup"><span data-stu-id="a896e-110">On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="a896e-111">Innkaupapöntunin stofnuð fyrir beina sendingu</span><span class="sxs-lookup"><span data-stu-id="a896e-111">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="a896e-112">Til að undirbúa beina sendingu fyrir vöru sem á að selja, stofnarðu innkaupapöntun sem venjulega, nema taka þarf fram í innkaupapöntun að senda verði til viðskiptamannsins, ekki til þíns sjálfs.</span><span class="sxs-lookup"><span data-stu-id="a896e-112">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="a896e-113">Stofna innkaupapöntun.</span><span class="sxs-lookup"><span data-stu-id="a896e-113">Create a purchase order.</span></span> <span data-ttu-id="a896e-114">Ekki fylla inn í neina reiti á línunum.</span><span class="sxs-lookup"><span data-stu-id="a896e-114">Do not fill any fields on the lines.</span></span> <span data-ttu-id="a896e-115">Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="a896e-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="a896e-116">Í reitnum **Selt til Viðskm.nr.**.</span><span class="sxs-lookup"><span data-stu-id="a896e-116">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="a896e-117">er valinn viðskiptamaður sem selt er til.</span><span class="sxs-lookup"><span data-stu-id="a896e-117">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="a896e-118">Veljið aðgerðina **beinar sendingar** og veljið síðan aðgerðina **sækja sölupöntun**.</span><span class="sxs-lookup"><span data-stu-id="a896e-118">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="a896e-119">Í **Sölulisti** glugganum er valin sölupöntun sem var útbúin í "stofna sölupöntun fyrir beina sendingu" hlutanum.</span><span class="sxs-lookup"><span data-stu-id="a896e-119">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="a896e-120">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="a896e-120">Choose the **OK** button.</span></span>

<span data-ttu-id="a896e-121">Línuupplýsingar úr sölupöntun er sett í sölupöntunarlínu(r).</span><span class="sxs-lookup"><span data-stu-id="a896e-121">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="a896e-122">Nú er hægt að segja lánardrottninum aðsenda vörur til viðskiptamanns, til dæmis, með því að póstleggja innkaupapöntun sem er PDF.</span><span class="sxs-lookup"><span data-stu-id="a896e-122">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="a896e-123">Til að skoða tengda innkaupapöntunina úr sölupöntuninni</span><span class="sxs-lookup"><span data-stu-id="a896e-123">To view the linked purchase order from the sales order</span></span>
1. <span data-ttu-id="a896e-124">Veldu Sölupöntunarlínu beinnar sendingar, veldu **Pöntun** aðgerð og veldu **Bein sending** aðgerð og síðan er valið aðgerðin **Innkaupapöntun**.</span><span class="sxs-lookup"><span data-stu-id="a896e-124">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

<span data-ttu-id="a896e-125">Tengd innkaupapöntun opnast.</span><span class="sxs-lookup"><span data-stu-id="a896e-125">The linked purchase order opens.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="a896e-126">Til að bóka beina afhendingu</span><span class="sxs-lookup"><span data-stu-id="a896e-126">To post a drop shipment</span></span>
<span data-ttu-id="a896e-127">Þegar lánardrottinn hefur sent vörur, er hægt að bóka sölupöntunina sem senda.</span><span class="sxs-lookup"><span data-stu-id="a896e-127">When the vendor has shipped the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="a896e-128">Einnig er hægt að bóka innkaupapöntun, en aðeins með **Móttöku** valkostinn fyrr en sölupöntunin hefur verið reikningsfært.</span><span class="sxs-lookup"><span data-stu-id="a896e-128">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>
1. <span data-ttu-id="a896e-129">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sölupantanir**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="a896e-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="a896e-130">Opnaðu sölupöntun sem þú stofnaðir í "stofna sölupöntun fyrir beina sendingu" hlutanum.</span><span class="sxs-lookup"><span data-stu-id="a896e-130">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="a896e-131">Í reitnum **magn til Afhendingar** er tilgreint hve mikið af pöntunarmagni skal senda, allt eða hluti pöntunarmagns.</span><span class="sxs-lookup"><span data-stu-id="a896e-131">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
3. <span data-ttu-id="a896e-132">Veljið aðgerðina **bóka** eða **Bóka og senda**.</span><span class="sxs-lookup"><span data-stu-id="a896e-132">Choose the **Post** or **Post and Send** action.</span></span>
4. <span data-ttu-id="a896e-133">Síðan er annað hvort valið **senda** valkosturinn til að reikningsfæra síðar eða valkostinn **senda og reikningsfæra** eigi að reikningsfæra strax.</span><span class="sxs-lookup"><span data-stu-id="a896e-133">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="a896e-134">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="a896e-134">See Also</span></span>
<span data-ttu-id="a896e-135">[Hvernig á að: Selja vörur](sales-how-sell-products.md)  </span><span class="sxs-lookup"><span data-stu-id="a896e-135">[How to: Sell Products](sales-how-sell-products.md)  </span></span>  
[<span data-ttu-id="a896e-136">Hvernig á að skrá kaup</span><span class="sxs-lookup"><span data-stu-id="a896e-136">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="a896e-137">Stjórna sölu</span><span class="sxs-lookup"><span data-stu-id="a896e-137">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="a896e-138">[Stjórna birgðum](inventory-manage-inventory.md)    </span><span class="sxs-lookup"><span data-stu-id="a896e-138">[Manage Inventory](inventory-manage-inventory.md)    </span></span>  
[<span data-ttu-id="a896e-139">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="a896e-139">Work with Dynamics NAV</span></span>](ui-work-product.md)

