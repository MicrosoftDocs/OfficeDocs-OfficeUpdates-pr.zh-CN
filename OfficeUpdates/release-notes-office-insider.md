---
title: Office 预览体验成员发行说明
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 6/14/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为“预览体验成员 - 快”受众提供关键新功能、修复程序或已知问题的最新列表
ms.openlocfilehash: 8a2bf54f60b7d35a0f3b2f023e0100ff65d09ed2
ms.sourcegitcommit: 288bea365b4c0265fb9ff182b19ff4eb30b4c7d7
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/14/2019
ms.locfileid: "34948788"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="6e3b8-103">Office 预览体验成员发行说明</span><span class="sxs-lookup"><span data-stu-id="6e3b8-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="6e3b8-104">本文包含 Windows 桌面版的 Word、Excel、PowerPoint、Outlook、Access 和 Project 的预览体验计划内部版本的发行说明。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="6e3b8-105">每周，我们都会提供精彩集锦，其中包含我们希望你了解的有趣新功能、重要修补程序和所有重要问题。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="6e3b8-106">注意，我们通常会在一段时间内向预览体验成员推出功能（有时甚至包括修补程序）。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="6e3b8-107">这可以让我们确保将功能向更多的受众发布之前，所用功能均可正常使用。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="6e3b8-108">因此，如果你没有看到下面所述的功能，请不要担心，你最终会获取这些功能。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="6e3b8-109">发行说明每周发布一次，可能是多个版本的编译</span><span class="sxs-lookup"><span data-stu-id="6e3b8-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="6e3b8-110">发行说明发布日期可能与实际内部版本发布日期不一致</span><span class="sxs-lookup"><span data-stu-id="6e3b8-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="6e3b8-111">Office 365 专业增强版现有安装的 Microsoft Teams - 从6月底开始, 将在更新这些安装的 Office 365 专业增强版 (和 Office 365 Business) 现有安装中包含 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="6e3b8-112">将添加 Teams 的日期取决于所使用的更新频道。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="6e3b8-113">有关详细信息，请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](https://docs.microsoft.com/zh-CN/deployoffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-14-2019"></a><span data-ttu-id="6e3b8-114">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-114">June 14, 2019</span></span>
<span data-ttu-id="6e3b8-115">版本 1907（内部版本 11807.20000）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-115">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-116">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-116">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-117">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-117">Word</span></span> 
- <span data-ttu-id="6e3b8-118">我们修复了可能会阻止用户在保存到 OneDrive 时登录的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-118">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="6e3b8-119">我们修复了以下问题：在限制访问模式下，系统可能会阻止用户更改 SharePoint 属性</span><span class="sxs-lookup"><span data-stu-id="6e3b8-119">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="6e3b8-120">我们修复了在调整边距时页眉和页脚内容可能发生更改的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-120">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="6e3b8-121">我们修复了在切换到 Web 视图时格式可能会遭到破坏的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-121">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="6e3b8-122">我们修复了可能会阻止用户在从 SharePoint 打开时使用自定义字段的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-122">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-123">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-123">Excel</span></span>
- <span data-ttu-id="6e3b8-124">我们修复了在删除筛选集的行时出现的性能问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-124">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="6e3b8-125">我们修复了在受保护的视图中有时可能会导致鼠标闪烁的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-125">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="6e3b8-126">我们修复了在删除系列时可能导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-126">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="6e3b8-127">我们修复了以下问题：在没有可用版本历史记录的情况下，某些用户却可以获得用以添加该信息的选项</span><span class="sxs-lookup"><span data-stu-id="6e3b8-127">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="6e3b8-128">我们修复了在使用电子表格比较工具时可能导致异常的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-128">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-129">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-130">我们修复了在单击 SharePoint 链接时出现崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-130">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="6e3b8-131">我们修复了在使用 Surface 触控笔键入过程中可能将用户切换到下一页的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-131">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-132">Outlook</span></span>
- <span data-ttu-id="6e3b8-133">我们修复了在某些情况下“收件人”字段比正常情况更大的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-133">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-134">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-134">Access</span></span>
- <span data-ttu-id="6e3b8-135">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-135">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-136">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-136">Project</span></span>
- <span data-ttu-id="6e3b8-137">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-137">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="6e3b8-138">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-138">June 7, 2019</span></span>
<span data-ttu-id="6e3b8-139">版本 1907（内部版本 11727.20064）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-139">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-140">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-140">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-141">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-141">Word</span></span> 
- <span data-ttu-id="6e3b8-142">我们修复了 Word 在将自动更正设置为句子首字母大写时有时会发生崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-142">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="6e3b8-143">我们改进了在 SharePoint 上编辑文档时的性能</span><span class="sxs-lookup"><span data-stu-id="6e3b8-143">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="6e3b8-144">我们修复了在 Adobe Illustrator 中创建的矢量图无法正确显示的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-144">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-145">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-145">Excel</span></span>
- <span data-ttu-id="6e3b8-146">我们修复了录制宏时排序字段有时无法正确设置的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-146">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="6e3b8-147">我们解决了在重新计算数组公式过程中导致挂起或崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-147">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-148">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-148">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-149">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-149">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-150">Outlook</span></span>
- <span data-ttu-id="6e3b8-151">我们修复了内联附件有时被错误缩放的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-151">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-152">访问</span><span class="sxs-lookup"><span data-stu-id="6e3b8-152">Access</span></span>
- <span data-ttu-id="6e3b8-153">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-153">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-154">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-154">Project</span></span>
- <span data-ttu-id="6e3b8-155">我们修复了固定时间段内的时间表有时可能会改变工作完成日期的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-155">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="6e3b8-156">我们修复了从早期版本打开项目时“完成的百分比”值可能错误的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-156">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="6e3b8-157">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-157">May 31, 2019</span></span>
<span data-ttu-id="6e3b8-158">版本 1906（内部版本 11722.20008）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-158">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-159">新增功能：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-159">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-160">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="6e3b8-161">用于联系支持人员的对话框现可停靠且显示在右侧</span><span class="sxs-lookup"><span data-stu-id="6e3b8-161">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="6e3b8-162">用于联系支持人员的对话框现将显示在右侧窗格且作为停靠的窗口启动。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-162">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="6e3b8-163">电子邮件中的墨迹功能！</span><span class="sxs-lookup"><span data-stu-id="6e3b8-163">Ink in Your Email!</span></span>

<span data-ttu-id="6e3b8-164">现可在 Outlook 电子邮件中绘制图片并进行批注。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-164">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-165">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-165">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="6e3b8-166">在 Word 中打开文档链接</span><span class="sxs-lookup"><span data-stu-id="6e3b8-166">Open document links in Word</span></span>

