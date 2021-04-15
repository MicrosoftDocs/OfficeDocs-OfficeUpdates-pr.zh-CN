---
title: 有关 2020 年半年企业频道（预览）发行的发行说明
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2020 年 Microsoft 365 应用版半年频道（定向）发行的发行说明
ms.openlocfilehash: d6c48db35445d15503c246506bc7d03da3ca0548
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/13/2021
ms.locfileid: "51748960"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="9dd0f-103">有关半年企业频道（预览）的发行说明</span><span class="sxs-lookup"><span data-stu-id="9dd0f-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="9dd0f-104">我们为 Microsoft 365 企业应用版、Microsoft 365 商业应用版以及 Project 和 Visio 桌面应用的订阅版本提供了半年企业频道（预览）更新。这些发行说明提供了有关这些更新中所含新功能和非安全更新的信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="9dd0f-105">我们正在对 Microsoft 365 应用的更新频道进行一些更改，包括添加新的更新频道（月度企业版频道）和更改现有更新频道的名称。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="9dd0f-106">若要了解详细信息，请[阅读这篇文章](/DeployOffice/update-channels-changes)。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="9dd0f-107">版本 2102：4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-107">Version 2102: April 13</span></span>
<span data-ttu-id="9dd0f-108">*版本 2102（内部版本 13801.20506）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="9dd0f-109">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-111">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9dd0f-112">Access</span><span class="sxs-lookup"><span data-stu-id="9dd0f-112">Access</span></span>

- <span data-ttu-id="9dd0f-113">修复了在某些情况下，运行 SQL Server 通过查询可能会收到指明"光标状态无效"的错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="9dd0f-114">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-114">Excel</span></span>

- <span data-ttu-id="9dd0f-115">解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="9dd0f-116">修复了在另一张工作表上添加行后，数据验证可能会意外应用到单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="9dd0f-117">修复了对话框表显示函数在 32 位版本的 Excel 中无法正常工作这一问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-118">Outlook</span></span>

- <span data-ttu-id="9dd0f-119">修复了导致 Outlook 在空闲时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="9dd0f-120">我们修复了导致云设置功能用户在新设备上配置 Outlook 后会看到默认设置覆盖自定义设置的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="9dd0f-121">修复了导致用户看到签名超过预期的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-122">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-123">解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="9dd0f-124">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-124">Word</span></span>

- <span data-ttu-id="9dd0f-125">解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="9dd0f-126">修复了与复制和粘贴相关的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="9dd0f-127">我们修复了在隐藏段落末尾键入时可能导致应用程序挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-128">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-128">Office Suite</span></span>

- <span data-ttu-id="9dd0f-129">解决了用户在打开以前打开的文件时无法保存文件（其中未保存编辑，但现在文件已删除）的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="9dd0f-130">修复后，用户收到友好消息，告知用户文件已删除，因此用户可选择放弃更改或另存为文件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="9dd0f-131">修复了脱机打开 SyncBacked 文件，然后在保存文件之前在应用中重命名文件时出现重命名失败问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="9dd0f-132">修复了 GCC 用户禁用听写的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="9dd0f-133">修复了有时可能导致 Outlook 中的文本变为透明且无法清晰显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-march-09"></a><span data-ttu-id="9dd0f-135">版本 2102：3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-135">Version 2102: March 09</span></span>
<span data-ttu-id="9dd0f-136">*版本 2102（内部版本 13801.20294）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="9dd0f-137">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="9dd0f-139">功能更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-140">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-140">Excel</span></span>

