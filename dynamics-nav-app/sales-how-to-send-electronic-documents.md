---
title: "Senda rafræn skjöl"
description: "lærðu hvernig á að senda reikninga rafrænt"
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5920ed97f054b3e7882f40f2fceec76183800297
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-send-electronic-documents"></a><span data-ttu-id="7aa96-103">Hvernig á að: Senda rafræn skjöl</span><span class="sxs-lookup"><span data-stu-id="7aa96-103">How to: Send Electronic Documents</span></span>
<span data-ttu-id="7aa96-104">Almenn útgáfa [!INCLUDE[d365fin](includes/d365fin_md.md)] styður sendingu rafrænna reikninga og kreditreikninga á PEPPOL-sniði, sem er stutt af stærstu skjalaskiptaþjónustuaðilunum.</span><span class="sxs-lookup"><span data-stu-id="7aa96-104">The generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)] supports sending electronic invoices and credit memos in the PEPPOL format, which is supported by the largest document exchange service providers.</span></span> <span data-ttu-id="7aa96-105">Þjónustuaðili í skjalaskiptaþjónustu sendir rafræn skjöl á milli viðskiptaaðila.</span><span class="sxs-lookup"><span data-stu-id="7aa96-105">A document exchange service provider dispatches electronic documents between trading partners.</span></span> <span data-ttu-id="7aa96-106">Til að veita stuðning á öðrum rafrænu formi er notaður gagnaskiptarammi.</span><span class="sxs-lookup"><span data-stu-id="7aa96-106">To provide support for other electronic document formats, you use the data exchange framework.</span></span>  

 <span data-ttu-id="7aa96-107">Í almennri útgáfu af [!INCLUDE[d365fin](includes/d365fin_md.md)] er skjalaskiptaþjónusta forstillt og tilbúinn til uppsetningar fyrir fyrirtækið.</span><span class="sxs-lookup"><span data-stu-id="7aa96-107">In the generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)], a document exchange service is preconfigured and ready to be set up for your company.</span></span> <span data-ttu-id="7aa96-108">Frekari upplýsingar, sjá [Hvernig á að setja upp skjalaskiptaþjónustu](across-how-to-set-up-a-document-exchange-service.md).</span><span class="sxs-lookup"><span data-stu-id="7aa96-108">For more information, see [How to: Set Up a Document Exchange Service](across-how-to-set-up-a-document-exchange-service.md).</span></span>  

 <span data-ttu-id="7aa96-109">Til að senda sölureikningi sem rafrænt PEPPOL-skjal er valinn valkosturinn **Rafrænt skjal** í **Bóka og senda** svarglugganum þar sem einnig er hægt að setja það upp sem sjálfgefið sendisnið skjals viðskiptamannsins.</span><span class="sxs-lookup"><span data-stu-id="7aa96-109">To send a sales invoice as an electronic PEPPOL document, you select the **Electronic Document** option in the **Post and Send** dialog box from where you can also set up the customer’s default document sending profile.</span></span> <span data-ttu-id="7aa96-110">Fyrst þarf að setja upp mismunandi aðalgögn, t.d. upplýsingar um fyrirtækið, viðskiptavini, atriði, og mælieiningar.</span><span class="sxs-lookup"><span data-stu-id="7aa96-110">First, you must set up various master data, such as company information, customers, items, and units of measure.</span></span> <span data-ttu-id="7aa96-111">Þau eru notuð til að bera kennsl á viðskiptafélaga og vörur þegar gögnum er umbreytt í reiti í [Hvernig skal: Setja upp rafræn skjöl sending og móttaka](across-how-to-set-up-electronic-document-sending-and-receiving.md)</span><span class="sxs-lookup"><span data-stu-id="7aa96-111">These are used to identify the business partners and items when converting data in fields in [How to: Set Up Electronic Document Sending and Receiving](across-how-to-set-up-electronic-document-sending-and-receiving.md).</span></span>  

### <a name="to-send-an-electronic-sales-invoice"></a><span data-ttu-id="7aa96-112">Til að senda rafrænan sölureikning</span><span class="sxs-lookup"><span data-stu-id="7aa96-112">To send an electronic sales invoice</span></span>  

1.  <span data-ttu-id="7aa96-113">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innkaupareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="7aa96-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoices**, and then choose the related link.</span></span>  

2.  <span data-ttu-id="7aa96-114">Nýr sölureikningur er búinn til.</span><span class="sxs-lookup"><span data-stu-id="7aa96-114">Create a new sales invoice.</span></span>  

3.  <span data-ttu-id="7aa96-115">Þegar hægt er að reikningsfæra sölureikninginn, á **Aðgerðir** flipanum í flokknum **Bókun** er valið **Bóka og senda**.</span><span class="sxs-lookup"><span data-stu-id="7aa96-115">When the sales invoice is ready to be invoiced, on the **Actions** tab, in the **Posting** group, choose **Post and Send**.</span></span>  

     <span data-ttu-id="7aa96-116">Ef sjálfgefið sendisnið viðskiptamannsins er **Rafrænt skjal**, mun það sjást í **Bóka og senda staðfestingu** svarglugganum og aðeins þarf að velja **Já** hnappinn til að bóka og senda reikninginn rafrænt á völdu sniði.</span><span class="sxs-lookup"><span data-stu-id="7aa96-116">If the customer’s default sending profile is **Electronic Document**, then it will be shown in the **Post and Send Confirmation** dialog box and you just have to choose the **Yes** button to post and send the invoice electronically in the selected format.</span></span>  

