---
title: "Úthluta notandaheimild og stofna eða breyta heimildarsamstæðum"
description: "Lýsir því hvernig skal bæta Office 365 notendum við Dynamics NAV, og svo úthluta heimildum, aðgangsréttindum og öryggisstillingum."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: access, right, security
ms.date: 06/27/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d7dd8230fd5945a3a47e84fde017c26d936d7a39
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-users-and-permissions"></a><span data-ttu-id="d9ef9-103">Hvernig á að: Stjórna notendur og heimildir</span><span class="sxs-lookup"><span data-stu-id="d9ef9-103">How to: Manage Users and Permissions</span></span>
<span data-ttu-id="d9ef9-104">Til að bæta notendum í [!INCLUDE[d365fin](includes/d365fin_md.md)], verður kerfisstjóri Office 365 í fyrirtækinu fyrst að stofna notendur í stjórnstöð Office 365.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-104">To add users in [!INCLUDE[d365fin](includes/d365fin_md.md)], your company's Office 365 administrator must first create the users in the Office 365 Admin Center.</span></span> <span data-ttu-id="d9ef9-105">Frekari upplýsingar, sjá [Bæta notendum við Office 365 fyrir fyrirtæki](https://support.office.com/en-us/article/Add-users-to-Office-365-for-business-435ccec3-09dd-4587-9ebd-2f3cad6bc2bc).</span><span class="sxs-lookup"><span data-stu-id="d9ef9-105">For more information, see [Add Users to Office 365 for business](https://support.office.com/en-us/article/Add-users-to-Office-365-for-business-435ccec3-09dd-4587-9ebd-2f3cad6bc2bc)</span></span>

<span data-ttu-id="d9ef9-106">Þegar notendur hafa verið stofnaðir í Office 365 er hægt að flytja þá inn í gluggann **notendur** með því að velja aðgerðina **Sækja notendur úr Office 365**</span><span class="sxs-lookup"><span data-stu-id="d9ef9-106">Once users are created in Office 365, they can be imported into the **Users** window by using the **Get Users from Office 365** action.</span></span> <span data-ttu-id="d9ef9-107">Notendur eru úthlutað heimildir söfn samkvæmt áætlun sem er úthlutað á notandann í Office 365.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-107">Users are assigned permission sets depending on the plan assigned to the User in Office 365.</span></span>

<span data-ttu-id="d9ef9-108">Má því næst úthluta notendum heimildarsöfnum til að skilgreina hvaða hluti úr gagnagrunni, og þar með hvaða einingar Viðmótsins, þeir hafa aðgang að og í hvaða fyrirtækjum.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-108">You can then proceed to assign permission sets to the users to define which database objects, and thereby which UI elements, they have access to, and in which companies.</span></span>

<span data-ttu-id="d9ef9-109">Heimildasafn er safn heimildir fyrir tiltekna hluti í gagnagrunninum.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-109">A permission set is a collection of permissions for specific objects in the database.</span></span> <span data-ttu-id="d9ef9-110">Öllum notendum verða að hafa verið úthlutað eitt eða fleiri heimildasöfn áður en þeir geta opnað [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="d9ef9-110">All users must be assigned one or more permission sets before they can access [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="d9ef9-111">Nokkur fyrirfram skilgreind heimildasöfn eru veitt sjálfvirkt.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-111">A number of predefined permission sets are provided by default.</span></span> <span data-ttu-id="d9ef9-112">Hægt er að nota þessi heimildasöfn eins og þau eru nú þegar, breyta sjálfgefnum heimildasöfnum eða búa til önnur söfn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-112">You can use these permission sets as already defined, modify the default permission sets, or create additional permission sets.</span></span>

<span data-ttu-id="d9ef9-113">Þú getur bætt notendum við notendahópa.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-113">You can add users to user groups.</span></span> <span data-ttu-id="d9ef9-114">Þannig er auðveldara að úthluta sama heimildarsöfn á mörgum notendum.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-114">This makes it easier to assign the same permission sets to multiple users.</span></span>

