---
title: "Hvernig á að: Selja vörur"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e45d67005364f7d45817d917ccaeab219b6f8446
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-sell-products"></a>Hvernig á að: Selja vörur
Búinn er til sölureikningur eða sölupöntun til að skrá samkomulag við viðskiptamann um að selja tilteknar vörur með tilteknum afhendingar- og greiðsluskilmálum.

**Athugasemd**: verður Að nota sölupantanir ef söluferlið krefst þess að hægt að afhenda hluta pöntunarmagns , til dæmis þar sem allt magnið er ekki tiltæk í einu. Ef vara er seld með því að afhenda beint frá lánardrottni til viðskiptamanns, sem bein sending þarf að einnig nota sölupantanir. Nánari upplýsingar eru í [Hvernig á að gera bein sending](sales-how-drop-shipment.md). Frá öllum sjónarhornum séð virka sölupantanir á sama hátt og sölureikningar. Nánari upplýsingar eru í [Hvernig á að reikningsfæra sölu](sales-how-invoice-sales.md).

Hægt er að semja við viðskiptamanninn með því að gera fyrst sölutilboð, sem hægt er að breyta í sölupöntun þegar samkomulag hefur náðst um söluna. Nánari upplýsingar eru í [Hvernig á að gera tilboð](sales-how-make-offers.md).

Þegar viðskiptamaðurinn hefur staðfest samninginn, til dæmis eftir tilboðsferli, geturðu sent staðfestingu pöntunar til að skrá afhendindingarskyldu vörunnar, eins og um var samið.

Þegar þú afhenda vörur, hvort sem er að fullu eða hluta, bókarðu sölupöntunina sem afhenta eða sem senda og reikningsfærða til að stofna viðkomandi vörufærslur og færslur í viðskiptamannabók í kerfinu. Við bókun sölupöntunar, er einnig hægt að senda skjalið í tölvupósti sem PDF viðhengi. Hægt er að láta meginmálslínur tölvupósts vera útfyllt fyrirfram með samantekt á pöntuninni og greiðsluupplýsingum, eins og tengli í PayPal. Nánari upplýsingar sjá [Hvernig á að: Senda Skjöl með Tölvupóst](ui-how-send-documents-email.md).

Í viðskiptaumhverfi þar sem viðskiptamaðurinn verður að greiða áður en vörur eru afhentar, til dæmis í smásölu, verður að bíða eftir greiðslukvittun fyrir vörunum áður en þær eru afhentar. Í flestum tilfellum er valið að vinna  greiðslur á innleið nokkrum vikum eftir afhendingu með því að jafna greiðslurnar við viðkomandi bókaða, ógreidda sölureikninga. Frekari upplýsingar eru í [hvernig á að afstemma greiðslur með því að nota sjálfvirka jöfnun](receivables-how-reconcile-payments-auto-application.md)

Ef bókaður sölureikningur er greiddur, verður að búa til sölukreditreikning til að afturkalla söluna. Fyrir frekar upplýsingar, sjá [hvernig á að: Meðhöndlun söluvöruskila eða afturkallana](sales-how-process-sales-returns-cancellations.md)

Framleiðsluvörur geta bæði verið birgðavörur og þjónusta. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md). Sölutilboðsferlið er það sama fyrir báðar vörutegundir.

**Athugasemd**: Í Dynamics NAV er vísað í afurð með hugtakið “vara”.

Hægt er að fylla út viðskiptamannsreitina á sölupöntunina með tveimur leiðum, eftir því hvort viðskiptamaðurinn hefur þegar verið skráður.

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
8. Fylltu í eftirstandandi reiti í glugganum **sölupöntun** eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

    Þú ert nú tilbúinn að fylla út í sölupöntunarlínurnar með birgðavöru eða þjónustu sem selja á viðskiptamanninum.

    Ef endurteknar sölulínur hafa verið settar upp fyrir viðskiptamanninn, svo sem mánaðarlegar endurnýjunarpantanir, er hægt að færa línuna inn í pöntunina með því að velja aðgerðina **Endurteknar sölulínur**.
