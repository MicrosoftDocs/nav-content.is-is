---
title: "Hvernig á að: Setja upp skjöl á innleið"
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
ms.openlocfilehash: 2bce97c76876c86a576ec6a281a306a46881027c
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-incoming-documents"></a>Hvernig á að: Setja upp skjöl á innleið
Ef stofnaðar eru færslubókarlínur úr færslum skjala á innleið verður að tilgreina í í glugganum **Uppsetning fyrir skjöl á innleið** hvaða sniðmát færslubókar og runu á að nota.

Ef notendur eiga ekki að geta stofnað reikninga eða færslubókarlínur úr færslum skjala á innleið nema skjöl séu fyrst samþykkt verður að setja upp samþykkjendur í glugganum **Samþykkjendur skjala á innleið**.

Til að Breyta PDF og myndaskrám í rafræn skjöl sem er hægt að breyta í, til dæmis innkaup reikninga innkaupareikninga innan Dynamics NAV, verður að fyrst að setja upp eiginleikann OCR og virkja þjónustu.

Þegar eiginleikinn Skjöl á innleið er uppsettur, er hægt að nota ólíkar aðgerðir til að yfirfara kostnaðarkvittanir, sýsla með OCR-verk og breyta skjölum á innleið, handvirkt eða sjálfvirkt, yfir í viðkomandi skjöl eða færslubókarlínur. Ytri skrárnar er hægt að hengja við tengd skjöl á öllum stigum úrvinnslunnar, þ.m.t. við bókuð skjöl og við færslur lánardrottins, viðskiptamanns eða fjárhags sem verða til. Nánari upplýsingar er að finna í [Hvernig á að vinna skjöl á innleið](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>Setja upp valkostinn fyrir skjal á innleið
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning skjala á innleið**, og velja síðan viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

## <a name="to-set-up-approvers-of-incoming-document-records"></a>Að setja upp samþykkjendur fyrir skjöl á innleið
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning skjala á innleið**, og velja síðan viðeigandi tengil.  
2. Í glugganum **Skjal á innleið** skal velja aðgerðina **Samþykkjendur**

    Glugginn **Samþykkjendur skjala á innleið** sýnir alla notendur sem hafa verið settir upp í Dynamics NAV.  
3. Veldu einn eða fleiri notendur sem geta samþykkt innsent skjal áður en hægt er að stofna fylgiskjals - eða bókarlínu.

Þegar samþykkjendur hafa verið settir upp í glugganum **Samþykkjendur skjala á innleið** geta aðeins þessir notendur samþykkt skjal á innleið ef gátreitur **Krefjast samþykkis fyrir stofnun** í glugganum **uppsetning skjala á innleið** er valinn.

**Athugasemd**: þessi uppsetning samþykkis er ekki tengt samþykktarverkflæðum. Nánari upplýsingar sjá [hvernig á að: nota Samþykkisverkflæði](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>Til að setja upp OCR-þjónustu
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **uppsetning OCR-þjónustu**, og velja síðan viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.


## <a name="to-encrypt-your-login-information"></a>Til að dulrita innskráningarupplýsingar
Mælt er með því að vernda innskráningarupplýsingar sem slegnar eru inn í **uppsetning OCR-þjónustu** gluggann. Hægt er að dulrita gögn á  netþjóninum með því að stofna nýjan dulritunarlykil eða flytja inn fyrirliggjandi lykla sem eru virkjaðir er á netþjónstilviki sem tengist við gagnagrunninn.

1. Í **uppsetning fyrir OCR-þjónusta** glugganum, veldu **stjórnun dulritunar**.
2.  Í glugganum **gagnadulritun**, virkja dulritun gagnanna.

## <a name="see-also"></a>Sjá einnig  
[Vinnsla skjala á innleið](across-process-income-documents.md)  
[Skjöl á innleið](across-income-documents.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