<span data-ttu-id="d9ef9-115">Stjórnendur geta notað **Notandauppsetningu** gluggann til að skilgreina tímabil þegar tilgreindir notendur geta bókað, og geta einnig tilgreint hvort kerfið skrái tímann sem notandinn er skráður inn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-115">Administrators can use the **User Setup** window to define periods of time during which specified users are able to post, and also specify if the system logs the amount of time users are logged on.</span></span>

## <a name="to-assign-permissions-to-a-user"></a><span data-ttu-id="d9ef9-116">Að úthluta notanda heimild</span><span class="sxs-lookup"><span data-stu-id="d9ef9-116">To assign permissions to a user</span></span>
1. <span data-ttu-id="d9ef9-117">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Notendur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Users**, and then choose the related link.</span></span>
2. <span data-ttu-id="d9ef9-118">Veldu notandann sem á að úthluta á þessum viðskiptamanni til.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-118">Select the user that you want to assign permission to.</span></span>
<span data-ttu-id="d9ef9-119">Öll heimildasöfn sem er nú þegar úthlutuð til notandans eru birtar í upplýsingakassanum **Heimildasöfn**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-119">Any permission sets that are already assigned to the user are displayed in the **Permission Sets** FactBox.</span></span>
3. <span data-ttu-id="d9ef9-120">Veldu **breyta** aðgerðina til að opna gluggann **Notandapjald** .</span><span class="sxs-lookup"><span data-stu-id="d9ef9-120">Choose the **Edit** action to open the **User Card** window.</span></span>
4. <span data-ttu-id="d9ef9-121">Á flýtiflipanum **Heimildasöfn notanda** skal fylla út reitina eins og þörf krefur í nýrri línu.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-121">On the **User Permission Sets** FastTab, on a new line, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-group-users-in-user-groups"></a><span data-ttu-id="d9ef9-122">Til hópnotenda í notandaflokkum</span><span class="sxs-lookup"><span data-stu-id="d9ef9-122">To group users in user groups</span></span>
<span data-ttu-id="d9ef9-123">Þú getur sett upp notendahópa til að hjálpa þér að stjórna heimildasamstæðum fyrir hópa notenda í fyrirtæki þínu.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-123">You can set up users groups to help you manage permission sets for groups of users in your company.</span></span> <span data-ttu-id="d9ef9-124">Hægt er að nota aðgerð til að afrita öll heimildasöfn úr núverandi notandaflokki yfir í nýja notandaflokkinn þinn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-124">You can use a function to copy all permission sets from an existing user group to your new user group.</span></span> <span data-ttu-id="d9ef9-125">Meðlimir úr notandaflokki eru ekki afritaðar.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-125">User group members are not copied.</span></span>

1. <span data-ttu-id="d9ef9-126">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Notandaflokkar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-126">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **User Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="d9ef9-127">Einnig, í glugganum **Notendur**, veldu aðgerðina **Notandaflokkar**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-127">Alternatively, in the **Users** window, choose the **User Groups** action.</span></span>
3. <span data-ttu-id="d9ef9-128">Í glugganum **Notandahópar** er valinn er fyrirliggjandi notandahópurinn sem á að afrita og veljið svo **Afrita notandahóp** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-128">In the **User Groups** window, select an existing user group that you want to copy, and then choose the **Copy User Group** action.</span></span>
4. <span data-ttu-id="d9ef9-129">Í reitnum **Kóðar fyrir nýja notandahópa** er tilgreint nafn þess notanda hópinn og síðan valið **Í lagi** hnappinn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-129">In the **New User Group Code** field, specify the name of the new user group, and then choose the **OK** button.</span></span>

    <span data-ttu-id="d9ef9-130">Í stað þess að afrita, er hægt er að velja Nýja aðgerð til að búa til nýja línu fyrir auður notandahópur, og fylla síðan út handvirkt.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-130">As an alternative to copying, you can choose the New action to create a new line for an empty user group, which you then fill in manually.</span></span>
