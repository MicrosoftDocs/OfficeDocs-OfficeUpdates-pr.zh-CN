---
title: 有关 2019 年半年频道（定向）发行的发行说明
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2019 年 Office 365 专业增强版半年频道（定向）发行的发行说明
ms.openlocfilehash: b0a39d61122691cd6a007866ec80444848e7389b
ms.sourcegitcommit: 2474d341cb1c1c2e0b43b5c324345d853e192c59
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/04/2020
ms.locfileid: "44565047"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a><span data-ttu-id="7305b-103">有关 2019 年半年频道（定向）发行的发行说明</span><span class="sxs-lookup"><span data-stu-id="7305b-103">Release notes for Semi-Annual Channel (Targeted) releases in 2019</span></span>

<span data-ttu-id="7305b-104">这些发行说明提供了 2019 年 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 Business 的半年频道（定向）更新中所包含的新功能和非安全更新的相关信息。</span><span class="sxs-lookup"><span data-stu-id="7305b-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel (Targeted) updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="7305b-105">我们经常会过一段时间就将功能（有时甚至是修补程序）发布到半年频道（定向）更新。</span><span class="sxs-lookup"><span data-stu-id="7305b-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="7305b-106">如果没有立即看到下述内容，则很快就会看到的。</span><span class="sxs-lookup"><span data-stu-id="7305b-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="7305b-107">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - <span data-ttu-id="7305b-108">Microsoft Teams 包含在半年频道(定向)的新安装中，从版本 1902 开始。</span><span class="sxs-lookup"><span data-stu-id="7305b-108">Microsoft Teams is included in new installations of Semi-Annual Channel(Targeted), starting with Version 1902.</span></span> <span data-ttu-id="7305b-109">当半年频道(定向)的现有安装更新到版本 1908 或更高版本时，将向现有安装添加 Teams。</span><span class="sxs-lookup"><span data-stu-id="7305b-109">Teams will be added to existing installations of Semi-Annual Channel(Targeted) when those are updated to Version 1908 or later.</span></span> <span data-ttu-id="7305b-110">有关详细信息，请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](https://docs.microsoft.com/DeployOffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="7305b-110">For more information, see [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).</span></span>

## <a name="version-1908-december-10"></a><span data-ttu-id="7305b-111">版本 1908：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7305b-111">Version 1908: December 10</span></span>
<span data-ttu-id="7305b-112">*版本 1908（内部版本 11929.20516）*</span><span class="sxs-lookup"><span data-stu-id="7305b-112">*Version 1908 (Build 11929.20516)*</span></span>

<span data-ttu-id="7305b-113">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-113">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="7305b-115">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="7305b-115">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7305b-116">Access</span><span class="sxs-lookup"><span data-stu-id="7305b-116">Access</span></span>

- <span data-ttu-id="7305b-117">修复了包含对远程表（例如 SQL Server 表）的引用的联合查询可能导致 Access 关闭并重新启动的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-117">Fixed an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="7305b-118">修复了诸如“总和”等聚合可能将结果截断为整数值的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-118">Fixed an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

### <a name="excel"></a><span data-ttu-id="7305b-119">Excel</span><span class="sxs-lookup"><span data-stu-id="7305b-119">Excel</span></span>

- <span data-ttu-id="7305b-120">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-120">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="7305b-121">我们修复了当 OLAP 数据透视表的筛选器设置为已从多维数据集中删除的值时的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-121">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="7305b-122">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-122">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="7305b-123">解决了 Lookup 函数可能返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-123">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="7305b-124">显著提高了删除包含合并单元格的列时的性能。</span><span class="sxs-lookup"><span data-stu-id="7305b-124">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="7305b-125">解决了导致激活最小化窗口的宏运行时错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-125">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

### <a name="outlook"></a><span data-ttu-id="7305b-126">Outlook</span><span class="sxs-lookup"><span data-stu-id="7305b-126">Outlook</span></span>

- <span data-ttu-id="7305b-127">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-127">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="7305b-128">解决了导致用户在打开“规则”对话框时看到&quot;此计算机上的规则与 Microsoft Exchange 上的规则不匹配&quot;提示的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-128">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="7305b-129">解决了导致 Web 加载项在不应该访问“数字版权管理”消息时访问它们的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-129">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

### <a name="word"></a><span data-ttu-id="7305b-130">Word</span><span class="sxs-lookup"><span data-stu-id="7305b-130">Word</span></span>

- <span data-ttu-id="7305b-131">我们修复了跟踪更改有时会陷入无限循环的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-131">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7305b-132">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-132">Office Suite</span></span>

- <span data-ttu-id="7305b-133">修复了在 PowerPoint 中的竖排文本框中，半角片假名字符未正确旋转的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-133">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="7305b-134">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-134">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="7305b-135">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="7305b-135">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-22"></a><span data-ttu-id="7305b-137">版本 1908：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7305b-137">Version 1908: November 22</span></span>
<span data-ttu-id="7305b-138">*版本 1908（内部版本 11929.20494）*</span><span class="sxs-lookup"><span data-stu-id="7305b-138">*Version 1908 (Build 11929.20494)*</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="7305b-140">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="7305b-140">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="7305b-141">Access</span><span class="sxs-lookup"><span data-stu-id="7305b-141">Access</span></span>

- <span data-ttu-id="7305b-142">已修复关于运行更新查询会错误地给出“查询已损坏”错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-142">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="excel"></a><span data-ttu-id="7305b-143">Excel</span><span class="sxs-lookup"><span data-stu-id="7305b-143">Excel</span></span>

- <span data-ttu-id="7305b-144">当文件具有大量条件格式时，单击“字体颜色”按钮时会出现性能较低的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-144">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="7305b-145">我们修复了打印预览中的打印区域不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-145">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="7305b-146">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-146">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="7305b-147">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-147">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="7305b-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="7305b-148">Outlook</span></span>

- <span data-ttu-id="7305b-149">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“&quot;确定&quot;”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-149">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="7305b-150">进行更改后，管理员能够启用策略以便在自动发现身份验证提示中首选提供的帐户电子邮件而不是 UPN。</span><span class="sxs-lookup"><span data-stu-id="7305b-150">Made a change that allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="7305b-151">默认情况下，自动发现优先于帐户 UPN（如果可用）。</span><span class="sxs-lookup"><span data-stu-id="7305b-151">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="7305b-152">解决了导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-152">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="7305b-153">解决了导致用户尝试从&quot;错过的对话&quot;消息创建规则时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-153">Addressed an issue that caused users to experience a crash when attempting to create a rule from a &quot;Missed Conversation&quot; message.</span></span>

- <span data-ttu-id="7305b-154">解决导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-154">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

### <a name="word"></a><span data-ttu-id="7305b-155">Word</span><span class="sxs-lookup"><span data-stu-id="7305b-155">Word</span></span>

- <span data-ttu-id="7305b-156">我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-156">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7305b-157">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-157">Office Suite</span></span>

- <span data-ttu-id="7305b-158">修复了防止 PowerPoint 用户在尝试联机演示时遇到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-158">Fixed an issue to prevent PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="7305b-159">改进了有关注册表完整性的 Office 更新进程的可靠性。</span><span class="sxs-lookup"><span data-stu-id="7305b-159">Improved reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="7305b-160">更正了按流量计费的网络上可能意外阻止更新的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-160">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="7305b-161">修复了 ODT 和 GPO Updae Deadline 设置中相对截止日期仅在第一次设置时起作用，修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-161">Fixed an issue in ODT and GPO Updae Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-12"></a><span data-ttu-id="7305b-163">版本 1908：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7305b-163">Version 1908: November 12</span></span>
<span data-ttu-id="7305b-164">*版本 1908（内部版本 11929.20436）*</span><span class="sxs-lookup"><span data-stu-id="7305b-164">*Version 1908 (Build 11929.20436)*</span></span>

<span data-ttu-id="7305b-165">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-165">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="7305b-167">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="7305b-167">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="7305b-168">Excel</span><span class="sxs-lookup"><span data-stu-id="7305b-168">Excel</span></span>

