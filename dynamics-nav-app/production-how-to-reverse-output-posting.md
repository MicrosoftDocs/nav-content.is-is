---
title: "Hvernig á að bakfæra frálagsbókun"
description: "Stundum verður að bakfæra frálagsbókun. Dæmi um þetta væri ef gagnafærsluvilla ætti sér stað og rangt magn af frálagi væri bókað í Framleiðslupöntun."
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
ms.openlocfilehash: 21eda3d822ca162b2d97f34eddc21f745e34f561
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reverse-output-posting"></a><span data-ttu-id="130dc-104">Hvernig á að bakfæra frálagsbókun</span><span class="sxs-lookup"><span data-stu-id="130dc-104">How to: Reverse Output Posting</span></span>
<span data-ttu-id="130dc-105">Stundum verður að bakfæra frálagsbókun.</span><span class="sxs-lookup"><span data-stu-id="130dc-105">There are times when output posting must be reversed.</span></span> <span data-ttu-id="130dc-106">Dæmi um þetta væri ef gagnafærsluvilla ætti sér stað og rangt magn af frálagi væri bókað í Framleiðslupöntun.</span><span class="sxs-lookup"><span data-stu-id="130dc-106">An example of this would be if a data entry error occurred and an incorrect amount of output is posted to a production order.</span></span>  

## <a name="to-reverse-an-output-posting"></a><span data-ttu-id="130dc-107">Til að bakfæra frálagsbókun</span><span class="sxs-lookup"><span data-stu-id="130dc-107">To reverse an output posting</span></span>  
1.  <span data-ttu-id="130dc-108">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **frálagsbók** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="130dc-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Output Journal**, and then choose the related link.</span></span> <span data-ttu-id="130dc-109">Veljið keyrsluna.</span><span class="sxs-lookup"><span data-stu-id="130dc-109">Select your batch.</span></span>  
2. <span data-ttu-id="130dc-110">Fyllið inn í reitina eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="130dc-110">Fill in the fields as necessary.</span></span> <span data-ttu-id="130dc-111">Frekari upplýsingar, sjá [Hvernig á að: fjöldabóka frálag og keyrslutíma](production-how-to-post-output-quantity.md).</span><span class="sxs-lookup"><span data-stu-id="130dc-111">For more information, see [How to: Batch Post Output and Run Times](production-how-to-post-output-quantity.md).</span></span>
3.  <span data-ttu-id="130dc-112">Í reitnum **Jafna færslu** veljið tengda birgðafærslu.</span><span class="sxs-lookup"><span data-stu-id="130dc-112">In the **Applies-To Entry** field, select the associated item ledger entry.</span></span> <span data-ttu-id="130dc-113">Þá bakfærast birgðafærslurnar og afkastagetufærslurnar.</span><span class="sxs-lookup"><span data-stu-id="130dc-113">This reverses the capacity and item ledger entries.</span></span>  
4. <span data-ttu-id="130dc-114">Bóka bakfærsluna með því að bóka færslubókina.</span><span class="sxs-lookup"><span data-stu-id="130dc-114">Post the reversal by posting the journal.</span></span>  

<span data-ttu-id="130dc-115">Færslurnar í Frálagsbókinni eru bókaðar í vörubókina sem jákvæð leiðrétting.</span><span class="sxs-lookup"><span data-stu-id="130dc-115">The output journal entries are posted to the item ledger as a positive adjustment.</span></span>  

## <a name="see-also"></a><span data-ttu-id="130dc-116">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="130dc-116">See Also</span></span>  
 <span data-ttu-id="130dc-117">[Framleiðsla](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="130dc-117">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
 [<span data-ttu-id="130dc-118">Uppsetning framleiðslu</span><span class="sxs-lookup"><span data-stu-id="130dc-118">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
 <span data-ttu-id="130dc-119">[Áætlun](production-planning.md)    </span><span class="sxs-lookup"><span data-stu-id="130dc-119">[Planning](production-planning.md)    </span></span>  
 [<span data-ttu-id="130dc-120">Birgðir</span><span class="sxs-lookup"><span data-stu-id="130dc-120">Inventory</span></span>](inventory-manage-inventory.md)  
 [<span data-ttu-id="130dc-121">Innkaup</span><span class="sxs-lookup"><span data-stu-id="130dc-121">Purchasing</span></span>](purchasing-manage-purchasing.md)  
 <span data-ttu-id="130dc-122">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="130dc-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