<span data-ttu-id="6e3b8-167">单击 Office 中的文档链接时，可更新要在 Word 应用中的默认打开的首选项。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-167">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="6e3b8-168">要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-168">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="6e3b8-169">了解详细信息：https://support.office.com/zh-CN/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="6e3b8-169">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-170">开始使用：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-170">Getting Started:</span></span>

<span data-ttu-id="6e3b8-171">功能默认关闭。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-171">Feature will default to off.</span></span> <span data-ttu-id="6e3b8-172">用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-172">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="6e3b8-173">当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-173">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="6e3b8-174">要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-174">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="6e3b8-175">“文件”->“选项”->“高级”->“链接处理”</span><span class="sxs-lookup"><span data-stu-id="6e3b8-175">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="6e3b8-176">此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-176">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-177">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-177">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-178">要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 Word 文档的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-178">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="6e3b8-179">选择加入后，链接将在 Win32 应用中默认启动。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-179">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-180">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="6e3b8-181">在 PowerPoint 中打开演示文稿链接</span><span class="sxs-lookup"><span data-stu-id="6e3b8-181">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="6e3b8-182">单击 Office 中的演示文稿链接时，可更新要在 PowerPoint 应用中的默认打开的首选项。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-182">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="6e3b8-183">要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-183">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="6e3b8-184">了解详细信息：https://support.office.com/zh-CN/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="6e3b8-184">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-185">开始使用：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-185">Getting Started:</span></span>

<span data-ttu-id="6e3b8-186">功能默认关闭。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-186">Feature will default to off.</span></span> <span data-ttu-id="6e3b8-187">用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-187">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="6e3b8-188">当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-188">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="6e3b8-189">要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-189">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="6e3b8-190">“文件”->“选项”->“高级”->“链接处理”</span><span class="sxs-lookup"><span data-stu-id="6e3b8-190">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="6e3b8-191">此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-191">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-192">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-192">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-193">要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 PowerPoint 演示文稿的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-193">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="6e3b8-194">选择加入后，链接将在 Win32 应用中默认启动。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-194">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-195">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-195">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="6e3b8-196">在 Excel 中打开工作簿链接</span><span class="sxs-lookup"><span data-stu-id="6e3b8-196">Open the workbook in Excel.</span></span>

<span data-ttu-id="6e3b8-197">单击 Office 中的工作簿链接时，可更新要在 Excel 应用中的默认打开的首选项。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-197">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="6e3b8-198">要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-198">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="6e3b8-199">了解详细信息：https://support.office.com/zh-CN/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="6e3b8-199">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-200">开始使用：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-200">Getting Started:</span></span>

<span data-ttu-id="6e3b8-201">功能默认关闭。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-201">Feature will default to off.</span></span> <span data-ttu-id="6e3b8-202">用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-202">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="6e3b8-203">当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-203">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="6e3b8-204">要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-204">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="6e3b8-205">“文件”->“选项”->“高级”->“链接处理”</span><span class="sxs-lookup"><span data-stu-id="6e3b8-205">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="6e3b8-206">此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-206">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-207">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-207">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-208">要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 Excel 工作簿的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-208">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="6e3b8-209">选择加入后，链接将在 Win32 应用中默认启动。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-209">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-210">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-210">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="6e3b8-211">所有</span><span class="sxs-lookup"><span data-stu-id="6e3b8-211">All</span></span>
- <span data-ttu-id="6e3b8-212">修复了即使已禁用“自动保存”，文件有时也会自动保存的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-212">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-213">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-213">Word</span></span> 
- <span data-ttu-id="6e3b8-214">修复了可能会阻止某些用户保存到 SharePoint 的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-214">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-215">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-215">Excel</span></span>
- <span data-ttu-id="6e3b8-216">修复了非活动筛选器的图标可能显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-216">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-217">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-218">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-218">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-219">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-219">Outlook</span></span>
- <span data-ttu-id="6e3b8-220">修复了某些用户在“小组日程”视图中错误地显示为“离线”的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-220">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="6e3b8-221">修复了阻止 SafeLink 分析带尾随空格的 URL 的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-221">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="6e3b8-222">修复了会议室在非工作时间之外显示为可用状态的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-222">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-223">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-223">Access</span></span>
- <span data-ttu-id="6e3b8-224">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-224">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-225">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-225">Project</span></span>
- <span data-ttu-id="6e3b8-226">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-226">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="6e3b8-227">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-227">May 24, 2019</span></span>
<span data-ttu-id="6e3b8-228">版本 1906（内部版本 11715.20002）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-228">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-229">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-229">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="6e3b8-230">用户体验更新</span><span class="sxs-lookup"><span data-stu-id="6e3b8-230">User Experience Updates</span></span>

<span data-ttu-id="6e3b8-231">现在即将推出的更新包含简化功能区, 以及文件夹窗格、邮件列表和阅读窗格的可视刷新。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-231">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-232">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-232">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="6e3b8-233">全部</span><span class="sxs-lookup"><span data-stu-id="6e3b8-233">All</span></span>

- <span data-ttu-id="6e3b8-234">我们解决了“聊天”窗格未显示的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-234">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-235">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-235">Word</span></span> 
- <span data-ttu-id="6e3b8-236">我们修复了在某些情况下 Word 可能不正确地突出显示具有语法错误的文字的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-236">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-237">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-237">Excel</span></span>
- <span data-ttu-id="6e3b8-238">我们修复了图标元素中使用了不正确的图标的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-238">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="6e3b8-239">我们修复了在已打开工作簿时可能会在 VBA 脚本中激活不正确的工作簿的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-239">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-240">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-240">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-241">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-241">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-242">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-242">Outlook</span></span>
- <span data-ttu-id="6e3b8-243">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-243">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-244">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-244">Access</span></span>
- <span data-ttu-id="6e3b8-245">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-245">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-246">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-246">Project</span></span>
- <span data-ttu-id="6e3b8-247">我们修复了在切换至任务栏后 Project 可能会崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-247">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="6e3b8-248">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-248">May 17, 2019</span></span>
<span data-ttu-id="6e3b8-249">版本 1906（内部版本 11708.20006）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-249">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-250">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-250">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-251">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-251">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="6e3b8-252">用户体验更新</span><span class="sxs-lookup"><span data-stu-id="6e3b8-252">User Experience Updates</span></span>

<span data-ttu-id="6e3b8-253">现在即将推出的更新包含简化功能区, 以及文件夹窗格、邮件列表和阅读窗格的可视刷新。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-253">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-254">入门指南：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-254">Getting Started:</span></span>

<span data-ttu-id="6e3b8-255">这些更改将成为新的默认 UI 的一部分;自12月中旬以来, 它一直对"即将推出"的切换按钮提供100% 的支持</span><span class="sxs-lookup"><span data-stu-id="6e3b8-255">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="6e3b8-256">可自定义的简化功能区</span><span class="sxs-lookup"><span data-stu-id="6e3b8-256">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="6e3b8-257">可在经典视图和简化视图之间轻松切换，还可置顶/取消置顶命令。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-257">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-258">入门指南：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-258">Getting Started:</span></span>

