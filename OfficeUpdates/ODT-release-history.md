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
ms.openlocfilehash: b0f53ad140880f7ef173efc544892d56f0658bb1
ms.sourcegitcommit: 917d87752cde322a74251b6d23b12815587d1e51
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/16/2019
ms.locfileid: "36444939"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="dd1c3-103">Office 部署工具的发布历史记录</span><span class="sxs-lookup"><span data-stu-id="dd1c3-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="dd1c3-104">Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Office 365 专业增强版），并将它部署到客户端计算机。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-104">The Office 2016 Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Office 365 ProPlus to your client computers.</span></span> 


<span data-ttu-id="dd1c3-105">使用 ODT，可以更全面地控制 Office 安装。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="dd1c3-106">可以定义安装了哪些产品和语言、应如何更新这些产品，以及是否向用户显示安装体验。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-106">The ODT gives you more control over an Office installation: you can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="dd1c3-107">若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](https://docs.microsoft.com/zh-CN/deployoffice/overview-of-the-office-2016-deployment-tool)。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/en-us/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="dd1c3-108">**支持的操作系统**：Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="dd1c3-108">The tool runs on Windows 10 , Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, and Windows Server 2012 R2.</span></span> 
 
 <span data-ttu-id="dd1c3-109">**安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-109">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="dd1c3-110">[下载 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span><span class="sxs-lookup"><span data-stu-id="dd1c3-110">Download the [Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="dd1c3-111">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="dd1c3-111">July 10, 2019</span></span>

<span data-ttu-id="dd1c3-112">版本 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="dd1c3-112">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="dd1c3-113">现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-113">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="dd1c3-114">现已开始支持从 MSI 升级时对独立产品进行条件安装。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-114">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="dd1c3-115">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="dd1c3-115">April 23, 2019</span></span>

<span data-ttu-id="dd1c3-116">版本 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="dd1c3-116">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="dd1c3-117">已修复 RemoveMSI=True 清理相关注册表设置的 bug。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-117">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="dd1c3-118">更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-118">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="dd1c3-119">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="dd1c3-119">April 16, 2019</span></span>

<span data-ttu-id="dd1c3-120">版本 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="dd1c3-120">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="dd1c3-121">支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-121">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="dd1c3-122">更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-122">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="dd1c3-123">MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-123">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="dd1c3-124">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="dd1c3-124">March 13, 2019</span></span>

<span data-ttu-id="dd1c3-125">版本 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="dd1c3-125">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="dd1c3-126">改进了升级和迁移方案。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-126">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="dd1c3-127">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="dd1c3-127">January 14, 2019</span></span>

<span data-ttu-id="dd1c3-128">版本 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="dd1c3-128">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="dd1c3-129">对部署配置改进了日志记录和遥测。</span><span class="sxs-lookup"><span data-stu-id="dd1c3-129">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="dd1c3-130">相关链接</span><span class="sxs-lookup"><span data-stu-id="dd1c3-130">Related links</span></span>

[<span data-ttu-id="dd1c3-131">ODT 发行说明</span><span class="sxs-lookup"><span data-stu-id="dd1c3-131">ODT Release notes</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)