- <span data-ttu-id="9dd0f-141">**墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="9dd0f-142">在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="9dd0f-143">**建立 PDF 连接：** 连接到 PDF，从其中导入数据，刷新数据。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="9dd0f-144">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="9dd0f-145">**创建用于公式的变量：** 通过 LET 函数改进性能、可读性和可组合性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="9dd0f-146">此功能允许你在新的或预先存在的公式中创建已命名的变量。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="9dd0f-147">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="9dd0f-148">在[博客文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="9dd0f-149">**保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="9dd0f-150">我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="9dd0f-151">我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="9dd0f-152">这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="9dd0f-153">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="9dd0f-154">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="9dd0f-155">**使用数据类型从 Power BI 获取组织数据：Power BI 中的** Excel 数据类型现向具有 Office 365/Microsoft 365 和 Power BI Pro 服务计划的组织的预览体验成员推出。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="9dd0f-156">获取所需信息并轻松刷新，这对许多日常工作流至关重要。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="9dd0f-157">我们将为你提供从 Power BI 到 Excel 中的数据类型的公司或组织信息的访问权限，这将扩大你在电子表格中引入链接信息的能力。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="9dd0f-158">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="9dd0f-159">在[博客文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="9dd0f-160">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="9dd0f-161">无需转换。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-161">No conversion required.</span></span><br /><span data-ttu-id="9dd0f-162">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-162">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="9dd0f-163">**在 Excel 中制作精美的 Visio 图表：** 根据工作表中的数据创建数据驱动的图表，例如流程图或组织结构图。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="9dd0f-164">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="9dd0f-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-165">Outlook</span></span>

- <span data-ttu-id="9dd0f-166">**帮助保护组中的数据：** 你在创建组时选择的敏感度标签应用于组电子邮件、文档和团队网站。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="9dd0f-167">**IT 管理员事件通知：** 使用 Outlook for Windows 中的新右侧面板通知，Microsoft 365 租户全局管理员和 Office 应用程序管理员将收到有关影响用户的 Outlook 和 O365 通知。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="9dd0f-168">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="9dd0f-169">**在 Outlook 中使用快速投票创建投票：** 轻松创建投票、收集选票和在电子邮件中查看结果 [了解详细信息](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="9dd0f-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="9dd0f-170">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="9dd0f-171">无需转换。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-171">No conversion required.</span></span><br /><span data-ttu-id="9dd0f-172">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-172">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="9dd0f-173">**新的会议室查找器：** 根据不同功能搜索会议室。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="9dd0f-174">**按照你说的方式搜索目标：** 使用日常语言（如“上周预约的兽医”）来筛选和缩小搜索范围。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="9dd0f-175">**从上一个 Outlook 会话快速重新打开项目的选项：** 我们添加了一个选项，可以从上一个 Outlook 会话快速重新打开项目。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="9dd0f-176">在[博客文章](https://insider.office.com/zh-CN/blog/automatically-restore-windows-in-outlook)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-176">See details in [blog post](https://insider.office.com/zh-CN/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9dd0f-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-177">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-178">**墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="9dd0f-179">在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="9dd0f-180">**保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="9dd0f-181">我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="9dd0f-182">我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="9dd0f-183">这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="9dd0f-184">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="9dd0f-185">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="9dd0f-186">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="9dd0f-187">无需转换。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-187">No conversion required.</span></span><br /><span data-ttu-id="9dd0f-188">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-188">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="9dd0f-189">Visio</span><span class="sxs-lookup"><span data-stu-id="9dd0f-189">Visio</span></span>

- <span data-ttu-id="9dd0f-190">**新 Azure 图案和形状：** 我们添加了很多图案，以帮助创建最新的 Azure 图表。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="9dd0f-191">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="9dd0f-192">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-192">Word</span></span>

- <span data-ttu-id="9dd0f-193">**墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="9dd0f-194">在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="9dd0f-195">**保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="9dd0f-196">我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="9dd0f-197">我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="9dd0f-198">这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="9dd0f-199">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="9dd0f-200">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="9dd0f-201">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="9dd0f-202">无需转换。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-202">No conversion required.</span></span><br /><span data-ttu-id="9dd0f-203">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-203">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-204">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-204">Office Suite</span></span>

- <span data-ttu-id="9dd0f-205">**制表符窗格：** 现在，可以使用应用程序右侧的选项卡 UI 在多个窗格之间进行切换。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="9dd0f-206">UI 将只在当打开2个以上的窗格时才会可见。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="9dd0f-207">在[博客文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-210">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9dd0f-211">Access</span><span class="sxs-lookup"><span data-stu-id="9dd0f-211">Access</span></span>

- <span data-ttu-id="9dd0f-212">我们修复了从非 Office 应用程序使用 DAO 时会导致应用程序意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="9dd0f-213">我们修复了用户收到错误对话”光标状态无效的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="9dd0f-214">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-214">Excel</span></span>

- <span data-ttu-id="9dd0f-215">我们修复了某些中断旧版 Excel 4.0 和 Excel 5.0 宏以及某些对 dialogsheets.show 的 VBA 调用的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="9dd0f-216">修复了使用数据透视表的“值显示方式”菜单时，Excel 可能意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="9dd0f-217">我们修复了一个阻止用户将 Excel 工作簿导出为 PDF 的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="9dd0f-218">我们修复了使用“粘贴链接图片”选项时导致图像小于预期的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="9dd0f-219">我们修复了保存为 .xls 或 .xlt 格式时导致某些数据透视表格式设置损坏工作簿的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="9dd0f-220">修复了打开包含 Excel 4.0 宏的 Excel 加载项文件时，Excel 可能会禁用宏而不提示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="9dd0f-221">修复了以下问题：Excel 错误地显示新版本文件可用的消息栏，并强制用户将更改保存在工作簿副本中或放弃更改。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="9dd0f-222">修复了以下问题：当某些用户共同创作时，会错误地向其显示存在新版本文件的消息栏通知。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="9dd0f-223">修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="9dd0f-224">我们修复了在图表中选择数据系列后 Excel 停止响应的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="9dd0f-225">此更改解决了在公式中正确显示字体的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-226">Outlook</span></span>

- <span data-ttu-id="9dd0f-227">解决了导致用户无法向其代理授予编辑器权限的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="9dd0f-228">我们解决了导致某些用户在特定搜索方案中遇到 Outlook 意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="9dd0f-229">修复了导致配置文件中具有较大层次结构的共享邮箱或委派邮箱的用户遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="9dd0f-230">解决了当主题行为空白时，某些自动生成的电子邮件将发送空白正文的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="9dd0f-231">解决了导致部分用户观察到 Outlook 在离线状态下意外启动的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="9dd0f-232">解决了导致代理在其他邮箱中打开共享文件夹时出现间歇性故障的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="9dd0f-233">我们修复了导致用户在选择搜索结果时遇到应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="9dd0f-234">我们修复了导致一些客户在加载日历时遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="9dd0f-235">我们修复了导致某些会议的原定与会者在其他与会者转发会议时收到取消通知的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="9dd0f-236">修复并解决了导致用户在创建新组后看到重复日历组的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="9dd0f-237">修复了导致“共享日历”改进用户无法将日历的颜色设置为黄色或棕色的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="9dd0f-238">我们修复了导致用户看到新添加的日历直到 Outlook 重新启动之后才会显示在导航窗格中的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="9dd0f-239">解决了在搜索未缓存的共享日历时，导致搜索不返回结果的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="9dd0f-240">我们修复了导致部分用户在关闭消息窗口时遇到关闭应用程序的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="9dd0f-241">我们修复了在发送任务状态报告时导致“收件人”字段为空的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="9dd0f-242">我们修复了导致 MailItem.BeforeAttachmentAdd 事件被破坏的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="9dd0f-243">我们修复了导致某些用户在特定搜索方案中遇到 Outlook 意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="9dd0f-244">我们修复了导致用户在 Outlook 中搜索时应用有时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="9dd0f-245">我们修复了一个导致云设置用户在更新设置时体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="9dd0f-246">我们修复了在提示用户保存后，已编辑的签名无法保存的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="9dd0f-247">我们已修复虽以配置一个或多个签名，但仍导致有的用户在签名下拉菜单中看不到签名的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="9dd0f-248">我们修复了导致默认情况下不会为用户打开云设置的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="9dd0f-249">我们修复了导致无法保存用户签名更改的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="9dd0f-250">我们修复了导致 Outlook 为已启用云设置的用户创建第二个空签名的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="9dd0f-251">我们修复了一个问题，该问题导致 OWA 中显示正确默认签名问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="9dd0f-252">修复了导致用户看到包含 unicode 内容的签名受损的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="9dd0f-253">修复了导致内联翻译用户无法提交反馈的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="9dd0f-254">解决了导致在答复或转发时中文电子邮件的标题不可阅读的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="9dd0f-255">我们修复了另存为 OFT 文件时汉字变成问号的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="9dd0f-256">我们添加了一个 regkey，允许客户在 IDataObject 操作中禁用附件的 filetime 包含（例如，拖放、剪贴板）。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="9dd0f-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="9dd0f-258">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="9dd0f-259">0 = filetimes 被排除。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="9dd0f-260">1 = （默认）包含 filetime。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="9dd0f-261">我们修复了以下问题：当回复带有来自 Azure 信息保护的保护标签的邮件时，将导致嵌入式图像消失。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="9dd0f-262">修复了使用仅加密选项发送的电子邮件上无法显示加密图标的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="9dd0f-263">我们已修复了在用户取消选中该选项后导致邮件以数字签名发送的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-264">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-265">修复了可能导致应用程序在文件保存失败时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="9dd0f-266">修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="9dd0f-267">此更改解决了使用特定几何图形对合并形状操作应用时路径填充的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="9dd0f-268">此更改解决了在公式中正确显示字体的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="9dd0f-269">此更改解决了处理视频加载过程中可能出现的错误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="9dd0f-270">我们修复了 Slide.Shapes.AddMediaObject2 在使用传统视频格式（MPG-1、Mpeg-2）时会意外关闭的 VBA 问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="9dd0f-271">我们修复了 QAT 中添加的字号命令在更新时自动完成为最接近定义字号的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="9dd0f-272">我们修复了以下问题：复制包含新近录制音频的幻灯片后，保存文件时出现错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="9dd0f-273">我们修复了表单内容加载项在插入后不显示，而要到用户单击另一张幻灯片来使其显示时才显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="9dd0f-274">我们修复了在受保护的视图中打开 PowerPoint 文件时禁用 IRM 保护的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="9dd0f-275">修复了在包含大量特定数据对象类型 (E2o) 的文件上导致共同创作速度下降的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="9dd0f-276">修复了在合并错误过程中使用 IRM/受保护的文档时遇到的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="9dd0f-277">这是针对以下问题的修补程序：关闭文档且存在侦听 PresentationBeforeClose 事件和检查作为事件处理程序一部分的 Presentation.Saved 属性的加载项时，“保存”提示会循环显示。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="9dd0f-278">修复了一些损坏的 PowerPoint 文件即使在执行文档修复操作后也无法正常打开的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="9dd0f-279">解决了某些情况下选择设计创意会删除演示文稿数据分类标签的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="9dd0f-280">Project</span><span class="sxs-lookup"><span data-stu-id="9dd0f-280">Project</span></span>

- <span data-ttu-id="9dd0f-281">修复了以下问题：将项目从 PWA 保存到本地 mpp 文件时，用户实际上未更改的数据将触发 ProjectBeforeTaskChangeEvent。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="9dd0f-282">修复了以下问题：如果在“任务窗体”类型视图中更改了滞后，ProjectBeforeTaskChange 事件中的 NewVal 没有正确的值。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="9dd0f-283">修复了以下问题：如果你正在运行事件代码并尝试通过 “任务窗体”视图进行更改，单击“确定”按钮可能无法提交所做的更改。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="9dd0f-284">解决了打开以特定方式指定资源分布的文件时，Project 可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="9dd0f-285">已修复项目文件加载到特定部分出现错误，导致可能打开特定项目的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="9dd0f-286">解决了视图中不显示任务边框的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="9dd0f-287">解决了“工作组规划器”视图中的拖放功能无法用于任务的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="9dd0f-288">修复了将成本资源分配给里程碑任务时，基线成本没有正确汇总的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="9dd0f-289">Visio</span><span class="sxs-lookup"><span data-stu-id="9dd0f-289">Visio</span></span>

- <span data-ttu-id="9dd0f-290">我们修复了一个问题，用户以后可以使用 Visio for Office 365 中的连接器创建自定义 Visio 模具和内置模板的直线。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="9dd0f-291">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-291">Word</span></span>

- <span data-ttu-id="9dd0f-292">修复了可能导致应用程序在文件保存失败时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="9dd0f-293">修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="9dd0f-294">此更改解决了编辑文档时光标存在的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="9dd0f-295">我们修复了将颜色应用于图标和具有 3D 效果的 SVG 图形的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="9dd0f-296">我们修复了讲述人可能跳过某个段落的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="9dd0f-297">我们修复了富文本内容控件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="9dd0f-298">我们修复了“样式库”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="9dd0f-299">我们已修复了在共同创作时解决冲突的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="9dd0f-300">我们修复了以模板中的其他样式替换文档样式的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="9dd0f-301">修复了影响 Word 的优化关口所暴露出的申明 bug。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-302">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-302">Office Suite</span></span>

- <span data-ttu-id="9dd0f-303">解决了尝试保存文件导致故障的问题，该文件从同步备份转换为仅支持服务器。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="9dd0f-304">修复了在某些情况下尝试执行 SaveAs 操作时失败的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="9dd0f-305">我们修复了 SaveRequestManagerCam 导致应用程序关闭而不是返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="9dd0f-306">修复了文件关闭序列，以便完全关闭所有相互依赖组件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="9dd0f-307">修复了当来自缓存的 URL 和来自 OneDrive 的 URL 不匹配时，文件在打开时不同步的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="9dd0f-308">修复了 Skype for Business 消息中复制/粘贴导致出现"粘贴内容时出错"的对话框的 bug。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="9dd0f-309">修复了将注释中的文本复制/粘贴到 Excel 时出错的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="9dd0f-310">修复了在包含数学公式的文本中使用讲述人时可能发生的崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="9dd0f-311">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="9dd0f-312">将信息更改为显示 "碳粉/墨水不足" & "无碳粉/墨水"。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="9dd0f-313">修正了在某些旧版本上安装较新版本的Office，可能会因缺少注册表项而导致功能受损（例如无法使用Power Query）的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="9dd0f-314">修复了 Microsoft 365 终结点数据丢失防护无法对磁盘上的 Office 文档进行分类的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="9dd0f-315">我们修复了“压缩图片”对话框不保留某些用户设置的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="9dd0f-316">修复了与媒体控制器事件通知相关的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="9dd0f-317">修复了与媒体播放器引擎计时相关的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="9dd0f-318">经过优化的二进制大小。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-318">Optimized binary size.</span></span>


- <span data-ttu-id="9dd0f-319">Anaheim WebView 尚不支持 Windows 信息保护(WIP)。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="9dd0f-320">通过此修复，Office 插件平台可以在启用 WIP 的环境中回退到较低级别的 WebView。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="9dd0f-321">根据客户的计算机环境，它可以是 Edge Spartan WebView 或 Trident WebView。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="9dd0f-322">两个低级别 WebView 均支持 WIP。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-322">Both down level WebViews support WIP.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-february-09"></a><span data-ttu-id="9dd0f-324">版本 2008：2 月 09 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-324">Version 2008: February 09</span></span>
<span data-ttu-id="9dd0f-325">*版本 2008（内部版本 13127.21216）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="9dd0f-326">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-328">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-329">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-329">Excel</span></span>

- <span data-ttu-id="9dd0f-330">修复了打开具有无效文件属性的 UNC 文件时 Excel 会意外关闭的问题（创建时间、修改时间等）</span><span class="sxs-lookup"><span data-stu-id="9dd0f-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="9dd0f-331">修复了将图表从 Excel 复制并粘贴到 Word 或 PowerPoint 时无法执行小数和千位分隔符设置的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="9dd0f-332">我们修复了这样一个问题，即每次运行宏时，涉及数据透视表区域格式的宏的性能会变差。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="9dd0f-333">修复了在将工作表复制或移动到另一个工作簿时条件格式规则被删除的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="9dd0f-334">修复了禁用应用启动屏幕时，用户无法将敏感度标签应用到 Excel 文件这一问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="9dd0f-335">修复了从 OneDrive 同步文件夹打开云文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-336">Outlook</span></span>

- <span data-ttu-id="9dd0f-337">解决了导致 Outlook 在添加或保存附件时偶尔停止工作的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-338">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-339">修复了 QAT 中添加的字号命令在更新时自动完成以最接近定义字号的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="9dd0f-340">修复了采用"保留源格式"选项的幻灯片复制和粘贴有时意外复制到新幻灯片母版上的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="9dd0f-341">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-341">Word</span></span>

- <span data-ttu-id="9dd0f-342">修复了修订中的问题：有时打开 Word 文档可能会显示错误对话框。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="9dd0f-343">修复了从 OneDrive 同步文件夹打开云文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-344">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-344">Office Suite</span></span>

- <span data-ttu-id="9dd0f-345">解决了阻止在 Office 中成功打开文件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="9dd0f-346">修复了通过格式刷将包含草图轮廓应用到连接线的文档可能会损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-2008-january-12"></a><span data-ttu-id="9dd0f-348">版本2008：1月12日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-348">Version 2008: January 12</span></span>
<span data-ttu-id="9dd0f-349">*版本2008（内部版本13127.21064）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="9dd0f-350">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-352">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-353">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-353">Excel</span></span>

- <span data-ttu-id="9dd0f-354">修正了只读书籍在打开时不再刷新数据透视表数据的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="9dd0f-355">此更改提供了对以下问题的修复：当从OneDrive本地同步文件夹插入文件时，Excel "插入对象 "不显示正确的图标。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="9dd0f-356">修正了当客户在共同创作时，会错误地收到关于新版本文件通知的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="9dd0f-357">修正了在覆写模式下使用输入法编辑器会错误地推进额外字符的编辑问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="9dd0f-358">修正了在使用实时数据和多线程重新计算功能时所出现的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="9dd0f-359">修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-360">Outlook</span></span>

- <span data-ttu-id="9dd0f-361">我们修复了保存到草稿时，SmartLink 格式丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="9dd0f-362">修复了替代策略时为用户提供自定义对齐文本方法的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="9dd0f-363">我们修复了另存为 OFT 文件时汉字变成问号的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-364">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-365">我们修正了 Slide.Shapes.AddMediaObject2 在使用传统视频格式（MPG-1,Mpeg-2）时会意外关闭的 VBA 问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="9dd0f-366">已修复一些损坏的 PowerPoint 文件无法正常打开的问题，即使在执行文档修复操作后也是如此。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="9dd0f-367">Project</span><span class="sxs-lookup"><span data-stu-id="9dd0f-367">Project</span></span>

- <span data-ttu-id="9dd0f-368">修正了当以某种方式指定资源分布时，项目可能在打开文件时意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="9dd0f-369">Skype</span><span class="sxs-lookup"><span data-stu-id="9dd0f-369">Skype</span></span>

- <span data-ttu-id="9dd0f-370">修复了用户的 TLS-DSK 证书无法在预期时间内更新，而是在有效期剩余不到12小时时续订。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="9dd0f-371">修复了当Office尚未获得授权时，Skype for Business用户界面在登录后显示为空白的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-372">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-372">Office Suite</span></span>

- <span data-ttu-id="9dd0f-373">此更改解决了与打开包含遗留图的文件相关的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="9dd0f-374">此更改解决 SVG 回退代理导致访问违规的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-december-08"></a><span data-ttu-id="9dd0f-376">版本 2008：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-376">Version 2008: December 08</span></span>
<span data-ttu-id="9dd0f-377">*版本 2008（内部版本 13127.20910）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-377">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="9dd0f-378">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-378">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-380">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-380">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9dd0f-381">Access</span><span class="sxs-lookup"><span data-stu-id="9dd0f-381">Access</span></span>

- <span data-ttu-id="9dd0f-382">我们修复了在尝试使用 ODBC DSN 生成器时的一个错误问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-382">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="9dd0f-383">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-383">Excel</span></span>

- <span data-ttu-id="9dd0f-384">修复了以下问题：无法编辑从 Project 计划导出的数据透视表，并且无法保存相同情况下的工作簿。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-384">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="9dd0f-385">我们修复了以下问题：在某些情况下，在只读模式下打开文件时，会显示多个消息栏。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-385">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="9dd0f-386">我们修复了以下问题：当存在多个重复的列标题值时，大纲小计可能会停止运转。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-386">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="9dd0f-387">我们修复了以下问题：当发生组策略对象更新（例如，通过远程组策略刷新）时，Excel 会停止运行。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-387">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="9dd0f-388">我们修复了以下问题：当用户在超过 255 个列中使用小计函数时，Excel 会停止运行。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-388">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="9dd0f-389">当从 Excel 中复制内容并使用“嵌入”选项粘贴到 PowerPoint 时，改进了 PowerPoint 中的文本间距调整。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-389">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="9dd0f-390">修复了导致在 PowerPivot 中无法从“表预览”和“查询编辑器”进行切换的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-390">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="9dd0f-391">修复了用户无法直接从 SharePoint 打开 atomsvc (UTF8+BOM) 文件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-391">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="9dd0f-392">我们修复了一个问题，现在 Power Pivot 将能够成功识别制表符分隔符。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-392">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-393">Outlook</span></span>

- <span data-ttu-id="9dd0f-394">我们修复了在发送任务状态报告时导致“收件人:”字段为空的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-394">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="9dd0f-395">我们修复了导致 MailItem.BeforeAttachmentAdd 事件被破坏的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-395">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="9dd0f-396">我们修复了导致某些用户在从 Outlook 以外的应用程序中发送 Outlook 邮件时遇到应用程序意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-396">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="9dd0f-397">我们修复了以下问题：在联机模式下，当用户在文件夹之间移动多个邮件项目时，性能会下降。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-397">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="9dd0f-398">我们添加了一个 regkey，允许客户在 IDataObject 操作（例如，拖放、剪贴板）中禁用附件的 filetime 包含。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-398">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="9dd0f-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = 排除 filetime  1 =（默认）包含 filetime</span><span class="sxs-lookup"><span data-stu-id="9dd0f-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="9dd0f-400">我们修复了以下问题：当回复带有来自 Azure 信息保护的保护标签的邮件时，将导致嵌入式图像消失。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-400">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="9dd0f-401">我们修复了以下问题：在发送受 Azure 保护的语音邮件时，用户名显示为电话号码，从而导致 Outlook 桌面用户无法打开来自外部用户的语音邮件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-401">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="9dd0f-402">我们修复了以下问题：设置 OME 配置时会在邮件项目上添加一个无关的附件，这会迫使 Outlook 对邮件进行加密，即使在服务端设置了 DecryptAttachmentsForEncryptOnly 选项也是如此。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-402">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-403">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-403">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-404">修复了以下问题：当用户将源路径更改为本地 OneDrive 文件夹时，链接的 excel 图表出现错误地更改为 excel 工作表。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-404">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="9dd0f-405">我们修复了导致功能“欢迎回来!</span><span class="sxs-lookup"><span data-stu-id="9dd0f-405">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="9dd0f-406">从在办公室中离开的位置开始”在 PowerPoint 中不起作用的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-406">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="9dd0f-407">Visio</span><span class="sxs-lookup"><span data-stu-id="9dd0f-407">Visio</span></span>

- <span data-ttu-id="9dd0f-408">我们修复了一个问题，用户以后可以使用 Visio for Office 365 中的连接器创建自定义 Visio 模具和内置模板的直线。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-408">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="9dd0f-409">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-409">Word</span></span>

- <span data-ttu-id="9dd0f-410">我们修复了将文档保存为 HTML 格式时长链接无法换行的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-410">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="9dd0f-411">我们修复了以下问题：如果你回复在扩展列表中具有未知扩展的父级评论，则回复将获得这些相同的扩展。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-411">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="9dd0f-412">我们修复了 Outlook 邮件设置为“不要转发”的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-412">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-413">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-413">Office Suite</span></span>

- <span data-ttu-id="9dd0f-414">解决了导致用户在已禁用 ADAL 时无法导入 SPO 列表的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-414">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-november-10"></a><span data-ttu-id="9dd0f-416">版本 2008：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-416">Version 2008: November 10</span></span>
<span data-ttu-id="9dd0f-417">*版本 2008（内部版本 13127.20760）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-417">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="9dd0f-418">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-418">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-420">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-420">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9dd0f-421">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-421">Excel</span></span>

- <span data-ttu-id="9dd0f-422">解决了某些函数在加载工作簿后可能出现错误结果的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-422">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="9dd0f-423">解决了与 XLAM 加载项引用和命名范围相关的应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-423">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="9dd0f-424">我们解决了以下问题：使用宏设置区域的 FormulaR1C1 属性时，如果图表工作表是活动工作表，则单元格引用将不正确。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-424">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="9dd0f-425">解决了可能导致“Excel 在尝试计算一个或多个公式时用尽资源”错误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-425">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="9dd0f-426">修复了将 Office 语言设置为西班牙语时出现的问题，在有问题的情况下，数据验证列表可能不会显示列表中的所有项目。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-426">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="9dd0f-427">解决了在刷新 OLAP 数据透视表时可能会导致挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-427">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-428">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-428">Outlook</span></span>

- <span data-ttu-id="9dd0f-429">我们修复了以下问题：现在用户可以禁用 Outlook 的 IRM （信息权限管理），而无需在其他 Office 应用程序中禁用它。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-429">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="9dd0f-430">解决了导致用户无法向其代理授予编辑器权限的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-430">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="9dd0f-431">解决了导致用户在选择搜索结果时遇到应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-431">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="9dd0f-432">解决了导致在组日历中搜索无法返回任何结果的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-432">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="9dd0f-433">解决了导致代理在其他邮箱中打开共享文件夹时出现间歇性故障的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-433">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="9dd0f-434">解决了当主题行为空白时，某些自动生成的电子邮件将发送空白正文的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-434">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="9dd0f-435">解决了导致在答复或转发时中文电子邮件的标题出现乱码的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-435">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="9dd0f-436">解决了可选的连接体验阻止加载 Web 加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-436">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="9dd0f-437">在[博客文章](https://developer.microsoft.com/zh-CN/office/blogs/outlook-add-ins-and-optional-connected-experiences/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-437">See details in [blog post](https://developer.microsoft.com/zh-CN/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-438">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-439">解决了 Forms 内容加载项在插入后不显示，而要到用户单击另一张幻灯片来使其放映时才显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-439">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-440">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-440">Office Suite</span></span>

- <span data-ttu-id="9dd0f-441">解决了使用 Microsoft 365 端点数据丢失防护利用 System Center Configuration Manager 或其他 Office Update 管理工具的商业客户的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-441">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="9dd0f-442">解决了 Office 加载项的消息传递 API 无法正常工作的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-442">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (请勿删除错误详细信息内容结尾)

## <a name="version-2008-october-13"></a><span data-ttu-id="9dd0f-444">版本 2008：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-444">Version 2008: October 13</span></span>
<span data-ttu-id="9dd0f-445">*版本 2008（内部版本 13127.20638）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-445">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="9dd0f-446">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-446">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-448">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-448">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-449">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-449">Excel</span></span>

- <span data-ttu-id="9dd0f-450">修复了 PivotDateFilter API 中“Before”和“After”筛选条件被颠倒的错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-450">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="9dd0f-451">修复了用户无法修改数据透视表筛选器的问题，因为它被设置为在 Analysis Services 数据库中已不存在的值。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-451">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="9dd0f-452">修复了以下问题：在冻结工作表首行后使用快速分析时，Excel 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-452">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="9dd0f-453">修复了以下问题：如果工作簿包含使用 IFNA() 的公式，则可能导致有关损坏的工作簿的警告。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-453">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-454">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-454">Outlook</span></span>

- <span data-ttu-id="9dd0f-455">解决了以下问题：用户单击角落的“X”无法关闭共享日历。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-455">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="9dd0f-456">解决了导致“打开共享的日历改进项”设置有时无法应用于现有共享日历的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-456">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="9dd0f-457">解决了导致用户在打开云附件时在安全链接页面（而不是试图打开的文档）上看到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-457">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="9dd0f-458">解决附件上传的性能问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-458">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-459">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-460">此更改解决了单击“导出到动态 GIF”功能的“导出”按钮后，并未成功导出的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-460">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="9dd0f-461">安全性修补程序解决了在受保护视图中打开 PowerPoint 文件时禁用 IRM 保护的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-461">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="9dd0f-462">我们修复了操作设置对话框中导致 PowerPoint 应用崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-462">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="9dd0f-463">Visio</span><span class="sxs-lookup"><span data-stu-id="9dd0f-463">Visio</span></span>

- <span data-ttu-id="9dd0f-464">修复了导致 Live 预览在文本对齐时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-464">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="9dd0f-465">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-465">Word</span></span>

- <span data-ttu-id="9dd0f-466">修复了用户打开某些很大的邮件时会遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-466">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="9dd0f-467">我们修复了用户在打开文档时可能遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-467">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="9dd0f-468">解决了可能在启动 Word 时导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-468">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="9dd0f-469">我们修复了“样式库”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-469">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-470">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-470">Office Suite</span></span>

- <span data-ttu-id="9dd0f-471">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-471">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="9dd0f-472">将信息更改为显示 "碳粉/墨水不足" & "无碳粉/墨水"。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-472">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="9dd0f-473">修复了使用 GIF/动画模型 3D 时空闲的高 CPU 使用率</span><span class="sxs-lookup"><span data-stu-id="9dd0f-473">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="9dd0f-474">此更改解决了启动 Office 应用时由于无法加载 d2d1 而出现的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-474">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-september-08"></a><span data-ttu-id="9dd0f-476">版本 2008：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-476">Version 2008: September 08</span></span>
<span data-ttu-id="9dd0f-477">*版本 2008（内部版本 13127.20408）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-477">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="9dd0f-478">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-478">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="9dd0f-480">功能更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-480">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9dd0f-481">Access</span><span class="sxs-lookup"><span data-stu-id="9dd0f-481">Access</span></span>

- <span data-ttu-id="9dd0f-482">**在“查询设计器”、“SQL 视图”和“关系”窗口中更高效地工作：** 右键单击表格，以对其进行打开、设计、调整大小和隐藏操作。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-482">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="9dd0f-483">在 SQL 视图中搜索和替换文本。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-483">Search and replace text in SQL View.</span></span> <span data-ttu-id="9dd0f-484">在“关系”窗口中选择多个表。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-484">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="9dd0f-485">**单击几下即可添加表：** 使用“添加表”任务窗格（在你工作时一直打开）向关系和查询添加表。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-485">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="9dd0f-486">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-486">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="9dd0f-487">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-487">Excel</span></span>

- <span data-ttu-id="9dd0f-488">**改进的地图图表：** 我们改进了地图图表，将其与 Excel 的地理数据类型相集成，可显示有关地图位置的丰富信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-488">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="9dd0f-489">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-489">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="9dd0f-490">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-490">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9dd0f-491">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-491">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9dd0f-492">**在 Excel 中从 Power BI 中的数据集创建数据透视表：** 你可以在 Excel 中创建连接到 Power BI 中存储的数据集的数据透视表，只需点击几下鼠标。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-492">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="9dd0f-493">这样做可以让你更好地利用数据透视表和 Power BI。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-493">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="9dd0f-494">使用数据透视表从你的安全的 Power BI 数据集计算、总结和分析数据。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-494">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="9dd0f-495">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-495">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="9dd0f-496">在[博客文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-496">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="9dd0f-497">**你喜爱的 Excel 函数运行速度更快：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函数运行速度比以往更快。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-497">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="9dd0f-498">更快达到底线。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-498">Get to the bottom line more quickly.</span></span> <span data-ttu-id="9dd0f-499">立即试用。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-499">Try one now.</span></span>

- <span data-ttu-id="9dd0f-500">**Realtimedata (RTD) 改进：** 在 Office 365 版本 2002 每月频道或更高版本中，Excel 的 RealTimeData (RTD) 函数要比 Excel 2010 计算电子表格中的数据的速度快得多。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-500">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="9dd0f-501">我们在其基本内存和数据结构中删除瓶颈，并使其变得线程安全，这能允许其在 多线程计算 (MTR) 的所有可用线程上进行计算。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-501">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-502">Outlook</span></span>

- <span data-ttu-id="9dd0f-503">**共享日历更新速度更快：** 对于 Office 365 中的共享日历，Outlook 可以使用 REST API 更新这些日历。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-503">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="9dd0f-504">打开预览，更快速、更可靠地更新共享日历。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-504">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="9dd0f-505">**更好的结果 - 瞬间完成：** 我们更新了搜索体验，使其更加智能、更快速，并且比以往更可靠。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-505">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="9dd0f-506">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-506">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="9dd0f-507">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-507">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9dd0f-508">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-508">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9dd0f-509">**将电子邮件拖动到你拥有的组：** 通过从收件箱中拖动来移动和复制邮件和对话。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-509">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="9dd0f-510">将与所有组成员共享你拖动的消息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-510">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="9dd0f-511">在[博客文章](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-511">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="9dd0f-512">**改进日历：** 可查看视觉对象更新，以便更轻松地扫描日历。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-512">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="9dd0f-513">了解更多详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-513">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="9dd0f-514">在[博客文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-514">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="9dd0f-515">**不退出收件箱加入会议：** 无需切换至日历以加入联机会议。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-515">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="9dd0f-516">通过固定日历至待办事项窗格，只需单机一次即可加入任何会议。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-516">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="9dd0f-517">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-517">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="9dd0f-518">**强制 wifi 网络新体验：** 是否已加入需要使用网页登录的 wifi 网络？</span><span class="sxs-lookup"><span data-stu-id="9dd0f-518">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="9dd0f-519">现在，Outlook 检测到这一点，帮助你进行连接。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-519">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="9dd0f-520">在[博客文章](https://insider.office.com/zh-CN/blog/outlook-on-public-wi-fi-networks-just-got-easier)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-520">See details in [blog post](https://insider.office.com/zh-CN/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="9dd0f-521">**搜索某个人时获取电子邮件建议：** 在“搜索”框中键入某人姓名时，最相关的电子邮件信息将包含在搜索建议中。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-521">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="9dd0f-522">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-522">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="9dd0f-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-523">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-524">**使用 \@提及** 功能引起他人的注意：在批注中使用 @提及，以在需要同事的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-524">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="9dd0f-525">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-525">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="9dd0f-526">**改进的地图图表：** 我们改进了地图图表，将其与 Excel 的地理数据类型相集成，可显示有关地图位置的丰富信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-526">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="9dd0f-527">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-527">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="9dd0f-528">**GIF 瞬间完成：** 一幻灯片、一帧。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-528">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="9dd0f-529">轻松在 PowerPoint 中创建循环 GIF。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-529">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="9dd0f-530">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-530">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="9dd0f-531">在[博客文章](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-531">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="9dd0f-532">**更好的图表：** 有了更好的连接器和更流程的墨迹转换过程，你可以更轻松用墨迹表达你的想法。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-532">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="9dd0f-533">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-533">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="9dd0f-534">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-534">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9dd0f-535">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-535">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9dd0f-536">**批注**：PowerPoint 中新的批注体验使你可以快速、轻松地发现批注并将其添加到文档中。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-536">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="9dd0f-537">通过批注锚定、解决、任务、改进的提及通知等新功能实现协作工作流现代化。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-537">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="9dd0f-538">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-538">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="9dd0f-539">**演示时同步所做的更改：** 即使演示文稿处于幻灯片放映模式，只要进行了更改就同步这些更改。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-539">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="9dd0f-540">了解更多详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-540">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="9dd0f-541">在[博客文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-541">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="9dd0f-542">**指向幻灯片的链接：** 让同事参与幻灯片的创作，让其直接转到你需要帮助的幻灯片上。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-542">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="9dd0f-543">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-543">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="9dd0f-544">在[博客文章](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-544">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="9dd0f-545">**改进了 PowerPoint 的流视频性能：** 我们对 Microsoft Stream 视频的回放性能进行了改进，以最小化视频加载时间，创造流畅的观看体验。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-545">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="9dd0f-546">使用来自 Microsoft Stream 的企业视频来创建更好的演示文稿。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-546">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="9dd0f-547">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-547">Word</span></span>

- <span data-ttu-id="9dd0f-548">**改进的地图图表：** 我们改进了地图图表，将其与 Excel 的地理数据类型相集成，可显示有关地图位置的丰富信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-548">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="9dd0f-549">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-549">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="9dd0f-550">**用套索选择墨迹：**“绘图”选项卡上的“套索”工具可帮助你选择用墨迹绘制的对象。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-550">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="9dd0f-551">选择单独的笔划或整个字。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-551">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="9dd0f-552">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-552">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="9dd0f-553">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-553">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9dd0f-554">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-554">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9dd0f-555">**屏幕阅读器中的操作确认：** 操作的确认是辅助功能一项重要的要求。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-555">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="9dd0f-556">随着 Windows 引入新的通知 API ，我们现在可以提醒屏幕阅读器用户的操作成功情况。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-556">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="9dd0f-557">剪切、复制、粘贴、加粗、斜体、下划线、撤消、重做、自动更正、自动大小写等功能，现在都已向Win32 Word"讲述人"用户公布。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-557">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="9dd0f-558">若要启用此功能，请按 windows + ctrl + enter 启用 "讲述人"。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-558">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="9dd0f-559">在[博客文章](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-559">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-560">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-560">Office Suite</span></span>

- <span data-ttu-id="9dd0f-561">**敏感度标签：** 你现在可以应用组织已配置的敏感度标签来提示自定义权限。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-561">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-564">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-564">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9dd0f-565">Access</span><span class="sxs-lookup"><span data-stu-id="9dd0f-565">Access</span></span>

- <span data-ttu-id="9dd0f-566">解决了插入包含身份（例如自动编号）字段的关联 SQL 表的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-566">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="9dd0f-567">我们修复了一个问题，即执行查询大约花费两倍于预期完成时间。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-567">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="9dd0f-568">修正了一个问题，以便能够在应用不会出现任何故障的情况下将日期/时间扩展数据类型调用到代码中。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-568">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="9dd0f-569">修正了一个问题，现在可以还原到最近更新的 Access 版本，并可使用 DAO/VBA 管理和编辑十进制数据类型。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-569">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="9dd0f-570">此修复解决了之前尝试运行某些查询时产生 "查询太复杂 "的错误信息的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-570">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="9dd0f-571">Access 已修复此当前问题，但将通过调查我们的其他界面来确保不会持续出现此问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-571">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="9dd0f-572">团队将向你通报未来的更新；非常感谢你的耐心等待。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-572">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="9dd0f-573">这个问题已经得到解决 - 现在，你可以在 Office 的即点即用应用程序之外使用我们的 ODBC 驱动程序。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-573">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="9dd0f-574">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-574">Excel</span></span>

- <span data-ttu-id="9dd0f-575">处于只读模式的工作簿可能已发生自动文档分类。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-575">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="9dd0f-576">修复了当你已从帐户注销时尝试创建数据连接时可能发生的故障。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-576">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="9dd0f-577">解决了在试图将数据透视表插入图表工作表时 Excel 可能故障的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-577">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="9dd0f-578">尝试使用 LET() 函数保存包含公式的文件时，可能会出现错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-578">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="9dd0f-579">解决了某些情况下使用格式刷时 Excel 可能会崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-579">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="9dd0f-580">修正了以下问题：保存到 SharePoint / OneDrive 时，自定义功能区标签的CustomUI XML被删除。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-580">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="9dd0f-581">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-581">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="9dd0f-582">修复了以下问题：在某些情况下，单击指向同一工作簿内某个位置的超链接将导致工作簿被隐藏。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-582">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="9dd0f-583">修复了以下问题：在文件重新打开后，如果文件路径太长，外部链接会停止工作。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-583">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="9dd0f-584">Application.Evaluate (VBA) 在某些情况下不能用于用户定义的功能。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-584">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="9dd0f-585">在当前版本的 Excel 中打开在 Excel 2016 保存含有数字签名的工作簿时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-585">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="9dd0f-586">修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-586">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="9dd0f-587">这解决了以下问题：由 SQL 数据提供程序在 Office 的较早版本中创建的连接将内部表属性设置为与 Office 365 不同。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-587">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="9dd0f-588">这会导致对于包含在旧版本的 Office 中创建的连接的文件，使用 Office 365 打开时，表预览/查询编辑器下拉列表被禁用。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-588">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="9dd0f-589">解决了如果关闭了源代码簿，则外部链接不会在填充时更新的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-589">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="9dd0f-590">解决了墨迹书写可能会导致 Excel 停止响应的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-590">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="9dd0f-591">OneNote</span><span class="sxs-lookup"><span data-stu-id="9dd0f-591">OneNote</span></span>

- <span data-ttu-id="9dd0f-592">通知用户有关 Microsoft OneNote 中的暂时调整的信息栏，可有助于提升全球范围内使用期间的同步和服务可用性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-592">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="9dd0f-593">通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-593">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="9dd0f-594">改进对共同创作状态的检测，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-594">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="9dd0f-595">在 OneNote 2016 中，通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-595">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="9dd0f-596">对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入OneNote。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-596">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="9dd0f-597">通过暂时禁用 OneNote 2016 中的应用内视频录制功能，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-597">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="9dd0f-598">本地笔记本不受此措施影响。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-598">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="9dd0f-599">通过临时更改页面版本历史记录的创建频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-599">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="9dd0f-600">通过暂时禁用将页面移动到回收站来提升同步和服务器稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-600">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="9dd0f-601">希望删除页面的用户将改为显示一个对话框，询问用户是否想要永久删除页面。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-601">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-602">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-602">Outlook</span></span>

- <span data-ttu-id="9dd0f-603">修复了导致尝试从添加到其个人资料的辅助帐户创建会议请求的用户看不到空白的“发件人：”字段，而是看到自己的电子邮件地址的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-603">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="9dd0f-604">修复了导致用户无法在添加共享邮箱后连接到公用文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-604">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="9dd0f-605">解决了导致在某些情况下，无法在代理拒绝会议时将其从经理的日历中删除的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-605">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="9dd0f-606">解决了共享日历改进功能的部分用户无法查看新添加的共享日历的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-606">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="9dd0f-607">修复了导致用户在与云附件交互时偶尔出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-607">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="9dd0f-608">解决了导致 CLP 用户在将回复的地址从受保护的上下文切换到不受保护的上下文时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-608">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="9dd0f-609">解决了针对 Outlook 未能向使用M365 Business Plus计划的付费用户启用数据丢失保护策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-609">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="9dd0f-610">解决了关于回复/转发标签的clp审核事件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-610">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="9dd0f-611">解决了导致文件夹窗格宽度意外改变的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-611">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="9dd0f-612">解决了导致用户看到通过拖放复制到其文件系统的附件的创建日期设置为 4501 年 1 月 1 日的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-612">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="9dd0f-613">解决了导致某些字符集的用户在向 SharePoint 文件添加智能链接时无法正确显示文件名的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-613">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="9dd0f-614">解决了导致用户在更新 Outlook 中的“规则”时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”消息的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-614">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="9dd0f-615">解决了导致 Outlook 无法检索搜索建议的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-615">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="9dd0f-616">解决了导致共享日历改进用户看到日历故障的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-616">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="9dd0f-617">解决了导致用户在某些情况下遇到间歇性挂起和崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-617">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="9dd0f-618">解决了通过选中 "仅下载邮件头" 选项删除来自 POP 帐户的4个或更多电子邮件时导致用户遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-618">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="9dd0f-619">解决了未选中“下载共享”文件夹时导致共享日历会议“响应选项”中缺少“允许转发”选项的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-619">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="9dd0f-620">解决了导致在编辑经理日历上的现有日历约会时，代表收到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-620">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="9dd0f-621">解决了用户在第三方 MAPI 应用程序中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-621">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="9dd0f-622">解决了 Windows 更新后导致 Outlook 在打开本地保存的 .msg 或 .oft 文件时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-622">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="9dd0f-623">解决了导致 Outlook 在某些版本的 Windows 上崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-623">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="9dd0f-624">解决了导致 Windows 10 服务器版本的用户看到警告“防病毒状态：无效”的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-624">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="9dd0f-625">此版本的 Windows 支持防病毒检测，但没有发现防病毒”，尽管这些用户已正确安装防病毒。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-625">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="9dd0f-626">解决了 Windows 更新后导致 Outlook 在打开本地保存的 .msg 或 .oft 文件时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-626">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="9dd0f-627">解决了导致 Outlook 在某些版本的 Windows 上崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-627">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="9dd0f-628">解决了导致用户看到 Outlook 不断提示他们运行收件箱修复工具的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-628">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="9dd0f-629">解决了在使用鼠标上的 "X" 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-629">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="9dd0f-630">解决了用户在安全对话框中选择”save” 选项时无法将 OneDrive 附件从租户外部保存到本地计算机的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-630">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="9dd0f-631">解决了导致日程安排助理页面无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-631">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="9dd0f-632">解决了导致“日程安排助理”页面无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-632">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="9dd0f-633">解决了导致用户在检索角色信息时偶尔会崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-633">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="9dd0f-634">修复了导致用户在编辑收件人时偶尔出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-634">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="9dd0f-635">修复了导致用户在使用压缩视图时出现异常的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-635">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="9dd0f-636">解决了导致 Outlook 用户在紧凑视图中导航时出现错误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-636">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="9dd0f-637">解决了导致右键单击上下文菜单无法在搜索控件中显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-637">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="9dd0f-638">解决了导致用户在答复或撰写新的电子邮件时收到错误的问题，其中该错误显示“此网页中的部分文件不在预期位置。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-638">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="9dd0f-639">是否仍要下载它们？</span><span class="sxs-lookup"><span data-stu-id="9dd0f-639">Do you want to download them anyway?</span></span> <span data-ttu-id="9dd0f-640">如果确定此网页来自可靠来源，请单击‘是’”</span><span class="sxs-lookup"><span data-stu-id="9dd0f-640">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="9dd0f-641">解决了导致用户在退出 Outlook 时遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-641">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="9dd0f-642">解决导致在中搜索功能的问题，该问题建议一项功能返回没有结果，使用户没有选择提交一个新功能想法。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-642">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="9dd0f-643">解决了导致事件通知警报出现格式问题的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-643">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="9dd0f-644">解决了用户在提交来自管理通知的反馈时故障的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-644">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="9dd0f-645">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-645">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="9dd0f-646">修复了导致用户在编辑收件人时偶尔出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-646">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="9dd0f-647">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-647">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-648">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-648">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-649">解决了当用户在文件中同时拥有现代和遗留评论时的故障，从而触发对评论的升级。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-649">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="9dd0f-650">修复了 PowerPoint 应用崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-650">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="9dd0f-651">我们已修正了“建议”窗格崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-651">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="9dd0f-652">Project</span><span class="sxs-lookup"><span data-stu-id="9dd0f-652">Project</span></span>

- <span data-ttu-id="9dd0f-653">解决了以下问题：在窗体视图中编辑前置/后续数据时，会触发额外的 ProjectBeforeTaskChangeevent 事件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-653">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="9dd0f-654">解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-654">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="9dd0f-655">修复了下列问题：启用保护实际工作的设置后，用户无法输入按时间分段的基准工作。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-655">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="9dd0f-656">解决了以下问题：在标记为完成后，任务完成百分比错误地更改为小于 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-656">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="9dd0f-657">修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-657">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="9dd0f-658">修复了有时无法正确计算摘要任务日期的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-658">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="9dd0f-659">解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-659">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="9dd0f-660">修复了以下问题：如果你使用的是连接到 Project Web App 的 Project，并且小数分隔符是逗号，则当你尝试向依赖项添加延迟时，TaskDependencies Add 方法将失败。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-660">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="9dd0f-661">修复了以下问题：如果 URL 以 ".com" 结尾，则无法在 Project 桌面端 Project Web App 中打开项目。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-661">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="9dd0f-662">修复了如果粘贴具有多个依赖项的任务，并不能正确复制所有依赖项的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-662">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="9dd0f-663">修正了无法将PDF/XPS从项目保存到 SharePoint 文档库的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-663">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="9dd0f-664">修正了当任务被错误地标记为100%完成，将其更改为小于100%完成的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-664">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="9dd0f-665">修正了当项目摘要任务(项目开始/任务字段)发生更改时，ProjectBeforeTaskChange事件没有触发的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-665">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="9dd0f-666">修复了在资源定义了多个成本费率表时，其余成本有时计算有误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-666">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="9dd0f-667">修复了与 SharePoint 任务列表连接的项目的项目完成日期无法更新的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-667">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="9dd0f-668">修复了以下问题：分配资源对话框中，选择的任务与任务板视图中选择的任务不一样。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-668">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="9dd0f-669">修复了无法打开已进入错误状态的项目的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-669">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="9dd0f-670">Skype</span><span class="sxs-lookup"><span data-stu-id="9dd0f-670">Skype</span></span>

- <span data-ttu-id="9dd0f-671">当用户被告知只能使用团队的策略时，他们仍然可以使用Skype for Business Outlook 插件来安排会议。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-671">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="9dd0f-672">在此更新之后，当客户端读取指示用户为仅限团队的策略并进入仅限会议加入模式后，你将不再能够为Skype安排商务会议。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-672">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="9dd0f-673">另外，如果 Skype for Business Outlook 插件在启动时看到 Skype for Business客户端处于会议加入模式，它将不会激活自己。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-673">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="9dd0f-674">已将跳舞表情符号肤色改为中性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-674">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="9dd0f-675">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-675">Word</span></span>

- <span data-ttu-id="9dd0f-676">解决了当URL包含查询组件时从自定义文档传递(aspx)打开Word文档的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-676">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="9dd0f-677">此更改修复了以下问题：在上一次共同创作会话后，Office 应用程序可能会陷入静默的保存失败状态。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-677">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="9dd0f-678">解决了用户在答复电子邮件或撰写新电子邮件时软件崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-678">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="9dd0f-679">解决了在使用鼠标上的 "X" 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-679">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="9dd0f-680">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-680">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="9dd0f-681">解决了以下问题：在调整形状的大小时，用户可能会丢失内容。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-681">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="9dd0f-682">我们修复了未使用普通样式更新基准样式的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-682">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="9dd0f-683">我们修复了宏 AutoOpen 在 AutoExec 之前运行的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-683">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="9dd0f-684">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-684">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="9dd0f-685">解决了可能导致在拖动应用中的某些内容时发生故障的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-685">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9dd0f-686">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-686">Office Suite</span></span>

- <span data-ttu-id="9dd0f-687">对于旧的、非基于网络服务的共享窗格，在共享窗格处于打开时关闭文档可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-687">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="9dd0f-688">此问题已修复。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-688">This is now fixed.</span></span>

- <span data-ttu-id="9dd0f-689">修复了关闭 Office 文件时可能会导致崩溃的计时问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-689">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="9dd0f-690">我们通过设置Bing插件安装验证默认为真实，并使MSI返回成功视为安装成功，解决了ValidateInstall失败率问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-690">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="9dd0f-691">我们对新的 AppV51 进行了备份，以修复之前 AppV51 中的回归问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-691">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="9dd0f-692">解决了尝试硬链接符号链接时导致更新失败的即点即用问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-692">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="9dd0f-693">修复了即使完成向完整产品的转换也导致显示运行时消息的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-693">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="9dd0f-694">解决此问题的方法是确保服务会正确计算添加的产品。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-694">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="9dd0f-695">我们筛选掉了新添加的产品（确保这些产品同时存在于新配置中），并将其添加到现有产品发布 ID 的末尾。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-695">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="9dd0f-696">解决了用户发现 UI 元素或内容在某些条件下（尤其是在进出演示者视图或使用多个显示器时）不显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-696">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="9dd0f-697">此更改解决了加载和播放动画内容（如 Gif 或 3D 模型）时可能挂起的情况。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-697">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="9dd0f-698">此更改解决了“压缩图片”对话框不保留某些用户设置的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-698">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="9dd0f-699">此更新修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-699">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="9dd0f-700">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-700">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="9dd0f-701">此修复程序解决了阻止同时使用密码限制访问和保护文件的错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-701">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="9dd0f-702">解决了 TabProcGrowth 注册表值为 REG_SZ 类型启用加载项时，windows 上的 office 主机会出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-702">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="9dd0f-703">当注册表键HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth被设置为零时，正在激活一个外接程序时，windows中的office主机故障。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-703">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="9dd0f-704">此更改可修复此问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-704">This change would fix this issue.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-august-11"></a><span data-ttu-id="9dd0f-706">版本2002:8月11日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-706">Version 2002: August 11</span></span>
<span data-ttu-id="9dd0f-707">*版本2002（内部版本12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-707">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="9dd0f-708">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-708">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-710">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-710">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-711">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-711">Excel</span></span>

- <span data-ttu-id="9dd0f-712">修复了以 "建议只读 "打开的文件无法切换到编辑的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-712">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="9dd0f-713">OneNote</span><span class="sxs-lookup"><span data-stu-id="9dd0f-713">OneNote</span></span>

- <span data-ttu-id="9dd0f-714">已删除多余的身份调用，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-714">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="9dd0f-715">改进对共同创作状态的检测，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-715">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="9dd0f-716">提高检测错误的能力和同步体验的质量。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-716">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-717">Outlook</span></span>

- <span data-ttu-id="9dd0f-718">解决了某些租户启动Outlook时出现重大性能问题的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-718">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="9dd0f-719">Skype</span><span class="sxs-lookup"><span data-stu-id="9dd0f-719">Skype</span></span>

- <span data-ttu-id="9dd0f-720">修复了32位Skype for Business客户端在运行数天后启动屏幕共享时可能出现失败的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-720">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-721">Office Suite</span><span class="sxs-lookup"><span data-stu-id="9dd0f-721">Office Suite</span></span>

- <span data-ttu-id="9dd0f-722">修复了一个问题：如果通过组策略关闭自动保存，一些文档可能在打开时不会显示最新的服务器内容，直到用户点击 "可用更新"。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-722">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-july-14"></a><span data-ttu-id="9dd0f-724">版本 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-724">Version 2002: July 14</span></span>
<span data-ttu-id="9dd0f-725">*版本 2002（内部版本 12527.20880）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-725">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="9dd0f-726">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-726">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-728">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-728">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-729">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-729">Excel</span></span>

- <span data-ttu-id="9dd0f-730">加快本地 OneDrive 文件夹上可用文件的加载速度。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-730">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="9dd0f-731">修正了以下问题：保存到 SharePoint / OneDrive 时，自定义功能区标签的CustomUI XML被删除。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-731">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="9dd0f-732">解决了以下问题：由于加载程序是按字母顺序加载的，而不是按用户指定的顺序加载，因此会出现“此工作簿目前由另一个工作簿引用，无法关闭”的错误信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-732">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="9dd0f-733">修复了单击超链接到已打开的工作簿中某个位置时，工作簿可能被隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-733">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="9dd0f-734">我们解决了某些复制粘贴图表链接使用映射驱动器地址而不是通用地址的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-734">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="9dd0f-735">解决删除含合并单元格的列时的性能问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-735">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="9dd0f-736">修复了在“打印”对话框中的打印机列表中可以重复打印机名称的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-736">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="9dd0f-737">我们修复了包含多个已定义名称的公式的工作表在保存文件时导致时间延长的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-737">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-738">Outlook</span></span>

- <span data-ttu-id="9dd0f-739">我们解决了当使用多个不同分辨率的显示器时，IME（输入法编辑器）窗口会重叠通过IME输入的底层文本的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-739">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="9dd0f-740">解决了在接近时区定义更改时导致在错误时间显示重复约会或会议的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-740">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="9dd0f-741">解决了导致用户在更新 Outlook 中的“规则”时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”消息的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-741">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="9dd0f-742">解决了未选中“下载共享”文件夹时导致共享日历会议“响应选项”中缺少“允许转发”选项的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-742">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="9dd0f-743">解决了导致类别偶尔从电子邮件中消失的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-743">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="9dd0f-744">解决了导致代理人在不同计算机上看到共享邮箱的不同文件夹层次结构的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-744">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="9dd0f-745">解决了导致在编辑经理日历上的现有日历约会时，代表收到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-745">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="9dd0f-746">修复了在编辑主题后导致 NDR 邮件的正文从 Unicode 更改为 ASCII 的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-746">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="9dd0f-747">解决了两个加载项将按钮添加到同一功能区组时导致用户崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-747">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="9dd0f-748">解决了导致用户无法向个人通讯组列表发送电子邮件地址的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-748">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="9dd0f-749">解决了将租户默认权限配置为“任何人”时，导致链接无法以正确的租户默认权限添加到电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-749">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="9dd0f-750">解决了用户在安全对话框中选择”save” 选项时无法将 OneDrive 附件从租户外部保存到本地计算机的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-750">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="9dd0f-751">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-751">Word</span></span>

- <span data-ttu-id="9dd0f-752">解决了启用 FileBlick\Word2007Files 策略时出现的协调问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-752">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="9dd0f-753">我们修复了添加已重命名的查找字段时，无法使用 Word QuickPart 的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-753">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-754">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-754">Office Suite</span></span>

- <span data-ttu-id="9dd0f-755">解决了用户在共同编辑大型 PowerPoint 文件时会遇到过多的网络和CPU使用率的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-755">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="9dd0f-756">我们对新的 AppV51 进行了备份，以修复之前 AppV51 中的回归问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-756">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="9dd0f-757">解决了 TabProcGrowth 注册表值为 REG_SZ 类型启用加载项时，windows 上的 office 主机会出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-757">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-june-09"></a><span data-ttu-id="9dd0f-759">版本 2002：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-759">Version 2002: June 09</span></span>
<span data-ttu-id="9dd0f-760">*版本 2002（内部版本 12527.20720）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-760">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="9dd0f-761">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-761">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-763">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-763">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-764">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-764">Excel</span></span>

- <span data-ttu-id="9dd0f-765">修复了以下问题：在文件重新打开后，如果文件路径太长，外部链接会停止工作。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-765">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="9dd0f-766">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-766">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="9dd0f-767">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-767">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="9dd0f-768">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-768">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="9dd0f-769">在筛选列表中插入列所需的时间可能比预期更长。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-769">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="9dd0f-770">修复了以下问题：将以公式开头的@符号被视为隐式交集运算符。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-770">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-771">Outlook</span></span>

- <span data-ttu-id="9dd0f-772">启用直接通过本机 Teams 客户端加入 Teams 会议。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-772">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="9dd0f-773">解决了针对 Outlook 未能向使用M365 Business Plus计划的付费用户启用数据丢失保护策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-773">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="9dd0f-774">解决了导致用户无法完成 Gmail 身份验证提示时使用错误的浏览器仿真设置的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-774">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="9dd0f-775">解决了导致服务器操作系统上的 Outlook 用户无法看到错误的问题，"防病毒状态：无效。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-775">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="9dd0f-776">此版本的 Windows 支持防病毒检测，但没有发现防病毒，尽管已正确配置防病毒。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-776">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="9dd0f-777">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-777">Word</span></span>

- <span data-ttu-id="9dd0f-778">修复了以下问题：在使用“快速打印”打印后尝试进行编辑时，文档中的字词对齐方式会被打乱。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-778">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-779">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-779">Office Suite</span></span>

- <span data-ttu-id="9dd0f-780">我们通过将后台的频道名称更新为 2020 年 1 月的分支中的新频道名称来解决此问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-780">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="9dd0f-781">我们已修复此问题，接下来，如果设备是由策略管理的，则不会调用 DMS Audience API。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-781">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="9dd0f-782">解决了在单个事务中添加和删除应用时删除不完整的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-782">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="9dd0f-783">当注册表键HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth被设置为零时，正在激活一个外接程序时，windows中的office主机故障。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-783">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="9dd0f-784">此更改可修复此问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-784">This change would fix this issue.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-may-12"></a><span data-ttu-id="9dd0f-786">版本 2002：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-786">Version 2002: May 12</span></span>
<span data-ttu-id="9dd0f-787">*版本 2002（内部版本 12527.20612）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-787">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="9dd0f-788">[此处](./microsoft365-apps-security-updates.md)列出了安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-788">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-790">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-790">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9dd0f-791">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-791">Excel</span></span>

- <span data-ttu-id="9dd0f-792">打开包含对许多其他工作簿（尤其是隐藏窗口）的引用的工作簿将比预期的慢。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-792">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="9dd0f-793">在某些情况下，打开 CSV 文件所花费的时间比预期的长。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-793">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="9dd0f-794">在具有不同缩放级别的工作簿之间切换时，在某些情况下 Excel 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-794">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="9dd0f-795">修复了一个有关 VBA 的问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-795">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="9dd0f-796">从按颜色筛选的列复制的数据有时无法正确粘贴。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-796">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="9dd0f-797">修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-797">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="9dd0f-798">含有数字签名且在 Excel 2016 中保存的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-798">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="9dd0f-799">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-799">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="9dd0f-800">使用 Range.Value 和 Range.Value2 (VBA) 会导致公式作为动态数组输入。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-800">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="9dd0f-801">OneNote</span><span class="sxs-lookup"><span data-stu-id="9dd0f-801">OneNote</span></span>

- <span data-ttu-id="9dd0f-802">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-802">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="9dd0f-803">显示了一条通知，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-803">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="9dd0f-804">通过暂时减少 OneNote 2016 中版本历史记录页面的数量和同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-804">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="9dd0f-805">通过暂时禁用 OneNote 2016 中的回收站，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-805">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="9dd0f-806">当用户尝试删除通常将发送到回收站中的数据时，系统会询问用户是希望保留还是永久删除数据。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-806">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="9dd0f-807">通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-807">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="9dd0f-808">在 OneNote 2016 中，通过暂时将联机笔记本中的嵌入式文件和图像的下载推迟到用户导航到相应页面时进行，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-808">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="9dd0f-809">通过暂时禁用 OneNote 2016 中的应用内视频录制功能，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-809">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="9dd0f-810">本地笔记本不受此措施影响。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-810">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="9dd0f-811">在 OneNote 2016 中，通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-811">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="9dd0f-812">对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-812">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-813">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-813">Outlook</span></span>

- <span data-ttu-id="9dd0f-814">解决了导致文件夹窗格宽度意外改变的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-814">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="9dd0f-815">解决了导致用户在某次 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-815">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="9dd0f-816">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-816">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="9dd0f-817">此更新修复了 Microsoft Outlook 在用户查看或撰写邮件时不显示当前敏感度标签的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-817">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="9dd0f-818">解决了导致用户无法向个人通讯组列表发送电子邮件地址的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-818">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9dd0f-819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-819">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-820">修复了在用户打开的文件副本中含有改进的批注时为用户中继正确消息的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-820">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="9dd0f-821">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-821">Word</span></span>

- <span data-ttu-id="9dd0f-822">解决了可能无法正确启动 Access 和 Publisher（具体取决于安装的语言）的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-822">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="9dd0f-823">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-823">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="9dd0f-824">我们修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-824">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-825">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-825">Office Suite</span></span>

- <span data-ttu-id="9dd0f-826">这是一个修复程序，用于解决在客户端缓存文件时，Project 应用不应阻止网络的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-826">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="9dd0f-827">我们已经解决了内部操作在失败时引发异常而不是进行记录并继续的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-827">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="9dd0f-828">受影响的用户将不再被阻止接收更新。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-828">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="9dd0f-829">此更改可确保草绘轮廓在功能区中正常工作。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-829">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="9dd0f-830">修复了从具有某些特定代理配置的本地位置打开文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-830">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="9dd0f-831">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-831">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="9dd0f-832">此更新修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-832">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="9dd0f-833">此更新修复了 Microsoft Word 中的一个问题，即如果某个敏感度标签策略应用了页眉、页脚或水印，则在应用该标签时插入的长度超过 255 个字符的文本随后将无法通过更改或删除该标签来标识和删除。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-833">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="9dd0f-834">修复了可在 Office 切换会话期间防止崩溃并提高用户体验可靠性的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-834">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="9dd0f-835">此 bug 将更新增强型配置服务 (ECS) url 终结点。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-835">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="9dd0f-836">调用此较新的终结点可以提高从 ECS 获取数据的成功率。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-836">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-april-14"></a><span data-ttu-id="9dd0f-838">版本 2002：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-838">Version 2002: April 14</span></span>
<span data-ttu-id="9dd0f-839">*版本 2002（内部版本 12527.20442）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-839">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="9dd0f-840">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-840">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="9dd0f-841">功能更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-841">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-842">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-842">Excel</span></span>

- <span data-ttu-id="9dd0f-843">**键入可返回多个值的公式：** 现可键入返回多个值的公式，它们将自动溢出到相邻的单元格中。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-843">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="9dd0f-844">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-844">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="9dd0f-845">**6 个强大的函数：** 我们添加了六个新函数来增强你的电子表格：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-845">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="9dd0f-846">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-846">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="9dd0f-847">**向左看，向右看… XLOOKUP 在此！** 使用 XLOOKUP 在表或区域中逐行查找所需内容。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-847">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="9dd0f-848">
  [了解更多](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="9dd0f-848">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-850">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-850">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-851">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-851">Excel</span></span>

- <span data-ttu-id="9dd0f-852">在某些情况下，重新打开嵌入 Word 或 PowerPoint 的工作簿时，Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-852">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="9dd0f-853">当另存为 CSV 文件时，在某些情况下，Excel 可能将所有列合并为一个列。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-853">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="9dd0f-854">在受保护工作表中的某个区域内使用 Range.ClearContents 的时间可能比预期的要长。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-854">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="9dd0f-855">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-855">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="9dd0f-856">与功能区交互的 VBA 宏可能在 ScreenUpdating 意外设置为 True 的情况下运行。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-856">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="9dd0f-857">解决了如果关闭了源代码簿，则外部链接不会在填充（向下填充、横跨填充等）时更新的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-857">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="9dd0f-858">使用 VBA 的应用程序。在某些情况下，评估无法用于用户定义的功能。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-858">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="9dd0f-859">解决了从模板创建图表时出现的性能问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-859">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-860">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-860">Outlook</span></span>

- <span data-ttu-id="9dd0f-861">解决了在某些方案中导致组页眉意外展开的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-861">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="9dd0f-862">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-862">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="9dd0f-863">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-863">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="9dd0f-864">解决了导致附件工具中缺少“保存到云”按钮的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-864">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9dd0f-865">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-865">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-866">改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-866">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="9dd0f-867">Project</span><span class="sxs-lookup"><span data-stu-id="9dd0f-867">Project</span></span>

- <span data-ttu-id="9dd0f-868">解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-868">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="9dd0f-869">解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-869">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="9dd0f-870">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-870">Word</span></span>

- <span data-ttu-id="9dd0f-871">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-871">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="9dd0f-872">我们修复了表格中文本适应的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-872">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="9dd0f-873">我们修复了插入水平线不短且居中的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-873">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-march-10"></a><span data-ttu-id="9dd0f-875">版本 2002：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-875">Version 2002: March 10</span></span>
<span data-ttu-id="9dd0f-876">*版本 2002（生成号 12527.20278）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-876">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="9dd0f-877">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-877">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="9dd0f-879">功能更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-879">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9dd0f-880">Access</span><span class="sxs-lookup"><span data-stu-id="9dd0f-880">Access</span></span>

- <span data-ttu-id="9dd0f-881">**快速查找链接的表格：** 新的“搜索”框使查找链接的表格成为一项轻松的乐事。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-881">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="9dd0f-882">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-882">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="9dd0f-883">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-883">Excel</span></span>

- <span data-ttu-id="9dd0f-884">**使用 \@提及** 功能引起他人的注意：在批注中使用 @提及，以在需要同事的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-884">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="9dd0f-885">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-885">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="9dd0f-886">**查找要找的内容：** 搜索命令、人员、文件、照片、Web 文章等等。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-886">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="9dd0f-887">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-887">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="9dd0f-888">**手绘：** 让工作簿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-888">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="9dd0f-889">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-889">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="9dd0f-890">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-890">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="9dd0f-891">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-891">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="9dd0f-892">**关注剩余待办事项：** 选择“解决”可折叠评论并突出显示待处理的项目。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-892">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="9dd0f-893">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-893">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="9dd0f-894">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-894">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="9dd0f-895">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-895">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="9dd0f-896">**数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-896">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="9dd0f-897">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-897">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="9dd0f-898">**随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-898">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="9dd0f-899">**获取工作簿统计信息：** 工作簿统计信息提供工作簿内容的概述，可帮助你更轻松地发现内容。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-899">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="9dd0f-900">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-900">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9dd0f-901">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-901">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9dd0f-902">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-902">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="9dd0f-903">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-903">Outlook</span></span>

- <span data-ttu-id="9dd0f-904">**将 LinkedIn 网络连接到 Outlook：** 以安全的方式将 LinkedIn 帐户连接到 Microsoft 帐户，直接在“人员”卡片中查看 LinkedIn 中的信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-904">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="9dd0f-905">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-905">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="9dd0f-p176">**所有加密选项都在一个位置：** 只需转到“选项”>“加密”以选择如何保护电子邮件。[了解更多](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="9dd0f-p176">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="9dd0f-908">**Outlook 中的插入链接菜单将插入包含租户管理员定义的权限的链接：** Outlook 插入链接 MRU 中的链接将插入仅对已经拥有权限的用户有效的链接。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-908">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="9dd0f-909">这通常会导致请求获得文档访问权限的用户之间发生往来电子邮件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-909">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="9dd0f-910">我们已更新了此体验，现在该链接将通过租户管理员设置的默认权限进行插入。对于 MSIT，这“可供组织编辑”，因此收到以此方式共享的链接的所有内部用户都可以访问它。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-910">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="9dd0f-911">**在有拼写错误的情况下进行搜索：** 即使你的拼写有误，Outlook 仍将找到你在查找的内容。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-911">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="9dd0f-912">**轻松发现网络钓鱼邮件：** 垃圾邮件和网络钓鱼邮件具有不同的外观，因此你可以轻松从收件箱中识别并删除它们。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-912">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="9dd0f-913">**针对攻击的高级防护：** 通过 Office 365 高级威胁防护, 可通过电子邮件主题中的超链接、附加邮件、签名邮件、网络路径等的方式抵御攻击。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-913">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="9dd0f-914">**让我把它画出来：** 在图片上进行涂鸦或添加绘图画布以使用墨迹表达你的想法。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-914">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="9dd0f-915">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-915">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="9dd0f-916">**查看搜索结果中的相关消息：** Outlook 会分析搜索词，并在搜索结果顶部显示最相关的电子邮件信息。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-916">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="9dd0f-917">还会在“热门搜索结果”部分看到按日期排序的所有搜索结果。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-917">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="9dd0f-918">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-918">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="9dd0f-919">**获取位置建议：** 在安排约会和会议时，开始键入位置，Outlook 就会推荐会议室、地址和其他邻近位置。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-919">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="9dd0f-920">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-920">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="9dd0f-921">**在屏幕上显示更多邮件：** 选择“视图”>“使用更紧密的间距”来调整邮件之间的间距。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-921">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="9dd0f-922">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-922">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="9dd0f-923">**以不同的亮度查看邮件：** 使用“太阳”/“月亮”按钮在阅读窗格中的明暗背景之间切换。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-923">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="9dd0f-924">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-924">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="9dd0f-925">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-925">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9dd0f-926">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-926">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9dd0f-927">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-927">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="9dd0f-928">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-928">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-929">**PowerPoint 中的快速实时协作：** 在 PowerPoint 中快速展开实时协作</span><span class="sxs-lookup"><span data-stu-id="9dd0f-929">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="9dd0f-930">**新增校对工具：** 无需在语言方面倍感压力。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-930">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="9dd0f-931">PowerPoint 现在可提供语法和写作建议。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-931">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="9dd0f-932">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-932">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="9dd0f-933">**实时字幕和对白字幕：** 演示者的文字会作为字幕自动显示在屏幕上或翻译成你所选语言的对白字幕。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-933">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="9dd0f-934">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-934">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="9dd0f-p186">**你来计算，我们来设置格式：** 我们将书写数学表达式更改成标准字符。只需选择“将墨迹转换为数学公式”，再选择手写笔记即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="9dd0f-p186">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="9dd0f-938">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-938">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="9dd0f-939">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-939">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="9dd0f-940">**查找并修复缺失的幻灯片标题：** 幻灯片标题可为你的推销词增色添彩，并使所有用户都可以访问你的幻灯片。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-940">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="9dd0f-941">辅助功能检查器显示标题缺失位置，以便你可以快速添加标题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-941">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="9dd0f-942">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-942">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="9dd0f-943">**手绘：** 让演示文稿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-943">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="9dd0f-944">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-944">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="9dd0f-945">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-945">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="9dd0f-946">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-946">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="9dd0f-947">**将插图另存为 SVG**：将图表、形状或其他插图另存为可缩放矢量图形，这样做可以调整其大小，而不会降低图像质量。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-947">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="9dd0f-948">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-948">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="9dd0f-949">**打印讲义上的幻灯片编号：** 幻灯片编号将会自动包括在讲义上。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-949">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="9dd0f-950">打开或是关闭它们，全都取决于你。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-950">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="9dd0f-951">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-951">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="9dd0f-952">**墨迹即时重播：** 在幻灯片上使用墨迹时，可应用重播动画，在幻灯片放映期间重播墨迹的实际绘制过程。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-952">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="9dd0f-953">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-953">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="9dd0f-954">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-954">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="9dd0f-955">**全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-955">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="9dd0f-956">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-956">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="9dd0f-957">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-957">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="9dd0f-958">**如果可以重复使用，为何还要重新创建呢？：** 通过重新使用你创建的幻灯片或其他人与你共享的幻灯片来节省时间。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-958">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="9dd0f-959">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-959">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="9dd0f-960">**在 PowerPoint for Office 365 中将手写墨迹更改为形状、文本或数学公式：** 从自由格式的墨迹转到几条笔划中的 Office 形状、文本或数学表达式。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-960">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="9dd0f-961">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-961">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="9dd0f-962">**用墨迹绘制精彩绝伦的幻灯片：** 将墨迹转换为标准形状和文本，然后从 PowerPoint 设计器获取智能幻灯片设计灵感。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-962">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="9dd0f-963">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-963">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="9dd0f-964">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-964">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9dd0f-965">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-965">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9dd0f-966">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-966">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="9dd0f-967">Visio</span><span class="sxs-lookup"><span data-stu-id="9dd0f-967">Visio</span></span>

- <span data-ttu-id="9dd0f-968">**返回到“犯罪”的场景：** 使用“犯罪场景调查模板”中的新证据、室内和户外模具，仔细地重新创建罪犯的犯罪场景。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-968">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="9dd0f-969">**在 Excel 中制作优美的 Visio 图表：** 通过将数据置于工作表上来创建流程图或组织结构图。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-969">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="9dd0f-970">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-970">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="9dd0f-971">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-971">Word</span></span>

- <span data-ttu-id="9dd0f-972">**简历编辑器加入 LinkedIn 简历助手：** 简历编辑器提供了一系列专为简历量身定制的语法和样式检查，以使你的写作更加精确和专业。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-972">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="9dd0f-973">**修复了 3D 对象合并导致的文档损坏问题：** 修复了 3D 对象合并导致的文档损坏问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-973">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="9dd0f-974">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-974">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="9dd0f-975">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-975">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="9dd0f-976">**色彩丰富的协作：** 批注和修订由参与者进行颜色编码，以便你能够轻松看到协作者是谁。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-976">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="9dd0f-977">**协同编辑启用宏的文档：** 将 docm 文件保存在 OneDrive for Business 上，并与协作者实时进行编辑。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-977">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="9dd0f-978">**合著改进**：提高了在具有修订的文档中进行合著时的 Word 性能。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-978">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="9dd0f-979">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-979">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9dd0f-980">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-980">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9dd0f-981">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-981">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="9dd0f-982">**其他人可以快速查看你所做的更改：** 共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-982">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="9dd0f-983">**手绘：** 让文档中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-983">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="9dd0f-984">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-984">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="9dd0f-985">**精确擦除：** 从两个橡皮擦尺寸中进行选择以修复小墨迹缺陷。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-985">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="9dd0f-986">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-986">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="9dd0f-987">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-987">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="9dd0f-988">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-988">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="9dd0f-989">了解更多详细信息</span><span class="sxs-lookup"><span data-stu-id="9dd0f-989">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="9dd0f-990">**合著改进：** 提高了合著时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-990">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="9dd0f-991">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-991">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="9dd0f-992">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-992">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="9dd0f-993">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-993">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="9dd0f-994">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-994">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="9dd0f-995">了解更多</span><span class="sxs-lookup"><span data-stu-id="9dd0f-995">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-998">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-998">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9dd0f-999">Access</span><span class="sxs-lookup"><span data-stu-id="9dd0f-999">Access</span></span>

- <span data-ttu-id="9dd0f-1000">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现“查询已损坏”错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1000">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="9dd0f-1001">此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1001">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="9dd0f-1002">此更新修复了使用 ADODB 的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1002">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="9dd0f-1003">VB 代码中的记录器对象可能会错误地报告错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1003">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="9dd0f-1004">Access 模板将不会再导致数据库中的附件列出现故障。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1004">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="9dd0f-1005">在实例化模板后，你现在应该可以将附件字段添加到数据库中。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1005">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="9dd0f-1006">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1006">Excel</span></span>

- <span data-ttu-id="9dd0f-1007">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1007">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="9dd0f-1008">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1008">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="9dd0f-1009">修复了一个问题，该问题导致某些用户在将文本转换为包含单元格（具有溢出数组）的列时遇到崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1009">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="9dd0f-1010">此更新修复了导致公式栏以不同于预期的字体显示文本的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1010">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="9dd0f-1011">某些区域设置的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1011">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="9dd0f-1012">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1012">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="9dd0f-1013">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1013">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="9dd0f-1014">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1014">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="9dd0f-1015">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1015">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="9dd0f-1016">某些本地化版本的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1016">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="9dd0f-1017">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1017">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="9dd0f-1018">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1018">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="9dd0f-1019">修复了某些用户可能遇到的嵌入和链接对象 (OLE) 问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1019">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="9dd0f-1020">我们修复了数据透视图的右键单击菜单，以便启用“显示详细信息”选项。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1020">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="9dd0f-1021">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1021">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="9dd0f-1022">修复了当工作簿中存在外部链接时某些用户可能遇到多个弹出窗口的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1022">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="9dd0f-1023">修复了未显示上下文菜单中的批注命令的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1023">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="9dd0f-1024">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1024">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="9dd0f-1025">修复了 CUBEVALUE 函数有时会返回错误结果的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1025">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-1026">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1026">Outlook</span></span>

- <span data-ttu-id="9dd0f-1027">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1027">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="9dd0f-1028">解决了导致用户在检索云设置时在 Outlook 中遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1028">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="9dd0f-1029">解决了导致搜索框在高 dpi 模式下未正确对齐的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1029">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="9dd0f-1030">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1030">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="9dd0f-1031">解决了在某些情况下导致用户看到电子邮件发送地址与显示的 SMTP 地址不匹配的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1031">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="9dd0f-1032">此更改恢复了在邮件头中查看多行主题的功能。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1032">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="9dd0f-1033">我们修复了可能会阻止文件保存到 WebDAV 位置的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1033">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="9dd0f-1034">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1034">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="9dd0f-1035">解决了导致第三方应用程序无法发送电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1035">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="9dd0f-1036">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1036">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="9dd0f-1037">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1037">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="9dd0f-1038">解决了导致 Outlook 在同步滑块设置为较小的设置时出现意外同步所有邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1038">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="9dd0f-1039">解决了导致使用Black Theme的用户在 "From "下拉菜单在白色背景上显示白色文本的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1039">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="9dd0f-1040">解决了导致用户在取消帐户设置时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1040">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="9dd0f-1041">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1041">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="9dd0f-1042">解决了一个问题，该问题导致在某些情况下无法使用相关选项来禁用标记项目突出显示。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1042">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="9dd0f-1043">解决了导致用户在打开规则对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1043">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="9dd0f-1044">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1044">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="9dd0f-1045">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1045">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="9dd0f-1046">解决了在多个窗口中查看同一项目时可能会导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1046">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="9dd0f-1047">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1047">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="9dd0f-1048">解决了导致用户无法打开某些定期日历项目实例的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1048">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="9dd0f-1049">解决了导致 Exchange 2010 服务器上的邮箱用户在将附件添加到日历项目时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1049">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="9dd0f-1050">解决了导致用户在答复数字签名邮件时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1050">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="9dd0f-1051">解决了导致会议中的“位置”字段意外更新的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1051">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="9dd0f-1052">解决了在会议的位置字段中导致逗号变为分号的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1052">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="9dd0f-1053">解决了导致会议位置在清除后意外添加回会议的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1053">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="9dd0f-1054">解决了与巴西时区中设置的会议和约会有关的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1054">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="9dd0f-1055">解决了关闭辅助功能检查器窗格后按 "S "键时，用户会看到邮件意外发送的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1055">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="9dd0f-1056">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1056">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="9dd0f-1057">解决了导致 Web 加载项访问数字权限管理邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1057">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="9dd0f-1058">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1058">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="9dd0f-1059">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1059">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9dd0f-1060">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1060">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-1061">我们修复了 Shape.Paste 方法的问题：当用户使用 Shape.Paste 方法复制和粘贴形状时，它会将所选内容更改为粘贴的形状。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1061">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="9dd0f-1062">解决了在旧版 PPT 批注中使用上下文菜单时可能导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1062">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="9dd0f-1063">Project</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1063">Project</span></span>

- <span data-ttu-id="9dd0f-1064">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1064">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="9dd0f-1065">修复了以下问题：固定持续时间类型的 100％ 任务可能会错误地将其完成百分比计算为小于 100％ 完成。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1065">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="9dd0f-1066">修复了有时无法正确计算摘要任务日期的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1066">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="9dd0f-1067">修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1067">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="9dd0f-1068">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1068">Word</span></span>

- <span data-ttu-id="9dd0f-1069">我们修复了以下问题：在某些情况下，保存现有文件始终会导致显示“另存为”对话框，而该文件从不实际保存。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1069">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="9dd0f-1070">构建基块管理器可能显示无效的警报：“你已更改样式、构建基块”。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1070">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-1071">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1071">Office Suite</span></span>

- <span data-ttu-id="9dd0f-1072">此更改解决了某些包含标记的散点图呈现缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1072">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="9dd0f-1073">此更改解决了所报告的使用 Intel 集成 GPU 的图形适配器的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1073">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="9dd0f-1074">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1074">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="9dd0f-1075">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1075">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="9dd0f-1076">修复了从同一 SharePoint 库在 Word/Excel/PowerPoint 中打开多个文件时，只能打开第一个文件进行策略符合性扫描的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1076">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-february-11"></a><span data-ttu-id="9dd0f-1078">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1078">Version 1908: February 11</span></span>
<span data-ttu-id="9dd0f-1079">*版本 1908（内部版本 11929.20606）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1079">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="9dd0f-1080">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1080">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-1082">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1082">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-1083">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1083">Excel</span></span>

- <span data-ttu-id="9dd0f-1084">此更新修复了以下问题：当使用 VBA 向图表的页眉/页脚添加图像时，将会导致出现错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1084">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="9dd0f-1085">修复了在打印预览中或打印时分组框控件的边框不可见的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1085">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="9dd0f-1086">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1086">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="9dd0f-1087">修复了以下问题：在保存包含图表的工作簿时，图表标题中的图像文件大小增加。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1087">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="9dd0f-1088">修复了以下问题：在使所选区域与交叉引用的工作簿保持同步时，导致交叉引用工作簿中的 DBCS 字符出现损坏。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1088">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="9dd0f-1089">解决了使用自动调整功能调整行高时复选框控件缩小的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1089">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="9dd0f-1090">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1090">Outlook</span></span>

- <span data-ttu-id="9dd0f-1091">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1091">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="9dd0f-1092">解决了导致用户在处理冲突消息时遇到同步失败的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1092">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="9dd0f-1093">解决了导致用户在启动 Outlook 时在“正在加载个人资料”屏幕上遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1093">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="9dd0f-1094">解决了导致用户在更改视图时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1094">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="9dd0f-1095">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1095">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="9dd0f-1096">[此处](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是单个 KB，包含针对先前版本记录的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1096">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="9dd0f-1097">解决了一个问题，该问题导致用户在将共享日历文件夹同步到 OST 时遇到问题，这导致他们与这些文件夹进行交互时出现权限错误。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1097">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9dd0f-1098">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1098">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-1099">改进了复制粘贴方案，即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1099">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="9dd0f-1100">修复了导致协作用户之间的效率降低的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1100">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="9dd0f-1101">修复了以下问题：当逐步打开文件时，如果其中一张幻灯片包含多个嵌入式媒体流，则可能会出现问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1101">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="9dd0f-1102">我们修复了以下问题：首次启动 PowerPoint 时，不受信任的加载项可能不会显示安全警告消息栏。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1102">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="9dd0f-1103">Project</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1103">Project</span></span>

- <span data-ttu-id="9dd0f-1104">修复了以下问题：由于基准日历发生更改时未更新资源日历，时间表与项目计划之间的实际工时可能不同。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1104">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="9dd0f-1105">Word</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1105">Word</span></span>

- <span data-ttu-id="9dd0f-1106">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1106">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-1107">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1107">Office Suite</span></span>

- <span data-ttu-id="9dd0f-1108">此更改解决了打开损坏的文件后正确渲染图像的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1108">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-january-14"></a><span data-ttu-id="9dd0f-1110">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1110">Version 1908: January 14</span></span>
<span data-ttu-id="9dd0f-1111">*版本 1908（内部版本 11929.20562）*</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1111">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="9dd0f-1112">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1112">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="9dd0f-1114">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9dd0f-1115">Excel</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1115">Excel</span></span>

- <span data-ttu-id="9dd0f-1116">荷兰语文档标题快捷键提示已更改为 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1116">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="9dd0f-1117">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1117">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="9dd0f-1118">发生问题时，将无法从加载项打开的 WPF （Windows Presentation Foundation）窗体的组合框中选择项目。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1118">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="9dd0f-1119">Outlook</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1119">Outlook</span></span>

- <span data-ttu-id="9dd0f-1120">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1120">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="9dd0f-1121">解决了在使用备用发件人时导致无法显示策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1121">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="9dd0f-1122">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1122">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9dd0f-1123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1123">PowerPoint</span></span>

- <span data-ttu-id="9dd0f-1124">我们修复了将一个幻灯片从一个演示文稿复制到另一个演示文稿时，可能创建重复母版的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1124">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="9dd0f-1125">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1125">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="9dd0f-1126">Office 套件</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1126">Office Suite</span></span>

- <span data-ttu-id="9dd0f-1127">修复了 Office 更新消息以与预期不同的语言显示的问题。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1127">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="9dd0f-1128">今后，Office 更新消息将正确匹配 Windows 显示语言。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1128">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="9dd0f-1129">解决了以下问题：在某些情况下，如果不是管理员，并且系统帐户没有网络连接，则不会应用更新。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1129">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

> [!NOTE]
> <span data-ttu-id="9dd0f-1131">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="9dd0f-1131">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (不修改管理中心元数据内容启动)
[//]: # (|Win32|FRDC|预览体验| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13801.20294|版本2102 年-march-09|)
[//]: # (|Win32|FRDC|预览体验成员| |16.0.13127.21216 | 版本-2008年2月09日|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.21064 | 版本-2008年1月12日|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20910|2008 年 12 月 8 日版|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20760|2008 年 11 月 10 日版|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20638|2008 年 10 月 13 日版|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|2002 年 8 月 11 日版|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.12527.20880|2002 年 7 月 14 日版|)
[//]: # (不修改管理中心元数据内容结束)
