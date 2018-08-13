---
title: "Hvernig á að setja upp staðgreiðsluviðskiptamenn"
description: "Þetta efnisatriði lýsir skrefum í uppsetningu viðskiptamanns sem staðgreiðir."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/11/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 2f7b7db12069fd9f93a616077ea2b61393c1e9a3
ms.openlocfilehash: 340bc717c3e7ead687c578e99cb6c39ac57ad434
ms.contentlocale: is-is
ms.lasthandoff: 08/13/2018

---
# <a name="how-to-set-up-cash-customers"></a><span data-ttu-id="70f58-103">Hvernig á að setja upp staðgreiðsluviðskiptamenn</span><span class="sxs-lookup"><span data-stu-id="70f58-103">How to: Set Up Cash Customers</span></span>
<span data-ttu-id="70f58-104">Ekki er hægt að gera reikning án viðskiptamannsnúmers.</span><span class="sxs-lookup"><span data-stu-id="70f58-104">You cannot create an invoice without a customer number.</span></span> <span data-ttu-id="70f58-105">Þetta á við þó svo að selt sé gegn staðgreiðslu og ekki sé þörf á að skrá upplýsingar í viðskiptamannareikning.</span><span class="sxs-lookup"><span data-stu-id="70f58-105">This is true, even if you make a cash sale and do not have anything to record in a customer account.</span></span>  

## <a name="to-set-up-a-cash-customer"></a><span data-ttu-id="70f58-106">Uppsetning staðgreiðsluviðskiptamanna</span><span class="sxs-lookup"><span data-stu-id="70f58-106">To set up a cash customer</span></span>  
1. <span data-ttu-id="70f58-107">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **viðskiptamaður** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="70f58-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer**, and then choose the related link.</span></span>  
2. <span data-ttu-id="70f58-108">Stofna nýtt spjald **Viðskiptamaður**.</span><span class="sxs-lookup"><span data-stu-id="70f58-108">Create a new **Customer** card.</span></span> <span data-ttu-id="70f58-109">Nánari upplýsingar eru í [Hvernig á að skrá nýjan viðskiptamaður](sales-how-register-new-customers.md).</span><span class="sxs-lookup"><span data-stu-id="70f58-109">For more information, see [How to: Register New Customers](sales-how-register-new-customers.md).</span></span>
3. <span data-ttu-id="70f58-110">Í reitnum **númer**</span><span class="sxs-lookup"><span data-stu-id="70f58-110">In the **No.**</span></span> <span data-ttu-id="70f58-111">er ritað **Reiðufé**, til dæmis.</span><span class="sxs-lookup"><span data-stu-id="70f58-111">field, enter **Cash**, for example.</span></span>  
4. <span data-ttu-id="70f58-112">Í reitinn **Heiti** er til dæmis ritað **Staðgreitt við sölu**.</span><span class="sxs-lookup"><span data-stu-id="70f58-112">In the **Name** field, enter **Cash Sale**, for example.</span></span>  
5. <span data-ttu-id="70f58-113">Á flýtiflipanum **Reikningsfærsla** þarf að fylla út reitina **Bókunarflokkur viðskiptam.** og **Alm. viðsk.bókunarflokkur**.</span><span class="sxs-lookup"><span data-stu-id="70f58-113">On the **Invoicing** FastTab, fill in the **Customer Posting Group** and the **Gen. Bus. Posting Group** fields.</span></span>  

   <span data-ttu-id="70f58-114">Nú hefur verið stofnaður viðskiptamaður með nægar upplýsingar til reikningsfærslu.</span><span class="sxs-lookup"><span data-stu-id="70f58-114">Now you have set up a customer that contains sufficient information for invoicing.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="70f58-115">Hugsanlega hefur verið valinn bókunarflokkur sem er einnig notaður við kreditsölu innanlands.</span><span class="sxs-lookup"><span data-stu-id="70f58-115">You may have chosen a posting group that is also used for domestic credit sales.</span></span> <span data-ttu-id="70f58-116">Eigi að geyma gögn um sölu gegn staðgreiðslu sérstaklega, til dæmis með sérstökum sölu- eða safnreikningi, er hægt að setja upp sérstakan bókunarflokk í því skyni.</span><span class="sxs-lookup"><span data-stu-id="70f58-116">If you want to maintain separate data on cash sales, for example, with a special sales or receivables account, you can set up an extra posting group for this purpose.</span></span>  
>   
>  <span data-ttu-id="70f58-117">Rita þarf safnreikningsnúmer fyrir bókunarflokkinn þó svo að staðan á reikningnum verði alltaf 0 eftir bókun reiknings.</span><span class="sxs-lookup"><span data-stu-id="70f58-117">You must enter a number for a receivables account for the posting group, even though the balance in this account will always be 0 after you post an invoice.</span></span>  

## <a name="see-also"></a><span data-ttu-id="70f58-118">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="70f58-118">See Also</span></span>
[<span data-ttu-id="70f58-119">Stjórnun skulda</span><span class="sxs-lookup"><span data-stu-id="70f58-119">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="70f58-120">[Hvernig á að Skrá nýja viðskiptamenn](sales-how-register-new-customers.md)  </span><span class="sxs-lookup"><span data-stu-id="70f58-120">[How to: Register New Customers](sales-how-register-new-customers.md)  </span></span>  
[<span data-ttu-id="70f58-121">Fjármál</span><span class="sxs-lookup"><span data-stu-id="70f58-121">Finance</span></span>](finance.md)  


