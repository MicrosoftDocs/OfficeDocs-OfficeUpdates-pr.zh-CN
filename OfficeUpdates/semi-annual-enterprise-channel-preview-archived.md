---
title: 有关 2019 年半年频道（已设定目标）发行的已存档发行说明
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2019 年 Office 365 专业增强版半年频道（已设定目标）发行的发行说明
ms.openlocfilehash: 2b9b90ef7e1d9bc792be381ba35a94f883156e90
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169601"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>有关半年企业频道（预览）的已存档发行说明

这些发行说明提供了 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 商业版的半年企业频道（预览）更新中所包含的新功能和非安全更新的相关信息。

> [!NOTE]
> - 我们经常会过一段时间就将功能（有时甚至是修补程序）发布到半年企业频道（预览）。 如果没有立即看到下述内容，则很快就会看到的。 [了解更多](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams 包含在半年企业频道（预览）的新安装中，从版本 1902 开始。 当半年企业频道（预览）的现有安装更新到版本 1908 或更高版本时，将向现有安装添加 Teams。 有关详细信息，请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](/deployoffice/teams-install)。

## <a name="version-1908-december-10"></a>版本 1908：12 月 10 日
*版本 1908（内部版本 11929.20516）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 修复了包含对远程表（例如 SQL Server 表）的引用的联合查询可能导致 Access 关闭并重新启动的问题。

- 修复了诸如“总和”等聚合可能将结果截断为整数值的问题。

### <a name="excel"></a>Excel

- 解决了在滚动后选择单元格时可能导致选择错误单元格的问题。

- 我们修复了当 OLAP 数据透视表的筛选器设置为已从多维数据集中删除的值时的问题。

- 此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。

- 解决了 Lookup 函数可能返回错误的问题。

- 显著提高了删除包含合并单元格的列时的性能。

- 解决了导致激活最小化窗口的宏运行时错误的问题。

### <a name="outlook"></a>Outlook

- 解决了 SMIME 算法选择方面的问题。

- 解决了导致用户在打开“规则”对话框时看到&quot;此计算机上的规则与 Microsoft Exchange 上的规则不匹配&quot;提示的问题。

- 解决了导致 Web 加载项在不应该访问“数字版权管理”消息时访问它们的问题。

### <a name="word"></a>Word

- 我们修复了跟踪更改有时会陷入无限循环的问题。

### <a name="office-suite"></a>Office 套件

- 修复了在 PowerPoint 中的竖排文本框中，半角片假名字符未正确旋转的问题。

- 解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。

- 为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-22"></a>版本 1908：11 月 22 日
*版本 1908（内部版本 11929.20494）*


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题

### <a name="access"></a>Access

- 已修复关于运行更新查询会错误地给出“查询已损坏”错误消息的问题。

### <a name="excel"></a>Excel

- 当文件具有大量条件格式时，单击“字体颜色”按钮时会出现性能较低的问题。

- 我们修复了打印预览中的打印区域不正确的问题。

- Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。

- 解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。

### <a name="outlook"></a>Outlook

- 解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“&quot;确定&quot;”按钮的空白消息框的问题。

- 进行更改后，管理员能够启用策略以便在自动发现身份验证提示中首选提供的帐户电子邮件而不是 UPN。 默认情况下，自动发现优先于帐户 UPN（如果可用）。

- 解决了导致用户无法在现代组中查看搜索的问题。

- 解决了导致用户尝试从&quot;错过的对话&quot;消息创建规则时遇到崩溃的问题。

- 解决导致用户无法在现代组中查看搜索的问题。

### <a name="word"></a>Word

- 我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题。

### <a name="office-suite"></a>Office 套件

- 修复了防止 PowerPoint 用户在尝试联机演示时遇到错误的问题。

- 改进了有关注册表完整性的 Office 更新进程的可靠性。

- 更正了按流量计费的网络上可能意外阻止更新的问题。

- 修复了 ODT 和 GPO Updae Deadline 设置中相对截止日期仅在第一次设置时起作用，修复程序为后续更新启用相对截止日期的问题。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-12"></a>版本 1908：11 月 12 日
*版本 1908（内部版本 11929.20436）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题

### <a name="excel"></a>Excel

- 修复了使用图表模板插入图表时预览中所用颜色的问题。
- 我们修复了在更改系列集合时可能导致散点图和折线图无法正确呈现的问题。
- 解决了在使用运行的宏更改自定义属性时导致共同创作中断的问题。
- 我们解决了异步用户定义函数的性能问题，该问题导致它们同步运行。
- 我们显著提高了按颜色筛选的性能。
- 解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。
- Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。

### <a name="outlook"></a>Outlook

- Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。
- 解决了在将用户主日历中的项复制到组日历时出现导致用户遇到权限错误的问题。
- 解决了导致非常长的 Outlook 会话出现内存泄漏的问题。
- 解决了导致用户在 Outlook 中与特定安全链接交互时遇到失败的问题。
- 解决了导致用户在处理某些自动发现响应时遇到失败的问题。
- 解决了导致某些用户在添加辅助 Exchange 帐户时会看到创建重复的特殊文件夹的问题。
- 解决了导致搜索反馈体验挂起的问题。

### <a name="powerpoint"></a>PowerPoint

- Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。
- 可靠性修复：修复了第三方加载项可能导致 PowerPoint 失败的问题。

### <a name="project"></a>Project

- 修复了“全部调配”命令无法正确解决资源过度分配的问题。
- 修复了以下问题：如果你的任务分配为零工作，该任务可能无法标记为已完成，并且始终显示为 99％。
- 发现了用户在打开只读项目时可能会收到几则消息的问题。

### <a name="word"></a>Word

- Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。
- 修复了应用可能会在关闭时挂起的各种问题。 此外，修复了某些与加载项相关的失败。

### <a name="office-suite"></a>Office 套件

- 解决了与第三方插件中的“文本框/形状自动调整”属性相关的问题。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="october-15"></a>10 月 15 日

### <a name="non-security-updates"></a>非安全更新

### <a name="office-suite"></a>Office 套件
- 我们暂时禁用了“云保存”对话框，以解决了我们在 2019 年 10 月 14 日对 16.0.11929.20396 之前的内部版本发布的保存问题。 此功能很快将重新启用。

## <a name="version-1908-october-14"></a>版本 1908：10 月 14 日
*版本 1908（内部版本 11929.20396）*


