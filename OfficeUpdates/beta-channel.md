---
title: Beta 频道发行说明
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为“预览体验成员 - 快”受众提供关键新功能、修复程序或已知问题的最新列表
ms.openlocfilehash: ab1953f105cbab856ac183335fb54edb538b5d43
ms.sourcegitcommit: 6bd9e41014037650170125aaed9847880d438645
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/19/2020
ms.locfileid: "44814301"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="b1460-103">Office 预览体验成员发行说明</span><span class="sxs-lookup"><span data-stu-id="b1460-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="b1460-104">本文包含适用于 Windows desktop 的 Word、Excel、PowerPoint、Outlook、Access 和 Project 的 Beta 频道版本的发行说明。</span><span class="sxs-lookup"><span data-stu-id="b1460-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="b1460-105">每周，我们都会提供精彩集锦，其中包含我们希望你了解的有趣新功能、重要修补程序和所有重要问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="b1460-106">请注意，我们经常在一段时间内向 Beta 频道推出功能（甚至有时也会进行修复）。</span><span class="sxs-lookup"><span data-stu-id="b1460-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="b1460-107">这可以让我们确保将功能向更多的受众发布之前，所用功能均可正常使用。</span><span class="sxs-lookup"><span data-stu-id="b1460-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="b1460-108">因此，如果你没有看到下面所述的功能，请不要担心，你最终会获取这些功能。</span><span class="sxs-lookup"><span data-stu-id="b1460-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="b1460-109">我们正在对 Microsoft 365 应用的更新频道进行一些更改，包括添加新的更新频道（月度企业版频道）和更改现有更新频道的名称。</span><span class="sxs-lookup"><span data-stu-id="b1460-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="b1460-110">若要了解详细信息，请[阅读这篇文章](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="b1460-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="b1460-111">发行说明每周发布一次，可能是多个版本的编译。</span><span class="sxs-lookup"><span data-stu-id="b1460-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="b1460-112">发行说明发布日期可能与实际内部版本发布日期不一致。</span><span class="sxs-lookup"><span data-stu-id="b1460-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (请勿移除)

[//]: # (请勿移除功能详细信息内容开头)

## <a name="version-2007-june-19"></a><span data-ttu-id="b1460-115">版本2007：6月19日</span><span class="sxs-lookup"><span data-stu-id="b1460-115">Version 2007: June 19</span></span>
<span data-ttu-id="b1460-116">*版本2007（内部版本13012.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-116">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-118">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-119">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-119">Excel</span></span>

- <span data-ttu-id="b1460-120">我们修复了以下问题：在将工作簿保存到 SharePoint/OneDrive 时，删除了自定义功能区选项卡的 CustomUI XML。</span><span class="sxs-lookup"><span data-stu-id="b1460-120">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="b1460-121">我们修复了以下问题：在仅建议只读文件时，工作簿是只读的。</span><span class="sxs-lookup"><span data-stu-id="b1460-121">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-122">Outlook</span></span>

- <span data-ttu-id="b1460-123">我们解决了以下问题：在使用具有不同分辨率的多个监视器时，输入法编辑器（IME）窗口将与通过 IME 输入的基础文本重叠。</span><span class="sxs-lookup"><span data-stu-id="b1460-123">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="b1460-124">我们解决的问题导致用户在关闭之前保存的约会时看到以下错误： "无法保存该项目，因为它已被另一个用户或另一个窗口更改。</span><span class="sxs-lookup"><span data-stu-id="b1460-124">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="b1460-125">是否要在默认文件夹中为该项目创建一个副本？</span><span class="sxs-lookup"><span data-stu-id="b1460-125">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="b1460-126">我们解决了以下问题：迷你日历中的日期未能以粗体显示为日本的用户。</span><span class="sxs-lookup"><span data-stu-id="b1460-126">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="b1460-127">我们修复了一个问题，该问题会阻止日历提醒显示在不到一周时间内的会议的确切时间。</span><span class="sxs-lookup"><span data-stu-id="b1460-127">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-128">PowerPoint</span></span>

- <span data-ttu-id="b1460-129">我们修复了以下问题：在实时共同创作会话过程中，用户的状态指示器未在共同创作库中刷新。</span><span class="sxs-lookup"><span data-stu-id="b1460-129">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-130">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-130">Project</span></span>

- <span data-ttu-id="b1460-131">我们修复了以下问题：如果固定工期任务已完成100% 但未指定实际完成时间，则任务完成百分比将显示为小于100%。</span><span class="sxs-lookup"><span data-stu-id="b1460-131">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-132">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-132">Word</span></span>

- <span data-ttu-id="b1460-133">我们修复了以下问题： HTML 超链接颜色没有正确呈现。</span><span class="sxs-lookup"><span data-stu-id="b1460-133">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b1460-134">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-134">Office Suite</span></span>

- <span data-ttu-id="b1460-135">我们修复了以下问题：不是基于 http 或 https 的 Url 未显示在最近使用过的列表中。</span><span class="sxs-lookup"><span data-stu-id="b1460-135">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2007-june-12"></a><span data-ttu-id="b1460-137">版本2007：6月12日</span><span class="sxs-lookup"><span data-stu-id="b1460-137">Version 2007: June 12</span></span>
<span data-ttu-id="b1460-138">*版本2007（内部版本13006.20002）*</span><span class="sxs-lookup"><span data-stu-id="b1460-138">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-140">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-140">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-141">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-141">Excel</span></span>

- <span data-ttu-id="b1460-142">**使用数据类型从 POWER BI 获取组织数据：** Power BI 中的 Excel 数据类型现已向组织中的内部部署了 Office 365 E5/A5 或 Microsoft 365 E5/A5。</span><span class="sxs-lookup"><span data-stu-id="b1460-142">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="b1460-143">获取所需的信息并轻松地刷新，对于许多日常工作流而言至关重要。</span><span class="sxs-lookup"><span data-stu-id="b1460-143">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="b1460-144">我们为你的公司或组织提供了从 Power BI 为 Excel 中的数据类型的信息的访问权限，这扩展了你在电子表格中引入链接信息的能力。</span><span class="sxs-lookup"><span data-stu-id="b1460-144">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="b1460-145">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="b1460-145">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="b1460-146">在[博客文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="b1460-146">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-149">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-149">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b1460-150">Access</span><span class="sxs-lookup"><span data-stu-id="b1460-150">Access</span></span>

- <span data-ttu-id="b1460-151">我们解决了导致 Microsoft Access 无法识别链接 SQL Server 表中的 Identity 列的问题，这可能会导致错误地将行报告为已删除。</span><span class="sxs-lookup"><span data-stu-id="b1460-151">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-152">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-152">Excel</span></span>

- <span data-ttu-id="b1460-153">我们修复了雷达图表的主要网格线无法正确格式化的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-153">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-154">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-154">Project</span></span>

- <span data-ttu-id="b1460-155">我们修复了以下问题：项目摘要任务（项目开始/任务域）发生更改时，ProjectBeforeTaskChange 事件不会触发。</span><span class="sxs-lookup"><span data-stu-id="b1460-155">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="b1460-156">我们修复了以下问题：比较基准重置或更新可能会更改时间分段预算成本/工时资源，并且比较基准可能会反映错误的预算值。</span><span class="sxs-lookup"><span data-stu-id="b1460-156">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-157">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-157">Word</span></span>

- <span data-ttu-id="b1460-158">我们修复了以下问题：通过 Office 功能区中的 "清除格式" 按钮清除批注窗格中的格式设置不起作用。</span><span class="sxs-lookup"><span data-stu-id="b1460-158">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="b1460-159">我们修复了以下问题：如果在不显示标尺时更改表的大小，则会导致在后台运行的其他应用程序开始闪烁。</span><span class="sxs-lookup"><span data-stu-id="b1460-159">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="b1460-160">我们解决了以下问题：在共同创作模式中，注释答复有时不会显示在 "批注" 窗格中，而是在 "修订" 窗格中可见。</span><span class="sxs-lookup"><span data-stu-id="b1460-160">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="b1460-161">我们修复了以下问题：如果 Word 的列表超过50个频繁打开的文档，则在保存并打开文档后，即使没有对该文档进行任何修订，也会显示修订历史记录。</span><span class="sxs-lookup"><span data-stu-id="b1460-161">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2006-june-05"></a><span data-ttu-id="b1460-163">版本2006：05年6月</span><span class="sxs-lookup"><span data-stu-id="b1460-163">Version 2006: June 05</span></span>
<span data-ttu-id="b1460-164">*版本2006（内部版本13001.20002）*</span><span class="sxs-lookup"><span data-stu-id="b1460-164">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-166">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-166">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-167">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-167">Excel</span></span>

- <span data-ttu-id="b1460-168">**在 Excel 中协作时排序/筛选：** 现在，您可以对 Excel 文件进行排序和筛选，同时与其他人协作。</span><span class="sxs-lookup"><span data-stu-id="b1460-168">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="b1460-169">此新功能可防止其他用户的排序和筛选器受到影响，同时共同创作文档。</span><span class="sxs-lookup"><span data-stu-id="b1460-169">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="b1460-170">在 Excel 中的**POWER BI 数据集中创建数据透视表：** 您可以通过几次单击在 Excel 中创建连接到存储在 Power BI 中的数据集的数据透视表。</span><span class="sxs-lookup"><span data-stu-id="b1460-170">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="b1460-171">这样一来，您就可以获得数据透视表和 Power BI 的最佳效果。</span><span class="sxs-lookup"><span data-stu-id="b1460-171"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="b1460-172">使用安全 Power BI 数据集中的数据透视表计算、汇总和分析数据。</span><span class="sxs-lookup"><span data-stu-id="b1460-172">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="b1460-173">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-173">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="b1460-174">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-174">Outlook</span></span>

- <span data-ttu-id="b1460-175">**快速重新打开上一会话中的项：** 我们添加了一个从以前的 Outlook 会话快速重新打开项目的选项。</span><span class="sxs-lookup"><span data-stu-id="b1460-175">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="b1460-176">无论 Outlook 是否崩溃或关闭它，现在都可以在重新打开应用程序时快速重新启动项目。</span><span class="sxs-lookup"><span data-stu-id="b1460-176">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="b1460-177">默认情况下，此功能处于启用状态。</span><span class="sxs-lookup"><span data-stu-id="b1460-177">This feature is on by default.</span></span> <span data-ttu-id="b1460-178">若要将其关闭，请转到 "选项" > 常规 > 启动选项 "。</span><span class="sxs-lookup"><span data-stu-id="b1460-178">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-181">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-182">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-182">Excel</span></span>

- <span data-ttu-id="b1460-183">我们修复了图表轴上的自定义值不能正确应用的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-183">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="b1460-184">我们修复了以下问题：在保存文件时，包含具有已定义名称的多个公式的工作表会导致更长时间。</span><span class="sxs-lookup"><span data-stu-id="b1460-184">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-185">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-185">Outlook</span></span>

- <span data-ttu-id="b1460-186">我们解决了以下问题：在使用具有不同分辨率的多个监视器时，IME （输入法编辑器）窗口将与通过 IME 输入的基础文本重叠。</span><span class="sxs-lookup"><span data-stu-id="b1460-186">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="b1460-187">我们修复了以下问题：撰写新电子邮件时，查看模板会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="b1460-187">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="b1460-188">我们修复了以下问题：用户无法在 Outlook 版本1911之后交换2010公用文件夹。</span><span class="sxs-lookup"><span data-stu-id="b1460-188">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="b1460-189">我们解决了以下问题：禁用了 Office 功能区中组日历的分类按钮。</span><span class="sxs-lookup"><span data-stu-id="b1460-189">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="b1460-190">我们解决了导致联系人冲突的用户在 Outlook 中遇到故障的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-190">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="b1460-191">我们解决了导致高 DPI 监视器上的用户丢失了文件夹属性中的联机存档下拉列表的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-191">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="b1460-192">我们解决了导致用户在使用纯文本电子邮件的超链接时遇到 Outlook 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-192">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="b1460-193">我们解决了导致 Outlook 无法分析使用 RFC2231 编码的长文件名的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-193">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="b1460-194">我们解决了导致 Outlook 用户在使用屏幕阅读器时遇到间歇性挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-194">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-195">PowerPoint</span></span>

- <span data-ttu-id="b1460-196">我们解决了使用基于表单的身份验证打开服务器配置的文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-196">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="b1460-197">我们解决了以下问题： PowerPoint 文件的嵌入图表/工作簿可能会导致在保存文件时出现故障。</span><span class="sxs-lookup"><span data-stu-id="b1460-197">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="b1460-198">我们解决了以下问题：用户已关闭的注释窗格将自动重新打开。</span><span class="sxs-lookup"><span data-stu-id="b1460-198">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="b1460-199">我们修复了以下问题：一张幻灯片中的幻灯片编辑器将重叠到下一张幻灯片。</span><span class="sxs-lookup"><span data-stu-id="b1460-199">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-200">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-200">Project</span></span>

- <span data-ttu-id="b1460-201">我们修复了阻止在删除父计划后删除或重新分配孤立任务的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-201">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-202">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-202">Word</span></span>

- <span data-ttu-id="b1460-203">我们修复了注释窗格中的时间戳不基于系统区域设置时间的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-203">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="b1460-204">我们修复了以下问题： web 应用和桌面应用程序之间的注释不同步。</span><span class="sxs-lookup"><span data-stu-id="b1460-204">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)


## <a name="version2006may29"></a><span data-ttu-id="b1460-206">版本2006：5月29日</span><span class="sxs-lookup"><span data-stu-id="b1460-206">Version 2006: May 29</span></span>
<span data-ttu-id="b1460-207">*版本2006（内部版本12920.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-207">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="b1460-208">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-208">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-209">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-209">Outlook</span></span>

- <span data-ttu-id="b1460-210">**添加到 Outlook toast 通知中的其他按钮：** 快速操作按钮现在在 Windows 10 上运行 Outlook 时出现在 Outlook toast 通知中。</span><span class="sxs-lookup"><span data-stu-id="b1460-210">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-211">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-211">PowerPoint</span></span>

- <span data-ttu-id="b1460-212">**改进了 PowerPoint 中的流视频性能：** 我们已经改进了 Microsoft Stream 视频的播放性能，以最大限度地减少视频加载时间，并创建流畅的观看体验。</span><span class="sxs-lookup"><span data-stu-id="b1460-212">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="b1460-213">使用 Microsoft Stream 中的公司视频来创建更好的演示文稿。</span><span class="sxs-lookup"><span data-stu-id="b1460-213">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolvedissues"></a><span data-ttu-id="b1460-216">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-216">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-217">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-217">Excel</span></span>

- <span data-ttu-id="b1460-218">我们修复了在使用 OneDrive 时 Excel 偶尔会关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-218">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="b1460-219">我们修复了以下问题：单击同一工作簿中的书签标记的超链接将导致工作簿被隐藏。</span><span class="sxs-lookup"><span data-stu-id="b1460-219">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="b1460-220">我们修复了以下问题：某些复制和粘贴的图表链接使用映射的驱动器地址，而不是通用地址。</span><span class="sxs-lookup"><span data-stu-id="b1460-220">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="b1460-221">我们修复了以下问题：使用 Ctrl + Shift + 箭头键在 Excel 窗口通过团队共享时，Excel 可能变得变慢。</span><span class="sxs-lookup"><span data-stu-id="b1460-221">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-222">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-222">PowerPoint</span></span>

- <span data-ttu-id="b1460-223">我们修复了以下问题：在使用鼠标滚轮缩放后，幻灯片未居中。</span><span class="sxs-lookup"><span data-stu-id="b1460-223">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-224">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-224">Word</span></span>

- <span data-ttu-id="b1460-225">我们修复了以下问题：不会显示将文本复制并粘贴到批注窗格的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-225">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="b1460-226">我们修复了以下问题：注释提示气泡在100% 时显示模糊。</span><span class="sxs-lookup"><span data-stu-id="b1460-226">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="b1460-227">我们修复了以下问题：启用策略 Word 2007 及更高版本的二进制文档和模板将导致某些共同创作案例失败。</span><span class="sxs-lookup"><span data-stu-id="b1460-227">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="b1460-228">我们修复了以下问题：将无法打开带有长路径名（大于32K）的文件，并且未显示相应的错误消息。</span><span class="sxs-lookup"><span data-stu-id="b1460-228">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="b1460-229">版本2006：5月22日</span><span class="sxs-lookup"><span data-stu-id="b1460-229">Version 2006: May 22</span></span>
<span data-ttu-id="b1460-230">*版本2006（内部版本12914.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-230">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-232">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-232">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-233">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-233">Excel</span></span>

- <span data-ttu-id="b1460-234">**保存到固定文件夹：** 固定文件夹可以更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="b1460-234">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="b1460-235">我们收到了反馈，用户需要更好地控制保存新文件时可用的文件夹。</span><span class="sxs-lookup"><span data-stu-id="b1460-235">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="b1460-236">我们非常兴奋地为你提供新功能：在 "保存" 对话框中固定你的文件夹。</span><span class="sxs-lookup"><span data-stu-id="b1460-236">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="b1460-237">这一新功能将使您的 Word、Excel 和 PowerPoint 文件更易于保存。</span><span class="sxs-lookup"><span data-stu-id="b1460-237">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="b1460-238">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="b1460-238">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-239">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-239">PowerPoint</span></span>

- <span data-ttu-id="b1460-240">**保存到固定文件夹：** 固定文件夹可以更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="b1460-240">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="b1460-241">我们收到了反馈，用户需要更好地控制保存新文件时可用的文件夹。</span><span class="sxs-lookup"><span data-stu-id="b1460-241">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="b1460-242">我们非常兴奋地为你提供新功能：在 "保存" 对话框中固定你的文件夹。</span><span class="sxs-lookup"><span data-stu-id="b1460-242">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="b1460-243">这一新功能将使您的 Word、Excel 和 PowerPoint 文件更易于保存。</span><span class="sxs-lookup"><span data-stu-id="b1460-243">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="b1460-244">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="b1460-244">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="b1460-245">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-245">Word</span></span>

- <span data-ttu-id="b1460-246">**保存到固定文件夹：** 固定文件夹可以更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="b1460-246">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="b1460-247">我们收到了反馈，用户需要更好地控制保存新文件时可用的文件夹。</span><span class="sxs-lookup"><span data-stu-id="b1460-247">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="b1460-248">我们非常兴奋地为你提供新功能：在 "保存" 对话框中固定你的文件夹。</span><span class="sxs-lookup"><span data-stu-id="b1460-248">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="b1460-249">这一新功能将使您的 Word、Excel 和 PowerPoint 文件更易于保存。</span><span class="sxs-lookup"><span data-stu-id="b1460-249">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="b1460-250">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="b1460-250">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-253">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-253">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-254">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-254">Excel</span></span>

- <span data-ttu-id="b1460-255">我们修复了以下问题：由于加载项是按字母顺序而不是以用户指定的顺序加载，因此将显示错误消息 "由于加载项正在被另一工作簿引用且无法关闭"。</span><span class="sxs-lookup"><span data-stu-id="b1460-255">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="b1460-256">我们修复了在 Excel 与一些第三方辅助技术应用程序之间管理字体时内存损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-256">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="b1460-257">我们修复了以下问题：当外接程序要求包含具有 noSelect 锁定的形状的工作表上的主机项时，Excel 将发生故障。</span><span class="sxs-lookup"><span data-stu-id="b1460-257">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-258">Outlook</span></span>

- <span data-ttu-id="b1460-259">我们解决了以下问题：当用户在文件夹之间移动项目时，BeforeItemMove 事件未正确触发。</span><span class="sxs-lookup"><span data-stu-id="b1460-259">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="b1460-260">我们修复了以下问题：用户看到跨越午夜阈值的日历项目作为全天事件。</span><span class="sxs-lookup"><span data-stu-id="b1460-260">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="b1460-261">我们修复了以下问题：当两个外接程序将一个按钮添加到功能区中的同一个组时，Outlook 崩溃。</span><span class="sxs-lookup"><span data-stu-id="b1460-261">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="b1460-262">我们修复了用户无法与来宾用户共享日历的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-262">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-263">PowerPoint</span></span>

- <span data-ttu-id="b1460-264">我们修复了以下问题：从演示文稿区域进行放大和缩小导致缩放后的选区选取框和鼠标指针之间存在间隙。</span><span class="sxs-lookup"><span data-stu-id="b1460-264">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-265">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-265">Project</span></span>

- <span data-ttu-id="b1460-266">我们修复了以下问题：单击 "选项" 后，Project 将发生故障。</span><span class="sxs-lookup"><span data-stu-id="b1460-266">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-267">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-267">Word</span></span>

- <span data-ttu-id="b1460-268">我们修复了批注中的超链接无法正常工作的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-268">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="b1460-269">我们修复了以下问题：从演示文稿区域进行放大和缩小导致缩放后的选区选取框和鼠标指针之间存在间隙。</span><span class="sxs-lookup"><span data-stu-id="b1460-269">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="b1460-270">我们修复了以下问题：将 HTML 粘贴到日历的 WordMail 中时不起作用。</span><span class="sxs-lookup"><span data-stu-id="b1460-270">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="b1460-271">我们修复了在共同创作的会话中答复注释有时可能导致 Word 冻结的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-271">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2006-may-15"></a><span data-ttu-id="b1460-273">版本 2006：5 月 15 日</span><span class="sxs-lookup"><span data-stu-id="b1460-273">Version 2006: May 15</span></span>
<span data-ttu-id="b1460-274">*版本 2006（内部版本 12905.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-274">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-276">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-276">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-277">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-277">Excel</span></span>

- <span data-ttu-id="b1460-278">**建立 PDF 连接：** 连接到 PDF，从其中导入数据，刷新数据。</span><span class="sxs-lookup"><span data-stu-id="b1460-278">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="b1460-279">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="b1460-279">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="b1460-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-280">Outlook</span></span>

- <span data-ttu-id="b1460-281">**找到所需内容：** 使用文件夹、发件人、日期、附件信息等选项来缩小搜索范围。</span><span class="sxs-lookup"><span data-stu-id="b1460-281">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-282">PowerPoint</span></span>

- <span data-ttu-id="b1460-283">**无需遥控器：使用耳塞即可：** 使用 Surface Earbuds 来控制 PowerPoint 演示文稿。</span><span class="sxs-lookup"><span data-stu-id="b1460-283">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="b1460-284">重要提示：必须使用 Windows 10 的 Surface Audio 应用配对 Surface Earbuds，才能使用手势控制演示文稿。</span><span class="sxs-lookup"><span data-stu-id="b1460-284">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="b1460-285">此处提供了有关 Windows 10 上的 Surface Audio 应用入门的说明。</span><span class="sxs-lookup"><span data-stu-id="b1460-285">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="b1460-286">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-286">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="b1460-287">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-287">Word</span></span>

- <span data-ttu-id="b1460-288">**自动应用或推荐敏感度标签：** Office 可以根据检测到的敏感内容来推荐或自动应用敏感度标签。</span><span class="sxs-lookup"><span data-stu-id="b1460-288">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-291">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-291">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-292">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-292">Excel</span></span>
- <span data-ttu-id="b1460-293">我们解决了在用户删除合并的列时导致性能时间增加的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-293">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="b1460-294">我们解决了导致打印机名称在可用打印机列表中重复的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-294">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="b1460-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-295">PowerPoint</span></span>
- <span data-ttu-id="b1460-296">我们解决了使用瑞士英语 (QWERTZ) 键盘时键盘快捷方式和拼写检查无法正常工作的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-296">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-297">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-297">Word</span></span>
- <span data-ttu-id="b1460-298">我们解决了向空白文档添加新批注不会执行任何操作的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-298">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="b1460-299">我们解决了以下问题：在包含 100 个以上条目的文档中插入或更新索引将导致应用程序崩溃。</span><span class="sxs-lookup"><span data-stu-id="b1460-299">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="b1460-300">我们解决了以下问题：带有自定义 xml 值的文件打开速度非常慢。</span><span class="sxs-lookup"><span data-stu-id="b1460-300">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b1460-301">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-301">Office Suite</span></span>
- <span data-ttu-id="b1460-302">修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="b1460-302">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2006-may-08"></a><span data-ttu-id="b1460-305">版本 2006：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="b1460-305">Version 2006: May 08</span></span>
<span data-ttu-id="b1460-306">*版本 2006（内部版本 12829.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-306">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-308">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-308">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-309">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-309">Excel</span></span>

- <span data-ttu-id="b1460-310">**使用动态 Gif 讲述故事：** 现在，Office 编辑器支持动画 Gif，你的文档更漂亮。</span><span class="sxs-lookup"><span data-stu-id="b1460-310">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-311">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-311">Outlook</span></span>

- <span data-ttu-id="b1460-312">**更好的结果 - 瞬间完成：** 我们更新了搜索体验，使其更加智能、更快速，并且比以往更可靠。</span><span class="sxs-lookup"><span data-stu-id="b1460-312">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="b1460-313">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-313">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="b1460-314">**使用动态 GIF 讲述故事：** 现在，Office 编辑器支持动画 GIF，你的文档会更漂亮。</span><span class="sxs-lookup"><span data-stu-id="b1460-314">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-315">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-315">PowerPoint</span></span>

- <span data-ttu-id="b1460-316">**使用动态 Gif 讲述故事：** 现在，Office 编辑器支持动画 Gif，你的文档更漂亮。</span><span class="sxs-lookup"><span data-stu-id="b1460-316">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="b1460-317">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-317">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="b1460-318">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-318">Word</span></span>

- <span data-ttu-id="b1460-319">**使用动态 Gif 讲述故事：** 现在，Office 编辑器支持动画 Gif，你的文档更漂亮。</span><span class="sxs-lookup"><span data-stu-id="b1460-319">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-322">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-322">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b1460-323">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-323">Office Suite</span></span>

- <span data-ttu-id="b1460-324">我们已调查并解决了操作系统关闭后，通过 InTune 执行 Office 365 企业应用版部署暂停的问题。 </span><span class="sxs-lookup"><span data-stu-id="b1460-324">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2005-may-01"></a><span data-ttu-id="b1460-326">版本 2005：5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b1460-326">Version 2005: May 01</span></span>
<span data-ttu-id="b1460-327">*版本 2005 （内部版本 12827.20030）*</span><span class="sxs-lookup"><span data-stu-id="b1460-327">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-329">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-329">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-330">Outlook</span></span>

- <span data-ttu-id="b1460-331">**电子邮件中的改进链接：** 包含文件的链接时，文件名会替换 URL。</span><span class="sxs-lookup"><span data-stu-id="b1460-331">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="b1460-332">可更改权限，以便所有收件人都可以访问。</span><span class="sxs-lookup"><span data-stu-id="b1460-332">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="b1460-333">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="b1460-333">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-336">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-336">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-337">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-337">Excel</span></span>

- <span data-ttu-id="b1460-338">修复了图表数据表可能在日期坐标轴中错误呈现值的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-338">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="b1460-339">修复了在进入页面布局或分页预览后无法禁用分页符的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-339">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="b1460-340">修复了隐藏和取消隐藏带序列数据的列后可能丢失图表行样式的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-340">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="b1460-341">在筛选列表中插入列所需的时间可能比预期更长。</span><span class="sxs-lookup"><span data-stu-id="b1460-341">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="b1460-342">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="b1460-342">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="b1460-343">解决了启用“以互补色代表负值”选项后不保存数据透视表中的自定义格式设置的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-343">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="b1460-344">解决了选择“以互补色代表负值”选项后不保存数据透视表中单个数据点的自定义格式设置的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-344">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="b1460-345">此更改修复了将“@”字符上传到 CSV 文件会导致字符串后面的“@”字符后转换为公式的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-345">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="b1460-346">修复了 SEQUENCE 函数中的小数值未正确舍入的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-346">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-347">Outlook</span></span>

- <span data-ttu-id="b1460-348">解决了导致安全链接（即用户在 Outlook 桌面版客户端中单击的因被截断而无法加载的链接）较长的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-348">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="b1460-349">修复了在与服务器同步时，名称包含 DBCS （双字节字符集）字符的 Outlook 文件夹间歇性消失的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-349">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="b1460-350">为此，必须使用 IMAP 帐户配置 Outlook 并在区域设置为“日语”的系统上运行。</span><span class="sxs-lookup"><span data-stu-id="b1460-350">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-351">PowerPoint</span></span>

- <span data-ttu-id="b1460-352">修复了以下问题：如果用户在未发布的情况下创建了批注并关闭了批注窗格，然后打开一个新窗口，在多张幻灯片中导航并关闭窗口，最后再打开原始演示文稿中的批注窗格，草稿批注将不可用的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-352">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-353">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-353">Project</span></span>

- <span data-ttu-id="b1460-354">修复了以下问题：如果 Project 连接到 Project Web App，并且小数分隔符是逗号，则 TaskDependencies Add 方法会在尝试添加延迟时失败。</span><span class="sxs-lookup"><span data-stu-id="b1460-354">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-355">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-355">Word</span></span>

- <span data-ttu-id="b1460-356">修复了在协作模式下插入文档批注并非总能正常工作的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-356">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="b1460-357">此更改修复了单击 @ 提及时人员卡片闪烁的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-357">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="b1460-358">修复了使用草稿批注关闭文档将提示用户是否希望关闭文档而不保存草稿批注的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-358">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="b1460-359">取消该提示会关闭文档，而不会将其保持打开状态。</span><span class="sxs-lookup"><span data-stu-id="b1460-359">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="b1460-360">修复了翻译已发布的批注会导致错误“插入已翻译的文本失败”的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-360">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="b1460-361">在 Web 视图/沉浸式阅读器中，单击提示会滚动到顶部，即使它已在视图中。</span><span class="sxs-lookup"><span data-stu-id="b1460-361">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="b1460-362">已修复此问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-362">This has been fixed.</span></span>
- <span data-ttu-id="b1460-363">我们修复了以下问题：尝试将包含宏的文件保存在新名称下时，无论用户输入何种内容，都将用 .docx 扩展名和文件名 WRO0004.docx 保存该文件，从而使文档显示为不可用。</span><span class="sxs-lookup"><span data-stu-id="b1460-363">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)


## <a name="version-2005-april-24"></a><span data-ttu-id="b1460-365">版本 2005：4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="b1460-365">Version 2005: April 24</span></span>
<span data-ttu-id="b1460-366">*版本 2005（内部版本 12816.20006）*</span><span class="sxs-lookup"><span data-stu-id="b1460-366">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-368">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-368">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-369">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-369">Excel</span></span>
- <span data-ttu-id="b1460-370">此更改修复了以下问题：即使 LINEST 函数返回的值正确，图表趋势线 R 平方值（在强制使用的 Y 轴截距情况下）也不正确。</span><span class="sxs-lookup"><span data-stu-id="b1460-370">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="b1460-371">此更改修复了自定义图表趋势线格式设置未始终处于保存状态的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-371">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-372">Outlook</span></span>
- <span data-ttu-id="b1460-373">修复了 Office 功能区中组日历的“分类”按钮被禁用的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-373">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="b1460-374">修复了以下问题：如果企业客户的组文件夹未实现或无法正常工作，将导致 Outlook 显示“未响应”消息。</span><span class="sxs-lookup"><span data-stu-id="b1460-374">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-375">PowerPoint</span></span>
- <span data-ttu-id="b1460-376">修复了将鼠标悬停在星号 (\*) 上方时未显示上次更新文档的人员的用户名和日期的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-376">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-377">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-377">Word</span></span>
- <span data-ttu-id="b1460-378">启用选项“显示书签”不会显示书签。</span><span class="sxs-lookup"><span data-stu-id="b1460-378">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="b1460-379">已修复此问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-379">This has been fixed.</span></span>
- <span data-ttu-id="b1460-380">此更改修复了以下问题：如果已启用“显示域代码而非域值”选项，可能不会显示包含超链接的文本。</span><span class="sxs-lookup"><span data-stu-id="b1460-380">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)


## <a name="version-2005-april-17"></a><span data-ttu-id="b1460-382">版本 2005：4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="b1460-382">Version 2005: April 17</span></span>
<span data-ttu-id="b1460-383">*版本 2005（内部版本 12810.20002）*</span><span class="sxs-lookup"><span data-stu-id="b1460-383">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-385">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-385">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-386">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-386">Excel</span></span>
- <span data-ttu-id="b1460-387">增大了与图表搭配使用的“自定义误差线”对话框上的单元格引用编辑控件的大小。</span><span class="sxs-lookup"><span data-stu-id="b1460-387">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="b1460-388">在 Excel 2016 中保存并且含有数字签名的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="b1460-388">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="b1460-389">修复了打印时窗体控件中的复选框缩放问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-389">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="b1460-390">Application.Evaluate (VBA) 在某些情况下不能用于用户定义的函数。</span><span class="sxs-lookup"><span data-stu-id="b1460-390">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="b1460-391">此更改修复了条件格式 (CF) 信息未正确保存到 XLSB 文件的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-391">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="b1460-392">OneNote</span><span class="sxs-lookup"><span data-stu-id="b1460-392">OneNote</span></span>
- <span data-ttu-id="b1460-393">修复了换行符存储为垂直标签的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-393">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-394">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-394">Outlook</span></span>
- <span data-ttu-id="b1460-395">解决了导致用户无法将个人联系人组添加为与会者的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-395">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="b1460-396">解决了距离开会时间超过 2 个月的会议无法在日程安排助理中显示会议主题的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-396">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="b1460-397">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-397">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="b1460-398">添加了通过组策略强制执行 S/MIME 默认签名配置的能力。</span><span class="sxs-lookup"><span data-stu-id="b1460-398">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="b1460-399">解决了导致删除为邮箱创建的规则而不是用户的主要邮箱无效的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-399">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="b1460-400">解决了在转发加密邮件时导致附件被删除的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-400">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-401">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-401">Project</span></span>
- <span data-ttu-id="b1460-402">在窗体视图中编辑前置/后续数据时，会触发额外的 ProjectBeforeTaskChangeevent 事件。</span><span class="sxs-lookup"><span data-stu-id="b1460-402">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="b1460-403">修复了以下问题：在连接至 SharePoint 任务列表的项目上更改版块状态字段时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="b1460-403">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="b1460-404">解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="b1460-404">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)


