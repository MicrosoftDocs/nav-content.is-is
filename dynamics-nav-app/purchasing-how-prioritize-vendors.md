---
title: "Úthluta forgangsstigi til lánardrottins"
description: "Þú getur úthlutað númerum til lánardrottins eða birgja til að forgangsraða þeim og auðvelda greiðslutillögur í Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supplier, payment priority
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 79458c1372c9f696a8331f2e7c83179dd42fb905
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-prioritize-vendors"></a>Hvernig á að forgangsraða Lánardrottnum
[!INCLUDE[d365fin](includes/d365fin_md.md)] getur lagt til ýmsar greiðslur til lánardrottna t.d. greiðslur sem eru bráðum á gjalddaga eða greiðslur sem hægt er að fá afslátt af. Nánari upplýsingar má sjá í [Hvernig á að: Leggja til greiðslutillögur til lánardrottna](payables-how-suggest-vendor-payments.md).

Fyrst verður að forgangsraða lánardrottnum með því að úthluta númerum á þá.

## <a name="to-prioritize-vendors"></a>Lánardrottnum forgangsraðað
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **lánardrottnar** og velja svo viðeigandi tengil.
2. Veljið viðeigandi lánardrottin og veljið því næst **Breyta**.
3. Í reitinn **Forgangur** skal færa inn númer.

[!INCLUDE[d365fin](includes/d365fin_md.md)] setur lægsta númerið, fyrir utan 0, efst í forgangsröðina. Þannig að t.d. ef notaðar eru tölurnar 1, 2 og 3 þá er 1 fyrst í forgangsröðinni.

Ef ekki á að forgangsraða lánardrottni er reiturinn **Forgangur** skilinn eftir auður. Síðan ef notuð er aðgerðin greiðslutillaga er lánardrottininn settur á lista á eftir öllum lánardrottnunum sem hafa forgangsnúmer. Hægt er að færa inn eins mörg forgangsstig og nauðsynlegt er.

## <a name="see-also"></a>Sjá einnig
[Uppsetning innkaupa](purchasing-setup-purchasing.md)  
[Stjórna skuldum](payables-manage-payables.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

