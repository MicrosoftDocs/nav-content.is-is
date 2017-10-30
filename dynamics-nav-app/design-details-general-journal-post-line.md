---
title: "Hönnunarupplýsingar: Bókunarlína færslubókar"
description: "Þetta efnisatriði veitir upplýsingar um hugtökin og reglurnar sem eru notaðar til að endurhanna bókarlínur færslubókarinnar í [!INCLUDE[d365fin](includes/d365fin_md.md)]."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, general journal, posting, codeunit 12
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f6fd873a34e40b7f795c8f8f687bf3f198f437b5
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-general-journal-post-line"></a><span data-ttu-id="a4fd2-103">Hönnunarupplýsingar: Bókunarlína færslubókar</span><span class="sxs-lookup"><span data-stu-id="a4fd2-103">Design Details: General Journal Post Line</span></span>
<span data-ttu-id="a4fd2-104">Þessi fylgiskjöl veita nákvæmar tæknilegar upplýsingar fyrir hugtökin og reglurnar sem eru notaðar til að endurhanna bókarlínur færslubókarinnar í [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="a4fd2-104">This documentation provides detailed technical insight into the concepts and principles that are used to redesign the general journal posting line feature in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="a4fd2-105">Endurhönnunin gerir kóðaeiningu 12 einfaldari og auðveldari að viðhalda.</span><span class="sxs-lookup"><span data-stu-id="a4fd2-105">The redesign makes codeunit 12 simpler and more maintainable.</span></span> <span data-ttu-id="a4fd2-106">Skjölin byrjar með því að lýsa huglæg yfirlit yfir endurhönnun.</span><span class="sxs-lookup"><span data-stu-id="a4fd2-106">The documentation starts by describing conceptual overviews of the redesign.</span></span> <span data-ttu-id="a4fd2-107">Þá er tæknistrúktúr útskýrður til að sýna breytingar eftir endurhönnun.</span><span class="sxs-lookup"><span data-stu-id="a4fd2-107">Then it explains the technical architecture to show the changes that result from the redesign.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="a4fd2-108">Í þessum hluta</span><span class="sxs-lookup"><span data-stu-id="a4fd2-108">In This Section</span></span>  
[<span data-ttu-id="a4fd2-109">Yfirlit bókunarlínu færslubókar</span><span class="sxs-lookup"><span data-stu-id="a4fd2-109">General Journal Post Line Overview</span></span>](design-details-general-journal-post-line-overview.md)  
[<span data-ttu-id="a4fd2-110">Hönnunarupplýsingar: Uppbygging bókunarviðmóts</span><span class="sxs-lookup"><span data-stu-id="a4fd2-110">Design Details: Posting Interface Structure</span></span>](design-details-posting-interface-structure.md)  
[<span data-ttu-id="a4fd2-111">Hönnunarupplýsingar: Uppbygging bókunarvélar</span><span class="sxs-lookup"><span data-stu-id="a4fd2-111">Design Details: Posting Engine Structure</span></span>](design-details-posting-engine-structure.md)  
[<span data-ttu-id="a4fd2-112">Kóðaeining 12 Breytingar: Vörpun altækra breyta fyrir bókunarlínu færslubókar</span><span class="sxs-lookup"><span data-stu-id="a4fd2-112">Codeunit 12 Changes: Mapping Global Variables for General Journal Post Line</span></span>](design-details-codeunit-12-changes-mapping-global-variables-for-general-journal-post-line.md)  
[<span data-ttu-id="a4fd2-113">Kóðaeining 12 Breytingar: Breytingar á bókunaraðferðum í færslubók</span><span class="sxs-lookup"><span data-stu-id="a4fd2-113">Codeunit 12 Changes: Changes in General Journal Post Procedures</span></span>](design-details-codeunit-12-changes-changes-in-general-journal-post-procedures.md)  

## <a name="see-also"></a><span data-ttu-id="a4fd2-114">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="a4fd2-114">See Also</span></span>  
[<span data-ttu-id="a4fd2-115">Vinna í færslubókum</span><span class="sxs-lookup"><span data-stu-id="a4fd2-115">Working with General Journals</span></span>](ui-work-general-journals.md)

