---
title: "Hönnunarupplýsingar- Codeunit 408 víddarstjórnun"
description: "Kóðaeining 408 Víddastjórnun er aðgerðasafn sem sér um algeng verkefni sem tengjast víddum, m.a. afritun úr einni töflu í aðra eða úr einu skjali í annað."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: c1b3c745597f96165aec92a08bba50ecb6727a84
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="design-details-codeunit-408-dimension-management"></a><span data-ttu-id="5304a-103">Hönnunarupplýsingar: Codeunit 408 víddarstjórnun</span><span class="sxs-lookup"><span data-stu-id="5304a-103">Design Details: Codeunit 408 Dimension Management</span></span>
<span data-ttu-id="5304a-104">Kóðaeining 408 Víddastjórnun er aðgerðasafn sem sér um algeng verkefni sem tengjast víddum, m.a. afritun úr einni töflu í aðra eða úr einu skjali í annað.</span><span class="sxs-lookup"><span data-stu-id="5304a-104">Codeunit 408 Dimension Management is a function library that handles common tasks that are related to dimensions, such as copying from one table to another or from one document to another.</span></span> <span data-ttu-id="5304a-105">Þetta efnisatriði er listi yfir aðgerðir sem er breytt í Microsoft Dynamics NAV 2013 R2 og skilgreinir hvað þarf að gera við aðgerðirnar.</span><span class="sxs-lookup"><span data-stu-id="5304a-105">This topic lists the functions that are modified in Microsoft Dynamics NAV 2013 R2 and specifies what has to be done to the functions.</span></span> <span data-ttu-id="5304a-106">Mörgum aðgerðum er eytt vegna þess að ekki er þörf á að afrita á milli víddatafla.</span><span class="sxs-lookup"><span data-stu-id="5304a-106">Many functions are deleted because there is no need for copying between dimension tables.</span></span>  

## <a name="modified-functions"></a><span data-ttu-id="5304a-107">Breyttar aðgerðir</span><span class="sxs-lookup"><span data-stu-id="5304a-107">Modified Functions</span></span>  

|<span data-ttu-id="5304a-108">Heiti aðgerðar</span><span class="sxs-lookup"><span data-stu-id="5304a-108">Function Name</span></span>|<span data-ttu-id="5304a-109">Lýsing á breytingum</span><span class="sxs-lookup"><span data-stu-id="5304a-109">Modification Description</span></span>|  
|-------------------|------------------------------|  
|<span data-ttu-id="5304a-110">CheckDimSetIDComb</span><span class="sxs-lookup"><span data-stu-id="5304a-110">CheckDimSetIDComb</span></span>|<span data-ttu-id="5304a-111">Ný aðgerð sem kemur í stað annarra skoðunaraðgerða og notar víddasamstæðukenni sem frumbreytu í stað víddatöflu.</span><span class="sxs-lookup"><span data-stu-id="5304a-111">New function that substitutes the other check functions and takes a Dimension Set ID as an argument instead of a dimension table.</span></span>|  
|<span data-ttu-id="5304a-112">CheckDimSetIDComb</span><span class="sxs-lookup"><span data-stu-id="5304a-112">CheckDimSetIDComb</span></span><br /><br /> <span data-ttu-id="5304a-113">CheckDocDimComb</span><span class="sxs-lookup"><span data-stu-id="5304a-113">CheckDocDimComb</span></span><br /><br /> <span data-ttu-id="5304a-114">CheckServContractDimComb</span><span class="sxs-lookup"><span data-stu-id="5304a-114">CheckServContractDimComb</span></span><br /><br /> <span data-ttu-id="5304a-115">CheckDimBuffer</span><span class="sxs-lookup"><span data-stu-id="5304a-115">CheckDimBuffer</span></span><br /><br /> <span data-ttu-id="5304a-116">CheckDimComb</span><span class="sxs-lookup"><span data-stu-id="5304a-116">CheckDimComb</span></span><br /><br /> <span data-ttu-id="5304a-117">CheckDimValueComb</span><span class="sxs-lookup"><span data-stu-id="5304a-117">CheckDimValueComb</span></span>|<span data-ttu-id="5304a-118">Eyða</span><span class="sxs-lookup"><span data-stu-id="5304a-118">Delete.</span></span> <span data-ttu-id="5304a-119">Allri notkun ætti að breyta í CheckDimSetIDComb.</span><span class="sxs-lookup"><span data-stu-id="5304a-119">All usage should be changed to CheckDimSetIDComb.</span></span>|  
|<span data-ttu-id="5304a-120">GetDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-120">GetDefaultDim</span></span>|<span data-ttu-id="5304a-121">Breytið til að skila víddasamstæðukenni í heiltölu í stað færslusafns.</span><span class="sxs-lookup"><span data-stu-id="5304a-121">Modify to return an integer Dimension Set ID instead of a set of records.</span></span>|  
|<span data-ttu-id="5304a-122">CopyDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-122">CopyJnlLineDimToICJnlDim</span></span><br /><br /> <span data-ttu-id="5304a-123">CopyDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-123">CopyICJnlDimToJnlLineDim</span></span><br /><br /> <span data-ttu-id="5304a-124">CopyDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-124">CopyDocDimtoICDocDim</span></span><br /><br /> <span data-ttu-id="5304a-125">CopyDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-125">CopyICDocDimtoICDocDim</span></span>|<span data-ttu-id="5304a-126">Bryeta til að vinna með DimSetID -> ICJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-126">Modify to work with DimSetID -> ICJnlLineDim</span></span>|  

