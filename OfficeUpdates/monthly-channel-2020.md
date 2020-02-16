---
title: 有关 2020 年每月频道发行的发行说明
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2020 年 Office 365 专业增强版每月频道发行的发行说明
ms.openlocfilehash: 35d4a8383dcfcb81a872901337cb5f36ed6166e6
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978600"
---
# <a name="release-notes-for-monthly-channel-releases-in-2020"></a><span data-ttu-id="e5146-103">有关 2020 年每月频道发行的发行说明</span><span class="sxs-lookup"><span data-stu-id="e5146-103">Release notes for Monthly Channel releases in 2020</span></span>

<span data-ttu-id="e5146-104">这些发行说明提供了 2020 年 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 Business 的每月频道更新中所包含的新功能和非安全更新的相关信息。</span><span class="sxs-lookup"><span data-stu-id="e5146-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2020, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="e5146-105">我们经常会过一段时间就将功能（有时甚至是修补程序）发布到每月频道更新。</span><span class="sxs-lookup"><span data-stu-id="e5146-105">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span>  <span data-ttu-id="e5146-106">如果没有立即看到下述内容，则很快就会看到的。</span><span class="sxs-lookup"><span data-stu-id="e5146-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="e5146-107">了解更多</span><span class="sxs-lookup"><span data-stu-id="e5146-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="e5146-108">Office 365 专业增强版现有安装的 Microsoft Teams - 从 7 月初开始，Office 365 专业增强版（和 Office 365 商业版）的更新将包含 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="e5146-108">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in early July, updates to Office 365 ProPlus (and Office 365 Business) will include Microsoft Teams.</span></span>  <span data-ttu-id="e5146-109">将添加 Teams 的日期取决于所使用的更新频道。</span><span class="sxs-lookup"><span data-stu-id="e5146-109">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="e5146-110">有关详细信息, 请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="e5146-110">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="e5146-111">版本 2001：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="e5146-111">Version 2001: February 11</span></span>
<span data-ttu-id="e5146-112">*版本 2001（内部版本 12430.20264）*</span><span class="sxs-lookup"><span data-stu-id="e5146-112">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="e5146-113">[此处](https://docs.microsoft.com/zh-CN/officeupdates/office365-proplus-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="e5146-113">Security updates listed [here](https://docs.microsoft.com/zh-CN/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="e5146-115">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="e5146-115">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e5146-116">Access</span><span class="sxs-lookup"><span data-stu-id="e5146-116">Access</span></span>

- <span data-ttu-id="e5146-117">Access 模板将不会再导致数据库中的附件列出现故障。</span><span class="sxs-lookup"><span data-stu-id="e5146-117">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="e5146-118">在实例化模板后，你现在应该可以将附件字段添加到数据库中。</span><span class="sxs-lookup"><span data-stu-id="e5146-118">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="e5146-119">Excel</span><span class="sxs-lookup"><span data-stu-id="e5146-119">Excel</span></span>

- <span data-ttu-id="e5146-120">修复了未显示上下文菜单中的批注命令的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-120">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="e5146-121">修复了一个问题，该问题导致某些用户在将文本转换为包含单元格（具有溢出数组）的列时遇到崩溃。</span><span class="sxs-lookup"><span data-stu-id="e5146-121">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="e5146-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="e5146-122">Outlook</span></span>

- <span data-ttu-id="e5146-123">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-123">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="e5146-124">解决了导致用户在取消帐户设置时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-124">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="e5146-125">Project</span><span class="sxs-lookup"><span data-stu-id="e5146-125">Project</span></span>

- <span data-ttu-id="e5146-126">修复了以下问题：固定持续时间类型的 100％ 任务可能会错误地将其完成百分比计算为小于 100％ 完成。</span><span class="sxs-lookup"><span data-stu-id="e5146-126">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e5146-127">Office 套件</span><span class="sxs-lookup"><span data-stu-id="e5146-127">Office Suite</span></span>

- <span data-ttu-id="e5146-128">此更改解决了所报告的使用 Intel 集成 GPU 的图形适配器的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-128">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-january-30"></a><span data-ttu-id="e5146-130">版本 2001：1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="e5146-130">Version 2001: January 30</span></span>
<span data-ttu-id="e5146-131">*版本 2001（内部版本 12430.20184）*</span><span class="sxs-lookup"><span data-stu-id="e5146-131">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="e5146-133">功能更新</span><span class="sxs-lookup"><span data-stu-id="e5146-133">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="e5146-134">Excel</span><span class="sxs-lookup"><span data-stu-id="e5146-134">Excel</span></span>

- <span data-ttu-id="e5146-135">**随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。</span><span class="sxs-lookup"><span data-stu-id="e5146-135">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="e5146-136">**向左看，向右看… XLOOKUP 在此！** 使用 XLOOKUP 在表或区域中逐行查找所需内容。</span><span class="sxs-lookup"><span data-stu-id="e5146-136">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="e5146-137">了解更多</span><span class="sxs-lookup"><span data-stu-id="e5146-137">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="e5146-138">Outlook</span><span class="sxs-lookup"><span data-stu-id="e5146-138">Outlook</span></span>

- <span data-ttu-id="e5146-139">**高级组电子邮件设置：** 此功能可帮助组用户自定义要在收件箱中接收/关注的电子邮件或事件。</span><span class="sxs-lookup"><span data-stu-id="e5146-139">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="e5146-140">**组命名策略：** 组命名策略使 IT 管理员能够标准化管理组织中由用户创建的组名。</span><span class="sxs-lookup"><span data-stu-id="e5146-140">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="e5146-141">管理员可以要求在创建组时向名称添加特定前缀和后缀，并阻止使用指定的字词。</span><span class="sxs-lookup"><span data-stu-id="e5146-141">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="e5146-142">这有助于尽可能在组名中减少使用不适宜的字词，以及有助于IT部门在目录中管理组的显示方式。</span><span class="sxs-lookup"><span data-stu-id="e5146-142">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="e5146-143">命名策略还可有助于组织根据部门部署团队网站，以进行分类。</span><span class="sxs-lookup"><span data-stu-id="e5146-143">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="e5146-144">Word</span><span class="sxs-lookup"><span data-stu-id="e5146-144">Word</span></span>

- <span data-ttu-id="e5146-145">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="e5146-145">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="e5146-146">了解更多</span><span class="sxs-lookup"><span data-stu-id="e5146-146">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="e5146-147">**用套索选择墨迹：**“绘图”选项卡上的“套索”工具可帮助你选择用墨迹绘制的对象。</span><span class="sxs-lookup"><span data-stu-id="e5146-147">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="e5146-148">选择单独的笔划或整个字。</span><span class="sxs-lookup"><span data-stu-id="e5146-148">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="e5146-149">了解更多</span><span class="sxs-lookup"><span data-stu-id="e5146-149">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="e5146-150">**将形状另存为图片：** 只需单击几下即可将形状、图标或其他对象另存为图片文件，以便您将其用于其他任何位置。</span><span class="sxs-lookup"><span data-stu-id="e5146-150">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="e5146-151">了解更多</span><span class="sxs-lookup"><span data-stu-id="e5146-151">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="e5146-154">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="e5146-154">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e5146-155">Access</span><span class="sxs-lookup"><span data-stu-id="e5146-155">Access</span></span>

- <div><span data-ttu-id="e5146-156"><span style="display:inline !important;">此更新修复了使用 ADODB 的问题。VB 代码中的录制器对象可能误报告错误。&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="e5146-156"><span style="display:inline !important;">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.&nbsp;</span></span></span><br></div>


- <div style="box-sizing:border-box;"><span data-ttu-id="e5146-157"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">此更新修复了可能会导致 Microsoft Access 无法在链接的 SQL Server 表中识别“标识列”的问题，该问题可能会导致行被误报告为已删除</span></span></span><span class="sxs-lookup"><span data-stu-id="e5146-157"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly</span></span></span></span></div>


### <a name="excel"></a><span data-ttu-id="e5146-158">Excel</span><span class="sxs-lookup"><span data-stu-id="e5146-158">Excel</span></span>

- <div><span data-ttu-id="e5146-159">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-159">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="e5146-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="e5146-160">Outlook</span></span>

- <div><span data-ttu-id="e5146-161">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-161">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>


### <a name="outlookexe"></a><span data-ttu-id="e5146-162">outlook.exe</span><span class="sxs-lookup"><span data-stu-id="e5146-162">outlook.exe</span></span>

- <div><span data-ttu-id="e5146-163">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-163">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-january-22"></a><span data-ttu-id="e5146-165">版本 1912：1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="e5146-165">Version 1912: January 22</span></span>
<span data-ttu-id="e5146-166">*版本 1912（内部版本 12325.20344）*</span><span class="sxs-lookup"><span data-stu-id="e5146-166">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="e5146-168">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="e5146-168">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e5146-169">Access</span><span class="sxs-lookup"><span data-stu-id="e5146-169">Access</span></span>

- <div><span data-ttu-id="e5146-170">此更新修复了可能会导致 Microsoft Access 无法在链接的 SQL Server 表中识别“标识列”的问题，该问题可能会导致行被误报告为已删除</span><span class="sxs-lookup"><span data-stu-id="e5146-170">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly</span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-january-14"></a><span data-ttu-id="e5146-172">版本 1912：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="e5146-172">Version 1912: January 14</span></span>
<span data-ttu-id="e5146-173">*版本 1912（内部版本 12325.20298 ）*</span><span class="sxs-lookup"><span data-stu-id="e5146-173">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="e5146-174">[此处](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="e5146-174">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="e5146-175">版本 1912：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="e5146-175">Version 1912: January 08</span></span>
<span data-ttu-id="e5146-176">*版本 1912（内部版本 12325.20288）*</span><span class="sxs-lookup"><span data-stu-id="e5146-176">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="e5146-178">功能更新</span><span class="sxs-lookup"><span data-stu-id="e5146-178">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="e5146-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="e5146-179">Outlook</span></span>

- <span data-ttu-id="e5146-180">**将易访问邮件发送给最需要的人员：** Outlook 将显示邮件提示，以帮助确保在向喜欢易访问内容的用户发送邮件时可访问你的内容</span><span class="sxs-lookup"><span data-stu-id="e5146-180">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e5146-181">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e5146-181">PowerPoint</span></span>

- <span data-ttu-id="e5146-182">**全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。</span><span class="sxs-lookup"><span data-stu-id="e5146-182">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="e5146-183">**GIF 瞬间完成：** 一幻灯片、一帧。</span><span class="sxs-lookup"><span data-stu-id="e5146-183">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="e5146-184">轻松在 PowerPoint 中创建循环 GIF。</span><span class="sxs-lookup"><span data-stu-id="e5146-184">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="e5146-185">了解更多</span><span class="sxs-lookup"><span data-stu-id="e5146-185">Learn more</span></span>](https://support.office.com/zh-CN/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="e5146-188">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="e5146-188">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e5146-189">Excel</span><span class="sxs-lookup"><span data-stu-id="e5146-189">Excel</span></span>

- <span data-ttu-id="e5146-190">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-190">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="e5146-191">Outlook</span><span class="sxs-lookup"><span data-stu-id="e5146-191">Outlook</span></span>

- <span data-ttu-id="e5146-192">解决了导致会议位置在清除后意外添加回会议的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-192">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="e5146-193">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-193">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="e5146-194">解决了在某些情况下导致用户看到电子邮件发送地址与显示的 SMTP 地址不匹配的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-194">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="e5146-195">解决了导致用户在检索云设置时在 Outlook 中遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-195">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="e5146-196">Word</span><span class="sxs-lookup"><span data-stu-id="e5146-196">Word</span></span>

- <span data-ttu-id="e5146-197">构建基块管理器可能显示无效的警报：&quot;你已更改样式、构建基块&quot;。</span><span class="sxs-lookup"><span data-stu-id="e5146-197">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e5146-198">Office 套件</span><span class="sxs-lookup"><span data-stu-id="e5146-198">Office Suite</span></span>

- <span data-ttu-id="e5146-199">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="e5146-199">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

> [!NOTE]
> <span data-ttu-id="e5146-201">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="e5146-201">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
