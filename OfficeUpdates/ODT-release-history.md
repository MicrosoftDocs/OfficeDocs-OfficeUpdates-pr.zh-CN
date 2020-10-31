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
ms.openlocfilehash: f578849552bb4fda0198bad3651170923d0ceb35
ms.sourcegitcommit: b19297da26ce6f740f3e2c94ea8a6c5d4e2aaa75
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/30/2020
ms.locfileid: "48806790"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="de0cd-103">Office 部署工具的发布历史记录</span><span class="sxs-lookup"><span data-stu-id="de0cd-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="de0cd-104">Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Microsoft 365 应用），并将它部署到客户端计算机。</span><span class="sxs-lookup"><span data-stu-id="de0cd-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="de0cd-105">使用 ODT，可以更全面地控制 Office 安装。</span><span class="sxs-lookup"><span data-stu-id="de0cd-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="de0cd-106">可以定义安装了哪些产品和语言、应如何更新这些产品，以及是否向用户显示安装体验。</span><span class="sxs-lookup"><span data-stu-id="de0cd-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="de0cd-107">若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="de0cd-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="de0cd-108">**支持的操作系统** ：Windows 10、Windows 7、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="de0cd-108">**Supported Operating System** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="de0cd-109">**安装说明** ：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="de0cd-109">**Install Instructions** : Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="de0cd-110">下载 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="de0cd-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="october-29-2020"></a><span data-ttu-id="de0cd-111">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-111">October 29, 2020</span></span>
<span data-ttu-id="de0cd-112">版本 16.0.13328.20292（setup.exe 版本 16.0.13328.20290）</span><span class="sxs-lookup"><span data-stu-id="de0cd-112">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="de0cd-113">解决了使用 RemoveMSI 时，某些 Office 2007 产品可能意外阻止安装的问题</span><span class="sxs-lookup"><span data-stu-id="de0cd-113">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="de0cd-114">2020 年 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-114">October 14, 2020</span></span>
<span data-ttu-id="de0cd-115">版本 16.0.13231.20368（setup.exe 版本 16.0.13231.20350）</span><span class="sxs-lookup"><span data-stu-id="de0cd-115">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="de0cd-116">如果未指定频道，则所有产品都将默认使用每月频道</span><span class="sxs-lookup"><span data-stu-id="de0cd-116">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="de0cd-117">增强了从包含其他 DLL 的目录运行 ODT 时的安全性</span><span class="sxs-lookup"><span data-stu-id="de0cd-117">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="de0cd-118">可靠性和复原能力方面的改进</span><span class="sxs-lookup"><span data-stu-id="de0cd-118">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="de0cd-119">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-119">June 9, 2020</span></span>

<span data-ttu-id="de0cd-120">版本 16.0.12827.20268（setup.exe 版本 16.0.12827.20258）</span><span class="sxs-lookup"><span data-stu-id="de0cd-120">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="de0cd-121">当前频道现在为未指定频道时的默认频道</span><span class="sxs-lookup"><span data-stu-id="de0cd-121">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="de0cd-122">增加了对每月企业频道的支持</span><span class="sxs-lookup"><span data-stu-id="de0cd-122">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="de0cd-123">增加了对新频道名称的支持</span><span class="sxs-lookup"><span data-stu-id="de0cd-123">Added support for new channel names</span></span>
- <span data-ttu-id="de0cd-124">其他复原功能可在可能的情况中继续安装（即使某些语言资源不可用）</span><span class="sxs-lookup"><span data-stu-id="de0cd-124">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="de0cd-125">MSIRemove 功能已展开，可删除 Office 2007 产品</span><span class="sxs-lookup"><span data-stu-id="de0cd-125">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="de0cd-126">MSIRemove 功能已展开，可删除访问数据库引擎</span><span class="sxs-lookup"><span data-stu-id="de0cd-126">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="de0cd-127">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-127">April 15, 2020</span></span>

