---
title: Office 部署工具 (ODT) 的发布历史记录
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 为 IT 专业人士提供 Office 部署工具 (ODT) 的发布历史记录
ms.openlocfilehash: ef130b3602d1f7d8c664167655cba09eb45b8e52
ms.sourcegitcommit: b7b3ebab7fc6b8424482107f650f6bb528afd8f7
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/19/2021
ms.locfileid: "53022095"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的发布历史记录

Office 部署工具 (ODT) 是命令行工具，可用于下载即点即用版本 Office（如 Microsoft 365 应用），并将它部署到客户端计算机。 


使用 ODT，可更好地控制 Office 安装：可以定义要安装哪些产品和语言、应该如何更新这些产品以及是否向用户显示安装体验。若要详细了解如何使用 ODT，请参阅 [Office 部署工具概述](/deployoffice/overview-of-the-office-2016-deployment-tool)。

 **支持的操作系统**：Windows 10、Windows 7、Windows 8.1、Windows Server 2019、Windows Server 2016 
 
 **安装说明**：下载文件后，运行自解压缩可执行文件，其中包含 Office 部署工具可执行文件 (setup.exe) 和示例配置文件 (configuration.xml)。 

[下载 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="june-17-2021"></a>2021 年 6 月 17 日
版本 16.0.14026.20236（setup.exe 版本 16.0.14026.20236）
- 修复了使用 MatchOS 语言选项的操作在某些操作系统配置中失败的问题


## <a name="june-7-2021"></a>2021 年 6 月 7 日
版本 16.0.14026.20254 (setup.exe 版本 16.0.14026.20252)
- ARM 平台的可靠性修补程序


## <a name="may-10-2021"></a>2021 年 5 月 10 日
版本 16.0.13929.20296（setup.exe 版本 16.0.13929.20238）
- 修复了如果配置文件同时包含 MigrateArch 和 RemoveMSI，则/configue 模式可能失败的问题。
- 其他可靠性改进

## <a name="april-13-2021"></a>2021 年 4 月 13 日
版本 16.0.13901.20336（setup.exe 版本 16.0.13901.20328）
- 在已安装 Office 的设备上运行的配置操作的可靠性修补程序
- 可在某些方案中避免显示重复的进度 UI
- 改进 UI 中显示的错误代码准确度
- ARM 平台的可靠性修补程序

## <a name="march-23-2021"></a>2021 年 3 月 23 日
版本 16.0.13801.20360（setup.exe 版本 16.0.13801.20340）
- 对即将发布的 Office 产品所做的更改
- ARM 平台的可靠性修补程序


## <a name="february-25-2021"></a>2021 年 2 月 25 日
版本 16.0.13628.20476（setup.exe 版本 16.0.13628.20462）
- 修复了无法验证指定数十种语言的 configuration.xml 文件的问题
- 修复了迁移存档方案中不遵守 FORCEAPPSHUTDOWN 属性的问题
- 修复了在 configuration.xml 中指定 2 个或更多 PIDKEY 属性无法安装 PIDKey 的问题



## <a name="february-9-2021"></a>2021 年 2 月 9 日
版本 16.0.13628.20274（setup.exe 版本 16.0.13628.20246）
- 添加了对 Windows 8.0 上不支持的安装发出警告验证
- ARM64 设备的可靠性修补程序


## <a name="january-12-2021"></a>2021 年 1 月 12 日
版本 16.0.13530.20376 （setup.exe 版本16.0.13530.20334）
- 修复了产品注册损坏或非标准产品注册可能导致RemoveMSI操作失败的问题

## <a name="december-21-2020"></a>2020 年 12 月 21 日
版本 16.0.13426.20370（setup.exe 版本 16.0.13426.20352）
- 修正了 PerpetualVL2019 频道的 ProofingTool 本地源安装失败的问题
- 修复了一个问题，以确保在向现有安装中添加其他非全文 Office 语言的产品时，即点即用客户端会尝试自我更新


## <a name="december-8-2020"></a>2020 年 12 月 8 日
版本 16.0.13426.20308（setup.exe 版本 16.0.13426.20308）
- 已修复以下问题：如果设备具有从非永久 2019 通道安装的 Office 产品，则下载模式会阻止永久性的 2019 通道下载。
- 已修复以下问题：体系结构迁移将无法针对通过下载模式创建的本地源，该源已在配置 XML 中指定了显式版本。


## <a name="november-23-2020"></a>2020 年 11 月 23 日
版本 16.0.13328.20420（setup.exe 版本 16.0.13328.20420）
- 已修复未通过 /download 模式下载校对工具的问题
- 已修复 /download 模式在普通用户中运行失败的问题
- 已修复在配置 XML 中指定 Version 属性导致在 /download 模式下无法完全下载的问题
- 已修复提取时 Office 部署工具未命名为 “setup.exe” 的问题
- 已修复在配置 XML 中提供频道属性时的安装源优先次序方面的问题

## <a name="november-10-2020"></a>2020 年 11 月 10 日
版本 16.0.13328.20356（setupODT.exe 版本 16.0.13328.20336）
- 可靠性和复原能力方面的改进
- 为了防止混淆并更轻松地诊断安装错误，ODT 现在默认命名为 setupODT.exe。

## <a name="october-29-2020"></a>2020 年 10 月 29 日
版本 16.0.13328.20292（setup.exe 版本 16.0.13328.20290）
- 解决了使用 RemoveMSI 时，某些 Office 2007 产品可能意外阻止安装的问题

## <a name="october-14-2020"></a>2020 年 10 月 14 日
版本 16.0.13231.20368（setup.exe 版本 16.0.13231.20350）
- 如果未指定频道，则所有产品都将默认使用每月频道
- 增强了从包含其他 DLL 的目录运行 ODT 时的安全性
- 可靠性和复原能力方面的改进

## <a name="june-9-2020"></a>2020 年 6 月 9 日

版本 16.0.12827.20268（setup.exe 版本 16.0.12827.20258）
- 当前频道现在为未指定频道时的默认频道
- 增加了对每月企业频道的支持
- 增加了对新频道名称的支持
- 其他复原功能可在可能的情况中继续安装（即使某些语言资源不可用）
- MSIRemove 功能已展开，可删除 Office 2007 产品
- MSIRemove 功能已展开，可删除访问数据库引擎 

## <a name="april-15-2020"></a>2020 年 4 月 15 日

版本 16.0.12624.20320 （setup.exe 版本 16.0.12624.20290）
- 增加了对 Windows 7 已停用 Office 版本的支持。
- 修复了自定义设置可能无法按预期应用的问题
- 修复了可能意外下载无关 .cat 文件的问题

## <a name="january-16-2020"></a>2020 年 1 月 16 日

版本 16.0.12325.20288
- 修复了在已安装多个语言的情况下 Office 安装 UI 可能显示为不正确的语言的问题
- 修复了在已安装某些校对工具包的情况下 Office 安装可能意外失败的问题
- 增加了以下支持：支持选择性地控制 [Microsoft 必应搜索功能](/deployoffice/microsoft-search-bing)的初始部署


## <a name="october-31-2019"></a>2019 年 10 月 31 日

版本 16.0.12130.20272
- 修复了一个问题，使 Skype for Business Basic 2019 能够随附 2019 永久企业批量许可产品一并安装
- 修复了当使用代理时可能导致 ODT 下载模式在某些情况下意外失败的问题
- 提供了使 ODT 下载模式可使用端口 80 以外的端口通过 HTTP 下载的新功能


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