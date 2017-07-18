---
title: "Hvernig á að: Defer Tekjum og önnur Útgjöld"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 865bc307e8635b5a5aba11b5bc2e2e448c05e769
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-defer-revenues-and-expenses"></a>Hvernig á að: Defer Tekjum og önnur Útgjöld
Hægt er að nota þessa aðgerð til samþykktar tekna á eða fyrir kostnað tímabil en tímabil sem færslan var bókuð í til sjálfkrafa defer tekjum og önnur útgjöld yfir tiltekinni áætlun.

Dreifa tekjur eða útgjöld fjárhagstímabila sem á að setja upp sniðmát deferral sem forðinn, varan eða fjárhagsreikningurinn sem tekjur eða kostnaðinn bókast. Þegar tengdar sölu eða innkaupaskjal er bókað fylgiskjal á tekjur eða kostnaðinn eru deferred til sögu reikningstímabil samkvæmt tímaáætlun deferral sem er stjórnað af stillingar í sniðmáti deferral og bókunardagsetningu.

## <a name="to-set-up-a-gl-account-for-deferral"></a>Verð sett upp fyrir fjárhagsreikning verks:
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **bókhaldslykill**, og velja síðan viðeigandi tengil.
2. Valið er **Nýtt** aðgerð.
3. Fyllt er út í reiti sem nauðsynlegt að stofna reikning fyrir deferred tekjur Fjárhags. Frekari upplýsingar er að finna í [Fjárhagur og bókhaldslyklar](finance-setup-general-ledger.md).
3. Endurtaka skal þrep 2 og 3 eru endurtekin til að stofna nýjan reikning Fjárhags fyrir deferred útgjöld.

Fyrir báðar gerðir deferral, velja **Efnahagsreikningur** í reitnum **Tegund** og heiti reikninga athuga, t.d. "Óinnleystra Tekna" deferred tekjum og "Ógreidda Útgjöld" fyrir deferred útgjöld.

## <a name="to-set-up-a-deferral-template"></a>Uppsetning sniðmáts viðskiptamanns
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sniðmát eignabóka**, og velja síðan viðeigandi tengil.
2. Valið er **Nýtt** aðgerð.
3. Fyllið inn í svæðin eftir þörfum.
4. Í á **Reikningsaðferð** er tilgreint hvernig **Upphæð** á hverju tímabili í á **Deferral Áætlun** glugganum reiknuð. Hægt er að velja um eftirfarandi kosti:
    - **Línuleg**: reglubundin deferral upphæðir eru reiknaðar fjölda tímabila dreift eftir lengd tímabils.
    - **Línuleg**: reglubundin deferral upphæðir eru reiknaðar fjölda tímabila dreift eftir lengd tímabils.
    - **Línuleg**: reglubundin deferral upphæðir eru reiknaðar fjölda tímabila dreift eftir lengd tímabils.
    - **Notandi Skilgreinir**: reglubundin deferral upphæðir eru ekki reiknaðir. Handvirkt er þarf að fylla í reitinn Upphæð fyrir hvert tímabil í glugganum Deferral Áætlun. Frekari upplýsingar má fá í hlutanum "til Að breyta tímaáætlun deferral úr sölureikningi".

5. Í reitnum **Desc Tímabils.** Tilgreinir lýsingu sem verður birt í færslum fyrir bókun frestunar. Má færa kóta eftirfarandi frátaka fyrir dæmigerðum gildi sem er settur sjálfkrafa þegar tímabil lýsing birtist.
    - %1 = Daganúmer bókunardagsetningar tímabilsins
    - %2 = Vikunúmer bókunardagsetningar tímabilsins
    - %3 = Mánaðarnúmer bókunardagsetningar tímabilsins
    - %4 = Mánaðarheiti bókunardagsetningar tímabilsins
    - %5 = Heiti bókunartímabils bókunardagsetningar tímabilsins
    - %6 = Fjárhagsár bókunardagsetningar tímabilsins

Dæmi: Bókunardagsetningin er 02/06/2016. Ef fært er inn "Útgjöld deferred fyrir %4 %6" síðan birt lýsing verður "Útgjöld deferred fyrir Febrúar 2016".

## <a name="to-assign-a-deferral-template-to-an-item"></a>Til að úthluta sérþekkingarkóða á vöru
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sniðmát eignabóka**, og velja síðan viðeigandi tengil.
2. Opna spjald fyrir vöruna sem tekjur eða útgjöld er verður að deferred á reikningstímabilin þegar varan var seld eða keypt.
3. Í reitnum **Sjálfgefin Sniðmát Deferral** er deferral viðeigandi sniðmát er valið.

## <a name="to-change-a-deferral-schedule-from-a-sales-invoice"></a>Til að breyta tímaáætlun deferral úr sölureikningi
**Bent**: liðir þessi aðferð er þau sömu og þegar breytt tímaáætlun deferral fyrir útgjöld, af innkaupareikningi.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **söluferli**, og velja síðan viðeigandi tengil.
2. Stofnaður sölureikningur fyrir vöru sem er til deferral sniðmát. Nánari upplýsingar eru í [Hvernig á að reikningsfæra sölu](sales-how-invoice-sales.md).

    Takið eftir að um leið og er að færa inn vöru (eða forða eða fjárhagsreiknings) í reikningslínunni, er **Deferral Kóta** fyllist með kóti sniðmáts deferral var úthlutað.
3. Valið er **Deferral Áætlun** aðgerð.
4. Í á **Deferral Áætlun** glugganum stillingar breytt í hausnum eða gildin í línunum, til dæmis til að defer upphæðinni öðrum reikningstímabil.
5. Valið er **Deferral Áætlun** aðgerð.
6. Velja hnappinn **Í lagi**. Áætlun deferral uppfærður til reikningnum. Sniðmát tengdar deferral er óbreytt.

## <a name="to-preview-how-deferred-revenues-or-expenses-will-be-posted-to-the-general-ledger"></a>Til að forskoða hvernig deferred tekjur eða útgjöld verða bókaðar í fjárhag.
**Bent**: liðir þessi aðferð er þau sömu og þegar er forskoða hvernig kostnaðinn deferrals eru bókuð.

1. Í reitnum **Bókaður Sölureikningur** er valið **leiðrétta** aðgerð.
2. Í reitnum **Forskoðun Bókunar** , valin **Fjárhagsfærsla**, og velja síðan **Sýna Tengdar Færslur**.

Fjárhagsfærslur á að bóka reikning tilgreinda deferral, til dæmis Óinnleystra Tekna, eru þjónustukótinn stendur lýsingin sem færður er inn í reitinn **Desc Tímabils.** reit deferral sniðmátinu, til dæmis, "Útgjöld deferred fyrir Febrúar 2016" í.

## <a name="to-review-posted-deferrals-in-the-sales-deferral-summary-report"></a>Til að skoða bókaðar deferrals í skýrslunni Deferral yfirlit Yfir Sölu
**Bent**: liðir þessi aðferð er þau sömu og þegar er forskoða hvernig kostnaðinn deferrals eru bókuð.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Skýrsluval - sala**, og velja síðan viðeigandi tengil.
2. Í á **Deferral yfirlit Yfir Sölu** glugga í á **Staða sem er af** er færð inn dagsetningin þegar á að skoða deferred tekjur.
3. Veldu hnappinn **Vista**.

## <a name="see-also"></a>Sjá einnig
[Fjármál](finance-setup.md)  
[Setja upp kjarnafjárhagsferli](finance-setup-setup-finance-setup.md)  
[Hvernig á að: Vinna með almennum færslubókum](ui-work-general-journals.md)

