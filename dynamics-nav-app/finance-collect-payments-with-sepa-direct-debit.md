---
title: "Bein skuldfærsla (SEPA) í Dynamics NAV"
description: "Hægt er að sækja greiðslur beint inn á bankareikninga viðskiptamanns samkvæmt SEPA-sniðinu."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9ead1f76883e3c8d98bef8c61175766ccf1414e7
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="collecting-payments-with-sepa-direct-debit"></a>Innheimta greiðslur með SEPA-beingreiðslum
Með samþykki viðskiptamanns er hægt að sækja greiðslur beint inn á bankareikninga viðskiptamanns út frá SEPA-sniðinu.  

 Setjið fyrst upp útflutningssnið bankaskráarinnar með leiðbeiningum til bankans um beingreiðsluaðgerð. Síðan, settu upp greiðslumáta viðskiptamanns. Að síðustu skal setja upp umboð fyrir beingreiðslu sem endurspeglar samning þinn við viðskiptavininn um söfnun greiðslna á tilteknu samningstímabili.  

 Til að gefa bankanum fyrirmæli um að flytja greiðsluupphæðir af bankareikningi viðskiptamannsins á reikning fyrirtækis þíns, stofnarðu innheimtufærslu beingreiðslu sem inniheldur upplýsingar um bankareikninga, sölureikningana sem um ræðir og umboð fyrir beingreiðslu. Flytjið svo út XML-skrá sem byggir á innheimtufærslu sem er send til úrvinnslu í banka. Bankinn lætur vita af greiðslum sem ekki er hægt að meðhöndla og þá þarf að hafna viðkomandi innheimtufærslur fyrir beingreiðslur.  

 Hægt er að setja upp staðlaða sölukóða viðskiptamanns með beingreiðsluaðferð og umboðsupplýsingum. Þá er hægt að nota **Stofna staðlaða viðskiptamannareikninga** runuvinnsluna til að mynda marga sölureikninga með fyrirfram útfylltum upplýsingum um beingreiðslur. Þetta er hægt að gera handvirkt eða sjálfkrafa, samkvæmt gjalddaga greiðslunnar.  

 Þegar banki staðfestir að greiðslur séu meðhöndlaðar er hægt að bóka greiðslukvittanir beint úr **Innheimtufærslubeingreiðslur** glugganum eða með því að færa greiðslulínurnar í færslubókina þar sem greiðslukvittanir eru bókaðar, s.s. í **Inngreiðslubók** glugganum. Bjóði sjóðseiginleikar upp á það er einnig hægt að bíða og jafna greiðslurnar úr bankaafstemmingu.  

> [!NOTE]  
>  Að safna greiðslum með SEPA-beingreiðslur, verður gengið á sölureikningi verður EURO.  

 Eftirfarandi tafla lýsir röð verkefna með tenglum í efnisatriði þar sem þeim er lýst.   

|**Til að**|**Sjá**|  
|------------|-------------|  
|Undirbúið bankareikningssnið, greiðsluaðferðir og samninga við viðskiptavini um SEPA-beingreiðslur.|[Hvernig á að: Setja upp SEPA-beingreiðslur](finance-how-to-set-up-sepa-direct-debit.md)|  
|Gefið bankanum fyrirmæli um að flytja greiðsluupphæðir af bankareikningum viðskiptavina á bankareikninga fyrirtækisins í samræmi við uppsetningu SEPA-beingreiðslna.|[Hvernig á að: Stofna SEPA-innheimtufærslur fyrir beingreiðslur og flytja út í bankaskrá](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md)|  
|Setjið upp staðalaða sölukóða viðskiptamann fyrir beingreiðslureikninga og stofnið sölureikninga með beingreiðsluupplýsingum þegar reikningarnir gjaldfalla.|[Hvernig á að: Stofna ítrekaðar sölu og innkaup](sales-how-work-standard-lines.md)|  
|Bóka greiðslur búnar til sem SEPA-beingreiðslur|[Hvernig á að. Bóka SEPA-greiðslukvittanir beingreiðslna](finance-how-to-post-sepa-direct-debit-payment-receipts.md)|  

## <a name="see-also"></a>Sjá einnig  
[Stjórnun skulda](receivables-manage-receivables.md)

