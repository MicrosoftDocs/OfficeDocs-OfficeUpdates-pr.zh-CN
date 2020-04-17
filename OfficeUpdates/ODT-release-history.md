---
title: Office 部署工具 (ODT) 的发布历史记录
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 为 IT 专业人士提供 Office 部署工具 (ODT) 的发布历史记录
ms.openlocfilehash: b9cb0e347e785f14c1dd23ae9cfbcaa327ce4873
ms.sourcegitcommit: fab2c3d8c42b3e2fde49853068c834f96ccbf105
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/15/2020
ms.locfileid: "43521210"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="7612d-103">Office 部署工具的发布历史记录</span><span class="sxs-lookup"><span data-stu-id="7612d-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="7612d-104">Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Office 365 专业增强版），并将它部署到客户端计算机。</span><span class="sxs-lookup"><span data-stu-id="7612d-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="7612d-105">使用 ODT，可以更全面地控制 Office 安装。</span><span class="sxs-lookup"><span data-stu-id="7612d-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="7612d-106">可以定义安装了哪些产品和语言、应如何更新这些产品，以及是否向用户显示安装体验。</span><span class="sxs-lookup"><span data-stu-id="7612d-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="7612d-107">若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="7612d-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="7612d-108">**支持的操作系统**：Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="7612d-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="7612d-109">**安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="7612d-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="7612d-110">下载 Office 部署工具</span><span class="sxs-lookup"><span data-stu-id="7612d-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="april-15-2020"></a><span data-ttu-id="7612d-111">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7612d-111">April 15, 2020</span></span>

<span data-ttu-id="7612d-112">版本 16.0.12624.20320 （setup.exe 版本 16.0.12624.20290）</span><span class="sxs-lookup"><span data-stu-id="7612d-112">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="7612d-113">增加了对 Windows 7 已停用 Office 版本的支持。</span><span class="sxs-lookup"><span data-stu-id="7612d-113">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="7612d-114">修复了自定义设置可能无法按预期应用的问题</span><span class="sxs-lookup"><span data-stu-id="7612d-114">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="7612d-115">修复了可能意外下载无关 .cat 文件的问题</span><span class="sxs-lookup"><span data-stu-id="7612d-115">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="7612d-116">2020 年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="7612d-116">January 16, 2020</span></span>

<span data-ttu-id="7612d-117">版本 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="7612d-117">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="7612d-118">修复了在已安装多个语言的情况下 Office 安装 UI 可能显示为不正确的语言的问题</span><span class="sxs-lookup"><span data-stu-id="7612d-118">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="7612d-119">修复了在已安装某些校对工具包的情况下 Office 安装可能意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="7612d-119">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="7612d-120">增加了以下支持：支持选择性地控制 [Microsoft 必应搜索功能](https://go.microsoft.com/fwlink/p/?linkid=2109345)的初始部署</span><span class="sxs-lookup"><span data-stu-id="7612d-120">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="7612d-121">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="7612d-121">October 31, 2019</span></span>

<span data-ttu-id="7612d-122">版本 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="7612d-122">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="7612d-123">修复了一个问题，使 Skype for Business Basic 2019 能够随附 2019 永久企业批量许可产品一并安装</span><span class="sxs-lookup"><span data-stu-id="7612d-123">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="7612d-124">修复了当使用代理时可能导致 ODT 下载模式在某些情况下意外失败的问题</span><span class="sxs-lookup"><span data-stu-id="7612d-124">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="7612d-125">提供了使 ODT 下载模式可使用端口 80 以外的端口通过 HTTP 下载的新功能</span><span class="sxs-lookup"><span data-stu-id="7612d-125">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="7612d-126">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7612d-126">July 10, 2019</span></span>

<span data-ttu-id="7612d-127">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="7612d-127">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="7612d-128">现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。</span><span class="sxs-lookup"><span data-stu-id="7612d-128">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="7612d-129">现已开始支持从 MSI 升级时对独立产品进行条件安装。</span><span class="sxs-lookup"><span data-stu-id="7612d-129">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="7612d-130">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="7612d-130">April 23, 2019</span></span>

<span data-ttu-id="7612d-131">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="7612d-131">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="7612d-132">已修复 RemoveMSI=True 清理相关注册表设置的 bug。</span><span class="sxs-lookup"><span data-stu-id="7612d-132">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="7612d-133">更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。</span><span class="sxs-lookup"><span data-stu-id="7612d-133">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="7612d-134">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="7612d-134">April 16 2019</span></span>

<span data-ttu-id="7612d-135">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="7612d-135">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="7612d-136">支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。</span><span class="sxs-lookup"><span data-stu-id="7612d-136">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="7612d-137">更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="7612d-137">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="7612d-138">MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。</span><span class="sxs-lookup"><span data-stu-id="7612d-138">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="7612d-139">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7612d-139">March 13, 2019</span></span>

<span data-ttu-id="7612d-140">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="7612d-140">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="7612d-141">改进了升级和迁移方案。</span><span class="sxs-lookup"><span data-stu-id="7612d-141">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="7612d-142">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7612d-142">January 14, 2019</span></span>

<span data-ttu-id="7612d-143">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="7612d-143">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="7612d-144">对部署配置改进了日志记录和遥测。</span><span class="sxs-lookup"><span data-stu-id="7612d-144">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="7612d-145">相关链接</span><span class="sxs-lookup"><span data-stu-id="7612d-145">Related links</span></span>

[<span data-ttu-id="7612d-146">ODT 下载中心</span><span class="sxs-lookup"><span data-stu-id="7612d-146">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)