<span data-ttu-id="6e3b8-259">用户可以通过打开 "即将推出" (最初) 并单击功能区中的燕尾形来切换经典的多行功能和新的简化的单行功能, 从而获得简化的功能区。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-259">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-260">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-260">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-261">从经典功能区切换为简化功能区</span><span class="sxs-lookup"><span data-stu-id="6e3b8-261">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="6e3b8-262">挑选你喜欢的操作</span><span class="sxs-lookup"><span data-stu-id="6e3b8-262">Pick your favorite action</span></span>

<span data-ttu-id="6e3b8-263">不要使用“标志”和“删除”？</span><span class="sxs-lookup"><span data-stu-id="6e3b8-263">Don't use Flag and Delete?</span></span> <span data-ttu-id="6e3b8-264">“存档”或“标记为已读”呢？</span><span class="sxs-lookup"><span data-stu-id="6e3b8-264">How about Archive or Mark as Read?</span></span> <span data-ttu-id="6e3b8-265">使用你最常用的命令自定义快速操作菜单。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-265">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-266">入门指南：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-266">Getting Started:</span></span>

<span data-ttu-id="6e3b8-267">若要选择“快速操作”, 请右键单击邮件列表中的电子邮件以显示“上下文菜单”。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-267">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="6e3b8-268">选择”设置快速操作“</span><span class="sxs-lookup"><span data-stu-id="6e3b8-268">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-269">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-269">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-270">将 "标记中的默认值" 和 "删除" 更改为 "存档"、"移动"、"标记为已读" 或 "无", 清理邮件列表</span><span class="sxs-lookup"><span data-stu-id="6e3b8-270">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="6e3b8-271">更紧凑还是更宽松的布局？</span><span class="sxs-lookup"><span data-stu-id="6e3b8-271">Relaxed or tighter layout?</span></span> <span data-ttu-id="6e3b8-272">由你决定</span><span class="sxs-lookup"><span data-stu-id="6e3b8-272">You choose</span></span>

<span data-ttu-id="6e3b8-273">“更紧凑的间距”让你能够决定是希望项目之间间距更大，还是希望布局更紧凑以显示更多内容。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-273">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-274">入门指南：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-274">Getting Started:</span></span>

<span data-ttu-id="6e3b8-275">"查看" 选项卡, 使用更紧凑的间距复选框——在 "消息" 组中的 "经典功能区"、"当前视图" 设置 (用于简化功能区)</span><span class="sxs-lookup"><span data-stu-id="6e3b8-275">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-276">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-276">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-277">使用 Outlook 在启用和不启用设置的情况下对电子邮件进行分类和写入。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-277">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="6e3b8-278">使用更紧凑的间距, 每页都可容纳更多的邮件, 撰写表格上的控件也会更加精简。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-278">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="6e3b8-279">使用 Onedrive 同步客户端时重复序列显示 MRU 项</span><span class="sxs-lookup"><span data-stu-id="6e3b8-279">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="6e3b8-280">通过删除 mru 条目, 实现与带云附件的 onedrive 同步客户端更好的集成, 并为同步数据启用更快的附加作为复制行为</span><span class="sxs-lookup"><span data-stu-id="6e3b8-280">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-281">入门指南：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-281">Getting Started:</span></span>

<span data-ttu-id="6e3b8-282">如果你使用 OneDrive 同步客户端, 则在附件 MRU 中将不会再看到文件重复的情况。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-282">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-283">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-283">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-284">启用 OneDrive 同步客户端并使用 Outlook 桌面版中的 "附件" 菜单</span><span class="sxs-lookup"><span data-stu-id="6e3b8-284">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="6e3b8-285">改进了多个文件夹的邮箱的共享文件夹同步</span><span class="sxs-lookup"><span data-stu-id="6e3b8-285">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="6e3b8-286">多年来同步共享邮箱时, Outlook 的最大数量限制为500文件夹。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-286">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="6e3b8-287">通过此更改, Outlook 已得到改进, 以不再遇到此500个文件夹限制的方式进行同步。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-287">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-288">入门指南：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-288">Getting Started:</span></span>

<span data-ttu-id="6e3b8-289">在邮箱中创建1000个文件夹, 让其他人访问该邮箱, 创建 "他人" 的 Outlook 配置文件, 并验证同步是否有效。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-289">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-290">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-290">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="6e3b8-291">只需删除一点</span><span class="sxs-lookup"><span data-stu-id="6e3b8-291">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-292">入门指南：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-292">Getting Started:</span></span>

