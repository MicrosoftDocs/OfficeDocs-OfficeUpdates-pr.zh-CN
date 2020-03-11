---
title: Office 预览体验成员发行说明
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为“预览体验成员 - 快”受众提供关键新功能、修复程序或已知问题的最新列表
ms.openlocfilehash: 98f2ec2386cc214cbe5912d428b781610d953aca
ms.sourcegitcommit: 4be8cb98eca74452720348595f0b8cfeaba4cef8
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/09/2020
ms.locfileid: "42568858"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="2ac07-103">Office 预览体验成员发行说明</span><span class="sxs-lookup"><span data-stu-id="2ac07-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="2ac07-104">本文包含 Windows 桌面版的 Word、Excel、PowerPoint、Outlook、Access 和 Project 的预览体验计划内部版本的发行说明。</span><span class="sxs-lookup"><span data-stu-id="2ac07-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="2ac07-105">每周，我们都会提供精彩集锦，其中包含我们希望你了解的有趣新功能、重要修补程序和所有重要问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="2ac07-106">注意，我们通常会在一段时间内向预览体验成员推出功能（有时甚至包括修补程序）。</span><span class="sxs-lookup"><span data-stu-id="2ac07-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="2ac07-107">这可以让我们确保将功能向更多的受众发布之前，所用功能均可正常使用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="2ac07-108">因此，如果你没有看到下面所述的功能，请不要担心，你最终会获取这些功能。</span><span class="sxs-lookup"><span data-stu-id="2ac07-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="2ac07-109">发行说明每周发布一次，可能是多个版本的编译。</span><span class="sxs-lookup"><span data-stu-id="2ac07-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="2ac07-110">发行说明发布日期可能与实际内部版本发布日期不一致。</span><span class="sxs-lookup"><span data-stu-id="2ac07-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="2ac07-111">Office 365 专业增强版现有安装的 Microsoft Teams - 从6月底开始, 将在更新这些安装的 Office 365 专业增强版 (和 Office 365 Business) 现有安装中包含 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="2ac07-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="2ac07-112">将添加 Teams 的日期取决于所使用的更新频道。</span><span class="sxs-lookup"><span data-stu-id="2ac07-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="2ac07-113">有关详细信息, 请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="2ac07-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (请勿移除)

## <a name="version-2003-march-06"></a><span data-ttu-id="2ac07-115">版本 2003：3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-115">Version 2003: March 06</span></span>
<span data-ttu-id="2ac07-116">*版本2003（内部版本 12624.20086）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-116">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-118">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-118">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-119">Outlook</span></span>

- <span data-ttu-id="2ac07-120">修复了通过 Outlook Web Access 创建规则不会保留到 Exchange 服务器且会导致冲突的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-120">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="2ac07-121">修复了深色模式下 Outlook 不会在“发件人:”字段中显示下拉列表的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-121">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="2ac07-122">解决了导致用户无法通过文件资源管理器将已在其他应用程序中打开的文件附加到其邮件中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-122">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-123">PowerPoint</span></span>

- <span data-ttu-id="2ac07-124">修复了将鼠标悬停在推荐的缩略图上时缩略图闪烁的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-124">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="2ac07-125">在某些情况下，这可能会导致 PowerPoint 崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-125">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-126">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-126">Word</span></span>

- <span data-ttu-id="2ac07-127">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-127">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-128">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-128">Office Suite</span></span>

- <span data-ttu-id="2ac07-129">修复了 Word/Excel/PowerPoint 中的用户主体名称 (UPN) 不再区分大小写的问题，从而减少了处理 SharePoint 上的文件时出现的故障。</span><span class="sxs-lookup"><span data-stu-id="2ac07-129">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="2ac07-130">修复了“文件\选项”对话框上的“确定”按钮显示为灰色但功能不受影响的外观问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-130">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

