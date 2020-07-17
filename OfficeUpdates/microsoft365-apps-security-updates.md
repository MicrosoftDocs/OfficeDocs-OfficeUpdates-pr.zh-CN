---
title: Microsoft 365 应用安全更新的发行说明
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人员提供 Microsoft 365 应用安全更新的发行说明
ms.openlocfilehash: 58228af0a7958547331b95c28c6497b5bfa3f460
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138518"
---
# <a name="release-notes-for-microsoft-365-apps-security-updates"></a><span data-ttu-id="55b52-103">Microsoft 365 应用安全更新的发行说明</span><span class="sxs-lookup"><span data-stu-id="55b52-103">Release notes for Microsoft 365 Apps Security Updates</span></span>

<span data-ttu-id="55b52-104">这些发行说明介绍了 Microsoft 365 应用更新中包含的安全修补程序。</span><span class="sxs-lookup"><span data-stu-id="55b52-104">These release notes provide information about security fixes that are included in updates to Microsoft 365 Apps.</span></span>

<span data-ttu-id="55b52-105">此信息适用于 Microsoft 365 企业应用版、Microsoft 365 商业应用版以及 Project 和 Visio 桌面应用的订阅版本。</span><span class="sxs-lookup"><span data-stu-id="55b52-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="55b52-106">我们正在对 Microsoft 365 应用的更新频道进行一些更改，包括添加新的更新频道（月度企业版频道）和更改现有更新频道的名称。</span><span class="sxs-lookup"><span data-stu-id="55b52-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="55b52-107">若要了解详细信息，请[阅读这篇文章](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="55b52-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="55b52-108">自版本 2004 起，Office 365 专业增强版现在重命名为“Microsoft 365 企业应用版”。</span><span class="sxs-lookup"><span data-stu-id="55b52-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="55b52-109">若要了解详细信息，请 [阅读这篇文章](https://go.microsoft.com/fwlink/p/?linkid=2123420)。</span><span class="sxs-lookup"><span data-stu-id="55b52-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="55b52-110">我们的文档通常将它称为“Microsoft 365 应用版”。</span><span class="sxs-lookup"><span data-stu-id="55b52-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (请勿删除上面的线条，它用于调节间距)  

## <a name="july-14-2020"></a><span data-ttu-id="55b52-112">2020 年 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="55b52-112">July 14, 2020</span></span>
<span data-ttu-id="55b52-113">当前频道：版本 2006（内部版本 13001.20384）</span><span class="sxs-lookup"><span data-stu-id="55b52-113">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="55b52-114">月度企业版渠道：版本 2005（内部版本 12827.20538）</span><span class="sxs-lookup"><span data-stu-id="55b52-114">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="55b52-115">月度企业版渠道：版本 2004（内部版本 12730.20602）</span><span class="sxs-lookup"><span data-stu-id="55b52-115">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="55b52-116">半年企业频道（预览）：版本 2002（内部版本 12527.20880）</span><span class="sxs-lookup"><span data-stu-id="55b52-116">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="55b52-117">半年企业频道：版本 2002（内部版本 12527.20880）</span><span class="sxs-lookup"><span data-stu-id="55b52-117">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="55b52-118">半年企业频道：版本 1908（内部版本 11929.20904）</span><span class="sxs-lookup"><span data-stu-id="55b52-118">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="55b52-119">半年企业频道：版本 1902（内部版本 11328.20624）</span><span class="sxs-lookup"><span data-stu-id="55b52-119">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="55b52-120">Windows 7 版 Microsoft 365 应用：版本 2002（内部版本 12527.20880）</span><span class="sxs-lookup"><span data-stu-id="55b52-120">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (请勿移除安全详细信息内容开头)


### <a name="excel"></a><span data-ttu-id="55b52-122">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-122">Excel</span></span>

-   [<span data-ttu-id="55b52-123">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="55b52-123">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="55b52-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="55b52-124">Outlook</span></span>

-   [<span data-ttu-id="55b52-125">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="55b52-125">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="55b52-126">Project</span><span class="sxs-lookup"><span data-stu-id="55b52-126">Project</span></span>

-   [<span data-ttu-id="55b52-127">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="55b52-127">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="55b52-128">Word</span><span class="sxs-lookup"><span data-stu-id="55b52-128">Word</span></span>

-   [<span data-ttu-id="55b52-129">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="55b52-129">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="55b52-130">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="55b52-130">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="55b52-131">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="55b52-131">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="55b52-132">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="55b52-132">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="55b52-133">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-133">Office Suite</span></span>

-   [<span data-ttu-id="55b52-134">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="55b52-134">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1458)

[//]: # (请勿移除安全详细信息内容结尾)



## <a name="june-09-2020"></a><span data-ttu-id="55b52-136">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="55b52-136">June 09, 2020</span></span>
<span data-ttu-id="55b52-137">当前频道：版本 2005（内部版本 12827.20336）</span><span class="sxs-lookup"><span data-stu-id="55b52-137">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="55b52-138">月度企业版渠道：版本 2004（内部版本 12730.20430）</span><span class="sxs-lookup"><span data-stu-id="55b52-138">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="55b52-139">月度企业版渠道：版本 2003（内部版本 12624.20708）</span><span class="sxs-lookup"><span data-stu-id="55b52-139">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="55b52-140">半年企业频道（预览）：版本 2002（内部版本 12527.20720）</span><span class="sxs-lookup"><span data-stu-id="55b52-140">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="55b52-141">半年企业频道：版本 1908（内部版本 11929.20838）</span><span class="sxs-lookup"><span data-stu-id="55b52-141">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="55b52-142">半年企业频道：版本 1902（内部版本 11328.20602）</span><span class="sxs-lookup"><span data-stu-id="55b52-142">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="55b52-143">Windows 7 版 Microsoft 365 应用：版本 2002（内部版本 12527.20720）</span><span class="sxs-lookup"><span data-stu-id="55b52-143">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (请勿移除安全详细信息内容开头)


### <a name="excel"></a><span data-ttu-id="55b52-145">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-145">Excel</span></span>

-   [<span data-ttu-id="55b52-146">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="55b52-146">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="55b52-147">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="55b52-147">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="55b52-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="55b52-148">Outlook</span></span>

-   [<span data-ttu-id="55b52-149">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="55b52-149">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="55b52-150">Project</span><span class="sxs-lookup"><span data-stu-id="55b52-150">Project</span></span>

-   [<span data-ttu-id="55b52-151">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="55b52-151">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="55b52-152">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-152">Office Suite</span></span>

-   [<span data-ttu-id="55b52-153">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="55b52-153">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-1321)

[//]: # (请勿移除安全详细信息内容结尾)



## <a name="may-12-2020"></a><span data-ttu-id="55b52-155">2020 年 5 月12 日</span><span class="sxs-lookup"><span data-stu-id="55b52-155">May 12, 2020</span></span>
<span data-ttu-id="55b52-156">月度频道：版本 2004（内部版本 12730.20270）</span><span class="sxs-lookup"><span data-stu-id="55b52-156">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="55b52-157">月度企业版渠道：版本 2003（内部版本 12624.20588）</span><span class="sxs-lookup"><span data-stu-id="55b52-157">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="55b52-158">半年频道（定向）：版本 2002（内部版本 12527.20612）</span><span class="sxs-lookup"><span data-stu-id="55b52-158">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="55b52-159">半年频道：版本 1908（内部版11929.20776）</span><span class="sxs-lookup"><span data-stu-id="55b52-159">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="55b52-160">半年频道：版本 1902（内部版11328.20586）</span><span class="sxs-lookup"><span data-stu-id="55b52-160">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="55b52-161">Windows 7 版 Microsoft 365 应用：版本 2002（内部版本 12527.20612）</span><span class="sxs-lookup"><span data-stu-id="55b52-161">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (请勿移除安全详细信息内容开头)


### <a name="excel"></a><span data-ttu-id="55b52-163">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-163">Excel</span></span>

-   [<span data-ttu-id="55b52-164">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="55b52-164">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0901)

[//]: # (请勿移除安全详细信息内容结尾)



## <a name="april-14-2020"></a><span data-ttu-id="55b52-166">2020 年 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="55b52-166">April 14, 2020</span></span>
<span data-ttu-id="55b52-167">每月频道：版本 2003（内部版本 12624.20442）</span><span class="sxs-lookup"><span data-stu-id="55b52-167">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="55b52-168">半年频道（定向）：版本 2002（内部版本 12527.20442）</span><span class="sxs-lookup"><span data-stu-id="55b52-168">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="55b52-169">半年频道：版本 1908（内部版本 11929.20708）</span><span class="sxs-lookup"><span data-stu-id="55b52-169">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="55b52-170">半年频道：版本 1902（内部版本 11328.20564）</span><span class="sxs-lookup"><span data-stu-id="55b52-170">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="55b52-171">Windows 7 版 Microsoft 365 应用：版本 2002（内部版本 12527.20442）</span><span class="sxs-lookup"><span data-stu-id="55b52-171">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (请勿移除安全详细信息内容开头)


### <a name="excel"></a><span data-ttu-id="55b52-173">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-173">Excel</span></span>

-   [<span data-ttu-id="55b52-174">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="55b52-174">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="55b52-175">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="55b52-175">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="55b52-176">Word</span><span class="sxs-lookup"><span data-stu-id="55b52-176">Word</span></span>

-   [<span data-ttu-id="55b52-177">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="55b52-177">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="55b52-178">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-178">Office Suite</span></span>

-   [<span data-ttu-id="55b52-179">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="55b52-179">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="55b52-180">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="55b52-180">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="55b52-181">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="55b52-181">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0961)

[//]: # (请勿移除安全详细信息内容结尾)



## <a name="march-10-2020"></a><span data-ttu-id="55b52-183">2020 年 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="55b52-183">March 10, 2020</span></span>
<span data-ttu-id="55b52-184">每月频道：版本 2002（内部版本 12527.20278）</span><span class="sxs-lookup"><span data-stu-id="55b52-184">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="55b52-185">半年频道（定向）：版本 2002（内部版本 12527.20278）</span><span class="sxs-lookup"><span data-stu-id="55b52-185">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="55b52-186">半年频道：版本 1908（内部版本 11929.20648）</span><span class="sxs-lookup"><span data-stu-id="55b52-186">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="55b52-187">半年频道：版本 1902（内部版本 11328.20554）</span><span class="sxs-lookup"><span data-stu-id="55b52-187">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="55b52-188">Windows 7 版 Microsoft 365 应用：版本 2002（内部版本 12527.20278）</span><span class="sxs-lookup"><span data-stu-id="55b52-188">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (请勿移除安全详细信息内容开头)



### <a name="word"></a><span data-ttu-id="55b52-190">Word</span><span class="sxs-lookup"><span data-stu-id="55b52-190">Word</span></span>

-   [<span data-ttu-id="55b52-191">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="55b52-191">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="55b52-192">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="55b52-192">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="55b52-193">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="55b52-193">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="55b52-194">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="55b52-194">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0851)

[//]: # (请勿移除安全详细信息内容结尾)



## <a name="february-11-2020"></a><span data-ttu-id="55b52-196">2020 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="55b52-196">February 11, 2020</span></span>
<span data-ttu-id="55b52-197">每月频道：版本 2001（内部版本 12430.20264）</span><span class="sxs-lookup"><span data-stu-id="55b52-197">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="55b52-198">半年频道（定向）：版本 1908（内部版本 11929.20606）</span><span class="sxs-lookup"><span data-stu-id="55b52-198">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="55b52-199">半年频道：版本 1908（内部版本 11929.20606）</span><span class="sxs-lookup"><span data-stu-id="55b52-199">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="55b52-200">半年频道：版本 1902（内部版本 11328.20526）</span><span class="sxs-lookup"><span data-stu-id="55b52-200">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="55b52-201">半年频道：版本 1808（内部版本 10730.20438）</span><span class="sxs-lookup"><span data-stu-id="55b52-201">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (请勿移除安全详细信息内容开头)


### <a name="excel"></a><span data-ttu-id="55b52-203">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-203">Excel</span></span>

-   [<span data-ttu-id="55b52-204">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="55b52-204">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="55b52-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="55b52-205">Outlook</span></span>

-   [<span data-ttu-id="55b52-206">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="55b52-206">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="55b52-207">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-207">Office Suite</span></span>

-   [<span data-ttu-id="55b52-208">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="55b52-208">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0697)

[//]: # (请勿移除安全详细信息内容结尾)



## <a name="january-14-2020"></a><span data-ttu-id="55b52-210">2020 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="55b52-210">January 14, 2020</span></span>
<span data-ttu-id="55b52-211">每月频道：版本 1912（内部版本 12325.20298）</span><span class="sxs-lookup"><span data-stu-id="55b52-211">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="55b52-212">半年频道（定向）：版本 1908（内部版本 11929.20562）</span><span class="sxs-lookup"><span data-stu-id="55b52-212">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="55b52-213">半年频道：版本 1908（内部版本 11929.20562）</span><span class="sxs-lookup"><span data-stu-id="55b52-213">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="55b52-214">半年频道：版本 1902（内部版本 11328.20512）</span><span class="sxs-lookup"><span data-stu-id="55b52-214">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="55b52-215">半年频道：版本 1808（内部版本 10730.20432）</span><span class="sxs-lookup"><span data-stu-id="55b52-215">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (请勿移除安全详细信息内容开头)


### <a name="excel"></a><span data-ttu-id="55b52-217">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-217">Excel</span></span>

-   [<span data-ttu-id="55b52-218">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="55b52-218">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="55b52-219">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="55b52-219">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="55b52-220">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="55b52-220">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="55b52-221">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-221">Office Suite</span></span>

-   [<span data-ttu-id="55b52-222">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="55b52-222">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2020-0652)

[//]: # (请勿移除安全详细信息内容结尾)



## <a name="december-10-2019"></a><span data-ttu-id="55b52-224">2019 年 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="55b52-224">December 10, 2019</span></span>
<span data-ttu-id="55b52-225">每月频道：版本 1911（内部版本 12228.20364）</span><span class="sxs-lookup"><span data-stu-id="55b52-225">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="55b52-226">半年频道（定向）：版本 1908（内部版本 11929.20516）</span><span class="sxs-lookup"><span data-stu-id="55b52-226">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="55b52-227">半年频道：版本 1902（内部版本 11328.20492）</span><span class="sxs-lookup"><span data-stu-id="55b52-227">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="55b52-228">半年频道：版本 1808（内部版本 10730.20426）</span><span class="sxs-lookup"><span data-stu-id="55b52-228">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="55b52-229">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-229">Excel</span></span>

-   [<span data-ttu-id="55b52-230">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="55b52-230">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="55b52-231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55b52-231">PowerPoint</span></span>

-   [<span data-ttu-id="55b52-232">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="55b52-232">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="55b52-233">Word</span><span class="sxs-lookup"><span data-stu-id="55b52-233">Word</span></span>

-   [<span data-ttu-id="55b52-234">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="55b52-234">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="55b52-235">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-235">Office Suite</span></span>

-   [<span data-ttu-id="55b52-236">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="55b52-236">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="55b52-237">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="55b52-237">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="55b52-238">2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="55b52-238">November 12, 2019</span></span>
<span data-ttu-id="55b52-239">每月频道：版本1910（内部版本12130.20344）</span><span class="sxs-lookup"><span data-stu-id="55b52-239">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="55b52-240">半年频道（定向）：版本 1908（内部版本 11929.20436）</span><span class="sxs-lookup"><span data-stu-id="55b52-240">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="55b52-241">半年频道：版本 1902（内部版本 11328.20468）</span><span class="sxs-lookup"><span data-stu-id="55b52-241">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="55b52-242">半年频道：版本 1808（内部版本 10730.20416）</span><span class="sxs-lookup"><span data-stu-id="55b52-242">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="55b52-243">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-243">Excel</span></span>

-   [<span data-ttu-id="55b52-244">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="55b52-244">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="55b52-245">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="55b52-245">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="55b52-246">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-246">Office Suite</span></span>

-   [<span data-ttu-id="55b52-247">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="55b52-247">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="55b52-248">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="55b52-248">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="55b52-249">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="55b52-249">October 08, 2019</span></span>
<span data-ttu-id="55b52-250">每月频道：版本 1909（内部版本 12026.20320）</span><span class="sxs-lookup"><span data-stu-id="55b52-250">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="55b52-251">半年频道（定向）：版本 1908（内部版本 11929.20388）</span><span class="sxs-lookup"><span data-stu-id="55b52-251">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="55b52-252">半年频道：版本 1902（内部版本 11328.20438）</span><span class="sxs-lookup"><span data-stu-id="55b52-252">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="55b52-253">半年频道：版本 1808（内部版本 10730.20386）</span><span class="sxs-lookup"><span data-stu-id="55b52-253">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="55b52-254">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-254">Excel</span></span>

-   [<span data-ttu-id="55b52-255">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="55b52-255">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="55b52-256">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="55b52-256">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="55b52-257">2019 年 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="55b52-257">September 10, 2019</span></span>
<span data-ttu-id="55b52-258">每月频道：版本 1908（内部版本 11929.20300）</span><span class="sxs-lookup"><span data-stu-id="55b52-258">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="55b52-259">半年频道（定向）：版本 1908（内部版本 11929.20300）</span><span class="sxs-lookup"><span data-stu-id="55b52-259">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="55b52-260">半年频道：版本 1902（内部版本 11328.20420）</span><span class="sxs-lookup"><span data-stu-id="55b52-260">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="55b52-261">半年频道：版本 1808（内部版本 10730.20380）</span><span class="sxs-lookup"><span data-stu-id="55b52-261">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="55b52-262">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-262">Excel</span></span>

-   [<span data-ttu-id="55b52-263">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="55b52-263">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="55b52-264">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="55b52-264">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="55b52-265">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-265">Office Suite</span></span>

-   [<span data-ttu-id="55b52-266">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="55b52-266">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="55b52-267">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="55b52-267">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="55b52-268">2019 年 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="55b52-268">August 13, 2019</span></span>
<span data-ttu-id="55b52-269">每月频道：版本 1907（内部版本 11901.20218）</span><span class="sxs-lookup"><span data-stu-id="55b52-269">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="55b52-270">半年频道（定向）：版本 1902（内部版本 11328.20392）</span><span class="sxs-lookup"><span data-stu-id="55b52-270">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="55b52-271">半年频道：版本 1902（内部版本 11328.20392）</span><span class="sxs-lookup"><span data-stu-id="55b52-271">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="55b52-272">半年频道：版本 1808（内部版本 10730.20370）</span><span class="sxs-lookup"><span data-stu-id="55b52-272">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="55b52-273">半年频道：版本 1803（内部版本 9126.2432）</span><span class="sxs-lookup"><span data-stu-id="55b52-273">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="55b52-274">Outlook</span><span class="sxs-lookup"><span data-stu-id="55b52-274">Outlook</span></span>

-   [<span data-ttu-id="55b52-275">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="55b52-275">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="55b52-276">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="55b52-276">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="55b52-277">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="55b52-277">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="55b52-278">Word</span><span class="sxs-lookup"><span data-stu-id="55b52-278">Word</span></span>

-   [<span data-ttu-id="55b52-279">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="55b52-279">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="55b52-280">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="55b52-280">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="55b52-281">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-281">Office Suite</span></span>

-   [<span data-ttu-id="55b52-282">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="55b52-282">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="55b52-283">2019 年 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="55b52-283">July 09, 2019</span></span>
<span data-ttu-id="55b52-284">每月频道：版本 1906（内部版本 11727.20244）</span><span class="sxs-lookup"><span data-stu-id="55b52-284">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="55b52-285">半年频道（定向）：版本 1902（内部版本 11328.20368）</span><span class="sxs-lookup"><span data-stu-id="55b52-285">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="55b52-286">半年频道：版本 1902（内部版本 11328.20368）</span><span class="sxs-lookup"><span data-stu-id="55b52-286">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="55b52-287">半年频道：版本 1808（内部版本 10730.20360）</span><span class="sxs-lookup"><span data-stu-id="55b52-287">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="55b52-288">半年频道：版本 1803（内部版本 9126.2428）</span><span class="sxs-lookup"><span data-stu-id="55b52-288">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="55b52-289">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-289">Excel</span></span>

-   [<span data-ttu-id="55b52-290">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="55b52-290">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="55b52-291">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="55b52-291">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="55b52-292">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="55b52-292">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="55b52-293">Outlook</span><span class="sxs-lookup"><span data-stu-id="55b52-293">Outlook</span></span>

-   [<span data-ttu-id="55b52-294">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="55b52-294">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="55b52-295">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="55b52-295">Skype for Business</span></span>

-   [<span data-ttu-id="55b52-296">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="55b52-296">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="55b52-297">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-297">Office Suite</span></span>

-   [<span data-ttu-id="55b52-298">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="55b52-298">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="55b52-299">2019 年 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="55b52-299">June 11, 2019</span></span>
<span data-ttu-id="55b52-300">每月频道：版本 1905（内部版本 11629.20246）</span><span class="sxs-lookup"><span data-stu-id="55b52-300">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="55b52-301">半年频道（定向）：版本 1902（生成号 11328.20318）</span><span class="sxs-lookup"><span data-stu-id="55b52-301">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="55b52-302">半年频道：版本 1808（内部版本 10730.20348）</span><span class="sxs-lookup"><span data-stu-id="55b52-302">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="55b52-303">半年频道：版本 1803（内部版本 9126.2388）</span><span class="sxs-lookup"><span data-stu-id="55b52-303">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="55b52-304">Word</span><span class="sxs-lookup"><span data-stu-id="55b52-304">Word</span></span>

-   [<span data-ttu-id="55b52-305">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="55b52-305">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="55b52-306">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="55b52-306">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="55b52-307">2019 年 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="55b52-307">May 14, 2019</span></span>
<span data-ttu-id="55b52-308">每月频道：版本 1904（内部版本 11601.20204）</span><span class="sxs-lookup"><span data-stu-id="55b52-308">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="55b52-309">半年频道（定向）：版本 1902（内部版本 11328.20286）</span><span class="sxs-lookup"><span data-stu-id="55b52-309">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="55b52-310">半年频道：版本 1808（内部版本 10730.20344）</span><span class="sxs-lookup"><span data-stu-id="55b52-310">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="55b52-311">半年频道：版本 1803（内部版本 9126.2387）</span><span class="sxs-lookup"><span data-stu-id="55b52-311">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="55b52-312">Word</span><span class="sxs-lookup"><span data-stu-id="55b52-312">Word</span></span>

-   [<span data-ttu-id="55b52-313">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="55b52-313">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="55b52-314">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-314">Office Suite</span></span>

-   [<span data-ttu-id="55b52-315">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="55b52-315">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="55b52-316">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="55b52-316">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="55b52-317">2019 年 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="55b52-317">April 09, 2019</span></span>
<span data-ttu-id="55b52-318">每月频道：版本 1903（内部版本 11425.20204）</span><span class="sxs-lookup"><span data-stu-id="55b52-318">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="55b52-319">半年频道（定向）：版本 1902（生成号 11328.20230）</span><span class="sxs-lookup"><span data-stu-id="55b52-319">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="55b52-320">半年频道：版本 1808（内部版本 10730.20334）</span><span class="sxs-lookup"><span data-stu-id="55b52-320">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="55b52-321">半年频道：版本 1803（内部版本 9126.2382）</span><span class="sxs-lookup"><span data-stu-id="55b52-321">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="55b52-322">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-322">Excel</span></span>

-   [<span data-ttu-id="55b52-323">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="55b52-323">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="55b52-324">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-324">Office Suite</span></span>

-   [<span data-ttu-id="55b52-325">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="55b52-325">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="55b52-326">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="55b52-326">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="55b52-327">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="55b52-327">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="55b52-328">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="55b52-328">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="55b52-329">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="55b52-329">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="55b52-330">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="55b52-330">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="55b52-331">2019 年 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="55b52-331">March 12, 2019</span></span>
<span data-ttu-id="55b52-332">本月任何渠道没有安全更新。</span><span class="sxs-lookup"><span data-stu-id="55b52-332">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="55b52-333">2019 年 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="55b52-333">February 12, 2019</span></span>
<span data-ttu-id="55b52-334">每月频道：版本 1901（内部版本 11231.20174）</span><span class="sxs-lookup"><span data-stu-id="55b52-334">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="55b52-335">半年频道（定向）：版本 1808（内部版本 10730.20280）</span><span class="sxs-lookup"><span data-stu-id="55b52-335">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="55b52-336">半年频道：版本 1808（内部版本 10730.20280）</span><span class="sxs-lookup"><span data-stu-id="55b52-336">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="55b52-337">半年频道：版本 1803（内部版本 9126.2356）</span><span class="sxs-lookup"><span data-stu-id="55b52-337">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="55b52-338">半年频道：版本 1708（内部版本 8431.2372）</span><span class="sxs-lookup"><span data-stu-id="55b52-338">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="55b52-339">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-339">Excel</span></span>

-   [<span data-ttu-id="55b52-340">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="55b52-340">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="55b52-341">Office 套件</span><span class="sxs-lookup"><span data-stu-id="55b52-341">Office suite</span></span>

-   [<span data-ttu-id="55b52-342">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="55b52-342">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="55b52-343">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="55b52-343">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="55b52-344">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="55b52-344">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="55b52-345">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="55b52-345">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="55b52-346">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="55b52-346">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="55b52-347">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="55b52-347">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="55b52-348">2019 年 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="55b52-348">January 8, 2019</span></span>

<span data-ttu-id="55b52-349">每月频道：版本 1812（内部版本 11126.20196）</span><span class="sxs-lookup"><span data-stu-id="55b52-349">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="55b52-350">半年定向频道：版本 1808（内部版本 10730.20264）</span><span class="sxs-lookup"><span data-stu-id="55b52-350">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="55b52-351">半年频道：版本 1808（内部版本 10730.20264）</span><span class="sxs-lookup"><span data-stu-id="55b52-351">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="55b52-352">半年频道：版本 1803（内部版本 9126.2351）</span><span class="sxs-lookup"><span data-stu-id="55b52-352">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="55b52-353">半年频道：版本 1708（内部版本 8431.2366）</span><span class="sxs-lookup"><span data-stu-id="55b52-353">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="55b52-354">Outlook</span><span class="sxs-lookup"><span data-stu-id="55b52-354">Outlook</span></span>
-   [<span data-ttu-id="55b52-355">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="55b52-355">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="55b52-356">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="55b52-356">Word: Security updates</span></span> 
-   [<span data-ttu-id="55b52-357">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="55b52-357">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="55b52-358">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="55b52-358">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="55b52-359">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="55b52-359">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="55b52-360">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="55b52-360">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="55b52-361">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="55b52-361">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="55b52-362">2018 年 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="55b52-362">December 11, 2018</span></span>
<span data-ttu-id="55b52-363">每月频道：版本 1811（内部版本 11029.20108）</span><span class="sxs-lookup"><span data-stu-id="55b52-363">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="55b52-364">半年频道：版本 1803（内部版本 9126.2336）</span><span class="sxs-lookup"><span data-stu-id="55b52-364">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="55b52-365">半年频道（定向）：版本 1808（内部版本 10730.20262）</span><span class="sxs-lookup"><span data-stu-id="55b52-365">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="55b52-366">Excel</span><span class="sxs-lookup"><span data-stu-id="55b52-366">Excel</span></span>

-   [<span data-ttu-id="55b52-367">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="55b52-367">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="55b52-368">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="55b52-368">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="55b52-369">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="55b52-369">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="55b52-370">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="55b52-370">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="55b52-371">Outlook</span><span class="sxs-lookup"><span data-stu-id="55b52-371">Outlook</span></span>

-   [<span data-ttu-id="55b52-372">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="55b52-372">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="55b52-373">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55b52-373">PowerPoint</span></span>

-   [<span data-ttu-id="55b52-374">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="55b52-374">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="55b52-375">2018 年 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="55b52-375">November 13, 2018</span></span>
<span data-ttu-id="55b52-376">每月频道：版本 1810（生成号 11001.20108）</span><span class="sxs-lookup"><span data-stu-id="55b52-376">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="55b52-377">半年频道：版本 1803（生成号 9126.2315）</span><span class="sxs-lookup"><span data-stu-id="55b52-377">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="55b52-378">半年频道（定向）：版本 1808（生成号 10730.20205）</span><span class="sxs-lookup"><span data-stu-id="55b52-378">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="55b52-379">Excel：</span><span class="sxs-lookup"><span data-stu-id="55b52-379">Excel:</span></span>

-   [<span data-ttu-id="55b52-380">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="55b52-380">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="55b52-381">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="55b52-381">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="55b52-382">Outlook：</span><span class="sxs-lookup"><span data-stu-id="55b52-382">Outlook:</span></span>

-   [<span data-ttu-id="55b52-383">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="55b52-383">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="55b52-384">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="55b52-384">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="55b52-385">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="55b52-385">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="55b52-386">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="55b52-386">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="55b52-387">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="55b52-387">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="55b52-388">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="55b52-388">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="55b52-389">Project：</span><span class="sxs-lookup"><span data-stu-id="55b52-389">Project:</span></span>

-   [<span data-ttu-id="55b52-390">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="55b52-390">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="55b52-391">Skype for Business：</span><span class="sxs-lookup"><span data-stu-id="55b52-391">Skype for Business:</span></span>

-   [<span data-ttu-id="55b52-392">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="55b52-392">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="55b52-393">Word：</span><span class="sxs-lookup"><span data-stu-id="55b52-393">Word:</span></span>

-   [<span data-ttu-id="55b52-394">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="55b52-394">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8573)