## <a name="version-2004-april-10"></a><span data-ttu-id="b1460-406">版本 2004：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="b1460-406">Version 2004: April 10</span></span>
<span data-ttu-id="b1460-407">*版本 2004（内部版本 12730.20024）*</span><span class="sxs-lookup"><span data-stu-id="b1460-407">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-409">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-409">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b1460-410">Access</span><span class="sxs-lookup"><span data-stu-id="b1460-410">Access</span></span>

- <span data-ttu-id="b1460-411">**绕过“显示表”对话框，直接转至任务面板，并简化添加关系和查询表：** 通过单击四个选项卡、多选名称、按文本进行搜索并在工作时拖动保持打开状态的任务窗格来添加表和查询。</span><span class="sxs-lookup"><span data-stu-id="b1460-411">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-412">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-412">Excel</span></span>

- <span data-ttu-id="b1460-413">**M365 高级版内容选取器：** 让你的文档更生动！</span><span class="sxs-lookup"><span data-stu-id="b1460-413">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b1460-414">探索上千张免费图片、图标和贴纸 [了解详细信息](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b1460-414">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-415">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-415">Outlook</span></span>

- <span data-ttu-id="b1460-416">**M365 高级版内容选取器：** 让你的文档更生动！</span><span class="sxs-lookup"><span data-stu-id="b1460-416">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b1460-417">探索上千张免费图片、图标和贴纸 [了解详细信息](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b1460-417">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="b1460-418">**将图片作为电子邮件一部分发送时，保持图片的高度机密性：** 将图片作为电子邮件内容的一部分发送时，可以使用新的 Outlook 设置限制图片压缩</span><span class="sxs-lookup"><span data-stu-id="b1460-418">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-419">PowerPoint</span></span>

