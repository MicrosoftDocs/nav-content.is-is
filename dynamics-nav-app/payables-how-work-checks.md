---
title: "Hvernig á að: vinna með tékka"
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
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a>Hvernig á að: vinna með tékka
Dynamics NAV styður rafrænar og handvirkar útgáfur á tékkum. Í báðum aðferðum er útgreiðslubók notuð til að gefa út tékka til lánardrottna. Einnig er hægt að ógilda tékka og skoða fjárhagsfærslur.

Vinnslan sem gefur út tékka stingur upp á greiðslum, býr til fjárhagsfærslur og prentar vélfærðu  tékkana.

Prentarinn verður að vera rétt stilltur með tékkaeyðublöðum, og þú verður að skilgreina hvaða útlit tékka á að nota. Nánari upplýsingar sjá [Hvernig á að: Skilgreina útlit tékka:](finance-setup-how-define-check-layouts.md)

## <a name="to-issue-checks"></a>gefa út tékka
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Greiðslubækur**, og velja síðan viðeigandi tengil.
2. Fyllið út færslubók, t.d. með viðeigandi greiðslum, til dæmis með því að nota virknina Greiðslutillögur til lánardrottna. Nánari upplýsingar má sjá í [Hvernig á að: Leggja til greiðslutillögur til lánardrottna](payables-how-suggest-vendor-payments.md).
3. Í reitnum **Tegund Bankagreiðslu** í færslubókarlínunum fyrir greiðslur sem þú vilt gera með tékkum, veldu einn af eftirfarandi valkostum.

 - **Vélfærður tékki**: veldu þennan valkost ef  á að prenta tékka með upphæðinni í færslubókarlínunni. Þú þarft að prenta tékkana áður en þú bókar færslubókarlínurnar. Þú getur eingöngu valið **Vélfærður tékki** ef **Tegund mótreiknings** eða **Tegund reiknings** er **Bankareikningur**.

 - **Handfærður tékki**  Þessi kostur er valinn ef handfærður tékki hefur verið búinn til og  á að búa til tékkafærslu sem samsvarar upphæðinni. Með þessum valkosti er ekki hægt að prenta tékka úr Dynamics NAV Þú getur eingöngu valið **handfærður tékki** ef **Tegund mótreiknings** eða **Tegund reiknings** er **Bankareikningur**.

    **Athugasemd** : Þarf að prenta vélfærðu tékkana áður en hægt er að bóka tengdu færslubókarlínurnar.
4. Ef um er að ræða vélfærða tékka, veldu **Prenta Tékka**.
5. Í glugganum **ávísun** þarf að fylla reitina út eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
6. Velja hnappinn **Prenta**.

**Athugasemd**: Ef prenta þarf tékka í fleiri en einum gjaldmiðli frá mismunandi bankareikningum verður að keyra keyrsluna **Prenta tékka** sérstaklega fyrir hvern gjaldmiðil og tilgreina réttan bankareikning.

## <a name="to-cancel-printed-checks-that-are-not-posted"></a>Til að ógilda prentaðan tékka sem ekki eru bókaðar
Hægt er að ógilda tékka sem eftir á að bóka þegar þær hafa verið prentuð með því að nota **Ógilda Tékka** aðgerð í á **greiðslubók** glugga.
1. Í á **greiðslubókarglugga** er valið á **Ógilda Tékka**, og síðan valið hvaða tékka á að ógilda.

## <a name="to-void-checks"></a>Tékkar ógiltir:
Þegar tékkagreiðslur hafa verið bókaðar, geturðu aðeins afturkallað (ógilt) tékka úr bankafærslum sem fengust út úr þessu.

1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.
2. Veldu viðeigandi bankareikning, veldu **breyta** aðgerðina og veldu síðan **tékkafærslur** aðgerðina.
3. Í **tékkafærslur** glugganum, veldu **ógilda tékka** aðgerðina.
4. Veldu gátreitinn **eingöngu ógilda tékka**.
5. Veldu hnappinn **Í lagi**.

## <a name="see-also"></a>Sjá einnig
[Umsjón viðskiptaskulda](payables-manage-payables.md)  
[Uppsetning bankaþjónustu](bank-setup-banking.md)  

