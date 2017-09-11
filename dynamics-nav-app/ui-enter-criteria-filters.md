---
title: "Afmörkun skjalanna"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: df386e1195db385ee053b69fec0f5082d8df4116
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="entering-criteria-in-filters"></a><span data-ttu-id="8ea48-102">Afmörkun skjalanna</span><span class="sxs-lookup"><span data-stu-id="8ea48-102">Entering Criteria in Filters</span></span>
<span data-ttu-id="8ea48-103">Til að leita að gögnum, svo sem heiti viðskiptamanna, aðsetrum eða vöruhópum er hægt að setja inn skilyrði.</span><span class="sxs-lookup"><span data-stu-id="8ea48-103">When you want to search for data, such as customer names, addresses, or product groups, you enter criteria.</span></span> <span data-ttu-id="8ea48-104">Í leitarskilyrðum er hægt að nota alla sömu tölustafi og bókstafi sem venjulega eru notaðir í reitnum.</span><span class="sxs-lookup"><span data-stu-id="8ea48-104">In search criteria you can use all the numbers and letters that you normally use in the specific field.</span></span> <span data-ttu-id="8ea48-105">Ennfremur er hægt að nota sértákn til að afmarka niðurstöðurnar frekar.</span><span class="sxs-lookup"><span data-stu-id="8ea48-105">In addition, you can use special symbols to further filter the results.</span></span>

## <a name="searching-using-the-quick-filter"></a><span data-ttu-id="8ea48-106">Leita með því að nota flýtiafmörkun</span><span class="sxs-lookup"><span data-stu-id="8ea48-106">Searching using the Quick Filter</span></span>
<span data-ttu-id="8ea48-107">Hægt er að bæta afmörkunum við allar síður með því að nota flýtiafmörkun.</span><span class="sxs-lookup"><span data-stu-id="8ea48-107">You can add filters to all pages by using the Quick Filter.</span></span> <span data-ttu-id="8ea48-108">Flýtiafmörkun er virkjuð með því að velja stækkunarglerstáknið í efra hægra horni síðu.</span><span class="sxs-lookup"><span data-stu-id="8ea48-108">The Quick Filter is enabled by choosing the magnifier icon in the top right corner of a page.</span></span> <span data-ttu-id="8ea48-109">Þessi síugerð er notuð fyrir flýtiinnfærslu viðmiða.</span><span class="sxs-lookup"><span data-stu-id="8ea48-109">This filtering type is used for a fast entry of criteria.</span></span>

<span data-ttu-id="8ea48-110">**Mikilvægt**: Flýtiafmörkun veitir auðveldan aðgang að afmörkunargögnum með því að færa inn texta án sniðtákna en veitir einnig margs konar valkosti fyrir leitarskilyrði.</span><span class="sxs-lookup"><span data-stu-id="8ea48-110">**Important**: The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options.</span></span> <span data-ttu-id="8ea48-111">Það fer eftir því hvort þú slærð texta eða texta með táknum, flýtiafmörkun hagar sér öðruvísi.</span><span class="sxs-lookup"><span data-stu-id="8ea48-111">Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.</span></span>  
- <span data-ttu-id="8ea48-112">Ef ósniðinn texti er sleginn inn í leitarskilyrðum eru leitarskilyrðin túlkuð sem leit óháð há- og lágstöfum sem inniheldur ákveðinn texta.</span><span class="sxs-lookup"><span data-stu-id="8ea48-112">If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.</span></span>  
- <span data-ttu-id="8ea48-113">Ef texti með táknum er sleginn inn í leitarskilyrðum eru leitarskilyrðin túlkuð nákvæmlega eins og þau voru slegin inn og leitin er háð há- og lágstöfum.</span><span class="sxs-lookup"><span data-stu-id="8ea48-113">If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive.</span></span>

