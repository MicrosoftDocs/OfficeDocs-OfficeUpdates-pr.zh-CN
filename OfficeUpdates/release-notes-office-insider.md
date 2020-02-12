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
ms.openlocfilehash: 8ffbc6900746ae11caf5b6e7d39a15b0d87a4a20
ms.sourcegitcommit: e9b03ec15c386e14680ed6c6693483bd24b224c4
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/11/2020
ms.locfileid: "41931958"
---
# <a name="release-notes-for-office-insiders"></a>Office 预览体验成员发行说明

本文包含 Windows 桌面版的 Word、Excel、PowerPoint、Outlook、Access 和 Project 的预览体验计划内部版本的发行说明。 每周，我们都会提供精彩集锦，其中包含我们希望你了解的有趣新功能、重要修补程序和所有重要问题。 注意，我们通常会在一段时间内向预览体验成员推出功能（有时甚至包括修补程序）。 这可以让我们确保将功能向更多的受众发布之前，所用功能均可正常使用。 因此，如果你没有看到下面所述的功能，请不要担心，你最终会获取这些功能。  

> [!NOTE]
> - 发行说明每周发布一次，可能是多个版本的编译。
> - 发行说明发布日期可能与实际内部版本发布日期不一致。
> - Office 365 专业增强版现有安装的 Microsoft Teams - 从6月底开始, 将在更新这些安装的 Office 365 专业增强版 (和 Office 365 Business) 现有安装中包含 Microsoft Teams。 将添加 Teams 的日期取决于所使用的更新频道。 有关详细信息, 请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。

