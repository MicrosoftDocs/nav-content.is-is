---
title: "Setja upp SEPA-kreditfærslur"
description: "Kynntu þér hvernig á að setja upp SEPA-kreditfærslur í Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: sepa, credit, transfer, payment,
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5dd85579a39fc9bfb3bb362e9573facc0c0a3977
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-sepa-credit-transfer"></a><span data-ttu-id="94b3e-103">Hvernig á að: Setja upp SEPA-beingreiðslur</span><span class="sxs-lookup"><span data-stu-id="94b3e-103">How to: Set Up SEPA Credit Transfer</span></span>
<span data-ttu-id="94b3e-104">Frá glugganum **Greiðslubók** er hægt að flytja út greiðslur í skrá til upphals í netbanka til vinnslu á tengdum peningamillifærslum.</span><span class="sxs-lookup"><span data-stu-id="94b3e-104">From the **Payment Journal** window, you can export payments to a file for upload to your electronic bank for processing of the related money transfers.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="94b3e-105"> styður SEPA-kreditfærslusniðið, en í heimalandi þínu / svæði geta önnur snið fyrir rafrænar greiðslur kunna að vera tiltækir.</span><span class="sxs-lookup"><span data-stu-id="94b3e-105"> supports the SEPA Credit Transfer format, but in your country/region, other formats for electronic payments may be available.</span></span>  

<span data-ttu-id="94b3e-106">Til að opna fyrir útflutning af skráasniði bankaskrár sem ekki eru studdar af [!INCLUDE[d365fin](includes/d365fin_md.md)] er hægt að setja upp gagnaskiptaskilgreiningu með því að nota gagnaskiptaumgjörð.</span><span class="sxs-lookup"><span data-stu-id="94b3e-106">To enable export of a bank file formats that are not supported out of the box in [!INCLUDE[d365fin](includes/d365fin_md.md)], you can set up a data exchange definition by using the data exchange framework.</span></span> <span data-ttu-id="94b3e-107">Frekari upplýsingar, sjá [Hvernig á að: Gagngaskiptaskilgreining](across-how-to-set-up-data-exchange-definitions.md).</span><span class="sxs-lookup"><span data-stu-id="94b3e-107">For more information, see [How to: Set Up Data Exchange Definitions](across-how-to-set-up-data-exchange-definitions.md).</span></span>  

<span data-ttu-id="94b3e-108">Áður en þú getur afgreitt greiðslu rafrænt með því að flytja greiðsluskrár í SEPA-kreditfærslusnið, verður þú að framkvæma eftirfarandi uppsetningarskref:</span><span class="sxs-lookup"><span data-stu-id="94b3e-108">Before you can process payment electronically by exporting payment files in the SEPA Credit Transfer format, you must perform the following setup steps:</span></span>  

* <span data-ttu-id="94b3e-109">Setja upp viðkomandi bankareikning til að meðhöndla SEPA-kreditfærslusnið.</span><span class="sxs-lookup"><span data-stu-id="94b3e-109">Set up the bank account in question to handle the SEPA Credit Transfer format</span></span>  
* <span data-ttu-id="94b3e-110">Setja upp lánardrottinn spjöld með því að flytja skrár úr í SEPA-kreditmillifærslur sniði.</span><span class="sxs-lookup"><span data-stu-id="94b3e-110">Set up vendor cards to process payments by exporting files in the SEPA Credit Transfer format</span></span>  
* <span data-ttu-id="94b3e-111">Setja upp viðeigandi bókarkeyrslu til að gera virkan útflutning greiðslu úr **greiðslubók** glugga.</span><span class="sxs-lookup"><span data-stu-id="94b3e-111">Set up the related general journal batch to enable payment export from the **Payment Journal** window</span></span>  
* <span data-ttu-id="94b3e-112">Tengja gagnaskiptaskilgreiningu fyrir eina eða fleiri greiðslugerðir með viðeigandi greiðslumáta.</span><span class="sxs-lookup"><span data-stu-id="94b3e-112">Connect the data exchange definition for one or more payment types with the relevant payment method or methods</span></span>  

