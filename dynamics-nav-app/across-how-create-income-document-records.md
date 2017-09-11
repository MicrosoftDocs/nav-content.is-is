---
title: "Hvernig á að stofna skjöl á innleið"
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
ms.openlocfilehash: e91c4570ff60d991974ac6afd16ba3bc3e73e44f
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-create-incoming-document-records"></a><span data-ttu-id="94f14-102">Hvernig á að stofna skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="94f14-102">How to: Create Incoming Document Records</span></span>
<span data-ttu-id="94f14-103">Í glugganum **Skjöl á innleið** er hægt að nota ólíkar aðgerðir til að yfirfara kostnaðarkvittanir, sýsla með OCR-verk og breyta skjölum á innleið, handvirkt eða sjálfvirkt, yfir í viðkomandi skjöl eða færslubókarlínur í.</span><span class="sxs-lookup"><span data-stu-id="94f14-103">In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="94f14-104">Ytri skrárnar er hægt að hengja við tengd skjöl á öllum stigum úrvinnslunnar, þ.m.t. við bókuð skjöl og við færslur lánardrottins, viðskiptamanns eða fjárhags sem verða til.</span><span class="sxs-lookup"><span data-stu-id="94f14-104">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span>

<span data-ttu-id="94f14-105">Til að skrá ytra skjal í Dynamics NAV verður fyrst að stofna eða ljúka við færsla skjal á innleið.</span><span class="sxs-lookup"><span data-stu-id="94f14-105">To record an external document in Dynamics NAV, you must first create or complete an incoming document record.</span></span> <span data-ttu-id="94f14-106">Þú getur gert þetta með handvirkt, eða þú getur tekið mynd af ytra skjal og síðan að búa til skjal á innleið með myndaskrá í viðhengi.</span><span class="sxs-lookup"><span data-stu-id="94f14-106">You can do this manually, or you can take a photo of the external document and then create the incoming document record with the image file attached.</span></span>

