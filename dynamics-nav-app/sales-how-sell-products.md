---
title: "Stofna sölupöntun og selja vörur"
description: "Lýsir því hvernig skal búa til  sölupöntun, til að skrá samkomulag við viðskiptamann um að selja eða eiga viðskipti með vörur með tilteknum skilmálum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: trade
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1371f7a1d1e5b5c9bd0add845d37e194db86218d
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-sell-products"></a>Hvernig á að: Selja vörur
Búinn er til sölureikningur eða sölupöntun til að skrá samkomulag við viðskiptamann um að selja tilteknar vörur með tilteknum afhendingar- og greiðsluskilmálum.

> [!NOTE]  
>   Þú notar sölupantanir ef söluferlið krefst þess að hægt að afhenda hluta pöntunarmagns , til dæmis þar sem allt magnið er ekki tiltæk í einu. Ef vara er seld með því að afhenda beint frá lánardrottni til viðskiptamanns, sem bein sending þarf að einnig nota sölupantanir. Nánari upplýsingar eru í [Hvernig á að gera bein sending](sales-how-drop-shipment.md). Frá öllum sjónarhornum séð virka sölupantanir á sama hátt og sölureikningar. Nánari upplýsingar eru í [Hvernig á að reikningsfæra sölu](sales-how-invoice-sales.md).

Hægt er að semja við viðskiptamanninn með því að gera fyrst sölutilboð, sem hægt er að breyta í sölupöntun þegar samkomulag hefur náðst um söluna. Nánari upplýsingar eru í [Hvernig á að gera tilboð](sales-how-make-offers.md).

Þegar viðskiptamaðurinn hefur staðfest samninginn, til dæmis eftir tilboðsferli, geturðu sent staðfestingu pöntunar til að skrá afhendindingarskyldu vörunnar, eins og um var samið.

Þegar þú afhenda vörur, hvort sem er að fullu eða hluta, bókarðu sölupöntunina sem afhenta eða sem senda og reikningsfærða til að stofna viðkomandi vörufærslur og færslur í viðskiptamannabók í kerfinu. Við bókun sölupöntunar, er einnig hægt að senda skjalið í tölvupósti sem PDF viðhengi. Hægt er að láta meginmálslínur tölvupósts vera útfyllt fyrirfram með samantekt á pöntuninni og greiðsluupplýsingum, eins og tengli í PayPal. Nánari upplýsingar sjá [Hvernig á að: Senda Skjöl með Tölvupóst](ui-how-send-documents-email.md).

Í viðskiptaumhverfi þar sem viðskiptamaðurinn verður að greiða áður en vörur eru afhentar, til dæmis í smásölu, verður að bíða eftir greiðslukvittun fyrir vörunum áður en þær eru afhentar. Í flestum tilfellum er valið að vinna  greiðslur á innleið nokkrum vikum eftir afhendingu með því að jafna greiðslurnar við viðkomandi bókaða, ógreidda sölureikninga. Frekari upplýsingar eru í [hvernig á að afstemma greiðslur með því að nota sjálfvirka jöfnun](receivables-how-reconcile-payments-auto-application.md)

Auðvelt er að leiðrétta eða afturkalla bókaðann sölureikning sem á uppruna sinn í sölupöntun áður en hann er greiddur. Þetta er gagnlegt þegar leiðrétta á mistök eða þegar viðskiptamaðurinn biður um breytingu snemma í pöntunarferlinu. Nánari upplýsingar er að finna [hvernig á að: Ógreiddir sölureikningar leiðréttir eða afturkallaðir](sales-how-correct-cancel-sales-invoice.md) Ef bókaður sölureikningur er greiddur, verður að búa til sölukreditreikning til að afturkalla söluna. Fyrir frekar upplýsingar, sjá [hvernig á að: Meðhöndlun söluvöruskila eða afturkallana](sales-how-process-sales-returns-cancellations.md)

Hægt er að fylla út viðskiptamannsreitina á sölupöntunina með tveimur leiðum, eftir því hvort viðskiptamaðurinn hefur þegar verið skráður. Sjá lið 2 og 3 í eftirfarandi ferli.

## <a name="to-create-a-sales-order"></a>Sölupöntun stofnuð
1. Í heimasíða veldu **sölupöntun** aðgerð.  
2. Í reitnum **Viðskiptamaður** er fært inn nafn núverandi viðskiptamanns.

    Aðrir reitir í glugganum **sölupöntun** eru nú fylltir út með stöðluðum upplýsingum um viðskiptamaður sem valinn hefur verið. Ef viðskiptamaður er ekki skráður, fylgið eftirfarandi skrefum:
