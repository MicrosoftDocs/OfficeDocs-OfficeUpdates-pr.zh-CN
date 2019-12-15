---
title: 每月频道（定向）的发行说明
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为“预览体验成员 - 慢”受众提供关键新功能、修复程序或已知问题的最新列表
ms.openlocfilehash: e7fc9ff0ba68aca9d73873c7c299fed4e7668236
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023617"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="3eb64-103">Office 每月频道（定向）的发行说明</span><span class="sxs-lookup"><span data-stu-id="3eb64-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="3eb64-104">本文包含 Windows 桌面版的 Word、Excel、PowerPoint、Outlook、Access 和 Project 的每月频道（定向）内部版本的发行说明。</span><span class="sxs-lookup"><span data-stu-id="3eb64-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="3eb64-105">每周，我们都会提供精彩集锦，其中包含我们希望你了解的有趣新功能、重要修补程序和所有重要问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="3eb64-106">请注意，我们经常会过一段时间就将功能（有时甚至是修补程序）发布到每月频道（定向）。</span><span class="sxs-lookup"><span data-stu-id="3eb64-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="3eb64-107">这可以让我们确保将功能向更多的受众发布之前，所用功能均可正常使用。</span><span class="sxs-lookup"><span data-stu-id="3eb64-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="3eb64-108">因此，如果你没有看到下面所述的功能，请不要担心，你最终会获取这些功能。</span><span class="sxs-lookup"><span data-stu-id="3eb64-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="3eb64-109">发行说明发布日期可能与实际内部版本发布日期不一致。</span><span class="sxs-lookup"><span data-stu-id="3eb64-109">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="3eb64-110">Office 365 专业增强版现有安装的 Microsoft Teams - 从6月底开始, 将在更新这些安装的 Office 365 专业增强版 (和 Office 365 Business) 现有安装中包含 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="3eb64-110">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="3eb64-111">将添加 Teams 的日期取决于所使用的更新频道。</span><span class="sxs-lookup"><span data-stu-id="3eb64-111">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="3eb64-112">有关详细信息, 请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。</span><span class="sxs-lookup"><span data-stu-id="3eb64-112">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (请勿移除)

