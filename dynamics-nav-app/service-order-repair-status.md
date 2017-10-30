---
title: "Setja upp stöður fyrir þjónustupantanir og viðgerðir"
description: "Þú verður að setja upp níu viðgerðarstöðuvalkosti sem sýna framvindu viðgerða og viðhalds á þjónustuvöru í þjónustupöntunum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d7dbc4cfc06d4c74476a04512bd368a0ab26f837
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-statuses-for-service-orders-and-repairs"></a><span data-ttu-id="4b16d-103">Hvernig skal Setja upp stöður fyrir þjónustupantanir og viðgerðir</span><span class="sxs-lookup"><span data-stu-id="4b16d-103">How to: Set Up Statuses for Service Orders and Repairs</span></span>
<span data-ttu-id="4b16d-104">Þú verður að setja upp viðgerðarstöðuvalkosti sem sýna framvindu viðgerða og viðhalds á þjónustuvöru í þjónustupöntunum.</span><span class="sxs-lookup"><span data-stu-id="4b16d-104">You must set up repair status options that identify the progress of repair and maintenance of service items in service orders.</span></span> <span data-ttu-id="4b16d-105">Gert er ráð fyrir níu mismunandi valkostum viðgerðarstöðu miðað við aðstæður eða aðgerðir sem gripið er til þegar þjónustuvörur eru teknar til þjónustu.</span><span class="sxs-lookup"><span data-stu-id="4b16d-105">You must set up at least nine repair status options that identify situations or actions taken when servicing service items.</span></span>  

<span data-ttu-id="4b16d-106">Þú getur stillt forgang stöðuvalkosti þjónustupöntunar.</span><span class="sxs-lookup"><span data-stu-id="4b16d-106">You can set the priority level for service order status options.</span></span> <span data-ttu-id="4b16d-107">Fernt kemur til greina: Mikill, Í meðallagi mikill, Í meðallagi lítill og Lítill.</span><span class="sxs-lookup"><span data-stu-id="4b16d-107">There four priorities are High, Medium High, Medium Low, and Low.</span></span>  
  
<span data-ttu-id="4b16d-108">Þegar viðgerðarstöðu þjónustuvöru í þjónustupöntun er breytt uppfærir kerfi þjónustupöntunarstöðuna.</span><span class="sxs-lookup"><span data-stu-id="4b16d-108">When you change the repair status of a service item in a service order, the service order status is updated.</span></span> <span data-ttu-id="4b16d-109">Viðgerðarstaða hverrar þjónustuvöru tengist stöðu þjónustupöntunarinnar.</span><span class="sxs-lookup"><span data-stu-id="4b16d-109">The repair status of each service item is linked to the service order status.</span></span> <span data-ttu-id="4b16d-110">Ef þjónustuvaran tengist tveimur eða fleiri þjónustupöntunarstöðuvalkostum er þjónustupöntunarstöðuvalkosturinn valinn sem gefur mesta forgangsröð.</span><span class="sxs-lookup"><span data-stu-id="4b16d-110">If the service items are linked to two or more service order status options, the service order status with the highest priority is selected.</span></span>  

