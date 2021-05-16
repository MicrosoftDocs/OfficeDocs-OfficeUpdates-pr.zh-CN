---
title: 有关每月企业频道发行的发行说明
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 向 IT 专业人士提供有关 Microsoft 365 应用版每月企业频道发行的发行说明
ms.openlocfilehash: 97275c74ed91f91cd6a307cb87bbdc83ffcdf49e
ms.sourcegitcommit: 8841de32b2d66cec6c0b07e7bc87faab0248c019
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/11/2021
ms.locfileid: "52322322"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a>每月企业频道发行说明

这些发行说明提供了有关新功能和非安全更新的信息，这些信息包含在 Microsoft 365 企业应用版、Microsoft 365 商业应用版，以及 Project 和 Visio 桌面应用订阅版本的每月企业频道更新中。


[//]: # (请勿移除)



## <a name="version-2103-may-11"></a>版本 2103：5 月 11 日
*版本 2103(内部版本 13901.20516)*

[此处](microsoft365-apps-security-updates.md)列出安全更新


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自动使用新数据类型**：当您键入类似于股票或地理位置的数据值时，Excel 将其转换为适当的关联数据类型：股票或地理位置。 [了解更多](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **链接数据类型：真实方案的真实数据：** 新链接数据类型带来数百个主题的事实和数据，帮助你在 Excel 中完成目标。

### <a name="outlook"></a>Outlook

- **使用内置翻译工具打破语言障碍：** 不再需要翻译加载项！ 现可在 Outlook 中使用智能翻译工具。 当你收到一封其他语言的邮件时，邮件顶部将显示一条提示，询问你是否希望 Outlook 将其翻译成默认语言。
也可以右键单击以翻译特定字词、短语或整封邮件。 [了解更多](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a>Visio

- **图表的现成图形：** 从可添加到 Visio 绘图中的图标、库存照片图像、人像抠图和贴纸的大型库中进行选择。 [了解更多](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />在[博客文章](https://insider.office.com/zh-CN/blog/access-illustrations-icons-in-visio)中查看详细信息


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 我们修复了外部应用程序请求辅助功能界面时，在其释放引用之前阻止我们关闭的问题。


- 此更改修复了在某些情况下，运行 SQL Server 通过查询可能会导致错误消息表明存在"光标状态无效"的问题。


### <a name="excel"></a>Excel

- 已修复使用加载项时某些语言的日期格式显示错误的问题。


- 已修复某些用户无法使用分析工具库加载项的问题。


- 已修复绘制图像时 Word 中可能的挂起问题。


### <a name="outlook"></a>Outlook

- 我们修复了一个问题，该问题导致当代表另一个用户发送邮件，并针对不是全局地址列表的通讯簿进行解析时，名称解析失败。


- 修复了导致 Outlook 覆盖 OWA 中配置的重点收件箱首选项这一问题。


- 修复了导致某些人员无法访问与次要邮件账户关联的签名问题。


- 修复了导致用户看到比预期多的签名问题。


- 修复了导致某些用户在导航窗格中看到主要和次要日历调换位置的问题。


- 我们修复了添加日历时导致用户错误地看到"这可能需要一段时间"消息的问题。


- 我们解决了导致代理人显示为新添加的日历上创建的会议的组织者这一问题。  在此州/省/市/区中的会议不会在主体的日历上显示。


- 修复了一个 Outlook 组件中的问题，该组件用于具有 ARM 处理器的计算机上启用 MAPI 的应用程序。 该问题可能导致搜索失败，或者由于后台应用反复重启而导致电脑产生额外负载。


- 修复了导致在同步文件夹层次结构更改时某些用户意外关闭 Outlook 的问题。


- 已修复绘制图像时 Word 中可能的挂起问题。


### <a name="powerpoint"></a>PowerPoint

- 我们修复了与链接图片相关的问题。


- 已修复绘制图像时 Word 中可能的挂起问题。


### <a name="project"></a>Project

- 修复了 Visio 在关闭期间停止运行的问题。


### <a name="visio"></a>Visio

- 修复了 Visio 在关闭期间停止运行的问题。


### <a name="word"></a>Word

- 修复了提供的用于文本预测的优化条件问题。


- 修复了有关自动保存标注为文件保存在本地的更新文本问题。


- 修复了共同创作文档时，在批注顺序更改时没有清除活动草稿的问题。


- 修复了打印预览意外关闭的问题。


- 已修复绘制图像时 Word 中可能的挂起问题。



### <a name="office-suite"></a>Office 套件

- 修复了与会话 0 中运行的 Office 应用支持相关的可靠性问题。


- 修复了在离线状态下打开 SyncBacked 文件，在保存文件之前重命名应用中的文件，而重命名操作没有响应的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-may-11"></a>版本 2102：5 月 11 日
*版本 2102(内部版本 13801.20638)*

[此处](microsoft365-apps-security-updates.md)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 已修复使用加载项时导致某些语言的日期格式显示错误的问题。


- 修复了阻止系统能够在受保护的工作表上粘贴公式的问题。


### <a name="outlook"></a>Outlook

- 这使最终用户可以配置 Outlook，以将联机会议添加到所创建的所有会议。


### <a name="powerpoint"></a>PowerPoint

- 我们修复了与链接图片相关的问题。


### <a name="word"></a>Word

- 修复了 Wordmail 中（当链接中的第 2084 个字符是转义字符时）出现有人“无法发送该项目”的问题。


### <a name="office-suite"></a>Office 套件

- 修复了打印长文档时出现 Word 意外关闭的问题。


- 在更改前，即使开启了禁用 Office 模板的 GPO，也会显示这些模板。 通过此更改，模板现可正确执行 GPO 并按要求进行显示/隐藏。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-april-13"></a>版本 2102：4 月 13 日
*版本 2102（内部版本 13801.20506）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用“高级”对话框创建数据类型：** 在“高级”对话框中，可手动选择合并所创建数据类型的列。

- **同时取消隐藏多张工作表：** 不再需要一次取消隐藏一个工作表，可以一次取消隐藏多个隐藏工作表。 [了解详细信息](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a>Outlook

- **“重点收件箱”设置在各设备之间保持不变：** 重点收件箱的首选项现在存储在云中。 在任何计算机上使用 Outlook for Windows 和 Outlook 网页版时，都可享受相同的体验。 [了解更多](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **云端的 Outlook 设置：** 选择 Outlook for Windows 设置（如“自动答复”、“重点收件箱”和“隐私”），然后在任何电脑上进行访问。

- **选择搜索位置：**“新建搜索范围”下拉列表使你能够更轻松地修改搜索并在当前文件夹和当前邮箱之间切换。 感谢在“即将推出”中对新的“热门搜索”体验提供反馈的每个人员。 此项设计和更新正是来自于该反馈！

- **使用语音撰写邮件：** 使用新的听写工具栏，语音命令，自动标点符号等撰写邮件。

### <a name="word"></a>Word

- **使用语音撰写文档：** 使用新的听写工具栏，语音命令和自动标点来起草文档。


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 修复了在某些情况下，运行 SQL Server 通过查询可能会收到指明"光标状态无效"的错误消息的问题。



### <a name="excel"></a>Excel

- 修复了在另一张工作表上添加行后，数据验证可能会意外应用到单元格的 Bug。


- 修复了对话框表显示函数在 32 位版本的 Excel 中无法正常工作这一问题


- 我们修复了使用“粘贴链接图片”选项时导致图像小于预期的问题。


- 我们修复了保存为 .xls 或 .xlt 格式时导致某些数据透视表格式设置损坏工作簿的问题。


- 我们修复了一个阻止用户将 Excel 工作簿导出为 PDF 的问题。


- 解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。


### <a name="outlook"></a>Outlook

- 修复了导致内联翻译用户无法提交反馈的问题。


- 修复了导致用户看到包含 unicode 内容的签名受损的问题。


- 修复了导致用户看到签名超过预期的问题。


- 修复了导致 Outlook 在空闲时崩溃的问题。


- 我们修复了导致部分用户在关闭消息窗口时遇到关闭应用程序的问题。


- 修复了导致“共享日历”改进用户无法将日历的颜色设置为黄色或棕色的问题。


- 修复并解决了导致用户在创建新组后看到重复日历组的问题。


- 我们修复了导致用户看到新添加的日历直到 Outlook 重新启动之后才会显示在导航窗格中的问题。


### <a name="powerpoint"></a>PowerPoint

- 解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。


### <a name="word"></a>Word

- 我们已修复了在共同身份验证时解决冲突的问题。


- 我们修复了富文本内容控件的问题。


- 我们修复了在隐藏段落末尾键入时可能导致应用程序挂起的问题。


- 我们修复了讲述人可能跳过某个段落的问题。


- 修复了与复制和粘贴相关的问题。


- 我们修复了应用于图标和具有 3D 效果的 SVG 图形的颜色问题。


- 解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。


### <a name="office-suite"></a>Office 套件

- 修复了与会话 0 中运行的 Office 应用支持相关的可靠性问题。


- 修复了有时可能导致 Outlook 中的文本变为透明且无法清晰显示的问题。


- 修复了在含有数学公式的文本内使用讲述人时可能发生的问题。


- 修复了 GCC 用户禁用听写的问题


- 解决了用户在打开以前打开的文件时无法保存文件（其中未保存编辑，但现在文件已删除）的问题。 修复后，用户收到友好消息，告知用户文件已删除，因此用户可选择放弃更改或另存为文件。


- 修复了脱机打开 SyncBacked 文件，然后在保存文件之前在应用中重命名文件时出现重命名失败问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2101-april-13"></a>版本 2101：4 月 13 日
*版本 2101（内部版本 13628.20664）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 列出安全更新

## <a name="version-2101-march-09"></a>版本 2101：3 月 9 日
*版本 2101（内部版本 13628.20528）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题


### <a name="outlook"></a>Outlook

- 修复了使用仅加密选项发送的电子邮件上无法显示加密图标的问题。


- 我们已修复了在用户取消选中该选项后导致邮件以数字签名方式发送的问题。


- 我们修复了导致 OWA 中显示正确默认签名问题的问题。


- 我们修复了一个导致云设置用户在更新设置时体验挂起的问题。


- 我们修复了导致用户在 Outlook 中搜索时应用有时意外关闭的问题。


- 我们修复了导致配置文件中具有较大层次结构共享邮箱或委派邮箱的用户遇到挂起的问题。


- 我们修复了导致某些用户在特定搜索方案中遇到 Outlook 意外关闭的问题。


### <a name="project"></a>Project

- 修复了将成本资源分配给里程碑任务时，基线成本没有正确汇总的问题。


- 解决了视图中不显示任务边框的问题。


- 解决了“工作组规划器”视图中的拖放功能无法用于任务的问题。


### <a name="office-suite"></a>Office 套件

- 修复了与媒体控制器事件通知相关的问题。


- 修复了与媒体播放器引擎计时相关的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2012-march-09"></a>版本 2012：3 月 9 日
*版本 2012（内部版本 13530.20628）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **要求用户应用敏感度标签：** 如果组织的策略要求，系统会提示用户应用敏感度标签。

### <a name="powerpoint"></a>PowerPoint

- **要求用户应用敏感度标签：** 如果组织的策略要求，系统会提示用户应用敏感度标签。

### <a name="word"></a>Word

- **要求用户应用敏感度标签：** 如果组织的策略要求，系统会提示用户应用敏感度标签。


## <a name="version-2012-february-09"></a>版本 2012：2 月 09 日
*版本 2012（内部版本 13530.20528）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **SVG 剪贴板支持：** 现在你可以将 Office 中的 SVG 内容粘贴到第三方应用程序中。 [了解详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **敏感度标签审核日志记录：** 当用户应用、更改或删除其文档和电子邮件上的敏感度标签时，Microsoft 365 审核日志中的管理员现在可以使用这些信息。

- **政府客户：对文档和电子邮件应用敏感度标签：** 敏感度标签功能现已适用于 GCC 和 GCC-H 环境中的客户。 [了解更多](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **SVG 剪贴板支持：** 现在你可以将 Office 中的 SVG 内容粘贴到第三方应用程序中。 [了解详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **在连续召开的会议之间提供时间：** 默认将会议设置为推迟 5-10 分钟开始，让与会者有时间喘口气或来往于不同地点。 [了解详细信息](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **敏感度标签审核日志记录：** 当用户应用、更改或删除其文档和电子邮件上的敏感度标签时，Microsoft 365 审核日志中的管理员现在可以使用这些信息。

- **所有联机会议：** 更新日历设置，确保在创建每个会议时都默认创建 Teams 会议，从而无需再记住单击“Teams 会议”选项。

- **政府客户：对文档和电子邮件应用敏感度标签：** 敏感度标签功能现已适用于 GCC 和 GCC-H 环境中的客户。 [了解更多](/microsoft-365/compliance/sensitivity-labels)

- **所有联机会议：** 更新日历设置，确保在创建每个会议时都默认创建 Teams 会议，从而无需再记住单击“Teams 会议”选项。

- **新的会议室查找器：** 根据不同功能搜索会议室。

- **新式会议室和工作区预定体验：** 会议室预定体验已刷新，通过此体验，我们添加了允许你安排个别工作区的功能


### <a name="powerpoint"></a>PowerPoint

- **SVG 剪贴板支持：** 现在你可以将 Office 中的 SVG 内容粘贴到第三方应用程序中。 [了解详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />在[博客文章](https://insider.office.com/zh-CN/blog/svg-content-office-third-party-apps)中查看详细信息

- **敏感度标签审核日志记录：** 当用户应用、更改或删除其文档和电子邮件上的敏感度标签时，Microsoft 365 审核日志中的管理员现在可以使用这些信息。

- **政府客户：对文档和电子邮件应用敏感度标签：** 敏感度标签功能现已适用于 GCC 和 GCC-H 环境中的客户。 [了解更多](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a>Visio

- **新 Azure 图案和形状：** 我们添加了很多图案，以帮助创建最新的 Azure 图表。 [了解详细信息](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **SVG 剪贴板支持：** 现在你可以将 Office 中的 SVG 内容粘贴到第三方应用程序中。 [了解详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **敏感度标签审核日志记录：** 当用户应用、更改或删除其文档和电子邮件上的敏感度标签时，Microsoft 365 审核日志中的管理员现在可以使用这些信息。

- **政府客户：对文档和电子邮件应用敏感度标签：** 敏感度标签功能现已适用于 GCC 和 GCC-H 环境中的客户。 [了解更多](/microsoft-365/compliance/sensitivity-labels)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 此更改解决了在公式中正确显示字体的问题。


- 修复了以下问题：当某些用户共同创作时，会错误地向其显示存在新文件版本的消息栏通知。


- 修复了当打开包含 Excel 4.0 宏的 Excel 加载项文件时，Excel 可能会禁用宏而不提示的问题。


- 修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题。


- 修复了使用数据透视表的“值显示方式”菜单时，Excel 可能意外关闭的问题。


- 我们修复了某些旧版 Excel 4.0 和 Excel 5.0 宏以及对话框表.show 的一些 VBA 调用的问题。


### <a name="outlook"></a>Outlook

- 我们修复了在提示用户保存后，编辑的签名无法保存的问题。


- 修复了某些搜索方案中导致某些用户意外体验 Outlook 关闭的问题。


- 我们修复了导致一些用户在加载日历时遇到挂起的问题。


- 修复了导致配置文件中具有较大层次结构的共享邮箱或委派邮箱的用户遇到挂起的问题。


### <a name="powerpoint"></a>PowerPoint

- 修复了 QAT 中添加的字号命令在更新时自动完成以最接近定义字号的问题。


- 此更改解决了在公式中正确显示字体的问题。


- 此更改解决了使用特定几何图形对合并形状操作应用时路径填充的问题。


### <a name="office-suite"></a>Office 套件

- Anaheim WebView 尚不支持 Windows 信息保护(WIP)。 通过此修复，Office 插件平台可以在启用 WIP 的环境中回退到较低级别的 WebView。 根据客户的计算机环境，它可以是 Edge Spartan WebView 或 Trident WebView。 两个低级别 WebView 均支持 WIP。


- 经过优化的二进制大小。


- 修复了文件关闭序列，以便完全关闭所有组件。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2011-february-09"></a>版本 2011：2 月 09 日
*版本 2011（内部版本 13426.20658）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新

## <a name="version-2011-january-12"></a>版本2011：1月12日
*版本2011（内部版本13426.20526）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **创建用于公式的变量：** 通过 LET 函数改进性能、可读性和可组合性。 此功能允许你在新的或预先存在的公式中创建已命名的变量。 [了解更多](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />在[博客文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看详细信息

- **在 Power Query 中创建自定义数据类型：** 使用任何数据源创建一个自定义数据类型，让你将多个相关信息加载到一列中。 [了解更多](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />在[博客文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看详细信息

- **在源查询之后命名新工作表：** 将数据加载到新工作表中时，将根据源查询名称命名工作表。

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a>PowerPoint

- **视频库：** 通过应用内所提供的免版税视频素材库来提升你的文档。

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **自动切换 Office 主题：** Office 可自动切换主题，使其与 Windows 10 主题设置相匹配。 转到“文件”>“帐户”，然后在“Office 主题”下拉列表中选择“使用系统设置”。 [了解详细信息](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修复了以下问题：Excel 错误地显示新版本文件可用的消息栏，并强制用户将更改保存在工作簿副本中或放弃更改。


- 修正了当打开包含 Excel 4.0 宏的 Excel 加载项文件时，Excel 可能会禁用宏而不提示的问题。


### <a name="outlook"></a>Outlook

- 我们已修复虽以配置一个或多个签名，但仍导致有的用户在签名下拉菜单中看不到签名的问题。


- 我们添加了一个 regkey，允许客户在 IDataObject 操作中禁用附件的 filetime 包含（例如，拖放、剪贴板）。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。 REG_DWORD IncludeFileTimesInDataObject。 0 = filetimes 被排除。 1 = （默认）包含 filetime。


- 我们修复了以下问题：当回复带有来自 Azure 信息保护的保护标签的邮件时，将导致嵌入式图像消失。


- 我们修复了导致 MailItem.BeforeAttachmentAdd 事件收到破坏的问题。


- 我们修复了在发送任务状态报告时，“收件人”字段为空的问题。


- 我们解决了导致某些会议的原定与会者在其他与会者转发会议时收到取消通知的问题。


### <a name="powerpoint"></a>PowerPoint

- 修复了一些损坏的 PowerPoint 文件即使在执行文档修复操作后亦无法正常打开的问题。


- 我们修复了以下问题：复制包含新近录制的音频的幻灯片后，保存文件时出现错误。


- 我们修复了 Slide.Shapes.AddMediaObject2 在使用传统的视频格式（MPG-1、Mpeg-2）时会崩溃的 VBA 问题。


- 此更改解决了处理视频加载过程中可能出现的错误的问题。


- 修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。


### <a name="project"></a>Project

- 已修复项目文件加载到特定部分出现错误，导致可能打开特定项目的问题。


### <a name="word"></a>Word

- 修复了影响 Word 的优化关口所暴露出的申明错误。


- 我们修复了替换文档样式为模板中的其他样式的问题。


- 此更改解决了编辑文档时光标存在的问题。


- 修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。


### <a name="office-suite"></a>Office 套件

- 修正了在某些旧版本上安装较新版本的Office，可能会因缺少注册表项而导致功能受损（例如无法使用Power Query）的问题。


- 修正了当来自缓存的 URL 和来自 OneDrive 的 URL 不匹配时，文件在打开时不同步的问题。


- 我们修复了 SaveRequestManagerCam 导致应用程序关闭而不是返回错误的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2010-january-12"></a>版本 2010：1 月 12 日
*版本2010（内部版本13328.20550）*

[此处](./microsoft365-apps-security-updates.md)列出安全更新



[//]: # (请勿移除错误详细信息内容结尾)


[//]: # (请勿移除错误详细信息内容结尾)

[//]: # (请勿移除结尾)

> [!NOTE]
> 如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。


[//]: # (不修改管理中心元数据内容启动)
[//]: # (|Win32|MEC|生产|功能|16.0.13901.20516|版本-2103-5-11|)
[//]: # (|Win32|MEC|生产|功能|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|生产|功能|16.0.13628.20528|版本-2101-3-9|)
[//]: # (|Win32|MEC|生产|功能|16.0.13530.20528|版本-2012 年 2 月 9 日|)
[//]: # (|Win32|MEC|生产|功能|16.0.13426.20526|版本-2011年1月12日|)
[//]: # (|Win32 |MEC |生产|功能|16.0.13328.20478|2010 年 12 月8 日版|)
[//]: # (|Win32|MEC|生产|功能|16.0.13231.20514|2009 年 11 月 10 日版|)
[//]: # (|Win32|MEC|生产|功能|16.0.13127.20638|2008 年 10 月 13 日版|)
[//]: # (|Win32|MEC|生产|功能|16.0.13029.20534|version-2007-september-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13001.20520|version-2006-august-11|)
[//]: # (不修改管理中心元数据内容结束)
