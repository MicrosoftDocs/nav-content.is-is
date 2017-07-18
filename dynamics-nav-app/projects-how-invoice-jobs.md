---
title: "Hvernig á að: Reikningsfæra verk"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c0dcce83dfba30af38f33a6bf814b15862d5fc19
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-invoice-jobs"></a>Hvernig á að: Reikningsfæra verk
Meðan á verkefninu stendur getur kostnaður vegna forðanotkunar, efnis og verktengdra innkaupa safnast upp. Þessar færslur eru bókaðar í verkbókina á vinnslutíma verksins. Mikilvægt er að allur kostnaður sé skráður í verkbókina áður en viðskiptavininum er sendur reikningur.

Hægt er að reikningsfæra allt verkið í glugganum **Verkhlutalínur** eða aðeins reikningsfæra ákveðnar reikningshæfar línur í glugganum **Áætlunarlínur**. Hægt er að reikningsfæra þegar verkinu er lokið eða með vissu millibili á meðan á vinnslu verksins stendur, byggt á reikningsáætlun.

**Til athugunar**: Ef valið er **Reikningshæft** í reitnum **Verklínutegund** í söluskjölum fyrir verktengd innkaup verða stofnaðar verkáætlunarlínur sem eru tilbúnar til að vera reikningsfærðar á viðskiptamann. Nánari upplýsingar eru í [Hvernig á að: Vinna með verkbirgðir](projects-how-manage-project-supplies.md).

## <a name="to-create-and-post-a-job-sales-invoice"></a>Til að stofna og bóka sölureikning verks:  
Hægt er að stofna reikning fyrir verk eða einn eða fleiri verkhluta fyrir viðskiptavin þegar verkinu sem á að reikningsfæra er lokið eða komið er að dagsetningu reikningafærslunnar, sem byggist á reikningsfærsluáætlun.

Í glugganum **Verk** er hægt að reikningsfæra til viðskiptamanns með því að velja verkið og velja svo aðgerðina **Stofna sölureikning verks**. Eftirfarandi ferli sýnir hvernig á að nota keyrslu til að reikningsfæra fleiri verk.  

1. Uppi í hægra horninu velurðu táknið **Leita að síðu eða skýrslu**, slærð inn **Stofna sölureikning verks** og velur svo viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Ef takmarka á verk sem keyrslan á að vinna skal tilgreina afmarkanir.
3. Velja hnappinn **Í lagi** til að stofna reikningana.  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a>Að búa til fleiri sölureikninga úr verkáætlunarlínum  
Hægt er að stofna reikning úr verkáætlunarlínum, og gefa upp á þeim tíma magnið af vörunni, forða eða fjárhagsreikning sem á að reikningsfæra.

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk** og velja svo viðeigandi tengil.
2. Opnið viðeigandi verk.
3. Valinn er verkhluti þar sem reiturinn **Verkhlutagerð** inniheldur **Bókuð** og svo er aðgerðin **Verkhlutalínur** valin.  
4. Í verkáætlunarlínu í reitnum **Magn Til að reikningsfæra** er slegið inn magn vörunnar, forðann, fjárhagsreikningsgerð sem á að reikningsfæra.  
5. Veljið aðgerðina **Stofna sölureikning**.
6. Í glugganum **Stofna sölureikning verks** færirðu inn bókunardagsetninguna og hvort eigi að stofna nýjan reikning eða skeyta þessum reikningi við fyrirliggjandi reikning.
7. Velja hnappinn **Í lagi**.

    Í reitnum **Magn flutt á reikning** í verkáætlunarlínunni er hægt að sjá magnið.

8. Í glugganum **Verkáætlunarlínur** skal velja aðgerðina **Sölureikningar/kreditreikningar**.

    Glugginn **Sölureikningur** opnast og sýnir það magn sem hefur verið flutt á reikninginn.  
9. Gerið frekari breytingar og veljið svo aðgerðina **Bóka**.

**Til athugunar**: Ofangreint ferli er svipað þegar verið er að stofna, yfirfara og bóka verktengdan sölukreditreikning.

## <a name="to-calculate-and-post-job-completion-entries"></a>Að reikna út og bóka verklokafærslur  
Þegar öllum aðgerðum verks hefur verið lokið, þar með talin bókun notkunar og reikningsfærsla, þarf að uppfæra verkið svo að **Staða** þess sé **Lokið**. Síðan þarf að bakfæra VÍV sem hefur verið bókað í fjárhag.

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk** og velja svo viðeigandi tengil.  
2. Veljið opið verk og veljið svo aðgerðina **Breyta**.
3. Í reitnum **Staða** skal velja **Lokið**.
4. Fylgið aðstoðarskrefunum til að reikna og bóka VÍV. Einnig er hægt að fylgja skrefum 5 og 6 til að gera það handvirkt.  
5. Veljið aðgerðina **Reikna VÍV**.
6. Í glugganum **Verk - Reikna VÍV** þarf að fylla reitina út eins og þörf krefur.  

     VÍV færslurnar sem voru stofnaðar með keyrslunni munu nú hafa gátmerki í reitnum **Verki lokið** til að sýna að þær séu lokafærslur.  

7. Velja skal aðgerðina **Verk - Bóka VÍV í fjárhag**.
8. Í glugganum **Verk - Bóka VÍV í fjárhag** skal fylla reitina út eins og þörf krefur.  

     VÍV-fjárlagsfærslur verks sem voru stofnaðar með keyrslunni munu nú hafa gátmerki í reitnum **Verki lokið** til að sýna að þær eru lokafærslur.

## <a name="see-also"></a>Sjá einnig
[Unnið með verkefni](projects-manage-projects.md)  
[Fjármál](finance-setup.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)         
[Stjórna sölu](sales-manage-sales.md)      
[Unnið með Dynamics NAV](ui-work-product.md)  