## <a name="to-set-up-a-repair-status"></a><span data-ttu-id="4b16d-111">Uppsetning viðgerðarstöðu</span><span class="sxs-lookup"><span data-stu-id="4b16d-111">To set up a repair status</span></span>  
1. <span data-ttu-id="4b16d-112">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **viðgerðarstaða** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="4b16d-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Repair Status**, and then choose the related link.</span></span> <span data-ttu-id="4b16d-113">2.</span><span class="sxs-lookup"><span data-stu-id="4b16d-113">2.</span></span> <span data-ttu-id="4b16d-114">Stofnið nýja viðgerðarstöðu.</span><span class="sxs-lookup"><span data-stu-id="4b16d-114">Create a new repair status.</span></span>  
3. <span data-ttu-id="4b16d-115">Fyllt er í reitina **Kóti** og **Lýsing**.</span><span class="sxs-lookup"><span data-stu-id="4b16d-115">Fill in the **Code** and **Description** fields.</span></span>  
4. <span data-ttu-id="4b16d-116">Í reitnum **Staða þjónustupöntunar** er valin staða pöntunar sem á að tengja viðgerðarstöðuna við.</span><span class="sxs-lookup"><span data-stu-id="4b16d-116">In the **Service Order Status** field, choose the order status to link the repair status to.</span></span> <span data-ttu-id="4b16d-117">Reiturinn **Forgangur** sýnir forgangi stöðunnar á þjónustupöntun sem valin var.</span><span class="sxs-lookup"><span data-stu-id="4b16d-117">The **Priority** field displays the priority of the service order status you have chosen.</span></span>  
5. <span data-ttu-id="4b16d-118">Veldu viðgerðarstaða</span><span class="sxs-lookup"><span data-stu-id="4b16d-118">Choose a repair status.</span></span> <span data-ttu-id="4b16d-119">Hægt er að velja aðeins eina</span><span class="sxs-lookup"><span data-stu-id="4b16d-119">You can choose only one.</span></span>  
6. <span data-ttu-id="4b16d-120">Til að hægt sé að bóka þjónustupantanir, þar með taldar þjónustuvörur, með þessa viðgerðarstöðu, skal velja **Bókun leyfð** reitinn.</span><span class="sxs-lookup"><span data-stu-id="4b16d-120">To be able to post service orders, including service items, with this repair status, choose the **Posting Allowed** field.</span></span>  
7. <span data-ttu-id="4b16d-121">Til að unnt sé að breyta handvirkt stöðukosti þjónustupöntunar í **Í undirbúningi** í þjónustupöntunum með þjónustuvöru sem hefur þessa viðgerðarstöðu, skal velja **Í undirbúningi staða leyfð** gátreitinn.</span><span class="sxs-lookup"><span data-stu-id="4b16d-121">To be able to manually change the service order status option to **Pending** in service orders including service items with this repair status, choose the **Pending Status Allowed** check box.</span></span>  
8. <span data-ttu-id="4b16d-122">Veljið gátreitina **Staðan Í vinnslu leyfð**, **Staðan Lokið leyfð** og **Staðan Í bið leyfð** á sama hátt.</span><span class="sxs-lookup"><span data-stu-id="4b16d-122">Choose the **In Process Status Allowed**, **Finished Status Allowed**, and **On Hold Status Allowed** check boxes in the same way.</span></span>
  
## <a name="to-set-up-service-status-priorities"></a><span data-ttu-id="4b16d-123">Uppsetning viðgerðarstöðuforgangs</span><span class="sxs-lookup"><span data-stu-id="4b16d-123">To set up service status priorities</span></span>  
1. <span data-ttu-id="4b16d-124">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Staða þjónustupöntunar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="4b16d-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Service Order Status**, and then choose the related link.</span></span>  
2. <span data-ttu-id="4b16d-125">Velja skal þjónustupöntunarstöðuna sem á að forgangsraða.</span><span class="sxs-lookup"><span data-stu-id="4b16d-125">Select the service order status you want to set a priority for.</span></span>  
3. <span data-ttu-id="4b16d-126">Í reitnum **Forgangur** er valin forgangsröð sem veita á þjónustupöntunarstöðunni.</span><span class="sxs-lookup"><span data-stu-id="4b16d-126">In the **Priority** field, choose the priority you want for this service order status.</span></span> <span data-ttu-id="4b16d-127">Endurtakið þetta skref fyrir hvert staða.</span><span class="sxs-lookup"><span data-stu-id="4b16d-127">Repeat this step for each status.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="4b16d-128">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="4b16d-128">See Also</span></span>  
[<span data-ttu-id="4b16d-129">Skilja þjónustupöntunarstaða og viðgerðarstaða</span><span class="sxs-lookup"><span data-stu-id="4b16d-129">Understanding Service Order Status and Repair Status</span></span>]()  
[<span data-ttu-id="4b16d-130">Þjónustustýring sett upp</span><span class="sxs-lookup"><span data-stu-id="4b16d-130">Setting Up Service Management</span></span>](service-setup-service.md)  