3. Í reitnum **Viðskiptamaður** er fært inn nafn nýs viðskiptamanns.
4. Í svarglugganum um að skrá nýja viðskiptavininn, veljið hnappinn **Já**.
5. Í glugganum **Velja sniðmát fyrir nýjan viðskiptamann**, skal velja sniðmát til að byggja nýja viðskiptamannaspjaldið á og veljið hnappinn **Í lagi**.

    Nýtt viðskiptamannaspjald opnast, fyrirfram fyllt út með upplýsingnum á valda viðskiptamannasniðmátinu. Reiturinn **Nafn** er fyrirfram fylltur út með nafni nýja viðskiptamannsins sem fært var inn á sölupöntun.
6. Haltu áfram að fylla út eftirstandandi reiti á spjaldi viðskiptamanns. Nánari upplýsingar eru í [Hvernig á að skrá nýjan viðskiptamaður](sales-how-register-new-customers.md).  
7. Þegar lokið hefur verið við viðskiptamannaspjaldið skal velja hnappinn **Í lagi** til að fara aftur í gluggann **sölupöntun**.

    Margir reitir í sölupöntun eru nú fullir af upplýsingar sem tilgreindar voru á nýja viðskiptamannaspjaldi.
8. Fylltu í eftirstandandi reiti í glugganum **sölupöntun** eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    Þú ert nú tilbúinn að fylla út í sölupöntunarlínurnar með birgðavöru eða þjónustu sem selja á viðskiptamanninum.

    Ef endurteknar sölulínur hafa verið settar upp fyrir viðskiptamanninn, svo sem mánaðarlegar endurnýjunarpantanir, er hægt að færa línuna inn í pöntunina með því að velja aðgerðina **Endurteknar sölulínur**.
9. Í flýtiflipanum **Línur** í reitnum **Vara** er sleginn inn fjöldi birgðavöru eða þjónustu.  
10. Í reitinn **Magn** er fært magn vara sem á að selja.

    Reiturinn **línuupphæð** uppfærist til að sýna að gildið í reitnum **einingarverð** margfaldað með gildinu í reitnum **magn**.

    Verð- og línuupphæðirnar eru sýndar með eða án VSK, en það fer eftir því hvað var valið í reitnum **verð með skatti** á viðskiptamannaspjaldinu.
11. Í reitnum **Línuafsláttur %**, færið inn prósentutölu ef veita á viðskiptamanninum afslátt af vörunni. Gildið í reitnum **Línuupphæð** er uppfært til samræmis.

    Ef sérstakt vöruverð hefur verið sett upp á flýtiflipanum **Afslættir söluverðs og sölulínu** á viðskiptamanns- eða birgðaspjaldinu uppfærist verðið og upphæðin á tilboðslínunni sjálfvirkt ef umsamin verðviðmið hafa náðst. Nánari upplýsingar eru í [Skrá söluverð, afslátt og greiðslusamkomulag](sales-how-record-sales-price-discount-payment-agreements.md).
12. Til að bæta við athugasemd um tilboðslínu sem viðskiptavinurinn getur séð á prentuðu sölureikningi, skrifaðu texta í **Lýsingarsvæði** sviði í auða línu.  
13. Endurtakið skref 10 til 13 fyrir hverja birgðavöru sem bjóða á viðskiptamanninum.

    Samtölur fyrir neðan línurnar eru sjálfkrafa reiknaðar þegar þú stofna eða breyta línur.
14. Nýtt viðskiptamannaspjald sýnir upplýsingarnar á valda viðskiptamannasniðmátinu. Eftirstandandi reitir eru fylltir út. Nánari upplýsingar eru í [Hvernig á að skrá nýjan viðskiptamaður](sales-how-register-new-customers.md).  
15. Þegar lokið hefur verið við viðskiptamannaspjaldið skal velja hnappinn **Í lagi** til að fara aftur í gluggann **sölupöntun**.

    Margir reitir í sölupöntun eru nú fullir af upplýsingar sem tilgreindar voru á nýja viðskiptamannaspjaldi.  
16. Fylltu í eftirstandandi reiti í glugganum **sölupöntun** eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

    Nú er hægt að fylla út í sölupöntunarlínur fyrir vörur sem selt er viðskiptamanni eða fyrir einhverri færslu við þann viðskiptamann sem á að skrá í reikning í Fjárhag.   

    Ef endurteknar sölulínur hafa verið settar upp fyrir viðskiptamanninn, svo sem mánaðarlegar endurnýjunarpantanir, er hægt að færa línuna inn í pöntunina með því að velja aðgerðina **Endurteknar sölulínur**.  