4.  <span data-ttu-id="7aa96-117">Í **Bóka og senda staðfestingu** svarglugganum er hnappurinn AssistEdit til hægri við **Senda skjal til** reitinn valinn.</span><span class="sxs-lookup"><span data-stu-id="7aa96-117">In the **Post and Send Confirmation** dialog box, choose the AssistEdit button to the right of the **Send Document to** field.</span></span>  

5.  <span data-ttu-id="7aa96-118">Í **Senda skjal til** svarglugganum í á **Rafrænt skjal** reitnum er valið **Gegnum skjalaskiptaþjónustu**.</span><span class="sxs-lookup"><span data-stu-id="7aa96-118">In the **Send Document to** dialog box, in the **Electronic Document** field, choose **Through Document Exchange Service**.</span></span>  

6.  <span data-ttu-id="7aa96-119">Í **Snið** reitnum er valið **PEPPOL**.</span><span class="sxs-lookup"><span data-stu-id="7aa96-119">In the **Format** field, choose **PEPPOL**.</span></span>  

7.  <span data-ttu-id="7aa96-120">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="7aa96-120">Choose the **OK** button.</span></span> <span data-ttu-id="7aa96-121">Svarglugginn **Bóka og senda staðfestingu** birtist.</span><span class="sxs-lookup"><span data-stu-id="7aa96-121">The **Post and Send Confirmation** dialog box appears.</span></span> <span data-ttu-id="7aa96-122">**Rafrænt skjal (PEPPOL)** er bætt við **Senda skjal til** reitinn.</span><span class="sxs-lookup"><span data-stu-id="7aa96-122">**Electronic Document (PEPPOL)** is added to the **Send Document to** field.</span></span>  

8.  <span data-ttu-id="7aa96-123">Velja hnappinn **Já**.</span><span class="sxs-lookup"><span data-stu-id="7aa96-123">Choose the **Yes** button.</span></span>  

     <span data-ttu-id="7aa96-124">Sölureikningur er bókaður og sendur til viðskiptamannsins sem rafrænt skjal á PEPPOL-sniði.</span><span class="sxs-lookup"><span data-stu-id="7aa96-124">The sales invoice is posted and sent to the customer as an electronic document in the PEPPOL format.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="7aa96-125">Einnig er hægt að senda bókaða sölureikninga sem rafrænt skjal.</span><span class="sxs-lookup"><span data-stu-id="7aa96-125">You can also send a posted sales invoice as an electronic document.</span></span> <span data-ttu-id="7aa96-126">Ferlið er það sama og lýst er í þessu efnisatriði fyrir óbókuð söluskjöl.</span><span class="sxs-lookup"><span data-stu-id="7aa96-126">The procedure is the same as described in this topic for non-posted sales documents.</span></span> <span data-ttu-id="7aa96-127">Í glugganum **Bókaðir sölureikningar**, á flipanum **Aðgerðir**, í flokknum **Almennt**, veljið **Aðgerðakladdi** til að skoða stöðu rafræna skjalsins.</span><span class="sxs-lookup"><span data-stu-id="7aa96-127">In the **Posted Sales Invoice** window, on the **Actions** tab, in the **General** group, choose **Activity Log** to view the status of the electronic document.</span></span> <span data-ttu-id="7aa96-128">Frekari upplýsingar, sjá **Aðgerðakladdi**.</span><span class="sxs-lookup"><span data-stu-id="7aa96-128">For more information, see **Activity Log**.</span></span>  

## <a name="see-also"></a><span data-ttu-id="7aa96-129">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="7aa96-129">See Also</span></span>  
[<span data-ttu-id="7aa96-130">Hvernig er reikningsfært</span><span class="sxs-lookup"><span data-stu-id="7aa96-130">How to: Invoice Sales</span></span>](sales-how-invoice-sales.md)  
[<span data-ttu-id="7aa96-131">Hvernig á að: Setja upp sendisnið skjala</span><span class="sxs-lookup"><span data-stu-id="7aa96-131">How to: Set Up Document Sending Profiles</span></span>](sales-how-setup-document-send-profiles.md)  
[<span data-ttu-id="7aa96-132">Hvernig á að: Setja upp sendingu og móttöku rafrænna skjala</span><span class="sxs-lookup"><span data-stu-id="7aa96-132">How to: Set Up Electronic Document Sending and Receiving</span></span>](across-how-to-set-up-electronic-document-sending-and-receiving.md)  
[<span data-ttu-id="7aa96-133">Hvernig á að: Setja upp skjalaskiptaþjónustu</span><span class="sxs-lookup"><span data-stu-id="7aa96-133">How to: Set Up a Document Exchange Service</span></span>](across-how-to-set-up-a-document-exchange-service.md)  
[<span data-ttu-id="7aa96-134">Hvernig á að: Setja upp skilgreiningar gagnaskipta</span><span class="sxs-lookup"><span data-stu-id="7aa96-134">How to: Set Up Data Exchange Definitions</span></span>](across-how-to-set-up-data-exchange-definitions.md)  
[<span data-ttu-id="7aa96-135">Rafræn gagnaskipti</span><span class="sxs-lookup"><span data-stu-id="7aa96-135">Exchanging Data Electronically</span></span>](across-data-exchange.md)  
[<span data-ttu-id="7aa96-136">Almenn viðskiptavirkni</span><span class="sxs-lookup"><span data-stu-id="7aa96-136">General Business Functionality</span></span>](ui-across-business-areas.md)  
