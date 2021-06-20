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
ms.openlocfilehash: ef130b3602d1f7d8c664167655cba09eb45b8e52
ms.sourcegitcommit: b7b3ebab7fc6b8424482107f650f6bb528afd8f7
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/19/2021
ms.locfileid: "53022095"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="feacb-103">Office 部署工具的发布历史记录</span><span class="sxs-lookup"><span data-stu-id="feacb-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="feacb-104">Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Microsoft 365 应用），并将它部署到客户端计算机。</span><span class="sxs-lookup"><span data-stu-id="feacb-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="feacb-p101">使用 ODT，可更好地控制 Office 安装：可以定义要安装哪些产品和语言、应该如何更新这些产品以及是否向用户显示安装体验。若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="feacb-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="feacb-108">**支持的操作系统**：Windows 10、Windows 7、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="feacb-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="feacb-109">**安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="feacb-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="feacb-110">下载 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="feacb-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="june-17-2021"></a><span data-ttu-id="feacb-111">2021 年 6 月 17 日</span><span class="sxs-lookup"><span data-stu-id="feacb-111">June 17, 2021</span></span>
<span data-ttu-id="feacb-112">版本 16.0.14026.20236（setup.exe 版本 16.0.14026.20236）</span><span class="sxs-lookup"><span data-stu-id="feacb-112">Version 16.0.14026.20306 (setup.exe version 16.0.14026.20306)</span></span>
- <span data-ttu-id="feacb-113">修复了使用 MatchOS 语言选项的操作在某些操作系统配置中失败的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-113">Fixes an issue where operations using the MatchOS language option were failing for some OS configurations</span></span>


## <a name="june-7-2021"></a><span data-ttu-id="feacb-114">2021 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="feacb-114">June 7, 2021</span></span>
<span data-ttu-id="feacb-115">版本 16.0.14026.20254 (setup.exe 版本 16.0.14026.20252)</span><span class="sxs-lookup"><span data-stu-id="feacb-115">Version 16.0.14026.20254 (setup.exe version 16.0.14026.20252)</span></span>
- <span data-ttu-id="feacb-116">ARM 平台的可靠性修补程序</span><span class="sxs-lookup"><span data-stu-id="feacb-116">Reliability fixes for ARM platforms</span></span>


## <a name="may-10-2021"></a><span data-ttu-id="feacb-117">2021 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="feacb-117">May 10, 2021</span></span>
<span data-ttu-id="feacb-118">版本 16.0.13929.20296（setup.exe 版本 16.0.13929.20238）</span><span class="sxs-lookup"><span data-stu-id="feacb-118">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span></span>
- <span data-ttu-id="feacb-119">修复了如果配置文件同时包含 MigrateArch 和 RemoveMSI，则/configue 模式可能失败的问题。</span><span class="sxs-lookup"><span data-stu-id="feacb-119">Fixed an issue where /configure mode may fail if a configuration file includes both MigrateArch and RemoveMSI</span></span>
- <span data-ttu-id="feacb-120">其他可靠性改进</span><span class="sxs-lookup"><span data-stu-id="feacb-120">Additional reliability improvements</span></span>

## <a name="april-13-2021"></a><span data-ttu-id="feacb-121">2021 年 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="feacb-121">April 13, 2021</span></span>
<span data-ttu-id="feacb-122">版本 16.0.13901.20336（setup.exe 版本 16.0.13901.20328）</span><span class="sxs-lookup"><span data-stu-id="feacb-122">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span></span>
- <span data-ttu-id="feacb-123">在已安装 Office 的设备上运行的配置操作的可靠性修补程序</span><span class="sxs-lookup"><span data-stu-id="feacb-123">Reliability fixes for configure operations that are run on devices with Office already installed</span></span>
- <span data-ttu-id="feacb-124">可在某些方案中避免显示重复的进度 UI</span><span class="sxs-lookup"><span data-stu-id="feacb-124">Fixes to avoid showing duplicate progress UI in some scenarios</span></span>
- <span data-ttu-id="feacb-125">改进 UI 中显示的错误代码准确度</span><span class="sxs-lookup"><span data-stu-id="feacb-125">Improvements to error code accuracy shown in UI</span></span>
- <span data-ttu-id="feacb-126">ARM 平台的可靠性修补程序</span><span class="sxs-lookup"><span data-stu-id="feacb-126">Reliability fixes for ARM platforms</span></span>

