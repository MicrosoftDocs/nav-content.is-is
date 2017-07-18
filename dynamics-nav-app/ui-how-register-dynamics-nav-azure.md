---
title: "Hvernig á að: Skrá Dynamics NAV í Azure stjórnunargáttinni"
author: edupont04
manager: edupont
ms.author: edupont
ms.custom: na
ms.date: 11/15/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 225773f7f686dd6e9a79f759d520d66f7e7b9d0a
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---
# <a name="how-to-register-dynamics-nav-in-the-azure-management-portal"></a>Hvernig á að: Skrá Dynamics NAV í Azure stjórnunargáttinni
Eigi að nota byggt á Microsoft Azure þjónustu þarf að skrá á Dynamics NAV Portal Azure Stjórnun. Til dæmis á [Sölu og Birgðum Spá](ui-extensions-sales-forecast.md) nafnaukanum þarf að tilgreina API lykillinn og API URI og annarri þjónustu microsoft krefjast svipaðar upplýsingar. Svo þar sem það er að finna upplýsingar sem?

Hægt er að nota í **Setja Upp Azure Stjórnun Portal** leiðarvísir skrá Azure Stjórnun Portal Dynamics NAV og til að ná upplýsingum sem þarf að nota þjónustu á borð við Sölu og Birgðir Spá beint, BI Öflugir, Office 365 og svo framvegis. Nauðsynlegt er að skrá í Azure Stjórnun Portal aðeins einu sinni, og verður að kerfisstjóri eða yfirnotandi í Dynamics NAV.

Bent á vöruhúsatínsluskjalið er skráð er sem Dynamics NAV og þjónustuvöru sem á að tengja við er nauðsynlegt að þekkja Azure Active Directory (Azure AD) upplýsingar um hvert öðru.

## <a name="to-register-dynamics-nav-in-the-azure-management-portal"></a>Til að skrá Azure Stjórnun Portal Dynamics NAV
1. Skrá er Portal Azure Stjórnun á [https://portal.azure.com](https://portal.azure.com).
    Ef ekki eru hafa þekkingu Portal Azure Viðskiptatengslastjórnunar er hægt að finna ákveða í reitnum [Azure documentation safn verksniðmáta](https://azure.microsoft.com/en-us/documentation/articles).
2. Vinstri yfirlitssvæðinu velja **Fleiri þjónustu**, og síðan valið **App skráningar**.
3. Efsta valmyndinni velja **bæta Við**, og síðan á **Stofna svæðinu**, fyllt út í reiti með eftirfarandi upplýsingum:
    - **Heiti**: Tilgreina nefna notanda lausnin, eins og *Dynamics NAV*.
    - **Tegund jöfnunar**: Velja * *Veftengingar app* / API**.
    - **Formerki-á URL**: Færð Veffangið á Dynamics NAV browser biðlara, t.d. *https://MyServer:8080/DynamicsNAV/WebClient/OAuthLanding.htm*.
        Skráin OAuthLanding.htm er skrá til við að stjórna gengi á gögnum á milli Dynamics NAV og aðrar þjónustu gegnum Azure AD.
4. Veldu hnappinn **Vista**.
    Dynamics NAV þannig að það bætir við **App skráningar svæðinu**, og nú er hægt að bæta stillingar á hann.
5. Í á **App skráningar listi**, velja app á ný. Ef þetta ekki opnaður á **Stillingar** er eigi að skoða aðgerð til að opna **Stillingar**.
6. Í sem **Stillingar** svæðinu í sem **API Aðgang** hlutanum, velja **Lyklar**.
7. Í reitnum **Lyklar** svæðinu, tilgreina lýsingu og þegar maður vill lykilinn falla úr gildi og síðan valið að láta **Vista**.
8. Afrita generated lykilinn tímabundinn staðsetning - þarf hana í næstu aðgerð.
9. Í **API-aðgangur** skal velja **Nauðsynlegar heimildir**.
    - Bætið við úthlutuðum heimildum til að sjá allar skýrslur til Power BI-þjónustunnar
    - Bætið við úthlutuðum heimildum til að innskrá og lesa notandaprófíl í Windows-Azure Active Directory
    - Þetta er endurtekið fyrir aðrar þjónustu sem á að veita aðgang að notanda Dynamics NAV
10. Loka sem **Stillingar** er og síðan á **Essentials** er afrita gildið í reitnum **Kenni Jöfnunar** til tímabundinn staðsetning sem.

Dynamics NAV hefur nú verið skráð í Azure-stjórnunargáttina, viðeigandi þjónustur hafa fengið heimildir og nauðsynlegar upplýsingar hafa verið sóttar í Dynamics NAV.  

## <a name="to-add-the-information-to-dynamics-nav"></a>Til að bæta upplýsingum við Dynamics NAV
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skýrsluval - sala**, og velja síðan viðeigandi tengil.
2. Álfinum valið **Næsta**.
3. Í reitnum **Biðlara Kenni** er tilgreint efni sem var afrituð úr á **Kenni Jöfnunar** reit fyrr.
4. Í reitnum **Biðlara Kenni** er tilgreint efni sem var afrituð úr á **Kenni Jöfnunar** reit fyrr.
5. Velja **Næsta**. Nema villuboð sjást er nú því.

Á Dynamics NAV er skráða og tilbúin til að tengja við þjónustu á borð við Cortana Intelligence og Öflugir BI.

## <a name="see-also"></a>Sjá einnig
[Spá um sölu og birgðir](ui-extensions-sales-forecast.md)  
[Setja upp eigið Dynamics NAV](setup.md)  

