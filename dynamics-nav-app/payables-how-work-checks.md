---
title: "Gefa út, Prenta, Hætta við og ógilda athuganir"
description: "Lýsir því hvernig skal gefa út ávísanir með því að nota greiðslubók, prenta ávísanir og ógilda eða skoða ávísanafjárhagsfærslur í Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment journal, print check, vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 716cb17bf65b225036576dc73f3fe43b102ccb81
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-checks"></a><span data-ttu-id="9285a-103">Hvernig á að: vinna með tékka</span><span class="sxs-lookup"><span data-stu-id="9285a-103">How to: Work With Checks</span></span>
<span data-ttu-id="9285a-104">Þú getur gefið út rafrænar og handvirkar ávísanir [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="9285a-104">You can issue electronic and manual checks in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="9285a-105">Í báðum aðferðum er útgreiðslubók notuð til að gefa út tékka til lánardrottna.</span><span class="sxs-lookup"><span data-stu-id="9285a-105">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="9285a-106">Einnig er hægt að ógilda tékka og skoða fjárhagsfærslur.</span><span class="sxs-lookup"><span data-stu-id="9285a-106">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="9285a-107">Vinnslan sem gefur út tékka stingur upp á greiðslum, býr til fjárhagsfærslur og prentar vélfærðu  tékkana.</span><span class="sxs-lookup"><span data-stu-id="9285a-107">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

> [!NOTE]  
>   <span data-ttu-id="9285a-108">Til að ganga úr skugga um að bankinn þinn eingöngu taki við fullgildum ávísunum og upphæðum, geturðu sent þeim skrá sem inniheldur seljanda, ávísun og greiðsluupplýsingar.</span><span class="sxs-lookup"><span data-stu-id="9285a-108">To make sure that your bank only clears validated checks and amounts, you can send them a file that contains vendor, check, and payment information.</span></span> <span data-ttu-id="9285a-109">Nánari upplýsingar er að finna í [Hvernig á að: flytja út jákvæða greiðsluskrá](finance-how-positive-pay.md).</span><span class="sxs-lookup"><span data-stu-id="9285a-109">For more information, see [How to: Export a Positive Pay file](finance-how-positive-pay.md).</span></span>

<span data-ttu-id="9285a-110">Prentarinn verður að vera rétt stilltur með tékkaeyðublöðum, og þú verður að skilgreina hvaða útlit tékka á að nota.</span><span class="sxs-lookup"><span data-stu-id="9285a-110">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="9285a-111">Nánari upplýsingar sjá [Hvernig á að: Skilgreina útlit tékka:](finance-how-define-check-layouts.md)</span><span class="sxs-lookup"><span data-stu-id="9285a-111">For more information, see [How to: Define Check Layouts](finance-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="9285a-112">gefa út tékka</span><span class="sxs-lookup"><span data-stu-id="9285a-112">To issue checks</span></span>
1. <span data-ttu-id="9285a-113">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **greiðslubækur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="9285a-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="9285a-114">Fyllið út færslubók, t.d. með viðeigandi greiðslum, til dæmis með því að nota virknina Greiðslutillögur til lánardrottna.</span><span class="sxs-lookup"><span data-stu-id="9285a-114">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="9285a-115">Nánari upplýsingar má sjá í [Hvernig á að: Leggja til greiðslutillögur til lánardrottna](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="9285a-115">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="9285a-116">Í reitnum **Tegund Bankagreiðslu** í færslubókarlínunum fyrir greiðslur sem þú vilt gera með tékkum, veldu einn af eftirfarandi valkostum.</span><span class="sxs-lookup"><span data-stu-id="9285a-116">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

   * <span data-ttu-id="9285a-117">**Vélfærður tékki**: veldu þennan valkost ef  á að prenta tékka með upphæðinni í færslubókarlínunni.</span><span class="sxs-lookup"><span data-stu-id="9285a-117">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="9285a-118">Þú þarft að prenta tékkana áður en þú bókar færslubókarlínurnar.</span><span class="sxs-lookup"><span data-stu-id="9285a-118">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="9285a-119">Þú getur eingöngu valið **Vélfærður tékki** ef **Tegund mótreiknings** eða **Tegund reiknings** er **Bankareikningur**.</span><span class="sxs-lookup"><span data-stu-id="9285a-119">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>
   * <span data-ttu-id="9285a-120">**Handfærður tékki**  Þessi kostur er valinn ef handfærður tékki hefur verið búinn til og  á að búa til tékkafærslu sem samsvarar upphæðinni.</span><span class="sxs-lookup"><span data-stu-id="9285a-120">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="9285a-121">Með þessum valkosti er ekki hægt að prenta tékka úr [!INCLUDE[d365fin](includes/d365fin_md.md)]</span><span class="sxs-lookup"><span data-stu-id="9285a-121">By using this option, you cannot print checks from [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="9285a-122">Þú getur eingöngu valið **handfærður tékki** ef **Tegund mótreiknings** eða **Tegund reiknings** er **Bankareikningur**.</span><span class="sxs-lookup"><span data-stu-id="9285a-122">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

     > [!NOTE]  
>   <span data-ttu-id="9285a-123">Þarf að prenta vélfærðu tékkana áður en hægt er að bóka tengdu færslubókarlínurnar.</span><span class="sxs-lookup"><span data-stu-id="9285a-123">You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="9285a-124">Ef um er að ræða vélfærða tékka, veldu **Prenta Tékka**.</span><span class="sxs-lookup"><span data-stu-id="9285a-124">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="9285a-125">Í glugganum **ávísun** þarf að fylla reitina út eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="9285a-125">In the **Check** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
6. <span data-ttu-id="9285a-126">Velja hnappinn **Prenta**.</span><span class="sxs-lookup"><span data-stu-id="9285a-126">Choose the **Print** button.</span></span>

> [!NOTE]  
>   <span data-ttu-id="9285a-127">Ef þarf að prenta tékka í fleiri en einum gjaldmiðli frá mismunandi bankareikningum verður að keyra keyrsluna **Prenta tékka** sérstaklega fyrir hvern gjaldmiðil og tilgreina réttan bankareikning.</span><span class="sxs-lookup"><span data-stu-id="9285a-127">If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="9285a-128">Til að ógilda prentaðan tékka sem ekki eru bókaðar</span><span class="sxs-lookup"><span data-stu-id="9285a-128">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="9285a-129">Hægt er að ógilda tékka sem eftir á að bóka þegar þær hafa verið prentuð með því að nota **Ógilda Tékka** aðgerð í á **greiðslubók** glugga.</span><span class="sxs-lookup"><span data-stu-id="9285a-129">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>

1. <span data-ttu-id="9285a-130">Í á **greiðslubókarglugga** er valið á **Ógilda Tékka**, og síðan valið hvaða tékka á að ógilda.</span><span class="sxs-lookup"><span data-stu-id="9285a-130">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="9285a-131">Tékkar ógiltir:</span><span class="sxs-lookup"><span data-stu-id="9285a-131">To void checks</span></span>
<span data-ttu-id="9285a-132">Þegar tékkagreiðslur hafa verið bókaðar, geturðu aðeins afturkallað (ógilt) tékka úr bankafærslum sem fengust út úr þessu.</span><span class="sxs-lookup"><span data-stu-id="9285a-132">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="9285a-133">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bankareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="9285a-133">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="9285a-134">Veldu viðeigandi bankareikning, veldu **breyta** aðgerðina og veldu síðan **tékkafærslur** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="9285a-134">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="9285a-135">Í **tékkafærslur** glugganum, veldu **ógilda tékka** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="9285a-135">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="9285a-136">Veldu gátreitinn **eingöngu ógilda tékka**.</span><span class="sxs-lookup"><span data-stu-id="9285a-136">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="9285a-137">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="9285a-137">Choose the **OK** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="9285a-138">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="9285a-138">See Also</span></span>
[<span data-ttu-id="9285a-139">Stjórna skuldum</span><span class="sxs-lookup"><span data-stu-id="9285a-139">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="9285a-140">Uppsetning bankaþjónustu</span><span class="sxs-lookup"><span data-stu-id="9285a-140">Setting Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="9285a-141">Hvernig á að: flytja út jákvæða greiðsluskrá</span><span class="sxs-lookup"><span data-stu-id="9285a-141">How to: Export a Positive Pay file</span></span>](finance-how-positive-pay.md)  
<span data-ttu-id="9285a-142">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9285a-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