5. <span data-ttu-id="d9ef9-131">Til að við bæta nýjum eða fleiri notendur í glugganum **Notandahópur** er valin **Meðlimir notandahóps** aðgerðin.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-131">To add new or additional users, in the **User Group** window, choose the **User Group Members** action.</span></span>
6. <span data-ttu-id="d9ef9-132">Í glugganum **Notandahópur** er í nýrri línu fyllt í reitina eftir þörfum með því að velja úr hópi notendur sem þegar eru til staðar.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-132">In the **User Group Members** window, on a new line, fill in the fields as necessary by selecting from existing users.</span></span>
7. <span data-ttu-id="d9ef9-133">Til að bæta nýjum eða fleiri heimildarsöfnum, velurðu í glugganum **Notandahópur** aðgerðina **Heimildarsöfn notandahóps**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-133">To add new or additional permission sets, in the **User Group** window, choose the **User Group Permission Sets** action.</span></span>
8. <span data-ttu-id="d9ef9-134">Í glugganum **Heimildarsöfn notandahópa** er í nýrri línu fyllt í reitina eftir þörfum með því að velja úr heimildarsöfnum sem þegar eru til staðar.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-134">In the **User Group Permission Sets** window, on a new line, fill in the fields as necessary by selecting from existing permission sets.</span></span>

## <a name="to-create-or-modify-permission-sets"></a><span data-ttu-id="d9ef9-135">Til að stofna eða breyta heimildarsöfnum</span><span class="sxs-lookup"><span data-stu-id="d9ef9-135">To create or modify permission sets</span></span>
<span data-ttu-id="d9ef9-136">Ef sjálfgefin heimildasöfn sem fylgja með [!INCLUDE[d365fin](includes/d365fin_md.md)] eru ekki fullnægjandi eða henta ekki fyrirtækinu er hægt að búa til ný heimildarsöfn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-136">If the default permission sets that are provided with [!INCLUDE[d365fin](includes/d365fin_md.md)] are not sufficient or not appropriate for your organization, you can create new permission sets.</span></span> <span data-ttu-id="d9ef9-137">Og ef hinar einstöku heimildir fyrir hluti sem skilgreina heimildasafn nægja ekki er hægt að breyta heimildasafninu.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-137">And if the individual object permissions that define a permission set are not adequate, you can modify a permission set.</span></span> <span data-ttu-id="d9ef9-138">Hægt er að búa til heimildasöfn handvirkt, eða hægt er að nota aðgerðina skráningu sem skráir aðgerðir þínar um leið og þú ferðast í gegnum sviðsmynd og býr til nauðsynlegar heimildasöfn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-138">You can create a permission set manually, or you can use a recording function that records your actions as you navigate through a scenario and then generates the required permission set.</span></span>

