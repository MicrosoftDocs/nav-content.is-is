---
title: "Setja upp eða breyta bókhaldslykill."
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
ms.openlocfilehash: 2a2f1f2ec3ac5bdd935ec19c11d74e16bdee7686
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="set-up-or-change-the-chart-of-accounts"></a><span data-ttu-id="e77fa-102">Setja upp eða breyta bókhaldslykill.</span><span class="sxs-lookup"><span data-stu-id="e77fa-102">Set Up or Change the Chart of Accounts</span></span>
<span data-ttu-id="e77fa-103">Bókhaldslykill sýnir fjárhagslykla sem geyma fjárhagsleg gögn.</span><span class="sxs-lookup"><span data-stu-id="e77fa-103">The chart of accounts shows the ledger accounts that store your financial data.</span></span> <span data-ttu-id="e77fa-104">Dynamics NAV innifelur staðlaðan bókhaldslykil sem er tilbúin til að styðja þitt fyrirtæki.</span><span class="sxs-lookup"><span data-stu-id="e77fa-104">Dynamics NAV includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="e77fa-105">Hins vegar er hægt að breyta sjálfgefnum lyklum og hægt er að bæta við nýjum lyklum.</span><span class="sxs-lookup"><span data-stu-id="e77fa-105">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="e77fa-106">Bæta við eða breyta lyklum</span><span class="sxs-lookup"><span data-stu-id="e77fa-106">Adding or Changing Accounts</span></span>
<span data-ttu-id="e77fa-107">Fyrir hvern bókhaldslykil er hægt að opna hvern einstakan fjárhagslykil og bæta við eða breyta stillingum.</span><span class="sxs-lookup"><span data-stu-id="e77fa-107">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

<span data-ttu-id="e77fa-108">**Athugasemd**: Hægt er að eyða fjárhagsreikningi.</span><span class="sxs-lookup"><span data-stu-id="e77fa-108">**Note**: You can delete a general ledger account.</span></span> <span data-ttu-id="e77fa-109">Áðu en honum er eytt þarf hins vegar eftirfarandi að vera rétt:</span><span class="sxs-lookup"><span data-stu-id="e77fa-109">However, before you delete it, the following must be true:</span></span>  
- <span data-ttu-id="e77fa-110">Staða reikningsins verður að vera núll.</span><span class="sxs-lookup"><span data-stu-id="e77fa-110">The balance on the account must be zero.</span></span>  
- <span data-ttu-id="e77fa-111">Reiturinn **Leyfa eyðingu fjárhagsr.fyrir** verður að vera stilltur í glugganum **Uppsetning fjárhags** og ekki mega vera fjárhagsfærslur í lyklinum frá og með þeim degi.</span><span class="sxs-lookup"><span data-stu-id="e77fa-111">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
- <span data-ttu-id="e77fa-112">Ef reiturinn **Athuga notkun fjárhagsr.** í glugganum **Uppsetning fjárhags** er valinn má ekki nota lykilinn í neinum bókunarflokkum eða bókunargrunnum.</span><span class="sxs-lookup"><span data-stu-id="e77fa-112">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

<span data-ttu-id="e77fa-113">Dynamics NAV kemur í veg fyrir að fjárhagsreikningi sé eytt sem geymir gögn sem þarf í bókhaldslyklinum.</span><span class="sxs-lookup"><span data-stu-id="e77fa-113">Dynamics NAV will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

##<a name="see-also"></a><span data-ttu-id="e77fa-114">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="e77fa-114">See Also</span></span>  
[<span data-ttu-id="e77fa-115">Fjárhagur og bókhaldslyklar</span><span class="sxs-lookup"><span data-stu-id="e77fa-115">The General Ledger and the Chart of Accounts</span></span>](finance-setup-general-ledger.md)  
[<span data-ttu-id="e77fa-116">Stjórna bankareikningum</span><span class="sxs-lookup"><span data-stu-id="e77fa-116">Manage Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="e77fa-117">Víddir</span><span class="sxs-lookup"><span data-stu-id="e77fa-117">Dimensions</span></span>](finance-setup-dimensions.md)  
[<span data-ttu-id="e77fa-118">Hvernig á að: Vinna með GIFI-kóða í Kanada</span><span class="sxs-lookup"><span data-stu-id="e77fa-118">How to: Work With GIFI Codes in Canada</span></span>](ca-finance-setup-work-GiFI-codes.md)

