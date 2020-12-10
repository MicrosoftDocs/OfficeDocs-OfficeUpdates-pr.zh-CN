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
ms.openlocfilehash: 125f37f1fb4b21d2d63784e51703c1297d928f49
ms.sourcegitcommit: c7f7982f4d2d0d8db4fc4fbf961b79a03bc8b36e
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601407"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="23e41-103">Office 部署工具的发布历史记录</span><span class="sxs-lookup"><span data-stu-id="23e41-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="23e41-104">Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Microsoft 365 应用），并将它部署到客户端计算机。</span><span class="sxs-lookup"><span data-stu-id="23e41-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="23e41-105">使用 ODT，可以更全面地控制 Office 安装。</span><span class="sxs-lookup"><span data-stu-id="23e41-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="23e41-106">可以定义安装了哪些产品和语言、应如何更新这些产品，以及是否向用户显示安装体验。</span><span class="sxs-lookup"><span data-stu-id="23e41-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="23e41-107">若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="23e41-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="23e41-108">**支持的操作系统**：Windows 10、Windows 7、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="23e41-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="23e41-109">**安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="23e41-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="23e41-110">下载 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="23e41-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="december-8-2020"></a><span data-ttu-id="23e41-111">2020 年 12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="23e41-111">December 8, 2020</span></span>
<span data-ttu-id="23e41-112">版本 16.0.13426.20308（setup.exe 版本 16.0.13426.20308）</span><span class="sxs-lookup"><span data-stu-id="23e41-112">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="23e41-113">已修复以下问题：如果设备具有从非永久 2019 通道安装的 Office 产品，则下载模式会阻止永久性的 2019 通道下载。</span><span class="sxs-lookup"><span data-stu-id="23e41-113">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="23e41-114">已修复以下问题：体系结构迁移将无法针对通过下载模式创建的本地源，该源已在配置 XML 中指定了显式版本。</span><span class="sxs-lookup"><span data-stu-id="23e41-114">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="23e41-115">2020 年 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="23e41-115">November 23, 2020</span></span>
<span data-ttu-id="23e41-116">版本 16.0.13328.20420（setup.exe 版本 16.0.13328.20420）</span><span class="sxs-lookup"><span data-stu-id="23e41-116">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="23e41-117">已修复未通过 /download 模式下载校对工具的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-117">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="23e41-118">已修复 /download 模式在普通用户中运行失败的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-118">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="23e41-119">已修复在配置 XML 中指定 Version 属性导致在 /download 模式下无法完全下载的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-119">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="23e41-120">已修复提取时 Office 部署工具未命名为 “setup.exe” 的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-120">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="23e41-121">已修复在配置 XML 中提供频道属性时的安装源优先次序方面的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-121">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="23e41-122">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="23e41-122">November 10, 2020</span></span>
<span data-ttu-id="23e41-123">版本 16.0.13328.20356（setupODT.exe 版本 16.0.13328.20336）</span><span class="sxs-lookup"><span data-stu-id="23e41-123">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="23e41-124">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="23e41-124">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="23e41-125">为了防止混淆并更轻松地诊断安装错误，ODT 现在默认命名为 setupODT.exe。</span><span class="sxs-lookup"><span data-stu-id="23e41-125">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="23e41-126">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="23e41-126">October 29, 2020</span></span>
<span data-ttu-id="23e41-127">版本 16.0.13328.20292（setup.exe 版本 16.0.13328.20290）</span><span class="sxs-lookup"><span data-stu-id="23e41-127">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="23e41-128">解决了使用 RemoveMSI 时，某些 Office 2007 产品可能意外阻止安装的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-128">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="23e41-129">2020 年 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="23e41-129">October 14, 2020</span></span>
<span data-ttu-id="23e41-130">版本 16.0.13231.20368（setup.exe 版本 16.0.13231.20350）</span><span class="sxs-lookup"><span data-stu-id="23e41-130">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="23e41-131">如果未指定频道，则所有产品都将默认使用每月频道</span><span class="sxs-lookup"><span data-stu-id="23e41-131">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="23e41-132">增强了从包含其他 DLL 的目录运行 ODT 时的安全性</span><span class="sxs-lookup"><span data-stu-id="23e41-132">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="23e41-133">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="23e41-133">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="23e41-134">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="23e41-134">June 9, 2020</span></span>