### <a name="quick-filter-criteria"></a><span data-ttu-id="8ea48-114">Skilyrði flýtiafmörkunar</span><span class="sxs-lookup"><span data-stu-id="8ea48-114">Quick filter criteria</span></span>
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH><span data-ttu-id="8ea48-115">Leitarskilyrði</span><span class="sxs-lookup"><span data-stu-id="8ea48-115">Search Criteria</span></span></TH>
    <TH><span data-ttu-id="8ea48-116">Túlkað sem...</span><span class="sxs-lookup"><span data-stu-id="8ea48-116">Interpreted as...</span></span></TH>
    <TH><span data-ttu-id="8ea48-117">Vöruskil...</span><span class="sxs-lookup"><span data-stu-id="8ea48-117">Returns...</span></span></TH>
  </TR>
  <TR>
    <TD><span data-ttu-id="8ea48-118">>man</span><span class="sxs-lookup"><span data-stu-id="8ea48-118">>man</span></span></TD>
    <TD><span data-ttu-id="8ea48-119">@*karlmaður*</span><span class="sxs-lookup"><span data-stu-id="8ea48-119">@*man*</span></span></TD>
    <TD><span data-ttu-id="8ea48-120">Allar færslur þurfa að innihalda textann man og rétta há- og lágstafi.</span><span class="sxs-lookup"><span data-stu-id="8ea48-120">All records that contain the text man and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8ea48-121">>se</span><span class="sxs-lookup"><span data-stu-id="8ea48-121">>se</span></span></TD>
    <TD><span data-ttu-id="8ea48-122">@*se*</span><span class="sxs-lookup"><span data-stu-id="8ea48-122">@*se*</span></span></TD>
    <TD><span data-ttu-id="8ea48-123">Allar færslur þurfa að innihalda textann se og rétta há- og lágstafi.</span><span class="sxs-lookup"><span data-stu-id="8ea48-123">All records that contain the text se and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8ea48-124">>Karl*</span><span class="sxs-lookup"><span data-stu-id="8ea48-124">>Man*</span></span></TD>
    <TD><span data-ttu-id="8ea48-125">Hefst á Man og greinarmunur á litlum og stórum stöfum.</span><span class="sxs-lookup"><span data-stu-id="8ea48-125">Starts with Man and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="8ea48-126">Allar færslur sem byrja á textanum Man</span><span class="sxs-lookup"><span data-stu-id="8ea48-126">All records that start with the text Man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8ea48-127">‚man‘</span><span class="sxs-lookup"><span data-stu-id="8ea48-127">'man'</span></span></TD>
    <TD><span data-ttu-id="8ea48-128">Nákvæmur texti og greinarmunur á litlum og stórum stöfum.</span><span class="sxs-lookup"><span data-stu-id="8ea48-128">An exact text and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="8ea48-129">Allar færslur sem samsvara man nákvæmlega.</span><span class="sxs-lookup"><span data-stu-id="8ea48-129">All records that match man exactly.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8ea48-130">@*man</span><span class="sxs-lookup"><span data-stu-id="8ea48-130">@*man</span></span></TD>
    <TD><span data-ttu-id="8ea48-131">Lýkur á og enginn greinarmunur á litlum og stórum stöfum.</span><span class="sxs-lookup"><span data-stu-id="8ea48-131">Ends with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="8ea48-132">Allar færslur sem enda á man.</span><span class="sxs-lookup"><span data-stu-id="8ea48-132">All records that end with man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="8ea48-133">@man*</span><span class="sxs-lookup"><span data-stu-id="8ea48-133">@man*</span></span></TD>
    <TD><span data-ttu-id="8ea48-134">Hefst á og enginn greinarmunur á litlum og stórum stöfum.</span><span class="sxs-lookup"><span data-stu-id="8ea48-134">Starts with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="8ea48-135">Allar færslur sem byrja á man.</span><span class="sxs-lookup"><span data-stu-id="8ea48-135">All records that start with man.</span></span></TD>
  </TR>
</TABLE>

<span data-ttu-id="8ea48-136">**Athugasemd**: Ekki er hægt að nota algildisstafi þegar afmarkanir eru á tölusettum reitum, til dæmis reiturinn **Staða** á sölupöntunum.</span><span class="sxs-lookup"><span data-stu-id="8ea48-136">**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders.</span></span> <span data-ttu-id="8ea48-137">Til að færa inn afmörkun fyrir þessa gerð reits, er hægt að færa inn númeragildið sem afmörkunarbreytu.</span><span class="sxs-lookup"><span data-stu-id="8ea48-137">To enter a filter for this type of field, you can enter the numeric value as a filtering parameter.</span></span> <span data-ttu-id="8ea48-138">Til dæmis í reitnum **Sala** á sölupöntun sem hafa gildin **Opin**, **Útgefið**, **Samþykkt í bið** og **Fyrirframgreiðsla í bið** skal nota gildin **0**, **1**, **2** og **3** til þess að afmarka þessa valmöguleika.</span><span class="sxs-lookup"><span data-stu-id="8ea48-138">For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.</span></span>  

## <a name="see-also"></a><span data-ttu-id="8ea48-139">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="8ea48-139">See Also</span></span>
[<span data-ttu-id="8ea48-140">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="8ea48-140">Work with Dynamics NAV</span></span>](ui-work-product.md)

