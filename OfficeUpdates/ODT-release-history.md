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
ms.openlocfilehash: a1553a3f08a254c9c177fec88073073c34a3427c
ms.sourcegitcommit: 413694d561d367e93ad51c9be41495ad09a24af3
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/23/2020
ms.locfileid: "49385478"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="bcffa-103">Office 部署工具的发布历史记录</span><span class="sxs-lookup"><span data-stu-id="bcffa-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="bcffa-104">Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Microsoft 365 应用版），并将它部署到客户端计算机。</span><span class="sxs-lookup"><span data-stu-id="bcffa-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="bcffa-p101">使用 ODT，可更好地控制 Office 安装：可以定义要安装哪些产品和语言、应该如何更新这些产品以及是否向用户显示安装体验。若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="bcffa-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="bcffa-108">**支持的操作系统**：Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="bcffa-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="bcffa-109">**安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="bcffa-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="bcffa-110">下载 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="bcffa-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-23-2020"></a><span data-ttu-id="bcffa-111">2020 年 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-111">November 23, 2020</span></span>
<span data-ttu-id="bcffa-112">版本 16.0.13328.20420（setup.exe 版本 16.0.13328.20420）</span><span class="sxs-lookup"><span data-stu-id="bcffa-112">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="bcffa-113">已通过/download 模式修复未下载校对工具的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-113">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="bcffa-114">修复了/download 模式在普通用户中运行失败的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-114">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="bcffa-115">修复了在配置 XML 中指定 Version 属性导致在/download 模式下无法完全下载的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-115">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="bcffa-116">修复了提取时 Office 部署工具未命名为 "setup.exe" 的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-116">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="bcffa-117">修复了在配置 XML 中提供频道属性时的安装源优先次序方面的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-117">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="bcffa-118">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-118">November 10, 2020</span></span>
<span data-ttu-id="bcffa-119">版本 16.0.13328.20356（setupODT.exe 版本 16.0.13328.20336）</span><span class="sxs-lookup"><span data-stu-id="bcffa-119">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="bcffa-120">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="bcffa-120">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="bcffa-121">为了防止混淆并更轻松地诊断安装错误，ODT 现在默认命名为 setupODT.exe。</span><span class="sxs-lookup"><span data-stu-id="bcffa-121">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="bcffa-122">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-122">October 29, 2020</span></span>
<span data-ttu-id="bcffa-123">版本 16.0.13328.20292（setup.exe 版本 16.0.13328.20290）</span><span class="sxs-lookup"><span data-stu-id="bcffa-123">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="bcffa-124">解决了使用 RemoveMSI 时，某些 Office 2007 产品可能意外阻止安装的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-124">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="bcffa-125">2020 年 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-125">October 14, 2020</span></span>
<span data-ttu-id="bcffa-126">版本 16.0.13231.20368（setup.exe 版本 16.0.13231.20350）</span><span class="sxs-lookup"><span data-stu-id="bcffa-126">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="bcffa-127">如果未指定频道，则所有产品都将默认使用每月频道</span><span class="sxs-lookup"><span data-stu-id="bcffa-127">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="bcffa-128">增强了从包含其他 DLL 的目录运行 ODT 时的安全性</span><span class="sxs-lookup"><span data-stu-id="bcffa-128">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="bcffa-129">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="bcffa-129">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="bcffa-130">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-130">June 9, 2020</span></span>

<span data-ttu-id="bcffa-131">版本 16.0.12827.20268（setup.exe 版本 16.0.12827.20258）</span><span class="sxs-lookup"><span data-stu-id="bcffa-131">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="bcffa-132">当前频道现在为未指定频道时的默认频道</span><span class="sxs-lookup"><span data-stu-id="bcffa-132">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="bcffa-133">增加了对每月企业频道的支持</span><span class="sxs-lookup"><span data-stu-id="bcffa-133">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="bcffa-134">增加了对新频道名称的支持</span><span class="sxs-lookup"><span data-stu-id="bcffa-134">Added support for new channel names</span></span>
- <span data-ttu-id="bcffa-135">其他复原功能可在可能的情况中继续安装（即使某些语言资源不可用）</span><span class="sxs-lookup"><span data-stu-id="bcffa-135">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="bcffa-136">MSIRemove 功能已展开，可删除 Office 2007 产品</span><span class="sxs-lookup"><span data-stu-id="bcffa-136">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="bcffa-137">MSIRemove 功能已展开，可删除访问数据库引擎</span><span class="sxs-lookup"><span data-stu-id="bcffa-137">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="bcffa-138">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-138">April 15, 2020</span></span>

