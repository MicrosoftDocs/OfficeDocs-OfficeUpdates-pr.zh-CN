---
title: 有关 2020 年当前频道发行的发行说明
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2020 年 Microsoft 365 应用版每月频道发行的发行说明
ms.openlocfilehash: 001bc31abe7d885133eac48c58c2c03ae67e6ac8
ms.sourcegitcommit: 6f79e3c3948db4d7ae1c6dfc855970551d3b1678
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/20/2020
ms.locfileid: "45187592"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a>有关 2020 年当前频道发行的发行说明

这些发行说明提供了有关新功能和非安全更新的信息，这些信息包含在 Microsoft 365 企业应用版、Microsoft 365 商业应用版，以及 Project 和 Visio 桌面应用的订阅版本的 2020 年当前频道更新中。

> [!IMPORTANT]
> 我们正在对 Microsoft 365 应用的更新频道进行一些更改，包括添加新的更新频道（月度企业版频道）和更改现有更新频道的名称。 若要了解详细信息，请[阅读这篇文章](https://go.microsoft.com/fwlink/p/?linkid=2127441)。

 > [!NOTE]
>
>- 我们经常会过一段时间就将功能（有时甚至是修补程序）发布到当前频道更新。  如果没有立即看到下述内容，则很快就会看到的。 [了解更多](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (请勿移除错误详细信息内容开头)



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2006-july-14"></a>版本 2006：7 月 14 日
*版本 2006（内部版本 13001.20384）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 解决了插入包含身份（例如自动编号）字段的关联 SQL 表的问题。

### <a name="excel"></a>Excel

- 处于只读模式的工作簿可能已发生自动文档分类。

- 修复了当你已从帐户注销时尝试创建数据连接时可能发生的故障。

### <a name="onenote"></a>OneNote

- 改进对共同创作状态的检测，以减少资源利用率。

### <a name="outlook"></a>Outlook

- 解决了用户在安全对话框中选择”save” 选项时无法将 OneDrive 附件从租户外部保存到本地计算机的问题。

### <a name="office-suite"></a>Office 套件

- 我们对新的 AppV51 进行了备份，以修复之前 AppV51 中的回归问题。

- 解决了 TabProcGrowth 注册表值为 REG_SZ 类型启用加载项时，windows 上的 office 主机会出现崩溃的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2006-june-30"></a>版本 2006：6 月 30 日
*版本 2006（内部版本 13001.20266）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **更长文件名：** Windows 桌面版 Excel 现在支持名称和路径长达 400 字符的 OneDrive/SharePoint 文件。

### <a name="outlook"></a>Outlook

- **新增了用于在 Outlook 中撰写邮件时禁用 @提及建议的选项：** 你是否觉得 @提及选取器更令人生厌，而不是更有用？ 现在，可以根据需要禁用它。<br />在[博客文章](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)中查看详细信息

- **IT 管理员事件通知：** 使用 Outlook for Windows 中的新右侧面板通知，Microsoft 365 租户全局管理员和 Office 应用程序管理员将收到有关影响用户的 Outlook 和 O365 通知。 [了解更多](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **在 Outlook toast 通知中增加了额外的按钮：** 在 Windows 10 上运行 Outlook 时，Outlook toast 通知中会出现快速操作按钮

### <a name="powerpoint"></a>PowerPoint

- **改进了 PowerPoint 的流视频性能：** 我们对 Microsoft Stream 视频的回放性能进行了改进，以最小化视频加载时间，创造流畅的观看体验。 使用来自 Microsoft Stream 的企业视频来创建更好的演示文稿。

### <a name="teams"></a>Teams

- **外部用户屏蔽了 PSTN 参与者的电话号码：** 对于为 Teams 会议启用了音频会议的客户，我们将向自组织外部加入的用户屏蔽 PSTN 参与者的电话号码。

- **管理频道通知设置的简化方法：** 通过团队和频道列表或从频道标题中，用户可以通过单击打开或关闭所有活动或深入了解自定义项来设置其首选排列，从而快速管理其通知设置。

- **Walkie Talkie：** 使用“按下即可发言”进行即时语音通信。


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 我们修复了一个问题，即执行查询大约花费两倍于预期完成时间。


### <a name="excel"></a>Excel

- 修正了以下问题：保存到 SharePoint / OneDrive 时，自定义功能区标签的CustomUI XML被删除。


### <a name="outlook"></a>Outlook

- 解决了导致用户看到通过拖放复制到其文件系统的附件的创建日期设置为 4501 年 1 月 1 日的问题。

- 解决了导致共享日历改进用户看到日历故障的问题。


- 解决了导致用户看到 Outlook 不断提示他们运行收件箱修复工具的问题。


- 解决了启用云设置时导致Ctrl+click停止工作的问题。


- 解决导致在中搜索功能的问题，该问题建议一项功能返回没有结果，使用户没有选择提交一个新功能想法。


### <a name="project"></a>Project

- 修复了以下问题：如果 URL 以 ".com" 结尾，则无法在 Project 桌面端 Project Web App 中打开项目。


- 修正了当项目摘要任务(项目开始/任务字段)发生更改时，ProjectBeforeTaskChange事件没有触发的问题。


- 修正了当任务被错误地标记为100%完成，将其更改为小于100%完成的问题。


### <a name="word"></a>Word

- 解决了当URL包含查询组件时从自定义文档传递(aspx)打开Word文档的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2005-june-24"></a>版本 2005：6 月 24 日
*版本 2005（内部版本 12827.20470）*

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 现在，此错误已修复；您应该可以在代码中调用“日期/时间扩展”数据类型，而不会在应用程序中遇到任何崩溃。 如果您遇到其他问题，请告知团队。


- 此问题现已修复。现在可以还原到最近更新的 Access 版本，并可使用 DAO/VBA 管理和编辑十进制数据类型。 如果在使用我们的数据类型时遇到任何其他问题，请告知 Access 团队。


### <a name="excel"></a>Excel

- 修正了以下问题：保存到 SharePoint / OneDrive 时，自定义功能区标签的CustomUI XML被删除。





### <a name="outlook"></a>Outlook

- 解决了针对 Outlook 未能向使用M365 Business Plus计划的付费用户启用数据丢失保护策略提示的问题。


- 解决了导致用户看到通过拖放复制到其文件系统的附件的创建日期设置为 4501 年 1 月 1 日的问题。


- 解决了导致用户在更新 Outlook 中的“规则”时看到“&quot;此计算机上的规则与 Microsoft Exchange 上的规则不匹配&quot;”消息的问题。


- 解决了导致共享日历改进用户看到日历故障的问题。


- 解决了导致用户在某些情况下遇到间歇性挂起和崩溃的问题。


- 解决了导致用户看到 Outlook 不断提示他们运行收件箱修复工具的问题。


- 解决导致在中搜索功能的问题，该问题建议一项功能返回没有结果，使用户没有选择提交一个新功能想法。


### <a name="powerpoint"></a>PowerPoint

- 我们已修正了“建议”窗格崩溃的问题。


### <a name="project"></a>Project

- 修正了当任务被错误地标记为100%完成，将其更改为小于100%完成的问题。

### <a name="word"></a>Word

- 解决了可能导致在拖动应用中的某些内容时发生故障的问题。


### <a name="office-suite"></a>Office 套件

- 此更改解决了加载和播放动画内容（如 Gif 或 3D 模型）时可能挂起的情况。




[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2005-june-09"></a>版本 2005：6 月 9 日
*版本 2005（内部版本 12827.20336）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 解决了在试图将数据透视表插入图表工作表时 Excel 可能会发生故障的问题。

### <a name="powerpoint"></a>PowerPoint

- 这修复了当用户在文件中同时拥有现代和遗留评论时的故障，从而触发对评论的升级。

### <a name="project"></a>Project

- 修正了当项目摘要任务(项目开始/任务字段)发生更改时，ProjectBeforeTaskChange事件没有触发的问题。

### <a name="office-suite"></a>Office 套件

- 我们通过设置Bing插件安装验证默认为真实，并使MSI返回成功视为安装成功，解决了ValidateInstall失败率问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2005-june-02"></a>版本 2005：6 月 2 日
*版本 2005（内部版本 12827.20268）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自动使用新数据类型**：当您键入类似于股票或地理位置的数据值时，Excel 将其转换为适当的关联数据类型：股票或地理位置。 [了解更多](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **使用动态 Gif 讲述故事：** 现在，Office 编辑器支持动画 Gif，你的文档更漂亮

### <a name="outlook"></a>Outlook

- **帮助保护组中的数据：** 你在创建组时选择的敏感度标签应用于组电子邮件、文档和团队网站

- **更好的结果 - 瞬间完成：** 我们更新了搜索体验，使其更加智能、更快速，并且比以往更可靠。 [了解更多](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **使用动态 Gif 讲述故事：** 现在，Office 编辑器支持动画 Gif，你的文档更漂亮

- **改进日历：** 可查看视觉对象更新，以便更轻松地扫描日历。 [了解更多详细信息](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />在[博客文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看详细信息

### <a name="powerpoint"></a>PowerPoint

- **使用动态 Gif 讲述故事：** 现在，Office 编辑器支持动画 Gif，你的文档更漂亮[了解更多信息](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

- **演示时同步所做的更改：** 即使演示文稿处于幻灯片放映模式，只要进行了更改就同步这些更改。 [了解更多详细信息](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />在[博客文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看详细信息

- **无需遥控器：使用耳塞即可：** 使用 Surface Earbuds 来控制 PowerPoint 演示文稿。 工作原理：配对后，需要在 PowerPoint 中启用此功能。 通过按 F5 或选择“幻灯片放映” > “从头开始”开始演示。  在幻灯片放映中，右键单击幻灯片，然后在“ Surface Earbuds 设置”下选择“使用手势控制演示”。  在以后的所有演示中都会记住此设置。 现在可以在左侧耳机上向前向后滑动，以在幻灯片放映模式中浏览演示文稿。  双击播放或暂停嵌入视频。  重要提示：必须使用 Windows 10 的 Surface Audio 应用配对 Surface Earbuds，才能使用手势控制演示文稿。 此处提供了有关 Windows 10 上的 Surface Audio 应用入门的说明。 [了解更多](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a>Teams

- **更换为 Teams 会议中的视频版式：** 很快，在 Teams 会议中可以同时查看的与会人员将从 4 人增加到 9 人。

- **直播活动中包含音频系统：** 现在，直播活动中的演示者和制作人可以在直播活动中共享桌面或窗口屏幕时包括系统音频。 这将使您的用户听到所共享内容的任何音频部分。

- **使组织者能够更改拨号参与者的会议厅设置：** 此设置控制通过电话拨入的用户是否直接加入会议或在大厅中等待，无需考虑 “自动允许人员” 设置。

- **在会议中举手：** 用户现在可以在会议中举起虚拟手！ 其他与会者将在会议台的姓名旁或名册的姓名旁看到你举起的手。

- **自定义会议视频背景：** 使用视频会议时，现可选择不同的静态背景图像。 这将让你显示此图像，而不是你所坐位置的实际背景。

- **添加更多人员至聊天：** 现在，我们可以在一个聊天线程中最多添加 350 人。

- **活动源“设置”齿轮：** 用户现在可以通过设置齿轮直接从源左栏访问活动源和通知设置。

- **轻松从进行中的 Teams 会议访问选项：** Teams 会议开始后，我们通过直接在参与者窗格中提供易于访问的链接，使会议组织者更快、轻松地更改其演示者和会议厅设置。 此新功能将同时出现在预定会议和“立即开会”会议中。

- **团队和频道分析：** 除团队分析之外，现在还可以查看频道级别的指标和见解。 我们还将时间范围延长到 90 天，因此可以分析更长的数据。 除此之外，此版本还包括有关团队或渠道的文章、回复和会议数量的新指标和图表。

- **进入/退出公告：** 我们添加了此功能，使会议组织者可以打开或关闭进入和退出会议的公告。

### <a name="word"></a>Word

- **无需退出 Word 即可解码首字母缩写词：** 遇到首字母缩写词时，Word 将会根据其他人的使用情况定义它。

- **使用动态 Gif 讲述故事：** 现在，Office 编辑器支持动画 Gif，你的文档更漂亮


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题

### <a name="excel"></a>Excel

- 修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。

- 在某些情况下，单击指向同一工作簿内某个位置的超链接将导致工作簿被隐藏。

### <a name="outlook"></a>Outlook

- 解决了关于回复/转发标签的clp审核事件的问题。

- 解决了导致 Windows 10 服务器版本的用户看到警告 “防病毒状态:无效”的问题。 此版本的 Windows 支持防病毒检测，但没有发现防病毒，尽管已正确安装防病毒。

- 解决了用户在提交来自管理通知的反馈时故障的问题。

### <a name="skype"></a>Skype

- 当用户被告知只能使用团队的策略时，他们仍然可以使用Skype for Business Outlook 插件来安排会议。 在此更新之后，当客户端读取指示用户为仅限团队的策略并进入仅限会议加入模式后，你将不再能够为Skype安排商务会议。 另外，如果 Skype for Business Outlook 插件在启动时看到 Skype for Business客户端处于会议加入模式，它将不会激活自己。

### <a name="office-suite"></a>Office 套件

- 此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。

- 此更新修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。

- 当注册表键HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth被设置为零时，正在激活一个外接程序时，windows中的office主机故障。 此更改可修复此问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2004-may-21"></a>版本 2004：5 月 21 日
*版本 2004（内部版本 12730.20352）*

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修复了以下问题：在文件重新打开后，如果文件路径太长，外部链接会停止工作。


### <a name="outlook"></a>Outlook

- 解决了用户在提交来自管理通知的反馈时故障的问题。


### <a name="office-suite"></a>Office 套件

- 修复了会导致最新版本偶尔导致更新失败的即点即用问题。

- 修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2004-may-12"></a>版本 2004：5 月 12 日
*版本 2004（内部版本 12730.20270）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="outlook"></a>Outlook

- 解决了导致用户在显示 toast 通知时遇到崩溃的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2004-may-04"></a>版本 2004：5 月 4 日
*版本 2004（生成号 12730.20250）*

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="office-suite"></a>Office 套件

- 此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2004-april-29"></a>版本 2004：4 月 29 日
*版本 2004（生成号 12730.20236）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在“查询设计器”、“SQL 视图”和“关系”窗口中更高效地工作：** 右键单击表格，以对其进行打开、设计、调整大小和隐藏操作。 在 SQL 视图中搜索和替换文本。 在“关系”窗口中选择多个表。

- **单击几下即可添加表：** 使用“添加表”任务窗格（在你工作时一直打开）向关系和查询添加表。 [了解详细信息](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a>Excel

- **Facebook 连接器支持即将结束：** 从 2020 年 4 月开始，Excel 将不再支持使用 Facebook 连接器的外部数据连接。

- **有问题？询问 Excel：** 现在，Excel Ideas 允许您提出有关数据的问题，无需花费时间编写公式（仅英语）。 [了解更多](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **新图像让工作簿变得生动有趣：** 可在工作簿中使用数以千计的免版税库存图像、图标和贴纸。 转到“插入”>“图片”>“库存图像”以开始使用。 [了解详细信息](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a>Outlook

- **不退出收件箱加入会议：** 无需切换至日历以加入联机会议。 通过固定日历至待办事项窗格，只需单机一次即可加入任何会议。

- **新图像让邮件变得生动有趣：** 可在电子邮件中使用数以千计的免版税库存图像、图标和贴纸。 转到“插入”>“图片”>“库存图像”以开始使用。 [了解更多](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- **定期会议的位置建议支持：** 搜索安排定期会议的会议室。

### <a name="powerpoint"></a>PowerPoint

- **在幻灯片放映期间更新幻灯片：** 在演示期间更新其他作者更改的幻灯片。

- **新图像让幻灯片变得生动有趣：** 可在演示文稿中使用数以千计的免版税库存图像、图标和贴纸。 转到“插入”>“图片”>“库存图像”以开始使用。 [了解详细信息](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a>Teams

- **Teams 日历改进：** 右键单击日历中的项以提取 RSVP 选项、开始与与会者交谈，或在会议开始时快速加入会议。 此外，我们还对事件计划窗体进行了改进。

- **没错，就是你!：** 创建标签并向其分配人员，以便你可以@提及组、角色、部门等。Teams 所有者们，亲自体验下吧。 转到团队，选择“更多”选项，然后选择“管理”标签。

### <a name="word"></a>Word

- **使工具易于使用：** 在绘图工具箱中，查找可向文本添加墨迹手势的智能笔。 [了解详细信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **新图像让文档变得生动有趣：** 可在文档中使用数以千计的免版税库存图像、图标和贴纸。 转到“插入”>“图片”>“库存图像”以开始使用。 [了解更多](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 在 Excel 2016 中保存并且含有数字签名的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。

- 修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 崩溃。

- Application.Evaluate (VBA) 在某些情况下不能用于用户定义的函数。

### <a name="outlook"></a>Outlook

- 解决了导致文件夹窗格宽度意外改变的问题。


- 解决了导致 Outlook 在某些版本的 Windows 上崩溃的问题。


- 解决了 Windows 更新后导致 Outlook 在打开本地保存的 .msg 或 .oft 文件时出现崩溃的问题。


- 解决了导致 Outlook 在某些版本的 Windows 上崩溃的问题。


- 解决了导致用户在退出 Outlook 时遇到挂起的问题。


### <a name="project"></a>Project

- 在窗体视图中编辑前置/后续数据时，会触发额外的 ProjectBeforeTaskChangeevent 事件。


- 修复了以下问题：如果你使用的是连接到 Project Web App 的 Project，并且小数分隔符是逗号，则当你尝试向依赖项添加延迟时，TaskDependencies Add 方法将失败。

### <a name="office-suite"></a>Office 套件

- 解决了阻止同时使用密码限制访问和保护文件的错误。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-april-15"></a>版本 2003：4 月 15 日
*版本 2003 （内部版本 12624.20466）*
* 各种 bug 和性能修补程序。

## <a name="version-2003-april-14"></a>版本 2003：4 月 14 日
*版本 2003（内部版本 12624.20442）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- Application.Evaluate (VBA) 在某些情况下不能用于用户定义的函数。

### <a name="outlook"></a>Outlook

- 解决了在使用鼠标上的 "X" 按钮时导致用户偶尔遇到崩溃的问题。

### <a name="project"></a>Project

- 在窗体视图中编辑前置/后续数据时，会触发额外的 ProjectBeforeTaskChangeevent 事件。

### <a name="word"></a>Word

- 解决了在使用鼠标上的 "X" 按钮时导致用户偶尔遇到崩溃的问题。


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-march-31"></a>版本 2003：3 月 31 日
*版本 2003（内部版本 12624.20382）*

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="onenote"></a>OneNote

- 通知用户有关 Microsoft OneNote 中的暂时调整的信息栏，可有助于提升全球范围内使用期间的同步和服务可用性。

### <a name="project"></a>Project

- 修复了下列问题：启用保护实际工作的设置后，用户无法输入按时间分段的基准工作。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2003-march-25"></a>版本 2003：3 月 25 日
*版本 2003（内部版本 12624.20320）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **将电子邮件拖动到你拥有的组：** 通过从收件箱中拖动来移动和复制邮件和对话。 将与所有组成员共享你拖动的消息。

- **强制 wifi 网络新体验：** 是否已加入需要使用网页登录的 wifi 网络？ 现在，Outlook 检测到这一点，帮助你进行连接。

### <a name="word"></a>Word

- **其他人可以快速查看你所做的更改: **共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。

### <a name="office-suite"></a>Office 套件

- **敏感度标签：** 你现在可以应用组织已配置的敏感度标签来提示自定义权限。


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 在某些情况下，重新打开嵌入 Word 或 PowerPoint 的工作簿时，Excel 会崩溃。

- 解决了如果关闭了源代码簿，则外部链接不会在填充时更新的问题。

- 解决了从模板创建图表时出现的性能问题。

### <a name="onenote"></a>OneNote

- 通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。 对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入 OneNote。

- 通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。

### <a name="outlook"></a>Outlook

- 解决了导致用户在退出后在任务管理器中看到 Outlook 进程延迟的问题。

### <a name="powerpoint"></a>PowerPoint

- 改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。


### <a name="project"></a>Project

- 解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。

- 解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。

- 解决了以下问题：在标记为完成后，任务完成百分比错误地更改为小于 100% 完成。

- 修复了有时无法正确计算摘要任务日期的问题。


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-march-10"></a>版本 2002：3 月 10 日
*版本 2002（生成号 12527.20278）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="project"></a>Project

- 修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-march-01"></a>版本 2002：3 月 1 日
*版本 2002（内部版本 12527.20242）*

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="outlook"></a>Outlook

- 解决了导致第三方应用程序无法发送电子邮件的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-february-25"></a>版本 2002：2 月 25 日
*版本 2002（内部版本 12527.20194）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **工作簿统计信息：** 单元格、公式、图表、表格... 我们将对其进行计数，无需进行此操作。

- **查询编辑器中的数据分析：** 快速分析列中的数据、确定错误和空值、查看分发直方图等。


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修复了 CUBEVALUE 函数有时会返回错误结果的问题。

### <a name="outlook"></a>Outlook

- 解决了在会议的位置字段中导致逗号变为分号的问题。

- 解决了在多个窗口中查看同一项目时可能会导致崩溃的问题。

- 解决了一个问题，该问题导致在某些情况下无法使用相关选项来禁用标记项目突出显示。

- 解决了导致 Outlook 在同步滑块设置为较小的设置时出现意外同步所有邮件的问题。


- 解决了具有黑色主题的用户在“发件人”下拉列表中看到白色背景上显示白色文本的问题。


- 此更改恢复了在邮件头中查看多行主题的功能。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-february-19"></a>版本 2001：2 月 19 日
*版本 2001（内部版本 12430.20288）*
* 各种 bug 和性能修补程序。

## <a name="version-2001-february-11"></a>版本 2001：2 月 11 日
*版本 2001（内部版本 12430.20264）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- Access 模板将不会再导致数据库中的附件列出现故障。 在实例化模板后，你现在应该可以将附件字段添加到数据库中。

### <a name="excel"></a>Excel

- 修复了未显示上下文菜单中的批注命令的问题。

- 修复了一个问题，该问题导致某些用户在将文本转换为包含单元格（具有溢出数组）的列时遇到崩溃。


### <a name="outlook"></a>Outlook

- 解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。


- 解决了导致用户在取消帐户设置时遇到崩溃的问题。


### <a name="project"></a>Project

- 修复了以下问题：固定持续时间类型的 100％ 任务可能会错误地将其完成百分比计算为小于 100％ 完成。


### <a name="office-suite"></a>Office 套件

- 此更改解决了所报告的使用 Intel 集成 GPU 的图形适配器的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-january-30"></a>版本 2001：1 月 30 日
*版本 2001（内部版本 12430.20184）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。

- **向左看，向右看… XLOOKUP 在此！** 使用 XLOOKUP 在表或区域中逐行查找所需内容。 [了解更多](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a>Outlook

- **高级组电子邮件设置：** 此功能可帮助组用户自定义要在收件箱中接收/关注的电子邮件或事件。

- **组命名策略：** 组命名策略使 IT 管理员能够标准化管理组织中由用户创建的组名。 管理员可以要求在创建组时向名称添加特定前缀和后缀，并阻止使用指定的字词。 这有助于尽可能在组名中减少使用不适宜的字词，以及有助于IT部门在目录中管理组的显示方式。 命名策略还可有助于组织根据部门部署团队网站，以进行分类。

### <a name="word"></a>Word

- **更安全的视频体验：** 安全增强意味着更安全的联机视频体验。 [了解更多](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **用套索选择墨迹：**“绘图”选项卡上的“套索”工具可帮助你选择用墨迹绘制的对象。 选择单独的笔划或整个字。 [了解更多](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 此更新修复了使用 ADODB 的问题。 VB 代码中的记录器对象可能会错误地报告错误。


- 此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。


### <a name="excel"></a>Excel

- 解决了导致用户在对签名进行重命名时发生崩溃的问题。


### <a name="outlook"></a>Outlook

- 解决了导致用户在对签名进行重命名时发生崩溃的问题。


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-january-22"></a>版本 1912：1 月 22 日
*版本 1912（内部版本 12325.20344）*

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-january-14"></a>版本 1912：1 月 14 日
*版本 1912（内部版本 12325.20298 ）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新

## <a name="version-1912-january-08"></a>版本 1912：1 月 8 日
*版本 1912（内部版本 12325.20288）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新

### <a name="outlook"></a>Outlook

- **将易访问邮件发送给最需要的人员：** Outlook 将显示邮件提示，以帮助确保在向喜欢易访问内容的用户发送邮件时可访问你的内容

### <a name="powerpoint"></a>PowerPoint

- **全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。

- **GIF 瞬间完成：** 一幻灯片、一帧。 轻松在 PowerPoint 中创建循环 GIF。 [了解更多](https://support.office.com/zh-CN/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。

### <a name="outlook"></a>Outlook

- 解决了导致会议位置在清除后意外添加回会议的问题。

- 解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。

- 解决了在某些情况下导致用户看到电子邮件发送地址与显示的 SMTP 地址不匹配的问题。

- 解决了导致用户在检索云设置时在 Outlook 中遇到挂起的问题。

### <a name="word"></a>Word

- 构建基块管理器可能显示无效的警报：“你已更改样式、构建基块”。

### <a name="office-suite"></a>Office 套件

- 解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。

[//]: # (请勿移除错误详细信息内容结尾)

> [!NOTE]
> 如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。

[//]: # (不修改管理中心元数据内容启动)
[//]: # (|Win32|CC|生产| |16.0.13001.20384|2006 年 7 月 14 日版|)
[//]: # (|Win32|CC|生产| |16.0.13001.20266|2006 年 6 月 30 日版|)
[//]: # (不修改管理中心元数据内容结束)