<span data-ttu-id="6e3b8-293">转到 "绘图" 选项卡。选择 "橡皮擦" 下拉列表。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-293">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="6e3b8-294">选择 "小型橡皮擦" 或 "中擦除"。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-294">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-295">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-295">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-296">转到 "绘图" 选项卡。选择笔。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-296">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="6e3b8-297">绘制墨迹笔划。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-297">Draw an ink stroke.</span></span> <span data-ttu-id="6e3b8-298">选择 "橡皮擦" 下拉列表。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-298">Select the Eraser dropdown.</span></span> <span data-ttu-id="6e3b8-299">选择 "小型橡皮擦" 或 "中擦除"。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-299">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="6e3b8-300">擦除墨迹笔划中的那位。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-300">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-301">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-301">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="6e3b8-302">全部</span><span class="sxs-lookup"><span data-stu-id="6e3b8-302">All</span></span> 
- <span data-ttu-id="6e3b8-303">我们已修复了可能会阻止某些用户另存为 PDF 的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-303">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="6e3b8-304">我们修复了一个问题, 该问题可能会影响用户在32位系统上保存大型文件的情况。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-304">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-305">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-305">Word</span></span> 
- <span data-ttu-id="6e3b8-306">显著提高了听写功能的响应性</span><span class="sxs-lookup"><span data-stu-id="6e3b8-306">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-307">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-307">Excel</span></span>
- <span data-ttu-id="6e3b8-308">我们修复了触摸屏设备上双击事件可能失败的问题。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-308">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="6e3b8-309">我们修复了可能会阻止某些用户编辑 VBA 宏的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-309">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="6e3b8-310">我们解决了在使用切片器时可能会影响性能的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-310">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-311">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-312">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-312">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-313">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-313">Outlook</span></span>
- <span data-ttu-id="6e3b8-314">我们解决了以下问题：可能会显示所选内容错误的模板</span><span class="sxs-lookup"><span data-stu-id="6e3b8-314">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-315">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-315">Access</span></span>
- <span data-ttu-id="6e3b8-316">我们解决了以下问题: 使用 "缩放生成器" 显示长格式文本, 可能很难阅读</span><span class="sxs-lookup"><span data-stu-id="6e3b8-316">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-317">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-317">Project</span></span>
- <span data-ttu-id="6e3b8-318">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-318">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="6e3b8-319">2019 年 5 月 10 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-319">May 10, 2019</span></span>
<span data-ttu-id="6e3b8-320">版本 1906（内部版本 11702.20000）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-320">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-321">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-321">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="6e3b8-322">所有</span><span class="sxs-lookup"><span data-stu-id="6e3b8-322">All</span></span>
- <span data-ttu-id="6e3b8-323">修复了“另存为”对话框可能显示错误路径的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-323">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-324">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-324">Word</span></span> 
- <span data-ttu-id="6e3b8-325">修复了“操作说明搜索”中的某些选项无法插入的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-325">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-326">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-326">Excel</span></span>
- <span data-ttu-id="6e3b8-327">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-327">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-328">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-329">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-329">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-330">Outlook</span></span>
- <span data-ttu-id="6e3b8-331">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-331">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-332">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-332">Access</span></span>
- <span data-ttu-id="6e3b8-333">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-333">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-334">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-334">Project</span></span>
- <span data-ttu-id="6e3b8-335">修复了任务 ID 可能需要突出显示才能看到的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-335">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="6e3b8-336">2019 年 5 月 3 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-336">May 3, 2019</span></span>
<span data-ttu-id="6e3b8-337">版本 1906（内部版本 11629.20008）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-337">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-338">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-338">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="6e3b8-339">所有</span><span class="sxs-lookup"><span data-stu-id="6e3b8-339">All</span></span>
- <span data-ttu-id="6e3b8-340">修复了一些用户在与 OneDrive for Business 同步时会遇到问题的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-340">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-341">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-341">Word</span></span> 
- <span data-ttu-id="6e3b8-342">修复了在某些情况下 Word 需要很长时间才能启动的问题。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-342">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-343">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-343">Excel</span></span>
- <span data-ttu-id="6e3b8-344">修复了在升级到较新版本的 Excel 后，有时会从工作簿中删除外部链接的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-344">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="6e3b8-345">修复了某些用户在新工作簿中选择单元格时可能会遇到困难的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-345">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-346">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-346">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-347">修复了在将绘图转换为文本时字体大小不一致的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-347">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-348">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-348">Outlook</span></span>
- <span data-ttu-id="6e3b8-349">修复了从 .VCF 文件中保存联系人可能会导致空字段的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-349">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="6e3b8-350">修复了尽管邮件已发送，但仍可能卡在发件箱文件夹中的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-350">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="6e3b8-351">修复了在查看 DRM 邮件时 Outlook 可能会崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-351">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-352">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-352">Access</span></span>
- <span data-ttu-id="6e3b8-353">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-353">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-354">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-354">Project</span></span>
- <span data-ttu-id="6e3b8-355">修复了编辑器可能会从中文切换到英语的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-355">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="6e3b8-356">修复了未发布任务可能出现在主项目的已发布副本中的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-356">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="6e3b8-357">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-357">April 26, 2019</span></span>
<span data-ttu-id="6e3b8-358">版本 1905（内部版本 11617.20002）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-358">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-359">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-359">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-360">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-360">Word</span></span> 
- <span data-ttu-id="6e3b8-361">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-361">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-362">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-362">Excel</span></span>
- <span data-ttu-id="6e3b8-363">修复了规划求解宏运行失败的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-363">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="6e3b8-364">修复了可能阻止将 Excel 文件导入 SharePoint 的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-364">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-365">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-365">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-366">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-366">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-367">Outlook</span></span>
- <span data-ttu-id="6e3b8-368">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-368">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-369">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-369">Access</span></span>
- <span data-ttu-id="6e3b8-370">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-370">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-371">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-371">Project</span></span>
- <span data-ttu-id="6e3b8-372">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-372">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="6e3b8-373">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-373">April 19, 2019</span></span>
<span data-ttu-id="6e3b8-374">版本 1905（内部版本 11609.20002）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-374">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-375">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-375">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-376">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-376">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="6e3b8-377">改进了使用数据类型的着色地图体验</span><span class="sxs-lookup"><span data-stu-id="6e3b8-377">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="6e3b8-378">对于使用 Excel 的地理数据类型绘制着色地图图表的用户而言，这是一项改进功能。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-378">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="6e3b8-379">对于最终用户而言，其优势是功能之间更丰富的集成，并提高了最终用户想要绘制的区域的准确性。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-379">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="6e3b8-380">额外优势包括绘制城市多边形的功能。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-380">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="6e3b8-381">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-381">Getting Started:</span></span>

- <span data-ttu-id="6e3b8-382">此功能是对 Excel 中现有功能的改进。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-382">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="6e3b8-383">若要使用此改进功能，可将位置转换为“丰富实体”并使用着色地图绘图。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-383">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-384">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-384">Scenarios to Try:</span></span>

- <span data-ttu-id="6e3b8-385">用户可尝试绘制城市、省/市/自治区、县、国家/地区和邮政编码。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-385">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-386">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-386">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="6e3b8-387">所有应用程序</span><span class="sxs-lookup"><span data-stu-id="6e3b8-387">All Applications</span></span>
- <span data-ttu-id="6e3b8-388">修复了应用程序启动时显示“首次运行”对话框的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-388">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="6e3b8-389">修复了“另存为”对话框中的 SharePoint 链接可能丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-389">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="6e3b8-390">修复了用户将误看到“立即修复”对话框的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-390">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-391">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-391">Word</span></span> 
- <span data-ttu-id="6e3b8-392">修复了一些用户在请求字体时可能会收到内存或磁盘空间不足错误的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-392">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="6e3b8-393">修复了从批注窗格切换时窗口可能丢失焦点的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-393">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-394">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-394">Excel</span></span>
- <span data-ttu-id="6e3b8-395">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-395">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-396">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-397">修复了阻止调整品牌形状大小的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-397">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="6e3b8-398">修复了 PowerPoint 在保护视图模式下打开文件时可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-398">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-399">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-399">Outlook</span></span>
- <span data-ttu-id="6e3b8-400">修复了阻止某些用户选择中文字词的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-400">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="6e3b8-401">修复了到期日期未正确计算的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-401">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-402">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-402">Access</span></span>
- <span data-ttu-id="6e3b8-403">修复了阻止某些用户使用宏生成器的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-403">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="6e3b8-404">修复了打印报告只打印第一页的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-404">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="6e3b8-405">修复了在鼠标悬停在超链接上时应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-405">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="6e3b8-406">修复了在使用关系视图时导致一些项目出现在屏幕之外的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-406">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-407">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-407">Project</span></span>
- <span data-ttu-id="6e3b8-408">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-408">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="6e3b8-409">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-409">April 12, 2019</span></span>
<span data-ttu-id="6e3b8-410">版本 1905（内部版本 11601.20042）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-410">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-411">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-411">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-412">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-412">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="6e3b8-413">Access 新增功能 - Microsoft Graph 数据连接器</span><span class="sxs-lookup"><span data-stu-id="6e3b8-413">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="6e3b8-414">链接到 Microsoft Graph 服务或者从 Microsoft Graph 服务导入，以构建可利用 Graph 中存储的智能上下文数据的应用程序</span><span class="sxs-lookup"><span data-stu-id="6e3b8-414">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-415">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-415">Getting Started:</span></span>

