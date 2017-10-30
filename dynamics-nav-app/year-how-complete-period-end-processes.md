---
title: "Valfrjálsar aðgerðir fyrir lokun tímabila"
description: "Þetta efnisatriði útskýrir valfrjáls ferli og aðgerðir fyrir lokun fjárhagstímabila í Dynamics NAV."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, aging, creditor payments, vendor payments
ms.date: 06/19/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ca22e72552c69d3bcb0b85101b586796ff026896
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="overview-of-tasks-to-close-accounting-periods"></a><span data-ttu-id="20d19-103">Yfirlit yfir verkhluta sem felur í sér lokun fjárhagstímabila</span><span class="sxs-lookup"><span data-stu-id="20d19-103">Overview of Tasks to Close Accounting Periods</span></span>
[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="20d19-104"> þvingar þig ekki til að loka tímabilum, en það eru margar aðgerðir í lokunartíma (lok mánaðar) sem þú getur gert.</span><span class="sxs-lookup"><span data-stu-id="20d19-104"> does not force you to close periods, however, there are many period-end (month-end) activities that you can do.</span></span> <span data-ttu-id="20d19-105">Þetta efni gefur yfirlit yfir valfrjáls ferli og starfsemi fyrir lokunartímabil.</span><span class="sxs-lookup"><span data-stu-id="20d19-105">This topic provides an overview of optional processes and activities for closing periods.</span></span>  

## <a name="general-ledger"></a><span data-ttu-id="20d19-106">Fjárhagur</span><span class="sxs-lookup"><span data-stu-id="20d19-106">General Ledger</span></span>
* <span data-ttu-id="20d19-107">Tilgreindu kerfisbundið og notendasértækt bókunartímabil.</span><span class="sxs-lookup"><span data-stu-id="20d19-107">Specify system-wide and user-specific posting periods.</span></span>  

    <span data-ttu-id="20d19-108">Þetta tilgreinir dagsetningar þar sem hægt er að bóka.</span><span class="sxs-lookup"><span data-stu-id="20d19-108">This specifies the dates between which you allow posting.</span></span> <span data-ttu-id="20d19-109">Þú gætir viljað leyfa bókun í byrjun tímabilsins eða í lok tímabilsins, allt eftir fyrirtækinu.</span><span class="sxs-lookup"><span data-stu-id="20d19-109">Depending on your business, you may want to allow posting at the start of the period, or toward the end.</span></span> <span data-ttu-id="20d19-110">Nánari upplýsingar eru í [Hvernig á að tilgreina bókunartímabil](finance-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="20d19-110">For more information, see [How to: Specify Posting Periods](finance-how-specify-posting-periods.md).</span></span>  
* <span data-ttu-id="20d19-111">Allar nauðsynlegar fjárhagsleiðréttingar eru framkvæmdar.</span><span class="sxs-lookup"><span data-stu-id="20d19-111">Make all necessary G/L adjustments.</span></span>  
* <span data-ttu-id="20d19-112">Ítrekunarbækur eru uppfærðar og bókaðar.</span><span class="sxs-lookup"><span data-stu-id="20d19-112">Update and post Recurring Journals.</span></span>  
  <!--* Process Consolidations-->
* <span data-ttu-id="20d19-113">Fjárhagsskema keyrt sem hér segir:</span><span class="sxs-lookup"><span data-stu-id="20d19-113">Run account schedules as follows:</span></span>  
  * <span data-ttu-id="20d19-114">Glugginn **Fjárhagsskema** er opnaður og smellt á aðgerðina **Prenta**.</span><span class="sxs-lookup"><span data-stu-id="20d19-114">Open the **Account Schedule** window, and then choose the **Print** action.</span></span>  

## <a name="sales-and-receivables"></a><span data-ttu-id="20d19-115">Sala and útistandandi</span><span class="sxs-lookup"><span data-stu-id="20d19-115">Sales and Receivables</span></span>
* <span data-ttu-id="20d19-116">Allar sölupantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.</span><span class="sxs-lookup"><span data-stu-id="20d19-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>  
* <span data-ttu-id="20d19-117">Inngreiðslubókin er bókuð.</span><span class="sxs-lookup"><span data-stu-id="20d19-117">Post all cash receipt journals.</span></span>  
* <span data-ttu-id="20d19-118">Uppfæra og birta bækur tímarit sem tengjast sölu og útistandandi.</span><span class="sxs-lookup"><span data-stu-id="20d19-118">Update and post recurring journals that are related to sales and receivables.</span></span>  
* <span data-ttu-id="20d19-119">Afstemma viðskiptakröfur við færslubók.</span><span class="sxs-lookup"><span data-stu-id="20d19-119">Reconcile accounts receivable to the general ledger.</span></span>  
* <span data-ttu-id="20d19-120">Runuvinnslan **Eyða reikningsf. sölupöntunum** er keyrð.</span><span class="sxs-lookup"><span data-stu-id="20d19-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>  

## <a name="purchases-and-payables"></a><span data-ttu-id="20d19-121">Innkaup og viðskiptaskuldir</span><span class="sxs-lookup"><span data-stu-id="20d19-121">Purchases and Payables</span></span>
* <span data-ttu-id="20d19-122">Allar pantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.</span><span class="sxs-lookup"><span data-stu-id="20d19-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>  
* <span data-ttu-id="20d19-123">Allar greiðslubækur eru bókaðar.</span><span class="sxs-lookup"><span data-stu-id="20d19-123">Post all payment journals.</span></span>  
* <span data-ttu-id="20d19-124">Ítrekunarfærslubækur tengdar innkaupum og viðskiptaskuldum eru uppfærðar og bókaðar.</span><span class="sxs-lookup"><span data-stu-id="20d19-124">Update and post recurring journals that are related to purchases & payables.</span></span>  
* <span data-ttu-id="20d19-125">Skýrslan **Aldursgreindar skuldir** er keyrð og skuldir stemmdar af við fjárhaginn.</span><span class="sxs-lookup"><span data-stu-id="20d19-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>  
* <span data-ttu-id="20d19-126">Runuvinnslan **Eyða reikningsf. innk.pöntunum** er keyrð.</span><span class="sxs-lookup"><span data-stu-id="20d19-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>  

<span data-ttu-id="20d19-127">Eignir</span><span class="sxs-lookup"><span data-stu-id="20d19-127">Fixed Assets</span></span>
* <span data-ttu-id="20d19-128">Allur viðhaldskostnaður hefur verið bókaður í gegnum Eignabók eða Reikningar</span><span class="sxs-lookup"><span data-stu-id="20d19-128">Post all maintenance costs have been posted through the fixed asset journals or invoices.</span></span>
* <span data-ttu-id="20d19-129">Leiðréttingar eru bókaðar</span><span class="sxs-lookup"><span data-stu-id="20d19-129">Post adjustments.</span></span>
* <span data-ttu-id="20d19-130">Uppfærsla er bókuð</span><span class="sxs-lookup"><span data-stu-id="20d19-130">Post appreciation.</span></span>
* <span data-ttu-id="20d19-131">Afskriftir eru bókaðar</span><span class="sxs-lookup"><span data-stu-id="20d19-131">Post depreciation.</span></span>
* <span data-ttu-id="20d19-132">Ítrekunarbók eigna er uppfærð og bókuð.</span><span class="sxs-lookup"><span data-stu-id="20d19-132">Update and post the recurring fixed asset journal.</span></span>

<span data-ttu-id="20d19-133">Milli fyrirtækja</span><span class="sxs-lookup"><span data-stu-id="20d19-133">Intercompany</span></span>
* <span data-ttu-id="20d19-134">Vinna úr færslum á milli fyrirtækja</span><span class="sxs-lookup"><span data-stu-id="20d19-134">Process Intercompany Transactions</span></span>

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="20d19-135">VSK er reiknaður og unninn</span><span class="sxs-lookup"><span data-stu-id="20d19-135">Calculate and Process Sales Tax</span></span>
* <span data-ttu-id="20d19-136">Lokið er við skattyfirlit.</span><span class="sxs-lookup"><span data-stu-id="20d19-136">Complete Tax Statements.</span></span>  

## <a name="see-also"></a><span data-ttu-id="20d19-137">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="20d19-137">See Also</span></span>
[<span data-ttu-id="20d19-138">Lokaár og Tímabil</span><span class="sxs-lookup"><span data-stu-id="20d19-138">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="20d19-139">Bókum lokað</span><span class="sxs-lookup"><span data-stu-id="20d19-139">Closing Books</span></span>](year-close-books.md)  
<span data-ttu-id="20d19-140">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="20d19-140">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
