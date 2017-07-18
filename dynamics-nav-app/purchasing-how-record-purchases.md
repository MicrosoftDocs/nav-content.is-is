---
title: "Hvernig á að skrá kaup"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 6d1933bf1e1c9236d34d429a4da84c907df13708
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-record-purchases"></a>Hvernig á að skrá kaup
Innkaupareikningur eða innkaupapöntun er stofnaður til að skrá kostnaðarverð keyptra vara og til að rekja viðskiptaskuldir. Ef stjórna þarf birgðum eru innkaupareikningar og innkaupapantanir líka notaðir til að uppfæra birgðastig gagnvirkt svo að hægt sé að lágmarka birgðakostnað og veita betri þjónustu við viðskiptavini. Innkaupakostnaður, að þjónustukostnaði meðtöldum, og birgðavirði sem leiðir af bókun innkaupareikninga eða -pantanir verða hluti af framlegðartölum og öðrum fjárhagslegum afkastavísum í hlutverkamiðstöðinni heimasíða þinni.

**Athugasemd**: verður Að nota innkaupapantanir ef innkaupaferlið krefst þess að hægt sé að skrá hlutamóttökur pöntunarmagns , til dæmis þar sem allt magnið var ekki tiltæk í hjá lánardrottinn. Ef vara er seld með því að afhenda beint frá lánardrottni til viðskiptamanns, sem bein sending þarf að einnig nota innkaupapantanir. Nánari upplýsingar eru í [Hvernig á að gera bein sending](sales-how-drop-shipment.md). Frá öllum sjónarhornum séð virka innkaupapantanir á sama hátt og innkaupareikningar. Eftirfarandi ferli byggist á innkaupareikningur. Skrefin eru svipuð fyrir innkaupapöntun.

Þegar þú tekur við birgðavörum eða þegar innkaupaaðgerð er lokið bókarðu innkaupareikninginn eða -pöntun til að uppfæra birgðir og fjármálaskrár og til að virkja greiðslu til lánardrottins, samkvæmt greiðsluskilmálum. Frekari upplýsingar er að finna á [framkvæma greiðslu](payables-make-payments.md)

**Áminning**: Ekki bóka innkaupareikning þar til vörur eru mótteknar og lokakostnaður er vitaður, þ.m.t. viðbótargjöld. Annars kunna birgðagildi og hagnaðartölur er vera röng.

Ef þegar hefur verið greitt fyrir vörur á bókuðum innkaupareikningi, þá verður að búa til innkaupakreditreikning til að snúa við innkaupunum. Nánari upplýsingar er að finna í [Hvernig á að: Vinna úr innkaupaskilum eða afturköllunum](purchasing-how-process-purchase-returns-cancellations.md).

Framleiðsluvörur geta bæði verið birgðavörur og þjónusta. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md). Innkaupareikningaferlið er það sama fyrir báðar vörutegundir.



Hægt er að fylla út  lánardrottnareitina í innkaupareikningunum með tveimur leiðum, eftir því hvort lánardrottinninn hefur þegar verið skráður.

## <a name="to-create-a-purchase-invoice"></a>Að Stofna innkaupareikning
1. Í heimasíða veldu **innkaupareikningur** aðgerð.  
2. Í reitnum **lánardrottinn** er fært inn nafn núverandi viðskiptamanns.

    Aðrir reitir í glugganum **innkaupareikningur** eru nú fylltir út með stöðluðum upplýsingum um lánardrottinn sem valinn hefur verið. Ef lánardrottinn er ekki skráður, fylgið eftirfarandi skrefum:
3. Í reitnum **lánardrottinn** er fært inn nafn nýs lánardrottinn.
4. Í svarglugganum um að skrá nýja lánardrottinn, veljið hnappinn **Já**.
5. Í glugganum **Velja sniðmát fyrir nýjan lánardrottinn**, skal velja sniðmát til að byggja nýja lánardrottnaspjaldið á og veljið hnappinn **Í lagi**.
6. Nýtt viðskiptamannaspjald opnast, fyrirfram fyllt út með upplýsingnum á valda viðskiptamannasniðmátinu. Reiturinn **Heiti** er fyrirfram fylltur út með nafni nýja lánardrottinsins sem fært var inn á innkaupareikninginn.
7. Haltu áfram að fylla út eftirstandandi reiti á spjaldi lánardrottins. Nánari upplýsingar eru í [Hvernig á að skrá nýjan lánardrottnar](purchasing-how-register-new-vendors.md).  
8. Þegar lokið hefur verið við lánardrottinsspjaldið skal velja hnappinn **Í lagi** til að fara aftur í gluggann **Innkaupareikningur**.

    Margir reitir í glugganum **innkaupareikningur** eru útfylltir með upplýsingar sem tilgreindar eru á nýju lánardrottinnspjaldi.
9. Fylltu í eftirstandandi reiti í glugganum **innkaupareikningur** eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

    Þú ert nú tilbúiinn að fylla út innkaupareikningslínurnar með birgðavöru eða þjónustu þú hefur keypt af lánardrottninum.

    **Athugasemd**: Ef endurteknar innkaupalínur hafa verið settar upp fyrir lánardrottinn, svo sem mánaðarlegar áfyllingarpantanir, er hægt að færa línurnar inn í reikninginn með því að velja aðgerðina **Ítrekaðar innkaupalínur**.
10. Á flýtiflipanum **Línur** í reitnum **vörunúmer** sleginn inn fjöldi birgðavöru eða þjónustu.
11. Í reitinn **Magn** er fært fjöldi vara sem á að kaupa.

    **Athugasemd**: Fyrir vörur af tegundinni **Þjónusta** er magnið tímaeining, t.d. klukkutímar, eins og gefið er til kynna í reitnum **Mælieiningarkóði** í línunni

    Reiturinn **línuupphæð** uppfærist til að sýna að gildið í reitnum **beint innkaupsverð** margfaldað með gildinu í reitnum **magn**.

    Verð- og línuupphæð eru sýndar með eða án VSK, en það fer eftir því hvað var valið í reitnum **verð með skatti** á lánardrottinsspjaldinu.
12. Í reitnum **afsláttarupphæð reiknings** færið inn upphæð sem draga á frá gildinu sem sýnt er í reitnum **Heildarupphæð með skatti** neðst á reikningnum.

    **Athugasemd**: Ef reikningsafslættir hafa verið settir upp fyrir lánardrottinn, er tilgreint prósentugildi sjálfvirkt fært inn í reitinn **reikningsafsláttur % lánardrottins** ef viðmiðum hefur verið mætt og upphæðin færð inn í reitinn **afsláttarupphæð reiknings**.
13. Þegar tekið er við innkeyptar vörur eða þjónustu velja **Bóka**.

Innkaupin eru nú skráð í birgðafærslum og fjármálafærslum og greiðsla lánardrottins er virkjuð. Innkaupareikningurinn er fjarlægður af lista innkaupareikninga og skipt út fyrir nýtt fylgiskjal á lista bókaðra innkaupareikninga.

## <a name="see-also"></a>Sjá einnig  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)  
[Setja upp innkaup](purchasing-setup-purchasing.md)  
[Hvernig á að: kaupa vörur til endursölu](purchasing-how-purchase-products-sale.md)  
[Hvernig á að skrá nýja lánardrottna](purchasing-how-register-new-vendors.md)  
[Hvernig á að undirbúa Beina sendingu](sales-how-drop-shipment.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