<span data-ttu-id="de0cd-128">版本 16.0.12624.20320 （setup.exe 版本 16.0.12624.20290）</span><span class="sxs-lookup"><span data-stu-id="de0cd-128">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="de0cd-129">增加了对 Windows 7 已停用 Office 版本的支持。</span><span class="sxs-lookup"><span data-stu-id="de0cd-129">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="de0cd-130">修复了自定义设置可能无法按预期应用的问题</span><span class="sxs-lookup"><span data-stu-id="de0cd-130">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="de0cd-131">修复了可能意外下载无关 .cat 文件的问题</span><span class="sxs-lookup"><span data-stu-id="de0cd-131">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="de0cd-132">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-132">January 16, 2020</span></span>

<span data-ttu-id="de0cd-133">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="de0cd-133">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="de0cd-134">修复了在已安装多个语言的情况下 Office 安装 UI 可能显示为不正确的语言的问题</span><span class="sxs-lookup"><span data-stu-id="de0cd-134">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="de0cd-135">修复了在已安装某些校对工具包的情况下 Office 安装可能意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="de0cd-135">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="de0cd-136">增加了以下支持：支持选择性地控制 [Microsoft 必应搜索功能](https://go.microsoft.com/fwlink/p/?linkid=2109345)的初始部署</span><span class="sxs-lookup"><span data-stu-id="de0cd-136">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="de0cd-137">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-137">October 31, 2019</span></span>

<span data-ttu-id="de0cd-138">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="de0cd-138">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="de0cd-139">修复了一个问题，使 Skype for Business Basic 2019 能够随附 2019 永久企业批量许可产品一并安装</span><span class="sxs-lookup"><span data-stu-id="de0cd-139">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="de0cd-140">修复了当使用代理时可能导致 ODT 下载模式在某些情况下意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="de0cd-140">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="de0cd-141">提供了使 ODT 下载模式可使用端口 80 以外的端口通过 HTTP 下载的新功能</span><span class="sxs-lookup"><span data-stu-id="de0cd-141">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="de0cd-142">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-142">July 10, 2019</span></span>

<span data-ttu-id="de0cd-143">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="de0cd-143">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="de0cd-144">现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。</span><span class="sxs-lookup"><span data-stu-id="de0cd-144">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="de0cd-145">现已开始支持从 MSI 升级时对独立产品进行条件安装。</span><span class="sxs-lookup"><span data-stu-id="de0cd-145">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="de0cd-146">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-146">April 23, 2019</span></span>

<span data-ttu-id="de0cd-147">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="de0cd-147">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="de0cd-148">已修复 RemoveMSI=True 清理相关注册表设置的 bug。</span><span class="sxs-lookup"><span data-stu-id="de0cd-148">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="de0cd-149">更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。</span><span class="sxs-lookup"><span data-stu-id="de0cd-149">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="de0cd-150">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-150">April 16 2019</span></span>

<span data-ttu-id="de0cd-151">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="de0cd-151">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="de0cd-152">支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。</span><span class="sxs-lookup"><span data-stu-id="de0cd-152">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="de0cd-153">更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="de0cd-153">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="de0cd-154">MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。</span><span class="sxs-lookup"><span data-stu-id="de0cd-154">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="de0cd-155">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-155">March 13, 2019</span></span>

<span data-ttu-id="de0cd-156">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="de0cd-156">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="de0cd-157">改进了升级和迁移方案。</span><span class="sxs-lookup"><span data-stu-id="de0cd-157">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="de0cd-158">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="de0cd-158">January 14, 2019</span></span>

<span data-ttu-id="de0cd-159">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="de0cd-159">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="de0cd-160">对部署配置改进了日志记录和遥测。</span><span class="sxs-lookup"><span data-stu-id="de0cd-160">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="de0cd-161">相关链接</span><span class="sxs-lookup"><span data-stu-id="de0cd-161">Related links</span></span>

[<span data-ttu-id="de0cd-162">ODT 下载中心</span><span class="sxs-lookup"><span data-stu-id="de0cd-162">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)