## <a name="deleted-functions"></a><span data-ttu-id="5304a-127">Eyddar aðgerðir</span><span class="sxs-lookup"><span data-stu-id="5304a-127">Deleted Functions</span></span>  
 <span data-ttu-id="5304a-128">Aðgerðum sem er eytt út úr kóðaeiningu 408 í tengslum við eiginleikann víddasamstæðufærslur eru skráðar hér fyrir neðan.</span><span class="sxs-lookup"><span data-stu-id="5304a-128">Functions that are deleted from codeunit 408 in connection with the Dimension Set Entries feature are listed below.</span></span>  

> [!CAUTION]  
>  <span data-ttu-id="5304a-129">Meðan á uppfærsla á forritakóðanum úr Microsoft Dynamics NAV 2009 eða fyrri útgáfum yfir í Microsoft Dynamics NAV 2016 eru eftirfarandi aðgerðir ekki tiltækar í Microsoft Dynamics NAV 2016.</span><span class="sxs-lookup"><span data-stu-id="5304a-129">During the upgrade of application code from Microsoft Dynamics NAV 2009 or earlier versions to Microsoft Dynamics NAV 2016, the following functions are not available in Microsoft Dynamics NAV 2016.</span></span> <span data-ttu-id="5304a-130">Ef þú ert með sérstillingar sem nota einn eða fleiri aðgerðir verður að uppfæra kóðann í samræmi við það.</span><span class="sxs-lookup"><span data-stu-id="5304a-130">If you have customizations that use one or more of the functions, you must upgrade that code accordingly.</span></span>

 <span data-ttu-id="5304a-131">InsertJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-131">InsertJnlLineDim</span></span>  

 <span data-ttu-id="5304a-132">UpdateJnlLineDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-132">UpdateJnlLineDefaultDim</span></span>  

 <span data-ttu-id="5304a-133">GetJnlLineDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-133">GetJnlLineDefaultDim</span></span>  

 <span data-ttu-id="5304a-134">GetPreviousDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-134">GetPreviousDocDefaultDim</span></span>  

 <span data-ttu-id="5304a-135">GetPreviousProdDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-135">GetPreviousProdDocDefaultDim</span></span>  

 <span data-ttu-id="5304a-136">InsertDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-136">InsertDocDim</span></span>  

 <span data-ttu-id="5304a-137">UpdateDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-137">UpdateDocDefaultDim</span></span>  

 <span data-ttu-id="5304a-138">ExtractDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-138">ExtractDocDefaultDim</span></span>  

 <span data-ttu-id="5304a-139">InsertProdDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-139">InsertProdDocDim</span></span>  

 <span data-ttu-id="5304a-140">UpdateProdDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="5304a-140">UpdateProdDocDefaultDim</span></span>  

 <span data-ttu-id="5304a-141">GetServContractDim</span><span class="sxs-lookup"><span data-stu-id="5304a-141">InsertServContractDim</span></span>  

 <span data-ttu-id="5304a-142">UpdateServcontractDim</span><span class="sxs-lookup"><span data-stu-id="5304a-142">UpdateServcontractDim</span></span>  

 <span data-ttu-id="5304a-143">UpdateDefaultDimNewDimValue</span><span class="sxs-lookup"><span data-stu-id="5304a-143">UpdateDefaultDimNewDimValue</span></span>  

 <span data-ttu-id="5304a-144">GetDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-144">GetDocDim</span></span>  

 <span data-ttu-id="5304a-145">GetProdDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-145">GetProdDocDim</span></span>  

 <span data-ttu-id="5304a-146">TypeToTableID1</span><span class="sxs-lookup"><span data-stu-id="5304a-146">TypeToTableID1</span></span>  

 <span data-ttu-id="5304a-147">TypeToTableID2</span><span class="sxs-lookup"><span data-stu-id="5304a-147">TypeToTableID2</span></span>  

 <span data-ttu-id="5304a-148">TypeToTableID3</span><span class="sxs-lookup"><span data-stu-id="5304a-148">TypeToTableID3</span></span>  

 <span data-ttu-id="5304a-149">TypeToTableID4</span><span class="sxs-lookup"><span data-stu-id="5304a-149">TypeToTableID4</span></span>  

 <span data-ttu-id="5304a-150">TypeToTableID5</span><span class="sxs-lookup"><span data-stu-id="5304a-150">TypeToTableID5</span></span>  

 <span data-ttu-id="5304a-151">DeleteJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-151">DeleteJnlLineDim</span></span>  

 <span data-ttu-id="5304a-152">DeleteDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-152">DeleteDocDim</span></span>  

 <span data-ttu-id="5304a-153">DeletePostedDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-153">DeletePostedDocDim</span></span>  

 <span data-ttu-id="5304a-154">DeleteProdDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-154">DeleteProdDocDim</span></span>  

 <span data-ttu-id="5304a-155">DeleteServContractDim</span><span class="sxs-lookup"><span data-stu-id="5304a-155">DeleteServContractDim</span></span>  

 <span data-ttu-id="5304a-156">ShowJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-156">ShowJnlLineDim</span></span>  

 <span data-ttu-id="5304a-157">SaveJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-157">SaveJnlLineDim</span></span>  

 <span data-ttu-id="5304a-158">ShowJnlLineNewDim</span><span class="sxs-lookup"><span data-stu-id="5304a-158">ShowJnlLineNewDim</span></span>  

 <span data-ttu-id="5304a-159">SaveJnlLineNewDim</span><span class="sxs-lookup"><span data-stu-id="5304a-159">SaveJnlLineNewDim</span></span>  

 <span data-ttu-id="5304a-160">ShowDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-160">ShowDocDim</span></span>  

 <span data-ttu-id="5304a-161">SaveDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-161">SaveDocDim</span></span>  

 <span data-ttu-id="5304a-162">ShowProdDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-162">ShowProdDocDim</span></span>  

 <span data-ttu-id="5304a-163">SaveProdDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-163">SaveProdDocDim</span></span>  

 <span data-ttu-id="5304a-164">ShowTempDim</span><span class="sxs-lookup"><span data-stu-id="5304a-164">ShowTempDim</span></span>  

 <span data-ttu-id="5304a-165">SaveTempDim</span><span class="sxs-lookup"><span data-stu-id="5304a-165">SaveTempDim</span></span>  

 <span data-ttu-id="5304a-166">ShowTempNewDim</span><span class="sxs-lookup"><span data-stu-id="5304a-166">ShowTempNewDim</span></span>  

 <span data-ttu-id="5304a-167">SaveTempNewDim</span><span class="sxs-lookup"><span data-stu-id="5304a-167">SaveTempNewDim</span></span>  

 <span data-ttu-id="5304a-168">SaveServContractDim</span><span class="sxs-lookup"><span data-stu-id="5304a-168">SaveServContractDim</span></span>  

 <span data-ttu-id="5304a-169">MoveJnlLineDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="5304a-169">MoveJnlLineDimToLedgEntryDim</span></span>  

 <span data-ttu-id="5304a-170">MoveDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-170">MoveDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="5304a-171">MoveOneDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-171">MoveOneDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="5304a-172">MoveLedgEntryDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-172">MoveLedgEntryDimToJnlLineDim</span></span>  

 <span data-ttu-id="5304a-173">MoveDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-173">MoveDimBufToJnlLineDim</span></span>  

 <span data-ttu-id="5304a-174">MoveDimBufToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="5304a-174">MoveDimBufToLedgEntryDim</span></span>  

 <span data-ttu-id="5304a-175">MoveDimBufToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-175">MoveDimBufToPostedDocDim</span></span>  

 <span data-ttu-id="5304a-176">MoveDimBufToGLBudgetDim</span><span class="sxs-lookup"><span data-stu-id="5304a-176">MoveDimBufToGLBudgetDim</span></span>  

 <span data-ttu-id="5304a-177">CopyDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-177">CopyJnlLineDimToJnlLineDim</span></span>  

 <span data-ttu-id="5304a-178">CopyLedgEntryDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-178">CopyLedgEntryDimToJnlLineDim</span></span>  

 <span data-ttu-id="5304a-179">CopyDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-179">CopyDocDimToDocDim</span></span>  

 <span data-ttu-id="5304a-180">CopyPostedDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-180">CopyPostedDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="5304a-181">CopyDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-181">CopyDocDimToJnlLineDim</span></span>  

 <span data-ttu-id="5304a-182">CopyDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-182">CopyDimBufToJnlLineDim</span></span>  

 <span data-ttu-id="5304a-183">CopyDimBufToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-183">CopyDimBufToDocDim</span></span>  

 <span data-ttu-id="5304a-184">CopyDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-184">CopySCDimToDocDim</span></span>  

 <span data-ttu-id="5304a-185">MoveDocDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="5304a-185">MoveDocDimToLedgEntryDim</span></span>  

 <span data-ttu-id="5304a-186">MoveDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-186">MoveDocDimToDocDim</span></span>  

 <span data-ttu-id="5304a-187">MoveDocDimArchvToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-187">MoveDocDimArchvToDocDim</span></span>  

 <span data-ttu-id="5304a-188">MoveLedgEntryDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-188">MoveLedgEntryDimToDocDim</span></span>  

 <span data-ttu-id="5304a-189">MoveProdDocDimToProdDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-189">MoveProdDocDimToProdDocDim</span></span>  

 <span data-ttu-id="5304a-190">MoveJnlLineDimToProdDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-190">MoveJnlLineDimToProdDocDim</span></span>  

 <span data-ttu-id="5304a-191">MoveJnlLineDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-191">MoveJnlLineDimToDocDim</span></span>  

 <span data-ttu-id="5304a-192">MoveJnlLineDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-192">MoveJnlLineDimToJnlLineDim</span></span>  

 <span data-ttu-id="5304a-193">CopyLedgEntryDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="5304a-193">CopyLedgEntryDimToLedgEntryDim</span></span>  

 <span data-ttu-id="5304a-194">MoveTempFromDimToTempToDim</span><span class="sxs-lookup"><span data-stu-id="5304a-194">MoveTempFromDimToTempToDim</span></span>  

 <span data-ttu-id="5304a-195">TransferTempToDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="5304a-195">TransferTempToDimToDocDim</span></span>  

 <span data-ttu-id="5304a-196">MoveJnlLineDimToBuf</span><span class="sxs-lookup"><span data-stu-id="5304a-196">MoveJnlLineDimToBuf</span></span>  

 <span data-ttu-id="5304a-197">CopyICJnlDimToICJnlDim</span><span class="sxs-lookup"><span data-stu-id="5304a-197">CopyICJnlDimToICJnlDim</span></span>  

 <span data-ttu-id="5304a-198">TestDimValue</span><span class="sxs-lookup"><span data-stu-id="5304a-198">TestDimValue</span></span>  

 <span data-ttu-id="5304a-199">TestNewDimValue</span><span class="sxs-lookup"><span data-stu-id="5304a-199">TestNewDimValue</span></span>  

 <span data-ttu-id="5304a-200">MoveDimBufToItemBudgetDim.</span><span class="sxs-lookup"><span data-stu-id="5304a-200">MoveDimBufToItemBudgetDim.</span></span> <span data-ttu-id="5304a-201">(Eyða vegna þessa að taflan ItemBudgetDim er eytt.)</span><span class="sxs-lookup"><span data-stu-id="5304a-201">(Delete because the ItemBudgetDim Table is deleted.)</span></span>  

 <span data-ttu-id="5304a-202">GetServContractDim</span><span class="sxs-lookup"><span data-stu-id="5304a-202">GetServContractDim</span></span>  

 <span data-ttu-id="5304a-203">MoveTempDimToBuf</span><span class="sxs-lookup"><span data-stu-id="5304a-203">MoveTempDimToBuf</span></span>  

 <span data-ttu-id="5304a-204">UpdateSCInvLineDim</span><span class="sxs-lookup"><span data-stu-id="5304a-204">UpdateSCInvLineDim</span></span>  

 <span data-ttu-id="5304a-205">CopyJnlLineDimToBuffer</span><span class="sxs-lookup"><span data-stu-id="5304a-205">CopyJnlLineDimToBuffer</span></span>  

 <span data-ttu-id="5304a-206">UpdateDocDefaultDim2</span><span class="sxs-lookup"><span data-stu-id="5304a-206">UpdateDocDefaultDim2</span></span>  