<span data-ttu-id="94f14-107">Áður en hægt er að nota valkostinn Skjöl á innleið þarf að framkvæma áskilda uppsetningu.</span><span class="sxs-lookup"><span data-stu-id="94f14-107">Before you can use the Incoming Documents feature, you must perform the required setup.</span></span> <span data-ttu-id="94f14-108">Nánari upplýsingar er að finna í [Hvernig á að setja upp skjöl á innleið](across-how-setup-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="94f14-108">For more information, see [How to: Set Up Incoming Documents](across-how-setup-income-documents.md).</span></span>

## <a name="to-approve-or-reject-an-incoming-document"></a><span data-ttu-id="94f14-109">Til að samþykkja eða hafna fylgiskjali á innleið</span><span class="sxs-lookup"><span data-stu-id="94f14-109">To approve or reject an incoming document</span></span>
<span data-ttu-id="94f14-110">Ef notendur eiga að geta stofnað reikninga eða færslubókarlínur úr færslum skjala á innleið nema skjöl séu fyrst samþykkt er hægt að setja upp samþykkjendur sem verða að samþykkja færslur áður en þær má vinna.</span><span class="sxs-lookup"><span data-stu-id="94f14-110">If you do want to allow users to create invoices or general journal lines from incoming document records unless they are approved, you can set up approvers who must approve the records before they can be processed.</span></span>

1. <span data-ttu-id="94f14-111">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skjöl á innleið**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="94f14-111">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="94f14-112">Valin er línan með skjalinu sem á að samþykkja eða hafna og síðan valið á **Samþykkja** eða **Hafna** aðgerðir.</span><span class="sxs-lookup"><span data-stu-id="94f14-112">Select the line with the document that you want to approve or reject, and then choose the **Approve** or **Reject** actions.</span></span>

<span data-ttu-id="94f14-113">Ef færsla skjals á innleið er samþykkt er gátreiturinn **Losað** á línu skjal á innleið valinn.</span><span class="sxs-lookup"><span data-stu-id="94f14-113">If you approve the incoming document record, the **Released** check box on the incoming document line is selected.</span></span> <span data-ttu-id="94f14-114">Notandi sem stjórnar t.d. stofnun innkaupareikninga getur haldið áfram að vinna úr færslunni.</span><span class="sxs-lookup"><span data-stu-id="94f14-114">The user in charge of creating, for example, purchase invoices can proceed to process the record.</span></span>

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="94f14-115">Til að stofna færslur skjala á innleið með því að taka mynd</span><span class="sxs-lookup"><span data-stu-id="94f14-115">To create an incoming document record by taking a photo</span></span>
<span data-ttu-id="94f14-116">**Athugið**: Eftirfarandi ferli á aðeins við um Dynamics NAV hvað varðar spjaldtölvu- og símaviðskiptavini.</span><span class="sxs-lookup"><span data-stu-id="94f14-116">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="94f14-117">Á forritastikunni skal velja **Stofna skjal á innleið úr myndavél** reitinn og fara svo í skref 4..</span><span class="sxs-lookup"><span data-stu-id="94f14-117">On the app bar, choose the **Create Incoming Document from Camera** tile, and then go to step 4.</span></span>
2. <span data-ttu-id="94f14-118">Að öðrum kosti skal á forritastikunni velja valkostahnappinn, velja **Skjöl á innleið** og velja svo **Öll**.</span><span class="sxs-lookup"><span data-stu-id="94f14-118">Alternatively, on the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
3. <span data-ttu-id="94f14-119">Í glugganum **Skjöl á innleið** skal velja úrfellingarmerkishnappinn og svo **Stofna úr myndavél**.</span><span class="sxs-lookup"><span data-stu-id="94f14-119">In the **Incoming Documents** window, choose the ellipsis button, and then choose **Create from Camera**.</span></span> <span data-ttu-id="94f14-120">Kveikt er á myndavél spjaldtölvu eða síma.</span><span class="sxs-lookup"><span data-stu-id="94f14-120">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="94f14-121">Takið mynd af skjali, t.d. innkaupakvittun, sem á að vinna sem skjal á innleið, og veljið svo hnappur **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="94f14-121">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="94f14-122">Ný færsla skjals á innleið er stofnað með mynd í viðhengi.</span><span class="sxs-lookup"><span data-stu-id="94f14-122">A new incoming document record is created, with the image attached.</span></span>

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="94f14-123">Til að hengja mynd við skjal á innleið færsla með því að taka mynd</span><span class="sxs-lookup"><span data-stu-id="94f14-123">To attach an image to an incoming document record by taking a photo</span></span>
<span data-ttu-id="94f14-124">**Athugið**: Eftirfarandi ferli á aðeins við um Dynamics NAV hvað varðar spjaldtölvu- og símaviðskiptavini.</span><span class="sxs-lookup"><span data-stu-id="94f14-124">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="94f14-125">Á forritastikunni velja valkostahnappinn, velja **Skjöl á innleið** og velja svo **Öll**.</span><span class="sxs-lookup"><span data-stu-id="94f14-125">On the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
2. <span data-ttu-id="94f14-126">Opnið kort fyrir fyrirliggjandi færsla skjal á innleið.</span><span class="sxs-lookup"><span data-stu-id="94f14-126">Open the card for an existing incoming document record.</span></span>
3. <span data-ttu-id="94f14-127">Í glugganum **Skjal á innleið** skal velja úrfellingarmerkishnappinn og svo **Hengja við mynd úr myndavél**.</span><span class="sxs-lookup"><span data-stu-id="94f14-127">In the **Incoming Document** window, choose the ellipsis button, and then choose **Attach Image from Camera**.</span></span> <span data-ttu-id="94f14-128">Kveikt er á myndavél spjaldtölvu eða síma.</span><span class="sxs-lookup"><span data-stu-id="94f14-128">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="94f14-129">Takið mynd af skjali, t.d. innkaupakvittun, sem á að vinna sem skjal á innleið, og veljið svo hnappur **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="94f14-129">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="94f14-130">Myndin er hengja við færsla skjal á innleið.</span><span class="sxs-lookup"><span data-stu-id="94f14-130">The image is attached to the incoming document record.</span></span>

## <a name="to-create-an-incoming-document-record-manually"></a><span data-ttu-id="94f14-131">Tila ð búa til færslu skjals á innleið handvirkt</span><span class="sxs-lookup"><span data-stu-id="94f14-131">To create an incoming document record manually</span></span>
1. <span data-ttu-id="94f14-132">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skjöl á innleið**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="94f14-132">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="94f14-133">Aðgerðin **Stofna úr Skrá** er valin.</span><span class="sxs-lookup"><span data-stu-id="94f14-133">Choose the **Create from File** action.</span></span>  
3. <span data-ttu-id="94f14-134">Í glugganum **Setja inn skrá** skal velja skrána sem táknar skjalið á innleið og svo hnappinn **Opna**.</span><span class="sxs-lookup"><span data-stu-id="94f14-134">In the **Insert File** window, select a file, and then choose **Open**.</span></span>

    <span data-ttu-id="94f14-135">Skráin er hengd við sjálfkrafa.</span><span class="sxs-lookup"><span data-stu-id="94f14-135">The file is automatically attached.</span></span>
4. <span data-ttu-id="94f14-136">Einnig er hægt að velja aðgerðina **Nýtt**.</span><span class="sxs-lookup"><span data-stu-id="94f14-136">Alternatively, choose the **New** action.</span></span>
5. <span data-ttu-id="94f14-137">Ef tengja á skrá, skal velja **Tengja Skrá** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="94f14-137">To attach a file, choose the **Attach File** action.</span></span>
6. <span data-ttu-id="94f14-138">Í glugganum **Setja inn skrá** skal velja skrána sem táknar skjalið á innleið og svo hnappinn **Opna**.</span><span class="sxs-lookup"><span data-stu-id="94f14-138">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>
7. <span data-ttu-id="94f14-139">Í glugganum **Skjal á innleið** þarf að fylla reitina út eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="94f14-139">In the **Incoming Document** window, fill in the fields as necessary.</span></span> <span data-ttu-id="94f14-140">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="94f14-140">Choose a field to read a short description of the field or link to more information.</span></span>

##<a name="see-also"></a><span data-ttu-id="94f14-141">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="94f14-141">See Also</span></span>  
[<span data-ttu-id="94f14-142">Vinnsla skjala á innleið</span><span class="sxs-lookup"><span data-stu-id="94f14-142">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="94f14-143">Skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="94f14-143">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="94f14-144">Stjórnun innkaupa</span><span class="sxs-lookup"><span data-stu-id="94f14-144">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="94f14-145">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="94f14-145">Work With Dynamics NAV</span></span>](ui-work-product.md)

