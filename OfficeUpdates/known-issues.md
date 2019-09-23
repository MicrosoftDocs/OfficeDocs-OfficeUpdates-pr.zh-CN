---
title: Office 365 专业增强版已知问题
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: 提供有关 Office 365 专业增强版已知问题的信息
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068048"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="98de4-103">Office 365 专业增强版已知问题</span><span class="sxs-lookup"><span data-stu-id="98de4-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="98de4-104">这些已知问题提供了 2019 年 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 Business 的每月频道、SACT 和 SAC 更新中所包含的非安全更新的相关信息。</span><span class="sxs-lookup"><span data-stu-id="98de4-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="98de4-105">下表简要介绍了当前处于活动状态的问题以及已解决的问题。</span><span class="sxs-lookup"><span data-stu-id="98de4-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="98de4-106">我们将用正在调查的重要问题来更新下表。</span><span class="sxs-lookup"><span data-stu-id="98de4-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="98de4-107">此列表并不全面。</span><span class="sxs-lookup"><span data-stu-id="98de4-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="98de4-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="98de4-108">September 10, 2019</span></span>

|<span data-ttu-id="98de4-109">摘要</span><span class="sxs-lookup"><span data-stu-id="98de4-109">Summary</span></span>|<span data-ttu-id="98de4-110">正在调查</span><span class="sxs-lookup"><span data-stu-id="98de4-110">Investigating</span></span>|<span data-ttu-id="98de4-111">已解决</span><span class="sxs-lookup"><span data-stu-id="98de4-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="98de4-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="98de4-112">**Outlook**</span></span>
<span data-ttu-id="98de4-113">发现了使文件无法保存到 WebDAV 位置的问题。</span><span class="sxs-lookup"><span data-stu-id="98de4-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="98de4-114">每月版本 1909</span><span class="sxs-lookup"><span data-stu-id="98de4-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="98de4-115">**Project**</span><span class="sxs-lookup"><span data-stu-id="98de4-115">**Project**</span></span>
<span data-ttu-id="98de4-116">以如下方案为例。</span><span class="sxs-lookup"><span data-stu-id="98de4-116">Consider the following scenario.</span></span> <span data-ttu-id="98de4-117">打开项目。</span><span class="sxs-lookup"><span data-stu-id="98de4-117">You open a project.</span></span> <span data-ttu-id="98de4-118">单击“文件”菜单，单击“导出”，然后单击“创建 PDF/XPS”按钮。</span><span class="sxs-lookup"><span data-stu-id="98de4-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="98de4-119">在“浏览”对话框中，输入文件名，然后单击“确定”。</span><span class="sxs-lookup"><span data-stu-id="98de4-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="98de4-120">在这种情况下，你会发现未创建 XPS 文件的 PDF。</span><span class="sxs-lookup"><span data-stu-id="98de4-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="98de4-121">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="98de4-121">SAC Version 1902</span></span>||
|<span data-ttu-id="98de4-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="98de4-122">**Word**</span></span>
<span data-ttu-id="98de4-123">发现了用户打开文件时可能遇到的问题。</span><span class="sxs-lookup"><span data-stu-id="98de4-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="98de4-124">每月版本 1908</span><span class="sxs-lookup"><span data-stu-id="98de4-124">Monthly Version 1908</span></span>||
<span data-ttu-id="98de4-125">对于由 OneDrive 同步引擎同步的 Office 文件，“保存”和“另存为”时将不再验证文档元数据（例如“需要属性”和“内容类型”）要求。</span><span class="sxs-lookup"><span data-stu-id="98de4-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="98de4-126">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="98de4-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="98de4-127">2019 年 5 月 - 示例</span><span class="sxs-lookup"><span data-stu-id="98de4-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="98de4-128">摘要</span><span class="sxs-lookup"><span data-stu-id="98de4-128">Summary</span></span>|<span data-ttu-id="98de4-129">正在调查</span><span class="sxs-lookup"><span data-stu-id="98de4-129">Investigating</span></span>|<span data-ttu-id="98de4-130">已解决</span><span class="sxs-lookup"><span data-stu-id="98de4-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="98de4-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="98de4-131">**Excel**</span></span>
<span data-ttu-id="98de4-132">在多个内部版本中已解决的问题的示例 -- 发现了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="98de4-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="98de4-133">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="98de4-133">SAC Version 1902</span></span> <br> <span data-ttu-id="98de4-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="98de4-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="98de4-135">每月版本 1905</span><span class="sxs-lookup"><span data-stu-id="98de4-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="98de4-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="98de4-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="98de4-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="98de4-137">**Word**</span></span>
<span data-ttu-id="98de4-138">某些内部版本（并非全部内部版本）中已解决的问题的示例 -- 发现了在为“文档”属性启用文档部件时的性能问题。</span><span class="sxs-lookup"><span data-stu-id="98de4-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="98de4-139">SAC 版本 1808</span><span class="sxs-lookup"><span data-stu-id="98de4-139">SAC Version 1808</span></span>|<span data-ttu-id="98de4-140">SAC 版本 1902</span><span class="sxs-lookup"><span data-stu-id="98de4-140">SAC Version 1902</span></span> <br> <span data-ttu-id="98de4-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="98de4-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="98de4-142">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="98de4-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
