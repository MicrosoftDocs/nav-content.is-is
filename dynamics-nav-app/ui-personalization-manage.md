---
title: "Stjórnun sérstillinga sem stjórnandi"
description: "Lærðu hvernig á að aðlaga notendaviðmótið til að henta því hvernig þú vinnur."
documentationcenter: 
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e3d088c35efca4d62b7db1f0d44d5ef2958317d4
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="managing-personalization-as-an-administrator"></a>Stjórnun sérstillinga sem stjórnandi
Notendur geta sérsniðið vinnusvæði sitt að vild. Sem stjórnandi geturðu stjórnað og unnið með sérstillingar með því að slökkva á valkosti notenda til að sérstilla síður og hreinsa allar sérstillingar síðu sem notendur hafa gert.

## <a name="disable-personalization-for-a-profile"></a>Slökkva á sérstillingu fyrir forstillingu
Hægt er að koma í veg fyrir að allir notendur sem tilheyra tiltekinni forstillingu geti sérstillt síður sínar.
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Forstillingar** og velja svo viðeigandi tengil.
2.  Veljið forstillinguna sem á að breyta í listanum.
3.  Veljið gátreitinn **Afvirkja sérstillingar notanda** og smellið síðan á hnappinn **Í lagi**.

## <a name="clear-user-personalizations"></a>Hreinsa sérstillingar notenda

Þegar sérstillingar síðu er eytt fer síðan aftur í upprunalegt útlit áður en sérstillingin var gerð. Það eru tvær leiðir til að hreinsa sérstillingar sem notendur hafa gert á síðum: með **Eyða sérstillingum notanda** síðunni og **Sérstillingaspjald notanda**.

### <a name="clear-user-personalizations-by-using-the-delete-user-personalization-page"></a>Hreinsa sérstillingar notenda með því að nota síðuna Eyða sérstillingum notanda

Síðan **Eyða sérstillingum notanda** gerir þér kleift að hreinsa sérstillingar á síðum, eftir notendum.

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Eyða sérstillingum notanda** og velja svo viðeigandi tengil.

    Á síðunni er listi yfir allar síður sem hafa verið sérstilltar og sem notandinn tilheyrir.

    >[!NOTE]
    > Gátmerki í **Eldri sérstilling** dálknum gefur til kynna að sérstillingin hafi verið framkvæmt strangt með því að nota [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] og/eða hún hafi verið gerð í [!INCLUDE[nav_web_md](includes/nav_web_md.md)] fyrir [!INCLUDE[navnow_md](includes/navnow_md.md)]. Notendur sem reyna að sérstilla þessar síður með því að nota [!INCLUDE[nav_web_md](includes/nav_web_md.md)] eru útilokaðir frá því að gera það nema þeir velji að opna síðuna. Frekari upplýsingar eru í [Af hverju er ekki hægt að sérstilla síðu](ui-personalization-locked.md). Nánari upplýsingar um sérstillingar milli [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] og [!INCLUDE[nav_web_md](includes/nav_web_md.md)], sjá [Unnið með sérstillingu milli Dynamics NAV Windows og vefbiðara](ui-personalization-overview.md#PersonalizationWinWeb).

2. Veljið færsluna sem á að eyða og veljið síðna aðgerðina **Eyða**.

    Notandinn mun sjá breytingarnar næst þegar hann skráir sig inn.

### <a name="clear-user-personalizations-by-using-the-user-personalization-card-page"></a>Hreinsa sérstillingar notenda með því að nota síðuna Sérstillingaspjald notanda

Síðan **Sérstillingaspjald notanda** gerir þér kleift að hreinsa sérstillingar á öllum síðum fyrir tiltekinn notanda. Þetta krefst skrifleyfis fyrir töflu 2000000072 **Forstilling**.

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Sérstillingar notanda** og velja svo viðeigandi tengil.

    Síðan **Sérstillingar notanda** sýnir alla notendur sem hugsanlega hafa sérstillt síður. Ef þú finnur ekki notanda á listanum þýðir það að hann hefur engar sérstilltar síður.

2. Veljið notanda af listanum og veljið svo aðgerðina **Breyta**.

3.  Í flipanum **Aðgerðir** veljið **Hreinsa sérstilltar síður**.

    Notandinn mun sjá breytingarnar næst þegar hann skráir sig inn.

## <a name="see-also"></a>Sjá einnig
[Yfirlit sérsniðs](ui-personalization-overview.md)  
[Sérstillingar verksvæðis](ui-personalization-user.md)  
[Unnið með [!INCLUDE[navnow_md](includes/navnow_md.md)]](ui-work-product.md)  
[Hvernig á að: Breyta Mitt hlutverk](change-role.md)  