### <a name="to-set-up-a-bank-account-for-sepa-credit-transfer"></a><span data-ttu-id="94b3e-113">Að setja upp bankareikning fyrir SEPA-kreditfærslu</span><span class="sxs-lookup"><span data-stu-id="94b3e-113">To set up a bank account for SEPA Credit Transfer</span></span>  
1. <span data-ttu-id="94b3e-114">Í reitinn **Leita** skal færa inn **Bankareikningar** og velja síðan viðkomandi tengi.</span><span class="sxs-lookup"><span data-stu-id="94b3e-114">In the **Search** box, enter **Bank Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="94b3e-115">Opnið spjald bankareikningsins sem á að flytja greiðsluskrár úr á SEPA-kreditfærslusniði.</span><span class="sxs-lookup"><span data-stu-id="94b3e-115">Open the card of the bank account from which you will export payment files in the SEPA Credit Transfer format.</span></span>  
3. <span data-ttu-id="94b3e-116">Á flýtiflipanum **Millifærsla**, í reitnum **Útflutningssvið greiðslu** skal velja **SEPADD**.</span><span class="sxs-lookup"><span data-stu-id="94b3e-116">On the **Transfer** FastTab, in the **Payment Export Format** field, choose **SEPADD**.</span></span>  
4. <span data-ttu-id="94b3e-117">Í **SEPA Kreditfærsla skilaboð kenni númeraröð** reitnum skal velja númeraröð sem tölum eru úthlutað úr til SEPA-kreditfærslu.</span><span class="sxs-lookup"><span data-stu-id="94b3e-117">In the **SEPA CT Msg. ID No. Series** field, choose a number series from which numbers are assigned to SEPA credit transfer entries.</span></span>  
5. <span data-ttu-id="94b3e-118">Gangið úr skugga um að reiturinn **IBAN** sé útfylltur.</span><span class="sxs-lookup"><span data-stu-id="94b3e-118">Make sure the **IBAN** field is filled.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="94b3e-119">Reiturinn **Gjaldmiðilskóði** verður að vera stilltur á **EUR**, því SEPA-kreditmillifærslur er aðeins hægt að gera í evrum.</span><span class="sxs-lookup"><span data-stu-id="94b3e-119">The **Currency Code** field must be set to **EUR**, because SEPA credit transfers can only be made in the EURO currency.</span></span>  

### <a name="to-set-up-a-vendor-card-for-sepa-credit-transfer"></a><span data-ttu-id="94b3e-120">Að setja upp lánardrottin fyrir SEPA-kreditfærslu</span><span class="sxs-lookup"><span data-stu-id="94b3e-120">To set up a vendor card for SEPA Credit Transfer</span></span>  
1. <span data-ttu-id="94b3e-121">Í reitnum **Leita** skal færa inn **Lánardrottnar** og velja síðan viðkomandi tengi.</span><span class="sxs-lookup"><span data-stu-id="94b3e-121">In the **Search** box, enter **Vendors**, and then choose the related link.</span></span>  
2. <span data-ttu-id="94b3e-122">Opnið spjald lánardrottins sem á að greiða til rafrænt útflutningi greiðsluskráa á SEPA-kreditfærslusniði.</span><span class="sxs-lookup"><span data-stu-id="94b3e-122">Open the card of the vendor whom you will pay electronically by export payment files in the SEPA Credit Transfer format.</span></span>  
3. <span data-ttu-id="94b3e-123">Á flýtiflipanum **Greiðsla**, í reitnum **Kóði greiðslumáta** skal velja **BANKI**.</span><span class="sxs-lookup"><span data-stu-id="94b3e-123">On the **Payment** FastTab, in the **Payment Method Code** field, choose **BANK**.</span></span>  
4. <span data-ttu-id="94b3e-124">Í **Valinn bankareikningur** reitnum, veldu banka sem fé verður flutt inn á þegar það er unnið með rafrænum bankann þinn.</span><span class="sxs-lookup"><span data-stu-id="94b3e-124">In the **Preferred Bank Account** field, choose the bank to which the money will be transferred when it is processed by your electronic bank.</span></span>  

     <span data-ttu-id="94b3e-125">Gildið í reitnum **Valinn bankareikningur** er afritað í reitinn **Móttökubankareikningur** í **Greiðslubók** glugganum.</span><span class="sxs-lookup"><span data-stu-id="94b3e-125">The value in the **Preferred Bank Account** field is copied to the **Recipient Bank Account** field in the **Payment Journal** window.</span></span>  

### <a name="to-set-the-payment-journal-up-to-export-payment-files"></a><span data-ttu-id="94b3e-126">Að stilla greiðslubók upp til að flytja greiðsluskrár</span><span class="sxs-lookup"><span data-stu-id="94b3e-126">To set the payment journal up to export payment files</span></span>  
1. <span data-ttu-id="94b3e-127">Í reitnum **Leit** skal færa inn **Greiðslubækur** og velja síðan viðkomandi tengil.</span><span class="sxs-lookup"><span data-stu-id="94b3e-127">In the **Search** box, enter **Payment Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="94b3e-128">Opnið greiðslubókina sem á að nota til vinna greiðslur með því að flytja skrár á SEPA-kreditfærslusniði.</span><span class="sxs-lookup"><span data-stu-id="94b3e-128">Open the payment journal that you use to process payments by exporting files in the SEPA Credit Transfer format.</span></span>  
3. <span data-ttu-id="94b3e-129">Í reitnum **Heiti keyrslu** er felli\-lista hnappurinn valinn.</span><span class="sxs-lookup"><span data-stu-id="94b3e-129">In the **Batch Name** field, choose the drop\-down button.</span></span>  
4. <span data-ttu-id="94b3e-130">Í glugganum **Færslubókarkeyrslur** á flipanum **Heim**, í flokknum **Stjórna**, skal velja **Breyta lista**.</span><span class="sxs-lookup"><span data-stu-id="94b3e-130">In the **General Journal Batches** window, on the **Home** tab, in the **Manage** group, choose **Edit List**.</span></span>  
5. <span data-ttu-id="94b3e-131">Á línunni fyrir greiðslubókina sem notuð verður til að flytja út greiðslur skal velja gátreitinn **Leyfa greiðsluútflutning**.</span><span class="sxs-lookup"><span data-stu-id="94b3e-131">On the line for the payment journal that you will use to export payments, select the **Allow Payment Export** check box.</span></span>  

