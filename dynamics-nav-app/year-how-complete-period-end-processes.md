---
title: "Loka tímabili"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a><span data-ttu-id="f3eae-102">Loka tímabili</span><span class="sxs-lookup"><span data-stu-id="f3eae-102">Close Periods</span></span>
<span data-ttu-id="f3eae-103">Jöfnunin þvingar notanda ekki til að loka tímabilum, hins vegar eru margar lokatímabilaaðgerðir (mánaðarlok) sem hægt er að gera í jöfnuninni ef óskað er eftir.</span><span class="sxs-lookup"><span data-stu-id="f3eae-103">The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want.</span></span> <span data-ttu-id="f3eae-104">Í þessu efnisatriði er veitt yfirsýn yfir þessar vinnslur og aðgerðir sem kunna að vera nauðsynlegar í fyrirtæki notanda.</span><span class="sxs-lookup"><span data-stu-id="f3eae-104">This topic provides an overview of these processes and activities, which may or may not be necessary for your company.</span></span>

## <a name="general-ledger"></a><span data-ttu-id="f3eae-105">Fjárhagur</span><span class="sxs-lookup"><span data-stu-id="f3eae-105">General Ledger</span></span>
* <span data-ttu-id="f3eae-106">Tilgreina notandaskilgreind bókunardagsetningatímabil fyrir allt kerfið.</span><span class="sxs-lookup"><span data-stu-id="f3eae-106">Specify system-wide and user-specific posting period.</span></span>

    <span data-ttu-id="f3eae-107">Þetta tilgreinir það dagsetningabil sem bókanir eru leyfðar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-107">This specifies the dates between which postings are allowed.</span></span> <span data-ttu-id="f3eae-108">Hugsanlega þarf að takmarka notandabókuð dagsetningabil við upphaf vinnslu lokatímabila, eða nær lokum tímabilsins, allt eftir þörfum fyrirtækisins.</span><span class="sxs-lookup"><span data-stu-id="f3eae-108">Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period.</span></span> <span data-ttu-id="f3eae-109">Nánari upplýsingar eru í [Hvernig á að tilgreina bókunartímabil](finance-setup-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="f3eae-109">For more information, see [How to: Specify Posting Periods](finance-setup-how-specify-posting-periods.md).</span></span>
* <span data-ttu-id="f3eae-110">Allar nauðsynlegar fjárhagsleiðréttingar eru framkvæmdar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-110">Make all necessary G/L adjustments.</span></span>
* <span data-ttu-id="f3eae-111">Ítrekunarbækur eru uppfærðar og bókaðar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-111">Update and post Recurring Journals.</span></span>
<!--* Process Consolidations-->
* <span data-ttu-id="f3eae-112">Fjárhagsskema keyrt sem hér segir:</span><span class="sxs-lookup"><span data-stu-id="f3eae-112">Run account schedules as follows:</span></span>
  1. <span data-ttu-id="f3eae-113">Glugginn **Fjárhagsskema** er opnaður og smellt á aðgerðina **Prenta**.</span><span class="sxs-lookup"><span data-stu-id="f3eae-113">Open the **Account Schedule** window, and choose the **Print** action.</span></span>
  2. <span data-ttu-id="f3eae-114">Fyllið inn í beiðnagluggann **Fjárhagsskema** og smellið á aðgerðina **Prenta**.</span><span class="sxs-lookup"><span data-stu-id="f3eae-114">Fill the **Account Schedule** request window and choose the **Print** action.</span></span>

## <a name="sales--receivables"></a><span data-ttu-id="f3eae-115">Sala</span><span class="sxs-lookup"><span data-stu-id="f3eae-115">Sales & Receivables</span></span>
* <span data-ttu-id="f3eae-116">Allar sölupantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="f3eae-117">Inngreiðslubókin er bókuð.</span><span class="sxs-lookup"><span data-stu-id="f3eae-117">Post all cash receipt journals.</span></span>
* <span data-ttu-id="f3eae-118">Ítrekunarfærslubækur tengdar sölugrunni eru uppfærðar og bókaðar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-118">Update and post recurring journals that are related to Sales & Receivables.</span></span>
* <span data-ttu-id="f3eae-119">Afstemma viðskiptakröfur við færslubók.</span><span class="sxs-lookup"><span data-stu-id="f3eae-119">Reconcile accounts receivable to the general ledger.</span></span>
* <span data-ttu-id="f3eae-120">Runuvinnslan **Eyða reikningsf. sölupöntunum** er keyrð.</span><span class="sxs-lookup"><span data-stu-id="f3eae-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>

## <a name="purchases--payables"></a><span data-ttu-id="f3eae-121">Innkaup</span><span class="sxs-lookup"><span data-stu-id="f3eae-121">Purchases & Payables</span></span>
* <span data-ttu-id="f3eae-122">Allar pantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="f3eae-123">Allar greiðslubækur eru bókaðar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-123">Post all payment journals.</span></span>
* <span data-ttu-id="f3eae-124">Ítrekunarfærslubækur tengdar innkaupum og viðskiptaskuldum eru uppfærðar og bókaðar.</span><span class="sxs-lookup"><span data-stu-id="f3eae-124">Update and post recurring journals that are related to purchases & payables.</span></span>
* <span data-ttu-id="f3eae-125">Skýrslan **Aldursgreindar skuldir** er keyrð og skuldir stemmdar af við fjárhaginn.</span><span class="sxs-lookup"><span data-stu-id="f3eae-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>
* <span data-ttu-id="f3eae-126">Runuvinnslan **Eyða reikningsf. innk.pöntunum** er keyrð.</span><span class="sxs-lookup"><span data-stu-id="f3eae-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="f3eae-127">VSK er reiknaður og unninn</span><span class="sxs-lookup"><span data-stu-id="f3eae-127">Calculate and Process Sales Tax</span></span>
*  <span data-ttu-id="f3eae-128">Lokið er við skattyfirlit.</span><span class="sxs-lookup"><span data-stu-id="f3eae-128">Complete Tax Statements.</span></span>

## <a name="see-also"></a><span data-ttu-id="f3eae-129">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="f3eae-129">See Also</span></span>
[<span data-ttu-id="f3eae-130">Lokaár og Tímabil</span><span class="sxs-lookup"><span data-stu-id="f3eae-130">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="f3eae-131">Loka bókum</span><span class="sxs-lookup"><span data-stu-id="f3eae-131">Close Books</span></span>](year-close-books.md)

