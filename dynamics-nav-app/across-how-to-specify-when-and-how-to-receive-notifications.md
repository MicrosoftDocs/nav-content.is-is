---
title: "Hvernig á að: Tilgreina hvenær og hvernig á að fá tilkynningar"
description: "Þegar notendur eru settir upp í samþykktarverkflæði verður að tilgreina í gluggunum Tilkynningagrunnur og Tilkynningaáætlun hvenær og hvernig hver notandi fær tilkynningar um skref í samþykktarverkflæði. Einstakir notendur geta einnig breytt tilkynningastillingum sínum með þí að velja hnappinn Breyta tilkynningastillingum á hverri tilkynningu."
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
ms.openlocfilehash: 7d4c09b216f64b41a1bd72507c7a09c05e19d06a
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-specify-when-and-how-to-receive-notifications"></a><span data-ttu-id="8e700-104">Hvernig á að: Tilgreina hvenær og hvernig á að fá tilkynningar</span><span class="sxs-lookup"><span data-stu-id="8e700-104">How to: Specify When and How to Receive Notifications</span></span>
<span data-ttu-id="8e700-105">Þegar notendur eru settir upp í samþykktarverkflæði verður að tilgreina í gluggunum **Tilkynningagrunnur** og **Tilkynningaáætlun** hvenær og hvernig hver notandi fær tilkynningar um skref í samþykktarverkflæði.</span><span class="sxs-lookup"><span data-stu-id="8e700-105">When you set up users in approval workflows, you must specify in the **Notification Setup** and **Notification Schedule** windows how and when each user receives notifications about approval workflow steps.</span></span> <span data-ttu-id="8e700-106">Einstakir notendur geta einnig breytt tilkynningastillingum sínum með þí að velja hnappinn **Breyta tilkynningastillingum** á hverri tilkynningu.</span><span class="sxs-lookup"><span data-stu-id="8e700-106">Individual users can also change their notification setup by choosing the **Change Notification Settings** button on any notification.</span></span>  

 <span data-ttu-id="8e700-107">Áður en hægt er að setja upp tilkynningastillingar samþykktarnotanda verður að setja notanda upp sem samþykktarnotanda</span><span class="sxs-lookup"><span data-stu-id="8e700-107">Before you can set up an approval user’s notification preferences, you must set the user up as an approval user.</span></span> <span data-ttu-id="8e700-108">Nánari upplýsingar eru í [Hvernig á að: Setja upp notendur sem samþykkjendur](across-how-to-set-up-approval-users.md)</span><span class="sxs-lookup"><span data-stu-id="8e700-108">For more information, [How to: Set Up Approval Users](across-how-to-set-up-approval-users.md).</span></span>  

 <span data-ttu-id="8e700-109">Með því að setja upp tilkynningasniðmát er útlit og innihald tilkynninga skilgreint.</span><span class="sxs-lookup"><span data-stu-id="8e700-109">You define the layout and content of notifications by setting up notification templates.</span></span> <span data-ttu-id="8e700-110">Nánari upplýsingar eru í [Hvernig á að: Vinna með tilkynningasniðmát](across-how-to-manage-notification-templates.md).</span><span class="sxs-lookup"><span data-stu-id="8e700-110">For more information, see [How to: Manage Notification Templates](across-how-to-manage-notification-templates.md).</span></span>  

 <span data-ttu-id="8e700-111">Mörg skref samþykktarverkflæðis snúast um að láta notendur vita að tilvik hafi átt sér stað og þeir þurfi að bregðast við því.</span><span class="sxs-lookup"><span data-stu-id="8e700-111">Many approval workflow steps are about notifying users that an event has occurred that they must act on.</span></span> <span data-ttu-id="8e700-112">Til dæmis getur eitt skref í verkflæði verið að tilvik óski eftir að Notandi 1 samþyki nýja færslu.</span><span class="sxs-lookup"><span data-stu-id="8e700-112">For example, on one workflow step, the event can be that User 1 requests approval of a new record.</span></span> <span data-ttu-id="8e700-113">Tengd viðbrögð eru að tilkynning er sent Notanda 2, sem er samþykkjandi.</span><span class="sxs-lookup"><span data-stu-id="8e700-113">The related response is that a notification is sent to User 2, the approver.</span></span> <span data-ttu-id="8e700-114">Í næsta skrefi verkflæðis getur tilvik verið að Notandi 2 samþykki nýja færslu.</span><span class="sxs-lookup"><span data-stu-id="8e700-114">On the next workflow step, the event can be that User 2 approves the record.</span></span> <span data-ttu-id="8e700-115">Tengd viðbrögð eru að tilkynning er sent Notanda 3 til að hefja ferli með samþykktri færslu.</span><span class="sxs-lookup"><span data-stu-id="8e700-115">The related response is that a notification is sent to User 3 to start a process with the approved record.</span></span> <span data-ttu-id="8e700-116">Í öllum skref verkflæðis sem snúast um samþykki eru tilkynningar tengdar samþykktarfærslu.</span><span class="sxs-lookup"><span data-stu-id="8e700-116">For workflow steps that are about approval, each notification is tied to an approval entry.</span></span> <span data-ttu-id="8e700-117">Frekari upplýsingar eru í [Verkflæði](across-workflow.md).</span><span class="sxs-lookup"><span data-stu-id="8e700-117">For more information, see [Workflow](across-workflow.md).</span></span>  

