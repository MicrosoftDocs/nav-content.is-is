---
title: "Að nota Dynamics NAV efnispakka fyrir Power BI"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ad9519b8ce9c244480308ccc99c05e78e4926b06
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a><span data-ttu-id="067c4-102">Að nota Dynamics NAV efnispakka fyrir Power BI</span><span class="sxs-lookup"><span data-stu-id="067c4-102">Using the Dynamics NAV Content Pack for Power BI</span></span>
<span data-ttu-id="067c4-103">Að fá innsýn í Dynamics NAV gögn er auðvelt með Power BI og efnispökkum Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="067c4-103">Getting insights into your Dynamics NAV data is easy with Power BI and the Dynamics NAV content pack.</span></span> <span data-ttu-id="067c4-104">Power BI sækir gögn þín og býr svo til út-fyrir-kassann yfirlit og skýrslur sem byggist á þeim gögnum.</span><span class="sxs-lookup"><span data-stu-id="067c4-104">Power BI retrieves your data and then builds an out-of-the-box dashboard and reports based on that data.</span></span>  

<span data-ttu-id="067c4-105">Efnispakkinn er forstilltur til að vinna með sölugögnum og fjárhagsgögnum úr sýnifyrirtæki sem þú færð þegar þú nýskráir þig fyrir Dynamics NAV forskoðun.</span><span class="sxs-lookup"><span data-stu-id="067c4-105">The content pack is preconfigured to work with sales data and financial data from the demonstration company that you get when you sign up for the Dynamics NAV preview.</span></span>  

- <span data-ttu-id="067c4-106">Velja hvaða sjónræna hlutinn á yfirlitinu til að kalla fram einn af sjö undirliggjandi skýrslum.</span><span class="sxs-lookup"><span data-stu-id="067c4-106">Choose any visual on the dashboard to bring up one of seven underlying reports.</span></span>  
- <span data-ttu-id="067c4-107">Síða skýrsluna eða bæta við reitum sem eiga að fylgjast með.</span><span class="sxs-lookup"><span data-stu-id="067c4-107">Filter the report or add fields that you want to monitor.</span></span>  
- <span data-ttu-id="067c4-108">Festu þetta sérsniðna yfirlit á yfirlitið til að halda áfram rakning á.</span><span class="sxs-lookup"><span data-stu-id="067c4-108">Pin this customized view to the dashboard to continue tracking.</span></span>  
<span data-ttu-id="067c4-109">Yfirlitið og skýrslunum endurnýja undirliggjandi eru uppfærð daglega.</span><span class="sxs-lookup"><span data-stu-id="067c4-109">The dashboard and underlying reports refresh daily.</span></span> <span data-ttu-id="067c4-110">Hægt er að stjórna uppfærsluáætlun og breyta tiíðninni á gagnamengi.</span><span class="sxs-lookup"><span data-stu-id="067c4-110">You can control the refresh schedule and modify the frequency on the dataset.</span></span>  

## <a name="accessing-dynamics-nav-in-power-bi"></a><span data-ttu-id="067c4-111">Aðgangur að Dynamics NAV í Power BI</span><span class="sxs-lookup"><span data-stu-id="067c4-111">Accessing Dynamics NAV in Power BI</span></span>
<span data-ttu-id="067c4-112">Til að skoða þitt Dynamics NAV gögn í Power BI, verður að hafa eftirfarandi:</span><span class="sxs-lookup"><span data-stu-id="067c4-112">To see your Dynamics NAV data in Power BI, you must have the following:</span></span>  