[//]: # (请勿移除功能详细信息内容开头)

## <a name="version-2003-february-28"></a><span data-ttu-id="2ac07-133">版本 2003：2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-133">Version 2003: February 28</span></span>
<span data-ttu-id="2ac07-134">*版本 2003（内部版本 12619.20002）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-134">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-136">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-136">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-137">Outlook</span></span>

- <span data-ttu-id="2ac07-138">**IT 管理员事件通知：** 使用 Outlook for Windows 中的新右侧面板通知，Microsoft 365 租户全局管理员和 Office 应用程序管理员将收到有关影响用户的 Outlook 和 O365 通知。</span><span class="sxs-lookup"><span data-stu-id="2ac07-138">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-139">PowerPoint</span></span>

- <span data-ttu-id="2ac07-140">**改进了将墨迹转换为图形制表的体验：** 绘制更好的图表，并将其转换为可以操作的 office 对象 [了解详细信息](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="2ac07-140">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-143">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-143">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-144">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-144">Excel</span></span>

- <span data-ttu-id="2ac07-145">修复了切片器中的文本在打印预览中无法缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-145">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-146">Outlook</span></span>

- <span data-ttu-id="2ac07-147">解决了将附件添加到邮件或通过拖放操作（而不是通过菜单）从邮件保存附件时，将更新文件的“上次修改时间”的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-147">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-148">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-148">Word</span></span>

- <span data-ttu-id="2ac07-149">解决了通过批注卡使用 Tab 键时，批注编辑框焦点无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-149">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="2ac07-150">如果在公式中插入控件（例如文本内容控件），然后保存再打开文件，会导致“内容不可读”错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-150">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="2ac07-151">解决了无法保存之前受密码保护文件至云存储的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-151">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-152">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-152">Office Suite</span></span>

- <span data-ttu-id="2ac07-153">修复了从同一 SharePoint 库在 Word/Excel/PowerPoint 中打开多个文件时，只能打开第一个文件进行策略符合性扫描的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-153">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-february-21"></a><span data-ttu-id="2ac07-155">版本 2003：2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-155">Version 2003: February 21</span></span>
<span data-ttu-id="2ac07-156">*版本 2003（内部版本 12615.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-156">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-158">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-158">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="2ac07-159">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-159">Office Suite</span></span>

- <span data-ttu-id="2ac07-160">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="2ac07-160">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-163">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-163">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-164">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-164">Excel</span></span>
- <span data-ttu-id="2ac07-165">修复了用户在重命名数据透视表度量时可能遇到的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-165">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="2ac07-166">修复了用户在使用 VBA 宏清除某区域中的内容时可能遇到的性能问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-166">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="2ac07-167">修复了用户执行与功能区交互的宏时会导致 UI 闪烁的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-167">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="2ac07-168">修复了 CSV 文件中的第一个单词为 TABLE 时无法正确加载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-168">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="2ac07-169">修复了用户在切换具有不同缩放级别的两个工作簿时可能遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-169">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-170">Outlook</span></span>
- <span data-ttu-id="2ac07-171">解决了 Outlook 在夜间运行时导致用户无法打开公用文件夹邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-171">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="2ac07-172">修复了在添加 Gmail 帐户的身份验证工作流程期间位于权限页面上的“允许”和“拒绝”按钮被禁用的竞态条件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-172">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="2ac07-173">解决了导致 Outlook 在某些情况下意外生成日志输出（即使已关闭日志记录）的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-173">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-174">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-174">Word</span></span>
- <span data-ttu-id="2ac07-175">修复了当鼠标指针悬停在批注卡上方时不会始终突出显示批注卡的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-175">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="2ac07-176">在活动文档共同创作会话期间，直接向批注卡添加图像可能会导致添加标记。</span><span class="sxs-lookup"><span data-stu-id="2ac07-176">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="2ac07-177">此问题已修复。</span><span class="sxs-lookup"><span data-stu-id="2ac07-177">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-178">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-178">Office Suite</span></span>
- <span data-ttu-id="2ac07-179">将 Multichoice/Lookup/Managed-metadata 属性用于 Word/Excel/PowerPoint 文档并保存到 SharePoint 文档库时，这些属性在以前会限制为 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="2ac07-179">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="2ac07-180">如果这些属性超过 255 个字符，则无法保存此类文档。</span><span class="sxs-lookup"><span data-stu-id="2ac07-180">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="2ac07-181">通过此次更改后，此限制已增加到 2048 个字符。</span><span class="sxs-lookup"><span data-stu-id="2ac07-181">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-february-14"></a><span data-ttu-id="2ac07-183">版本 2003：2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-183">Version 2003: February 14</span></span>
<span data-ttu-id="2ac07-184">*版本 2003（内部版本 12607.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-184">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-186">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-186">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-187">Outlook</span></span>

- <span data-ttu-id="2ac07-188">**强制 wifi 网络新体验：** 是否已加入需要使用网页登录的 wifi 网络？</span><span class="sxs-lookup"><span data-stu-id="2ac07-188">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="2ac07-189">现在，Outlook 检测到这一点，帮助你进行连接。</span><span class="sxs-lookup"><span data-stu-id="2ac07-189">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-190">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-190">Word</span></span>

- <span data-ttu-id="2ac07-191">**在绘图工具箱中查找墨迹编辑器：** 选择“绘图”，然后选择“墨迹编辑器”笔使用手指或数字笔编辑文档。</span><span class="sxs-lookup"><span data-stu-id="2ac07-191">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="2ac07-192">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-192">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="2ac07-193">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-193">Office Suite</span></span>

- <span data-ttu-id="2ac07-194">**更清晰的状态栏图标：** 状态栏图标现在更容易看到</span><span class="sxs-lookup"><span data-stu-id="2ac07-194">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-197">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-197">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-198">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-198">Outlook</span></span>

- <span data-ttu-id="2ac07-199">解决了导致用户无法访问“ 闲/忙选项”日历权限对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-199">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="2ac07-200">修复了以下问题：打开从不同时区发送的定期会议实例时出现警告“很抱歉，无法打开此项目”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-200">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="2ac07-201">解决了可能导致用户在从邮件中拖拽附件后无法重新打开 .msg 文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-201">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="2ac07-202">修复了将文件附件从 Outlook 上传到 OneDrive 后出现的问题，如果附件名称包含圆括号，则会导致文件名被更改。</span><span class="sxs-lookup"><span data-stu-id="2ac07-202">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-203">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-203">PowerPoint</span></span>

- <span data-ttu-id="2ac07-204">修复了可能导致无法保存文档至含 Excel 图表的 PowerPoint 或 Word 的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-204">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-205">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-205">Word</span></span>

- <span data-ttu-id="2ac07-206">修复了导出至 PDF 时文档中的图片失去透明度的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-206">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-february-07"></a><span data-ttu-id="2ac07-208">版本 2002：2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-208">Version 2002: February 07</span></span>
<span data-ttu-id="2ac07-209">*版本 2002（内部版本 12527.20040）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-209">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-211">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-211">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2ac07-212">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-212">Access</span></span>

- <span data-ttu-id="2ac07-213">**在“查询设计器”、“SQL 视图”和“关系”窗口中更高效地工作：** 右键单击表格，以对其进行打开、设计、调整大小和隐藏操作。</span><span class="sxs-lookup"><span data-stu-id="2ac07-213">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="2ac07-214">在 SQL 视图中搜索和替换文本。</span><span class="sxs-lookup"><span data-stu-id="2ac07-214">Search and replace text in SQL View.</span></span> <span data-ttu-id="2ac07-215">在“关系”窗口中选择多个表。</span><span class="sxs-lookup"><span data-stu-id="2ac07-215">Select multiple tables in the Relationships window.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-218">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-218">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ac07-219">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-219">Access</span></span>

- <span data-ttu-id="2ac07-220">此更新修复了使用 ADODB 的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-220">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2ac07-221">VB 代码中的记录器对象可能会错误地报告错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-221">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2ac07-222">此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。</span><span class="sxs-lookup"><span data-stu-id="2ac07-222">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-223">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-223">Excel</span></span>

- <span data-ttu-id="2ac07-224">解决了将文本分列用于动态数组时 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-224">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-225">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-225">Outlook</span></span>

- <span data-ttu-id="2ac07-226">解决了在采用月视图的日历中进行滚动时无法显示以前的日历事件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-226">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="2ac07-227">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到系统崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-227">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-228">PowerPoint</span></span>

- <span data-ttu-id="2ac07-229">修复了以下问题：关闭文件后，如果有任何事件处理程序正在运行，PowerPoint 不会立即从演示文稿集合中删除该文件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-229">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="2ac07-230">因此，由对象模型报告的打开的演示文稿数目不正确，并且系统会阻止关闭 PowerPoint。</span><span class="sxs-lookup"><span data-stu-id="2ac07-230">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="2ac07-231">修复了荧光笔问题：带有黑色荧光笔颜色的白色文本在打印后显示为灰度中的黑色。</span><span class="sxs-lookup"><span data-stu-id="2ac07-231">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-232">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-232">Word</span></span>

- <span data-ttu-id="2ac07-233">更新和滚动浏览目录时，有时可能会在文档上显示灰色区域。</span><span class="sxs-lookup"><span data-stu-id="2ac07-233">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="2ac07-234">修复了共同创作文档时可能不会保留根批注的草稿版本的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-234">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="2ac07-235">修复了在批注卡之间来回切换时有时会显示最初所选批注并突出显示所选内容的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-235">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="2ac07-236">修复了以下问题：如果编写了批注但未发布内容且用户尝试了保存文件，则使用“浏览”保存文件将不起作用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-236">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="2ac07-237">在启用 SlideTrack 并关闭批注窗格后，按 Ctrl+Alt+M 可能无法打开批注窗格。</span><span class="sxs-lookup"><span data-stu-id="2ac07-237">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="2ac07-238">修复了在表中添加 @提及时可能会生成错误消息“此文档中的某个表格已损坏”的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-238">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-239">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-239">Office Suite</span></span>

- <span data-ttu-id="2ac07-240">解决了可能是导致无法正确安装挪威尼诺斯克语 (nn-no) 校对工具程序包的原因的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-240">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-january-31"></a><span data-ttu-id="2ac07-242">版本 2002：1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-242">Version 2002: January 31</span></span>
<span data-ttu-id="2ac07-243">*版本 2002（内部版本 12513.20010）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-243">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-245">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-245">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-246">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-246">Excel</span></span>

- <span data-ttu-id="2ac07-247">**随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。</span><span class="sxs-lookup"><span data-stu-id="2ac07-247">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2ac07-248">**查询编辑器中的数据分析：** 快速分析列中的数据、确定错误和空值、查看分发直方图等。</span><span class="sxs-lookup"><span data-stu-id="2ac07-248">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-251">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-251">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-252">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-252">Outlook</span></span>

- <span data-ttu-id="2ac07-253">修复了以下问题：电子邮件根据保留策略过期时将显示两个标签。</span><span class="sxs-lookup"><span data-stu-id="2ac07-253">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="2ac07-254">一个标签显示邮件将在一天后过期，另一个标签显示将在两天后过期。</span><span class="sxs-lookup"><span data-stu-id="2ac07-254">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-255">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-255">Word</span></span>

- <span data-ttu-id="2ac07-256">修复了在阅读模式中使用&quot;反转&quot;页面颜色看不到批注提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-256">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="2ac07-257">修复了在编辑批注、将文本设置为斜体并随后将其发布之后斜体格式丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-257">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="2ac07-258">修复了批注上下文菜单中的批注命令（“编辑批注”、“批注答复”、“删除批注”、“解决批注”）不显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-258">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-january-17"></a><span data-ttu-id="2ac07-260">版本 2002：1 月 17 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-260">Version 2002: January 17</span></span>
<span data-ttu-id="2ac07-261">*版本 2002（内部版本 12508.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-261">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-263">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-263">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="2ac07-264">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-264">Word</span></span>

- <span data-ttu-id="2ac07-265">**提及 和评论通知电子邮件现在包含预览：** 提及的电子邮件通知评论将立即包含评论文本和所引用上下文的预览。</span><span class="sxs-lookup"><span data-stu-id="2ac07-265">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-268">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-268">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-269">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-269">Excel</span></span>

- <span data-ttu-id="2ac07-270">在某些情况中，辅助功能检查器不会显示形状建议。</span><span class="sxs-lookup"><span data-stu-id="2ac07-270">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-271">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-271">Outlook</span></span>

- <span data-ttu-id="2ac07-272">保存在左侧导航窗格“收藏夹”中的文件夹可能间歇消失。</span><span class="sxs-lookup"><span data-stu-id="2ac07-272">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-273">PowerPoint</span></span>

- <span data-ttu-id="2ac07-274">修复了在 PowerPoint 墨迹动画中使用时，墨迹可能无法完全呈现或跳过的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-274">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-january-10"></a><span data-ttu-id="2ac07-276">版本 2001：1 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-276">Version 2001: January 10</span></span>
<span data-ttu-id="2ac07-277">*版本 2001（内部版本 12430.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-277">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-279">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-279">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-280">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-280">Excel</span></span>
- <span data-ttu-id="2ac07-281">**将形状另存为图片：** 只需单击几下即可将形状、图标或其他对象另存为图片文件，以便您将其用于其他任何位置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-281">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="2ac07-282">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-282">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="2ac07-283">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-283">Outlook</span></span>
- <span data-ttu-id="2ac07-284">**在 Windows 中，用户现在可以将 Word/Excel/Outlook 中的对象另存为图片：** 通过 PowerPoint 中已有的功能，用户现在可以将 Word、Excel 和 Outlook 中的对象另存为图片。</span><span class="sxs-lookup"><span data-stu-id="2ac07-284">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="2ac07-285">对象包括形状、图标、图片等！</span><span class="sxs-lookup"><span data-stu-id="2ac07-285">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="2ac07-286">可以通过右键单击菜单访问它。</span><span class="sxs-lookup"><span data-stu-id="2ac07-286">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-287">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-287">Word</span></span>
- <span data-ttu-id="2ac07-288">**通过在对象周围绘制形状轻松选择 Word 中的墨迹：**“绘图”选项卡上的套索工具可以帮助你选择使用墨迹绘制的对象。</span><span class="sxs-lookup"><span data-stu-id="2ac07-288">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="2ac07-289">选择单独的笔划或整个字。</span><span class="sxs-lookup"><span data-stu-id="2ac07-289">Select individual strokes, or whole words.</span></span> <span data-ttu-id="2ac07-290">当你拥有大量墨迹并且只想使用其中的一部分时，这就非常方便。</span><span class="sxs-lookup"><span data-stu-id="2ac07-290">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="2ac07-291">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-291">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="2ac07-292">**将形状另存为图片：** 只需单击几下即可将形状、图标或其他对象另存为图片文件，以便您将其用于其他任何位置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-292">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="2ac07-293">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-293">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-296">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-296">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="2ac07-297">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ac07-297">OneNote</span></span>
- <span data-ttu-id="2ac07-298">页面选项卡可能显示太小，并且以 100% 分辨率紧密排列在一起。</span><span class="sxs-lookup"><span data-stu-id="2ac07-298">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-299">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-299">Word</span></span>
- <span data-ttu-id="2ac07-300">在大量备注中，删除靠近备注列表末尾的备注可能会导致窗格一直滚动至顶部。</span><span class="sxs-lookup"><span data-stu-id="2ac07-300">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-january-03"></a><span data-ttu-id="2ac07-302">版本 2001：1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-302">Version 2001: January 03</span></span>
<span data-ttu-id="2ac07-303">*版本 2001（内部版本 12425.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-303">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-305">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-305">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-306">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-306">Excel</span></span>
- <span data-ttu-id="2ac07-307">某些边框线可能无法在 A4 大小的纸张上按预期打印。</span><span class="sxs-lookup"><span data-stu-id="2ac07-307">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="2ac07-308">如果使用 VBA 向工作表上图表对象的页眉/页脚添加图像，则可能导致错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-308">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="2ac07-309">设置图表坐标轴的格式时，标签之前的间隔限制为 255。</span><span class="sxs-lookup"><span data-stu-id="2ac07-309">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="2ac07-310">解决了尝试刷新 XML 查询时出错（其中数据源的 URL 遭到截断）的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-310">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="2ac07-311">工作簿统计信息会报告所有打开的工作簿（包括个人宏工作簿）中的宏计数。</span><span class="sxs-lookup"><span data-stu-id="2ac07-311">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-312">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-312">Outlook</span></span>
- <span data-ttu-id="2ac07-313">切换文件夹可能导致邮件列表/邮件预览中“闪现”短暂的空白。</span><span class="sxs-lookup"><span data-stu-id="2ac07-313">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="2ac07-314">此行为在深色模式下更明显。</span><span class="sxs-lookup"><span data-stu-id="2ac07-314">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-315">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-315">PowerPoint</span></span>
- <span data-ttu-id="2ac07-316">解决了调用 Shape.Paste 方法会导致粘贴的形状被置于焦点之下的问题。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="2ac07-316">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="2ac07-317">改进了复制粘贴方案：&nbsp;以编程方式复制 PowerPoint 幻灯片中的形状并将其粘贴到循环中的其他幻灯片会失败并出现异常错误。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="2ac07-317">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="2ac07-318">在折叠和展开节标题后，幻灯片的节标题中的动画无法正常呈现。</span><span class="sxs-lookup"><span data-stu-id="2ac07-318">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-319">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-319">Project</span></span>
- <span data-ttu-id="2ac07-320">解决了文本环绕在文本和资源使用情况视图中不起作用的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-320">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="2ac07-321">解决了如果某资源有多个成本费率，则分配上的成本值可能不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-321">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-322">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-322">Word</span></span>
- <span data-ttu-id="2ac07-323">如果在公式中插入控件（例如文本内容控件），然后保存再打开文件，则会导致“内容不可读”错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-323">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="2ac07-324">共同创作时，Word 桌面版中可能不会显示使用 Word Online 添加批注的功能。</span><span class="sxs-lookup"><span data-stu-id="2ac07-324">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-325">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-325">Office Suite</span></span>
- <span data-ttu-id="2ac07-326">尝试在只有一个许可证的情况下更改许可证时，不再显示对有效许可证而言错误的过期日期。</span><span class="sxs-lookup"><span data-stu-id="2ac07-326">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-december-13"></a><span data-ttu-id="2ac07-328">版本 2001：12 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-328">Version 2001: December 13</span></span>
<span data-ttu-id="2ac07-329">*版本 2001（内部版本 12410.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-329">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-331">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-331">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-332">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-332">Outlook</span></span>

- <span data-ttu-id="2ac07-333">**将电子邮件拖动到你拥有的组：** 通过从收件箱中拖动来移动和复制邮件和对话。</span><span class="sxs-lookup"><span data-stu-id="2ac07-333">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="2ac07-334">将与所有组成员共享你拖动的消息。</span><span class="sxs-lookup"><span data-stu-id="2ac07-334">Messages you drag will be shared with all group members.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-337">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ac07-338">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-338">Access</span></span>
- <span data-ttu-id="2ac07-339">执行引用链接 ODBC 表并包含 Order By 子句的联合查询会导致 64 位 Access 崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-339">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="2ac07-340">在 Access (O365) 中对联合查询的数据进行汇总可能导致十进制数据被截断。</span><span class="sxs-lookup"><span data-stu-id="2ac07-340">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="2ac07-341">ACE 的 COM 接口未公开在 Office 应用程序外部使用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-341">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-342">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-342">Excel</span></span>
- <span data-ttu-id="2ac07-343">插入 3D 模型（动画或静态）并尝试“另存为图片”不起作用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-343">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="2ac07-344">从 Backstage 启动反馈的快捷键 (Alt+Ctrl + 7/8) 与 AZERTY 键盘 (Alt-Gr + 7/8) 发生冲突。</span><span class="sxs-lookup"><span data-stu-id="2ac07-344">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="2ac07-345">影响：用户可能无法使用某些字符，例如：'\'。</span><span class="sxs-lookup"><span data-stu-id="2ac07-345">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-346">Outlook</span></span>
- <span data-ttu-id="2ac07-347">解决了导致将电子邮件发送到收件人错误地址的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-347">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="2ac07-348">解决了导致 Outlook 错误地允许具有邮箱&quot;读取&quot;权限的用户更改邮件已读/未读状态的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-348">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="2ac07-349">产品支持人员无法再现网站上的安全证书吊销。</span><span class="sxs-lookup"><span data-stu-id="2ac07-349">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="2ac07-350">需要添加日志来帮助找出问题的根本原因。</span><span class="sxs-lookup"><span data-stu-id="2ac07-350">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="2ac07-351">解决了导致用户看到同步失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-351">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-352">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-352">PowerPoint</span></span>
- <span data-ttu-id="2ac07-353">插入 3D 模型（动画或静态）并尝试“另存为图片”不起作用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-353">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-354">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-354">Project</span></span>
- <span data-ttu-id="2ac07-355">对于手动计划的子任务，无法在摘要汇总中计算任务工时。</span><span class="sxs-lookup"><span data-stu-id="2ac07-355">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="2ac07-356">尝试保存基于服务器的项目时，从功能区按钮调用的 Project VBA 代码可能不起作用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-356">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="2ac07-357">除非 Project 已在运行，否则从 SharePoint 文档库中打开 Project 文件时将显示错误，并且无法打开该文件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-357">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-358">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-358">Word</span></span>
- <span data-ttu-id="2ac07-359">保存现有文件可能不起作用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-359">Saving existing files may not work.</span></span>
- <span data-ttu-id="2ac07-360">在“拼写和语法”编辑器窗口中使用箭头键可能导致间歇性闪烁。</span><span class="sxs-lookup"><span data-stu-id="2ac07-360">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="2ac07-361">解析跟进时，关联的批注可能无法转换为重点批注。</span><span class="sxs-lookup"><span data-stu-id="2ac07-361">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="2ac07-362">插入 3D 模型（动画或静态）并尝试“另存为图片”不起作用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-362">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-363">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-363">Office Suite</span></span>
- <span data-ttu-id="2ac07-364">修复了 Office 更新消息以与预期不同的语言显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-364">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2ac07-365">今后，Office 更新消息将正确匹配 Windows 显示语言。</span><span class="sxs-lookup"><span data-stu-id="2ac07-365">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-december-06"></a><span data-ttu-id="2ac07-367">版本 1912：12 月 6日</span><span class="sxs-lookup"><span data-stu-id="2ac07-367">Version 1912: December 06</span></span>
<span data-ttu-id="2ac07-368">*版本 1912（内部版本 12325.20012）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-368">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-370">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-370">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-371">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-371">Outlook</span></span>

- <span data-ttu-id="2ac07-372">**高级组电子邮件设置：** 此功能可帮助组用户自定义要在收件箱中接收/关注的电子邮件或事件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-372">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="2ac07-373">**组命名策略：** 组命名策略使 IT 管理员能够标准化管理组织中由用户创建的组名。</span><span class="sxs-lookup"><span data-stu-id="2ac07-373">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="2ac07-374">管理员可以要求在创建组时向名称添加特定前缀和后缀，并阻止使用指定的字词。</span><span class="sxs-lookup"><span data-stu-id="2ac07-374">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="2ac07-375">这有助于尽可能在组名中减少使用不适宜的字词，以及有助于IT部门在目录中管理组的显示方式。</span><span class="sxs-lookup"><span data-stu-id="2ac07-375">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="2ac07-376">命名策略还可有助于组织根据部门部署团队网站，以进行分类。</span><span class="sxs-lookup"><span data-stu-id="2ac07-376">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-377">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-377">Office Suite</span></span>

- <span data-ttu-id="2ac07-378">**制表符窗格：** 现在，可以使用应用程序右侧的选项卡 UI 在多个窗格之间进行切换。</span><span class="sxs-lookup"><span data-stu-id="2ac07-378">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="2ac07-379">UI 将只在当打开2个以上的窗格时才会可见。</span><span class="sxs-lookup"><span data-stu-id="2ac07-379">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-382">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-382">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-383">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-383">Excel</span></span>
- <span data-ttu-id="2ac07-384">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="2ac07-384">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="2ac07-385">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-385">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="2ac07-386">禁用 4k 分辨率硬件图形加速可能会延迟单元格的渲染。</span><span class="sxs-lookup"><span data-stu-id="2ac07-386">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="2ac07-387">清除覆盖单元格边界的长公式，可能仍会跨单元格边界显示。</span><span class="sxs-lookup"><span data-stu-id="2ac07-387">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="2ac07-388">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-388">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="2ac07-389">页边距下拉菜单可能无法正确呈现。</span><span class="sxs-lookup"><span data-stu-id="2ac07-389">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="2ac07-390">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ac07-390">OneNote</span></span>
- <span data-ttu-id="2ac07-391">OneNote 可能无法通过‘会议记录’ Outlook 加载项打开。</span><span class="sxs-lookup"><span data-stu-id="2ac07-391">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-392">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-392">Outlook</span></span>
- <span data-ttu-id="2ac07-393">保留策略标签可能会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="2ac07-393">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="2ac07-394">日语语言包的联系人卡片中可能出现空格。</span><span class="sxs-lookup"><span data-stu-id="2ac07-394">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="2ac07-395">内联插入 Outlook 电子邮件正文中的图像，有时尺寸会发生变化。</span><span class="sxs-lookup"><span data-stu-id="2ac07-395">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-396">PowerPoint</span></span>
- <span data-ttu-id="2ac07-397">如果用户在云端文件的幻灯片中有两个（或更多）不同的视频，视频图像可以正确渲染，但当用户单击各视频进行播放时，视频内容相同。</span><span class="sxs-lookup"><span data-stu-id="2ac07-397">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="2ac07-398">在某些情况中，无法使用触摸设备滚动。</span><span class="sxs-lookup"><span data-stu-id="2ac07-398">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="2ac07-399">页边距下拉菜单可能无法正确呈现。</span><span class="sxs-lookup"><span data-stu-id="2ac07-399">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="2ac07-400">一个 Office 应用程序至其它应用程序的 Safelink 可能无法启动关联的应用程序。</span><span class="sxs-lookup"><span data-stu-id="2ac07-400">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-401">项目</span><span class="sxs-lookup"><span data-stu-id="2ac07-401">Project</span></span>
- <span data-ttu-id="2ac07-402">使用 "比较项目" 功能时，项目可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-402">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="2ac07-403">如果处于深色模式，转至含有过度分配资源的任务的任务检查器面板时，将无法读取表格。</span><span class="sxs-lookup"><span data-stu-id="2ac07-403">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="2ac07-404">无分配任务的工作量取舍为1天。</span><span class="sxs-lookup"><span data-stu-id="2ac07-404">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-405">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-405">Word</span></span>
- <span data-ttu-id="2ac07-406">在某些情况下，合并邮件后可能无法保存文件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-406">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="2ac07-407">构建基块管理器可能显示无效的警报：&quot;你已更改样式、构建基块&quot;。</span><span class="sxs-lookup"><span data-stu-id="2ac07-407">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="2ac07-408">使用粘贴/复制时，批注窗格有时会重新载入。</span><span class="sxs-lookup"><span data-stu-id="2ac07-408">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="2ac07-409">有时批注无法采用正确顺序粘贴。</span><span class="sxs-lookup"><span data-stu-id="2ac07-409">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="2ac07-410">应用含有多级列表及自定义样式的模板，可能无法在指定条件下保留样式。</span><span class="sxs-lookup"><span data-stu-id="2ac07-410">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="2ac07-411">重新调整分屏边框大小可能产生附加的分屏。</span><span class="sxs-lookup"><span data-stu-id="2ac07-411">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="2ac07-412">页边距下拉菜单可能无法正确呈现。</span><span class="sxs-lookup"><span data-stu-id="2ac07-412">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="2ac07-413">批注卡中的用户可能显示 JSON。</span><span class="sxs-lookup"><span data-stu-id="2ac07-413">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="2ac07-414">一个 Office 应用程序至其它应用程序的 Safelink 可能无法启动关联的应用程序。</span><span class="sxs-lookup"><span data-stu-id="2ac07-414">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-415">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-415">Office Suite</span></span>
- <span data-ttu-id="2ac07-416">对于基于日语的产品，账户用户的名字、姓氏可能按照错误的顺序显示。</span><span class="sxs-lookup"><span data-stu-id="2ac07-416">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="2ac07-417">悬停鼠标指针在批注上方可能会在批注周围显示文本框轮廓。</span><span class="sxs-lookup"><span data-stu-id="2ac07-417">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-november-15"></a><span data-ttu-id="2ac07-419">版本 1912：11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-419">Version 1912: November 15</span></span>
<span data-ttu-id="2ac07-420">*版本 1912（内部版本 12307.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-420">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-422">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-422">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="2ac07-423">见解服务</span><span class="sxs-lookup"><span data-stu-id="2ac07-423">Insights Services</span></span>
- <span data-ttu-id="2ac07-424">**Excel 中的“创意”中的自然语言查询：** Excel 创意的针对数据进行自然语言提问的新功能。</span><span class="sxs-lookup"><span data-stu-id="2ac07-424">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-427">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-427">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-428">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-428">Excel</span></span>
- <span data-ttu-id="2ac07-429">某些本地化版本的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="2ac07-429">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="2ac07-430">编辑单元格中的动态数组公式可能会导致文本在单元格边界之外对齐。</span><span class="sxs-lookup"><span data-stu-id="2ac07-430">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-431">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-431">Outlook</span></span>
- <span data-ttu-id="2ac07-432">添加了通过组策略强制执行 S/MIME 配置的能力。</span><span class="sxs-lookup"><span data-stu-id="2ac07-432">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="2ac07-433">嵌入的图像可能看起来比预期的要小。</span><span class="sxs-lookup"><span data-stu-id="2ac07-433">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-434">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-434">PowerPoint</span></span>
- <span data-ttu-id="2ac07-435">将焦点从文本移动后，光标可能会消失。</span><span class="sxs-lookup"><span data-stu-id="2ac07-435">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-436">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-436">Project</span></span>
- <span data-ttu-id="2ac07-437">用户可能遇到有关许可方面的错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-437">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="2ac07-438">日期选取器中的“今天”按钮有时可能会设置错误的日期。</span><span class="sxs-lookup"><span data-stu-id="2ac07-438">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-439">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-439">Word</span></span>
- <span data-ttu-id="2ac07-440">右键单击有时无法选择整个单词。</span><span class="sxs-lookup"><span data-stu-id="2ac07-440">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="2ac07-441">在转换为建议的格式后，光标可能在对象中保持活动状态。</span><span class="sxs-lookup"><span data-stu-id="2ac07-441">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="2ac07-442">在某些情况下，邮件中的图像可能无法正确缩放。</span><span class="sxs-lookup"><span data-stu-id="2ac07-442">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="2ac07-443">某些主题可能会导致难以确定选择了哪个批注。</span><span class="sxs-lookup"><span data-stu-id="2ac07-443">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="2ac07-444">现在，选择批注提示会在其在窗格切换器中隐藏时显示新式批注窗格。</span><span class="sxs-lookup"><span data-stu-id="2ac07-444">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-445">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-445">Office Suite</span></span>
- <span data-ttu-id="2ac07-446">回复批注可能会导致文本框垂直展开到窗格边缘以外。</span><span class="sxs-lookup"><span data-stu-id="2ac07-446">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-november-08"></a><span data-ttu-id="2ac07-448">版本 1912：11 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-448">Version 1912: November 08</span></span>
<span data-ttu-id="2ac07-449">*版本 1912（内部版本 12231.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-449">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-451">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-451">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="2ac07-452">用户生命周期</span><span class="sxs-lookup"><span data-stu-id="2ac07-452">User Lifecycle</span></span>
- <span data-ttu-id="2ac07-453">**体验改进 AFO 激活：** 在激活与新电脑捆绑的 Office 时，客户看到的屏幕更新。</span><span class="sxs-lookup"><span data-stu-id="2ac07-453">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-454">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-454">Word</span></span>
- <span data-ttu-id="2ac07-455">**Word 中新的和改进的在线视频体验：** 新的和更安全的在线视频体验，帮助你在 Word 中插入新视频和播放现有视频。</span><span class="sxs-lookup"><span data-stu-id="2ac07-455">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-458">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-458">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-459">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-459">Outlook</span></span>
- <span data-ttu-id="2ac07-460">涉及跨文件夹内容的间歇性崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-460">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-461">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-461">Office Suite</span></span>
- <span data-ttu-id="2ac07-462">将图表从 Excel 粘贴到 PowerPoint 后，可减小图表的大小。</span><span class="sxs-lookup"><span data-stu-id="2ac07-462">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1911-november-01"></a><span data-ttu-id="2ac07-464">版本 1911：11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-464">Version 1911: November 01</span></span>
<span data-ttu-id="2ac07-465">*版本 1911（内部版本 12228.20020）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-465">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-467">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-467">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-468">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-468">Excel</span></span>
- <span data-ttu-id="2ac07-469">**将上下文和 SVG 对象一起显示！：** 现在，你可以在 Office 中转换这些对象时保留地图、图表和其他 SVG 向量中的文本。</span><span class="sxs-lookup"><span data-stu-id="2ac07-469">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="2ac07-470">**选择 Surface 触控笔时查看触控笔选项：** 首次在 Word、Excel 或 PowerPoint 中选取 Surface 触控笔时，将激活“绘图”选项卡，以轻松选择笔颜色。</span><span class="sxs-lookup"><span data-stu-id="2ac07-470">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-471">PowerPoint</span></span>
- <span data-ttu-id="2ac07-472">**将上下文和 SVG 对象一起显示！：** 现在，你可以在 Office 中转换这些对象时保留地图、图表和其他 SVG 向量中的文本。</span><span class="sxs-lookup"><span data-stu-id="2ac07-472">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="2ac07-473">**选择 Surface 触控笔时查看触控笔选项：** 首次在 Word、Excel 或 PowerPoint 中选取 Surface 触控笔时，将激活“绘图”选项卡，以轻松选择笔颜色。</span><span class="sxs-lookup"><span data-stu-id="2ac07-473">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="2ac07-474">Visio</span><span class="sxs-lookup"><span data-stu-id="2ac07-474">Visio</span></span>
- <span data-ttu-id="2ac07-475">**在 Excel 中制作精美的 Visio 图表：** 在 Excel 中快速轻松地将数据可视化为精美的 Visio 图表。</span><span class="sxs-lookup"><span data-stu-id="2ac07-475">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="2ac07-476">[了解详细信息](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)。</span><span class="sxs-lookup"><span data-stu-id="2ac07-476">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-477">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-477">Word</span></span>
- <span data-ttu-id="2ac07-478">**选择 Surface 触控笔时查看触控笔选项：** 首次在 Word、Excel 或 PowerPoint 中选取 Surface 触控笔时，将激活“绘图”选项卡，以轻松选择笔颜色。</span><span class="sxs-lookup"><span data-stu-id="2ac07-478">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="2ac07-479">**共同创作改进：** 通过让其他人以更接近实时的方式接收内容更改，改进了共同创作体验。</span><span class="sxs-lookup"><span data-stu-id="2ac07-479">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="2ac07-480">\*\*其他人可以快速查看你所做的更改: \*\*共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="2ac07-480">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-483">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-483">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-484">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-484">Excel</span></span>
- <span data-ttu-id="2ac07-485">解决了在编辑不受信任的网络共享中的受保护文件时 Excel 可能发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-485">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="2ac07-486">解决了以下问题：如果删除了包含引用其他工作表上数据的迷你图的工作表，则重新打开时，该文件会被标识为损坏。</span><span class="sxs-lookup"><span data-stu-id="2ac07-486">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="2ac07-487">解决了以下问题：将报表筛选器与查询的数据透视表其余部分一起转换为 SQL 表格式服务器时，可能会得到错误的结果。</span><span class="sxs-lookup"><span data-stu-id="2ac07-487">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="2ac07-488">同时使用“讲述人”和“放大镜”可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-488">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="2ac07-489">同时使用“讲述人”和“放大镜”可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-489">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-490">Outlook</span></span>
- <span data-ttu-id="2ac07-491">转发的电子邮件可能缺少嵌入图像。</span><span class="sxs-lookup"><span data-stu-id="2ac07-491">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="2ac07-492">对于可用会议室，会议室查找工具可能显示“&quot;无&quot;”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-492">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="2ac07-493">用户可能无法创建具有严格租户限制的 Outlook 配置文件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-493">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-494">PowerPoint</span></span>
- <span data-ttu-id="2ac07-495">同时使用“讲述人”和“放大镜”可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-495">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-496">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-496">Project</span></span>
- <span data-ttu-id="2ac07-497">用户无法将任务标记为“已完成”，而只能将其设置为 99%。</span><span class="sxs-lookup"><span data-stu-id="2ac07-497">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="2ac07-498">无法通过调配解决过度分配问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-498">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-499">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-499">Word</span></span>
- <span data-ttu-id="2ac07-500">同时使用“讲述人”和“放大镜”可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-500">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="2ac07-501">打开旧版文档后转到“信息”选项卡会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-501">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="2ac07-502">校对建议未显示在上下文菜单中。</span><span class="sxs-lookup"><span data-stu-id="2ac07-502">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="2ac07-503">内容策略被错误地应用到了批注。</span><span class="sxs-lookup"><span data-stu-id="2ac07-503">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="2ac07-504">在深色模式中看不到用深色文本编写的旧式批注。</span><span class="sxs-lookup"><span data-stu-id="2ac07-504">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="2ac07-505">使用韩语/英语自动更正时可能出现不正确的字符。</span><span class="sxs-lookup"><span data-stu-id="2ac07-505">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="2ac07-506">当较高的策略标签具有优先级时可能应用较低的策略标签。</span><span class="sxs-lookup"><span data-stu-id="2ac07-506">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="2ac07-507">Outlook 邮件中的 cid: images 链接&nbsp;现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ac07-507">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="2ac07-508">同时使用“讲述人”和“放大镜”可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-508">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="2ac07-509">从导航窗格中搜索可能失败。</span><span class="sxs-lookup"><span data-stu-id="2ac07-509">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-510">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-510">Office Suite</span></span>
- <span data-ttu-id="2ac07-511">预览或幻灯片放映中可能不会显示某些绘图。</span><span class="sxs-lookup"><span data-stu-id="2ac07-511">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="2ac07-512">竖排文本框中有些片假名字符可能无法正确显示。</span><span class="sxs-lookup"><span data-stu-id="2ac07-512">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="2ac07-513">尝试将文件保存到断开的网络共享可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ac07-513">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1911-october-25"></a><span data-ttu-id="2ac07-515">版本 1911：10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-515">Version 1911: October 25</span></span>
<span data-ttu-id="2ac07-516">*版本 1911（内部版本 12215.20006）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-516">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-518">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-518">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="2ac07-519">Visio</span><span class="sxs-lookup"><span data-stu-id="2ac07-519">Visio</span></span>

- <span data-ttu-id="2ac07-520">**在 Excel 中制作精美的 Visio 图表：** 在 Excel 中快速轻松地将数据可视化为精美的 Visio 图表。</span><span class="sxs-lookup"><span data-stu-id="2ac07-520">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="2ac07-521">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-521">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="2ac07-522">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-522">Word</span></span>

- <span data-ttu-id="2ac07-523">**共同创作改进：** 通过让其他人以更接近实时的方式接收内容更改，改进了共同创作体验。</span><span class="sxs-lookup"><span data-stu-id="2ac07-523">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="2ac07-524">\*\*其他人可以快速查看你所做的更改: \*\*共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="2ac07-524">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ac07-527">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-527">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ac07-528">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-528">Access</span></span>

- <div><span data-ttu-id="2ac07-529"><span>记录计数可能不正确</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-529"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="2ac07-530">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-530">Excel</span></span>

- <div><span data-ttu-id="2ac07-531"><span>显著提高了使用合并单元格删除列的性能</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-531"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="2ac07-532"><span>可阻止用户以 Office 365 Excel 工作簿格式保存</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-532"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="2ac07-533"><span>无法正确呈现复选框</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-533"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="2ac07-534"><span>无法保存对图表大小所做的更改</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-534"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="2ac07-535"><span>某些 VBA 函数将在新的图表类型上返回错误</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-535"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="2ac07-536"><span>“选择数据源”对话框对于某些字段不区分大小写</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-536"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-537">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-538"><span>无法保存对图表大小所做的更改</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-538"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="2ac07-539">Publisher</span><span class="sxs-lookup"><span data-stu-id="2ac07-539">Publisher</span></span>

- <div><span data-ttu-id="2ac07-540"><span>形状可能出现在图形边框之外</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-540"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-541">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-541">Word</span></span>

- <div><span data-ttu-id="2ac07-542"><span>形状可能出现在图形边框之外</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-542"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="2ac07-543"><span>突出显示文本可能很困难</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-543"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="2ac07-544"><span>可以防止用户导航到编辑器中的单个项目</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-544"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="2ac07-545"><span>可能未突出显示语法或拼写错误</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-545"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="2ac07-546"><span>无法保存对图表大小所做的更改</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-546"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="2ac07-547"><span>将格式应用于 @ 提及后，可能会阻止联系卡打开</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-547"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="2ac07-548"><span>解决了用户可能无法保存 Word、Excel 和 PowerPoint 文档的问题。&nbsp; 此问题会影响用户创建新文件并在单击“保存”图标或按 Ctrl + S 后弹出 &quot;另存为模型对话框&quot; 选项。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-548"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="2ac07-549">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-549">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-550"><span>在 Windows 7 上使用形状时出现性能问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-550"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1911-october-18"></a><span data-ttu-id="2ac07-552">版本 1911：10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-552">Version 1911: October 18</span></span>
<span data-ttu-id="2ac07-553">*版本 1911（内部版本 12209.20010）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-553">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-555">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-555">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2ac07-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-556">Outlook</span></span>

- <span data-ttu-id="2ac07-557">**将易访问邮件发送给最需要的人员：** Outlook 将显示邮件提示，以帮助确保在向喜欢易访问内容的用户发送邮件时可访问你的内容</span><span class="sxs-lookup"><span data-stu-id="2ac07-557">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-558">PowerPoint</span></span>

- <span data-ttu-id="2ac07-559">**全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。</span><span class="sxs-lookup"><span data-stu-id="2ac07-559">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ac07-560">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-560">Office Suite</span></span>

- <span data-ttu-id="2ac07-561">**“需要注意的文件”体验将替换上载中心：**“需要注意的文件”体验将替换上载中心，该体验将显示在 Office 应用程序的“文件”>“打开”中。</span><span class="sxs-lookup"><span data-stu-id="2ac07-561">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="2ac07-562">与上载中心相比，这种新体验更加现代、集成度更高并且干扰性更低。</span><span class="sxs-lookup"><span data-stu-id="2ac07-562">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-565">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-565">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-566">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-566">Excel</span></span>

- <div><span data-ttu-id="2ac07-567"><span>解决了使用自动调整功能调整行高时复选框控件可能缩小的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-567"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="2ac07-568"><span>解决了在滚动后选择单元格时可能导致选择错误单元格的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-568"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="2ac07-569">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-569">Outlook</span></span>

- <div><span data-ttu-id="2ac07-570"><span>发现了在对带有数字签名附件的电子邮件进行签名时可能导致数字签名破坏的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-570"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="2ac07-571"><span>发现了将长文件名拖放到邮件正文后被截断的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-571"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="2ac07-572">发现了将功能区设置为自动隐藏时搜索框可能消失的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-572">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-573">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-573">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-574"><span>发现了幻灯片预览的纵横比未正确锁定/解锁的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-574"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="2ac07-575">项目</span><span class="sxs-lookup"><span data-stu-id="2ac07-575">Project</span></span>

- <div><span data-ttu-id="2ac07-576">发现了在执行更新任务时输入的备注可能无法保留的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-576">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="2ac07-577">发现了用户可以锁定文件但错误消息中未显示用户名的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-577">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="2ac07-578"><span>发现了用户在打开只读项目时可能会收到几则消息的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-578"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-579">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-579">Word</span></span>

- <div><span data-ttu-id="2ac07-580"><span>在使用屏幕阅读器查看批注时发现了一个问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-580"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="2ac07-581"><span>发现了某些评论被误认为是拼写或语法评论的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-581"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="2ac07-582"><span>发现了新批注对话框有时无法获取焦点的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-582"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="2ac07-583">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-583">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-584"><span>我们修复了错误消息&quot;正在进行其他安装&quot;阻止升级的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-584"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="2ac07-585"><span>发现了可能影响从本地资源同步到云资源的的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-585"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="2ac07-586"><span>发现了欢迎消息中包含无效链接的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-586"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-october-11"></a><span data-ttu-id="2ac07-588">版本 1910：10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-588">Version 1910: October 11</span></span>
<span data-ttu-id="2ac07-589">*版本 1910（内部版本 12130.20112）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-589">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)
[//]: # (请勿移除功能详细信息内容结尾)
[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-593">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-593">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-594">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-594">Excel</span></span>

- <div><span data-ttu-id="2ac07-595">解决了将文件作为来自 OneDrive 的对象插入时出现的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-595">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="2ac07-596">解决了无法将超链接格式正确应用到某些内容的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-596">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="2ac07-597">解决了包含结构化绝对引用的公式可能无法正确调整的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-597">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="2ac07-598">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起</span><span class="sxs-lookup"><span data-stu-id="2ac07-598">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="2ac07-599">解决了一个问题，当从 Excel 复制内容粘贴到其他 Office 应用程序中时，可能会显示不正确</span><span class="sxs-lookup"><span data-stu-id="2ac07-599">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="2ac07-600">修复了使用图表模板插入图表时预览中所用颜色的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-600">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-601">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-601">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-602">发现了 ARC 设备在 AirSpace WinComp 下运行时可能会断开连接的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-602">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-603">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-603">Word</span></span>

- <div><span data-ttu-id="2ac07-604">解决了将文件作为来自 OneDrive 的对象插入时出现的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-604">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="2ac07-605">改进了恢复步骤以<span>修复导致图形内容从电子邮件线程中被删除的问题。&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-605">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-october-04"></a><span data-ttu-id="2ac07-607">版本 1910：10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-607">Version 1910: October 04</span></span>
<span data-ttu-id="2ac07-608">*版本 1910（内部版本 12126.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-608">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-610">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-610">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-611">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-611">Excel</span></span>

- <span data-ttu-id="2ac07-612">**数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。</span><span class="sxs-lookup"><span data-stu-id="2ac07-612">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="2ac07-613">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-613">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-616">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-616">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-617">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-617">Excel</span></span>

- <div><span data-ttu-id="2ac07-618"><span>我们修复了打印预览中的打印区域不正确的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-618"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="2ac07-619"><span>我们修复了在共同创作会话期间可能阻止刷新数据透视表的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-619"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="2ac07-620">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-620">Access</span></span>

- <div><span data-ttu-id="2ac07-621">我们修复了一个问题，即用户在使用共享数据库时可能会收到“&quot;不一致状态&quot;”错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-621">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="2ac07-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-622">Outlook</span></span>

- <div><span data-ttu-id="2ac07-623"><span>我们修复了可能导致邮件文件夹重复的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-623"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="2ac07-624"><span>我们修复了当尝试发送 S/MIME 加密电子邮件时可能导致错误消息的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-624"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="2ac07-625"><span>我们修复了一个问题，即当用户从 Skype 收到“错过的对话”消息时，该问题有时可能会导致崩溃</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-625"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="2ac07-626"><span>我们修复了可能导致内存泄漏的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-626"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="2ac07-627"><span>我们修复了当另存为草稿时可能导致发件人的姓名发生更改的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-627"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-628">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-628">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="2ac07-629">我们修复了一个问题，即将文本粘贴到幻灯片母版和幻灯片版式上的页眉/页脚/幻灯片编号占位符后，TextRanges 出现损坏</span><span class="sxs-lookup"><span data-stu-id="2ac07-629">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="2ac07-630">我们修复了在粘贴带有超链接的文本时阻止创建超链接的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-630">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="2ac07-631">我们修复了阻止统计信息正常工作的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-631">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-632">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-632">Word</span></span>

- <div><span data-ttu-id="2ac07-633"><span>我们修复了未提交字体颜色的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-633"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="2ac07-634">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-634">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-635">我们修复了禁用该功能后可能提供版本历史记录的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-635">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-27"></a><span data-ttu-id="2ac07-637">版本 1910：9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-637">Version 1910: September 27</span></span>
<span data-ttu-id="2ac07-638">*版本 1910（内部版本 12119.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-638">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)
[//]: # (请勿移除功能详细信息内容结尾)
[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-642">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-642">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-643">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-643">Excel</span></span>

- <div><span data-ttu-id="2ac07-644"><span>我们修复了在更改系列集合时可能导致散点图和折线图无法正确呈现的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-644"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="2ac07-645">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-645">Outlook</span></span>

- <div><span data-ttu-id="2ac07-646"><span>我们修复了与共享日历文件夹进行交互时可能报告权限错误的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-646"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="2ac07-647"><span>我们修复了可能阻止用户向日历添加附件的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-647"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="2ac07-648"><span>我们修复了导致在答复数字签名邮件时显示错误消息的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-648"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-649">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-649">Word</span></span>

- <div><span data-ttu-id="2ac07-650"><span>我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-650"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="2ac07-651">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-651">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-652"><span>我们修复了中粗体文本具有错误样式的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-652"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="2ac07-653"><span>我们修复了一个问题，即关闭等待上传的文件时，用户可能收到错误消息</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-653"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-20"></a><span data-ttu-id="2ac07-655">版本 1910：9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-655">Version 1910: September 20</span></span>
<span data-ttu-id="2ac07-656">*版本 1910（内部版本 12112.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-656">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-660">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-660">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-661">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-661">Excel</span></span>

- <div><span data-ttu-id="2ac07-662"><span>我们修复了 Excel 有时可能在启动时挂起的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-662"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="2ac07-663">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-663">Outlook</span></span>

- <div><span data-ttu-id="2ac07-664"><span>我们显著改善了当有大量会议室可用时进行房间选择的性能</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-664"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="2ac07-665"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我们修复了以下问题：在迁移到 Office 365 中的新式验证时，在 Outlook 中使用多个邮箱的客户可能无法进行邮箱同步。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-665"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="2ac07-666"><span>我们修复了签名标签中某些字符在下拉菜单中不会显示的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-666"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="2ac07-667">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-667">Project</span></span>

- <div><span data-ttu-id="2ac07-668"><span>我们修复了将企业资源替换为本地资源时可能导致崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-668"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-669">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-669">Word</span></span>

- <div><span data-ttu-id="2ac07-670"><span>我们修复了可能导致同步滚动操作在草稿视图中无法正常工作的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-670"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="2ac07-671">我们修复了可能导致在首次保存文档后无法正常显示工具提示的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-671">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-13"></a><span data-ttu-id="2ac07-673">版本 1910：9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-673">Version 1910: September 13</span></span>
<span data-ttu-id="2ac07-674">*版本 1910（内部版本 12105.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-674">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-676">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-676">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-677">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-677">Excel</span></span>

- <div><span data-ttu-id="2ac07-678"><span>已修复阻止用户在某些受保护的工作表中粘贴超链接的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-678"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="2ac07-679">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-679">Outlook</span></span>

- <div><span data-ttu-id="2ac07-680"><span>已修复问题：UI 在紧凑视图中卡顿</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-680"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-681">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-681">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-682"><span>已修复问题：用户打印到 PDF 时发生错误</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-682"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="2ac07-683">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-683">Project</span></span>

- <div><span data-ttu-id="2ac07-684"><span>已修复问题：<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">在启用了工作保护的情况下，对摘要任务的工作值进行更改会导致崩溃</span></span></span><span class="sxs-lookup"><span data-stu-id="2ac07-684"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="2ac07-685"><font size=2 style="background-color:rgb(255, 255, 255);">已修复妨碍与企业日历同步事件的功能的问题</font></span><span class="sxs-lookup"><span data-stu-id="2ac07-685"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="2ac07-686">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-686">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-687"><span>我们已修复导致放弃文件的本地版本的重复警告的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-687"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-06"></a><span data-ttu-id="2ac07-689">版本 1910：9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-689">Version 1910: September 06</span></span>
<span data-ttu-id="2ac07-690">*版本 1910（内部版本 12030.20004）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-690">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-692">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-692">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-693">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-693">Excel</span></span>

- <span data-ttu-id="2ac07-694">**准备、设置、绘图：** 抓住 Surface 触控笔时，即可绘图。</span><span class="sxs-lookup"><span data-stu-id="2ac07-694">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="2ac07-695">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-695">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="2ac07-696">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-696">PowerPoint</span></span>

- <span data-ttu-id="2ac07-697">**准备、设置、绘图：** 抓住 Surface 触控笔时，即可绘图。</span><span class="sxs-lookup"><span data-stu-id="2ac07-697">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="2ac07-698">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="2ac07-698">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="2ac07-699">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-699">Word</span></span>

- <span data-ttu-id="2ac07-700">**准备、设置、绘图：** 抓住 Surface 触控笔时，即可绘图。</span><span class="sxs-lookup"><span data-stu-id="2ac07-700">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="2ac07-701">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="2ac07-701">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-704">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-704">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-705">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-705">Excel</span></span>

- <div><span data-ttu-id="2ac07-706"><span>我们修复了一个问题，它可能导致功能区中的字体名称与正在使用的字体不同</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-706"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="2ac07-707">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-707">Outlook</span></span>

- <div><span data-ttu-id="2ac07-708"><span>我们修复了一个问题，即在 Internet Explorer 中为受限站点禁用保护模式时，Outlook 可能会导致资源消耗不当</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-708"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="2ac07-709"><span>我们修复了一个问题，即当从 ANSI 源粘贴文本时，有时会导致出现 Unicode 字符</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-709"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="2ac07-710"><span>修复了某些用户在“小组日程”视图中错误地显示为“离线”的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-710"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-711">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-711">Word</span></span>

- <div><span data-ttu-id="2ac07-712"><span>我们修复了表格格式可能丢失的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-712"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="2ac07-713"><span>我们修复了可能断开 CTRL+V 键盘快捷方式的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-713"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1909-august-30"></a><span data-ttu-id="2ac07-715">版本 1909：8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-715">Version 1909: August 30</span></span>
<span data-ttu-id="2ac07-716">*版本 1909（内部版本 12026.20000）*</span><span class="sxs-lookup"><span data-stu-id="2ac07-716">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ac07-718">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-718">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-719">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-719">Access</span></span>

- <span data-ttu-id="2ac07-720">**快速查找链接的表格：** 新的“搜索”框使查找链接的表格成为一项轻松的乐事。</span><span class="sxs-lookup"><span data-stu-id="2ac07-720">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-721">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-721">PowerPoint</span></span>

- <span data-ttu-id="2ac07-722">**将插图另存为 SVG**：将图表、形状或其他插图另存为可缩放矢量图形，这样做可以调整其大小，而不会降低图像质量。</span><span class="sxs-lookup"><span data-stu-id="2ac07-722">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="2ac07-723">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="2ac07-723">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ac07-726">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-726">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ac07-727">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-727">Excel</span></span>

- <div><span data-ttu-id="2ac07-728"><span>我们修复了&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">敏感度</span>的快捷键提示与&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">另一个快捷键提示相冲突的问题。</span></span></span><span class="sxs-lookup"><span data-stu-id="2ac07-728"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="2ac07-729"><span>我们修复了在处理共享工作簿和尝试保存时发生的问题。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-729"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="2ac07-730"><span>我们修复了一个问题，即 Excel 仅列出位于“\Excel\Add-in Manager”注册表值中的前 16 个加载项。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="2ac07-730"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="2ac07-731"><span>我们修复了 Frequency 函数返回错误结果的问题。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-731"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="2ac07-732"><span>我们显著提高了按颜色筛选的性能。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-732"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="2ac07-733"><span>我们修复了 Surface 用户遇到的一个问题，即移动鼠标可能解释为鼠标单击事件。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-733"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="2ac07-734"><span>我们修复了阻止在“查找/替换”对话框中进行键盘导航的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-734"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="2ac07-735"><span>我们修复了某些字体名称无法正确显示的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-735"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="2ac07-736"><span>我们修复了阻止 CSV 显示为受支持的文件类型的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-736"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="2ac07-737">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-737">Access</span></span>

- <div><span data-ttu-id="2ac07-738">我们修复了一个问题，即用户在使用共享数据库时可能会收到“&quot;不一致状态&quot;”错误。</span><span class="sxs-lookup"><span data-stu-id="2ac07-738">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="2ac07-739"><span>我们修复了可能导致在错误时间显示日期选取器的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-739"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="2ac07-740">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-740">Outlook</span></span>

- <div><span data-ttu-id="2ac07-741"><span>们修复了阻止向某些 POP3 用户显示 HTML 内容的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-741"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="2ac07-742"><span>我们修复了一个问题，即在其不可用的环境中工作时，将从联系人卡片的溢出菜单中删除不起作用的“规划器”链接。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-742"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="2ac07-743">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ac07-743">OneNote</span></span>

- <div><span data-ttu-id="2ac07-744"><span>我们修复了 &nbsp;OneNote 后台同步有时会成为焦点的问题。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-744"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-745">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-745">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-746"><span>我们修复了会影响 3D 转盘旋转方向的问题。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-746"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="2ac07-747"><span>我们修复了如果某些超链接中包含特殊字符，则会阻止其打开的问题。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-747"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="2ac07-748"><span>我们修复了导致多个评论窗格同时打开的问题。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-748"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="2ac07-749">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-749">Project</span></span>

- <div><span data-ttu-id="2ac07-750"><span>我们修复了在打印工作组规划器视图后有时会导致崩溃的问题。</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-750"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="2ac07-751">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-751">Word</span></span>

- <div><span data-ttu-id="2ac07-752">我们<span>修复了垂直文本框中的多字节字符在阅读视图中重叠显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-752">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="2ac07-753"><span>我们&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">修复了以下问题：当用户在加载项向导中执行操作时，找不到日语明信片和贺卡相关加载项资源。</span></span></span><span class="sxs-lookup"><span data-stu-id="2ac07-753"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="2ac07-754"><span>我们修复了一个问题，即在受保护视图中，它可能导致标题栏用户界面出现问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-754"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="2ac07-755">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-755">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-756"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">我们修复了在包含普通形状和连接线形状的选择中更改形状时出现的文件损坏问题。</span></span></span><span class="sxs-lookup"><span data-stu-id="2ac07-756"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="2ac07-757"><span>我们修复了<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">从多个外部显示器使用停靠/取消停靠时导致应用程序出现问题的问题。</span></span></span><span class="sxs-lookup"><span data-stu-id="2ac07-757"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="august-23-2019br"></a><span data-ttu-id="2ac07-759">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="2ac07-759">**August 23, 2019**</span></span><br/>
<span data-ttu-id="2ac07-760">版本 1909（内部版本 12015.20004）</span><span class="sxs-lookup"><span data-stu-id="2ac07-760">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="2ac07-761">与安全无关的更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-761">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-762">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-762">Excel</span></span>

- <div><span data-ttu-id="2ac07-763"><span>显著提高了使用合并单元格删除列的性能</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-763"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="2ac07-764">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-764">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-765"><span>修复了在浏览器中查看时某些 Unicode 字符无法显示的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-765"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="2ac07-766">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-766">Outlook</span></span>

- <div><span data-ttu-id="2ac07-767"><span>修复了使文件无法保存到 WebDAV 位置的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-767"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-768">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-768">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-769"><span>修复了单击一个评论却选中的是另一个评论的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-769"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="2ac07-770">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="2ac07-770">**August 16, 2019**</span></span><br/>
<span data-ttu-id="2ac07-771">版本 1909（内部版本 12013.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-771">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="2ac07-772">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-772">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="2ac07-773">**打印讲义上的幻灯片编号：** 幻灯片编号将会自动包括在讲义上。</span><span class="sxs-lookup"><span data-stu-id="2ac07-773">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="2ac07-774">打开或是关闭它们，全都取决于你。</span><span class="sxs-lookup"><span data-stu-id="2ac07-774">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="2ac07-775">与安全无关的更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-775">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-776">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-776">Excel</span></span>

- <div><span data-ttu-id="2ac07-777"><span>解决了可能导致启用“自动保存”功能的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-777"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="2ac07-778">修复了未能准确测量单元格高度的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-778">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="2ac07-779">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-779">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-780"><span>解决了一项问题，从而显著提高了“评论”功能的性能</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-780"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="2ac07-781"><span>解决了在搜索时使用箭头键可能会导致崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-781"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="2ac07-782"><span>解决了如果 @ 符号位于某些字符之后可能会阻止 @ 提及的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-782"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="2ac07-783"><span>解决了删除 @ 提及时，有时会出现崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-783"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="2ac07-784"><span>解决了表情符号无法在评论卡片中正确显示的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-784"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="2ac07-785"><span>解决了活动剪贴板​​有时会导致崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-785"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="2ac07-786"><span>修复了致使“快速访问工具栏”按钮停止工作的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-786"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="2ac07-787"><span>解决了阻止“文档格式预览”切换到后台操作的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-787"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="2ac07-788">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ac07-788">OneNote</span></span>

- <span data-ttu-id="2ac07-789">解决了在 Office 主题设置为“空白”时分区名称在分区下拉列表中显示空白的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-789">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-790">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-790">Outlook</span></span>

- <div><span data-ttu-id="2ac07-791"><span>解决了发送事件时可能导致 Outlook 反复获得和失去焦点的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-791"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="2ac07-792"><span>解决了阻止“将答复投递到文件夹”快捷方式正常工作的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-792"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-793">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-793">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-794"><span>解决了协作时“受保护的视图”有时出现故障的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-794"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="2ac07-795"><span>解决了可能阻止评论窗格中的任务正确显示的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-795"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="2ac07-796"><span>解决了插入新的幻灯片时可能会发生崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-796"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="2ac07-797">用户生命周期</span><span class="sxs-lookup"><span data-stu-id="2ac07-797">User Lifecycle</span></span>

- <div><span data-ttu-id="2ac07-798"><span>解决了有时导致订阅功能不可见的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-798"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="2ac07-799">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-799">Word</span></span>

- <div><span data-ttu-id="2ac07-800"><span>解决了在超链接包含某些字符时超链接可能遭到损坏的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-800"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="2ac07-801"><span>解决了查看图像的注释时图像尺寸可能不正确的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-801"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="2ac07-802"><span>修复了“项目符号列表”下拉菜单有时会崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-802"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="2ac07-803">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="2ac07-803">**August 09, 2019**</span></span><br/>
<span data-ttu-id="2ac07-804">版本 1909（内部版本 12001.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-804">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="2ac07-805">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-805">Excel Feature updates:</span></span>

- <span data-ttu-id="2ac07-806">**协作更简单：** 共同创作改进意味着使用条件格式、单元格样式等时，所做的更改将与协作者无缝合并。</span><span class="sxs-lookup"><span data-stu-id="2ac07-806">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="2ac07-807">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="2ac07-807">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ac07-808">选择时，“插入”按钮会告诉你已挑选的数目。</span><span class="sxs-lookup"><span data-stu-id="2ac07-808">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="2ac07-809">Office 套件功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-809">Office Suite Feature updates:</span></span>

- <span data-ttu-id="2ac07-810">**新的 Office 应用图标：** 重新设计应用图标，以反映出 Office 简单、强大而智能的体验。</span><span class="sxs-lookup"><span data-stu-id="2ac07-810">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="2ac07-811">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-811">Outlook Feature updates:</span></span>

- <span data-ttu-id="2ac07-812">**针对攻击的高级防护：** 通过 Office 365 高级威胁防护, 可通过电子邮件主题中的超链接、附加邮件、签名邮件、网络路径等的方式抵御攻击。</span><span class="sxs-lookup"><span data-stu-id="2ac07-812">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="2ac07-813">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="2ac07-813">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ac07-814">选择时，“插入”按钮会告诉你已挑选的数目。</span><span class="sxs-lookup"><span data-stu-id="2ac07-814">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="2ac07-815">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-815">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="2ac07-816">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="2ac07-816">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ac07-817">选择时，“插入”按钮会告诉你已挑选的数目。</span><span class="sxs-lookup"><span data-stu-id="2ac07-817">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="2ac07-818">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-818">Word Feature updates:</span></span>

- <span data-ttu-id="2ac07-819">\*\*其他人可以快速查看你所做的更改: \*\*共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="2ac07-819">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="2ac07-820">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="2ac07-820">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ac07-821">选择时，“插入”按钮会告诉你已挑选的数目。</span><span class="sxs-lookup"><span data-stu-id="2ac07-821">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="2ac07-822">非安全更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-822">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-823">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-823">Outlook</span></span>

- <div><span data-ttu-id="2ac07-824"><span>我们修复了导致会议收件人在取消会议后收到两个通知的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-824"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="2ac07-825">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-825">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-826"><span>我们修复了用户为“形状”和“图标”选择 "无轮廓" 或 "无填充" 时，可能会导致崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-826"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="2ac07-827">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="2ac07-827">**August 02, 2019**</span></span><br/>
<span data-ttu-id="2ac07-828">版本 1908（内部版本 11929.20002）</span><span class="sxs-lookup"><span data-stu-id="2ac07-828">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="2ac07-829">Excel 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-829">Excel Feature updates:</span></span>

- <span data-ttu-id="2ac07-830">\*\*将文件转换为改进辅助功能: \*\*将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="2ac07-830">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="2ac07-831">**向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。</span><span class="sxs-lookup"><span data-stu-id="2ac07-831">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="2ac07-832">Outlook 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-832">Outlook Feature updates:</span></span>

- <span data-ttu-id="2ac07-833">**向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。</span><span class="sxs-lookup"><span data-stu-id="2ac07-833">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="2ac07-834">PowerPoint 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-834">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="2ac07-835">\*\*将文件转换为改进辅助功能: \*\*将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="2ac07-835">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="2ac07-836">**向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。</span><span class="sxs-lookup"><span data-stu-id="2ac07-836">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="2ac07-837">Word 功能更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-837">Word Feature updates:</span></span>

- <span data-ttu-id="2ac07-838">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="2ac07-838">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="2ac07-839">**换一种说法：** 想要用另一种方法表达，重写功能帮你大忙。</span><span class="sxs-lookup"><span data-stu-id="2ac07-839">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="2ac07-840">重写功能为你完善语言提供了替代方案。</span><span class="sxs-lookup"><span data-stu-id="2ac07-840">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="2ac07-841">**向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。</span><span class="sxs-lookup"><span data-stu-id="2ac07-841">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="2ac07-842">与安全无关的更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-842">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-843">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-843">Access</span></span>
- <span data-ttu-id="2ac07-844">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-844">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-845">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-845">Excel</span></span>

- <div><span data-ttu-id="2ac07-846"><span>我们修复了打印到 PDF 时似乎应用了&quot;重复所有标签&quot;的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-846"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="2ac07-847">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ac07-847">Office Suite</span></span>

- <div><span data-ttu-id="2ac07-848"><span>我们修复了可能会阻止用户在桌面上打开文档的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-848"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="2ac07-849"><span>我们修复了错误消息&quot;正在进行其他安装&quot;阻止升级的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-849"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="2ac07-850"><span>我们修复了安装安全更新时用户可能会看到错误消息的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-850"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="2ac07-851"><span>我们解决了可能会导致光标消失的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-851"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="2ac07-852"><span>我们修复了用户可能默认使用“绘图”选项卡而不是“开始”选项卡的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-852"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="2ac07-853"><span>我们修复了大型树视图可能会导致崩溃的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-853"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="2ac07-854">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-854">Outlook</span></span>

- <div></div><span data-ttu-id="2ac07-855"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我们解决了可能会导致不断提示输入密码的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-855"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="2ac07-856"><span>我们修复了可能会妨碍电子邮件地址被正确查询的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-856"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="2ac07-857"><span>我们修复了可能会阻止用户打开旧版 Outlook 所创建的日历项目的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-857"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-858">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-858">PowerPoint</span></span>

- <div><span data-ttu-id="2ac07-859"><span>我们修复了可能阻止某些动画启动的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-859"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="2ac07-860">项目</span><span class="sxs-lookup"><span data-stu-id="2ac07-860">Project</span></span>
- <span data-ttu-id="2ac07-861">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-861">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-862">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-862">Word</span></span>

- <div><span data-ttu-id="2ac07-863"><span>我们解决了批注回复显示顺序错误的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-863"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="2ac07-864"><span>我们解决了在某些情况下, 显示的是提示, 而不是批注的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-864"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="2ac07-865"><span>我们解决了当用户尝试添加新的批注时，修订窗格可能会显示的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-865"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="2ac07-866"><span>我们解决了可能会阻止显示“撤消”下拉列表的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-866"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="2ac07-867"><span>我们修复了有时可能会阻止添加批注的问题</span></span><span class="sxs-lookup"><span data-stu-id="2ac07-867"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="2ac07-868">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-868">July 26, 2019</span></span>
<span data-ttu-id="2ac07-869">版本 1908（内部版本 11916.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-869">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-870">新增功能：</span><span class="sxs-lookup"><span data-stu-id="2ac07-870">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="2ac07-871">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-871">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="2ac07-872">创建更易于访问的 PDF</span><span class="sxs-lookup"><span data-stu-id="2ac07-872">Create more accessible PDFs</span></span>

<span data-ttu-id="2ac07-873">创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-873">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-874">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-874">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-875">全部</span><span class="sxs-lookup"><span data-stu-id="2ac07-875">All</span></span>

- <span data-ttu-id="2ac07-876">我们修复了 Office 的文件类型关联和图标有时可能会在 Office 更新后中断的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-876">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-877">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-877">Word</span></span> 
- <span data-ttu-id="2ac07-878">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-878">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-879">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-879">Excel</span></span>
- <span data-ttu-id="2ac07-880">我们修复了移动图表有时会导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-880">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="2ac07-881">我们修复了在更改图表类型后，从图表对象中获取工作簿对象有时会导致错误的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-881">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-882">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-882">PowerPoint</span></span>
- <span data-ttu-id="2ac07-883">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-883">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-884">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-884">Outlook</span></span>
- <span data-ttu-id="2ac07-885">我们修复了在简化功能区中，禁用的控件有时不能在功能区中呈灰色显示的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-885">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-886">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-886">Access</span></span>
- <span data-ttu-id="2ac07-887">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-887">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-888">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-888">Project</span></span>
- <span data-ttu-id="2ac07-889">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-889">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="2ac07-890">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-890">July 19, 2019</span></span>
<span data-ttu-id="2ac07-891">版本 1908（内部版本 11911.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-891">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-892">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-892">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-893">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-893">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="2ac07-894">了解在 Word Online 中阅读时所遇到的首字母缩略词的含义</span><span class="sxs-lookup"><span data-stu-id="2ac07-894">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="2ac07-895">当你遇到首字母缩略词时，我们会尝试使用组织内的数据来定义它。</span><span class="sxs-lookup"><span data-stu-id="2ac07-895">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="2ac07-896">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-896">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-897">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-897">Word</span></span> 
- <span data-ttu-id="2ac07-898">我们修复了缺少 BookMarkEnd 标记的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-898">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="2ac07-899">我们修复了在用户输入特殊字符时字体选择可能发生改变的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-899">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="2ac07-900">我们修复了有时导致对新评论卡进行空白回复的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-900">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="2ac07-901">我们修复了可能导致共享电子邮件时格式设置丢失的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-901">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-902">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-902">Excel</span></span>
- <span data-ttu-id="2ac07-903">我们修复了包含大区域的数组有时可能导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-903">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="2ac07-904">我们显著提高了从已筛选区域复制数据的性能</span><span class="sxs-lookup"><span data-stu-id="2ac07-904">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="2ac07-905">我们修复了一个问题，即如果文件名包含特殊字符，则会阻止打开某些文件</span><span class="sxs-lookup"><span data-stu-id="2ac07-905">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-906">PowerPoint</span></span>
- <span data-ttu-id="2ac07-907">我们修复了一个问题，即默认情况下未为 PowerPoint 中新创建的分区选择分区名称。</span><span class="sxs-lookup"><span data-stu-id="2ac07-907">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="2ac07-908">我们修复了当使用 4:3 显示时可能导致 UI 难以使用的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-908">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-909">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-909">Outlook</span></span>
- <span data-ttu-id="2ac07-910">我们修复了可能阻止列出可用房间的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-910">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="2ac07-911">我们修复了阻止某些 POP3 用户使用 HTML 格式设置的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-911">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-912">访问</span><span class="sxs-lookup"><span data-stu-id="2ac07-912">Access</span></span>
- <span data-ttu-id="2ac07-913">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-913">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-914">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-914">Project</span></span>
- <span data-ttu-id="2ac07-915">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-915">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="2ac07-916">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-916">July 12, 2019</span></span>
<span data-ttu-id="2ac07-917">版本 1907（内部版本 11901.20038）</span><span class="sxs-lookup"><span data-stu-id="2ac07-917">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-918">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-918">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-919">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-919">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="2ac07-920">在演示文稿中使用墨迹重播</span><span class="sxs-lookup"><span data-stu-id="2ac07-920">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="2ac07-921">在 PowerPoint 中应用墨迹的重播动画，在演示文稿中表达和传达更多信息。</span><span class="sxs-lookup"><span data-stu-id="2ac07-921">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-922">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-922">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-923">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-923">Word</span></span> 
- <span data-ttu-id="2ac07-924">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-924">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-925">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-925">Excel</span></span>
- <span data-ttu-id="2ac07-926">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-926">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-927">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-927">PowerPoint</span></span>
- <span data-ttu-id="2ac07-928">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-928">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-929">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-929">Outlook</span></span>
- <span data-ttu-id="2ac07-930">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-930">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-931">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-931">Access</span></span>
- <span data-ttu-id="2ac07-932">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-932">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-933">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-933">Project</span></span>
- <span data-ttu-id="2ac07-934">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-934">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="2ac07-935">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-935">July 5, 2019</span></span>
<span data-ttu-id="2ac07-936">版本 1907（内部版本 11901.20018）</span><span class="sxs-lookup"><span data-stu-id="2ac07-936">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-937">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-937">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="2ac07-938">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-938">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="2ac07-939">粗略形状！</span><span class="sxs-lookup"><span data-stu-id="2ac07-939">Sketchy Shapes!</span></span>

<span data-ttu-id="2ac07-940">正在起草演示文稿？</span><span class="sxs-lookup"><span data-stu-id="2ac07-940">In the middle of drafting a presentation?</span></span> <span data-ttu-id="2ac07-941">你可以应用粗略样式来表明自己仍在进行此工作。</span><span class="sxs-lookup"><span data-stu-id="2ac07-941">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="2ac07-942">因此，无需转换成自由形式的手绘形状，即可为对象提供个性化风格。</span><span class="sxs-lookup"><span data-stu-id="2ac07-942">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-943">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-943">Excel</span></span>

- <span data-ttu-id="2ac07-944">**更快的文件共享**：直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-944">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2ac07-945">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-945">PowerPoint</span></span>

- <span data-ttu-id="2ac07-946">**“在讲义中打印幻灯片编号”设置已移至打印菜单，便于访问：** 选择讲义布局时，在“打印”>“打印布局”下拉菜单中选择它。</span><span class="sxs-lookup"><span data-stu-id="2ac07-946">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="2ac07-947">这也使得可以根据演示文稿轻松切换设置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-947">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="2ac07-948">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ac07-948">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="2ac07-949">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-949">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-950">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-950">Word</span></span>

- <span data-ttu-id="2ac07-951">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-951">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-952">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-952">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-953">全部</span><span class="sxs-lookup"><span data-stu-id="2ac07-953">All</span></span>
- <span data-ttu-id="2ac07-954">显著提高了功能区快捷键提示的性能</span><span class="sxs-lookup"><span data-stu-id="2ac07-954">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="2ac07-955">我们修复了阻止“查看即将推出的内容”对话框正确显示的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-955">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="2ac07-956">我们修复了可能导致“共同创作图库”浮出控件中的照片未对齐问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-956">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-957">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-957">Word</span></span> 
- <span data-ttu-id="2ac07-958">我们修复了有时可能会阻止添加新批注的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-958">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="2ac07-959">我们修复了表有时可能导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-959">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="2ac07-960">我们修复了可能会在邮件合并结尾处添加无效数据的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-960">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="2ac07-961">我们修复了可能导致某些 LaTeX 公式错误呈现的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-961">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-962">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-962">Excel</span></span>
- <span data-ttu-id="2ac07-963">我们修复了更改图表类型有时会导致运行时异常的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-963">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="2ac07-964">我们修复了在打开多个窗口时可能会显示错误功能区的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-964">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="2ac07-965">我们修复了在宏打开工作簿的第二个实例时可能会导致错误的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-965">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="2ac07-966">我们修复了在打开或创建工作簿或者在工作簿之间切换时可能导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-966">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="2ac07-967">我们修复了阻止用户打开通过 Teams 中的 Word 创建的 PDF 的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-967">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-968">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-968">PowerPoint</span></span>
- <span data-ttu-id="2ac07-969">我们修复了将图表导出到 pdf 时可能降低图表质量的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-969">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="2ac07-970">我们修复了阻止显示工具提示（用于指示与中心之间的距离）的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-970">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-971">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-971">Outlook</span></span>
- <span data-ttu-id="2ac07-972">我们修复了有时可能会阻止显示“磁盘已满”错误的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-972">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="2ac07-973">我们修复了在更新会议请求时可能会导致附件出现重复的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-973">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-974">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-974">Access</span></span>
- <span data-ttu-id="2ac07-975">我们修复了阻止某些查询返回大型整数值的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-975">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="2ac07-976">我们修复了可能使 SQL 文本框不可编辑的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-976">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="2ac07-977">我们修复了难以在一些高 DPI 显示器上查看工具提示的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-977">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-978">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-978">Project</span></span>
- <span data-ttu-id="2ac07-979">我们修复了可能导致标志值在新任务中不可编辑的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-979">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="2ac07-980">我们修复了可能导致状态更新会错误地设置工作分配和任务的实际开始日期的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-980">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="2ac07-981">我们修复了可能会导致某些资源错误地显示为过度分配的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-981">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="2ac07-982">我们修复了当添加 Lag 时、小数点分隔符为逗号时以及连接到服务器时 TaskDependencies Add 方法可能失败的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-982">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="2ac07-983">我们修复了通过 CSOM 更新本地自定义字段查找表值可能会导致 PCS 崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-983">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="2ac07-984">我们修复了总工时值包含小数时可能显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-984">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="2ac07-985">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-985">June 28, 2019</span></span>
<span data-ttu-id="2ac07-986">版本 1907（内部版本 11819.20002）</span><span class="sxs-lookup"><span data-stu-id="2ac07-986">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-987">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-987">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-988">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-988">Excel</span></span>

- <span data-ttu-id="2ac07-989">**使用 Power Query 增强功能快速编码：** 使用自动完成和语法着色快速完成代码编写。</span><span class="sxs-lookup"><span data-stu-id="2ac07-989">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="2ac07-990">也可以轻松发现函数、列和参数。</span><span class="sxs-lookup"><span data-stu-id="2ac07-990">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="2ac07-991">**在类似列上连接表：** 在比较用于合并表的列时，获取和转换 (Power Query) 现在具有近似文本匹配逻辑（也称为模糊匹配）。</span><span class="sxs-lookup"><span data-stu-id="2ac07-991">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-992">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-992">Word</span></span>

- <span data-ttu-id="2ac07-993">**合著改进：** 提高了合著时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ac07-993">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="2ac07-994">Word、Excel、PowerPoint 和 Visio</span><span class="sxs-lookup"><span data-stu-id="2ac07-994">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="2ac07-995">建议的文档</span><span class="sxs-lookup"><span data-stu-id="2ac07-995">Recommended Documents</span></span>

<span data-ttu-id="2ac07-996">查找为你推荐的相关活动的文档。</span><span class="sxs-lookup"><span data-stu-id="2ac07-996">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-997">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-997">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-998">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-998">Word</span></span> 
- <span data-ttu-id="2ac07-999">我们修复了可能阻止打开某些 .DOC 文件的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-999">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="2ac07-1000">我们修复了可能阻止正确加载批注的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1000">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1001">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1001">Excel</span></span>
- <span data-ttu-id="2ac07-1002">我们改进了 Power 查询的性能</span><span class="sxs-lookup"><span data-stu-id="2ac07-1002">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1003">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1003">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1004">我们修复了与在 Surface 设备上使用触控笔相关的问题，这可能会导致屏幕闪烁</span><span class="sxs-lookup"><span data-stu-id="2ac07-1004">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1005">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1005">Outlook</span></span>
- <span data-ttu-id="2ac07-1006">我们修复了一个问题，该问题可能会在转换为会议时更改约会的忙/闲状态</span><span class="sxs-lookup"><span data-stu-id="2ac07-1006">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="2ac07-1007">我们修复了一个问题，即当使用临时模板保护电子邮件时，将显示错误的模板和说明</span><span class="sxs-lookup"><span data-stu-id="2ac07-1007">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1008">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1008">Access</span></span>
- <span data-ttu-id="2ac07-1009">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1009">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1010">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1010">Project</span></span>
- <span data-ttu-id="2ac07-1011">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1011">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="2ac07-1012">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1012">June 21, 2019</span></span>
<span data-ttu-id="2ac07-1013">版本 1907（生成号 11815.20002）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1013">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1014">新变化：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1014">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1015">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1015">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="2ac07-1016">Outlook Desktop 中黑色主题的深色模式</span><span class="sxs-lookup"><span data-stu-id="2ac07-1016">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="2ac07-1017">在深色模式下，使用黑色主题的用户现在还可以在阅读电子邮件时看到有深色背景的阅读窗格，并在撰写电子邮件时看到有深色背景的撰写窗格。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1017">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="2ac07-1018">阅读窗格和功能区上有“太阳/月亮”切换，以防用户想要改用浅色背景来预览邮件外观。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1018">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1019">开始使用：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1019">Getting Started:</span></span>

1. <span data-ttu-id="2ac07-1020">黑色主题和深色模式默认处于启用状态。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1020">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="2ac07-1021">用户可以使用阅读窗格和功能区上的“月亮/太阳”切换，在浅色模式下预览邮件外观</span><span class="sxs-lookup"><span data-stu-id="2ac07-1021">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1022">可尝试的方案</span><span class="sxs-lookup"><span data-stu-id="2ac07-1022">Scenarios to Try</span></span>

1. <span data-ttu-id="2ac07-1023">在深色模式下阅读电子邮件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1023">Read emails in dark mode.</span></span> <span data-ttu-id="2ac07-1024">如果你无法阅读某些内容，请使用“阅读窗格”中的太阳切换按钮切换为浅色背景。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1024">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="2ac07-1025">在深色模式下撰写电子邮件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1025">Compose emails in dark mode.</span></span> <span data-ttu-id="2ac07-1026">使用功能区中的太阳切换按钮，在浅色背景下预览邮件的显示效果。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1026">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="2ac07-1027">如果遇到任何无法正常呈现的电子邮件，请将它们作为附件发送到 OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="2ac07-1027">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="2ac07-1028">获取位置建议</span><span class="sxs-lookup"><span data-stu-id="2ac07-1028">Get location suggestions</span></span>

<span data-ttu-id="2ac07-1029">开始键入内容，Outlook 将会搜索匹配的位置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1029">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="2ac07-1030">这适用于在创建约会和会议时看到的“位置”字段。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1030">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1031">开始使用：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1031">Getting Started:</span></span>

- <span data-ttu-id="2ac07-1032">在 Outlook 的 O365 或 Outlook.com 日历上创建约会或会议。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1032">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="2ac07-1033">单击“位置”字段，并开始键入内容…</span><span class="sxs-lookup"><span data-stu-id="2ac07-1033">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1034">可尝试的方案</span><span class="sxs-lookup"><span data-stu-id="2ac07-1034">Scenarios to Try</span></span>

<span data-ttu-id="2ac07-1035">向会议添加会议室时，单击“位置”字段，而不是使用“会议室查找器”加载项或通讯录。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1035">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="2ac07-1036">对于在有公共位置的实体场所（比如餐馆、咖啡店或甚至是牙医诊所）进行的约会，试着用新的选取器来查找确切位置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1036">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="2ac07-1037">这样一来，就可以在要离开时收到 Outlook Mobile 通知。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1037">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1038">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1038">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-1039">全部</span><span class="sxs-lookup"><span data-stu-id="2ac07-1039">All</span></span>
- <span data-ttu-id="2ac07-1040">修复了以下问题：搜索框在脱机时一直处于启用状态</span><span class="sxs-lookup"><span data-stu-id="2ac07-1040">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1041">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1041">Word</span></span> 
- <span data-ttu-id="2ac07-1042">修复了以下问题：键盘焦点有时难以看到</span><span class="sxs-lookup"><span data-stu-id="2ac07-1042">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="2ac07-1043">修复了以下问题：粘贴到新文档中的文本有时可能会出现错误的文本对齐方式</span><span class="sxs-lookup"><span data-stu-id="2ac07-1043">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="2ac07-1044">修复了以下问题：某些用户可能无法在暂停计算机后保存更改</span><span class="sxs-lookup"><span data-stu-id="2ac07-1044">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="2ac07-1045">修复了以下问题：在某些情况下，打印的是整个文档，而不是选定页面</span><span class="sxs-lookup"><span data-stu-id="2ac07-1045">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="2ac07-1046">修复了以下问题：批注可能会在小型显示器上难以阅读</span><span class="sxs-lookup"><span data-stu-id="2ac07-1046">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="2ac07-1047">修复了以下问题：在捕获到设备时可能会发生故障</span><span class="sxs-lookup"><span data-stu-id="2ac07-1047">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1048">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1048">Excel</span></span>
- <span data-ttu-id="2ac07-1049">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1049">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1050">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1050">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1051">修复了以下问题：键盘焦点有时难以看到</span><span class="sxs-lookup"><span data-stu-id="2ac07-1051">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1052">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1052">Outlook</span></span>
- <span data-ttu-id="2ac07-1053">修复了以下问题：禁用的加载项可能会错误地显示为已启用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1053">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="2ac07-1054">修复了以下问题：客户无法查看所有保留策略（如果有大量保留策略的话）。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1054">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1055">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1055">Access</span></span>
- <span data-ttu-id="2ac07-1056">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1056">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1057">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1057">Project</span></span>
- <span data-ttu-id="2ac07-1058">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1058">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="2ac07-1059">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1059">June 14, 2019</span></span>
<span data-ttu-id="2ac07-1060">版本 1907（内部版本 11807.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1060">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1061">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1061">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1062">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1062">Word</span></span> 
- <span data-ttu-id="2ac07-1063">我们修复了可能会阻止用户在保存到 OneDrive 时登录的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1063">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="2ac07-1064">我们修复了以下问题：在限制访问模式下，系统可能会阻止用户更改 SharePoint 属性</span><span class="sxs-lookup"><span data-stu-id="2ac07-1064">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="2ac07-1065">我们修复了在调整边距时页眉和页脚内容可能发生更改的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1065">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="2ac07-1066">我们修复了在切换到 Web 视图时格式可能会遭到破坏的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1066">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="2ac07-1067">我们修复了可能会阻止用户在从 SharePoint 打开时使用自定义字段的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1067">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1068">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1068">Excel</span></span>
- <span data-ttu-id="2ac07-1069">我们修复了在删除筛选集的行时出现的性能问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1069">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="2ac07-1070">我们修复了在受保护的视图中有时可能会导致鼠标闪烁的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1070">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="2ac07-1071">我们修复了在删除系列时可能导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1071">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="2ac07-1072">我们修复了以下问题：在没有可用版本历史记录的情况下，某些用户却可以获得用以添加该信息的选项</span><span class="sxs-lookup"><span data-stu-id="2ac07-1072">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="2ac07-1073">我们修复了在使用电子表格比较工具时可能导致异常的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1073">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1074">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1074">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1075">我们修复了在单击 SharePoint 链接时出现崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1075">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="2ac07-1076">我们修复了在使用 Surface 触控笔键入过程中可能将用户切换到下一页的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1076">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1077">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1077">Outlook</span></span>
- <span data-ttu-id="2ac07-1078">我们修复了在某些情况下“收件人”字段比正常情况更大的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1078">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1079">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1079">Access</span></span>
- <span data-ttu-id="2ac07-1080">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1080">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1081">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1081">Project</span></span>
- <span data-ttu-id="2ac07-1082">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1082">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="2ac07-1083">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1083">June 7, 2019</span></span>
<span data-ttu-id="2ac07-1084">版本 1907（内部版本 11727.20064）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1084">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1085">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1085">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1086">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1086">Word</span></span> 
- <span data-ttu-id="2ac07-1087">我们修复了 Word 在将自动更正设置为句子首字母大写时有时会发生崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1087">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="2ac07-1088">我们改进了在 SharePoint 上编辑文档时的性能</span><span class="sxs-lookup"><span data-stu-id="2ac07-1088">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="2ac07-1089">我们修复了在 Adobe Illustrator 中创建的矢量图无法正确显示的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1089">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1090">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1090">Excel</span></span>
- <span data-ttu-id="2ac07-1091">我们修复了录制宏时排序字段有时无法正确设置的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1091">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="2ac07-1092">我们解决了在重新计算数组公式过程中导致挂起或崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1092">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1093">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1093">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1094">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1094">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1095">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1095">Outlook</span></span>
- <span data-ttu-id="2ac07-1096">我们修复了内联附件有时被错误缩放的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1096">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1097">访问</span><span class="sxs-lookup"><span data-stu-id="2ac07-1097">Access</span></span>
- <span data-ttu-id="2ac07-1098">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1099">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1099">Project</span></span>
- <span data-ttu-id="2ac07-1100">我们修复了固定时间段内的时间表有时可能会改变工作完成日期的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1100">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="2ac07-1101">我们修复了从早期版本打开项目时“完成的百分比”值可能错误的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1101">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="2ac07-1102">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1102">May 31, 2019</span></span>
<span data-ttu-id="2ac07-1103">版本 1906（内部版本 11722.20008）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1103">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1104">新增功能：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1104">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1105">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1105">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="2ac07-1106">用于联系支持人员的对话框现可停靠且显示在右侧</span><span class="sxs-lookup"><span data-stu-id="2ac07-1106">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="2ac07-1107">用于联系支持人员的对话框现将显示在右侧窗格且作为停靠的窗口启动。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1107">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="2ac07-1108">电子邮件中的墨迹功能！</span><span class="sxs-lookup"><span data-stu-id="2ac07-1108">Ink in Your Email!</span></span>

<span data-ttu-id="2ac07-1109">现可在 Outlook 电子邮件中绘制图片并进行批注。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1109">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1110">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1110">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="2ac07-1111">在 Word 中打开文档链接</span><span class="sxs-lookup"><span data-stu-id="2ac07-1111">Open document links in Word</span></span>

<span data-ttu-id="2ac07-1112">单击 Office 中的文档链接时，可更新要在 Word 应用中的默认打开的首选项。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1112">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="2ac07-1113">要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1113">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2ac07-1114">了解详细信息：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2ac07-1114">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1115">开始使用：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1115">Getting Started:</span></span>

<span data-ttu-id="2ac07-1116">功能默认关闭。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1116">Feature will default to off.</span></span> <span data-ttu-id="2ac07-1117">用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1117">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2ac07-1118">当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1118">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2ac07-1119">要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1119">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2ac07-1120">“文件”->“选项”->“高级”->“链接处理”</span><span class="sxs-lookup"><span data-stu-id="2ac07-1120">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2ac07-1121">此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1121">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1122">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1122">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1123">要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 Word 文档的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1123">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2ac07-1124">选择加入后，链接将在 Win32 应用中默认启动。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1124">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1125">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="2ac07-1126">在 PowerPoint 中打开演示文稿链接</span><span class="sxs-lookup"><span data-stu-id="2ac07-1126">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="2ac07-1127">单击 Office 中的演示文稿链接时，可更新要在 PowerPoint 应用中的默认打开的首选项。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1127">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="2ac07-1128">要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1128">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2ac07-1129">了解详细信息：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2ac07-1129">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1130">开始使用：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1130">Getting Started:</span></span>

<span data-ttu-id="2ac07-1131">功能默认关闭。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1131">Feature will default to off.</span></span> <span data-ttu-id="2ac07-1132">用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1132">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2ac07-1133">当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1133">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2ac07-1134">要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1134">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2ac07-1135">“文件”->“选项”->“高级”->“链接处理”</span><span class="sxs-lookup"><span data-stu-id="2ac07-1135">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2ac07-1136">此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1136">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1137">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1137">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1138">要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 PowerPoint 演示文稿的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1138">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2ac07-1139">选择加入后，链接将在 Win32 应用中默认启动。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1139">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1140">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1140">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="2ac07-1141">在 Excel 中打开工作簿链接</span><span class="sxs-lookup"><span data-stu-id="2ac07-1141">Open workbook links in Excel</span></span>

<span data-ttu-id="2ac07-1142">单击 Office 中的工作簿链接时，可更新要在 Excel 应用中的默认打开的首选项。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1142">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="2ac07-1143">要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1143">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2ac07-1144">了解详细信息：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2ac07-1144">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1145">开始使用：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1145">Getting Started:</span></span>

<span data-ttu-id="2ac07-1146">功能默认关闭。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1146">Feature will default to off.</span></span> <span data-ttu-id="2ac07-1147">用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1147">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2ac07-1148">当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1148">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2ac07-1149">要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1149">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2ac07-1150">“文件”->“选项”->“高级”->“链接处理”</span><span class="sxs-lookup"><span data-stu-id="2ac07-1150">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2ac07-1151">此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1151">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1152">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1152">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1153">要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 Excel 工作簿的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1153">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2ac07-1154">选择加入后，链接将在 Win32 应用中默认启动。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1154">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1155">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1155">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-1156">所有</span><span class="sxs-lookup"><span data-stu-id="2ac07-1156">All</span></span>
- <span data-ttu-id="2ac07-1157">修复了即使已禁用“自动保存”，文件有时也会自动保存的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1157">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1158">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1158">Word</span></span> 
- <span data-ttu-id="2ac07-1159">修复了可能会阻止某些用户保存到 SharePoint 的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1159">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1160">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1160">Excel</span></span>
- <span data-ttu-id="2ac07-1161">修复了非活动筛选器的图标可能显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1161">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1162">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1162">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1163">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1163">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1164">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1164">Outlook</span></span>
- <span data-ttu-id="2ac07-1165">修复了某些用户在“小组日程”视图中错误地显示为“离线”的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1165">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="2ac07-1166">修复了阻止 SafeLink 分析带尾随空格的 URL 的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1166">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="2ac07-1167">修复了会议室在非工作时间之外显示为可用状态的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1167">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1168">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1168">Access</span></span>
- <span data-ttu-id="2ac07-1169">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1169">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1170">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1170">Project</span></span>
- <span data-ttu-id="2ac07-1171">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1171">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="2ac07-1172">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1172">May 24, 2019</span></span>
<span data-ttu-id="2ac07-1173">版本 1906（内部版本 11715.20002）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1173">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1174">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1174">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="2ac07-1175">用户体验更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-1175">User Experience Updates</span></span>

<span data-ttu-id="2ac07-1176">现在即将推出的更新包含简化功能区, 以及文件夹窗格、邮件列表和阅读窗格的可视刷新。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1176">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1177">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1177">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-1178">全部</span><span class="sxs-lookup"><span data-stu-id="2ac07-1178">All</span></span>

- <span data-ttu-id="2ac07-1179">我们解决了“聊天”窗格未显示的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1179">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1180">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1180">Word</span></span> 
- <span data-ttu-id="2ac07-1181">我们修复了在某些情况下 Word 可能不正确地突出显示具有语法错误的文字的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1181">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1182">Excel</span></span>
- <span data-ttu-id="2ac07-1183">我们修复了图标元素中使用了不正确的图标的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1183">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="2ac07-1184">我们修复了在已打开工作簿时可能会在 VBA 脚本中激活不正确的工作簿的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1184">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1185">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1185">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1186">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1186">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1187">Outlook</span></span>
- <span data-ttu-id="2ac07-1188">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1188">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1189">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1189">Access</span></span>
- <span data-ttu-id="2ac07-1190">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1190">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1191">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1191">Project</span></span>
- <span data-ttu-id="2ac07-1192">我们修复了在切换至任务栏后 Project 可能会崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1192">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="2ac07-1193">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1193">May 17, 2019</span></span>
<span data-ttu-id="2ac07-1194">版本 1906（内部版本 11708.20006）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1194">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1195">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1195">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1196">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1196">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="2ac07-1197">用户体验更新</span><span class="sxs-lookup"><span data-stu-id="2ac07-1197">User Experience Updates</span></span>

<span data-ttu-id="2ac07-1198">现在即将推出的更新包含简化功能区, 以及文件夹窗格、邮件列表和阅读窗格的可视刷新。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1198">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1199">入门指南：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1199">Getting Started:</span></span>

<span data-ttu-id="2ac07-1200">这些更改将成为新的默认 UI 的一部分;自12月中旬以来, 它一直对"即将推出"的切换按钮提供100% 的支持</span><span class="sxs-lookup"><span data-stu-id="2ac07-1200">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="2ac07-1201">可自定义的简化功能区</span><span class="sxs-lookup"><span data-stu-id="2ac07-1201">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="2ac07-1202">可在经典视图和简化视图之间轻松切换，还可置顶/取消置顶命令。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1202">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1203">入门指南：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1203">Getting Started:</span></span>

<span data-ttu-id="2ac07-1204">用户可以通过打开 "即将推出" (最初) 并单击功能区中的燕尾形来切换经典的多行功能和新的简化的单行功能, 从而获得简化的功能区。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1204">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1205">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1205">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1206">从经典功能区切换为简化功能区</span><span class="sxs-lookup"><span data-stu-id="2ac07-1206">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="2ac07-1207">挑选你喜欢的操作</span><span class="sxs-lookup"><span data-stu-id="2ac07-1207">Pick your favorite action</span></span>

<span data-ttu-id="2ac07-1208">不要使用“标志”和“删除”？</span><span class="sxs-lookup"><span data-stu-id="2ac07-1208">Don't use Flag and Delete?</span></span> <span data-ttu-id="2ac07-1209">“存档”或“标记为已读”呢？</span><span class="sxs-lookup"><span data-stu-id="2ac07-1209">How about Archive or Mark as Read?</span></span> <span data-ttu-id="2ac07-1210">使用你最常用的命令自定义快速操作菜单。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1210">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1211">入门指南：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1211">Getting Started:</span></span>

<span data-ttu-id="2ac07-1212">若要选择“快速操作”, 请右键单击邮件列表中的电子邮件以显示“上下文菜单”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1212">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="2ac07-1213">选择”设置快速操作“</span><span class="sxs-lookup"><span data-stu-id="2ac07-1213">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1214">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1214">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1215">将 "标记中的默认值" 和 "删除" 更改为 "存档"、"移动"、"标记为已读" 或 "无", 清理邮件列表</span><span class="sxs-lookup"><span data-stu-id="2ac07-1215">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="2ac07-1216">更紧凑还是更宽松的布局？</span><span class="sxs-lookup"><span data-stu-id="2ac07-1216">Relaxed or tighter layout?</span></span> <span data-ttu-id="2ac07-1217">由你决定</span><span class="sxs-lookup"><span data-stu-id="2ac07-1217">You choose</span></span>

<span data-ttu-id="2ac07-1218">“更紧凑的间距”让你能够决定是希望项目之间间距更大，还是希望布局更紧凑以显示更多内容。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1218">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1219">入门指南：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1219">Getting Started:</span></span>

<span data-ttu-id="2ac07-1220">"查看" 选项卡, 使用更紧凑的间距复选框——在 "消息" 组中的 "经典功能区"、"当前视图" 设置 (用于简化功能区)</span><span class="sxs-lookup"><span data-stu-id="2ac07-1220">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1221">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1221">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1222">使用 Outlook 在启用和不启用设置的情况下对电子邮件进行分类和写入。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1222">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="2ac07-1223">使用更紧凑的间距, 每页都可容纳更多的邮件, 撰写表格上的控件也会更加精简。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1223">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="2ac07-1224">使用 Onedrive 同步客户端时重复序列显示 MRU 项</span><span class="sxs-lookup"><span data-stu-id="2ac07-1224">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="2ac07-1225">通过删除 mru 条目, 实现与带云附件的 onedrive 同步客户端更好的集成, 并为同步数据启用更快的附加作为复制行为</span><span class="sxs-lookup"><span data-stu-id="2ac07-1225">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1226">入门指南：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1226">Getting Started:</span></span>

<span data-ttu-id="2ac07-1227">如果你使用 OneDrive 同步客户端, 则在附件 MRU 中将不会再看到文件重复的情况。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1227">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1228">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1228">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1229">启用 OneDrive 同步客户端并使用 Outlook 桌面版中的 "附件" 菜单</span><span class="sxs-lookup"><span data-stu-id="2ac07-1229">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="2ac07-1230">改进了多个文件夹的邮箱的共享文件夹同步</span><span class="sxs-lookup"><span data-stu-id="2ac07-1230">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="2ac07-1231">多年来同步共享邮箱时, Outlook 的最大数量限制为500文件夹。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1231">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="2ac07-1232">通过此更改, Outlook 已得到改进, 以不再遇到此500个文件夹限制的方式进行同步。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1232">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1233">入门指南：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1233">Getting Started:</span></span>

<span data-ttu-id="2ac07-1234">在邮箱中创建1000个文件夹, 让其他人访问该邮箱, 创建 "他人" 的 Outlook 配置文件, 并验证同步是否有效。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1234">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1235">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1235">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="2ac07-1236">只需删除一点</span><span class="sxs-lookup"><span data-stu-id="2ac07-1236">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1237">入门指南：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1237">Getting Started:</span></span>

<span data-ttu-id="2ac07-1238">转到 "绘图" 选项卡。选择 "橡皮擦" 下拉列表。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1238">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="2ac07-1239">选择 "小型橡皮擦" 或 "中擦除"。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1239">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1240">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1240">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1241">转到 "绘图" 选项卡。选择笔。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1241">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="2ac07-1242">绘制墨迹笔划。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1242">Draw an ink stroke.</span></span> <span data-ttu-id="2ac07-1243">选择 "橡皮擦" 下拉列表。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1243">Select the Eraser dropdown.</span></span> <span data-ttu-id="2ac07-1244">选择 "小型橡皮擦" 或 "中擦除"。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1244">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="2ac07-1245">擦除墨迹笔划中的那位。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1245">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1246">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1246">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-1247">全部</span><span class="sxs-lookup"><span data-stu-id="2ac07-1247">All</span></span> 
- <span data-ttu-id="2ac07-1248">我们已修复了可能会阻止某些用户另存为 PDF 的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1248">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="2ac07-1249">我们修复了一个问题, 该问题可能会影响用户在32位系统上保存大型文件的情况。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1249">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1250">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1250">Word</span></span> 
- <span data-ttu-id="2ac07-1251">显著提高了听写功能的响应性</span><span class="sxs-lookup"><span data-stu-id="2ac07-1251">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1252">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1252">Excel</span></span>
- <span data-ttu-id="2ac07-1253">我们修复了触摸屏设备上双击事件可能失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1253">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="2ac07-1254">我们修复了可能会阻止某些用户编辑 VBA 宏的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1254">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="2ac07-1255">我们解决了在使用切片器时可能会影响性能的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1255">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1256">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1256">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1257">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1257">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1258">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1258">Outlook</span></span>
- <span data-ttu-id="2ac07-1259">我们解决了以下问题：可能会显示所选内容错误的模板</span><span class="sxs-lookup"><span data-stu-id="2ac07-1259">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1260">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1260">Access</span></span>
- <span data-ttu-id="2ac07-1261">我们解决了以下问题: 使用 "缩放生成器" 显示长格式文本, 可能很难阅读</span><span class="sxs-lookup"><span data-stu-id="2ac07-1261">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1262">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1262">Project</span></span>
- <span data-ttu-id="2ac07-1263">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1263">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="2ac07-1264">2019 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1264">May 10, 2019</span></span>
<span data-ttu-id="2ac07-1265">版本 1906（内部版本 11702.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1265">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1266">新增功能：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1266">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1267">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1267">Outlook</span></span>

<span data-ttu-id="2ac07-1268">**在屏幕上显示更多邮件：** 选择“视图”>“使用更紧密的间距”来调整邮件之间的间距。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1268">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1269">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1269">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-1270">所有</span><span class="sxs-lookup"><span data-stu-id="2ac07-1270">All</span></span>
- <span data-ttu-id="2ac07-1271">修复了“另存为”对话框可能显示错误路径的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1271">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1272">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1272">Word</span></span> 
- <span data-ttu-id="2ac07-1273">修复了“操作说明搜索”中的某些选项无法插入的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1273">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1274">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1274">Excel</span></span>
- <span data-ttu-id="2ac07-1275">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1275">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1276">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1276">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1277">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1277">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1278">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1278">Outlook</span></span>
- <span data-ttu-id="2ac07-1279">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1279">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1280">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1280">Access</span></span>
- <span data-ttu-id="2ac07-1281">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1281">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1282">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1282">Project</span></span>
- <span data-ttu-id="2ac07-1283">修复了任务 ID 可能需要突出显示才能看到的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1283">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="2ac07-1284">2019 年 5 月 3 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1284">May 3, 2019</span></span>
<span data-ttu-id="2ac07-1285">版本 1906（内部版本 11629.20008）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1285">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1286">新增功能：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1286">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1287">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1287">Outlook</span></span>

<span data-ttu-id="2ac07-1288">**所有加密选项都在一个位置：** 只需转到“选项”>“加密”以选择如何保护电子邮件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1288">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1289">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1289">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2ac07-1290">所有</span><span class="sxs-lookup"><span data-stu-id="2ac07-1290">All</span></span>
- <span data-ttu-id="2ac07-1291">修复了一些用户在与 OneDrive for Business 同步时会遇到问题的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1291">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1292">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1292">Word</span></span> 
- <span data-ttu-id="2ac07-1293">修复了在某些情况下 Word 需要很长时间才能启动的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1293">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1294">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1294">Excel</span></span>
- <span data-ttu-id="2ac07-1295">修复了在升级到较新版本的 Excel 后，有时会从工作簿中删除外部链接的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1295">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="2ac07-1296">修复了某些用户在新工作簿中选择单元格时可能会遇到困难的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1296">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1297">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1298">修复了在将绘图转换为文本时字体大小不一致的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1298">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1299">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1299">Outlook</span></span>
- <span data-ttu-id="2ac07-1300">修复了从 .VCF 文件中保存联系人可能会导致空字段的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1300">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="2ac07-1301">修复了尽管邮件已发送，但仍可能卡在发件箱文件夹中的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1301">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="2ac07-1302">修复了在查看 DRM 邮件时 Outlook 可能会崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1302">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1303">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1303">Access</span></span>
- <span data-ttu-id="2ac07-1304">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1304">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1305">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1305">Project</span></span>
- <span data-ttu-id="2ac07-1306">修复了编辑器可能会从中文切换到英语的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1306">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="2ac07-1307">修复了未发布任务可能出现在主项目的已发布副本中的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1307">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="2ac07-1308">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1308">April 26, 2019</span></span>
<span data-ttu-id="2ac07-1309">版本 1905（内部版本 11617.20002）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1309">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="2ac07-1310">新功能</span><span class="sxs-lookup"><span data-stu-id="2ac07-1310">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1311">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1311">Outlook</span></span>

<span data-ttu-id="2ac07-1312">**共享日历更新速度更快：** 对于 Office 365 中的共享日历，Outlook 可以使用 REST API 更新这些日历。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1312">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="2ac07-1313">打开预览，更快速、更可靠地更新共享日历。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1313">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1314">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1314">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="2ac07-1315">共同创作改进</span><span class="sxs-lookup"><span data-stu-id="2ac07-1315">Coauthoring improvements</span></span>

<span data-ttu-id="2ac07-1316">通过让其他人以更接近实时的方式接收内容更改，改进了共同创作体验。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1316">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="2ac07-1317">Visio</span><span class="sxs-lookup"><span data-stu-id="2ac07-1317">Visio</span></span>

- <span data-ttu-id="2ac07-1318">**从 Power BI 导出 Visio 视觉对象：** 将 Power BI 报表导出为 PDF、PowerPoint 文件等时，Power BI 的 Visio 视觉对象现在将会正常显示。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1318">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1319">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1319">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1320">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1320">Word</span></span> 
- <span data-ttu-id="2ac07-1321">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1321">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1322">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1322">Excel</span></span>
- <span data-ttu-id="2ac07-1323">修复了规划求解宏运行失败的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1323">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="2ac07-1324">修复了可能阻止将 Excel 文件导入 SharePoint 的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1324">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1325">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1325">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1326">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1326">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1327">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1327">Outlook</span></span>
- <span data-ttu-id="2ac07-1328">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1328">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1329">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1329">Access</span></span>
- <span data-ttu-id="2ac07-1330">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1330">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1331">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1331">Project</span></span>
- <span data-ttu-id="2ac07-1332">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1332">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="2ac07-1333">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1333">April 19, 2019</span></span>
<span data-ttu-id="2ac07-1334">版本 1905（内部版本 11609.20002）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1334">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1335">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1335">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1336">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1336">Outlook</span></span>

<span data-ttu-id="2ac07-1337">**搜索某个人时获取电子邮件建议：** 在“搜索”框中键入某人姓名时，相关度最高的电子邮件信息将包含在搜索建议中。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1337">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1338">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1338">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="2ac07-1339">改进了使用数据类型的着色地图体验</span><span class="sxs-lookup"><span data-stu-id="2ac07-1339">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="2ac07-1340">对于使用 Excel 的地理数据类型绘制着色地图图表的用户而言，这是一项改进功能。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1340">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="2ac07-1341">对于最终用户而言，其优势是功能之间更丰富的集成，并提高了最终用户想要绘制的区域的准确性。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1341">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="2ac07-1342">额外优势包括绘制城市多边形的功能。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1342">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2ac07-1343">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1343">Getting Started:</span></span>

- <span data-ttu-id="2ac07-1344">此功能是对 Excel 中现有功能的改进。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1344">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="2ac07-1345">若要使用此改进功能，可将位置转换为“丰富实体”并使用着色地图绘图。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1345">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1346">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1346">Scenarios to Try:</span></span>

- <span data-ttu-id="2ac07-1347">用户可尝试绘制城市、省/市/自治区、县、国家/地区和邮政编码。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1347">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1348">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1348">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2ac07-1349">所有应用程序</span><span class="sxs-lookup"><span data-stu-id="2ac07-1349">All Applications</span></span>
- <span data-ttu-id="2ac07-1350">修复了应用程序启动时显示“首次运行”对话框的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1350">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="2ac07-1351">修复了“另存为”对话框中的 SharePoint 链接可能丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1351">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="2ac07-1352">修复了用户将误看到“立即修复”对话框的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1352">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1353">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1353">Word</span></span> 
- <span data-ttu-id="2ac07-1354">修复了一些用户在请求字体时可能会收到内存或磁盘空间不足错误的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1354">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="2ac07-1355">修复了从批注窗格切换时窗口可能丢失焦点的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1355">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1356">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1356">Excel</span></span>
- <span data-ttu-id="2ac07-1357">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1357">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1358">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1359">修复了阻止调整品牌形状大小的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1359">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="2ac07-1360">修复了 PowerPoint 在保护视图模式下打开文件时可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1360">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1361">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1361">Outlook</span></span>
- <span data-ttu-id="2ac07-1362">修复了阻止某些用户选择中文字词的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1362">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="2ac07-1363">修复了到期日期未正确计算的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1363">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1364">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1364">Access</span></span>
- <span data-ttu-id="2ac07-1365">修复了阻止某些用户使用宏生成器的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1365">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="2ac07-1366">修复了打印报告只打印第一页的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1366">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="2ac07-1367">修复了在鼠标悬停在超链接上时应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1367">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="2ac07-1368">修复了在使用关系视图时导致一些项目出现在屏幕之外的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1368">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1369">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1369">Project</span></span>
- <span data-ttu-id="2ac07-1370">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1370">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="2ac07-1371">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1371">April 12, 2019</span></span>
<span data-ttu-id="2ac07-1372">版本 1905（内部版本 11601.20042）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1372">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1373">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1373">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1374">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1374">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="2ac07-1375">使用 Microsoft Graph，更智能</span><span class="sxs-lookup"><span data-stu-id="2ac07-1375">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="2ac07-1376">导入或链接到智能数据，通过智能技术彻底改变你的桌面数据库。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1376">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1377">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1377">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2ac07-1378">所有应用程序</span><span class="sxs-lookup"><span data-stu-id="2ac07-1378">All Applications</span></span>
 - <span data-ttu-id="2ac07-1379">我们修复了一个阻止某些用户将文件保存到云端的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1379">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="2ac07-1380">我们修复了错误的窗格可以从功能区打开的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1380">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1381">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1381">Word</span></span> 
- <span data-ttu-id="2ac07-1382">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1382">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1383">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1383">Excel</span></span>
- <span data-ttu-id="2ac07-1384">我们修复了一个问题，即当工作簿不包含链接的数据类型时，用户会看到链接的数据类型的错误消息</span><span class="sxs-lookup"><span data-stu-id="2ac07-1384">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="2ac07-1385">我们修复了一个问题，即当在本地和在线查看时，Word 文档中的 URL 链接可能会发生变化</span><span class="sxs-lookup"><span data-stu-id="2ac07-1385">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1386">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1387">我们修复了从动画选项卡中撤消更改后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1387">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1388">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1388">Outlook</span></span>
- <span data-ttu-id="2ac07-1389">我们修复了阻止某些用户修改公用文件夹中联系人的“备注”字段的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1389">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="2ac07-1390">我们修复了在到期日期和删除日期之间可能发生冲突的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1390">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1391">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1391">Access</span></span>
- <span data-ttu-id="2ac07-1392">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1392">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1393">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1393">Project</span></span>
- <span data-ttu-id="2ac07-1394">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1394">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="2ac07-1395">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1395">April 5, 2019</span></span>
<span data-ttu-id="2ac07-1396">版本 1904（内部版本 11527.20014）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1396">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1397">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1397">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1398">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1398">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="2ac07-1399">Outlook for Windows：设置和共享“重点收件箱”设置</span><span class="sxs-lookup"><span data-stu-id="2ac07-1399">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="2ac07-1400">“重点收件箱”首选项存储在云中，因此，在任何计算机上使用 Outlook for Windows 和 Outlook 网页版时，可以享受相同、一致的体验。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1400">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1401">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1401">Getting Started:</span></span>

<span data-ttu-id="2ac07-1402">“文件”>“选项”>“常规”选项卡下存在“将我的 Outlook 设置存储在云中”的新首选项。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1402">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="2ac07-1403">用户需要选中该框，才能使其“重点收件箱”设置漫游到其他桌面 Outlook 安装和 OWA。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1403">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1404">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1404">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1405">在计算机上更改已启用云设置首选项的“重点收件箱”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1405">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="2ac07-1406">导航至 OWA 并查看此处应用的首选项。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1406">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="2ac07-1407">在 OWA 中更改“重点收件箱”并启动 Outlook 桌面版以查看反映的首选项。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1407">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1408">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1408">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="2ac07-1409">“学习工具”模式可提供更多页面颜色的其他支持</span><span class="sxs-lookup"><span data-stu-id="2ac07-1409">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="2ac07-1410">Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1410">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="2ac07-1411">许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1411">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1412">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1412">Getting Started:</span></span>

<span data-ttu-id="2ac07-1413">若要尝试，请转至“视图”选项卡并选择“学习工具”，然后再选择“页面颜色”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1413">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1414">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1414">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1415">若要尝试，请转至“视图”选项卡并选择“学习工具”，然后再选择“页面颜色”。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1415">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1416">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1416">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="2ac07-1417">利用动画 3D 模型提升创意</span><span class="sxs-lookup"><span data-stu-id="2ac07-1417">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="2ac07-1418">Office 现支持动画模型，这些模型可以在编辑器中播放，从而让你的表单看起来栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="2ac07-1418">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1419">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1419">Getting Started:</span></span>

1. <span data-ttu-id="2ac07-1420">打开 Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1420">Open Excel</span></span>
2. <span data-ttu-id="2ac07-1421">插入动画 3D 模型（即将在 Remix 中推出，但目前请访问以下位置的动画模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1421">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="2ac07-1422">动画模型将在编辑器中播放！</span><span class="sxs-lookup"><span data-stu-id="2ac07-1422">The animated model will play in the editor!</span></span> <span data-ttu-id="2ac07-1423">选中幻灯片放映模式 - 它也可以在此播放！</span><span class="sxs-lookup"><span data-stu-id="2ac07-1423">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="2ac07-1424">在 3D 格式功能区中，浏览此模型中的更多动画场景</span><span class="sxs-lookup"><span data-stu-id="2ac07-1424">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1425">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1425">Scenarios to Try:</span></span>

1. <span data-ttu-id="2ac07-1426">插入动画模型并在编辑器中观看该模型</span><span class="sxs-lookup"><span data-stu-id="2ac07-1426">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="2ac07-1427">通过场景库（可在 3D 格式功能区中找到）浏览动画模型中可用的动画场景</span><span class="sxs-lookup"><span data-stu-id="2ac07-1427">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="2ac07-1428">通过功能区、浮动条或空格键轻松播放/暂停动画。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1428">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1429">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1429">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2ac07-1430">所有应用程序</span><span class="sxs-lookup"><span data-stu-id="2ac07-1430">All Applications</span></span>
- <span data-ttu-id="2ac07-1431">我们修复了以下问题：Excel 的上下文菜单中的应用图标无法正常显示</span><span class="sxs-lookup"><span data-stu-id="2ac07-1431">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="2ac07-1432">我们修复了以下问题：安装更新后，“文件”菜单按钮可能会消失</span><span class="sxs-lookup"><span data-stu-id="2ac07-1432">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="2ac07-1433">我们修复了可能更改用户许可证的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1433">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1434">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1434">Word</span></span> 
- <span data-ttu-id="2ac07-1435">我们修复了以下问题：文本在某些缩放级别上无法正确呈现</span><span class="sxs-lookup"><span data-stu-id="2ac07-1435">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1436">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1436">Excel</span></span>
- <span data-ttu-id="2ac07-1437">我们修复了以下问题：在进行编辑后，系统不会提示用户保存工作簿</span><span class="sxs-lookup"><span data-stu-id="2ac07-1437">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="2ac07-1438">我们修复了以下问题：如果用户共享了工作簿，则不会触发 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1438">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="2ac07-1439">我们修复了以下问题：将列大小调整为少于 6 个像素可能会抛出不正确的错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1439">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="2ac07-1440">我们修复了以下问题：Excel 会忽略 Application.Visible 标志</span><span class="sxs-lookup"><span data-stu-id="2ac07-1440">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="2ac07-1441">我们修复了以下问题：跟踪箭头保留在非活动的冻结窗格中</span><span class="sxs-lookup"><span data-stu-id="2ac07-1441">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="2ac07-1442">我们修复了以下问题：打开工作簿时货币可能更改日期的单元格格式</span><span class="sxs-lookup"><span data-stu-id="2ac07-1442">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="2ac07-1443">我们修复了以下问题：工具提示可能意外移动</span><span class="sxs-lookup"><span data-stu-id="2ac07-1443">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="2ac07-1444">我们修复了 Power Query 编辑器的本地化问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1444">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="2ac07-1445">我们修复了以下问题：通过电子邮件发送时，工作簿将作为附件删除</span><span class="sxs-lookup"><span data-stu-id="2ac07-1445">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1446">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1446">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1447">我们修复了以下问题：复制形状的时间可能比预期要长</span><span class="sxs-lookup"><span data-stu-id="2ac07-1447">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1448">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1448">Outlook</span></span>
- <span data-ttu-id="2ac07-1449">我们修复了以下问题：使用“绘图”工具时 Outlook 可能会崩溃</span><span class="sxs-lookup"><span data-stu-id="2ac07-1449">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="2ac07-1450">我们修复了撰写 HTML 电子邮件时的本地化问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1450">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="2ac07-1451">我们修复了以下问题：用户难以选择下部窗格</span><span class="sxs-lookup"><span data-stu-id="2ac07-1451">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1452">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1452">Access</span></span>
- <span data-ttu-id="2ac07-1453">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1453">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1454">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1454">Project</span></span>
- <span data-ttu-id="2ac07-1455">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1455">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="2ac07-1456">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1456">March 22, 2019</span></span>
<span data-ttu-id="2ac07-1457">版本 1904（内部版本 11514.20004）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1457">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="2ac07-1458">新功能</span><span class="sxs-lookup"><span data-stu-id="2ac07-1458">New Features</span></span>

- <span data-ttu-id="2ac07-1459">**隐私控制：** 对诊断数据和连接体验的全新、更新和改进控制。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1459">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="2ac07-1460">了解更多<https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="2ac07-1460">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="2ac07-1461">**Office 图标具有新的外观：** Office 图标经过重新设计，可体现简单、强大和智能的 Office 体验。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1461">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1462">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1462">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1463">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1463">Word</span></span> 
- <span data-ttu-id="2ac07-1464">我们修复了 UI 会不断显示“正在检查更改”的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1464">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1465">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1465">Excel</span></span>
- <span data-ttu-id="2ac07-1466">我们修复了在移动工作表后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1466">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="2ac07-1467">我们修复了在另存为 PDF 后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1467">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="2ac07-1468">我们修复了“保存”对话框不接受某些韩语字符的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1468">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1469">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1469">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1470">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1470">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1471">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1471">Outlook</span></span>
- <span data-ttu-id="2ac07-1472">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1472">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1473">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1473">Access</span></span>
- <span data-ttu-id="2ac07-1474">我们修复了在 Access 中，创建 Access 的额外快捷方式错误消息</span><span class="sxs-lookup"><span data-stu-id="2ac07-1474">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="2ac07-1475">我们修复了所链接的 SharePoint 中数据显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1475">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1476">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1476">Project</span></span>
- <span data-ttu-id="2ac07-1477">我们解决了语言设置从中文切换到英语的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1477">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="2ac07-1478">我们修复了在同步到 SharePoint 时应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1478">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="2ac07-1479">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1479">March 15, 2019</span></span>
<span data-ttu-id="2ac07-1480">版本 1904（内部版本 11504.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1480">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1481">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1481">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1482">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1482">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="2ac07-1483">焦点模式</span><span class="sxs-lookup"><span data-stu-id="2ac07-1483">Focus Mode</span></span>

<span data-ttu-id="2ac07-1484">切换到“视图”菜单上的焦点模式，消除干扰，让你专注于工作。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1484">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="2ac07-1485">仅适用于 Office 365 订阅者。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1485">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1486">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1486">Getting Started:</span></span>

<span data-ttu-id="2ac07-1487">查看功能区状态栏中的选项卡“焦点”按钮 -“焦点”按钮</span><span class="sxs-lookup"><span data-stu-id="2ac07-1487">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1488">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1488">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1489">进入焦点模式并体验焦点体验</span><span class="sxs-lookup"><span data-stu-id="2ac07-1489">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1490">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1490">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1491">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1491">Word</span></span> 
- <span data-ttu-id="2ac07-1492">我们修复了文档中的图片另存为 PDF 时产生不正确 DPI 的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1492">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1493">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1493">Excel</span></span>
- <span data-ttu-id="2ac07-1494">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1494">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1495">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1495">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1496">我们修复了批准窗格无法正确打开或关闭的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1496">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="2ac07-1497">我们修复了在删除视频时应用程序崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1497">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="2ac07-1498">我们修复了应用程序在某些实例中无法启动的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1498">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1499">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1499">Outlook</span></span>
- <span data-ttu-id="2ac07-1500">我们修复了已读回执在日语版中显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1500">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1501">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1501">Access</span></span>
- <span data-ttu-id="2ac07-1502">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1502">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1503">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1503">Project</span></span>
- <span data-ttu-id="2ac07-1504">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1504">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="2ac07-1505">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1505">March 8, 2019</span></span> 
<span data-ttu-id="2ac07-1506">版本 1903（内部版本 11425.20036）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1506">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1507">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1507">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1508">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1508">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="2ac07-1509">通过 Microsoft 搜索找到要查找的内容</span><span class="sxs-lookup"><span data-stu-id="2ac07-1509">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="2ac07-1510">使用 Microsoft 搜索，你可以找到完成工作所需的所有文件、操作、人员和帮助。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1510">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1511">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1511">Getting Started:</span></span>

- <span data-ttu-id="2ac07-1512">此功能醒目地显示在标题界面的顶部。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1512">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1513">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1513">Scenarios to Try:</span></span>

- <span data-ttu-id="2ac07-1514">搜索学院、最近使用的文档或搜索最常用的功能区命令</span><span class="sxs-lookup"><span data-stu-id="2ac07-1514">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="2ac07-1515">查找主题以获取有关它的详细信息</span><span class="sxs-lookup"><span data-stu-id="2ac07-1515">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="2ac07-1516">CoAuthoring</span><span class="sxs-lookup"><span data-stu-id="2ac07-1516">CoAuthoring</span></span>

<span data-ttu-id="2ac07-1517">厌倦了被包含宏的文档拒之门外？</span><span class="sxs-lookup"><span data-stu-id="2ac07-1517">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="2ac07-1518">现在，OneDrive for Business 上的文档文件允许被多位创作者同时编辑。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1518">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1519">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1519">Getting Started:</span></span>

<span data-ttu-id="2ac07-1520">用户无需在 UI 中按任何按钮即可访问此功能。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1520">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="2ac07-1521">默认情况下，OneDrive for Business 文档文件已启用此功能。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1521">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="2ac07-1522">因此，用户应将文档文件保存到 OneDrive for Business 中以进行试用。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1522">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1523">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1523">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1524">在 OneDrive for Business 上创建一个文档文件，将其与同事共享，然后进行协作！</span><span class="sxs-lookup"><span data-stu-id="2ac07-1524">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1525">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1525">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1526">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1526">Word</span></span> 
- <span data-ttu-id="2ac07-1527">我们修复了在“选项”中按“ESC”时发生的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1527">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="2ac07-1528">我们修复了回复评论时发生的崩溃问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1528">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="2ac07-1529">我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1529">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1530">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1530">Excel</span></span>
- <span data-ttu-id="2ac07-1531">我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1531">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1532">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1532">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1533">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1533">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1534">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1534">Outlook</span></span>
- <span data-ttu-id="2ac07-1535">我们修复了 Outlook 搜索不按选定的时间顺序排序的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1535">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="2ac07-1536">我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1536">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="2ac07-1537">我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1537">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1538">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1538">Access</span></span>
- <span data-ttu-id="2ac07-1539">我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1539">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="2ac07-1540">我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1540">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1541">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1541">Project</span></span>
- <span data-ttu-id="2ac07-1542">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1542">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="2ac07-1543">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1543">March 1, 2019</span></span> 
<span data-ttu-id="2ac07-1544">版本 1903（内部版本 11414.20014）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1544">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1545">新增功能</span><span class="sxs-lookup"><span data-stu-id="2ac07-1545">What's New</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1546">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1546">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="2ac07-1547">修订、备注和实时同步协作的颜色</span><span class="sxs-lookup"><span data-stu-id="2ac07-1547">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="2ac07-1548">产品中的修复现在可确保以相同的颜色显示备注、修订和协作者光标。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1548">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1549">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1549">Getting Started:</span></span>

<span data-ttu-id="2ac07-1550">打开其他人已打开的 SharePoint 或 OneDrive 文档。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1550">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="2ac07-1551">验证用户的修订和备注颜色是否与用户光标的颜色匹配。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1551">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1552">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1552">Scenarios to Try:</span></span>

<span data-ttu-id="2ac07-1553">打开其他人已打开的 SharePoint 或 OneDrive 文档。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1553">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="2ac07-1554">验证用户的修订和备注颜色是否与用户光标的颜色匹配。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1554">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1555">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1555">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1556">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1556">Word</span></span> 
- <span data-ttu-id="2ac07-1557">我们修复了在“选项”中按“ESC”时发生的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1557">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="2ac07-1558">我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1558">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1559">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1559">Excel</span></span>
- <span data-ttu-id="2ac07-1560">我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1560">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1561">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1561">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1562">我们修复了在 PowerPoint 中使用 @提及功能时幻灯片图像大小的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1562">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1563">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1563">Outlook</span></span>
- <span data-ttu-id="2ac07-1564">我们修复了 Outlook 搜索不按选定的时间顺序排序的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1564">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="2ac07-1565">我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1565">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="2ac07-1566">我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1566">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1567">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1567">Access</span></span>
- <span data-ttu-id="2ac07-1568">我们更新了确认重链接表格与数据源时显示的提示文本</span><span class="sxs-lookup"><span data-stu-id="2ac07-1568">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="2ac07-1569">我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1569">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="2ac07-1570">我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1570">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1571">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1571">Project</span></span>
- <span data-ttu-id="2ac07-1572">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1572">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="2ac07-1573">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1573">February 15, 2019</span></span> 
<span data-ttu-id="2ac07-1574">版本 1903（内部版本 11310.20016）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1574">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2ac07-1575">最近更新：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1575">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1576">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1576">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="2ac07-1577">平滑切换增强功能 - 按名称平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1577">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="2ac07-1578">选择需要平滑的形状</span><span class="sxs-lookup"><span data-stu-id="2ac07-1578">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1579">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1579">Getting Started:</span></span>

- <span data-ttu-id="2ac07-1580">若要使“平滑”将两个对象视为同一对象，用户可以使用“选择窗格”来重命名形状。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1580">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="2ac07-1581">该名称必须以“!!”</span><span class="sxs-lookup"><span data-stu-id="2ac07-1581">The name must be prefaced with "!!"</span></span> <span data-ttu-id="2ac07-1582">（两个感叹号）开头，以便“平滑”使用它来覆盖默认匹配行为，例如“!!Name”</span><span class="sxs-lookup"><span data-stu-id="2ac07-1582">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="2ac07-1583">用户可以使用任何不是以“!!”开头的名称来重命名形状，</span><span class="sxs-lookup"><span data-stu-id="2ac07-1583">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="2ac07-1584">不必担心这会改变 Morph 的工作方式</span><span class="sxs-lookup"><span data-stu-id="2ac07-1584">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1585">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1585">Scenarios to Try:</span></span>

- <span data-ttu-id="2ac07-1586">在幻灯片中插入一个形状，假设它为矩形</span><span class="sxs-lookup"><span data-stu-id="2ac07-1586">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="2ac07-1587">创建新幻灯片</span><span class="sxs-lookup"><span data-stu-id="2ac07-1587">Create a new slide</span></span>
- <span data-ttu-id="2ac07-1588">在第 2 张幻灯片中插入不同的形状，假设它为三角形</span><span class="sxs-lookup"><span data-stu-id="2ac07-1588">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="2ac07-1589">打开“选择窗格”，将幻灯片 1 中的矩形重命名为“!!shape”，并将幻灯片 2 中的三角形重命名为“!!shape”</span><span class="sxs-lookup"><span data-stu-id="2ac07-1589">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="2ac07-1590">在第 2 张幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1590">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="2ac07-1591">平滑切换增强功能 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="2ac07-1591">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="2ac07-1592">具有更流畅切换效果的 SmartArt 平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1592">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1593">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1593">Getting Started:</span></span>

<span data-ttu-id="2ac07-1594">按照使用 SmartArt 的相同方式来使用平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1594">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1595">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1595">Scenarios to Try:</span></span>

- <span data-ttu-id="2ac07-1596">在幻灯片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="2ac07-1596">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="2ac07-1597">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="2ac07-1597">Duplicate the Slide</span></span>
- <span data-ttu-id="2ac07-1598">在复制的幻灯片上调整/更改/移动 SmartArt</span><span class="sxs-lookup"><span data-stu-id="2ac07-1598">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="2ac07-1599">在复制的幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1599">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="2ac07-1600">平滑切换增强功能 - 表格</span><span class="sxs-lookup"><span data-stu-id="2ac07-1600">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="2ac07-1601">具有更流畅切换效果的表格平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1601">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2ac07-1602">入门：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1602">Getting Started:</span></span>
<span data-ttu-id="2ac07-1603">按照使用表格的相同方式来使用平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1603">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1604">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1604">Scenarios to Try:</span></span>

- <span data-ttu-id="2ac07-1605">在幻灯片中插入表格</span><span class="sxs-lookup"><span data-stu-id="2ac07-1605">Insert a Table in a slide</span></span>
- <span data-ttu-id="2ac07-1606">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="2ac07-1606">Duplicate the slide</span></span>
- <span data-ttu-id="2ac07-1607">在复制的幻灯片上调整/更改/移动表格</span><span class="sxs-lookup"><span data-stu-id="2ac07-1607">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="2ac07-1608">在复制的幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="2ac07-1608">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="2ac07-1609">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="2ac07-1609">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="2ac07-1610">在帐户之间无缝切换</span><span class="sxs-lookup"><span data-stu-id="2ac07-1610">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="2ac07-1611">新的帐户管理员在一个位置显示你的所有工作和个人帐户，让你在帐户之间自如切换。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1611">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="2ac07-1612">更新后的这一体验清晰展示了你的登录方式，你现无需先退出或处理复杂的对话，即可在工作帐户和个人帐户之间切换。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1612">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="2ac07-1614">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1614">Scenarios to Try:</span></span>
- <span data-ttu-id="2ac07-1615">在帐户之间切换</span><span class="sxs-lookup"><span data-stu-id="2ac07-1615">Switch between accounts</span></span>
- <span data-ttu-id="2ac07-1616">添加新帐户[注意：你可能需要先转到“文件”|“帐户”|“已连接的服务”，然后删除与工作帐户相关的任何个人服务，反之亦然]</span><span class="sxs-lookup"><span data-stu-id="2ac07-1616">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="2ac07-1617">从帐户注销</span><span class="sxs-lookup"><span data-stu-id="2ac07-1617">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1618">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1618">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1619">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1619">Word</span></span> 
- <span data-ttu-id="2ac07-1620">我们修复了表格和图像的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1620">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1621">Excel</span></span>
- <span data-ttu-id="2ac07-1622">我们修复了自动筛选搜索字段中的文本在黑色主题中显示为白色的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1622">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="2ac07-1623">我们修复了新 Office 加载项的许可 UI 问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1623">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1624">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1624">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1625">我们修复了在笔记本电脑或平板电脑上演示幻灯片时自动扩展显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ac07-1625">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1626">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1626">Outlook</span></span>
- <span data-ttu-id="2ac07-1627">我们修复了“发送至 OneNote”按钮显示的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1627">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1628">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1628">Access</span></span>
- <span data-ttu-id="2ac07-1629">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1629">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1630">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1630">Project</span></span>
- <span data-ttu-id="2ac07-1631">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1631">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="2ac07-1632">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1632">February 11, 2019</span></span>
<span data-ttu-id="2ac07-1633">版本 1903（内部版本 11330.20014）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1633">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1634">显著修复：</span><span class="sxs-lookup"><span data-stu-id="2ac07-1634">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1635">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1635">Word</span></span> 
- <span data-ttu-id="2ac07-1636">我们已修复以下问题：一些自定义样式无法应用于 word online</span><span class="sxs-lookup"><span data-stu-id="2ac07-1636">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="2ac07-1637">我们修复了 Word 中丰富对象的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1637">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="2ac07-1638">我们修复了以下问题：粘贴列表将导致 Word 崩溃</span><span class="sxs-lookup"><span data-stu-id="2ac07-1638">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1639">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1639">Excel</span></span>
- <span data-ttu-id="2ac07-1640">我们修复了以下问题：当没有货币符号时，数字格式后不再显示附加空格</span><span class="sxs-lookup"><span data-stu-id="2ac07-1640">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="2ac07-1641">我们修复了自动检测股票的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1641">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1642">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1642">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1643">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1643">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1644">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1644">Outlook</span></span>
- <span data-ttu-id="2ac07-1645">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1645">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1646">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1646">Access</span></span>
- <span data-ttu-id="2ac07-1647">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1647">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1648">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1648">Project</span></span>
- <span data-ttu-id="2ac07-1649">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1649">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="2ac07-1650">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2ac07-1650">February 1, 2019</span></span> 
<span data-ttu-id="2ac07-1651">版本 1902（内部版本 11326.20000）</span><span class="sxs-lookup"><span data-stu-id="2ac07-1651">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="2ac07-1652">显著修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1652">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="2ac07-1653">Word</span><span class="sxs-lookup"><span data-stu-id="2ac07-1653">Word</span></span> 
- <span data-ttu-id="2ac07-1654">我们修复了在嵌入式 Excel 表格中调整单元格大小的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1654">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="2ac07-1655">我们修复了在画布中复制/粘贴形状的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1655">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="2ac07-1656">Excel</span><span class="sxs-lookup"><span data-stu-id="2ac07-1656">Excel</span></span>
- <span data-ttu-id="2ac07-1657">我们修复了从 Excel Web 应用程序中打开文件的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1657">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="2ac07-1658">我们修复了由于文件名长度而无法将 .XLSX 另存为 CSV 文件的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1658">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="2ac07-1659">我们修复了上下文菜单显示上下文菜单选项的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1659">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ac07-1660">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ac07-1660">PowerPoint</span></span>
- <span data-ttu-id="2ac07-1661">我们修复了用户无法使用键盘快捷方式 ctrl+alt+7/ctrl+alt+8 进入方括号的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1661">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="2ac07-1662">我们修复了将本地视频插入 PPT 会减少“C”驱动器磁盘空间的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1662">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="2ac07-1663">我们修复了未向某些用户显示“发布到 Microsoft Stream”按钮的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1663">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="2ac07-1664">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ac07-1664">Outlook</span></span>
- <span data-ttu-id="2ac07-1665">我们修复了日历中的任务视图未正确显示任务主题的问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1665">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="2ac07-1666">Access</span><span class="sxs-lookup"><span data-stu-id="2ac07-1666">Access</span></span>
- <span data-ttu-id="2ac07-1667">我们修复了图表的缩放比例问题</span><span class="sxs-lookup"><span data-stu-id="2ac07-1667">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="2ac07-1668">Project</span><span class="sxs-lookup"><span data-stu-id="2ac07-1668">Project</span></span>
- <span data-ttu-id="2ac07-1669">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="2ac07-1669">Various performance and stability fixes</span></span>