<span data-ttu-id="6e3b8-416">工具区中的“外部数据”选项卡，单击“新数据”并在“联机服务”菜单中找到新的 Graph 连接器</span><span class="sxs-lookup"><span data-stu-id="6e3b8-416">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-417">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-417">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-418">从不同 Graph 服务导入或链接至不同 Graph 服务，包括人脉、组和 OneDrive 项。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-418">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-419">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-419">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="6e3b8-420">所有应用程序</span><span class="sxs-lookup"><span data-stu-id="6e3b8-420">All Applications</span></span>
 - <span data-ttu-id="6e3b8-421">我们修复了一个阻止某些用户将文件保存到云端的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-421">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="6e3b8-422">我们修复了错误的窗格可以从功能区打开的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-422">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-423">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-423">Word</span></span> 
- <span data-ttu-id="6e3b8-424">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-424">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-425">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-425">Excel</span></span>
- <span data-ttu-id="6e3b8-426">我们修复了一个问题，即当工作簿不包含链接的数据类型时，用户会看到链接的数据类型的错误消息</span><span class="sxs-lookup"><span data-stu-id="6e3b8-426">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="6e3b8-427">我们修复了一个问题，即当在本地和在线查看时，Word 文档中的 URL 链接可能会发生变化</span><span class="sxs-lookup"><span data-stu-id="6e3b8-427">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-428">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-428">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-429">我们修复了从动画选项卡中撤消更改后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-429">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-430">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-430">Outlook</span></span>
- <span data-ttu-id="6e3b8-431">我们修复了阻止某些用户修改公用文件夹中联系人的“备注”字段的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-431">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="6e3b8-432">我们修复了在到期日期和删除日期之间可能发生冲突的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-432">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-433">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-433">Access</span></span>
- <span data-ttu-id="6e3b8-434">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-434">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-435">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-435">Project</span></span>
- <span data-ttu-id="6e3b8-436">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-436">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="6e3b8-437">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-437">April 5, 2019</span></span>
<span data-ttu-id="6e3b8-438">版本 1904（内部版本 11527.20014）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-438">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-439">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-439">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-440">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="6e3b8-441">Outlook for Windows：设置和共享“重点收件箱”设置</span><span class="sxs-lookup"><span data-stu-id="6e3b8-441">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="6e3b8-442">“重点收件箱”首选项存储在云中，因此，在任何计算机上使用 Outlook for Windows 和 Outlook 网页版时，可以享受相同、一致的体验。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-442">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-443">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-443">Getting Started:</span></span>

<span data-ttu-id="6e3b8-444">“文件”>“选项”>“常规”选项卡下存在“将我的 Outlook 设置存储在云中”的新首选项。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-444">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="6e3b8-445">用户需要选中该框，才能使其“重点收件箱”设置漫游到其他桌面 Outlook 安装和 OWA。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-445">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-446">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-446">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-447">在计算机上更改已启用云设置首选项的“重点收件箱”。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-447">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="6e3b8-448">导航至 OWA 并查看此处应用的首选项。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-448">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="6e3b8-449">在 OWA 中更改“重点收件箱”并启动 Outlook 桌面版以查看反映的首选项。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-449">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-450">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-450">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="6e3b8-451">“学习工具”模式可提供更多页面颜色的其他支持</span><span class="sxs-lookup"><span data-stu-id="6e3b8-451">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="6e3b8-452">Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-452">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="6e3b8-453">许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-453">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-454">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-454">Getting Started:</span></span>

<span data-ttu-id="6e3b8-455">若要尝试，请转至“视图”选项卡并选择“学习工具”，然后再选择“页面颜色”。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-455">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-456">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-456">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-457">若要尝试，请转至“视图”选项卡并选择“学习工具”，然后再选择“页面颜色”。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-457">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-458">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-458">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="6e3b8-459">利用动画 3D 模型提升创意</span><span class="sxs-lookup"><span data-stu-id="6e3b8-459">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="6e3b8-460">Office 现支持动画模型，这些模型可以在编辑器中播放，从而让你的表单看起来栩栩如生！</span><span class="sxs-lookup"><span data-stu-id="6e3b8-460">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-461">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-461">Getting Started:</span></span>

1. <span data-ttu-id="6e3b8-462">打开 Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-462">Open Excel.</span></span>
2. <span data-ttu-id="6e3b8-463">插入动画 3D 模型（即将在 Remix 中推出，但目前请访问以下位置的动画模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-463">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="6e3b8-464">动画模型将在编辑器中播放！</span><span class="sxs-lookup"><span data-stu-id="6e3b8-464">The animated model will play in the editor!</span></span> <span data-ttu-id="6e3b8-465">选中幻灯片放映模式 - 它也可以在此播放！</span><span class="sxs-lookup"><span data-stu-id="6e3b8-465">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="6e3b8-466">在 3D 格式功能区中，浏览此模型中的更多动画场景</span><span class="sxs-lookup"><span data-stu-id="6e3b8-466">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-467">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-467">Scenarios to Try:</span></span>

