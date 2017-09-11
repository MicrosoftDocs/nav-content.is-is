---
title: "Hvernig á að: Skrá söluverð og afslætti"
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
ms.openlocfilehash: 80a0ac1edc994f44795f7f907a647b269578bc47
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a><span data-ttu-id="79eb8-102">Hvernig á að: Skrá söluverð og afslætti</span><span class="sxs-lookup"><span data-stu-id="79eb8-102">How to: Record Sales Prices and Discounts</span></span>
<span data-ttu-id="79eb8-103">Skilgreina þarf ólíka verð- og greiðsluskilmála sem gilda þegar ólíkum viðskiptamönnum er selt þannig að umsamin gildi og reglur séu notuð í söluskjölum sem stofnuð eru fyrir viðskiptamennina.</span><span class="sxs-lookup"><span data-stu-id="79eb8-103">The different price and discount agreements that apply when selling to different customers must be defined so that the agreed rules and values are applied to sales documents that you create for the customers.</span></span>

<span data-ttu-id="79eb8-104">Hvað varðar verð er hægt að hafa sérstakt söluverð sett í sölulínur ef tiltekin samsetning á viðskiptamanni, vöru, lágmarksmagni, mælieiningu, eða tupphafs-/ lokadagsetningu er til staðar.</span><span class="sxs-lookup"><span data-stu-id="79eb8-104">Concerning prices, you can have a special sales price inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span>

<span data-ttu-id="79eb8-105">Hvað varðar afslætti er hægt að setja upp og nota tvær tegundir söluafsláttar:</span><span class="sxs-lookup"><span data-stu-id="79eb8-105">Concerning discounts, you can set up and use two types of sales discounts:</span></span>

|<span data-ttu-id="79eb8-106">Afsláttargerð</span><span class="sxs-lookup"><span data-stu-id="79eb8-106">Discount Type</span></span> |<span data-ttu-id="79eb8-107">Lýsing</span><span class="sxs-lookup"><span data-stu-id="79eb8-107">Description</span></span> |
|--------------|------------|
|<span data-ttu-id="79eb8-108">**Sölulínuafsláttur**</span><span class="sxs-lookup"><span data-stu-id="79eb8-108">**Sales Line Discount**</span></span>|<span data-ttu-id="79eb8-109">Afsláttarupphæð sem er sett inn í sölulínu ef tiltekin samsetning á viðskiptamanni, vöru, lágmarksmagni, mælieiningu, eða upphafs-/ lokadagsetningu er til staðar.</span><span class="sxs-lookup"><span data-stu-id="79eb8-109">An amount discount that is inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span> <span data-ttu-id="79eb8-110">Þetta virkar á sama hátt og fyrir söluverð.</span><span class="sxs-lookup"><span data-stu-id="79eb8-110">This works in the same way as for sales prices.</span></span>|
|<span data-ttu-id="79eb8-111">**Reikningsafsláttur**</span><span class="sxs-lookup"><span data-stu-id="79eb8-111">**Invoice Discount**</span></span>|<span data-ttu-id="79eb8-112">Hlutfallsafsláttur sem er dreginn frá heildarupphæð skjalsins ef upphæðin í öllum línum í söluskjali fer fram yfir ákveðið lágmark.</span><span class="sxs-lookup"><span data-stu-id="79eb8-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a sales document exceeds a certain minimum.</span></span>|

<span data-ttu-id="79eb8-113">Af því að söluverð og afsláttur á sölulínur byggist á samsetningu vöru og viðskiptamanns þá má einnig framkvæma þessa grunnstillingu í birgðaspjaldi vörunnar þar sem reglurnar og gildin eiga við.</span><span class="sxs-lookup"><span data-stu-id="79eb8-113">Because sales prices and sales line discounts are based on a combination of item and customer, you can also perform this configuration from the item card of the item where the rules and values apply.</span></span>

