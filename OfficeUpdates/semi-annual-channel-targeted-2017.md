---
title: 2017中针对半年频道 (目标) 版本的发行说明
ms.author: anankani
author: andymosten
manager: anankani
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关半年频道 (目标) 版本 for Office 365 专业增强版 in 2017 的发布说明
ms.openlocfilehash: 44f6c4b86f88419f97bee4e89b99b5a4a46133c9
ms.sourcegitcommit: db492a4c51ec771ab97c67e4b1d43ee36d8794b8
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/07/2020
ms.locfileid: "48370090"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>2017中针对半年频道 (目标) 版本的发行说明

这些发行说明提供了有关半年频道 (目标) 更新到2017中的 Office 365 专业增强版的新功能、安全更新和非安全更新的信息。
 
> [!NOTE]
> - 以下说明还提供了有关 Visio Pro for Office 365 和 Project Online 桌面客户端的新功能、安全更新和非安全更新的信息。
> - 此信息还适用于 Office 365 商业版，即随附一些 Office 365 计划的 Office 版本（如企业高级版）。
> - 半年频道 (目标) 在9月2017之前为延期频道命名为第一版。

## <a name="version-1708-december-12"></a>版本1708：12月12日
*版本 1708（内部版本 8431.2131）*

 ### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935)：Microsoft Excel 远程代码执行漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了在使用宏打开 Office 2007 或更低版本工作簿（.xls 或 .xla）时，用户错误地看到“灾难性故障”错误消息的问题。
-   修复了通过命令行打开工作簿可能会导致单元格中 RTF 格式丢失的问题。

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 信息泄漏漏洞

### <a name="powerpoint-security-updates"></a>PowerPoint：安全更新
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 信息泄漏漏洞

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了以下问题：项目级自定义字段数据可能会在保存时丢失。
-   修复了以下问题：如果保存失败，则会损坏文件，并导致 Project 在打开时发生故障。
-   修复了以下问题：打开项目计划可能会导致故障发生。

### <a name="word-security-updates"></a>Word：安全更新
-   [公告 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新



## <a name="version-1708-november-14"></a>版本1708：11月14
*版本 1708（内部版本 8431.2110）*

### <a name="access-non-security-updates"></a>Access：非安全更新
-   修复了以下问题：尝试选择文本框或组合框中的文本时似乎会选择所有文本，而不是指示的选择内容。

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全功能规避漏洞
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 内存损坏漏洞
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 内存损坏漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了当文件名包含方括号时，用户无法在受保护视图中关闭工作簿的问题。
-   修复了以下问题：当用户尝试在现有的工作簿中插入对象时，用户单击“浏览”导致 Excel 发生故障的问题。
-   修复了以下问题：（在“设置形状格式”窗格的“文本选项/文本框”部分中）选择“调整形状大小以修复文本”不会产生任何形状更改。
-   修复了以下问题：通过双击工作簿将其打开时，不加载单元格文本字体和格式或为单个模板打开两个相同的工作簿。
-   修复了在打开或创建新工作簿时，Excel 启动时创建的第一个工作簿将不会关闭的问题。
-   修复了以下问题：拖动或拖动填充时，工具提示的位置未对齐。
-   修复了以下问题：使用“文件”\>“另存为”保存工作簿时，包含句点的文件名在文件保存对话框中显示为空白或被截断。
-   修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。
-   修复了由于图形驱动程序错误导致出现黑线和标题的呈现问题。
-   修复了在插入图表后 Excel 发生故障或无法保存工作簿的问题。
-   修复了在分页预览下页面分隔线定位不正确的问题。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了用户在删除邮件时看到邮件列表中的焦点意外跳转的问题。
-   修复了用户在对附件执行操作时看到验证提示的问题。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。
-   修复了在表格中执行撤销操作后编辑和格式化的文本导致 PowerPoint 发生故障的问题。
-   修复了对基于 Flash Player 的 YouTube 嵌入代码进行引用导致打开新窗口播放视频的问题。旧嵌入代码现已升级以引用基于 HTML5 的 YouTube 视频，以便正确播放这些视频。

### <a name="word-security-updates"></a>Word：安全更新
-   [公告 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防御更新

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了以下问题：如果用户尝试对 OneDrive for Business 上的现有文档执行“另存为”操作，然后又取消保存或尝试合并现有更改，Word 发生故障。
-   修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。
-   修复了在用户打开 Word 后立即导航到“插入”选项卡时 Word 挂起的问题。
-   修复了在单击边距后，若输入字符，字符会显示在屏幕左上角的问题。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 内存损坏漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了以下问题：在动态 DPI 环境下 Office 加载项存在的缩放问题。
-   修复了以下问题：即使当前安装了 Office 365 专业增强版，Office 配置服务提供程序 (CSP) 的 CurrentStatus 节点也会返回空字符串。
-   修复了导致 .box 文件格式更改的问题，这些更改会影响安装在同一台计算机上的旧版 Office 的功能，因为 .box 文件在同一台计算机上的所有 Office 应用版本之间共享。
-   修复了以下问题：在使用共享计算机激活的某些情况下，出现一条错误消息，指示应用遇到错误，阻止其正常工作并询问用户是否运行修复。



## <a name="version-1708-october-10"></a>版本1708：10月10
*版本 1708（内部版本 8431.2107）*

### <a name="access-non-security-updates"></a>Access：非安全更新
-   修复了当查询与 Microsoft Dynamics 链接表中的主键存在连接时，查询不执行的问题。
-   修复了以下问题：Microsoft Dynamics 表中货币值不显示小数位数。

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了打开 .XLL 文件时 Excel 崩溃的问题。
-   修复了以下问题：在“页面布局”视图中添加页眉或页脚后，单元格的图案样式显示不正确。
-   修复了以下问题：将数据透视表的一个副本粘贴到另一个工作簿时，可能会导致崩溃。
-   修复了以下问题：选择“替换”命令并且“查找和替换”对话框打开时，对话框的焦点位于“查找”选项卡上，而非“替换”选项卡上。
-   修复了以下问题：打开工作薄（它从版本早于 SharePoint Server 2016 的 SharePoint Server 打开）的“活动”窗格时 Excel 崩溃。
-   修复了以下问题：启用一个或多个 XLL 外接程序时，Excel 打开并显示空白窗口。
-   修复了以下问题：在已关闭的工作簿中使用“窗体”按钮后，Excel 崩溃。
-   修复了以下问题：在使用 SheetBeforeRightClick 事件时，插入与合并单元格相交的列不会展开合并的单元格。

### <a name="outlook-security-updates"></a>Outlook：安全更新程序
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774)：Microsoft Outlook 安全功能绕过漏洞
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776)：Microsoft Outlook 信息泄漏漏洞

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了在使用深灰色主题时，策略提示中的“了解更多”链接不可见的问题。
-   修复了以下问题：用户尝试设置新帐户和在完成帐户设置之前关闭窗口时，Outlook 崩溃。
-   修复了以下问题：“标记为已读”和“标记为未读”显示为群组共享收件箱中的邮件选项。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：从版本早于 SharePoint Server 2016 的 SharePoint Server 打开演示文稿时，PowerPoint 崩溃。

### <a name="word-security-updates"></a>Word：安全更新
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826)：Microsoft Office 内存损坏漏洞

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了在打开文档（从版本早于 SharePoint Server 2016 的 SharePoint 服务器打开）的“活动”窗格时，Word 崩溃的问题。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825)：Microsoft Office 远程执行代码漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了不向用户显示联机修复进度的问题。
-   修复了文件资源管理器中不显示 Office 文件属性的问题。
-   修复了以下问题：打开第二个文档时，Office 外接程序按钮从功能区消失。
-   修复了无法打开一些名称为双字节字符的 VBA 模块的问题。



## <a name="version-1708-september-12"></a>版本1708：9月12
*版本 1708（内部版本 8431.2079）*