1. <span data-ttu-id="6e3b8-468">插入动画模型并在编辑器中观看该模型</span><span class="sxs-lookup"><span data-stu-id="6e3b8-468">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="6e3b8-469">通过场景库（可在 3D 格式功能区中找到）浏览动画模型中可用的动画场景</span><span class="sxs-lookup"><span data-stu-id="6e3b8-469">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="6e3b8-470">通过功能区、浮动条或空格键轻松播放/暂停动画。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-470">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-471">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-471">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="6e3b8-472">所有应用程序</span><span class="sxs-lookup"><span data-stu-id="6e3b8-472">All Applications</span></span>
- <span data-ttu-id="6e3b8-473">我们修复了以下问题：Excel 的上下文菜单中的应用图标无法正常显示</span><span class="sxs-lookup"><span data-stu-id="6e3b8-473">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="6e3b8-474">我们修复了以下问题：安装更新后，“文件”菜单按钮可能会消失</span><span class="sxs-lookup"><span data-stu-id="6e3b8-474">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="6e3b8-475">我们修复了可能更改用户许可证的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-475">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-476">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-476">Word</span></span> 
- <span data-ttu-id="6e3b8-477">我们修复了以下问题：文本在某些缩放级别上无法正确呈现</span><span class="sxs-lookup"><span data-stu-id="6e3b8-477">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-478">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-478">Excel</span></span>
- <span data-ttu-id="6e3b8-479">我们修复了以下问题：在进行编辑后，系统不会提示用户保存工作簿</span><span class="sxs-lookup"><span data-stu-id="6e3b8-479">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="6e3b8-480">我们修复了以下问题：如果用户共享了工作簿，则不会触发 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-480">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="6e3b8-481">我们修复了以下问题：将列大小调整为少于 6 个像素可能会抛出不正确的错误消息。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-481">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="6e3b8-482">我们修复了以下问题：Excel 会忽略 Application.Visible 标志</span><span class="sxs-lookup"><span data-stu-id="6e3b8-482">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="6e3b8-483">我们修复了以下问题：跟踪箭头保留在非活动的冻结窗格中</span><span class="sxs-lookup"><span data-stu-id="6e3b8-483">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="6e3b8-484">我们修复了以下问题：打开工作簿时货币可能更改日期的单元格格式</span><span class="sxs-lookup"><span data-stu-id="6e3b8-484">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="6e3b8-485">我们修复了以下问题：工具提示可能意外移动</span><span class="sxs-lookup"><span data-stu-id="6e3b8-485">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="6e3b8-486">我们修复了 Power Query 编辑器的本地化问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-486">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="6e3b8-487">我们修复了以下问题：通过电子邮件发送时，工作簿将作为附件删除</span><span class="sxs-lookup"><span data-stu-id="6e3b8-487">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-488">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-489">我们修复了以下问题：复制形状的时间可能比预期要长</span><span class="sxs-lookup"><span data-stu-id="6e3b8-489">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-490">Outlook</span></span>
- <span data-ttu-id="6e3b8-491">我们修复了以下问题：使用“绘图”工具时 Outlook 可能会崩溃</span><span class="sxs-lookup"><span data-stu-id="6e3b8-491">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="6e3b8-492">我们修复了撰写 HTML 电子邮件时的本地化问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-492">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="6e3b8-493">我们修复了以下问题：用户难以选择下部窗格</span><span class="sxs-lookup"><span data-stu-id="6e3b8-493">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-494">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-494">Access</span></span>
- <span data-ttu-id="6e3b8-495">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-495">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-496">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-496">Project</span></span>
- <span data-ttu-id="6e3b8-497">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-497">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="6e3b8-498">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-498">March 22, 2019</span></span>
<span data-ttu-id="6e3b8-499">版本 1904（内部版本 11514.20004）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-499">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-500">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-500">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-501">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-501">Word</span></span> 
- <span data-ttu-id="6e3b8-502">我们修复了 UI 会不断显示“正在检查更改”的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-502">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-503">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-503">Excel</span></span>
- <span data-ttu-id="6e3b8-504">我们修复了在移动工作表后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-504">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="6e3b8-505">我们修复了在另存为 PDF 后应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-505">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="6e3b8-506">我们修复了“保存”对话框不接受某些韩语字符的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-506">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-507">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-508">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-508">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-509">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-509">Outlook</span></span>
- <span data-ttu-id="6e3b8-510">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-510">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-511">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-511">Access</span></span>
- <span data-ttu-id="6e3b8-512">我们修复了在 Access 中，创建 Access 的额外快捷方式错误消息</span><span class="sxs-lookup"><span data-stu-id="6e3b8-512">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="6e3b8-513">我们修复了所链接的 SharePoint 中数据显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-513">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-514">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-514">Project</span></span>
- <span data-ttu-id="6e3b8-515">我们解决了语言设置从中文切换到英语的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-515">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="6e3b8-516">我们修复了在同步到 SharePoint 时应用程序可能崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-516">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="6e3b8-517">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-517">March 15, 2019</span></span>
<span data-ttu-id="6e3b8-518">版本 1904（内部版本 11504.20000）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-518">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-519">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-519">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-520">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-520">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="6e3b8-521">焦点模式</span><span class="sxs-lookup"><span data-stu-id="6e3b8-521">Focus mode</span></span>

<span data-ttu-id="6e3b8-522">切换到“视图”菜单上的焦点模式，消除干扰，让你专注于工作。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-522">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="6e3b8-523">仅适用于 Office 365 订阅者。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-523">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-524">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-524">Getting Started:</span></span>

<span data-ttu-id="6e3b8-525">查看功能区状态栏中的选项卡“焦点”按钮 -“焦点”按钮</span><span class="sxs-lookup"><span data-stu-id="6e3b8-525">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-526">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-526">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-527">进入焦点模式并体验焦点体验</span><span class="sxs-lookup"><span data-stu-id="6e3b8-527">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-528">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-528">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-529">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-529">Word</span></span> 
- <span data-ttu-id="6e3b8-530">我们修复了文档中的图片另存为 PDF 时产生不正确 DPI 的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-530">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-531">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-531">Excel</span></span>
- <span data-ttu-id="6e3b8-532">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-532">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-533">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-534">我们修复了批准窗格无法正确打开或关闭的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-534">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="6e3b8-535">我们修复了在删除视频时应用程序崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-535">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="6e3b8-536">我们修复了应用程序在某些实例中无法启动的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-536">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-537">Outlook</span></span>
- <span data-ttu-id="6e3b8-538">我们修复了已读回执在日语版中显示不正确的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-538">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-539">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-539">Access</span></span>
- <span data-ttu-id="6e3b8-540">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-540">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-541">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-541">Project</span></span>
- <span data-ttu-id="6e3b8-542">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-542">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="6e3b8-543">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-543">March 8, 2019</span></span> 
<span data-ttu-id="6e3b8-544">版本 1903（内部版本 11425.20036）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-544">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-545">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-545">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-546">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-546">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="6e3b8-547">通过 Microsoft 搜索找到要查找的内容</span><span class="sxs-lookup"><span data-stu-id="6e3b8-547">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="6e3b8-548">使用 Microsoft 搜索，你可以找到完成工作所需的所有文件、操作、人员和帮助。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-548">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-549">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-549">Getting Started:</span></span>

- <span data-ttu-id="6e3b8-550">此功能醒目地显示在标题界面的顶部。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-550">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-551">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-551">Scenarios to Try:</span></span>

- <span data-ttu-id="6e3b8-552">搜索学院、最近使用的文档或搜索最常用的功能区命令</span><span class="sxs-lookup"><span data-stu-id="6e3b8-552">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="6e3b8-553">查找主题以获取有关它的详细信息</span><span class="sxs-lookup"><span data-stu-id="6e3b8-553">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="6e3b8-554">CoAuthoring</span><span class="sxs-lookup"><span data-stu-id="6e3b8-554">CoAuthoring</span></span>

<span data-ttu-id="6e3b8-555">厌倦了被包含宏的文档拒之门外？</span><span class="sxs-lookup"><span data-stu-id="6e3b8-555">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="6e3b8-556">现在，OneDrive for Business 上的文档文件允许被多位创作者同时编辑。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-556">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-557">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-557">Getting Started:</span></span>

