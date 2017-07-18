---
title: "Hvernig á að: Senda skjöl í tölvupósti"
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
ms.openlocfilehash: e4476c2ab903001017dcd6c8bdaa84892ba79c9e
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-send-documents-by-email"></a>Hvernig á að: Senda skjöl í tölvupósti
Hægt er að nota aðgerðina Uppsetning skýrslu til að miðla efni fyrir sértæk viðskiptaskjöl sem fer sjálfkrafa inn í tölvupóst til að gefa upplýsingar um innihald viðskiptaskjala hratt og vel til viðskiptafélaga þinna.

Til að virkja tölvupósta innan Dynamics NAV, skal ræsa hjálparuppsetninguna **Setja upp tölvupóst** á heimasíðu.

Hægt er að senda nær allar skjalategundir sem viðhengi í tölvupóstskilaboðum beint úr glugganum sem sýnir skjalið. Auk viðhengis er hægt að setja upp tölvupóstskilaboð sem eru sértæk fyrir ákveðin skjöl með kjarnaupplýsingum úr viðkomandi skjali, þar sem stöðluð kveðja og kynning á skjalinu kemur á undan þeim upplýsingum. Til að hægt sé að bjóða viðskiptamönnum til að greiða rafrænt fyrir sölur með rafrænni greiðsluþjónustu, t.d. PayPal, er einnig hægt að láta PayPal upplýsingar og tengla í meginmáli tölvupóstsins.

Úr öllum studdum skjölum er tölvupóstur virkjaður með því að velja aðgerðina **Senda** í bókuðum skjölum, eða aðgerðina **Bóka og senda** í skjölum sem eftir á að bóka.

Ef reiturinn **Tölvupóstur** í glugganum **Senda skjal til** er stilltur á **Já (Biðja um Stillingar)**, mun glugginn **Senda tölvupóst** opnast með tengiliðinn fyrirfram skráðan í reitnum **Til:** og skjalið hengt við sem PDF-skrá. Í reitnum **Meginmál** er annað hvort hægt að færa textann inn handvirkt eða hafa reitinn fylltur út með fyrirfram uppsettum meginmálslínum sem eru sértækar fyrir skjalið.

Eftirfarandi ferli sýnir hvernig á að setja skýrsluna **Sala - Reikningur** upp til að nota fyrir meginmálslínur tölvupósts sem eru sértækar fyrir skjalið þegar bókaðir sölureikningar eru sendir í tölvupósti.

## <a name="to-set-up-a-document-specific-email-body-for-sales-invoices"></a>Að setja upp meginmálslínur tölvupósts sem eru sértækar fyrir sölureikninga.
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skýrsluval - sala**, og velja síðan viðeigandi tengil.
2. Í glugganum **Skýrsluval - Sala** í reitnum **Notkun** skal velja **Reikningur**.
3. Í nýrri línu í reitnum **Skýrslukenni** skal velja t.d. staðlaða skýrslu 1306.
4. Veljið gátreitinn **Nota fyrir meginmál tölvupósts**.
5. Veljið reitinn **Útlitsauðkenni meginmáls tölvupósts** og veljið síðan eitt af tiltæku útliti úr glugganum **Sérsniðið skýrsluútlit**.
6. Skýrsluútlit skilgreinir bæði stílsnið og innihald meginmáls tölvupósts, þar á meðal staðlaðan texta sem fer á undan skjalaupplýsingum í meginmáli tölvupóstsins.
7. Í glugganum **Sérsniðið skýrsluútlit** skal velja **Breyta útliti** til að skoða eða breyta því útliti sem meginmál tölvupóstsins byggist á.
8. Til að hægt sé að bjóða viðskiptamönnum að greiða rafrænt fyrir sölur er hægt að setja upp tengda rafræna greiðsluþjónustu, til dæmis PayPal, og láta PayPal upplýsingar og tengla í meginmál tölvupóstsins. Nánari upplýsingar eru í [Hvernig á að: Virkja greiðslur viðskiptamanns gegnum PayPal](sales-how-enable-customer-payments-paypal.md).
9. Velja hnappinn **Í lagi**.

Nú þegar t.d. er valið aðgerðin Senda í glugganum **Bókaður Sölureikningur** munu meginmálslínur tölvupósts innihalda upplýsingar fylgiskjals skýrslu 1306 á eftir sérsniðnum stöðluðum texta í samræmi við skýrsluútlitið sem valið var í 5. þrepi.

Eftirfarandi ferli sýnir hvernig eigi að senda bókaðan sölureikning sem tölvupóst með fylgiskjalið í viðhengi sem PDF-skrá og með meginmál tölvupósts sem á sérstaklega við skjalið.
## <a name="to-send-documents-by-email"></a>Að senda fylgiskjöl með tölvupósti
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bókaður sölureikningur** og velja síðan viðkomandi tengil.
2. Veljið viðeigandi sölureikning og veljið aðgerðina **Senda**. Glugginn **Senda skjal til** opnast.
3. Í reitnum **Tölvupóstur** skal velja **Já (biðja um stillingar)**. Frekari upplýsingar er að finna á [Hvernig á að: Setja upp sendisnið skjala](sales-how-setup-document-send-profiles.md)
4. Velja hnappinn **Í lagi**. Glugginn **Senda tölvupóst** opnast.
5. Í reitnum **Til:** er fært inn gilt netfang. Sjálfgefna gildið°er netfang viðskiptamannsins.
6. Í reitinn **Afrit:** skal tilgreina netfang til að senda afrit af tölvupóstinum á annan viðtakanda.
7. Í reitinn **Falið afrit** skal tilgreina netfang til að senda afrit af tölvupóstinum á annan viðtakanda án þess að netfang og nafn viðkomandi birtist öðrum viðtakendum.
8. Lýsandi texti er færður inn í reitinn **Efni**. Sjálfgefna gildið er nafn og reikningsnúmer viðskiptamannsins.
9. Í reitnum **Viðhengi** er myndaður reikningur sjálfgefið hengdur við sem PDF-skrá. Veljið uppflettingarhnappinn til að opna skrána eða til að tengja aðra skrá.
10. Í reitinn **Meginmál** skal slá inn stutt skilaboð til viðtakanda.

    Ef meginmál tölvupósts sértækt fyrir skjal er sett upp í glugganum **Skýrsluval - Sala** er reiturinn **Meginmálslínur** útfylltur sjálfkrafa. Nánari upplýsingar eru í hlutanum“Að setja upp Að setja upp meginmálslínur tölvupósts sem eru sértækar fyrir sölureikninga” í þessu efnisatriði.
11. Veljið gátreitinn **Breyta í Outlook Web App** til að opna tölvupóstskilaboð í tölvupóstsmáforritinu í Office 365.
12. Veldu hnappinn **Í lagi** til að senda tölvupóstinn.

**Athugasemd**: Ef ekki þarf að tilgreina stillingar tölvupósts í hvert sinn sem skjal er sent í tölvupósti er hægt að velja valkostinn **Já (nota sjálfgefnar stillingar)** í glugganum **Senda skjal til**. Í því tilfelli mun glugginn **Senda tölvupóst** ekki opnast. Sjá skref 4. Frekari upplýsingar er að finna á [Hvernig á að: Setja upp sendisnið skjala](sales-how-setup-document-send-profiles.md)

## <a name="see-also"></a>Sjá einnig  
[Unnið með Dynamics NAV](ui-work-product.md)  
[Hvernig er reikningsfært](sales-how-invoice-sales.md)