- <span data-ttu-id="067c4-113">Aðgang að Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="067c4-113">Access to Dynamics NAV.</span></span> <span data-ttu-id="067c4-114">Nánari upplýsingar sjá [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).</span><span class="sxs-lookup"><span data-stu-id="067c4-114">For more information, see [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).</span></span>  
- <span data-ttu-id="067c4-115">Aðgang að Power BI</span><span class="sxs-lookup"><span data-stu-id="067c4-115">Access to Power BI.</span></span> <span data-ttu-id="067c4-116">Nánari upplýsingar eru í [Power BI](https://powerbi.microsoft.com), .</span><span class="sxs-lookup"><span data-stu-id="067c4-116">For more information, see [Power BI](https://powerbi.microsoft.com).</span></span>

<span data-ttu-id="067c4-117">Á vefsvæði Power BI má finna viðbótarupplýsingar um [bæta Verksins Dynamics NAV-efnispakka við Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).</span><span class="sxs-lookup"><span data-stu-id="067c4-117">On the Power BI site, you can find additional information about [adding the Dynamics NAV content pack to Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).</span></span>  

<span data-ttu-id="067c4-118">Til að fá aðgang að Dynamics NAV efnispakka í Power BI, í tengingaglugganum, verður að tilgreina eftirfarandi upplýsingar:</span><span class="sxs-lookup"><span data-stu-id="067c4-118">To access the Dynamics NAV content pack in Power BI, in the connection window, you must specify the following information:</span></span>

| <span data-ttu-id="067c4-119">Reitur</span><span class="sxs-lookup"><span data-stu-id="067c4-119">Field</span></span>       | <span data-ttu-id="067c4-120">Lýsing</span><span class="sxs-lookup"><span data-stu-id="067c4-120">Description</span></span>              |
|-------------|--------------------------|
|<span data-ttu-id="067c4-121">**OData streymisvefslóð**</span><span class="sxs-lookup"><span data-stu-id="067c4-121">**OData Feed URL**</span></span>|<span data-ttu-id="067c4-122">Odata vefslóð svo Power BI geti fengið aðgang að gögnum úr fyrirtæki þínu, eins og https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').</span><span class="sxs-lookup"><span data-stu-id="067c4-122">The OData URL so Power BI can access data from your company, such as https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').</span></span>|
|<span data-ttu-id="067c4-123">**Sannvottunaraðferð**</span><span class="sxs-lookup"><span data-stu-id="067c4-123">**Authentication method**</span></span>|<span data-ttu-id="067c4-124">Velja **Grunn**.</span><span class="sxs-lookup"><span data-stu-id="067c4-124">Choose **Basic**.</span></span>|
|<span data-ttu-id="067c4-125">**Notandanafn**</span><span class="sxs-lookup"><span data-stu-id="067c4-125">**User name**</span></span>|<span data-ttu-id="067c4-126">Tölvupóstur sem var notuð til að skrá sig í Dynamics NAV, eins og *me@mybusiness.com*.</span><span class="sxs-lookup"><span data-stu-id="067c4-126">The email account that you used to sign up for Dynamics NAV, such as *me@mybusiness.com*.</span></span>|
|<span data-ttu-id="067c4-127">**Aðgangsorð**</span><span class="sxs-lookup"><span data-stu-id="067c4-127">**Password**</span></span>|<span data-ttu-id="067c4-128">Þetta er aðgangslykill vefþjónustu fyrir notandareikningur í Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="067c4-128">This is the web service access key for your user account in Dynamics NAV.</span></span>|

