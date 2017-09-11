---
title: "Hvernig á að: Vinna með GIFI kóða í Kanada"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a><span data-ttu-id="e8f31-102">Hvernig á að: Vinna með GIFI kóða í Kanada</span><span class="sxs-lookup"><span data-stu-id="e8f31-102">How to: Work With GIFI Codes in Canada</span></span>
<span data-ttu-id="e8f31-103">Fjárhagsupplýsingar geta innihaldið fjárhagsreikninga, skýrslur, rekstrarreikninga, efnahagsreikninga og yfirlit yfir óráðstafað eigið fé.</span><span class="sxs-lookup"><span data-stu-id="e8f31-103">Fiscal information can include general ledger accounts, reports, income statements, balance sheets, and statements of retained earnings.</span></span> <span data-ttu-id="e8f31-104">Fjárhagsupplýsingar eru flokkaðar með kóðum.</span><span class="sxs-lookup"><span data-stu-id="e8f31-104">Fiscal information is classified using codes.</span></span> <span data-ttu-id="e8f31-105">Notkun kóða hjálpar hinu opinbera að vinna upplýsingar, undirbúa rafræn skattskil og staðfesta upplýsingar um skatta rafrænt.</span><span class="sxs-lookup"><span data-stu-id="e8f31-105">The use of codes helps the government to process information, prepare for electronic filing, and validate tax information electronically.</span></span> <span data-ttu-id="e8f31-106">Notkun kóða auðveldar einnig hagstofum og slíkum stofnunum vinnuna, þar sem fjárhagsupplýsingar eru aðgengilegri.</span><span class="sxs-lookup"><span data-stu-id="e8f31-106">The use of codes also helps statistical organizations to work more efficiently, as financial information is more readily available.</span></span> <span data-ttu-id="e8f31-107">Nánari upplýsingar eru á vefsíðu [Tekjuskrifstofu Kanada](http://www.cra-arc.gc.ca/).</span><span class="sxs-lookup"><span data-stu-id="e8f31-107">For more information, see the [Canada Revenue Agency website](http://www.cra-arc.gc.ca/).</span></span>

<span data-ttu-id="e8f31-108">Tekjuskrifstofa Kanada notar kóða úr Almennri atriðaskrá um fjárhagsupplýsingar (General Index of Financial Information, GIFI) til að safna saman, sannprófa, og vinna ársreikninga og vsk-upplýsingar rafrænt.</span><span class="sxs-lookup"><span data-stu-id="e8f31-108">The Canada Revenue Agency uses General Index of Financial Information (GIFI) codes to collect, validate, and process financial and tax information electronically.</span></span> <span data-ttu-id="e8f31-109">Það er best að úthluta GIFI kóðum aðeins á bókunarreikninga, til þess að allar samtölur séu gerðar af hugbúnaðinum sem notaður er fyrir undirbúning vsk-skatts.</span><span class="sxs-lookup"><span data-stu-id="e8f31-109">It is a best practice to assign GIFI codes only to posting accounts, so that all totaling is done by your tax preparation software.</span></span>

<span data-ttu-id="e8f31-110">Þegar reikningur er tengdur GIFI kóða er hann skráður í tekjuskrifstofunni undir þeim kóða.</span><span class="sxs-lookup"><span data-stu-id="e8f31-110">When an account is associated with a GIFI code, it is reported to the revenue agency under that code.</span></span> <span data-ttu-id="e8f31-111">Margir sameinaðir reikningar geta haft sama GIFI kóða, en hver reikningur getur aðeins haft einn GIFI kóða.</span><span class="sxs-lookup"><span data-stu-id="e8f31-111">Multiple accounts can all have the same GIFI code, but each account can have only one GIFI code.</span></span>

<span data-ttu-id="e8f31-112">Hægt er að flytja út upplýsingar um stöðu eftir GIFI kóða og vista útfluttu skrána í Excel, sem er gagnlegt við að flytja upplýsingar til hugbúnaðarins sem notaður er fyrir undirbúning vsk-skatts.</span><span class="sxs-lookup"><span data-stu-id="e8f31-112">You can export balance information by GIFI code and save the exported file in Excel, which is useful for transferring information to your tax preparation software.</span></span>

## <a name="to-set-up-gifi-codes"></a><span data-ttu-id="e8f31-113">Uppsetning GIFI kóða</span><span class="sxs-lookup"><span data-stu-id="e8f31-113">To set up GIFI codes</span></span>
<span data-ttu-id="e8f31-114">Í Dynamics NAV þarf að setja upp GIFI kóða fyrir fjárhagsreikninga, skýrslur, efnahagsreikninga, tekjureikninga og yfirlit yfir óráðstafað eigið fé.</span><span class="sxs-lookup"><span data-stu-id="e8f31-114">In Dynamics NAV, you must set up GIFI codes for general ledger accounts, reports, balance sheets, income sheets, and statements of retained earnings.</span></span>

1. <span data-ttu-id="e8f31-115">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **GIFI kóða**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e8f31-115">In the top right corner, choose the **Search for Page or Report** icon, enter **GIFI Codes**, and then choose the related link.</span></span>
2. <span data-ttu-id="e8f31-116">Í glugganum **GIFI kóðar** skal velja aðgerðina **Nýtt**.</span><span class="sxs-lookup"><span data-stu-id="e8f31-116">In the **GIFI Codes** window, choose the **New** action.</span></span>
3. <span data-ttu-id="e8f31-117">Setjið upp GIFI kóða með því að fylla í reitina.</span><span class="sxs-lookup"><span data-stu-id="e8f31-117">Set up GIFI codes by filling the fields.</span></span> <span data-ttu-id="e8f31-118">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="e8f31-118">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-associate-gifi-codes-with-gl-accounts"></a><span data-ttu-id="e8f31-119">Til að tengja GIFI kóða við fjárhagsreikninga</span><span class="sxs-lookup"><span data-stu-id="e8f31-119">To associate GIFI codes with G/L accounts</span></span>
<span data-ttu-id="e8f31-120">Til að tilkynna fjárhagslegar upplýsingar eftir GIFI kóða þarf hver GIFI kóði að vera tengdur við viðeigandi reikninga í bókhaldslyklinum.</span><span class="sxs-lookup"><span data-stu-id="e8f31-120">To report financial information by GIFI code, each GIFI code must be associated with the appropriate accounts in the chart of accounts.</span></span>

1. <span data-ttu-id="e8f31-121">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **bókhaldslykill**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e8f31-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="e8f31-122">Veljið viðeigandi fjárhagsreikning og veljið svo aðgerðina **Breyta**.</span><span class="sxs-lookup"><span data-stu-id="e8f31-122">Select a relevant general ledger account, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="e8f31-123">Í flýtiflipanum **Kostnaðarbókhald** í svæðinu **GIFI kóði** er viðeigandi GIFI kóði valinn.</span><span class="sxs-lookup"><span data-stu-id="e8f31-123">On the **Cost Accounting** FastTab, in the **GIFI Code** field, select an appropriate GIFI code.</span></span>

## <a name="to-view-account-balances-using-the-gifi-code-report"></a><span data-ttu-id="e8f31-124">Til að skoða reikningsstöður með GIFI kóða skýrslunni.</span><span class="sxs-lookup"><span data-stu-id="e8f31-124">To view account balances using the GIFI code report</span></span>
<span data-ttu-id="e8f31-125">Hægt er að skoða stöðu reikninga eftir GIFI kóða með því að nota skýrsluna **Staða reikninga eftir GIFI kóða**.</span><span class="sxs-lookup"><span data-stu-id="e8f31-125">You can review your account balances by GIFI code by using the **Account Balances by GIFI Code** report.</span></span>

1. <span data-ttu-id="e8f31-126">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Staða reikninga eftir GIFI kóða**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e8f31-126">In the top right corner, choose the **Search for Page or Report** icon, enter **Account Balances by GIFI Code**, and then choose the related link.</span></span>
2. <span data-ttu-id="e8f31-127">Tilgreina þarf hvað eigi að taka með í skýrslunni með því að fylla í reitina.</span><span class="sxs-lookup"><span data-stu-id="e8f31-127">Specify what to include in the report by filling the fields.</span></span> <span data-ttu-id="e8f31-128">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="e8f31-128">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="e8f31-129">Veljið hnappinn **Prenta** eða **Forskoðun**.</span><span class="sxs-lookup"><span data-stu-id="e8f31-129">Choose the **Print** or the **Preview** button.</span></span>

## <a name="to-export-balance-information-using-gifi-codes"></a><span data-ttu-id="e8f31-130">Til að flytja út reikningsupplýsingar með því að nota GIFI kóða</span><span class="sxs-lookup"><span data-stu-id="e8f31-130">To export balance information using GIFI codes</span></span>
<span data-ttu-id="e8f31-131">Hægt er að flytja út reikningsupplýsingar með því að nota GIFI kóða og vista útfluttu skrána í Excel.</span><span class="sxs-lookup"><span data-stu-id="e8f31-131">You can export balance information using GIFI codes and save the exported file in Excel.</span></span> <span data-ttu-id="e8f31-132">Hægt er að breyta, vista eða eyða skrám.</span><span class="sxs-lookup"><span data-stu-id="e8f31-132">You can modify, save, or delete the file.</span></span> <span data-ttu-id="e8f31-133">Skrána má nota til að flytja upplýsingar til hugbúnaðarins sem notaður er fyrir undirbúning vsk-skatts.</span><span class="sxs-lookup"><span data-stu-id="e8f31-133">You can use the file to transfer information to your tax preparation software.</span></span>

1. <span data-ttu-id="e8f31-134">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Flytja GIFI upplýsingar í Excel**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="e8f31-134">In the top right corner, choose the **Search for Page or Report** icon, enter **Export GIFI Info. to Excel**, and then choose the related link.</span></span>
2. <span data-ttu-id="e8f31-135">Skilgreina þarf hvað eigi að flytja út í Excel með því að fylla í reitina.</span><span class="sxs-lookup"><span data-stu-id="e8f31-135">Specify what to export to Excel by filling the fields.</span></span> <span data-ttu-id="e8f31-136">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="e8f31-136">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="e8f31-137">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="e8f31-137">Choose the **OK** button.</span></span>

<span data-ttu-id="e8f31-138">**Athugasemd:** Excel-skráin hefur eftirfarandi einkenni:</span><span class="sxs-lookup"><span data-stu-id="e8f31-138">**Note:** The Excel file has the following characteristics:</span></span>

* <span data-ttu-id="e8f31-139">Staðan er sléttuð í næstu prósentu en gildi reitsins viðheldur sömu prósentu og í fjárhag.</span><span class="sxs-lookup"><span data-stu-id="e8f31-139">The balance is rounded to the nearest percentage, but the cell value maintains the same percentage as it does in the general ledger.</span></span>

* <span data-ttu-id="e8f31-140">Neikvæð númer eru sýnd sem jákvæð númer í svigum.</span><span class="sxs-lookup"><span data-stu-id="e8f31-140">Negative numbers are represented as positive number in brackets.</span></span> <span data-ttu-id="e8f31-141">Í samræmi við það er talan -123 sýnd sem (123).</span><span class="sxs-lookup"><span data-stu-id="e8f31-141">Accordingly, -123 is represented as (123).</span></span>

## <a name="see-also"></a><span data-ttu-id="e8f31-142">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="e8f31-142">See Also</span></span>
<span data-ttu-id="e8f31-143">[Fjármál](finance-setup.md) </span><span class="sxs-lookup"><span data-stu-id="e8f31-143">[Finance](finance-setup.md) </span></span>  
[<span data-ttu-id="e8f31-144">Setja upp kjarnafjárhagsferli</span><span class="sxs-lookup"><span data-stu-id="e8f31-144">Set Up Core Financial Processes</span></span>](finance-setup-setup-finance-setup.md)