### <a name="to-connect-the-data-exchange-definition-for-one-or-more-payment-types-with-the-relevant-payment-method-or-methods"></a><span data-ttu-id="94b3e-132">Tengja gagnaskiptaskilgreiningu fyrir eina eða fleiri greiðslugerðir með viðeigandi greiðslumáta.</span><span class="sxs-lookup"><span data-stu-id="94b3e-132">To connect the data exchange definition for one or more payment types with the relevant payment method or methods</span></span>  
1. <span data-ttu-id="94b3e-133">Í reitnum **Leit** skal færa inn **Greiðsluhættir** og velja síðan viðkomandi tengil.</span><span class="sxs-lookup"><span data-stu-id="94b3e-133">In the **Search** box, enter **Payment Methods**, and then choose the related link.</span></span>  
2. <span data-ttu-id="94b3e-134">Í **Greiðslumáti** glugganum skaltu velja greiðslumáta sem er notað til að flytja út greiðslur frá, og þá velja **Greiðsluútflutningur Línuskilgreining** reitinn.</span><span class="sxs-lookup"><span data-stu-id="94b3e-134">In the **Payment Methods** window, select the payment method that is used to export payments from, and then choose the **Pmt. Export Line Definition** field.</span></span>  
3. <span data-ttu-id="94b3e-135">Í **Greiðsluútflutningur Línuskilgreining** glugganum skal velja kóðann sem var tilgreindur í **Kóði** reitnum á **Línuskilgreiningar** flýtiflipanum í skrefi 4 í „Að lýsa sniði lína og dálka í skránni“ hlutanum í [Hvernig skal: setja upp gagnaskiptaskilgreiningar](across-how-to-set-up-data-exchange-definitions.md) aðgerðinni.</span><span class="sxs-lookup"><span data-stu-id="94b3e-135">In the **Pmt. Export Line Definitions** window, select the code that you specified in the **Code** field on the **Line Definitions** FastTab in step 4 in the “To describe the formatting of lines and columns in the file” section in the [How to: Set Up Data Exchange Definitions](across-how-to-set-up-data-exchange-definitions.md) procedure.</span></span>  

    <span data-ttu-id="94b3e-136">Umboðið fyrir beingreiðslur er sjálfkrafa sett inn í **Kenni umboðs fyrir beint debet** reitinn þegar sölureikningur er stofnaður fyrir viðskiptamann sem var valinn í skrefi 2.</span><span class="sxs-lookup"><span data-stu-id="94b3e-136">The direct-debit mandate is automatically inserted in the **Direct Debit Mandate ID** field when you create a sales invoice for the customer that you selected in step 2.</span></span> <span data-ttu-id="94b3e-137">Nánari upplýsingar er að finna í [Hvernig á að: Stofna ítrekaðar sölu og innkaupalínur](sales-how-work-standard-lines.md)</span><span class="sxs-lookup"><span data-stu-id="94b3e-137">For more information, see [How to: Create Recurring Sales and Purchase Lines](sales-how-work-standard-lines.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="94b3e-138">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="94b3e-138">See Also</span></span>  
[<span data-ttu-id="94b3e-139">Innheimta greiðslur með SEPA-beingreiðslum</span><span class="sxs-lookup"><span data-stu-id="94b3e-139">Collecting Payments with SEPA Direct Debit</span></span>](finance-collect-payments-with-sepa-direct-debit.md)  
[<span data-ttu-id="94b3e-140">Hvernig á að: Setja upp skilgreiningar gagnaskipta</span><span class="sxs-lookup"><span data-stu-id="94b3e-140">How to: Set Up Data Exchange Definitions</span></span>](across-how-to-set-up-data-exchange-definitions.md)  
[<span data-ttu-id="94b3e-141">Hvernig á að: Stofna ítrekaðar sölu og innkaup</span><span class="sxs-lookup"><span data-stu-id="94b3e-141">How to: Create Recurring Sales and Purchase Lines</span></span>](sales-how-work-standard-lines.md)  
[<span data-ttu-id="94b3e-142">Rafræn gagnaskipti</span><span class="sxs-lookup"><span data-stu-id="94b3e-142">Exchanging Data Electronically</span></span>](across-data-exchange.md)  