- <span data-ttu-id="7305b-169">修复了使用图表模板插入图表时预览中所用颜色的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-169">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>
- <span data-ttu-id="7305b-170">我们修复了在更改系列集合时可能导致散点图和折线图无法正确呈现的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-170">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>
- <span data-ttu-id="7305b-171">解决了在使用运行的宏更改自定义属性时导致共同创作中断的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-171">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>
- <span data-ttu-id="7305b-172">我们解决了异步用户定义函数的性能问题，该问题导致它们同步运行。</span><span class="sxs-lookup"><span data-stu-id="7305b-172">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>
- <span data-ttu-id="7305b-173">我们显著提高了按颜色筛选的性能。</span><span class="sxs-lookup"><span data-stu-id="7305b-173">We have significantly improved the performance of filtering by color.</span></span>
- <span data-ttu-id="7305b-174">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。</span><span class="sxs-lookup"><span data-stu-id="7305b-174">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>
- <span data-ttu-id="7305b-175">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="7305b-175">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

### <a name="outlook"></a><span data-ttu-id="7305b-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="7305b-176">Outlook</span></span>

- <span data-ttu-id="7305b-177">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="7305b-177">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="7305b-178">解决了在将用户主日历中的项复制到组日历时出现导致用户遇到权限错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-178">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>
- <span data-ttu-id="7305b-179">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-179">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>
- <span data-ttu-id="7305b-180">解决了导致用户在 Outlook 中与特定安全链接交互时遇到失败的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-180">Addressed an issue that would cause users to experience a failure in Outlook when interacting with certain safelinks.</span></span>
- <span data-ttu-id="7305b-181">解决了导致用户在处理某些自动发现响应时遇到失败的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-181">Addressed an issue that caused users to experience a failure when processing some AutoDiscover responses.</span></span>
- <span data-ttu-id="7305b-182">解决了导致某些用户在添加辅助 Exchange 帐户时会看到创建重复的特殊文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-182">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>
- <span data-ttu-id="7305b-183">解决了导致搜索反馈体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-183">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7305b-184">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7305b-184">PowerPoint</span></span>

- <span data-ttu-id="7305b-185">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="7305b-185">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="7305b-186">可靠性修复：修复了第三方加载项可能导致 PowerPoint 失败的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-186">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="project"></a><span data-ttu-id="7305b-187">Project</span><span class="sxs-lookup"><span data-stu-id="7305b-187">Project</span></span>

- <span data-ttu-id="7305b-188">修复了“全部调配”命令无法正确解决资源过度分配的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-188">Fixed an issue where the Level All command wasn't properly resolving a resource overallocation.</span></span>
- <span data-ttu-id="7305b-189">修复了以下问题：如果你的任务分配为零工作，该任务可能无法标记为已完成，并且始终显示为 99％。</span><span class="sxs-lookup"><span data-stu-id="7305b-189">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>
- <span data-ttu-id="7305b-190">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-190">Identified an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="word"></a><span data-ttu-id="7305b-191">Word</span><span class="sxs-lookup"><span data-stu-id="7305b-191">Word</span></span>

- <span data-ttu-id="7305b-192">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="7305b-192">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="7305b-193">修复了应用可能会在关闭时挂起的各种问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-193">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="7305b-194">此外，修复了某些与加载项相关的失败。</span><span class="sxs-lookup"><span data-stu-id="7305b-194">Also fixed certain add-in related failures.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7305b-195">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-195">Office Suite</span></span>

- <span data-ttu-id="7305b-196">解决了与第三方插件中的“文本框/形状自动调整”属性相关的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-196">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="october-15"></a><span data-ttu-id="7305b-198">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7305b-198">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="7305b-199">非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-199">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="7305b-200">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-200">Office Suite</span></span>
- <span data-ttu-id="7305b-201">我们暂时禁用了“云保存”对话框，以解决了我们在 2019 年 10 月 14 日对 16.0.11929.20396 之前的内部版本发布的保存问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-201">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 16.0.11929.20396.</span></span> <span data-ttu-id="7305b-202">此功能很快将重新启用。</span><span class="sxs-lookup"><span data-stu-id="7305b-202">This feature will be re-enabled soon.</span></span>

## <a name="version-1908-october-14"></a><span data-ttu-id="7305b-203">版本 1908：10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7305b-203">Version 1908: October 14</span></span>
<span data-ttu-id="7305b-204">*版本 1908（内部版本 11929.20396）*</span><span class="sxs-lookup"><span data-stu-id="7305b-204">*Version 1908 (Build 11929.20396)*</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="7305b-206">非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-206">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7305b-207">Excel</span><span class="sxs-lookup"><span data-stu-id="7305b-207">Excel</span></span>

- <div><span data-ttu-id="7305b-208">解决了一个“查找和替换”问题，即在找到第一个项目后它改变了对话框中焦点的位置。</span><span class="sxs-lookup"><span data-stu-id="7305b-208">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span></div>

### <a name="office-suite"></a><span data-ttu-id="7305b-209">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-209">Office Suite</span></span>

- <span data-ttu-id="7305b-210">解决了对于 16.0.11929.20396 之前的内部版本而言，用户可能无法保存 Word、Excel 和 PowerPoint 2019 文档的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-210">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 16.0.11929.20396.</span></span>  <span data-ttu-id="7305b-211">此问题会影响创建新文件并在单击“保存”图标或按 Ctrl+S 后显示“另存为”对话框的用户。</span><span class="sxs-lookup"><span data-stu-id="7305b-211">This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="7305b-212">解决了一个问题，即在某些情况下，Office 快捷方式可能会在更新后消失。</span><span class="sxs-lookup"><span data-stu-id="7305b-212">Resolved an issue where in certain circumstances, Office shortcuts may disappear following an update.</span></span>  <span data-ttu-id="7305b-213">此更新改进了发布 Office 快捷方式的可靠性。</span><span class="sxs-lookup"><span data-stu-id="7305b-213">This update improves reliability when publishing of Office shortcuts.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-october-08"></a><span data-ttu-id="7305b-215">版本 1908：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7305b-215">Version 1908: October 08</span></span>
<span data-ttu-id="7305b-216">*版本 1908（内部版本 11929.20388）*</span><span class="sxs-lookup"><span data-stu-id="7305b-216">*Version 1908 (Build 11929.20388)*</span></span>

<span data-ttu-id="7305b-217">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="7305b-219">非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-219">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7305b-220">Excel</span><span class="sxs-lookup"><span data-stu-id="7305b-220">Excel</span></span>

- <span data-ttu-id="7305b-221">解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-221">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="7305b-222">修复了在加载项管理器中浏览时允许显示超过 16 个加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-222">Fixed an issue to enable more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="7305b-223">修复了在 Excel 创意功能中发现一个的问题，即通过单击 Win32 客户端中的“创意”按钮加载加载项时出错。</span><span class="sxs-lookup"><span data-stu-id="7305b-223">Fixed issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="7305b-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="7305b-224">Outlook</span></span>

- <span data-ttu-id="7305b-225">解决了导致简单悬停 URL 无法显示某些安全链接的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-225">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="7305b-226">已将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="7305b-226">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="7305b-227">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-227">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7305b-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7305b-228">PowerPoint</span></span>

- <span data-ttu-id="7305b-229">修复了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-229">Fixed an issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7305b-230">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-230">Office Suite</span></span>

- <span data-ttu-id="7305b-231">修复了用户打开文件时可能遇到的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-231">Fixed an issue for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="7305b-232">修复了在后台的信息放置面板中未显示可访问性信息的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-232">Fixed an issue where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="7305b-233">通过恢复以前可能已中断的下载，增强了下载 Office 更新时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="7305b-233">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="7305b-234">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="7305b-234">To protect Office customer’s security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-september-10"></a><span data-ttu-id="7305b-236">版本 1908：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7305b-236">Version 1908: September 10</span></span>
<span data-ttu-id="7305b-237">*版本 1908（内部版本 11929.20300）*</span><span class="sxs-lookup"><span data-stu-id="7305b-237">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="7305b-238">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-238">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="7305b-240">功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-240">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7305b-241">Access</span><span class="sxs-lookup"><span data-stu-id="7305b-241">Access</span></span>

