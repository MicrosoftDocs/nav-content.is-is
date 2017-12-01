---
title: "Flytja út jákvæðar greiðsluskrár"
description: "Hægt er að ganga úr skugga um að bankinn þinn taki eingöngu við fullgildum ávísunum með því að flytja út jákvæða greiðsluskrá sem inniheldur upplýsingar um lánardrottna og greiðslur."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: check, clearing
ms.date: 06/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 44e027a1c80c30e748773f12c5d74fc7c3763b3e
ms.contentlocale: is-is
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-export-a-positive-pay-file"></a><span data-ttu-id="b5a2a-103">Hvernig á að: flytja út jákvæða greiðsluskrá</span><span class="sxs-lookup"><span data-stu-id="b5a2a-103">How to: Export a Positive Pay file</span></span>
<span data-ttu-id="b5a2a-104">Til að ganga úr skugga um að bankinn þinn eingöngu taki til fullgiltar athuganir og fjárhæðir getur þú flutt greiðslubréf sem inniheldur upplýsingar um söluaðila, athuga fjölda og greiðslu upphæð sem þú sendir til bankans til viðmiðunar þegar þú vinnur greiðslur.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-104">To make sure that your bank only clears validated checks and amounts, you can export a Positive Pay file that contains vendor information, check number, and payment amount, which you send to the bank for reference when you process payments.</span></span>

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="b5a2a-105"> er forstillt á að styðja jákvæðar greiðsluskrár fyrir Bank of America og City Bank.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-105"> is preconfigured to support Positive Pay files for Bank of America and City Bank.</span></span>

## <a name="to-set-up-a-bank-account-for-positive-pay"></a><span data-ttu-id="b5a2a-106">Að setja upp bankareikning fyrir Positive Pay</span><span class="sxs-lookup"><span data-stu-id="b5a2a-106">To set up a bank account for Positive Pay</span></span>
1. <span data-ttu-id="b5a2a-107">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bankareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="b5a2a-108">Opnaðu kortið fyrir bankann sem þú vilt nota Jákvæð Borga fyrir.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-108">Open the card for the bank that you want to use Positive Pay for.</span></span>
3. <span data-ttu-id="b5a2a-109">Sláðu inn POSPAYBANK í reitnum **Útflutningskóði jákvæðrar greiðslu**.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-109">In the **Positive Pay Export Code** field, enter POSPAYBANK.</span></span>
4. <span data-ttu-id="b5a2a-110">Glugganum er lokað.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-110">Close the window.</span></span>

## <a name="to-export-a-positive-pay-file"></a><span data-ttu-id="b5a2a-111">Til að flytja út jákvæða greiðsluskrá</span><span class="sxs-lookup"><span data-stu-id="b5a2a-111">To export a Positive Pay file</span></span>
1. <span data-ttu-id="b5a2a-112">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bankareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="b5a2a-113">Veldu bankareikninginn sem þú vilt flytja út jákvæð greiðsluskilríki fyrir.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-113">Select the bank account that you want to export a Positive Pay file for.</span></span>
3. <span data-ttu-id="b5a2a-114">Veldu **Útflutningur jákvæðrar greiðslu** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-114">Choose **Positive Pay Export** action.</span></span>

    <span data-ttu-id="b5a2a-115">Gluggi með **jákvæðu greiðslumiðlun** opnast með því að birta greiðslur sem hafa verið gerðar á bankareikningnum frá síðasta upphleðsludegi, eins og sýnt er í **Síðasti dagur** og **Siðast hlaðið inn**.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-115">The **Positive Pay Export** window opens displaying payments that have been made for the bank account since the last upload date, as shown in the **Last Upload Date** and **Last Upload Time** fields.</span></span>
