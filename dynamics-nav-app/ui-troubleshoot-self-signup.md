---
title: "Úrræðaleit innskráning í sjálfsafgreiðslu"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 931c427518694cbd0003ea82735292a019b388d5
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="troubleshooting-self-service-sign-up"></a>Úrræðaleit innskráning í sjálfsafgreiðslu
Innskráning fyrir Dynamics NAV er auðvelt og er hægt að gera mjög skjótan hátt. Hægt er að stofna reikning án endurgjalds jafnvel þó að þú sért fyrirtæki sem þegar er til. Þessi grein fjallar um vandamál sem gætu komið upp við innskráningu.

## <a name="what-email-address-can-i-use-with-dynamics-nav"></a>Hvaða tölvupóstfang get ég notað með Dynamics NAV?
Dynamics NAV krefst að þú notir vinnu eða skóla netfang til að nýskrá. Dynamics NAV styður ekki netföng frá tölvupóstfangsveitendum sem þjónusta neytendur eða frá fjarskiptafyrirtækjum. Þetta felur í sér outlook.com, hotmail.com, gmail.com og aðra.

Ef þú reynir að nýskrá með einka tölvupóstfang færðu skilaboð sem gefa til kynna að þú eigir að nota vinnu eða skóla netfang.

## <a name="troubleshooting"></a>Úrræðaleit
Í mörgum tilfellum er innskráning í Dynamics NAV möguleg með því að fylgja eftirfarandi innskráningarferli. Hins vegar eru nokkrar ástæður fyrir því að þú getur ekki verið fær um að ljúka sjálfsafgreiðslu innskráningu. Taflan hér að neðan er yfirlit yfir nokkrar af algengustu ástæðum fyrir því að vera ekki fær til að ljúka skráningunni og leiðir sem þú getur farið við að leysa þessi vandamál.

|Einkenni/villuboð:                                                                              |Ástæða og leið framhjá|
|--------------------------------------------------------------------------------------------------|--------------------|
|Fyrir Office 365 tölvupóstfang sem eru ekki skráð í USA, geturðu fengið skilaboð eins og þessi við innskráningu: <br>**Þetta gekk ekki, við styðjum ekki land þitt eða svæði enn.**<br> |Dynamics NAV styður eins og er aðeins Office 365 reikninga sem eru skráðir tölvupóstar í USA.|
|Persónulegir tölvupóstfang eins og nancy@gmail.com eru ekki studd. Þú færð skilaboð eins og þessi við innskráningu: <br>**Þú færðir inn einka tölvupóstfang: vinsamlegast færðu inn vinnutölvupóstfang svo við getum geymt gögn fyrirtækis þíns á öruggan hátt.**<br> Eða <br> **Það lítur út eins og persónulegt netfang. Færðu inn póstfang svo við getum tengt þig við aðra í fyrirtækinu. Og ekki hafa áhyggjur. Við munum ekki deila netfanginu þínu með neinum.** | Dynamics NAV styður ekki netföng frá tölvupóstfangsveitendum sem þjónusta neytendur eða frá fjarskiptafyrirtækjum. Til að klára innskráninguna, reyndu aftur með því að nota tölvupóstfang sem þér var úthlutað af skólanum eða vinnunni. Ef þú getur enn ekki skrá sig og ert tilbúin/n til að ljúka ítarlegra uppsetningarferli, getur þú skrá sig fyrir nýjum Office 365 prufuáskrift og nota það netfang til að skrá þig inn.
|.gov eða .mil tölvupóstfang Þú færð skilaboð eins og eftirfarandi við innskráningu: <br>**Dynamics NAV er ótiltækt: Dynamics NAV er ekki tiltækt fyrir notendur með .gov eða .mil tölvupóst eins og stendur. Notaðu annað vinnu tölvupóstfang eða athugaðu aftur seinna.** <br>Eða <br>**Við getum ekki lokið við að skrá þig. Það lítur út fyrir að Dynamics NAV er ekki í boði fyrir vinnu þína eða skóla.**|Dynamics NAV styðja ekki þennan .gov eða .mil póstföng eins og stendur.|
|Sjálfsafgreiðslu innskráning er ekki virkjuð. Þú færð skilaboð eins og þessi við innskráningu: <br>**Við getum ekki lokið við að skrá þig. Tölvudeildin þín hefur slökkt á skráningu fyrir Dynamics NAV. Hafðu samband við þá til að ljúka skráningu.** <br>Eða <br> **Það lítur út eins og persónulegt netfang. Færðu inn póstfang svo við getum tengt þig við aðra í fyrirtækinu. Og ekki hafa áhyggjur. Við munum ekki deila netfanginu þínu með neinum.**|Kerfisstjóri fyrirtækis þíns hefur slökkt á sjálfsafgreiðslu innskráningu fyrir Dynamics NAV. Til að klára innskráninguna, hafðu samband við tæknistjóra og biddu þá um að fara að leiðbeiningunum í síðunni fyrir neðan til að leyfa fyrirliggjandi notendum að innskrá sig í Dynamics NAV og leyfa nýjum notendum að ganga til liðs við núverandi leigjanda. Þú gætir einnig upplifað þetta vandamál ef þú skráðir þig í Office 365 í gegnum félaga.|
|Tölvupóstfang er ekki Office 365 kenni. Þú færð skilaboð eins og þessi við innskráningu: <br>**Við getum ekki fundið þig á contoso.com. Notarðu annað auðkenni í vinnunni eða skólanum? Prófaðu að skrá þig inn og ef það virkar ekki skaltu hafa samband við tæknideildina þína.**|Fyrirtæki þitt notar kenni til að skrá sig inn í Office 365 og aðrar Microsoft þjónustur, sem eru aðrar en tölvupóstfang þitt. Til dæmis gæti netfangið þitt verið Nancy.Smith@contoso.com en auðkenni þitt nancys@contoso.com. Til að ljúka við innskráningu, notaðu kenni sem fyrirtæki þitt hefur úthlutað til að skrá sig inn í Office 365 eða aðrar Microsoft þjónustur. Ef þú veist ekki hvað það er, hafðu samband við tæknistjórann þinn. Ef þú getur enn ekki skrá sig og getur lokið ítarlegra uppsetningarferli, getur þú skrá sig fyrir nýjum Office 365 prufuáskrift og nota það netfang til að skrá þig inn.|


## <a name="see-also"></a>Sjá einnig
[Velkomin í Dynamics NAV](across-get-started.md)  
[Unnið með Dynamics NAV](ui-work-product.md)