## <a name="see-also"></a><span data-ttu-id="5304a-207">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="5304a-207">See Also</span></span>
 <span data-ttu-id="5304a-208">[Hönnunarupplýsingarn: Færslur víddarsamstæða](design-details-dimension-set-entries.md) </span><span class="sxs-lookup"><span data-stu-id="5304a-208">[Design Details: Dimension Set Entries](design-details-dimension-set-entries.md) </span></span>  
 <span data-ttu-id="5304a-209">[Hönnunarupplýsingar - Færslur víddarsamstæða yfirlit](design-details-dimension-set-entries-overview.md) </span><span class="sxs-lookup"><span data-stu-id="5304a-209">[Design Details: Dimension Set Entries Overview](design-details-dimension-set-entries-overview.md) </span></span>  
 <span data-ttu-id="5304a-210">[Hönnunarupplýsingar Leitað að víddarsamsetningum](design-details-searching-for-dimension-combinations.md) </span><span class="sxs-lookup"><span data-stu-id="5304a-210">[Design Details: Searching for Dimension Combinations](design-details-searching-for-dimension-combinations.md) </span></span>  
 <span data-ttu-id="5304a-211">[Hönnunarupplýsingar töfluuppbygging](design-details-table-structure.md) </span><span class="sxs-lookup"><span data-stu-id="5304a-211">[Design Details: Table Structure](design-details-table-structure.md) </span></span>  
 [<span data-ttu-id="5304a-212">Hönnunarupplýsingar: Kóðadæmi um breytt mynstur í Breytingar</span><span class="sxs-lookup"><span data-stu-id="5304a-212">Design Details: Code Examples of Changed Patterns in Modifications</span></span>](design-details-code-examples-of-changed-patterns-in-modifications.md)
