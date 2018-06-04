---
title: 半年通道 （目标） 版本中 2017年发行说明
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: IT 专业人员使用发行说明半年通道 （目标） 版本的 Office 365 proplus 中提供 2017
ms.openlocfilehash: 6014107ae2471707d226602cc71efaa24f1de310
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/04/2018
ms.locfileid: "19555922"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>半年通道 （目标） 版本中 2017年发行说明

这些发行说明提供涉及新功能、 安全更新和非安全更新中 2017年半年通道 （目标） 对 Office 365 ProPlus 的更新中包含的信息。
 
> [!NOTE]
> - 下面还提供了有关新功能、 安全更新和非安全更新的 Visio Pro for Office 365 和 Project Online 桌面客户端。
> - 此信息也适用于 Office 365 企业版，即附带了一些 Office 365 计划，如企业高级版的 Office 的版本。
> - 半年通道 （目标） 是用于之前年 9 月 2017年推迟通道名为第一版。

## <a name="version-1708-december-12"></a>版本 1708年: 12 月 12 日
*版本 1708 （构建 8431.2131）*

 ### <a name="excel-security-updates"></a>Excel： 安全更新
-   [CVE-2017年 11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Microsoft Excel 远程代码执行漏洞

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   解决问题其中用户正确看到"灾难性 failure"错误消息时打开的 Office 2007 或较旧的工作簿 （.xls 或.xla） 与宏。
-   解决问题，从命令行打开工作簿可能导致丢失的富文本格式的单元格中。

### <a name="outlook-security-updates"></a>Outlook： 安全更新
-   [CVE-2017年 11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office 信息泄露漏洞

### <a name="powerpoint-security-updates"></a>PowerPoint： 安全更新
-   [CVE-2017年 11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint 信息泄露漏洞

### <a name="project-non-security-updates"></a>项目： 非安全更新
-   解决问题问题项目级别自定义字段数据可以在获取丢失的保存位置。
-   解决问题，其中失败保存可能会损坏的文件，并导致崩溃在打开的项目。
-   其中打开项目计划崩溃会导致修复问题。

### <a name="word-security-updates"></a>Word： 安全更新
-   [顾问 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office 纵深防御深度更新



## <a name="version-1708-november-14"></a>版本 1708年: 11 月 14 日
*版本 1708 （构建 8431.2110）*

### <a name="access-non-security-updates"></a>Access： 非安全更新
-   解决问题尝试文本框或组合框中选择文本选择所有文本，而不是指示所选内容的显示位置。

### <a name="excel-security-updates"></a>Excel： 安全更新
-   [CVE-2017年 11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel 安全功能绕过漏洞
-   [CVE-2017年 11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel 内存损坏漏洞
-   [CVE-2017年 11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office 内存损坏漏洞

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   解决问题时文件名称包含方括号用户无法关闭受保护的视图中的工作簿的位置。
-   其中，当用户尝试现有工作簿中插入一个对象，Excel 崩溃当用户单击浏览修复问题。
-   解决问题其中 （的文本选项/Text 部分中的设置形状格式窗格） 中选择"调整形状调整宽度"导致不更改该形状。
-   解决问题，其中，通过双击在其上打开工作簿时, 的单元格文本字体和格式不获取加载或两个相同的工作簿打开的单个模板。
-   其中，Excel 启动时创建的第一个工作簿不会关闭时打开或创建新的工作簿修复问题。
-   解决问题拖动时的工具提示的放置位置未对齐或拖动填充。
-   解决问题，使用文件中保存工作簿时\>另存为包含句点的文件名称将显示空白或被截断对话框保存在文件中。
-   其中时保存同步备份文件，则无法写入磁盘，但将文件上载到 OneDrive Office 保留 Office 修复问题。 使用此修复后，用户现在将会看到一条错误消息，然后上载不会继续。
-   由于出错的显卡驱动程序的显示黑色的行和标题的位置与呈现修复问题。
-   修复的问题 Excel 崩溃或无法保存工作簿后会插入一个图表的位置。
-   解决问题分页预览中的页换行不正确的位置。

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题其中用户看到的邮件列表重点跳意外时删除邮件。
-   修复，导致用户交互的附件时，请参阅身份验证提示的问题。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   其中时保存同步备份文件，则无法写入磁盘，但将文件上载到 OneDrive Office 保留 Office 修复问题。 使用此修复后，用户现在将会看到一条错误消息，然后上载不会继续。
-   修复其中编辑和格式文本设置表中撤消之后使崩溃的 PowerPoint 问题。
-   修复其中引用 Flash Player 基于 YouTube 问题中新的窗口打开，若要播放视频嵌入代码的结果。 旧嵌入代码立即升级到引用 HTML5 基于 YouTube 视频，以便它们正确就地播放。

### <a name="word-security-updates"></a>Word： 安全更新
-   [顾问 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office 纵深防御深度更新

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题，其中 Word 崩溃时的用户尝试另存为到 OneDrive for Business 上现有文档执行操作然后取消保存或尝试合并现有的更改。
-   其中时保存同步备份文件，则无法写入磁盘，但将文件上载到 OneDrive Office 保留 Office 修复问题。 使用此修复后，用户现在将会看到一条错误消息，然后上载不会继续。
-   如果同时打开 Word 后，当用户导航到插入选项卡 Word 可以挂起其中修复问题。
-   解决问题，单击边距后字符的显示位置屏幕的左上角时输入字符。

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   [CVE-2017年 11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office 内存损坏漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   修复缩放和缩放动态 DPI 环境下 Office 加载项中的问题。
-   修复问题，其中的 CurrentStatus 节点的 Office 配置服务提供程序 (CSP) 返回一个空字符串，即使当前安装 Office 365 ProPlus。
-   修复，导致.box 文件格式的更改，这将影响较旧版本的 Office 安装在同一计算机上的功能，因为.box 文件共享在同一台计算机上 Office 相关应用程序的所有版本的问题。
-   其中，某些情况下使用共享的计算机激活时，出现错误消息指出应用程序具有遇到阻止了其工作正常和询问用户是否想运行修复的错误修复问题。



## <a name="version-1708-october-10"></a>版本 1708年： 年 10 月 10
*版本 1708 （构建 8431.2107）*

### <a name="access-non-security-updates"></a>Access： 非安全更新
-   如果查询具有与从 Microsoft Dynamics 链接表的主键的联接查询不执行其中修复问题。
-   其中小数位数不显示 Microsoft Dynamics 表中的货币值的情况下解决问题。

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   解决问题，其中 Excel 崩溃时打开。XLL 文件。
-   其中单元格图案样式不正确呈现在页面布局视图中添加页眉或页脚后修复问题。
-   修复问题，其中将数据透视表的副本粘贴到另一个工作簿可能会导致崩溃。
-   解决问题，当您选择替换命令和查找和替换对话框将打开，焦点的对话框中的位置而不是替换选项卡的查找选项卡。
-   解决问题 Excel 其中崩溃时从早于 SharePoint Server 2016 SharePoint 服务器上打开工作簿的活动窗格中打开。
-   解决问题，其中 Excel 打开并显示一个空白窗口时启用一个或多个 XLL 加载项。
-   Excel 其中崩溃具有已关闭工作簿中使用表单按钮后修复问题。
-   其中，当使用 SheetBeforeRightClick 事件，插入相交合并单元格的列不展开合并单元格修复问题。

### <a name="outlook-security-updates"></a>Outlook： 安全更新
-   [CVE-2017年 11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Microsoft Outlook 安全功能绕过漏洞
-   [CVE-2017年 11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Microsoft Outlook 信息泄露漏洞

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题时使用深灰色主题策略提示中的"了解更多"链接，不可见。
-   解决问题其中 Outlook 崩溃时用户尝试设置新帐户和它们不帐户安装完成关闭窗口。
-   解决问题标记为已读和标记为未读其中显示为一组共享的收件箱中的邮件的选项。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   解决问题 PowerPoint 其中崩溃时从 SharePoint server 早于 SharePoint Server 2016 打开演示文稿。

### <a name="word-security-updates"></a>Word： 安全更新
-   [CVE-2017年 11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Microsoft Office 内存损坏漏洞

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题 Word 其中崩溃时从早于 SharePoint Server 2016 SharePoint 服务器上打开文档的活动窗格中打开。

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   [CVE-2017年 11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Microsoft Office 远程代码执行漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   向用户显示联机修复进度不其中修复问题。
-   解决问题其中 Office 文件属性不会显示在文件资源管理器。
-   打开的 Office 外接程序按钮消失从功能区，第二个文档时所在的情况下解决问题。
-   解决问题无法打开具有与双字节字符的名称的一些 VBA 模块的位置。



## <a name="version-1708-september-12"></a>版本 1708年： 年 9 月 12
*版本 1708 （构建 8431.2079）*

### <a name="access-feature-updates"></a>Access： 功能更新
-   **标签名称属性：** 通过将与窗体上控件关联的标签增强辅助功能。
-   **编辑新项是更轻松地访问：** 使用快速的键盘快捷方式 (Ctrl + E) 要编辑新项目从组合框或列表框。
-   **Dynamics 连接器：** 导入或链接到数据存储在 Microsoft Dynamics 中。 [详细信息](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **销售队伍连接器：** 导入或链接到销售队伍中存储的数据。 [详细信息](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel： 功能更新
-   **"从示例添加列"增强功能：** 支持多个日期/时间、 数学、 和索引列的转换。
-   **性能改进：** Excel 打开复杂的工作簿与多个表更快，因此您可以处理大范围的公式，筛选大量行，或复制并粘贴快速。
-   **插入联机图片：** 用于选择图像和归属信息的新登陆页面将自动插入的图像。
-   **Azure 数据湖泊存储连接器：** 用户可以从 Azure 数据湖泊存储现在导入数据。
-   **"示例中的添加列"增强功能：** 支持建议、 更多的日期/时间操作和更多转换。
-   **数据选项卡**: 数据选项卡上的功能区按钮具有已重新排列为两个新的组： 获取和转换数据和查询和连接。
-   **共享查询**： 导出到的 Office 数据库连接 (ODC) 文件，任何查询定义和跨工作簿或与其他人共享它。
-   **加载数据：** 无需将数据保存到数据模型，可将数据查询加载直接到数据透视表或数据透视图。
-   **共享文件活动：** 在右上角的文件以查看文件共享中的 OneDrive for Business 的时选择活动按钮或 SharePoint 已共享、 编辑、 重命名，或还原。
-   **安全的链接：** 当用户单击链接时，Office 365 高级威胁保护 (ATP) 检查以查看是否恶意的链接。 如果链接被确认恶意，则会将用户重定向到而不是原始目标 URL 警告页上。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **增强数据导入功能：** 轻松地导入和形状来自各种源的数据。 管理工作簿查询和与查询和连接的连接侧面窗格中，并通过 ODC 文件与他人共享查询。 [详细信息](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **共享文件中的更改**： 查看谁具有共享工作簿中, 进行更改和还原早期版本。 [详细信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **套索选择与笔按钮：** 使用无访问功能区支持数字笔按钮来套索选择墨迹。

### <a name="excel-security-updates"></a>Excel： 安全更新
-   [CVE-2017年 8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Microsoft Office 内存损坏漏洞

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   其中 Excel 暂时挂起时展开或折叠数据透视表和数据透视表标题移开屏幕修复问题。
-   解决问题，其中选项卡将被忽略时复制和粘贴制表符分隔的文本单词，导致无法解析为列的文本。
-   修复 Excel 其中崩溃时打开发布为网页对话框中的问题。
-   解决问题，其中数据刷新失效或 Excel 崩溃时使用从 SQL Server Analysis Services 服务器的数据和 Excel 的区域设置和 SQL Server Analysis Services 服务器的区域设置不同。
-   解决问题时尝试将更改保存到文档与 OneDrive 客户端同步错误出现的位置。
-   解决问题，无法更改任意位置工作表中字段的筛选区域中，但没有其他任何位置的字段的数据透视表时。

### <a name="outlook-feature-updates"></a>Outlook： 功能更新
-   **辅助功能改进：** 我们已进行更轻松地读取和编辑文本、 表格、 列表和电子邮件中的图像，当您使用的屏幕阅读器时。
-   **新帐户配置：** 设置新帐户需要较少的手动步骤新向导。
-   **链接的附加对话框：** 将连接时使用功能区上的附加文件的链接，您可以选择是否以将其添加为链接还是作为附件。 如果您不希望每次查看此对话框，请转到文件\>选项\>常规并指定希望如何链接附加下"附件选项"。
-   **的内部部署附件的支持：** 从内部部署 SharePoint Server 的文件显示为消息下的最新文件\>附加文件的本地 OneDrive for Business 和 SharePoint 工作组网站显示在附加文件下\>可以将浏览 Web 位置和本地文件上载到内部部署的 OneDrive for Business 站点。
-   **组业务分类：** 创建或编辑组时，可指定由租户管理员，例如 2 私有 3 机密，定义业务分类级别和组页眉中显示该分类。
-   **来宾访问到 Office 365 组：** 通过向其授予访问组对话、 文件、 日历邀请和组笔记本与组织外部的人员进行协作。 [详细信息](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **可操作的消息：** 开发人员可以创建可轻松用户可以直接从 Outlook 采取简单或快速操作，而无需切换到一个外部网站或单独的应用程序的邮件。 [详细信息](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook： 安全更新
-   [CVE-2017年 8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook 安全功能绕过漏洞
-   [CVE-2017年 8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook 信息泄露漏洞
-   [CVE-2017年 8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook 内存损坏漏洞

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题，您无法在 Outlook 中配置 IMAP 帐户。
-   修复，导致间歇性故障，打开 Outlook 时的问题。

### <a name="powerpoint-feature-updates"></a>PowerPoint： 功能更新
-   **插入联机图片：** 用于选择图像和归属信息的新登陆页面将自动插入的图像。
-   **关闭视频标题：** 将关闭的标题添加到视频以使其更轻松地访问。 [详细信息](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **旁白录制：** 包括您自己旁白进行演示文稿的录音时的视频。 录制可以包括动画、 墨迹、 音频和视频。
-   **共享文件活动：** 在右上角的文件以查看文件共享中的 OneDrive for Business 的时选择活动按钮或 SharePoint 已共享、 编辑、 重命名，或还原。
-   **替换文字创建：** 基于云的服务会自动生成演示文稿中的图片的可选文字。
-   **安全的链接：** 当用户单击链接时，Office 365 高级威胁保护 (ATP) 检查以查看是否恶意的链接。 如果链接被确认恶意，则会将用户重定向到而不是原始目标 URL 警告页上。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **设计器改进：** 建议专业设计想法面向操作的列表。
-   **共享文件中的更改：** 查看谁具有共享演示文稿中进行更改和还原早期版本。 [详细信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint： 安全更新
-   [CVE-2017年 8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): PowerPoint 远程代码执行漏洞
-   [CVE-2017年 8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): PowerPoint 远程代码执行漏洞

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   解决问题链接到字体的最终用户定义字符 (EUDCs) 无法显示。

### <a name="project-non-security-updates"></a>项目： 非安全更新
-   解决问题其中从 Project Online 中打开某些文件会崩溃的项目。
-   修复其中实际开始时间可能会错误地清除设置剩余工时时的问题。
-   解决问题比报告了通过 Project Web App 中的进展状况的资源分配实际开始日期可能会显示不同的数据的位置。
-   如果更改任务的完成日期，则可能会重排实际工时修复问题。
-   修复其中复制和粘贴 cost 字段，粘贴的值可能不完全匹配由于舍入问题复制的值的问题。
-   解决问题预算资源按时间分段数据不复制到另一个保存从一个比较基准时的位置。
-   解决问题，其中状态字段不总是能正确进行计算的摘要任务。
-   解决问题其中实际工时错误地获取转接到企业资源时它会替换本地资源和启用受保护的工作。
-   修复项目其中崩溃如果您有一个表，其中第一列为任务名称、 列被锁定，并在任务上单击问题。
-   解决问题，您可以将分配相同的资源多次到通过任务分配状况视图相同的任务。
-   解决问题其中中数字自定义域的值时可能会丢失打开 XML 文件。
-   解决问题其中首要任务缩进不正确从项目到同步 SharePoint 任务列表。
-   解决问题，如果您从导入任务、 资源或工作分配信息 Excel 工作簿，工时域中的值可能会忽略。
-   修复其中按时间分段比较基准值不匹配的初始值，将项目保存到 XML 文件格式时的问题。
-   解决问题 Project 客户端不会打开其中项目它认为该项目已签出时它实际上不会因为。
-   解决问题，以便打开项目文件从文件服务器的高延迟打开更快。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 安全更新
-   [CVE-2017年 8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Windows GDI + 信息泄露漏洞
-   [CVE-2017年 8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695)： 图形组件信息泄露漏洞
-   [CVE-2017年 8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Microsoft 图形组件远程代码执行

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   添加对话框解释为什么用户将无法加入会议，阻止特定端口或 Ip 不白名单时。
-   修复其中永久聊天室中的未读的邮件标记为已读单击 IM 对话选项卡时的问题。
-   解决问题其中传入 IM toast 体验几秒的延迟。
-   修复其中 AD 联系人显示为电话号码而不是联系人的姓名时禁用与 Exchange 同步问题。
-   其中阻止匿名加入用户加入时禁用联盟和匿名加入由会议组织者不明确阻止修复问题。
-   解决问题到会议组织者的会议超出该限制的正确显示被邀请者的个数。
-   其中电话号码不显示在上入站 PSTN 呼叫的 toast 修复问题。
-   其中时重命名联系人列表组时使用 Delete 键，, 将删除整个组修复问题。
-   其中将 IM 对话中的共享通知消除共享停止之前修复问题。
-   在登录屏幕上为空的一些非英语语言修复问题。
-   其中聊天和聊天历史记录中的非英语字符乱码修复问题。
-   显示呼叫者的电话号码的传入呼叫处理由组织的自动助理，如果不已知用户的名称。
-   添加的"这些人不需要在会议厅等待。"允许"任何人 （无限制）"选项的限制种带内设置
-   添加在 VDIv2 能够打开或关闭自助式视频的 P2P 视频呼叫。
-   解决问题重复的数字的呼叫下拉列表菜单中的联系人的显示位置。
-   修复代理人的 Skype for Business 和 Skype 的业务基本之间移动的用户的删除其中的问题。
-   解决问题，其中显示为脱机不可见时使用启用显示为脱机和自定义状态 URL 客户端策略。
-   加宽加入会议按钮以修复截断的某些本地化语言。
-   增加聊天中的重要性-高邮件突出部分。
-   将 Office 和 Skype 业务文件扩展名类型添加到允许的文件传输 blocklists。
-   在非英语中设置的会议页脚文本的 Outlook 会议邀请中的本地化更正。
-   修复问题，其中可以切换发件人名称的多个用户的对话中。
-   修复空白的对话窗口未能成功加入会议之前会出现问题。
-   解决问题标题字段是否为空的联系人卡片中的部门字段信息其中为空搜索结果中。
-   有关用户从内部部署迁移到 online 由于防火墙规则，请修复登录失败。
-   添加一个新的 DWORD 注册表项，若要解决问题，其中，当用户登录到执行 LyncAutoD 外部网络上的客户端，客户端将重置 OAuthUsed 注册表项为 false。 若要解决该问题，将值设置为 1 下 HKEY EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket\_当前\_用户\\软件\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio： 功能更新
-   **进行从 Excel 数据的图表：** 自动创建基本流程图或跨职能流程图的 Excel 数据使用新数据可视化工具模板。 [详细信息](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **安全的链接：** 当用户单击链接时，Office 365 高级威胁保护 (ATP) 检查以查看是否恶意的链接。 如果链接被确认恶意，则会将用户重定向到而不是原始目标 URL 警告页上。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio： 非安全更新
-   修复其中 COM 加载项未收到文档打开事件 Visio 文件打开通过文件图标或文件名上双击时的问题。

### <a name="word-feature-updates"></a>Word： 功能更新
-   **插入联机图片：** 用于选择图像和归属信息的新登陆页面将自动插入的图像。
-   **替换文字创建：** 基于云的服务会自动生成文档中的图片的替代文本 （alt 文本）。
-   **共享文件活动：** 在右上角的文件以查看文件共享中的 OneDrive for Business 的时选择活动按钮或 SharePoint 已共享、 编辑、 重命名，或还原。
-   **安全的链接：** 当用户单击链接时，Office 365 高级威胁保护 (ATP) 检查以查看是否恶意的链接。 如果链接被确认恶意，则会将用户重定向到而不是原始目标 URL 警告页上。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **共享文件中的更改：** 查看谁具有共享文档中进行更改并还原早期版本。 [详细信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题 Word 其中意外关闭时加载 Grammarly 加载项。
-   其中，某些情况下的 Word 崩溃时要恢复的基于云的文件尝试修复问题。
-   其中不能旋转形状在绘图画布修复问题。
-   解决问题中，键入在朝鲜语时, 辅音和元音不正确的分隔开。
-   将文档保存为 pdf 格式将文档保存为版本 1.7 PDF。

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   [CVE-2017年 8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Microsoft Office 内存损坏漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   修复问题阻止什么是从出现的新建对话框。
-   其中绘制选项卡上单击使应用程序崩溃为一些用户修复问题。
-   解决问题其中悬停在公共控件具有对其的工具提示导致应用程序崩溃。
-   解决问题时使用公共控件，其中出现许可错误消息。
-   修复问题如何签署某些程序文件、 导致防病毒程序来标记这些文件以及保护的问题或访问数据下 Windows 信息保护 (WIP)。
-   添加 support.to 允许用户在 64 位版本的 Office 以打开宏文件包含 mscomctl.ocx 控件中工作。
-   提高 mscomctl.ocx 中使用的控件的辅助功能。
-   解决问题命令的功能区或快速访问工具栏自定义对话框中缺少的位置。



## <a name="version-1705-august-8"></a>版本 1705年： 年 8 月 8
*版本 1705 （构建 8201.2171）*

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   与拖动 scrollbar 的邮件的列表中移动修复问题。

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   修复问题如何签署某些程序文件、 导致防病毒程序来标记这些文件以及保护的问题或访问数据下 Windows 信息保护 (WIP)。
-   修复问题阻止什么是从出现的新建对话框。



## <a name="version-1705-july-27"></a>版本 1705年: 7 月 27 日
*版本 1705 （构建 8201.2158）*

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   解决问题时尝试将更改保存到文档与 OneDrive 客户端同步错误出现的位置。
-   解决问题，其中 Excel 崩溃时将工作表数据添加到数据模型和高对比度主题设置为黑色。

### <a name="outlook-security-updates"></a>Outlook： 安全更新
-   [CVE-2017年 8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook 安全功能绕过漏洞
-   [CVE-2017年 8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook 信息泄露漏洞
-   [CVE-2017年 8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook 内存损坏漏洞

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   修复问题，其中将形状添加另一个用户更改布局后使合并失败。

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题中，键入在朝鲜语时, 辅音和元音不正确的分隔开。
-   其中信封上的收信人地址太近打印到的左边缘修复问题。



## <a name="version-1705-july-13"></a>版本 1705年： 年 7 月 13
*版本 1705 （构建 8201.2136）*

### <a name="excel-security-updates"></a>Excel： 安全更新
-   [CVE-2017年 8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office 内存损坏漏洞

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   Excel 工作簿包含外部链接的崩溃其中修复问题。
-   解决问题其中粘贴 Excel 至 Word 单元格显示零单元格中，即使未选择"零具有零值的单元格中的 Show"设置。

### <a name="project-non-security-updates"></a>项目： 非安全更新
-   解决问题所选图表/表的值不会显示在图表中的表窗格。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   解决问题，其中对话窗口不会显示在后台加入会议时，并向用户显示音频设备加入对话框。
-   解决问题其中从 Outlook 会议链接并不总是传递内部 URI 正确。
-   加宽加入会议按钮以修复截断的某些本地化语言。

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   表无法正确显示某些操作后修复问题。
-   解决问题，多个编辑引文一些时间显示设置为单个撤消操作而不是连续的单个操作。
-   其中某些操作后禁用撤消修复问题。
-   解决问题，以防止可能会丢失数据后某些撤消操作。

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   [CVE-2017年 8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office 远程代码执行漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   修复问题导致的 Office 2013 的无人参与的升级到 Office 2016 失败时使用 System Center Configuration Manager。
-   旧外接程序部署从通过公司目录存储区不加载其中修复问题。



## <a name="version-1705-june-13"></a>1705 的版本： 6 月 13 日
*版本 1705 （构建 8201.2102）*

### <a name="access-feature-updates"></a>Access： 功能更新
-   **什么是新的对话框：** 访问新的功能与更新后打开 Access 时，将出现一个对话框，重点介绍新访问功能。 对话框中，还可通过转到文件\>帐户\>What's New。
-   **大量 (bigint) 支持：** 使用 Access 表中的大量数据类型可计算大量，并可链接到或从使用等效的数据类型，如 bigint SQL Server 中的外部数据库导入。 [详细信息](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel： 功能更新
-   **Windows 信息保护 (WIP) 支持：**  Excel 现启发式应用程序，并可以区分公司和个人数据，正确确定用于保护，基于已配置的策略。  [详细信息](https://aka.ms/wiptechnet)
-   **获取和变换改善：** 在查询编辑器中，通过提供示例值创建一个新列。 键入时，Excel 会检测所需的转换，并显示新列的预览。
-   **插入新的链接：** 轻松地将超链接附加到新的基于云的文件或网站，并创建的人员使用屏幕阅读器的有意义的显示名称。 [详细信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **进行个性化设置的默认数据透视表布局：** 设置数据透视表的方式，并且每次创建新的数据透视表开头的布局。 [详细信息](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **获取和变换改进：** 用户可以通过示例创建新的列和拆分成的行的表格列。 指定参数到 SAP HANA 和分组数据现更轻松。
-   **集中式外接程序部署**： 管理员可以部署和从 Office 365 管理中心更新为用户或组的加载项。 [详细信息](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **快速访问工具栏自定义项：** 下标和上标图标可以添加到快速访问工具栏。
-   **获取和变换改进：** 自动检测的分隔符字符时拆分列，使用查询编辑器中，选择用于将二进制文件的示例文件并指定要连接到使用 DB2 连接器时的程序包集合。
-   **迪拜字体：** 支持西欧语言以及使用阿拉伯语脚本的主要语言的字体系列。 [详细信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景删除：** 删除图片背景自由格式绘图工具。
-   **获取和变换改进：** 在导航器对话框的"选择相关表"使用 ODCB 和 OLEDB 连接器、 合并多个文件直接从文件夹数据预览对话框中，并使用查询编辑器窗口中新的上下文菜单选项现有查询中插入新的步骤。
-   **使用笔选择并更改对象：** 获取对象与要调整大小、 旋转、 移动、 数字笔等的句柄。
-   **映射图表：** 比较的值，并显示跨不同地理区域的类别。 [详细信息](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **SVG 图像：** 插入和编辑工作簿中的可缩放的向量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：** 转到插入来自标准的可缩放的向量图形 (SVG) 文件库使用图标\>的示意图，介绍\>图标。 [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **将保存到最近的文件夹：** 将工作簿保存到最近使用过文件夹中，当您转到文件时，使用最近选项卡\>另存为。
-   **辅助功能改进：** 使用键盘，讲述人和其他辅助技术来读取和编辑工作簿的改进的支持。 [详细信息](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel： 安全更新
-   Microsoft 安全公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office (3217868) 的安全更新

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   解决问题 Excel 不在其中设置以编程方式应用程序在 Excel 2010 或更早版本创建的工作簿时的工作表保护密码。
-   修复其中合并和中心不起作用组合的工作表中的问题。
-   例如引入 Office 2016-发行后的新功能、 TEXTJOIN、 CONCAT、 IFS、 MAXIFS 和 MINIFS-何处缺少修复问题。
-   解决问题 Excel 其中崩溃时用户试图应用单元格级别权限。
-   解决问题，其中的大型文件保存到 OneDrive for Business 导致文件被锁定，用户无法编辑该文件，直到用户关闭并重新打开 Excel。
-   修复其中一个新窗口显示处于灰显状态的.xls 工作簿打开时的问题。
-   其中，Excel 可能崩溃时插入超链接修复问题。
-   其中，Excel 可能会失败时添加 XML 映射修复问题。
-   其中外, 接程序的命令按钮不起作用升级外接程序后或之后删除和外接程序再次下载从 Office 商店修复问题。
-   修复其中 Excel 可能会崩溃，崩溃操作通过 VBA DLL 表时出现问题。
-   解决问题 Excel 其中崩溃时选择图表工作表上的窗体控件组合框。

### <a name="onenote-feature-updates"></a>OneNote： 功能更新
-   **Windows 信息保护 (WIP) 支持：** OneNote 现启发式应用程序，并可以区分公司和个人数据，正确确定用于保护，基于已配置的策略。 [详细信息](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote： 非安全更新
-   修复其中 OneNote 画布隐藏内容或更新多个段落在视图中时的问题。

### <a name="outlook-feature-updates"></a>Outlook： 功能更新
-   **Windows 信息保护 (WIP) 支持：**  Outlook 现启发式应用程序，并可以区分公司和个人数据，正确确定用于保护，基于已配置的策略。  [详细信息](https://aka.ms/wiptechnet)
-   **插入新的链接：** 将超链接附加到新的基于云的文件或网站，并创建的人员使用屏幕阅读器的有意义的显示名称。 [详细信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **迪拜字体：** 支持西欧语言以及使用阿拉伯语脚本的主要语言的字体系列。 [详细信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景删除：** 删除图片背景自由格式绘图工具。
-   **检查共享文件具有访问权限：** Outlook 告诉提前用户，如果收件人可能无法访问附加的 OneDrive 或 SharePoint 文件，并建议如何解决此问题。
-   **对附件设置权限：** 对于 OneDrive 或 SharePoint 附件，用户可以设置是否收件人在组织中或外部，具有读取或编辑权限对附件。
-   **可固定 taskpane:** 在邮箱中的邮件之间切换时，保持外接程序 taskpane 打开。 [详细信息](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **SVG 图像：** 插入和编辑在电子邮件中的可缩放的向量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：** 转到插入来自标准的可缩放的向量图形 (SVG) 文件库使用图标\>的示意图，介绍\>图标。  [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook： 安全更新
-   [CVE 2017:](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook 远程代码执行漏洞
-   [CVE-2017年 0204年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Microsoft Office 安全功能绕过漏洞
-   [CVE-2017年 8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): Microsoft Office 远程代码执行
-   [CVE-2017年 8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): Microsoft Office 安全功能绕过漏洞

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题的计算机内存不足时，Outlook 导航窗格其中停止其中的呈现。
-   附件宽度以可视方式扩展，以容纳文件名和权限信息。
-   解决问题，用户不能在其中搜索 PST 文件。
-   解决问题，其中用户看到新"Microsoft Exchange"类型存储在"新建 Outlook 数据文件"对话框中，并选择此新的数据类型导致用户配置变得不可用。
-   修复其中一条消息中的图像发送从计算机使用高 DPI 时灰显问题。

### <a name="powerpoint-feature-updates"></a>PowerPoint： 功能更新
-   **Windows 信息保护 (WIP) 支持：**  PowerPoint 现启发式应用程序，并可以区分公司和个人数据，正确确定用于保护，基于已配置的策略。  [详细信息](https://aka.ms/wiptechnet)
-   **插入新的链接：** 将超链接附加到新的基于云的文件或网站，并创建的人员使用屏幕阅读器的有意义的显示名称。 [详细信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **集中式外接程序部署**： 管理员可以部署和从 Office 365 管理中心更新为用户或组的加载项。 [详细信息](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **迪拜字体：** 支持西欧语言以及使用阿拉伯语脚本的主要语言的字体系列。 [详细信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景删除：** 删除图片背景自由格式绘图工具。
-   **SVG 图像：** 插入和编辑演示文稿中的可缩放的向量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：** 转到插入来自标准的可缩放的向量图形 (SVG) 文件库使用图标\>的示意图，介绍\>图标。 [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **当共同创作的实时键入：** 请参阅其中其他人使用的演示文稿和视图更改在键入时。 [详细信息](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **将保存到最近的文件夹：** 当您转到文件时，使用最近选项卡到最近使用的文件夹中保存演示文稿\>另存为。
-   **创建精确墨迹形状：** 拖动段橡皮擦删除多余位墨迹，从右到最接近的行为止。
-   **选择和使用笔处理对象：** 使用数字笔移动、 调整大小或旋转对象使用其图柄，或使用支持的笔按钮来套索选择墨迹。
-   **辅助功能改进：** 使用键盘，讲述人和其他辅助技术来读取和编辑演示文稿的改进的支持。 [详细信息](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   PowerPoint 其中崩溃时用户在设计想法窗格中的计算机上未安装 mfplat.dll 文件修复问题。
-   其中外, 接程序的命令按钮不起作用升级外接程序后或之后删除和外接程序再次下载从 Office 商店修复问题。

### <a name="project-feature-updates"></a>项目： 功能更新
-   **设置前置任务的快速下拉：** 使用甘特图下拉列表选择哪些前置任务或想要链接到任务的后续任务。
-   **任务摘要名称：** 显示任务的摘要任务的名称的只读的任务域。  

### <a name="project-non-security-updates"></a>项目： 非安全更新
-   修复创建项目网站对话框中显示网站的正确位置，既然 Project Online 中每个企业项目模板 (EPT) 将具有自己的项目网站的 URL。
-   解决问题，其中保存提示之前会触发 VBA BeforeClose 事件和您无需确定保存的用户的响应的编程方法提示。
-   解决问题其中实际完成百分比不能上卷正确的项目状态日期后开始的任务。
-   解决问题的成本和资源分配给相同的任务后，您可能不能更改任务状态管理器。
-   其中某些项目，调配整个项目会使您在无限循环中修复问题。
-   修复的问题，其中任务开始日期和完成日期不同步到 SharePoint 任务列表正确如果您有某些西班牙语的区域设置。
-   解决问题，如果启动从 Project 客户端的状态审批过程，它可能永远无法完成，留下中不可用状态的项目。
-   其中打印预览不布局任务名称正确如果您具有中文和英文单词修复问题。
-   解决问题其中为单个形状复制到 PowerPoint 的日程表操作不起作用。
-   解决问题"项目间链接"对话框意外显示值"找不到文件。"
-   问题您收到不一致结果分配资源 0 的最大单位时的修补程序。
-   解决问题，其中任务的开始日期获取时重置为尽快删除工作分配的开始日期，忽略等前置任务，这会导致前导拆分工作分配。
-   解决问题，如果您在通过最近菜单从 SharePoint 打开的文件，该项目自动签出给您即使"需要签出之前可以编辑文档？"的设置 已启用。
-   解决问题，如果您直接转到的项目配置文件应用程序，则项目崩溃。
-   修复其中手动计划的任务更新不正确的用户从 Project 2013 升级的问题。
-   其中时打开项目从 SharePoint 任务列表，项目可能会崩溃，项目启动任务同步过程修复问题。
-   其中项目有时崩溃时转到建立工作组修复问题。
-   解决问题时保存项目比较基准信息其中会丢失。
-   解决问题打印输出何处阅读大型项目计划变得比较困难。
-   解决问题其中编辑 Project Web App 中的项目不显示公式字段的正确值。
-   解决问题其中资源企业自定义域的信息未正确保存的项目计划。
-   解决问题，更新任务的 %工时完成的信息更新任务的 %完整信息。
-   修复其中的项目的所有权更改保存项目时的问题。
-   摘要任务不正确地计算 CPI 其中修复问题。
-   解决问题，其中复制并粘贴任务可延伸的比较基准数据，数据将会保存，即使不允许用户保存受保护的比较基准数据。
-   解决问题将数据从 Excel 导入其中导致不正确的日期任务和工作分配的信息。
-   其中，打开报告后, 项目崩溃时关闭修复问题。
-   解决问题其中项目工作时停止保存项目的自定义列表其中包含验证设置。
-   解决问题其中输入"\>"在测试列在筛选器定义对话框中的字符不正确解释为含义"is greater than。"
-   相对于"比较基准计划。"进度线的显示与修复问题
-   解决问题时自定义筛选器字段名称下拉列表不显示的位置。
-   解决问题条形图样式预览不显示条形图样式对话框中的位置。

### <a name="publisher-non-security-updates"></a>Publisher： 非安全更新
-   解决问题其中 Publisher 才会显示 CMYK TIF 图像。

### <a name="skype-for-business-feature-updates"></a>Skype for Business： 功能更新
-   **插入的链接：** 将链接添加到 IM 和组聊天提供友好的文本，而不是完整的 URL 的链接。
-   **屏幕共享通知：** 当您正在共享屏幕 IM 对话中时，或者在屏幕共享继续在您离开会议后，在对话窗口中显示通知。 通知提醒您在您仍共享您的屏幕，并可以轻松要停止共享使用的"停止共享"按钮。
-   **Windows 信息保护 (WIP) 支持：** 作为 WIP 工作仅应用程序现在支持 for Business 的 Skype。  通过将 Skype 添加到允许应用程序列表中，它指示到 Windows 它并不处理个人数据。  Windows 将代表 for Business 的 Skype 保护数据。  [详细信息](https://aka.ms/wiptechnet)
-   **密码重置选项：** 用户无法至少一次登录时，重置按钮链接将出现在登录窗口。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 安全更新
-   Microsoft 安全公告[MS17 013](https://technet.microsoft.com/library/security/ms17-013): Microsoft 图形组件 (4013075) 的安全更新
-   [CVE-2017年 0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 0283年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): Windows Uniscribe 远程代码执行漏洞
-   [CVE-2017年 8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550)： 业务远程代码执行漏洞的 Skype

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   更改与策略禁用从"无法完成呼叫"到"不能调用因为 IT 管理员具有受限音频音频尝试呼叫用户消息。 转为尝试使用即时消息或电子邮件和提出要检查其 IT 管理员"。
-   添加"忘记了您的电话拨入 PIN"超链接到会议邀请的启用 PSTN 会议用户的 Skype 业务 online。
-   从 Skype 团队与会启用业务联机。
-   更改默认扬声器会话音量从 40%到 75%。
-   允许调整为较小的最小宽度选项卡列表的大小。
-   更新快捷键匹配选项卡的顺序。
-   从移动设备发送时，请修复不正确的希伯来语的文本的方向。
-   解说由屏幕阅读器存在桌面/授予控制权功能的信息解决问题。
-   除了选择会议室列表中的已关注聊天室显示打开聊天室。
-   添加功能时启用自定义 RCC 应用程序禁用 VoIP 功能。
-   更改脱机 IM 标志行以"尝试 Skype 业务移动应用程序"。
-   修复问题导致的自动接受的对话，而不是作为普通窗口中，打开对话窗口最小化，并意外离开其他窗口获得焦点。
-   在 Skype 会议选项对话框上使用屏幕阅读器修复问题。
-   解决问题其中邀请中的第一条不错过的对话电子邮件中所示。
-   解决问题从 Outlook 中使用新建 Skype 会议按钮创建会议邀请时显示重复的电话拨入式号码的位置。
-   解决问题时显示滚动条，IM 历史记录中的所有对话不都选中了时使用 Ctrl + A 选择全部。
-   修复其中输出文本可能不是相同的确切格式的使用 Export-csarchivingdata cmdlet 时的问题。
-   解决问题，会议组织者不能与 3 个或多个参与者使用立即开会时，请参阅远程参与者的视频。
-   解决问题在会议名单中的第一行为空的当用户右键单击参与者列表中的另一个用户的名称。
-   解决问题，用户将无法登录时内部和外部的企业网络之间进行切换。
-   修复其中的聊天区域不会关闭时从 IM 自发升级到音频咨询转接问题。
-   其中名称的两个终结点同时响铃使用时被截断吐司通知的情况下解决问题。
-   解决问题中文件共享通知其中被截断文件名。
-   将工具提示后添加到呼叫和转接按钮。
-   请在咨询转接窗口中供屏幕阅读器，如讲述人保持所用的时间。
-   添加作为咨询转接默认首选项中选择 IM 或呼叫的功能。
-   执行咨询转接，请右键单击"转接"按钮以查看联系人的电话号码的列表时，请添加的功能。
-   提高常规错误消息，以使其清除的问题是用户具有无效的许可证或尚未分配许可证。
-   解决问题并不是所有联系人的都显示位置中的对话窗口标题时用户与联系人开始对话，然后添加另一个联系人。
-   解决问题讲述人不在其中读取通知的第一行。
-   解决问题其中呼叫转移到 VOIP 而非顾问的号码。
-   解决问题时用户的定位内容的窗口中，讲述人其中宣布不正确的信息。
-   解决问题的创建者和修饰符名称不显示悬停在白板上批注时的位置

### <a name="visio-feature-updates"></a>Visio： 功能更新
-   **查找第三方模具：** 搜索由所选内容的提供程序提供的第三方模具。
-   **幻灯片代码段：** 代码段的 Visio 绘图并将其导出为向 PowerPoint 幻灯片。 [详细信息](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word： 功能更新
-   **Windows 信息保护 (WIP) 支持：**  Word 现启发式应用程序，并可以区分公司和个人数据，正确确定用于保护，基于已配置的策略。  [详细信息](https://aka.ms/wiptechnet)
-   **插入新的链接：** 将超链接附加到新的基于云的文件或网站，并创建的人员使用屏幕阅读器的有意义的显示名称。 [详细信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **集中式外接程序部署**： 管理员可以部署和从 Office 365 管理中心更新为用户或组的加载项。  [详细信息](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **迪拜字体：** 支持西欧语言以及使用阿拉伯语脚本的主要语言的字体系列。 [详细信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景删除：** 删除图片背景自由格式绘图工具。
-   **两侧：** 通过类似的纸张堆栈的左到右滑动导航页面视图中的页面。 [详细信息](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **使用笔选择并更改对象：** 获取对象与要调整大小、 旋转、 移动、 数字笔等的句柄。
-   **SVG 图像：** 插入和编辑文档中的可缩放的向量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：** 转到插入来自标准的可缩放的向量图形 (SVG) 文件库使用图标\>的示意图，介绍\>图标。  [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **将保存到最近的文件夹：** 当您转到文件时，使用最近选项卡将文档保存到最近使用过文件夹\>另存为。
-   **改进阅读学习工具：** 读取模式提升读取技能通过调整间距的文本中的新命令，显示音节，之间的分隔符和突出显示每个 word 文档作为将朗读。 [详细信息](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **形状识别：** 使用绘制自动转换为形状绘图\>转换形状。 [详细信息](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word： 安全更新
-   Microsoft 安全公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office (3217868) 的安全更新
-   [CVE-2017年 0254年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 0292年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): Windows PDF 远程代码执行漏洞 
-   [CVE-2017年 8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): Microsoft Office 远程代码执行漏洞  

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题，用户不能在其中搜索 PST 文件。
-   解决问题，其中用户看到新"Microsoft Exchange"类型存储在"新建 Outlook 数据文件"对话框中，并选择此新的数据类型导致用户配置变得不可用。

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   [CVE-2017年 0199年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/写字板远程代码执行漏洞 w/Windows API
-   [CVE-2017年 0260年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): Microsoft Office 远程代码执行
-   [CVE-2017年 0261年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 0262年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): Microsoft Office 远程代码执行漏洞



## <a name="version-1701-may-9"></a>版本 1701年： 年 5 月 9
*版本 1701 （构建 7766.2084）*

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   修复，导致间歇性查看跳意外时删除邮件消息列表中的邮件选定内容的用户的问题。
-   修复，导致间歇性故障数的问题。
-   添加 HKEY\_当前\_用户\\软件\\Microsoft\\Office\\16.0\\Outlook\\选项\\常规\\允许管理员可以隐藏支持 DisableSupportBackstage 注册表项在文件选项卡下的选项。
-   添加 HKEY\_当前\_用户\\软件\\Microsoft\\Office\\16.0\\Outlook\\选项\\常规\\允许管理员关闭 DisableOutlookFeedbackFeatures 注册表项在文件下的"outlook 2016 Feedback"和"Outlook 博客"选项\>的反馈。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 安全更新
-   [CVE-2017年 0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 远程代码执行漏洞

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   修复问题导致的自动接受的对话，而不是作为普通窗口中，打开对话窗口最小化，并意外离开其他窗口获得焦点。

### <a name="word-security-updates"></a>Word： 安全更新
-   [CVE-2017年 0254年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office 内存损坏漏洞
-   [CVE-2017年 0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 远程代码执行漏洞

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   [CVE-2017年 0261年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 0262年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office 远程代码执行漏洞
-   [CVE-2017年 0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 远程代码执行漏洞



## <a name="version-1701-april-11"></a>版本 1701年： 年 4 月 11
*版本 1701 （构建 7766.2076）*

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   修复其中一个新窗口显示处于灰显状态的.xls 工作簿打开时的问题。

### <a name="outlook-security-updates"></a>Outlook： 安全更新
-   [CVE 2017:](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook 远程代码执行漏洞
-   [CVE-2017年 0204年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Microsoft Office 安全功能绕过漏洞

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题，其中用户看到新"Microsoft Exchange"类型存储在"新建 Outlook 数据文件"对话框中，并选择此新的数据类型导致用户配置变得不可用。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   解决问题映像缺少错误发生时用户执行"另存为"到 PowerPoint 文件存储在可移动媒体，如 USB 缩略图驱动器上的备用位置。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   解决问题，用户将无法登录时内部和外部的企业网络之间进行切换。

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   [CVE-2017年 0199年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/写字板远程代码执行漏洞 w/Windows API



## <a name="version-1701-march-14"></a>版本 1701年： 年 3 月 14
*版本 1701 （构建 7766.2071）*

### <a name="access-non-security-updates"></a>Access： 非安全更新
-   解决问题无法取消弹出菜单的位置。

### <a name="excel-security-updates"></a>Excel： 安全更新
-   Microsoft 安全公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office (3217868) 的安全更新

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   其中，Excel 可能崩溃时插入超链接修复问题。
-   其中，Excel 可能会失败时添加 XML 映射修复问题。
-   其中外, 接程序的命令按钮不起作用升级外接程序后或之后删除和外接程序再次下载从 Office 商店修复问题。
-   修复其中 Excel 可能会崩溃，崩溃操作通过 VBA DLL 表时出现问题。

### <a name="onenote-non-security-updates"></a>OneNote： 非安全更新
-   OneNote 页面画布其中停止响应后进行身份验证使用 PIN Windows 10 版本 1607 （也称为 Windows 周年日更新） 上的鼠标单击修复问题。
-   当用户插入一个可编辑的文档，如.docx 或.pptx 时，禁用优化 EDU 特定打印输出的行为。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   解决问题合并冲突错误时出现的位置的共同创作。
-   其中外, 接程序的命令按钮不起作用升级外接程序后或之后删除和外接程序再次下载从 Office 商店修复问题。
-   解决问题其中 VBA 调用对象模型将导致运行时错误时应用于图表中的形状。

### <a name="publisher-non-security-updates"></a>Publisher： 非安全更新
-   解决问题其中 Publisher 才会显示 CMYK TIF 图像。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 安全更新
-   Microsoft 安全公告[MS17 013](https://technet.microsoft.com/library/security/ms17-013): Microsoft 图形组件 (4013075) 的安全更新

### <a name="word-security-updates"></a>Word： 安全更新
-   Microsoft 安全公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office (3217868) 的安全更新

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   使用某些监视器配置时，请使用内存消耗修复问题。
-   其中外, 接程序的命令按钮不起作用升级外接程序后或之后删除和外接程序再次下载从 Office 商店修复问题。



## <a name="version-1701-february-22"></a>版本 1701年: 2 月 22 日
*版本 1701 （构建 7766.2060）*

### <a name="excel-feature-updates"></a>Excel： 功能更新
-   **数据转换和连接的增强功能：** 具有值，之间分隔符的新文本列到展开列表并指定故障转移选项，连接到 SQL 时。
-   **数据转换和连接的增强功能：** 现在支持百分比数据类型，并二进制组合函数创作体验已得到增强。
-   **OLEDB 连接器：** 使用 Get 转换中的 OLEDB 连接器来创建查询通过指定连接字符串和 （可选） 的 SQL 语句，以执行导入数据。
-   **墨迹重播：** 转到绘制\>墨迹重播重播手写向前和向后隐藏和显示内容，提供分步说明，或更好地了解他人的想法的流。 [详细信息](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **CSV (utf-8) 支持：** 打开和保存使用 utf-8 字符编码的 CSV 文件。
-   **数据转换和连接增强功能：** 选择要导入相关的表时加载数据从 OData 源与值来自函数计算，添加自定义列或显示查询使用专用的视图之间的依赖关系。
-   **与我共享：** 查看其他人通过转到文件共享与您的文档\>打开\>共享与 me。 [详细信息](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **更改颜色：** 使用告诉我设置字体、 突出显示、 形状填充和更多的颜色。 [详细信息](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel： 安全更新
-   Microsoft 安全公告[MS16 148](https://technet.microsoft.com/library/security/ms16-148): Microsoft Office (3204068) 的安全更新

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   其中，当 Office 主题设置为黑色，"意外错误"时出现错误消息右键单击工作簿查询窗格中的查询修复问题。
-   解决问题 Excel 其中崩溃时用户尝试访问数据透视表选项。
-   其中具有文本和双引号括起来的单元格值不另存为 CSV 或 CSV utf-8 时正确导出修复问题。
-   解决问题，其中 Excel 挂起或崩溃时关闭。
-   修复问题，其中包含 concatenate 公式的超链接将忽略 concatenate 结果的一部分。
-   解决问题其中富文本格式 (RTF) 对 Word 在粘贴 Excel 表格不保留的表格格式。
-   其中用户工作簿包含 MS Excel 4.0 宏工作表时无法执行另存为修复问题。
-   使 CTRL + ALT + 5 将选定内容移动到的对象层匹配其他应用程序的快捷方式。
-   修复的问题位置时的公式栏中键入和函数中使用下拉列表中，如 VLOOKUP，按 Enter 以完成公式选择顶部的项目从而不是 leavingthe 记忆式键入下拉列表中的值键入-是。
-   解决问题其中打开 Excel 97-Excel 2003 二进制文件格式 (BIFF8) 文件，包含受保护的工作表中的超链接使 Excel 认为该文件已损坏，Excel 尝试修复或删除的不可读的内容。

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business： 非安全更新
-   解决问题，其中，如果 GrooveIntlResource.dll 无法加载成功 （这是正常情况下太），Office 应用程序可能会崩溃如果用户尝试打开或将文件保存到同步文件夹，或如果用户导航到 Windows 资源管理器可能会崩溃使用 Windows 资源管理器的同步的文件夹。
-   修复问题其中没有禁用 OneDrive for Business，即使相应的注册表项设置为 Office 配置为接收来自 Office 内容交付网络 (CDN) 之外的位置的更新时禁用它，也是如此。

### <a name="onenote-feature-updates"></a>OneNote： 功能更新
-   **控制文件和图像的同步：** 转到文件\>选项\>是否笔记本中的所有页面的自动下载所有文件和图像同步到控件。

### <a name="onenote-non-security-updates"></a>OneNote： 非安全更新
-   解决问题 OneNote 崩溃时打印图像大于页上的位置。
-   解决问题，用户不能删除自定义网页模板。

### <a name="outlook-feature-updates"></a>Outlook： 功能更新
-   **附件实时协作：** 上载到 OneDrive for Business 人从事的最新版本的附件。 使用对附件下拉菜单中上载或将其保存。
-   **摘要卡的差旅预订和程序包：** 验证并跟踪差旅预订以及包 ニ，使用自动创建收件箱和日历中的摘要卡。 [详细信息](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **编辑器：** 提供高级、 上下文校对帮助改善之一的编写。 [详细信息](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题时右键单击对话附件的附件列表中，, 所有的上下文菜单项是可见的而不是只适用的菜单项。
-   修复其中富文本格式 (RTF) 电子邮件时无法打开收件人发送邮件时使用信息权限管理问题。

### <a name="powerpoint-feature-updates"></a>PowerPoint： 功能更新
-   **关闭标题：** 如果幻灯片包含已关闭标题的视频，可以在幻灯片播放标题。
-   **多个音频轨道：** 如果幻灯片包含具有多个音频跟踪的视频，可以在幻灯片播放跟踪。
-   **部分复制：** 复制和粘贴的演示文稿之间的节。
-   **与我共享：** 查看其他人通过转到文件共享与您的文档\>打开\>共享与 me。 [详细信息](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **墨迹重播：** 重播手写向前和向后要隐藏和显示内容、 提供分步说明，或更好地了解他人的想法的流。 [详细信息](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **更好的录制：** 创建构成录制幻灯片，屏幕录像和插入的视频，演示文稿，然后共享远程查看该录制的内容。 您还可以嵌入测验帮助远程学习和使您的演示文稿以及更改更多交互式墨迹颜色和使用简单控件添加到记录旁白和音频。
-   **设计器改进：** 提供了以下设计建议为项目符号过程列表使用 SmartArt。
-   **录制功能区选项卡：** 通过自定义功能区中添加一个录制选项卡。
-   **更改颜色：** 使用告诉我设置字体、 突出显示、 形状填充和更多的颜色。 [详细信息](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **缩放 （英文):** 使用自动导航链接创建您的演示文稿交互式摘要。 [详细信息](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **打开超链接：** 使用 CTRL + 单击编辑演示文稿时打开超链接。
-   **文本突出显示：** 使用文本荧光笔绘制注意重要的文本。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   其中时裁剪图像, 的裁剪的图像部分显示深修复问题。
-   其中，当运行时在幻灯片放映模式和讲述人中，当用户单击超链接和站点上的 PowerPoint 崩溃太慢加载修复问题。
-   解决问题其中实时键入当 coauthoring 表不起作用。
-   修复已安装的 Malwarebytes 3.0 的计算机上打开 PowerPoint 时, 出现"已停止工作"错误或 PowerPoint 崩溃的位置，问题。
-   解决问题的默认模板不在文件下的显示位置\>新建。
-   解决问题，其中键入文本是中断，延迟具有嵌入字体的文件时自动保存。
-   与从 Adobe Illustrator 复制可缩放的向量图形 (SVG) 图像修复问题。

### <a name="project-feature-updates"></a>项目： 功能更新
-   **Locked 字段：** 将值设置为是以防止工作组成员提交任务更新。
-   **时间线标签：** 通过使用标签为其提供描述性名称区分日程表栏。
-   **日程表进度指示器：** 使用复选标记，并且彩色中时间线视图，显示进展进度栏已与每个任务。
-   **辅助功能改进：** 使用键盘，讲述人和其他辅助技术来读取和编辑项目的改进的支持。

### <a name="project-non-security-updates"></a>项目： 非安全更新
-   解决问题创建主项目和子项目之间的跨项目链接时没有链接线的显示位置。
-   解决问题，其中按时间分段比较基准值不会始终正确保存为 XML 格式，尤其是工作和成本包括部分持续时间的值。
-   其中，当应用状态更新，实际工时将添加到的工作分配的工作组成员未报告修复问题。
-   比较基准值的显示位置资源，资源尚未创建一个比较基准的情况下，即使修复问题。
-   打印预览其中剪辑文本，以便文本不可见的情况下解决问题。
-   解决问题其中，打开时的.mpp 文件从 sharepoint 网站使用快捷方式 URL，该文件以打开已签出，即使设置"需要签出其可以编辑文档？" 已启用。
-   从 Project Web Apps 更新材料资源不正确更改时间分段数据的情况下解决问题。
-   解决问题其中打开具有里程碑任务的项目可能的实际开始日期向其添加即使它没有在上次保存时的时间的日期。
-   与工作细分结构 (WBS) 重新编号修复问题。
-   解决问题，其中 Project 崩溃基于网格视图切换时，讲述人是上。
-   打开 XML 文件时，按时间分段数据截断有关显示不正确的错误消息是其中修复问题。
-   解决问题在其中保存比较基准不正确设置时间分段的值。
-   从 XML 文件中读取 project 数据时工作分配延迟，则忽略其中修复问题。
-   其中，当从 Project Online 中打开文件，而不是时区的 UTC 时间上次修改时间日期显示调整时间修复问题。
-   解决问题其中分组色带打印工作表视图中时不显示非分组行。
-   其中修复选项不正确时显示用户检查任务具有工作分配超过最大单位问题修复问题。
-   修复后发布项目大纲代码字段的值不能更改其中的问题。
-   其中甘特条形图不正确调整大小 175%显示在高 DPI 屏幕上修复问题。
-   解决问题，如果用户通过任务信息对话框设置延迟时间，它不正确设置为 24 小时制的工期。
-   其中时打开任务开始日期的某些 XML 文件，不正确设置由于工作分配的问题修复问题。

### <a name="skype-for-business-feature-updates"></a>Skype for Business： 功能更新
-   **Windows 通知样式：** 更改的传入呼叫和对话通知的外观。 [详细信息](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **咨询转接：** 从内呼叫，请咨询通过 IM 或呼叫之前将呼叫转接到该用户的另一个用户。 [详细信息](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **麦克风通知：** 麦克风静音操作系统中时，或者如果麦克风不拿任何音频，请在对话窗口中显示通知。
-   **禁用"我的号码":** 使用 DisableDisplayMyNumber 注册表项禁用"我的号码"拨号盘下。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   更改用于允许或拒绝参与者从文本图像 （X 或一个复选标记） 的会议厅按钮。
-   更改会议提醒通知文本"Accept"从"加入"。
-   更新收件人的状态设置为请勿打扰时，向 IM 发件人显示的消息。
-   更新时接收人处于脱机状态和"保存到历史记录"被禁用，以使其清除的发件人的即时消息，向显示邮件收件人不会收到消息。
-   添加的聊天历史记录和群聊中的名单之间移动的垂直拆分条的功能。
-   添加的功能来调整大小的即时消息或聊天室窗口中的选项卡列表。
-   添加选择聊天室时创建主题源搜索的功能。
-   修复其中消息停止聊天历史记录中端对话中出现问题。
-   解决问题： 在对话窗口中出现重复的邮件。
-   解决问题 （接受和忽略） 的吐司通知操作不会正确显示期间较大的通知。
-   解决问题用户不能在其中键入一条消息后使用 Alt + Tab 打开一个最小化的对话窗口。
-   解决问题其中 IM 按钮为灰显状态在联系人卡片中的用户，即使 IM 是可用。
-   解决问题，多个对话窗口不回其以前的大小和位置后打开正在关闭并重新打开。
-   其中自定义链接不启动时选择修复问题。
-   修复问题，其中区域字段中的联机会议文本显示不正确的非英语字符。
-   修复其中通知信息，如呼叫持续时间不正确呈现从右到左语言的问题。
-   其中时创建主题源，清除搜索结果不重置结果的关注的房间列表修复问题。
-   修复其中 for Business 的 Skype 挂起同时打开多个对话窗口时的问题。
-   解决问题一旦关闭其他所有选项卡最后一个对话窗口，显示为空白。
-   解决问题其中默认焦点时不在聊天输入区域选项卡式的对话都将被禁用。
-   解决问题其中"忘记了您的电话拨入 PIN？" 会议邀请中不显示链接。
-   时使用高 DPI 屏幕显示 175%或更高，其中一些文本是剪裁，截断问题修复常规和音频设备页面上。
-   解决问题时挂起的计算机或将其恢复时没有网络和计算机是"always on，始终连接 (AOAC)"的计算机的业务的 Skype 崩溃，其中。
-   修复任何麦克风检测到发生调用中使用 Polycom CX100 设备时的问题。
-   解决问题其中选择一个链接，如\\ \\servername 或 IM 消息中的 file:// 生成一条错误消息，而不是打开位置。
-   解决问题，使用基于位置的路由，其中用户不能发起或接收 PSTN 呼叫，因为服务器认为用户的位置不是有效的 PSTN 呼叫的虚拟桌面基础结构 (VDI) 环境中。
-   更改时从用户的状态设置为请勿打扰或演示时，对于错过消息，发送的电子邮件的主题行"错过的与对话\<名称\>"目标"\<名称\>for Business 的 Skype 在向您发送一条消息。"
-   启动捕获[统计数据](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices)来帮助标识登录可靠性趋势的一部分的第一次登录设备上的时间戳。
-   解决问题共享辅助监视器的选项与窗口 10 版本 1607 （也称为周年日更新） 上的特定监视器配置不出现的位置。
-   解决问题其中 Skype 对业务崩溃如果放大共享内容，如果共享者使用第三方 RDP 的实现。
-   解决问题时用户单击控件按钮中虚拟桌面基础结构 (VDI) 环境中的音频呼叫的音频控件面板不显示的位置。
-   解决问题，查看者看到黑屏时用户正在运行 Windows 7 和首先，共享主要监视器，然后切换共享第二个监视器。
-   解决问题其中某些特殊字符，例如与号 (&)，不能在搜索输入的框或"今天的最新动态？"中输入 部分的框。
-   修复的问题时有未读的计数不显示其中错过脱机 Im。
-   "通过电子邮件邀请"模板其中提到而不是 Skype Lync 修复问题。
-   修复问题，其中的行号是缺少从拨号盘下的"我的号码"区域。
-   其中鼠标指针不显示在 IM 输入区域中发送邮件中聊天后修复问题。
-   解决问题，其中 for Business 的 Skype 挂起时登录，并且没有问题加载缓存池。
-   其中 for Business 的 Skype 崩溃时登录并还原对话的情况下解决问题。
-   其中 for Business 的 Skype 挂起恢复后在登录后修复问题。
-   如果两个组织中的 Exchange 服务器禁用 TNEF 会议链接禁用的情况下解决问题。
-   如果没有事只有一个 IM 对话，则不能重新视频呼叫的情况下解决问题。
-   解决问题时将白板另存为 PNG 文件在白板上的文本注释其中会丢失。
-   解决问题时输入中日语 IM 窗口中的跨两行的第一行其中隐藏。
-   解决问题其中 & 字符 (&) 不正确替换为下划线字符名称中。
-   与计划的会议中的"加入联机会议"URL 修复问题。
-   解决问题其中鼠标悬停在窗口不激活窗口即使操作系统被配置为执行的操作。
-   其中传出呼叫对话历史记录项显示呼叫者而不是呼叫方修复问题。
-   F12 键不本地保存对话的情况下解决问题。
-   解决问题的错过的对话电子邮件其中不包含初始 IM。
-   解决问题 emoji 可以在其中添加 IM 文本区域中即使演示者已禁用 IM 参与。
-   与铃声和声音选项对话框的版式修复问题。
-   解决问题 for Business 的 Skype 其中崩溃时关闭对话窗口。
-   解决问题时作为虚域注册域 DNS 小于登录失败的位置。
-   解决问题，其中持久聊天通知设置不会被保存或无法正确加载。
-   其中现有的对等对话窗口或聊天室不显示登录，即使已设置的设置，以重新打开对话后修复问题。
-   解决问题其中调节到静音或 unmuting 活动对话使其他对话窗口中显示就好像他们有未读的邮件。
-   解决问题其中媒体绕过配置的用户将无法继续呼叫来自 PSTN 网关之后该呼叫置于保持状态。
-   修复其中用户看到一个蓝色框而不是视频时使用第三方的 RDP 实现加入通过 URL 会议时的问题。
-   解决问题的用户的 SIP 地址一部分而不吐司通知的显示名称的显示位置。
-   解决问题，其中，当 Skype for Business 连接至 SIP 服务器通过端口 443 和代理服务器 is present、 有登录过程中是较长的延迟，如果代理不允许这样的连接。 通过添加下 HKEY EnableDetectProxyForAllConnections DWORD 注册表项启用 fix\_当前\_用户\\软件\\Microsoft\\UCCPlatform\\Lync，并将值设置为 1。
-   其中，当使用选项卡式的对话，双击选项卡上，并开始键入有时会导致焦点移至不同的选项卡，并继续该对话窗口中键入修复问题。
-   修复问题，其中包括即时消息中的 Url 不能选择聊天历史记录窗口中使用键盘。
-   如果铃声和声音选项下选择"查看 IM 对话和人正在键入时播放声音"复选框，则应听到键入声音修复问题。
-   使用屏幕阅读器，如讲述人时显示的对话框不宣布其中修复问题。
-   解决问题，其中第一台运行本教程不能使用键盘来导航和无法读取由屏幕阅读器，如讲述人。
-   在高 DPI 设置缩放任务栏状态图标不其中修复问题。
-   不能在搜索框中的清除字段按钮选择使用键盘修复问题。
-   解决问题，用户无法启动会议，如果 invite 来自另一个池中的用户。
-   解决问题，用户将自己添加到会议错误地显示为其他用户。
-   其中状态更改通知上的联系人的状态图标已隐藏的传入呼叫的老板修复问题。
-   修复 IM 窗口中的文本光标闪烁速率不符键盘属性设置在 Windows 中的问题。
-   解决问题屏幕阅读器宣布组对话中的联系人名称不正确的位置。
-   解决问题，用户不能选择多个联系人使用键盘。
-   无法从 Exchange 中检索用户照片修复问题。
-   解决问题其中 Skype 业务客户端连接到 Skype 业务服务器在内部网络中，而不是一个在外部网络中，当用户连接使用直接访问。
-   解决问题其中 Skype 业务客户端崩溃时尝试解决会议所有者的名称。
-   其中更改 Windows 设置 for Business 的 Skype 启动时或关机的情况下会导致 for Business 崩溃的 Skype 修复问题。
-   解决问题 for Business 的 Skype 其中崩溃时打开持久聊天室中的参与者列表并尝试移动键盘焦点移至参与者列表中。
-   其中 for Business 的 Skype 崩溃在恢复时没有网络可修复问题。

### <a name="visio-feature-updates"></a>Visio： 功能更新
-   **数据库建模加载项：** 使用外接程序创建的现有数据库以帮助规划新的数据库或了解一个现有数据库模型。 [详细信息](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614)，[下载外接程序](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **辅助功能改进：** 改进了对使用键盘、 讲述人和其他辅助技术来处理形状，支持编辑与其他人，等。
-   **第三方模板和图表：** 浏览或新模板和示例图表可从选择第三方内容提供搜索。 缩略图上列出的第三方提供程序的名称。
-   **墨迹支持：** 使用笔或手指以绘制和注释与新的绘制选项卡上的工具。

### <a name="word-feature-updates"></a>Word： 功能更新
-   **辅助功能改进：** 使用键盘，讲述人和其他辅助技术来读取和编辑文档的改进的支持。 [详细信息](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **编辑器：** 提供高级、 上下文校对帮助改善之一的编写。 [详细信息](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **墨迹重播：** 转到绘制\>墨迹重播重播手写向前和向后隐藏和显示内容，提供分步说明，或更好地了解他人的想法的流。 [详细信息](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **使用自然笔势编辑：** 通过按旋转选择和交叉删除对文档进行更改。 [详细信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **与我共享：** 查看其他人通过转到文件共享与您的文档\>打开\>共享与 me。 [详细信息](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **更改颜色：** 使用告诉我设置字体、 突出显示、 形状填充和更多的颜色。 [详细信息](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   修复问题，其中在阅读模式中查看一个文档阻止从正在查看的打印布局中的第二个文档中使用的 TAB 键。
-   Word 其中崩溃时加载多个语法库修复问题。
-   绘制的笔画其中消失后两个或三个笔画修复问题。
-   用引号引起来消失时使用 Google 输入法编辑器 (IME) 中修复问题。
-   解决问题，用户不能使用墨迹内容控件或进行连续的选择时。

### <a name="office-suite-feature-updates"></a>Office 套件： 功能更新
-   **提供反馈：** 建议新功能或告知 Microsoft 您喜欢或什么不起作用，转到文件\>的反馈

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   Microsoft 安全公告[MS16 148](https://technet.microsoft.com/library/security/ms16-148): Microsoft Office (3204068) 的安全更新

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   解决问题其中德语键盘上使用 CTRL + ALT + 7 或 CTRL + ALT + 8 打开用户反馈工具，而不是插入相应字符。
-   其中 TraceLogging 使崩溃上安装或更新 Office 时的 Windows 7 修复问题。
-   其中，当使用墨迹绘图和使用鼠标释放鼠标按钮导致墨迹以 shift 稍微修复问题。
-   其中，Office 文档中插入 SVG 图像之后, SVG 图像将消失保存和重新打开文档时的情况下解决问题。
-   解决问题 Office 其中在非英语用户的激活过程中显示以下错误消息:"产品密钥的最大长度是 25 个字符。"
-   使用 VBA 表单会导致要停止运行或无法正确显示的帧 z-顺序的修复问题。
-   触发 System Center Configuration Manager 更新注册表中的 UpdateChannel 设置更改为不是有效的更新通道修复问题。



## <a name="version-1609-january-10"></a>版本 1609年： 年 1 月 10
*版本 1609 （构建 7369.2102）*

注意： 在 Microsoft 安全公告[MS17 002](https://technet.microsoft.com/library/security/ms17-002)中介绍的安全更新不应用于此通道版本中的 Word 版本。

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   解决问题，使用编辑度量值对话框使 Excel 崩溃。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   其中使用形状有时会导致 PowerPoint 崩溃修复问题。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   解决问题共享辅助监视器的选项与窗口 10 版本 1607 （也称为周年日更新） 上的特定监视器配置不出现的位置。
-   解决问题其中 Skype 对业务崩溃如果放大共享内容，如果共享者使用第三方 RDP 的实现。
-   解决问题，其中，当 Skype for Business 连接至 SIP 服务器通过端口 443 和代理服务器 is present、 有登录过程中是较长的延迟，如果代理不允许这样的连接。 通过添加下 HKEY EnableDetectProxyForAllConnections DWORD 注册表项启用 fix\_当前\_用户\\软件\\Microsoft\\UCCPlatform\\Lync，并将值设置为 1。

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   其中，使用 InsertXML 方法时，则断开的图片链接的占位符显示而不是实际的图像修复问题。

