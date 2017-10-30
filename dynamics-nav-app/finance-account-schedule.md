---
title: "Fjárhagsskema"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5a072d9b0984adf8bf4ab89fb26d658cb13f50f0
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---

# <a name="account-schedules"></a><span data-ttu-id="c14db-102">Fjárhagsskema</span><span class="sxs-lookup"><span data-stu-id="c14db-102">Account Schedules</span></span>
<span data-ttu-id="c14db-103">Með fjárhagsskema er hægt að fá nákvæma innsýn í fjárhagsgögn.</span><span class="sxs-lookup"><span data-stu-id="c14db-103">With account schedules, you can get detailed insights into your financial data.</span></span> <span data-ttu-id="c14db-104">Hægt er að setja upp margvísleg útlit til að skilgreina upplýsingarnar sem á að finna í bókhaldslyklinum. Bókhaldslykilinn geymir fjárhagsleg gögn, en stundum gætir þú viljað fá yfirlit yfir gögn sem bókhaldslykillinn getur ekki sýnt.</span><span class="sxs-lookup"><span data-stu-id="c14db-104">You can set up various layouts to define the information that you want to extract from the chart of accounts The chart of accounts stores your financial data, but sometimes you want to get a view on your data that the chart of accounts cannot really show.</span></span> <span data-ttu-id="c14db-105">Í þeim tilfellum eru fjárhagsskemu notuð til að greina upphæðir í fjárhagsreikningi og bera saman fjárhagsfærslur og færslur í fjárhagsáætlunarskýrslu.</span><span class="sxs-lookup"><span data-stu-id="c14db-105">So you use account schedules to analyze figures in general ledger accounts and to compare general ledger entries with general ledger budget entries.</span></span>
<span data-ttu-id="c14db-106">Til dæmis, ætlir þú að reikna millisamtölu fyrir hóp reikninga og þú vilt hafa þessar millisamtölur í nýjum samtölum, og svo framvegis.</span><span class="sxs-lookup"><span data-stu-id="c14db-106">For example, you want to calculate subtotals for groups of accounts, and you want to include these subtotals in new totals, and so on.</span></span>
<span data-ttu-id="c14db-107">Dynamics NAV felur í sér sýnifjárhagsskemu sem eru notuð til að búa til myndrit á heimasíðu fyrirtækisins.</span><span class="sxs-lookup"><span data-stu-id="c14db-107">Dynamics NAV includes sample account schedules that are used to generate the charts on your Home page.</span></span> <span data-ttu-id="c14db-108">Einnig er hægt að búa til fjárhagskemu til að reikna út hagnaðarhlutfall fyrir víddir eins og deildir eða hópa viðskiptamanna.</span><span class="sxs-lookup"><span data-stu-id="c14db-108">You can also create account schedules to calculate profit margins on such dimensions as departments or customer groups.</span></span>  

<span data-ttu-id="c14db-109">Uppsetning fjárhagsskema krefst skilnings á fjárhagsgögnum í bókhaldslyklinum.</span><span class="sxs-lookup"><span data-stu-id="c14db-109">Setting up account schedules requires an understanding of the financial data in the chart of accounts.</span></span>
<span data-ttu-id="c14db-110">Hægt er til dæmis að skoða fjárhagsfærslur sem prósentuhlutfall af áætlunarfærslum.</span><span class="sxs-lookup"><span data-stu-id="c14db-110">For example, you can view general ledger entries as percentages of budget entries.</span></span>
<span data-ttu-id="c14db-111">Hægt er að nota eitt af sjálfgefnum sniðum fyrir fjárhagsskema eða setja upp eigin raðir og dálka svo hægt sé að ákveða nákvæmlega hvaða tölur á að bera saman og hvernig.</span><span class="sxs-lookup"><span data-stu-id="c14db-111">You can use one of the default layouts for your account schedule, or you can set up your own rows and columns so that you can decide exactly which figures you wish to compare and how.</span></span>
<span data-ttu-id="c14db-112">Þetta þýðir að hægt er að búa til eins margar sérsniðnar fjárhagsskýrslur og óskað er.</span><span class="sxs-lookup"><span data-stu-id="c14db-112">This means that you can create as many customized financial statements as you want.</span></span> <span data-ttu-id="c14db-113">Glugginn **Fjárhagsskema** er notaður til að setja upp fjárhagsskemu.</span><span class="sxs-lookup"><span data-stu-id="c14db-113">You use the **Account Schedule** window to set up account schedules.</span></span>  

## <a name="account-categories-and-account-schedules"></a><span data-ttu-id="c14db-114">Lykiltegundir og fjárhagsskemu</span><span class="sxs-lookup"><span data-stu-id="c14db-114">Account Categories and Account Schedules</span></span>
<span data-ttu-id="c14db-115">Hægt er að nota lykiltegundir til að breyta sniði fjárhagsskýrslna.</span><span class="sxs-lookup"><span data-stu-id="c14db-115">You can use account categories to change the layout of your financial statements.</span></span> <span data-ttu-id="c14db-116">Þegar lykiltegundir hafa verið settar upp í glugganum **Flokkar fjárhagsreikninga** og aðgerðin **Mynda fjárhagsskemu** er valin, eru undirliggjandi fjárhagsskemu fyrir kjarnaviðskiptaskýrslur uppfærð.</span><span class="sxs-lookup"><span data-stu-id="c14db-116">When you have set up your account categories in the **G/L Account Categories** window, and you choose the **Generate Account Schedules** action, the underlying account schedules for the core financial reports are updated.</span></span> <span data-ttu-id="c14db-117">næst þegar einhver af þessum skýrslum er keyrð, eins og stöðuyfirlit, er nýjum samtölum og undirfærslum bætt við, samkvæmt þeim breytingum sem gerðar voru.</span><span class="sxs-lookup"><span data-stu-id="c14db-117">the next time you run one of these reports, such as the balance statement, new totals and subentries are added, based on your changes.</span></span> <span data-ttu-id="c14db-118">Frekari upplýsingar er að finna í [Fjárhagur og bókhaldslyklar](finance-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="c14db-118">For more information, see [The General Ledger and the Chart of Accounts](finance-general-ledger.md).</span></span>    
## <a name="see-also"></a><span data-ttu-id="c14db-119">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="c14db-119">See Also</span></span>
[<span data-ttu-id="c14db-120">Fjármál</span><span class="sxs-lookup"><span data-stu-id="c14db-120">Finance</span></span>](finance.md)  
[<span data-ttu-id="c14db-121">Uppsetning fjármála</span><span class="sxs-lookup"><span data-stu-id="c14db-121">Set Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="c14db-122">Fjárhagur og bókhaldslyklar</span><span class="sxs-lookup"><span data-stu-id="c14db-122">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
