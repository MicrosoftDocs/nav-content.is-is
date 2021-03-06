---
title: "Nota runuvinnsluna Greiðslutillögur til lánardrottna"
description: "Hægt er að tilgreina stillingar fyrir greiðslur til lánardrottna og fá þannig greiðslutillögur sem taka mið af gjalddögum og afsláttum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 99bec4a5cc06209d4e7cfc0e7d2736bfc6fe9e1e
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-suggest-vendor-payments"></a>Hvernig á að leggja til greiðslutillögur til lánardrottna
Í glugganum **Greiðslubók** geturðu notað **Greiðslutillögur til lánardr.** runuvinnsluna til að stinga upp á greiðslulínur. Línur fyrir hluti eins og greiðslur sem eiga sér stað fljótlega, eða greiðslur þar sem greiðsla afsláttur er í boði, er leiðbeinandi miðað við stillingarnar þínar.

Til að njóta fulls af leiðbeinandi línur, verður þú fyrst að forgangsraða söluaðilum þínum. Nánari upplýsingar sjá [Hvernig: forgangsraða lánardrottnum](purchasing-how-prioritize-vendors.md).  

Lánardrottnafærslur sem eru ekki merktar **Í biðstöðu** eru ekki teknar með.  

> [!IMPORTANT]  
>   Ef nýta á greiðsluafslátt og tiltæk upphæð hefur verið færð inn, verður upphæðin notuð fyrir:  

* Forgangsatriði fyrirframgreiddar seljenda færslur fyrst í forgangsröð.  
* Lánardrottnafærslur sem eru fallnar á tíma sem eru ekki forgangsraðar.  
* Opnaðu söluaðili færslur sem eiga rétt á greiðslukortum, raðað eftir seljanda númeri.  

## <a name="to-use-the-suggest-vendor-payments-function"></a>nota aðgerðina Greiðslutillögur til lánardrottna
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **greiðslubækur** og velja svo viðeigandi tengil.  
2. Opna skal viðeigandi færslubók, og síðan velja **Greiðslutillögur til lánardrottna** aðgerðina.  
3. Fyllið inn í svæðin eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
4. Velja hnappinn **Í lagi**.  

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>Setja inn skiladag sem bókunardagsetningu á greiðslubókarlínum
Þegar þú notar runuvinnsluna **Greiðslutillögur til lánardrottna** til að stofna greiðslulínur fyrir lánardrottna þína getur þú fyllt út tvo sérstaka reiti til að gæta þess að stofnuðu línurnar noti gjalddaga til að reikna út bókunardagsetningu. Þessir reitir eru **Reikna Bókunardagsetning úr Gjalddaga jöfnunar** og **frávik gjalddaga jöfnunar**.  

> [!IMPORTANT]  
>   Ekki er hægt að nota reitinn **Reikna út bókunardagsetningu úr gildisdegi** samhliða reitunum **Finna greiðsluafslátt** eða **Samantekt fyrir lánardrottinn**. Ef staðsetningardagsetningin er byggð á gjalddaga, geta sumir afsláttarmöguleikar ekki reiknað rétt vegna þess að póstsetningardagur er eftir gjalddaga.  

Ef útreiknuð bókunardagsetning er liðin er bókunardagsetningin færð upp að vinnudagsetningunni og viðvörun birtist.  

Einnig er hægt að myndað sjálfkrafa greiðslulínur með gjalddaga til að reikna bókunardagsetningu Þegar lánardrottnafærslur hafa verið jafnaðar er hægt að nota **Reikna út bókunardagsetningu** til að uppfæra bókunardagsetningu á færslubókarlínunni með gjalddaga tengds innkaupareiknings. Nánari upplýsingar sjá [Hvernig: Jafna innkaupafærslur Handvirkt](payables-how-apply-purchase-transactions-manually.md).  

> [!NOTE]  
>   Ef innkaupareikningur er gjaldfallinn, er bókunardagsetningin stillt á vinnudag og leturgerð á línunni verður rautt.  

## <a name="see-also"></a>Sjá einnig
[Stjórna skuldum](payables-manage-payables.md)  
[Framkvæma greiðslur](payables-make-payments.md)  
[Vinna í færslubókum](ui-work-general-journals.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

