---
title: Office 预览体验成员发行说明
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 4/5/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为“预览体验成员 - 快”受众提供关键新功能、修复程序或已知问题的最新列表
ms.openlocfilehash: a829ee5b17b51382cbb85dd7a135b271b62235fc
ms.sourcegitcommit: d4f64674c19638db73a9706b105299dc0559ea64
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/08/2019
ms.locfileid: "31516067"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="adea6-103">Office 预览体验成员发行说明</span><span class="sxs-lookup"><span data-stu-id="adea6-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="adea6-104">本文包含 Windows 桌面版的 Word、Excel、PowerPoint、Outlook、Access 和 Project 的预览体验计划内部版本的发行说明。</span><span class="sxs-lookup"><span data-stu-id="adea6-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="adea6-105">每周，我们都会提供精彩集锦，其中包含我们希望你了解的有趣新功能、重要修补程序和所有重要问题。</span><span class="sxs-lookup"><span data-stu-id="adea6-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="adea6-106">注意，我们通常会在一段时间内向预览体验成员推出功能（有时甚至包括修补程序）。</span><span class="sxs-lookup"><span data-stu-id="adea6-106">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span> <span data-ttu-id="adea6-107">这可以让我们确保将功能向更多的受众发布之前，所用功能均可正常使用。</span><span class="sxs-lookup"><span data-stu-id="adea6-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="adea6-108">因此，如果你没有看到下面所述的功能，请不要担心，你最终会获取这些功能。</span><span class="sxs-lookup"><span data-stu-id="adea6-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="adea6-109">发行说明每周发布一次，可能是多个版本的编译</span><span class="sxs-lookup"><span data-stu-id="adea6-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="adea6-110">发行说明发布日期可能与实际内部版本发布日期不一致</span><span class="sxs-lookup"><span data-stu-id="adea6-110">The release notes publication date may not match the actual build release date</span></span>

## <a name="april-5th-2019"></a><span data-ttu-id="adea6-111">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="adea6-111">April 5th, 2019</span></span>
<span data-ttu-id="adea6-112">版本 1904（内部版本 11527.20014）</span><span class="sxs-lookup"><span data-stu-id="adea6-112">Version 1904 (build 11527.20014)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="adea6-113">显著修复：</span><span class="sxs-lookup"><span data-stu-id="adea6-113">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="adea6-114">所有应用程序</span><span class="sxs-lookup"><span data-stu-id="adea6-114">All Applications</span></span>
 - <span data-ttu-id="adea6-115">我们修复了以下问题：Excel 的上下文菜单中的应用图标无法正常显示</span><span class="sxs-lookup"><span data-stu-id="adea6-115">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="adea6-116">我们修复了以下问题：安装更新后，“文件”菜单按钮可能会消失</span><span class="sxs-lookup"><span data-stu-id="adea6-116">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="adea6-117">我们修复了可能更改用户许可证的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-117">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="adea6-118">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-118">Word</span></span> 