<span data-ttu-id="23e41-135">版本 16.0.12827.20268（setup.exe 版本 16.0.12827.20258）</span><span class="sxs-lookup"><span data-stu-id="23e41-135">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="23e41-136">当前频道现在为未指定频道时的默认频道</span><span class="sxs-lookup"><span data-stu-id="23e41-136">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="23e41-137">增加了对每月企业频道的支持</span><span class="sxs-lookup"><span data-stu-id="23e41-137">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="23e41-138">增加了对新频道名称的支持</span><span class="sxs-lookup"><span data-stu-id="23e41-138">Added support for new channel names</span></span>
- <span data-ttu-id="23e41-139">其他复原功能可在可能的情况中继续安装（即使某些语言资源不可用）</span><span class="sxs-lookup"><span data-stu-id="23e41-139">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="23e41-140">MSIRemove 功能已展开，可删除 Office 2007 产品</span><span class="sxs-lookup"><span data-stu-id="23e41-140">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="23e41-141">MSIRemove 功能已展开，可删除访问数据库引擎</span><span class="sxs-lookup"><span data-stu-id="23e41-141">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="23e41-142">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="23e41-142">April 15, 2020</span></span>

<span data-ttu-id="23e41-143">版本 16.0.12624.20320 （setup.exe 版本 16.0.12624.20290）</span><span class="sxs-lookup"><span data-stu-id="23e41-143">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="23e41-144">增加了对 Windows 7 已停用 Office 版本的支持。</span><span class="sxs-lookup"><span data-stu-id="23e41-144">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="23e41-145">修复了自定义设置可能无法按预期应用的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-145">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="23e41-146">修复了可能意外下载无关 .cat 文件的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-146">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="23e41-147">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="23e41-147">January 16, 2020</span></span>

<span data-ttu-id="23e41-148">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="23e41-148">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="23e41-149">修复了在已安装多个语言的情况下 Office 安装 UI 可能显示为不正确的语言的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-149">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="23e41-150">修复了在已安装某些校对工具包的情况下 Office 安装可能意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-150">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="23e41-151">增加了以下支持：支持选择性地控制 [Microsoft 必应搜索功能](https://go.microsoft.com/fwlink/p/?linkid=2109345)的初始部署</span><span class="sxs-lookup"><span data-stu-id="23e41-151">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="23e41-152">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="23e41-152">October 31, 2019</span></span>

<span data-ttu-id="23e41-153">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="23e41-153">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="23e41-154">修复了一个问题，使 Skype for Business Basic 2019 能够随附 2019 永久企业批量许可产品一并安装</span><span class="sxs-lookup"><span data-stu-id="23e41-154">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="23e41-155">修复了当使用代理时可能导致 ODT 下载模式在某些情况下意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="23e41-155">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="23e41-156">提供了使 ODT 下载模式可使用端口 80 以外的端口通过 HTTP 下载的新功能</span><span class="sxs-lookup"><span data-stu-id="23e41-156">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="23e41-157">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="23e41-157">July 10, 2019</span></span>

<span data-ttu-id="23e41-158">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="23e41-158">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="23e41-159">现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。</span><span class="sxs-lookup"><span data-stu-id="23e41-159">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="23e41-160">现已开始支持从 MSI 升级时对独立产品进行条件安装。</span><span class="sxs-lookup"><span data-stu-id="23e41-160">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="23e41-161">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="23e41-161">April 23, 2019</span></span>

<span data-ttu-id="23e41-162">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="23e41-162">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="23e41-163">已修复 RemoveMSI=True 清理相关注册表设置的 bug。</span><span class="sxs-lookup"><span data-stu-id="23e41-163">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="23e41-164">更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。</span><span class="sxs-lookup"><span data-stu-id="23e41-164">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="23e41-165">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="23e41-165">April 16 2019</span></span>

<span data-ttu-id="23e41-166">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="23e41-166">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="23e41-167">支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。</span><span class="sxs-lookup"><span data-stu-id="23e41-167">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="23e41-168">更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="23e41-168">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="23e41-169">MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。</span><span class="sxs-lookup"><span data-stu-id="23e41-169">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="23e41-170">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="23e41-170">March 13, 2019</span></span>

<span data-ttu-id="23e41-171">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="23e41-171">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="23e41-172">改进了升级和迁移方案。</span><span class="sxs-lookup"><span data-stu-id="23e41-172">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="23e41-173">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="23e41-173">January 14, 2019</span></span>

<span data-ttu-id="23e41-174">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="23e41-174">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="23e41-175">对部署配置改进了日志记录和遥测。</span><span class="sxs-lookup"><span data-stu-id="23e41-175">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="23e41-176">相关链接</span><span class="sxs-lookup"><span data-stu-id="23e41-176">Related links</span></span>

[<span data-ttu-id="23e41-177">ODT 下载中心</span><span class="sxs-lookup"><span data-stu-id="23e41-177">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)