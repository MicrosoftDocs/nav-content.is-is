---
title: "Hvernig á að: Finna bókuð fylgiskjöl án færslu skjals á innleið"
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
ms.openlocfilehash: eb65922decc86ca6834cae4cf46c6f2ff492e29c
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a>Hvernig á að: Finna bókuð fylgiskjöl án færslu skjals á innleið
Úr gluggunum **Bókhaldslyklar** og **Fjárhagsfærslur** er hægt að nota leitaraðgerð til að finna fjárhagsfærslur fyrir bókuð innkaupa- og söluskjöl sem hafa ekki færslur fyrir skjöl á innleið og tengjast miðlægt við fyrirliggjandi færslur eða stofna nýjar með viðhengdum skrám.

## <a name="to-find-posted-documents-without-incoming-document-records"></a>Hvernig á að finna bókuð fylgiskjöl án færslu skjals á innleið
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **bókhaldslykill**, og velja síðan viðeigandi tengil.
2. Veljið línu fyrir þann fjárhagsreikning þar sem skoða á fjárhagsfærslur og bókuð innkaupa- og söluskjöl án færslna fyrir skjöl á innleið og veljið síðan **bókuð skjöl án skjal á innleið**
3. Einnig, Valið er **fjárhagsfærslur** aðgerð.
4. Í glugganum **fjárhagsfærslur**, veljið aðgerðina **bókuð skjöl án skjala á innleið**.

Glugginn **Bókuð fylgiskjöl án skjals á innleið** opnast og hann sýnir bókuð innkaupa- og söluskjöl án færslna fyrir skjöl á innleið sem tengjast fjárhagsfærslum á fjárhagsreikningi sem gluggninn var opnaður fyrir. Glugginn getur birt mest 1000 línur í einu. Sjálfgefið inniheldur reiturinn **dagsetningarafmörkun** því síu sem takmarkar línurnar við færslur með bókunardagsetningum frá upphafi bókhaldstímabils til vinnudagsetningar.

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a>Til að tengja fundin skjöl við fyrirliggjandi færslur skjala á innleið
1. Í glugganum **Bókuð fylgiskjöl án skjals á innleið** skal velja línu fyrir bókað skjal sem á að tengja við fyrirliggjandi færslu skjals á innleið, og veljið svo aðgerðina velja **skjal á innleið**.
2. Í **skjal á innleið** glugganum skal velja færslu fyrir skjal á innleið sem tengja á við bókað skjal sem fannst og velja svo hnappinn **Í lagi**.
3. Í glugganum **Bókuð fylgiskjöl án skjals á innleið** er valin færsla skjals á innleið nú tengt við bókaða skjalið, eins og sjá má í upplýsingakassanum **skrár fyrir skjal á innleið**.

Ef viðkomandi færsla skjals á innleið er ekki til í glugganum **skjal á innleið** er hægt að stofna hana. Frekari upplýsingar eru í [Hvernig á að stofna færslur fyrir skjal á innleið ](across-how-create-income-document-records.md).

## <a name="see-also"></a>Sjá einnig  
[Vinnsla skjala á innleið](across-process-income-documents.md)  
[Skjöl á innleið](across-income-documents.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