## <a name="to-set-up-a-sales-price-for-a-customer"></a><span data-ttu-id="79eb8-114">Að setja upp söluverð fyrir viðskiptamann</span><span class="sxs-lookup"><span data-stu-id="79eb8-114">To set up a sales price for a customer</span></span>
1. <span data-ttu-id="79eb8-115">Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **viðskiptamenn** og velja síðan viðkomandi tengil.</span><span class="sxs-lookup"><span data-stu-id="79eb8-115">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="79eb8-116">Opna skal viðeigandi viðskiptamannaspjald og veljið síðan aðgerðina **Verð**.</span><span class="sxs-lookup"><span data-stu-id="79eb8-116">Open the relevant customer card, and then choose the **Prices** action.</span></span>

    <span data-ttu-id="79eb8-117">Í reitnum **Tegund sölu** er búið að fylla út **Viðskiptamaður** og í reitnum **Sölukóði** er búið að fylla út númer viðskiptamannsins.</span><span class="sxs-lookup"><span data-stu-id="79eb8-117">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3. <span data-ttu-id="79eb8-118">Fyllið út reitina í línunni eins og þörf er á.</span><span class="sxs-lookup"><span data-stu-id="79eb8-118">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="79eb8-119">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="79eb8-119">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="79eb8-120">Fyllt er út lína fyrir hverja samsetningu sem veitir sérstakt söluverð fyrir viðskiptamanninn.</span><span class="sxs-lookup"><span data-stu-id="79eb8-120">Fill a line for each combination that will grant a special sales price to the customer.</span></span>

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a><span data-ttu-id="79eb8-121">Sölulínuafsláttur stofnaður fyrir viðskiptamann</span><span class="sxs-lookup"><span data-stu-id="79eb8-121">To set up a sales line discount for a customer</span></span>
1. <span data-ttu-id="79eb8-122">Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **viðskiptamenn** og velja síðan viðkomandi tengil.</span><span class="sxs-lookup"><span data-stu-id="79eb8-122">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="79eb8-123">Opna skal viðeigandi viðskiptamannaspjald og veljið svo aðgerðina **Línuafslættir**.</span><span class="sxs-lookup"><span data-stu-id="79eb8-123">Open the relevant customer card, and then choose the **Line Discounts** action.</span></span>

    <span data-ttu-id="79eb8-124">Í reitnum **Tegund sölu** er búið að fylla út **Viðskiptamaður** og í reitnum **Sölukóði** er búið að fylla út númer viðskiptamannsins.</span><span class="sxs-lookup"><span data-stu-id="79eb8-124">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3.  <span data-ttu-id="79eb8-125">Fyllið út reitina í línunni eins og þörf er á.</span><span class="sxs-lookup"><span data-stu-id="79eb8-125">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="79eb8-126">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="79eb8-126">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="79eb8-127">Fyllt er út lína fyrir hverja samsetningu sem veitir sérstakan sölulínuafslátt fyrir viðskiptamanninn.</span><span class="sxs-lookup"><span data-stu-id="79eb8-127">Fill a line for each combination that will grant a sales line discount to the customer.</span></span>

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a><span data-ttu-id="79eb8-128">Að setja upp reikningsafslátt fyrir viðskiptamann</span><span class="sxs-lookup"><span data-stu-id="79eb8-128">To set up an invoice discount for a customer</span></span>
<span data-ttu-id="79eb8-129">Eftir að ákveðið hefur verið hvaða viðskiptamenn geti fengið reikningsafslátt eru færðir inn reikningsafsláttarkóðar á viðskiptamannaspjöldin og sett upp skilyrði fyrir hvern kóða.</span><span class="sxs-lookup"><span data-stu-id="79eb8-129">When you have decided which customers are eligible for invoice discounts, enter the invoice discount code on the customer cards and set up the terms for each code.</span></span>