[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div>解决了一个“查找和替换”问题，即在找到第一个项目后它改变了对话框中焦点的位置。</div>

### <a name="office-suite"></a>Office 套件

- 解决了对于 16.0.11929.20396 之前的内部版本而言，用户可能无法保存 Word、Excel 和 PowerPoint 2019 文档的问题。  此问题会影响创建新文件并在单击“保存”图标或按 Ctrl+S 后显示“另存为”对话框的用户。

- 解决了一个问题，即在某些情况下，Office 快捷方式可能会在更新后消失。  此更新改进了发布 Office 快捷方式的可靠性。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-october-08"></a>版本 1908：10 月 8 日
*版本 1908（内部版本 11929.20388）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- 解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。

- 修复了在加载项管理器中浏览时允许显示超过 16 个加载项的问题。

- 修复了在 Excel 创意功能中发现一个的问题，即通过单击 Win32 客户端中的“创意”按钮加载加载项时出错。

### <a name="outlook"></a>Outlook

- 解决了导致简单悬停 URL 无法显示某些安全链接的问题。

- 已将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。

- 解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。

### <a name="powerpoint"></a>PowerPoint

- 修复了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。

### <a name="office-suite"></a>Office 套件

- 修复了用户打开文件时可能遇到的崩溃问题。

- 修复了在后台的信息放置面板中未显示可访问性信息的问题。

- 通过恢复以前可能已中断的下载，增强了下载 Office 更新时的可靠性。

- 为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-september-10"></a>版本 1908：9 月 10 日
*版本 1908（内部版本 11929.20300）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **缩放更多空间：** 让缩放框变大，更改字体，缩放功能会记住一切。 [了解更多](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **密切关注数据库对象：** 可以清楚地看到活动选项卡，轻松拖动选项卡以重新排列它们，并且只需单击一下即可关闭数据库对象。

- **无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。 帐户之间可轻松自如切换。 [了解更多](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **深入发掘数据：** 全新的“想法”按钮可查找数据中的模式并使用这些模式创建智能、个性化的建议。[了解详细信息](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **快速找到文件：** 正在寻找你最近使用过的文件？ 只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。

- **增加内容的覆盖面：** 需要让你的演示文稿易于访问？ 让辅助功能检查器随时进行关注，但不妨碍到你。 通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。

- **无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。 帐户之间可轻松自如切换。 [了解更多](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **见证工作表生动起来的过程：** 插入动态 3D 图形，观看心跳、行星轨道和霸王龙在整个工作簿中四处跳动。 [了解详细信息](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **协作更简单：** 共同创作改进意味着使用条件格式、单元格样式等时，所做的更改将与协作者无缝合并。

- **在类似列上连接表：** 在比较用于合并表的列时，获取和转换 (Power Query) 现在具有近似文本匹配逻辑（也称为模糊匹配）。 [了解更多](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **使用 Power Query 增强功能快速编码：** 使用自动完成和语法着色快速完成代码编写。 也可以轻松发现函数、列和参数。

- **搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。 选择时，“插入”按钮会显示已选数目。 [了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **移动邮件时继续工作：** Outlook 现在在后台移动邮件，因此你可以在文件夹之间移动大量邮件时继续工作。

- **在连续召开的会议之间提供时间：** 默认将会议设置为提前 5-10 分钟结束，让与会者有时间喘口气或来往于不同地点。

- **清晰呈现思路：** 当文本或静态图像不起作用时，请使用动态 GIF 来发表你的观点。[了解详细信息](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **我们已经为你更新了 Outlook 用户体验：** 简化的体验，以前可供预览，现即将推出，旨在帮助你关注最重要的内容。 [了解更多](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **更紧凑还是更宽松的布局？由你决定：**“更紧凑的间距”让你能够决定是希望项目之间间距更大，还是希望布局更紧凑以显示更多内容。

- **还可自定义的简化功能区：** 最常用的按钮排成一行，带给你简化体验。 可在经典视图和简化视图之间轻松切换，还可固定/取消固定命令。 [了解详细信息](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **添加帐户的更快捷方式：** 由于帐户设置改进，现在可以更轻松地将使用双重身份验证的 Outlook.com 和 Gmail 帐户添加到 Outlook。 [了解更多](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **挑选你喜欢的操作：** 不要使用“标志”和“删除”？ “存档”或“标记为已读”呢？ 使用你最常用的命令自定义快速操作菜单。

- **告别同步限制：** Outlook 改进意味着文件夹限制已取消，因此请继续操作并同步共享邮箱。

- **搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。 选择时，“插入”按钮会显示已选数目。 [了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **邀请受众参加测验或调查：** 幻灯片上放入测验或调查。Office 为你收集并存储该响应。[了解详细信息](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **快速找到文件：** 正在寻找你最近使用过的文件？ 只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。

- **增加内容的覆盖面：** 需要让你的演示文稿易于访问？ 让辅助功能检查器随时进行关注，但不妨碍到你。 通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。

- **在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。

- **比以往更轻松地插入联机视频：** 想要将 Vimeo 或 YouTube 中的视频放到幻灯片上？只需使用视频页面链接即可。[了解详细信息](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **切换效果更好：** 对形状命名，以更好地掌控其平滑效果。 [了解详细信息](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。 帐户之间可轻松自如切换。 [了解更多](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **联机视频获得新的存储位置：** 将视频保存到 Microsoft Stream，以便组织中的任何人都可以看到它。 插入视频链接，只需占用相当于相应文件大小的一小部分的空间，即可享受多媒体演示。 [了解更多](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。 选择时，“插入”按钮会显示已选数目。 [了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。 帐户之间可轻松自如切换。 [了解更多](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **告别断开的 Excel 链接：** 找不到链接到 Data Visualizer 图表的 Excel 工作簿？ 重新链接，你又可以开工了。[了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **内置 Azure 模具：** 使用数十个 Azure 模具设计云应用或规划基础结构。 [了解更多](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **数据流程图上的 Double-take：** 数据可视化工具流程图上引入注目的新布局干净、清爽且易于理解。 单击“设计”选项卡可查看选项。

- **无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。 帐户之间可轻松自如切换。 [了解更多](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **将流程图导出至 Word：** 向 Word 文档自动添加流程图内容，如形状和元数据。 然后自定义文档以创建过程指南和操作手册。 [了解更多](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **从 Power BI 导出 Visio 视觉对象：** 将 Power BI 导出为 PDF、PowerPoint 文件等时，Power BI 的 Visio 视觉对象现在将会正常显示。 [了解更多](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **使用笔迹编辑器随心编辑：** 使用单个笔划、拆分或连接字词、添加新行或使用手写笔插入字词。[了解详细信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **将文档从静态转换为惊艳：** 将文档转换为易于共享的交互式网页，使其在任何设备上都看起来很棒。[了解更多](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **使用 \@提及功能引起他人的注意：** 在批注中使用 @提及，以在需要他人的意见时让他们知悉。 [了解详细信息](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **使用 Line Focus 提高理解力：** 专心地逐行浏览文档。调整焦点，一目一行、三行或五行。[了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **快速找到文件：** 正在寻找你最近使用过的文件？ 只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。

- **在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。

- **增加内容的覆盖面：** 需要让你的文档易于访问？ 让辅助功能检查器随时进行关注，但不妨碍到你。 通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。

- **“学习工具”模式可额外支持更多页面颜色：** Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。 许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。

- **无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。 帐户之间可轻松自如切换。 [了解更多](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- **搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。 选择时，“插入”按钮会显示已选数目。 [了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Office 套件

- **Microsoft Teams 的安装：** 向 Office 365 专业增强版的现有安装添加了 Teams。 [了解更多](/deployoffice/teams-install)

- **在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。

- **隐私控制：** 对诊断数据和连接体验的全新、更新和改进控制。 [了解更多](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Office 图标具有新的外观：** Office 图标经过重新设计，可体现简单、强大和智能的 Office 体验。

- **Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。 [了解更多](/DeployOffice/teams-install)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- 修复了 Excel 中的问题，其中分配给形状或表单控件的宏可能显示不正确的错误消息，或者可能在不正确的目标区域中工作。

- 修复了以下问题：在更改数据透视表的排序方式并在与其他用户进行共同创作会话期间刷新它时可能会导致其失败。

- 解决了导致瀑布图和漏斗图无法在插入或删除单元格时与表格同步的问题。

- 已修复了 Excel 中的合并冲突问题，该问题会导致系统提示用户重新打开工作簿以使更改生效。

- 解决了在与其他人共同创作时表旁边的剪切和粘贴操作失败的问题。

### <a name="outlook"></a>Outlook

- 修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得与其 Outlook 配置文件关联的错误帐户的问题。

- 解决了导致部分 POP3 用户看到无论设置如何，其所有电子邮件均采用纯文本格式的问题。 此修补程序将还原 HTML 格式邮件的视图。

- 解决了导致用户无法通过屏幕阅读器访问位置建议的问题。

- 已修复导致某些用户在尝试检索 Outlook 的云设置时遇到身份验证错误的问题。

- 解决了导致经理不清楚代理人是否已响应指定的会议请求的问题。

- 修复了导致 Outlook 用户在某些情况下“需要密码”的问题。

- 解决导致当前文件夹搜索间歇性失败的问题。

- 解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。

- 修复了导致用户在使用云附件时看到错误“无法找到此文件。 验证路径和文件名是否正确”的临时服务问题。 [了解更多](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- 修复了以下问题：用户看到从 Outlook 上传到 OneDrive 或 Sharepoint 的文件名已更改，其中多个字符替换为下划线。

- 已修复非英语用户邮件中的主题行非常小的问题。


### <a name="powerpoint"></a>PowerPoint

- 修复了某些加载项会在图表中的形状周围引发意外错误的问题。

- 修复了还原 PowerPoint 视频控件易于访问的名称的问题。

- 修复了可能阻止某些动画启动的问题

### <a name="project"></a>Project

- 修复了 Windows 7 上的用户能够从 Project Web App 和 SharePoint 网站打开项目的问题。


### <a name="visio"></a>Visio

- 从 Visio 导出到 SVG 的操作无法用于各种形状。

### <a name="word"></a>Word

- 修复了用户在 Word 文档中与他人协作时收到错误消息的问题。

- 修复了一个问题，该问题导致用户在尝试共享存储在 SharePoint 2016 上的文件时收到消息“抱歉，无法我们共享此内容”。


### <a name="office-suite"></a>Office 套件

- 解决了以下问题：在某些情况下，同步引擎支持的 sharepoint 文件可能显示“已保存”，但并未真正保存任何更改。

- 修复了大型树视图失败的问题。

- 修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-august-13"></a>版本 1902：8 月 13 日
*版本 1902（内部版本 11328.20392）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新

### <a name="excel-non-security-updates"></a>Excel：非安全更新
- 修复了表中针对已筛选切片器和未筛选切片器均显示清除筛选器图标的问题。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
- 修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得错误的关联帐户的问题

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
- 修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
- 修复了 VBA 更新字段的速度缓慢的问题。
- 修复了打开某个 DOC 文件时系统表示该文件已损坏的问题。
- 修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
- 修复了在某些情况下设置 API 在 Office JavaScript 库中无法正常工作的问题[了解更多](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>版本 1902：7 月 9 日
*版本 1902（内部版本 11328.20368）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新


### <a name="excel-non-security-updates"></a>Excel：非安全更新
- 修复了删除已筛选的 excel 行时速度极慢的问题。
- 修复了双指滚动时会在工作表上留下灰色矩形印及 Excel 无响应的问题。


### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
- 解决了以下问题：用户偶尔看到 Outlook 插入英语拼音字母, 而不是将 IME 字符窗口保持打开状态以供选择中文字词。
- 解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。
- 解决了导致用户尝试打开会议系列而不是打开主系列异常的问题。
- 解决了导致用户看到“已删除项”文件夹中的项的到期日期计算错误的问题。


### <a name="teams-non-security-updates"></a>Teams：非安全更新

- 安装完成后，Teams 安装程序现在已有用于关闭自动启动的策略。


### <a name="visio-non-security-updates"></a>Visio：非安全更新

- 解决了 Visio 无法与 Office 365 搭配使时与 ActiveX 解决方案相关的问题，错误信息指示无法找到 riched20.dll。


### <a name="word--non-security-updates"></a>Word：非安全更新

- 修复了用于禁用模板搜索栏的 GPO 设置
- 修复了以下问题：在脱机并编辑仅限服务器的文档之后，用户丢失了部分更改。
- 改善了启用“文档属性”中“文档部件”时的性能
- 修复了从服务器首次下载修订可能失败的问题


### <a name="office-suite--non-security-updates"></a>Office 套件：非安全更新

- 解决了以下问题：在安装其他 Office 产品或语言包时，使用共享计算机激活的设备可能会意外恢复成基于用户的激活。
- 修复了代理身份验证作为 SYSTEM 运行时 Office 更新受阻的问题。
- 修复解决了 Office 加载项在用户配置文件更改时消失的问题。


## <a name="version-1902-june-11"></a>版本 1902：6 月 11 日
*版本 1902（内部版本 11328.20318）*
<br/>[此处](./microsoft365-apps-security-updates.md)列出安全更新

### <a name="excel-non-security-updates"></a>Excel：非安全更新
 - 解决了将包含 XML 映射的文件保存为 PDF 时导致崩溃的问题。
 - 解决了在加载包含无效工作表名称的工作簿时导致外部链接被删除的问题。
 - 解决了在 Excel 中使用照相机工具会导致电子表格挂起的问题。
 - 解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。
 - 解决了在工作表计算期间使用另一张工作表上的数组公式（具体取决于表）重新计算数据表时发生崩溃的问题。 
 - 解决了在未先签出文件的情况下阻止从 SharePoint 打开受密码保护的工作簿的问题。
 - 已进行更改，以确保在共享或切换“自动保存”时处理 BeforeSave 事件。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
 - 解决了在向“分组依据”添加第 2 个条件时导致客户看到其任务似乎消失的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
 - 修复了在共享当前处于协作状态的文档时生成扩展名为 .asd 的附件的问题。
 - 修复了将评论归因于随机作者的问题。
 - 修复了在签出文档时删除签名的问题。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新程序
 - 修复了在执行“撤消”操作后 VBA 报告错误形状填充状态的问题。


## <a name="version-1902-may-14"></a>版本 1902：5 月 14 日
*版本 1902（内部版本 11328.20286）*

### <a name="excel-non-security-updates"></a>Excel：非安全更新
 -  解决了在 Excel 中使用照相机工具会导致电子表格挂起的问题。
 - 修复了在带有图表工作表的活动窗口中使用鼠标滚轮时导致崩溃的问题。
 - 解决了在 SharePoint 中导入电子表格时出现“意外错误”消息的问题。
 - 解决了在打开包含使用其规则的名称和应用了自定义视图的条件格式的工作簿时导致 Excel 崩溃的问题。
 - 使用长度超过 255 个字符的公式进行数据验证的宏可能会产生运行时错误。 此问题现已得到更正。
 - 导致包含链接到其他工作簿的数据透视表的文件加载缓慢的问题。 此问题已解决。
 - 解决了打开 HTML 文件和接收“文件格式和扩展名不匹配”错误的问题。
 - 已经进行了更改以解决在非活动窗口上滚动鼠标滚轮的问题。  

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
 - 解决了导致客户无法在已迁移的项目上编辑部分字段的问题。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
- 解决了 PowerPoint 停止上传用户更改到云端的问题（此情况极不常见）。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
 - 修复了以下问题：Lync (Skype for Business) 中对于任何有 7 个以上参与者的在线会议，会议窗口可能会消失。
 - 使用登录其他 Office 应用程序时所用的凭据登录 Skype for Business。
 - 在安装有共享计算机激活时正确激活 Skype for Business 应用。

### <a name="visio-non-security-updates"></a>Visio：非安全更新
 - 解决了导致第三方解决方案通过禁用动态 DPI 功能来扩展 Visio 时出现窗口层次结构损坏的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
 - 解决了在编辑由 SharePoint 添加的相关人员时出现崩溃的问题。
 - 解决了在 Word 启动时出现“未能加载资源”对话框的问题。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新程序
 - 这是文件无法保存至 Apache WebDAV 文件夹问题的修复。
 - 修复了在客户打开某些云存储文件时 Office 突然关闭的问题。
 - 修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。
 - 解决了 Windows 10 上貌似已清除多位用户的“最近使用的文件”列表这一问题。
 - 解决了即使站在进行管理器触发的更新，最终用户仍会看到“Office 更新”业务栏的问题。
 - 解决了与登录提示间歇性空白相关的问题。
 

## <a name="version-1902-april-9"></a>版本 1902：4 月 9 日
*版本 1902（内部版本 11328.20230）*

### <a name="excel-non-security-updates"></a>Excel：非安全更新

- 解决了在包含以定义名称结尾的公式的单元格中按 Tab 键不会移动到下一个单元格的问题。
- 解决了单元格格式化导致文件大小不必要增长的问题。
- 解决了在工作簿之间剪切和粘贴数据透视表可能导致数据被粘贴的问题，不包含与你正在协作的其他人的数据透视表。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新

- 修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。
- 解决了导致客户在联系人卡片上加载图片时遇到崩溃的问题。
- 解决了导致某些客户在启动 Office 应用程序时遇到崩溃的问题。
- 修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。
- 解决了导致客户无法在已迁移的项目上编辑部分字段的问题。

### <a name="visio-non-security-updates"></a>Visio：非安全更新

- 修复了以下问题：导致通过禁用动态 DPI 功能扩展 Visio 的第 3 方解决方案的窗口层次结构损坏问题。

### <a name="word-non-security-updates"></a>Word：非安全更新

- 如果文件以只读模式打开，并且你从“信息”窗格中单击“另存为”，则修复问题以便显示“保存 UI”。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新程序

- 修复了以下问题：Office 更新的某些部分不使用传递优化对等缓存。 [了解详细信息](/windows/deployment/update/waas-delivery-optimization)
- 修复了如果使用 Office 部署工具安装 Office 且存在不匹配的情况时，可能导致产品被删除或未激活的 bug。
- 修复了导致 Windows 10（版本 1803 或更高版本）设备上出现过多登录提示的问题。
- 修复了下载链接图片时导致挂起的回归。
- 修复了粘贴在 Word、Excel、PowerPoint 中的大型 EMF 文件的模糊性。
- 修复了版本历史记录解析逻辑中的 bug，这些 bug 在少数情况下会导致文档以只读方式打开。

## <a name="version-1902-march-12"></a>版本 1902：3 月 12 日
*版本 1902（内部版本 11328.20158）*

### <a name="access-feature-updates"></a>Access：功能更新

- **刷新、重新链接或删除链接表** 更新的链接表管理器可用于管理所有数据源和链接表。 [了解更多](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **将其涂成黑色，将其涂成灰色：** 根据需要随时更改 Access 的外观。四种主题可供选择：彩色、深灰色、黑色和白色。[了解详细信息](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。

### <a name="excel-feature-updates"></a>Excel：功能更新

- **更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。 减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。
- **通过注释进行协作：** 使用内置回复框在电子表格中保持正常对话。 [了解更多](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。 此外，这些图标在各种尺寸的屏幕上看起来都很美观。 [了解更多](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **呼叫所有“获取和转换”功能的粉丝：** 如果你经常使用“获取和转换”功能，那么对于“从示例中添加列”功能已得到改进的消息一定兴奋不已。 另外，许多连接器也得到了改进。 [了解更多](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **快速查找** 已极大地提升了 VLOOKUP、HLOOKUP 和 MATCH 计算速度，以便能够更快地获取答案。 [了解更多](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **使用“大声朗读”来收听你的电子邮件：** Outlook 可以大声朗读你的电子邮件，并突出显示正在阅读的文本。要打开大声朗读功能，请转到“轻松访问”设置。[了解详细信息](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **无需键入，解放双手：** 有麦克风？ 单击“听写”，即可看到 Outlook 随着你说话而键入文字。 [了解更多](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。 此外，这些图标在各种尺寸的屏幕上看起来都很美观。 [了解更多](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **默认阻止下载 SMIME 加密和签名的电子邮件中的外部内容：** 鉴于 SMIME 协议中的漏洞，Outlook 将阻止下载由 SMIME 加密或签名的邮件上的外部内容。 用户将无法通过 Outlook UI 单击下载外部内容，以防止受到安全漏洞的危害。 “选项”对话框提供了一个新选项，用户可使用它还原至旧行为。
- **禁用会议转发：** 阻止与会者将会议转发给其他人。 只需转到功能区，然后单击“响应选项”即可。 [了解更多](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **日程安排助理中的人员建议：** 安排会议时查看有关要添加的与会者的建议。无需在日程安排助理和收件人行之间来回切换。[了解详细信息](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **保留会议室变得更加容易：** 使用多个会议室列表查找会议室，切换列表时不会丢失所选的会议室。
- **重复周期范围的新默认值：** 对于“重复周期”对话框，在过去重复周期范围的默认值为“无结束日期”。这有助于创建长期运行的定期系列，随着时间的推移可能会损坏。我们将“重复周期”对话框的默认值更新为“结束日期”，以便我们的默认值与建议的日历最佳做法相匹配。
- **从“Outlook 提醒”对话框加入团队会议：** 当 Outlook 提醒用户参加即将召开的会议时，如果即将召开的会议是团队在线会议，则它将显示一个“联机加入”按钮。这与从“Outlook 提醒”对话框加入 Skype for Business 会议的体验类似。
- **停止查看过去活动的提醒：** 可以将日历设置为在活动结束后自动关闭活动提醒。 [了解更多](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **查看安全链接背后的 URL：** 安全链接有助于保护你免受电子邮件中收到的恶意 URL 的攻击，但它们会隐藏原始 URL。 若要查看原始 URL，请将鼠标悬停在 URL上。 需要高级威胁防护许可证。 [了解更多](https://products.office.com/exchange/advance-threat-protection)
- **缩放和粘贴：** 选择默认设置用于所有邮件，而无需在每次阅读邮件时调整缩放。 [了解更多](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **邮件加密：仅加密 IRM 策略：** 新的仅加密选项显示在 Office 365 邮件加密用户的“选项”>“权限”菜单中。 此选项允许你加密邮件并将其发送给组织内部或外部的任何人。
- **密件抄送 (BCC) 警告：** BCC 信息提示会在你意外对被密件抄送的邮件全部答复之前发出警告。
- **更智能的“收件人:”行：** 在单击“收件人:”行处理邮件时，会提示用户可能要选择的收件人。 此外，还可以看到收件人的照片，这样用户便知道将要向其发送邮件的收件人正确无误。 [了解更多](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。 减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。
- **无需键入，解放双手：** 有麦克风？ 单击“听写”，即可看到 PowerPoint 随着你说话而键入文字。 [了解更多](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。 此外，这些图标在各种尺寸的屏幕上看起来都很美观。 [了解更多](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **使用其他生动颜色显示超链接：** 超链接不再只是蓝色的。 可以根据需要应用任何字体颜色。 [了解更多](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **查看栩栩如生的幻灯片：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个屏幕中横冲直撞的霸王龙。 [了解更多](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **用户绘制草图，我们来润色：** 我们将手绘文本和形状变为精致的图表。只需选择笔划墨迹即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **发布到 Microsoft Stream：** 通过使用 Microsoft Stream 在组织中更为安全地将演示文稿作为视频进行共享。  [了解更多](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- **导出为 4K 视频：** 将演示文稿导出为视频时，现在可以选择 4K 分辨率。  [了解更多](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **大文件现在可以更快地打开：** 打开存储在 OneDrive 或 SharePoint 中的文件时，图像、视频和其他大文件现在可以在后台下载。

### <a name="word-feature-updates"></a>Word：功能更新

- **更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。 减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。
- **无需键入，解放双手：** 有麦克风？ 单击“听写”，即可看到 Word 随着你说话而键入文字。 [了解更多](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **查看栩栩如生的文档：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个页面中横冲直撞的霸王龙。[了解详细信息](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。 此外，这些图标在各种尺寸的屏幕上看起来都很美观。 [了解更多](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **在 LinkedIn 的帮助下编写你的出色简历：** 通过简历助手查看工作经验、建议技能及给定角色的详细信息。 [了解详细信息](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project：功能更新

- **在任务板卡片上了解更多信息：** 如果单独的标题无法描述详情，可以自定义任务板卡片以显示所有最重要的详细信息。 [了解更多](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。

### <a name="publisher-feature-updates"></a>Publisher：功能更新

- **Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。

### <a name="visio-feature-updates"></a>Visio：功能更新

- **在下一个图表中享受全新图标时刻：** 从 26 个新的模具中挑选，其中包含用于分析、艺术、庆祝、人脸、运动等的图标。
- **Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **Office 第三方应用程序现已支持通过 office.js API 插入 SVG：** 第三方应用程序也称为 Office 中的加载项，它们现可插入 SVG。用户现可将其个人的 SVG 集合连接到 Office。而开发人员可通过 Office.js API 使用该项功能。
- **Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。 [了解更多](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype for Business：功能更新

- **增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams：功能更新

- **增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>版本 1808：2 月 12 日
版本 1808（内部版本 10730.20280） 

### <a name="access-non-security-updates"></a>Access：非安全更新 

- 此更新将对新日本和历的支持添加到 Access。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新 

- 解决以下问题：具有引用不再存在的文件夹规则的用户在尝试管理规则时看到错误，以及看到客户端规则运行失败。
- 处理以下问题：具有缓存委托邮箱的用户在不可预测的时间间隔遇到频繁挂起。
- 处理以下问题：由于会议结束时间设置为第二天的午夜，在一些视图中，全天会议似乎超过预期的一天时间。
- 修复了创建引用日本和历的新约会或会议时的挂起。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新程序

- 修复以下问题：使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的外接程序被冻结且不可用。


## <a name="version-1808-january-8"></a>版本 1808：1 月 8 日
*版本 1808（内部版本 10730.20264）* 

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新 

- 修复了导致用户遇到日历同步错误的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新

- 提高打开性能。

## <a name="version-1808-december-11"></a>版本 1808：12 月 11 日
*版本 1808（内部版本 10730.20262）*

### <a name="excel-security-updates"></a>Excel：安全更新 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 远程代码执行漏洞 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 信息泄漏漏洞 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 信息泄漏漏洞 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 远程代码执行漏洞 

### <a name="outlook-security-updates"></a>Outlook：安全更新 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 远程代码执行漏洞 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全更新 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 远程代码执行漏洞 

### <a name="excel-non-security-updates"></a>Excel：非安全更新 

- 修复了以下问题：在合著会话中，当其他用户对切片器中的数据应用列筛选之后，切片器无法正确更新。
- 修复了以下问题：在合著会话中，如果其中一个用户清除了某个切片器的标题，则会导致合著会话中的其他用户遇到 Excel 崩溃的情况。
- 修复了以下问题：将创建的多个表切片器绑定到同一数据列，然后再删除该数据列时，可能会出现崩溃。
- 修复了以下问题：自动调整列宽选项关闭时，如果刷新单元格中包含换行文本的已筛选查询表，Excel 有时会发生崩溃。
- 修复了以下问题：当切片器中显示的项数改变时，如果在更高版本的 Excel 中打开在 Excel 2007 中保存的切片器，将会触发崩溃。
- 引入了对“获取诊断”按钮的支持，以简化对支持请求的调查。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新

- 修复了导致用户在启动“管理规则和警报”对话框时看到错误消息的问题。
- 修复了导致用户在使用按流量计费的连接时无法通过 DirectAccess 连接到其邮箱的问题。
- 修复了导致用户看到“公用文件夹”中保存的免费文本在“受保护的视图”中错误打开的问题。
- 修复了导致用户在转发带有内嵌附件的项目时意外看到附件的问题。
- 修复了导致 OFT 文件在作为附件发送之后呈现效果欠佳的问题。
- 修复了导致部分使用加载项的用户在向共享日历添加会议时发生崩溃的问题。
- 修复了导致用户在打开“对话历史记录”文件夹时发生挂机的问题。

### <a name="project-non-security-updates"></a>Project：非安全更新

- 修复了与 Project 中新增委内瑞拉货币支持相关的问题。
- 修复了以下问题：使用连接到外部监视器的 Surface 4 时，Project 可能会挂机。
- 修复了以下问题：将项目保存为 XML 格式时，Project 可能会发生崩溃。
- 修复了以下问题：编辑某个资源的日历之后，企业资源自定义字段可能会被删除。
- 修复了导致用户在搜索韩语显示名称时发生崩溃的问题。

## <a name="version-1808-november-13"></a>版本 1808：11 月 13 日
*版本 1808（内部版本 10730.20205）*

### <a name="excel-security-updates"></a>Excel：安全更新

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 远程代码执行漏洞 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 远程代码执行漏洞 

### <a name="outlook-security-updates"></a>Outlook：安全更新 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 远程代码执行漏洞 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 远程代码执行漏洞 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 信息泄漏漏洞 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 远程代码执行漏洞 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 信息泄漏漏洞 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 远程代码执行漏洞 

### <a name="project-security-updates"></a>Project：安全更新 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 远程代码执行漏洞 

### <a name="word-security-updates"></a>Word：安全更新 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 远程代码执行漏洞 

### <a name="skype-for-business-security-updates"></a>Skype for Business：安全更新 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546)：Microsoft Skype for Business 拒绝服务漏洞 

### <a name="excel-non-security-updates"></a>Excel：非安全更新 

- 已修复以下问题：某些内部版本/版本中不显示 Power Pivot。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新 

- 已修复以下问题：用户无法成功使用帐户控制按钮在自定义窗体上的帐户之间切换。
- 已修复以下问题：用户使用 ScanPST 修复 OST/PST 文件时，遇到故障。
- 已修复以下问题：某些邮件上的“抄送:”字段无法显示具有联机模式配置文件的用户。

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新 

- 修复了涉及同步和导航到已删除分区时可能出现的稳定性问题。

### <a name="project-non-security-updates"></a>Project：非安全更新 

- 已修复以下问题：如果在新现代体验中的 SharePoint 文档库中处理 Project 文件，“要求签出”和“只读”操作不会正确执行。


## <a name="version-1808-october-9"></a>版本 1808：10 月 9 日
*版本 1808（内部版本 10730.20155）*

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 远程代码执行漏洞 

### <a name="outlook-security-updates"></a>Outlook：安全更新 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全更新 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 远程代码执行漏洞

### <a name="word-security-updates"></a>Word：安全更新 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 远程代码执行漏洞 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全更新 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 组件远程代码执行漏洞 

### <a name="excel-non-security-updates"></a>Excel：非安全更新 
-   已修复以下问题：范围 2190...2194 中的符号切换为 Cambria Math 时，Excel 单元格高度增加 3 倍。
-   已修复以下问题：当用户将鼠标悬停在具有许多定义名称的工作簿中的格式化选项上时，Excel 可能无响应，当在选项中禁用实时预览时，Excel 可能在快速分析工具中无响应。
-   我们现在正在调查将 Excel 应用程序窗口从一个桌面移动到另一个桌面时性能缓慢的原因。在此期间，如果你发现了此性能缓慢，可以考虑使用以下变通方法：在“文件选项”对话框的“通用”选项卡中，针对“使用多个显示器时”选择“优化兼容性”。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新程序
-   已修复以下问题：保存包含 ActiveX 内容的文件时，文件可能损坏。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   已修复以下问题：插入 Word 文档对象时，会显示公式编辑器。

### <a name="project-non-security-updates"></a>Project：非安全更新
-   已修复以下问题：如果为打印内容设置页眉或页脚，下一次打印项目时，此更改可能不会保持。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了以下问题：即使通过辅助功能和性能设置关闭动画，应用仍显示动画。 
-   修复了以下问题：使用荧光笔绘图工具时，背景变成空白。

## <a name="version-1808-september-11"></a>版本 1808：9 月 11 日
*版本 1808（内部版本 10730.20102）*

### <a name="access-feature-updates"></a>Access：功能更新
 - **利用新图表实现数据的可视化效果：** 从 11 个图表中选择一个图表并将其添加到窗体和报表，更好地实现数据的可视化效果，并做出明智的决策。[了解详细信息](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access：安全更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞

### <a name="excel-feature-updates"></a>Excel：功能更新
 - **协作编辑：** 与其他人同时协作处理工作簿。[了解详细信息](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **现在，默认情况下启用云文件自动保存：** 在 2018 年 9 月半年频道（定向）发布中默认启用自动保存。此更改意味着用户无需担心丢失存储在 OneDrive 或 SharePoint Online 中的文档的更改。更改将自动保存在云端，用户无需显式按 Ctrl+S 或“保存”按钮。但是，用户必须了解此行为更改，以便不会对文档作出意外更改。注意，用户可使用屏幕顶部的“自动保存”切换关闭“自动保存”。我们建议你向用户告知此即将推出的更改，让其了解如何利用此 Office 365 新功能。[详细了解自动保存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [详细了解 IT 管理员应知晓的自动保存内容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **改进了单元格和编辑栏编辑：** 现在可以按 CTRL+A 选择单元格或编辑栏中的文本。同时还改进了对表情符号和其他复杂字符的支持。[了解详细信息](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的工作簿更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **避免不需要的编辑：** 将工作簿设置为以只读方式打开，避免意外更改。转到“文件”>“信息”>“保护工作簿”>“始终以只读方式打开”

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 信息泄漏漏洞
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 远程代码执行漏洞 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 远程代码执行漏洞 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 信息泄漏漏洞
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 信息泄漏漏洞
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 信息泄漏漏洞
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 远程代码执行漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   已修复以下问题：从图表源数据的原始单元格集更改图表源数据时，Excel 可能出现故障。
-   已修复以下问题：即使已设置 FullCalcOnLoad 属性，打开时也可能不会进行重新计算。  
-   修复了在日期单元格格式中使用日本和历日历时显示错误年份的问题。
-   将数据导入 Excel 数据模型时，传入的负零值将导致错误。此次修复将此类值导入为零。
-   修复了以下问题：Excel 数据透视表中的组合（或取消组合）操作有时可能会触发故障。
-   修复了制作图表操作可能导致 Excel 崩溃的问题。
-   修复了对某些用户无意禁用 Power View 加载项的问题。
-   修复了在文档恢复期间创建的临时自动恢复文件从未清理的问题。
-   修复了以下问题：尝试对受保护的工作簿中的文本文件建立新连接时收到“工作簿处于受保护状态，无法更改”的错误消息。
-   修复了以下问题：无法快速打印附加到 Outlook 电子邮件的 Excel 工作簿。
-   修复了以下问题：单击超链接可能会导致 Excel 发生故障。
-   修复了以下问题：使用多维数据集函数导致 Excel 发生故障。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
 - **辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的邮件更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **从配置文件选取器管理配置文件：** 如果启动 Outlook 时使用配置文件选取器，现在可以在无需转到控制面板的情况下进行更改。可通过配置文件选取器进行创建和删除配置文件、更改设置等操作。
- **内置辅助功能：** 通过将说明性可选文字添加到图像，使所有人都可访问你的邮件。
- **Outlook 加载项警告：** Outlook COM 加载项有时会遇到导致 Outlook 其余部分运行速度变慢的问题。这些问题可能是由事件延迟导致的，例如在 Outlook 文件夹之间切换、新邮件的到达、正在打开日历项目等。出现此类问题时，Outlook 将在通知栏中显示一条警告。
- **知道将与谁一起开会：** 即使你不是组织者，现在也可以看到其他人对会议请求的响应。
- **绝不错过任何提醒：** 设置在工作窗口中弹出的提醒。如果不设置，Outlook 会在任务栏中闪烁，以引起用户注意。[了解详细信息](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **将已删除邮件标记为已读：** 现在可以将任何已删除邮件设置为已读。启用方法为，依次转到“文件”\>“选项”\>“邮件”\>“其他”。
- **查看 3 个时区：** 需要跨时区安排会议？将多个时区添加到日历，轻松地查看每个人的空闲时间并选择适合所有人的时间。[了解详细信息](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **优化创建组的用户体验：** 已优化创建组的用户体验，使其更现代、更简便。[了解详细信息](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 篡改漏洞
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 特权提升漏洞
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全功能规避漏洞
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防御更新

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   已修复以下问题：如果将系统语言切换为日语并且尝试将日语字符键入 VBA IDE，在 Outlook 中加载时，可能会冻结。
-   修复了切换到发件箱或已发送邮件文件夹会导致 Outlook 崩溃的问题。
-   修复了当会议正文或附件更改时，所有与会者都会收到会议更新（而不是向与会者发送会议更新）属于可选项的问题。
-   修复了由于 User-Agent 字符串的更改，导致用户无法连接到 EWS 和 REST 终结点的问题。
-   修复了以下问题：对与会者更新的会议地点显示旧位置，而不是新位置。
-   修复了以下问题：用户在阅读窗格中预览附件时看到错误消息。
-   修复了以下问题：在用户撰写电子邮件期间，Outlook 将显示名称解析为电子邮件地址时发生故障。
-   修复了以下问题：一些用户没有收到租户管理员已启用的支持功能。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新 
- **现在，默认情况下启用云文件自动保存：** 在 2018 年 9 月半年频道（定向）发布中默认启用自动保存。此更改意味着用户无需担心丢失存储在 OneDrive 或 SharePoint Online 中的文档的更改。更改将自动保存在云端，用户无需显式按 Ctrl+S 或“保存”按钮。但是，用户必须了解此行为更改，以便不会对演示文稿作出意外更改。注意，用户可使用屏幕顶部的“自动保存”切换关闭“自动保存”。我们建议你向用户告知此即将推出的更改，让其了解如何利用此 Office 365 新功能。[详细了解自动保存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [详细了解 IT 管理员应知晓的自动保存内容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **转换墨迹：** 获取自由曲线备注和绘图，并将它们转换为可读文本和清晰形状，以创建完善的演示文稿。[了解详细信息](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **改进了 SVG 支持：** 可以插入应用了筛选器的 SVG。[了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **使用手写笔为幻灯片添加标题：** 使用手写笔撰写标题，然后 PowerPoint 会将它转换为文本。[了解更多](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **避免不需要的编辑：** 将工作簿设置为以只读方式打开，避免意外更改。转到“文件”>“信息”>“保护工作簿”>“始终以只读方式打开”
- **辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使演示文稿更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新程序
-   修复了表格显示不正常并带有粗边框的问题。
-   修复了以下问题：更改 Shape.Visibile 属性时，可能会发生潜在故障。
-   修复了以下问题：无法合并合著文档中的更改。
-   修复了以下问题：包含 ActiveX 控件的文档会导致合著失败。
-   修复了在形状中使用拼写更正导致 PowerPoint 崩溃的问题。
-   修复了从 SharePoint Online 打开文件时 PowerPoint 崩溃的问题。
-   修复了当自动保存处于打开状态时，恢复窗格错误打开的问题。
-   修复了不显示登录，从而阻止用户访问文件的问题。
-   修复了以下问题：多个用户在同一个演示文稿中共同创作导致幻灯片母板复制不正确。
-   修复了以下问题：打开保存在 OneDrive 上的文件导致 PowerPoint 在退出受保护的视图时出现故障。

### <a name="project-feature-updates"></a>Project：功能更新 
- **冲刺 (sprint) 管理：** 快速添加、更新或删除敏捷冲刺 (sprint)。
- **任务板筛选：** 通过筛选主要资源或摘要任务来简化任务板。
- **在任务板中设置完成百分比：** 为每列都选择一个完成百分比，再通过拖放操作来更新任务完成进度。
- **冲刺 (sprint) 导航：** 从一个冲刺 (sprint) 视图切换到另一个，并在两个冲刺 (sprint) 视图之间快速移动任务。
- **管理冲刺 (sprint) 的新方法：** 采用敏捷方法来处理任务板。转到管理冲刺 (sprint) ，随着你的项目演进添加和删除冲刺 (sprint)。
- **最近保存位置有条理：** Project 通过可不断扩充的列表列出了其他项目的保存位置。准备保存项目时，只需选择最近保存位置之一，即可继续工作。

### <a name="project-non-security-updates"></a>Project 非安全更新程序
- 修复了以下问题：通过主项目的上下文处理子项目时，无法保存子项目。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复了与 TLS 1.2 支持相关的问题。（注意：这是 4 月 10 日说明中提到的同一个修补程序。在这里作为 9 月汇总的一部分再次提到。）
-   修复了在会议中通过选择“Skype 通话”来添加用户导致出错的问题。
-   如果 Skype 会议室已被添加为位置且会议已包含 Teams 会议协调人，则删除要求用户向会议添加 Skype 协调人的提示。
-   修复了以下问题：即使将 UseLocationForE911Only 设置为 true，位置也会被填充。
-   修复了以下问题：通过“使用会议中心呼叫”选项邀请名单中的用户时，Skype for Business 挂起。
-   修复了以下问题：创建 Skype for Business 会议期间，终端服务器上运行的 Outlook 冻结。
-   将 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的默认值更改为 TRUE。

### <a name="visio-feature-updates"></a>Visio：功能更新
- **保持图表和源同步：** 在 Visio 中编辑数据可视化工具图表时，可以视需要根据最新图表内容，更新链接的 Excel 源数据。
- **数据可视化工具审核模板：** 从 Excel 导入内容，并创建财务交易记录、库存管理等的审计图。
- **入门图表：** 组织结构图、头脑风暴和 SDL 模板具有新的入门图表，让你能够快速使用起来。
 - **利用 Visio 形状生成 Word 文档：** 自动向 Word 文档添加关系图内容（包括形状和元数据）。然后对文档进行自定义，以创建过程准则和操作手册。[了解详细信息](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word：功能更新
- **现在，默认情况下启用云文件自动保存：** 在 2018 年 9 月半年频道（定向）发布中默认启用自动保存。此更改意味着用户无需担心丢失存储在 OneDrive 或 SharePoint Online 中的文档的更改。更改将自动保存在云端，用户无需显式按 Ctrl+S 或“保存”按钮。但是，用户必须了解此行为更改，以便不会对演示文稿作出意外更改。注意，用户可使用屏幕顶部的“自动保存”切换关闭“自动保存”。我们建议你向用户告知此即将推出的更改，让其了解如何利用此 Office 365 新功能。[详细了解自动保存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [详细了解 IT 管理员应知晓的自动保存内容]
- **辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的文档更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **改进了 SVG 支持：** 可以插入应用了筛选器的 SVG。[了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word：安全更新
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430)：Word PDF 远程代码执行漏洞
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 信息泄漏漏洞

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了导致出现内存不足消息的问题。
-   修复了阻止某些用户打开由其他组织中的人员与其共享的受 IRM 保护的文档和电子邮件的一系列问题。
-   修复了一些性能问题。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332)：Win32k Graphics 远程代码执行漏洞
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 信息泄漏漏洞
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 远程代码执行漏洞
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 远程代码执行漏洞
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 远程代码执行漏洞
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 信息泄漏漏洞
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 远程执行代码漏洞
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 远程代码执行漏洞
-   
  **出于安全考虑，禁止在 Office 中激活 Flash、Silverlight 和 Shockwave 控件：** 出于安全考虑，Windows 上的 Microsoft Office for Office 365 新版本阻止激活 Flash、Silverlight 和 Shockwave 控件。可通过[此处](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和[此处](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)了解详细信息。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-  修复了在某些场景中导致更新安装所用时间过长的问题。
-  修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。
-  修复了一些性能问题。

## <a name="version-1803-august-14"></a>版本 1803：8 月 14 日
*版本 1803（内部版本 9126.2275）*

### <a name="access-security-updates"></a>Access：安全更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 远程代码执行漏洞 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 远程代码执行漏洞 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 信息泄漏漏洞 

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防御更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 信息泄漏漏洞 

## <a name="version-1803-july-10"></a>版本 1803：7 月 10 日
*版本 1803（内部版本 9126.2259）*

### <a name="access-security-updates"></a>Access：安全更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞

### <a name="outlook-security-updates"></a>Outlook：安全更新程序
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 篡改漏洞

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 远程代码执行漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新程序
-   修复了在日期单元格格式中使用日本和历日历时显示错误年份的问题。
-   将数据导入 Excel 数据模型时，传入的负零值将导致错误。此次修复将此类值导入为零。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新程序
-   修复了表格显示不正常并带有粗边框的问题。

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了以下问题：如果使用成本资源对任务进行拆分，则成本资源无法正确更新且成本丢失。
-   修复了以下问题：“日程表”视图中的“将现有任务添加到日程表”对话框仅显示第一个摘要任务中的任务。
-   修复了以下问题：将 Project Online 或 Project Server 中的主项目另存为 XML 可能会失败。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新程序
-   修复了在某些应用场景中导致更新安装所用时间过长的 bug。 
-   修复了 SVG 测试失败的问题
-   修复了以下问题：使用 Configuration Manager 将更新部署到运行 Office 应用程序的客户端时，在 Office 应用程序正在运行的情况下重启设备后更新未应用。


## <a name="version-1803-june-12"></a>版本 1803：6 月 12 日
*版本 1803（生成号 9126.2227）*

### <a name="excel-security-updates"></a>Excel：安全更新程序
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 信息泄漏漏洞
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 远程代码执行漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新程序
-   修复了以下问题：Excel 数据透视表中的组合（或取消组合）操作有时可能会触发故障。

### <a name="outlook-security-updates"></a>Outlook：安全更新程序
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 特权提升漏洞

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新程序
-   修复了以下问题：更改 Shape.Visibile 属性时，可能会发生潜在故障。
-   修复了以下问题：无法合并合著文档中的更改。
-   修复了以下问题：包含 ActiveX 控件的文档会导致合著失败。

### <a name="project-non-security-updates"></a>Project：非安全更新程序
-   修复了以下问题：“日程表”视图“将现有任务添加到日程表”对话框仅显示第一个摘要任务中的任务。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了以下问题：使用 Configuration Manager 将更新部署到运行 Office 应用程序的客户端时，在 Office 应用程序正在运行的情况下重启设备后更新未应用。



## <a name="version-1803-may-18"></a>版本 1803：5 月 18 日
*版本 1803（内部版本 9126.2210）*

### <a name="excel-non-security-updates"></a>Excel：非安全更新
- 修复了制作图表操作可能导致 Excel 崩溃的问题。
- 修复了对某些用户无意禁用 Power View 加载项的问题。
- 修复了在文档恢复期间创建的临时自动恢复文件从未清理的问题。
- 修复了以下问题：尝试对受保护的工作簿中的文本文件建立新连接时收到“工作簿处于受保护状态，无法更改”的错误消息。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
- 修复了在形状中使用拼写更正导致 PowerPoint 崩溃的问题。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
- 修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。



## <a name="version-1803-may-8"></a>版本 1803：5 月 8 日
*版本 1803（内部版本 9126.2191）*

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 远程代码执行漏洞
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 信息泄漏漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了从 SharePoint Online 打开文件时 Excel 崩溃的问题。
-   修复了打印或打印预览只打印或显示工作表部分，内容被工作表上的切片器截断的问题。

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全功能规避漏洞

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了切换到发件箱或已发送邮件文件夹会导致 Outlook 崩溃的问题。
-   修复了当会议正文或附件更改时，所有与会者都会收到会议更新（而不是向与会者发送会议更新）属于可选项的问题。
-   修复了由于 User-Agent 字符串的更改，导致用户无法连接到 EWS 和 REST 终结点的问题。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了从 SharePoint Online 打开文件时 PowerPoint 崩溃的问题。
-   修复了当自动保存处于打开状态时，恢复窗格错误打开的问题。
-   修复了不显示登录，从而阻止用户访问文件的问题。

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了在日期列使用自动筛选下拉菜单导致 Project 中的所有任务被隐藏的问题。
-   修复了在日程表视图中时，当将现有任务添加到日程表时，只有第一个摘要任务中的任务会显示在对话框中的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了从 SharePoint Online 打开文件时 Word 崩溃的问题。
-   修复了小写罗马数字页码 被错误地更改为大写的问题。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 远程代码执行漏洞
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 远程代码执行漏洞



## <a name="version-1803-april-10"></a>版本 1803：4 月 10 日
*版本 1803（内部版本 9126.2152）*

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 远程代码执行漏洞

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：多个用户在同一个演示文稿中共同创作导致幻灯片母板复制不正确。
-   修复了以下问题：打开保存在 OneDrive 上的文件导致 PowerPoint 在退出受保护的视图时出现故障。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复了与 TLS 1.2 支持相关的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了导致出现内存不足消息的问题。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 信息泄漏漏洞
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 远程执行代码漏洞
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 远程代码执行漏洞



## <a name="version-1803-march-20"></a>版本 1803：3 月 20 日
*版本 1803（内部版本 9126.2098）*

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了以下问题：无法快速打印附加到 Outlook 电子邮件的 Excel 工作簿。
-   修复了以下问题：单击超链接可能会导致 Excel 发生故障。
-   修复了以下问题：使用多维数据集函数导致 Excel 发生故障。

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business：非安全更新
-   修复了以下问题：OneDrive for Business (Groove.exe) 在任务管理器中长时间使用 CPU 的一个 CPU 内核资源（例如，4 核 CPU 的 25%）。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了以下问题：对与会者更新的会议地点显示旧位置，而不是新位置。
-   修复了以下问题：用户在阅读窗格中预览附件时看到错误消息。
-   修复了以下问题：在用户撰写电子邮件期间，Outlook 将显示名称解析为电子邮件地址时发生故障。
-   修复了以下问题：一些用户没有收到租户管理员已启用的支持功能。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了以下问题：如果运行 Windows 7 的计算机未安装 [客户体验和诊断遥测更新](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)，无法打开 Word。
-   修复了以下问题：无法打印列表中的项目符号。



## <a name="version-1803-march-13"></a>版本 1803：3 月 13 日
*版本 1803（内部版本 9126.2072）*

### <a name="access-security-updates"></a>Access：安全更新
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 远程代码执行漏洞

### <a name="access-non-security-updates"></a>Access：非安全更新
-   修复了以下问题：打开 Access 运行时应用程序 (.accde file) 导致“无法识别此数据库的格式”错误消息出现，且应用程序无法打开。
-   修复了以下问题：尝试选择文本框或组合框中的文本时，似乎会选择所有文本，而不是指示的选择内容。

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 将字词、短语或句子翻译成其他语言。可以在功能区的“审阅”选项卡中执行此操作。
-   **将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。
-   **取消选中单元格：** 在工作表中进行选择，并取消选中不小心单击的单元格，而不必重新开始。
-   **快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。
-   **数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。
-   **LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 模型：** 使用 3D 增强工作簿的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。
-   **共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。
-   **阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。
-   **触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全功能规避漏洞
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 内存损坏漏洞
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 远程执行代码漏洞
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 远程执行代码漏洞
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全功能规避漏洞
-   [公告 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了以下问题：如果编辑语言是日语、中文或韩语，那么尝试在“开始”选项卡上选择新字体或进行编辑时，Excel 可能会冻结。
-   修复了以下问题：在最小化 Excel 后打开工作簿时，缺少滚动条。
-   修复了以下问题：在文件资源管理器中双击文件名打开多个工作簿时，工作簿引用失败。
-   修复了以下问题：以编程方式依次创建数据透视表和刷新导致 Excel 发生故障。
-   修复了以下问题：以编程方式调用 Workbook.Open() 可能会导致 Excel 发生故障。
-   修复了以下问题：使用宏打开 Office 2007 或更低版本工作簿（.xls 或 .xla）时，用户错误地看到“灾难性故障”错误消息。
-   修复了以下问题：Excel 可能会在用户打开关联菜单时发生故障。
-   修复了以下问题：当用户尝试在现有的工作簿中插入对象时，用户单击“浏览”导致 Excel 发生故障的问题。
-   修复了以下问题：如果使用密码保护区域，看不到用于输入密码以解锁区域的对话框。
-   修复了以下问题：当文件名包含方括号时，用户无法关闭受保护的视图中的工作簿。
-   修复了以下问题：拖动或拖动填充时，工具提示的位置未对齐。
-   修复了以下问题：使用“文件”\>“另存为”保存工作簿时，包含句点的文件名在文件保存对话框中显示为空白或被截断。
-   修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **轻松排序电子邮件：** 感谢提供反馈，我们已为未使用重点收件箱的用户，在邮件列表和未读邮件筛选器上方恢复了排序功能。
-   **将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，以便可更改其颜色、大小或纹理。
-   **Office 365 群组的改进：** 阅读和回复群组对话比以往更加简便，因为可以双击群组消息，在它自己的窗口中打开消息。
-   **LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 模型：** 使用 3D 增强电子邮件的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **个人资料卡片：** 无论是桌面版、Web 版还是使用移动应用，都显示与人员和群组最相关的详细信息。
-   **将约会添加到群组日历中：** 现在无需以电子邮件方式发送会议安排，即可让群组中的所有人都知道你何时离开。
-   **下载云附件：** 将 OneDrive 附件保存或拖放到计算机后，我们会为用户下载文件。
-   **实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **重点收件箱：** 收件箱分为两个选项卡 – 重点和其他。邮件根据邮件内容以及最常与之交互的联系人进行排序。 [了解更多](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **快速访问最常用的组：** 最常与之交互的组现在显示在“文件夹”窗格的“组”下方列表的顶部。

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 信息泄漏漏洞
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 远程代码执行漏洞
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程执行代码漏洞
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 特权提升漏洞
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 内存损坏漏洞

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了以下问题：在搜索范围为全部邮箱时，搜索失败且看到“找不到匹配”错误消息。
-   修复了以下问题：如果在使用可访问事件观察程序 (AccEvent.exe) 进行监视时切换文件夹，导致 Outlook 发生故障。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 将字词、短语或句子翻译成其他语言。可以在功能区的“审阅”选项卡中执行此操作。
-   **3D 动画：** 通过添加轻轻摇摆、跳跃和旋转等动画效果，让你的 3D 模型活起来。
-   **将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。
-   **修订跟踪信息漫游：** 突出显示其他人修改的共享幻灯片的已读/未读状态，现在存储在漫游服务中（而不是存储在用户本地计算机上），这样就可以跨多个设备或平台同步此类信息。
-   **快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。
-   **数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。
-   **LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **使用数控笔执行幻灯片放映：** 使用 Surface 触控笔或其他带有蓝牙按钮的触笔切换幻灯片。需要安装 Windows 10 Fall Creators Update。 [了解更多](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **3D 模型：** 使用 3D 增强演示文稿的视觉效果和创意效果。使用切换效果（例如可在幻灯片之间打造电影动画效果的“平滑”）使演示文稿中的 3D 模型栩栩如生。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。
-   **共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。
-   **阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **修订突出显示：** 突出显示由其他用户已修改的幻灯片。
-   **离开期间：** PowerPoint 显示自你上次访问以后对共享演示文稿进行过编辑的用户。
-   **设计器改进：** 现在，设计器会推荐有关项目符号列表中日程表的设计灵感。
-   **实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。
-   **触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。
-   **设计器改进：** 设计器现在为幻灯片中添加的图表提供设计灵感建议。
-   **快速启动：** 自动生成大纲，帮助用户开始研究他们所选的主题。[了解详细信息](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **数字标尺：** 在具有触摸屏的设备上，转到“绘图”\>“标尺”，然后使用笔或手指绘制直线或对齐一组对象。 [了解更多](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint：安全更新
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 信息泄漏漏洞

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：删除文档属性和个人信息导致无法保存到 SharePoint。
-   修复了以下问题：引用基于 Flash Player 的 YouTube 嵌入代码，导致打开新窗口来播放视频。旧嵌入代码现已升级为，引用基于 HTML5 的 YouTube 视频，以便正确就地播放这些视频。
-   修复了以下问题：保存支持同步的文件时，Office 无法对磁盘执行写入操作，但 Office 仍继续将文件上传到 OneDrive。修复此问题后，用户现在会看到错误消息，且上传不会继续执行。

### <a name="project-feature-updates"></a>Project：功能更新
-   **“任务板”视图：** 在“任务板”视图中，对卡片上的任务进行排序。在任务板上的各栏之间重新排序和移动卡片，就跟在敏捷项目中一样。
-   **敏捷项目：** 使用积压工作 (backlog)、任务板、冲刺 (sprint) 等管理敏捷项目。支持使用 Scrum 或看板方法。[了解详细信息](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **在规划器中管理任务：** 将项目任务关联到规划器，并为任务创建计划。将任务分解为子任务，添加团队，分配任务，并管理任务板上的工时。

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了以下问题：在会话中设置多个基线会将 MOD\_DATE 值设为相同的值。
-   修复了以下问题：在“​​保存以共享”会话中删除“实际工时”后，它仍显示在报表中。
-   修复了进行日程安排时在德语版本中使用“星期”日期格式返回错误的问题。
-   修复了在日程安排 Web 部件中编辑完成日期时任务每天停留 8 小时而不随着时间推移的问题。
-   修复了以下问题：在意外位置绘制“进度点形状”。
-   修复了以下问题：VBA 代码从项目中丢失。
-   修复了以下问题：即使还有剩余工时，任务也仍显示为已完成。
-   修复了在使用任务路径功能时项目挂起的问题。
-   修复了时间刻度不显示时间刻度标签的问题。
-   修复了视觉对象报表显示信息不完整或完全无法显示信息的问题。
-   修复了以下问题：如果保存失败，则会损坏文件，并导致 Project 在打开时发生故障。
-   修复了以下问题：无法在“日程表和工作组规划器”视图中拖动任务。
-   修复了以下问题：工作组生成器中不显示资源可用性。
-   修复了图形指示器未正确显示的问题。
-   修复了在按小时或按天的基础上调配时项目挂起的问题。
-   修复了从 SharePoint 文档库使用主项目/子项目的问题。
-   修复了在将作业添加到固定工期任务时，最终可能获得无名资源的问题。
-   修复了以下问题：更改受保护的工时看到不正确的错误消息。
-   修复了以下问题：转到包含多个图像的报表时，Project 可能会发生故障。

### <a name="publisher-feature-updates"></a>Publisher：功能更新
-   **阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher：非安全更新
-   修复了以下问题：运行“邮件合并”向导时，无法筛选包含 null（空）值的数据源字段。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复了在会议中通过选择“Skype 通话”来添加用户导致出错的问题。
-   如果 Skype 会议室已被添加为位置且会议已包含 Teams 会议协调人，则删除要求用户向会议添加 Skype 协调人的提示。
-   修复了以下问题：即使将 UseLocationForE911Only 设置为 true，位置也会被填充。
-   修复了以下问题：通过“使用会议中心呼叫”选项邀请名单中的用户时，Skype for Business 挂起。
-   修复了以下问题：创建 Skype for Business 会议期间，终端服务器上运行的 Outlook 冻结。
-   将 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的默认值更改为 TRUE。
-   修复了以下问题：当会议处于全屏模式时，“更多选项”和“邀请更多人”按钮隐藏。
-   修复了尝试加入时 P2P 音频呼叫窗口或电话会议窗口变成透明的问题。
-   修复了即将开始的 Skype 会议不出现在“会议”选项卡中的问题。
-   修复了在没有音频的情况下配置 Skype for Business 以加入会议时，添加音频到会议会对用户本人启动一个新的 P2P 呼叫，而不是添加音频到现有会议的问题。
-   修复了以下问题：在 Outlook 中单击会议请求内的“加入 Skype 会议”链接时，用户看到“找不到此 Skype 会议”错误消息。
-   在用于传入 PSTN 呼叫的 Toast UI 中添加呼叫转移按钮。
-   当 ChatDefaultClient 和 CallDefaultClient 设置为“团队”时，通知用户呼叫和聊天正在发送到“团队”。
-   当用户不在会议中时，显示用户为“离线”状态，并禁用 Skype for Business，同时会议加入体验设置为“本机有限客户端”。
-   当 Skype for Business 最小化到通知区域时，禁用除“打开”和“退出”外的所有选项。
-   当启用与 Aries 手机和 RedirectClient 配对时，禁止新的呼叫和对话。
-   修复了日期格式不是美国格式 (mm/dd/yy) 时，按日期在 PChat 中搜索消息失败的问题。
-   修复了以下问题：当 EnableExternalP2PFileTransfer 策略设置为 false 时，用户仍能在会议中附加文件。
-   修复了以下问题：对话历史记录中显示的是呼叫方，而不是被叫方。如果使用 Active Directory 修改被叫方的工作电话号码，就会出现此问题。
-   修复了以下问题：对于向手机号码拨出的传出 PSTN 呼叫，对话历史记录中的呼叫历史记录内缺少接听人信息。
-   修复了以下问题：从 Outlook 中的电子邮件启动 IM 时，IM 的主题中没有电子邮件的主题行。
-   修复了以下问题：当 IM 对话窗口贴靠到一侧时，对话出现双层堆叠。
-   修复了以下问题：在 VDIv2 环境中，VbSS 屏幕共享请求显示为 基于 RDP 的请求。
-   修复了以下问题：当呼叫转移失败时，失败通知中列出的是呼叫方，而不是未接来电的接听人。
-   修复了以下问题：客户端升级重定向横幅中隐藏“开始使用 Teams”按钮。
-   修复了以下问题：IM 窗口中的 DPI 缩放问题。
-   修复了以下问题：Skype for Business 联系人卡片中不显示 LinkedIn 数据。
-   用户现在可以代表智能寻线停止接听电话。
-   如果 Skype for Business 或 Teams 中有通话正在进行中，且接听或启动了新电话，现在可以自动保持呼叫。
-   修复了以下问题：用户在共享全屏后无法发送 IM。
-   修复了以下问题：会议厅中的用户在被拒绝进入会议时收不到通知。
-   修复了以下问题：在通话期间，自动增益控制的增加不受控。
-   修复了以下问题：如果会议室资源邮箱已添加到会议邀请，用户无法在“会议选项”中选择演示者。
-   修复了以下问题：如果 AllowlPVideo 设置为 False，桌面共享按钮在对等视频呼叫期间灰显。
-   修复了以下问题：将“会议选项”设置更改为对使用“禁用 IM”创建的现有会议启用 IM 后，IM 仍处于禁用状态。
-   修复了以下问题：在聊天窗口中将鼠标悬停在“插入链接”按钮之上时，工具提示不显示，并且在选择此按钮后看不到辅助功能名称。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **内置数据库模型图：** 使用新增的数据库模型图模板，可以将数据库准确建模为 Visio 图。不需要加载项。
-   **更多适用于业务图表的模具：** 使用新式形状，通过维恩图比较和对比数据，或绘制循环图、矩阵图或棱锥图来帮助传达信息。
-   **创建网站的线框图表：** 快速创建网站的线框图表，其中包含界面、导航及其协作方式。 [了解更多](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **创建移动应用程序的线框：** 使用模板创建移动应用程序的线框。[了解详细信息](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **将数据图形应用到数据可视化工具图表：** 通过自动将形状数据应用为数据图形，从而在创建数据可视化工具图表时节省时间。 [了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **协作绘图：** 通过在 OneDrive for Business 或 SharePoint Online 上共享绘图，可以与人协作绘图。可以查看谁正在处理绘图，也可以添加注释和查看文件活动。 [了解更多](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word：功能更新
-   **将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。
-   **字符计数：** 在输入过程中，可以在状态栏上看到字符计数。可以通过“自定义状态栏”菜单启用此功能。
-   **快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。
-   **Microsoft Translator：** 在 Word 中直接使用 Microsoft Translator 将字词、短语或整篇文档翻译成其他语言。[了解详细信息](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。
-   **LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **SharePoint 属性面板：** 在文档中显示和编辑 SharePoint 文档库列值。借助“视图”选项卡上的功能区按钮，可以轻松地访问面板，并且 SharePoint 管理员能够使用文档库设置自动打开属性面板。
-   **3D 模型：** 使用 3D 增强文档的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。
-   **共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。
-   **阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **使用学习工具进行编辑：** 学习工具现适用于 Word 的 Web 布局。编辑时，可以调整文字间距，并显示音节。在任意视图中，大声朗读文档时，每个单词都会突出显示。 [了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **LaTeX 语法：** 使用 LaTeX 语法创建和编辑数学公式。
-   **实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。
-   **触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。
-   **通过“编辑器”窗格增强了书写帮助：** “编辑器”窗格可用于提供高级拼写、语法和写作风格建议。对辅助技术的支持已经过改进，可以访问此窗格。

### <a name="word-security-updates"></a>Word：安全更新
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 远程执行代码漏洞
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 内存损坏漏洞
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 信息泄漏漏洞
-   [公告 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防御更新

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了以下问题：如果用户尝试对 OneDrive for Business 上的现有文档执行“另存为”操作，然后又取消保存或尝试合并现有更改，Word 发生故障。
-   修复了以下问题：运行“邮件合并”向导时，无法筛选包含 null（空）值的数据源字段。
-   修复了以下问题：保存支持同步的文件时，Office 无法对磁盘执行写入操作，但 Office 仍继续将文件上传到 OneDrive。修复此问题后，用户现在会看到错误消息，且上传不会继续执行。
-   修复了以下问题：无法撤消对文档的 IRM 保护。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 远程执行代码漏洞
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 信息泄漏漏洞
-   [公告 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防御更新

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。
-   启用 Office COM 对象时，“文件 \> 帐户 \> 更新选项”中的“立即更新”选项处于隐藏状态，以便 Configuration Manager 能够管理 Office 365 客户端更新。
-   修复了以下问题：当用户尝试使用“激活 Office”对话框激活 Office 时，Office 应用程序发生故障。
-   修复了以下问题：在动态 DPI 环境下 Office 加载项存在的缩放问题。
-   修复了以下问题：即使当前安装了 Office 365 专业增强版，Office 配置服务提供程序 (CSP) 的 CurrentStatus 节点也会返回空字符串。
-   修复了导致 .box 文件格式更改的问题，这些更改会影响安装在同一台计算机上的旧版 Office 的功能，因为 .box 文件在同一台计算机上的所有 Office 应用版本之间共享。



## <a name="version-1708-february-13"></a>版本 1708：2 月 13 日
*版本 1708（内部版本 8431.2215）*

### <a name="access-non-security-updates"></a>Access：非安全更新
-   修复了以下问题：在使用多项目窗体时，调整鼠标滚轮的位置或滚动条缩略图不更改窗体中显示的项目。

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 远程代码执行漏洞

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 特权提升漏洞
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 内存损坏漏洞

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 信息泄漏漏洞



## <a name="version-1708-january-9"></a>版本 1708：1 月 9 日
*版本 1708（内部版本 8431.2153）*

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 远程代码执行漏洞
-   [公告 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了在编程创建数据透视表后，编程刷新导致 Excel 崩溃的问题。

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 远程代码执行漏洞
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞

### <a name="word-security-updates"></a>Word：安全更新
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 远程执行代码漏洞
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 内存损坏漏洞
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 远程代码执行漏洞
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 内存损坏漏洞

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 远程代码执行漏洞
-   [公告 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防御更新

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   针对 Office 365 德国计划，为身份与本地 Active Directory 联合的域用户添加了单一登录 (SSO) 的支持。
-   添加了防止未成年人获取和激活来自 Office 应用商店的 Office 外接程序的功能。


> [!NOTE]
> 如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。