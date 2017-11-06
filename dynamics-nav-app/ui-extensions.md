---
title: "Uppsetning vi�b�ta til a� s�rstilla Dynamics NAV"
description: "Kynntu ��r hvernig skal b�ta virkni og s�rstilla Dynamics NAV me� �v� a� setja upp vi�b�tur."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: app, add-in, manifest, customize
ms.date: 07/07/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 109eb8d0e2a38566739878ef513ffa3bec8dcd30
ms.contentlocale: is-is
ms.lasthandoff: 10/26/2017

---
# <a name="customizing-dynamics-nav-using-extensions"></a>S�rstillir Dynamics NAV me� vi�b�tum
�� getur breytt [!INCLUDE[d365fin](includes/d365fin_md.md)] me� �v� a� setja vi�b�tur sem b�ta vi� virkni, breyta heg�un e�a gefa ��r a�gang a� n�jum net�j�nustu, til d�mis.
�egar �� fyrst r�sir [!INCLUDE[d365fin](includes/d365fin_md.md)], eru nokkrar vi�b�tur �egar settar upp fyrir �ig. Me� t�manum ver�a fleiri vi�b�tur tilt�kar fyrir �ig, og �� getur s��an vali� hvort �� viljir nota vi�b�tina e�a ekki.

Til d�mis veitir Microsoft vi�b�t sem veitir sam��ttingu vi� PayPal Payments Standard. �essi vi�b�t er uppsett sj�lfgefi�
En ef �nnur vi�b�t er ger� sem veitir sam��ttingu vi� a�ra grei�slu�j�nusta, getur�u sett inn n�ja vi�b�t og s��an vali� hva�a af �essum tveimur �j�nustum �� notar.  

�� stj�rnar vi�b�tum � **vi�b�tastj�rnun** glugganum. H�gt er a� opna �ennan glugga �r heimasv��inu. Einnig er h�gt a� velja **Leit a� s��u e�a sk�rslu** t�kni� ![Leit a� s��u e�a sk�rslu](media/ui-search/search_small.png "Leit a� s��u e�a sk�rslu") efst � h�gra horninu, sl� inn **Vi�b�t** og velja svo tengdan tengil.  

> [!NOTE]  
>   Ef �� telur a� �� �ttir a� hafa a�gang a� vi�b�t en finnur ekki virknina sem � henni felst, skaltu athuga gluggann **Vi�b�tarstj�rnun** - ef vi�b�tin er ekki skr�� �ar getur �� sett hana upp eins og l�st er � eftirfarandi kafla.  

## <a name="installing-an-extension"></a>Uppsetning vi�b�tar
H�r getur �� fengi� n�jar vi�b�tur fr� marka�storginu � [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1). H�r getur �� s�� allar tilt�kar vi�b�tur fyrir [!INCLUDE[d365fin](includes/d365fin_md.md)], og �� getur fengi� forrit, vi�b�tur og innihaldsefni fyrir a�rar Microsoft v�rur. Stilltu vi�eigandi s�ur, sko�a�u uppl�singar um hverja vi�b�t og f��u vi�b�t fyrir �inn [!INCLUDE[d365fin](includes/d365fin_md.md)].  
> [!NOTE]  
>   Skr��u �ig inn � [AppSource.microsoft.com](https://appsource.microsoft.com/) me� �v� a� nota netfangi� sem �� notar fyrir [!INCLUDE[d365fin](includes/d365fin_md.md)]. Nota sama t�lvup�streikning fyrir a�ra �j�nustu og v�rur fyrir er hn�kralausa upplifun.  

Einnig er h�gt a� f� a� marka�storgi� �r [!INCLUDE[d365fin](includes/d365fin_md.md)]. � **framlengingarstj�rnun** getur�u s�� eftirnafnin sem eru � uppsettri r�� og �� getur opna� **Framlengingarmarka�** s��u sem s�nir [!INCLUDE[d365fin](includes/d365fin_md.md)] vi�b�tur sem eru � bo�i � AppSource. Ef vali� er *Fleiri �pp* tengilinn, er fari� me� �ig � [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1).  

Ef �� velur vi�b�t getur�u lesi� um hva� vi�b�tin gerir, og �� getur fengi� a�gang a� hj�lp fyrir vi�b�tinni til a� l�ra meira. �egar vali� er a� f� vi�b�t, ver�ur�u a� sam�ykkja skilm�la um notkun. Ef �� f�r� framlengingu fr� AppSource vefs��u ver�ur �� skr�� (ur) inn � [!INCLUDE[d365fin](includes/d365fin_md.md)] til a� lj�ka uppsetningunni.  

�egar �� setur upp vi�b�t g�tir�u �urft a� setja �a� upp, svo sem a� tilgreina reikning til notkunar me� **PayPal-grei�slusta�all fyrir [!INCLUDE[d365fin](includes/d365fin_md.md)]** framlengingu.
A�rar vi�b�tur b�ta einfaldlega reitum vi� fyrirliggjandi s��u, e�a �eir b�ta vi� n�jum s��um, til d�mis.   

Ef �� fjarl�gir vi�b�t og skiptir um sko�un getur�u sett hana inn aftur. �egar �� fjarl�gir vi�b�t sem �� hefur veri� a� nota, eru g�gnin geymd svo a� ef �� setur �au upp aftur, eru g�gnin ��nn enn tilt�k.  

Sumar vi�b�tur eru veittar af Microsoft, og a�rar vi�b�tur eru veittar af [��rum fyrirt�kjum.](ui-extensions-other.md) Allar vi�b�tur eru pr�fa�ar ��ur en ��r eru ger�ar tilt�kar til �in, en vi� m�lum me� a� �� farir � gegnum tenglana sem eru veittir me� hverri vi�b�t til a� l�ra meira um vi�b�tina ��ur en �� setur hana upp.  

Microsoft veitir eftirfarandi vi�b�tur:  

* [Dynamics GP Gagnaf�rsla](ui-extensions-dynamicsgp-data-migration.md)  
* [PayPal Payments Standard](ui-extensions-paypal-payments-standard.md)  
* [QuickBooks gagnaflutningur](ui-extensions-quickbooks-data-migration.md)  
* [Sp� um s�lu og birg�ir](ui-extensions-sales-forecast.md)  
* [Ceridian Payroll](ui-extensions-ceridian-payroll.md)  
* [Quickbooks-vi�b�tin fyrir innflutning � launaskr�](ui-extensions-quickbooks-payroll.md)  
* [WorldPay-grei�slusta�all](ui-extensions-worldpay-payments-standard.md)
* [GetAddress.io UK Postcodes](ui-extensions-getaddressio.md)
* [QuickBooks gagnaflutningur � netinu](ui-extensions-quickbooks-online-data-migration.md)
* [Endursko�andag�tt](ui-extensions-accountant-portal.md)  
* [Myndgreinandi](ui-extensions-image-analyzer.md)

> [!NOTE]  
>  N�jar vi�b�tur eru ekki tilt�kar � AppSource strax eftir a� vi� tilkynnum um uppf�rslu. �� getur fylgst me� vi�b�tum � [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1).

## <a name="see-also"></a>Sj� einnig
[Hvernig � a�: Virkja grei�slur vi�skiptamanna gegnum PayPal](sales-how-enable-payment-service-extensions.md)  
[Yfirf�ra vi�skiptag�gn �r ��rum fj�rhagskerfum](upload-data.md)    
[[!INCLUDE[d365fin](includes/d365fin_md.md)] Vi�b�tur fr� ��rum veitum](ui-extensions-other.md)  
[Velkomin(n) � [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  

##