1. <span data-ttu-id="79eb8-130">Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **viðskiptamenn** og velja síðan viðkomandi tengil.</span><span class="sxs-lookup"><span data-stu-id="79eb8-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="79eb8-131">Opna skal spjald viðskiptamanns sem getur fengið reikningsafslátt.</span><span class="sxs-lookup"><span data-stu-id="79eb8-131">Open the customer card for a customer that will be eligible for invoice discounts.</span></span>
3. <span data-ttu-id="79eb8-132">Í reitinn **Reikningsafsláttarkóði** er færður inn kóði fyrir viðeigandi reikningsafsláttarskilmála sem forritið notar til að reikna reikningsafslátt fyrir viðskiptamanninn.</span><span class="sxs-lookup"><span data-stu-id="79eb8-132">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the customer.</span></span>

    <span data-ttu-id="79eb8-133">**Athugasemd**: Fyrirliggjandi viðskiptamannaspjöld standa fyrir reikningsafsláttarkóða.</span><span class="sxs-lookup"><span data-stu-id="79eb8-133">**Note**: Invoice discount codes are represented by existing customer cards.</span></span> <span data-ttu-id="79eb8-134">Þetta gerir kleift að úthluta reikningsafsláttarskilmálum hratt og örugglega til viðskiptamanna með því að velja nafn annars viðskiptamanns sem hefur sömu skilmála.</span><span class="sxs-lookup"><span data-stu-id="79eb8-134">This enables you to quickly assign invoice discount terms to customers by picking the name of another customer who will have the same terms.</span></span>

    <span data-ttu-id="79eb8-135">Næsta skref er að setja upp nýja skilmála fyrir sölureikningsafslætti.</span><span class="sxs-lookup"><span data-stu-id="79eb8-135">Proceed to set up new the sales invoice discount terms.</span></span>
4. <span data-ttu-id="79eb8-136">Í glugganum **Viðskiptamannaspjald** er aðgerðin **Reikningsafsláttur** valin.</span><span class="sxs-lookup"><span data-stu-id="79eb8-136">In the **Customer Card** window, choose the **Invoice Discounts** action.</span></span> <span data-ttu-id="79eb8-137">Glugginn **Reikningsafsláttur viðskm.** opnast.</span><span class="sxs-lookup"><span data-stu-id="79eb8-137">The **Cust. Invoice Discounts** window opens.</span></span>
5. <span data-ttu-id="79eb8-138">Í reitnum **Gjaldmiðilskóði** er færður inn kóðinn fyrir gjaldmiðilinn sem reikningsafsláttarskilyrði í línunni eiga við um.</span><span class="sxs-lookup"><span data-stu-id="79eb8-138">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span></span> <span data-ttu-id="79eb8-139">Reiturinn er skilinn eftir auður ef setja á upp reikningsafsláttarskilyrði í USD.</span><span class="sxs-lookup"><span data-stu-id="79eb8-139">Leave the field blank to set up invoice discount terms in USD.</span></span>
6. <span data-ttu-id="79eb8-140">Í reitinn **Lágmarksupphæð** er færð inn lágmarksupphæð sem reikningur þarf að hafa til að hægt sé að fá afslátt.</span><span class="sxs-lookup"><span data-stu-id="79eb8-140">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span></span>
7. <span data-ttu-id="79eb8-141">Í reitnum **Afsláttar %** skal slá inn reikningsafslátt sem prósentu af reikningsupphæð.</span><span class="sxs-lookup"><span data-stu-id="79eb8-141">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span></span>
8. <span data-ttu-id="79eb8-142">Endurtakið skref 5 til 7 fyrir alla gjaldmiðla sem viðskiptamaðurinn mun fá mismunandi reikningsafslátt í.</span><span class="sxs-lookup"><span data-stu-id="79eb8-142">Repeat steps 5 through 7 for each currency that the customer will receive a different invoice discount for.</span></span>

<span data-ttu-id="79eb8-143">Reikningsafsláttur er nú settur upp og úthlutað á umræddan viðskiptamann.</span><span class="sxs-lookup"><span data-stu-id="79eb8-143">The invoice discount is now set up and assigned to the customer in question.</span></span> <span data-ttu-id="79eb8-144">Þegar valinn er kóði viðskiptamannsins í reitnum **Reikningsafsl.kóði** á öðrum viðskiptamannaspjöldum er sama reikningsafslætti úthlutað þeim viðskiptamönnum.</span><span class="sxs-lookup"><span data-stu-id="79eb8-144">When you select the customer code in the **Invoice Disc. Code** field on other customer cards, the same invoice discount is assigned to those customers.</span></span>

## <a name="see-also"></a><span data-ttu-id="79eb8-145">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="79eb8-145">See Also</span></span>  
[<span data-ttu-id="79eb8-146">Uppsetning sölu</span><span class="sxs-lookup"><span data-stu-id="79eb8-146">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="79eb8-147">Stjórna sölu</span><span class="sxs-lookup"><span data-stu-id="79eb8-147">Manage Sales</span></span>](sales-manage-sales.md)