9. Í flýtiflipanum **Línur** í reitnum **Vara** er sleginn inn fjöldi birgðavöru eða þjónustu.  
10. Í reitinn **Magn** er fært magn vara sem á að selja.

    Fyrir vörur af tegundinni **Þjónusta** er magnið tímaeining, t.d. klukkutímar, eins og gefið er til kynna í reitnum **Mælieiningarkóði** í línunni

    Reiturinn **línuupphæð** uppfærist til að sýna að gildið í reitnum **einingarverð** margfaldað með gildinu í reitnum **magn**.

    Verð- og línuupphæðirnar eru sýndar með eða án VSK, en það fer eftir því hvað var valið í reitnum **verð með skatti** á viðskiptamannaspjaldinu.
11. Í reitnum **Línuafsláttur %**, færið inn prósentutölu ef veita á viðskiptamanninum afslátt af vörunni. Gildið í reitnum **Línuupphæð** er uppfært til samræmis.

    Ef sérstakt vöruverð hefur verið sett upp á flýtiflipanum **Afslættir söluverðs og sölulínu** á viðskiptamanns- eða birgðaspjaldinu uppfærist verðið og upphæðin á tilboðslínunni sjálfvirkt ef umsamin verðviðmið hafa náðst. Nánari upplýsingar eru í [Skrá söluverð, afslátt og greiðslusamkomulag](sales-how-record-sales-price-discount-payment-agreements.md).
12. Til að bæta við athugasemd um tilboðslínu sem viðskiptavinurinn getur séð á prentuðu sölureikningi, skrifaðu texta í **Lýsingarsvæði** sviði í auða línu.  
13. Endurtakið skref 10 til 13 fyrir hverja birgðavöru sem bjóða á viðskiptamanninum.

    Samtölur fyrir neðan línurnar eru sjálfkrafa reiknaðar þegar þú stofna eða breyta línur.
14. Í reitnum **afsláttarupphæð reiknings** færið inn upphæð sem draga á frá gildinu sem sýnt er í reitnum **Heildarupphæð með skatti**.

    Ef reikningsafslættir hafa verið settir upp fyrir viðskiptamanninn, er tilgreint prósentugildi sjálfvirkt fært inn í reitinn **reikningsafsláttur %** ef viðmiðum hefur verið mætt og upphæðin færð inn í reitinn **afsláttarupphæð án skatts**. Nánari upplýsingar eru í [Skrá söluverð, afslátt og greiðslusamkomulag](sales-how-record-sales-price-discount-payment-agreements.md).
15. Til að afhenda Aðeins hluta pöntunarmagns, skal færa magn í reitinn **magn til Afhendingar** reit. Gildið er afritað í reitinn **magn til Reikningsfærslu**.
16. Til að reikningsfæra Aðeins hluta sends magns, skal færa magn í reitinn **magn til að reikningsfæra** . Magnið verður að vera minna en gildið í reitnum **Magn til að senda**.   
17. Þegar sölupöntunarlínunum er lokið, skal velja **bóka og senda** aðgerðina.
Í **Bóka og Senda staðfestingu** svargluggi opnast og sýnir notuð valda sendingaraðferð fyrir viðskiptamanninn.

Hægt er að breyta sendingaraðferð með því að velja uppflettihnappinn fyrir reitinn **senda skjal** Frekari upplýsingar er að finna á [Hvernig á að: Setja upp sendisnið skjala](sales-how-setup-document-send-profiles.md)

Tengdar vöru- og viðskiptamannafærslur eru nú búnar til í kerfinu og sölupöntunin er frálag sem PDF fylgiskjal. Þegar sölupantanir eru að fullu bókaðar, er þær fjarlægður af lista sölupantana og skipt út fyrir nýtt fylgiskjal á lista bókaðra sölureikninga og lista yfir bókaðar sendingar.

## <a name="see-also"></a>Sjá einnig  
[Stjórna sölu](sales-manage-sales.md)  
[Uppsetning sölu](sales-setup-sales.md)  
[Birgðir](inventory-manage-inventory.md)  
[Hvernig á að: Senda skjöl í tölvupósti](ui-how-send-documents-email.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

