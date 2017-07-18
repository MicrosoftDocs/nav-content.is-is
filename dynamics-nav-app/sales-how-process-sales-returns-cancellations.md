---
title: "Meðhöndlun söluvöruskila eða afturkallana"
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
ms.openlocfilehash: 92b65379f2ec633712a2b2c0f06615c6de61cc6e
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-process-sales-returns-or-cancellations"></a>Meðhöndlun söluvöruskila eða afturkallana
Ef viðskiptamaður vill skila vörum eða fá endurgreiðslu fyrir vöru eða þjónustu sem honum hefur verið veitt og búið er að greiða fyrir verður að búa til og bóka sölukreditreikning sem tilgreinir breytingarnar sem óskað er eftir. Til að taka með réttar sölureikningsupplýsingar, er hægt að stofna sölukreditreikning úr bókaða innkaupareikningnum eða nota aðgerðina afritun.

Auk upprunalega bókaðs sölureiknings, er hægt að jafna sölukreditreikning öðrum söluskjölum, t.d. aðra bókað sölureikninga, þar sem viðskiptamaðurinn er einnig að skila vörum sem voru afhentar með viðkomandi reikningi.

Skil eða endurgreiðsla getur átt við um aðeins hluta af vörum eða þjónustum á upprunalega sölureikningnum. Í því tilviki þarf að breyta upplýsingum í línunum á sölukreditreikningnum. Við bókun sölukreditreiknings eru þau söluskjöl sem eru breytingin hefur áhrif á bakfærð og hægt er að stofna endurgreiðslu til viðskiptamannsins.

Hægt er að senda bókaða sölukreditreikninga til viðskiptamannsins til að staðfesta vöruskil eða afturköllun og miðla því að virðið verði endurgreitt, til dæmis þegar vörum er skilað.

## <a name="to-create-a-sales-credit-memo-from-a-posted-sales-invoice"></a>Að stofna nýjan sölukreditreikning úr bókuðum sölureikningi.
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Bókaðir sölureikningar**, og velja síðan viðeigandi tengil.  
2. Í glugganum **Bókaðir sölureikningar** skal velja þá bókuðu sölureikninga sem á að bakfæra og veljið síðan aðgerðina **Stofna leiðréttan kreditreikning**.

    Flestir reitirnir í á sölukreditreikningshausnum eru fylltir út með upplýsingum úr bókaða sölureikningnum. Hægt er að breyta allir reitir, til dæmis með nýjar upplýsingar sem endurspegla endursenda samkomulagið.
3. Breytið upplýsingum í línunum í samræmi við samninga, eins og fjöldi þeirra vara sem skilað eða endurgreiðsluupphæð.
4. Valið er **Jafna Færslur** aðgerð.
5. Í glugganum **Jafna viðskm.færslur** skal velja línuna með bókaða söluskjalinu sem á að jafna sölukreditreikninginn við og veljið síðan aðgerðina **Kenni jöfnunar**.

    Númer sölukreditreikningsins er sett í reitinn **Kenni jöfnunar**.  
6. Í reitnum  **Upphæð til jöfnunar** er rituð upphæðin sem á að jafna ef hún er lægri en upprunalega upphæðin.

    Neðst á glugganum **Jafna viðskm.færslur** er hægt að skoða heildarupphæðina sem á að nota til að bakfæra allar færslur, nefnilega þegar gildið í reitnum **Staða** er núll.  
7. Velja hnappinn **Í lagi**. Þegar sölukreditreikningurinn er bókaður, verður hann jafnaður við tilgreind bókuð söluskjöl.

    Þegar línur fyrir sölukreditreikningana hafa verið stofnaðar eða þeim breytt og ein eða fleiri jöfnun tilgreind, er hægt að bóka sölukreditreikninginn.
8. Veljið aðgerðina **Bóka og senda**.

Í **Bóka og Senda staðfestingu** svargluggi opnast og sýnir notuð valda sendingaraðferð fyrir viðskiptamanninn. Hægt er að breyta sendingaraðferð með því að velja uppflettihnappinn í reitnum **Senda skjal** til. Frekari upplýsingar er að finna á [Hvernig á að: Setja upp sendisnið skjala](sales-how-setup-document-send-profiles.md)

Bókuðu söluskjölin sem jafnað var við kreditreikninginn eru nú bakfærðir og endurgreiðslu má nú búa til fyrir viðskiptamanninn. Sölukreditreikningurinn er fjarlægður og skipt út fyrir nýtt fylgiskjal á lista bókaðra sölukreditreikninga.

## <a name="to-create-a-sales-credit-memo-from-scratch"></a>Að búa til sölukreditreikning frá grunni
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bókaður sölureikningur** og velja síðan viðkomandi tengil.
2. Veljið aðgerðina **Nýtt** til að opna nýjan auðan sölukreditreikning.
3. Í reitnum **Viðskiptamaður** er fært inn nafn núverandi viðskiptamanns.
4. Valið er **Afrita fylgiskjal** aðgerð.
5. Í glugganum **Afrita söluskjal** í reitnum **Gerð skjals** skal velja **Bókaður reikningur**.
6. Veljið **skjalanúmer** reitinn til að opna gluggann **Bókaðir sölureikningar** og velið síðan bókaða sölureikninginn sem inniheldur línur sem þú vilt bakfæra.
7. Veljið gátreitinn **Endurreikna línur**, ef bókaða sölureikningslínan sem var afrituð á að uppfærast með breytingum á vöruverði og kostnaðarverði síðan reikningurinn var bókaður.
8. Velja hnappinn **Í lagi**. Afrituðu reikningslínurnar eru settar inn í sölukreditreikninginn.
9. Sölukreditreikningnum er lokið eins og útskýrt er í hlutanum "Að stofna sölukreditreikning úr bókuðum sölureikningi" í þessu efnisatriði.

## <a name="see-also"></a>Sjá einnig  
[Stjórna sölu](sales-manage-sales.md)  
[Uppsetning sölu](sales-setup-sales.md)  
[Hvernig á að: Senda skjöl í tölvupósti](ui-how-send-documents-email.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

