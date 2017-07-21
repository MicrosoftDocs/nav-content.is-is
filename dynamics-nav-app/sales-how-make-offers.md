---
title: "Hvernig á að: Gera tilboð"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e126c755a9121c3a91f3af72f3f1ae14702a4701
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-offers"></a>Hvernig á að: Gera tilboð
Búið er til sölutilboð til að skrá tilboðið við viðskiptamann um að selja tilteknar vörur með tilteknum afhendingar- og greiðsluskilmálum. Hægt er að senda sölutilboð til viðskiptamannsins til að miðla tilboðinu. Hægt er að senda skjalið í tölvupósti sem PDF viðhengi. Hægt er að láta meginmálslínur tölvupósts vera útfyllt fyrirfram með tilboði. Nánari upplýsingar sjá [Hvernig á að: Senda Skjöl með Tölvupóst](ui-how-send-documents-email.md).

Þegar samið er við viðskiptamanninn, er hægt að breyta og endursenda sölutilboðið eins mikið og oft og þörf er á. Þegar viðskiptamaður tekur tilboði, er sölutilboðinu breytt í sölureikning eða sölupöntun þar sem salan er meðhöndluð. Nánari upplýsingar eru í [Hvernig á að reikningsfæra sölu](sales-how-invoice-sales.md) eða [hvernig á að: selja vörur.](sales-how-sell-products.md)

Framleiðsluvörur geta bæði verið birgðavörur og þjónusta. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md). Sölutilboðsferlið er það sama fyrir báðar vörutegundir.

**Athugasemd**: Í Dynamics NAV er vísað í afurð með hugtakið “vara”.

Hægt er að fylla út viðskiptamannsreitina á sölutilboðinu með tveimur leiðum, eftir því hvort viðskiptamaðurinn hefur þegar verið skráður.

## <a name="to-create-a-sales-quote"></a>Sölutilboð búin til:
1. Í heimasíða veldu **sölutilboð** aðgerð.  
2. Í reitnum **Viðskiptamaður** er fært inn nafn núverandi viðskiptamanns.

    Aðrir reitir í glugganum **sölutilboð** eru nú fylltir út með stöðluðum upplýsingum um viðskiptamanninn sem valinn hefur verið. Ef viðskiptamaður er ekki skráður, fylgið eftirfarandi skrefum:

3. Í reitnum **Viðskiptamaður** er fært inn nafn nýs viðskiptamanns.
4. Í svarglugganum um að skrá nýja viðskiptavininn, veljið hnappinn **Já**.
5. Í glugganum **Velja sniðmát fyrir nýjan viðskiptamann**, skal velja sniðmát til að byggja nýja viðskiptamannaspjaldið á og veljið hnappinn **Í lagi**.
6. Nýtt viðskiptamannaspjald opnast, fyrirfram fyllt út með upplýsingnum á valda viðskiptamannasniðmátinu. Reiturinn **Nafn** er fyrirfram fylltur út með nafni nýja viðskiptamannsins sem fært var inn á sölureikninginn.
7. Haltu áfram að fylla út eftirstandandi reiti á spjaldi viðskiptamanns. Nánari upplýsingar eru í [Hvernig á að skrá nýjan viðskiptamaður](sales-how-register-new-customers.md).  
8. Þegar lokið hefur verið við viðskiptamannaspjaldið skal velja hnappinn **Í lagi** til að fara aftur í gluggann **sölutilboð**.

    Margir reitir í sölutilboði eru nú fullir af upplýsingar sem tilgreindar voru á nýja viðskiptamannaspjaldi.
9. Fylltu í eftirstandandi reikningana í glugganum **sölutilboð** eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

    Þú ert nú tilbúinn að fylla út í sölutilboðslínurnar með birgðavöru eða þjónustu sem bjóða viðskiptamanninum.

    **Athugasemd**: Ef endurteknar sölulínur hafa verið settar upp fyrir viðskiptamanninn, svo sem mánaðarlegar endurnýjunarpantanir, er hægt að færa línuna inn í tilboð með því að velja aðgerðina **Endurteknar sölulínur**.