<span data-ttu-id="6e3b8-558">用户无需在 UI 中按任何按钮即可访问此功能。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-558">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="6e3b8-559">默认情况下，OneDrive for Business 文档文件已启用此功能。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-559">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="6e3b8-560">因此，用户应将文档文件保存到 OneDrive for Business 中以进行试用。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-560">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-561">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-561">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-562">在 OneDrive for Business 上创建一个文档文件，将其与同事共享，然后进行协作！</span><span class="sxs-lookup"><span data-stu-id="6e3b8-562">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-563">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-563">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-564">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-564">Word</span></span> 
- <span data-ttu-id="6e3b8-565">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span><span class="sxs-lookup"><span data-stu-id="6e3b8-565">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="6e3b8-566">我们修复了回复评论时发生的崩溃问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-566">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="6e3b8-567">我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-567">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-568">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-568">Excel</span></span>
- <span data-ttu-id="6e3b8-569">我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-569">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-570">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-570">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-571">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-571">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-572">Outlook</span></span>
- <span data-ttu-id="6e3b8-573">我们修复了 Outlook 搜索不按选定的时间顺序排序的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-573">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="6e3b8-574">我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-574">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="6e3b8-575">我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-575">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-576">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-576">Access</span></span>
- <span data-ttu-id="6e3b8-577">我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-577">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="6e3b8-578">我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-578">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-579">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-579">Project</span></span>
- <span data-ttu-id="6e3b8-580">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-580">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="6e3b8-581">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-581">March 1, 2019</span></span> 
<span data-ttu-id="6e3b8-582">版本 1903（内部版本 11414.20014）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-582">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-583">新增功能</span><span class="sxs-lookup"><span data-stu-id="6e3b8-583">What's New</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-584">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-584">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="6e3b8-585">修订、备注和实时同步协作的颜色</span><span class="sxs-lookup"><span data-stu-id="6e3b8-585">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="6e3b8-586">产品中的修复现在可确保以相同的颜色显示备注、修订和协作者光标。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-586">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-587">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-587">Getting Started:</span></span>

<span data-ttu-id="6e3b8-588">打开其他人已打开的 SharePoint 或 OneDrive 文档。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-588">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="6e3b8-589">验证用户的修订和备注颜色是否与用户光标的颜色匹配。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-589">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-590">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-590">Scenarios to Try:</span></span>

<span data-ttu-id="6e3b8-591">打开其他人已打开的 SharePoint 或 OneDrive 文档。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-591">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="6e3b8-592">验证用户的修订和备注颜色是否与用户光标的颜色匹配。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-592">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-593">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-593">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-594">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-594">Word</span></span> 
- <span data-ttu-id="6e3b8-595">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span><span class="sxs-lookup"><span data-stu-id="6e3b8-595">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="6e3b8-596">我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-596">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-597">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-597">Excel</span></span>
- <span data-ttu-id="6e3b8-598">我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-598">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-599">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-599">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-600">我们修复了在 PowerPoint 中使用 @提及功能时幻灯片图像大小的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-600">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-601">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-601">Outlook</span></span>
- <span data-ttu-id="6e3b8-602">我们修复了 Outlook 搜索不按选定的时间顺序排序的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-602">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="6e3b8-603">我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-603">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="6e3b8-604">我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-604">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-605">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-605">Access</span></span>
- <span data-ttu-id="6e3b8-606">我们更新了确认重链接表格与数据源时显示的提示文本</span><span class="sxs-lookup"><span data-stu-id="6e3b8-606">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="6e3b8-607">我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-607">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="6e3b8-608">我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-608">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-609">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-609">Project</span></span>
- <span data-ttu-id="6e3b8-610">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-610">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="6e3b8-611">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-611">February 15, 2019</span></span> 
<span data-ttu-id="6e3b8-612">版本 1903（内部版本 11310.20016）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-612">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="6e3b8-613">最近更新：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-613">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-614">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-614">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="6e3b8-615">平滑切换增强功能 - 按名称平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-615">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="6e3b8-616">选择需要平滑的形状</span><span class="sxs-lookup"><span data-stu-id="6e3b8-616">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-617">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-617">Getting Started:</span></span>

- <span data-ttu-id="6e3b8-618">若要使“平滑”将两个对象视为同一对象，用户可以使用“选择窗格”来重命名形状。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-618">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="6e3b8-619">该名称必须以“!!”</span><span class="sxs-lookup"><span data-stu-id="6e3b8-619">The name must be prefaced with “!!”</span></span> <span data-ttu-id="6e3b8-620">（两个感叹号）开头，以便“平滑”使用它来覆盖默认匹配行为，例如“!!Name”</span><span class="sxs-lookup"><span data-stu-id="6e3b8-620">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="6e3b8-621">用户可以使用任何不是以“!!”开头的名称来重命名形状，</span><span class="sxs-lookup"><span data-stu-id="6e3b8-621">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="6e3b8-622">不必担心这会改变 Morph 的工作方式</span><span class="sxs-lookup"><span data-stu-id="6e3b8-622">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-623">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-623">Scenarios to Try:</span></span>

- <span data-ttu-id="6e3b8-624">在幻灯片中插入一个形状，假设它为矩形</span><span class="sxs-lookup"><span data-stu-id="6e3b8-624">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="6e3b8-625">创建新幻灯片</span><span class="sxs-lookup"><span data-stu-id="6e3b8-625">Create a new slide</span></span>
- <span data-ttu-id="6e3b8-626">在第 2 张幻灯片中插入不同的形状，假设它为三角形</span><span class="sxs-lookup"><span data-stu-id="6e3b8-626">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="6e3b8-627">打开“选择窗格”，将幻灯片 1 中的矩形重命名为“!!shape”，并将幻灯片 2 中的三角形重命名为“!!shape”</span><span class="sxs-lookup"><span data-stu-id="6e3b8-627">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="6e3b8-628">在第 2 张幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-628">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="6e3b8-629">平滑切换增强功能 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="6e3b8-629">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="6e3b8-630">具有更流畅切换效果的 SmartArt 平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-630">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-631">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-631">Getting Started:</span></span>

<span data-ttu-id="6e3b8-632">按照使用 SmartArt 的相同方式来使用平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-632">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-633">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-633">Scenarios to Try:</span></span>

- <span data-ttu-id="6e3b8-634">在幻灯片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="6e3b8-634">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="6e3b8-635">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="6e3b8-635">Duplicate the Slide</span></span>
- <span data-ttu-id="6e3b8-636">在复制的幻灯片上调整/更改/移动 SmartArt</span><span class="sxs-lookup"><span data-stu-id="6e3b8-636">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="6e3b8-637">在复制的幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-637">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="6e3b8-638">平滑切换增强功能 - 表格</span><span class="sxs-lookup"><span data-stu-id="6e3b8-638">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="6e3b8-639">具有更流畅切换效果的表格平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-639">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="6e3b8-640">入门：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-640">Getting Started:</span></span>
<span data-ttu-id="6e3b8-641">按照使用表格的相同方式来使用平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-641">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-642">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-642">Scenarios to Try:</span></span>

