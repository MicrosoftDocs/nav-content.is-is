---
title: Bankareikningar settir upp
description: "Hægt er að afstemma bankareikninga í Dynamics NAV við yfirlit frá bankanum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: feed, stream
ms.date: 09/26/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3581615fe94006aa9245f5e66fe6cf475b22acfb
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-bank-accounts"></a>Hvernig á að setja upp Bankareikninga lánardrottna
Þú notar bankareikninga í [!INCLUDE[d365fin](includes/d365fin_md.md)] til að fylgjast með bankafærslunum þínum. Hægt er að hafa reikninga í SGM eða erlendum gjaldmiðli. Þegar bankareikningar hafa verið settir upp er einnig hægt að nota valkostinn prentskoðun.

## <a name="to-set-up-bank-accounts"></a>Bankareikningar settir upp
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bankareikningar** og velja svo viðeigandi tengil.
2. Í glugganum **bankareikningar** skal velja aðgerðina **Nýtt**.
3. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]
> Til að fylla út í reitinn **Staða** með onunarstöðu verður þú að bóka fjárhagsfærslu bankareiknings með upphæðinni. Hægt er að gera þetta með því að framkvæma afstemmingu bankareiknings. Frekari upplýsingar í [hvernig á að: Afstemma Bankareikninga Sérstaklega](bank-how-reconcile-bank-accounts-separately.md). Einnig er hægt að tiltaka opnunarstöðu sem hluta af almennri gagnamyndun í nýjum fyrirtækjum með því að nota hjálpina fyrir **Flytja viðskiptagögn**. Nánari upplýsingar sjá í [Velkomin í [!INCLUDE[d365fin](includes/d365fin_md.md)](index.md).

## <a name="to-set-up-your-bank-account-for-import-or-export-of-bank-files"></a>Til að setja upp bankareikning þinn til að flytja inn eða flytja út bankaskrár
Reitir á **Flutningur** flýtiflipanum í **Bankareikningsspjald** glugganum eru tengdir innflutningi og útflutningi á banka straumum og skrám. Nánari upplýsingar er að finna í [Hvernig á að: Setja upp umreikningsþjónustu fyrir bankagögn](bank-how-setup-bank-data-conversion-service.md).

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bankareikningar** og velja svo viðeigandi tengil.
2. Opnaðu kortið fyrir bankareikning sem þú vilt flytja út eða flytja inn bankaskrár fyrir.
3. Fyllt er út í reiti eftir því sem við á í flýtiflipanum **Flytja**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   Mismunandi útflutningsþjónusta skráa og snið þeirra þurfa mismunandi uppsetningargildi í glugganum **Bankareikningsspjald**. Þú færð að vita um uppsetningargildi sem eru röng eða sem vantar þegar þú reynir að flytja út skrána. Svo lestu stuttar lýsingar á reitunum vandlega eða vísaðu til viðkomandi efnisferlis. Til dæmis, við útflutning greiðsluskráar fyrir kortamillifærslu NA (EFT) þarf að fylla út reitina **Síðasta greiðslutilkynningarnúmer** og **Kenninúmer**. Nánari upplýsingar sjá [Hvernig: Flytja Greiðslur í bankaskrá](payables-how-export-payments-bank-file.md).

## <a name="to-set-up-vendor-bank-accounts-for-export-of-bank-files"></a>Til að setja upp bankareikninga lánardrottna fyrir útflutning bankaskráa
Reitir á **Flutningur** flýtiflipanum í **Bankareikningsspjald lánardrottins** glugganum eru tengdir innflutningi og útflutningi á banka straumum og skrám. Nánari upplýsingar er að finna í [Hvernig á að: Setja upp umreikningsþjónustu fyrir bankagögn](bank-how-setup-bank-data-conversion-service.md) og [Hvernig á að: Flytja út greiðslur í bankaskrá](payables-how-export-payments-bank-file.md).

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **lánardrottnar** og velja svo viðeigandi tengil.
2. Opnaðu kortið fyrir lánardrottinn með bankareikning sem þú sendir út greiðslubankaskrár til.
3. Veldu aðgerðina **Bankareikningar**.
3. Í glugganum **Bankareikn.spjald lánardr** á flipanum **Flutningur** fylltu inn reitina eftir því sem þörf er á. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-the-opening-balance-on-new-bank-accounts"></a>Til að stilla opnunarstöðuna á nýjum bankareikningum


## <a name="see-also"></a>Sjá einnig
[Uppsetning bankaþjónustu](bank-setup-banking.md)  
[Stjórna bankareikningum](bank-manage-bank-accounts.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

