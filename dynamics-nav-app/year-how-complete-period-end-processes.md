---
title: "Loka tímabili"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a>Loka tímabili
Jöfnunin þvingar notanda ekki til að loka tímabilum, hins vegar eru margar lokatímabilaaðgerðir (mánaðarlok) sem hægt er að gera í jöfnuninni ef óskað er eftir. Í þessu efnisatriði er veitt yfirsýn yfir þessar vinnslur og aðgerðir sem kunna að vera nauðsynlegar í fyrirtæki notanda.

## <a name="general-ledger"></a>Fjárhagur
* Tilgreina notandaskilgreind bókunardagsetningatímabil fyrir allt kerfið.

    Þetta tilgreinir það dagsetningabil sem bókanir eru leyfðar. Hugsanlega þarf að takmarka notandabókuð dagsetningabil við upphaf vinnslu lokatímabila, eða nær lokum tímabilsins, allt eftir þörfum fyrirtækisins. Nánari upplýsingar eru í [Hvernig á að tilgreina bókunartímabil](finance-setup-how-specify-posting-periods.md).
* Allar nauðsynlegar fjárhagsleiðréttingar eru framkvæmdar.
* Ítrekunarbækur eru uppfærðar og bókaðar.
<!--* Process Consolidations-->
* Fjárhagsskema keyrt sem hér segir:
  1. Glugginn **Fjárhagsskema** er opnaður og smellt á aðgerðina **Prenta**.
  2. Fyllið inn í beiðnagluggann **Fjárhagsskema** og smellið á aðgerðina **Prenta**.

## <a name="sales--receivables"></a>Sala
* Allar sölupantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.
* Inngreiðslubókin er bókuð.
* Ítrekunarfærslubækur tengdar sölugrunni eru uppfærðar og bókaðar.
* Afstemma viðskiptakröfur við færslubók.
* Runuvinnslan **Eyða reikningsf. sölupöntunum** er keyrð.

## <a name="purchases--payables"></a>Innkaup
* Allar pantanir, reikningar, kreditreikningar og vöruskilapantanir eru bókaðar.
* Allar greiðslubækur eru bókaðar.
* Ítrekunarfærslubækur tengdar innkaupum og viðskiptaskuldum eru uppfærðar og bókaðar.
* Skýrslan **Aldursgreindar skuldir** er keyrð og skuldir stemmdar af við fjárhaginn.
* Runuvinnslan **Eyða reikningsf. innk.pöntunum** er keyrð.

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a>VSK er reiknaður og unninn
*  Lokið er við skattyfirlit.

## <a name="see-also"></a>Sjá einnig
[Lokaár og Tímabil](year-close-years-periods.md)  
[Loka bókum](year-close-books.md)