<span data-ttu-id="067c4-129">Þetta þýðir fá þarf tvö stykki af upplýsingar úr Dynamics NAV: OData vefslóð og aðgangslykill vefþjónustu fyrir notandareikning.</span><span class="sxs-lookup"><span data-stu-id="067c4-129">This means that you must get two pieces of information from Dynamics NAV: The OData URL and the web service access key for your user account.</span></span>  
<span data-ttu-id="067c4-130">**Veffangið sótt**</span><span class="sxs-lookup"><span data-stu-id="067c4-130">**Getting the URL**</span></span>  
<span data-ttu-id="067c4-131">Þegar Dynamics NAV er bætt við Power BI verður að tilgreina vefslóð þannig að Power Bi geti fá aðgang að gögnum fyrirtækisins.</span><span class="sxs-lookup"><span data-stu-id="067c4-131">When you add Dynamics NAV to Power BI, you must specify a URL so Power BI can access data from your company.</span></span> <span data-ttu-id="067c4-132">Í tengingarglugganum, er vísað til vefslóðar sem **OData streymisvefslóð**, og hann verður að vera á eftirfarandi sniði:</span><span class="sxs-lookup"><span data-stu-id="067c4-132">In the connection window, the URL is referred to as the **OData Feed URL**, and it must have the following format:</span></span>

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
<span data-ttu-id="067c4-133">Í þessu dæmi er *mybusiness* heiti Dynamics NAV þjónustu, og *CRONUS U.S.* er heiti sýndarfyrirtækinu með *% 20* sem táknar bil í heitinu.</span><span class="sxs-lookup"><span data-stu-id="067c4-133">In this example, *mybusiness* is the name of your Dynamics NAV service, and *CRONUS US* is the name of the demonstration company with *%20* representing the space in the name.</span></span>   
<span data-ttu-id="067c4-134">Til að fá vefslóð, í Dynamics NAV, leita að og opna gluggann **vefþjónustur**.</span><span class="sxs-lookup"><span data-stu-id="067c4-134">To get the URL, in Dynamics NAV, search for and open the **Web Services** window.</span></span> <span data-ttu-id="067c4-135">Í þessum glugga er listi yfir vefþjónustur sem eru nú tiltækar og hægt er að afrita tengillinn úr reitnum **OData vefslóð** fyrir eina af sjálfgefnu OData vefþjónustunum.</span><span class="sxs-lookup"><span data-stu-id="067c4-135">This window lists the web services that are currently available, and you can copy the link from the **OData URL** field for one of the default OData web services.</span></span>  
<span data-ttu-id="067c4-136">**Að komast yfir aðgangslykil vefþjónustu**</span><span class="sxs-lookup"><span data-stu-id="067c4-136">**Getting the web service access key**</span></span>  
<span data-ttu-id="067c4-137">Til að Nota gögn úr Dynamics NAV, í Power BI í á **tengjast Dynamics NAV** glugganum, verður að tilgreina notandanafn þitt, sem er tölvupóstreikningur þinn, og aðgangsorð.</span><span class="sxs-lookup"><span data-stu-id="067c4-137">In order to use data from Dynamics NAV, in Power BI, in the **Connect to Dynamics NAV** window, you must specify your user name, which is your email account, and a password.</span></span> <span data-ttu-id="067c4-138">Aðgangsorðið er aðgangslykill vefþjónustu sem er sett upp fyrir notandareikning þinn í Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="067c4-138">The password is the web service access key that is set up for your user account in Dynamics NAV.</span></span>  
<span data-ttu-id="067c4-139">Til að fá aðgangslykill vefþjónustu, í Dynamics NAV, leita að **Notendur** glugganum og síðan opna spjald fyrir notandareikning þinn.</span><span class="sxs-lookup"><span data-stu-id="067c4-139">To get a web service access key, in Dynamics NAV, search for the **Users** window, and then open the card for your user account.</span></span> <span data-ttu-id="067c4-140">Í á **aðgangur vefþjónustu** Flýtiflipanum, afrita efni reitsins á **aðgangslykill vefþjónustu** reit.</span><span class="sxs-lookup"><span data-stu-id="067c4-140">On the **Web Service Access** FastTab, copy the contents of the **Web Service Access Key** field.</span></span> <span data-ttu-id="067c4-141">Ef reiturinn er auður, í borðanum skaltu velja **Breyta aðgangslykill vefþjónustu**, velja **Lykillinn Rennur Aldrei út** og velja síðan hnappinn í lagi.</span><span class="sxs-lookup"><span data-stu-id="067c4-141">If the field is blank, in the ribbon, choose **Change Web Service Access Key**, choose the **Key Never Expires** field, and then choose the OK button.</span></span> <span data-ttu-id="067c4-142">Síðan er hægt að afrita lykill</span><span class="sxs-lookup"><span data-stu-id="067c4-142">You can then copy the key.</span></span>  

## <a name="getting-data-from-dynamics-nav"></a><span data-ttu-id="067c4-143">Sækja Gögnum úr Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="067c4-143">Getting Data from Dynamics NAV</span></span>
<span data-ttu-id="067c4-144">Dynamics NAV-yfirlit sýnir flestar dæmigerðum skýrslur sem þarf að nota til að rekja fyrirtækið.</span><span class="sxs-lookup"><span data-stu-id="067c4-144">The Dynamics NAV dashboard shows the most typical reports that you will want to use to track your business.</span></span> <span data-ttu-id="067c4-145">Gögnin eru fengin úr Dynamics NAV-fyrirtæki þíns með því að nota vefþjónustur til að lesa lifandi gögn.</span><span class="sxs-lookup"><span data-stu-id="067c4-145">The data is extracted from your Dynamics NAV company using web services to read live data.</span></span> <span data-ttu-id="067c4-146">Í Dynamics NAV, sýnir **vefþjónustu** gluggi listi yfir vefþjónustur sem hafa verið settar upp fyrir þig, þar á meðal eftirfarandi sem er notað af efnispakka í Power BI:</span><span class="sxs-lookup"><span data-stu-id="067c4-146">In Dynamics NAV, the **Web Services** window lists the web services that have been set up for you, including the following that are consumed by the content pack in Power BI:</span></span>  