### <a name="access-feature-updates"></a>Access：功能更新
-   **标签名称属性：** 通过将标签与窗体上的控件相关联，增强了辅助功能。
-   **编辑新项更加容易：** 使用键盘快捷方式 (Ctrl+E) 通过组合框或列表框编辑新项。
-   **Dynamics 连接器：** 导入 Microsoft Dynamics 中的数据，或链接到其中存储的数据。[更多信息](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Salesforce 连接器：** 导入 Salesforce 中的数据，或链接到其中存储的数据。[详细信息](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **“从示例中添加列”增强功能：** 支持更多的日期/时间、数学和索引列转换。
-   **性能改进：** Excel 将以更快的速度打开包含多个工作表的复杂工作簿，以便可以更快地处理包含大片区域的公式、筛选多个行或进行复制和粘贴。
-   **插入联机图片：** 自动将图像插入用于选择图像和属性信息的新登录页。
-   **Azure Data Lake Store 连接器：** 用户现在可以从 Azure Data Lake Store 导入数据。
-   **“从示例中添加列”增强功能：** 支持建议、更多的日期/时间操作和其他转换。
-   **“数据”选项卡**：“数据”选项卡上的功能区按钮已被重排到两个新组中：“获取和转换数据”以及“查询和连接”。
-   **共享查询**：可以将任意查询定义导出到 Office 数据库连接 (ODC) 文件中，然后跨工作簿共享或与其他人共享。
-   **加载数据：** 可以将查询中的数据直接加载到数据透视表或数据透视图中，而无需将数据保存到数据模型中。
-   **共享文件活动：** 选择文件右上角的“活动”按钮，可以查看在 OneDrive for Business 或 SharePoint 中共享的文经共享、编辑、重命名或恢复的时间。
-   **安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **增强的数据导入功能：** 可从各种源轻松导入并形成数据。通过“查询和连接”侧窗格管理工作簿查询和连接，并通过 ODC 文件与他人共享查询。 [更多信息](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **对共享文件做出的更改**：查看共享工作簿的更改人，并还原旧版工作簿。[更多信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **含有笔按钮的套索选择：** 无需访问功能区，即可使用套索选择墨迹带的支持数字笔按钮。

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632)：Microsoft Office 内存损坏漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了在展开或折叠数据透视表时，Excel 会暂时挂起，并且数据透视表标题移动到屏幕之外的问题。
-   修复了从 Word 复制并粘贴制表符分隔的文本时制表符被忽略，进而导致文本无法解析到列中的问题。
-   修复了以下问题：以网页对话框形式打开发布时 Excel 出现故障。
-   修复了以下问题：使用 SQL Server Analysis Services 服务器中的数据，且 Excel 与 SQL Server Analysis Services 服务器的区域设置不同时，数据刷新无法成功或 Excel 发生故障。
-   修复了以下问题：在尝试将更改保存到与 OneDrive 客户端同步的文档时出现错误。
-   修复了以下问题：在筛选区中存在具有字段的数据透视表，但在其他任何位置没有字段时，无法在工作表的任何位置进行更改。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **辅助功能改进：** 简化了使用屏幕阅读器读取和编辑电子邮件中的文本、表、列表和图像的方式。
-   **新帐户配置：** 使用新向导设置一个手动操作步骤较少的新帐户。
-   **链接附加对话框：** 使用功能区上的“附加文件”附加链接时，可以选择是将它添加为链接，还是添加为附件。如果不想每次都看到此对话框，请依次转到“文件”\>“选项”\>“常规”，并在“附件选项”下指定所需的链接附加方式。
-   **支持本地附件：** 本地 SharePoint Server 中的文件显示为“邮件”\>“附加文件”下的最近使用的文件，本地 OneDrive for Business 和 SharePoint 团队网站显示在“附加文件”\>“浏览 Web 位置”下，本地文件可以上传到本地的 OneDrive for Business 站点。
-   **组业务分类：** 可在创建或编辑组时分配由租户管理员定义的业务分类级别，例如“机密”，并且分类会显示在组标头中。
-   **Office 365 组的来宾访问：** 向组织外的用户授予组对话、文件、日历邀请和组笔记本的访问权限，并与他们进行协作。 [更多信息](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **可操作邮件：** 开发人员可以创建能够轻松地使用户直接从 Outlook 执行简单或快速操作而无需切换到外部网站或单独应用的邮件。[更多信息](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)：Microsoft Office Outlook 安全功能规避漏洞
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)：Microsoft Office Outlook 信息泄漏漏洞
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)：Microsoft Office Outlook 内存损坏漏洞

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了无法在 Outlook 中配置 IMAP 帐户的问题。
-   修复了以下问题：打开 Outlook 时，发生间歇性故障。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **插入联机图片：** 自动将图像插入用于选择图像和属性信息的新登录页。
-   **视频的隐藏式字幕：** 可以在视频中添加隐藏式字幕，使其更易于访问。[详细信息](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **对记录添加旁白：** 录制演示文稿时，请将自己旁白的视频包括在内。录制的内容可以包括动画、墨迹、音频和视频。
-   **共享文件活动：** 选择文件右上角的“活动”按钮，可以查看在 OneDrive for Business 或 SharePoint 中共享的文经共享、编辑、重命名或恢复的时间。
-   **替换文字创建：** 基于云的服务自动生成演示文稿中的图片的可选文字。
-   **安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **设计器改进：** 推荐面向操作的列表的专业设计灵感。
-   **对共享文件做出的更改：** 查看共享演示文稿的更改人，并还原旧版演示文稿。[更多信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint：安全更新
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742)：PowerPoint 远程代码执行漏洞
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743)：PowerPoint 远程代码执行漏洞

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：无法显示与字体关联的最终用户定义字符 (EUDC)。

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了从 Project Online 打开某些文件会导致项目出现故障的问题。
-   修复了设置剩余工时时可能会错误地将实际开始时间清除的问题。
-   修复了工作分配实际开始日期显示的数据可能与通过 Project Web App 进展状况中的资源报告的数据不同的问题。
-   修复了更改任务的完成日期后可能会重排实际工时的问题。
-   修复了复制并粘贴成本字段时由于舍入问题粘贴值可能与复制值不完全一致的问题。
-   修复了从一个基线保存到另一个基线时无法复制预算资源的时间分段数据的问题。
-   修复了无法始终正确计算摘要任务的状态字段的问题。
-   修复了在替换本地资源并启用受保护的工作时，将实际工作错误地转移到企业资源的问题。
-   修复了如果拥有一个第一列为“任务名称”的表，该列已锁定，单击某项任务后，Project 崩溃的问题。
-   修复了可以通过“任务分配状况”视图将同一资源多次分配到相同任务的问题。
-   修复了打开 XML 文件时，数字自定义字段中的值可能会丢失的问题。
-   修复了顶级任务缩进不正确地从 Project 同步到 SharePoint 任务列表的问题。
-   修复了如果从 Excel 工作簿导入任务、资源或分配信息，工作字段中的值可能会被忽略的问题。
-   修复了以下问题：在以 XML 文件格式保存项目时，时间分段的基准值与初始值不匹配。
-   修复了以下问题：Project 客户端不会打开项目，因为它认为项目已签出，而实际上并非如此。
-   修复了一个问题，使得从高延迟文件服务器打开 Project 文件的速度更快。

### <a name="skype-for-business-security-updates"></a>Skype for Business：安全更新
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676)：Windows GDI+ 信息泄漏漏洞
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695)：图形组件信息泄漏漏洞
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696)：Microsoft 图形组件远程代码执行

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   添加对话框，解释当阻止特定端口或 IP 未列入白名单时，用户为何无法加入某个会议。
-   修复了在单击即时消息对话标签页时，持久聊天室中的未读消息会标记为已读的问题。
-   修复了传入即时消息 Toast 发生数秒钟延迟的问题。
-   修复了当禁用与 Exchange 同步时，AD 联系人显示为电话号码，而非联系人姓名的问题。
-   修复了当禁用联盟，且会议组织者未明确阻止匿名加入时，阻止匿名加入用户加入的问题。
-   修复了对于超出限制的会议，被邀请者人数未正确显示给会议组织者的问题。
-   修复了电话号码未在入站 PSTN 通话上的 Toast 中显示的问题。
-   修复了在重命名联系人列表组的同时使用 Delete 键时，会删除整个组的问题。
-   修复了在共享停止之前，即时消息对话中的共享通知消除的问题。
-   修复了某些非英语语言的登录屏幕为空的问题。
-   修复了聊天和聊天历史记录中的非英语字符乱码问题。
-   显示组织自动助理处理的来电的呼叫者电话号码（如果用户名未知的话）。
-   新增了一个带内设置，允许“任何人(无限制)”限制作为“这些人不必在大厅等待”的选项。
-   新增了在 VDIv2 中为 P2P 视频呼叫启用或禁用自拍视频的功能。
-   修复了以下问题：呼叫下拉菜单中显示联系人的重复号码。
-   修复了以下问题：删除了在 Skype for Business 和 Skype for Business Basic 之间移动的用户的代理。
-   修复了以下问题：使用“启用显示脱机和自定义状态 URL”客户端策略时，“显示脱机”不可见。
-   扩大“会议加入”按钮来修复某些本地化语言的截断问题。
-   更加突出显示聊天中重要级别高的消息。
-   将 Office 和 Skype for Business 文件扩展名类型添加到允许的文件传输阻止列表。
-   Outlook 会议邀请中用于会议页脚文本的本地化更正设置为非英语语言。
-   修复了在多个用户的对话中可切换发送者名称的问题。
-   修复了在成功加入会议前空白会话窗口无法显示的问题。
-   修复了以下问题：如果标题字段为空，则联系人卡片中的部门字段信息在搜索结果中为空。
-   修复了以下问题：防火墙规则导致从本地迁移到在线环境的用户登录失败。
-   添加了新的 DWORD 注册表项以修复以下问题：当用户登录到执行 LyncAutoD 的外部网络上的客户端时，客户端将 OAuthUsed 注册表项重置为 False。 若要解决此问题，请将 "HKEY \_ 当前 \_ 用户 \\ 软件 \\ Microsoft \\ Office \\ 16.0 \\ Lync \\ \<SipID\> " 下的 "EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket" 的值设置为1。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **使用 Excel 数据制作图表：** 通过使用新的数据可视化工具模板，从 Excel 数据自动创建基本流程图或跨职能流程图。 [更多信息](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio：非安全更新
-   修复了以下问题：当通过双击文件图标或文件名打开 Visio 文件时，COM 外接程序不接收文档打开事件。

### <a name="word-feature-updates"></a>Word：功能更新
-   **插入联机图片：** 自动将图像插入用于选择图像和属性信息的新登录页。
-   **替换文字创建：** 基于云的服务在文档中自动生成图片可选文字（替换文字）。
-   **共享文件活动：** 选择文件右上角的“活动”按钮，可以查看在 OneDrive for Business 或 SharePoint 中共享的文经共享、编辑、重命名或恢复的时间。
-   **安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **对共享文件做出的更改：** 查看共享文档的更改人，并还原旧版文档。 [更多信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了在加载 Grammarly 外接程序时，Word 意外关闭的问题。
-   修复了以下问题：在某些情况下，当尝试恢复基于云的文件时，Word 发生故障。
-   修复了画布中的形状无法旋转的问题。
-   修复了以下问题：键入朝鲜语时，辅音和元音分隔错误。
-   如果将文档另存为 PDF，则可另存为 PDF 1.7 版本。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)：Microsoft Office 远程代码执行漏洞
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744)：Microsoft Office 内存损坏漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了无法显示“新增功能”对话框的问题。
-   修复了单击“绘图”选项卡导致某些用户的应用程序崩溃的问题。
-   修复了当鼠标悬停在具有工具提示的公共控件上会导致应用程序崩溃的问题。
-   修复了使用公共控件时出现授权错误消息的问题。
-   修复了以下问题：一些程序文件的签名方式存在问题，导致防病毒程序标记这些文件，并且 Windows 信息保护 (WIP) 无法保护或访问数据。
-   添加支持，以允许用户使用 64 位版本的 Office 打开包含 mscomctl.ocx 控件的宏文件。
-   改进 mscomctl.ocx 中所使用控件的辅助功能。
-   修复了功能区或快速访问工具栏自定义对话框中缺失命令的问题。



