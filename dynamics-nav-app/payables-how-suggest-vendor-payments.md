---
title: "Hvernig á að leggja til greiðslutillögur til lánardrottna"
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
ms.openlocfilehash: 3ede5942798e34fd0e4b3ab8cc48ca94eed3d1a4
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-suggest-vendor-payments"></a><span data-ttu-id="6d392-102">Hvernig á að leggja til greiðslutillögur til lánardrottna</span><span class="sxs-lookup"><span data-stu-id="6d392-102">How to: Suggest Vendor Payments</span></span>
<span data-ttu-id="6d392-103">Í reitnum **greiðslubók** er hægt að nota aðgerð til að leggja til greiðslulínur í samræmi við stillingar þínar, t.d. greiðslur sem eru komnar á gjalddaga fljótlega eða greiðslur þar sem greiðsluafsláttur er tiltækur.</span><span class="sxs-lookup"><span data-stu-id="6d392-103">In the **Payment Journal** window, you can use a function to suggest payment lines according to your settings, such as payments that are due soon or payments where a payment discount is available.</span></span>

<span data-ttu-id="6d392-104">Til að njóta fulls hagnaðar af eiginelikanum Leggja til lánardrottnagreiðslur, verðurðu að forgangsraða lánardrottnum þínum.</span><span class="sxs-lookup"><span data-stu-id="6d392-104">To benefit fully from the Suggest Vendor Payments function, you must first prioritize your vendors.</span></span> <span data-ttu-id="6d392-105">Nánari upplýsingar sjá [Hvernig: forgangsraða lánardrottnum](purchasing-how-prioritize-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="6d392-105">For more information, see [How to: Prioritize Vendors](purchasing-how-prioritize-vendors.md).</span></span>

<span data-ttu-id="6d392-106"> lánardrottnafærslur sem eru ekki merktar **Bið** eru teknar með í keyrslu.</span><span class="sxs-lookup"><span data-stu-id="6d392-106">Vendor entries that are not marked **On Hold** are not included in the batch job.</span></span>  

<span data-ttu-id="6d392-107">**Mikilvægt**: Ef nýta á greiðsluafslátt og tiltæk upphæð hefur verið færð inn, verður upphæðin notuð fyrir forgangsraðaðar gjaldfallnar lánardrottnafærslur, fyrst samkvæmt forgangsröðun og síðan fyrir gjaldfallnar lánardrottnafærslur sem ekki hefur verið forgangsraðað og loks fyrir opnar lánardrottnafærslur sem hægt er að fá greiðsluafslátt fyrir samkvæmt lánardrottnanúmeri.</span><span class="sxs-lookup"><span data-stu-id="6d392-107">**Important**: If you want to take advantage of payment discounts and have entered an available amount, the amount will be used for prioritized overdue vendor entries first in order of priority, and then for overdue vendor entries that are not prioritized, and finally for open vendor entries that qualify for payment discounts in order of vendor number.</span></span>

## <a name="to-use-the-suggest-vendor-payments-function"></a><span data-ttu-id="6d392-108">nota aðgerðina Greiðslutillögur til lánardrottna</span><span class="sxs-lookup"><span data-stu-id="6d392-108">To use the Suggest Vendor Payments function</span></span>
1. <span data-ttu-id="6d392-109">Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Greiðslubækur**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="6d392-109">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="6d392-110">Opna skal viðeigandi færslubók, og síðan velja **Greiðslutillögur til lánardrottna** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="6d392-110">Open the relevant journal, and then choose the **Suggest Vendor Payments** action.</span></span>
3. <span data-ttu-id="6d392-111">Fyllið inn í svæðin eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="6d392-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="6d392-112">Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="6d392-112">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="6d392-113">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="6d392-113">Choose the **OK** button.</span></span>

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a><span data-ttu-id="6d392-114">Setja inn skiladag sem bókunardagsetningu á greiðslubókarlínum</span><span class="sxs-lookup"><span data-stu-id="6d392-114">To insert the due date as posting date on payment journal lines</span></span>
<span data-ttu-id="6d392-115">Þegar þú notar runuvinnsluna **Greiðslutillögur til lánardrottna** til að stofna greiðslulínur fyrir lánardrottna þína getur þú fyllt út tvo sérstaka reiti til að gæta þess að stofnuðu línurnar noti gjalddaga til að reikna út bókunardagsetningu.</span><span class="sxs-lookup"><span data-stu-id="6d392-115">When you use the **Suggest Vendor Payments** batch job to create payment lines for your vendors, you can fill two special fields to make sure that the generated lines use the due date to calculate the posting date.</span></span> <span data-ttu-id="6d392-116">Þessir reitir eru **Reikna Bókunardagsetning úr Gjalddaga jöfnunar** og **frávik gjalddaga jöfnunar**.</span><span class="sxs-lookup"><span data-stu-id="6d392-116">These fields are **Calculate Posting Date from Applies-to-Doc Due Date** and **Applies-to-Doc Due Date Offset**.</span></span>

<span data-ttu-id="6d392-117">**Mikilvægt**: Ekki er hægt að nota reitinn **Reikna út bókunardagsetningu úr gildisdegi jöfnunar** samhliða reitunum **Finna greiðsluafslátt** eða **Samantekt fyrir lánardrottinn**.</span><span class="sxs-lookup"><span data-stu-id="6d392-117">**Important**: You cannot use the **Calculate Posting Date from Applies-to-Doc Due Date** field together with the **Find Payment Discounts** field or the **Summarize per Vendor** field.</span></span> <span data-ttu-id="6d392-118">Ástæðan er að ef bókunardagsetningin er byggð á gjalddaga er hugsanlegt að einhver greiðsluafsláttur hafi ekki verið rétt reiknaður því bókunardagsetningin gæti verið eftir dagsetningu greiðsluafsláttar.</span><span class="sxs-lookup"><span data-stu-id="6d392-118">The reason is that if the posting date is based on the due date, then some payment discount may not be calculated correctly, because the posting date could occur after the payment discount date.</span></span>
<span data-ttu-id="6d392-119">Einnig, Ef útreiknuð bókunardagsetning er liðin verður bókunardagsetningin færð upp að vinnudagsetningunni og viðvörun birtist.</span><span class="sxs-lookup"><span data-stu-id="6d392-119">Also, if the calculated posting date occurs in the past, then the posting date will be moved up to the work date, and a warning is displayed.</span></span>

<span data-ttu-id="6d392-120">Einnig, geturðu einnig sjálfkrafa myndað greiðslulínur með gjalddaga til að reikna bókunardagsetningu</span><span class="sxs-lookup"><span data-stu-id="6d392-120">Alternatively, you can also manually create payment lines using the due date to calculate the posting date.</span></span> <span data-ttu-id="6d392-121">Þegar búið er að jafna lánardrottnafærslur er hægt að nota aðgerðina **Reikna Bókunardagsetning**</span><span class="sxs-lookup"><span data-stu-id="6d392-121">After you have applied vendor ledger entries, you can use the **Calculate Posting Date** action.</span></span> <span data-ttu-id="6d392-122">Þetta uppfærir Bókunardagsetning færslubókarlínunnar að gjalddaga tengda innkaupareikningsins.</span><span class="sxs-lookup"><span data-stu-id="6d392-122">This will update the posting date on the journal line with the due date of the related purchase invoice.</span></span> <span data-ttu-id="6d392-123">Nánari upplýsingar sjá [Hvernig: Jafna innkaupafærslur Handvirkt](payables-how-apply-purchase-transactions-manually.md).</span><span class="sxs-lookup"><span data-stu-id="6d392-123">For more information, see [How to: Apply Purchase Transactions Manually](payables-how-apply-purchase-transactions-manually.md).</span></span>  

<span data-ttu-id="6d392-124">**Athugasemd**: Ef innkaupareikningurinn er gjaldfallinn verður bókunardagsetningin stillt á vinnudagsetninguna og leturgerðin á línunni breytist í rauðan lit.</span><span class="sxs-lookup"><span data-stu-id="6d392-124">**Note**: If the purchase invoice is overdue, then the posting date will be set to the work date, and the font on the line will change to red color.</span></span>

## <a name="see-also"></a><span data-ttu-id="6d392-125">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="6d392-125">See Also</span></span>
[<span data-ttu-id="6d392-126">Umsjón viðskiptaskulda</span><span class="sxs-lookup"><span data-stu-id="6d392-126">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="6d392-127">Framkvæma greiðslur</span><span class="sxs-lookup"><span data-stu-id="6d392-127">Make Payments</span></span>](payables-make-payments.md)  
[<span data-ttu-id="6d392-128">Vinna í færslubókum</span><span class="sxs-lookup"><span data-stu-id="6d392-128">Work with General Journals</span></span>](ui-work-general-journals.md)

