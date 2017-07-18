---
title: "Hvernig á að: Flytja bankainnistæður"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f34bef80c64cbad0a0b20d4d021cefbdc5a1cb64
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-transfer-bank-funds"></a>Hvernig á að: Flytja bankainnistæður
Stundum þarf að bóka millifærslu á upphæðum af einum bankareikningi yfir á annan. Til að gera þetta verður að bóka á færslu í færslubók. Verkið er misjafnt eftir því hvort bankareikningarnir nota sama gjaldmiðil eða mismunandi gjaldmiðla.

## <a name="to-post-a-transfer-between-bank-accounts-with-the-same-currency-code"></a>Millifærslur af einum bankareikningi á annan með sama gjaldmiðilskóða
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Færslubók**, og velja síðan viðeigandi tengil.
2. **Bókunardagsetning** og **Númer fylgiskjals** eru fylltir út í færslubókarlínu. Reitir
3. Í reitnum **Tegund reiknings** er valinn **Bankareikningur**.
4. Í svæðinu **Bankareikningsnúmer**,  veljið bankann sem flytja á bankainnistæðuna frá.
5. Heildarupphæðin sem á að úthluta í reitinn  **Upphæð** er færð inn.
6. Í reitnum **Tegund mótreiknings** er **Bankareikningur** valinn.
7. Í svæðinu **Númer mótreiknings**,  veljið bankareikninginn sem flytja á bankainnistæðuna til.
8. Bóka skal færslubókina.

## <a name="to-post-a-transfer-between-bank-accounts-with-different-currency-codes"></a>Færslur milli bankareikninga bókaðar með gjaldmiðilskótum
Til að færa fjármuni milli bankareikninga sem nota mismunandi gjaldmiðla, verður að bóka tvær færslubókarlínur.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Færslubók**, og velja síðan viðeigandi tengil.
2. Búið til tvær færslubókarlínur og fyllið út reitina **Bókunardagsetning** og **Númer fylgiskjals**. Reitir
3. Í fyrstu færslubókarlínunni skal færa inn **Bankareikningur** í reitnum **Tegund reiknings**.
4. Í svæðinu **Bankareikningsnúmer**,  veljið bankareikninginn sem flytja á bankainnistæðuna frá.
5. Í reitnum **Upphæð** er rituð upphæðin sem er í gjaldmiðli bankareiknings. Færið inn kreditáætlunarupphæð með neikvæðu formerki. Færið inn debetáætlunarupphæð með neikvæðu formerki.
6. Í reitnum **Tegund mótreiknings** er **Bankareikningur** valinn.
7. Í svæðinu **Númer mótreiknings**,  veljið bankareikninginn sem flytja á bankainnistæðuna til.
8. Í seinni færslubókarlínunni skal færa inn **Bankareikningur** í reitnum **Tegund reiknings**.
9. Í svæðinu **Bankareikningsnúmer**,  veljið bankareikninginn sem flytja á bankainnistæðuna til.
10. Í reitnum **Upphæð** er rituð upphæðin sem er í gjaldmiðli bankareiknings. Færið inn kreditáætlunarupphæð með neikvæðu formerki. Færið inn debetáætlunarupphæð með neikvæðu formerki.
11. Í reitnum **Tegund mótreiknings** er **Bankareikningur** valinn.  
12. Í svæðinu **Númer mótreiknings**,  veljið bankareikninginn sem flytja á bankainnistæðuna frá.

    **Athugið**: Ef gengið sem notað er í færslunni er annað en gengið í glugganum **Gengi gjaldmiðils** þarf að bæta inn þriðju línunni fyrir gengishagnað eða -tap. Færið inn **Fjárhagsreikning** í reitnum **Tegund reiknings**. Færið inn fjárhagsreikningsnúmer fyrir gengishagnað eða -tap í reitinn **Reikningur nr.**. . Færa inn gengishagnað eða -tap í reitinn **Upphæð** með eða án neikvæðs formerkis, eftir því hvort um er að ræða kreditupphæð eða debetupphæð.
13. Bóka skal færslubókina.

## <a name="see-also"></a>Sjá einnig  
[Stjórna bankareikningum](bank-manage-bank-accounts.md)  
[Uppsetning bankaþjónustu](bank-setup-banking.md)  
[Vinna í færslubókum](ui-work-general-journals.md)

