---
title: "Uppsetning bókhaldslykilsins"
description: "Þú breytir sjálfgefnum lyklum og í bókhaldslyklum og hægt er að bæta við nýjum lyklum."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: COA, cha of acc
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b9ed31ae8e7478f57457ad68fd69d7809f706e2a
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-or-changing-the-chart-of-accounts"></a><span data-ttu-id="5e81a-103">Uppsetning eða breyting á bókhaldslykli</span><span class="sxs-lookup"><span data-stu-id="5e81a-103">Setting Up or Changing the Chart of Accounts</span></span>
<span data-ttu-id="5e81a-104">Bókhaldslykill sýnir fjárhagslykla sem geyma fjárhagsleg gögn.</span><span class="sxs-lookup"><span data-stu-id="5e81a-104">The chart of accounts shows the ledger accounts that store your financial data.</span></span> [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]<span data-ttu-id="5e81a-105"> inniheldur staðlaðan bókhaldslykil sem er tilbúin til að styðja þitt fyrirtæki.</span><span class="sxs-lookup"><span data-stu-id="5e81a-105"> includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="5e81a-106">Hins vegar er hægt að breyta sjálfgefnum lyklum og hægt er að bæta við nýjum lyklum.</span><span class="sxs-lookup"><span data-stu-id="5e81a-106">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="5e81a-107">Bæta við eða breyta lyklum</span><span class="sxs-lookup"><span data-stu-id="5e81a-107">Adding or Changing Accounts</span></span>
<span data-ttu-id="5e81a-108">Fyrir hvern bókhaldslykil er hægt að opna hvern einstakan fjárhagslykil og bæta við eða breyta stillingum.</span><span class="sxs-lookup"><span data-stu-id="5e81a-108">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

> [!NOTE]  
>   <span data-ttu-id="5e81a-109">Hægt er að eyða fjárhagsreikningur.</span><span class="sxs-lookup"><span data-stu-id="5e81a-109">You can delete a general ledger account.</span></span> <span data-ttu-id="5e81a-110">Áðu en honum er eytt þarf hins vegar eftirfarandi að vera rétt:</span><span class="sxs-lookup"><span data-stu-id="5e81a-110">However, before you delete it, the following must be true:</span></span>  

* <span data-ttu-id="5e81a-111">Staða reikningsins verður að vera núll.</span><span class="sxs-lookup"><span data-stu-id="5e81a-111">The balance on the account must be zero.</span></span>  
* <span data-ttu-id="5e81a-112">Reiturinn **Leyfa eyðingu fjárhagsr.fyrir** verður að vera stilltur í glugganum **Uppsetning fjárhags** og ekki mega vera fjárhagsfærslur í lyklinum frá og með þeim degi.</span><span class="sxs-lookup"><span data-stu-id="5e81a-112">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
* <span data-ttu-id="5e81a-113">Ef reiturinn **Athuga notkun fjárhagsr.** í glugganum **Uppsetning fjárhags** er valinn má ekki nota lykilinn í neinum bókunarflokkum eða bókunargrunnum.</span><span class="sxs-lookup"><span data-stu-id="5e81a-113">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="5e81a-114"> kemur í veg fyrir að fjárhagsreikningi sé eytt sem geymir gögn sem þarf í bókhaldslyklinum.</span><span class="sxs-lookup"><span data-stu-id="5e81a-114"> will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="5e81a-115">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="5e81a-115">See Also</span></span>
[<span data-ttu-id="5e81a-116">Fjárhagur og bókhaldslyklar</span><span class="sxs-lookup"><span data-stu-id="5e81a-116">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
[<span data-ttu-id="5e81a-117">Stjórna bankareikningum</span><span class="sxs-lookup"><span data-stu-id="5e81a-117">Managing Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="5e81a-118">Unnið með víddir</span><span class="sxs-lookup"><span data-stu-id="5e81a-118">Working with Dimensions</span></span>](finance-dimensions.md)  
[<span data-ttu-id="5e81a-119">Flytja inn úr öðrum fjárhagskerfum</span><span class="sxs-lookup"><span data-stu-id="5e81a-119">Importing from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="5e81a-120">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="5e81a-120">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

## 