### <a name="to-create-or-modify-permission-sets-manually"></a><span data-ttu-id="d9ef9-139">Til að stofna eða breyta heimildarsöfnum handvirkt</span><span class="sxs-lookup"><span data-stu-id="d9ef9-139">To create or modify permission sets manually</span></span>
1. <span data-ttu-id="d9ef9-140">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Notendur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-140">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Users**, and then choose the related link.</span></span>
2. <span data-ttu-id="d9ef9-141">Einnig, í glugganum **Notendur**, veldu aðgerðina **Heimildarsöfn**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-141">In the **Users** window, choose the **Permission Sets** action.</span></span>
3. <span data-ttu-id="d9ef9-142">Í glugganum **Heimildarsöfn**, veldu aðgerðina **Nýtt**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-142">In the **Permission Sets** window, choose the **New** Action.</span></span>
4. <span data-ttu-id="d9ef9-143">Fyllið í reitina eftir þörfum í nýrri línu.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-143">On a new line, fill in the fields as necessary.</span></span>
5. <span data-ttu-id="d9ef9-144">Veljið aðgerðina **Heimildir**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-144">Choose the **Permissions** action.</span></span>
6. <span data-ttu-id="d9ef9-145">Í glugganum **Heimildir** skal fylla út reitina á hausnum eins og þörf krefur.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-145">In the **Permissions** window, fill in the fields on the header as necessary.</span></span>
7. <span data-ttu-id="d9ef9-146">Í nýrri línu skal fylla út fimm reiti fyrir tegundir mismunandi heimild, eins og lýst er í eftirfarandi töflu.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-146">On a new line, fill in the five fields for the different permission types as described in the following table.</span></span>

    |<span data-ttu-id="d9ef9-147">Valkostur</span><span class="sxs-lookup"><span data-stu-id="d9ef9-147">Option</span></span>|<span data-ttu-id="d9ef9-148">Lýsing</span><span class="sxs-lookup"><span data-stu-id="d9ef9-148">Description</span></span>|
    |------|-----------|
    |<span data-ttu-id="d9ef9-149">Autt</span><span class="sxs-lookup"><span data-stu-id="d9ef9-149">Blank</span></span>|<span data-ttu-id="d9ef9-150">Tilgreinir að heimildartegundin er ekki veitt fyrir hlutinn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-150">Specifies that the permission type is not granted for the object.</span></span>|
    |<span data-ttu-id="d9ef9-151">**Já**</span><span class="sxs-lookup"><span data-stu-id="d9ef9-151">**Yes**</span></span>|<span data-ttu-id="d9ef9-152">Tilgreinir að heimildartegundin er veitt með beinan aðgang að hlutinn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-152">Specifies that the permission type is granted with direct access to the object.</span></span>|
    |<span data-ttu-id="d9ef9-153">**Óbeint**</span><span class="sxs-lookup"><span data-stu-id="d9ef9-153">**Indirect**</span></span>|<span data-ttu-id="d9ef9-154">Tilgreinir að heimildartegundin er veitt með óbeinan aðgang að hlutinn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-154">Specifies that the permission type is granted with indirect access to the object.</span></span>|

    <span data-ttu-id="d9ef9-155">Óbeinn heimildir í töflu merkir að þú getur ekki opnað töflunni og lesa úr henni, en hægt er að skoða gögnin í töflunni gegnum aðra hlutur, eins og síðu, sem þú hefur beina heimild til að fá aðgang að.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-155">Indirect permission to a table means that you cannot open the table and read from it, but you can view the data in the table through another object, such as a page, that you have direct permission to access.</span></span> <span data-ttu-id="d9ef9-156">Nánari upplýsingar, sjá „Dæmi - óbein heimild“ hlutann í þessu efnisatriði.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-156">For more information, see the “Example - Indirect Permission” section in this topic.</span></span>

8. <span data-ttu-id="d9ef9-157">Í reitnum **Öryggi Afmörkun** skal færa inn afmörkun sem þú vilt að eigi við heimildir með því að velja reiturinn sem á að takmarka aðgang notanda.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-157">In the **Security Filter** field, enter a filter that you want to apply to the permission by selecting the field on which you want to limit a user's access.</span></span>

    <span data-ttu-id="d9ef9-158">Til dæmis ef þú vilt búa til afmörkun öryggi svo að notandi geti aðeins skoðað sölu með tilteknum sölumannskóða, velurðu reitanúmer fyrir **Sölumannskóða** reitinn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-158">For example, if you want to create a security filter so that a user can view only sales with a specific salesperson code, you choose the field number for the **Salesperson Code** field.</span></span> <span data-ttu-id="d9ef9-159">Síðan, í reitnum **Reitaafmörkun** færir þú gildið inn sem á að nota til að takmarka aðgang.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-159">Then, in the **Field Filter** field, you enter the value of the that you want to use to limit access.</span></span> <span data-ttu-id="d9ef9-160">Til dæmis til að takmarka aðgang notanda að öllu nema sölu Annettes Hill, færirðu inn AH.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-160">For example, to limit a user's access to only Annette Hill's sales, enter AH.</span></span>
9. <span data-ttu-id="d9ef9-161">Endurtaka skal þrep 7 og 8 til að bæta heimildum fyrir öðrum hluti í heimildir safn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-161">Repeat steps 7 and 8 to add permissions for additional objects to the permission set.</span></span>

