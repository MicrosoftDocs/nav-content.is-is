---
title: "Hvernig á að: Setja upp vinnuskýrslur"
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
ms.openlocfilehash: 6cbacce79ce185d6ed00ea8383259d1b28f9e11b
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-time-sheets"></a>Hvernig á að setja upp tímablöð
Vinnuskýrslur í Dynamics NAV meðhöndla tímaskráningu í vikulegum sjö daga bilum. Þær eru notaðar til að fylgjast með þeim tíma sem varið er í verk og hægt er að nota þær fyrir einfalda tímaskráningu forða. Áður en hægt er að nota vinnuskýrslur, verður að skilgreina hvernig þær eiga að vera settar upp og grunnstilltar.

Þegar búið er að setja upp hvernig fyrirtækið á að nota vinnuskýrslur er hægt að tilgreina hvort og hvernig tímaskýrslur eru samþykktar. Allt eftir þörfum fyrirtækisins er hægt að tilgreina:

- Einn eða fleiri notendur sem vinnuskýrslustjóra og sem samþykkja allar vinnuskýrslur.
- Vinnuskýrslusamþykkjandi fyrir hvern forða.

Þegar búið er að setja upp vinnuskýrslur er hægt að búa til vinnuskýrslur fyrir forða, úthluta þeim á verkáætlunarlínur og bóka vinnuskýrslulínur. Frekari upplýsingar eru í [Hvernig á að: Nota vinnuskýrslur](projects-how-use-time-sheets.md).

## <a name="to-set-up-general-information-for-time-sheets"></a>Til að setja upp almennar upplýsingar um vinnuskýrslur  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Forðagrunnur** og velja síðan viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Í reitnum **Vinnuskýrslur eftir samþykkt verks** skal velja einn af eftirfarandi valkostum.

|Valkostur |Lýsing|
|---|---|
|**Aldrei**|Notandinn í reitnum **Notandakenni samþykktaraðila vinnuskýrslu** á forðaspjaldinu samþykkir vinnuskýrsluna.|
|**Alltaf**|Notandinn í reitnum **Ábyrgðaraðili** á verkspjaldinu samþykkir vinnuskýrsluna.|
|**Aðeins vélar**´|Ef vinnuskýrsla vélar er tengd við verk er það notandinn í reitnum **Ábyrgðaraðili** á verkspjaldinu sem samþykkir vinnuskýrsluna. Ef vinnuskýrsla vélar er tengd við forða er það notandinn í reitnum **Notandakenni samþykktaraðila vinnuskýrslu** á forðaspjaldinu sem samþykkir vinnuskýrsluna.

## <a name="to-assign-a-time-sheet-administrator"></a>Til að tilnefna vinnuskýrslustjóra  

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Notandauppsetning** og velja svo viðeigandi tengil.  
2.  Bæta við nýjum notanda ef notandalistinn inniheldur ekki einstaklinginn sem notandinn vill að sé vinnuskýrslustjórnandi. Hafðu samband við kerfisstjóra til að fá frekari upplýsingar.  
3. Velja skal notanda sem á að vera vinnuskýrslustjóri og svo skal velja gátreitinn**Stjórnandi vinnuskýrslu** .  

**Ábending**: Mælt er með því að aðeins einn notandi sé tilgreindur sem vinnuskýrslustjóri fyrir fyrirtæki. Í eftirfarandi ferli eru eigandi og samþykkjandi vinnuskýrslu settir upp þar sem samþykkjandi er tilgreindur fyrir hvern forða.  

## <a name="to-assign-a-time-sheets-owner-and-approver"></a>Til að tilgreina eiganda og samþykkjanda vinnuskýrslu  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Forðar** og velja síðan viðeigandi tengil.
2. Veljið forðann sem á að geta notað vinnuskýrslur og veljið svo gátreitinn **Nota vinnuskýrslu**.  
3. Í reitinn **Notandakenni eiganda vinnuskýrslu** skal slá inn notandakenni eiganda vinnuskýrslunnar. Eigandinn getur fært inn tímanotkun á vinnuskýrslu og sent hana til samþykktar. Þegar forði er einstaklingur er einstaklingurinn yfirleitt einnig eigandi.  
4. Í reitinn **Notandakenni samþykkjanda vinnuskýrslu** skal slá inn notandakenni samþykkjanda vinnuskýrslunnar. Samþykkjandi getur samþykkt, hafnað eða enduropnað vinnuskýrslu.  

**Til athugunar**: Ekki er hægt að breyta notandakenni samþykkjanda vinnuskýrslu ef til staðar eru vinnuskýrslur sem ekki hafa verið unnar og eru með stöðuna **Sent** eða **Opið**.

## <a name="see-also"></a>Sjá einnig
[Setja upp verkefnastjórnun](projects-setup-projects.md)  
[Unnið með verkefni](projects-manage-projects.md)  
[Fjármál](finance-setup.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)         
[Stjórna sölu](sales-manage-sales.md)      
[Unnið með Dynamics NAV](ui-work-product.md)  