10. Á flýtiflipanum **Línur** í reitnum **vörunúmer** sleginn inn fjöldi birgðavöru eða þjónustu.
11. Í reitinn **Magn** er fært magn vara sem á að bjóða.

    Fyrir vörur af tegundinni **Þjónusta** er magnið tímaeining, t.d. klukkutímar, eins og gefið er til kynna í reitnum **Mælieiningarkóði** í línunni

    Reiturinn **línuupphæð** uppfærist til að sýna að gildið í reitnum **einingarverð** margfaldað með gildinu í reitnum **magn**.

    Verð- og línuupphæðirnar eru sýndar með eða án VSK, en það fer eftir því hvað var valið í reitnum **verð með VSK** á viðskiptamannaspjaldinu.
12. Í reitnum **Línuafsláttur %**, færið inn prósentutölu ef veita á viðskiptamanninum afslátt af vörunni. Gildið í reitnum **Línuupphæð** er uppfært til samræmis.

    **Athugasemd**: Ef sérstakt vöruverð hefur verið sett upp á flýtiflipanum **Afslættir söluverðs og sölulínu** á viðskiptamanns- eða birgðaspjaldinu uppfærist verðið og upphæðin á tilboðslínunni sjálfvirkt ef umsamin verðviðmið hafa náðst. Nánari upplýsingar eru í [Skrá söluverð, afslátt og greiðslusamkomulag](sales-how-record-sales-price-discount-payment-agreements.md).
13. Til að bæta við athugasemd um tilboðslínu sem viðskiptavinurinn getur séð á prentuðu sölureikningi, skrifaðu texta í **Lýsingarsvæði** sviði í auða línu.  
14. Endurtakið skref 10 til 13 fyrir hverja birgðavöru sem bjóða á viðskiptamanninum.

    Samtölur fyrir neðan línurnar eru sjálfkrafa reiknaðar þegar þú stofna eða breyta línur.
15. Í reitnum **afsláttarupphæð reiknings** færið inn upphæð sem draga á frá gildinu sem sýnt er í reitnum **Heildarupphæð með skatti**.

    **Athugasemd**: Ef reikningsafslættir hafa verið settir upp fyrir viðskiptamanninn, er tilgreint prósentugildi sjálfvirkt fært inn í reitinn **reikningsafsláttur %** ef viðmiðum hefur verið mætt og viðkomandi upphæðin færð inn í reitinn **afsláttarupphæð reiknings án skatts**. Nánari upplýsingar eru í [Skrá söluverð, afslátt og greiðslusamkomulag](sales-how-record-sales-price-discount-payment-agreements.md).
16. Þegar sölutilboðslínunum er lokið, skal velja aðgerðina **tölvupósti** eða **Prenta**.

    Ef **Tölvupóstur** aðgerð er valið er PDF-skrá hengd sjálfkrafa við tölvupóst til viðskiptavinar. Hægt er að láta tölvupósts innihalda samantekt tilboðs. Nánari upplýsingar sjá [Hvernig á að: Senda Skjöl með Tölvupóst](ui-how-send-documents-email.md).
17. Ef viðskiptamaðurinn samþykkir tilboðið, velja **Búa til Reikning** eða **búa til pöntun** aðgerð.

Sölutilboðið er fjarlægt úr gagnagrunninum. Sölureikningur eða sölupöntun er stofnaður byggður á upplýsingum í sölutilboðinu þar sem hægt er að vinna söluna. Í reitnum **Tilboðsnúmer** á sölureikningnum eða sölupöntun er hægt að sjá fjölda sölutilboða sem hann var búinn til úr. Nánari upplýsingar eru í [Hvernig á að reikningsfæra sölu](sales-how-invoice-sales.md) eða [hvernig á að: selja vörur.](sales-how-sell-products.md)

## <a name="see-also"></a>Sjá einnig  
[Stjórna sölu](sales-manage-sales.md)  
[Uppsetning sölu](sales-setup-sales.md)  
[Hvernig á að: Senda skjöl í tölvupósti](ui-how-send-documents-email.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