## <a name="march-23-2021"></a><span data-ttu-id="feacb-127">2021 年 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="feacb-127">March 23, 2021</span></span>
<span data-ttu-id="feacb-128">版本 16.0.13801.20360（setup.exe 版本 16.0.13801.20340）</span><span class="sxs-lookup"><span data-stu-id="feacb-128">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="feacb-129">对即将发布的 Office 产品所做的更改</span><span class="sxs-lookup"><span data-stu-id="feacb-129">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="feacb-130">ARM 平台的可靠性修补程序</span><span class="sxs-lookup"><span data-stu-id="feacb-130">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="feacb-131">2021 年 2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="feacb-131">February 25, 2021</span></span>
<span data-ttu-id="feacb-132">版本 16.0.13628.20476（setup.exe 版本 16.0.13628.20462）</span><span class="sxs-lookup"><span data-stu-id="feacb-132">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="feacb-133">修复了无法验证指定数十种语言的 configuration.xml 文件的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-133">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="feacb-134">修复了迁移存档方案中不遵守 FORCEAPPSHUTDOWN 属性的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-134">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="feacb-135">修复了在 configuration.xml 中指定 2 个或更多 PIDKEY 属性无法安装 PIDKey 的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-135">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="feacb-136">2021 年 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="feacb-136">February 9, 2021</span></span>
<span data-ttu-id="feacb-137">版本 16.0.13628.20274（setup.exe 版本 16.0.13628.20246）</span><span class="sxs-lookup"><span data-stu-id="feacb-137">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="feacb-138">添加了对 Windows 8.0 上不支持的安装发出警告验证</span><span class="sxs-lookup"><span data-stu-id="feacb-138">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="feacb-139">ARM64 设备的可靠性修补程序</span><span class="sxs-lookup"><span data-stu-id="feacb-139">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="feacb-140">2021 年 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="feacb-140">January 12, 2021</span></span>
<span data-ttu-id="feacb-141">版本 16.0.13530.20376 （setup.exe 版本16.0.13530.20334）</span><span class="sxs-lookup"><span data-stu-id="feacb-141">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="feacb-142">修复了产品注册损坏或非标准产品注册可能导致RemoveMSI操作失败的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-142">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="feacb-143">2020 年 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="feacb-143">December 21, 2020</span></span>
<span data-ttu-id="feacb-144">版本 16.0.13426.20370（setup.exe 版本 16.0.13426.20352）</span><span class="sxs-lookup"><span data-stu-id="feacb-144">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="feacb-145">修正了 PerpetualVL2019 频道的 ProofingTool 本地源安装失败的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-145">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="feacb-146">修复了一个问题，以确保在向现有安装中添加其他非全文 Office 语言的产品时，即点即用客户端会尝试自我更新</span><span class="sxs-lookup"><span data-stu-id="feacb-146">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="feacb-147">2020 年 12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="feacb-147">December 8, 2020</span></span>
<span data-ttu-id="feacb-148">版本 16.0.13426.20308（setup.exe 版本 16.0.13426.20308）</span><span class="sxs-lookup"><span data-stu-id="feacb-148">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="feacb-149">已修复以下问题：如果设备具有从非永久 2019 通道安装的 Office 产品，则下载模式会阻止永久性的 2019 通道下载。</span><span class="sxs-lookup"><span data-stu-id="feacb-149">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="feacb-150">已修复以下问题：体系结构迁移将无法针对通过下载模式创建的本地源，该源已在配置 XML 中指定了显式版本。</span><span class="sxs-lookup"><span data-stu-id="feacb-150">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="feacb-151">2020 年 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="feacb-151">November 23, 2020</span></span>
<span data-ttu-id="feacb-152">版本 16.0.13328.20420（setup.exe 版本 16.0.13328.20420）</span><span class="sxs-lookup"><span data-stu-id="feacb-152">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="feacb-153">已修复未通过 /download 模式下载校对工具的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-153">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="feacb-154">已修复 /download 模式在普通用户中运行失败的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-154">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="feacb-155">已修复在配置 XML 中指定 Version 属性导致在 /download 模式下无法完全下载的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-155">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="feacb-156">已修复提取时 Office 部署工具未命名为 “setup.exe” 的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-156">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="feacb-157">已修复在配置 XML 中提供频道属性时的安装源优先次序方面的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-157">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="feacb-158">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="feacb-158">November 10, 2020</span></span>
<span data-ttu-id="feacb-159">版本 16.0.13328.20356（setupODT.exe 版本 16.0.13328.20336）</span><span class="sxs-lookup"><span data-stu-id="feacb-159">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="feacb-160">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="feacb-160">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="feacb-161">为了防止混淆并更轻松地诊断安装错误，ODT 现在默认命名为 setupODT.exe。</span><span class="sxs-lookup"><span data-stu-id="feacb-161">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="feacb-162">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="feacb-162">October 29, 2020</span></span>
<span data-ttu-id="feacb-163">版本 16.0.13328.20292（setup.exe 版本 16.0.13328.20290）</span><span class="sxs-lookup"><span data-stu-id="feacb-163">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="feacb-164">解决了使用 RemoveMSI 时，某些 Office 2007 产品可能意外阻止安装的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-164">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="feacb-165">2020 年 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="feacb-165">October 14, 2020</span></span>
<span data-ttu-id="feacb-166">版本 16.0.13231.20368（setup.exe 版本 16.0.13231.20350）</span><span class="sxs-lookup"><span data-stu-id="feacb-166">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="feacb-167">如果未指定频道，则所有产品都将默认使用每月频道</span><span class="sxs-lookup"><span data-stu-id="feacb-167">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="feacb-168">增强了从包含其他 DLL 的目录运行 ODT 时的安全性</span><span class="sxs-lookup"><span data-stu-id="feacb-168">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="feacb-169">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="feacb-169">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="feacb-170">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="feacb-170">June 9, 2020</span></span>

