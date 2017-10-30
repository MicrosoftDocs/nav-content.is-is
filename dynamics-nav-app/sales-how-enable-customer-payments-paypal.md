---
title: "Hvernig á að: Virkja greiðslur viðskiptamanna gegnum PayPal"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 15f30a03c3e7ccc865ef527a707794c2c6428b2f
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a><span data-ttu-id="be3c2-102">Hvernig á að: Virkja greiðslur viðskiptamanna gegnum PayPal#</span><span class="sxs-lookup"><span data-stu-id="be3c2-102">How to: Enable Customer Payments Through PayPal#</span></span>
<span data-ttu-id="be3c2-103">Í stað þess að innheimta greiðslur með gíró eða kreditkort getur boðið að viðskiptamenn greiði gegnum PayPal reikning þeirra .</span><span class="sxs-lookup"><span data-stu-id="be3c2-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span>

<span data-ttu-id="be3c2-104">Þegar viðskiptamaður velur PayPal tengilinn á sölureikningi eða sölupöntunarskjali, birtist þjónustusíða fyrir PayPal reikning hans þar sem nákvæmar greiðsluupplýsingar fyrir söluna koma fram.</span><span class="sxs-lookup"><span data-stu-id="be3c2-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="be3c2-105">Viðskiptamaður getur síðan greiða reikning og sem hverja aðra PayPal greiðslu.</span><span class="sxs-lookup"><span data-stu-id="be3c2-105">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="be3c2-106">Til að Virkja greiðslur viðskiptamanna gegnum PayPal verðurðu að gera eftirfarandi:</span><span class="sxs-lookup"><span data-stu-id="be3c2-106">To enable customer payments through PayPal, you must do the following:</span></span>

1. <span data-ttu-id="be3c2-107">Setja upp PayPal Payments Standard sem greiðsluþjónustu í glugganum **GreiðslÞjónusta** .</span><span class="sxs-lookup"><span data-stu-id="be3c2-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span></span>
2. <span data-ttu-id="be3c2-108">Velja PayPal Payments Standard í á **Greiðsluþjónustu** reit á viðkomandi söluskjal.</span><span class="sxs-lookup"><span data-stu-id="be3c2-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span></span>

<span data-ttu-id="be3c2-109">PayPal-greiðslustaðalþjónusta er uppsett sem viðbót við Dynamics NAV og tilbúin til virkjunar.</span><span class="sxs-lookup"><span data-stu-id="be3c2-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span></span> <span data-ttu-id="be3c2-110">Frekari upplýsingar skoða [Sérstilla Dynamics NAV Nota viðbætur](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="be3c2-110">For more information, see [Customizing Dynamics NAV Using Extensions ](ui-extensions.md).</span></span>

## <a name="to-enable-the-paypal-payments-standard-service"></a><span data-ttu-id="be3c2-111">Virkja PayPal Payments Standard þjónustuna</span><span class="sxs-lookup"><span data-stu-id="be3c2-111">To enable the PayPal Payments Standard service</span></span>
1. <span data-ttu-id="be3c2-112">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, **greiðsluþjónusta**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="be3c2-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="be3c2-113">Í glugganum **Greiðsluþjónustur** skal velja aðgerðina **Nýtt**.</span><span class="sxs-lookup"><span data-stu-id="be3c2-113">In the **Payment Services** window, choose the **New** action.</span></span>
3. <span data-ttu-id="be3c2-114">Veljið **PayPal Standard** og lokið svo glugganum.</span><span class="sxs-lookup"><span data-stu-id="be3c2-114">Select **PayPal Standard**, and then close the window.</span></span>
4. <span data-ttu-id="be3c2-115">Í glugganum **Greiðsluþjónustur** skal velja aðgerðina **uppsetning**.</span><span class="sxs-lookup"><span data-stu-id="be3c2-115">In the **Payment Services** window, choose the **Setup** action.</span></span>
5. <span data-ttu-id="be3c2-116">Fyllið inn í svæðin eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="be3c2-116">Fill in the fields as necessary.</span></span> <span data-ttu-id="be3c2-117">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="be3c2-117">Choose a field to read a short description of the field or link to more information.</span></span>

    <span data-ttu-id="be3c2-118">**Bent er á**: Valið er **Alltaf Með skjölum** gátreitinn ef tenglum fyrir PayPal greiðsluþjónustu ætti alltaf að vera sýnilegt í söluskjölum þar sem greiðsla í gegnum PayPal er virkjuð.</span><span class="sxs-lookup"><span data-stu-id="be3c2-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span></span>

6. <span data-ttu-id="be3c2-119">Glugganum er lokað.</span><span class="sxs-lookup"><span data-stu-id="be3c2-119">Close the window.</span></span>

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a><span data-ttu-id="be3c2-120">Til að velja PayPal Payments Standard á sölureikning.</span><span class="sxs-lookup"><span data-stu-id="be3c2-120">To select PayPal Payments Standard on a sales invoice</span></span>
1. <span data-ttu-id="be3c2-121">Í reitnum heimasíða velja **sölureikningar**.</span><span class="sxs-lookup"><span data-stu-id="be3c2-121">On the Home page, choose **Sales Invoices**.</span></span>
2. <span data-ttu-id="be3c2-122">Opnið sölureikningur sem á að virkja paypal greiðslur fyrir.</span><span class="sxs-lookup"><span data-stu-id="be3c2-122">Open the sales invoice that you want to enable PayPal payments for.</span></span>
3. <span data-ttu-id="be3c2-123">Í reitnum **GreiðsluÞjónustu** er valið er PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="be3c2-123">In the **Payment Service** field, choose PayPal Payments Standard.</span></span>

<span data-ttu-id="be3c2-124">**Athuga skal að**: **GreiðsluÞjónustu** reiturinn birtist aðeins ef PayPal Payments Standard er virkjað.</span><span class="sxs-lookup"><span data-stu-id="be3c2-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span></span>   

## <a name="see-also"></a><span data-ttu-id="be3c2-125">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="be3c2-125">See Also</span></span>  
[<span data-ttu-id="be3c2-126">Uppsetning sölu</span><span class="sxs-lookup"><span data-stu-id="be3c2-126">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="be3c2-127">Stjórna sölu</span><span class="sxs-lookup"><span data-stu-id="be3c2-127">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="be3c2-128">Sérstilling Dynamics NAV með viðbótum</span><span class="sxs-lookup"><span data-stu-id="be3c2-128">Customizing Dynamics NAV Using Extensions</span></span>](ui-extensions.md)