<span data-ttu-id="bcffa-139">版本 16.0.12624.20320 （setup.exe 版本 16.0.12624.20290）</span><span class="sxs-lookup"><span data-stu-id="bcffa-139">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="bcffa-140">增加了对 Windows 7 已停用 Office 版本的支持。</span><span class="sxs-lookup"><span data-stu-id="bcffa-140">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="bcffa-141">修复了自定义设置可能无法按预期应用的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-141">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="bcffa-142">修复了可能意外下载无关 .cat 文件的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-142">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="bcffa-143">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-143">January 16, 2020</span></span>

<span data-ttu-id="bcffa-144">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="bcffa-144">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="bcffa-145">修复了在已安装多个语言的情况下 Office 安装 UI 可能显示为不正确的语言的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-145">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="bcffa-146">修复了在已安装某些校对工具包的情况下 Office 安装可能意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-146">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="bcffa-147">增加了以下支持：支持选择性地控制 [Microsoft 必应搜索功能](https://go.microsoft.com/fwlink/p/?linkid=2109345)的初始部署</span><span class="sxs-lookup"><span data-stu-id="bcffa-147">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="bcffa-148">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-148">October 31, 2019</span></span>

<span data-ttu-id="bcffa-149">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="bcffa-149">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="bcffa-150">修复了一个问题，使 Skype for Business Basic 2019 能够随附 2019 永久企业批量许可产品一并安装</span><span class="sxs-lookup"><span data-stu-id="bcffa-150">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="bcffa-151">修复了当使用代理时可能导致 ODT 下载模式在某些情况下意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="bcffa-151">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="bcffa-152">提供了使 ODT 下载模式可使用端口 80 以外的端口通过 HTTP 下载的新功能</span><span class="sxs-lookup"><span data-stu-id="bcffa-152">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="bcffa-153">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-153">July 10, 2019</span></span>

<span data-ttu-id="bcffa-154">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="bcffa-154">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="bcffa-155">现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。</span><span class="sxs-lookup"><span data-stu-id="bcffa-155">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="bcffa-156">现已开始支持从 MSI 升级时对独立产品进行条件安装。</span><span class="sxs-lookup"><span data-stu-id="bcffa-156">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="bcffa-157">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-157">April 23, 2019</span></span>

<span data-ttu-id="bcffa-158">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="bcffa-158">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="bcffa-159">已修复 RemoveMSI=True 清理相关注册表设置的 bug。</span><span class="sxs-lookup"><span data-stu-id="bcffa-159">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="bcffa-160">更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。</span><span class="sxs-lookup"><span data-stu-id="bcffa-160">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="bcffa-161">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-161">April 16 2019</span></span>

<span data-ttu-id="bcffa-162">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="bcffa-162">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="bcffa-163">支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。</span><span class="sxs-lookup"><span data-stu-id="bcffa-163">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="bcffa-164">更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="bcffa-164">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="bcffa-165">MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。</span><span class="sxs-lookup"><span data-stu-id="bcffa-165">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="bcffa-166">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-166">March 13, 2019</span></span>

<span data-ttu-id="bcffa-167">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="bcffa-167">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="bcffa-168">改进了升级和迁移方案。</span><span class="sxs-lookup"><span data-stu-id="bcffa-168">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="bcffa-169">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="bcffa-169">January 14, 2019</span></span>

<span data-ttu-id="bcffa-170">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="bcffa-170">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="bcffa-171">对部署配置改进了日志记录和遥测。</span><span class="sxs-lookup"><span data-stu-id="bcffa-171">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="bcffa-172">相关链接</span><span class="sxs-lookup"><span data-stu-id="bcffa-172">Related links</span></span>

[<span data-ttu-id="bcffa-173">ODT 下载中心</span><span class="sxs-lookup"><span data-stu-id="bcffa-173">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)