- <span data-ttu-id="7305b-242">**缩放更多空间：** 让缩放框变大，更改字体，缩放功能会记住一切。</span><span class="sxs-lookup"><span data-stu-id="7305b-242">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="7305b-243">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-243">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- <span data-ttu-id="7305b-244">**密切关注数据库对象：** 可以清楚地看到活动选项卡，轻松拖动选项卡以重新排列它们，并且只需单击一下即可关闭数据库对象。</span><span class="sxs-lookup"><span data-stu-id="7305b-244">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="7305b-245">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="7305b-245">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7305b-246">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="7305b-246">Switching between them has never been easier.</span></span> [<span data-ttu-id="7305b-247">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-247">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a><span data-ttu-id="7305b-248">Excel</span><span class="sxs-lookup"><span data-stu-id="7305b-248">Excel</span></span>

- <span data-ttu-id="7305b-p110">**深入发掘数据：** 全新的“想法”按钮可查找数据中的模式并使用这些模式创建智能、个性化的建议。[了解详细信息](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="7305b-p110">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="7305b-251">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="7305b-251">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="7305b-252">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="7305b-252">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="7305b-253">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="7305b-253">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="7305b-254">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="7305b-254">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="7305b-255">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="7305b-255">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="7305b-256">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="7305b-256">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7305b-257">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="7305b-257">Switching between them has never been easier.</span></span> [<span data-ttu-id="7305b-258">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-258">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="7305b-259">**见证工作表生动起来的过程：** 插入动态 3D 图形，观看心跳、行星轨道和霸王龙在整个工作簿中四处跳动。</span><span class="sxs-lookup"><span data-stu-id="7305b-259">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="7305b-260">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="7305b-260">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="7305b-261">**协作更简单：** 共同创作改进意味着使用条件格式、单元格样式等时，所做的更改将与协作者无缝合并。</span><span class="sxs-lookup"><span data-stu-id="7305b-261">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="7305b-262">**在类似列上连接表：** 在比较用于合并表的列时，获取和转换 (Power Query) 现在具有近似文本匹配逻辑（也称为模糊匹配）。</span><span class="sxs-lookup"><span data-stu-id="7305b-262">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="7305b-263">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-263">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="7305b-264">**使用 Power Query 增强功能快速编码：** 使用自动完成和语法着色快速完成代码编写。</span><span class="sxs-lookup"><span data-stu-id="7305b-264">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="7305b-265">也可以轻松发现函数、列和参数。</span><span class="sxs-lookup"><span data-stu-id="7305b-265">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="7305b-266">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="7305b-266">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7305b-267">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="7305b-267">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7305b-268">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-268">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="7305b-269">Outlook</span><span class="sxs-lookup"><span data-stu-id="7305b-269">Outlook</span></span>

- <span data-ttu-id="7305b-270">**移动邮件时继续工作：** Outlook 现在在后台移动邮件，因此你可以在文件夹之间移动大量邮件时继续工作。</span><span class="sxs-lookup"><span data-stu-id="7305b-270">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="7305b-271">**在连续召开的会议之间提供时间：** 默认将会议设置为提前 5-10 分钟结束，让与会者有时间喘口气或来往于不同地点。</span><span class="sxs-lookup"><span data-stu-id="7305b-271">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="7305b-p118">**清晰呈现思路：** 当文本或静态图像不起作用时，请使用动态 GIF 来发表你的观点。[了解详细信息](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="7305b-p118">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="7305b-274">**我们已经为你更新了 Outlook 用户体验：** 简化的体验，以前可供预览，现即将推出，旨在帮助你关注最重要的内容。</span><span class="sxs-lookup"><span data-stu-id="7305b-274">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="7305b-275">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-275">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="7305b-276">**更紧凑还是更宽松的布局？由你决定：**“更紧凑的间距”让你能够决定是希望项目之间间距更大，还是希望布局更紧凑以显示更多内容。</span><span class="sxs-lookup"><span data-stu-id="7305b-276">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="7305b-277">**还可自定义的简化功能区：** 最常用的按钮排成一行，带给你简化体验。</span><span class="sxs-lookup"><span data-stu-id="7305b-277">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="7305b-278">可在经典视图和简化视图之间轻松切换，还可固定/取消固定命令。</span><span class="sxs-lookup"><span data-stu-id="7305b-278">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="7305b-279">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="7305b-279">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="7305b-280">**添加帐户的更快捷方式：** 由于帐户设置改进，现在可以更轻松地将使用双重身份验证的 Outlook.com 和 Gmail 帐户添加到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="7305b-280">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="7305b-281">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-281">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="7305b-282">**挑选你喜欢的操作：** 不要使用“标志”和“删除”？</span><span class="sxs-lookup"><span data-stu-id="7305b-282">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="7305b-283">“存档”或“标记为已读”呢？</span><span class="sxs-lookup"><span data-stu-id="7305b-283">How about Archive or Mark as Read?</span></span> <span data-ttu-id="7305b-284">使用你最常用的命令自定义快速操作菜单。</span><span class="sxs-lookup"><span data-stu-id="7305b-284">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="7305b-285">**告别同步限制：** Outlook 改进意味着文件夹限制已取消，因此请继续操作并同步共享邮箱。</span><span class="sxs-lookup"><span data-stu-id="7305b-285">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="7305b-286">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="7305b-286">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7305b-287">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="7305b-287">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7305b-288">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-288">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="7305b-289">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7305b-289">PowerPoint</span></span>

- <span data-ttu-id="7305b-p124">**邀请受众参加测验或调查：** 幻灯片上放入测验或调查。Office 为你收集并存储该响应。[了解详细信息](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="7305b-p124">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="7305b-293">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="7305b-293">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="7305b-294">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="7305b-294">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="7305b-295">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="7305b-295">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="7305b-296">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="7305b-296">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="7305b-297">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="7305b-297">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="7305b-298">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="7305b-298">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="7305b-p127">**比以往更轻松地插入联机视频：** 想要将 Vimeo 或 YouTube 中的视频放到幻灯片上？只需使用视频页面链接即可。[了解详细信息](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="7305b-p127">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="7305b-302">**切换效果更好：** 对形状命名，以更好地掌控其平滑效果。</span><span class="sxs-lookup"><span data-stu-id="7305b-302">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="7305b-303">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="7305b-303">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="7305b-304">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="7305b-304">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7305b-305">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="7305b-305">Switching between them has never been easier.</span></span> [<span data-ttu-id="7305b-306">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-306">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="7305b-307">**联机视频获得新的存储位置：** 将视频保存到 Microsoft Stream，以便组织中的任何人都可以看到它。</span><span class="sxs-lookup"><span data-stu-id="7305b-307">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="7305b-308">插入视频链接，只需占用相当于相应文件大小的一小部分的空间，即可享受多媒体演示。</span><span class="sxs-lookup"><span data-stu-id="7305b-308">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="7305b-309">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-309">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="7305b-310">**搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。</span><span class="sxs-lookup"><span data-stu-id="7305b-310">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7305b-311">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="7305b-311">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7305b-312">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-312">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="7305b-313">Project</span><span class="sxs-lookup"><span data-stu-id="7305b-313">Project</span></span>

- <span data-ttu-id="7305b-314">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="7305b-314">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7305b-315">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="7305b-315">Switching between them has never been easier.</span></span> [<span data-ttu-id="7305b-316">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-316">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="7305b-317">Visio</span><span class="sxs-lookup"><span data-stu-id="7305b-317">Visio</span></span>

- <span data-ttu-id="7305b-p133">**告别断开的 Excel 链接：** 找不到链接到 Data Visualizer 图表的 Excel 工作簿？ 重新链接，你又可以开工了。[了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="7305b-p133">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="7305b-321">**内置 Azure 模具：** 使用数十个 Azure 模具设计云应用或规划基础结构。</span><span class="sxs-lookup"><span data-stu-id="7305b-321">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="7305b-322">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-322">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="7305b-323">**数据流程图上的 Double-take：** 数据可视化工具流程图上引入注目的新布局干净、清爽且易于理解。</span><span class="sxs-lookup"><span data-stu-id="7305b-323">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="7305b-324">单击“设计”选项卡可查看选项。</span><span class="sxs-lookup"><span data-stu-id="7305b-324">Click the Design tab for options.</span></span>

- <span data-ttu-id="7305b-325">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="7305b-325">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7305b-326">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="7305b-326">Switching between them has never been easier.</span></span> [<span data-ttu-id="7305b-327">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-327">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="7305b-328">**将流程图导出至 Word：** 向 Word 文档自动添加流程图内容，如形状和元数据。</span><span class="sxs-lookup"><span data-stu-id="7305b-328">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="7305b-329">然后自定义文档以创建过程指南和操作手册。</span><span class="sxs-lookup"><span data-stu-id="7305b-329">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="7305b-330">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-330">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="7305b-331">**从 Power BI 导出 Visio 视觉对象：** 将 Power BI 导出为 PDF、PowerPoint 文件等时，Power BI 的 Visio 视觉对象现在将会正常显示。</span><span class="sxs-lookup"><span data-stu-id="7305b-331">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="7305b-332">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-332">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="7305b-333">Word</span><span class="sxs-lookup"><span data-stu-id="7305b-333">Word</span></span>

- <span data-ttu-id="7305b-p139">**使用笔迹编辑器随心编辑：** 使用单个笔划、拆分或连接字词、添加新行或使用手写笔插入字词。[了解详细信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="7305b-p139">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="7305b-p140">**将文档从静态转换为惊艳：** 将文档转换为易于共享的交互式网页，使其在任何设备上都看起来很棒。[了解更多](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="7305b-p140">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="7305b-338">**使用 \@提及功能引起他人的注意：** 在批注中使用 @提及，以在需要他人的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="7305b-338">**Get Their Attention with \@Mentions:** Use @mentions in comments to let others know when you need their input.</span></span> [<span data-ttu-id="7305b-339">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="7305b-339">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="7305b-p142">**使用 Line Focus 提高理解力：** 专心地逐行浏览文档。调整焦点，一目一行、三行或五行。[了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="7305b-p142">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="7305b-343">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="7305b-343">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="7305b-344">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="7305b-344">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="7305b-345">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="7305b-345">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="7305b-346">**增加内容的覆盖面：** 需要让你的文档易于访问？</span><span class="sxs-lookup"><span data-stu-id="7305b-346">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="7305b-347">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="7305b-347">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="7305b-348">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="7305b-348">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="7305b-349">**“学习工具”模式可额外支持更多页面颜色：** Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。</span><span class="sxs-lookup"><span data-stu-id="7305b-349">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="7305b-350">许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。</span><span class="sxs-lookup"><span data-stu-id="7305b-350">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="7305b-351">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="7305b-351">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7305b-352">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="7305b-352">Switching between them has never been easier.</span></span> [<span data-ttu-id="7305b-353">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-353">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- <span data-ttu-id="7305b-354">**搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。</span><span class="sxs-lookup"><span data-stu-id="7305b-354">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7305b-355">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="7305b-355">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7305b-356">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-356">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="7305b-357">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-357">Office Suite</span></span>

- <span data-ttu-id="7305b-358">**Microsoft Teams 的安装：** 向 Office 365 专业增强版的现有安装添加了 Teams。</span><span class="sxs-lookup"><span data-stu-id="7305b-358">**Installation of Microsoft Teams:** Teams is added to existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="7305b-359">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-359">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

- <span data-ttu-id="7305b-360">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="7305b-360">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="7305b-361">**隐私控制：** 对诊断数据和连接体验的全新、更新和改进控制。</span><span class="sxs-lookup"><span data-stu-id="7305b-361">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="7305b-362">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-362">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="7305b-363">**Office 图标具有新的外观：** Office 图标经过重新设计，可体现简单、强大和智能的 Office 体验。</span><span class="sxs-lookup"><span data-stu-id="7305b-363">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="7305b-364">**Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="7305b-364">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="7305b-365">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-365">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="7305b-368">非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-368">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7305b-369">Excel</span><span class="sxs-lookup"><span data-stu-id="7305b-369">Excel</span></span>

- <span data-ttu-id="7305b-370">修复了 Excel 中的问题，其中分配给形状或表单控件的宏可能显示不正确的错误消息，或者可能在不正确的目标区域中工作。</span><span class="sxs-lookup"><span data-stu-id="7305b-370">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="7305b-371">修复了以下问题：在更改数据透视表的排序方式并在与其他用户进行共同创作会话期间刷新它时可能会导致其失败。</span><span class="sxs-lookup"><span data-stu-id="7305b-371">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could cause it to fail.</span></span>

- <span data-ttu-id="7305b-372">解决了导致瀑布图和漏斗图无法在插入或删除单元格时与表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-372">Fixed an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="7305b-373">已修复了 Excel 中的合并冲突问题，该问题会导致系统提示用户重新打开工作簿以使更改生效。</span><span class="sxs-lookup"><span data-stu-id="7305b-373">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="7305b-374">解决了在与其他人共同创作时表旁边的剪切和粘贴操作失败的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-374">Fixed an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook"></a><span data-ttu-id="7305b-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="7305b-375">Outlook</span></span>

- <span data-ttu-id="7305b-376">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得与其 Outlook 配置文件关联的错误帐户的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-376">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="7305b-377">解决了导致部分 POP3 用户看到无论设置如何，其所有电子邮件均采用纯文本格式的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-377">Fixed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="7305b-378">此修补程序将还原 HTML 格式邮件的视图。</span><span class="sxs-lookup"><span data-stu-id="7305b-378">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="7305b-379">解决了导致用户无法通过屏幕阅读器访问位置建议的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-379">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="7305b-380">已修复导致某些用户在尝试检索 Outlook 的云设置时遇到身份验证错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-380">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="7305b-381">解决了导致经理不清楚代理人是否已响应指定的会议请求的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-381">Fixed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="7305b-382">修复了导致 Outlook 用户在某些情况下“需要密码”的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-382">Fixed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="7305b-383">解决导致当前文件夹搜索间歇性失败的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-383">Fixed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="7305b-384">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="7305b-384">Fixed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="7305b-385">修复了导致用户在使用云附件时看到错误“无法找到此文件。</span><span class="sxs-lookup"><span data-stu-id="7305b-385">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="7305b-386">验证路径和文件名是否正确”的临时服务问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-386">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="7305b-387">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-387">Learn More</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="7305b-388">修复了以下问题：用户看到从 Outlook 上传到 OneDrive 或 Sharepoint 的文件名已更改，其中多个字符替换为下划线。</span><span class="sxs-lookup"><span data-stu-id="7305b-388">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

- <span data-ttu-id="7305b-389">已修复非英语用户邮件中的主题行非常小的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-389">Fixed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7305b-390">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7305b-390">PowerPoint</span></span>

- <span data-ttu-id="7305b-391">修复了某些加载项会在图表中的形状周围引发意外错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-391">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="7305b-392">修复了还原 PowerPoint 视频控件易于访问的名称的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-392">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="7305b-393">修复了可能阻止某些动画启动的问题</span><span class="sxs-lookup"><span data-stu-id="7305b-393">Fixed an issue which could prevent some animations from starting</span></span>

### <a name="project"></a><span data-ttu-id="7305b-394">Project</span><span class="sxs-lookup"><span data-stu-id="7305b-394">Project</span></span>

- <span data-ttu-id="7305b-395">修复了 Windows 7 上的用户能够从 Project Web App 和 SharePoint 网站打开项目的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-395">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>


### <a name="visio"></a><span data-ttu-id="7305b-396">Visio</span><span class="sxs-lookup"><span data-stu-id="7305b-396">Visio</span></span>

- <span data-ttu-id="7305b-397">从 Visio 导出到 SVG 的操作无法用于各种形状。</span><span class="sxs-lookup"><span data-stu-id="7305b-397">Export to SVG from Visio was not working for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="7305b-398">Word</span><span class="sxs-lookup"><span data-stu-id="7305b-398">Word</span></span>

- <span data-ttu-id="7305b-399">修复了用户在 Word 文档中与他人协作时收到错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-399">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

- <span data-ttu-id="7305b-400">修复了一个问题，该问题导致用户在尝试共享存储在 SharePoint 2016 上的文件时收到消息“抱歉，无法我们共享此内容”。</span><span class="sxs-lookup"><span data-stu-id="7305b-400">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7305b-401">Office 套件</span><span class="sxs-lookup"><span data-stu-id="7305b-401">Office Suite</span></span>

- <span data-ttu-id="7305b-402">解决了以下问题：在某些情况下，同步引擎支持的 sharepoint 文件可能显示“已保存”，但并未真正保存任何更改。</span><span class="sxs-lookup"><span data-stu-id="7305b-402">Fixed an issue where in some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes.</span></span>

- <span data-ttu-id="7305b-403">修复了大型树视图失败的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-403">Fixed an issue where large tree views were failing.</span></span>

- <span data-ttu-id="7305b-404">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-404">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-august-13"></a><span data-ttu-id="7305b-406">版本 1902：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7305b-406">Version 1902: August 13</span></span>
<span data-ttu-id="7305b-407">*版本 1902（内部版本 11328.20392）*</span><span class="sxs-lookup"><span data-stu-id="7305b-407">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="7305b-408">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7305b-409">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-409">Excel: Non-security updates</span></span>
- <span data-ttu-id="7305b-410">修复了表中针对已筛选切片器和未筛选切片器均显示清除筛选器图标的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-410">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7305b-411">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-411">Outlook: Non-security updates</span></span>
- <span data-ttu-id="7305b-412">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得错误的关联帐户的问题</span><span class="sxs-lookup"><span data-stu-id="7305b-412">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="7305b-413">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-413">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="7305b-414">修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-414">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="7305b-415">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-415">Word: Non-security updates</span></span>
- <span data-ttu-id="7305b-416">修复了 VBA 更新字段的速度缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-416">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="7305b-417">修复了打开某个 DOC 文件时系统表示该文件已损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-417">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="7305b-418">修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-418">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7305b-419">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-419">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="7305b-420">修复了在某些情况下设置 API 在 Office JavaScript 库中无法正常工作的问题[了解更多](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="7305b-420">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1902-july-09"></a><span data-ttu-id="7305b-421">版本 1902：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7305b-421">Version 1902: July 09</span></span>
<span data-ttu-id="7305b-422">*版本 1902（内部版本 11328.20368）*</span><span class="sxs-lookup"><span data-stu-id="7305b-422">*Version 1902 (Build 11328.20368)*</span></span>

<span data-ttu-id="7305b-423">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-423">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="excel-non-security-updates"></a><span data-ttu-id="7305b-424">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-424">Excel: Non-security updates</span></span>
- <span data-ttu-id="7305b-425">修复了删除已筛选的 excel 行时速度极慢的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-425">Fixed extreme slowness Issue in deleting filtered excel rows.</span></span>
- <span data-ttu-id="7305b-426">修复了双指滚动时会在工作表上留下灰色矩形印及 Excel 无响应的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-426">Fixed two finger scrolling causes grey rectangles to be drawn over worksheet and Excel to hang.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="7305b-427">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-427">Outlook: Non-security updates</span></span>
- <span data-ttu-id="7305b-428">解决了以下问题：用户偶尔看到 Outlook 插入英语拼音字母, 而不是将 IME 字符窗口保持打开状态以供选择中文字词。</span><span class="sxs-lookup"><span data-stu-id="7305b-428">Addresses an issue that caused users to occasionally see Outlook inserting English pinyin letters rather than keeping the IME candidate window open to allow the selection of Chinese words.</span></span>
- <span data-ttu-id="7305b-429">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="7305b-429">Addresses an issue that caused users to see rooms being suggested for meetings that were scheduled outside of that room's availability.</span></span>
- <span data-ttu-id="7305b-430">解决了导致用户尝试打开会议系列而不是打开主系列异常的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-430">Addresses an issue that caused users attempting to open an exception to a meeting series to instead open the master series.</span></span>
- <span data-ttu-id="7305b-431">解决了导致用户看到“已删除项”文件夹中的项的到期日期计算错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-431">Addresses an issue that caused users to see expiry dates being calculated incorrectly for items in Deleted Items folder.</span></span>


### <a name="teams-non-security-updates"></a><span data-ttu-id="7305b-432">Teams：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-432">Teams: Non-security updates</span></span>

- <span data-ttu-id="7305b-433">安装完成后，Teams 安装程序现在已有用于关闭自动启动的策略。</span><span class="sxs-lookup"><span data-stu-id="7305b-433">Teams installer has now available Policy to turn off auto-launch after installation is completed.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="7305b-434">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-434">Visio: Non-security updates</span></span>

- <span data-ttu-id="7305b-435">解决了 Visio 无法与 Office 365 搭配使时与 ActiveX 解决方案相关的问题，错误信息指示无法找到 riched20.dll。</span><span class="sxs-lookup"><span data-stu-id="7305b-435">Addresses issue related to ActiveX solutions for Visio not working with Office 365, expressed as an error message stating that riched20.dll can't be found.</span></span>


### <a name="word--non-security-updates"></a><span data-ttu-id="7305b-436">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-436">Word:  Non-security updates</span></span>

- <span data-ttu-id="7305b-437">修复了用于禁用模板搜索栏的 GPO 设置</span><span class="sxs-lookup"><span data-stu-id="7305b-437">Fixed GPO setting to disable template search bar</span></span>
- <span data-ttu-id="7305b-438">修复了以下问题：在脱机并编辑仅限服务器的文档之后，用户丢失了部分更改。</span><span class="sxs-lookup"><span data-stu-id="7305b-438">Fixed an issue where users could lose some of their changes after being offline and editing a document that was server-only.</span></span>
- <span data-ttu-id="7305b-439">改善了启用“文档属性”中“文档部件”时的性能</span><span class="sxs-lookup"><span data-stu-id="7305b-439">Improved performance when enabling Quick Parts for Document properties</span></span>
- <span data-ttu-id="7305b-440">修复了从服务器首次下载修订可能失败的问题</span><span class="sxs-lookup"><span data-stu-id="7305b-440">Fixed an issue where first download revision from the server might fail</span></span>


### <a name="office-suite--non-security-updates"></a><span data-ttu-id="7305b-441">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-441">Office Suite:  Non-security updates</span></span>

- <span data-ttu-id="7305b-442">解决了以下问题：在安装其他 Office 产品或语言包时，使用共享计算机激活的设备可能会意外恢复成基于用户的激活。</span><span class="sxs-lookup"><span data-stu-id="7305b-442">Addressed an issue where devices using shared computer activation may unexpectedly revert to user-based activation upon installation of additional Office products or language packs.</span></span>
- <span data-ttu-id="7305b-443">修复了代理身份验证作为 SYSTEM 运行时 Office 更新受阻的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-443">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>
- <span data-ttu-id="7305b-444">修复解决了 Office 加载项在用户配置文件更改时消失的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-444">Fixes to address Office add-ins disappearing on user profile changes.</span></span>


## <a name="version-1902-june-11"></a><span data-ttu-id="7305b-445">版本 1902：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7305b-445">Version 1902: June 11</span></span>
<span data-ttu-id="7305b-446">*版本 1902（内部版本 11328.20318）*</span><span class="sxs-lookup"><span data-stu-id="7305b-446">*Version 1902 (Build 11328.20318)*</span></span>
<br/><span data-ttu-id="7305b-447">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-447">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7305b-448">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-448">Excel: Non-security updates</span></span>
 - <span data-ttu-id="7305b-449">解决了将包含 XML 映射的文件保存为 PDF 时导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-449">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
 - <span data-ttu-id="7305b-450">解决了在加载包含无效工作表名称的工作簿时导致外部链接被删除的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-450">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
 - <span data-ttu-id="7305b-451">解决了在 Excel 中使用照相机工具会导致电子表格挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-451">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="7305b-452">解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-452">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
 - <span data-ttu-id="7305b-453">解决了在工作表计算期间使用另一张工作表上的数组公式（具体取决于表）重新计算数据表时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-453">Resolved a crash when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
 - <span data-ttu-id="7305b-454">解决了在未先签出文件的情况下阻止从 SharePoint 打开受密码保护的工作簿的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-454">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
 - <span data-ttu-id="7305b-455">已进行更改，以确保在共享或切换“自动保存”时处理 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="7305b-455">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7305b-456">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-456">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="7305b-457">解决了在向“分组依据”添加第 2 个条件时导致客户看到其任务似乎消失的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-457">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="7305b-458">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-458">Word: Non-security updates</span></span>
 - <span data-ttu-id="7305b-459">修复了在共享当前处于协作状态的文档时生成扩展名为 .asd 的附件的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-459">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="7305b-460">修复了将评论归因于随机作者的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-460">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="7305b-461">修复了在签出文档时删除签名的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-461">Fixed an issue in the remove signature when checking out a document.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7305b-462">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="7305b-462">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="7305b-463">修复了在执行“撤消”操作后 VBA 报告错误形状填充状态的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-463">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>


## <a name="version-1902-may-14"></a><span data-ttu-id="7305b-464">版本 1902：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7305b-464">Version 1902: May 14</span></span>
<span data-ttu-id="7305b-465">*版本 1902（内部版本 11328.20286）*</span><span class="sxs-lookup"><span data-stu-id="7305b-465">*Version 1902 (Build 11328.20286)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7305b-466">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-466">Excel: Non-security updates</span></span>
 -  <span data-ttu-id="7305b-467">解决了在 Excel 中使用照相机工具会导致电子表格挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-467">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="7305b-468">修复了在带有图表工作表的活动窗口中使用鼠标滚轮时导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-468">An issue that caused a crash when using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
 - <span data-ttu-id="7305b-469">解决了在 SharePoint 中导入电子表格时出现“意外错误”消息的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-469">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
 - <span data-ttu-id="7305b-470">解决了在打开包含使用其规则的名称和应用了自定义视图的条件格式的工作簿时导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-470">A problem that caused Excel to crash when opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
 - <span data-ttu-id="7305b-471">使用长度超过 255 个字符的公式进行数据验证的宏可能会产生运行时错误。</span><span class="sxs-lookup"><span data-stu-id="7305b-471">Macros using data validation with formulas longer than 255 characters may have produced run-time errors.</span></span> <span data-ttu-id="7305b-472">此问题现已得到更正。</span><span class="sxs-lookup"><span data-stu-id="7305b-472">This issue has now been corrected.</span></span>
 - <span data-ttu-id="7305b-473">导致包含链接到其他工作簿的数据透视表的文件加载缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-473">A problem which caused files containing PivotTables linked to other workbooks to load slowly.</span></span> <span data-ttu-id="7305b-474">此问题已解决。</span><span class="sxs-lookup"><span data-stu-id="7305b-474">This issue has been resolved.</span></span>
 - <span data-ttu-id="7305b-475">解决了打开 HTML 文件和接收“文件格式和扩展名不匹配”错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-475">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
 - <span data-ttu-id="7305b-476">已经进行了更改以解决在非活动窗口上滚动鼠标滚轮的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-476">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>  

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7305b-477">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-477">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="7305b-478">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-478">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="7305b-479">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-479">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="7305b-480">解决了 PowerPoint 停止上传用户更改到云端的问题（此情况极不常见）。</span><span class="sxs-lookup"><span data-stu-id="7305b-480">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7305b-481">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-481">Skype for Business: Non-security updates</span></span>
 - <span data-ttu-id="7305b-482">修复了以下问题：Lync (Skype for Business) 中对于任何有 7 个以上参与者的在线会议，会议窗口可能会消失。</span><span class="sxs-lookup"><span data-stu-id="7305b-482">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
 - <span data-ttu-id="7305b-483">使用登录其他 Office 应用程序时所用的凭据登录 Skype for Business。</span><span class="sxs-lookup"><span data-stu-id="7305b-483">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
 - <span data-ttu-id="7305b-484">在安装有共享计算机激活时正确激活 Skype for Business 应用。</span><span class="sxs-lookup"><span data-stu-id="7305b-484">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="7305b-485">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-485">Visio: Non-security updates</span></span>
 - <span data-ttu-id="7305b-486">解决了导致第三方解决方案通过禁用动态 DPI 功能来扩展 Visio 时出现窗口层次结构损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-486">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="7305b-487">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-487">Word: Non-Security updates</span></span>
 - <span data-ttu-id="7305b-488">解决了在编辑由 SharePoint 添加的相关人员时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-488">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="7305b-489">解决了在 Word 启动时出现“未能加载资源”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-489">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7305b-490">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="7305b-490">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="7305b-491">这是文件无法保存至 Apache WebDAV 文件夹问题的修复。</span><span class="sxs-lookup"><span data-stu-id="7305b-491">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="7305b-492">修复了在客户打开某些云存储文件时 Office 突然关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-492">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="7305b-493">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-493">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="7305b-494">解决了 Windows 10 上貌似已清除多位用户的“最近使用的文件”列表这一问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-494">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="7305b-495">解决了即使站在进行管理器触发的更新，最终用户仍会看到“Office 更新”业务栏的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-495">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="7305b-496">解决了与登录提示间歇性空白相关的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-496">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 

## <a name="version-1902-april-9"></a><span data-ttu-id="7305b-497">版本 1902：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7305b-497">Version 1902: April 9</span></span>
<span data-ttu-id="7305b-498">*版本 1902（内部版本 11328.20230）*</span><span class="sxs-lookup"><span data-stu-id="7305b-498">*Version 1902 (Build 11328.20230)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7305b-499">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-499">Excel: Non-Security updates</span></span>

- <span data-ttu-id="7305b-500">解决了在包含以定义名称结尾的公式的单元格中按 Tab 键不会移动到下一个单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-500">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="7305b-501">解决了单元格格式化导致文件大小不必要增长的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-501">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="7305b-502">解决了在工作簿之间剪切和粘贴数据透视表可能导致数据被粘贴的问题，不包含与你正在协作的其他人的数据透视表。</span><span class="sxs-lookup"><span data-stu-id="7305b-502">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7305b-503">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-503">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="7305b-504">修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-504">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="7305b-505">解决了导致客户在联系人卡片上加载图片时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-505">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="7305b-506">解决了导致某些客户在启动 Office 应用程序时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-506">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="7305b-507">修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-507">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="7305b-508">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-508">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="7305b-509">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-509">Visio: Non-Security updates</span></span>

- <span data-ttu-id="7305b-510">修复了以下问题：导致通过禁用动态 DPI 功能扩展 Visio 的第 3 方解决方案的窗口层次结构损坏问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-510">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling the Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="7305b-511">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-511">Word: Non-Security updates</span></span>

- <span data-ttu-id="7305b-512">如果文件以只读模式打开，并且你从“信息”窗格中单击“另存为”，则修复问题以便显示“保存 UI”。</span><span class="sxs-lookup"><span data-stu-id="7305b-512">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7305b-513">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="7305b-513">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="7305b-514">修复了以下问题：Office 更新的某些部分不使用传递优化对等缓存。</span><span class="sxs-lookup"><span data-stu-id="7305b-514">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="7305b-515">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="7305b-515">Learn more</span></span>](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="7305b-516">修复了如果使用 Office 部署工具安装 Office 且存在不匹配的情况时，可能导致产品被删除或未激活的 bug。</span><span class="sxs-lookup"><span data-stu-id="7305b-516">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="7305b-517">修复了导致 Windows 10（版本 1803 或更高版本）设备上出现过多登录提示的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-517">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="7305b-518">修复了下载链接图片时导致挂起的回归。</span><span class="sxs-lookup"><span data-stu-id="7305b-518">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="7305b-519">修复了粘贴在 Word、Excel、PowerPoint 中的大型 EMF 文件的模糊性。</span><span class="sxs-lookup"><span data-stu-id="7305b-519">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="7305b-520">修复了版本历史记录解析逻辑中的 bug，这些 bug 在少数情况下会导致文档以只读方式打开。</span><span class="sxs-lookup"><span data-stu-id="7305b-520">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="7305b-521">版本 1902：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7305b-521">Version 1902: March 12</span></span>
<span data-ttu-id="7305b-522">*版本 1902（内部版本 11328.20158）*</span><span class="sxs-lookup"><span data-stu-id="7305b-522">*Version 1902 (Build 11328.20158)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="7305b-523">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-523">Access: Feature updates</span></span>

- <span data-ttu-id="7305b-524">**刷新、重新链接或删除链接表** 更新的链接表管理器可用于管理所有数据源和链接表。</span><span class="sxs-lookup"><span data-stu-id="7305b-524">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables.</span></span> [<span data-ttu-id="7305b-525">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-525">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- <span data-ttu-id="7305b-p157">**将其涂成黑色，将其涂成灰色：** 根据需要随时更改 Access 的外观。四种主题可供选择：彩色、深灰色、黑色和白色。[了解详细信息](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="7305b-p157">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="7305b-529">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="7305b-529">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7305b-530">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-530">Excel: Feature updates</span></span>

- <span data-ttu-id="7305b-531">**更快开始**新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="7305b-531">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="7305b-532">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="7305b-532">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="7305b-533">**通过注释进行协作：** 使用内置回复框在电子表格中保持正常对话。</span><span class="sxs-lookup"><span data-stu-id="7305b-533">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box.</span></span> [<span data-ttu-id="7305b-534">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-534">Learn more</span></span>](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- <span data-ttu-id="7305b-535">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="7305b-535">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="7305b-536">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="7305b-536">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="7305b-537">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-537">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="7305b-p161">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="7305b-p161">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="7305b-p162">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="7305b-p162">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="7305b-543">**呼叫所有“获取和转换”功能的粉丝：** 如果你经常使用“获取和转换”功能，那么对于“从示例中添加列”功能已得到改进的消息一定兴奋不已。</span><span class="sxs-lookup"><span data-stu-id="7305b-543">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved.</span></span> <span data-ttu-id="7305b-544">另外，许多连接器也得到了改进。</span><span class="sxs-lookup"><span data-stu-id="7305b-544">And, many connectors have been improved as well.</span></span> [<span data-ttu-id="7305b-545">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-545">Learn more</span></span>](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- <span data-ttu-id="7305b-546">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="7305b-546">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="7305b-547">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-547">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="7305b-548">**快速查找** 已极大地提升了 VLOOKUP、HLOOKUP 和 MATCH 计算速度，以便能够更快地获取答案。</span><span class="sxs-lookup"><span data-stu-id="7305b-548">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster.</span></span> [<span data-ttu-id="7305b-549">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-549">Learn more</span></span>](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a><span data-ttu-id="7305b-550">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-550">Outlook: Feature updates</span></span>

- <span data-ttu-id="7305b-p166">**使用“大声朗读”来收听你的电子邮件：** Outlook 可以大声朗读你的电子邮件，并突出显示正在阅读的文本。要打开大声朗读功能，请转到“轻松访问”设置。[了解详细信息](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="7305b-p166">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="7305b-554">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="7305b-554">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="7305b-555">单击“听写”，即可看到 Outlook 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="7305b-555">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="7305b-556">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-556">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="7305b-557">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="7305b-557">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="7305b-558">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="7305b-558">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="7305b-559">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-559">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="7305b-560">**默认阻止下载 SMIME 加密和签名的电子邮件中的外部内容：** 鉴于 SMIME 协议中的漏洞，Outlook 将阻止下载由 SMIME 加密或签名的邮件上的外部内容。</span><span class="sxs-lookup"><span data-stu-id="7305b-560">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME.</span></span> <span data-ttu-id="7305b-561">用户将无法通过 Outlook UI 单击下载外部内容，以防止受到安全漏洞的危害。</span><span class="sxs-lookup"><span data-stu-id="7305b-561">Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability.</span></span> <span data-ttu-id="7305b-562">“选项”对话框提供了一个新选项，用户可使用它还原至旧行为。</span><span class="sxs-lookup"><span data-stu-id="7305b-562">There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="7305b-563">**禁用会议转发：** 阻止与会者将会议转发给其他人。</span><span class="sxs-lookup"><span data-stu-id="7305b-563">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others.</span></span> <span data-ttu-id="7305b-564">只需转到功能区，然后单击“响应选项”即可。</span><span class="sxs-lookup"><span data-stu-id="7305b-564">Just go to the ribbon and click Response Options.</span></span> [<span data-ttu-id="7305b-565">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-565">Learn more</span></span>](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- <span data-ttu-id="7305b-p171">**日程安排助理中的人员建议：** 安排会议时查看有关要添加的与会者的建议。无需在日程安排助理和收件人行之间来回切换。[了解详细信息](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="7305b-p171">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="7305b-569">**保留会议室变得更加容易：** 使用多个会议室列表查找会议室，切换列表时不会丢失所选的会议室。</span><span class="sxs-lookup"><span data-stu-id="7305b-569">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="7305b-p172">**重复周期范围的新默认值：** 对于“重复周期”对话框，在过去重复周期范围的默认值为“无结束日期”。这有助于创建长期运行的定期系列，随着时间的推移可能会损坏。我们将“重复周期”对话框的默认值更新为“结束日期”，以便我们的默认值与建议的日历最佳做法相匹配。</span><span class="sxs-lookup"><span data-stu-id="7305b-p172">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date". This facilitated the creation of long-running recurring series, which can become corrupted over time. We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="7305b-p173">**从“Outlook 提醒”对话框加入团队会议：** 当 Outlook 提醒用户参加即将召开的会议时，如果即将召开的会议是团队在线会议，则它将显示一个“联机加入”按钮。这与从“Outlook 提醒”对话框加入 Skype for Business 会议的体验类似。</span><span class="sxs-lookup"><span data-stu-id="7305b-p173">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="7305b-575">**停止查看过去活动的提醒：** 可以将日历设置为在活动结束后自动关闭活动提醒。</span><span class="sxs-lookup"><span data-stu-id="7305b-575">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended.</span></span> [<span data-ttu-id="7305b-576">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-576">Learn more</span></span>](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- <span data-ttu-id="7305b-577">**查看安全链接背后的 URL：** 安全链接有助于保护你免受电子邮件中收到的恶意 URL 的攻击，但它们会隐藏原始 URL。</span><span class="sxs-lookup"><span data-stu-id="7305b-577">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="7305b-578">若要查看原始 URL，请将鼠标悬停在 URL上。</span><span class="sxs-lookup"><span data-stu-id="7305b-578">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="7305b-579">需要高级威胁防护许可证。</span><span class="sxs-lookup"><span data-stu-id="7305b-579">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="7305b-580">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-580">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="7305b-581">**缩放和粘贴：** 选择默认设置用于所有邮件，而无需在每次阅读邮件时调整缩放。</span><span class="sxs-lookup"><span data-stu-id="7305b-581">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.</span></span> [<span data-ttu-id="7305b-582">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-582">Learn more</span></span>](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- <span data-ttu-id="7305b-583">**邮件加密：仅加密 IRM 策略：** 新的仅加密选项显示在 Office 365 邮件加密用户的“选项”>“权限”菜单中。</span><span class="sxs-lookup"><span data-stu-id="7305b-583">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="7305b-584">此选项允许你加密邮件并将其发送给组织内部或外部的任何人。</span><span class="sxs-lookup"><span data-stu-id="7305b-584">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="7305b-585">**密件抄送 (BCC) 警告：** BCC 信息提示会在你意外对被密件抄送的邮件全部答复之前发出警告。</span><span class="sxs-lookup"><span data-stu-id="7305b-585">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="7305b-586">**更智能的“收件人:”行：** 在单击“收件人:”行处理邮件时，会提示用户可能要选择的收件人。</span><span class="sxs-lookup"><span data-stu-id="7305b-586">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="7305b-587">此外，还可以看到收件人的照片，这样用户便知道将要向其发送邮件的收件人正确无误。</span><span class="sxs-lookup"><span data-stu-id="7305b-587">Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> [<span data-ttu-id="7305b-588">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-588">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="7305b-p179">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="7305b-p179">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="7305b-591">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="7305b-591">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="7305b-592">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-592">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7305b-593">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-593">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7305b-594">**更快开始**新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="7305b-594">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="7305b-595">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="7305b-595">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="7305b-596">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="7305b-596">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="7305b-597">单击“听写”，即可看到 PowerPoint 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="7305b-597">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="7305b-598">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-598">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="7305b-599">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="7305b-599">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="7305b-600">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="7305b-600">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="7305b-601">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-601">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="7305b-602">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="7305b-602">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="7305b-603">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-603">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="7305b-604">**使用其他生动颜色显示超链接：** 超链接不再只是蓝色的。</span><span class="sxs-lookup"><span data-stu-id="7305b-604">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="7305b-605">可以根据需要应用任何字体颜色。</span><span class="sxs-lookup"><span data-stu-id="7305b-605">Apply any font color you like.</span></span> [<span data-ttu-id="7305b-606">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-606">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="7305b-607">**查看栩栩如生的幻灯片：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个屏幕中横冲直撞的霸王龙。</span><span class="sxs-lookup"><span data-stu-id="7305b-607">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.</span></span> [<span data-ttu-id="7305b-608">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-608">Learn more</span></span>](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- <span data-ttu-id="7305b-p187">**用户绘制草图，我们来润色：** 我们将手绘文本和形状变为精致的图表。只需选择笔划墨迹即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="7305b-p187">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="7305b-p188">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="7305b-p188">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="7305b-615">**发布到 Microsoft Stream：** 通过使用 Microsoft Stream 在组织中更为安全地将演示文稿作为视频进行共享。 </span><span class="sxs-lookup"><span data-stu-id="7305b-615">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="7305b-616">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-616">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="7305b-617">**导出为 4K 视频：** 将演示文稿导出为视频时，现在可以选择 4K 分辨率。</span><span class="sxs-lookup"><span data-stu-id="7305b-617">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="7305b-618">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-618">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="7305b-p191">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="7305b-p191">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="7305b-621">**大文件现在可以更快地打开：** 打开存储在 OneDrive 或 SharePoint 中的文件时，图像、视频和其他大文件现在可以在后台下载。</span><span class="sxs-lookup"><span data-stu-id="7305b-621">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7305b-622">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-622">Word: Feature updates</span></span>

- <span data-ttu-id="7305b-623">**更快开始**新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="7305b-623">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="7305b-624">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="7305b-624">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="7305b-625">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="7305b-625">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="7305b-626">单击“听写”，即可看到 Word 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="7305b-626">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="7305b-627">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-627">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="7305b-p194">**查看栩栩如生的文档：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个页面中横冲直撞的霸王龙。[了解详细信息](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="7305b-p194">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="7305b-630">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="7305b-630">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="7305b-631">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="7305b-631">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="7305b-632">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-632">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="7305b-p196">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="7305b-p196">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="7305b-p197">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="7305b-p197">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="7305b-638">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="7305b-638">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="7305b-639">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-639">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="7305b-p199">**在 LinkedIn 的帮助下编写你的出色简历：** 通过简历助手查看工作经验、建议技能及给定角色的详细信息。 [了解详细信息](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="7305b-p199">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="7305b-642">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-642">Project: Feature updates</span></span>

- <span data-ttu-id="7305b-643">**在任务板卡片上了解更多信息：** 如果单独的标题无法描述详情，可以自定义任务板卡片以显示所有最重要的详细信息。</span><span class="sxs-lookup"><span data-stu-id="7305b-643">**See more info on Task Board cards:** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details.</span></span> [<span data-ttu-id="7305b-644">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-644">Learn more</span></span>](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- <span data-ttu-id="7305b-645">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="7305b-645">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="7305b-646">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-646">Publisher: Feature updates</span></span>

- <span data-ttu-id="7305b-647">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="7305b-647">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7305b-648">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-648">Visio: Feature updates</span></span>

- <span data-ttu-id="7305b-649">**在下一个图表中享受全新图标时刻：** 从 26 个新的模具中挑选，其中包含用于分析、艺术、庆祝、人脸、运动等的图标。</span><span class="sxs-lookup"><span data-stu-id="7305b-649">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="7305b-650">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="7305b-650">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="7305b-651">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-651">Office Suite: Feature updates</span></span>

- <span data-ttu-id="7305b-p201">**Office 第三方应用程序现已支持通过 office.js API 插入 SVG：** 第三方应用程序也称为 Office 中的加载项，它们现可插入 SVG。用户现可将其个人的 SVG 集合连接到 Office。而开发人员可通过 Office.js API 使用该项功能。</span><span class="sxs-lookup"><span data-stu-id="7305b-p201">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="7305b-655">**Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="7305b-655">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="7305b-656">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-656">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="7305b-657">Skype for Business：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-657">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="7305b-658">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="7305b-658">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="7305b-659">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-659">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a><span data-ttu-id="7305b-660">Teams：功能更新</span><span class="sxs-lookup"><span data-stu-id="7305b-660">Teams: Feature updates</span></span>

- <span data-ttu-id="7305b-661">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="7305b-661">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="7305b-662">了解更多</span><span class="sxs-lookup"><span data-stu-id="7305b-662">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a><span data-ttu-id="7305b-663">版本 1808：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7305b-663">Version 1808: February 12</span></span>
<span data-ttu-id="7305b-664">版本 1808（内部版本 10730.20280）\*\*</span><span class="sxs-lookup"><span data-stu-id="7305b-664">*Version 1808 (Build 10730.20280)*</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="7305b-665">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-665">Access: Non-Security updates</span></span> 

- <span data-ttu-id="7305b-666">此更新将对新日本和历的支持添加到 Access。</span><span class="sxs-lookup"><span data-stu-id="7305b-666">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7305b-667">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-667">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="7305b-668">解决以下问题：具有引用不再存在的文件夹规则的用户在尝试管理规则时看到错误，以及看到客户端规则运行失败。</span><span class="sxs-lookup"><span data-stu-id="7305b-668">Addresses an issue that caused users with rules that refer to a folder that no longer exist to see an error when trying to manage rules and to see client-side rules fail to run.</span></span>
- <span data-ttu-id="7305b-669">处理以下问题：具有缓存委托邮箱的用户在不可预测的时间间隔遇到频繁挂起。</span><span class="sxs-lookup"><span data-stu-id="7305b-669">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="7305b-670">处理以下问题：由于会议结束时间设置为第二天的午夜，在一些视图中，全天会议似乎超过预期的一天时间。</span><span class="sxs-lookup"><span data-stu-id="7305b-670">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="7305b-671">修复了创建引用日本和历的新约会或会议时的挂起。</span><span class="sxs-lookup"><span data-stu-id="7305b-671">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7305b-672">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="7305b-672">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="7305b-673">修复以下问题：使用 [O365 Office 集中式部署](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment)部署的外接程序被冻结且不可用。</span><span class="sxs-lookup"><span data-stu-id="7305b-673">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="7305b-674">版本 1808：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7305b-674">Version 1808: January 8</span></span>
<span data-ttu-id="7305b-675">*版本 1808（内部版本 10730.20264）*</span><span class="sxs-lookup"><span data-stu-id="7305b-675">*Version 1808 (Build 10730.20264)*</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7305b-676">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-676">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="7305b-677">修复了导致用户遇到日历同步错误的问题。</span><span class="sxs-lookup"><span data-stu-id="7305b-677">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="7305b-678">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="7305b-678">Word: Non-security updates</span></span>

- <span data-ttu-id="7305b-679">提高打开性能。</span><span class="sxs-lookup"><span data-stu-id="7305b-679">Improve open performance.</span></span>


> [!NOTE]
> <span data-ttu-id="7305b-680">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="7305b-680">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