## <a name="version-1705-august-8"></a>版本1705：8月8日
*版本 1705（内部版本 8201.2171）*

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了拖动滚动条在消息列表中移动的问题。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了以下问题：一些程序文件的签名方式存在问题，导致防病毒程序标记这些文件，并且 Windows 信息保护 (WIP) 无法保护或访问数据。
-   修复了无法显示“新增功能”对话框的问题。



## <a name="version-1705-july-27"></a>版本1705：7月27日
*版本 1705（内部版本 8201.2158）*

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了以下问题：在尝试将更改保存到与 OneDrive 客户端同步的文档时出现错误。
-   修复了以下问题：将工作表数据添加到数据模型，并将“高对比度”主题设置为“黑色”时，Excel 发生故障。

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)：Microsoft Office Outlook 安全功能规避漏洞
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)：Microsoft Office Outlook 信息泄漏漏洞
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)：Microsoft Office Outlook 内存损坏漏洞

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：在另一个用户更改布局后添加形状导致合并失败。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了以下问题：键入朝鲜语时，辅音和元音分隔错误。
-   修复了以下问题：信封上打印出的交货地址太靠近左侧边缘。



## <a name="version-1705-july-13"></a>版本1705：7月13日
*版本 1705（内部版本 8201.2136）*

### <a name="excel-security-updates"></a>Excel：安全更新
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)：Microsoft Office 内存损坏漏洞

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了由于工作簿包含外部链接而导致 Excel 崩溃的问题。
-   修复了即使未选择“在具有零值的单元格中显示零”设置，将单元格从 Excel 粘贴到 Word 也在单元格中显示零的问题。

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了为图表/表选择的值在图表/表窗格中不可见的问题。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复了在加入会议时会话窗口在后台不显示，并且向用户显示音频设备加入对话框的问题。
-   修复了 Outlook 中的会议链接并不总是正确地传递内部 URI 的问题。
-   扩大“会议加入”按钮来修复某些本地化语言的截断问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了在某些操作之后表无法正确显示的问题。
-   修复了一段时间内对引文的多次编辑显示为单个撤消操作而不是连续的单个操作的问题。
-   修复了在某些操作之后禁用撤消的问题。
-   修复了问题，以防止在执行某些撤消操作后可能出现数据丢失。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)：Microsoft Office 远程代码执行漏洞

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了在使用 Configuration Manager 时导致 office 2013 到 Office 2016 的无人参与升级失败的问题。
-   修复了通过企业目录从存储部署的旧版外接程序不加载的问题。



## <a name="version-1705-june-13"></a>版本1705：6月13日
*版本 1705（内部版本 8201.2102）*

