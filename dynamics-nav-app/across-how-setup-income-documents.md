---
title: "Setja upp skjöl á innleið"
description: "Nota eiginleikann Skjöl á innleið til að stofna rafræn skjöl, stjórna OCR-verkum, flytja inn reikninga og umbreyta myndaskrám."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 80c57f6a332ace58941929811e3f3a9b1f156028
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="f6713-103">Hvernig á að: Setja upp skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="f6713-103">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="f6713-104">Ef stofnaðar eru færslubókarlínur úr færslum skjala á innleið verður að tilgreina í í glugganum **Uppsetning fyrir skjöl á innleið** hvaða sniðmát færslubókar og runu á að nota.</span><span class="sxs-lookup"><span data-stu-id="f6713-104">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="f6713-105">Ef notendur eiga ekki að geta stofnað reikninga eða færslubókarlínur úr færslum skjala á innleið nema skjöl séu fyrst samþykkt verður að setja upp samþykkjendur í glugganum **Samþykkjendur skjala á innleið**.</span><span class="sxs-lookup"><span data-stu-id="f6713-105">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="f6713-106">Til að breyta PDF og myndaskrám í rafræn skjöl sem er hægt að breyta í til dæmis innkaupareikninga innan [!INCLUDE[d365fin](includes/d365fin_md.md)], verður að fyrst að setja upp eiginleikann OCR og virkja þjónustuna.</span><span class="sxs-lookup"><span data-stu-id="f6713-106">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside [!INCLUDE[d365fin](includes/d365fin_md.md)], you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="f6713-107">Þegar eiginleikinn Skjöl á innleið er uppsettur, er hægt að nota ólíkar aðgerðir til að yfirfara kostnaðarkvittanir, sýsla með OCR-verk og breyta skjölum á innleið, handvirkt eða sjálfvirkt, yfir í viðkomandi skjöl eða færslubókarlínur.</span><span class="sxs-lookup"><span data-stu-id="f6713-107">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="f6713-108">Ytri skrárnar er hægt að hengja við tengd skjöl á öllum stigum úrvinnslunnar, þ.m.t. við bókuð skjöl og við færslur lánardrottins, viðskiptamanns eða fjárhags sem verða til.</span><span class="sxs-lookup"><span data-stu-id="f6713-108">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="f6713-109">Nánari upplýsingar er að finna í [Vinna skjöl á innleið](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="f6713-109">For more information, see [Processing Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="f6713-110">Setja upp valkostinn fyrir skjal á innleið</span><span class="sxs-lookup"><span data-stu-id="f6713-110">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="f6713-111">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning fyrir skjöl á innleið** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="f6713-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="f6713-112">Fyllið inn í svæðin eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="f6713-112">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="f6713-113">Að setja upp samþykkjendur fyrir skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="f6713-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="f6713-114">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning fyrir skjöl á innleið** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="f6713-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="f6713-115">Í glugganum **Skjal á innleið** skal velja aðgerðina **Samþykkjendur**</span><span class="sxs-lookup"><span data-stu-id="f6713-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="f6713-116">Glugginn **Samþykkjendur skjala á innleið** sýnir alla notendur sem hafa verið settir upp í [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="f6713-116">The **Incoming Document Approvers** window shows all users that are set up in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  
3. <span data-ttu-id="f6713-117">Veldu einn eða fleiri notendur sem geta samþykkt innsent skjal áður en hægt er að stofna fylgiskjals - eða bókarlínu.</span><span class="sxs-lookup"><span data-stu-id="f6713-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="f6713-118">Þegar samþykkjendur hafa verið settir upp í glugganum **Samþykkjendur skjala á innleið** geta aðeins þessir notendur samþykkt skjal á innleið ef gátreitur **Krefjast samþykkis fyrir stofnun** í glugganum **uppsetning skjala á innleið** er valinn.</span><span class="sxs-lookup"><span data-stu-id="f6713-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

> [!NOTE]  
>   <span data-ttu-id="f6713-119">Þessi uppsetning samþykkis er ekki tengd samþykktarverkflæðum.</span><span class="sxs-lookup"><span data-stu-id="f6713-119">This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="f6713-120">Nánari upplýsingar sjá [hvernig á að: nota Samþykkisverkflæði](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="f6713-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="f6713-121">Til að setja upp OCR-þjónustu</span><span class="sxs-lookup"><span data-stu-id="f6713-121">To set up an OCR service</span></span>
1. <span data-ttu-id="f6713-122">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning OCR-þjónustu** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="f6713-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="f6713-123">Fyllið inn í svæðin eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="f6713-123">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="f6713-124">Til að dulrita innskráningarupplýsingar</span><span class="sxs-lookup"><span data-stu-id="f6713-124">To encrypt your login information</span></span>
<span data-ttu-id="f6713-125">Mælt er með því að vernda innskráningarupplýsingar sem slegnar eru inn í **uppsetning OCR-þjónustu** gluggann.</span><span class="sxs-lookup"><span data-stu-id="f6713-125">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="f6713-126">Hægt er að dulrita gögn á  netþjóninum með því að stofna nýjan dulritunarlykil eða flytja inn fyrirliggjandi lykla sem eru virkjaðir er á netþjónstilviki sem tengist við gagnagrunninn.</span><span class="sxs-lookup"><span data-stu-id="f6713-126">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="f6713-127">Í **uppsetning fyrir OCR-þjónusta** glugganum, veldu **stjórnun dulritunar**.</span><span class="sxs-lookup"><span data-stu-id="f6713-127">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="f6713-128"> Í glugganum **gagnadulritun**, virkja dulritun gagnanna.</span><span class="sxs-lookup"><span data-stu-id="f6713-128">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="f6713-129">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="f6713-129">See Also</span></span>
[<span data-ttu-id="f6713-130">Vinnsla skjala á innleið</span><span class="sxs-lookup"><span data-stu-id="f6713-130">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="f6713-131">Skjöl á innleið</span><span class="sxs-lookup"><span data-stu-id="f6713-131">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="f6713-132">Innkaup</span><span class="sxs-lookup"><span data-stu-id="f6713-132">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="f6713-133">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f6713-133">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