### <a name="to-create-or-modify-permission-sets-by-recording-your-actions"></a><span data-ttu-id="d9ef9-162">Að stofna eða breyta heimildasöfn með skráning við aðgerðir þínar</span><span class="sxs-lookup"><span data-stu-id="d9ef9-162">To create or modify permission sets by recording your actions</span></span>
1. <span data-ttu-id="d9ef9-163">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Notendur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-163">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Users**, and then choose the related link.</span></span>
2. <span data-ttu-id="d9ef9-164">Einnig, í glugganum **Notendur**, veldu aðgerðina **Heimildarsöfn**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-164">In the **Users** window, choose the **Permission Sets** action.</span></span>
3. <span data-ttu-id="d9ef9-165">Í glugganum **Heimildarsöfn**, veldu aðgerðina **Nýtt**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-165">In the **Permission Sets** window, choose the **New** Action.</span></span>
4. <span data-ttu-id="d9ef9-166">Fyllið í reitina eftir þörfum í nýrri línu.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-166">On a new line, fill in the fields as necessary.</span></span>
5. <span data-ttu-id="d9ef9-167">Veljið aðgerðina **Heimildir**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-167">Choose the **Permissions** action.</span></span>
6. <span data-ttu-id="d9ef9-168">Í glugganum **Heimildir**, veldu aðgerðina **Byrja**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-168">In the **Permissions** window, choose the **Start** action.</span></span>

    <span data-ttu-id="d9ef9-169">Skráningarvinnsla byrjar að ná yfir allar aðgerðir þínar í notandaviðmótinu.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-169">A recording process starts to capture all your actions in the user interface.</span></span>
7. <span data-ttu-id="d9ef9-170">Farðu yfir í ýmsir gluggar og aðgerðir í [!INCLUDE[d365fin](includes/d365fin_md.md)] sem þú vilt að notendum með þessa heimildasöfn fá aðgang að.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-170">Go to the various windows and activities in [!INCLUDE[d365fin](includes/d365fin_md.md)] that you want users with this permission set to access.</span></span> <span data-ttu-id="d9ef9-171">Þú verður að ljúka verkinu sem ætlunin er að skrá heimildir fyrir.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-171">You must carry out the tasks that you want to record permissions for.</span></span>
8. <span data-ttu-id="d9ef9-172">Þegar á að ljúka við skráningu er farið aftur á **Heimildir** gluggann og velja síðan **Stöðva** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-172">When you want to finish the recording, return to the **Permissions** window, and then choose the **Stop** action.</span></span>
9. <span data-ttu-id="d9ef9-173">Velja **Já** hnappinn til að bæta skráð heimildir við nýja heimildasafnið.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-173">Choose the **Yes** button to add the recorded permissions to the new permission set.</span></span>
10. <span data-ttu-id="d9ef9-174">Fyrir hvern hlutar á skráningar listanum, tilgreinið ef notendur geta sett inn, breytt eða eytt skráningum í skráningartöflunum.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-174">For each object in the recorded list, specify if users are able to insert, modify, or delete records in the recorded tables.</span></span> <span data-ttu-id="d9ef9-175">Sjá skref 7 í hlutanum „Að stofna eða breyta heimildir söfn handvirkt“.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-175">See step 7 in the "To create or modify permission sets manually" section.</span></span>

### <a name="example---indirect-permission"></a><span data-ttu-id="d9ef9-176">Dæmi - Óbein heimild</span><span class="sxs-lookup"><span data-stu-id="d9ef9-176">Example - Indirect Permission</span></span>
<span data-ttu-id="d9ef9-177">Hægt er að úthlutað óbeinni heimild til að nota hlut aðeins í gegnum annan hlut.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-177">You can assign an indirect permission to use an object only through another object.</span></span>
<span data-ttu-id="d9ef9-178">Til dæmis getur notandi haft heimild til að keyra kóðaeiningu 80, **Sölur-bókun**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-178">For example, a user can have permission to run codeunit 80, **Sales-Post**.</span></span> <span data-ttu-id="d9ef9-179">**Sölubókun** framkvæmir mörg verk, þar á meðal að breyta töflu 37, **Sölulína**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-179">The **Sales-Post** codeunit performs many tasks, including modifying table 37, **Sales Line**.</span></span> <span data-ttu-id="d9ef9-180">Þegar notandinn bókar söluskjal athugar **Sala-Bókun** kóðaeiningin, [!INCLUDE[d365fin](includes/d365fin_md.md)] hvort að notandinn hafi heimild til að breyta **Sölulína** töflunni.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-180">When the user posts a sales document, the **Sales-Post** codeunit, [!INCLUDE[d365fin](includes/d365fin_md.md)] checks if the user has permission to modify the **Sales Line** table.</span></span> <span data-ttu-id="d9ef9-181">Ef svo er ekki getur kótaeiningin ekki lokið við verkefni sín og þá munu villuboð birtast notandanum.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-181">If not, the codeunit cannot complete its tasks, and the user receives an error message.</span></span> <span data-ttu-id="d9ef9-182">Ef svo er verður kótaeiningin keyrð.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-182">If so, the codeunit runs successfully.</span></span>

