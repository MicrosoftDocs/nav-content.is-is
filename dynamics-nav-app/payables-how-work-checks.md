---
title: "Hvernig á að: vinna með tékka"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a><span data-ttu-id="6a43a-102">Hvernig á að: vinna með tékka</span><span class="sxs-lookup"><span data-stu-id="6a43a-102">How to: Work With Checks</span></span>
<span data-ttu-id="6a43a-103">Dynamics NAV styður rafrænar og handvirkar útgáfur á tékkum.</span><span class="sxs-lookup"><span data-stu-id="6a43a-103">Dynamics NAV supports electronic and manual check issuance.</span></span> <span data-ttu-id="6a43a-104">Í báðum aðferðum er útgreiðslubók notuð til að gefa út tékka til lánardrottna.</span><span class="sxs-lookup"><span data-stu-id="6a43a-104">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="6a43a-105">Einnig er hægt að ógilda tékka og skoða fjárhagsfærslur.</span><span class="sxs-lookup"><span data-stu-id="6a43a-105">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="6a43a-106">Vinnslan sem gefur út tékka stingur upp á greiðslum, býr til fjárhagsfærslur og prentar vélfærðu  tékkana.</span><span class="sxs-lookup"><span data-stu-id="6a43a-106">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

<span data-ttu-id="6a43a-107">Prentarinn verður að vera rétt stilltur með tékkaeyðublöðum, og þú verður að skilgreina hvaða útlit tékka á að nota.</span><span class="sxs-lookup"><span data-stu-id="6a43a-107">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="6a43a-108">Nánari upplýsingar sjá [Hvernig á að: Skilgreina útlit tékka:](finance-setup-how-define-check-layouts.md)</span><span class="sxs-lookup"><span data-stu-id="6a43a-108">For more information, see [How to: Define Check Layouts](finance-setup-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="6a43a-109">gefa út tékka</span><span class="sxs-lookup"><span data-stu-id="6a43a-109">To issue checks</span></span>
1. <span data-ttu-id="6a43a-110">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Greiðslubækur**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="6a43a-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="6a43a-111">Fyllið út færslubók, t.d. með viðeigandi greiðslum, til dæmis með því að nota virknina Greiðslutillögur til lánardrottna.</span><span class="sxs-lookup"><span data-stu-id="6a43a-111">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="6a43a-112">Nánari upplýsingar má sjá í [Hvernig á að: Leggja til greiðslutillögur til lánardrottna](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="6a43a-112">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="6a43a-113">Í reitnum **Tegund Bankagreiðslu** í færslubókarlínunum fyrir greiðslur sem þú vilt gera með tékkum, veldu einn af eftirfarandi valkostum.</span><span class="sxs-lookup"><span data-stu-id="6a43a-113">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

 - <span data-ttu-id="6a43a-114">**Vélfærður tékki**: veldu þennan valkost ef  á að prenta tékka með upphæðinni í færslubókarlínunni.</span><span class="sxs-lookup"><span data-stu-id="6a43a-114">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="6a43a-115">Þú þarft að prenta tékkana áður en þú bókar færslubókarlínurnar.</span><span class="sxs-lookup"><span data-stu-id="6a43a-115">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="6a43a-116">Þú getur eingöngu valið **Vélfærður tékki** ef **Tegund mótreiknings** eða **Tegund reiknings** er **Bankareikningur**.</span><span class="sxs-lookup"><span data-stu-id="6a43a-116">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

 - <span data-ttu-id="6a43a-117">**Handfærður tékki**  Þessi kostur er valinn ef handfærður tékki hefur verið búinn til og  á að búa til tékkafærslu sem samsvarar upphæðinni.</span><span class="sxs-lookup"><span data-stu-id="6a43a-117">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="6a43a-118">Með þessum valkosti er ekki hægt að prenta tékka úr Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="6a43a-118">By using this option, you cannot print checks from Dynamics NAV.</span></span> <span data-ttu-id="6a43a-119">Þú getur eingöngu valið **handfærður tékki** ef **Tegund mótreiknings** eða **Tegund reiknings** er **Bankareikningur**.</span><span class="sxs-lookup"><span data-stu-id="6a43a-119">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

    <span data-ttu-id="6a43a-120">**Athugasemd** : Þarf að prenta vélfærðu tékkana áður en hægt er að bóka tengdu færslubókarlínurnar.</span><span class="sxs-lookup"><span data-stu-id="6a43a-120">**Note**: You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="6a43a-121">Ef um er að ræða vélfærða tékka, veldu **Prenta Tékka**.</span><span class="sxs-lookup"><span data-stu-id="6a43a-121">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="6a43a-122">Í glugganum **ávísun** þarf að fylla reitina út eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="6a43a-122">In the **Check** window, fill in the fields as necessary.</span></span> <span data-ttu-id="6a43a-123">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="6a43a-123">Choose a field to read a short description of the field or link to more information.</span></span>
6. <span data-ttu-id="6a43a-124">Velja hnappinn **Prenta**.</span><span class="sxs-lookup"><span data-stu-id="6a43a-124">Choose the **Print** button.</span></span>

<span data-ttu-id="6a43a-125">**Athugasemd**: Ef prenta þarf tékka í fleiri en einum gjaldmiðli frá mismunandi bankareikningum verður að keyra keyrsluna **Prenta tékka** sérstaklega fyrir hvern gjaldmiðil og tilgreina réttan bankareikning.</span><span class="sxs-lookup"><span data-stu-id="6a43a-125">**Note**: If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="6a43a-126">Til að ógilda prentaðan tékka sem ekki eru bókaðar</span><span class="sxs-lookup"><span data-stu-id="6a43a-126">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="6a43a-127">Hægt er að ógilda tékka sem eftir á að bóka þegar þær hafa verið prentuð með því að nota **Ógilda Tékka** aðgerð í á **greiðslubók** glugga.</span><span class="sxs-lookup"><span data-stu-id="6a43a-127">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>
1. <span data-ttu-id="6a43a-128">Í á **greiðslubókarglugga** er valið á **Ógilda Tékka**, og síðan valið hvaða tékka á að ógilda.</span><span class="sxs-lookup"><span data-stu-id="6a43a-128">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="6a43a-129">Tékkar ógiltir:</span><span class="sxs-lookup"><span data-stu-id="6a43a-129">To void checks</span></span>
<span data-ttu-id="6a43a-130">Þegar tékkagreiðslur hafa verið bókaðar, geturðu aðeins afturkallað (ógilt) tékka úr bankafærslum sem fengust út úr þessu.</span><span class="sxs-lookup"><span data-stu-id="6a43a-130">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="6a43a-131">Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.</span><span class="sxs-lookup"><span data-stu-id="6a43a-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="6a43a-132">Veldu viðeigandi bankareikning, veldu **breyta** aðgerðina og veldu síðan **tékkafærslur** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="6a43a-132">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="6a43a-133">Í **tékkafærslur** glugganum, veldu **ógilda tékka** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="6a43a-133">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="6a43a-134">Veldu gátreitinn **eingöngu ógilda tékka**.</span><span class="sxs-lookup"><span data-stu-id="6a43a-134">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="6a43a-135">Veldu hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="6a43a-135">Choose the **OK**button.</span></span>

## <a name="see-also"></a><span data-ttu-id="6a43a-136">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="6a43a-136">See Also</span></span>
[<span data-ttu-id="6a43a-137">Umsjón viðskiptaskulda</span><span class="sxs-lookup"><span data-stu-id="6a43a-137">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="6a43a-138">Uppsetning bankaþjónustu</span><span class="sxs-lookup"><span data-stu-id="6a43a-138">Set Up Banking</span></span>](bank-setup-banking.md)  