- <span data-ttu-id="adea6-119">我们修复了以下问题：文本在某些缩放级别上无法正确呈现</span><span class="sxs-lookup"><span data-stu-id="adea6-119">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-120">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-120">Excel</span></span>
- <span data-ttu-id="adea6-121">我们修复了以下问题：在进行编辑后，系统不会提示用户保存工作簿</span><span class="sxs-lookup"><span data-stu-id="adea6-121">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="adea6-122">我们修复了以下问题：如果用户共享了工作簿，则不会触发 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="adea6-122">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="adea6-123">我们修复了以下问题：将列大小调整为少于 6 个像素可能会抛出不正确的错误消息。</span><span class="sxs-lookup"><span data-stu-id="adea6-123">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="adea6-124">我们修复了以下问题：Excel 会忽略 Application.Visible 标志</span><span class="sxs-lookup"><span data-stu-id="adea6-124">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="adea6-125">我们修复了以下问题：跟踪箭头保留在非活动的冻结窗格中</span><span class="sxs-lookup"><span data-stu-id="adea6-125">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="adea6-126">我们修复了以下问题：打开工作簿时货币可能更改日期的单元格格式</span><span class="sxs-lookup"><span data-stu-id="adea6-126">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="adea6-127">我们修复了以下问题：工具提示可能意外移动</span><span class="sxs-lookup"><span data-stu-id="adea6-127">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="adea6-128">我们修复了 Power Query 编辑器的本地化问题</span><span class="sxs-lookup"><span data-stu-id="adea6-128">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="adea6-129">我们修复了以下问题：通过电子邮件发送时，工作簿将作为附件删除</span><span class="sxs-lookup"><span data-stu-id="adea6-129">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-130">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-130">PowerPoint</span></span>
- <span data-ttu-id="adea6-131">我们修复了以下问题：复制形状的时间可能比预期要长</span><span class="sxs-lookup"><span data-stu-id="adea6-131">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-132">Outlook</span></span>
- <span data-ttu-id="adea6-133">我们修复了以下问题：使用“绘图”工具时 Outlook 可能会崩溃</span><span class="sxs-lookup"><span data-stu-id="adea6-133">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="adea6-134">我们修复了撰写 HTML 电子邮件时的本地化问题</span><span class="sxs-lookup"><span data-stu-id="adea6-134">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="adea6-135">我们修复了以下问题：用户难以选择下部窗格</span><span class="sxs-lookup"><span data-stu-id="adea6-135">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="adea6-136">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-136">Access</span></span>
- <span data-ttu-id="adea6-137">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-137">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="adea6-138">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-138">Project</span></span>
- <span data-ttu-id="adea6-139">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-139">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="adea6-140">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="adea6-140">March 22, 2019</span></span>
<span data-ttu-id="adea6-141">版本 1904（内部版本 11514.20004）</span><span class="sxs-lookup"><span data-stu-id="adea6-141">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="adea6-142">显著修复：</span><span class="sxs-lookup"><span data-stu-id="adea6-142">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="adea6-143">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-143">Word</span></span> 
- <span data-ttu-id="adea6-144">我们修复了 UI 会不断显示“正在检查更改”的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-144">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-145">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-145">Excel</span></span>
- <span data-ttu-id="adea6-146">我们修复了在移动工作表后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-146">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="adea6-147">我们修复了在另存为 PDF 后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-147">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="adea6-148">我们修复了“保存”对话框不接受某些韩语字符的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-148">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-149">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-149">PowerPoint</span></span>
- <span data-ttu-id="adea6-150">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-150">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-151">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-151">Outlook</span></span>
- <span data-ttu-id="adea6-152">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-152">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="adea6-153">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-153">Access</span></span>
- <span data-ttu-id="adea6-154">我们修复了在 Access 中，创建 Access 的额外快捷方式错误消息</span><span class="sxs-lookup"><span data-stu-id="adea6-154">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="adea6-155">我们修复了所链接的 SharePoint 中数据显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-155">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="adea6-156">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-156">Project</span></span>
- <span data-ttu-id="adea6-157">我们解决了语言设置从中文切换到英语的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-157">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="adea6-158">我们修复了在同步到 SharePoint 时应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-158">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="adea6-159">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="adea6-159">March 15, 2019</span></span>
<span data-ttu-id="adea6-160">版本 1904（内部版本 11504.20000）</span><span class="sxs-lookup"><span data-stu-id="adea6-160">Version 1904 (Build 11504.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="adea6-161">显著修复：</span><span class="sxs-lookup"><span data-stu-id="adea6-161">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="adea6-162">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-162">Word</span></span> 
- <span data-ttu-id="adea6-163">我们修复了文档中的图片另存为 PDF 时产生不正确 DPI 的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-163">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-164">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-164">Excel</span></span>
- <span data-ttu-id="adea6-165">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-165">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-166">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-166">PowerPoint</span></span>
- <span data-ttu-id="adea6-167">我们修复了批准窗格无法正确打开或关闭的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-167">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="adea6-168">我们修复了在删除视频时应用程序崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-168">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="adea6-169">我们修复了应用程序在某些实例中无法启动的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-169">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-170">Outlook</span></span>
- <span data-ttu-id="adea6-171">我们修复了已读回执在日语版中显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-171">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="adea6-172">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-172">Access</span></span>
- <span data-ttu-id="adea6-173">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-173">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="adea6-174">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-174">Project</span></span>
- <span data-ttu-id="adea6-175">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-175">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="adea6-176">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="adea6-176">March 8, 2019</span></span> 
<span data-ttu-id="adea6-177">版本 1903（内部版本 11425.20036）</span><span class="sxs-lookup"><span data-stu-id="adea6-177">Version 1903 (Build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="adea6-178">最近更新：</span><span class="sxs-lookup"><span data-stu-id="adea6-178">What's new</span></span>

### <a name="word"></a><span data-ttu-id="adea6-179">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-179">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="adea6-180">通过 Microsoft 搜索找到要查找的内容</span><span class="sxs-lookup"><span data-stu-id="adea6-180">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="adea6-181">使用 Microsoft 搜索，你可以找到完成工作所需的所有文件、操作、人员和帮助。</span><span class="sxs-lookup"><span data-stu-id="adea6-181">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="adea6-182">入门：</span><span class="sxs-lookup"><span data-stu-id="adea6-182">Getting started</span></span>

- <span data-ttu-id="adea6-183">此功能醒目地显示在标题界面的顶部。</span><span class="sxs-lookup"><span data-stu-id="adea6-183">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="adea6-184">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="adea6-184">Scenarios to Try:</span></span>

- <span data-ttu-id="adea6-185">搜索学院、最近使用的文档或搜索最常用的功能区命令</span><span class="sxs-lookup"><span data-stu-id="adea6-185">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="adea6-186">查找主题以获取有关它的详细信息</span><span class="sxs-lookup"><span data-stu-id="adea6-186">Look up a topic or subject to get more information on it</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="adea6-187">显著修复：</span><span class="sxs-lookup"><span data-stu-id="adea6-187">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="adea6-188">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-188">Word</span></span> 
- <span data-ttu-id="adea6-189">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span><span class="sxs-lookup"><span data-stu-id="adea6-189">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="adea6-190">我们修复了回复评论时发生的崩溃问题</span><span class="sxs-lookup"><span data-stu-id="adea6-190">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="adea6-191">我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题</span><span class="sxs-lookup"><span data-stu-id="adea6-191">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-192">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-192">Excel</span></span>
- <span data-ttu-id="adea6-193">我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-193">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-194">PowerPoint</span></span>
- <span data-ttu-id="adea6-195">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-195">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-196">Outlook</span></span>
- <span data-ttu-id="adea6-197">我们修复了 Outlook 搜索不按选定的时间顺序排序的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-197">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="adea6-198">我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-198">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="adea6-199">我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-199">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="adea6-200">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-200">Access</span></span>
- <span data-ttu-id="adea6-201">我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-201">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="adea6-202">我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-202">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="adea6-203">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-203">Project</span></span>
- <span data-ttu-id="adea6-204">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-204">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="adea6-205">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="adea6-205">March 1, 2019</span></span> 
<span data-ttu-id="adea6-206">版本 1903（内部版本 11414.20014）</span><span class="sxs-lookup"><span data-stu-id="adea6-206">Version 1903 (Build 11414.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="adea6-207">显著修复：</span><span class="sxs-lookup"><span data-stu-id="adea6-207">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="adea6-208">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-208">Word</span></span> 
- <span data-ttu-id="adea6-209">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span><span class="sxs-lookup"><span data-stu-id="adea6-209">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="adea6-210">我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题</span><span class="sxs-lookup"><span data-stu-id="adea6-210">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-211">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-211">Excel</span></span>
- <span data-ttu-id="adea6-212">我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-212">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-213">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-213">PowerPoint</span></span>
- <span data-ttu-id="adea6-214">我们修复了在 PowerPoint 中使用 @Mentions 提及功能时幻灯片图像大小的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-214">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-215">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-215">Outlook</span></span>
- <span data-ttu-id="adea6-216">我们修复了 Outlook 搜索不按选定的时间顺序排序的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-216">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="adea6-217">我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-217">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="adea6-218">我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-218">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="adea6-219">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-219">Access</span></span>
- <span data-ttu-id="adea6-220">我们更新了确认重链接表格与数据源时显示的提示文本</span><span class="sxs-lookup"><span data-stu-id="adea6-220">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="adea6-221">我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-221">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="adea6-222">我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-222">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="adea6-223">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-223">Project</span></span>
- <span data-ttu-id="adea6-224">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-224">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="adea6-225">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="adea6-225">February 15, 2019</span></span> 
<span data-ttu-id="adea6-226">版本 1903（内部版本 11310.20016）</span><span class="sxs-lookup"><span data-stu-id="adea6-226">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="adea6-227">最近更新：</span><span class="sxs-lookup"><span data-stu-id="adea6-227">What's new</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-228">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="adea6-229">平滑切换增强功能 - 按名称平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-229">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="adea6-230">选择需要平滑的形状</span><span class="sxs-lookup"><span data-stu-id="adea6-230">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="adea6-231">入门：</span><span class="sxs-lookup"><span data-stu-id="adea6-231">Getting started</span></span>

- <span data-ttu-id="adea6-232">若要使“平滑”将两个对象视为同一对象，用户可以使用“选择窗格”来重命名形状。</span><span class="sxs-lookup"><span data-stu-id="adea6-232">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="adea6-233">该名称必须以“!!”</span><span class="sxs-lookup"><span data-stu-id="adea6-233">The name must be prefaced with “!!”</span></span> <span data-ttu-id="adea6-234">（两个感叹号）开头，以便“平滑”使用它来覆盖默认匹配行为，例如“!!Name”</span><span class="sxs-lookup"><span data-stu-id="adea6-234">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="adea6-235">用户可以使用任何不是以“!!”开头的名称来重命名形状，</span><span class="sxs-lookup"><span data-stu-id="adea6-235">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="adea6-236">不必担心这会改变 Morph 的工作方式</span><span class="sxs-lookup"><span data-stu-id="adea6-236">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="adea6-237">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="adea6-237">Scenarios to Try:</span></span>

- <span data-ttu-id="adea6-238">在幻灯片中插入一个形状，假设它为矩形</span><span class="sxs-lookup"><span data-stu-id="adea6-238">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="adea6-239">创建新幻灯片</span><span class="sxs-lookup"><span data-stu-id="adea6-239">Create a new slide</span></span>
- <span data-ttu-id="adea6-240">在第 2 张幻灯片中插入不同的形状，假设它为三角形</span><span class="sxs-lookup"><span data-stu-id="adea6-240">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="adea6-241">打开“选择窗格”，将幻灯片 1 中的矩形重命名为“!!shape”，并将幻灯片 2 中的三角形重命名为“!!shape”</span><span class="sxs-lookup"><span data-stu-id="adea6-241">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="adea6-242">在第 2 张幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-242">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="adea6-243">平滑切换增强功能 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="adea6-243">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="adea6-244">具有更流畅切换效果的 SmartArt 平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-244">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="adea6-245">入门：</span><span class="sxs-lookup"><span data-stu-id="adea6-245">Getting started</span></span>

<span data-ttu-id="adea6-246">按照使用 SmartArt 的相同方式来使用平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-246">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="adea6-247">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="adea6-247">Scenarios to Try:</span></span>

- <span data-ttu-id="adea6-248">在幻灯片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="adea6-248">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="adea6-249">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="adea6-249">Duplicate the Slide</span></span>
- <span data-ttu-id="adea6-250">在复制的幻灯片上调整/更改/移动 SmartArt</span><span class="sxs-lookup"><span data-stu-id="adea6-250">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="adea6-251">在复制的幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-251">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="adea6-252">平滑切换增强功能 - 表格</span><span class="sxs-lookup"><span data-stu-id="adea6-252">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="adea6-253">具有更流畅切换效果的表格平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-253">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="adea6-254">入门：</span><span class="sxs-lookup"><span data-stu-id="adea6-254">Getting started</span></span>
<span data-ttu-id="adea6-255">按照使用表格的相同方式来使用平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-255">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="adea6-256">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="adea6-256">Scenarios to Try:</span></span>

- <span data-ttu-id="adea6-257">在幻灯片中插入表格</span><span class="sxs-lookup"><span data-stu-id="adea6-257">Insert a Table in a slide</span></span>
- <span data-ttu-id="adea6-258">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="adea6-258">Duplicate the slide</span></span>
- <span data-ttu-id="adea6-259">在复制的幻灯片上调整/更改/移动表格</span><span class="sxs-lookup"><span data-stu-id="adea6-259">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="adea6-260">在复制的幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="adea6-260">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="adea6-261">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="adea6-261">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="adea6-262">在帐户之间无缝切换</span><span class="sxs-lookup"><span data-stu-id="adea6-262">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="adea6-263">新的帐户管理员在一个位置显示你的所有工作和个人帐户，让你在帐户之间自如切换。</span><span class="sxs-lookup"><span data-stu-id="adea6-263">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="adea6-264">更新后的这一体验清晰展示了你的登录方式，你现无需先退出或处理复杂的对话，即可在工作帐户和个人帐户之间切换。</span><span class="sxs-lookup"><span data-stu-id="adea6-264">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="adea6-266">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="adea6-266">Scenarios to Try:</span></span>
- <span data-ttu-id="adea6-267">在帐户之间切换</span><span class="sxs-lookup"><span data-stu-id="adea6-267">Switch between accounts</span></span>
- <span data-ttu-id="adea6-268">添加新帐户[注意：你可能需要先转到“文件”|“帐户”|“已连接的服务”，然后删除与工作帐户相关的任何个人服务，反之亦然]</span><span class="sxs-lookup"><span data-stu-id="adea6-268">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="adea6-269">从帐户注销</span><span class="sxs-lookup"><span data-stu-id="adea6-269">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="adea6-270">显著修复：</span><span class="sxs-lookup"><span data-stu-id="adea6-270">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="adea6-271">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-271">Word</span></span> 
- <span data-ttu-id="adea6-272">我们修复了表格和图像的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="adea6-272">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-273">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-273">Excel</span></span>
- <span data-ttu-id="adea6-274">我们修复了自动筛选搜索字段中的文本在黑色主题中显示为白色的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-274">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="adea6-275">我们修复了新 Office 加载项的许可 UI 问题</span><span class="sxs-lookup"><span data-stu-id="adea6-275">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-276">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-276">PowerPoint</span></span>
- <span data-ttu-id="adea6-277">我们修复了在笔记本电脑或平板电脑上演示幻灯片时自动扩展显示的问题。</span><span class="sxs-lookup"><span data-stu-id="adea6-277">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-278">Outlook</span></span>
- <span data-ttu-id="adea6-279">我们修复了“发送至 OneNote”按钮显示的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-279">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="adea6-280">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-280">Access</span></span>
- <span data-ttu-id="adea6-281">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-281">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="adea6-282">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-282">Project</span></span>
- <span data-ttu-id="adea6-283">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-283">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="adea6-284">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="adea6-284">Week of February 11, 2019</span></span>
<span data-ttu-id="adea6-285">版本 1903（内部版本 11330.20014）</span><span class="sxs-lookup"><span data-stu-id="adea6-285">Version 1903 (Build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="adea6-286">显著修复：</span><span class="sxs-lookup"><span data-stu-id="adea6-286">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="adea6-287">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-287">Word</span></span> 
- <span data-ttu-id="adea6-288">我们已修复以下问题：一些自定义样式无法应用于 word online</span><span class="sxs-lookup"><span data-stu-id="adea6-288">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="adea6-289">我们修复了 Word 中丰富对象的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="adea6-289">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="adea6-290">我们修复了以下问题：粘贴列表将导致 Word 崩溃</span><span class="sxs-lookup"><span data-stu-id="adea6-290">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-291">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-291">Excel</span></span>
- <span data-ttu-id="adea6-292">我们修复了以下问题：当没有货币符号时，数字格式后不再显示附加空格</span><span class="sxs-lookup"><span data-stu-id="adea6-292">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="adea6-293">我们修复了自动检测股票的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-293">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-294">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-294">PowerPoint</span></span>
- <span data-ttu-id="adea6-295">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-295">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-296">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-296">Outlook</span></span>
- <span data-ttu-id="adea6-297">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-297">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="adea6-298">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-298">Access</span></span>
- <span data-ttu-id="adea6-299">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-299">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="adea6-300">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-300">Project</span></span>
- <span data-ttu-id="adea6-301">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-301">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="adea6-302">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="adea6-302">February 1, 2019</span></span> 
<span data-ttu-id="adea6-303">版本 1902（内部版本 11326.20000）</span><span class="sxs-lookup"><span data-stu-id="adea6-303">Version 1902 (Build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="adea6-304">显著修复</span><span class="sxs-lookup"><span data-stu-id="adea6-304">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="adea6-305">Word</span><span class="sxs-lookup"><span data-stu-id="adea6-305">Word</span></span> 
- <span data-ttu-id="adea6-306">我们修复了在嵌入式 Excel 表格中调整单元格大小的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-306">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="adea6-307">我们修复了在画布中复制/粘贴形状的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-307">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="adea6-308">Excel</span><span class="sxs-lookup"><span data-stu-id="adea6-308">Excel</span></span>
- <span data-ttu-id="adea6-309">我们修复了从 Excel Web 应用程序中打开文件的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-309">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="adea6-310">我们修复了由于文件名长度而无法将 .XLSX 另存为 CSV 文件的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-310">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="adea6-311">我们修复了上下文菜单显示上下文菜单选项的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-311">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="adea6-312">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="adea6-312">PowerPoint</span></span>
- <span data-ttu-id="adea6-313">我们修复了用户无法使用键盘快捷方式 ctrl+alt+7/ctrl+alt+8 进入方括号的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-313">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="adea6-314">我们修复了将本地视频插入 PPT 会减少“C”驱动器磁盘空间的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-314">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="adea6-315">我们修复了未向某些用户显示“发布到 Microsoft Stream”按钮的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-315">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="adea6-316">Outlook</span><span class="sxs-lookup"><span data-stu-id="adea6-316">Outlook</span></span>
- <span data-ttu-id="adea6-317">我们修复了日历中的任务视图未正确显示任务主题的问题</span><span class="sxs-lookup"><span data-stu-id="adea6-317">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="adea6-318">Access</span><span class="sxs-lookup"><span data-stu-id="adea6-318">Access</span></span>
- <span data-ttu-id="adea6-319">我们修复了图表的缩放比例问题</span><span class="sxs-lookup"><span data-stu-id="adea6-319">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="adea6-320">Project</span><span class="sxs-lookup"><span data-stu-id="adea6-320">Project</span></span>
- <span data-ttu-id="adea6-321">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="adea6-321">Various performance and stability fixes</span></span>
