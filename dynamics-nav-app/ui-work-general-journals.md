---
title: "Vinna í færslubókum"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 2dc2b22fbc0ff70addd16ca14e8c5416c49915e7
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="work-with-general-journals"></a>Vinna í færslubókum
Þú notar Færslubækur eru til að bóka fjárhagsfærslur og aðra reikninga, svo sem banka-, viðskiptamanna-, lánardrottnareikninga. Bókun með almennri færslubók stofnar alltaf færslur á fjárhagsreikningum. Slíkt á við jafnvel í tilvikum þegar færslubókarlína er bókuð á reikning viðskiptamanns, vegna þess að færsla er bókuð í safnreikning færslubókar með bókunarflokki.

Upplýsingarnar sem eru færðar inn í færslubók eru til bráðabirgða og það er hægt að breyta þeim í færslubókinni. Þegar færslubókin er bókuð, eru upplýsingarnar færðar í færslur á einstökum reikningum, þar sem ekki er hægt að breyta þeim. Það er samt sem áður hægt að ógilda bókaðar færslur og snúa við bókunum eða leiðrétta bókanir.

## <a name="journal-templates-and-batches"></a>Sniðmát færslubóka og keyrslur
Til eru nokkur færslubókarsniðmát. Hvert sniðmát er með sérstakan glugga með ákveðnum aðgerðum og reitum sem verða að styðja aðgerðirnar, eins og **greiðsluafstemmingarbók** glugginn til að vinna bankagreiðslur og **greiðslubók** glugginn til að borga lánardrottnum þínum.

Fyrir hvert sniðmát færslubókar, geturðu sett upp þína eigin færslbók sem bókarkeyrsla. Til dæmis er hægt að skilgreina eigin færslubókarkeyrslu fyrir greiðslubók sem er með þitt persónulega útlit og stillingar.

**Athuga skal að**: dæmi um persónuleg stillingar sem hægt er að skilgreina á bókarkeyrslu er til að láta kerfið hjálpa þér að fulla í upphæðarreitina. Ef valið er **Leggja til afstemmingarupphæð** gátreitinn á línunni fyrir keyrsla í á **færslubókakeyrslur** glugganum, þá er **Upphæð** reiturinní, t.d. færslubókarlínur fyrir sama skjalnúmer sjálfkrafa forfyllt út með sama gildi sem þarf til að stemma fylgiskjal. Frekari upplýsingar eru í [Að láta Dynamics NAV leggja til gildi](ui-let-system-suggest-values.md)

## <a name="main-accounts-and-balancing-accounts"></a>Aðalreikningar og mótreikningar
Ef stofnaðir voru sjálfgefnir mótreikningar fyrir bókakeyrslur, eru mótreikningarnir fylltir út sjálfkrafa þegar fyllt er í reitinn **Reikningur nr** . Að öðrum kosti er fyllt bæði í reitinn **Reikningur nr.** og **Mótreikningur nr.** handvirkt. Jákvæð upphæð í reitnum **Upphæð** er tekin út af aðalreikningnum og lögð inn á mótreikninginn. Neikvæð upphæð er lögð inn á aðalreikninginn og tekin út af mótreikningnum.

**Athugasemd**: VSK er reiknaður út á aðskilin hátt fyrir aðalreikninginn og mótreikninginn, þannig að þar er hægt að nota mismunandi VSK prósentuhlutfall.

## <a name="recurring-journals"></a>Ítrekunarbækur
Ítrekunarbók er færslubók með sérstökum reitum til að stjórna færslum sem eru bókaðar reglulega með litlum eða engum breytingum. Með því að nota þessa reiti fyrir endurteknar færslur er hægt að bóka bæði fastar og breytilegar upphæðir. Einnig er hægt að tilgreina sjálfvirkar bakfærslur daginn eftir bókunardag og nota úthlutunarlykla fyrir ítrekunarfærslur.

## <a name="see-also"></a>Sjá einnig
[Hvernig á að nota úthlutunarlykla í færslubókum](ui-how-use-allocation-keys-general-journals.md)  
[Fjármál](finance-setup.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

