---
title: "Tilgreina prentaraval fyrir skýrslur"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---
    
# <a name="specify-printer-selection-for-reports"></a><span data-ttu-id="9a502-102">Tilgreina prentaraval fyrir skýrslur</span><span class="sxs-lookup"><span data-stu-id="9a502-102">Specify Printer Selection for Reports</span></span>
<span data-ttu-id="9a502-103">Hægt er að setja upp skýrslur þannig að það þurfi að prenta þær út á tilteknum prentara</span><span class="sxs-lookup"><span data-stu-id="9a502-103">You can set up reports so that they must be printed on a specific printer.</span></span> <span data-ttu-id="9a502-104">Hér á eftir koma nokkur dæmi um notkun prentaravals:</span><span class="sxs-lookup"><span data-stu-id="9a502-104">The following are some uses of printer selection:</span></span> 

- <span data-ttu-id="9a502-105">Hægt er að prenta skýrslur á sérstakt bréfsefni fyrirtækis.</span><span class="sxs-lookup"><span data-stu-id="9a502-105">You can print reports on special company letterhead.</span></span>
- <span data-ttu-id="9a502-106">Hægt er að prenta færslur á mismunandi pappírstærðir.</span><span class="sxs-lookup"><span data-stu-id="9a502-106">You can print reports on different paper sizes.</span></span>
- <span data-ttu-id="9a502-107">Hægt er að prenta skýrslur á sjálfgefnum prentara tiltekins starfsmanns.</span><span class="sxs-lookup"><span data-stu-id="9a502-107">You can print reports on the default printer of a specified employee.</span></span>

<span data-ttu-id="9a502-108">Nota gluggann **prentaraval** til að stilla mismunandi gildi til að fá ólíka útkomu.</span><span class="sxs-lookup"><span data-stu-id="9a502-108">You use the **Printer Selections** window to set different values to obtain different output.</span></span> <span data-ttu-id="9a502-109">Ef sértækt prentaraval er stillt hefur það forgang fram yfir almennt prentaraval.</span><span class="sxs-lookup"><span data-stu-id="9a502-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span></span> <span data-ttu-id="9a502-110">Til dæmis er hægt að stilla á prentaraval sem hefur gildi í reitunum **Kenni notanda**, **Kenni skýrslu** og **Prentaraheiti**.</span><span class="sxs-lookup"><span data-stu-id="9a502-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span></span> <span data-ttu-id="9a502-111">Þetta prentaraval hefur forgand yfir prentaraval með eyður í reitunum **Kenni notanda** eða **Kenni skýrslu**.</span><span class="sxs-lookup"><span data-stu-id="9a502-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span></span> 

<span data-ttu-id="9a502-112">Eftirfarandi tafla lýsir samsetningu gilda til að tilgreina hvenær eigi að setja upp prentaraval fyrir skýrslu.</span><span class="sxs-lookup"><span data-stu-id="9a502-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span></span>

|<span data-ttu-id="9a502-113">Til að</span><span class="sxs-lookup"><span data-stu-id="9a502-113">To</span></span>                                                 |<span data-ttu-id="9a502-114">Stilla eftirfarandi gildi:</span><span class="sxs-lookup"><span data-stu-id="9a502-114">Set the following values</span></span>                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|<span data-ttu-id="9a502-115">Prenta skýrslu í tilteknum prentara fyrir alla notendur</span><span class="sxs-lookup"><span data-stu-id="9a502-115">Print a report to a specific printer for all users</span></span> |<span data-ttu-id="9a502-116">Tilgreinið gildi í reitunum **Kenni skýrslu** og **Prentaraheiti** og skiljið reitinn **Kenni notanda** eftir auðan.</span><span class="sxs-lookup"><span data-stu-id="9a502-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span></span>|
|<span data-ttu-id="9a502-117">Prenta allar skýrslur í tilteknum prentara fyrir tiltekinn notanda</span><span class="sxs-lookup"><span data-stu-id="9a502-117">Print all reports to a specific printer for a specific user</span></span>|<span data-ttu-id="9a502-118">Tilgreinið gildi í reitunum **Kenni notanda** og **Prentaraheiti** og skiljið reitinn **Kenni skýrslu** eftir auðan.</span><span class="sxs-lookup"><span data-stu-id="9a502-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span></span>|
|<span data-ttu-id="9a502-119">Stilla sjálfgefinn prentara fyrir allar skýrslur</span><span class="sxs-lookup"><span data-stu-id="9a502-119">Set the default printer for all reports</span></span>|<span data-ttu-id="9a502-120">Tilgreinið gildi í reitnum **Prentaraheiti** og skiljið reitina **Kenni notanda** og **Kenni skýrslu** eftir auða.</span><span class="sxs-lookup"><span data-stu-id="9a502-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span></span>|
|<span data-ttu-id="9a502-121">Prenta tiltekna skýrslu í sjálfgefnum prentara notandans</span><span class="sxs-lookup"><span data-stu-id="9a502-121">Print a specific report to the user’s default printer</span></span>|<span data-ttu-id="9a502-122">Tilgreinið gildi í reitnum **Kenni skýrslu** og skiljið reitina **Prentaraheiti** og **Kenni notanda** eftir auða.</span><span class="sxs-lookup"><span data-stu-id="9a502-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span></span>|
|<span data-ttu-id="9a502-123">Prenta tiltekna skýrslu í tilteknum prentara fyrir tiltekinn notanda</span><span class="sxs-lookup"><span data-stu-id="9a502-123">Print a specific report to a specific printer for a specific user</span></span>|<span data-ttu-id="9a502-124">Tilgreinið gildi í öllum þremur reitunum.</span><span class="sxs-lookup"><span data-stu-id="9a502-124">Specify values in all three fields.</span></span>|

## <a name="see-also"></a><span data-ttu-id="9a502-125">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="9a502-125">See Also</span></span>
[<span data-ttu-id="9a502-126">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="9a502-126">Work with Dynamics NAV</span></span>](ui-work-product.md)

