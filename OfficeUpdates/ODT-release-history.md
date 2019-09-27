---
title: Office 部署工具 (ODT) 的发布历史记录
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 为 IT 专业人士提供 Office 部署工具 (ODT) 的发布历史记录
ms.openlocfilehash: 1622ddf9a89767c2d0e456737362eecf4123b3fd
ms.sourcegitcommit: a5da36df390868d76bddfc78e9481ed8e9c5b673
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/26/2019
ms.locfileid: "37275483"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的发布历史记录

Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Office 365 专业增强版），并将它部署到客户端计算机。 


使用 ODT，可以更全面地控制 Office 安装。 可以定义安装了哪些产品和语言、应如何更新这些产品，以及是否向用户显示安装体验。 若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](https://docs.microsoft.com/zh-CN/deployoffice/overview-of-the-office-2016-deployment-tool)。

 **支持的操作系统**：Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2 
 
 **安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。 

[下载 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="july-10-2019"></a>2019 年 7 月 10 日

版本 16.0.11901.20022
- 现已开始支持与 Office 2019 一起安装的其他产品：Access Runtime、Skype for Business Basic。
- 现已开始支持从 MSI 升级时对独立产品进行条件安装。

## <a name="april-23-2019"></a>2019 年 4 月 23 日

版本 16.0.11617.33601
- 已修复 RemoveMSI=True 清理相关注册表设置的 bug。
- 更新了错误代码，以提供意外故障 (E_UNEXPECTED) 的其他详细信息。

## <a name="april-16-2019"></a>2019 年 4 月 16 日

版本 16.0.11615.33602
- 支持使用新的 MigrateArch 属性将 32 位 C2R 升级到 64 位 C2R。
- 更新了 /configure 逻辑，可便于访问存储在 Web 位置（http 和 https）中的配置 XML 文件。
- MatchInstalled 已添加为新属性，这样 ODT 就能在添加其他产品或语言时匹配现有版本。

## <a name="march-13-2019"></a>2019 年 3 月 13 日

版本 16.0.11509.33604
- 改进了升级和迁移方案。

## <a name="january-14-2019"></a>2019 年 1 月 14 日

版本 16.0.11306.33602
- 对部署配置改进了日志记录和遥测。


## <a name="related-links"></a>相关链接

[ODT 下载中心](https://www.microsoft.com/en-us/download/details.aspx?id=49117)