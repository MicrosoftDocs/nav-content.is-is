---
title: "Stjórna viðskiptaskuldum"
description: "Yfirlit yfir það hvernig Dynamics NAV hjálpar þér að stjórna viðskiptaskuldum (AP), þar á meðal greiðslum lánardrottna, lánardrottnar, skuldir og gjaldfallin staða."
documentationcenter: 
author: bholtorf
manager: edupont
editor: 
ms.prod: dynamics-nav-2018
ms.workload: na
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.search.keywords: vendor payment, creditor, debt, balance due, AP
ms.date: 06/02/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 698cb92c4209f2675fda3a4b2280ab8afad0c9cc
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="managing-payables"></a>Stjórna skuldum
[!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] hefur það sem þú þarft til að stjórna viðskiptaskuldum.  

## <a name="payments"></a>Greiðslur
Það er auðvelt að forgangsraða greiðslum, reikna með viðurlögum vegna tímabundinna greiðslna og takast á við afslætti fyrir snemma greiðslur.

Þú getur skráð greiðslur í almennri dagbók og síðan prentað eftir því áður en þú sendir greiðslubókina.

Þú getur sótt greiðslur til loka reikninga þegar þú sendir inn greiðsluna eða eftir að þú hefur sent greiðsluna. **Jöfnunaraðferðin** sem tilgreind er fyrir lánardrottinn (á **lánardrottnaspjaldinu**) ákvarðar hvort þú sækir greiðsluna handvirkt eða sjálfkrafa. Þú getur alltaf jafnað færslur handvirkt. En ef jöfnunaraðferðin fyrir lánardrottin er **Jafna elstu** og þú tilgreinir ekki fylgiskjal fyrir greiðsluna sem jafna á við verður greiðslan jöfnuð við elstu opnu færsluna fyrir þennan lánardrottin.

## <a name="suggest-vendor-payments"></a>Greiðslutillögur til lánardr.
[!INCLUDE[d365fin](includes/d365fin_md.md)] getur lagt til ýmsar greiðslur til lánardrottna, svo sem greiðslur sem eru bráðum á gjalddaga eða greiðslur sem hægt er að fá afslátt af. Greiðslutillagan getur tekið til greina upphæð sem skilgreind er sem tiltækir fjármunir fyrir greiðslu og hægt er að fá greiðsluafslátt af.

## <a name="issue-checks"></a>Útgáfa tékka
[!INCLUDE[d365fin](includes/d365fin_md.md)] leyfir þér að gefa út eftirlit með söluaðilum handvirkt og rafrænt. Þú gerir bæði í **Greiðslubækur** glugganum þar sem einnig er hægt að ógilda tékka og skoða fjárhagsfærslur.

## <a name="export-payments-to-a-bank-file"></a>Flytja út greiðslur í bankaskrá
Þegar þú ert tilbúinn til að greiða lánardrottni er hægt úr **Greiðslubók** að flytja út skrá með greiðsluupplýsingum á færslubókarlínur. Þá er hægt að hlaða upp skránni í netbanka til að meðhöndla peningaflutning.

Ef þú vilt ekki bóka greiðslubókarlínu fyrir útflutta greiðslu, t.d. vegna þess að þú ert að bíða eftir staðfestingu frá banka á færslunni geturðu einfaldlega eytt línunni. Þegar þú síðar stofnar greiðslubókarlínu til að greiða eftirstandandi upphæð á reikningnum sýnir reiturinn **Heildarupphæð flutt út** hversu mikið af greiðsluupphæðinni hefur þegar verið flutt út. Þú getur einnig fundið ítarlegar upplýsingar um heildarupphæðir sem hafa verið fluttar út með því að velja hnappinn **Skráningarfærslur kreditmillifærslna**.

Ef þú bíður eftir að bóka greiðslur þar til bankinn þinn staðfestir að hann hafi meðhöndlað viðskipti, þá eru tvær leiðir til að koma í veg fyrir að greiðslur sé fluttar út aftur fyrir opin skjöl óvart:  

* Í greiðslubók með tillögum að greiðslulínum geturðu flokkað með annað hvort dálkinum **Flutt út í greiðsluskrá** eða **Heildarupphæð flutt út** dálkunum og svo eytt greiðslutillögum fyrir opna reikninga þar sem greiðslur hafa þegar átt sér stað og þú vilt ekki greiða.

    **Athugaðu** Þú gætir þurft að bæta þessum dálkum við listann. Nánari upplýsingar er að finna í [Sérstillingar notanda](ui-user-personalization.md).  
* Einnig, á **Greiðslutillögur til lánardrottna** runuvinnslunni þar sem hægt er að tilgreina greiðslur sem á að taka með í greiðslubókinni er hægt að tilgreina að setja ekki inn greiðslulínur fyrir greiðslur sem hafa þegar verið fluttar út með því að velja **Sleppa útfluttum greiðslum** gátreitinn.

## <a name="see-also"></a>Sjá einnig
[Greiðsluhættir](finance-payment-methods.md)  
[Fjármál](finance.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

