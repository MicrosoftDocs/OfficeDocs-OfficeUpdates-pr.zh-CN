---
title: 每月通道版本中 2015年发行说明
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/11/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: 提供在 2015 Office 365 ProPlus 的发行版的 IT 专业人员使用的每月通道发行说明
ms.openlocfilehash: 0b235ba177dd2378cbb953315e2ead6b692ed52b
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/04/2018
ms.locfileid: "19555918"
---
# <a name="release-notes-for-monthly-channel-releases-in-2015"></a>每月通道版本中 2015年发行说明

这些发行说明提供涉及新功能、 安全更新和非安全更新 2015年在 Office 365 ProPlus 每月通道更新中包含的信息。
 
> [!NOTE]
> - 下面还提供了有关新功能、 安全更新和非安全更新的 Visio Pro for Office 365 和 Project Online 桌面客户端。
> - 此信息也适用于 Office 365 企业版，即附带了一些 Office 365 计划，如企业高级版的 Office 的版本。
> - 每月通道被命名为年 9 月 2017年之前的当前通道。

## <a name="version-1511-december-11"></a>版本 1511年： 年 12 月 11
*版本 1511 （构建 6366.2036）*

### <a name="excel-feature-updates"></a>Excel： 功能更新
-   **BI 模板：** 利用商业智能 (BI) 功能的 Excel 的三个新模板：[日历见解](https://support.office.com/article/7edbeb88-99ca-403f-a394-7e957d3d3f40)，[股票分析](https://support.office.com/article/f65e62ac-7af6-4cc6-98f3-f68b147ed65d)，[我现金流](https://support.office.com/article/215e9e2e-5813-41ad-a9ef-a0c0874841bb)

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   其中拖动断行为长日期数字的单元格的填充柄崩溃使 Excel 修复问题。
-   解决问题其中的数据连接创建数据透视表或数据透视图，并放到新工作表导致 Excel 崩溃。
-   修复其中的数据透视图筛选器按钮不可见的未筛选的基础数据透视表字段时的问题。
-   解决问题时保存个人隐藏的宏工作簿时之前关闭 Excel 数据模型其中会丢失。
-   解决问题其中编辑与在早期版本的 Excel 2016 treemap 图表工作表不是在创建它使 treemap 图表丢失其数据。

### <a name="onenote-feature-updates"></a>OneNote： 功能更新
-   **插入联机视频：** 将 YouTube、 OfficeMix 或 Vimeo 视频嵌入到页。 [详细信息](https://support.office.com/article/0a862f29-665c-43a5-9dd8-68009423cf7c)

### <a name="onenote-non-security-updates"></a>OneNote： 非安全更新
-   与 Office 365 企业版解决问题，其中尝试使用与 SharePoint 的 OneNote 将导致错误消息，告知他们必须升级到 Office 的不同版本的用户。

### <a name="outlook-feature-updates"></a>Outlook： 功能更新
-   **波斯日历：** 添加作为主或备用日历波斯日历。

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题其中邮件列表拖动 scrollbar 使该列表以跳转到列表末尾。

### <a name="powerpoint-feature-updates"></a>PowerPoint： 功能更新
-   **变形转换：** 创建幻灯片之间的无缝切换和动画置于演示文稿更有效地传达概念和信息。 [详细信息](https://support.office.com/article/8dd1c7b2-b935-44f5-a74c-741d8d9244ea)
-   **PowerPoint 设计器：** 允许您采用您的内容并自动生成各种想法可以选择用来使您更好的外观的幻灯片的新服务。 [详细信息](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

    此服务需要 Internet 连接。 若要禁用此功能，[使用最新的组策略管理模板文件](https://www.microsoft.com/download/details.aspx?id=49030)和启用 PowerPoint 设计器选项设置。 您可以找到用户配置下的此策略设置\\管理模板\\Microsoft Office 2016\\工具 |选项 |常规 |服务选项...\\PowerPoint 设计器。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 非安全更新
-   解决问题其中采用动画的 SmartArt 不会显示在幻灯片放映视图与演示者视图预期的顺序。
-   解决问题号码的主要导航无法在幻灯片放映视图。

### <a name="visio-non-security-updates"></a>Visio： 非安全更新
-   在 Visio 中查看 AutoCAD 文件会显示模糊修复问题。

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题无法保存到文档库已必需的列的文档的位置。

### <a name="office-suite-feature-updates"></a>Office 套件： 功能更新
-   **作为选项发送**： 从 Word 或 PowerPoint 中的共享窗格中发送电子邮件作为附件或为 PDF 文档。
-   **插入图片 API**： 使用常见的 office.js 库中[document.setSelectedDataAsync 方法](https://msdn.microsoft.com/library/office/fp142145.aspx)将图像插入到 Word、 Excel 或 PowerPoint。 Word 的 JavaScript API 提供特定于宿主的方法调用 insertInlinePictureFromBase64() 设置[正文](https://msdn.microsoft.com/library/office/mt598674.aspx)、 [ContentControl](https://msdn.microsoft.com/library/office/mt598675.aspx)、[段落](https://msdn.microsoft.com/library/office/mt598682.aspx)和 Range 对象上的嵌入式图片。

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   解决问题的修改日期信息时执行打开或另存为操作显示被截断的位置。
-   解决问题的 SmartArt 图形的文本窗格中双击其中导致应用程序崩溃。
-   其中安装过程中播放视频将一直保留在黑屏它完成后，关闭"安装已完成"对话框之前修复问题。
-   将鼠标悬停在受保护文档中的"受保护的视图"通知其中使该通知以通过很宽滚动按钮遮盖修复问题。
-   其中，计划 Office 更新的通知被截断哈萨克语和匈牙利语修复问题。
-   修复其中固定快捷方式在任务栏上不会删除所有用户手动升级过程中的问题。
-   解决问题其中自动升级过程中由与许可相关的操作导致的失败离开而无需 Office 安装的用户。
-   其中有 Office 预安装工具包在审核模式下运行的 Windows 7 OEM 计算机上升级到 Office 2016 导致错误 0x80070005 激活期间修复问题。


## <a name="version-1509-december-8"></a>版本 1509年: 12 月 8 日
*版本 1509 （构建 6001.1043）*

### <a name="onenote-non-security-updates"></a>OneNote： 非安全更新
-   修复其中 XPS 或打印版本创建使用 Windows 的桌面客户端显示为红色 X 在非 Windows 桌面客户端，因为这些客户端不支持本机 XPS 呈现问题。

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   修复的问题在其中创建书签跨越多个段落，但当收到电子邮件时，转到使用时，则仅书签的第一段处于选中状态。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 安全更新
-   Microsoft 安全公告[MS15 128](https://go.microsoft.com/fwlink/?LinkId=690559): Microsoft 图形组件地址远程代码执行 (3104503) 的安全更新

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   修复应用程序共享会话的故障其中，尤其是期间突发通信问题。
-   修复，如果第一个应用程序启动之后安装 Office 2016 崩溃导致 for Business 的 Skype 的问题。

### <a name="word-security-updates"></a>Word： 安全更新
-   Microsoft 安全公告[MS15 131](https://go.microsoft.com/fwlink/?LinkId=699410): Microsoft Office，以解决远程代码执行 (3116111) 的安全更新

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   修复问题，其中不中断连字符时，显示为一个方形使用某些字体。

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   更改将在后台的更新从缓存/位下载到 HTTP 默认传输类型。
-   解决问题其中自动升级过程中由与许可相关的操作导致的失败离开而无需 Office 安装的用户。
-   其中有 Office 预安装工具包在审核模式下运行的 Windows 7 OEM 计算机上升级到 Office 2016 导致错误 0x80070005 激活期间修复问题。



## <a name="version-1509-november-10"></a>版本 1509年： 年 11 月 10
*版本 1509 （构建 6001.1038）*

### <a name="access-security-updates"></a>Access： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="excel-security-updates"></a>Excel： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="excel-non-security-updates"></a>Excel： 非安全更新
-   录制宏查询创建其中导致编译错误修复问题。
-   其中，在删除某个列在查询编辑器中后，空白列结尾处出现表的刷新查询后修复问题。
-   快速分析的查询表中选择迷你图选项卡时，其中发生意外的错误修复问题。
-   其中，在执行剪切和粘贴操作中的查询表后，您无法刷新该查询使用工作簿查询窗格修复问题。
-   修复的问题刷新查询，将焦点移到其关联的查询表的表。
-   删除对电源查询有关受支持的 OData 版本的错误消息中的引用。
-   修复 Power 查询功能其中显示为可用，但不起作用，当产品未激活问题。
-   更新文件中的 Dotlesscss URL\>帐户\>有关 Excel。

### <a name="onenote-security-updates"></a>OneNote： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   解决问题不会显示将文本粘贴到 Outlook 全文如果粘贴文本的量大于窗口的高度。

### <a name="powerpoint-security-updates"></a>PowerPoint： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="project-security-updates"></a>项目： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="publisher-security-updates"></a>Publisher： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="skype-for-business-security-updates"></a>Skype for Business： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新
-   Microsoft 安全公告[MS15 123](https://technet.microsoft.com/library/security/ms15-123): Skype 商业和 Microsoft Lync，以解决信息泄露 (3105872) 的安全更新

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   使用具有两个输入的麦克风设备上的音频干扰修复问题。
-   解决问题用户无法成功加入会议后恢复休眠模式的便携式计算机和 Skype 之前客户端已签名后中。
-   添加上下文的消息，可帮助向用户提供的功能的认知度的支持。
-   更新以将用户指引到正确的位置在 ui 中更改设置加入会议音频对话框中的文本。
-   通知用户，请参阅时遇到同时发送和接收网络问题与解决问题。

### <a name="visio-security-updates"></a>Visio： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="word-security-updates"></a>Word： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题的脚注编号不与 Word 中的显示和打印输出之间时在后台打印文档已设置为"重新开始编号每一页"的脚注。
-   解决问题，其中实时共同创作不使用文件存储在 OneDrive，包括用户不显示给其他人为实时编辑并没有可用的状态信息。
-   从 SharePoint 或 OneDrive 期间对文档的实时共同创作 Word 崩溃的打开位置修复问题。
-   修复的格式的问题，这将导致表放置到 HTML 时无法正确呈现电子邮件中 Outlook 和窗口大小进行调整。

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   Microsoft 安全公告[MS15 116](https://technet.microsoft.com/library/security/ms15-116): Microsoft Office，以解决远程代码执行 (3104540) 的安全更新

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   修复其中反复提示用户登录尝试从 SharePoint Online 中打开文件时的问题。
-   修复其中固定快捷方式在任务栏上不会删除所有用户手动升级过程中的问题。
-   添加用于检测如果 Outlook 连接到 Exchange Server 2007 或 Business Contact Manager 安装才能警告的可能的升级问题的用户单击即点即用手动升级过程的功能。
-   使对话结束进程更可见期间卸载或升级，因为这些对话框可以获取对用户隐藏的后面打开应用程序或其他用户界面。
-   解决问题，用户不获取登录到 Office 应用程序自动时用作标识的计算机加入域和云域。



## <a name="version-1509-october-21"></a>版本 1509年： 年 10 月 21
*版本 1509 （构建 6001.1034）*

### <a name="onenote-non-security-updates"></a>OneNote： 非安全更新
-   修复，导致 OneNote 崩溃相同的边框颜色选择颜色选取器中出现两次时的问题。

### <a name="outlook-non-security-updates"></a>Outlook： 非安全更新
-   在其中屏幕阅读器仅读取多段落电子邮件签名的第一段编辑电子邮件签名时修复问题。
-   解决问题光标位置不在编写或答复电子邮件时在正确的位置。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   内存不足的情况，尝试查看共享的桌面或应用程序中的位置，将导致断开连接，并尝试自动重新连接并查看共享的桌面或应用程序的重复修复问题。
-   其中，参与者增加数，作为共享的桌面体验恶化修复问题。
-   配置多重身份验证，电话身份验证的重复的提示在一天的接收位置时，请修复问题。

### <a name="visio-non-security-updates"></a>Visio： 非安全更新
-   其中插入显示为图标的 Word 对象为空后关闭并重新打开 Visio 修复问题。

### <a name="word-non-security-updates"></a>Word： 非安全更新
-   解决问题，其中共同创作不可用，在 SharePoint Server 2013 文档时，可获取锁定文档。
-   其中 table 是可见的即使表中的内容必须包含隐藏选项的样式应用于其 docx 文档中解决问题。
-   解决问题带有相对的超链接的文档无法保存后执行自动更正的位置。
-   解决问题周围带有镜像缩进的文档中的段落的编辑过程中快速行。
-   修复其中行显示不一致编辑禁用子像素定位时过程中的问题。
-   解决问题其中单击第一个其中将标记为已完成的多个批注注释的弹出窗口会崩溃。
-   使用不正确的线条损坏修复问题。
-   解决问题，其中运行宏的文档中标题 textbox 中使用 TransformDocument 函数或页脚会导致崩溃。
-   解决问题.docm 文档 （英文） 打开文档时，其中就删除所有 ActiveX 控件导致错误。
-   其中 ContentControlOnExit 事件不会触发时在页眉单击修复问题。
-   解决问题跟踪更改其中显示具有相同名称的审阅者的删除。
-   保存的配置以移除个人信息其中更改显示修订为每个时间文档的文档的实时共同创作的问题的修补程序。

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   解决问题，其中第一次打开 Office 应用程序升级到 2016年后导致应用程序正在处于缩减的功能模式，需要重新启动以获取完整功能的应用程序。
-   其中运行 Office 与共享计算机激活时打开，告知用户他们需要使用 Office 的批量许可版本的应用程序，在出错，运行远程桌面服务结果的计算机上启用修复问题。
-   安装滞留在约 90%完成修复问题。
-   解决问题时它们不应是其中本地化产品名称。
-   解决问题，其中的工具提示和快捷键的"告诉我"的提示不匹配，与在不同的本地化版本中的功能区上的其他键提示冲突。
-   其中 Windows 显示 Outlook 作为新应用程序的升级后从 Office 2013 到 Office 2016 修复问题。
-   从 Office 2013 版本 15.0.4615.1002 （2014 年 5 月） 升级到 Office 2016 其中导致 0x80041015 错误修复问题。



## <a name="version-1509-october-5"></a>版本 1509年: 10 月 5 日
*版本 1509 （构建 4229.1029）*

### <a name="onenote-non-security-updates"></a>OneNote： 非安全更新
-   与 Office 365 企业版解决问题，其中尝试使用与 SharePoint 的 OneNote 将导致错误消息，告知他们必须升级到 Office 的不同版本的用户。
-   为 Surface Pro 3 其中视频录制预览不会显示正在录制内容修复问题。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 非安全更新
-   更改查看者看到的内容时共享者 RDP 中锁定屏幕。 查看器立即显示通知，而不是 RDP 暂停图像。

### <a name="office-suite-non-security-updates"></a>Office 套件： 非安全更新
-   修复的即点即单击问题的 Office 2013 单击即点即用服务不还原，如果由于错误或用户取消而未完成对 Office 2016 的自动更新。
-   修复单击即点即用问题其中对 Office 2016 的自动更新期间的故障导致失败的更新且不能够使用或卸载 Office 2013 应用程序。
-   单击即点即用问题其中重新尝试自动更新到 Office 2016 在上一过程中重新启动后尝试更新的修复指向更新失败并无法关闭。
-   修复的即点即单击问题在安装过程中的流任务不是能够成功恢复如果重新启动计算机。
-   修复的即点即单击问题其中对 Office 2016 手动更新过程中重新启动离开任务"执行"状态。
-   修复的即点即单击问题其中期间安装中间启动新安装的应用程序处理在"Internet 连接丢失"对话框中显示的结果。
-   修复其中显示在安装过程中的应用程序图块并不是活动不启动应用程序，当用户单击应用程序图块的即点即单击问题。
-   修复其中自动更新到 Office 2016 sr-latn cr 安装不转换为客户端语言 sr-latn rs 单击即点即用问题。
-   修复其中自动更新失败时准备更新多个 Office Sku 时安装在计算机上的即点即单击问题。
-   修复的即点即单击问题如果手动更新已启动自动更新运行时错误对话框的显示位置。
-   更新对"加载项"产品其中术语的大写不正确的 UI 中的引用。



## <a name="version-1509-september-22"></a>版本 1509年： 年 9 月 22
*版本 1509 （构建 4229.1024）*

这是此频道的初始版本。 此版本中提供了 Office 2016 应用程序的第一个可用性。

### <a name="excel-security-updates"></a>Excel： 安全更新
-   Microsoft 安全公告[MS15 099](https://technet.microsoft.com/library/security/ms15-099): Microsoft Office 中的漏洞可能允许远程代码执行 (3089664)
-   Microsoft 安全公告[MS15 110](https://technet.microsoft.com/library/security/ms15-110)： 安全更新 for Microsoft Office，以解决远程代码执行 (3096440)

### <a name="visio-security-updates"></a>Visio： 安全更新
-   Microsoft 安全公告[MS15 081](https://technet.microsoft.com/library/security/ms15-081): Microsoft Office 中的漏洞可能允许远程代码执行 (3080790)

### <a name="word-security-updates"></a>Word： 安全更新
-   Microsoft 安全公告[MS15 081](https://technet.microsoft.com/library/security/ms15-081): Microsoft Office 中的漏洞可能允许远程代码执行 (3080790)

### <a name="office-suite-security-updates"></a>Office 套件： 安全更新
-   Microsoft 安全公告[MS15 081](https://technet.microsoft.com/library/security/ms15-081): Microsoft Office 中的漏洞可能允许远程代码执行 (3080790)
-   Microsoft 安全公告[MS15 099](https://technet.microsoft.com/library/security/ms15-099): Microsoft Office 中的漏洞可能允许远程代码执行 (3089664)
