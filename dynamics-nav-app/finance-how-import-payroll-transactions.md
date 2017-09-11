---
title: "Hvernig á að: Flytja inn launafærslur "
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d5e70a0a1659c7facdeec3f0971eda43ff8a03cc
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-import-payroll-transactions"></a><span data-ttu-id="b388a-102">Hvernig á að: Flytja inn launafærslur </span><span class="sxs-lookup"><span data-stu-id="b388a-102">How to: Import Payroll Transactions</span></span>
<span data-ttu-id="b388a-103">Fyrir launagreiðslur og tengdar færslur verður að flytja inn og birta fjárhagslegar færslur úr launaveitu í fjárhag.</span><span class="sxs-lookup"><span data-stu-id="b388a-103">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span> <span data-ttu-id="b388a-104">Til að gera þetta verður að flytja inn csv.</span><span class="sxs-lookup"><span data-stu-id="b388a-104">To do this, you first import a csv.</span></span> <span data-ttu-id="b388a-105">skrá sem berst frá launaveitunni í gluggann **Færslubók**.</span><span class="sxs-lookup"><span data-stu-id="b388a-105">file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="b388a-106">Síðan varparðu ytri reikningunum í skránni launagreiðslur á viðeigandi fjárhagsreikninga.</span><span class="sxs-lookup"><span data-stu-id="b388a-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="b388a-107">Að lokum bókarðu launafærslur samkvæmt reikningsvörpuninni.</span><span class="sxs-lookup"><span data-stu-id="b388a-107">Lastly, you post the payroll transactions according to the account mapping.</span></span>

## <a name="to-import-a-payroll-file"></a><span data-ttu-id="b388a-108">Til að flytja inn launaskrá</span><span class="sxs-lookup"><span data-stu-id="b388a-108">To import a payroll file</span></span>
1. <span data-ttu-id="b388a-109">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Færslubókum**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="b388a-109">In the top right corner, choose the **Search for Page or Report** icon, enter **General Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="b388a-110">Í viðkomandi færslubókarkeyrslu skal velja **Flytja inn launafærslur**.</span><span class="sxs-lookup"><span data-stu-id="b388a-110">In the relevant general journal batch, choose the **Import Payroll Transactions** action.</span></span>
3. <span data-ttu-id="b388a-111">Í glugganum **Flytja inn** skal velja viðeigandi launaskrá og svo hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="b388a-111">In the **Import** window, select the relevant payroll file, and then choose the **OK** button.</span></span> <span data-ttu-id="b388a-112">Skráin verður að vera á CSV-sniði.</span><span class="sxs-lookup"><span data-stu-id="b388a-112">The file must be in CSV format.</span></span> 
4. <span data-ttu-id="b388a-113">Fylgdu leiðbeiningunum í **Flytja launafærslur** til að flytja inn færslur og varpa reikningum og veldu síðan hnappinn **Ljúka**.</span><span class="sxs-lookup"><span data-stu-id="b388a-113">Follow the steps in the **Import Payroll Transactions** window to import transactions and map accounts, and then choose the **Finish** button.</span></span>

    <span data-ttu-id="b388a-114">Færslubókin er fyllt út með línum sem varða færslur sem launagreiðsluskráin hefur að geyma og viðkomandi reikningsyfirlit í dálknum **Fjárhagsreikningur**.</span><span class="sxs-lookup"><span data-stu-id="b388a-114">The general journal is filled with lines representing the transactions that the payroll file contains and with the relevant accounts in the **G/L Account** column.</span></span>
4. <span data-ttu-id="b388a-115">Breyta skal eða bóka færslubókarlínur líkt og fyrir allar aðrar færslur í fjárhag.</span><span class="sxs-lookup"><span data-stu-id="b388a-115">Edit or post the journal lines as for any other general ledger transactions.</span></span> <span data-ttu-id="b388a-116">Frekari upplýsingar eru í [hvernig á að: vinna með almenn færslubók](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="b388a-116">For more information, see [How to: Work With General Journals](ui-work-general-journals.md).</span></span>   

## <a name="see-also"></a><span data-ttu-id="b388a-117">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="b388a-117">See Also</span></span>
[<span data-ttu-id="b388a-118">Fjármál</span><span class="sxs-lookup"><span data-stu-id="b388a-118">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="b388a-119">Hvernig á að: Vinna með almennum færslubókum</span><span class="sxs-lookup"><span data-stu-id="b388a-119">How to: Work With General Journals</span></span>](ui-work-general-journals.md)  

