---
title: "Hvernig á að Sameina móttökur"
description: "Ef reikningsfæra á fleiri en eina innkaupamóttöku í einu er hægt að nota aðgerðina sameinaðar móttökur."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 10749dc8d8d692d94c5405fbb0a4a965d482f013
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-combine-receipts-on-a-single-invoice"></a><span data-ttu-id="7340c-103">Hvernig á að: sameina móttökur í einn reikning</span><span class="sxs-lookup"><span data-stu-id="7340c-103">How to: Combine Receipts on a Single Invoice</span></span>
<span data-ttu-id="7340c-104">Ef reikningsfæra á fleiri en eina innkaupamóttöku í einu er hægt að nota aðgerðina **sameinaðar móttökur**.</span><span class="sxs-lookup"><span data-stu-id="7340c-104">If you want to invoice more than one purchase receipt at a time, you can use the **Combine Receipts** function.</span></span>  

<span data-ttu-id="7340c-105">Áður en hægt er að búa til sameinaða innkaupamóttöku, þarf að vera búið að bóka fleiri en eina móttöku frá sama lánardrottininn í sama gjaldmiðlinum.</span><span class="sxs-lookup"><span data-stu-id="7340c-105">Before you can create a combined purchase receipt, more than one receipt from the same vendor in the same currency must be posted.</span></span> <span data-ttu-id="7340c-106">Það er að segja, það þarf að vera búið að fylla út tvær eða fleiri innkaupapantanir og bóka þær sem mótteknar en ekki reikningsfærðar.</span><span class="sxs-lookup"><span data-stu-id="7340c-106">In other words, you must have filled in two or more purchase orders and posted them as received, but not invoiced.</span></span>  

<span data-ttu-id="7340c-107">Þegar innkaupareikningar eru sameinaðir og bókaðir á reikningi, er bókaður innkaupareikningur stofnaður fyrir reikningslínu(r).</span><span class="sxs-lookup"><span data-stu-id="7340c-107">When purchase receipts are combined on an invoice and posted, then a posted purchase invoice is created for the invoiced lines.</span></span> <span data-ttu-id="7340c-108">Reiturinn **Reikningsfært magn** á upprunalegri innkaupapöntun eða standandi innkaupapöntun er uppfærður á grundvelli reikningsfærða magnsins.</span><span class="sxs-lookup"><span data-stu-id="7340c-108">The **Quantity Invoiced** field on the originating purchase order, or blanket purchase order, is updated based on the invoiced quantity.</span></span> <span data-ttu-id="7340c-109">Hins vegar er upprunalega innkaupaskjalinu ekki eytt jafnvel þó það hafi verið móttekið og reikningsfært að fullu og því verður að eyða innkaupaskjalinu.</span><span class="sxs-lookup"><span data-stu-id="7340c-109">However, this original purchase document is not deleted, even if it has been fully received and invoiced, and you must therefore delete the purchase document.</span></span>  

## <a name="to-combine-receipts"></a><span data-ttu-id="7340c-110">Sameining móttakna:</span><span class="sxs-lookup"><span data-stu-id="7340c-110">To combine receipts</span></span>  
1. <span data-ttu-id="7340c-111">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innkaupareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="7340c-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7340c-112">Valið er **Nýtt** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="7340c-112">Choose the **New** action.</span></span> <span data-ttu-id="7340c-113">Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="7340c-113">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>  
3. <span data-ttu-id="7340c-114">Á flýtiflipanum **Línur** skal velja **Sækja móttökulínur** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="7340c-114">On the **Lines** FastTab, choose the **Get Receipt Lines** action.</span></span>  
4. <span data-ttu-id="7340c-115">Nokkrar móttökulínur eru valdar sem eiga að vera á reikningnum:</span><span class="sxs-lookup"><span data-stu-id="7340c-115">Select multiple receipt lines that you want to include in the invoice.</span></span>  

    <span data-ttu-id="7340c-116">Ef röng móttökulína var valin eða byrja á upp á nýtt er einfaldlega hægt að eyða línunum í innkaupareikningum og nota aftur aðgerðina **Sækja móttökulínur**.</span><span class="sxs-lookup"><span data-stu-id="7340c-116">If an incorrect receipt line was selected or you want to start over, you can just delete the lines on the purchase invoice and then use the **Get Receipt Lines** function again.</span></span>  
5. <span data-ttu-id="7340c-117">Til að bóka reikningur er valið aðgerðin **bóka**.</span><span class="sxs-lookup"><span data-stu-id="7340c-117">To post the invoice, choose the **Post** action.</span></span>  

## <a name="to-remove-open-purchase-orders-after-combined-receipt-posting"></a><span data-ttu-id="7340c-118">Til að fjarlægja opnar innkaupapantanir eftir bókun sameinaðrar móttöku</span><span class="sxs-lookup"><span data-stu-id="7340c-118">To remove open purchase orders after combined receipt posting</span></span>  
1. <span data-ttu-id="7340c-119">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Eyða reikningsfærðum innkaupapantanir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="7340c-119">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Delete Invoiced Purchase Orders**, and select the related link.</span></span>  
2. <span data-ttu-id="7340c-120">Fyllið inn í reitina eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="7340c-120">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]<span data-ttu-id="7340c-121">.</span><span class="sxs-lookup"><span data-stu-id="7340c-121">.</span></span>
3. <span data-ttu-id="7340c-122">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="7340c-122">Choose the **OK** button.</span></span>  

<span data-ttu-id="7340c-123">Að öðrum kosti skal eyða einstökum pöntunum handvirkt.</span><span class="sxs-lookup"><span data-stu-id="7340c-123">Alternatively, delete the individual orders manually.</span></span>

<span data-ttu-id="7340c-124">Skref 1 til 3 eru endurtekin fyrir öll skjöl sem urðu fyrir áhrifum, eins og auðar innikaupapantanir.</span><span class="sxs-lookup"><span data-stu-id="7340c-124">Repeat steps 1 through 3 for any other affected documents, such as blanket purchase orders.</span></span>

## <a name="see-also"></a><span data-ttu-id="7340c-125">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="7340c-125">See Also</span></span>  
[<span data-ttu-id="7340c-126">Innkaup</span><span class="sxs-lookup"><span data-stu-id="7340c-126">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="7340c-127">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="7340c-127">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