- <span data-ttu-id="067c4-147">ItemSalesAndProfit</span><span class="sxs-lookup"><span data-stu-id="067c4-147">ItemSalesAndProfit</span></span>  
- <span data-ttu-id="067c4-148">ItemSalesByCustomer</span><span class="sxs-lookup"><span data-stu-id="067c4-148">ItemSalesByCustomer</span></span>  
- <span data-ttu-id="067c4-149">powerbifinance-setup</span><span class="sxs-lookup"><span data-stu-id="067c4-149">powerbifinance-setup</span></span>  
- <span data-ttu-id="067c4-150">SalesDashboard</span><span class="sxs-lookup"><span data-stu-id="067c4-150">SalesDashboard</span></span>  
- <span data-ttu-id="067c4-151">SalesOpportunities</span><span class="sxs-lookup"><span data-stu-id="067c4-151">SalesOpportunities</span></span>  
- <span data-ttu-id="067c4-152">SalesOrdersBySalesPerson</span><span class="sxs-lookup"><span data-stu-id="067c4-152">SalesOrdersBySalesPerson</span></span>  
- <span data-ttu-id="067c4-153">TopCustomerOverview</span><span class="sxs-lookup"><span data-stu-id="067c4-153">TopCustomerOverview</span></span>  

<span data-ttu-id="067c4-154">**Athuga skal að**: Ef þú breytir heiti einhverra þessara vefþjónusta munu gögnin ekki birtast í Power BI.</span><span class="sxs-lookup"><span data-stu-id="067c4-154">**Note**: If you change the name of any of these web services, the data will not show up in Power BI.</span></span>  
<span data-ttu-id="067c4-155">Ef þú vilt bæta við nota önnur gögn í Power BI verður þú að finna töflurnar í Dynamics NAV, sýna þær sem vefþjónustur og síðan bæta þeim við efnispakkann.</span><span class="sxs-lookup"><span data-stu-id="067c4-155">If you want to add use other data in Power BI, you must find the tables in Dynamics NAV, expose them as web services, and then add them to the content pack.</span></span> <span data-ttu-id="067c4-156">Þetta eru aðstæður fyrir lengra komna, og við mælum með að þú byrjar með gögn sem er nú þegar í boði í Power BI.</span><span class="sxs-lookup"><span data-stu-id="067c4-156">This is an advanced scenario, and we recommend that you start with the data that is already available in Power BI.</span></span>  

## <a name="troubleshooting"></a><span data-ttu-id="067c4-157">Úrræðaleit</span><span class="sxs-lookup"><span data-stu-id="067c4-157">Troubleshooting</span></span>
<span data-ttu-id="067c4-158">Power BI yfirlitið byggir á birtum vefþjónustum sem eru hér að ofan skráðar, og það mun sýna gögn sýnifyrirtæki eða eigin fyrirtæki þitt ef þú flytja inn gögn úr núverandi fjárhagsuppsetningarlausn þinni.</span><span class="sxs-lookup"><span data-stu-id="067c4-158">The Power BI dashboard relies on the published web services that are listed above, and it will show data from the demonstration company or your own company if you import data from your current finance-setup solution.</span></span> <span data-ttu-id="067c4-159">Hins vegar, ef eitthvað fer úrskeiðis, þessi kafli gefur lausn fyrir dæmigerður vandamál.</span><span class="sxs-lookup"><span data-stu-id="067c4-159">However, if something goes wrong, this section provides a workaround for the most typical issues.</span></span>  

<span data-ttu-id="067c4-160">**„Sannprófun færibreyta tókst ekki, vinsamlegast vertu viss um að allar færibreytur séu gildar“**</span><span class="sxs-lookup"><span data-stu-id="067c4-160">**"Parameter validation failed, please make sure all parameters are valid"**</span></span>  
<span data-ttu-id="067c4-161">Ef þú sérð þessa villumeldingu eftir að þú færir inn vefslóð Dynamics NAV skaltu tryggja að eftirfarandi kröfur eru fullnægt:</span><span class="sxs-lookup"><span data-stu-id="067c4-161">If you see this error after you enter your Dynamics NAV URL, make sure the following requirements are satisfied:</span></span>  

- <span data-ttu-id="067c4-162">Veffangið fylgir nákvæmlega þessum mynstri:</span><span class="sxs-lookup"><span data-stu-id="067c4-162">The URL follows exactly this pattern:</span></span>

    <span data-ttu-id="067c4-163">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span><span class="sxs-lookup"><span data-stu-id="067c4-163">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span></span>  
- <span data-ttu-id="067c4-164">Eyða öllum texti á eftir heiti fyrirtækis í svigum</span><span class="sxs-lookup"><span data-stu-id="067c4-164">Delete any text after the company name in parenthesis</span></span>  
- <span data-ttu-id="067c4-165">Ganga þarf úr skugga um að engin skaástrik komi í kjölfar vefslóðar</span><span class="sxs-lookup"><span data-stu-id="067c4-165">Make sure there are no trailing forward slash at the end of the URL.</span></span>  
- <span data-ttu-id="067c4-166">tryggja skal að um sé að ræða öruggra tengingu eins og tilgreint af Veffangið sem byrjar á *https*.</span><span class="sxs-lookup"><span data-stu-id="067c4-166">Make sure that it is a secure connection as indicated by the URL starting with *https*.</span></span>  


