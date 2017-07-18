---
title: "Hvernig á að: Viðhalda Eignir"
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
ms.openlocfilehash: 58077a38433a73b981a6f3d05ce7ed106acf32f4
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-maintain-fixed-assets"></a>Hvernig á að: Viðhalda Eignir
Viðhaldskostnaður er reglubundinn kostnaður sem varið er til þess að viðhalda virði eigna. Ólíkt viðbótarfjárfestingum eykur hann ekki verðgildi.

Hægt er að skrá og viðhalda dagréttri skrá um viðhald og þjónustu við eignir og hafa þannig fullkomnar viðhaldsskrár um eignir aðgengilegar. Í hvert sinn sem eign fær þjónustu skráir notandi allar viðeigandi upplýsingar eins og dagsetningu, númer lánardrottins og símanúmer þjónustuaðila. Skráning viðhalds er færð vegna allra eigna á viðeigandi eignaspjaldi.

Endurmat er notað til að laga virði að almennum verðbreytingum. Hægt er að nota keyrsluna **Endurmat eigna** til að endurreikna viðhaldskostnað.

## <a name="to-record-maintenance-work-on-a-fixed-asset"></a>Skrá viðhaldsvinna á eign  
Í hvert sinn sem viðhaldi hefur verið framkvæmt, eins og þjónustuheimsókn, er hægt að skrá það á viðeigandi eign í glugganum **Skráning viðhalds**.  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.  
2. Valin er eignin sem á að skrá viðhald fyrir og veldu síðan aðgerðina **skráning viðhalds**.
3. Í glugganum **skráning viðhalds** þarf að fylla reitina út eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.  

## <a name="to-post-maintenance-costs-from-a-fixed-asset-gl-journal"></a>Bóka viðhaldskostnað úr fjárhagsbók eigna
1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **afskriftarbókalisti**, og velja síðan viðeigandi tengil.  
2. Veljið afskriftabókina sem er tengd eigninni og veljið síðan aðgerðina **breyta**.
3. Í glugganum **Afskriftabókarspjald** skal ganga úr skugga um að gátreiturinn **Viðhald** er ekki valinn. Þetta tryggir að viðhaldskostnaðar eru ekki bókaðar í fjárhag.
4. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.  
5. Stofnaður er upprunaleg Færslubókarlína og reitirnir fylltir út eftir þörfum.
6. Í reitnum **Eignabókunartegund** er valinn **viðhald**.
7. Valið er **Setja inn mótreikn. eigna** aðgerð. Seinni færslubókarlína er búin til fyrir mótreiknings sem er sett upp fyrir bókun viðhalds.

    **Athugasemd**: skref 7 virkar eingöngu ef búið er að setja upp eftirfarandi: Í **Eignabókunarflokksspjald** glugganum fyrir bókunarflokkur eigna, inniheldur reiturinn **viðhaldsreikningur** debetreikning fjárhags og reikningurinn **Mótreikning viðhalds** inniheldur fjárhagsreikninginn sem á að bóka mótfærslur í fyrir uppfærslu. Nánari upplýsingar eru í "setja upp bókunarflokka eigna" hlutanum í [Hvernig: Setja Upp almennar upplýsingar um eignir](fa-how-setup-general.md).
8. Valið er **bóka** aðgerð.

## <a name="to-follow-up-on-fixed-assets-service-visits"></a>Til að fylgja eftir þjónustuheimsóknum eigna:
Þú getur Prenta skýrsluna **Viðhald - Næsta þjónusta** til að skoða fyrir hvaða eignir er búið að áætla þjónustuheimsóknir. Einnig er hægt að nota þessa skýrslu þegar reiturinn **Næsta þjónustudags.** á eignspjöldunum er uppfærður.  

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**,slá inn **næsta viðhaldsþjónusta**, og velja síðan viðeigandi tengil.  
2. Reitirnir **Upphafsdagsetning** og **Lokadagsetning** eru fylltir út.  
3. Veljið hnappinn **Prenta** eða **Forskoðun**.

## <a name="to-monitor-maintenance-costs"></a>Fylgst með viðhaldskostnaði  
Hægt er að skoða viðhaldskostnaðinn þegar skoðaðar eru upplýsingar um eign.  

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.
2. Valin er eignin sem á að skoða viðhaldskostnað fyrir og veldu síðan aðgerðina **afskriftabækur**.
3. Í reitnum **Eignaafskriftabækur** er valin viðeigandi eignaafskriftabók og síðan valið **upplýsingar** aðgerð.
4. Í glugganum **Eignaupplýsingar** er valið **viðhald** .

Glugginn **viðhaldsbókarfærslur** opnast og sýnir færslur sem mynda upphæðina í reitnum **viðhald**.

## <a name="to-view-or-print-maintenance-costs-for-multiple-fixed-assets"></a>Skoða eða prenta viðhaldskostnað fyrir margar eignir  
Í skýrslunni **Viðhald - Greining** er hægt er að velja að sjá viðhalds byggt á einn, tvo eða þrjá viðhaldskóta á tilgreindri dagsetningu eða tímabili. Einnig er hægt að sjá samtölu allra valinna eigna eða samtölu hverrar eignar fyrir sig.

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **viðhaldsgreining**, og velja síðan viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum.
3. Veljið hnappinn **Prenta** eða **Forskoðun**.

## <a name="to-view-maintenance-ledger-entries"></a>Skoðun viðhaldsfærslna:
Hægt er einnig að sjá viðhaldskostnaðinn með því að skoða viðhaldsbókarfærslurnar.  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.
2. Valin er eignin sem á að skoða fjárhagsfærslur fyrir og veldu síðan aðgerðina **afskriftabækur**.
3. Í reitnum **Eignaafskriftabækur** er valin viðeigandi eignaafskriftabók og síðan valið **viðhaldsbókarfærslur** aðgerð.

## <a name="to-view-or-print-maintenance-ledger-entries-for-multiple-fixed-assets"></a>Skoða eða prenta viðhaldsbókarfærslur fyrir margar eignir  
Í **Viðhald - Sundurliðun** skýrslu er hægt að skoða eða prenta viðhaldsbókarfærslur fyrir eina eða margar eignir.  

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **viðhaldsupplýsingar**, og velja síðan viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum.
3. Veljið hnappinn **Prenta** eða **Forskoðun**.

## <a name="see-also"></a>Sjá einnig
[Eignastjórnun](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

