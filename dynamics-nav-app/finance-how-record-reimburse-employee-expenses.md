---
title: "Skrá og endurgreiða útgjöld starfsmanna í viðskiptaerindum"
description: "Bóka útgjöld starfsmanna með færslubók á reikning starfsmanns og bóka síðar greiðslu á bankareikning starfsmanns til að endurgreiða útgjöld í viðskiptaerindum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reimbursement
ms.date: 06/28/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 344d104607da8cefa6096d4ae873ebc652de0dd4
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-record-and-reimburse-employees-expenses"></a>Hvernig á að: Skrá og endurgreiða starfsmannaútgjöld.
[!INCLUDE[d365fin](includes/d365fin_md.md)] styður færslur fyrir starfsmann á svipaðan hátt og fyrir lánardrottna. Til eru bókunarflokkar starfsmanna, sem eiga að tryggja að fjárhagsfærslur starfsmanna séu bókaðar á viðeigandi reikninga í færslubókinni.

> [!NOTE]  
> Starfsmannafærslur er eingöngu hægt að bóka í staðbundna gjaldmiðlinum. Endurgreiðslur til starfsmanna styðja ekki aflsætti og greiðsluvikmörk.

Ef starfsmenn eyða sínum eigin peningum í viðskiptaerindum, er hægt að bóka útgjöldin á reikning starfsmanns. Þá geturðu endurgreitt starfsmanninum með því að framkvæma greiðslu inn á bankareikning starfsmannsins, á svipaðan hátt og þú borgar lánardrottnum.

## <a name="to-record-an-employees-expense"></a>Skrá útgjöld starfsmanns
Útgjöld starfsmanna eru bókuð í **Færslubók** glugga
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **færslubók** og velja svo viðeigandi tengil.
2. Viðeigandi færslubók keyrsla er opnaður. Frekari upplýsingar, sjá [Vinna með almennar færslubækur](ui-work-general-journals.md).
3. Fyllið í reitina eftir þörfum í nýrri færslubókarlínu. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]    
4. Endurtakið skref 3 fyrir öll útgjöld sem starfsmaður hefur stofnað til.

    > [!TIP]  
    > Ef þú vilt færa inn fleiri kostnaðarlínur fyrir ofan eina mótreikningslínu fyrir bankareikning starfsmanns, skaltu velja gátreitinn **Leggja til afstemmingarupphæð** á línunni fyrir þína keyrslu í glugganum **færslubókakeyrslur**. Þá verður reiturinn **Upphæð** á mótreikningslínunni sjálfkrafa fylltur út með gildinu sem er nauðsynlegt til að jafna útgjöldin.
5. Veljið **Bóka** aðgerðina til að skrá útgjöldin á reikning starfsmanns.

## <a name="to-reimburse-an-employee"></a>Endurgreiða starfsmanni
Þú endurgreiðir starfsmanni með því að bóka greiðslur á bankareikning hans í glugganum **greiðslubók**.
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **greiðslubækur** og velja svo viðeigandi tengil.
2. Viðeigandi greiðslubók keyrsla er opnaður. Frekari upplýsingar, sjá [Vinna með almennar færslubækur](ui-work-general-journals.md).
3. Fyllið inn í reitina eftir þörfum. Frekari upplýsingar eru í [Greiðslur framkvæmdar](payables-make-payments.md).
4. Að öðrum kosti skal velja **Leggja til starfsmannagreiðslu** aðgerðina til að setja sjálfvirkt inn færslubókarlínu fyrir endurgreiðslu í bið til starfsmanns.
5. Valið er **bóka** aðgerð til að skrá endurgreiðsluna.  

## <a name="to-reconcile-reimbursements-with-employee-ledger-entries"></a>Afstemma endurgreiðslur við fjárhagsfærslur starfsmanns
Þú jafnar greiðslu til starfsmanns við tengdar og opnar fjárhagsfærslur starfsmanns á sama hátt og greiðslur til lánardrottins, til dæmis í glugganum **Greiðsluafstemmingarbók**, byggt á tengdum bankayfirlitsfærslum. Nánari upplýsingar er að finna í [Jafna greiðslur sjálfkrafa og afstemma bankareikninga](receivables-apply-payments-auto-reconcile-bank-accounts.md). Einnig er hægt að jafna handvirkt í glugganum **Fjárhagsfærslur starfsmanna**. Frekari upplýsingar, sjá [Hvernig á að:: afstemma greiðsla lánardrottinss handvirkt](payables-how-apply-purchase-transactions-manually.md).  

## <a name="see-also"></a>Sjá einnig
[Hvernig skal: Bóka færslu beint í Fjárhag](finance-how-post-transactions-directly.md)  
[Vinna í færslubókum](ui-work-general-journals.md)  
[Hvernig skal: Bakfæra bókanir](finance-how-reverse-journal-posting.md).  
[Fjármál](finance.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

