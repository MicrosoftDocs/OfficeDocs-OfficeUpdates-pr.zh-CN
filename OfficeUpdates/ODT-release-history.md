---
title: Office 部署工具 (ODT) 的发布历史记录
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 为 IT 专业人士提供 Office 部署工具 (ODT) 的发布历史记录
ms.openlocfilehash: df3e2d20f3355f25da37aaeb078687a1c4763993
ms.sourcegitcommit: 8d67b1150d1818c1faa7f0ef4d7ab58a7dd653d2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/22/2020
ms.locfileid: "49725067"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="5bd01-103">Office 部署工具的发布历史记录</span><span class="sxs-lookup"><span data-stu-id="5bd01-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="5bd01-104">Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Microsoft 365 应用），并将它部署到客户端计算机。</span><span class="sxs-lookup"><span data-stu-id="5bd01-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="5bd01-105">使用 ODT，可以更全面地控制 Office 安装。</span><span class="sxs-lookup"><span data-stu-id="5bd01-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="5bd01-106">可以定义安装了哪些产品和语言、应如何更新这些产品，以及是否向用户显示安装体验。</span><span class="sxs-lookup"><span data-stu-id="5bd01-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="5bd01-107">若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="5bd01-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="5bd01-108">**支持的操作系统**：Windows 10、Windows 7、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="5bd01-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="5bd01-109">**安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="5bd01-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="5bd01-110">下载 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="5bd01-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="december-21-2020"></a><span data-ttu-id="5bd01-111">2020 年 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-111">December 21, 2020</span></span>
<span data-ttu-id="5bd01-112">版本 16.0.13426.20370（setup.exe 版本 16.0.13426.20352）</span><span class="sxs-lookup"><span data-stu-id="5bd01-112">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="5bd01-113">修正了 PerpetualVL2019 频道的 ProofingTool 本地源安装失败的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-113">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="5bd01-114">修复了一个问题，以确保在向现有安装中添加其他非全文 Office 语言的产品时，即点即用客户端会尝试自我更新</span><span class="sxs-lookup"><span data-stu-id="5bd01-114">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="5bd01-115">2020 年 12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-115">December 8, 2020</span></span>
<span data-ttu-id="5bd01-116">版本 16.0.13426.20308（setup.exe 版本 16.0.13426.20308）</span><span class="sxs-lookup"><span data-stu-id="5bd01-116">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="5bd01-117">已修复以下问题：如果设备具有从非永久 2019 通道安装的 Office 产品，则下载模式会阻止永久性的 2019 通道下载。</span><span class="sxs-lookup"><span data-stu-id="5bd01-117">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="5bd01-118">已修复以下问题：体系结构迁移将无法针对通过下载模式创建的本地源，该源已在配置 XML 中指定了显式版本。</span><span class="sxs-lookup"><span data-stu-id="5bd01-118">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="5bd01-119">2020 年 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-119">November 23, 2020</span></span>
<span data-ttu-id="5bd01-120">版本 16.0.13328.20420（setup.exe 版本 16.0.13328.20420）</span><span class="sxs-lookup"><span data-stu-id="5bd01-120">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="5bd01-121">已修复未通过 /download 模式下载校对工具的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-121">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="5bd01-122">已修复 /download 模式在普通用户中运行失败的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-122">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="5bd01-123">已修复在配置 XML 中指定 Version 属性导致在 /download 模式下无法完全下载的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-123">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="5bd01-124">已修复提取时 Office 部署工具未命名为 “setup.exe” 的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-124">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="5bd01-125">已修复在配置 XML 中提供频道属性时的安装源优先次序方面的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-125">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="5bd01-126">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-126">November 10, 2020</span></span>
<span data-ttu-id="5bd01-127">版本 16.0.13328.20356（setupODT.exe 版本 16.0.13328.20336）</span><span class="sxs-lookup"><span data-stu-id="5bd01-127">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="5bd01-128">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="5bd01-128">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="5bd01-129">为了防止混淆并更轻松地诊断安装错误，ODT 现在默认命名为 setupODT.exe。</span><span class="sxs-lookup"><span data-stu-id="5bd01-129">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="5bd01-130">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-130">October 29, 2020</span></span>
<span data-ttu-id="5bd01-131">版本 16.0.13328.20292（setup.exe 版本 16.0.13328.20290）</span><span class="sxs-lookup"><span data-stu-id="5bd01-131">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="5bd01-132">解决了使用 RemoveMSI 时，某些 Office 2007 产品可能意外阻止安装的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-132">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="5bd01-133">2020 年 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-133">October 14, 2020</span></span>
<span data-ttu-id="5bd01-134">版本 16.0.13231.20368（setup.exe 版本 16.0.13231.20350）</span><span class="sxs-lookup"><span data-stu-id="5bd01-134">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="5bd01-135">如果未指定频道，则所有产品都将默认使用每月频道</span><span class="sxs-lookup"><span data-stu-id="5bd01-135">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="5bd01-136">增强了从包含其他 DLL 的目录运行 ODT 时的安全性</span><span class="sxs-lookup"><span data-stu-id="5bd01-136">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="5bd01-137">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="5bd01-137">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="5bd01-138">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-138">June 9, 2020</span></span>

