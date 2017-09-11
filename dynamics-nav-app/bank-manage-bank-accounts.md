---
title: "Stjórna bankareikningum"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: d97c3afba0e899768bda1b637c4f288db210d38c
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="manage-bank-accounts"></a><span data-ttu-id="18f73-102">Stjórna bankareikningum</span><span class="sxs-lookup"><span data-stu-id="18f73-102">Manage Bank Accounts</span></span>
<span data-ttu-id="18f73-103">Með reglulegu millibili þarf að stemma bankareikningsfærslur í Dynamics NAV við viðkomandi bankafærslur í bankareikningum í bankanum þínum, og bóka svo stöðuna á þinn bankareikning.</span><span class="sxs-lookup"><span data-stu-id="18f73-103">At regular intervals, you must reconcile your bank ledger entries in Dynamics NAV with the related bank transactions in bank accounts at your bank, and then post the balance to your bank account.</span></span> <span data-ttu-id="18f73-104">Hægt er að framkvæma þetta verk, annað hvort sem hluta af vinnslu á greiðslum sem koma fram á bankayfirliti í **greiðsluafstemmingarbók**.</span><span class="sxs-lookup"><span data-stu-id="18f73-104">You can perform this task either as part of processing the payments represented on a bank statement in the **Payment Reconciliation Journal**.</span></span> <span data-ttu-id="18f73-105">Einnig er hægt að framkvæma verkið sérstaklega úr greiðsluvinnslu, í glugganum **Afstemming bankareiknings** sem styður tékkafærslur.</span><span class="sxs-lookup"><span data-stu-id="18f73-105">Alternatively, you can perform the task separately from payment processing, in the **Bank Acc. Reconciliation** window, which supports check ledger entries.</span></span> <span data-ttu-id="18f73-106">Í báðum tilvikum er fyllt í gluggann með innflutningi á bankayfirlitið í Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="18f73-106">In both cases, you fill the windows by importing the bank statement into Dynamics NAV.</span></span>

<span data-ttu-id="18f73-107">Stundum þarf að færa upphæðir milli bankareikninga í Dynamics NAV til að endurspegla millifærslur í bankanum þínum.</span><span class="sxs-lookup"><span data-stu-id="18f73-107">Sometimes, you need to transfer amounts between bank account in Dynamics NAV to reflect transfers at your bank.</span></span> <span data-ttu-id="18f73-108">Þú framkvæmir þetta verk í flugganum **almenn Færslubók** með mismunandi hætti eftir gjaldmiðli sjóðanna.</span><span class="sxs-lookup"><span data-stu-id="18f73-108">You perform this task in the **General Journal** window, in different ways depending on the currency of the funds.</span></span>

<span data-ttu-id="18f73-109">Áður en hægt er að stjórna bankareikningum verður að stofna sérhvern bankareikning sem bankareikningsspjald.</span><span class="sxs-lookup"><span data-stu-id="18f73-109">Before you can manage bank accounts, you must set each bank account up as a bank account card.</span></span> <span data-ttu-id="18f73-110">Þar að auki þarf að setja upp rafrænar þjónustu sem má nota fyrir innflutning bankayfirlits og útflutning greiðsluskrár.</span><span class="sxs-lookup"><span data-stu-id="18f73-110">In addition, you must set up electronic services that you may use for bank statement import and payment file export.</span></span> <span data-ttu-id="18f73-111">Nánari upplýsingar um það eru í [Setja upp bankareikninga](bank-setup-banking.md).</span><span class="sxs-lookup"><span data-stu-id="18f73-111">For more information, see [Set Up Bank Accounts](bank-setup-banking.md).</span></span>

<span data-ttu-id="18f73-112">Eftirfarandi tafla lýsir röð verkefna með tenglum í efnisatriði þar sem þeim er lýst.</span><span class="sxs-lookup"><span data-stu-id="18f73-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

|<span data-ttu-id="18f73-113">Til</span><span class="sxs-lookup"><span data-stu-id="18f73-113">To</span></span> |<span data-ttu-id="18f73-114">Sjá</span><span class="sxs-lookup"><span data-stu-id="18f73-114">See</span></span> |
|---|----|
|<span data-ttu-id="18f73-115">Afstemma bankareikninga í tengslum við greiðsluvinnslu í glugganum **greiðsluafstemmingarbók**</span><span class="sxs-lookup"><span data-stu-id="18f73-115">Reconcile bank accounts in connection with payment processing in the **Payment Reconciliation Journal** window.</span></span>|[<span data-ttu-id="18f73-116">Jafna greiðslur sjálfkrafa og afstemma bankareikninga</span><span class="sxs-lookup"><span data-stu-id="18f73-116">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|<span data-ttu-id="18f73-117">Afstemma bankareikninga sem sérstakt verk í reitinn **afstemming bankareiknings** glugganum, þar með talið tékkafærslur.</span><span class="sxs-lookup"><span data-stu-id="18f73-117">Reconcile bank accounts, including check ledger entries, as a separate task in the **Bank Acc. Reconciliation** window.</span></span>|[<span data-ttu-id="18f73-118">Hvernig á að: Afstemma bankareikninga hvern fyrir sig</span><span class="sxs-lookup"><span data-stu-id="18f73-118">How to: Reconcile Bank Accounts Separately</span></span>](bank-how-reconcile-bank-accounts-separately.md)|
|<span data-ttu-id="18f73-119">Bóka færslur milli bankareikninga í sama gjaldmiðli eða í öðrum gjaldmiðlum.</span><span class="sxs-lookup"><span data-stu-id="18f73-119">Post transfers between bank accounts in the same currency or in different currencies.</span></span>|[<span data-ttu-id="18f73-120">Hvernig á að: Flytja bankainnistæður</span><span class="sxs-lookup"><span data-stu-id="18f73-120">How to: Transfer Bank Funds</span></span>](bank-how-transfer-bank-funds.md)
## <a name="see-also"></a><span data-ttu-id="18f73-121">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="18f73-121">See Also</span></span>  
[<span data-ttu-id="18f73-122">Uppsetning bankaþjónustu</span><span class="sxs-lookup"><span data-stu-id="18f73-122">Set Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="18f73-123">Umsjón viðskiptakrafna</span><span class="sxs-lookup"><span data-stu-id="18f73-123">Manage Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="18f73-124">[Umsjón viðskiptaskulda](payables-manage-payables.md)  </span><span class="sxs-lookup"><span data-stu-id="18f73-124">[Manage Payables](payables-manage-payables.md)  </span></span>  
[<span data-ttu-id="18f73-125">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="18f73-125">Work With Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="18f73-126">Yfir viðskiptasvið</span><span class="sxs-lookup"><span data-stu-id="18f73-126">Across Business Areas</span></span>](ui-across-business-areas.md)

