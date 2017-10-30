---
title: "Nota PayPal greiðslur staðlaðar viðbætur"
description: "Lýsir því hvernig nota skal viðbætur til að gera viðskiptamönnum kleift að framkvæma greiðslur með PayPal."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9ce797091adf1ddd04e14729d27730dad50d819c
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="the-paypal-payments-standard-extension-to-dynamics-nav"></a><span data-ttu-id="3c8da-103">Staðlaðar PayPal greiðslur, viðbót við Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="3c8da-103">The PayPal Payments Standard Extension to Dynamics NAV</span></span>
<span data-ttu-id="3c8da-104">Viðskiptamenn þurfa stöðugt hærra þjónustustig, bæði hvað varðar gæði vöru en einnig hvað varðar valkosti afhendingar og greiðslu.</span><span class="sxs-lookup"><span data-stu-id="3c8da-104">Customers continuously require higher customer service, both in terms of product quality but also in terms of delivery and payment options.</span></span> <span data-ttu-id="3c8da-105">Staðlaða PayPal greiðsluþjónustan gerir kleift að veita viðskiptamanninum meiri þjónustu.</span><span class="sxs-lookup"><span data-stu-id="3c8da-105">The PayPal Payments Standard service helps you increase your customer service.</span></span>

<span data-ttu-id="3c8da-106">Í stað þess að innheimta greiðslur með gíró eða kreditkort getur boðið að viðskiptamenn greiði gegnum PayPal reikning þeirra .</span><span class="sxs-lookup"><span data-stu-id="3c8da-106">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span> <span data-ttu-id="3c8da-107">Þegar sölureikningur eða sölupöntun er send með tölvupósti er tengill fyrir PayPal í meginmáli tölvupóstsins og í viðhengdu PDF-skjali.</span><span class="sxs-lookup"><span data-stu-id="3c8da-107">When you send a sales invoice or sales order by email, there is a PayPal link in the email body and in the attached PDF document.</span></span> <span data-ttu-id="3c8da-108">Þegar viðskiptamaður velur tengilinn birtist þjónustusíða fyrir PayPal reikning hans þar sem nákvæmar greiðsluupplýsingar fyrir söluna koma fram.</span><span class="sxs-lookup"><span data-stu-id="3c8da-108">When the customer chooses the link, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="3c8da-109">Viðskiptamaður getur síðan greiða reikning og sem hverja aðra PayPal greiðslu.</span><span class="sxs-lookup"><span data-stu-id="3c8da-109">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="3c8da-110">Staðlaða PayPal greiðsluþjónustan býður upp á eftirfarandi kosti:</span><span class="sxs-lookup"><span data-stu-id="3c8da-110">The PayPal Payments Standard service provides the following benefits:</span></span>

* <span data-ttu-id="3c8da-111">Greiðslur viðskiptamanns berast hraðar á bankareikning þinn.</span><span class="sxs-lookup"><span data-stu-id="3c8da-111">Customer payments arrive faster in your bank account.</span></span>
* <span data-ttu-id="3c8da-112">Viðskiptamenn hafa úr fleiri leiðum að velja til að greiða reikninga.</span><span class="sxs-lookup"><span data-stu-id="3c8da-112">Customers have more ways to pay invoices.</span></span>
* <span data-ttu-id="3c8da-113">PayPal býður upp á trausta greiðsluþjónustu, og viðskiptamenn kjósa hana oft fram yfir að gefa kreditkortaupplýsingar upp á vefsíðum.</span><span class="sxs-lookup"><span data-stu-id="3c8da-113">PayPal offers a trustworthy payment service, which customers prefer to entering credit card information on web sites.</span></span>
* <span data-ttu-id="3c8da-114">PayPal býður upp á margar leiðir á meðhöndlun greiðslna, þar á meðal vinnslu kreditkorta, PayPal reikninga og aðrar leiðir.</span><span class="sxs-lookup"><span data-stu-id="3c8da-114">PayPal offers multiple ways of handling payments, including credit card processing, PayPal accounts, and other sources.</span></span>
* <span data-ttu-id="3c8da-115">Hægt er að bæta PayPal tenglinum sjálfkrafa við söluskjöl eða notandinn getur gert það handvirkt.</span><span class="sxs-lookup"><span data-stu-id="3c8da-115">The PayPal link can be added automatically to sales documents or manually by the user.</span></span>
* <span data-ttu-id="3c8da-116">Stöðluð PayPal greiðsluþjónusta felur ekki í sér mánaðarleg gjöld eða gjöld vegna uppsetningar.</span><span class="sxs-lookup"><span data-stu-id="3c8da-116">The PayPal Payments Standard service does not involve monthly fees or setup fees.</span></span>
* <span data-ttu-id="3c8da-117">Þar sem þetta er viðbót er auðvelt að virkja stöðluðu PayPal greiðsluþjónustuna þegar og ef fyrirtækið þarf á að halda.</span><span class="sxs-lookup"><span data-stu-id="3c8da-117">Because it is an extension, you can easily enable the PayPal Payment Standard service when and if your business requires it.</span></span>  

<span data-ttu-id="3c8da-118">Nánari upplýsingar eru í [Hvernig á að: Virkja greiðslur viðskiptamanna gegnum PayPal](sales-how-enable-payment-service-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="3c8da-118">For more information, see [How to: Enable Customer Payment Through PayPal](sales-how-enable-payment-service-extensions.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="3c8da-119">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="3c8da-119">See Also</span></span>
<span data-ttu-id="3c8da-120">[Sérstilling [!INCLUDE[d365fin](includes/d365fin_md.md)] með viðbótum](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="3c8da-120">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md)</span></span>  
[<span data-ttu-id="3c8da-121">Uppsetning sölu</span><span class="sxs-lookup"><span data-stu-id="3c8da-121">Setting Up Sales</span></span>](sales-setup-sales.md)  
<span data-ttu-id="3c8da-122">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="3c8da-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