[//]: # (请勿移除)

## <a name="version-2002-february-07"></a>版本 2002：2 月 7 日
*版本 2002（内部版本 12527.20040）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在“查询设计器”、“SQL 视图”和“关系”窗口中更高效地工作：** 右键单击表格，以对其进行打开、设计、调整大小和隐藏操作。 在 SQL 视图中搜索和替换文本。 在“关系”窗口中选择多个表。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 此更新修复了使用 ADODB 的问题。 VB 代码中的记录器对象可能会错误地报告错误。

- 此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。

### <a name="excel"></a>Excel

- 解决了将文本分列用于动态数组时 Excel 崩溃的问题。

### <a name="outlook"></a>Outlook

- 解决了在采用月视图的日历中进行滚动时无法显示以前的日历事件的问题。

- 解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到系统崩溃的问题。

### <a name="powerpoint"></a>PowerPoint

- 修复了以下问题：关闭文件后，如果有任何事件处理程序正在运行，PowerPoint 不会立即从演示文稿集合中删除该文件。 因此，由对象模型报告的打开的演示文稿数目不正确，并且系统会阻止关闭 PowerPoint。

- 修复了荧光笔问题：带有黑色荧光笔颜色的白色文本在打印后显示为灰度中的黑色。

### <a name="word"></a>Word

- 更新和滚动浏览目录时，有时可能会在文档上显示灰色区域。

- 修复了共同创作文档时可能不会保留根批注的草稿版本的问题。

- 修复了在批注卡之间来回切换时有时会显示最初所选批注并突出显示所选内容的问题。

- 修复了以下问题：如果编写了批注但未发布内容且用户尝试了保存文件，则使用“浏览”保存文件将不起作用。

- 在启用 SlideTrack 并关闭批注窗格后，按 Ctrl+Alt+M 可能无法打开批注窗格。

- 修复了在表中添加 @提及时可能会生成错误消息“此文档中的某个表格已损坏”的问题。

### <a name="office-suite"></a>Office 套件

- 解决了可能是导致无法正确安装挪威尼诺斯克语 (nn-no) 校对工具程序包的原因的问题。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-january-31"></a>版本 2002：1 月 31 日
*版本 2002（内部版本 12513.20010）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。

- **查询编辑器中的数据分析：** 快速分析列中的数据、确定错误和空值、查看分发直方图等。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="outlook"></a>Outlook

- 修复了以下问题：电子邮件根据保留策略过期时将显示两个标签。 一个标签显示邮件将在一天后过期，另一个标签显示将在两天后过期。

### <a name="word"></a>Word

- 修复了在阅读模式中使用&quot;反转&quot;页面颜色看不到批注提示的问题。

- 修复了在编辑批注、将文本设置为斜体并随后将其发布之后斜体格式丢失的问题。

- 修复了批注上下文菜单中的批注命令（“编辑批注”、“批注答复”、“删除批注”、“解决批注”）不显示的问题。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-january-17"></a>版本 2002：1 月 17 日
*版本 2002（内部版本 12508.20000）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="word"></a>Word

- **提及 和评论通知电子邮件现在包含预览：** 提及的电子邮件通知评论将立即包含评论文本和所引用上下文的预览。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 在某些情况中，辅助功能检查器不会显示形状建议。

### <a name="outlook"></a>Outlook

- 保存在左侧导航窗格“收藏夹”中的文件夹可能间歇消失。

### <a name="powerpoint"></a>PowerPoint

- 修复了在 PowerPoint 墨迹动画中使用时，墨迹可能无法完全呈现或跳过的问题。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-january-10"></a>版本 2001：1 月 10 日
*版本 2001（内部版本 12430.20000）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel
- **将形状另存为图片：** 只需单击几下即可将形状、图标或其他对象另存为图片文件，以便您将其用于其他任何位置。 [了解更多](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a>Outlook
- **在 Windows 中，用户现在可以将 Word/Excel/Outlook 中的对象另存为图片：** 通过 PowerPoint 中已有的功能，用户现在可以将 Word、Excel 和 Outlook 中的对象另存为图片。 对象包括形状、图标、图片等！ 可以通过右键单击菜单访问它。

### <a name="word"></a>Word
- **通过在对象周围绘制形状轻松选择 Word 中的墨迹：**“绘图”选项卡上的套索工具可以帮助你选择使用墨迹绘制的对象。 选择单独的笔划或整个字。 当你拥有大量墨迹并且只想使用其中的一部分时，这就非常方便。 [了解更多](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **将形状另存为图片：** 只需单击几下即可将形状、图标或其他对象另存为图片文件，以便您将其用于其他任何位置。 [了解更多](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="onenote"></a>OneNote
- 页面选项卡可能显示太小，并且以 100% 分辨率紧密排列在一起。

### <a name="word"></a>Word
- 在大量备注中，删除靠近备注列表末尾的备注可能会导致窗格一直滚动至顶部。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-january-03"></a>版本 2001：1 月 3 日
*版本 2001（内部版本 12425.20000）*

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题

### <a name="excel"></a>Excel
- 某些边框线可能无法在 A4 大小的纸张上按预期打印。
- 如果使用 VBA 向工作表上图表对象的页眉/页脚添加图像，则可能导致错误。
- 设置图表坐标轴的格式时，标签之前的间隔限制为 255。
- 解决了尝试刷新 XML 查询时出错（其中数据源的 URL 遭到截断）的问题。
- 工作簿统计信息会报告所有打开的工作簿（包括个人宏工作簿）中的宏计数。

### <a name="outlook"></a>Outlook
- 切换文件夹可能导致邮件列表/邮件预览中“闪现”短暂的空白。 此行为在深色模式下更明显。

### <a name="powerpoint"></a>PowerPoint
- 解决了调用 Shape.Paste 方法会导致粘贴的形状被置于焦点之下的问题。&nbsp;
- 改进了复制粘贴方案：&nbsp;以编程方式复制 PowerPoint 幻灯片中的形状并将其粘贴到循环中的其他幻灯片会失败并出现异常错误。&nbsp;
- 在折叠和展开节标题后，幻灯片的节标题中的动画无法正常呈现。

### <a name="project"></a>Project
- 解决了文本环绕在文本和资源使用情况视图中不起作用的问题。
- 解决了如果某资源有多个成本费率，则分配上的成本值可能不正确的问题。

### <a name="word"></a>Word
- 如果在公式中插入控件（例如文本内容控件），然后保存再打开文件，则会导致“内容不可读”错误。
- 共同创作时，Word 桌面版中可能不会显示使用 Word Online 添加批注的功能。

### <a name="office-suite"></a>Office 套件
- 尝试在只有一个许可证的情况下更改许可证时，不再显示对有效许可证而言错误的过期日期。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2001-december-13"></a>版本 2001：12 月 13 日
*版本 2001（内部版本 12410.20000）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **将电子邮件拖动到你拥有的组：** 通过从收件箱中拖动来移动和复制邮件和对话。 将与所有组成员共享你拖动的消息。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access
- 执行引用链接 ODBC 表并包含 Order By 子句的联合查询会导致 64 位 Access 崩溃。
- 在 Access (O365) 中对联合查询的数据进行汇总可能导致十进制数据被截断。
- ACE 的 COM 接口未公开在 Office 应用程序外部使用。

### <a name="excel"></a>Excel
- 插入 3D 模型（动画或静态）并尝试“另存为图片”不起作用。
- 从 Backstage 启动反馈的快捷键 (Alt+Ctrl + 7/8) 与 AZERTY 键盘 (Alt-Gr + 7/8) 发生冲突。 影响：用户可能无法使用某些字符，例如：'\'。

### <a name="outlook"></a>Outlook
- 解决了导致将电子邮件发送到收件人错误地址的问题。
- 解决了导致 Outlook 错误地允许具有邮箱&quot;读取&quot;权限的用户更改邮件已读/未读状态的问题。
- 产品支持人员无法再现网站上的安全证书吊销。 需要添加日志来帮助找出问题的根本原因。
- 解决了导致用户看到同步失败的问题。

### <a name="powerpoint"></a>PowerPoint
- 插入 3D 模型（动画或静态）并尝试“另存为图片”不起作用。

### <a name="project"></a>Project
- 对于手动计划的子任务，无法在摘要汇总中计算任务工时。
- 尝试保存基于服务器的项目时，从功能区按钮调用的 Project VBA 代码可能不起作用。
- 除非 Project 已在运行，否则从 SharePoint 文档库中打开 Project 文件时将显示错误，并且无法打开该文件。

### <a name="word"></a>Word
- 保存现有文件可能不起作用。
- 在“拼写和语法”编辑器窗口中使用箭头键可能导致间歇性闪烁。
- 解析跟进时，关联的批注可能无法转换为重点批注。
- 插入 3D 模型（动画或静态）并尝试“另存为图片”不起作用。

### <a name="office-suite"></a>Office 套件
- 修复了 Office 更新消息以与预期不同的语言显示的问题。 今后，Office 更新消息将正确匹配 Windows 显示语言。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-december-06"></a>版本 1912：12 月 6日
*版本 1912（内部版本 12325.20012）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **高级组电子邮件设置：** 此功能可帮助组用户自定义要在收件箱中接收/关注的电子邮件或事件。

- **组命名策略：** 组命名策略使 IT 管理员能够标准化管理组织中由用户创建的组名。 管理员可以要求在创建组时向名称添加特定前缀和后缀，并阻止使用指定的字词。 这有助于尽可能在组名中减少使用不适宜的字词，以及有助于IT部门在目录中管理组的显示方式。 命名策略还可有助于组织根据部门部署团队网站，以进行分类。

### <a name="office-suite"></a>Office 套件

- **制表符窗格：** 现在，可以使用应用程序右侧的选项卡 UI 在多个窗格之间进行切换。 UI 将只在当打开2个以上的窗格时才会可见。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel
- 用户在使用部分非英文字符集保存更改时可能会出错。
- 访问隐藏命名区域时，用户可能会遇到错误。
- 禁用 4k 分辨率硬件图形加速可能会延迟单元格的渲染。
- 清除覆盖单元格边界的长公式，可能仍会跨单元格边界显示。
- 解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。
- 页边距下拉菜单可能无法正确呈现。

### <a name="onenote"></a>OneNote
- OneNote 可能无法通过‘会议记录’ Outlook 加载项打开。

### <a name="outlook"></a>Outlook
- 保留策略标签可能会在括号中显示保留时间段。
- 日语语言包的联系人卡片中可能出现空格。
- 内联插入 Outlook 电子邮件正文中的图像，有时尺寸会发生变化。

### <a name="powerpoint"></a>PowerPoint
- 如果用户在云端文件的幻灯片中有两个（或更多）不同的视频，视频图像可以正确渲染，但当用户单击各视频进行播放时，视频内容相同。
- 在某些情况中，无法使用触摸设备滚动。
- 页边距下拉菜单可能无法正确呈现。
- 一个 Office 应用程序至其它应用程序的 Safelink 可能无法启动关联的应用程序。

### <a name="project"></a>项目
- 使用 "比较项目" 功能时，项目可能会崩溃。
- 如果处于深色模式，转至含有过度分配资源的任务的任务检查器面板时，将无法读取表格。
- 无分配任务的工作量取舍为1天。

### <a name="word"></a>Word
- 在某些情况下，合并邮件后可能无法保存文件。
- 构建基块管理器可能显示无效的警报：&quot;你已更改样式、构建基块&quot;。
- 使用粘贴/复制时，批注窗格有时会重新载入。
- 有时批注无法采用正确顺序粘贴。
- 应用含有多级列表及自定义样式的模板，可能无法在指定条件下保留样式。
- 重新调整分屏边框大小可能产生附加的分屏。
- 页边距下拉菜单可能无法正确呈现。
- 批注卡中的用户可能显示 JSON。
- 一个 Office 应用程序至其它应用程序的 Safelink 可能无法启动关联的应用程序。

### <a name="office-suite"></a>Office 套件
- 对于基于日语的产品，账户用户的名字、姓氏可能按照错误的顺序显示。
- 悬停鼠标指针在批注上方可能会在批注周围显示文本框轮廓。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-november-15"></a>版本 1912：11 月 15 日
*版本 1912（内部版本 12307.20000）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="insights-services"></a>见解服务
- **Excel 中的“创意”中的自然语言查询：** Excel 创意的针对数据进行自然语言提问的新功能。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel
- 某些本地化版本的“文本分列”功能可能会失败。
- 编辑单元格中的动态数组公式可能会导致文本在单元格边界之外对齐。

### <a name="outlook"></a>Outlook
- 添加了通过组策略强制执行 S/MIME 配置的能力。
- 嵌入的图像可能看起来比预期的要小。

### <a name="powerpoint"></a>PowerPoint
- 将焦点从文本移动后，光标可能会消失。

### <a name="project"></a>Project
- 用户可能遇到有关许可方面的错误。
- 日期选取器中的“今天”按钮有时可能会设置错误的日期。

### <a name="word"></a>Word
- 右键单击有时无法选择整个单词。
- 在转换为建议的格式后，光标可能在对象中保持活动状态。
- 在某些情况下，邮件中的图像可能无法正确缩放。
- 某些主题可能会导致难以确定选择了哪个批注。
- 现在，选择批注提示会在其在窗格切换器中隐藏时显示新式批注窗格。

### <a name="office-suite"></a>Office 套件
- 回复批注可能会导致文本框垂直展开到窗格边缘以外。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1912-november-08"></a>版本 1912：11 月 8 日
*版本 1912（内部版本 12231.20000）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="user-lifecycle"></a>用户生命周期
- **体验改进 AFO 激活：** 在激活与新电脑捆绑的 Office 时，客户看到的屏幕更新。

### <a name="word"></a>Word
- **Word 中新的和改进的在线视频体验：** 新的和更安全的在线视频体验，帮助你在 Word 中插入新视频和播放现有视频。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="outlook"></a>Outlook
- 涉及跨文件夹内容的间歇性崩溃。

### <a name="office-suite"></a>Office 套件
- 将图表从 Excel 粘贴到 PowerPoint 后，可减小图表的大小。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1911-november-01"></a>版本 1911：11 月 1 日
*版本 1911（内部版本 12228.20020）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel
- **将上下文和 SVG 对象一起显示！：** 现在，你可以在 Office 中转换这些对象时保留地图、图表和其他 SVG 向量中的文本。

- **选择 Surface 触控笔时查看触控笔选项：** 首次在 Word、Excel 或 PowerPoint 中选取 Surface 触控笔时，将激活“绘图”选项卡，以轻松选择笔颜色。

### <a name="powerpoint"></a>PowerPoint
- **将上下文和 SVG 对象一起显示！：** 现在，你可以在 Office 中转换这些对象时保留地图、图表和其他 SVG 向量中的文本。

- **选择 Surface 触控笔时查看触控笔选项：** 首次在 Word、Excel 或 PowerPoint 中选取 Surface 触控笔时，将激活“绘图”选项卡，以轻松选择笔颜色。

### <a name="visio"></a>Visio
- **在 Excel 中制作精美的 Visio 图表：** 在 Excel 中快速轻松地将数据可视化为精美的 Visio 图表。 [了解详细信息](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)。

### <a name="word"></a>Word
- **选择 Surface 触控笔时查看触控笔选项：** 首次在 Word、Excel 或 PowerPoint 中选取 Surface 触控笔时，将激活“绘图”选项卡，以轻松选择笔颜色。

- **共同创作改进：** 通过让其他人以更接近实时的方式接收内容更改，改进了共同创作体验。

- **其他人可以快速查看你所做的更改: **共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel
- 解决了在编辑不受信任的网络共享中的受保护文件时 Excel 可能发生崩溃的问题。
- 解决了以下问题：如果删除了包含引用其他工作表上数据的迷你图的工作表，则重新打开时，该文件会被标识为损坏。
- 解决了以下问题：将报表筛选器与查询的数据透视表其余部分一起转换为 SQL 表格式服务器时，可能会得到错误的结果。
- 同时使用“讲述人”和“放大镜”可能会导致崩溃。
- 同时使用“讲述人”和“放大镜”可能会导致崩溃。

### <a name="outlook"></a>Outlook
- 转发的电子邮件可能缺少嵌入图像。
- 对于可用会议室，会议室查找工具可能显示“&quot;无&quot;”。
- 用户可能无法创建具有严格租户限制的 Outlook 配置文件。

### <a name="powerpoint"></a>PowerPoint
- 同时使用“讲述人”和“放大镜”可能会导致崩溃。

### <a name="project"></a>Project
- 用户无法将任务标记为“已完成”，而只能将其设置为 99%。
- 无法通过调配解决过度分配问题。

### <a name="word"></a>Word
- 同时使用“讲述人”和“放大镜”可能会导致崩溃。
- 打开旧版文档后转到“信息”选项卡会导致崩溃。
- 校对建议未显示在上下文菜单中。
- 内容策略被错误地应用到了批注。
- 在深色模式中看不到用深色文本编写的旧式批注。
- 使用韩语/英语自动更正时可能出现不正确的字符。
- 当较高的策略标签具有优先级时可能应用较低的策略标签。
- Outlook 邮件中的 cid: images 链接&nbsp;现在可以在请求时成功断开。
- 同时使用“讲述人”和“放大镜”可能会导致崩溃。
- 从导航窗格中搜索可能失败。

### <a name="office-suite"></a>Office 套件
- 预览或幻灯片放映中可能不会显示某些绘图。
- 竖排文本框中有些片假名字符可能无法正确显示。
- 尝试将文件保存到断开的网络共享可能会导致崩溃。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1911-october-25"></a>版本 1911：10 月 25 日
*版本 1911（内部版本 12215.20006）*

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="visio"></a>Visio

- **在 Excel 中制作精美的 Visio 图表：** 在 Excel 中快速轻松地将数据可视化为精美的 Visio 图表。 [了解更多](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **共同创作改进：** 通过让其他人以更接近实时的方式接收内容更改，改进了共同创作体验。

- **其他人可以快速查看你所做的更改: **共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- <div><span>记录计数可能不正确</span></div>


### <a name="excel"></a>Excel

- <div><span>显著提高了使用合并单元格删除列的性能</span></div>


- <div><span>可阻止用户以 Office 365 Excel 工作簿格式保存</span></div>


- <div><span>无法正确呈现复选框</span></div>


- <div><span>无法保存对图表大小所做的更改</span></div>


- <div><span>某些 VBA 函数将在新的图表类型上返回错误</span></div>


- <div><span>“选择数据源”对话框对于某些字段不区分大小写</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>无法保存对图表大小所做的更改</span></div>


### <a name="publisher"></a>Publisher

- <div><span>形状可能出现在图形边框之外</span></div>


### <a name="word"></a>Word

- <div><span>形状可能出现在图形边框之外</span></div>


- <div><span>突出显示文本可能很困难</span></div>


- <div><span>可以防止用户导航到编辑器中的单个项目</span></div>


- <div><span>可能未突出显示语法或拼写错误</span></div>


- <div><span>无法保存对图表大小所做的更改</span></div>


- <div><span>将格式应用于 @ 提及后，可能会阻止联系卡打开</span></div>


- <div><span>解决了用户可能无法保存 Word、Excel 和 PowerPoint 文档的问题。&nbsp; 此问题会影响用户创建新文件并在单击“保存”图标或按 Ctrl + S 后弹出 &quot;另存为模型对话框&quot; 选项。</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>在 Windows 7 上使用形状时出现性能问题</span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1911-october-18"></a>版本 1911：10 月 18 日
*版本 1911（内部版本 12209.20010）*


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **将易访问邮件发送给最需要的人员：** Outlook 将显示邮件提示，以帮助确保在向喜欢易访问内容的用户发送邮件时可访问你的内容

### <a name="powerpoint"></a>PowerPoint

- **全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。

### <a name="office-suite"></a>Office 套件

- **“需要注意的文件”体验将替换上载中心：**“需要注意的文件”体验将替换上载中心，该体验将显示在 Office 应用程序的“文件”>“打开”中。 与上载中心相比，这种新体验更加现代、集成度更高并且干扰性更低。


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div><span>解决了使用自动调整功能调整行高时复选框控件可能缩小的问题</span></div>


- <div><span>解决了在滚动后选择单元格时可能导致选择错误单元格的问题</span></div>


### <a name="outlook"></a>Outlook

- <div><span>发现了在对带有数字签名附件的电子邮件进行签名时可能导致数字签名破坏的问题</span></div>


- <div><span>发现了将长文件名拖放到邮件正文后被截断的问题</span></div>


- <div>发现了将功能区设置为自动隐藏时搜索框可能消失的问题</div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>发现了幻灯片预览的纵横比未正确锁定/解锁的问题</span></div>

### <a name="project"></a>项目

- <div>发现了在执行更新任务时输入的备注可能无法保留的问题<br></div>


- <div>发现了用户可以锁定文件但错误消息中未显示用户名的问题</div>


- <div><span>发现了用户在打开只读项目时可能会收到几则消息的问题</span></div>


### <a name="word"></a>Word

- <div><span>在使用屏幕阅读器查看批注时发现了一个问题</span></div>


- <div><span>发现了某些评论被误认为是拼写或语法评论的问题</span></div>


- <div><span>发现了新批注对话框有时无法获取焦点的问题</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>我们修复了错误消息&quot;正在进行其他安装&quot;阻止升级的问题</span></div>

- <div><span>发现了可能影响从本地资源同步到云资源的的问题</span></div>

- <div><span>发现了欢迎消息中包含无效链接的问题</span></div>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-october-11"></a>版本 1910：10 月 11 日
*版本 1910（内部版本 12130.20112）*


[//]: # (请勿移除功能详细信息内容开头)
[//]: # (请勿移除功能详细信息内容结尾)
[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div>解决了将文件作为来自 OneDrive 的对象插入时出现的问题</div>


- <div>解决了无法将超链接格式正确应用到某些内容的问题</div>


- <div>解决了包含结构化绝对引用的公式可能无法正确调整的问题</div>


- <div>解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起</div>


- <div>解决了一个问题，当从 Excel 复制内容粘贴到其他 Office 应用程序中时，可能会显示不正确</div>


- <div>修复了使用图表模板插入图表时预览中所用颜色的问题</div>


### <a name="powerpoint"></a>PowerPoint

- <div>发现了 ARC 设备在 AirSpace WinComp 下运行时可能会断开连接的问题</div>


### <a name="word"></a>Word

- <div>解决了将文件作为来自 OneDrive 的对象插入时出现的问题</div>


- <div>改进了恢复步骤以<span>修复导致图形内容从电子邮件线程中被删除的问题。&nbsp;</span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-october-04"></a>版本 1910：10 月 4 日
*版本 1910（内部版本 12126.20000）*


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。 [了解更多](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div><span>我们修复了打印预览中的打印区域不正确的问题</span></div>


- <div><span>我们修复了在共同创作会话期间可能阻止刷新数据透视表的问题</span></div>


### <a name="access"></a>Access

- <div>我们修复了一个问题，即用户在使用共享数据库时可能会收到“&quot;不一致状态&quot;”错误。</div>


### <a name="outlook"></a>Outlook

- <div><span>我们修复了可能导致邮件文件夹重复的问题</span></div>


- <div><span>我们修复了当尝试发送 S/MIME 加密电子邮件时可能导致错误消息的问题</span></div>


- <div><span>我们修复了一个问题，即当用户从 Skype 收到“错过的对话”消息时，该问题有时可能会导致崩溃</span></div>


- <div><span>我们修复了可能导致内存泄漏的问题</span></div>


- <div><span>我们修复了当另存为草稿时可能导致发件人的姓名发生更改的问题</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span></span></div>我们修复了一个问题，即将文本粘贴到幻灯片母版和幻灯片版式上的页眉/页脚/幻灯片编号占位符后，TextRanges 出现损坏


- <div><span></span></div>我们修复了在粘贴带有超链接的文本时阻止创建超链接的问题


- <div>我们修复了阻止统计信息正常工作的问题</div>


### <a name="word"></a>Word

- <div><span>我们修复了未提交字体颜色的问题</span></div>


### <a name="office-suite"></a>Office 套件

- <div>我们修复了禁用该功能后可能提供版本历史记录的问题</div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-27"></a>版本 1910：9 月 27 日
*版本 1910（内部版本 12119.20000）*


[//]: # (请勿移除功能详细信息内容开头)
[//]: # (请勿移除功能详细信息内容结尾)
[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div><span>我们修复了在更改系列集合时可能导致散点图和折线图无法正确呈现的问题</span></div>


### <a name="outlook"></a>Outlook

- <div><span>我们修复了与共享日历文件夹进行交互时可能报告权限错误的问题</span></div>


- <div><span>我们修复了可能阻止用户向日历添加附件的问题</span></div>


- <div><span>我们修复了导致在答复数字签名邮件时显示错误消息的问题</span></div>


### <a name="word"></a>Word

- <div><span>我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>我们修复了中粗体文本具有错误样式的问题</span></div>


- <div><span>我们修复了一个问题，即关闭等待上传的文件时，用户可能收到错误消息</span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-20"></a>版本 1910：9 月 20 日
*版本 1910（内部版本 12112.20000）*


[//]: # (请勿移除功能详细信息内容开头)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div><span>我们修复了 Excel 有时可能在启动时挂起的问题</span></div>

### <a name="outlook"></a>Outlook

- <div><span>我们显著改善了当有大量会议室可用时进行房间选择的性能</span></div>


- <div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我们修复了以下问题：在迁移到 Office 365 中的新式验证时，在 Outlook 中使用多个邮箱的客户可能无法进行邮箱同步。</span><br></div>


- <div><span>我们修复了签名标签中某些字符在下拉菜单中不会显示的问题</span></div>


### <a name="project"></a>Project

- <div><span>我们修复了将企业资源替换为本地资源时可能导致崩溃的问题</span></div>


### <a name="word"></a>Word

- <div><span>我们修复了可能导致同步滚动操作在草稿视图中无法正常工作的问题</span></div>


- <div>我们修复了可能导致在首次保存文档后无法正常显示工具提示的问题</div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-13"></a>版本 1910：9 月 13 日
*版本 1910（内部版本 12105.20000）*


[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div><span>已修复阻止用户在某些受保护的工作表中粘贴超链接的问题</span></div>


### <a name="outlook"></a>Outlook

- <div><span>已修复问题：UI 在紧凑视图中卡顿</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>已修复问题：用户打印到 PDF 时发生错误</span></div>


### <a name="project"></a>Project

- <div><span>已修复问题：<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">在启用了工作保护的情况下，对摘要任务的工作值进行更改会导致崩溃</span></span></div>


- <font size=2 style="background-color:rgb(255, 255, 255);">已修复妨碍与企业日历同步事件的功能的问题</font>


### <a name="office-suite"></a>Office 套件

- <div><span>我们已修复导致放弃文件的本地版本的重复警告的问题</span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1910-september-06"></a>版本 1910：9 月 6 日
*版本 1910（内部版本 12030.20004）*


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **准备、设置、绘图：** 抓住 Surface 触控笔时，即可绘图。 [了解更多](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a>PowerPoint

- **准备、设置、绘图：** 抓住 Surface 触控笔时，即可绘图。 [了解详细信息](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **准备、设置、绘图：** 抓住 Surface 触控笔时，即可绘图。 [了解详细信息](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div><span>我们修复了一个问题，它可能导致功能区中的字体名称与正在使用的字体不同</span></div>


### <a name="outlook"></a>Outlook

- <div><span>我们修复了一个问题，即在 Internet Explorer 中为受限站点禁用保护模式时，Outlook 可能会导致资源消耗不当</span></div>


- <div><span>我们修复了一个问题，即当从 ANSI 源粘贴文本时，有时会导致出现 Unicode 字符</span></div>


- <div><span>修复了某些用户在“小组日程”视图中错误地显示为“离线”的问题</span></div>


### <a name="word"></a>Word

- <div><span>我们修复了表格格式可能丢失的问题</span></div>


- <div><span>我们修复了可能断开 CTRL+V 键盘快捷方式的问题</span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1909-august-30"></a>版本 1909：8 月 30 日
*版本 1909（内部版本 12026.20000）*


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新

### <a name="access"></a>Access

- **快速查找链接的表格：** 新的“搜索”框使查找链接的表格成为一项轻松的乐事。

### <a name="powerpoint"></a>PowerPoint

- **将插图另存为 SVG**：将图表、形状或其他插图另存为可缩放矢量图形，这样做可以调整其大小，而不会降低图像质量。 [了解详细信息](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a>非安全更新
### <a name="excel"></a>Excel

- <div><span>我们修复了&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">敏感度</span>的快捷键提示与&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">另一个快捷键提示相冲突的问题。</span></span></div>

- <div><span>我们修复了在处理共享工作簿和尝试保存时发生的问题。</span></div>

- <div><span>我们修复了一个问题，即 Excel 仅列出位于“\Excel\Add-in Manager”注册表值中的前 16 个加载项。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></div>


- <div><span>我们修复了 Frequency 函数返回错误结果的问题。</span></div>


- <div><span>我们显著提高了按颜色筛选的性能。</span></div>


- <div><span>我们修复了 Surface 用户遇到的一个问题，即移动鼠标可能解释为鼠标单击事件。</span></div>


- <div><span>我们修复了阻止在“查找/替换”对话框中进行键盘导航的问题</span></div>


- <div><span>我们修复了某些字体名称无法正确显示的问题</span></div>


- <div><span>我们修复了阻止 CSV 显示为受支持的文件类型的问题</span></div>


### <a name="access"></a>Access

- <div>我们修复了一个问题，即用户在使用共享数据库时可能会收到“&quot;不一致状态&quot;”错误。</div>


- <div><span>我们修复了可能导致在错误时间显示日期选取器的问题</span></div>


### <a name="outlook"></a>Outlook

- <div><span>们修复了阻止向某些 POP3 用户显示 HTML 内容的问题</span></div>


- <div><span>我们修复了一个问题，即在其不可用的环境中工作时，将从联系人卡片的溢出菜单中删除不起作用的“规划器”链接。</span></div>

### <a name="onenote"></a>OneNote

- <div><span>我们修复了 &nbsp;OneNote 后台同步有时会成为焦点的问题。</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>我们修复了会影响 3D 转盘旋转方向的问题。</span></div>

- <div><span>我们修复了如果某些超链接中包含特殊字符，则会阻止其打开的问题。</span></div>

- <div><span>我们修复了导致多个评论窗格同时打开的问题。</span></div>

### <a name="project"></a>Project

- <div><span>我们修复了在打印工作组规划器视图后有时会导致崩溃的问题。</span></div>

### <a name="word"></a>Word

- <div>我们<span>修复了垂直文本框中的多字节字符在阅读视图中重叠显示的问题。<br></span></div>

- <div><span>我们&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">修复了以下问题：当用户在加载项向导中执行操作时，找不到日语明信片和贺卡相关加载项资源。</span></span></div>

- <div><span>我们修复了一个问题，即在受保护视图中，它可能导致标题栏用户界面出现问题</span></div>

### <a name="office-suite"></a>Office 套件

- <div><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">我们修复了在包含普通形状和连接线形状的选择中更改形状时出现的文件损坏问题。</span></span></div>

- <div><span>我们修复了<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">从多个外部显示器使用停靠/取消停靠时导致应用程序出现问题的问题。</span></span></div>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="august-23-2019br"></a>**2019 年 8 月 23 日**<br/>
版本 1909（内部版本 12015.20004）<br/>



## <a name="non-security-updates"></a>与安全无关的更新：

### <a name="excel"></a>Excel

- <div><span>显著提高了使用合并单元格删除列的性能</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>修复了在浏览器中查看时某些 Unicode 字符无法显示的问题</span></div>


### <a name="outlook"></a>Outlook

- <div><span>修复了使文件无法保存到 WebDAV 位置的问题</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>修复了单击一个评论却选中的是另一个评论的问题</span></div>





## <a name="august-16-2019br"></a>**2019 年 8 月 16 日**<br/>
版本 1909（内部版本 12013.20000）<br/>

### <a name="powerpoint-feature-updates"></a>PowerPoint 功能更新：

- **打印讲义上的幻灯片编号：** 幻灯片编号将会自动包括在讲义上。 打开或是关闭它们，全都取决于你。




## <a name="non-security-updates"></a>与安全无关的更新：

### <a name="excel"></a>Excel

- <div><span>解决了可能导致启用“自动保存”功能的问题</span></div>


- <div>修复了未能准确测量单元格高度的问题</div>


### <a name="office-suite"></a>Office 套件

- <div><span>解决了一项问题，从而显著提高了“评论”功能的性能</span></div>


- <div><span>解决了在搜索时使用箭头键可能会导致崩溃的问题</span></div>


- <div><span>解决了如果 @ 符号位于某些字符之后可能会阻止 @ 提及的问题</span></div>


- <div><span>解决了删除 @ 提及时，有时会出现崩溃的问题</span></div>


- <div><span>解决了表情符号无法在评论卡片中正确显示的问题</span></div>


- <div><span>解决了活动剪贴板​​有时会导致崩溃的问题</span></div>


- <div><span>修复了致使“快速访问工具栏”按钮停止工作的问题</span></div>


- <div><span>解决了阻止“文档格式预览”切换到后台操作的问题</span></div>

### <a name="onenote"></a>OneNote

- 解决了在 Office 主题设置为“空白”时分区名称在分区下拉列表中显示空白的问题。

### <a name="outlook"></a>Outlook

- <div><span>解决了发送事件时可能导致 Outlook 反复获得和失去焦点的问题</span></div>


- <div><span>解决了阻止“将答复投递到文件夹”快捷方式正常工作的问题</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>解决了协作时“受保护的视图”有时出现故障的问题</span></div>


- <div><span>解决了可能阻止评论窗格中的任务正确显示的问题</span></div>


- <div><span>解决了插入新的幻灯片时可能会发生崩溃的问题</span></div>


### <a name="user-lifecycle"></a>用户生命周期

- <div><span>解决了有时导致订阅功能不可见的问题</span></div>


### <a name="word"></a>Word

- <div><span>解决了在超链接包含某些字符时超链接可能遭到损坏的问题</span></div>


- <div><span>解决了查看图像的注释时图像尺寸可能不正确的问题</span></div>


- <div><span>修复了“项目符号列表”下拉菜单有时会崩溃的问题</span></div>





## <a name="august-09-2019br"></a>**2019 年 8 月 9 日**<br/>
版本 1909（内部版本 12001.20000）<br/>

### <a name="excel-feature-updates"></a>Excel 功能更新：

- **协作更简单：** 共同创作改进意味着使用条件格式、单元格样式等时，所做的更改将与协作者无缝合并。


- **搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。 选择时，“插入”按钮会告诉你已挑选的数目。


### <a name="office-suite-feature-updates"></a>Office 套件功能更新：

- **新的 Office 应用图标：** 重新设计应用图标，以反映出 Office 简单、强大而智能的体验。


### <a name="outlook-feature-updates"></a>Outlook 功能更新：

- **针对攻击的高级防护：** 通过 Office 365 高级威胁防护, 可通过电子邮件主题中的超链接、附加邮件、签名邮件、网络路径等的方式抵御攻击。


- **搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。 选择时，“插入”按钮会告诉你已挑选的数目。


### <a name="powerpoint-feature-updates"></a>PowerPoint 功能更新：

- **搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。 选择时，“插入”按钮会告诉你已挑选的数目。


### <a name="word-feature-updates"></a>Word 功能更新：

- **其他人可以快速查看你所做的更改: **共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。


- **搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。 选择时，“插入”按钮会告诉你已挑选的数目。




## <a name="non-security-updates"></a>非安全更新：

### <a name="outlook"></a>Outlook

- <div><span>我们修复了导致会议收件人在取消会议后收到两个通知的问题</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>我们修复了用户为“形状”和“图标”选择 "无轮廓" 或 "无填充" 时，可能会导致崩溃的问题</span></div>





## <a name="august-02-2019br"></a>**2019 年 8 月 2 日**<br/>
版本 1908（内部版本 11929.20002）<br/>

### <a name="excel-feature-updates"></a>Excel 功能更新：

- **将文件转换为改进辅助功能: **将文件升级到新式格式，使其更易于所有人访问。


- **向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。


### <a name="outlook-feature-updates"></a>Outlook 功能更新：

- **向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。


### <a name="powerpoint-feature-updates"></a>PowerPoint 功能更新：

- **将文件转换为改进辅助功能: **将文件升级到新式格式，使其更易于所有人访问。


- **向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。


### <a name="word-feature-updates"></a>Word 功能更新：

- **将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。


- **换一种说法：** 想要用另一种方法表达，重写功能帮你大忙。 重写功能为你完善语言提供了替代方案。


- **向文档应用敏感度标签：** 向文档和邮件应用敏感度标签，使其符合组织的信息保护策略。




## <a name="non-security-updates"></a>与安全无关的更新：

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="excel"></a>Excel

- <div><span>我们修复了打印到 PDF 时似乎应用了&quot;重复所有标签&quot;的问题</span></div>

### <a name="office-suite"></a>Office 套件

- <div><span>我们修复了可能会阻止用户在桌面上打开文档的问题</span></div>

- <div><span>我们修复了错误消息&quot;正在进行其他安装&quot;阻止升级的问题</span></div>

- <div><span>我们修复了安装安全更新时用户可能会看到错误消息的问题</span></div>

- <div><span>我们解决了可能会导致光标消失的问题</span></div>

- <div><span>我们修复了用户可能默认使用“绘图”选项卡而不是“开始”选项卡的问题</span></div>

- <div><span>我们修复了大型树视图可能会导致崩溃的问题</span></div>

### <a name="outlook"></a>Outlook

- <div></div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我们解决了可能会导致不断提示输入密码的问题</span>

- <div><span>我们修复了可能会妨碍电子邮件地址被正确查询的问题</span></div>

- <div><span>我们修复了可能会阻止用户打开旧版 Outlook 所创建的日历项目的问题</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>我们修复了可能阻止某些动画启动的问题</span></div>

### <a name="project"></a>项目
- 各种性能和稳定性修复

### <a name="word"></a>Word

- <div><span>我们解决了批注回复显示顺序错误的问题</span></div>

- <div><span>我们解决了在某些情况下, 显示的是提示, 而不是批注的问题</span></div>

- <div><span>我们解决了当用户尝试添加新的批注时，修订窗格可能会显示的问题</span></div>

- <div><span>我们解决了可能会阻止显示“撤消”下拉列表的问题</span></div>

- <div><span>我们修复了有时可能会阻止添加批注的问题</span></div>


## <a name="july-26-2019"></a>2019 年 7 月 26 日
版本 1908（内部版本 11916.20000）

## <a name="whats-new"></a>新增功能：

### <a name="word-excel-powerpoint"></a>Word、Excel、PowerPoint

#### <a name="create-more-accessible-pdfs"></a>创建更易于访问的 PDF

创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>全部

- 我们修复了 Office 的文件类型关联和图标有时可能会在 Office 更新后中断的问题

### <a name="word"></a>Word 
- 各种性能和稳定性修复

### <a name="excel"></a>Excel
- 我们修复了移动图表有时会导致崩溃的问题
- 我们修复了在更改图表类型后，从图表对象中获取工作簿对象有时会导致错误的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 我们修复了在简化功能区中，禁用的控件有时不能在功能区中呈灰色显示的问题

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="july-19-2019"></a>2019 年 7 月 19 日
版本 1908（内部版本 11911.20000）

## <a name="whats-new"></a>最近更新：

### <a name="word"></a>Word

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a>了解在 Word Online 中阅读时所遇到的首字母缩略词的含义

当你遇到首字母缩略词时，我们会尝试使用组织内的数据来定义它。


## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们修复了缺少 BookMarkEnd 标记的问题。
- 我们修复了在用户输入特殊字符时字体选择可能发生改变的问题
- 我们修复了有时导致对新评论卡进行空白回复的问题
- 我们修复了可能导致共享电子邮件时格式设置丢失的问题

### <a name="excel"></a>Excel
- 我们修复了包含大区域的数组有时可能导致崩溃的问题
- 我们显著提高了从已筛选区域复制数据的性能
- 我们修复了一个问题，即如果文件名包含特殊字符，则会阻止打开某些文件

### <a name="powerpoint"></a>PowerPoint
- 我们修复了一个问题，即默认情况下未为 PowerPoint 中新创建的分区选择分区名称。
- 我们修复了当使用 4:3 显示时可能导致 UI 难以使用的问题

### <a name="outlook"></a>Outlook
- 我们修复了可能阻止列出可用房间的问题
- 我们修复了阻止某些 POP3 用户使用 HTML 格式设置的问题

### <a name="access"></a>访问
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="july-12-2019"></a>2019 年 7 月 12 日
版本 1907（内部版本 11901.20038）

## <a name="whats-new"></a>最近更新：

### <a name="powerpoint"></a>PowerPoint
 
#### <a name="use-ink-replay-in-your-presentations"></a>在演示文稿中使用墨迹重播
 
在 PowerPoint 中应用墨迹的重播动画，在演示文稿中表达和传达更多信息。 

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 各种性能和稳定性修复

### <a name="excel"></a>Excel
- 各种性能和稳定性修复

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 各种性能和稳定性修复

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="july-5-2019"></a>2019 年 7 月 5 日
版本 1907（内部版本 11901.20018）

## <a name="whats-new"></a>最近更新：

### <a name="word-excel-powerpoint"></a>Word、Excel、PowerPoint

#### <a name="sketchy-shapes"></a>粗略形状！

正在起草演示文稿？ 你可以应用粗略样式来表明自己仍在进行此工作。 因此，无需转换成自由形式的手绘形状，即可为对象提供个性化风格。

### <a name="excel"></a>Excel

- **更快的文件共享**：直接从最近使用的文件列表中共享文档，而无需打开文件。
### <a name="powerpoint"></a>PowerPoint

- **“在讲义中打印幻灯片编号”设置已移至打印菜单，便于访问：** 选择讲义布局时，在“打印”>“打印布局”下拉菜单中选择它。 这也使得可以根据演示文稿轻松切换设置。 [了解更多](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。

### <a name="word"></a>Word

- **更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>全部
- 显著提高了功能区快捷键提示的性能
- 我们修复了阻止“查看即将推出的内容”对话框正确显示的问题
- 我们修复了可能导致“共同创作图库”浮出控件中的照片未对齐问题

### <a name="word"></a>Word 
- 我们修复了有时可能会阻止添加新批注的问题
- 我们修复了表有时可能导致崩溃的问题
- 我们修复了可能会在邮件合并结尾处添加无效数据的问题
- 我们修复了可能导致某些 LaTeX 公式错误呈现的问题

### <a name="excel"></a>Excel
- 我们修复了更改图表类型有时会导致运行时异常的问题
- 我们修复了在打开多个窗口时可能会显示错误功能区的问题
- 我们修复了在宏打开工作簿的第二个实例时可能会导致错误的问题
- 我们修复了在打开或创建工作簿或者在工作簿之间切换时可能导致崩溃的问题
- 我们修复了阻止用户打开通过 Teams 中的 Word 创建的 PDF 的问题

### <a name="powerpoint"></a>PowerPoint
- 我们修复了将图表导出到 pdf 时可能降低图表质量的问题
- 我们修复了阻止显示工具提示（用于指示与中心之间的距离）的问题

### <a name="outlook"></a>Outlook
- 我们修复了有时可能会阻止显示“磁盘已满”错误的问题
- 我们修复了在更新会议请求时可能会导致附件出现重复的问题

### <a name="access"></a>Access
- 我们修复了阻止某些查询返回大型整数值的问题
- 我们修复了可能使 SQL 文本框不可编辑的问题
- 我们修复了难以在一些高 DPI 显示器上查看工具提示的问题

### <a name="project"></a>Project
- 我们修复了可能导致标志值在新任务中不可编辑的问题
- 我们修复了可能导致状态更新会错误地设置工作分配和任务的实际开始日期的问题
- 我们修复了可能会导致某些资源错误地显示为过度分配的问题
- 我们修复了当添加 Lag 时、小数点分隔符为逗号时以及连接到服务器时 TaskDependencies Add 方法可能失败的问题
- 我们修复了通过 CSOM 更新本地自定义字段查找表值可能会导致 PCS 崩溃的问题
- 我们修复了总工时值包含小数时可能显示不正确的问题

</BR></BR>

## <a name="june-28-2019"></a>2019 年 6 月 28 日
版本 1907（内部版本 11819.20002）

## <a name="whats-new"></a>最近更新：

### <a name="excel"></a>Excel

- **使用 Power Query 增强功能快速编码：** 使用自动完成和语法着色快速完成代码编写。 也可以轻松发现函数、列和参数。

- **在类似列上连接表：** 在比较用于合并表的列时，获取和转换 (Power Query) 现在具有近似文本匹配逻辑（也称为模糊匹配）。

### <a name="word"></a>Word

- **合著改进：** 提高了合著时的可靠性。
 
### <a name="word-excel-powerpoint-and-visio"></a>Word、Excel、PowerPoint 和 Visio

#### <a name="recommended-documents"></a>建议的文档

查找为你推荐的相关活动的文档。

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们修复了可能阻止打开某些 .DOC 文件的问题
- 我们修复了可能阻止正确加载批注的问题

### <a name="excel"></a>Excel
- 我们改进了 Power 查询的性能

### <a name="powerpoint"></a>PowerPoint
- 我们修复了与在 Surface 设备上使用触控笔相关的问题，这可能会导致屏幕闪烁

### <a name="outlook"></a>Outlook
- 我们修复了一个问题，该问题可能会在转换为会议时更改约会的忙/闲状态
- 我们修复了一个问题，即当使用临时模板保护电子邮件时，将显示错误的模板和说明

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="june-21-2019"></a>2019 年 6 月 21 日
版本 1907（生成号 11815.20002）

## <a name="whats-new"></a>新变化：

### <a name="outlook"></a>Outlook

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a>Outlook Desktop 中黑色主题的深色模式

在深色模式下，使用黑色主题的用户现在还可以在阅读电子邮件时看到有深色背景的阅读窗格，并在撰写电子邮件时看到有深色背景的撰写窗格。 阅读窗格和功能区上有“太阳/月亮”切换，以防用户想要改用浅色背景来预览邮件外观。

#### <a name="getting-started"></a>开始使用：

1. 黑色主题和深色模式默认处于启用状态。
2. 用户可以使用阅读窗格和功能区上的“月亮/太阳”切换，在浅色模式下预览邮件外观

#### <a name="scenarios-to-try"></a>可尝试的方案

1. 在深色模式下阅读电子邮件。 如果你无法阅读某些内容，请使用“阅读窗格”中的太阳切换按钮切换为浅色背景。 
2. 在深色模式下撰写电子邮件。 使用功能区中的太阳切换按钮，在浅色背景下预览邮件的显示效果。 

如果遇到任何无法正常呈现的电子邮件，请将它们作为附件发送到 OutlookDarkModeFail@service.microsoft.com

#### <a name="get-location-suggestions"></a>获取位置建议

开始键入内容，Outlook 将会搜索匹配的位置。

这适用于在创建约会和会议时看到的“位置”字段。

#### <a name="getting-started"></a>开始使用：

- 在 Outlook 的 O365 或 Outlook.com 日历上创建约会或会议。 
- 单击“位置”字段，并开始键入内容…

#### <a name="scenarios-to-try"></a>可尝试的方案

向会议添加会议室时，单击“位置”字段，而不是使用“会议室查找器”加载项或通讯录。
对于在有公共位置的实体场所（比如餐馆、咖啡店或甚至是牙医诊所）进行的约会，试着用新的选取器来查找确切位置。 这样一来，就可以在要离开时收到 Outlook Mobile 通知。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>全部
- 修复了以下问题：搜索框在脱机时一直处于启用状态

### <a name="word"></a>Word 
- 修复了以下问题：键盘焦点有时难以看到
- 修复了以下问题：粘贴到新文档中的文本有时可能会出现错误的文本对齐方式
- 修复了以下问题：某些用户可能无法在暂停计算机后保存更改
- 修复了以下问题：在某些情况下，打印的是整个文档，而不是选定页面
- 修复了以下问题：批注可能会在小型显示器上难以阅读
- 修复了以下问题：在捕获到设备时可能会发生故障

### <a name="excel"></a>Excel
- 各种性能和稳定性修复

### <a name="powerpoint"></a>PowerPoint
- 修复了以下问题：键盘焦点有时难以看到

### <a name="outlook"></a>Outlook
- 修复了以下问题：禁用的加载项可能会错误地显示为已启用。
- 修复了以下问题：客户无法查看所有保留策略（如果有大量保留策略的话）。

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="june-14-2019"></a>2019 年 6 月 14 日
版本 1907（内部版本 11807.20000）

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们修复了可能会阻止用户在保存到 OneDrive 时登录的问题
- 我们修复了以下问题：在限制访问模式下，系统可能会阻止用户更改 SharePoint 属性
- 我们修复了在调整边距时页眉和页脚内容可能发生更改的问题
- 我们修复了在切换到 Web 视图时格式可能会遭到破坏的问题
- 我们修复了可能会阻止用户在从 SharePoint 打开时使用自定义字段的问题

### <a name="excel"></a>Excel
- 我们修复了在删除筛选集的行时出现的性能问题
- 我们修复了在受保护的视图中有时可能会导致鼠标闪烁的问题
- 我们修复了在删除系列时可能导致崩溃的问题
- 我们修复了以下问题：在没有可用版本历史记录的情况下，某些用户却可以获得用以添加该信息的选项
- 我们修复了在使用电子表格比较工具时可能导致异常的问题

### <a name="powerpoint"></a>PowerPoint
- 我们修复了在单击 SharePoint 链接时出现崩溃的问题
- 我们修复了在使用 Surface 触控笔键入过程中可能将用户切换到下一页的问题

### <a name="outlook"></a>Outlook
- 我们修复了在某些情况下“收件人”字段比正常情况更大的问题

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="june-7-2019"></a>2019 年 6 月 7 日
版本 1907（内部版本 11727.20064）

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们修复了 Word 在将自动更正设置为句子首字母大写时有时会发生崩溃的问题
- 我们改进了在 SharePoint 上编辑文档时的性能
- 我们修复了在 Adobe Illustrator 中创建的矢量图无法正确显示的问题

### <a name="excel"></a>Excel
- 我们修复了录制宏时排序字段有时无法正确设置的问题
- 我们解决了在重新计算数组公式过程中导致挂起或崩溃的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 我们修复了内联附件有时被错误缩放的问题

### <a name="access"></a>访问
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 我们修复了固定时间段内的时间表有时可能会改变工作完成日期的问题
- 我们修复了从早期版本打开项目时“完成的百分比”值可能错误的问题

</BR></BR>

## <a name="may-31-2019"></a>2019 年 5 月 31 日
版本 1906（内部版本 11722.20008）

## <a name="whats-new"></a>新增功能：

### <a name="outlook"></a>Outlook

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a>用于联系支持人员的对话框现可停靠且显示在右侧

用于联系支持人员的对话框现将显示在右侧窗格且作为停靠的窗口启动。

#### <a name="ink-in-your-email"></a>电子邮件中的墨迹功能！

现可在 Outlook 电子邮件中绘制图片并进行批注。

### <a name="word"></a>Word

#### <a name="open-document-links-in-word"></a>在 Word 中打开文档链接

单击 Office 中的文档链接时，可更新要在 Word 应用中的默认打开的首选项。  要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。 了解详细信息：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>开始使用：

功能默认关闭。 用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。
当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。

要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：

“文件”->“选项”->“高级”->“链接处理”

此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。

##### <a name="scenarios-to-try"></a>可尝试的方案：

要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 Word 文档的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。 选择加入后，链接将在 Win32 应用中默认启动。

### <a name="powerpoint"></a>PowerPoint

#### <a name="open-presentation-links-in-powerpoint"></a>在 PowerPoint 中打开演示文稿链接

单击 Office 中的演示文稿链接时，可更新要在 PowerPoint 应用中的默认打开的首选项。 要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。 了解详细信息：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>开始使用：

功能默认关闭。 用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。
当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。

要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：

“文件”->“选项”->“高级”->“链接处理”

此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。

##### <a name="scenarios-to-try"></a>可尝试的方案：

要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 PowerPoint 演示文稿的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。 选择加入后，链接将在 Win32 应用中默认启动。

### <a name="excel"></a>Excel

#### <a name="open-workbook-links-in-excel"></a>在 Excel 中打开工作簿链接

单击 Office 中的工作簿链接时，可更新要在 Excel 应用中的默认打开的首选项。 要更新首选项，请转到“文件”->“选项”->“高级”->“链接处理”。 了解详细信息：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>开始使用：

功能默认关闭。 用户可通过“选项”->“高级”->“链接处理”设置将其启用，也可在 Win32 WXP 应用引导其使用“选择加入”体验时选择加入。
当用户通过 Outlook/Word/PowerPoint/Excel 单击 OneDrive/OneDrive for Business/SharePoint 上存储的 Word/PowerPoint/Excel 文件的链接时，这些链接将在相应的 Office 应用程序中打开，而不是默认在浏览器中打开。

要更改此默认设置，用户可在 Outlook/Word/Excel/PowerPoint 中更新以下设置：

“文件”->“选项”->“高级”->“链接处理”

此设置跨 Outlook/Word/PowerPoint/Excel 共享，且可在上述任一应用中进行设置。

##### <a name="scenarios-to-try"></a>可尝试的方案：

要触发“选择加入”体验 - 请通过 Outlook/Word/PowerPoint/Excel 打开 OneDrive/SharePoint 中存储的 Excel 工作簿的链接（通过 Office Online 在客户端中单击“打开”），在 30 天的时间段内执行此操作两次。 选择加入后，链接将在 Win32 应用中默认启动。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>所有
- 修复了即使已禁用“自动保存”，文件有时也会自动保存的问题

### <a name="word"></a>Word 
- 修复了可能会阻止某些用户保存到 SharePoint 的问题

### <a name="excel"></a>Excel
- 修复了非活动筛选器的图标可能显示不正确的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 修复了某些用户在“小组日程”视图中错误地显示为“离线”的问题
- 修复了阻止 SafeLink 分析带尾随空格的 URL 的问题
- 修复了会议室在非工作时间之外显示为可用状态的问题

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="may-24-2019"></a>2019 年 5 月 24 日
版本 1906（内部版本 11715.20002）

## <a name="whats-new"></a>最近更新：

#### <a name="user-experience-updates"></a>用户体验更新

现在即将推出的更新包含简化功能区, 以及文件夹窗格、邮件列表和阅读窗格的可视刷新。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>全部

- 我们解决了“聊天”窗格未显示的问题

### <a name="word"></a>Word 
- 我们修复了在某些情况下 Word 可能不正确地突出显示具有语法错误的文字的问题

### <a name="excel"></a>Excel
- 我们修复了图标元素中使用了不正确的图标的问题
- 我们修复了在已打开工作簿时可能会在 VBA 脚本中激活不正确的工作簿的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 各种性能和稳定性修复

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 我们修复了在切换至任务栏后 Project 可能会崩溃的问题

</BR></BR>

## <a name="may-17-2019"></a>2019 年 5 月 17 日
版本 1906（内部版本 11708.20006）

## <a name="whats-new"></a>最近更新：

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>用户体验更新

现在即将推出的更新包含简化功能区, 以及文件夹窗格、邮件列表和阅读窗格的可视刷新。

##### <a name="getting-started"></a>入门指南：

这些更改将成为新的默认 UI 的一部分;自12月中旬以来, 它一直对"即将推出"的切换按钮提供100% 的支持

#### <a name="customizable-simplified-ribbon"></a>可自定义的简化功能区

可在经典视图和简化视图之间轻松切换，还可置顶/取消置顶命令。

##### <a name="getting-started"></a>入门指南：

用户可以通过打开 "即将推出" (最初) 并单击功能区中的燕尾形来切换经典的多行功能和新的简化的单行功能, 从而获得简化的功能区。

##### <a name="scenarios-to-try"></a>可尝试的方案：

从经典功能区切换为简化功能区

#### <a name="pick-your-favorite-action"></a>挑选你喜欢的操作

不要使用“标志”和“删除”？ “存档”或“标记为已读”呢？ 使用你最常用的命令自定义快速操作菜单。

##### <a name="getting-started"></a>入门指南：

若要选择“快速操作”, 请右键单击邮件列表中的电子邮件以显示“上下文菜单”。 选择”设置快速操作“

##### <a name="scenarios-to-try"></a>可尝试的方案：

将 "标记中的默认值" 和 "删除" 更改为 "存档"、"移动"、"标记为已读" 或 "无", 清理邮件列表

#### <a name="relaxed-or-tighter-layout-you-choose"></a>更紧凑还是更宽松的布局？ 由你决定

“更紧凑的间距”让你能够决定是希望项目之间间距更大，还是希望布局更紧凑以显示更多内容。

##### <a name="getting-started"></a>入门指南：

"查看" 选项卡, 使用更紧凑的间距复选框——在 "消息" 组中的 "经典功能区"、"当前视图" 设置 (用于简化功能区)

##### <a name="scenarios-to-try"></a>可尝试的方案：

使用 Outlook 在启用和不启用设置的情况下对电子邮件进行分类和写入。 使用更紧凑的间距, 每页都可容纳更多的邮件, 撰写表格上的控件也会更加精简。

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>使用 Onedrive 同步客户端时重复序列显示 MRU 项

通过删除 mru 条目, 实现与带云附件的 onedrive 同步客户端更好的集成, 并为同步数据启用更快的附加作为复制行为

##### <a name="getting-started"></a>入门指南：

如果你使用 OneDrive 同步客户端, 则在附件 MRU 中将不会再看到文件重复的情况。

##### <a name="scenarios-to-try"></a>可尝试的方案：

启用 OneDrive 同步客户端并使用 Outlook 桌面版中的 "附件" 菜单

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>改进了多个文件夹的邮箱的共享文件夹同步

多年来同步共享邮箱时, Outlook 的最大数量限制为500文件夹。 通过此更改, Outlook 已得到改进, 以不再遇到此500个文件夹限制的方式进行同步。

##### <a name="getting-started"></a>入门指南：

在邮箱中创建1000个文件夹, 让其他人访问该邮箱, 创建 "他人" 的 Outlook 配置文件, 并验证同步是否有效。

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>只需删除一点

##### <a name="getting-started"></a>入门指南：

转到 "绘图" 选项卡。选择 "橡皮擦" 下拉列表。 选择 "小型橡皮擦" 或 "中擦除"。

##### <a name="scenarios-to-try"></a>可尝试的方案：

转到 "绘图" 选项卡。选择笔。 绘制墨迹笔划。 选择 "橡皮擦" 下拉列表。 选择 "小型橡皮擦" 或 "中擦除"。 擦除墨迹笔划中的那位。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>全部 
- 我们已修复了可能会阻止某些用户另存为 PDF 的问题
- 我们修复了一个问题, 该问题可能会影响用户在32位系统上保存大型文件的情况。

### <a name="word"></a>Word 
- 显著提高了听写功能的响应性

### <a name="excel"></a>Excel
- 我们修复了触摸屏设备上双击事件可能失败的问题。
- 我们修复了可能会阻止某些用户编辑 VBA 宏的问题
- 我们解决了在使用切片器时可能会影响性能的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 我们解决了以下问题：可能会显示所选内容错误的模板

### <a name="access"></a>Access
- 我们解决了以下问题: 使用 "缩放生成器" 显示长格式文本, 可能很难阅读

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="may-10-2019"></a>2019 年 5 月 10 日
版本 1906（内部版本 11702.20000）

## <a name="whats-new"></a>新增功能：

### <a name="outlook"></a>Outlook

**在屏幕上显示更多邮件：** 选择“视图”>“使用更紧密的间距”来调整邮件之间的间距。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>所有
- 修复了“另存为”对话框可能显示错误路径的问题

### <a name="word"></a>Word 
- 修复了“操作说明搜索”中的某些选项无法插入的问题

### <a name="excel"></a>Excel
- 各种性能和稳定性修复

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 各种性能和稳定性修复

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 修复了任务 ID 可能需要突出显示才能看到的问题

</BR></BR>

## <a name="may-3-2019"></a>2019 年 5 月 3 日
版本 1906（内部版本 11629.20008）

## <a name="whats-new"></a>新增功能：

### <a name="outlook"></a>Outlook

**所有加密选项都在一个位置：** 只需转到“选项”>“加密”以选择如何保护电子邮件。

## <a name="notable-fixes"></a>显著修复：

### <a name="all"></a>所有
- 修复了一些用户在与 OneDrive for Business 同步时会遇到问题的问题

### <a name="word"></a>Word 
- 修复了在某些情况下 Word 需要很长时间才能启动的问题。

### <a name="excel"></a>Excel
- 修复了在升级到较新版本的 Excel 后，有时会从工作簿中删除外部链接的问题
- 修复了某些用户在新工作簿中选择单元格时可能会遇到困难的问题

### <a name="powerpoint"></a>PowerPoint
- 修复了在将绘图转换为文本时字体大小不一致的问题

### <a name="outlook"></a>Outlook
- 修复了从 .VCF 文件中保存联系人可能会导致空字段的问题
- 修复了尽管邮件已发送，但仍可能卡在发件箱文件夹中的问题
- 修复了在查看 DRM 邮件时 Outlook 可能会崩溃的问题

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 修复了编辑器可能会从中文切换到英语的问题
- 修复了未发布任务可能出现在主项目的已发布副本中的问题

</BR></BR>

## <a name="april-26-2019"></a>2019 年 4 月 26 日
版本 1905（内部版本 11617.20002）

## <a name="new-features"></a>新功能

### <a name="outlook"></a>Outlook

**共享日历更新速度更快：** 对于 Office 365 中的共享日历，Outlook 可以使用 REST API 更新这些日历。 打开预览，更快速、更可靠地更新共享日历。

### <a name="excel"></a>Excel

#### <a name="coauthoring-improvements"></a>共同创作改进

通过让其他人以更接近实时的方式接收内容更改，改进了共同创作体验。

### <a name="visio"></a>Visio

- **从 Power BI 导出 Visio 视觉对象：** 将 Power BI 报表导出为 PDF、PowerPoint 文件等时，Power BI 的 Visio 视觉对象现在将会正常显示。

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 各种性能和稳定性修复

### <a name="excel"></a>Excel
- 修复了规划求解宏运行失败的问题
- 修复了可能阻止将 Excel 文件导入 SharePoint 的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 各种性能和稳定性修复

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="april-19-2019"></a>2019 年 4 月 19 日
版本 1905（内部版本 11609.20002）

## <a name="whats-new"></a>最近更新：

### <a name="outlook"></a>Outlook

**搜索某个人时获取电子邮件建议：** 在“搜索”框中键入某人姓名时，最相关的电子邮件信息将包含在搜索建议中。

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>改进了使用数据类型的着色地图体验

对于使用 Excel 的地理数据类型绘制着色地图图表的用户而言，这是一项改进功能。 对于最终用户而言，其优势是功能之间更丰富的集成，并提高了最终用户想要绘制的区域的准确性。 额外优势包括绘制城市多边形的功能。

##### <a name="getting-started"></a>入门：

- 此功能是对 Excel 中现有功能的改进。 若要使用此改进功能，可将位置转换为“丰富实体”并使用着色地图绘图。 

##### <a name="scenarios-to-try"></a>可尝试的方案：

- 用户可尝试绘制城市、省/市/自治区、县、国家/地区和邮政编码。 


## <a name="notable-fixes"></a>显著修复：

### <a name="all-applications"></a>所有应用程序
- 修复了应用程序启动时显示“首次运行”对话框的问题
- 修复了“另存为”对话框中的 SharePoint 链接可能丢失的问题。
- 修复了用户将误看到“立即修复”对话框的问题

### <a name="word"></a>Word 
- 修复了一些用户在请求字体时可能会收到内存或磁盘空间不足错误的问题
- 修复了从批注窗格切换时窗口可能丢失焦点的问题

### <a name="excel"></a>Excel
- 各种性能和稳定性修复

### <a name="powerpoint"></a>PowerPoint
- 修复了阻止调整品牌形状大小的问题
- 修复了 PowerPoint 在保护视图模式下打开文件时可能崩溃的问题

### <a name="outlook"></a>Outlook
- 修复了阻止某些用户选择中文字词的问题
- 修复了到期日期未正确计算的问题

### <a name="access"></a>Access
- 修复了阻止某些用户使用宏生成器的问题
- 修复了打印报告只打印第一页的问题
- 修复了在鼠标悬停在超链接上时应用程序可能崩溃的问题
- 修复了在使用关系视图时导致一些项目出现在屏幕之外的问题

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="april-12-2019"></a>2019 年 4 月 12 日
版本 1905（内部版本 11601.20042）

## <a name="whats-new"></a>最近更新：

### <a name="access"></a>Access

#### <a name="get-smart-with-microsoft-graph"></a>使用 Microsoft Graph，更智能

导入或链接到智能数据，通过智能技术彻底改变你的桌面数据库。

## <a name="notable-fixes"></a>显著修复：

### <a name="all-applications"></a>所有应用程序
 - 我们修复了一个阻止某些用户将文件保存到云端的问题
 - 我们修复了错误的窗格可以从功能区打开的问题

### <a name="word"></a>Word 
- 各种性能和稳定性修复

### <a name="excel"></a>Excel
- 我们修复了一个问题，即当工作簿不包含链接的数据类型时，用户会看到链接的数据类型的错误消息
- 我们修复了一个问题，即当在本地和在线查看时，Word 文档中的 URL 链接可能会发生变化

### <a name="powerpoint"></a>PowerPoint
- 我们修复了从动画选项卡中撤消更改后应用程序可能崩溃的问题

### <a name="outlook"></a>Outlook
- 我们修复了阻止某些用户修改公用文件夹中联系人的“备注”字段的问题
- 我们修复了在到期日期和删除日期之间可能发生冲突的问题

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="april-5-2019"></a>2019 年 4 月 5 日
版本 1904（内部版本 11527.20014）

## <a name="whats-new"></a>最近更新：

### <a name="outlook"></a>Outlook

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a>Outlook for Windows：设置和共享“重点收件箱”设置

“重点收件箱”首选项存储在云中，因此，在任何计算机上使用 Outlook for Windows 和 Outlook 网页版时，可以享受相同、一致的体验。

#### <a name="getting-started"></a>入门：

“文件”>“选项”>“常规”选项卡下存在“将我的 Outlook 设置存储在云中”的新首选项。 用户需要选中该框，才能使其“重点收件箱”设置漫游到其他桌面 Outlook 安装和 OWA。

#### <a name="scenarios-to-try"></a>可尝试的方案：

在计算机上更改已启用云设置首选项的“重点收件箱”。 导航至 OWA 并查看此处应用的首选项。 在 OWA 中更改“重点收件箱”并启动 Outlook 桌面版以查看反映的首选项。

### <a name="word"></a>Word

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a>“学习工具”模式可提供更多页面颜色的其他支持

Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。  许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。

#### <a name="getting-started"></a>入门：

若要尝试，请转至“视图”选项卡并选择“学习工具”，然后再选择“页面颜色”。

#### <a name="scenarios-to-try"></a>可尝试的方案：

若要尝试，请转至“视图”选项卡并选择“学习工具”，然后再选择“页面颜色”。

### <a name="excel"></a>Excel

#### <a name="elevate-creativity-with-animated-3d-models"></a>利用动画 3D 模型提升创意

Office 现支持动画模型，这些模型可以在编辑器中播放，从而让你的表单看起来栩栩如生！

#### <a name="getting-started"></a>入门：

1. 打开 Excel
2. 插入动画 3D 模型（即将在 Remix 中推出，但目前请访问以下位置的动画模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art）
3. 动画模型将在编辑器中播放！ 选中幻灯片放映模式 - 它也可以在此播放！
4. 在 3D 格式功能区中，浏览此模型中的更多动画场景

#### <a name="scenarios-to-try"></a>可尝试的方案：

1. 插入动画模型并在编辑器中观看该模型
2. 通过场景库（可在 3D 格式功能区中找到）浏览动画模型中可用的动画场景
3. 通过功能区、浮动条或空格键轻松播放/暂停动画。

## <a name="notable-fixes"></a>显著修复：

### <a name="all-applications"></a>所有应用程序
- 我们修复了以下问题：Excel 的上下文菜单中的应用图标无法正常显示
- 我们修复了以下问题：安装更新后，“文件”菜单按钮可能会消失
- 我们修复了可能更改用户许可证的问题

### <a name="word"></a>Word 
- 我们修复了以下问题：文本在某些缩放级别上无法正确呈现

### <a name="excel"></a>Excel
- 我们修复了以下问题：在进行编辑后，系统不会提示用户保存工作簿
- 我们修复了以下问题：如果用户共享了工作簿，则不会触发 BeforeSave 事件。
- 我们修复了以下问题：将列大小调整为少于 6 个像素可能会抛出不正确的错误消息。
- 我们修复了以下问题：Excel 会忽略 Application.Visible 标志
- 我们修复了以下问题：跟踪箭头保留在非活动的冻结窗格中
- 我们修复了以下问题：打开工作簿时货币可能更改日期的单元格格式
- 我们修复了以下问题：工具提示可能意外移动
- 我们修复了 Power Query 编辑器的本地化问题
- 我们修复了以下问题：通过电子邮件发送时，工作簿将作为附件删除

### <a name="powerpoint"></a>PowerPoint
- 我们修复了以下问题：复制形状的时间可能比预期要长

### <a name="outlook"></a>Outlook
- 我们修复了以下问题：使用“绘图”工具时 Outlook 可能会崩溃
- 我们修复了撰写 HTML 电子邮件时的本地化问题
- 我们修复了以下问题：用户难以选择下部窗格

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="march-22-2019"></a>2019 年 3 月 22 日
版本 1904（内部版本 11514.20004）

## <a name="new-features"></a>新功能

- **隐私控制：** 对诊断数据和连接体验的全新、更新和改进控制。 了解更多<https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json>

- **Office 图标具有新的外观：** Office 图标经过重新设计，可体现简单、强大和智能的 Office 体验。

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们修复了 UI 会不断显示“正在检查更改”的问题

### <a name="excel"></a>Excel
- 我们修复了在移动工作表后应用程序可能崩溃的问题
- 我们修复了在另存为 PDF 后应用程序可能崩溃的问题
- 我们修复了“保存”对话框不接受某些韩语字符的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 各种性能和稳定性修复

### <a name="access"></a>Access
- 我们修复了在 Access 中，创建 Access 的额外快捷方式错误消息
- 我们修复了所链接的 SharePoint 中数据显示不正确的问题

### <a name="project"></a>Project
- 我们解决了语言设置从中文切换到英语的问题
- 我们修复了在同步到 SharePoint 时应用程序可能崩溃的问题

</BR></BR>

## <a name="march-15-2019"></a>2019 年 3 月 15 日
版本 1904（内部版本 11504.20000）

## <a name="whats-new"></a>最近更新：

### <a name="word"></a>Word

#### <a name="focus-mode"></a>焦点模式

切换到“视图”菜单上的焦点模式，消除干扰，让你专注于工作。 仅适用于 Office 365 订阅者。

#### <a name="getting-started"></a>入门：

查看功能区状态栏中的选项卡“焦点”按钮 -“焦点”按钮

#### <a name="scenarios-to-try"></a>可尝试的方案：

进入焦点模式并体验焦点体验

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们修复了文档中的图片另存为 PDF 时产生不正确 DPI 的问题

### <a name="excel"></a>Excel
- 各种性能和稳定性修复

### <a name="powerpoint"></a>PowerPoint
- 我们修复了批准窗格无法正确打开或关闭的问题
- 我们修复了在删除视频时应用程序崩溃的问题
- 我们修复了应用程序在某些实例中无法启动的问题

### <a name="outlook"></a>Outlook
- 我们修复了已读回执在日语版中显示不正确的问题

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>

## <a name="march-8-2019"></a>2019 年 3 月 8 日 
版本 1903（内部版本 11425.20036）

## <a name="whats-new"></a>最近更新：

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>通过 Microsoft 搜索找到要查找的内容

使用 Microsoft 搜索，你可以找到完成工作所需的所有文件、操作、人员和帮助。

#### <a name="getting-started"></a>入门：

- 此功能醒目地显示在标题界面的顶部。

#### <a name="scenarios-to-try"></a>可尝试的方案：

- 搜索学院、最近使用的文档或搜索最常用的功能区命令
- 查找主题以获取有关它的详细信息
- 
#### <a name="coauthoring"></a>CoAuthoring

厌倦了被包含宏的文档拒之门外？ 现在，OneDrive for Business 上的文档文件允许被多位创作者同时编辑。

#### <a name="getting-started"></a>入门：

用户无需在 UI 中按任何按钮即可访问此功能。 默认情况下，OneDrive for Business 文档文件已启用此功能。
因此，用户应将文档文件保存到 OneDrive for Business 中以进行试用。

#### <a name="scenarios-to-try"></a>可尝试的方案：

在 OneDrive for Business 上创建一个文档文件，将其与同事共享，然后进行协作！

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options
- 我们修复了回复评论时发生的崩溃问题
- 我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题

### <a name="excel"></a>Excel
- 我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 我们修复了 Outlook 搜索不按选定的时间顺序排序的问题
- 我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题
- 我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题

### <a name="access"></a>Access
- 我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题
- 我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题

### <a name="project"></a>Project
- 各种性能和稳定性修复


## <a name="march-1-2019"></a>2019 年 3 月 1 日 
版本 1903（内部版本 11414.20014）

## <a name="whats-new"></a>新增功能

### <a name="word"></a>Word

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a>修订、备注和实时同步协作的颜色

产品中的修复现在可确保以相同的颜色显示备注、修订和协作者光标。

#### <a name="getting-started"></a>入门：

打开其他人已打开的 SharePoint 或 OneDrive 文档。 验证用户的修订和备注颜色是否与用户光标的颜色匹配。

#### <a name="scenarios-to-try"></a>可尝试的方案：

打开其他人已打开的 SharePoint 或 OneDrive 文档。 验证用户的修订和备注颜色是否与用户光标的颜色匹配。

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options
- 我们修复了从 Word 到 PowerPoint Online 的复制粘贴问题

### <a name="excel"></a>Excel
- 我们修复了打开受保护文档和可编辑文档时在 Excel 中复制单元格导致 CPU 使用率过高的问题

### <a name="powerpoint"></a>PowerPoint
- 我们修复了在 PowerPoint 中使用 @提及功能时幻灯片图像大小的问题

### <a name="outlook"></a>Outlook
- 我们修复了 Outlook 搜索不按选定的时间顺序排序的问题
- 我们修复了“打开此任务”工作流程功能区按钮对某些电子邮件无响应的问题
- 我们修复了用户在会议室查找工具中选择可用会议室时 Outlook 无法清除本地会议室的问题

### <a name="access"></a>Access
- 我们更新了确认重链接表格与数据源时显示的提示文本
- 我们修复了已保存的导入/导出对话框在深色主题的白色背景上具有白色文本的问题
- 我们修复了用户无法在表格设计时将“显示控件”属性的“是/否”字段设为文本框的问题

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>



## <a name="february-15-2019"></a>2019 年 2 月 15 日 
版本 1903（内部版本 11310.20016）

## <a name="whats-new"></a>最近更新：

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>平滑切换增强功能 - 按名称平滑

选择需要平滑的形状

#### <a name="getting-started"></a>入门：

- 若要使“平滑”将两个对象视为同一对象，用户可以使用“选择窗格”来重命名形状。
- 该名称必须以“!!” （两个感叹号）开头，以便“平滑”使用它来覆盖默认匹配行为，例如“!!Name”
- 用户可以使用任何不是以“!!”开头的名称来重命名形状， 不必担心这会改变 Morph 的工作方式

#### <a name="scenarios-to-try"></a>可尝试的方案：

- 在幻灯片中插入一个形状，假设它为矩形
- 创建新幻灯片
- 在第 2 张幻灯片中插入不同的形状，假设它为三角形
- 打开“选择窗格”，将幻灯片 1 中的矩形重命名为“!!shape”，并将幻灯片 2 中的三角形重命名为“!!shape”
- 在第 2 张幻灯片上应用平滑

</BR>

### <a name="morph-transition-enhancements---smartart"></a>平滑切换增强功能 - SmartArt

具有更流畅切换效果的 SmartArt 平滑

#### <a name="getting-started"></a>入门：

按照使用 SmartArt 的相同方式来使用平滑

#### <a name="scenarios-to-try"></a>可尝试的方案：

- 在幻灯片中插入 SmartArt
- 复制幻灯片
- 在复制的幻灯片上调整/更改/移动 SmartArt
- 在复制的幻灯片上应用平滑

</BR>

### <a name="morph-transition-enhancements---tables"></a>平滑切换增强功能 - 表格

具有更流畅切换效果的表格平滑

#### <a name="getting-started"></a>入门：
按照使用表格的相同方式来使用平滑

#### <a name="scenarios-to-try"></a>可尝试的方案：

- 在幻灯片中插入表格
- 复制幻灯片
- 在复制的幻灯片上调整/更改/移动表格
- 在复制的幻灯片上应用平滑

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio

### <a name="seamlessly-switch-between-accounts"></a>在帐户之间无缝切换

新的帐户管理员在一个位置显示你的所有工作和个人帐户，让你在帐户之间自如切换。 更新后的这一体验清晰展示了你的登录方式，你现无需先退出或处理复杂的对话，即可在工作帐户和个人帐户之间切换。


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>可尝试的方案：
- 在帐户之间切换
- 添加新帐户[注意：你可能需要先转到“文件”|“帐户”|“已连接的服务”，然后删除与工作帐户相关的任何个人服务，反之亦然]
- 从帐户注销
</BR>

## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们修复了表格和图像的上下文预览问题

### <a name="excel"></a>Excel
- 我们修复了自动筛选搜索字段中的文本在黑色主题中显示为白色的问题
- 我们修复了新 Office 加载项的许可 UI 问题

### <a name="powerpoint"></a>PowerPoint
- 我们修复了在笔记本电脑或平板电脑上演示幻灯片时自动扩展显示的问题。

### <a name="outlook"></a>Outlook
- 我们修复了“发送至 OneNote”按钮显示的问题

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复


</BR></BR>
## <a name="february-11-2019"></a>2019 年 2 月 11 日
版本 1903（内部版本 11330.20014）


## <a name="notable-fixes"></a>显著修复：

### <a name="word"></a>Word 
- 我们已修复以下问题：一些自定义样式无法应用于 word online
- 我们修复了 Word 中丰富对象的上下文预览问题
- 我们修复了以下问题：粘贴列表将导致 Word 崩溃

### <a name="excel"></a>Excel
- 我们修复了以下问题：当没有货币符号时，数字格式后不再显示附加空格
- 我们修复了自动检测股票的问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修复

### <a name="outlook"></a>Outlook
- 各种性能和稳定性修复

### <a name="access"></a>Access
- 各种性能和稳定性修复

### <a name="project"></a>Project
- 各种性能和稳定性修复

</BR></BR>


## <a name="february-1-2019"></a>2019 年 2 月 1 日 
版本 1902（内部版本 11326.20000）


## <a name="notable-fixes"></a>显著修复

### <a name="word"></a>Word 
- 我们修复了在嵌入式 Excel 表格中调整单元格大小的问题
- 我们修复了在画布中复制/粘贴形状的问题

### <a name="excel"></a>Excel
- 我们修复了从 Excel Web 应用程序中打开文件的问题
- 我们修复了由于文件名长度而无法将 .XLSX 另存为 CSV 文件的问题
- 我们修复了上下文菜单显示上下文菜单选项的问题

### <a name="powerpoint"></a>PowerPoint
- 我们修复了用户无法使用键盘快捷方式 ctrl+alt+7/ctrl+alt+8 进入方括号的问题
- 我们修复了将本地视频插入 PPT 会减少“C”驱动器磁盘空间的问题
- 我们修复了未向某些用户显示“发布到 Microsoft Stream”按钮的问题

### <a name="outlook"></a>Outlook
- 我们修复了日历中的任务视图未正确显示任务主题的问题

### <a name="access"></a>Access
- 我们修复了图表的缩放比例问题

### <a name="project"></a>Project
- 各种性能和稳定性修复