## <a name="specify-when-and-how-users-receive-notifications"></a><span data-ttu-id="8e700-118">Tilgreinið hvenær og hvernig notendur fá tilkynningar</span><span class="sxs-lookup"><span data-stu-id="8e700-118">Specify when and how users receive notifications</span></span>  

1.  <span data-ttu-id="8e700-119">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning samþykkts notanda** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="8e700-119">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Approval User Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="8e700-120">Veljið línu fyrir notanda sem á að nota til að setja upp tilkynningarstillingar fyrir og því næst er valið **Uppsetning tilkynninga**.</span><span class="sxs-lookup"><span data-stu-id="8e700-120">Select the line for the user that you want to set up notification preferences for, and then choose the **Notification Setup** action.</span></span>  
3.  <span data-ttu-id="8e700-121">Í glugganum **Tilkynningagrunnur** þarf að fylla reitina út eins og lýst er í eftirfarandi töflu.</span><span class="sxs-lookup"><span data-stu-id="8e700-121">In the **Notification Setup** window, fill the fields as described in the following table.</span></span>  

    |<span data-ttu-id="8e700-122">Svæði</span><span class="sxs-lookup"><span data-stu-id="8e700-122">Field</span></span>|<span data-ttu-id="8e700-123">Description</span><span class="sxs-lookup"><span data-stu-id="8e700-123">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="8e700-124">**Gerð tilkynningar**</span><span class="sxs-lookup"><span data-stu-id="8e700-124">**Notification Type**</span></span>|<span data-ttu-id="8e700-125">Tilgreinið hvaða gerð tilviks tilkynning fjallar um.</span><span class="sxs-lookup"><span data-stu-id="8e700-125">Specify what type of event the notification is about.</span></span><br /><br /> <span data-ttu-id="8e700-126">Einn af eftirfarandi kostum er valinn:</span><span class="sxs-lookup"><span data-stu-id="8e700-126">Select one of the following options:</span></span><br /><br /> <span data-ttu-id="8e700-127">-   **Ný færsla** tilgreinir að tilkynningin sé um nýja færslu, svo sem skjal, sem notandinn þarf að bregðast við.</span><span class="sxs-lookup"><span data-stu-id="8e700-127">-   **New Record** specifies that the notification is about a new record, such as a document, that the user must act on.</span></span><br /><span data-ttu-id="8e700-128">-   **Samþykktir** tilgreinir að tilkynningin fjalli um eina eða fleiri samþykktarbeiðnir.</span><span class="sxs-lookup"><span data-stu-id="8e700-128">-   **Approval** specifies that the notification is about one or more approval requests.</span></span><br /><span data-ttu-id="8e700-129">-   **Komið fram yfir tíma** tilgreinir að tilkynningin er um áminningu notenda um að þeir séu seinir að bregðast við viðburði.</span><span class="sxs-lookup"><span data-stu-id="8e700-129">-   **Overdue** specifies that the notification is to remind users that they are late in acting on an event.</span></span>|  
    |<span data-ttu-id="8e700-130">**Sniðmátskóði tilkynningar**</span><span class="sxs-lookup"><span data-stu-id="8e700-130">**Notification Template Code**</span></span>|<span data-ttu-id="8e700-131">Tilgreinið kóða tilkynningasniðmátsins sem er notað til að stofna tilkynningar fyrir notandann.</span><span class="sxs-lookup"><span data-stu-id="8e700-131">Specify the code of the notification template that is used to create notifications for the user.</span></span>|  
    |<span data-ttu-id="8e700-132">**Snjallar tilkynningar**</span><span class="sxs-lookup"><span data-stu-id="8e700-132">**Unaggregated Notifications**</span></span>|<span data-ttu-id="8e700-133">Tilgreinið hvort notandinn fær eina tilkynningu fyrir hvern viðburð eða uppsafnaðar tilkynningar.</span><span class="sxs-lookup"><span data-stu-id="8e700-133">Specify if the user receives one notification for each event or aggregated notifications.</span></span><br /><br /> <span data-ttu-id="8e700-134">Ef gátreitur **Snjallar tilkynningar** er ekki valinn mun notandi fá tilkynningar sem safna saman upplýsingum um tilvik sem eiga sér stað innan sama endurtekningarmynsturs í tilkynningaáætlun.</span><span class="sxs-lookup"><span data-stu-id="8e700-134">If the **Unaggregated Notifications** check box is not selected, then the user receives notifications that aggregate information about events that occur within the same recurrence pattern in the notification schedule.</span></span>|  

     <span data-ttu-id="8e700-135">Tilgreint hefur verið hvernig notandi fær tilkynningar.</span><span class="sxs-lookup"><span data-stu-id="8e700-135">You have now specified how the user receives notifications.</span></span> <span data-ttu-id="8e700-136">Halda áfram að ákveða hvenær notandi fær tilkynningar.</span><span class="sxs-lookup"><span data-stu-id="8e700-136">Proceed to specify when the user receives notifications.</span></span>  

