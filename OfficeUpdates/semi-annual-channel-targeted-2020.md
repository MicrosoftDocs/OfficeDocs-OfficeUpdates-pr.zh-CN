---
title: 有关 2020 年半年频道（已设定目标）发行的发行说明
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2020 年 Office 365 专业增强版半年频道（已设定目标）发行的发行说明
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978710"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>有关 2020 年半年频道（已设定目标）发行的发行说明

这些发行说明提供了 2020 年 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 Business 的半年频道（已设定目标）更新中所包含的新功能和非安全更新的相关信息。

> [!NOTE]
>
> - 我们经常会过一段时间就将功能（有时甚至是修补程序）发布到半年频道（定向）更新。 如果没有立即看到下述内容，则很快就会看到的。 [了解更多](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams 包含在半年频道(定向)的新安装中，从版本 1902 开始。 当半年频道(定向)的现有安装更新到版本 1908 或更高版本时，将向现有安装添加 Teams。 有关详细信息，请参阅[使用 Office 365 专业增强版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。

## <a name="version-1908-february-11"></a>版本 1908：2 月 11 日
*版本 1908（内部版本 11929.20606）*

[此处](https://docs.microsoft.com/zh-CN/officeupdates/office365-proplus-security-updates)列出安全更新


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


- 解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到崩溃的问题。 [此处](https://support.microsoft.com/zh-CN/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是单个 KB，包含针对先前版本记录的问题。

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

[此处](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)列出安全更新


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