17. Á **Línur** Flýtiflipanum í **Tegund** reitnum, veldu hvaða tegund framleiðsluflokks, kostnaðarauka eða færslu þú munt bókað fyrir viðskiptamanninn með sölulínunni.
18. Í reitnum **númer** Reitnum er valin færsla til að bóka samkvæmt gildinu í reitnum **Tegund** reit.

    Þú skilur **nr.** reitinn eftir auðan í eftirfarandi tilvikum: – Ef línan er fyrir athugasemd. Rita athugasemdina í **Lýsing** reitinn.
    – Ef línan er fyrir utanbirgðavöru. Veljið **Velja utanbirgðavörur** aðgerð. Frekari upplýsingar, sjá [Hvernig á að: vinna með utanbirgðavörur](inventory-how-work-nonstock-items.md).

19. Í reitnum **Magn** er fært inn hversu margar einingar vöru, kostnaðarauka eða færslu sem línan skráir fyrir viðskiptamanninn.  

    > [!NOTE]  
    >   Ef varan er af tegundinni **Vara - Þjónusta** eða **Forði**, er magnið tímaeining, t.d. klukkutímar, eins og gefið er til kynna í reitnum **Mælieiningarkóði** í línunni.  

    Gildið í reitnum **Línuupphæð** er reiknaður sem *Einingarverð* x *Magn*.  

    Verð- og línuupphæðirnar eru sýndar með eða án VSK, en það fer eftir því hvað var valið í reitnum **verð með skatti** á viðskiptamannaspjaldinu.  
20. Í reitnum **Línuafsláttur %**, færið inn prósentutölu ef veita á afslátt af vörunni. Gildið í reitnum **Línuupphæð** er uppfært til samræmis.  

    Ef sérstakt vöruverð hefur verið sett upp á flýtiflipanum **Afslættir söluverðs og sölulínu** á viðskiptamanns- eða vöruspjaldinu, uppfærist verðið og upphæðin á tilboðslínunni sjálfvirkt ef umsamin verðviðmið hafa náðst. Nánari upplýsingar eru í [Skrá söluverð, afslátt og greiðslusamkomulag](sales-how-record-sales-price-discount-payment-agreements.md).  
21. Endurtakið skref 9 til 12 fyrir hverja vöru eða gjald sem selja á viðskiptamanninum.  

    Samtölur fyrir neðan línurnar eru sjálfkrafa reiknaðar þegar þú stofna eða breyta línur.  
22. Í reitnum **afsláttarupphæð reiknings** færið inn upphæð sem draga á frá gildinu sem sýnt er í reitnum **Heildarupphæð með skatti**.

    Ef reikningsafslættir hafa verið settir upp fyrir viðskiptamanninn, er tilgreint prósentugildi sjálfvirkt fært inn í reitinn **reikningsafsláttur %** ef viðmiðum hefur verið mætt og upphæðin færð inn í reitinn **afsláttarupphæð án skatts**. Nánari upplýsingar eru í [Skrá söluverð, afslátt og greiðslusamkomulag](sales-how-record-sales-price-discount-payment-agreements.md).
23. Til að afhenda Aðeins hluta pöntunarmagns, skal færa magn í reitinn **magn til Afhendingar** reit. Gildið er afritað í reitinn **magn til Reikningsfærslu**.
24. Til að reikningsfæra Aðeins hluta sends magns, skal færa magn í reitinn **magn til að reikningsfæra** . Magnið verður að vera minna en gildið í reitnum **Magn til að senda**.   
25. Þegar sölupöntunarlínunum er lokið, skal velja **bóka og senda** aðgerðina.

**Bóka og Senda á staðfestingu** svarglugginn birtir þá aðferð sem viðskiptamaðurinn vill nota til að taka á móti fylgiskjölum. Hægt er að breyta sendingaraðferð með því að velja uppflettihnappinn fyrir reitinn **senda skjal** Frekari upplýsingar er að finna á [Hvernig á að: Setja upp sendisnið skjala](sales-how-setup-document-send-profiles.md)

Tengdar vöru- og viðskiptamannafærslur eru nú búnar til í kerfinu og sölupöntunin er frálag sem PDF fylgiskjal. Þegar sölupantanir eru að fullu bókaðar, er þær fjarlægður af lista sölupantana og skipt út fyrir nýtt fylgiskjal á lista bókaðra sölureikninga og lista yfir bókaðar söluafhendingar.

## <a name="see-also"></a>Sjá einnig
[Sala](sales-manage-sales.md)  
[Uppsetning sölu](sales-setup-sales.md)  
[Birgðir](inventory-manage-inventory.md)  
[Hvernig á að: Senda skjöl í tölvupósti](ui-how-send-documents-email.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

