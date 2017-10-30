---
title: "Hönnunarupplýsingar - lota fyrir lotu"
description: "Lærið að nota lota fyrir lotu regluna til að gera upp pöntunarmagn á grunni eftispurnar."
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
ms.openlocfilehash: 039afd9dd6f7e4c608b17229f5b438c23ba3624b
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-lot-for-lot"></a><span data-ttu-id="1f43c-103">Hönnunarupplýsingar: lota fyrir lotu</span><span class="sxs-lookup"><span data-stu-id="1f43c-103">Design Details: Lot-for-Lot</span></span>
<span data-ttu-id="1f43c-104">Lota-fyrir-lotu reglan er sveigjanlegust vegna þess að kerfið bregst bara við raunverulegri eftirspurn og bregst auk þess við væntanlegri eftirspurn samkvæmt spám og standandi pöntunum og ákvarðar svo magn pantanan á grundvelli eftirspurnarinnar.</span><span class="sxs-lookup"><span data-stu-id="1f43c-104">The lot-for-lot policy is the most flexible because the system only reacts on actual demand, plus it acts on anticipated demand from forecast and blanket orders and then settles the order quantity based on the demand.</span></span> <span data-ttu-id="1f43c-105">Lota-fyrir-lotu reglan beinist að A- og B-vörum þar sem hægt er að samþykkja birgðir en ætti helst að forðast það.</span><span class="sxs-lookup"><span data-stu-id="1f43c-105">The lot-for-lot policy is aimed at A- and B-items where inventory can be accepted but should be avoided.</span></span>  
  
<span data-ttu-id="1f43c-106">Að sumu leyti er lota fyrir lotu stefnan eins og pantanastefnan en er með almenna nálgun á vörur; það getur samþykkt magn í birgðum, og það flokkareftirspurn og samsvarandi framboð í tímarömmum skilgreindum af notanda.</span><span class="sxs-lookup"><span data-stu-id="1f43c-106">In some ways, the lot-for-lot policy looks like the Order policy, but it has a generic approach to items; it can accept quantities in inventory, and it bundles demand and corresponding supply in time buckets defined by the user.</span></span>  
  
<span data-ttu-id="1f43c-107">Tímaramminn er skilgreindum í reitnum **Tímarammi**.</span><span class="sxs-lookup"><span data-stu-id="1f43c-107">The time bucket is defined in the **Time Bucket** field.</span></span> <span data-ttu-id="1f43c-108">Kerfið vinnur með lágmarks tímaramma upp á einn dag, þar sem það er minnsta tímamælieining fyrir birgðir og eftirspurn í kerfin (þó svo að í raun geti tímamælieining á framleiðslupöntunum og íhlutaþörfum verið sekúndur).</span><span class="sxs-lookup"><span data-stu-id="1f43c-108">The system works with a minimum time bucket of one day, since this is the smallest time unit of measure on demand and supply events in the system (although, in practice, the time unit of measure on production orders and component needs can be seconds).</span></span>  
  
<span data-ttu-id="1f43c-109">Tímaramminn setur einnig takmörkun á það hvenær birgðapöntun er enduráætluð til að mæta tiltekinni eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="1f43c-109">The time bucket also sets limits on when an existing supply order should be rescheduled to meet a given demand.</span></span> <span data-ttu-id="1f43c-110">Ef framboð er innan tímarammans verður það enduráætlað inn eða út til að svara eftirspurninni.</span><span class="sxs-lookup"><span data-stu-id="1f43c-110">If the supply lies within the time bucket, it will be rescheduled in or out to meet the demand.</span></span> <span data-ttu-id="1f43c-111">Annars, ef það liggur fyrr, mun það valda óþarfa uppsöfnun birgða og ætti að afturkalla.</span><span class="sxs-lookup"><span data-stu-id="1f43c-111">Otherwise, if it lies earlier, it will cause unnecessary build-up of inventory and should be canceled.</span></span> <span data-ttu-id="1f43c-112">Ef það er síðar verður nýtt framboð stofnað í staðinn.</span><span class="sxs-lookup"><span data-stu-id="1f43c-112">If it lies later, a new supply order will be created instead.</span></span>  
  
<span data-ttu-id="1f43c-113">Með þessari reglu er einnig mögulegt að skilgreina öryggisbirgðir til að bæta upp hugsanlegar sveiflur á birgðum eða til að mæta skyndilegri eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="1f43c-113">With this policy, it is also possible to define a safety stock in order to compensate for possible fluctuations in supply, or to meet sudden demand.</span></span>  
  
<span data-ttu-id="1f43c-114">Þar sem birgðapöntunarmagn byggir á raunveruleg eftirspurn getur það borgað sig að nota raðabreytur: slétta pöntunarmagn til að það passi við tiltekna pöntunarstuðul (eða innkaupamælieiningu), auka pöntuina upp í tiltekið magn, eða minnka magnið í hámarksmagn (og því búa til tvær eða fleiri birgðir til að uppfylla allt magnið).</span><span class="sxs-lookup"><span data-stu-id="1f43c-114">Because the supply order quantity is based on the actual demand it can make sense to use the order modifiers: round the order quantity up to meet a specified order multiple (or purchase unit of measure), increase the order to a specified minimum order quantity, or decrease the quantity to the specified maximum quantity (and thus create two or more supplies to reach the total needed quantity).</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="1f43c-115">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="1f43c-115">See Also</span></span>  
<span data-ttu-id="1f43c-116">[Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="1f43c-116">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="1f43c-117">[Hönnunarupplýsingar: Áætlunarfæribreytur](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="1f43c-117">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="1f43c-118">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="1f43c-118">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="1f43c-119">Hönnunarupplýsingar: framboðsáætlun</span><span class="sxs-lookup"><span data-stu-id="1f43c-119">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)