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
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: d41b96ab5807402a342991d5c5bc2d672db09e2f
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-register-dynamics-nav-in-the-azure-management-portal"></a>Hvernig á að: Skrá Dynamics NAV í Azure stjórnunargáttinni
Til að nota þjónustu sem byggir á Microsoft Azure þjónustu þarf að skrá Dynamics NAV í Azure stjórnunargátt. Til dæmis á [Sölu og Birgðum Spá](ui-extensions-sales-forecast.md) nafnaukanum þarf að tilgreina API lykillinn og API URI og annarri þjónustu microsoft krefjast svipaðar upplýsingar. Svo þar sem það er að finna upplýsingar sem?

Hægt er að nota **Setja upp Azure stjórnunargátt** leiðsögn til að skrá Dynamics NAV í Azure stjórnunargátt og draga út upplýsingarnar sem eru nauðsynlegar til að nota þjónustu líkt og Spá um sölu og birgðir viðbót, Power BI, Office 365 o.s.frv.. Skráning í Azure stjórnunargátt er nauðsynleg aðeins einu sinni og þú verður að vera kerfisstjóri eða yfirnotandi í Dynamics NAV.

Dynamics NAV og þjónustan sem á að tengjast við verða að þekkja Azure Active Directory (Azure AD) upplýsingar um hvora aðra.

## <a name="to-register-dynamics-nav-in-the-azure-management-portal"></a>Til að skrá Dynamics NAV í Azure stjórnunargáttinni.
1. Skráðu þig inn í Azure Management Portal á [https://portal.azure.com](https://portal.azure.com). Ef notendur þekkja ekki Azure stjórnunargátt má finna upplýsingar á [Azure skjalasafni](https://azure.microsoft.com/en-us/documentation/articles).
2. Vinstri yfirlitssvæðinu velja **Fleiri þjónustu**, og síðan valið **App skráningar**.
3. Efsta valmyndinni velja **bæta Við**, og síðan á **Stofna svæðinu**, fyllt út í reiti með eftirfarandi upplýsingum:
    - **Heiti**: Tilgreindu heiti Dynamics NAV lausninnar, eins og *Dynamics NAV*.
    - **Tegund jöfnunar**: Velja **Veftengingar app* / API**.
    - **Formerki-á URL**: Færðu inn Veffangið á Dynamics NAV browser biðlara, t.d. *https://MyServer:8080/DynamicsNAV/WebClient/OAuthLanding.htm*.
        Skráin OAuthLanding.htm er skrá til við að stjórna gengi á gögnum á milli Dynamics NAV og aðrar þjónustu gegnum Azure AD.
4. Veldu hnappinn **Vista**.
    Þetta bætir Dynamics NAV við **Skráningasvæði forrits**, og nú er hægt að bæta stillingar á hann.
5. Í á **App skráningar listi**, velja app á ný. Ef þetta ekki opnaður á **Stillingar** er eigi að skoða aðgerð til að opna **Stillingar**.
6. Í sem **Stillingar** svæðinu í sem **API Aðgang** hlutanum, velja **Lyklar**.
7. Í reitnum **Lyklar** svæðinu, tilgreina lýsingu og þegar maður vill lykilinn falla úr gildi og síðan valið að láta **Vista**.
8. Afrita generated lykilinn tímabundinn staðsetning - þarf hana í næstu aðgerð.
9. Í **API-aðgangur** skal velja **Nauðsynlegar heimildir**.
    - Bætið við úthlutuðum heimildum til að sjá allar skýrslur til Power BI-þjónustunnar
    - Bætið við úthlutuðum heimildum til að innskrá og lesa notandaprófíl í Windows-Azure Active Directory
    - Endurtaktu þetta fyrir aðra þjónustu sem þú vilt veita aðgang að Dynamics NAV
10. Loka sem **Stillingar** er og síðan á **Essentials** er afrita gildið í reitnum **Kenni Jöfnunar** til tímabundinn staðsetning sem.

Nú hefur Dynamics NAV verið skráð í Azure stjórnunargáttinni og upplýsingar sem þarf í Dynamics NAV verið dregnar út.  

## <a name="to-add-the-information-to-dynamics-nav"></a>Til að bæta upplýsingunum við Dynamics NAV
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skýrsluval - sala**, og velja síðan viðeigandi tengil.
2. Álfinum valið **Næsta**.
3. Í reitnum **Biðlara Kenni** er tilgreint efni sem var afrituð úr á **Kenni Jöfnunar** reit fyrr.
4. Í reitnum **Biðlara Kenni** er tilgreint efni sem var afrituð úr á **Kenni Jöfnunar** reit fyrr.
5. Velja **Næsta**. Nema villuboð sjást er nú því.

Dynamics NAV er skráð og tilbúið til að tengjast við þjónustu líkt og Cortana Intelligence og Power BI.

## <a name="see-also"></a>Sjá einnig
[Spá um sölu og birgðir](ui-extensions-sales-forecast.md)  
[Setja upp Dynamics NAV](setup.md)  

