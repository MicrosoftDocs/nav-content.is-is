---
title: "Hvernig á að: Setja upp skjöl á innleið"
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
ms.openlocfilehash: d55329b571e4c59d4821a86a39362ea58480b86a
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="d7efe-102">Hvernig á að: Setja upp skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="d7efe-102">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="d7efe-103">Ef stofnaðar eru færslubókarlínur úr færslum skjala á innleið verður að tilgreina í í glugganum **Uppsetning fyrir skjöl á innleið** hvaða sniðmát færslubókar og runu á að nota.</span><span class="sxs-lookup"><span data-stu-id="d7efe-103">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="d7efe-104">Ef notendur eiga ekki að geta stofnað reikninga eða færslubókarlínur úr færslum skjala á innleið nema skjöl séu fyrst samþykkt verður að setja upp samþykkjendur í glugganum **Samþykkjendur skjala á innleið**.</span><span class="sxs-lookup"><span data-stu-id="d7efe-104">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="d7efe-105">Til að Breyta PDF og myndaskrám í rafræn skjöl sem er hægt að breyta í, til dæmis innkaup reikninga innkaupareikninga innan Dynamics NAV, verður að fyrst að setja upp eiginleikann OCR og virkja þjónustu.</span><span class="sxs-lookup"><span data-stu-id="d7efe-105">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="d7efe-106">Þegar eiginleikinn Skjöl á innleið er uppsettur, er hægt að nota ólíkar aðgerðir til að yfirfara kostnaðarkvittanir, sýsla með OCR-verk og breyta skjölum á innleið, handvirkt eða sjálfvirkt, yfir í viðkomandi skjöl eða færslubókarlínur.</span><span class="sxs-lookup"><span data-stu-id="d7efe-106">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="d7efe-107">Ytri skrárnar er hægt að hengja við tengd skjöl á öllum stigum úrvinnslunnar, þ.m.t. við bókuð skjöl og við færslur lánardrottins, viðskiptamanns eða fjárhags sem verða til.</span><span class="sxs-lookup"><span data-stu-id="d7efe-107">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="d7efe-108">Nánari upplýsingar er að finna í [Hvernig á að vinna skjöl á innleið](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="d7efe-108">For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="d7efe-109">Setja upp valkostinn fyrir skjal á innleið</span><span class="sxs-lookup"><span data-stu-id="d7efe-109">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="d7efe-110">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning skjala á innleið**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d7efe-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="d7efe-111">Fyllið inn í svæðin eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="d7efe-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="d7efe-112">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="d7efe-112">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="d7efe-113">Að setja upp samþykkjendur fyrir skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="d7efe-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="d7efe-114">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning skjala á innleið**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d7efe-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d7efe-115">Í glugganum **Skjal á innleið** skal velja aðgerðina **Samþykkjendur**</span><span class="sxs-lookup"><span data-stu-id="d7efe-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="d7efe-116">Glugginn **Samþykkjendur skjala á innleið** sýnir alla notendur sem hafa verið settir upp í Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="d7efe-116">The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .</span></span>  
3. <span data-ttu-id="d7efe-117">Veldu einn eða fleiri notendur sem geta samþykkt innsent skjal áður en hægt er að stofna fylgiskjals - eða bókarlínu.</span><span class="sxs-lookup"><span data-stu-id="d7efe-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="d7efe-118">Þegar samþykkjendur hafa verið settir upp í glugganum **Samþykkjendur skjala á innleið** geta aðeins þessir notendur samþykkt skjal á innleið ef gátreitur **Krefjast samþykkis fyrir stofnun** í glugganum **uppsetning skjala á innleið** er valinn.</span><span class="sxs-lookup"><span data-stu-id="d7efe-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

<span data-ttu-id="d7efe-119">**Athugasemd**: þessi uppsetning samþykkis er ekki tengt samþykktarverkflæðum.</span><span class="sxs-lookup"><span data-stu-id="d7efe-119">**Note**: This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="d7efe-120">Nánari upplýsingar sjá [hvernig á að: nota Samþykkisverkflæði](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="d7efe-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="d7efe-121">Til að setja upp OCR-þjónustu</span><span class="sxs-lookup"><span data-stu-id="d7efe-121">To set up an OCR service</span></span>
1. <span data-ttu-id="d7efe-122">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning OCR-þjónustu**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d7efe-122">In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="d7efe-123">Fyllið inn í svæðin eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="d7efe-123">Fill in the fields as necessary.</span></span> <span data-ttu-id="d7efe-124">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="d7efe-124">Choose a field to read a short description of the field or link to more information.</span></span>


## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="d7efe-125">Til að dulrita innskráningarupplýsingar</span><span class="sxs-lookup"><span data-stu-id="d7efe-125">To encrypt your login information</span></span>
<span data-ttu-id="d7efe-126">Mælt er með því að vernda innskráningarupplýsingar sem slegnar eru inn í **uppsetning OCR-þjónustu** gluggann.</span><span class="sxs-lookup"><span data-stu-id="d7efe-126">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="d7efe-127">Hægt er að dulrita gögn á  netþjóninum með því að stofna nýjan dulritunarlykil eða flytja inn fyrirliggjandi lykla sem eru virkjaðir er á netþjónstilviki sem tengist við gagnagrunninn.</span><span class="sxs-lookup"><span data-stu-id="d7efe-127">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="d7efe-128">Í **uppsetning fyrir OCR-þjónusta** glugganum, veldu **stjórnun dulritunar**.</span><span class="sxs-lookup"><span data-stu-id="d7efe-128">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="d7efe-129"> Í glugganum **gagnadulritun**, virkja dulritun gagnanna.</span><span class="sxs-lookup"><span data-stu-id="d7efe-129">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="d7efe-130">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="d7efe-130">See Also</span></span>  
[<span data-ttu-id="d7efe-131">Vinnsla skjala á innleið</span><span class="sxs-lookup"><span data-stu-id="d7efe-131">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="d7efe-132">Skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="d7efe-132">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="d7efe-133">Stjórnun innkaupa</span><span class="sxs-lookup"><span data-stu-id="d7efe-133">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="d7efe-134">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="d7efe-134">Work With Dynamics NAV</span></span>](ui-work-product.md)