4.  <span data-ttu-id="8e700-137">Veldu **Áætlun tilkynninga**.</span><span class="sxs-lookup"><span data-stu-id="8e700-137">Choose the **Notification Schedule** action.</span></span>  
5.  <span data-ttu-id="8e700-138">Í glugganum **Áætlun tilkynninga** þarf að fylla reitina út eins og lýst er í eftirfarandi töflu.</span><span class="sxs-lookup"><span data-stu-id="8e700-138">In the **Notification Schedule** window, fill the fields as described in the following table.</span></span>  

    |<span data-ttu-id="8e700-139">Svæði</span><span class="sxs-lookup"><span data-stu-id="8e700-139">Field</span></span>|<span data-ttu-id="8e700-140">Description</span><span class="sxs-lookup"><span data-stu-id="8e700-140">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="8e700-141">**Endurtekning**</span><span class="sxs-lookup"><span data-stu-id="8e700-141">**Recurrence**</span></span>|<span data-ttu-id="8e700-142">Tilgreinið endurtekningarmynstur þar sem notandi fær tilkynningar.</span><span class="sxs-lookup"><span data-stu-id="8e700-142">Specify the recurrence pattern in which the user receives notifications.</span></span>|  
    |<span data-ttu-id="8e700-143">**Tími**</span><span class="sxs-lookup"><span data-stu-id="8e700-143">**Time**</span></span>|<span data-ttu-id="8e700-144">Tilgreinir hvenær dagsins notandinn fær tilkynningar þegar gildið í **Endurtekning** reitnum er frábrugðið **Strax**.</span><span class="sxs-lookup"><span data-stu-id="8e700-144">Specify what time of the day the user receives notifications when the value in the **Recurrence** field is different from **Instantly**.</span></span>|  
    |<span data-ttu-id="8e700-145">**Dagleg tíðni**</span><span class="sxs-lookup"><span data-stu-id="8e700-145">**Daily Frequency**</span></span>|<span data-ttu-id="8e700-146">Tilgreinið á hvers kyns dögum notandinn fær tilkynningar þegar gildið í **Endurtekning** reitnum er **Daglega**.</span><span class="sxs-lookup"><span data-stu-id="8e700-146">Specify on which type of days the user receives notifications when the value in the **Recurrence** field is **Daily**.</span></span><br /><br /> <span data-ttu-id="8e700-147">Velja **Virkur dagur** til að fá tilkynningar hvern virkan dag vikunnar.</span><span class="sxs-lookup"><span data-stu-id="8e700-147">Select **Weekday** to receive notifications every work day of the week.</span></span> <span data-ttu-id="8e700-148">Velja **Daglega** til að fá tilkynningar hvern dag vikunnar, þar á meðal um helgar.</span><span class="sxs-lookup"><span data-stu-id="8e700-148">Select **Daily** to receive notifications every day of the week, including weekends.</span></span>|  
    |<span data-ttu-id="8e700-149">**Mánudagur** til **Sunnudags**</span><span class="sxs-lookup"><span data-stu-id="8e700-149">**Monday** through **Sunday**</span></span>|<span data-ttu-id="8e700-150">Tilgreinið á hvers kyns dögum notandinn fær tilkynningar þegar gildið í **Endurtekning** reitnum er **Vikulega**.</span><span class="sxs-lookup"><span data-stu-id="8e700-150">Specify on which days the user receives notifications when the value in the **Recurrence** field is **Weekly**.</span></span>|  
    |<span data-ttu-id="8e700-151">**Mánaðardagur**</span><span class="sxs-lookup"><span data-stu-id="8e700-151">**Date of Month**</span></span>|<span data-ttu-id="8e700-152">Tilgreinið hvort notandinn fær tilkynningar á fyrsta, síðasta eða tilteknum degi mánaðarins.</span><span class="sxs-lookup"><span data-stu-id="8e700-152">Specify if the user receives notifications on the first, last, or a specific date of the month.</span></span>|  
    |<span data-ttu-id="8e700-153">**Dagsetning mánaðarlegrar tilkynningar**</span><span class="sxs-lookup"><span data-stu-id="8e700-153">**Monthly Notification Date**</span></span>|<span data-ttu-id="8e700-154">Tilgreinið á hvaða degi mánaðarins notandinn fær tilkynningar þegar gildið í **Mánaðardagur** reitnum er **Sérsniðið**.</span><span class="sxs-lookup"><span data-stu-id="8e700-154">Specify the date of the month on which the user receives notifications when the value in the **Date of Month** field is **Custom**.</span></span>|  

