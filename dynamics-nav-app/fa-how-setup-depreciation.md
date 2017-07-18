---
title: "Hvernig á að: Uppsetning afskriftir eigna"
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
ms.openlocfilehash: 7efc50c673514498de0caa5b3a2dc4b32d4f7f5d
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-depreciation"></a>Hvernig á að: Uppsetning afskriftir eigna
 Hægt er að nota ýmsar afskriftaaðferðir vegna reikningsskila og skattframtals. Mörg stórfyrirtæki nota beinlínuafskriftir í reikningsskilum vegna þess að með þeim er yfirleitt hægt að tilgreina hærri tekjur. Vegna tekjuskatts nota þó mörg fyrirtæki hraðafskriftaaðferð. Frekari upplýsingar eru í [afskriftaaðferðir](fa-depreciation-methods.md)

 Þegar stofnaðar hafa verið viðeigandi afskriftabækur verður að tengja eina eða fleiri afskriftabækur við hverja eign. Afskriftabók sem úthlutað er á eign er vísað til sem afskriftabók eigna. Í samræmi við það heitir glugginn fyrir úthlutaðar afskriftabækur **Eignaafskriftabækur**.

## <a name="to-create-a-depreciation-book"></a>Stofna afskriftabók  
Í eignaafskriftabók er tilgreint hvernig eignir eru afskrifaðar. Ef gera á ráð fyrir margvíslegum afskriftaaðferðum má setja upp margar afskriftabækur.  
1.  Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **afskriftarbækur**, og velja síðan viðeigandi tengil.
2. Í glugganum **afskriftabókalisti** skal velja aðgerðina **Nýtt**.
3. Í glugganum **afskriftabókarspjald** þarf að fylla reitina út eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

    **Athugasemd**: hægt er Að skrá eignafærslur í **Fjárhagsbók eigna** glugga eða í **færslubók eigna** glugga, allt eftir því hvort færslur eru fyrir fjárhagsskýrslugerð eða fyrir innri stjórnun. Fylgja á næsta skref til að skilgreina hvaða tegund færslubókar er notuð sjálfgefið fyrir hinum ýmsu aðgerðum eigna.
4. Í **Samþætting** Flýtiflipanum skal velja gátreit fyrir hverja aðgerð eignar sem bóka á færslur fyrir með því að nota **Fjárhagsbók eigna** gluggann.
5. Endurtaka skal skref 2 til 4 fyrir hverja afskriftaaðferð eða bókunaraðferð sem úthluta á á eignir sem afskriftabók.

## <a name="to-assign-a-depreciation-book-to-a-fixed-asset"></a>Úthluta afskriftabók á eign.  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.
2. Valin er eignin sem setja á upp eignaafskriftabók fyrir.
3. Fyllt er út í reiti eftir því sem við á í flýtiflipanum **afskriftabók**.
4. Ef það þarf að úthluta fleiri en einni afskriftabók á eign skal velja **bæta Við Fleiri Afskriftabækur** aðgerð.
5. Einnig má velja aðgerðina **Afskriftabækur** til að tilgreina eina eða fleiri eigna-/afskriftabók.

**Athugasemd**: Þegar handvirk afskriftaaðferð er notuð verður að færa afskriftirnar handvirkt annaðhvort í eignafjárhagsfærslubók eða eignafærslubók. Aðgerðin **Reikna afskriftir** sleppir eignum sem handvirk afskriftaaðferð er notuð á. Hægt er að nota þessa aðferð á eignir sem ekki eru afskrifanlegar, til dæmis land.

## <a name="to-assign-a-depreciation-book-to-multiple-fixed-assets-with-a-batch-job"></a>Til að tengja afskriftabók við margar eignir með keyrslu
Ef úthluta á afskriftabók við margar eignir er hægt að nota keyrsluna **Stofna eignaafskriftabækur** til að láta Dynamics NAV stofna sjálfkrafa þær eignaafskriftabækur sem þarf.  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.
2. Valin er eignin fyrir hverja setja á upp afskriftabók fyrir, og velja síðan sem **Breyta** aðgerð.
3. Í glugganum **Afskriftabókarspjald** er valið **Stofna Eignaafskriftabækur** aðgerð.
4. Í glugganum **stofna eignaafskriftabækur** er fyllt inn í reitinn **afskriftarbók** .
5. Veldu **Afrita frá eignarnr.** reitinn, og veljið síðan eignanúmerið sem á að nota sem grunn að stofnun nýrra eignaafskriftabóka.

    Ef þessi reitur er fylltur út verða sömu upplýsingar í afskriftareitunum í nýju eignaafskriftabókinni og eru í samsvarandi reitum í eignaafskriftabókinni sem er afritað úr. Reiturinn er hafður auður ef búa á til nýja eignaafskriftabók með auðum afskriftareitum.  
6. Á flýtiflipanum **Eign** er hægt að setja afmörkun til að velja eignirnar sem á að stofna eignaafskriftabók fyrir.
7. Velja hnappinn **Í lagi**.

## <a name="to-set-up-depreciation-posting-types"></a>Uppsetning bókunartegundir afskrifta:  
Fyrir hverja afskriftabók þarf að stilla hvernig Dynamics NAV á að meðhöndla ýmsar bókunartegundir. Til dæmis hvort bókun eigi að vera í debet eða kredit og hvort taka eigi bókunartegund með í afskriftargrunni.  
1.  Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **afskriftarbækur**, og velja síðan viðeigandi tengil.  
2. Valin er afskriftabók sem á að setja upp og velja síðan **eignarbókunarflokkur** aðgerð.
3. Í glugganum **uppstning eignarbókunarflokks** þarf að fylla reitina út eftir þörfum.

**Athugasemd**: Ekki er hægt að skjóta inn eða eyða línum í glugganum **uppsetning eignarbókunarflokks**. Aðeins er hægt að breyta þeim línum sem fyrir eru.

Sterklega er mælt með því að uppsetningunni fyrir afskriftarbækur sem búið er að bóka í sé ekki breytt. Breytingarnar hafa ekki áhrif á færslur sem þegar er búið að bóka og sem myndu gera tölfræðigögn afskriftarbókarinnar óáreiðanleg.

## <a name="to-set-up-default-templates-and-batches-for-fixed-asset-depreciation"></a>Uppsetning Sjálfgefinna sniðmáta og -keyrslna fyrir afskriftir eigna.  
Skilgreina þarf sjálfgefna uppsetningu fyrir sniðmát og keyrslur fyrir hverja afskriftabók. Þessi sjálfgildi eru notuð til að:
- Afrita línur úr einni bók í aðra.
- Stofna bókarlínur með keyrslunni **Reikna afskriftir** eða **Endurmat eigna**.
- Afrita stofnkostnað í vátryggingabók.

1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **afskriftarbækur**, og velja síðan viðeigandi tengil.
2. Valin er afskriftabók sem á að skilgreina sjálfgefnar bækur fyrir, og veldu svo aðgerðina **uppsetning eignabókar**.
3. Ef sjálfgefin uppsetning á að vera fyrir hvern notanda skal velja reiturinn **Kenni notanda** til að velja úr glugganum **Notendur**.
4. Í öðrum reitum er valið er sniðmát færslubókar eða bókarkeyrslu sem nota verður sjálfgefið.

## <a name="see-also"></a>Sjá einnig
[Uppsetning eigna](fa-setup.md)  
[Eignastjórnun](fa-manage.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

