---
title: 有关 2021 年半年企业频道（预览）发行的发行说明
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2021 年 Microsoft 365 应用版半年频道（定向）发行的发行说明
ms.openlocfilehash: 89c71d3aae644cf5d77a0568643a82175806a468
ms.sourcegitcommit: 556c7532cd820796db244f0949205c75c013d9fc
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/13/2021
ms.locfileid: "52470776"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a>有关半年企业频道（预览）的发行说明

我们为 Microsoft 365 企业应用版、Microsoft 365 商业应用版以及 Project 和 Visio 桌面应用的订阅版本提供了半年企业频道（预览）更新。这些发行说明提供了有关这些更新中所含新功能和非安全更新的信息。


## <a name="version-2102-may-11"></a>版本 2102：5 月 11 日
*版本 2102（内部版本 13801.20638）*

此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修复了 Excel 无法加载某些自动化加载项的问题。


- 已修复使用加载项时导致某些语言的日期格式显示错误的问题。


- 修复了阻止在受保护的工作表上粘贴为公式的能力的问题。


### <a name="outlook"></a>Outlook

- 这使最终用户可以配置 Outlook，以将联机会议添加到所创建的所有会议。


### <a name="powerpoint"></a>PowerPoint

- 我们修复了与链接图片相关的问题。


### <a name="word"></a>Word

- 修复了链接中第 2084 个字符为转义字符时，某些用户无法在 Wordmail 中发送项目的问题。


### <a name="office-suite"></a>Office 套件

- 修复了即使 GPO 发出禁用请求，但 Office 模板仍然打开的问题。


- 修复了打印长文档时导致 Word 意外关闭的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-april-13"></a>版本 2102：4 月 13 日
*版本 2102（内部版本 13801.20506）*

此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 修复了在某些情况下，运行 SQL Server 通过查询可能会收到指明"光标状态无效"的错误消息的问题。


### <a name="excel"></a>Excel

- 解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。


- 修复了在另一张工作表上添加行后，数据验证可能会意外应用到单元格的问题。


- 修复了对话框表显示函数在 32 位版本的 Excel 中无法正常工作这一问题


### <a name="outlook"></a>Outlook

- 修复了导致 Outlook 在空闲时崩溃的问题。


- 我们修复了导致云设置功能用户在新设备上配置 Outlook 后会看到默认设置覆盖自定义设置的问题。


- 修复了导致用户看到签名超过预期的问题。


### <a name="powerpoint"></a>PowerPoint

- 解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。


### <a name="word"></a>Word

- 解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。


- 修复了与复制和粘贴相关的问题。


- 我们修复了在隐藏段落末尾键入时可能导致应用程序挂起的问题。


### <a name="office-suite"></a>Office 套件

- 解决了用户在打开以前打开的文件时无法保存文件（其中未保存编辑，但现在文件已删除）的问题。 修复后，用户收到友好消息，告知用户文件已删除，因此用户可选择放弃更改或另存为文件。


- 修复了脱机打开 SyncBacked 文件，然后在保存文件之前在应用中重命名文件时出现重命名失败问题。


- 修复了 GCC 用户禁用听写的问题


- 修复了有时可能导致 Outlook 中的文本变为透明且无法清晰显示的问题。


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-march-09"></a>版本 2102：3 月 9 日
*版本 2102（内部版本 13801.20294）*

此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。<br />在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息