## <a name="change-when-and-how-you-receive-notifications"></a><span data-ttu-id="8e700-155">Breyta hvenær og hvernig notandi fær tilkynningar</span><span class="sxs-lookup"><span data-stu-id="8e700-155">Change when and how you receive notifications</span></span>  
1.  <span data-ttu-id="8e700-156">Í einni tilkynningu sem borist hefur, annaðhvort í tölvupósti eða sem athugasemd, skal velja hnappinn **Breyta tilkynningastillingum**.</span><span class="sxs-lookup"><span data-stu-id="8e700-156">On one of the notifications that you have received, either as email or note, choose the **Change Notification Settings** button.</span></span>  
2.  <span data-ttu-id="8e700-157">Í glugganum **Tilkynningagrunnur** skal breyta tilkynningarstillingunum eins og lýst er í fyrra ferli.</span><span class="sxs-lookup"><span data-stu-id="8e700-157">In the **Notification Setup** window, change your notification preferences as described in the previous procedure.</span></span>  

## <a name="see-also"></a><span data-ttu-id="8e700-158">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="8e700-158">See Also</span></span>  
 <span data-ttu-id="8e700-159">[Hvernig á að: Setja upp notendur sem samþykkjendur](across-how-to-set-up-approval-users.md) </span><span class="sxs-lookup"><span data-stu-id="8e700-159">[How to: Set Up Approval Users](across-how-to-set-up-approval-users.md) </span></span>  
 <span data-ttu-id="8e700-160">[Hvernig á að: Vinna með tilkynningasniðmát](across-how-to-manage-notification-templates.md) </span><span class="sxs-lookup"><span data-stu-id="8e700-160">[How to: Manage Notification Templates](across-how-to-manage-notification-templates.md) </span></span>  
 <span data-ttu-id="8e700-161">[Setja upp tilkynningar verkflæðis](across-setting-up-workflow-notifications.md) </span><span class="sxs-lookup"><span data-stu-id="8e700-161">[Setting Up Workflow Notifications](across-setting-up-workflow-notifications.md) </span></span>  
 <span data-ttu-id="8e700-162">[Uppsetning verkflæðis](across-set-up-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="8e700-162">[Setting Up Workflows](across-set-up-workflows.md) </span></span>  
 [<span data-ttu-id="8e700-163">Nota verkflæði</span><span class="sxs-lookup"><span data-stu-id="8e700-163">Using Workflows</span></span>](across-use-workflows.md)
