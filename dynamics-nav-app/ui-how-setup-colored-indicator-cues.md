---
title: "Hvernig á að setja upp litaðan vísi á bunka"
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
ms.openlocfilehash: 38cd904d0cf22374eac430d035e6ea6d205bcab8
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---
    
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a><span data-ttu-id="d36da-102">Hvernig á að setja upp litaðan vísi á bunka</span><span class="sxs-lookup"><span data-stu-id="d36da-102">How to: Set Up a Colored Indicator on Cues</span></span>
<span data-ttu-id="d36da-103">Þú getur sett upp Bunka sem birtast í **heimasíðu** þannig að þeir innihaldi vísi sem breytir um lit eftir gagnagildum í bunkum.</span><span class="sxs-lookup"><span data-stu-id="d36da-103">You can set up Cues that appear on the **Home** page to include an indicator that changes color based on the data values in the Cues.</span></span> 

<span data-ttu-id="d36da-104">Vísirinn birtist sem stika efst í ramma bendingarinnar.</span><span class="sxs-lookup"><span data-stu-id="d36da-104">The indicator appears as a colored bar along the top border of the Cue tile.</span></span> <span data-ttu-id="d36da-105">Veitir sjónrænt merki um virknistöðu bendingarinnar sem getur táknað hagstæð eða óhagstæð skilyrði sem kalla á viðbrögð frá notanda.</span><span class="sxs-lookup"><span data-stu-id="d36da-105">It provides a visual signal of the status of the Cue's activity, which can indicate favorable or unfavorable conditions to prompt the user to take action.</span></span> <span data-ttu-id="d36da-106">Ef bunki birtir til dæmis viðvarandi sölureikninga er hægt að stilla vísinn á að vera grænn (jákvætt) þegar heildarfjöldi viðvarandi sölureikninga er undir 10 og rauður (óæskilegt) þegar samtalan er yfir 20.</span><span class="sxs-lookup"><span data-stu-id="d36da-106">For example, if a Cue displays ongoing sales invoices, you can set up the indicator to appear green (favorable) when total number of ongoing sales invoices is below 10, and appears red (unfavorable) when the total is greater than 20.</span></span>

<span data-ttu-id="d36da-107">Í glugganum **uppsetning bunka** seturðu setja upp vísa fyrir allar bendingar sem eru tiltækar í gagnagrunni fyrirtækisins.</span><span class="sxs-lookup"><span data-stu-id="d36da-107">From the **Cue Setup** window, you set up indicators for all the Cues that are available in the company database.</span></span>

<span data-ttu-id="d36da-108">Til að setja upp vísi tilgreinirðu allt að tvö þröskuldsgildi sem tilgreina þrjú svið gagnagilda (lágt, miðlungs og hátt) sem hægt er að nota annan lit (eða stíl) við.</span><span class="sxs-lookup"><span data-stu-id="d36da-108">To set up the indicator, you specify up to two threshold values that define three ranges of data values (low, middle, and high) to which you can apply a different color (or style).</span></span>

## <a name="to-set-up-colored-indicators-on-cues"></a><span data-ttu-id="d36da-109">Til að setja upp litaða vísa í bendingum</span><span class="sxs-lookup"><span data-stu-id="d36da-109">To set up colored indicators on Cues</span></span>
1. <span data-ttu-id="d36da-110">Undir **Aðgerðir** í notanda **Heimasíðu** , velja **Setja Upp bunka**.</span><span class="sxs-lookup"><span data-stu-id="d36da-110">Under **Activities** on your **Home** page, choose **Set Up Cues**.</span></span>  
<span data-ttu-id="d36da-111">Glugginn **uppsetning bunka** birtist.</span><span class="sxs-lookup"><span data-stu-id="d36da-111">The **Cue Setup** window appears.</span></span> <span data-ttu-id="d36da-112">Glugginn birtir vísana sem nú eru uppsettir í bunkum.</span><span class="sxs-lookup"><span data-stu-id="d36da-112">The window lists the indicators that are currently setup up on Cues.</span></span>
2. <span data-ttu-id="d36da-113">Til að breyta vísi, breyta reitunum og breyta, t.d. gildi fyrir mismunandi þröskulda.</span><span class="sxs-lookup"><span data-stu-id="d36da-113">To modify an indicator, edit the fields and modify, for example, the values for the different thresholds.</span></span>  

<span data-ttu-id="d36da-114">Eftirfarandi tafla sýnir liti sem samsvara valkostir af sem **lágsviðsstíll**, **millisviðsstíll**, og **hásviðsstíll** reiti.</span><span class="sxs-lookup"><span data-stu-id="d36da-114">The following table lists the colors that correspond to the options of the **Low Range Style**, **Middle Range Style**, and **High Range Style** fields.</span></span>

|<span data-ttu-id="d36da-115">Valkostur</span><span class="sxs-lookup"><span data-stu-id="d36da-115">Option</span></span>|<span data-ttu-id="d36da-116">Litur</span><span class="sxs-lookup"><span data-stu-id="d36da-116">Color</span></span>|
|------|-----|
|<span data-ttu-id="d36da-117">**Ekkert**</span><span class="sxs-lookup"><span data-stu-id="d36da-117">**None**</span></span>|<span data-ttu-id="d36da-118">Enginn litur (sami litur og í bunkareit)</span><span class="sxs-lookup"><span data-stu-id="d36da-118">No color (same color as the Cue tile</span></span>|
|<span data-ttu-id="d36da-119">**Hagstæð**</span><span class="sxs-lookup"><span data-stu-id="d36da-119">**Favorable**</span></span>|<span data-ttu-id="d36da-120">Grænt</span><span class="sxs-lookup"><span data-stu-id="d36da-120">Green</span></span>|
|<span data-ttu-id="d36da-121">**Slæmt**</span><span class="sxs-lookup"><span data-stu-id="d36da-121">**Unfavorable**</span></span>|<span data-ttu-id="d36da-122">Rautt</span><span class="sxs-lookup"><span data-stu-id="d36da-122">Red</span></span>|
|<span data-ttu-id="d36da-123">**Tvírætt**</span><span class="sxs-lookup"><span data-stu-id="d36da-123">**Ambiguous**</span></span>|<span data-ttu-id="d36da-124">Gult</span><span class="sxs-lookup"><span data-stu-id="d36da-124">Yellow</span></span>|
|<span data-ttu-id="d36da-125">**Undirstig**</span><span class="sxs-lookup"><span data-stu-id="d36da-125">**Subordinate**</span></span>|<span data-ttu-id="d36da-126">Grár</span><span class="sxs-lookup"><span data-stu-id="d36da-126">Gray</span></span>|

## <a name="see-also"></a><span data-ttu-id="d36da-127">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="d36da-127">See Also</span></span>
[<span data-ttu-id="d36da-128">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="d36da-128">Work with Dynamics NAV</span></span>](ui-work-product.md)