- **建立 PDF 连接：** 连接到 PDF，从其中导入数据，刷新数据。 [了解更多](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **创建用于公式的变量：** 通过 LET 函数改进性能、可读性和可组合性。 此功能允许你在新的或预先存在的公式中创建已命名的变量。 [了解更多](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />在[博客文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看详细信息

- **保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。  我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。 我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。 这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。 [了解更多](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息

- **使用数据类型从 Power BI 获取组织数据：Power BI 中的** Excel 数据类型现向具有 Office 365/Microsoft 365 和 Power BI Pro 服务计划的组织的预览体验成员推出。 获取所需信息并轻松刷新，这对许多日常工作流至关重要。 我们将为你提供从 Power BI 到 Excel 中的数据类型的公司或组织信息的访问权限，这将扩大你在电子表格中引入链接信息的能力。 [了解更多](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />在[博客文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看详细信息

- **将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。 无需转换。<br />在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息

- **在 Excel 中制作精美的 Visio 图表：** 根据工作表中的数据创建数据驱动的图表，例如流程图或组织结构图。 [了解更多](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **帮助保护组中的数据：** 你在创建组时选择的敏感度标签应用于组电子邮件、文档和团队网站。

- **IT 管理员事件通知：** 使用 Outlook for Windows 中的新右侧面板通知，Microsoft 365 租户全局管理员和 Office 应用程序管理员将收到有关影响用户的 Outlook 和 O365 通知。 [了解更多](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **在 Outlook 中使用快速投票创建投票：** 轻松创建投票、收集选票和在电子邮件中查看结果 [了解详细信息](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。 无需转换。<br />在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息

- **新的会议室查找器：** 根据不同功能搜索会议室。

- **按照你说的方式搜索目标：** 使用日常语言（如“上周预约的兽医”）来筛选和缩小搜索范围。

- **从上一个 Outlook 会话快速重新打开项目的选项：** 我们添加了一个选项，可以从上一个 Outlook 会话快速重新打开项目。<br />在[博客文章](https://insider.office.com/zh-CN/blog/automatically-restore-windows-in-outlook)中查看详细信息

### <a name="powerpoint"></a>PowerPoint

- **墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。<br />在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息

- **保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。  我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。 我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。 这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。 [了解更多](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息

- **将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。 无需转换。<br />在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息

### <a name="visio"></a>Visio

- **新 Azure 图案和形状：** 我们添加了很多图案，以帮助创建最新的 Azure 图表。 [了解详细信息](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。<br />在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息

- **保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。  我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。 我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。 这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。 [了解更多](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息

- **将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。 无需转换。<br />在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息

### <a name="office-suite"></a>Office 套件

- **制表符窗格：** 现在，可以使用应用程序右侧的选项卡 UI 在多个窗格之间进行切换。 UI 将只在当打开2个以上的窗格时才会可见。<br />在[博客文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看详细信息


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 我们修复了从非 Office 应用程序使用 DAO 时会导致应用程序意外关闭的问题。


- 我们修复了用户收到错误对话”光标状态无效的问题。


### <a name="excel"></a>Excel

- 我们修复了某些中断旧版 Excel 4.0 和 Excel 5.0 宏以及某些对 dialogsheets.show 的 VBA 调用的问题。


- 修复了使用数据透视表的“值显示方式”菜单时，Excel 可能意外关闭的问题。


- 我们修复了一个阻止用户将 Excel 工作簿导出为 PDF 的问题。


- 我们修复了使用“粘贴链接图片”选项时导致图像小于预期的问题。


- 我们修复了保存为 .xls 或 .xlt 格式时导致某些数据透视表格式设置损坏工作簿的问题。


- 修复了打开包含 Excel 4.0 宏的 Excel 加载项文件时，Excel 可能会禁用宏而不提示的问题。


- 修复了以下问题：Excel 错误地显示新版本文件可用的消息栏，并强制用户将更改保存在工作簿副本中或放弃更改。


- 修复了以下问题：当某些用户共同创作时，会错误地向其显示存在新版本文件的消息栏通知。


- 修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题。


- 我们修复了在图表中选择数据系列后 Excel 停止响应的问题。


- 此更改解决了在公式中正确显示字体的问题。


### <a name="outlook"></a>Outlook

- 解决了导致用户无法向其代理授予编辑器权限的问题。


- 我们解决了导致某些用户在特定搜索方案中遇到 Outlook 意外关闭的问题。


- 修复了导致配置文件中具有较大层次结构的共享邮箱或委派邮箱的用户遇到挂起的问题。


- 解决了当主题行为空白时，某些自动生成的电子邮件将发送空白正文的问题。


- 解决了导致部分用户观察到 Outlook 在离线状态下意外启动的问题。


- 解决了导致代理在其他邮箱中打开共享文件夹时出现间歇性故障的问题。


- 我们修复了导致用户在选择搜索结果时遇到应用程序意外终止的问题。


- 我们修复了导致一些客户在加载日历时遇到挂起的问题。


- 我们修复了导致某些会议的原定与会者在其他与会者转发会议时收到取消通知的问题。


- 修复并解决了导致用户在创建新组后看到重复日历组的问题。


- 修复了导致“共享日历”改进用户无法将日历的颜色设置为黄色或棕色的问题。


- 我们修复了导致用户看到新添加的日历直到 Outlook 重新启动之后才会显示在导航窗格中的问题。


- 解决了在搜索未缓存的共享日历时，导致搜索不返回结果的问题。


- 我们修复了导致部分用户在关闭消息窗口时遇到关闭应用程序的问题。


- 我们修复了在发送任务状态报告时导致“收件人”字段为空的问题。


- 我们修复了导致 MailItem.BeforeAttachmentAdd 事件被破坏的问题。


- 我们修复了导致某些用户在特定搜索方案中遇到 Outlook 意外关闭的问题。


- 我们修复了导致用户在 Outlook 中搜索时应用有时意外关闭的问题。


- 我们修复了一个导致云设置用户在更新设置时体验挂起的问题。


- 我们修复了在提示用户保存后，已编辑的签名无法保存的问题。


- 我们已修复虽以配置一个或多个签名，但仍导致有的用户在签名下拉菜单中看不到签名的问题。


- 我们修复了导致默认情况下不会为用户打开云设置的问题。


- 我们修复了导致无法保存用户签名更改的问题。


- 我们修复了导致 Outlook 为已启用云设置的用户创建第二个空签名的问题。


- 我们修复了一个问题，该问题导致 OWA 中显示正确默认签名问题。


- 修复了导致用户看到包含 unicode 内容的签名受损的问题。


- 修复了导致内联翻译用户无法提交反馈的问题。


- 解决了导致在答复或转发时中文电子邮件的标题不可阅读的问题。


- 我们修复了另存为 OFT 文件时汉字变成问号的问题。


- 我们添加了一个 regkey，允许客户在 IDataObject 操作中禁用附件的 filetime 包含（例如，拖放、剪贴板）。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。  REG_DWORD IncludeFileTimesInDataObject。  0 = filetimes 被排除。  1 = （默认）包含 filetime。


- 我们修复了以下问题：当回复带有来自 Azure 信息保护的保护标签的邮件时，将导致嵌入式图像消失。


- 修复了使用仅加密选项发送的电子邮件上无法显示加密图标的问题。


- 我们已修复了在用户取消选中该选项后导致邮件以数字签名发送的问题。


### <a name="powerpoint"></a>PowerPoint

- 修复了可能导致应用程序在文件保存失败时意外关闭的问题。


- 修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。


- 此更改解决了使用特定几何图形对合并形状操作应用时路径填充的问题。


- 此更改解决了在公式中正确显示字体的问题。


- 此更改解决了处理视频加载过程中可能出现的错误的问题。


- 我们修复了 Slide.Shapes.AddMediaObject2 在使用传统视频格式（MPG-1、Mpeg-2）时会意外关闭的 VBA 问题。


- 我们修复了 QAT 中添加的字号命令在更新时自动完成为最接近定义字号的问题。


- 我们修复了以下问题：复制包含新近录制音频的幻灯片后，保存文件时出现错误。


- 我们修复了表单内容加载项在插入后不显示，而要到用户单击另一张幻灯片来使其显示时才显示的问题。


- 我们修复了在受保护的视图中打开 PowerPoint 文件时禁用 IRM 保护的问题。


- 修复了在包含大量特定数据对象类型 (E2o) 的文件上导致共同创作速度下降的问题。


- 修复了在合并错误过程中使用 IRM/受保护的文档时遇到的问题。


- 这是针对以下问题的修补程序：关闭文档且存在侦听 PresentationBeforeClose 事件和检查作为事件处理程序一部分的 Presentation.Saved 属性的加载项时，“保存”提示会循环显示。


- 修复了一些损坏的 PowerPoint 文件即使在执行文档修复操作后也无法正常打开的问题。


- 解决了某些情况下选择设计创意会删除演示文稿数据分类标签的问题。


### <a name="project"></a>Project

- 修复了以下问题：将项目从 PWA 保存到本地 mpp 文件时，用户实际上未更改的数据将触发 ProjectBeforeTaskChangeEvent。


- 修复了以下问题：如果在“任务窗体”类型视图中更改了滞后，ProjectBeforeTaskChange 事件中的 NewVal 没有正确的值。


- 修复了以下问题：如果你正在运行事件代码并尝试通过 “任务窗体”视图进行更改，单击“确定”按钮可能无法提交所做的更改。


- 解决了打开以特定方式指定资源分布的文件时，Project 可能意外终止的问题。


- 已修复项目文件加载到特定部分出现错误，导致可能打开特定项目的问题。


- 解决了视图中不显示任务边框的问题。


- 解决了“工作组规划器”视图中的拖放功能无法用于任务的问题。


- 修复了将成本资源分配给里程碑任务时，基线成本没有正确汇总的问题。


### <a name="visio"></a>Visio

- 我们修复了一个问题，用户以后可以使用 Visio for Office 365 中的连接器创建自定义 Visio 模具和内置模板的直线。


### <a name="word"></a>Word

- 修复了可能导致应用程序在文件保存失败时意外关闭的问题。


- 修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。


- 此更改解决了编辑文档时光标存在的问题。


- 我们修复了将颜色应用于图标和具有 3D 效果的 SVG 图形的问题。


- 我们修复了讲述人可能跳过某个段落的问题。


- 我们修复了富文本内容控件的问题。


- 我们修复了“样式库”对话框的问题。


- 我们已修复了在共同创作时解决冲突的问题。


- 我们修复了以模板中的其他样式替换文档样式的问题。


- 修复了影响 Word 的优化关口所暴露出的申明 bug。


### <a name="office-suite"></a>Office 套件

- 解决了尝试保存文件导致故障的问题，该文件从同步备份转换为仅支持服务器。


- 修复了在某些情况下尝试执行 SaveAs 操作时失败的问题。


- 我们修复了 SaveRequestManagerCam 导致应用程序关闭而不是返回错误的问题。


- 修复了文件关闭序列，以便完全关闭所有相互依赖组件。


- 修复了当来自缓存的 URL 和来自 OneDrive 的 URL 不匹配时，文件在打开时不同步的问题。


- 修复了 Skype for Business 消息中复制/粘贴导致出现"粘贴内容时出错"的对话框的 bug。


- 修复了将注释中的文本复制/粘贴到 Excel 时出错的问题。


- 修复了在包含数学公式的文本中使用讲述人时可能发生的崩溃。


- 当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。将信息更改为显示“碳粉/墨水不足”&“无碳粉/墨水”。


- 修正了在某些旧版本上安装较新版本的Office，可能会因缺少注册表项而导致功能受损（例如无法使用Power Query）的问题。


- 修复了 Microsoft 365 终结点数据丢失防护无法对磁盘上的 Office 文档进行分类的问题。


- 我们修复了“压缩图片”对话框不保留某些用户设置的问题。


- 修复了与媒体控制器事件通知相关的问题。


- 修复了与媒体播放器引擎计时相关的问题。


- 经过优化的二进制大小。


- Anaheim WebView 尚不支持 Windows 信息保护(WIP)。 通过此修复，Office 插件平台可以在启用 WIP 的环境中回退到较低级别的 WebView。 根据客户的计算机环境，它可以是 Edge Spartan WebView 或 Trident WebView。 两个低级别 WebView 均支持 WIP。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-february-09"></a>版本 2008：2 月 09 日
*版本 2008（内部版本 13127.21216）*

此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修复了打开具有无效文件属性的 UNC 文件时 Excel 会意外关闭的问题（创建时间、修改时间等）


- 修复了将图表从 Excel 复制并粘贴到 Word 或 PowerPoint 时无法执行小数和千位分隔符设置的问题。


- 我们修复了这样一个问题，即每次运行宏时，涉及数据透视表区域格式的宏的性能会变差。


- 修复了在将工作表复制或移动到另一个工作簿时条件格式规则被删除的问题。


- 修复了禁用应用启动屏幕时，用户无法将敏感度标签应用到 Excel 文件这一问题。


- 修复了从 OneDrive 同步文件夹打开云文件时出现的问题。


### <a name="outlook"></a>Outlook

- 解决了导致 Outlook 在添加或保存附件时偶尔停止工作的问题。


### <a name="powerpoint"></a>PowerPoint

- 修复了 QAT 中添加的字号命令在更新时自动完成以最接近定义字号的问题。


- 修复了采用"保留源格式"选项的幻灯片复制和粘贴有时意外复制到新幻灯片母版上的问题


### <a name="word"></a>Word

- 修复了修订中的问题：有时打开 Word 文档可能会显示错误对话框。


- 修复了从 OneDrive 同步文件夹打开云文件时出现的问题。


### <a name="office-suite"></a>Office 套件

- 解决了阻止在 Office 中成功打开文件的问题。


- 修复了通过格式刷将包含草图轮廓应用到连接线的文档可能会损坏的问题。



[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-2008-january-12"></a>版本2008：1月12日
*版本2008（内部版本13127.21064）*

此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修正了只读书籍在打开时不再刷新数据透视表数据的问题。


- 此更改提供了对以下问题的修复：当从OneDrive本地同步文件夹插入文件时，Excel "插入对象 "不显示正确的图标。


- 修正了当客户在共同创作时，会错误地收到关于新版本文件通知的问题。


- 修正了在覆写模式下使用输入法编辑器会错误地推进额外字符的编辑问题。


- 修正了在使用实时数据和多线程重新计算功能时所出现的问题。


- 修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题


### <a name="outlook"></a>Outlook

- 我们修复了保存到草稿时，SmartLink 格式丢失的问题。


- 修复了替代策略时为用户提供自定义对齐文本方法的问题。


- 我们修复了另存为 OFT 文件时汉字变成问号的问题。


### <a name="powerpoint"></a>PowerPoint

- 我们修正了 Slide.Shapes.AddMediaObject2 在使用传统视频格式（MPG-1,Mpeg-2）时会意外关闭的 VBA 问题。


- 已修复一些损坏的 PowerPoint 文件无法正常打开的问题，即使在执行文档修复操作后也是如此。


### <a name="project"></a>Project

- 修正了当以某种方式指定资源分布时，项目可能在打开文件时意外终止的问题。


### <a name="skype"></a>Skype

- 修复了用户的 TLS-DSK 证书无法在预期时间内更新，而是在有效期剩余不到12小时时续订。


- 修复了当Office尚未获得授权时，Skype for Business用户界面在登录后显示为空白的问题。


### <a name="office-suite"></a>Office 套件

- 此更改解决了与打开包含遗留图的文件相关的问题。


- 此更改解决 SVG 回退代理导致访问违规的问题。



[//]: # (请勿移除错误详细信息内容结尾)



[//]: # (请勿移除错误详细信息内容结尾)

> [!NOTE]
> 如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。


[//]: # (不修改管理中心元数据内容启动)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13801.20638|版本 2102-5-11|)
[//]: # (|Win32|FRDC|预览体验| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13801.20294|版本2102 年-march-09|)
[//]: # (|Win32|FRDC|预览体验成员| |16.0.13127.21216 | 版本-2008年2月09日|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.21064 | 版本-2008年1月12日|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20910|2008 年 12 月 8 日版|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20760|2008 年 11 月 10 日版|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20638|2008 年 10 月 13 日版|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|2002 年 8 月 11 日版|)
[//]: # (不修改管理中心元数据内容结束)