[//]: # (请勿移除功能详细信息内容开头)

[//]: # (请勿移除功能详细信息内容结尾)

## <a name="version-1912-december-12"></a><span data-ttu-id="3eb64-116">版本 1912：12 月 12 日</span><span class="sxs-lookup"><span data-stu-id="3eb64-116">Version 1912: December 06</span></span>
<span data-ttu-id="3eb64-117">*版本 1912（内部版本 12325.20172）*</span><span class="sxs-lookup"><span data-stu-id="3eb64-117">*Version 1912 (Build 12325.20012)*</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="3eb64-119">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="3eb64-119">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3eb64-120">Excel</span><span class="sxs-lookup"><span data-stu-id="3eb64-120">Excel</span></span>

- <span data-ttu-id="3eb64-121">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="3eb64-121">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3eb64-122">编辑单元格中的动态数组公式可能会导致文本在单元格边界之外对齐。</span><span class="sxs-lookup"><span data-stu-id="3eb64-122">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell</span></span>

- <span data-ttu-id="3eb64-123">某些本地化版本的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="3eb64-123">Text to Column functionality may fail for some localizations</span></span>

- <span data-ttu-id="3eb64-124">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-124">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="3eb64-125">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="3eb64-125">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="3eb64-126">页边距下拉菜单可能无法正确呈现。</span><span class="sxs-lookup"><span data-stu-id="3eb64-126">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="3eb64-127">禁用 4k 分辨率硬件图形加速可能会延迟单元格的渲染。</span><span class="sxs-lookup"><span data-stu-id="3eb64-127">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>

- <span data-ttu-id="3eb64-128">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-128">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="onenote"></a><span data-ttu-id="3eb64-129">OneNote</span><span class="sxs-lookup"><span data-stu-id="3eb64-129">OneNote</span></span>

- <span data-ttu-id="3eb64-130">OneNote 可能无法通过‘会议记录’ Outlook 加载项打开。</span><span class="sxs-lookup"><span data-stu-id="3eb64-130">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="3eb64-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="3eb64-131">Outlook</span></span>

- <span data-ttu-id="3eb64-132">涉及跨文件夹内容的间歇性崩溃。</span><span class="sxs-lookup"><span data-stu-id="3eb64-132">Intermittent crash involving cross folder content</span></span>

- <span data-ttu-id="3eb64-133">内联插入 Outlook 电子邮件正文中的图像，有时尺寸会发生变化。</span><span class="sxs-lookup"><span data-stu-id="3eb64-133">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

- <span data-ttu-id="3eb64-134">添加了通过组策略强制执行 S/MIME 默认签名配置的能力。</span><span class="sxs-lookup"><span data-stu-id="3eb64-134">Added the ability to enforce S/MIME configuration via group policy</span></span>

- <span data-ttu-id="3eb64-135">嵌入的图像可能看起来比预期的要小。</span><span class="sxs-lookup"><span data-stu-id="3eb64-135">Embedded images may appear smaller than expected</span></span>

- <span data-ttu-id="3eb64-136">保留策略标签可能会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="3eb64-136">Retention policy labels may display the retention time period in parenthesis.</span></span>

- <span data-ttu-id="3eb64-137">解决了在使用备用发件人时导致无法显示策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-137">Addresses an issue that caused Policy tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="3eb64-138">日语语言包的联系人卡片中可能出现空格。</span><span class="sxs-lookup"><span data-stu-id="3eb64-138">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>

- <span data-ttu-id="3eb64-139">解决了导致会议位置在清除后意外添加回会议的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-139">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3eb64-140">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3eb64-140">PowerPoint</span></span>

- <span data-ttu-id="3eb64-141">将焦点从文本移动后，光标可能会消失。</span><span class="sxs-lookup"><span data-stu-id="3eb64-141">Cursor may disappear after moving focus from text</span></span>

- <span data-ttu-id="3eb64-142">一个 Office 应用程序至其它应用程序的 Safelink 可能无法启动关联的应用程序。</span><span class="sxs-lookup"><span data-stu-id="3eb64-142">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="3eb64-143">在某些情况中，无法使用触摸设备滚动。</span><span class="sxs-lookup"><span data-stu-id="3eb64-143">In some cases, scrolling with touch devices will not work.</span></span>

- <span data-ttu-id="3eb64-144">如果用户在云端文件的幻灯片中有两个（或更多）不同的视频，视频图像可以正确渲染，但当用户单击各视频进行播放时，视频内容相同。</span><span class="sxs-lookup"><span data-stu-id="3eb64-144">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>

- <span data-ttu-id="3eb64-145">页边距下拉菜单可能无法正确呈现。</span><span class="sxs-lookup"><span data-stu-id="3eb64-145">Margin dropdown menu may not render correctly.</span></span>

### <a name="project"></a><span data-ttu-id="3eb64-146">Project</span><span class="sxs-lookup"><span data-stu-id="3eb64-146">Project</span></span>

- <span data-ttu-id="3eb64-147">如果处于深色模式，转至含有过度分配资源的任务的任务检查器面板时，将无法读取表格。</span><span class="sxs-lookup"><span data-stu-id="3eb64-147">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>

- <span data-ttu-id="3eb64-148">用户可能遇到有关许可方面的错误。</span><span class="sxs-lookup"><span data-stu-id="3eb64-148">Users may experience an error regarding licensing</span></span>

- <span data-ttu-id="3eb64-149">日期选取器中的“今天”按钮有时可能会设置错误的日期。</span><span class="sxs-lookup"><span data-stu-id="3eb64-149">The Today button in the date picker may sometimes set the incorrect date</span></span>

- <span data-ttu-id="3eb64-150">使用“比较项目”功能时，项目可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="3eb64-150">Project may crash when you use the Compare Projects feature.</span></span>

- <span data-ttu-id="3eb64-151">无分配任务的工作量取舍为1天。</span><span class="sxs-lookup"><span data-stu-id="3eb64-151">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="3eb64-152">Word</span><span class="sxs-lookup"><span data-stu-id="3eb64-152">Word</span></span>

- <span data-ttu-id="3eb64-153">现在，选择批注提示会在其在窗格切换器中隐藏时显示新式批注窗格。</span><span class="sxs-lookup"><span data-stu-id="3eb64-153">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher</span></span>

- <span data-ttu-id="3eb64-154">右键单击有时无法选择整个单词。</span><span class="sxs-lookup"><span data-stu-id="3eb64-154">Right-clicking can sometimes not result in selecting the whole word</span></span>

- <span data-ttu-id="3eb64-155">一个 Office 应用程序至其它应用程序的 Safelink 可能无法启动关联的应用程序。</span><span class="sxs-lookup"><span data-stu-id="3eb64-155">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="3eb64-156">构建基块管理器可能显示无效的警报：&quot;你已更改样式、构建基块&quot;。</span><span class="sxs-lookup"><span data-stu-id="3eb64-156">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

- <span data-ttu-id="3eb64-157">某些主题可能会导致难以确定选择了哪个批注。</span><span class="sxs-lookup"><span data-stu-id="3eb64-157">Some themes may make it difficult to determine which comment is selected</span></span>

- <span data-ttu-id="3eb64-158">在转换为建议的格式后，光标可能在对象中保持活动状态。</span><span class="sxs-lookup"><span data-stu-id="3eb64-158">The cursor may remain active within an object after converting to a suggested format</span></span>

- <span data-ttu-id="3eb64-159">在某些情况下，邮件中的图像可能无法正确缩放。</span><span class="sxs-lookup"><span data-stu-id="3eb64-159">Images in messages may be incorrectly scaled in some scenarios</span></span>

- <span data-ttu-id="3eb64-160">使用粘贴/复制时，批注窗格有时会重新载入。</span><span class="sxs-lookup"><span data-stu-id="3eb64-160">Comment pane sometimes gets reloaded when using copy/paste.</span></span>

- <span data-ttu-id="3eb64-161">有时批注无法采用正确顺序粘贴。</span><span class="sxs-lookup"><span data-stu-id="3eb64-161">Comments are sometimes not pasted in the correct order.</span></span>

- <span data-ttu-id="3eb64-162">批注卡中的用户可能显示 JSON。</span><span class="sxs-lookup"><span data-stu-id="3eb64-162">At-mentioning a user in a comment card may show JSON.</span></span>

- <span data-ttu-id="3eb64-163">页边距下拉菜单可能无法正确呈现。</span><span class="sxs-lookup"><span data-stu-id="3eb64-163">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="3eb64-164">重新调整分屏边框大小可能产生附加的分屏。</span><span class="sxs-lookup"><span data-stu-id="3eb64-164">Resizing a split screen border may introduce an additional split screen.</span></span>

- <span data-ttu-id="3eb64-165">应用含有多级列表及自定义样式的模板，可能无法在指定条件下保留样式。</span><span class="sxs-lookup"><span data-stu-id="3eb64-165">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>

- <span data-ttu-id="3eb64-166">在某些情况下，合并邮件后可能无法保存文件。</span><span class="sxs-lookup"><span data-stu-id="3eb64-166">Saving a file after doing a mail merge may not work under certain conditions.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3eb64-167">Office 套件</span><span class="sxs-lookup"><span data-stu-id="3eb64-167">Office Suite</span></span>

- <span data-ttu-id="3eb64-168">将图表从 Excel 粘贴到 PowerPoint 后，可减小图表的大小。</span><span class="sxs-lookup"><span data-stu-id="3eb64-168">Pasting a chart from Excel to PowerPoint can reduce the size of the chart</span></span>

- <span data-ttu-id="3eb64-169">回复批注可能会导致文本框垂直展开到窗格边缘以外。</span><span class="sxs-lookup"><span data-stu-id="3eb64-169">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane</span></span>

- <span data-ttu-id="3eb64-170">对于基于日语的产品，账户用户的名字、姓氏可能按照错误的顺序显示。</span><span class="sxs-lookup"><span data-stu-id="3eb64-170">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>

- <span data-ttu-id="3eb64-171">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-171">Fixed an issue in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="3eb64-172">悬停鼠标指针在批注上方可能会在批注周围显示文本框轮廓。</span><span class="sxs-lookup"><span data-stu-id="3eb64-172">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

- <span data-ttu-id="3eb64-173">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-173">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1911-december-10"></a><span data-ttu-id="3eb64-175">版本 1911：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="3eb64-175">Version 1911: December 10</span></span>
<span data-ttu-id="3eb64-176">*版本 1911（内部版本 12228.20364）*</span><span class="sxs-lookup"><span data-stu-id="3eb64-176">*Version 1911 (Build 12228.20364)*</span></span>

<span data-ttu-id="3eb64-177">[此处](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="3eb64-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="3eb64-179">功能更新</span><span class="sxs-lookup"><span data-stu-id="3eb64-179">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3eb64-180">Excel</span><span class="sxs-lookup"><span data-stu-id="3eb64-180">Excel</span></span>

- <span data-ttu-id="3eb64-181">\*\*将文件转换为改进辅助功能: \*\*将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="3eb64-181">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="3eb64-182">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-182">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="3eb64-183">了解更多</span><span class="sxs-lookup"><span data-stu-id="3eb64-183">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

### <a name="outlook"></a><span data-ttu-id="3eb64-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="3eb64-184">Outlook</span></span>

- <span data-ttu-id="3eb64-185">**组命名策略：** 组命名策略使 IT 管理员能够标准化管理组织中由用户创建的组名。</span><span class="sxs-lookup"><span data-stu-id="3eb64-185">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="3eb64-186">管理员可以要求在创建组时向名称添加特定前缀和后缀，并阻止使用指定的字词。</span><span class="sxs-lookup"><span data-stu-id="3eb64-186">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="3eb64-187">这有助于尽可能在组名中减少使用不适宜的字词，以及有助于IT部门在目录中管理组的显示方式。</span><span class="sxs-lookup"><span data-stu-id="3eb64-187">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="3eb64-188">命名策略还可有助于组织根据部门部署团队网站，以进行分类。</span><span class="sxs-lookup"><span data-stu-id="3eb64-188">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3eb64-189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3eb64-189">PowerPoint</span></span>

- <span data-ttu-id="3eb64-190">**墨迹即时重播：** 在幻灯片上使用墨迹时，可应用重播动画，在幻灯片放映期间重播墨迹的实际绘制过程。</span><span class="sxs-lookup"><span data-stu-id="3eb64-190">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="3eb64-191">了解更多</span><span class="sxs-lookup"><span data-stu-id="3eb64-191">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="3eb64-192">\*\*将文件转换为改进辅助功能: \*\*将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="3eb64-192">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="3eb64-193">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-193">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

### <a name="word"></a><span data-ttu-id="3eb64-194">Word</span><span class="sxs-lookup"><span data-stu-id="3eb64-194">Word</span></span>

- <span data-ttu-id="3eb64-195">\*\*其他人可以快速查看你所做的更改: \*\*共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="3eb64-195">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="3eb64-196">\*\*将文件转换为改进辅助功能: \*\*将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="3eb64-196">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="3eb64-197">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-197">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="3eb64-198">了解更多</span><span class="sxs-lookup"><span data-stu-id="3eb64-198">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

## <a name="resolved-issues"></a><span data-ttu-id="3eb64-199">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="3eb64-199">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3eb64-200">Excel</span><span class="sxs-lookup"><span data-stu-id="3eb64-200">Excel</span></span>

- <span data-ttu-id="3eb64-201">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-201">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="3eb64-202">我们修复了数据透视图的右键单击菜单，以便启用“显示详细信息”选项。</span><span class="sxs-lookup"><span data-stu-id="3eb64-202">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

### <a name="outlook"></a><span data-ttu-id="3eb64-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="3eb64-203">Outlook</span></span>

- <span data-ttu-id="3eb64-204">解决了导致 Web 加载项访问数字权限管理邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-204">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

## <a name="version-1911-november-20"></a><span data-ttu-id="3eb64-206">版本 1911：11 月 20 日</span><span class="sxs-lookup"><span data-stu-id="3eb64-206">Version 1911: November 20</span></span>
<span data-ttu-id="3eb64-207">*版本 1911（内部版本 12228.20250）*</span><span class="sxs-lookup"><span data-stu-id="3eb64-207">*Version 1911 (Build 12228.20250)*</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="3eb64-209">功能更新</span><span class="sxs-lookup"><span data-stu-id="3eb64-209">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="3eb64-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="3eb64-210">Outlook</span></span>

- <span data-ttu-id="3eb64-211">**高级组电子邮件设置：** 此功能可帮助组用户自定义要在收件箱中接收/关注的电子邮件或事件。</span><span class="sxs-lookup"><span data-stu-id="3eb64-211">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

## <a name="version-1911-november-15"></a><span data-ttu-id="3eb64-213">版本 1911：11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="3eb64-213">Version 1911: November 15</span></span>
<span data-ttu-id="3eb64-214">*版本 1911（内部版本 12228.20206）*</span><span class="sxs-lookup"><span data-stu-id="3eb64-214">*Version 1911 (Build 12228.20206)*</span></span>

## <a name="version-1911-november-12"></a><span data-ttu-id="3eb64-215">版本 1911：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="3eb64-215">Version 1911: November 12</span></span>
<span data-ttu-id="3eb64-216">*版本 1911（内部版本 12228.20120）*</span><span class="sxs-lookup"><span data-stu-id="3eb64-216">*Version 1911 (Build 12228.20120)*</span></span>

<span data-ttu-id="3eb64-217">[此处](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="3eb64-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="3eb64-219">功能更新</span><span class="sxs-lookup"><span data-stu-id="3eb64-219">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3eb64-220">Excel</span><span class="sxs-lookup"><span data-stu-id="3eb64-220">Excel</span></span>

- <span data-ttu-id="3eb64-221">**数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。</span><span class="sxs-lookup"><span data-stu-id="3eb64-221">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="3eb64-222">了解更多</span><span class="sxs-lookup"><span data-stu-id="3eb64-222">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="3eb64-223">Outlook</span><span class="sxs-lookup"><span data-stu-id="3eb64-223">Outlook</span></span>

- <span data-ttu-id="3eb64-224">**将易访问邮件发送给最需要的人员：** Outlook 将显示邮件提示，以帮助确保在向喜欢易访问内容的用户发送邮件时可访问你的内容。</span><span class="sxs-lookup"><span data-stu-id="3eb64-224">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3eb64-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3eb64-225">PowerPoint</span></span>

- <span data-ttu-id="3eb64-226">**全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。</span><span class="sxs-lookup"><span data-stu-id="3eb64-226">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="visio"></a><span data-ttu-id="3eb64-227">Visio</span><span class="sxs-lookup"><span data-stu-id="3eb64-227">Visio</span></span>

- <span data-ttu-id="3eb64-228">**在 Excel 中制作精美的 Visio 图表：** 在 Excel 中快速轻松地将数据可视化为精美的 Visio 图表。</span><span class="sxs-lookup"><span data-stu-id="3eb64-228">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="3eb64-229">了解更多</span><span class="sxs-lookup"><span data-stu-id="3eb64-229">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="3eb64-230">Word</span><span class="sxs-lookup"><span data-stu-id="3eb64-230">Word</span></span>

- <span data-ttu-id="3eb64-231">**共同创作改进：** 通过让其他人以更接近实时的方式接收内容更改，改进了共同创作体验。</span><span class="sxs-lookup"><span data-stu-id="3eb64-231">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3eb64-232">Office 套件</span><span class="sxs-lookup"><span data-stu-id="3eb64-232">Office Suite</span></span>

- <span data-ttu-id="3eb64-233">**“需要注意的文件”体验将替换上载中心：**“需要注意的文件”体验将替换上载中心，该体验将显示在 Office 应用程序的“文件”>“打开”中。</span><span class="sxs-lookup"><span data-stu-id="3eb64-233">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="3eb64-234">与上载中心相比，这种新体验更加现代、集成度更高并且干扰性更低。</span><span class="sxs-lookup"><span data-stu-id="3eb64-234">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="3eb64-237">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="3eb64-237">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3eb64-238">Access</span><span class="sxs-lookup"><span data-stu-id="3eb64-238">Access</span></span>

- <span data-ttu-id="3eb64-239">记录计数可能不正确。</span><span class="sxs-lookup"><span data-stu-id="3eb64-239">The record count could be incorrect.</span></span>

### <a name="excel"></a><span data-ttu-id="3eb64-240">Excel</span><span class="sxs-lookup"><span data-stu-id="3eb64-240">Excel</span></span>

- <span data-ttu-id="3eb64-241">解决了以下问题：如果删除了包含引用其他工作表上数据的迷你图的工作表，则重新打开时，该文件会被标识为损坏。</span><span class="sxs-lookup"><span data-stu-id="3eb64-241">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="3eb64-242">无法保存对图表大小所做的更改。</span><span class="sxs-lookup"><span data-stu-id="3eb64-242">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="3eb64-243">无法正确呈现复选框。</span><span class="sxs-lookup"><span data-stu-id="3eb64-243">Checkboxes could not render correctly.</span></span>
- <span data-ttu-id="3eb64-244">“选择数据源”对话框对于某些字段不区分大小写。</span><span class="sxs-lookup"><span data-stu-id="3eb64-244">Select Data Source dialogs were not case sensitive for some fields.</span></span>
- <span data-ttu-id="3eb64-245">某些 VBA 函数将在新的图表类型上返回错误。</span><span class="sxs-lookup"><span data-stu-id="3eb64-245">Some VBA functions would return an error on new chart.</span></span>
- <span data-ttu-id="3eb64-246">可阻止用户以 Office 365 Excel 工作簿格式保存。</span><span class="sxs-lookup"><span data-stu-id="3eb64-246">Users could be prevented from saving in Office 365 Excel Workbook format.</span></span>
- <span data-ttu-id="3eb64-247">解决了使用自动调整功能调整行高时复选框控件可能缩小的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-247">Resolved an issue where check box controls could shrink when using autofit to adjust row height.</span></span>
- <span data-ttu-id="3eb64-248">解决了以下问题：将报表筛选器与查询的数据透视表其余部分一起转换为 SQL 表格式服务器时，可能会得到错误的结果。</span><span class="sxs-lookup"><span data-stu-id="3eb64-248">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="3eb64-249">解决了在编辑不受信任的网络共享中的受保护文件时 Excel 可能失败的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-249">Resolved an issue where Excel may fail when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="3eb64-250">同时使用“讲述人”和“放大镜”可能会导致失败。</span><span class="sxs-lookup"><span data-stu-id="3eb64-250">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="3eb64-251">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-251">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>
- <span data-ttu-id="3eb64-252">显著提高了使用合并单元格删除列的性能。</span><span class="sxs-lookup"><span data-stu-id="3eb64-252">We significantly improved the performance of deleting columns with merged cells.</span></span>

### <a name="onenote"></a><span data-ttu-id="3eb64-253">OneNote</span><span class="sxs-lookup"><span data-stu-id="3eb64-253">OneNote</span></span>

- <span data-ttu-id="3eb64-254">发现了可能影响从本地资源同步到云资源的的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-254">Identified an issue which could affect syncing from a local resource to a cloud resource.</span></span>

### <a name="outlook"></a><span data-ttu-id="3eb64-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="3eb64-255">Outlook</span></span>

- <span data-ttu-id="3eb64-256">对于可用会议室，会议室查找工具可能显示“&quot;无&quot;”。</span><span class="sxs-lookup"><span data-stu-id="3eb64-256">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="3eb64-257">发现了将功能区设置为自动隐藏时搜索框可能消失的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-257">Identified an issue where the search box could disappear when the ribbon is set to hide automatically.</span></span>
- <span data-ttu-id="3eb64-258">发现了在对带有数字签名附件的电子邮件进行签名时可能导致数字签名破坏的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-258">Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment.</span></span>
- <span data-ttu-id="3eb64-259">转发的电子邮件可能缺少嵌入图像。</span><span class="sxs-lookup"><span data-stu-id="3eb64-259">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="3eb64-260">用户可能无法创建具有严格租户限制的 Outlook 配置文件。</span><span class="sxs-lookup"><span data-stu-id="3eb64-260">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>
- <span data-ttu-id="3eb64-261">发现了将长文件名拖放到邮件正文后被截断的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-261">Identified an issue where long filenames were truncated after draging and droping to the message body.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3eb64-262">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3eb64-262">PowerPoint</span></span>

- <span data-ttu-id="3eb64-263">无法保存对图表大小所做的更改。</span><span class="sxs-lookup"><span data-stu-id="3eb64-263">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="3eb64-264">同时使用“讲述人”和“放大镜”可能会导致失败。</span><span class="sxs-lookup"><span data-stu-id="3eb64-264">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="3eb64-265">发现了幻灯片预览的纵横比未正确锁定/解锁的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-265">Identified an issue where aspect ratio for the slide preview was not being properly locked/unlocked.</span></span>

### <a name="project"></a><span data-ttu-id="3eb64-266">Project</span><span class="sxs-lookup"><span data-stu-id="3eb64-266">Project</span></span>

- <span data-ttu-id="3eb64-267">发现了在执行更新任务时输入的备注可能无法保留的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-267">Identified an issue where notes might not persist if entered while doing update tasks.</span></span>
- <span data-ttu-id="3eb64-268">用户无法将任务标记为“已完成”，而只能将其设置为 99%。</span><span class="sxs-lookup"><span data-stu-id="3eb64-268">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="3eb64-269">无法通过调配解决过度分配问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-269">Overallocations are not resolved by leveling.</span></span>
- <span data-ttu-id="3eb64-270">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-270">Identified an issue where users could get several messages when opening a read-only project.</span></span>
- <span data-ttu-id="3eb64-271">发现了用户可以锁定文件但错误消息中未显示用户名的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-271">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message.</span></span>

### <a name="publisher"></a><span data-ttu-id="3eb64-272">Publisher</span><span class="sxs-lookup"><span data-stu-id="3eb64-272">Publisher</span></span>

- <span data-ttu-id="3eb64-273">形状可能出现在图形边框之外。</span><span class="sxs-lookup"><span data-stu-id="3eb64-273">Shapes could appear outside of the graphics border.</span></span>

### <a name="word"></a><span data-ttu-id="3eb64-274">Word</span><span class="sxs-lookup"><span data-stu-id="3eb64-274">Word</span></span>

- <span data-ttu-id="3eb64-275">校对建议未显示在上下文菜单中。</span><span class="sxs-lookup"><span data-stu-id="3eb64-275">Proofing suggestions are not displaying in contextual menus.</span></span>
- <span data-ttu-id="3eb64-276">无法保存对图表大小所做的更改。</span><span class="sxs-lookup"><span data-stu-id="3eb64-276">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="3eb64-277">形状可能出现在图形边框之外。</span><span class="sxs-lookup"><span data-stu-id="3eb64-277">Shapes could appear outside of the graphics border.</span></span>
- <span data-ttu-id="3eb64-278">在使用屏幕阅读器查看批注时发现了一个问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-278">Identified an issue when viewing comments while using a screen reader.</span></span>
- <span data-ttu-id="3eb64-279">发现了某些评论被误认为是拼写或语法评论的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-279">Identified an issue where some critiques were misidentified as being spelling or grammar critiques.</span></span>
- <span data-ttu-id="3eb64-280">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="3eb64-280">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="3eb64-281">使用韩语/英语自动更正时可能出现不正确的字符。</span><span class="sxs-lookup"><span data-stu-id="3eb64-281">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="3eb64-282">从导航窗格中搜索可能失败。</span><span class="sxs-lookup"><span data-stu-id="3eb64-282">Searching from the Navigation pane may fail.</span></span>
- <span data-ttu-id="3eb64-283">同时使用“讲述人”和“放大镜”可能会导致失败。</span><span class="sxs-lookup"><span data-stu-id="3eb64-283">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="3eb64-284">内容策略被错误地应用到了批注。</span><span class="sxs-lookup"><span data-stu-id="3eb64-284">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="3eb64-285">当较高的策略标签具有优先级时可能应用较低的策略标签。</span><span class="sxs-lookup"><span data-stu-id="3eb64-285">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="3eb64-286">打开旧版文档后转到“信息”选项卡会导致失败。</span><span class="sxs-lookup"><span data-stu-id="3eb64-286">Opening legacy documents and then going to the Info tab can cause a failure.</span></span>
- <span data-ttu-id="3eb64-287">发现了新批注对话框有时无法获取焦点的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-287">Identified an issue where a new comment dialog could sometimes not obtain focus.</span></span>
- <span data-ttu-id="3eb64-288">将格式应用于 @提及后，可能会阻止联系卡打开。</span><span class="sxs-lookup"><span data-stu-id="3eb64-288">A contact card could be prevented from opening after apply formatting to an @ mention.</span></span>
- <span data-ttu-id="3eb64-289">突出显示文本可能很困难。</span><span class="sxs-lookup"><span data-stu-id="3eb64-289">Highlighting text could be challenging.</span></span>
- <span data-ttu-id="3eb64-290">解决了用户可能无法保存 Word、Excel 和 PowerPoint 文档的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-290">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="3eb64-291">此问题会影响创建新文件并在单击“保存”图标或按 Ctrl + S 后显示“另存为”选项的用户。</span><span class="sxs-lookup"><span data-stu-id="3eb64-291">This issue affects users that create a new file and bring up the "Save as" option after clicking on the Save icon or pressing Ctrl + S.</span></span>
- <span data-ttu-id="3eb64-292">在深色模式中看不到用深色文本编写的旧式批注。</span><span class="sxs-lookup"><span data-stu-id="3eb64-292">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="3eb64-293">可以防止用户导航到编辑器中的单个项目。</span><span class="sxs-lookup"><span data-stu-id="3eb64-293">A user could be prevented from navigating to an individual item in the editor.</span></span>
- <span data-ttu-id="3eb64-294">可能未突出显示语法或拼写错误。</span><span class="sxs-lookup"><span data-stu-id="3eb64-294">Grammar or spelling errors might not be highlighted.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3eb64-295">Office 套件</span><span class="sxs-lookup"><span data-stu-id="3eb64-295">Office Suite</span></span>

- <span data-ttu-id="3eb64-296">预览或幻灯片放映中可能不会显示某些绘图。</span><span class="sxs-lookup"><span data-stu-id="3eb64-296">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="3eb64-297">我们修复了错误消息“正在进行其他安装”阻止升级的问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-297">We fixed an issue where an upgrade could be prevented by a incorrect error message of "Another install in progress".</span></span>
- <span data-ttu-id="3eb64-298">竖排文本框中有些片假名字符可能无法正确显示。</span><span class="sxs-lookup"><span data-stu-id="3eb64-298">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="3eb64-299">尝试将文件保存到断开的网络共享可能会导致失败。</span><span class="sxs-lookup"><span data-stu-id="3eb64-299">Attempting to save a file to a disconnected network share may result in a filure.</span></span>
- <span data-ttu-id="3eb64-300">在 Windows 7 上使用形状时出现性能问题。</span><span class="sxs-lookup"><span data-stu-id="3eb64-300">Performance issue when using Shapes on Windows 7.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

[//]: # (请勿移除错误详细信息内容结尾)

