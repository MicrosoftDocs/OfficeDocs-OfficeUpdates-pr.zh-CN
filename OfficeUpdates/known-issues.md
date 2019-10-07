---
title: Office 365 专业增强版已知问题
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: 提供有关 Office 365 专业增强版已知问题的信息
ms.openlocfilehash: 18082351f0ed6df9b50e5c1193adb2d85a2da40a
ms.sourcegitcommit: 01ac73d10be11b830776836c70d0a0efe4e7aafc
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/04/2019
ms.locfileid: "37391306"
---
# <a name="office-365-proplus-known-issues"></a>Office 365 专业增强版已知问题

这些已知问题提供了 2019 年 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 Business 的每月频道、SACT 和 SAC 更新中所包含的非安全更新的相关信息。

下表简要介绍了当前处于活动状态的问题以及已解决的问题。  我们将用正在调查的重要问题来更新下表。

 > [!NOTE]
 >- 此列表并不全面。

<br>

## <a name="september-2019"></a>2019 年 9 月

|摘要|正在调查|已解决|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
我们发现了一个阻止将超链接粘贴到某些受保护工作表中的问题。|SACT 版本 1908 <br> SAC 版本 1902|每月版本 1909 <br> (16.0.12026.20264)|
我们在 Excel 创意功能中发现一个问题，通过单击 Win32 客户端中的创意按钮加载外接程序时出错。||每月版本 1909 <br> (16.0.12026.20264)|
我们发现一个问题，在外接程序管理器中浏览时仅显示 16 个外接程序。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)|
|**Outlook**
发现了使文件无法保存到 WebDAV 位置的问题。||每月版本 1909 <br> (16.0.12026.20264)|
解决了导致简单悬停 URL 无法显示某些安全链接的问题。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)|
我们发现了更新 Outlook 中的附件阻止逻辑也阻止 python 附件的问题。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)|
解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)|
|**PowerPoint**
我们发现了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)|
|**Project**
从文件菜单创建 PDF/XPS 时发现一个问题，未创建文件。 |SAC 版本 1902||
|**Word**
发现了用户打开文件时可能遇到的问题。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)|
我们发现一个问题，对于由 OneDrive 同步引擎同步的 Office 文件，“保存”和“另存为”时将不再验证文档元数据（例如“需要属性”和“内容类型”）要求。|SAC 版本 1902||
我们发现了使用 Caps + 向右箭头时，Windows 19H1 版本上的 JAWS 不会读单词的问题。|SAC 版本 1902||
|**Office 套件**
SHA-1 弃用：为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)|
通过恢复以前可能已中断的下载来下载 Office 更新时，我们发现了一个问题。|SACT 版本 1908|每月版本 1909 <br> (16.0.12026.20264)||
我们发现登录成功后，出现“修复我的帐户”通知未消失的问题。|SAC 版本 1902||



## <a name="may-2019---sample"></a>2019 年 5 月 - 示例

|摘要|正在调查|已解决|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
在多个内部版本中已解决的问题的示例 -- 发现了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。||SAC 版本 1902 <br> (16.0.11328.20306) <br> 每月版本 1905 <br> (16.0.11629.20210)|
|**Word**
某些内部版本（并非全部内部版本）中已解决的问题的示例 -- 发现了在为“文档”属性启用文档部件时的性能问题。|SAC 版本 1808|SACT 版本 1902 <br> (16.0.11328.20340)|

<br>
<br>

> [!NOTE]
> 如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。