<span data-ttu-id="feacb-171">版本 16.0.12827.20268（setup.exe 版本 16.0.12827.20258）</span><span class="sxs-lookup"><span data-stu-id="feacb-171">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="feacb-172">当前频道现在为未指定频道时的默认频道</span><span class="sxs-lookup"><span data-stu-id="feacb-172">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="feacb-173">增加了对每月企业频道的支持</span><span class="sxs-lookup"><span data-stu-id="feacb-173">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="feacb-174">增加了对新频道名称的支持</span><span class="sxs-lookup"><span data-stu-id="feacb-174">Added support for new channel names</span></span>
- <span data-ttu-id="feacb-175">其他复原功能可在可能的情况中继续安装（即使某些语言资源不可用）</span><span class="sxs-lookup"><span data-stu-id="feacb-175">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="feacb-176">MSIRemove 功能已展开，可删除 Office 2007 产品</span><span class="sxs-lookup"><span data-stu-id="feacb-176">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="feacb-177">MSIRemove 功能已展开，可删除访问数据库引擎</span><span class="sxs-lookup"><span data-stu-id="feacb-177">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="feacb-178">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="feacb-178">April 15, 2020</span></span>

<span data-ttu-id="feacb-179">版本 16.0.12624.20320 （setup.exe 版本 16.0.12624.20290）</span><span class="sxs-lookup"><span data-stu-id="feacb-179">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="feacb-180">增加了对 Windows 7 已停用 Office 版本的支持。</span><span class="sxs-lookup"><span data-stu-id="feacb-180">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="feacb-181">修复了自定义设置可能无法按预期应用的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-181">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="feacb-182">修复了可能意外下载无关 .cat 文件的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-182">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="feacb-183">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="feacb-183">January 16, 2020</span></span>

<span data-ttu-id="feacb-184">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="feacb-184">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="feacb-185">修复了在已安装多个语言的情况下 Office 安装 UI 可能显示为不正确的语言的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-185">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="feacb-186">修复了在已安装某些校对工具包的情况下 Office 安装可能意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-186">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="feacb-187">增加了以下支持：支持选择性地控制 [Microsoft 必应搜索功能](/deployoffice/microsoft-search-bing)的初始部署</span><span class="sxs-lookup"><span data-stu-id="feacb-187">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="feacb-188">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="feacb-188">October 31, 2019</span></span>

<span data-ttu-id="feacb-189">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="feacb-189">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="feacb-190">修复了一个问题，使 Skype for Business Basic 2019 能够随附 2019 永久企业批量许可产品一并安装</span><span class="sxs-lookup"><span data-stu-id="feacb-190">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="feacb-191">修复了当使用代理时可能导致 ODT 下载模式在某些情况下意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="feacb-191">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="feacb-192">提供了使 ODT 下载模式可使用端口 80 以外的端口通过 HTTP 下载的新功能</span><span class="sxs-lookup"><span data-stu-id="feacb-192">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="feacb-193">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="feacb-193">July 10, 2019</span></span>

<span data-ttu-id="feacb-194">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="feacb-194">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="feacb-195">现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。</span><span class="sxs-lookup"><span data-stu-id="feacb-195">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="feacb-196">现已开始支持从 MSI 升级时对独立产品进行条件安装。</span><span class="sxs-lookup"><span data-stu-id="feacb-196">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="feacb-197">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="feacb-197">April 23, 2019</span></span>

<span data-ttu-id="feacb-198">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="feacb-198">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="feacb-199">已修复 RemoveMSI=True 清理相关注册表设置的 bug。</span><span class="sxs-lookup"><span data-stu-id="feacb-199">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="feacb-200">更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。</span><span class="sxs-lookup"><span data-stu-id="feacb-200">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="feacb-201">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="feacb-201">April 16 2019</span></span>

<span data-ttu-id="feacb-202">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="feacb-202">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="feacb-203">支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。</span><span class="sxs-lookup"><span data-stu-id="feacb-203">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="feacb-204">更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="feacb-204">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="feacb-205">MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。</span><span class="sxs-lookup"><span data-stu-id="feacb-205">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="feacb-206">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="feacb-206">March 13, 2019</span></span>

<span data-ttu-id="feacb-207">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="feacb-207">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="feacb-208">改进了升级和迁移方案。</span><span class="sxs-lookup"><span data-stu-id="feacb-208">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="feacb-209">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="feacb-209">January 14, 2019</span></span>

<span data-ttu-id="feacb-210">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="feacb-210">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="feacb-211">对部署配置改进了日志记录和遥测。</span><span class="sxs-lookup"><span data-stu-id="feacb-211">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="feacb-212">相关链接</span><span class="sxs-lookup"><span data-stu-id="feacb-212">Related links</span></span>

[<span data-ttu-id="feacb-213">ODT 下载中心</span><span class="sxs-lookup"><span data-stu-id="feacb-213">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)