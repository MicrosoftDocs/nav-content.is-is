---
title: "Stofna skjal á innleið úr skjölum"
description: "Hægt er að stofna færslur yfir skjöl á innleið, eins og t.d. rafræna reikninga, og stjórna OCR-verkum, netviðskiptum og skjalaskiptum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fd8eba03f98d4d667a25639c1c958edf6936b0cb
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-incoming-document-records-directly-from-documents-and-entries"></a>Hvernig á að: Stofna færslur yfir Skjöl á innleið, beint frá Skjöl og Færslur.
Hægt er að vista ytri viðskiptaskjöl í [!INCLUDE[d365fin](includes/d365fin_md.md)] með því að hengja skjöl við tengdar færslur skjala á innleið. Ef skjalið, s.s. innkaupareikningur, var upprunlega ekki færsla skjals á innleið, er samt hægt að stofna og tengja færslur skjals á innleið við það síðar. Einnig er hægt að hengja skjöl á innleið við bókuð innkaupa- og söluskjöl og við færslur lánardrottins, viðskiptamanns og fjárhagsfærslur með því að nota upplýsingakassann **Skjöl á innleið** á til dæmis gluggunum **Bókaðir innkaupareikningar** og **Lánardrottnabók**.

Úr gluggunum **Bókhaldslyklar** og **Fjárhagsfærslur** er hægt að nota leitaraðgerð til að finna fjárhagsfærslur fyrir bókuð innkaupa- og söluskjöl sem hafa ekki færslur fyrir skjöl á innleið og tengjast miðlægt við fyrirliggjandi færslur eða stofna nýjar með viðhengdum skrám. Fyrir nánari upplýsingar, sjá [Hvernig á að: Finna bókuð skjöl án færslu skjals á innleið](across-how-find-posted-documents-without-income-document-records.md).

Eftirfarandi ferli sýna hvernig á að hengja skjal við fyrirliggjandi innkaupareikning sem var ekki stofnaður úr færslu skjals á innleið og hvernig á að hengja skjal við fjárhagsfærslu lánardrottins. Að festa viðhengi við bókað innkaupa- eða söluskjal fer fram á svipaðan hátt.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a>Að stofna og tengja færslu skjals á innleið úr innkaupareikningi
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innkaupareikningar** og velja svo viðeigandi tengil.
2. Veljið línu fyrir innkaupareikning sem á að hengja skrá við og veljið síðan aðgerðina **Búa til skjal á innleið úr skrá**.
3. Einnig er hægt að velja línu fyrir innkaupareikning sem á að hengja skrá við og velja svo aðgerðina **Hengja skrá við**.
4. Í glugganum **Setja inn skrá** skal velja skrána sem táknar skjalið á innleið og svo hnappinn **Opna**.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a>Að stofna og tengja færslu skjals á innleið úr fjárhagsfærsla lánardrottins
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsfærslur lánardrottins** og velja svo viðeigandi tengil.
2. Veljið línu fyrir lánardrottnafærslu sem á að hengja skrá við og veljið síðan aðgerðina **Búa til skjal á innleið úr skrá**.
3. Einnig er hægt að velja línu fyrir lánardrottnafærslu sem á að hengja skrá við og velja svo aðgerðina **Hengja skrá við**.
4. Í glugganum **Setja inn skrá** skal velja skrána sem táknar skjalið á innleið og svo hnappinn **Opna**.

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a>Til að fjarlægja tengingu á milli færslu fyrir skjal á innleið og bókaðs skjals
Hægt er að fjarlægja viðhengi skjals úr óbókuðum skjölum hvenær sem er með því að eyða tengdum færslum fyrir skjöl á innleið. Ef skjalið er bókað verður fyrst að fjarlægja tengingu úr færslu fyrir skjal á innleið.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **skjöl á innleið** og velja svo viðeigandi tengil.
2. Veljið línu fyrir færslu skjals á innleið sem tengist bókaða fylgiskjalinu sem á að fjarlægja og veljið svo aðgerðina **Fjarlægja tilvísun í skrá**.

Tengingin við bókað skjal var var fjarlægt. Nú er hægt að tengja aðra færslu skjals á innleið við bókað skjal eins og lýst er í þessu efnisatriði.

## <a name="see-also"></a>Sjá einnig
[Vinnsla skjala á innleið](across-process-income-documents.md)  
[Skjöl á innleið](across-income-documents.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