4. <span data-ttu-id="b5a2a-116">Tilgreindu **Lokadagsetning upphleðslu** áður en greiðsla er ekki innifalin í útfluttri skrá í Afhendingarsímabilinu.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-116">In the **Cutoff Upload Date** field, specify a date before which payments are not included in the exported file.</span></span>
5. <span data-ttu-id="b5a2a-117">Veldu **Export** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-117">Choose the **Export** action.</span></span>
6. <span data-ttu-id="b5a2a-118">Í glugganum **Flytja út skrá** skaltu velja **Vista** hnappinn og síðan vistaðu skrána á þægilegan stað.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-118">In the **Export File** window, choose the **Save** button, and then save the file to a convenient location.</span></span>
7. <span data-ttu-id="b5a2a-119">Hladdu skránni í rafræna bankasíða þína.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-119">Upload the file to your electronic bank site.</span></span>
8. <span data-ttu-id="b5a2a-120">Skrifaðu niður eða afritaðu staðfestingarnúmerið sem birtist þegar skráarupphæðin tekst vel.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-120">Write down or copy the confirmation number that is displayed when the file upload is successful.</span></span>

<span data-ttu-id="b5a2a-121">Til að skoða útfluttar jákvæðar greiðslur</span><span class="sxs-lookup"><span data-stu-id="b5a2a-121">To view exported Positive Pay records</span></span>

1. <span data-ttu-id="b5a2a-122">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bankareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="b5a2a-123">Veldu bankareikninginn sem þú vilt skoða.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-123">Select the bank account that you want to view Positive Pay export records for.</span></span>
3. <span data-ttu-id="b5a2a-124">Veldu aðgerðina **Jákvæðar greiðslufærslur**.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-124">Choose the **Positive Pay Entries** action.</span></span>

    <span data-ttu-id="b5a2a-125">Í glugganum **Jákvæðar greiðslufærslur** er hægt að sjá allar greiðslur fyrir jákvæð greiðsla fyrir bankareikninginn.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-125">In the **Positive Pay Entries** window, you can see all the Positive Pay export records for the bank account.</span></span>
4. <span data-ttu-id="b5a2a-126">Í **Staðfestingarnúmer** skaltu slá inn, fyrir hvern útflutningsskrá, staðfestingarnúmerið sem þú færð þegar skráarupphæðin til bankans hefur náð árangri.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-126">In the **Confirmation Number** field, enter, for each export record, the confirmation number that you receive when the file upload to the bank is successful.</span></span>
5. <span data-ttu-id="b5a2a-127">Til að skoða tengda greiðslulínur skaltu velja aðgerðina **Sundurliðun færslu á jákvæðri greiðslu**.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-127">To view the related payment lines, choose the **Positive Pay Entry Details** action.</span></span>

<span data-ttu-id="b5a2a-128">Til að flytja út jákvæðar greiðslur</span><span class="sxs-lookup"><span data-stu-id="b5a2a-128">To reexport Positive Pay files</span></span>

1. <span data-ttu-id="b5a2a-129">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bankareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-129">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="b5a2a-130">Veldu bankareikninginn sem þú vilt endurútgefa jákvæð greiðslur fyrir.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-130">Select the bank account that you want to reexport Positive Pay files for.</span></span>
3. <span data-ttu-id="b5a2a-131">Veldu aðgerðina **Jákvæðar greiðslufærslur**.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-131">Choose the **Positive Pay Entries** action.</span></span>
4. <span data-ttu-id="b5a2a-132">Veldu línuna fyrir útflutningsskrána fyrir jákvæð greiðsla sem þú vilt endurútgefa.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-132">Select the line for the Positive Pay export file that you want to reexport.</span></span>
5. <span data-ttu-id="b5a2a-133">Í reitnum **Jákvæðar greiðslur** skaltu velja **Endurútflytja jákvæðar greiðslur** í skrá aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="b5a2a-133">In the **Positive Pay Entries** window, choose the **Reexport Positive Pay to File** action.</span></span>

## <a name="see-also"></a><span data-ttu-id="b5a2a-134">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="b5a2a-134">See Also</span></span>
[<span data-ttu-id="b5a2a-135">Fjármál</span><span class="sxs-lookup"><span data-stu-id="b5a2a-135">Finance</span></span>](finance.md)  
[<span data-ttu-id="b5a2a-136">Uppsetning Fjármála</span><span class="sxs-lookup"><span data-stu-id="b5a2a-136">Setting Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="b5a2a-137">Vinna í færslubókum</span><span class="sxs-lookup"><span data-stu-id="b5a2a-137">Working with General Journals</span></span>](ui-work-general-journals.md)  
<span data-ttu-id="b5a2a-138">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b5a2a-138">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

