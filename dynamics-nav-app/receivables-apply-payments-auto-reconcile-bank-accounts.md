---
title: "Jafna greiðslur sjálfkrafa og afstemma bankareikninga"
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
ms.openlocfilehash: 11df387c16e19421090531fd03c209103b9989d9
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="apply-payments-automatically-and-reconcile-bank-accounts"></a>Jafna greiðslur sjálfkrafa og afstemma bankareikninga
Þú verður reglulega að afstemma bankann þinn, útistandandi kröfur og viðskiptaskuldir í Dynamics NAV með því að jafna greiðslur skráðar í bankanum við tengda ógreidda reikninga og kreditreikninga, eða aðrar opnar færslur í Dynamics NAV

Þú getur framkvæmt þessi verk í **greiðsluafstemmingarbók** glugganum með því að flytja inn bankayfirlitsskrá eða streymi til að skrá greiðslurnar á fljótlegan hátt í Dynamics NAV. Sjálfvirk jöfnunaraðgerð jafnar greiðslur við tengdar opnar viðskiptavina- og lánadrottnafærslur á grunni gagnasamsvörunar á milli greiðslutexta og færsluupplýsinga. Hægt er að skoða og breyta sjálfvirk jafnanir áður en færslubókin er bókuð. Þú getur valið að loka öllum opnum bankareikningsfærslum sem tengjast jöfnuðu fjárhagsfærslunum þegar þú bókar færslubókina. Þetta þýðir að bankareikningurinn er sjálfvirkt stemmdur af þegar allar greiðslur eru jafnaðar.

Til að virkja innflutning bankayfirlits sem bankastreymis, verður þú að setja upp og virkja Envestnet Yodlee bankastreymisþjónustu, og tengja síðan bankareikningana við viðkomandi netbankareikninga. Frekari upplýsingar sjá [Hvernig: Setja á Upp Envestnet Yodlee bankastreymisþjónustu](bank-how-setup-bank-statement-service.md).

**Athuga skal að**: Þá Envestnet Yodlee Banka Feeds þjónustupöntunarinnar eða banki anther provider á feed þjónustu kunna að vera tiltækar í kerfinu. Tengiliður félaginn Microsoft ef notaður er bankareikningur feed þjónustu til að flytja inn bankayfirlit.

Einnig geturðu notað Umreikningsþjónustu fyrir bankagögn til að láta umbreyta bankayfirliti sem þú fékkst úr bankanum þínum í gagnastraum sem hægt er að flyja inn í Dynamics NAV. Nánari upplýsingar er að finna í [Hvernig á að: Setja upp umreikningsþjónustu fyrir bankagögn](bank-how-setup-bank-data-conversion-service.md).

Eftirfarandi tafla lýsir röð verkefna með tenglum í efnisatriði þar sem þeim er lýst.

|Til |Sjá |
|---|----|
|Jafna greiðslur við opnar viðskiptavina- eða lánardrottnafærslur með því að flytja inn bankayfirlit, og afstemma bankareikning þegar allar greiðslur eru jafnaðar. | [Hvernig á að afstemma greiðslur með sjálfvirkri jöfnun](receivables-how-reconcile-payments-auto-application.md) |
|Jafnaðu greiðslur handvirkt með því að skoða ítarlegar upplýsingar um samsvöruð gögn og tillögur um mögulegar færslur til að jafna greiðslur á. | [Hvernig á að: Endurskoða eða sækja um greiðslur eftir sjálfvirkan umsókn](receivables-how-review-apply-payments-auto-application.md)
|Leysa greiðslur sem ekki er hægt að jafna sjálfkrafa við tengdar opnar fjárhagsfærslur, , t.d. vegna þess að upphæðirnar eru mismunandi eða vegna þess að tengd fjárhagsfærsla er ekki til. | [Hvernig á að: afstemma greiðslur sem ekki er hægt að afstemma sjálfkrafa](receivables-how-reconcile-payments-cannot-apply-auto.md)
|Tengja skal texta á greiðslum við tiltekinn viðskiptamanns-, lánardrottins- eða fjárhagsreikning til að bóka alltaf endurtekna móttöku eða útgjöld reiðufés á þá reikninga þegar engin skjöl eru til til að beita þessu.| [Hvernig á að: Varpa texta um endurteknar greiðslur í reikninga fyrir sjálfvirka afstemmingu](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)|

## <a name="see-also"></a>Sjá einnig
[Umsjón viðskiptakrafna](receivables-manage-receivables.md)  
[Stjórna sölu](sales-manage-sales.md)