- <span data-ttu-id="b1460-420">**M365 高级版内容选取器：** 让你的文档更生动！</span><span class="sxs-lookup"><span data-stu-id="b1460-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b1460-421">探索上千张免费图片、图标和贴纸 [了解详细信息](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b1460-421">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="b1460-422">**演示时同步所做的更改：** 即使演示文稿处于幻灯片放映模式，只要进行了更改就同步这些更改。</span><span class="sxs-lookup"><span data-stu-id="b1460-422">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-423">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-423">Word</span></span>

- <span data-ttu-id="b1460-424">**M365 高级版内容选取器：** 让你的文档更生动！</span><span class="sxs-lookup"><span data-stu-id="b1460-424">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b1460-425">探索上千张免费图片、图标和贴纸 [了解详细信息](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b1460-425">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="b1460-426">**为私人副本添加批注：** 通过制作共享文档的私人副本，创建手写笔记供你自己查看。</span><span class="sxs-lookup"><span data-stu-id="b1460-426">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="b1460-427">转到“查看”>“创建私人副本”以开始使用。</span><span class="sxs-lookup"><span data-stu-id="b1460-427">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-430">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-430">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b1460-431">Access</span><span class="sxs-lookup"><span data-stu-id="b1460-431">Access</span></span>

- <span data-ttu-id="b1460-432">修复了在任务窗格中调整表格大小和刷新表格时遇到的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-432">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-433">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-433">Excel</span></span>

- <span data-ttu-id="b1460-434">修复了以下问题：在工作表上选择单元格区域导致选择单个单元格。</span><span class="sxs-lookup"><span data-stu-id="b1460-434">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="b1460-435">修复了在使用某些 X 轴区域减小图表大小时可能导致 Excel 停止响应的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-435">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="b1460-436">修复了以下问题：插入用户定义的图表模板用作默认模板会导致将其另存为柱形图。</span><span class="sxs-lookup"><span data-stu-id="b1460-436">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="b1460-437">修复了以下问题：当基础数据单元格没有标题时，图表上的数据标签显示为空白。</span><span class="sxs-lookup"><span data-stu-id="b1460-437">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="b1460-438">修复了以下问题：对于启用了 R1C1 单元格引用且正在共同创作/共享的 Excel 工作表，将鼠标悬停在用户状态图标上时，在 R1C1 模式下不显示活动单元格引用。</span><span class="sxs-lookup"><span data-stu-id="b1460-438">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-439">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-439">Outlook</span></span>

- <span data-ttu-id="b1460-440">解决了导致类别偶尔从电子邮件中消失的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-440">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="b1460-441">解决了导致代理人在不同计算机上看到共享邮箱的不同文件夹层次结构的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="b1460-442">解决了导致用户在尝试查看组织表单属性时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-442">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="b1460-443">解决了导致在更改计算机上的时区时一些提醒无法触发的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-443">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-444">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-444">PowerPoint</span></span>

- <span data-ttu-id="b1460-445">此更改修复了以下问题：在 PowerPoint 或 Word 中嵌入为 OLE 对象的旧版 Excel 图表呈现时，可能并不总是显示图表标题。</span><span class="sxs-lookup"><span data-stu-id="b1460-445">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b1460-446">修复了以下问题：将文本从 Excel 复制到 PowerPoint 时可能会更改其格式。</span><span class="sxs-lookup"><span data-stu-id="b1460-446">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="b1460-447">此更改修复了以下问题：使用“全字匹配”查找特殊字符时并非总是按预期工作。</span><span class="sxs-lookup"><span data-stu-id="b1460-447">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-448">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-448">Project</span></span>

- <span data-ttu-id="b1460-449">修复了下列问题：启用保护实际工作的设置后，用户无法输入按时间分段的基准工作。</span><span class="sxs-lookup"><span data-stu-id="b1460-449">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-450">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-450">Word</span></span>

- <span data-ttu-id="b1460-451">此更改修复了以下问题：将光标悬停在提示上不会突出显示其卡片。</span><span class="sxs-lookup"><span data-stu-id="b1460-451">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="b1460-452">此更改修复了以下问题：使用套索选择工具时，分组形状中的文本暂时消失。</span><span class="sxs-lookup"><span data-stu-id="b1460-452">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="b1460-453">此更改修复了以下问题：在 PowerPoint 或 Word 中嵌入为 OLE 对象的旧版 Excel 图表呈现时，可能并不总是显示图表标题。</span><span class="sxs-lookup"><span data-stu-id="b1460-453">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b1460-454">此更改修复了以下问题：在双页视图中，在创建批注时，批注锚点并不总是出现在视图中。</span><span class="sxs-lookup"><span data-stu-id="b1460-454">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="b1460-455">修复了以下问题：如果某个段落的样式是链接到列表的样式的上级，则该列表的编号可能会丢失。</span><span class="sxs-lookup"><span data-stu-id="b1460-455">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2004-march-27"></a><span data-ttu-id="b1460-457">版本 2004：3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="b1460-457">Version 2004: March 27</span></span>
<span data-ttu-id="b1460-458">*版本 2004（生成号 12718.20010）*</span><span class="sxs-lookup"><span data-stu-id="b1460-458">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-460">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-460">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-461">Outlook</span></span>

- <span data-ttu-id="b1460-462">**新增了用于在撰写邮件时禁用 @提及建议的选项：** 你是否觉得 @提及选取器更令人生厌，而不是更有用？</span><span class="sxs-lookup"><span data-stu-id="b1460-462">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="b1460-463">现在，可以根据需要禁用它。</span><span class="sxs-lookup"><span data-stu-id="b1460-463">Now you can turn it off if you prefer.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-466">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-466">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-467">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-467">Outlook</span></span>
- <span data-ttu-id="b1460-468">修复了以下问题：附件工具中缺少“保存到云”按钮。</span><span class="sxs-lookup"><span data-stu-id="b1460-468">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="b1460-469">修复了以下问题：如果用户对要回复的邮件没有所有者权限，在检查器窗口中回复受数字权限管理的邮件时，用户无法添加签名。</span><span class="sxs-lookup"><span data-stu-id="b1460-469">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="b1460-470">修复了以下问题：用户无法将其他附件从 Web 位置添加到先前创建的会议。</span><span class="sxs-lookup"><span data-stu-id="b1460-470">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-471">PowerPoint</span></span>
- <span data-ttu-id="b1460-472">此更改修复了以下错误：无法保存包含表情符号的 PowerPoint 文件。</span><span class="sxs-lookup"><span data-stu-id="b1460-472">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-473">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-473">Project</span></span>
- <span data-ttu-id="b1460-474">修复了以下问题：在执行“CustomFieldValueListGetItem”时，如果自定义字段的查阅表格不存在，则会创建空的查阅表格，即使不应该创建。</span><span class="sxs-lookup"><span data-stu-id="b1460-474">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-475">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-475">Word</span></span>
- <span data-ttu-id="b1460-476">此更改修复了以下问题：在“视图”菜单中选择多个页面时，批注窗格可能会显示为空白。</span><span class="sxs-lookup"><span data-stu-id="b1460-476">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-20"></a><span data-ttu-id="b1460-478">版本 2004：3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="b1460-478">Version 2004: March 20</span></span>
<span data-ttu-id="b1460-479">*版本 2004（生成号 12711.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-479">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-481">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-481">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-482">Outlook</span></span>

- <span data-ttu-id="b1460-483">**日历旧貌换新颜：** 去年，我们推出了全新的邮件体验；而今年，轮到日历改头换面了！</span><span class="sxs-lookup"><span data-stu-id="b1460-483">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="b1460-484">尽管这些更新是全新的，但却很熟悉。作为经验丰富的 Outlook 用户，你可以立即使用并提高工作效率。</span><span class="sxs-lookup"><span data-stu-id="b1460-484">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="b1460-485">**帮助保护组中的数据：** 你在创建组时选择的敏感度标签应用于组电子邮件、文档和团队网站</span><span class="sxs-lookup"><span data-stu-id="b1460-485">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-486">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-486">PowerPoint</span></span>

- <span data-ttu-id="b1460-487">**在幻灯片放映期间更新幻灯片：** 在演示期间更新其他作者更改的幻灯片。</span><span class="sxs-lookup"><span data-stu-id="b1460-487">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-490">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-490">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-491">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-491">Excel</span></span>

- <span data-ttu-id="b1460-492">此更改修复了以下问题：在处理包含格式不正确或无效协议信息的图片时出现延迟。</span><span class="sxs-lookup"><span data-stu-id="b1460-492">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-493">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-493">Outlook</span></span>

- <span data-ttu-id="b1460-494">此更改修复了以下问题：在处理包含格式不正确或无效协议信息的图片时出现延迟。</span><span class="sxs-lookup"><span data-stu-id="b1460-494">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b1460-495">此更改修复了以下问题：对电子邮件草稿的最新更改没有得到更新。</span><span class="sxs-lookup"><span data-stu-id="b1460-495">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="b1460-496">修复了以下问题：无法鼠标右键单击文件并使用“发送到”。</span><span class="sxs-lookup"><span data-stu-id="b1460-496">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="b1460-497">修复了以下问题：如果用户有通讯簿的自定义搜索路径，Outlook 的名称解析范围会被限制为此自定义路径，而不包括全局地址列表 (GAL)。</span><span class="sxs-lookup"><span data-stu-id="b1460-497">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="b1460-498">修复了以下问题：在一组返回的搜索结果中，按“类别”对结果排序时看不到“类别”颜色。</span><span class="sxs-lookup"><span data-stu-id="b1460-498">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-499">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-499">Project</span></span>

- <span data-ttu-id="b1460-500">修复了以下问题：当用户单击了“任务”功能区上“计划”分组中的“停用”按钮后，“ProjectBeforeTaskChange”Visual Basic Applications (VBA) 事件未触发。</span><span class="sxs-lookup"><span data-stu-id="b1460-500">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="b1460-501">如果你在“窗体类型”视图中设置前置任务或后续任务详细信息，ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件并不总是能够捕获更改。</span><span class="sxs-lookup"><span data-stu-id="b1460-501">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="b1460-502">例如，如果你删除了依赖项，并单击了窗体上的“确定”，但此事件并未触发。</span><span class="sxs-lookup"><span data-stu-id="b1460-502">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="b1460-503">此行为已修复。</span><span class="sxs-lookup"><span data-stu-id="b1460-503">This behavior has been fixed.</span></span>

- <span data-ttu-id="b1460-504">修复了以下问题：在你更改（如更改日期）后，“已完成工作量的实际成本(ACWP)”的最新值不会显示。</span><span class="sxs-lookup"><span data-stu-id="b1460-504">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="b1460-505">修复了以下问题：使用“最近经常使用(MRU)”菜单打开项目时，打开的是带有读/写访问权限的项目文件。</span><span class="sxs-lookup"><span data-stu-id="b1460-505">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="b1460-506">此更改修复了以下问题：如果你创建的手动任务包含开始日期和时间（但没有持续时间），它会在时间线上显示不正确的时间。</span><span class="sxs-lookup"><span data-stu-id="b1460-506">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="b1460-507">修复了以下问题：使用回历打印时间线会导致在打印视图中跳过或重复某个月。</span><span class="sxs-lookup"><span data-stu-id="b1460-507">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="b1460-508">此更改修复了以下问题：在工作组规划器中使用 GDI 对象时，可能会导致 GDI 对象的过度分配，并导致内存不足。</span><span class="sxs-lookup"><span data-stu-id="b1460-508">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-509">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-509">Word</span></span>

- <span data-ttu-id="b1460-510">修复了以下问题：评论发布功能已遭禁用。</span><span class="sxs-lookup"><span data-stu-id="b1460-510">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="b1460-511">此更改修复了以下问题：在处理包含格式不正确或无效协议信息的图片时出现延迟。</span><span class="sxs-lookup"><span data-stu-id="b1460-511">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b1460-512">此更改修复了以下问题：帐户管理员不会分派消息，导致第三方应用程序挂起。</span><span class="sxs-lookup"><span data-stu-id="b1460-512">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="b1460-513">此更改修复了以下问题：目录会使用文档中没有的标题样式进行更新。</span><span class="sxs-lookup"><span data-stu-id="b1460-513">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="b1460-514">修复了以下问题：当你通过邮件发送文档时，保存在 Word 文档中的数字签名会遭删除。</span><span class="sxs-lookup"><span data-stu-id="b1460-514">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-13"></a><span data-ttu-id="b1460-516">版本 2004：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="b1460-516">Version 2004: March 13</span></span>
<span data-ttu-id="b1460-517">*版本 2004（内部版本 12703.20010）*</span><span class="sxs-lookup"><span data-stu-id="b1460-517">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-519">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-519">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-520">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-520">Excel</span></span>
- <span data-ttu-id="b1460-521">**敏感度标签**：你现在可以应用组织已配置的敏感度标签来提示自定义权限。</span><span class="sxs-lookup"><span data-stu-id="b1460-521">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b1460-522">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-522">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="b1460-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-523">PowerPoint</span></span>
- <span data-ttu-id="b1460-524">**敏感度标签**：你现在可以应用组织已配置的敏感度标签来提示自定义权限。</span><span class="sxs-lookup"><span data-stu-id="b1460-524">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b1460-525">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-525">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="b1460-526">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-526">Word</span></span>
- <span data-ttu-id="b1460-527">**敏感度标签**：你现在可以应用组织已配置的敏感度标签来提示自定义权限。</span><span class="sxs-lookup"><span data-stu-id="b1460-527">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b1460-528">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-528">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-531">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-531">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="b1460-532">Access</span><span class="sxs-lookup"><span data-stu-id="b1460-532">Access</span></span>
- <span data-ttu-id="b1460-533">修复了 Access 国际版本在用户界面中显示英文字符串的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-533">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-534">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-534">Excel</span></span>
- <span data-ttu-id="b1460-535">修复了用户以编程方式编辑大量单元格时可能遇到的性能问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-535">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="b1460-536">修复了在日语环境中打开 csv 文件时出现的性能问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-536">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-537">Outlook</span></span>
- <span data-ttu-id="b1460-538">解决了将附件添加到邮件或通过拖放操作（而不是通过菜单）从邮件保存附件时，将更新文件的“上次修改时间”的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-538">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="b1460-539">解决了导致在展开的查找窗格中按回车键无法启动搜索，而是要求用户单击搜索按钮的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-539">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="b1460-540">修复了禁用“可用时显示用户照片”选项时，搜索不显示有关用户的信息的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-540">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="b1460-541">Project</span><span class="sxs-lookup"><span data-stu-id="b1460-541">Project</span></span>
- <span data-ttu-id="b1460-542">修复了有时无法正确计算摘要任务日期的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-542">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="b1460-543">修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。</span><span class="sxs-lookup"><span data-stu-id="b1460-543">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-544">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-544">Word</span></span>
- <span data-ttu-id="b1460-545">修复了在键入或编辑批注时使用 Ctrl+A 将导致在画布中选择文本而不是仅在批注卡中选择文本的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-545">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="b1460-546">修复了以下问题，即在使用“快速打印”打印后尝试进行编辑时，文档中的单词对齐方式会被打乱。</span><span class="sxs-lookup"><span data-stu-id="b1460-546">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="b1460-547">修复了将两个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-547">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="b1460-548">修复了标记涉及公式的修订后可能导致保存文件失败的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-548">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-march-06"></a><span data-ttu-id="b1460-550">版本 2003：3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="b1460-550">Version 2003: March 06</span></span>
<span data-ttu-id="b1460-551">*版本2003（内部版本 12624.20086）*</span><span class="sxs-lookup"><span data-stu-id="b1460-551">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-553">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-553">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-554">Outlook</span></span>

- <span data-ttu-id="b1460-555">修复了通过 Outlook Web Access 创建规则不会保留到 Exchange 服务器且会导致冲突的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-555">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="b1460-556">修复了深色模式下 Outlook 不会在“发件人:”字段中显示下拉列表的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-556">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="b1460-557">解决了导致用户无法通过文件资源管理器将已在其他应用程序中打开的文件附加到其邮件中的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-557">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-558">PowerPoint</span></span>

- <span data-ttu-id="b1460-559">修复了将鼠标悬停在推荐的缩略图上时缩略图闪烁的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-559">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="b1460-560">在某些情况下，这可能会导致 PowerPoint 崩溃。</span><span class="sxs-lookup"><span data-stu-id="b1460-560">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-561">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-561">Word</span></span>

- <span data-ttu-id="b1460-562">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-562">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b1460-563">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-563">Office Suite</span></span>

- <span data-ttu-id="b1460-564">修复了 Word/Excel/PowerPoint 中的用户主体名称 (UPN) 不再区分大小写的问题，从而减少了处理 SharePoint 上的文件时出现的故障。</span><span class="sxs-lookup"><span data-stu-id="b1460-564">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="b1460-565">修复了“文件\选项”对话框上的“确定”按钮显示为灰色但功能不受影响的外观问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-565">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

[//]: # (请勿移除功能详细信息内容开头)

## <a name="version-2003-february-28"></a><span data-ttu-id="b1460-568">版本 2003：2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="b1460-568">Version 2003: February 28</span></span>
<span data-ttu-id="b1460-569">*版本 2003（内部版本 12619.20002）*</span><span class="sxs-lookup"><span data-stu-id="b1460-569">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-571">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-571">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-572">Outlook</span></span>

- <span data-ttu-id="b1460-573">**IT 管理员事件通知：** 使用 Outlook for Windows 中的新右侧面板通知，Microsoft 365 租户全局管理员和 Office 应用程序管理员将收到有关影响用户的 Outlook 和 O365 通知。</span><span class="sxs-lookup"><span data-stu-id="b1460-573">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="b1460-574">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-574">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="b1460-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-575">PowerPoint</span></span>

- <span data-ttu-id="b1460-576">**改进了将墨迹转换为图形制表的体验：** 绘制更好的图表，并将其转换为可以操作的 office 对象 [了解详细信息](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="b1460-576">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-579">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-579">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b1460-580">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-580">Excel</span></span>

- <span data-ttu-id="b1460-581">修复了切片器中的文本在打印预览中无法缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-581">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-582">Outlook</span></span>

- <span data-ttu-id="b1460-583">解决了将附件添加到邮件或通过拖放操作（而不是通过菜单）从邮件保存附件时，将更新文件的“上次修改时间”的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-583">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="b1460-584">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-584">Word</span></span>

- <span data-ttu-id="b1460-585">解决了通过批注卡使用 Tab 键时，批注编辑框焦点无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-585">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="b1460-586">如果在公式中插入控件（例如文本内容控件），然后保存再打开文件，会导致“内容不可读”错误。</span><span class="sxs-lookup"><span data-stu-id="b1460-586">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="b1460-587">解决了无法保存之前受密码保护文件至云存储的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-587">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b1460-588">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-588">Office Suite</span></span>

- <span data-ttu-id="b1460-589">修复了从同一 SharePoint 库在 Word/Excel/PowerPoint 中打开多个文件时，只能打开第一个文件进行策略符合性扫描的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-589">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-february-21"></a><span data-ttu-id="b1460-591">版本 2003：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="b1460-591">Version 2003: February 21</span></span>
<span data-ttu-id="b1460-592">*版本 2003（内部版本 12615.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-592">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-594">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-594">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="b1460-595">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-595">Office Suite</span></span>

- <span data-ttu-id="b1460-596">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="b1460-596">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-599">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-599">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-600">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-600">Excel</span></span>
- <span data-ttu-id="b1460-601">修复了用户在重命名数据透视表度量时可能遇到的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-601">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="b1460-602">修复了用户在使用 VBA 宏清除某区域中的内容时可能遇到的性能问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-602">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="b1460-603">修复了用户执行与功能区交互的宏时会导致 UI 闪烁的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-603">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="b1460-604">修复了 CSV 文件中的第一个单词为 TABLE 时无法正确加载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-604">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="b1460-605">修复了用户在切换具有不同缩放级别的两个工作簿时可能遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-605">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-606">Outlook</span></span>
- <span data-ttu-id="b1460-607">解决了 Outlook 在夜间运行时导致用户无法打开公用文件夹邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-607">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="b1460-608">修复了在添加 Gmail 帐户的身份验证工作流程期间位于权限页面上的“允许”和“拒绝”按钮被禁用的竞态条件。</span><span class="sxs-lookup"><span data-stu-id="b1460-608">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="b1460-609">解决了导致 Outlook 在某些情况下意外生成日志输出（即使已关闭日志记录）的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-609">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-610">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-610">Word</span></span>
- <span data-ttu-id="b1460-611">修复了当鼠标指针悬停在批注卡上方时不会始终突出显示批注卡的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-611">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="b1460-612">在活动文档共同创作会话期间，直接向批注卡添加图像可能会导致添加标记。</span><span class="sxs-lookup"><span data-stu-id="b1460-612">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="b1460-613">此问题已修复。</span><span class="sxs-lookup"><span data-stu-id="b1460-613">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b1460-614">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-614">Office Suite</span></span>
- <span data-ttu-id="b1460-615">将 Multichoice/Lookup/Managed-metadata 属性用于 Word/Excel/PowerPoint 文档并保存到 SharePoint 文档库时，这些属性在以前会限制为 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="b1460-615">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="b1460-616">如果这些属性超过 255 个字符，则无法保存此类文档。</span><span class="sxs-lookup"><span data-stu-id="b1460-616">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="b1460-617">通过此次更改后，此限制已增加到 2048 个字符。</span><span class="sxs-lookup"><span data-stu-id="b1460-617">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-february-14"></a><span data-ttu-id="b1460-619">版本 2003：2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="b1460-619">Version 2003: February 14</span></span>
<span data-ttu-id="b1460-620">*版本 2003（内部版本 12607.20000）*</span><span class="sxs-lookup"><span data-stu-id="b1460-620">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-622">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-622">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-623">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-623">Outlook</span></span>

- <span data-ttu-id="b1460-624">**强制 wifi 网络新体验：** 是否已加入需要使用网页登录的 wifi 网络？</span><span class="sxs-lookup"><span data-stu-id="b1460-624">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="b1460-625">现在，Outlook 检测到这一点，帮助你进行连接。</span><span class="sxs-lookup"><span data-stu-id="b1460-625">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-626">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-626">Word</span></span>

- <span data-ttu-id="b1460-627">**在绘图工具箱中查找墨迹编辑器：** 选择“绘图”，然后选择“墨迹编辑器”笔使用手指或数字笔编辑文档。</span><span class="sxs-lookup"><span data-stu-id="b1460-627">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="b1460-628">了解更多</span><span class="sxs-lookup"><span data-stu-id="b1460-628">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="b1460-629">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-629">Office Suite</span></span>

- <span data-ttu-id="b1460-630">**更清晰的状态栏图标：** 状态栏图标现在更容易看到</span><span class="sxs-lookup"><span data-stu-id="b1460-630">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-633">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-633">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b1460-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-634">Outlook</span></span>

- <span data-ttu-id="b1460-635">解决了导致用户无法访问“ 闲/忙选项”日历权限对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-635">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="b1460-636">修复了以下问题：打开从不同时区发送的定期会议实例时出现警告“很抱歉，无法打开此项目”。</span><span class="sxs-lookup"><span data-stu-id="b1460-636">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="b1460-637">解决了可能导致用户在从邮件中拖拽附件后无法重新打开 .msg 文件的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-637">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="b1460-638">修复了将文件附件从 Outlook 上传到 OneDrive 后出现的问题，如果附件名称包含圆括号，则会导致文件名被更改。</span><span class="sxs-lookup"><span data-stu-id="b1460-638">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-639">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-639">PowerPoint</span></span>

- <span data-ttu-id="b1460-640">修复了可能导致无法保存文档至含 Excel 图表的 PowerPoint 或 Word 的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-640">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-641">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-641">Word</span></span>

- <span data-ttu-id="b1460-642">修复了导出至 PDF 时文档中的图片失去透明度的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-642">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-february-07"></a><span data-ttu-id="b1460-644">版本 2002：2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="b1460-644">Version 2002: February 07</span></span>
<span data-ttu-id="b1460-645">*版本 2002（内部版本 12527.20040）*</span><span class="sxs-lookup"><span data-stu-id="b1460-645">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="b1460-647">功能更新</span><span class="sxs-lookup"><span data-stu-id="b1460-647">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b1460-648">Access</span><span class="sxs-lookup"><span data-stu-id="b1460-648">Access</span></span>

- <span data-ttu-id="b1460-649">**在“查询设计器”、“SQL 视图”和“关系”窗口中更高效地工作：** 右键单击表格，以对其进行打开、设计、调整大小和隐藏操作。</span><span class="sxs-lookup"><span data-stu-id="b1460-649">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="b1460-650">在 SQL 视图中搜索和替换文本。</span><span class="sxs-lookup"><span data-stu-id="b1460-650">Search and replace text in SQL View.</span></span> <span data-ttu-id="b1460-651">在“关系”窗口中选择多个表。</span><span class="sxs-lookup"><span data-stu-id="b1460-651">Select multiple tables in the Relationships window.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="b1460-654">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="b1460-654">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b1460-655">Access</span><span class="sxs-lookup"><span data-stu-id="b1460-655">Access</span></span>

- <span data-ttu-id="b1460-656">此更新修复了使用 ADODB 的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-656">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="b1460-657">VB 代码中的记录器对象可能会错误地报告错误。</span><span class="sxs-lookup"><span data-stu-id="b1460-657">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="b1460-658">此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。</span><span class="sxs-lookup"><span data-stu-id="b1460-658">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="b1460-659">Excel</span><span class="sxs-lookup"><span data-stu-id="b1460-659">Excel</span></span>

- <span data-ttu-id="b1460-660">解决了将文本分列用于动态数组时 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-660">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="b1460-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="b1460-661">Outlook</span></span>

- <span data-ttu-id="b1460-662">解决了在采用月视图的日历中进行滚动时无法显示以前的日历事件的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-662">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="b1460-663">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到系统崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-663">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b1460-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b1460-664">PowerPoint</span></span>

- <span data-ttu-id="b1460-665">修复了以下问题：关闭文件后，如果有任何事件处理程序正在运行，PowerPoint 不会立即从演示文稿集合中删除该文件。</span><span class="sxs-lookup"><span data-stu-id="b1460-665">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="b1460-666">因此，由对象模型报告的打开的演示文稿数目不正确，并且系统会阻止关闭 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="b1460-666">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="b1460-667">修复了荧光笔问题：带有黑色荧光笔颜色的白色文本在打印后显示为灰度中的黑色。</span><span class="sxs-lookup"><span data-stu-id="b1460-667">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="b1460-668">Word</span><span class="sxs-lookup"><span data-stu-id="b1460-668">Word</span></span>

- <span data-ttu-id="b1460-669">更新和滚动浏览目录时，有时可能会在文档上显示灰色区域。</span><span class="sxs-lookup"><span data-stu-id="b1460-669">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="b1460-670">修复了共同创作文档时可能不会保留根批注的草稿版本的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-670">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="b1460-671">修复了在批注卡之间来回切换时有时会显示最初所选批注并突出显示所选内容的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-671">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="b1460-672">修复了以下问题：如果编写了批注但未发布内容且用户尝试了保存文件，则使用“浏览”保存文件将不起作用。</span><span class="sxs-lookup"><span data-stu-id="b1460-672">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="b1460-673">在启用 SlideTrack 并关闭批注窗格后，按 Ctrl+Alt+M 可能无法打开批注窗格。</span><span class="sxs-lookup"><span data-stu-id="b1460-673">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="b1460-674">修复了在表中添加 @提及时可能会生成错误消息“此文档中的某个表格已损坏”的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-674">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b1460-675">Office 套件</span><span class="sxs-lookup"><span data-stu-id="b1460-675">Office Suite</span></span>

- <span data-ttu-id="b1460-676">解决了可能是导致无法正确安装挪威尼诺斯克语 (nn-no) 校对工具程序包的原因的问题。</span><span class="sxs-lookup"><span data-stu-id="b1460-676">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)