### <a name="access-feature-updates"></a>Access：功能更新
-   **新增功能对话框：** 在 Access 更新了新功能后，打开 Access 时，会显示一个突出显示新 Access 功能的对话框。此外，还可以通过转到“文件”\>“帐户”\>“新增功能”找到此对话框。
-   **支持大数 (bigint)：** 使用 Access 表中的 Large Number 数据类型来计算大型数字，并链接到使用等效数据类型的外部数据库（如 SQL Server 中的 bigint）或从中导入。 [详细信息](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **Windows 信息保护 (WIP) 支持：**   Excel 现在是一个智能型应用，可以区分企业数据和个人数据，并根据配置的策略正确地确定要保护的数据。  [详细信息](https://aka.ms/wiptechnet)
-   **“获取和转换数据”改进：** 在“查询编辑器”中，可以通过提供示例值创建新列。在输入过程中，Excel 会检测所需的转换，然后显示新列的预览效果。
-   **插入最近使用的链接：** 轻松地将超链接附加到最近使用的基于云的文件或网站，并为使用屏幕阅读器的用户创建有意义的显示名称。 [详细信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **个性化设置默认的数据透视表布局：** 以你喜欢的方式设置数据透视表，并在每次创建新的数据透视表时从该布局开始。 [更多信息](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **“获取和转换”改进：** 用户可以通过示例创建新列，并将表列拆分为行。现在可以更轻松地为 SAP HANA 指定参数，以及进行数据分组了。
-   **外接程序的集中式部署**：管理员可以从 Office 365 管理中心将加载项部署并更新到用户或组。 [更多信息](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **快速访问工具栏自定义：** 可将“下标”和“上标”图标添加至快速访问工具栏。
-   **“获取和转换”改进：** 使用查询编辑器拆分列时自动检测分隔符字符，选择要与合并二进制数据一起使用的示例文件，并指定使用 DB2 连接器时要连接的包集合。
-   **迪拜字体：** 支持西欧语言和使用阿拉伯语脚本的主要语言的字体系列。 [更多信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景消除：** 使用任意格式的绘图工具删除图片背景。
-   **“获取和转换”改进：** 在“导航器”对话框中通过 ODCB 和 OLEDB 连接器使用“选择相关表”，直接从文件夹“数据预览”对话框中合并多个文件，并在“查询编辑器”窗口中使用新的上下文菜单选项在现有查询中插入新步骤。
-   **使用触笔选择和更改对象：** 使用数字触笔捕捉对象句柄，以执行重设大小、旋转、移动等操作。
-   **地图图表：** 跨地理区域比较值和显示类别。 [更多信息](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **SVG 图像：** 在工作簿中插入和编辑可缩放的矢量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：**  通过转到插入插图图标 (SVG) 文件的标准库中的图标（通过可缩放的矢量图形） \> \> 。 [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **保存到最近访问的文件夹：** 依次转到“文件”\>“另存为”，使用“最近访问的位置”选项卡，将工作簿保存到最近访问的文件夹中。
-   **辅助功能改进：** 改进了支持，可以更好地使用键盘、讲述人和其他辅助技术阅读和编辑工作簿。 [更多信息](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel：安全更新
-   Microsoft 安全公告 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 安全更新程序 (3217868)

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了以下问题：以编程方式为使用 Excel 2010 或更低版本创建的工作簿应用工作表保护密码时，Excel 无法设置此密码。
-   修复了以下问题：“合并后居中”对分组的工作表无效。
-   修复了以下问题：缺少在 Office 2016 发布后引入的新函数，例如 TEXTJOIN、CONCAT、IFS、MAXIFS 和 MINIFS。
-   修复了以下问题：Excel 在用户尝试应用单元格级权限时出现故障。
-   修复了以下问题：将大型文件保存到 OneDrive for Business 导致文件锁定并且用户无法编辑该文件直到用户关闭并重新打开 Excel。
-   修复了以下问题：打开 .xls 工作簿时，新窗口显示为灰色。
-   修复了以下问题：Excel 可能会在用户插入超链接时发生故障。
-   修复了在添加 XML 映射时 Excel 可能发生故障的问题。
-   修复了外接程序升级后或从 Office 应用商店中删除并再次下载该外接程序后，外接程序的命令按钮不起作用的问题。
-   修复了以下问题：通过 VBA 控制 DLL 工作表时，Excel 可能会发生故障。
-   修复了以下问题：选择图表工作表上的表单控件组合框时，Excel 可能会发生故障。

### <a name="onenote-feature-updates"></a>OneNote：功能更新
-   **Windows 信息保护 (WIP) 支持：** OneNote 应用程序现已启用 WIP，可以区分企业数据和个人数据，并能根据配置的策略正确地确定要保护的内容。 [更多信息](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新
-   修复了以下问题：显示多个段落时，OneNote 画布会隐藏内容或更新。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **Windows 信息保护 (WIP) 支持：**   Outlook 现在是一个智能型应用程序，可以区分企业数据和个人数据，并根据配置的策略正确地确定要保护的数据。  [详细信息](https://aka.ms/wiptechnet)
-   **插入最近使用的链接：** 将超链接附加到最近使用的基于云的文件或网站，并为使用屏幕阅读器的用户创建有意义的显示名称。 [详细信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **迪拜字体：** 支持西欧语言和使用阿拉伯语脚本的主要语言的字体系列。 [更多信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景消除：** 使用任意格式的绘图工具删除图片背景。
-   **检查对共享文件的访问权限：** Outlook 会提前告知用户，收件人可能无法访问附加的 OneDrive 或 SharePoint 文件，并对如何解决该问题提供建议。
-   **对附件设置权限：** 对于 OneDrive 或 SharePoint 附件，用户可以设置组织中或外部的收件人是否具有对附件的读取或编辑权限。
-   **可固定的任务窗格：** 在邮箱中切换邮件的同时，可让外接程序任务窗格一直处于打开状态。 [更多信息](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **SVG 图像：** 在电子邮件中插入和编辑可缩放的矢量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：**  通过转到插入插图图标 (SVG) 文件的标准库中的图标（通过可缩放的矢量图形） \> \> 。  [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook：安全更新
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106)：Microsoft Outlook 远程代码执行漏洞
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204)：Microsoft Office 安全功能绕过漏洞
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506)：Microsoft Office 远程代码执行
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508)：Microsoft Office 安全功能绕过漏洞

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了以下问题：当计算机内存不足时，Outlook 导航窗格停止呈现。
-   扩展附件的可见宽度，以适应文件名和权限信息的大小。
-   修复了以下问题：用户无法搜索 PST 文件。
-   修复了以下问题：用户在“新建 Outlook 数据文件”对话框中看到有新的“Microsoft Exchange”存储类型，但在选择这一新增的数据类型后用户的配置文件就不可用了。
-   修复了当使用高 DPI 从计算机发送邮件时，邮件中的图像变暗的问题。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **Windows 信息保护 (WIP) 支持：**   PowerPoint 现在是一个智能型应用程序，可以区分企业数据和个人数据，并根据配置的策略正确地确定要保护的数据。  [详细信息](https://aka.ms/wiptechnet)
-   **插入最近使用的链接：** 将超链接附加到最近使用的基于云的文件或网站，并为使用屏幕阅读器的用户创建有意义的显示名称。 [更多信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **外接程序的集中式部署**：管理员可以从 Office 365 管理中心将加载项部署并更新到用户或组。 [更多信息](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **迪拜字体：** 支持西欧语言和使用阿拉伯语脚本的主要语言的字体系列。 [更多信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景消除：** 使用任意格式的绘图工具删除图片背景。
-   **SVG 图像：** 在演示文稿中插入和编辑可缩放的矢量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：**  通过转到插入插图图标 (SVG) 文件的标准库中的图标（通过可缩放的矢量图形） \> \> 。 [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **共同创作时的实时键入：** 查看其他人在演示文稿中的工作方式并在键入时查看更改。 [详细信息](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **保存到最近访问的文件夹：** 依次转到“文件”\>“另存为”，使用“最近访问的位置”选项卡，将演示文稿保存到最近访问的文件夹中。
-   **精确创建墨迹形状：** 拖动线段橡皮擦擦去多余墨迹，直到与最近线段交汇之处为止。
-   **使用触笔选择并操作对象：** 使用数字触笔时，利用对象句柄或套索选择墨迹带的支持触笔按钮来移动、调整大小或旋转对象。
-   **辅助功能改进：** 改进了支持，可以更好地使用键盘、讲述人和其他辅助技术阅读和编辑演示文稿。 [更多信息](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了当用户处于“设计灵感”窗格中时，如果计算机上未安装 mfplat.dll 文件，PowerPoint 会崩溃的问题。
-   修复了外接程序升级后或从 Office 应用商店中删除并再次下载该外接程序后，外接程序的命令按钮不起作用的问题。

### <a name="project-feature-updates"></a>Project：功能更新
-   **用于设置前导活动的快速下拉列表：** 使用甘特图下拉列表选择要链接到任务的前导活动或后续活动。
-   **任务摘要名称：**  只读任务域，显示任务的摘要任务的名称。  

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了“创建项目网站”对话框，使其能够显示网站的正确位置。这样，在 Project Online 中，每个企业项目模板 (EPT) 都有自己的项目网站 URL。
-   修复了以下问题：VBA BeforeClose 事件在保存提示出现前触发，无法以编程方式确定用户对保存提示的响应。
-   修复了以下问题：对于在项目状态日期之后开始执行的任务，无法正确汇总“实际完成百分比”。
-   修复了以下问题：将成本和工时资源分配给同一任务时，可能无法更改任务的状态管理员。
-   修复了以下问题：对于某些项目，调配整个项目可能会进入无限循环。
-   修复了以下问题：如果有特定的西班牙语区域设置，无法将任务开始日期和完成日期正确同步到 SharePoint 任务列表中。
-   修复了以下问题：如果从 Project 客户端启动状态审批流程，可能永远无法完成，导致项目处于不可用状态。
-   修复了以下问题：如果有中文和英语字词，打印预览无法正确列出任务名称。
-   修复了以下问题：由于单个形状不可用，要将日程表复制到 PowerPoint 中。
-   修复了以下问题：“在项目间链接”对话框意外显示值“找不到文件”。
-   修复了以下问题：分配最大单位为 0 的资源时，获得的结果不一致。
-   修复了以下问题：删除作业的开始日期后，任务的开始日期重置为“尽快”，忽略了前置任务等事项，进而导致对作业进行前导拆分。
-   修复了以下问题：即使已启用“是否要求先签出文档然后再对其进行编辑?”设置，通过“最近”菜单打开 SharePoint 中的文件时，仍会自动签出项目。
-   修复了以下问题：如果直接转到“Project Profiles”应用程序，Project 会发生故障。
-   修复了以下问题：无法为从 Project 2013 升级的用户正确更新手动计划任务。
-   修复了以下问题：打开 SharePoint 任务列表中的项目后，Project 可能会在启动任务同步进程时发生故障。
-   修复了以下问题：转到“生成团队”时，Project 有时会发生故障。
-   修复了以下问题：保存项目时丢失基线信息。
-   修复了难以针对大型项目计划读取打印输出的问题。
-   修复了在 Project Web App 中编辑的项目不显示公式域的正确值的问题。
-   修复了未针对项目计划正确保存资源企业自定义字段的信息的问题。
-   修复了更新任务的工时完成百分比信息时会更新任务的完成百分比信息的问题。
-   修复了保存项目时项目所有权更改的问题。
-   修复了对摘要任务错误计算 CPI 的问题。
-   修复了即使用户不被允许保存受保护的基线数据，复制和粘贴任务时仍会覆盖基线数据并保存数据的问题。
-   修复了从 Excel 导入数据导致任务和分配的日期信息不正确的问题。
-   修复了在打开报告后，关闭时 Project 会崩溃的问题。
-   修复了当保存项目时 Project 停止工作的问题，其中自定义列表包含验证设置。
-   修复了在“筛选器定义”对话框中的“测试”列中输入“\>”字符未正确解释为“大于”的含义的问题。
-   修复了与“基线计划”相关的进度线显示问题。
-   修复了在自定义筛选器时不显示域名下拉列表的问题。
-   修复了“条形图样式”对话框中不显示“条形图样式”预览的问题。

### <a name="publisher-non-security-updates"></a>Publisher：非安全更新
-   修复了发布服务器不显示 CMYK TIFF 图像的问题。

### <a name="skype-for-business-feature-updates"></a>Skype for Business：功能更新
-   **插入链接：** 可以在 IM 和群组聊天中添加链接，并输入易记的链接文本，而不是完整 URL。
-   **屏幕共享通知：** 在 IM 对话中共享屏幕或在离开会议后仍继续共享屏幕时，对话窗口中会显示屏幕共享通知。此通知旨在提醒仍在共享屏幕，只需使用“停止共享”按钮，即可轻松停止共享。
-   **Windows 信息保护 (WIP) 支持：** Skype for Business 现作为“仅 WIP 作业”应用受到支持。通过将 Skype 添加到允许的应用列表，可以指示 Windows 不处理个人数据。Windows 将代表 Skype for Business 保护数据。  [详细信息](https://aka.ms/wiptechnet)
-   **密码重置选项：** 当用户至少登录失败一次时，重置按钮链接将显示在登录窗口中。

### <a name="skype-for-business-security-updates"></a>Skype for Business：安全更新
-   Microsoft 安全公告 [MS17-013](https://technet.microsoft.com/library/security/ms17-013)：Microsoft 图形组件安全更新 (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283)：Windows Uniscribe 远程代码执行漏洞
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550)：Skype for Business 远程代码执行漏洞

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   如果尝试呼叫用户未成功，且已根据策略禁用音频，显示的消息从“无法完成呼叫”更改为“由于 IT 管理员已限制音频，无法呼叫。请尝试改用即时消息或电子邮件，并咨询 IT 管理员。”
-   在已启用 PSTN 会议的 Skype for Business Online 用户的会议邀请中添加了“忘记了拨入 PIN”超链接。
-   允许从 Skype for Business Online 加入团队会议。
-   将默认扬声器会话音量从 40% 更改为 75%。
-   允许重设更小的选项卡列表最小宽度。
-   将快捷键更新为与选项卡的顺序匹配。
-   修复了以下问题：通过移动设备发送希伯来语文本时，文本方向不正确。
-   修复了以下问题：屏幕阅读器中“演示桌面/授予控制权”功能的旁白信息不正确。
-   “选择会议室”列表中除了显示关注的会议室之外，还显示已打开的会议室。
-   添加了在启用自定义 RCC 应用的同时禁用 VoIP 功能的功能。
-   将脱机 IM 标志行更改为“尝试 Skype for Business 移动应用”。
-   修复了导致自动接受的对话的对话窗口以普通窗口而不是最小化窗口模式打开，并意外地将焦点从其他窗口移开的问题。
-   修复了使用“Skype 会议选项”对话框上的屏幕阅读器时遇到的问题。
-   修复了邀请中的第一个邮件不在“错过的对话”电子邮件中显示的问题。
-   修复了使用“新建 Skype 会议”按钮从 Outlook 创建会议邀请时显示重复的拨号号码的问题。
-   修复了在显示滚动条后使用 Ctrl+A 选中全部时未选中 IM 历史记录中的所有对话的问题。
-   修复了使用 Export-CsArchivingData cmdlet 时输出文本的格式可能不完全相同的问题。
-   修复了在有 3 个或更多个与会者的情况下使用“立即开会”时会议组织者无法看到远程与会者视频的问题。
-   修复了用户右键单击与会者列表中的其他用户名字时会议名单的第一行为空白的问题。
-   修复了以下问题：用户在切换内外公司网络后无法登录。
-   修复了在咨询转接中从 IM 升级到音频时，聊天区域不会关闭的问题。
-   修复了所使用的两个端点同时响铃时，toast 通知中的名称被截断的问题。
-   修复了共享通知时，文件中的文件名被截断的问题。
-   添加“返回通话”和转接按钮的工具提示。
-   使“咨询转接”窗口的保持时间用于屏幕阅读器（如讲述人）。
-   添加了可选择 IM 或呼叫作为咨询转接的默认首选项的功能。
-   添加了以下功能：进行咨询式呼叫转移时，右键单击“转接”按钮可以查看联系人的电话号码列表。
-   改进了常见错误消息，以表明问题在于用户具有无效的许可证还是尚未分配许可证。
-   修复了当用户开始与联系人进行对话，然后添加其他联系人时，并非所有联系人都显示在对话窗口标题中的问题。
-   修复了讲述人不读取通知第 2 行的问题。
-   修复了呼叫转移到 VOIP 而不是咨询的号码的问题。
-   修复了当用户在“内容”窗口中导航时，讲述者宣布不正确的信息的问题。
-   修复了以下问题：将鼠标悬停在白板注释上时，看不到创建者和修改者名称

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **查找第三方模具：** 搜索所选内容提供商提供的第三方模具。
-   **幻灯片片段：** 获取 Visio 绘图的片段，并将其作为幻灯片导出到 PowerPoint。 [更多信息](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word：功能更新
-   **Windows 信息保护 (WIP) 支持：**   Word 现在是一个智能型应用，可以区分企业数据和个人数据，并根据配置的策略正确地确定要保护的数据。  [详细信息](https://aka.ms/wiptechnet)
-   **插入最近使用的链接：** 将超链接附加到最近使用的基于云的文件或网站，并为使用屏幕阅读器的用户创建有意义的显示名称。 [更多信息](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **外接程序的集中部署**：管理员可以从 Office 365 管理中心将外接程序部署和更新到用户或组。  [详细信息](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **迪拜字体：** 支持西欧语言和使用阿拉伯语脚本的主要语言的字体系列。 [更多信息](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景消除：** 使用任意格式的绘图工具删除图片背景。
-   **并排：** 通过将页面像一叠纸一样并排滑动实现在页面视图下浏览页面。 [详细信息](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **使用触笔选择和更改对象：** 使用数字触笔捕捉对象句柄，以执行重设大小、旋转、移动等操作。
-   **SVG 图像：** 在文档中插入和编辑可缩放的矢量图形 (SVG)。 [详细信息](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入图标：**  通过转到插入插图图标 (SVG) 文件的标准库中的图标（通过可缩放的矢量图形） \> \> 。  [详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **保存到最近访问的文件夹：** 依次转到“文件”\>“另存为”，使用“最近访问的位置”选项卡，将文档保存到最近访问的文件夹中。
-   **借助学习工具提升阅读技能：** 阅读模式中的新命令可提升阅读技能，具体包括调整文字间距、在音节之间显示分隔符和突出显示每个单词（如同在大声朗读文档一样）。 [更多信息](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **形状识别：** 使用“绘图”\>“转换为形状”将绘图自动转换为形状。 [详细信息](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word：安全更新
-   Microsoft 安全公告 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 安全更新程序 (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292)：Windows PDF 远程代码执行漏洞 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509)：Microsoft Office 远程执行代码漏洞  

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了用户无法搜索 PST 文件的问题。
-   修复了以下问题：用户在“新建 Outlook 数据文件”对话框中看到有新的“Microsoft Exchange”存储类型，但在选择这一新增的数据类型后用户的配置文件就不可用了。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199)：Microsoft Office/WordPad 远程代码执行漏洞 w/Windows API
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260)：Microsoft Office 远程代码执行
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512)：Microsoft Office 远程执行代码漏洞



## <a name="version-1701-may-9"></a>版本1701：5月9
*版本 1701（内部版本 7766.2084）*

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了删除消息时导致用户间歇性地看到消息列表中的所选消息意外跳转的问题。
-   修复了导致间歇性崩溃的问题。
-   添加了 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage 注册表项，以允许管理员以隐藏“文件”选项卡下的支持选项。
-   添加了 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableOutlookFeedbackFeatures 注册表项，以便管理员可以在“文件”\>“反馈”下禁用“Outlook 2016 反馈”和“Outlook 博客”选项。

### <a name="skype-for-business-security-updates"></a>Skype for Business：安全更新
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 远程执行代码漏洞

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复了导致自动接受的对话的对话窗口以普通窗口而不是最小化窗口模式打开，并意外地将焦点从其他窗口移开的问题。

### <a name="word-security-updates"></a>Word：安全更新
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254)：Microsoft Office 内存损坏漏洞
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 远程执行代码漏洞

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262)：Microsoft Office 远程执行代码漏洞
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 远程执行代码漏洞



## <a name="version-1701-april-11"></a>版本1701：4月11日
*版本 1701（内部版本 7766.2076）*

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了以下问题：打开 .xls 工作簿时，新窗口显示为灰色。

### <a name="outlook-security-updates"></a>Outlook：安全更新程序
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106)：Microsoft Outlook 远程代码执行漏洞
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204)：Microsoft Office 安全功能绕过漏洞

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了以下问题：用户在“新建 Outlook 数据文件”对话框中看到有新的“Microsoft Exchange”存储类型，但在选择这一新增的数据类型后用户的配置文件就不可用了。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：用户在将 U 盘等可移动媒体上存储的 PowerPoint 文件“另存”到备用位置时看到图像缺失错误。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复了以下问题：用户在切换公司内外网络后无法登录。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199)：Microsoft Office/WordPad 远程代码执行漏洞 w/Windows API



## <a name="version-1701-march-14"></a>版本1701：3月14
*版本 1701（内部版本 7766.2071）*

### <a name="access-non-security-updates"></a>Access：非安全更新
-   修复了无法取消浮出控件菜单的问题。

### <a name="excel-security-updates"></a>Excel：安全更新
-   Microsoft 安全公告 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 安全更新程序 (3217868)

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了插入超链接时 Excel 可能崩溃的问题。
-   修复了在添加 XML 映射时 Excel 可能发生故障的问题。
-   修复了外接程序升级后或从 Office 应用商店中删除并再次下载该外接程序后，外接程序的命令按钮不起作用的问题。
-   修复了通过 VBA 操作 DLL 工作表时 Excel 可能崩溃的问题。

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新
-   修复了在 Windows 10 版本 1607（也称为 Windows 周年更新）上使用 PIN 进行身份验证后，OneNote 页面画布停止响应鼠标单击的问题。
-   在用户插入可编辑文档（例如 .docx 或 .pptx）时禁用优化的、特定于 EDU 的输出行为。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了合并冲突在共同创作时不正确显示的问题。
-   修复了外接程序升级后或从 Office 应用商店中删除并再次下载该外接程序后，外接程序的命令按钮不起作用的问题。
-   修复了将 VBA对象模型应用于图表中的形状时，调用 VBA对象模型会导致运行时错误的问题。

### <a name="publisher-non-security-updates"></a>Publisher：非安全更新
-   修复了发布服务器不显示 CMYK TIFF 图像的问题。

### <a name="skype-for-business-security-updates"></a>Skype for Business：安全更新
-   Microsoft 安全公告 [MS17-013](https://technet.microsoft.com/library/security/ms17-013)：Microsoft 图形组件安全更新 (4013075)

### <a name="word-security-updates"></a>Word：安全更新
-   Microsoft 安全公告 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 安全更新程序 (3217868)

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了使用某些监视器配置时的内存消耗问题。
-   修复了外接程序升级后或从 Office 应用商店中删除并再次下载该外接程序后，外接程序的命令按钮不起作用的问题。



## <a name="version-1701-february-22"></a>版本1701：2月22日
*版本 1701（内部版本 7766.2060）*

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **改进了数据转换和连接性：** 将列表扩展为在各值之间使用分隔符的新文本列，并在连接 SQL 时指定故障转移选项。
-   **改进了数据转换和连接性：** 现在支持百分比数据类型，并改进了二进制组合和函数创作体验。
-   **OLEDB 连接器：** 在“获取并转换”中使用 OLEDB 连接器创建查询以导入数据，具体方法为指定连接字符串和要执行 SQL 语句（可选）。
-   **墨迹重播：** 依次转到“绘图”\>“墨迹重播”，可以向前和向后重播手写内容以隐藏和显示内容，也可以提供分步说明或更好地理解其他人的思路。 [更多信息](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **CSV (UTF-8) 支持：** 打开和保存使用 UTF-8 字符编码的 CSV 文件。
-   **增强了数据转换功能和连接性：** 从 OData 源加载数据时选择导入相关表，添加包含函数计算值的自定义列，或使用专用视图展示查询之间的依赖关系。
-   **与我共享的内容：** 依次转到“文件”\>“打开”\>“与我共享的内容”，查看其他人与你共享的文档。 [详细信息](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **更改颜色：** 使用“操作说明搜索”来设置字体、突出显示、形状填充等的颜色。 [更多信息](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel：安全更新
-   Microsoft 安全公告 [MS16-148](https://technet.microsoft.com/library/security/ms16-148)：Microsoft Office 安全更新程序 (3204068)

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了以下问题：如果 Office 主题设为“黑色”，用户在“工作簿查询”窗格中右键单击查询时会看到内容为“意外错误”的错误消息。
-   修复了以下问题：Excel 在用户尝试访问数据透视表选项时发生故障。
-   修复了以下问题：在另存为 CSV 或 CSV UTF-8 时，无法正确导出包含文本和双引号的单元格值。
-   修复了以下问题：Excel 在关闭时挂起或发生故障。
-   修复了以下问题：包含连接公式的超链接忽略部分连接结果。
-   修复了以下问题：在 Word 中粘贴 RTF 格式 Excel 表格时，无法保留表格格式。
-   修复了以下问题：当工作簿包含 MS Excel 4.0 宏工作表时，用户无法另存为。
-   设置 CTRL+ALT+5 快捷键，用于将选定内容移到对象层，以与其他应用程序保持一致。
-   修复了以下问题：在编辑栏中键入内容并使用带下拉列表的函数（如 VLOOKUP）时，如果按下 Enter 完成公式，系统会选择自动完成下拉列表中最上面一项，而不是原封不动地保留所键入的值。
-   修复了以下问题：打开受保护的工作表中有超链接的 Excel 97-Excel 2003 二进制文件格式 (BIFF8) 文件时，Excel 认为文件已损坏，并尝试修复或删除不可读取的内容。

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business：非安全更新
-   修复了以下问题：在无法成功加载 GrooveIntlResource.dll 的情况下（通常不太可能会发生这种情况），如果用户尝试打开文件或将文件保存到同步文件夹，Office 应用可能会发生故障，或者如果用户使用 Windows 资源管理器转到同步文件夹，Windows 资源管理器可能会发生故障。
-   修复了以下问题：如果将 Office 配置为从除 Office 内容传送网络 (CDN) 之外的位置接收更新程序，无法禁用 OneDrive for Business，即使将相应的注册表项设置为禁用它，也是如此。

### <a name="onenote-feature-updates"></a>OneNote：功能更新
-   **控制文件和图像同步：** 依次转到“文件”\>“选项”\>“同步”，以控制是否为笔记本中的所有页面自动下载全部文件和图像。

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新
-   修复了以下问题：当打印的图像大于页面时，OneNote 发生故障。
-   修复了以下问题：用户无法删除自定义网页模板。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **针对附件开展实时协作：** 将附件上载到 OneDrive for Business，允许所有人使用最新版本。使用附件上的下拉菜单进行上载或保存。
-   **旅游预订和行程的摘要卡：** 使用收件箱和日历中自动创建的摘要卡验证并跟踪旅游预订以及发送行程。 [更多信息](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **编辑器：** 提供了高级的上下文校对功能，有助于改进撰写内容。 [更多信息](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复了以下问题：用户在右键单击对话附件列表中的附件时，可以看到所有上下文菜单项，而不是只看到适用的菜单项。
-   修复了以下问题：收件人无法打开使用信息权限管理予以发送的 RTF 格式电子邮件。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **隐藏式字幕：** 如果幻灯片中的视频包含隐藏式字幕，可在幻灯片中播放这些字幕。
-   **多音轨：** 如果幻灯片中的视频包含多音轨，可在幻灯片中播放这些音轨。
-   **节复制：** 复制并粘贴演示文稿节。
-   **与我共享的内容：** 依次转到“文件”\>“打开”\>“与我共享的内容”，查看其他人与你共享的文档。 [更多信息](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **墨迹重播：** 可以向前和向后重播手写内容以隐藏和显示内容，也可以提供分步说明或更好地理解其他人的思路。 [详细信息](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **优化录制：** 可以使用录制好的幻灯片、屏幕录像和插入的视频创建演示文稿，然后分享这些录制的内容以进行远程查看。另外，也可以在其中嵌入问卷，帮助远程学习，让你的演示文稿更具交互性，还可以更改墨迹颜色并使用更简单的控件来录制旁白和音频。
-   **设计器改进：** 提供了针对加点符的流程列表使用 SmartArt 的设计建议。
-   **录制功能区选项卡：** 通过自定义功能区添加“录制”选项卡。
-   **更改颜色：** 使用“操作说明搜索”来设置字体、突出显示、形状填充等的颜色。 [详细信息](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **缩放：** 创建带有自动导航链接的演示文稿交互式摘要。 [更多信息](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **打开超链接：** 使用 CTRL+单击，在编辑演示文稿时打开超链接。
-   **文本突出显示：** 使用文本荧光笔突出显示重要文本。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：裁剪图像时，图像的裁剪部分看上去较暗。
-   修复了以下问题：在幻灯片放映模式下，当“讲述人”正在运行时，如果用户单击超链接，PowerPoint 会发生故障，且网站加载缓慢。
-   修复了以下问题：共同创作时，实时键入对表不起作用。
-   修复了以下问题：在安装了 Malwarebytes 3.0 的计算机上打开 PowerPoint 时，看到“已停止运行”错误消息，或 PowerPoint 发生故障。
-   修复了以下问题：“文件”\>“新建”下未显示默认模板。
-   修复了以下问题：当包含嵌入字体的文件自动保存时，文本键入发生中断和延迟。
-   修复了以下问题：无法从 Adobe Illustrator 复制可缩放的矢量图形 (SVG) 图像。

### <a name="project-feature-updates"></a>Project：功能更新
-   **锁定的字段：** 将值设为“是”可禁止团队成员提交任务更新。
-   **日程表标签：** 使用标签为日程表条形图指定描述性名称，从而区分它们。
-   **日程表进度指示器：** 在日程表视图中使用复选标记和彩色进度栏，显示每个任务的进度。
-   **辅助功能改进：** 改进了支持，可以更好地使用键盘、讲述人和其他辅助技术阅读和编辑项目。

### <a name="project-non-security-updates"></a>Project：非安全更新
-   修复了以下问题：在主项目与子项目之间创建跨项目链接时看不到链接线。
-   修复了以下问题：时间分段基线值不能始终正确地保存为 XML 格式，尤其是包含部分工期的工时值和成本值。
-   修复了以下问题：应用状态更新后，实际工时会添加到团队成员未报告的工作分配中。
-   修复了以下问题：系统会显示资源的基线值，即使尚未为资源创建基线，也会显示。
-   修复了以下问题：打印预览会剪切文本，导致文本不可见。
-   修复了以下问题：使用快捷方式 URL 从 SharePoint 打开 .mpp 文件时，文件以已签出的形式打开，即使启用了“是否必须先签出文档，然后才能进行编辑?”设置，也是如此。
-   修复了以下问题：更新 Project Web App 中的材料资源会不正确地更改时间分段数据。
-   修复了以下问题：打开包含里程碑任务的项目会将实际开始日期添加到项目中，即使项目在上次保存时还没有日期，也是如此。
-   修复了以下问题：工作分解结构 (WBS) 重新编号故障。
-   修复了以下问题：当“讲述人”正在运行时，如果用户从基于网格的视图切换到其他视图，Project 发生故障。
-   修复了以下问题：用户打开 XML 文件时，看到的时间分段数据截断错误消息不正确。
-   修复了以下问题：保存基线并未正确设置时间分段值。
-   修复了以下问题：从 XML 文件读取项目数据时，忽略工作分配延迟。
-   修复了以下问题：当用户使用 Project Online 打开文件时，看到“上次修改日期”显示的是 UTC 时间，而不是时区调整后的时间。
-   修复了以下问题：打印表视图时，没有看到非分组行的分组色带。
-   修复了以下问题：当用户检查存在分配超出最大单位问题的任务时，修复选项没有正确显示。
-   修复了以下问题：发布项目后无法更改“大纲代码”字段值。
-   修复了以下问题：甘特条在显示比例为 175% 的高 DPI 屏幕上无法以正确大小显示。
-   修复了以下问题：如果用户通过“任务信息”对话框设置延隔时间，延隔时间会设置为错误的 24 小时制工期。
-   修复了以下问题：在打开某些 XML 文件时，由于工作分配存在问题，无法正确设置任务开始日期。

### <a name="skype-for-business-feature-updates"></a>Skype for Business：功能更新
-   **Windows 通知样式：** 更改了传入呼叫和对话的通知外观。 [更多信息](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **咨询式转移：** 在呼叫中，在将呼叫转移到该用户之前，通过 IM 或呼叫咨询另一个用户。 [详细信息](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **麦克风通知：** 当操作系统中的麦克风静音或麦克风不拾音时，在对话窗口中显示通知。
-   **禁用“我的号码”：** 使用 DisableDisplayMyNumber 注册表项禁止在拨号盘下显示“我的号码”。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   将用来允许或拒绝参与者的介绍按钮从文本更改为图像（X 或选中标记）。
-   将会议提醒通知文本从“接受”更改为“加入”。
-   更新了 IM 发件人在收件人的状态设置为“请勿打扰”时看到的消息。
-   更新了 IM 发件人在收件人处于脱机状态且已禁用“保存到历史记录”时看到的消息，以明确指出收件人不会收到消息。
-   新增以下功能：移动组聊天的聊天历史记录和名单之间的垂直拆分栏。
-   新增以下功能：在 IM 或聊天室窗口中调整选项卡列表的大小。
-   新增以下功能：在创建主题源时选择搜索到的聊天室。
-   修复了以下问题：在对话中途，在聊天历史记录中看不到消息。
-   修复了以下问题：对话窗口显示重复消息。
-   修复了以下问题：在有大量通知的情况下，toast 通知操作（“接受”和“忽略”）不会正确显示。
-   修复了以下问题：使用 Alt+Tab 打开最小化的对话窗口后，用户无法键入消息。
-   修复了以下问题：IM 按钮在用户的联系人卡片中灰显，即使可发送 IM，也是如此。
-   修复了以下问题：多个对话窗口在关闭并重新打开后无法恢复之前的大小和位置。
-   修复了以下问题：选择自定义链接后无法启动。
-   修复了以下问题：“地区”字段中的非英语字符联机会议文本无法正确显示。
-   修复了以下问题：若为从右到左书写的语言，呼叫持续时间等通知信息无法正确呈现。
-   修复了以下问题：创建主题源时，清除搜索结果不会将结果重置为访问过的聊天室列表。
-   修复了以下问题：同时打开多个对话窗口时，Skype for Business 挂起。
-   修复了以下问题：关闭其他所有选项卡后，最后一个对话窗口变为空白。
-   修复了以下问题：禁用选项卡式对话后，默认焦点不在聊天输入区域中。
-   修复了以下问题：会议邀请中没有显示“忘记了你的拨入 PIN?”链接。
-   修复了以下问题：当用户使用显示比例为 175% 或更高比例的高 DPI 屏幕时，“常规和音频设备”页面上的某些文本遭到剪切和截断。
-   修复了以下问题：当“始终开机，始终联网 (AOAC)”计算机因无法访问网络而暂停或恢复时，Skype for Busines 发生故障。
-   修复了以下问题：如果使用 Polycom CX100 设备，通话时检测不到麦克风。
-   修复了以下问题：在 IM 消息中单击 \\\\servername 或 file:// 等链接会看到错误消息，而不是打开相应的位置。
-   修复了以下问题：在使用基于位置的路由的虚拟桌面基础结构 (VDI) 环境中，用户无法拨打或接听 PSTN 呼叫，因为服务器认为用户的位置对 PSTN 呼叫无效。
-   当用户的状态设置为 "请勿打扰" 或 "正在进行演示" 时，请更改 "缺少与 ' 的会话 \<name\> 向 \<Name\> 您发送了 Skype for business 中的邮件" 中的未送达邮件的主题行。
-   开始在设备上捕获首次登录的时间戳作为 [统计数据的](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) 一部分，以帮助确定登录可靠性趋势。
-   修复了以下问题：在 Window 10 版本 1607（亦称为“周年更新”）上，用于共享辅助监视器的选项没有与特定的监视器配置一起显示。
-   修复了以下问题：如果共享者使用第三方 RDP 实现，Skype for Business 在放大共享内容时发生故障。
-   修复了以下问题：用户在虚拟桌面基础结构 (VDI) 环境中单击音频呼叫控件按钮后未看到“音频控件”面板。
-   修复了以下问题：当运行 Windows 7 的用户先共享主监视器，然后切换共享另一台监视器时，出现黑屏。
-   修复了以下问题：无法在搜索输入框或“今天有什么新鲜事?”部分框中输入某些特殊字符（如 & 号）。
-   修复了以下问题：无法在有未读脱机 IM 时显示未读计数。
-   修复了以下问题：“通过电子邮件邀请”模板提到的是 Lync，而不是 Skype。
-   修复了以下问题：拨号盘下方的“我的号码”区域中缺少行号。
-   修复了以下问题：发送聊天消息后，在 IM 输入区域中看不到鼠标指针。
-   修复了以下问题：登录时，Skype for Business 挂起，无法加载缓存池。
-   修复了以下问题：登录和还原对话时，Skype for Business 发生故障。
-   修复了以下问题：在恢复后登录时，Skype for Business 挂起。
-   修复了以下问题：如果两个组织的 Exchange 服务器均禁用 TNEF，会议链接也遭禁用。
-   修复了以下问题：无法在只有一个 IM 对话的情况下重启视频呼叫。
-   修复了以下问题：将白板另存为 PNG 文件时，丢失白板上的文本注释。
-   修复了以下问题：在 IM 窗口中使用日语输入超过两行时，第一行被隐藏。
-   修复了以下问题：名称中的 & 号字符被错误地替换为下划线字符。
-   修复了预定的会议中的“加入联机会议”URL 存在的问题。
-   修复了以下问题：无法通过在窗口上悬停鼠标来激活窗口，即使操作系统已进行了这样的配置，也是如此。
-   修复了以下问题：传出呼叫对话历史记录项显示呼叫方，而不是被叫方。
-   修复了以下问题：按 F12 无法在本地保存对话。
-   修复了以下问题：未读的对话电子邮件不包含初始 IM。
-   修复了以下问题：即使演示者已禁用 IM 参与，仍可以在 IM 文本区域中添加表情符号。
-   修复了“铃声和声音”选项对话框布局存在的问题。
-   修复了以下问题：关闭对话窗口时，Skype for Business 发生故障。
-   修复了以下问题：如果域注册为虚域，免 DNS 登录失败。
-   修复了以下问题：无法正确保存或加载持久聊天通知设置。
-   修复了以下问题：登录后看不到现有对等对话窗口或聊天室，即使已设置重新打开对话，也是如此。
-   修复了以下问题：静音或取消静音当前对话导致其他对话窗口显示，就像有未读消息一样。
-   修复了以下问题：配置了媒体旁路的用户在将通话处于暂候状态后无法通过 PSTN 网关恢复通话。
-   修复了以下问题：使用 RDP 第三方实现时，用户在通过 URL 加入会议时看到的是蓝色框，而不是视频。
-   修复了以下问题：toast 警报中显示的是 SIP 地址的用户部分，而不是显示名称。
-   修复了以下问题：当 Skype for Business 通过端口 443 连接到 SIP 服务器且存在代理服务器时，如果代理不允许此类连接，登录过程会明显延迟。通过在 HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync 下添加 EnableDetectProxyForAllConnections DWORD 注册表项，并将值设置为 1，可以启用修复程序。
-   修复了以下问题：使用选项卡式对话时，如果双击选项卡并开始键入内容，有时会导致焦点移至其他选项卡，但却继续在对话窗口中键入内容。
-   修复了以下问题：无法在聊天历史记录窗口中使用键盘选择即时消息中的 URL。
-   修复了选中“铃声”和“声音”选项下的“查看 IM 对话及键入时播放声音”复选框后，应可以听到键入声音的问题。
-   修复了使用屏幕阅读器（例如 Narrator）时，显示的对话框不通知的问题。
-   修复了第一个运行的教程无法用键盘导航、无法通过屏幕阅读器（例如 Narrator）读取的问题。
-   修复了任务栏状态图标无法在高 DPI 设置中进行缩放的问题。
-   修复了无法使用键盘选择搜索框中的“清除字段”按钮的问题。
-   修复了邀请来自另一个池中的用户时，用户无法启动会议的问题。
-   修复了用户将自己添加到会议时，错误地显示为其他用户的问题。
-   修复了状态更改通知上的联系人状态图标在进行老板的传入呼叫时会隐藏的问题。
-   修复了即时消息窗口中的文本光标闪烁频率与 Windows 中的键盘属性设置不匹配的问题。
-   修复了屏幕阅读器通知组对话的错误的联系人名称的问题。
-   修复了用户使用键盘无法选择多个联系人的问题。
-   修复了无法从 Exchange 中检索用户照片的问题。
-   修复了用户使用直接访问进行连接时，Skype for Business 客户端连接到内部网络上的 Skype for Business Server 而不是外部网络的问题。
-   修复了尝试解析会议所有者的名称时，Skype for Business 客户端崩溃的问题。
-   修复了 Skype for Business 启动或关闭导致 Skype for Business 崩溃的同时，Windows 设置会更改的问题。
-   修复了以下问题：打开持久聊天室中的参与者列表并尝试将键盘焦点移至参与者列表时，Skype for Business 发生故障。
-   修复了以下问题：Skype for Business 在无法连接网络时发生故障，无法继续运行。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **数据库建模外接程序：** 使用外接程序创建现有数据库的数据库模型，以帮助规划新数据库或了解现有数据库。 [更多信息](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [下载外接程序](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **辅助功能改进：** 改进了对键盘、讲述人和其他辅助技术的支持，方便用户处理图形、与他人协同编辑等。
-   **第三方模板和关系图：** 浏览或搜索精选第三方内容提供商提供的新模板和示例图表。缩略图上列出了第三方提供商的名称。
-   **墨迹书写支持：** 使用触笔或手指进行绘画，并使用新的“绘制”选项卡上的工具进行注释。

### <a name="word-feature-updates"></a>Word：功能更新
-   **辅助功能改进：** 改进了支持，可以更好地使用键盘、讲述人和其他辅助技术阅读和编辑文档。 [详细信息](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **编辑器：** 提供了高级的上下文校对功能，有助于改进撰写内容。 [详细信息](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **墨迹重播：** 依次转到“绘图”\>“墨迹重播”，可以向前和向后重播手写内容以隐藏和显示内容，也可以提供分步说明或更好地理解其他人的思路。 [更多信息](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **用自然笔势进行编辑：** 通过画圈选择内容，以及通过划删除线删除内容，对文档进行更改。 [更多信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **与我共享的内容：** 依次转到“文件”\>“打开”\>“与我共享的内容”，查看其他人与你共享的文档。 [详细信息](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **更改颜色：** 使用“操作说明搜索”来设置字体、突出显示、形状填充等的颜色。 [更多信息](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了以下问题：在阅读模式下查看一个文档导致在页面视图中查看第二个文档时无法使用 TAB 键。
-   修复了以下问题：加载多个语法库时 Word 发生故障。
-   修复了以下问题：在绘制两个或三个笔划后，墨迹笔划消失。
-   修复了以下问题：使用 Google 输入法编辑器 (IME) 时，引号消失。
-   修复了以下问题：用户无法在有内容控件或进行非连续选择的情况下使用墨迹书写功能。

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新
-   **提供反馈：** 依次转到“文件”\>“反馈”，提出新功能建议，或告诉 Microsoft 你喜欢的功能或无法使用的功能

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   Microsoft 安全公告 [MS16-148](https://technet.microsoft.com/library/security/ms16-148)：Microsoft Office 安全更新程序 (3204068)

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复了以下问题：在德国键盘上按 CTRL+ALT+7 或 CTRL+ALT+8 会打开用户反馈工具，而不是插入相应的字符。
-   修复了以下问题：安装或更新 Office 时，TraceLogging 导致 Windows 7 发生故障。
-   修复了以下问题：使用墨迹绘图时，按住并释放鼠标按钮导致墨迹轻微移动。
-   修复了以下问题：在 Office 文档中插入 SVG 图像后，SVG 图像在文档保存和重新打开后消失。
-   修复了以下问题：针对非英语用户激活期间，Office 显示以下错误消息：“产品密钥的长度上限为 25 个字符。”
-   修复了以下问题：使用 VBA 窗体可能会导致框架的 z 顺序无法正常运行或显示。
-   修复了以下问题：配置管理器触发的更新将注册表中的 UpdateChannel 设置更改为不是有效更新通道的内容。



## <a name="version-1609-january-10"></a>版本1609：1月10日
*版本 1609（内部版本 7369.2102）*

注意： Microsoft 安全公告 [MS17-002](https://technet.microsoft.com/library/security/ms17-002) 中涵盖的安全更新不适用于此通道版本中的 Word 版本。

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了以下问题：使用“编辑度量值”对话框导致 Excel 发生故障。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复了以下问题：使用形状有时会导致 PowerPoint 发生故障。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复了以下问题：在 Window 10 版本 1607（亦称为“周年更新”）上，用于共享辅助监视器的选项没有与特定的监视器配置一起显示。
-   修复了以下问题：如果共享者使用第三方 RDP 实现，Skype for Business 在放大共享内容时发生故障。
-   修复了以下问题：当 Skype for Business 通过端口 443 连接到 SIP 服务器且存在代理服务器时，如果代理不允许此类连接，登录过程会明显延迟。通过在 HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync 下添加 EnableDetectProxyForAllConnections DWORD 注册表项，并将值设置为 1，可以启用修复程序。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复了以下问题：使用 InsertXML 方法时，显示的是断开的图片链接占位符，而不是实际图像。