- <span data-ttu-id="6e3b8-643">在幻灯片中插入表格</span><span class="sxs-lookup"><span data-stu-id="6e3b8-643">Insert a Table in a slide</span></span>
- <span data-ttu-id="6e3b8-644">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="6e3b8-644">Duplicate the slide</span></span>
- <span data-ttu-id="6e3b8-645">在复制的幻灯片上调整/更改/移动表格</span><span class="sxs-lookup"><span data-stu-id="6e3b8-645">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="6e3b8-646">在复制的幻灯片上应用平滑</span><span class="sxs-lookup"><span data-stu-id="6e3b8-646">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="6e3b8-647">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="6e3b8-647">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="6e3b8-648">在帐户之间无缝切换</span><span class="sxs-lookup"><span data-stu-id="6e3b8-648">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="6e3b8-649">新的帐户管理员在一个位置显示你的所有工作和个人帐户，让你在帐户之间自如切换。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-649">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="6e3b8-650">更新后的这一体验清晰展示了你的登录方式，你现无需先退出或处理复杂的对话，即可在工作帐户和个人帐户之间切换。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-650">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="6e3b8-652">可尝试的方案：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-652">Scenarios to Try:</span></span>
- <span data-ttu-id="6e3b8-653">在帐户之间切换</span><span class="sxs-lookup"><span data-stu-id="6e3b8-653">Switch between accounts</span></span>
- <span data-ttu-id="6e3b8-654">添加新帐户[注意：你可能需要先转到“文件”|“帐户”|“已连接的服务”，然后删除与工作帐户相关的任何个人服务，反之亦然]</span><span class="sxs-lookup"><span data-stu-id="6e3b8-654">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="6e3b8-655">从帐户注销</span><span class="sxs-lookup"><span data-stu-id="6e3b8-655">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-656">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-656">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-657">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-657">Word</span></span> 
- <span data-ttu-id="6e3b8-658">我们修复了表格和图像的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-658">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-659">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-659">Excel</span></span>
- <span data-ttu-id="6e3b8-660">我们修复了自动筛选搜索字段中的文本在黑色主题中显示为白色的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-660">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="6e3b8-661">我们修复了新 Office 加载项的许可 UI 问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-661">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-662">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-662">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-663">我们修复了在笔记本电脑或平板电脑上演示幻灯片时自动扩展显示的问题。</span><span class="sxs-lookup"><span data-stu-id="6e3b8-663">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-664">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-664">Outlook</span></span>
- <span data-ttu-id="6e3b8-665">我们修复了“发送至 OneNote”按钮显示的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-665">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-666">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-666">Access</span></span>
- <span data-ttu-id="6e3b8-667">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-667">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-668">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-668">Project</span></span>
- <span data-ttu-id="6e3b8-669">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-669">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="6e3b8-670">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-670">February 11, 2019</span></span>
<span data-ttu-id="6e3b8-671">版本 1903（内部版本 11330.20014）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-671">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-672">显著修复：</span><span class="sxs-lookup"><span data-stu-id="6e3b8-672">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-673">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-673">Word</span></span> 
- <span data-ttu-id="6e3b8-674">我们已修复以下问题：一些自定义样式无法应用于 word online</span><span class="sxs-lookup"><span data-stu-id="6e3b8-674">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="6e3b8-675">我们修复了 Word 中丰富对象的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-675">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="6e3b8-676">我们修复了以下问题：粘贴列表将导致 Word 崩溃</span><span class="sxs-lookup"><span data-stu-id="6e3b8-676">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-677">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-677">Excel</span></span>
- <span data-ttu-id="6e3b8-678">我们修复了以下问题：当没有货币符号时，数字格式后不再显示附加空格</span><span class="sxs-lookup"><span data-stu-id="6e3b8-678">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="6e3b8-679">我们修复了自动检测股票的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-679">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-680">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-681">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-681">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-682">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-682">Outlook</span></span>
- <span data-ttu-id="6e3b8-683">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-683">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-684">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-684">Access</span></span>
- <span data-ttu-id="6e3b8-685">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-685">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-686">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-686">Project</span></span>
- <span data-ttu-id="6e3b8-687">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-687">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="6e3b8-688">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6e3b8-688">February 1, 2019</span></span> 
<span data-ttu-id="6e3b8-689">版本 1902（内部版本 11326.20000）</span><span class="sxs-lookup"><span data-stu-id="6e3b8-689">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="6e3b8-690">显著修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-690">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="6e3b8-691">Word</span><span class="sxs-lookup"><span data-stu-id="6e3b8-691">Word</span></span> 
- <span data-ttu-id="6e3b8-692">我们修复了在嵌入式 Excel 表格中调整单元格大小的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-692">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="6e3b8-693">我们修复了在画布中复制/粘贴形状的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-693">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="6e3b8-694">Excel</span><span class="sxs-lookup"><span data-stu-id="6e3b8-694">Excel</span></span>
- <span data-ttu-id="6e3b8-695">我们修复了从 Excel Web 应用程序中打开文件的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-695">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="6e3b8-696">我们修复了由于文件名长度而无法将 .XLSX 另存为 CSV 文件的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-696">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="6e3b8-697">我们修复了上下文菜单显示上下文菜单选项的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-697">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="6e3b8-698">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="6e3b8-698">PowerPoint</span></span>
- <span data-ttu-id="6e3b8-699">我们修复了用户无法使用键盘快捷方式 ctrl+alt+7/ctrl+alt+8 进入方括号的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-699">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="6e3b8-700">我们修复了将本地视频插入 PPT 会减少“C”驱动器磁盘空间的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-700">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="6e3b8-701">我们修复了未向某些用户显示“发布到 Microsoft Stream”按钮的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-701">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="6e3b8-702">Outlook</span><span class="sxs-lookup"><span data-stu-id="6e3b8-702">Outlook</span></span>
- <span data-ttu-id="6e3b8-703">我们修复了日历中的任务视图未正确显示任务主题的问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-703">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="6e3b8-704">Access</span><span class="sxs-lookup"><span data-stu-id="6e3b8-704">Access</span></span>
- <span data-ttu-id="6e3b8-705">我们修复了图表的缩放比例问题</span><span class="sxs-lookup"><span data-stu-id="6e3b8-705">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="6e3b8-706">Project</span><span class="sxs-lookup"><span data-stu-id="6e3b8-706">Project</span></span>
- <span data-ttu-id="6e3b8-707">各种性能和稳定性修复</span><span class="sxs-lookup"><span data-stu-id="6e3b8-707">Various performance and stability fixes</span></span>
