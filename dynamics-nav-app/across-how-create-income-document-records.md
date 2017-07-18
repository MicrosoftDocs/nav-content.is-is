---
title: "Hvernig á að stofna skjöl á innleið"
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
ms.openlocfilehash: 10ba191b197be8b98b2d5d5ab9ac4bc3baf0d82b
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-incoming-document-records"></a>Hvernig á að stofna skjöl á innleið
Í glugganum **Skjöl á innleið** er hægt að nota ólíkar aðgerðir til að yfirfara kostnaðarkvittanir, sýsla með OCR-verk og breyta skjölum á innleið, handvirkt eða sjálfvirkt, yfir í viðkomandi skjöl eða færslubókarlínur í. Ytri skrárnar er hægt að hengja við tengd skjöl á öllum stigum úrvinnslunnar, þ.m.t. við bókuð skjöl og við færslur lánardrottins, viðskiptamanns eða fjárhags sem verða til.

Til að skrá ytra skjal í Dynamics NAV verður fyrst að stofna eða ljúka við færsla skjal á innleið. Þú getur gert þetta með handvirkt, eða þú getur tekið mynd af ytra skjal og síðan að búa til skjal á innleið með myndaskrá í viðhengi.

Áður en hægt er að nota valkostinn Skjöl á innleið þarf að framkvæma áskilda uppsetningu. Nánari upplýsingar er að finna í [Hvernig á að setja upp skjöl á innleið](across-how-setup-income-documents.md).

## <a name="to-approve-or-reject-an-incoming-document"></a>Til að samþykkja eða hafna fylgiskjali á innleið
Ef notendur eiga að geta stofnað reikninga eða færslubókarlínur úr færslum skjala á innleið nema skjöl séu fyrst samþykkt er hægt að setja upp samþykkjendur sem verða að samþykkja færslur áður en þær má vinna.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skjöl á innleið**, og velja síðan viðeigandi tengil.
2. Valin er línan með skjalinu sem á að samþykkja eða hafna og síðan valið á **Samþykkja** eða **Hafna** aðgerðir.

Ef færsla skjals á innleið er samþykkt er gátreiturinn **Losað** á línu skjal á innleið valinn. Notandi sem stjórnar t.d. stofnun innkaupareikninga getur haldið áfram að vinna úr færslunni.

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a>Til að stofna færslur skjala á innleið með því að taka mynd
**Athugið**: Eftirfarandi ferli á aðeins við um Dynamics NAV hvað varðar spjaldtölvu- og símaviðskiptavini.

1. Á forritastikunni skal velja **Stofna skjal á innleið úr myndavél** reitinn og fara svo í skref 4..
2. Að öðrum kosti skal á forritastikunni velja valkostahnappinn, velja **Skjöl á innleið** og velja svo **Öll**.
3. Í glugganum **Skjöl á innleið** skal velja úrfellingarmerkishnappinn og svo **Stofna úr myndavél**. Kveikt er á myndavél spjaldtölvu eða síma.
4. Takið mynd af skjali, t.d. innkaupakvittun, sem á að vinna sem skjal á innleið, og veljið svo hnappur **Í lagi**.

Ný færsla skjals á innleið er stofnað með mynd í viðhengi.

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a>Til að hengja mynd við skjal á innleið færsla með því að taka mynd
**Athugið**: Eftirfarandi ferli á aðeins við um Dynamics NAV hvað varðar spjaldtölvu- og símaviðskiptavini.

1. Á forritastikunni velja valkostahnappinn, velja **Skjöl á innleið** og velja svo **Öll**.
2. Opnið kort fyrir fyrirliggjandi færsla skjal á innleið.
3. Í glugganum **Skjal á innleið** skal velja úrfellingarmerkishnappinn og svo **Hengja við mynd úr myndavél**. Kveikt er á myndavél spjaldtölvu eða síma.
4. Takið mynd af skjali, t.d. innkaupakvittun, sem á að vinna sem skjal á innleið, og veljið svo hnappur **Í lagi**.

Myndin er hengja við færsla skjal á innleið.

## <a name="to-create-an-incoming-document-record-manually"></a>Tila ð búa til færslu skjals á innleið handvirkt
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skjöl á innleið**, og velja síðan viðeigandi tengil.
2. Aðgerðin **Stofna úr Skrá** er valin.  
3. Í glugganum **Setja inn skrá** skal velja skrána sem táknar skjalið á innleið og svo hnappinn **Opna**.

    Skráin er hengd við sjálfkrafa.
4. Einnig er hægt að velja aðgerðina **Nýtt**.
5. Ef tengja á skrá, skal velja **Tengja Skrá** aðgerð.
6. Í glugganum **Setja inn skrá** skal velja skrána sem táknar skjalið á innleið og svo hnappinn **Opna**.
7. Í glugganum **Skjal á innleið** þarf að fylla reitina út eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

##<a name="see-also"></a>Sjá einnig  
[Vinnsla skjala á innleið](across-process-income-documents.md)  
[Skjöl á innleið](across-income-documents.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

