---
title: "Hvernig á að leggja til greiðslutillögur til lánardrottna"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 11bfba9f279f6bd84c5d169f6f97fd48759bc6df
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-suggest-vendor-payments"></a>Hvernig á að leggja til greiðslutillögur til lánardrottna
Í reitnum **greiðslubók** er hægt að nota aðgerð til að leggja til greiðslulínur í samræmi við stillingar þínar, t.d. greiðslur sem eru komnar á gjalddaga fljótlega eða greiðslur þar sem greiðsluafsláttur er tiltækur.

Til að njóta fulls hagnaðar af eiginelikanum Leggja til lánardrottnagreiðslur, verðurðu að forgangsraða lánardrottnum þínum. Nánari upplýsingar sjá [Hvernig: forgangsraða lánardrottnum](purchasing-how-prioritize-vendors.md).

 lánardrottnafærslur sem eru ekki merktar **Bið** eru teknar með í keyrslu.  

**Mikilvægt**: Ef nýta á greiðsluafslátt og tiltæk upphæð hefur verið færð inn, verður upphæðin notuð fyrir forgangsraðaðar gjaldfallnar lánardrottnafærslur, fyrst samkvæmt forgangsröðun og síðan fyrir gjaldfallnar lánardrottnafærslur sem ekki hefur verið forgangsraðað og loks fyrir opnar lánardrottnafærslur sem hægt er að fá greiðsluafslátt fyrir samkvæmt lánardrottnanúmeri.

## <a name="to-use-the-suggest-vendor-payments-function"></a>nota aðgerðina Greiðslutillögur til lánardrottna
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Greiðslubækur**, og velja síðan viðeigandi tengil.
2. Opna skal viðeigandi færslubók, og síðan velja **Greiðslutillögur til lánardrottna** aðgerðina.
3. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
4. Velja hnappinn **Í lagi**.

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>Setja inn skiladag sem bókunardagsetningu á greiðslubókarlínum
Þegar þú notar runuvinnsluna **Greiðslutillögur til lánardrottna** til að stofna greiðslulínur fyrir lánardrottna þína getur þú fyllt út tvo sérstaka reiti til að gæta þess að stofnuðu línurnar noti gjalddaga til að reikna út bókunardagsetningu. Þessir reitir eru **Reikna Bókunardagsetning úr Gjalddaga jöfnunar** og **frávik gjalddaga jöfnunar**.

**Mikilvægt**: Ekki er hægt að nota reitinn **Reikna út bókunardagsetningu úr gildisdegi jöfnunar** samhliða reitunum **Finna greiðsluafslátt** eða **Samantekt fyrir lánardrottinn**. Ástæðan er að ef bókunardagsetningin er byggð á gjalddaga er hugsanlegt að einhver greiðsluafsláttur hafi ekki verið rétt reiknaður því bókunardagsetningin gæti verið eftir dagsetningu greiðsluafsláttar.
Einnig, Ef útreiknuð bókunardagsetning er liðin verður bókunardagsetningin færð upp að vinnudagsetningunni og viðvörun birtist.

Einnig, geturðu einnig sjálfkrafa myndað greiðslulínur með gjalddaga til að reikna bókunardagsetningu Þegar búið er að jafna lánardrottnafærslur er hægt að nota aðgerðina **Reikna Bókunardagsetning** Þetta uppfærir Bókunardagsetning færslubókarlínunnar að gjalddaga tengda innkaupareikningsins. Nánari upplýsingar sjá [Hvernig: Jafna innkaupafærslur Handvirkt](payables-how-apply-purchase-transactions-manually.md).  

**Athugasemd**: Ef innkaupareikningurinn er gjaldfallinn verður bókunardagsetningin stillt á vinnudagsetninguna og leturgerðin á línunni breytist í rauðan lit.

## <a name="see-also"></a>Sjá einnig
[Umsjón viðskiptaskulda](payables-manage-payables.md)  
[Framkvæma greiðslur](payables-make-payments.md)  
[Vinna í færslubókum](ui-work-general-journals.md)