<span data-ttu-id="5bd01-139">版本 16.0.12827.20268（setup.exe 版本 16.0.12827.20258）</span><span class="sxs-lookup"><span data-stu-id="5bd01-139">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="5bd01-140">当前频道现在为未指定频道时的默认频道</span><span class="sxs-lookup"><span data-stu-id="5bd01-140">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="5bd01-141">增加了对每月企业频道的支持</span><span class="sxs-lookup"><span data-stu-id="5bd01-141">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="5bd01-142">增加了对新频道名称的支持</span><span class="sxs-lookup"><span data-stu-id="5bd01-142">Added support for new channel names</span></span>
- <span data-ttu-id="5bd01-143">其他复原功能可在可能的情况中继续安装（即使某些语言资源不可用）</span><span class="sxs-lookup"><span data-stu-id="5bd01-143">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="5bd01-144">MSIRemove 功能已展开，可删除 Office 2007 产品</span><span class="sxs-lookup"><span data-stu-id="5bd01-144">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="5bd01-145">MSIRemove 功能已展开，可删除访问数据库引擎</span><span class="sxs-lookup"><span data-stu-id="5bd01-145">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="5bd01-146">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-146">April 15, 2020</span></span>

<span data-ttu-id="5bd01-147">版本 16.0.12624.20320 （setup.exe 版本 16.0.12624.20290）</span><span class="sxs-lookup"><span data-stu-id="5bd01-147">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="5bd01-148">增加了对 Windows 7 已停用 Office 版本的支持。</span><span class="sxs-lookup"><span data-stu-id="5bd01-148">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="5bd01-149">修复了自定义设置可能无法按预期应用的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-149">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="5bd01-150">修复了可能意外下载无关 .cat 文件的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-150">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="5bd01-151">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-151">January 16, 2020</span></span>

<span data-ttu-id="5bd01-152">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="5bd01-152">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="5bd01-153">修复了在已安装多个语言的情况下 Office 安装 UI 可能显示为不正确的语言的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-153">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="5bd01-154">修复了在已安装某些校对工具包的情况下 Office 安装可能意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-154">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="5bd01-155">增加了以下支持：支持选择性地控制 [Microsoft 必应搜索功能](https://go.microsoft.com/fwlink/p/?linkid=2109345)的初始部署</span><span class="sxs-lookup"><span data-stu-id="5bd01-155">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="5bd01-156">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-156">October 31, 2019</span></span>

<span data-ttu-id="5bd01-157">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="5bd01-157">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="5bd01-158">修复了一个问题，使 Skype for Business Basic 2019 能够随附 2019 永久企业批量许可产品一并安装</span><span class="sxs-lookup"><span data-stu-id="5bd01-158">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="5bd01-159">修复了当使用代理时可能导致 ODT 下载模式在某些情况下意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="5bd01-159">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="5bd01-160">提供了使 ODT 下载模式可使用端口 80 以外的端口通过 HTTP 下载的新功能</span><span class="sxs-lookup"><span data-stu-id="5bd01-160">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="5bd01-161">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-161">July 10, 2019</span></span>

<span data-ttu-id="5bd01-162">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="5bd01-162">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="5bd01-163">现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。</span><span class="sxs-lookup"><span data-stu-id="5bd01-163">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="5bd01-164">现已开始支持从 MSI 升级时对独立产品进行条件安装。</span><span class="sxs-lookup"><span data-stu-id="5bd01-164">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="5bd01-165">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-165">April 23, 2019</span></span>

<span data-ttu-id="5bd01-166">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="5bd01-166">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="5bd01-167">已修复 RemoveMSI=True 清理相关注册表设置的 bug。</span><span class="sxs-lookup"><span data-stu-id="5bd01-167">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="5bd01-168">更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。</span><span class="sxs-lookup"><span data-stu-id="5bd01-168">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="5bd01-169">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-169">April 16 2019</span></span>

<span data-ttu-id="5bd01-170">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="5bd01-170">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="5bd01-171">支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。</span><span class="sxs-lookup"><span data-stu-id="5bd01-171">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="5bd01-172">更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="5bd01-172">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="5bd01-173">MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。</span><span class="sxs-lookup"><span data-stu-id="5bd01-173">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="5bd01-174">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-174">March 13, 2019</span></span>

<span data-ttu-id="5bd01-175">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="5bd01-175">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="5bd01-176">改进了升级和迁移方案。</span><span class="sxs-lookup"><span data-stu-id="5bd01-176">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="5bd01-177">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="5bd01-177">January 14, 2019</span></span>

<span data-ttu-id="5bd01-178">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="5bd01-178">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="5bd01-179">对部署配置改进了日志记录和遥测。</span><span class="sxs-lookup"><span data-stu-id="5bd01-179">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="5bd01-180">相关链接</span><span class="sxs-lookup"><span data-stu-id="5bd01-180">Related links</span></span>

[<span data-ttu-id="5bd01-181">ODT 下载中心</span><span class="sxs-lookup"><span data-stu-id="5bd01-181">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)