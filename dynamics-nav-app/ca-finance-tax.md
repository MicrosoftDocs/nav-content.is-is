---
title: "Söluskattur og vöru- og þjónustuskattur í Kanada"
author: edupont04
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c032a02b545441b927ef5c4facc9f77731f37ab7
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="sales-tax-and-goods-and-services-tax-in-canada"></a><span data-ttu-id="6af6f-102">Söluskattur og vöru- og þjónustuskattur í Kanada</span><span class="sxs-lookup"><span data-stu-id="6af6f-102">Sales Tax and Goods and Services Tax in Canada</span></span>
<span data-ttu-id="6af6f-103">Í Kanada gilda þær reglur að þegar lánardrottinn hefur ekki viðskiptalögsögu í því fylki sem viðskiptin eru gerð í mun lánardrottinn aðeins innheimta vöru- og þjónustuskatt (GST) eða samræmdan söluskatt (HST).</span><span class="sxs-lookup"><span data-stu-id="6af6f-103">In Canada, when a vendor does not have a business presence in the province in which purchases are made, the vendor will charge the Goods and Services Tax (GST) or Harmonized Sales Tax (HST) only.</span></span> <span data-ttu-id="6af6f-104">Hins vegar, ef fylkið notar fylkissöluskatt (PST) mun kaupandinn þurfa að reikna út PST, og borga hann beint til fylkisins.</span><span class="sxs-lookup"><span data-stu-id="6af6f-104">However, if the province has a Provincial Sales Tax (PST), then the purchaser must still calculate the PST and pay it directly to the province.</span></span> <span data-ttu-id="6af6f-105">Þegar skattsvæðiskóði fylkis er valinn, notar Dynamics NAV hann við útreikning á PST og bókar hann þannig að skattskuld sé bæði í fjárhag og skattfærsluskránum.</span><span class="sxs-lookup"><span data-stu-id="6af6f-105">When a Provincial Tax Area Code is selected, Dynamics NAV uses it to calculate the PST and post it so that there is a tax liability in both the general ledger and the tax entry records.</span></span> <span data-ttu-id="6af6f-106">Þar af leiðandi ætti skattsvæðiskóði fylkis einungis að fela í sér PST, ekki GST.</span><span class="sxs-lookup"><span data-stu-id="6af6f-106">Therefore, the tax area code selected here should be one where only the PST is included, not the GST.</span></span>  
<span data-ttu-id="6af6f-107">Frekari upplýsingar um söluskatt má sjá í [Söluskattur og skattflokkar í Bandaríkjunum og Kanada](us-finance-setup-sales-tax.md).</span><span class="sxs-lookup"><span data-stu-id="6af6f-107">For more information about sales tax, see [Sales Tax and Tax Groups in the US and Canada](us-finance-setup-sales-tax.md).</span></span>  

## <a name="submitting-the-gsthst-file"></a><span data-ttu-id="6af6f-108">Að senda GST/HST skrá</span><span class="sxs-lookup"><span data-stu-id="6af6f-108">Submitting the GST/HST File</span></span>
<span data-ttu-id="6af6f-109">Upplýsingar um skatta í innkaupaskjölum eru notaðar til að búa til GST/HST millifærsluskrá á internetinu sem verður að berast til skattyfirvalda.</span><span class="sxs-lookup"><span data-stu-id="6af6f-109">The tax information in purchase documents is used to generate a GST/HST internet file transfer that you must  provided to the tax authorities.</span></span> <span data-ttu-id="6af6f-110">Þessi skrá inniheldur vöru- og þjónustuskatt (GST) og samræmdan söluskatt (HST).</span><span class="sxs-lookup"><span data-stu-id="6af6f-110">This file includes goods and services tax (GST) and harmonized sales tax (HST).</span></span> <span data-ttu-id="6af6f-111">Skráin er búin til í skráarsniði fyrir skatt, sem hægt er að millifæra yfir internetið.</span><span class="sxs-lookup"><span data-stu-id="6af6f-111">The file is created in a .tax file format, which can be transferred via the internet.</span></span>  

## <a name="see-also"></a><span data-ttu-id="6af6f-112">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="6af6f-112">See Also</span></span>
[<span data-ttu-id="6af6f-113">Fjármál</span><span class="sxs-lookup"><span data-stu-id="6af6f-113">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="6af6f-114">Uppsetning fjármála</span><span class="sxs-lookup"><span data-stu-id="6af6f-114">Set Up Finance</span></span>](finance-setup-setup-finance-setup.md)  
[<span data-ttu-id="6af6f-115">Söluskattur og skattflokkar í Bandaríkjunum og Kanada</span><span class="sxs-lookup"><span data-stu-id="6af6f-115">Sales Tax and Tax Groups in the US and Canada</span></span>](us-finance-setup-sales-tax.md)

