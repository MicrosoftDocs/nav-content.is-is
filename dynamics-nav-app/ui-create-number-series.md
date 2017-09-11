---
title: "Stofnun númeraraða"
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
ms.openlocfilehash: e42e5ed139b2487fea13ef0fd57757035764addd
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="create-number-series"></a><span data-ttu-id="b0ae1-102">Stofnun númeraraða</span><span class="sxs-lookup"><span data-stu-id="b0ae1-102">Create Number Series</span></span>

<span data-ttu-id="b0ae1-103">Fyrir hvert uppsett fyrirtæki þarf að úthluta einstökum kennikóta á atriði eins og fjárhagsreikninga og reikninga viðskiptamanna og lánardrottna, reikninga og skjöl.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-103">For each company that you set up, you need to assign unique identification codes to things such as general ledger accounts, customer and vendor accounts, invoices, and documents.</span></span> <span data-ttu-id="b0ae1-104">Númeraröð er ekki aðeins mikilvæg fyrir auðkenningu.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-104">Numbering is important not only for identification.</span></span> <span data-ttu-id="b0ae1-105">Vel unnið númerakerfi gerir einnig auðveldara að stýra og greina fyrirtækið og getur fækkað villum sem upp koma í gagnafærslu.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-105">A well-designed numbering system also makes the company more manageable and easy to analyze, and can reduce the number of errors that occur in data entry.</span></span>

<span data-ttu-id="b0ae1-106">Hægt er að setja upp heildarnúmerakerfi með ótakmörkuðum fjölda númeraraða.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-106">You can set up a complete numbering system with an unlimited number of number series.</span></span> <span data-ttu-id="b0ae1-107">Nota má númeraraðir fyrir allar gerðir skjala og færslubóka, sem og fyrir aðalgögn á borð við viðskiptamenn, vörur og verk.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-107">You can use number series for all types of documents and journals, as well as for master data such as customers, items, and jobs.</span></span>

<span data-ttu-id="b0ae1-108">Blanda má saman notkun númeraraða og handvirkrar númerunar.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-108">You can combine the use of number series with manual numbering.</span></span>

<span data-ttu-id="b0ae1-109">Númerakerfi er stofnað með því að setja upp einn eða fleiri kóta fyrir hverja tegund aðalgagna eða skjala.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-109">You create a numbering system by setting up one or more codes for each type of master data or document.</span></span> <span data-ttu-id="b0ae1-110">Til dæmis má setja upp einn kóta fyrir númerun viðskiptamanna, annan kóta fyrir númerun sölureikninga og annan fyrir númerun skjala í almennri færslubók.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-110">For example, you can set up one code for numbering customers, another code for numbering sales invoices, and another code for numbering documents in general journals.</span></span>

<span data-ttu-id="b0ae1-111">Þegar kóti hefur verið settur upp verður að setja upp minnst eina númeraraðarlínu.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-111">After you have set up a code, you set must set up at least one number series line.</span></span> <span data-ttu-id="b0ae1-112">Í númeraraðarlínunni eru upplýsingar líkt og fyrsta og síðasta talan í röðinni og upphafsdagsetningin.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-112">The number series line contains information such as the first and last number in the series and the starting date.</span></span> <span data-ttu-id="b0ae1-113">Hægt er að setja upp fleiri en eina númeraraðarlínu á hvern númeraraðarkóta með mismunandi upphafsdagsetningu fyrir hverja línu.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-113">You can set up more than one number series line per number series code, with a different starting date for each line.</span></span> <span data-ttu-id="b0ae1-114">Raðirnar verða notaðar hver á eftir annarri og hver röð hefst á tilgreindum upphafsdegi.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-114">The series will be used consecutively, starting each series on the respective starting date.</span></span>

<span data-ttu-id="b0ae1-115">Hægt er að nota fleiri en einn númeraraðarkóta fyrir hverja tegund frumgagna með því að nota númeraraðatengsl, til dæmis til að nota mismunandi númeraraðir fyrir mismunandi vöruflokka.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-115">If you want to use more than one number series code for one type of master data - for example, if you want to use different number series for different categories of items - you can use number series relationships.</span></span>

<span data-ttu-id="b0ae1-116">Auk talnanna sem úthlutað er handvirkt eða með notkun númerkerfis er öllum viðskiptum (færslum) sjálfkrafa úthlutað tölu eftir röð.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-116">In addition to the numbers that you assign manually or by use of the numbering system, all transactions (ledger entries) are automatically assigned consecutive numbers.</span></span> <span data-ttu-id="b0ae1-117">Þessar tölur má sjá í reitnum **Færslunr.**</span><span class="sxs-lookup"><span data-stu-id="b0ae1-117">These numbers can be seen in the **Entry No.**</span></span> <span data-ttu-id="b0ae1-118">í öllum fjárhagsfærslugluggum.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-118">field in all the ledger entry windows.</span></span> <span data-ttu-id="b0ae1-119">Ekki er hægt að breyta eða eyða þessum tölum.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-119">You cannot modify or delete these numbers.</span></span>

## <a name="to-create-relationships-between-number-series"></a><span data-ttu-id="b0ae1-120">Stofnun tengsla milli númeraraða</span><span class="sxs-lookup"><span data-stu-id="b0ae1-120">To create relationships between number series</span></span>
<span data-ttu-id="b0ae1-121">Ef settir hafa verið upp fleiri númeraraðakótar en einn fyrir sömu tegund grunnupplýsinga eða færslna er hægt að stofna tengsl milli kótanna.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-121">If you have set up more than one number series code for the same kind of basic information or transactions, you can create relationships between the codes.</span></span> <span data-ttu-id="b0ae1-122">Með þessari aðgerð er auðvelt að velja á milli kóta þegar númer er notað.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-122">This feature can assist you in deciding among the codes when you use a number.</span></span>

1. <span data-ttu-id="b0ae1-123">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Númeraröð**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-123">In the top right corner, choose the **Search for Page or Report** icon, enter **No. Series**, and then choose the related link.</span></span>
2. <span data-ttu-id="b0ae1-124">Velja skal línuna með númeraröðinni sem á að stofna tengsl við. og veljið síðan **Tengsl**.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-124">Select the line with the number series you want to create relationships for and then choose **Relationships**.</span></span>
3. <span data-ttu-id="b0ae1-125">Færður er inn í reitinn **Raðarkóti** kóti fyrir númeraröðina sem á að tengja við röðina sem valin var í 2. þrepi.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-125">In the **Series Code** field, enter the code for the number series that you want to relate to the series you selected in step 2.</span></span>
4. <span data-ttu-id="b0ae1-126">Bætt er við línu fyrir hvern kóta sem á að tengja völdum númeraröðum.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-126">Add a line for each code that you want to relate to the selected number series.</span></span>
5. <span data-ttu-id="b0ae1-127">Glugganum er lokað.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-127">Close the window.</span></span>

<span data-ttu-id="b0ae1-128">Þegar eitthvað er sett upp eftir þetta sem þarfnast númers er hægt að nota tengslin sem voru stofnuð til að velja úr skyldum númeraröðum.</span><span class="sxs-lookup"><span data-stu-id="b0ae1-128">Now when you set up something that requires a number, you can use the relationships you created to select among the related number series.</span></span>

## <a name="see-also"></a><span data-ttu-id="b0ae1-129">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="b0ae1-129">See Also</span></span>
[<span data-ttu-id="b0ae1-130">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="b0ae1-130">Work with Dynamics NAV</span></span>](ui-work-product.md)

