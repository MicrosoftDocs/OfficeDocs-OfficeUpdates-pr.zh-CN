---
title: 2015中的每月频道发布的发行说明
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/11/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人员提供有关 Office 365 专业增强版的每月频道发布的发行说明2015
ms.openlocfilehash: 0b235ba177dd2378cbb953315e2ead6b692ed52b
ms.sourcegitcommit: 358a0cbd1b722d309556c50d53abbe6c1a348f60
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "32438804"
---
# <a name="release-notes-for-monthly-channel-releases-in-2015"></a>2015中的每月频道发布的发行说明

这些发行说明提供了有关在2015中的 Office 365 专业增强版的每月频道更新中包含的新功能、安全更新和非安全更新的信息。
 
> [!NOTE]
> - 以下说明还提供了有关 Visio Pro for Office 365 和 Project Online 桌面客户端的新功能、安全更新和非安全更新的信息。
> - 此信息还适用于 Office 365 商业版，即随附一些 Office 365 计划的 Office 版本（如企业高级版）。
> - 每月频道的名称为9月2017日之前的当前频道。

## <a name="version-1511-december-11"></a>版本 1511:12 月11日
*版本 1511（内部版本 6366.2036）*

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **BI 模板:** 利用 Excel 的商业智能 (BI) 功能的三个新模板:[日历见解](https://support.office.com/article/7edbeb88-99ca-403f-a394-7e957d3d3f40)、[股票分析](https://support.office.com/article/f65e62ac-7af6-4cc6-98f3-f68b147ed65d)、我的[现金流量](https://support.office.com/article/215e9e2e-5813-41ad-a9ef-a0c0874841bb)

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   修复了拖动格式为使用数字作为长日期的单元格的填充手柄导致 Excel 崩溃的问题。
-   修复从数据连接创建数据透视表或数据透视图并将其置于新表中导致 Excel 崩溃的问题。
-   修复当未对基础数据透视表字段进行筛选时数据透视图的筛选按钮不可见的问题。
-   修复当存在隐藏的私人宏工作簿时，在保存之前关闭 Excel 导致数据模型丢失的问题。
-   修复在其创建所在的 Excel 2016 早期版本中使用树图编辑工作表导致树图丢失数据的问题。

### <a name="onenote-feature-updates"></a>OneNote：功能更新
-   **插入联机视频：** 将 YouTube、OfficeMix 或 Vimeo 视频嵌入到页面中。 [更多信息](https://support.office.com/article/0a862f29-665c-43a5-9dd8-68009423cf7c)

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新
-   解决 Office 365 商业版问题，即尝试结合使用 SharePoint 和 OneNote 时会看到错误消息，提示用户需要升级到其他版本的 Office。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **波斯语日历：** 添加波斯日历作为主要或备用日历。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复在消息列表中拖动滚动条导致列表跳到末尾的问题。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **Morph 转换：** 在幻灯片之间创建无缝转换并为演示文稿添加动画功能，以便更有效地传达概念和信息。 [详细信息](https://support.office.com/article/8dd1c7b2-b935-44f5-a74c-741d8d9244ea)
-   **PowerPoint 设计器：** 允许您提取内容并自动生成各种想法，使您可从中选择以使您的幻灯片效果更佳的新服务。 [更多信息](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

    此服务需要 Internet 连接。 若要禁用此功能, 请[使用最新的组策略管理模板文件](https://www.microsoft.com/download/details.aspx?id=49030)并启用 PowerPoint 设计器选项设置。 可以在 "用户配置\\管理模板\\" 下找到此策略设置 Microsoft\\Office 2016 Tools |选项 |常规 |服务选项 .。。\\PowerPoint 设计器。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全更新
-   修复带有动画的 SmartArt 在演示者视图中不按预期顺序出现在幻灯片放映视图中的问题。
-   修复数字键导航在幻灯片放映视图中不起作用的问题。

### <a name="visio-non-security-updates"></a>Visio：非安全更新
-   修复在 Visio 中查看的 AutoCAD 文件看起来模糊不清的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复文档无法保存在具有所需列的文档库中的问题。

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新
-   **代理发送选项**：在 Word 或 PowerPoint 中从“共享”窗格将文档作为附件或 PDF 发送。
-   **插入图片 API**：使用通用 office.js 库中的 [document.setSelectedDataAsync 方法将图像插入 Word、](https://msdn.microsoft.com/library/office/fp142145.aspx)Excel 或 PowerPoint。 Word JavaScript API 提供了特定于主机的方法, 称为 insertInlinePictureFromBase64 (), 用于在[Body](https://msdn.microsoft.com/library/office/mt598674.aspx)、 [ContentControl](https://msdn.microsoft.com/library/office/mt598675.aspx)、[段落](https://msdn.microsoft.com/library/office/mt598682.aspx)和 Range 对象上设置内联图片。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复执行“打开”或“另存为”操作时显示的“修改日期”信息被截断的问题。
-   修复在 SmartArt 图形的文本窗格中双击导致应用崩溃的问题。
-   修复在安装过程中播放的视频在播放完之后仍显示在黑色屏幕上，直到关闭“安装完成”对话框的问题。
-   修复将鼠标悬停在受保护文档中的“受保护视图”通知上时导致通知被一个很宽的滚动按钮覆盖的问题。
-   修复哈萨克语和匈牙利语中计划进行 Office 更新的通知被截断的问题。
-   解决所有用户在手动升级过程中无法删除固定在任务栏上的快捷方式的问题。
-   修复在自动升级过程中由于与许可相关的操作导致的失败使用户未能完成 Office 安装的问题。
-   修复在 Office 预安装工具包在审核模式下运行的 Windows 7 OEM 计算机上升级到 Office 2016 时导致激活过程中出现错误 0x80070005 的问题。


## <a name="version-1509-december-8"></a>版本 1509:12 月8日
*版本 1509（内部版本 6001.1043）*

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新
-   修复由于非 Windows 桌面客户端不支持本机 XPS 呈现，使用 Windows 桌面客户端创建的 XPS 或打印输出在非 Windows 桌面客户端中显示为一个红色 X 的问题。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复书签跨多个段落创建，但当收到电子邮件时，使用“转到”时仅选择书签的第一段的问题。

### <a name="skype-for-business-security-updates"></a>Skype for Business：安全更新
-   Microsoft 安全公告 [MS15-128](https://go.microsoft.com/fwlink/?LinkId=690559)：可修复远程执行代码的 Microsoft 图形组件安全更新 (3104503)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复应用共享会话失败（尤其是在突发通信期间）的问题。
-   修复在安装 Office 2016 后第一个启动 Skype for Business 时导致其崩溃的问题。

### <a name="word-security-updates"></a>Word：安全更新
-   Microsoft 安全公告 [MS15-131](https://go.microsoft.com/fwlink/?LinkId=699410)：可解决远程执行代码的 Microsoft Office 安全更新 (3116111)

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复在使用某些字体时不间断连字符显示为正方形的问题。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   将后台中对下载更新的默认传输从 Cached/BITS 更改到 HTTP。
-   修复在自动升级过程中由于与许可相关的操作导致的失败使用户未能完成 Office 安装的问题。
-   修复在 Office 预安装工具包在审核模式下运行的 Windows 7 OEM 计算机上升级到 Office 2016 时导致激活过程中出现错误 0x80070005 的问题。



## <a name="version-1509-november-10"></a>版本 1509:11 月10日
*版本 1509（内部版本 6001.1038）*

### <a name="access-security-updates"></a>Access：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="excel-security-updates"></a>Excel：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="excel-non-security-updates"></a>Excel：非安全更新
-   解决记录查询创建宏导致编译错误的问题。
-   解决在删除查询编辑器中的列并刷新查询后，表格的末尾处出现空白列的问题。
-   解决在选择查询表的“快速分析”中的“迷你图表”选项卡时，出现意外错误的问题。
-   解决在查询表中执行剪切和粘贴操作之后，您无法使用“工作簿查询”窗格刷新查询的问题。
-   解决在您刷新查询时，焦点转移到相关查询表的工作表的问题。
-   根据有关受支持的 OData 版本的错误消息，移除对 Power Query 的引用。
-   解决当产品尚未激活时 Power Query 功能显示为可用但不起作用的问题。
-   更新“文件”\>“帐户”\>“关于 Excel”中的 Dotlesscss URL。

### <a name="onenote-security-updates"></a>OneNote：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   解决在粘贴的文本量大于窗口高度时，Outlook 不会显示粘贴的全部文本的问题。

### <a name="powerpoint-security-updates"></a>PowerPoint：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="project-security-updates"></a>Project：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="publisher-security-updates"></a>Publisher：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="skype-for-business-security-updates"></a>Skype for Business：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)
-   Microsoft 安全公告 [MS15-123](https://technet.microsoft.com/library/security/ms15-123)：可修复信息泄漏的 Skype for Business 和 Microsoft Lync 安全更新 (3105872)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   解决有两个输入麦克风的设备上的音频噪声问题。
-   解决用户在将笔记本电脑从休眠模式恢复后，以及在 Skype 客户端重新登录前，无法成功加入会议的问题。
-   添加对上下文消息的支持，帮助用户注意到功能。
-   更新“加入会议音频”对话框中的文本，将用户引导至 UI 中的正确位置来更改设置。
-   解决用户在遇到发送和接收网络问题时看到的通知的相关问题。

### <a name="visio-security-updates"></a>Visio：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="word-security-updates"></a>Word：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="word-non-security-updates"></a>Word：非安全更新
-   解决在后台打印已将脚注设置为“每页重新开始编号”的文档时，Word 显示和打印结果中的脚注编号不一致的问题。
-   解决实时共同创作对存储在 OneDrive 中的文件无效的问题，包括实时编辑时当前用户不向其他用户显示，以及无联机状态信息。
-   解决在实时共同创作从 SharePoint 或 OneDrive 打开的文档期间，Word 发生故障的问题。
-   解决导致在窗口调整大小时，Outlook 内 HTML 电子邮件中嵌入的表格无法正确呈现的格式设置问题。

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   Microsoft 安全公告 [MS15-116](https://technet.microsoft.com/library/security/ms15-116)：可解决远程执行代码的 Microsoft Office 安全更新 (3104540)

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   解决用户在尝试从 SharePoint Online 打开文件时反复收到登录提示的问题。
-   解决所有用户在手动升级过程中无法删除固定在任务栏上的快捷方式的问题。
-   添加使用即点即用手动升级流程的功能，以检测 Outlook 是否连接到 Exchange Server 2007，或 Business Contact Manager 是否安装以警告用户可能在升级中出现的问题。
-   在卸载或升级过程中，结束进程的对话更显眼，因为这些对话可以隐藏在打开的应用或其他 UI 后面，不让用户看见。
-   解决当计算机被识别为加入域和云域时，用户无法自动登录 Office 应用的问题。



## <a name="version-1509-october-21"></a>版本 1509:10 月21日
*版本 1509（内部版本 6001.1034）*

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新
-   修复在颜色选取器中为某个边框两次选择同一种颜色时导致 OneNote 崩溃的问题。

### <a name="outlook-non-security-updates"></a>Outlook：非安全更新
-   修复编辑电子邮件签名时屏幕阅读器仅读取多段落电子邮件签名的第一段的问题。
-   修复撰写或回复电子邮件时光标位置不正确的问题。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   修复在内存不足的情况下，尝试查看共享桌面或应用导致连接断开并重复尝试自动重新连接和查看共享桌面或应用的问题。
-   修复随着参与者数量增加，共享桌面体验下降的问题。
-   修复当配置多重身份验证时，在一天内收到电话身份验证的重复提示的问题。

### <a name="visio-non-security-updates"></a>Visio：非安全更新
-   修复原本应显示为图标的插入 Word 对象在关闭并重新打开 Visio 后显示为空的问题。

### <a name="word-non-security-updates"></a>Word：非安全更新
-   修复当文档位于 SharePoint Server 2013 上时共同创作不可用且文档可能锁定的问题。
-   修复 docx 文档中即使表中的内容应用了包含隐藏选项的样式时，表仍然可见的问题。
-   修复执行自动更正后无法保存包含相对超链接的文档的问题。
-   修复在编辑具有镜像缩进的文档中的某个段落时行跳来跳去的问题。
-   修复禁用子像素定位时行显示在编辑期间不一致的问题。
-   修复在单击具有多个注释的注释弹出窗口，且第一个注释标记为“完成”时导致崩溃的问题。
-   修复换行不正确的问题。
-   修复运行宏导致崩溃的问题，该宏在页面或页脚中具有文本框的文档中使用 TransformDocument 函数。
-   修复当 .docm 文档处于打开状态时删除所有 ActiveX 控件导致错误的问题。
-   修复单击进入页眉时未触发 ContentControlOnExit 事件的问题。
-   修复跟踪更改为名称相同的审阅者显示删除的问题。
-   修复在对配置为删除个人信息的文档进行实时共同创作时，每次保存文档时更改都显示为已跟踪更改的问题。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   修复在升级到 2016 后第一次打开 Office 应用时导致应用处于功能缩减模式且要求应用重新启动才能获得完整功能的问题。
-   修复在运行远程桌面服务的计算机上启用共享计算机激活的情况下运行 Office 导致在打开应用时出现错误，告知用户需使用 Office 批量许可版本的问题。
-   修复安装在大约完成 90% 时卡住的问题。
-   修复产品名称在不需要的时候被本地化的问题。
-   修复不同本地化版本中“告诉我”的工具提示和键提示不匹配且与功能区上的其他键提示冲突的问题。
-   修复从 Office 2013 升级到 Office 2016 之后 Windows 将 Outlook 显示为新应用的问题。
-   修复从 Office 2013 版本 15.0.4615.1002（2014 年 5 月）升级到 Office 2016 导致 0x80041015 错误的问题。



## <a name="version-1509-october-5"></a>版本 1509:10 月5日
*版本 1509（内部版本 4229.1029）*

### <a name="onenote-non-security-updates"></a>OneNote：非安全更新
-   解决 Office 365 商业版问题，即尝试结合使用 SharePoint 和 OneNote 时会看到错误消息，提示用户需要升级到其他版本的 Office。
-   解决 Surface Pro 3 问题，即视频录制预览不显示正在录制的内容。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business：非安全更新
-   更改当共享者在 RDP 中锁定屏幕时，查看者看到的内容。查看者现在看到的是通知，而不是 RDP 暂停图像。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全更新
-   解决即点即用问题，即因错误或用户取消而导致无法完成自动更新为 Office 2016 时，Office 2013 即点即用服务无法恢复。
-   解决即点即用问题，即在自动更新为 Office 2016 期间出现故障，导致更新失败，并且无法使用或卸载 Office 2013 应用。
-   解决即点即用问题，即在上一次更新尝试期间重启后，重新尝试自动更新为 Office 2016，导致更新失败且无法关闭。
-   解决即点即用问题，即重启计算机后无法成功恢复安装过程中的流任务。
-   解决即点即用问题，即在手动更新为 Office 2016 期间重启会遗留下处于“正在执行”状态的任务。
-   解决即点即用问题，即在安装中途启动新安装的应用会导致系统显示“Internet 连接断开”对话框。
-   解决即点即用问题，即安装过程中出现的应用磁贴不可用，用户在单击应用磁贴后无法启动应用。
-   解决即点即用问题，即将 sr-latn-cr 安装自动更新为 Office 2016 没有将客户端语言转换为 sr-latn-rs。
-   解决即点即用问题，即当计算机上安装了多个 Office SKU 时，准备更新时自动更新发生故障。
-   解决即点即用问题，即在一边运行自动更新一边启动手动更新时，出现错误对话。
-   更新产品 UI 中对“外接程序”的引用，其中字词大写是错误的。



## <a name="version-1509-september-22"></a>版本 1509: 9 月22日
*版本 1509（内部版本 4229.1024）*

这是此分支的初始版本。在此版本中，Office 2016 应用程序首次可用。

### <a name="excel-security-updates"></a>Excel：安全更新
-   Microsoft 安全公告 [MS15-099](https://technet.microsoft.com/library/security/ms15-099)：Microsoft Office 中的漏洞可能允许远程执行代码 (3089664)
-   Microsoft 安全公告 [MS15-110](https://technet.microsoft.com/library/security/ms15-110)：可修复远程执行代码的 Microsoft Office 安全更新 (3096440)

### <a name="visio-security-updates"></a>Visio：安全更新
-   Microsoft 安全公告 [MS15-081](https://technet.microsoft.com/library/security/ms15-081)：Microsoft Office 中的漏洞可能允许远程执行代码 (3080790)

### <a name="word-security-updates"></a>Word：安全更新
-   Microsoft 安全公告 [MS15-081](https://technet.microsoft.com/library/security/ms15-081)：Microsoft Office 中的漏洞可能允许远程执行代码 (3080790)

### <a name="office-suite-security-updates"></a>Office 套件：安全更新
-   Microsoft 安全公告 [MS15-081](https://technet.microsoft.com/library/security/ms15-081)：Microsoft Office 中的漏洞可能允许远程执行代码 (3080790)
-   Microsoft 安全公告 [MS15-099](https://technet.microsoft.com/library/security/ms15-099)：Microsoft Office 中的漏洞可能允许远程执行代码 (3089664)