<span data-ttu-id="d9ef9-183">Hins vegar þarf notandi ekki að hafa ótakmarkaðan aðgang að töflunni **Sölulína** til að keyra kótaeininguna.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-183">However, the user does not need to have full access to the **Sales Line** table to run the codeunit.</span></span> <span data-ttu-id="d9ef9-184">Ef notandinn hefur óbeina heimild fyrir töfluna **Sölulína** þá keyrir kóðaeiningin **Sölubókun** rétt.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-184">If the user has indirect permission to the **Sales Line** table, then the **Sales-Post** codeunit runs successfully.</span></span> <span data-ttu-id="d9ef9-185">Þegar notandi hefur óbeina heimild, getur sá notandi aðeins breytt töflunni **Sölulína** með því að keyra **Sölubókun** kóðaeiningunni eða annan hlut sem hefur heimild til að breyta töflunni **Sölulína**.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-185">When a user has indirect permission, that user can only modify the **Sales Line** table by running the **Sales-Post** codeunit or another object that has permission to modify the **Sales Line** table.</span></span> <span data-ttu-id="d9ef9-186">Notandinn getur aðeins breytt töflunni **Sölulína** frá studdum forritssvæðum.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-186">The user can only modify the **Sales Line** table when doing so from supported application areas.</span></span> <span data-ttu-id="d9ef9-187">Notandinn getur ekki keyrt eiginleikann óvart eða í sviksamlegum tilgangi á annan hátt.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-187">The user cannot run the feature inadvertently or maliciously by other methods.</span></span>

## <a name="to-set-up-user-time-constraints"></a><span data-ttu-id="d9ef9-188">Til að setja upp tímaskorður notanda</span><span class="sxs-lookup"><span data-stu-id="d9ef9-188">To set up user time constraints</span></span>
<span data-ttu-id="d9ef9-189">Stjórnendur geta skilgreint tímabil þegar tilgreindir notendur geta bókað, og geta einnig tilgreint hvort kerfið skrái tímann sem notandinn er skráður inn.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-189">Administrators can define periods of time during which specified users are able to post, and also specify if the system logs the amount of time users are logged on.</span></span> <span data-ttu-id="d9ef9-190">Stjórnendur geta einnig úthlutað ábyrgðarstöðvum á notendur.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-190">Administrators can also assign responsibility centers to users.</span></span>

1. <span data-ttu-id="d9ef9-191">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Notandauppsetning** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-191">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **User Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="d9ef9-192">Í glugganum **Notandauppsetning** opnast, skal velja **Nýtt** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-192">In the **User Setup** window opens, choose the **New** action.</span></span>
3. <span data-ttu-id="d9ef9-193">Í reitnum **Kenni notanda**, skal færa inn kenni notanda, eða velja reitinn til að sjá alla núverandi Windows notendur innan kerfisins.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-193">In the **User ID** field, enter the ID of a user, or choose the field to see all current Windows users in the system.</span></span>
4. <span data-ttu-id="d9ef9-194">Fyllið inn í reitina eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="d9ef9-194">Fill in the fields as necessary.</span></span>

## <a name="see-also"></a><span data-ttu-id="d9ef9-195">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="d9ef9-195">See Also</span></span>
[<span data-ttu-id="d9ef9-196">Undirbúðu þig fyrir að gera viðskipti</span><span class="sxs-lookup"><span data-stu-id="d9ef9-196">Getting Ready for Doing Business</span></span>](ui-get-ready-business.md)  
[<span data-ttu-id="d9ef9-197">Uppsetning og stjórnun í Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="d9ef9-197">Setup and Administration in Dynamics NAV</span></span>](admin-setup-and-administration.md)  
<span data-ttu-id="d9ef9-198">[Velkomin(n) í [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="d9ef9-198">[Welcome to [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span></span>  
<span data-ttu-id="d9ef9-199">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="d9ef9-199">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
