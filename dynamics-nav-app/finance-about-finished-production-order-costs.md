---
title: "Um lokinn framleiðslupantanakostnað"
description: "Það er mikilvægur þáttur í að ljúka kostnaðarferli þeirrar vöru sem verið er að framleiða að fullvinna framleiðslupöntunina. Lokakostnaður þ.m.t. frávik í stöðluðu kostnaðarumhverfi; rauntölur í FIFO-, meðaltals-, eða LIFO-kostnaðarumhverfi er reiknaður út með því að nota keyrsluna **Stilla kostnað - Birgðafærslur**."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6b6fd4fe1ba4bd279aacbca38bf953bce5a996fc
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="about-finished-production-order-costs"></a><span data-ttu-id="6d373-104">Um lokinn framleiðslupantanakostnað</span><span class="sxs-lookup"><span data-stu-id="6d373-104">About Finished Production Order Costs</span></span>
<span data-ttu-id="6d373-105">Það er mikilvægur þáttur í að ljúka kostnaðarferli þeirrar vöru sem verið er að framleiða að fullvinna framleiðslupöntunina.</span><span class="sxs-lookup"><span data-stu-id="6d373-105">Finishing the production order is an important task in completing the costing lifecycle of the item that is being produced.</span></span> <span data-ttu-id="6d373-106">Lokakostnaður þ.m.t. frávik í stöðluðu kostnaðarumhverfi; rauntölur í FIFO-, meðaltals-, eða LIFO-kostnaðarumhverfi er reiknaður út með því að nota keyrsluna **Stilla kostnað - Birgðafærslur** sem gerir fjárhagslega afstemmingu af kostnaðinum af vöruframleiðslu mögulega.</span><span class="sxs-lookup"><span data-stu-id="6d373-106">Final costs, including variances in a standard cost environment, actuals in a FIFO, Average, or LIFO cost environment, are calculated using the **Adjust Cost - Item Entries** batch job, which allows for financial reconciliation of the costs of item production.</span></span> <span data-ttu-id="6d373-107">Framleiðslupöntun er bara tekin til kostnaðarleiðréttingar ef staða hennar er **Lokið**.</span><span class="sxs-lookup"><span data-stu-id="6d373-107">For a production order to be considered for cost adjustment, the status must be **Finished**.</span></span> <span data-ttu-id="6d373-108">Þess vegna er mikilvægt að þegar gerð framleiðslupöntunar er lokið sé stöðu hennar breytt í **Lokið**.</span><span class="sxs-lookup"><span data-stu-id="6d373-108">It is therefore critical that upon completion, the status of a production order is changed to **Finished**.</span></span>  

## <a name="example"></a><span data-ttu-id="6d373-109">Dæmi</span><span class="sxs-lookup"><span data-stu-id="6d373-109">Example</span></span>  
 <span data-ttu-id="6d373-110">Í umhverfi með stöðluðum kostnaði fara kostnaður vöru auk starfsmannakostnaðar og sameiginlegs kostnaðar í VÍV þegar efni er bókað til að framleiða vöru.</span><span class="sxs-lookup"><span data-stu-id="6d373-110">In a standard cost environment, when you consume material to produce an item, stated simply, the cost of the item plus labor and overhead go into WIP.</span></span> <span data-ttu-id="6d373-111">Þegar vara er framleidd er VÍV minnkað um upphæð staðalkostnaðar vörunnar.</span><span class="sxs-lookup"><span data-stu-id="6d373-111">When the item is produced, WIP is reduced by the amount of the standard cost of the item.</span></span> <span data-ttu-id="6d373-112">Yfirleitt er útkoman úr þessu ekki núll.</span><span class="sxs-lookup"><span data-stu-id="6d373-112">Typically, these costs do not net to zero.</span></span> <span data-ttu-id="6d373-113">Ef útkoman á að verða núll, þarf því að nota keyrsluna **Stilla kostnað - Vörufærslur** og athuga að aðeins framleiðslupantanir með stöðuna **Lokið** séu teknar til leiðréttingar.</span><span class="sxs-lookup"><span data-stu-id="6d373-113">So that these costs can net to zero, you must run the **Adjust Cost - Item Entries** batch job, noting that only production orders with the status of **Finished** will be considered for adjustment.</span></span>  

## <a name="see-also"></a><span data-ttu-id="6d373-114">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="6d373-114">See Also</span></span>  
[<span data-ttu-id="6d373-115">Birgðakostnaði stjórnað</span><span class="sxs-lookup"><span data-stu-id="6d373-115">Managing Inventory Costs</span></span>](finance-manage-inventory-costs.md)  
[<span data-ttu-id="6d373-116">Framleiðsla</span><span class="sxs-lookup"><span data-stu-id="6d373-116">Manufacturing</span></span>](production-manage-manufacturing.md)  
<span data-ttu-id="6d373-117">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="6d373-117">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