<span data-ttu-id="067c4-167">**„Innskráning mistókst“**</span><span class="sxs-lookup"><span data-stu-id="067c4-167">**"Login failed"**</span></span>  
<span data-ttu-id="067c4-168">Ef þú færð "innskráning mistókst" villu þegar notandinn skráir sig inn í yfirlitið, með því að nota innskráningarupplýsingar Dynamics NAV, þá getur eitt af eftirfarandi vandamálum valdið þessu:</span><span class="sxs-lookup"><span data-stu-id="067c4-168">If you get a "login failed" error when you log in to the dashboard, using your Dynamics NAV credentials, then this can be caused by one of the following issues:</span></span>

* <span data-ttu-id="067c4-169">Reikningur sem verið er að nota er ekki með heimildir til að lesa gögn Dynamics NAV úr reikninginn þínn.</span><span class="sxs-lookup"><span data-stu-id="067c4-169">The account you are using does not have permissions to read the Dynamics NAV data from your account.</span></span>

    <span data-ttu-id="067c4-170">Staðfesta notandareikning í Dynamics NAV, ganga úr skugga um að notaðar hafa verið rétt aðgangslykill vefþjónustu og reyndu síðan aftur.</span><span class="sxs-lookup"><span data-stu-id="067c4-170">Verify your user account in Dynamics NAV, and make sure that you have used the right web service access key as the password, and then try again.</span></span>  
* <span data-ttu-id="067c4-171">Tilvik Dynamics NAV sem verið er að reyna að tengjast er ekki með gilt SLL vottorð</span><span class="sxs-lookup"><span data-stu-id="067c4-171">The Dynamics NAV  instance that you are trying to connect to does not have a valid SSL certificate.</span></span> <span data-ttu-id="067c4-172">Í þessu tilviki sérðu nákvæmari villuboð ("ekki er hægt að stofna traust SSL samband").</span><span class="sxs-lookup"><span data-stu-id="067c4-172">In this case you'll see a more detailed error message ("unable to establish trusted SSL relationship").</span></span>

    <span data-ttu-id="067c4-173">**Athuga skal að**: sjálfárituð vottorð eru ekki studd.</span><span class="sxs-lookup"><span data-stu-id="067c4-173">**Note**: Self-signed certificates are not supported.</span></span>  


<span data-ttu-id="067c4-174">**"Úps"**</span><span class="sxs-lookup"><span data-stu-id="067c4-174">**"Oops"**</span></span>  
<span data-ttu-id="067c4-175">Ef þú sérð "Úps" villuglugga þegar þú ert kominn framhjá sannvottunarglugganum, er þetta oftast vegna vandamáls við að tengjast gögnum fyrir efnispakkann.</span><span class="sxs-lookup"><span data-stu-id="067c4-175">If you see an "Oops" error dialog after you pass the authentication dialog, this is most frequently caused by a problem connecting to the data for the content pack.</span></span>

* <span data-ttu-id="067c4-176">Sannprófa að vefslóð er samkvæmt mynstri sem var tilgreint áður.</span><span class="sxs-lookup"><span data-stu-id="067c4-176">Verify that the URL follows the pattern that was specified earlier:</span></span>

    <span data-ttu-id="067c4-177">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span><span class="sxs-lookup"><span data-stu-id="067c4-177">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span></span>  
* <span data-ttu-id="067c4-178">Algeng mistök eru að tilgreina fulla vefslóð fyrir tiltekna vefþjónustu.</span><span class="sxs-lookup"><span data-stu-id="067c4-178">A common mistake is to specify the full URL for a specific web service:</span></span>

    <span data-ttu-id="067c4-179">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup</span><span class="sxs-lookup"><span data-stu-id="067c4-179">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup</span></span>  
* <span data-ttu-id="067c4-180">Eða þú gætir hafa gleymt að tilgreina heiti fyrirtækis.</span><span class="sxs-lookup"><span data-stu-id="067c4-180">Or you might have forgotten to specify the company name:</span></span>

    <span data-ttu-id="067c4-181">https://mybusiness.projectmadeira.com:7048/MS/OData/</span><span class="sxs-lookup"><span data-stu-id="067c4-181">https://mybusiness.projectmadeira.com:7048/MS/OData/</span></span>  


## <a name="see-also"></a><span data-ttu-id="067c4-182">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="067c4-182">See Also</span></span>
[<span data-ttu-id="067c4-183">Velkomin í Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="067c4-183">Welcome to Dynamics NAV</span></span>](across-get-started.md)  

