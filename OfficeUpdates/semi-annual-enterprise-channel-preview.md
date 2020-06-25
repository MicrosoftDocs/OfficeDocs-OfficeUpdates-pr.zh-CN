---
title: 2020中的半年企业频道（预览）版本的发行说明
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2020 年 Microsoft 365 应用版半年频道（定向）发行的发行说明
ms.openlocfilehash: be72a3d95178f0fde5bbe48428abb0895d5afefd
ms.sourcegitcommit: cc48ae789324e085a976c3a7a388353447b10d42
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/12/2020
ms.locfileid: "44724956"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a>2020中的半年企业频道（预览）版本的发行说明

这些发行说明提供了有关以下内容的信息： Microsoft 365 应用程序的半年企业版频道（预览）更新2020中包含的新功能和非安全更新、Microsoft 365 应用程序的商业版以及适用于 Project 和 Visio 的桌面应用程序的订阅版本。

> [!IMPORTANT]
> 我们正在对 Microsoft 365 应用的更新频道进行一些更改，包括添加新的更新频道（月度企业版频道）和更改现有更新频道的名称。 若要了解详细信息，请[阅读这篇文章](https://go.microsoft.com/fwlink/p/?linkid=2127441)。


## <a name="version-2002-june-09"></a>版本2002：6月09日
*版本2002（内部版本12527.20720）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出了安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 修复了以下问题：如果文件路径过长，外部链接将在文件重新打开后停止工作。

- 修复了以下问题：使用 Ctrl + Shift + 箭头键在 Excel 窗口通过团队共享时，Excel 可能会变得变慢。

- 修复了打印时窗体控件中的复选框缩放问题。

- 尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。

- 在筛选列表中插入列所需的时间可能比预期更长。

- 修复了以下问题： @ 符号开始一个公式将被视为隐式交集运算符。

### <a name="outlook"></a>Outlook

- 启用通过本机团队客户端直接加入团队会议。

- 解决了 Outlook 未能启用数据丢失保护策略提示的问题，即针对 M365 商业版和计划的服务付费用户的人员。

- 解决了一个问题，该问题导致用户无法完成 Gmail 的身份验证提示时浏览器仿真设置不正确。

- 解决了导致服务器操作系统上的 Outlook 用户看到错误 "防病毒状态：无效" 的问题。 此版本的 Windows 支持防病毒检测，但未找到防病毒软件，但未正确配置防病毒。

### <a name="word"></a>Word

- 修复了以下问题：在使用“快速打印”打印后尝试进行编辑时，文档中的字词对齐方式会被打乱。

### <a name="office-suite"></a>Office 套件

- 我们解决此问题的方法是，将 backstage 中的频道名称更新为2020年1月的新频道名称。

- 我们已修复此问题，如果设备是策略管理的，它将不会调用 DMS 访问群体 API。

- 解决了在单个事务中添加和删除应用程序时未完成删除的问题。

- Office 主机在 windows 中崩溃，当在注册表项 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 设置为0时激活外接程序。 此更改将修复此问题。


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-may-12"></a>版本 2002：5 月 12 日
*版本 2002（内部版本 12527.20612）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出了安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题

### <a name="excel"></a>Excel

- 打开包含对许多其他工作簿（尤其是隐藏窗口）的引用的工作簿将比预期的慢。

- 在某些情况下，打开 CSV 文件所花费的时间比预期的长。

- 在具有不同缩放级别的工作簿之间切换时，在某些情况下 Excel 可能会崩溃。

- 修复了一个有关 VBA 的问题：将值写入某个区域可能比预期的要慢。

- 从按颜色筛选的列复制的数据有时无法正确粘贴。

- 修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 会崩溃。

- 含有数字签名且在 Excel 2016 中保存的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。

- 解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。

- 使用 Range.Value 和 Range.Value2 (VBA) 会导致公式作为动态数组输入。

### <a name="onenote"></a>OneNote

- 对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。

- 显示了一条通知，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。

- 通过暂时减少 OneNote 2016 中版本历史记录页面的数量和同步频率，提升了同步和服务稳定性。

- 通过暂时禁用 OneNote 2016 中的回收站，提升了同步和服务稳定性。 当用户尝试删除通常将发送到回收站中的数据时，系统会询问用户是希望保留还是永久删除数据。

- 通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。

- 在 OneNote 2016 中，通过暂时将联机笔记本中的嵌入式文件和图像的下载推迟到用户导航到相应页面时进行，提升了同步和服务稳定性。

- 通过暂时禁用 OneNote 2016 中的应用内视频录制功能，提升了同步和服务稳定性。 本地笔记本不受此措施影响。

- 在 OneNote 2016 中，通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。 对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入 OneNote。

### <a name="outlook"></a>Outlook

- 解决了导致文件夹窗格宽度意外改变的问题。

- 解决了导致用户在某次 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。

- 解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。

- 此更新修复了 Microsoft Outlook 在用户查看或撰写邮件时不显示当前敏感度标签的问题。

- 解决了导致用户无法将电子邮件地址发送到个人通讯组列表的问题。

### <a name="powerpoint"></a>PowerPoint

- 修复了在用户打开的文件副本中含有改进的批注时为用户中继正确消息的问题。

### <a name="word"></a>Word

- 解决了可能无法正确启动 Access 和 Publisher（具体取决于安装的语言）的问题。

- 修复了受编辑保护的文档的“比较”功能问题。

- 我们修复了将 2 个文档合并为一个文档时出现的问题。

### <a name="office-suite"></a>Office 套件

- 这是一个修复程序，用于解决在客户端缓存文件时，Project 应用不应阻止网络的问题。

- 我们已经解决了内部操作在失败时引发异常而不是进行记录并继续的问题。 受影响的用户将不再被阻止接收更新。

- 此更改可确保草绘轮廓在功能区中正常工作。

- 修复了从具有某些特定代理配置的本地位置打开文件时出现的问题。

- 此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。

- 此更新修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。

- 此更新修复了 Microsoft Word 中的一个问题，即如果某个敏感度标签策略应用了页眉、页脚或水印，则在应用该标签时插入的长度超过 255 个字符的文本随后将无法通过更改或删除该标签来标识和删除。

- 修复了可在 Office 切换会话期间防止崩溃并提高用户体验可靠性的问题。  

- 此 bug 将更新增强型配置服务 (ECS) url 终结点。 调用此较新的终结点可以提高从 ECS 获取数据的成功率。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-april-14"></a>版本 2002：4 月 14 日
*版本 2002（内部版本 12527.20442）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **键入可返回多个值的公式：** 现可键入返回多个值的公式，它们将自动溢出到相邻的单元格中。 [了解更多](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **六个强大的函数：** 我们添加了六个新函数来增强你的电子表格：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。  [了解更多](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **向左看，向右看… XLOOKUP 在此！：** 使用 XLOOKUP 在表或区域中逐行查找所需内容。  [了解更多](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 在某些情况下，重新打开嵌入 Word 或 PowerPoint 的工作簿时，Excel 会崩溃。

- 当另存为 CSV 文件时，在某些情况下，Excel 可能将所有列合并为一个列。

- 在受保护工作表中的某个区域内使用 Range.ClearContents 的时间可能比预期的要长。

- 修复了在“打印预览”中显示时表单控件中的文本缩放问题。

- 与功能区交互的 VBA 宏可能在 ScreenUpdating 意外设置为 True 的情况下运行。

- 解决了如果关闭了源代码簿，则外部链接不会在填充（向下填充、横跨填充等）时更新的问题。

- 使用 VBA 的应用程序。在某些情况下，评估无法用于用户定义的功能。

- 解决了从模板创建图表时出现的性能问题。


### <a name="outlook"></a>Outlook

- 解决了在某些方案中导致组页眉意外展开的问题。

- 解决了导致用户在选择某些搜索结果时遇到崩溃的问题。

- 解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。

- 解决了导致附件工具中缺少“保存到云”按钮的问题。

### <a name="powerpoint"></a>PowerPoint

- 改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。


### <a name="project"></a>Project

- 解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。

- 解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。

### <a name="word"></a>Word

- 解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。

- 我们修复了表格中文本适应的问题。

- 我们修复了插入水平线不短且居中的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-march-10"></a>版本 2002：3 月 10 日
*版本 2002（生成号 12527.20278）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **快速查找链接的表格：** 新的“搜索”框使查找链接的表格成为一项轻松的乐事。 [了解详细信息](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **使用 \@提及**功能引起他人的注意：在批注中使用 @提及，以在需要同事的意见时让他们知悉。 [了解更多](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **查找要找的内容：** 搜索命令、人员、文件、照片、Web 文章等等。 [了解更多](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **手绘：** 让工作簿中的 Office 形状呈现随意的手绘外观。 [了解更多](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。

- **不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。

- **关注剩余待办事项：** 选择“解决”可折叠评论并突出显示待处理的项目。

- **创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。 [了解更多](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **将文件转换为改进辅助功能: **将文件升级到新式格式，使其更易于所有人访问。

- **数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。 [了解详细信息](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。

- **获取工作簿统计信息：** 工作簿统计信息提供工作簿内容的概述，可帮助你更轻松地发现内容。





### <a name="outlook"></a>Outlook



- **将 LinkedIn 网络连接到 Outlook：** 以安全的方式将 LinkedIn 帐户连接到 Microsoft 帐户，直接在“人员”卡片中查看 LinkedIn 中的信息。 [了解更多](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Outlook 中的插入链接菜单将插入包含租户管理员定义的权限的链接：** Outlook 插入链接 MRU 中的链接将插入仅对已经拥有权限的用户有效的链接。 这通常会导致请求获得文档访问权限的用户之间发生往来电子邮件。 我们已更新了此体验，现在该链接将通过租户管理员设置的默认权限进行插入。对于 MSIT，这“可供组织编辑”，因此收到以此方式共享的链接的所有内部用户都可以访问它。

- **在有拼写错误的情况下进行搜索：** 即使你的拼写有误，Outlook 仍将找到你在查找的内容。

- **轻松发现网络钓鱼邮件：** 垃圾邮件和网络钓鱼邮件具有不同的外观，因此你可以轻松从收件箱中识别并删除它们。

- **针对攻击的高级防护：** 通过 Office 365 高级威胁防护, 可通过电子邮件主题中的超链接、附加邮件、签名邮件、网络路径等的方式抵御攻击。

- **让我把它画出来：** 在图片上进行涂鸦或添加绘图画布以使用墨迹表达你的想法。 [了解更多](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **查看搜索结果中的相关消息：** Outlook 会分析搜索词，并在搜索结果顶部显示最相关的电子邮件信息。 还会在“热门搜索结果”部分看到按日期排序的所有搜索结果。 [了解更多](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **获取位置建议：** 在安排约会和会议时，开始键入位置，Outlook 就会推荐会议室、地址和其他邻近位置。 [了解更多](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **在屏幕上显示更多邮件：** 选择“视图”>“使用更紧密的间距”来调整邮件之间的间距。 [了解更多](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **以不同的亮度查看邮件：** 使用“太阳”/“月亮”按钮在阅读窗格中的明暗背景之间切换。 [了解更多](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)



### <a name="powerpoint"></a>PowerPoint

- **PowerPoint 中的快速实时协作：** 在 PowerPoint 中快速展开实时协作

- **新增校对工具：** 无需在语言方面倍感压力。 PowerPoint 现在可提供语法和写作建议。 [了解更多](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)


- **实时字幕和对白字幕：** 演示者的文字会作为字幕自动显示在屏幕上或翻译成你所选语言的对白字幕。 [了解更多](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。 [了解更多](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **查找并修复缺失的幻灯片标题：** 幻灯片标题可为你的推销词增色添彩，并使所有用户都可以访问你的幻灯片。 辅助功能检查器显示标题缺失位置，以便你可以快速添加标题。 [了解更多](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **手绘：** 让演示文稿中的 Office 形状呈现随意的手绘外观。 [了解更多](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。

- **不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。

- **将插图另存为 SVG**：将图表、形状或其他插图另存为可缩放矢量图形，这样做可以调整其大小，而不会降低图像质量。 [了解更多](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **打印讲义上的幻灯片编号：** 幻灯片编号将会自动包括在讲义上。 打开或是关闭它们，全都取决于你。 [了解更多](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **墨迹即时重播：** 在幻灯片上使用墨迹时，可应用重播动画，在幻灯片放映期间重播墨迹的实际绘制过程。 [了解更多](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。

- **全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。

- **将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。

- **更安全的视频体验：** 安全增强意味着更安全的联机视频体验。

- **如果可以重复使用，为何还要重新创建呢？：** 通过重新使用你创建的幻灯片或其他人与你共享的幻灯片来节省时间。 [了解更多](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **在 PowerPoint for Office 365 中将手写墨迹更改为形状、文本或数学公式：** 从自由格式的墨迹转到几条笔划中的 Office 形状、文本或数学表达式。 [了解更多](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **用墨迹绘制精彩绝伦的幻灯片：** 将墨迹转换为标准形状和文本，然后从 PowerPoint 设计器获取智能幻灯片设计灵感。 [了解更多](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

### <a name="visio"></a>Visio

- **返回到“犯罪”的场景：** 使用“犯罪场景调查模板”中的新证据、室内和户外模具，仔细地重新创建罪犯的犯罪场景。

- **在 Excel 中制作优美的 Visio 图表：** 通过将数据置于工作表上来创建流程图或组织结构图。 [了解更多](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **简历编辑器加入 LinkedIn 简历助手：** 简历编辑器提供了一系列专为简历量身定制的语法和样式检查，以使你的写作更加精确和专业。

- **修复了 3D 对象合并导致的文档损坏问题：** 修复了 3D 对象合并导致的文档损坏问题。

- **查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。 [了解更多](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **色彩丰富的协作：** 批注和修订由参与者进行颜色编码，以便你能够轻松看到协作者是谁。

- **协同编辑启用宏的文档：** 将 docm 文件保存在 OneDrive for Business 上，并与协作者实时进行编辑。

- **合著改进**：提高了在具有修订的文档中进行合著时的 Word 性能。

- **更多符合你心情的图标：** 我们添加了 300 多个新图标。 可在“插入”>“图标”中找到它们。 [了解更多](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **其他人可以快速查看你所做的更改：** 共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。

- **手绘：** 让文档中的 Office 形状呈现随意的手绘外观。 [了解更多](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **精确擦除：** 从两个橡皮擦尺寸中进行选择以修复小墨迹缺陷。 [了解更多](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。

- **不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。 [了解更多](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **其他人可以快速查看你所做的更改：** 共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。

- **合著改进：** 提高了合著时的可靠性。

- **创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。 [了解更多](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。

- **更安全的视频体验：** 安全增强意味着更安全的联机视频体验。 [了解更多](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **将形状另存为图片：** 只需单击几下即可将形状、图标或其他对象另存为图片文件，以便您将其用于其他任何位置。 [了解详细信息](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="access"></a>Access

- 此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现&quot;查询已损坏&quot;错误。

- 此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。

- 此更新修复了使用 ADODB 的问题。 VB 代码中的记录器对象可能会错误地报告错误。

- Access 模板将不会再导致数据库中的附件列出现故障。 在实例化模板后，你现在应该可以将附件字段添加到数据库中。

### <a name="excel"></a>Excel

- 解决了导致用户在对签名进行重命名时发生崩溃的问题。

- 此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。

- 修复了一个问题，该问题导致某些用户在将文本转换为包含单元格（具有溢出数组）的列时遇到崩溃。

- 此更新修复了导致公式栏以不同于预期的字体显示文本的问题。

- 某些区域设置的“文本分列”功能可能会失败。

- 访问隐藏命名区域时，用户可能会遇到错误。

- 用户在使用部分非英文字符集保存更改时可能会出错。

- 解决了在滚动后选择单元格时可能导致选择错误单元格的问题。

- Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。

- 某些本地化版本的“文本分列”功能可能会失败。

- 访问隐藏命名区域时，用户可能会遇到错误。

- 用户在使用部分非英文字符集保存更改时可能会出错。

- 修复了某些用户可能遇到的嵌入和链接对象 (OLE) 问题。

- 我们修复了数据透视图的右键单击菜单，以便启用“显示详细信息”选项。

- 解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。

- 修复了当工作簿中存在外部链接时某些用户可能遇到多个弹出窗口的问题。

- 修复了未显示上下文菜单中的批注命令的问题。

- 解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。

- 修复了 CUBEVALUE 函数有时会返回错误结果的问题。

### <a name="outlook"></a>Outlook

- 解决了导致“搜索反馈”体验挂起的问题。

- 解决了导致用户在检索云设置时在 Outlook 中遇到挂起的问题。

- 解决了导致搜索框在高 dpi 模式下未正确对齐的问题。

- 解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。

- 解决了在某些情况下导致用户看到电子邮件发送地址与显示的 SMTP 地址不匹配的问题。

- 此更改恢复了在邮件头中查看多行主题的功能。

- 我们修复了可能会阻止文件保存到 WebDAV 位置的问题。

- 解决了 SMIME 算法选择方面的问题。

- 解决了导致第三方应用程序无法发送电子邮件的问题。

- 解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“&quot;确定&quot;”按钮的空白消息框的问题。

- 解决了导致用户在配置文件创建过程中遇到崩溃的问题。

- 解决了导致 Outlook 在同步滑块设置为较小的设置时出现意外同步所有邮件的问题。

- 解决了具有黑色主题的用户在“&quot;发件人&quot;”下拉列表中看到白色背景上显示白色文本的问题。

- 解决了导致用户在取消帐户设置时遇到崩溃的问题。

- 解决了导致用户在对签名进行重命名时发生崩溃的问题。

- 解决了一个问题，该问题导致在某些情况下无法使用相关选项来禁用标记项目突出显示。

- 解决了导致用户在打开“规则”对话框时看到&quot;此计算机上的规则与 Microsoft Exchange 上的规则不匹配&quot;提示的问题。

- 解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。

- 解决了导致非常长的 Outlook 会话出现内存泄漏的问题。

- 解决了在多个窗口中查看同一项目时可能会导致崩溃的问题。

- 解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。

- 解决了导致用户无法打开某些定期日历项目实例的问题。

- 解决了导致 Exchange 2010 服务器上的邮箱用户在将附件添加到日历项目时遇到问题的问题。

- 解决了导致用户在答复数字签名邮件时遇到问题的问题。

- 解决了导致会议中的“位置”字段意外更新的问题。

- 解决了在会议的位置字段中导致逗号变为分号的问题。

- 解决了导致会议位置在清除后意外添加回会议的问题。

- 解决了与巴西时区中设置的会议和约会有关的问题。

- 解决了在关闭辅助功能检查器窗格后按 &quot;S&quot; 键时导致用户看到邮件意外发送的问题。

- 这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。

- 解决了导致 Web 加载项访问数字权限管理邮件的问题。

- 解决了导致用户在配置文件创建过程中遇到崩溃的问题。

- 解决了导致用户在对签名进行重命名时发生崩溃的问题。

### <a name="powerpoint"></a>PowerPoint

- 我们修复了 Shape.Paste 方法的问题：当用户使用 Shape.Paste 方法复制和粘贴形状时，它会将所选内容更改为粘贴的形状。

- 解决了在旧版 PPT 批注中使用上下文菜单时可能导致崩溃的问题。

### <a name="project"></a>Project

- 发现了用户在打开只读项目时可能会收到几则消息的问题。

- 修复了以下问题：固定持续时间类型的 100％ 任务可能会错误地将其完成百分比计算为小于 100％ 完成。

- 修复了有时无法正确计算摘要任务日期的问题。

- 修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。

### <a name="word"></a>Word

- 我们修复了以下问题：在某些情况下，保存现有文件始终会导致显示“另存为”对话框，而该文件从不实际保存。

- 构建基块管理器可能显示无效的警报：&quot;你已更改样式、构建基块&quot;。

### <a name="office-suite"></a>Office 套件

- 此更改解决了某些包含标记的散点图呈现缓慢的问题。

- 此更改解决了所报告的使用 Intel 集成 GPU 的图形适配器的问题。

- 修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。

- 解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。

- 修复了从同一 SharePoint 库在 Word/Excel/PowerPoint 中打开多个文件时，只能打开第一个文件进行策略符合性扫描的问题。

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-february-11"></a>版本 1908：2 月 11 日
*版本 1908（内部版本 11929.20606）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 此更新修复了以下问题：当使用 VBA 向图表的页眉/页脚添加图像时，将会导致出现错误。

- 修复了在打印预览中或打印时分组框控件的边框不可见的问题。

- 用户在使用部分非英文字符集保存更改时可能会出错。

- 修复了以下问题：在保存包含图表的工作簿时，图表标题中的图像文件大小增加。


- 修复了以下问题：在使所选区域与交叉引用的工作簿保持同步时，导致交叉引用工作簿中的 DBCS 字符出现损坏。

- 解决了使用自动调整功能调整行高时复选框控件缩小的问题。


### <a name="outlook"></a>Outlook

- 解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。

- 解决了导致用户在处理冲突消息时遇到同步失败的问题。

- 解决了导致用户在启动 Outlook 时在“正在加载个人资料”屏幕上遇到挂起的问题。

- 解决了导致用户在更改视图时遇到间歇性崩溃的问题。


- 解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到崩溃的问题。 [此处](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是单个 KB，包含针对先前版本记录的问题。

- 解决了一个问题，该问题导致用户在将共享日历文件夹同步到 OST 时遇到问题，这导致他们与这些文件夹进行交互时出现权限错误。


### <a name="powerpoint"></a>PowerPoint

- 改进了复制粘贴方案，即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。


- 修复了导致协作用户之间的效率降低的问题。

- 修复了以下问题：当逐步打开文件时，如果其中一张幻灯片包含多个嵌入式媒体流，则可能会出现问题。

- 我们修复了以下问题：首次启动 PowerPoint 时，不受信任的加载项可能不会显示安全警告消息栏。

### <a name="project"></a>Project

- 修复了以下问题：由于基准日历发生更改时未更新资源日历，时间表与项目计划之间的实际工时可能不同。

### <a name="word"></a>Word

- 通过移出已弃用的 API，修复了 Word 中的崩溃。

### <a name="office-suite"></a>Office 套件

- 此更改解决了打开损坏的文件后正确渲染图像的问题。



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-january-14"></a>版本 1908：1 月 14 日
*版本 1908（内部版本 11929.20562）*

[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a>已解决的问题
### <a name="excel"></a>Excel

- 荷兰语文档标题快捷键提示已更改为 Alt-G。

- 解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。

- 发生问题时，将无法从加载项打开的 WPF （Windows Presentation Foundation）窗体的组合框中选择项目。

### <a name="outlook"></a>Outlook

- 解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。

- 解决了在使用备用发件人时导致无法显示策略提示的问题。

- 解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。

### <a name="powerpoint"></a>PowerPoint

- 我们修复了将一个幻灯片从一个演示文稿复制到另一个演示文稿时，可能创建重复母版的问题。
- 如果在不支持的版本中打开，采用新批注的文件将显示黄色警告

### <a name="office-suite"></a>Office 套件

- 修复了 Office 更新消息以与预期不同的语言显示的问题。 今后，Office 更新消息将正确匹配 Windows 显示语言。

- 解决了以下问题：在某些情况下，如果不是管理员，并且系统帐户没有网络连接，则不会应用更新。


[//]: # (请勿移除错误详细信息内容结尾)

> [!NOTE]
> 如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。