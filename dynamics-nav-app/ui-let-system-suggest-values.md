---
title: "Að láta Dynamics NAV leggja til gildi"
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
ms.openlocfilehash: 889d0aa5da36d7a4b7e2be1d796ac95e74aaaaf6
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="letting-dynamics-nav-suggest-values"></a>Að láta Dynamics NAV leggja til gildi
Dynamics NAV getur hjálpað við að ljúka verkefni hraðar og réttara með því að forfylla í reiti eða klára línur með gögnum sem þú myndir annars þurfa að reikna og færa inn sjálfur. Þótt slíka sjálfvirka færslan er ekki alltaf rétt má breyta eftirá.

Virkni sem færir reitiargildi fyrir þig eru yfirleitt boðnir fyrir verk þar sem þú færir inn mikið magn af færslugögnum og vilt komast hjá villum og spara tíma. Í þessu efnisatriði er hluti af slíkri virkni. Fleiri hlutar bætist við í framtíðinni fyrir uppfært Dynamics NAV.

## <a name="the-suggest-balancing-amount-check-box-in-the-general-journal-batches-window"></a>Gátreiturinn **Leggja til Upphæð Mótreiknings** í **færslubókarkeyrsla** glugganum
Þegar til dæmis þu ert að færa inn færslubókarlína fyrir margir útgjöld sem þurfa allir að vera bókaðir á sama bankareikninginn, þá hvert skipti sem þú færir inn nýja færslubókarlínu fyrir útgjöld, geturðu haft **upphæðar** reitinn á bankareikningslínunni sjálfkrafa uppfærða í þá upphæð sem kemur jafnvægi á útgjöld. Nánari upplýsingar um að vinna færslubækur sjá [Vinna Með Færslubækur](ui-work-general-journals.md).

### <a name="to-have-the-amount-field-on-balancing-general-journal-lines-filled-automatically"></a>Til að láta í **Upphæð** reitinn á færslubókarlínur fyllast út sjálfkrafa
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Færslubókum**, og velja síðan viðeigandi tengil.
2. Á línunni fyrir keyrsla færslubók er valin á **Leggja til afstemmingarUpphæð** gátreitinn.
3. Opnaðu færslubókina og farðu í að skrá og bóka færslur með því að nota lýsta virkni fyrir sjálfvirka færslu á reitagildum.       

Fyrir upplýsingar um hvernig skuli setja upp persónulega færslubókarkeyrslu, til dæmis, fyrir meðhöndlun útgjalda, sjá [vinna með færslubækur](ui-work-general-journals.md)

## <a name="the-automatically-fill-date-received-field-in-the-payment-registration-window"></a>Reiturinn **Dagsetning móttöku fyllt út sjálfkrafa** í glugganum **Skráning greiðslna** glugga
Glugginn **skráning greiðslna**Sýnir útistandandi væntanlega innkomu á línum sem tákna söluskjöl þar sem upphæð er fallinn á gjalddaga. Fyrir frekari upplýsingar um jöfnun greiðsla viðskiptavinar sjá [Hvernig skal stemma handvirkt af greiðslur  viðskiptamanns úr lista yfir ógreidda söluskjöl.](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)

Aðal aðgerðir þínar í glugganum eru að fylla í gátreitur **greiðslur framkvæmdar** og **Dagsetning Móttöku** reit. Dynamics NAV er hægt að setja upp til að sjálfvirkt færa inn vinnudagsetninguna í á **Dagsetning Móttöku** reit þegar valið er **greiðsla framkvæmd** gátreitinn.

### <a name="to-have-the-date-received-field-in-the-payment-registration-window-filled-automatically"></a>Til að láta **Sjálfkrafa fylla inn í Dagsetning Móttöku** í á **Greiðslu Skráning** glugga
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **uppsetning skráningar greiðslna** og velja síðan viðkomandi tengil.
2. Veldu gátreitinn **Dagsetning móttöku fyllt út sjálfkrafa**
3. Opnaðu Glugginn **Greiðslu Skráning** og byrja að vinna innsend greiðslur viðskiptamanns með þeim aðgerðum sem var lýst fyrir sjálfvirka innfærslu fyrir reitargildi.

## <a name="see-also"></a>Sjá einnig
[Unnið með Dynamics NAV](ui-work-product.md)  
[Fjármál](Finance.md)

