---
title: "Hvernig á að: Setja upp umreikningsþjónustu fyrir bankagögn"
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
ms.openlocfilehash: 801e2abee52ec9804028a797e4f330b5e080549a
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-the-bank-data-conversion-service"></a>Hvernig á að: Setja upp umreikningsþjónustu fyrir bankagögn
Hægt er að flytja út greiðslulínum úr á **greiðslubók** glugganum í gagnastreymi sem þú síðan hleður upp í bankann þinn fyrir sjálfvirka vinnslu svo að þú þarft ekki að gera rafræn greiðsla í sitthvoru lagi. Nánari upplýsingar sjá [Hvernig: Flytja Greiðslur í bankaskrá](payables-how-export-payments-bank-file.md).

Altæk þjónustuveita til að umreikna greiðsluupplýsingar í hvaða gagnaskráarsnið sem bankinn þinn þarf eru uppsett og tilbúið til að vera virkjað í Dynamics NAV.

Sem annar valkostur við Envestnet Bankastreymisþjónustuna, geturðu nota búnaðinn Umreikningsþjónustu fyrir bankagögn til að láta umbreyta bankayfirliti sem þú fékkst úr bankanum þínum í gagnastraum sem hægt er að flyja inn í Dynamics NAV. Nánari upplýsingar er að finna í [hvernig á að: Jafna greiðslur sjálfkrafa og stemma af bankareikninga](receivables-apply-payments-auto-reconcile-bank-accounts.md).

**Athugasemd** Umskráningarþjónusta fyrir bankagögn kann að setja hámark á það hversu margar línur má flytja út í einni skrá. Ef farið er yfir hámarkið munu koma upp villuboð. Mælt er með því að bankayfirlitsskrár fari ekki yfir 1.000 línur þar sem vinnslutími umreikningsþjónusta bankagagna kann þá að aukast til muna.

## <a name="to-sign-your-company-up-for-the-bank-data-conversion-service"></a>Að skrá fyrirtækið fyrir umreikningsþjónustu bankagagna
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **uppsetning umreikningsþjónustu fyrir bankagögn** og velja síðan viðkomandi tengil.  
2. **Uppsetning Umreikningsþjónusta fyrir bankagögn** Glugginn opnast með þremur reitum útfylltum með viðeigandi vefslóðir frá veitanda umreikningsþjónustu fyrir bankagögn.

    **Athugasemd**: Í CRONUS International Ltd. sýnigagnagrunnui, eru notandanafn og lykilorð reitirnir fylltar með sýnidæmum um innskráningarupplýsingar sem þú verður að skipta út með raunverulegum upplýsingum fyrirtækis þíns þegar þú skráir þig fyrir umreikningsþjónustu bankagagna.
3. Í **innskráningarvefslóð** reitnum, veldu vafrahnappinn til að opna innskráningarsíðu þjónustuveitunnar.  
4. Á skráningarsíðu þjónustuveitu bankagagna skal slá inn notandanafn og aðgangsorð fyrir áskrift fyrirtækisins að þjónustunni og ljúka svo skráningarferlinu samkvæmt leiðbeiningum þjónustuveitunnar.

    Fyrirtæki þitt er nú skráð fyrir umreikningsþjónustu bankagagna. Sláið inn notandanafn og aðgangsorð sem tilgreind voru fyrir þjónustuna í tengdum uppsetningarreitum í Dynamics NAV.
5. Í **uppsetning umreikningsþjónustu fyrir bankagögn** glugga í **notandanafn** reitnum, sláðu inn sama gildi sem þú færðir inn sem innskráningarnafn á síðu þjónustuveitunnar í 4. skrefi.
6. Í  reitnum **lykilorð**, sláðu inn sama gildi sem þú færðir inn í reitinn **Aðgangsorð** á síðu þjónustuveitunnar í 4. skrefi.

## <a name="to-encrypt-your-login-information"></a>Til að dulrita innskráningarupplýsingar
Mælt er með því að vernda innskráningarupplýsingar sem slegnar eru inn í **uppsetning umreikningsþjónustu fyrir bankagögn** gluggann. Hægt er að dulrita gögn á Dynamics NAV netþjóninum með því að stofna nýjan dulritunarlykil eða flytja inn fyrirliggjandi lykla sem eru virkjaðir er á Dynamics NAV netþjónstilviki sem tengist við gagnagrunninn.

1. Í **uppsetning umreikningsþjónustu fyrir bankagögn** glugganum, veldu **stjórnun dulritunar**.
2.  Í glugganum **gagnadulritun**, virkja dulritun gagnanna.

##<a name="to-view-or-update-the-list-of-currently-supported-bank-data-formats"></a>Til að skoða eða uppfæra listann yfir studd bankagagnasnið
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **uppsetning umreikningsþjónustu fyrir bankagögn** og velja síðan viðkomandi tengil.
2. Á glugganum **uppsetning umreikningsþjónustu fyrir bankagögn** , skal velja **Nafn banka – umskráningarlisti gagna** til að opna lista yfir nöfn banka sem standa fyrir bankagagnasnið sem eru studd af umskráningarþjónustunni.
3. Á síðunni **Nafn banka – gagnaumreikningslisti**, veldu **uppfæra nafnalista banka**

Listi yfir bankagagnasnið sem eru studd af umreikningsþjónustunni fyrir bankagögn er nú uppfærður. Þetta er listinn yfir nöfn banka, afmörkuð eftir landi/svæði, sem hægt er að velja úr í reitnum **Nafn banka - gagnaumreikningur** í glugganum **Bankareikningsspjald**.

**Athugasemd**: Uppfærsla studdra bankagagnasniða á sér einnig stað þegar gildi er valið eða slegið inn í reitinn **Nafn banka - gagnaumreikningur** á bankareikningnum.

Þú hefur nú skráð þig fyrir umreikningsþjónustu bankagagna. Halda áfram að endurspegla skráningarupplýsingar í öllum bankareikningum sem nota þjónustuna.

## <a name="to-set-up-bank-accounts-to-use-the-bank-data-conversion-service"></a>Að setja upp bankareikninga til að nota umreikningsþjónustu fyrir bankagögn
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **bankareikning** og velja síðan viðkomandi tengil.
2. Opnið spjaldið fyrir bankareikninginn sem á að flytja bankaskrár út og inn fyrir með umreikningsþjónustu fyrir bankagögn.
3. lÁ flýtiflipanum **Millifærsa**, í reitnum **greiðsluútflutningssnið** skal velja **Umreikningsþjónusta fyrir bankagögn – kreditmillifærsla** til að setja upp fyrir útflutning greiðslu.
4. Í reitinn **Nafn banka - gagnaumreikningur** skaltu slá inn eða velja nafn gagnasniðs bankareiknings er sem þú skráðir þig fyrir í skrefi 4 í hlutanum “Að skrá sig fyrir umreikningsþjónustu bankagagna.”
5. Endurtaktu skref 1 til 4 fyrir annarra bankareikninga sem vilja nota eiginelikann Umreikningsþjónustu bankagagna

## <a name="see-also"></a>Sjá einnig  
[Uppsetning bankaþjónustu](bank-setup-banking.md)  
[Stjórna bankareikningum](bank-manage-bank-accounts.md)

