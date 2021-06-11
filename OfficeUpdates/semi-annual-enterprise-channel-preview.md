---
title: 有关 2021 年半年企业频道（预览）发行的发行说明
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2021 年 Microsoft 365 应用版半年频道（定向）发行的发行说明
ms.openlocfilehash: 95bdd111e041dd07689ad84254dde5b95a8efebe
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/09/2021
ms.locfileid: "52852002"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="1173e-103">有关半年企业频道（预览）的发行说明</span><span class="sxs-lookup"><span data-stu-id="1173e-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="1173e-104">我们为 Microsoft 365 企业应用版、Microsoft 365 商业应用版以及 Project 和 Visio 桌面应用的订阅版本提供了半年企业频道（预览）更新。这些发行说明提供了有关这些更新中所含新功能和非安全更新的信息。</span><span class="sxs-lookup"><span data-stu-id="1173e-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


## <a name="version-2102-june-08"></a><span data-ttu-id="1173e-105">版本 2102：6 月 8 日</span><span class="sxs-lookup"><span data-stu-id="1173e-105">Version 2102: June 08</span></span>
<span data-ttu-id="1173e-106">*版本 2102（内部版本 13801.20738）*</span><span class="sxs-lookup"><span data-stu-id="1173e-106">*Version 2102 (Build 13801.20738)*</span></span>

<span data-ttu-id="1173e-107">[此处](microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="1173e-107">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="1173e-109">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-109">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1173e-110">Excel</span><span class="sxs-lookup"><span data-stu-id="1173e-110">Excel</span></span>

- <span data-ttu-id="1173e-111">我们已修复了一个问题，删除了在帕累托图上出现的额外填充，减少了可用图表空间。</span><span class="sxs-lookup"><span data-stu-id="1173e-111">We fixed an issue which removes extra padding that appeared on Pareto charts and reduced the available charting space.</span></span>


- <span data-ttu-id="1173e-112">解决了某些用户的 Excel 加载项列表中出现额外条目的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-112">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="1173e-113">我们修复了导致某些用户的“状态栏”不显示“就绪”状态的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-113">We fixed an issue that caused the Status Bar to not indicate a Ready state for some users.</span></span>


- <span data-ttu-id="1173e-114">我们通过刷新 Power BI 数据类型时出现错误消息修复了一个问题，并且用户无法访问某些数据类型。</span><span class="sxs-lookup"><span data-stu-id="1173e-114">We fixed an issue by improving the error message when refreshing Power BI data types and the user does not have access to some of the data types.</span></span>


- <span data-ttu-id="1173e-115">我们修复了该问题，将属性“自动完成”下拉列表中可显示的属性数提高至 256 个。</span><span class="sxs-lookup"><span data-stu-id="1173e-115">We fixed an issue by increasing the number of properties that can show in the property AutoComplete drop down to 256 properties.</span></span>


### <a name="outlook"></a><span data-ttu-id="1173e-116">Outlook</span><span class="sxs-lookup"><span data-stu-id="1173e-116">Outlook</span></span>

- <span data-ttu-id="1173e-117">我们修复了内部和外部 EWS 终结点不同，且调用内部终结点失败时导致用户获取连接错误这一问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-117">We fixed an issue that caused users to get connectivity errors when the internal and external EWS endpoints are different and the call to the internal endpoint fails.</span></span>


- <span data-ttu-id="1173e-118">我们修复了在重新发送电子邮件时导致发件人地址显示为 LegacyExchangeDN 的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-118">We fixed an issue that caused the sender's address to be displayed as a LegacyExchangeDN when resending an email.</span></span>


- <span data-ttu-id="1173e-119">我们修复了最终用户和管理员无法启用云设置这一问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-119">Fixed an issue where end users and administrators were unable to turn on Cloud Settings.</span></span>


- <span data-ttu-id="1173e-120">修复了一个问题，过去导致 Zero ConfigExchange 无法在连接到外部网络的已建立混合 Azure AD 联接正常工作。</span><span class="sxs-lookup"><span data-stu-id="1173e-120">We fixed an issue that caused ZeroConfigExchange to fail to work properly on Hybrid Azure AD joined machines connected to an external network.</span></span>


- <span data-ttu-id="1173e-121">我们修复了一个问题，该问题导致自定义域的用户在将链接粘贴到电子邮件时看到关于权限的警告消息。</span><span class="sxs-lookup"><span data-stu-id="1173e-121">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>
</br>

- <span data-ttu-id="1173e-122">我们添加了一个注册表项，该注册表项禁用了新的会议室查找工具体验（与 Outlook for Web 中相同的体验），并启用旧版会议室查找工具和"建议时间"。</span><span class="sxs-lookup"><span data-stu-id="1173e-122">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

    <span data-ttu-id="1173e-123">注册表项:</span><span class="sxs-lookup"><span data-stu-id="1173e-123">Registry Key:</span></span>

    ><span data-ttu-id="1173e-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="1173e-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    ><span data-ttu-id="1173e-125">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="1173e-125">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    ><span data-ttu-id="1173e-126">0(默认) - 当用户点击‘会议室查找器’按钮搜索可用会议室时，Outlook 会使用新的会议室查找器 OWA 支持的体验</span><span class="sxs-lookup"><span data-stu-id="1173e-126">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    ><span data-ttu-id="1173e-127">1 - Outlook 使用旧版会议室查找器 UI 搜索可用会议室</span><span class="sxs-lookup"><span data-stu-id="1173e-127">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


### <a name="powerpoint"></a><span data-ttu-id="1173e-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1173e-128">PowerPoint</span></span>

- <span data-ttu-id="1173e-129">修复了应用商店更新到 1.0.0.2 版本以支持集中部署的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-129">We fixed an issue where the store is updated to version 1.0.0.2 to support central deployment.</span></span> <span data-ttu-id="1173e-130">用户需要更新 PowerPoint 中的版本信息以访问应用商店。</span><span class="sxs-lookup"><span data-stu-id="1173e-130">The user will need to update the version info in PowerPoint to access the store.</span></span>


### <a name="project"></a><span data-ttu-id="1173e-131">Microsoft Project</span><span class="sxs-lookup"><span data-stu-id="1173e-131">Project</span></span>

- <span data-ttu-id="1173e-132">修复了问题: 如果你创建使用 ProjectDate */ProjectDur* 函数的自定义字段公式，且第二个参数为 Date()、Now() or Time() 日期和时间函数，则会出现 #ERROR 结果。</span><span class="sxs-lookup"><span data-stu-id="1173e-132">Fixed an issue where if you create a custom field formula which uses the ProjectDate */ProjectDur* functions and if the second parameter is the Date(), Now() or Time() date and time functions, then a #ERROR results.</span></span>


- <span data-ttu-id="1173e-133">修复了资源池无响应且无法打开的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-133">Fixed an issue where the resource pool becomes unresponsive and can't be opened.</span></span>


### <a name="visio"></a><span data-ttu-id="1173e-134">Visio</span><span class="sxs-lookup"><span data-stu-id="1173e-134">Visio</span></span>

- <span data-ttu-id="1173e-135">我们修复了形状搜索中输入搜索关键字时缺少结果的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-135">We fixed an issue related to missing results on entering search keywords in shape search.</span></span>


### <a name="word"></a><span data-ttu-id="1173e-136">Word</span><span class="sxs-lookup"><span data-stu-id="1173e-136">Word</span></span>

- <span data-ttu-id="1173e-137">修复了插入联机图片时应用程序没有响应的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-137">Fixed an issue related to unresponsiveness of the application when inserting Online Pictures.</span></span>


- <span data-ttu-id="1173e-138">我们修复了粘贴并复制文本可能与粘贴的文本不同的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-138">We fixed an issue where copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="1173e-139">我们修复了一个问题，即删除了内容控件允许的字符串大小限制。</span><span class="sxs-lookup"><span data-stu-id="1173e-139">We fixed an issue which removes limit on size of strings allowed for content controls.</span></span>


- <span data-ttu-id="1173e-140">我们修复了与编辑 OLE 对象有关的一个问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-140">We fixed an issue related to editing OLE object.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1173e-141">Office 套件</span><span class="sxs-lookup"><span data-stu-id="1173e-141">Office Suite</span></span>

- <span data-ttu-id="1173e-142">修复了打开占位符文件时的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-142">Fixed an issue when open placeholder files.</span></span> <span data-ttu-id="1173e-143">Office 未响应，无法打开同步备份的文件。</span><span class="sxs-lookup"><span data-stu-id="1173e-143">Office was non-responsive to open the sync-backed file.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-may-11"></a><span data-ttu-id="1173e-145">版本 2102：5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="1173e-145">Version 2102: May 11</span></span>
<span data-ttu-id="1173e-146">*版本 2102（内部版本 13801.20638）*</span><span class="sxs-lookup"><span data-stu-id="1173e-146">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="1173e-147">此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="1173e-147">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="1173e-149">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-149">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1173e-150">Excel</span><span class="sxs-lookup"><span data-stu-id="1173e-150">Excel</span></span>

- <span data-ttu-id="1173e-151">修复了 Excel 无法加载某些自动化加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-151">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="1173e-152">已修复使用加载项时导致某些语言的日期格式显示错误的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-152">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="1173e-153">修复了阻止系统能够在受保护的工作表上粘贴公式的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-153">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="1173e-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="1173e-154">Outlook</span></span>

- <span data-ttu-id="1173e-155">这使最终用户可以配置 Outlook，以将联机会议添加到所创建的所有会议。</span><span class="sxs-lookup"><span data-stu-id="1173e-155">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1173e-156">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1173e-156">PowerPoint</span></span>

- <span data-ttu-id="1173e-157">我们修复了与链接图片相关的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-157">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="1173e-158">Word</span><span class="sxs-lookup"><span data-stu-id="1173e-158">Word</span></span>

- <span data-ttu-id="1173e-159">修复了链接中第 2084 个字符为转义字符时，某些用户无法在 Wordmail 中发送项目的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-159">Fixed an issue in Wordmail where someone cannot send an item when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1173e-160">Office 套件</span><span class="sxs-lookup"><span data-stu-id="1173e-160">Office Suite</span></span>

- <span data-ttu-id="1173e-161">修复了即使 GPO 发出禁用请求，但 Office 模板仍然打开的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-161">Fixed an issue where Office templates turned on even with GPO placed disable request.</span></span>


- <span data-ttu-id="1173e-162">修复了打印长文档时导致 Word 意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-162">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-april-13"></a><span data-ttu-id="1173e-164">版本 2102：4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="1173e-164">Version 2102: April 13</span></span>
<span data-ttu-id="1173e-165">*版本 2102（内部版本 13801.20506）*</span><span class="sxs-lookup"><span data-stu-id="1173e-165">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="1173e-166">此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="1173e-166">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="1173e-168">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-168">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1173e-169">Access</span><span class="sxs-lookup"><span data-stu-id="1173e-169">Access</span></span>

- <span data-ttu-id="1173e-170">修复了在某些情况下，运行 SQL Server 通过查询可能会收到指明"光标状态无效"的错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-170">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="1173e-171">Excel</span><span class="sxs-lookup"><span data-stu-id="1173e-171">Excel</span></span>

- <span data-ttu-id="1173e-172">解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-172">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="1173e-173">修复了在另一张工作表上添加行后，数据验证可能会意外应用到单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-173">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="1173e-174">修复了对话框表显示函数在 32 位版本的 Excel 中无法正常工作这一问题</span><span class="sxs-lookup"><span data-stu-id="1173e-174">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="1173e-175">Outlook</span><span class="sxs-lookup"><span data-stu-id="1173e-175">Outlook</span></span>

- <span data-ttu-id="1173e-176">修复了导致 Outlook 在空闲时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-176">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="1173e-177">我们修复了导致云设置功能用户在新设备上配置 Outlook 后会看到默认设置覆盖自定义设置的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-177">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="1173e-178">修复了导致用户看到签名超过预期的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-178">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1173e-179">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1173e-179">PowerPoint</span></span>

- <span data-ttu-id="1173e-180">解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-180">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="1173e-181">Word</span><span class="sxs-lookup"><span data-stu-id="1173e-181">Word</span></span>

- <span data-ttu-id="1173e-182">解决了 Office 功能区中禁用的命令只会灰显图标而使 Office 主题中的文本无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-182">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="1173e-183">修复了与复制和粘贴相关的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-183">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="1173e-184">我们修复了在隐藏段落末尾键入时可能导致应用程序挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-184">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1173e-185">Office 套件</span><span class="sxs-lookup"><span data-stu-id="1173e-185">Office Suite</span></span>

- <span data-ttu-id="1173e-186">解决了用户在打开以前打开的文件时无法保存文件（其中未保存编辑，但现在文件已删除）的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-186">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="1173e-187">修复后，用户收到友好消息，告知用户文件已删除，因此用户可选择放弃更改或另存为文件。</span><span class="sxs-lookup"><span data-stu-id="1173e-187">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="1173e-188">修复了脱机打开 SyncBacked 文件，然后在保存文件之前在应用中重命名文件时出现重命名失败问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-188">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="1173e-189">修复了 GCC 用户禁用听写的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-189">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="1173e-190">修复了有时可能导致 Outlook 中的文本变为透明且无法清晰显示的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-190">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2102-march-09"></a><span data-ttu-id="1173e-192">版本 2102：3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="1173e-192">Version 2102: March 09</span></span>
<span data-ttu-id="1173e-193">*版本 2102（内部版本 13801.20294）*</span><span class="sxs-lookup"><span data-stu-id="1173e-193">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="1173e-194">此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="1173e-194">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="1173e-196">功能更新</span><span class="sxs-lookup"><span data-stu-id="1173e-196">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="1173e-197">Excel</span><span class="sxs-lookup"><span data-stu-id="1173e-197">Excel</span></span>

- <span data-ttu-id="1173e-198">**墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。</span><span class="sxs-lookup"><span data-stu-id="1173e-198">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="1173e-199">在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-199">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="1173e-200">**建立 PDF 连接：** 连接到 PDF，从其中导入数据，刷新数据。</span><span class="sxs-lookup"><span data-stu-id="1173e-200">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="1173e-201">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-201">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="1173e-202">**创建用于公式的变量：** 通过 LET 函数改进性能、可读性和可组合性。</span><span class="sxs-lookup"><span data-stu-id="1173e-202">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="1173e-203">此功能允许你在新的或预先存在的公式中创建已命名的变量。</span><span class="sxs-lookup"><span data-stu-id="1173e-203">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="1173e-204">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-204">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="1173e-205">在[博客文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-205">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="1173e-206">**保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="1173e-206">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="1173e-207">我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。</span><span class="sxs-lookup"><span data-stu-id="1173e-207">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="1173e-208">我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。</span><span class="sxs-lookup"><span data-stu-id="1173e-208">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="1173e-209">这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。</span><span class="sxs-lookup"><span data-stu-id="1173e-209">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="1173e-210">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-210">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="1173e-211">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-211">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="1173e-212">**使用数据类型从 Power BI 获取组织数据：Power BI 中的** Excel 数据类型现向具有 Office 365/Microsoft 365 和 Power BI Pro 服务计划的组织的预览体验成员推出。</span><span class="sxs-lookup"><span data-stu-id="1173e-212">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="1173e-213">获取所需信息并轻松刷新，这对许多日常工作流至关重要。</span><span class="sxs-lookup"><span data-stu-id="1173e-213">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="1173e-214">我们将为你提供从 Power BI 到 Excel 中的数据类型的公司或组织信息的访问权限，这将扩大你在电子表格中引入链接信息的能力。</span><span class="sxs-lookup"><span data-stu-id="1173e-214">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="1173e-215">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-215">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="1173e-216">在[博客文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-216">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="1173e-217">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="1173e-217">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="1173e-218">无需转换。</span><span class="sxs-lookup"><span data-stu-id="1173e-218">No conversion required.</span></span><br /><span data-ttu-id="1173e-219">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-219">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="1173e-220">**在 Excel 中制作精美的 Visio 图表：** 根据工作表中的数据创建数据驱动的图表，例如流程图或组织结构图。</span><span class="sxs-lookup"><span data-stu-id="1173e-220">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="1173e-221">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-221">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


- <span data-ttu-id="1173e-222">**AMSI 与适用于 XLM 宏的 Office 集成：** AMSI 是在 Windows 10 上提供的开放接口，应用程序可在运行时请求已安装的防病毒或安全解决方案对内存缓冲区进行同步扫描。</span><span class="sxs-lookup"><span data-stu-id="1173e-222">**AMSI integration with Office for XLM macros:** AMSI is an open interface available on Windows 10 for applications to request, at runtime, a synchronous scan of a memory buffer by an installed antivirus or security solution.</span></span> <span data-ttu-id="1173e-223">检测到恶意活动时，Excel 会通知用户，并关闭应用程序会话以避免进一步损失。</span><span class="sxs-lookup"><span data-stu-id="1173e-223">When malicious activity is detected, the user is notified by Excel, and the application session is shut down to avoid any further damage.</span></span> <span data-ttu-id="1173e-224">此操作可以就地阻止攻击，保护设备和用户。</span><span class="sxs-lookup"><span data-stu-id="1173e-224">This can stop an attack in its tracks, protecting both the device and user.</span></span> <span data-ttu-id="1173e-225">请在 [博客文章](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/) 中查看详细信息。</span><span class="sxs-lookup"><span data-stu-id="1173e-225">See details in [blog post](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/).</span></span>

### <a name="outlook"></a><span data-ttu-id="1173e-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="1173e-226">Outlook</span></span>

- <span data-ttu-id="1173e-227">**帮助保护组中的数据：** 你在创建组时选择的敏感度标签应用于组电子邮件、文档和团队网站。</span><span class="sxs-lookup"><span data-stu-id="1173e-227">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="1173e-228">**IT 管理员事件通知：** 使用 Outlook for Windows 中的新右侧面板通知，Microsoft 365 租户全局管理员和 Office 应用程序管理员将收到有关影响用户的 Outlook 和 O365 通知。</span><span class="sxs-lookup"><span data-stu-id="1173e-228">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="1173e-229">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-229">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="1173e-230">**在 Outlook 中使用快速投票创建投票：** 轻松创建投票、收集选票和在电子邮件中查看结果 [了解详细信息](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="1173e-230">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="1173e-231">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="1173e-231">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="1173e-232">无需转换。</span><span class="sxs-lookup"><span data-stu-id="1173e-232">No conversion required.</span></span><br /><span data-ttu-id="1173e-233">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-233">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="1173e-234">**新的会议室查找器：** 根据不同功能搜索会议室。</span><span class="sxs-lookup"><span data-stu-id="1173e-234">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="1173e-235">**按照你说的方式搜索目标：** 使用日常语言（如“上周预约的兽医”）来筛选和缩小搜索范围。</span><span class="sxs-lookup"><span data-stu-id="1173e-235">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="1173e-236">**从上一个 Outlook 会话快速重新打开项目的选项：** 我们添加了一个选项，可以从上一个 Outlook 会话快速重新打开项目。</span><span class="sxs-lookup"><span data-stu-id="1173e-236">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="1173e-237">在[博客文章](https://insider.office.com/zh-CN/blog/automatically-restore-windows-in-outlook)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-237">See details in [blog post](https://insider.office.com/zh-CN/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1173e-238">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1173e-238">PowerPoint</span></span>

- <span data-ttu-id="1173e-239">**墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。</span><span class="sxs-lookup"><span data-stu-id="1173e-239">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="1173e-240">在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-240">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="1173e-241">**保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="1173e-241">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="1173e-242">我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。</span><span class="sxs-lookup"><span data-stu-id="1173e-242">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="1173e-243">我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。</span><span class="sxs-lookup"><span data-stu-id="1173e-243">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="1173e-244">这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。</span><span class="sxs-lookup"><span data-stu-id="1173e-244">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="1173e-245">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-245">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="1173e-246">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-246">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="1173e-247">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="1173e-247">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="1173e-248">无需转换。</span><span class="sxs-lookup"><span data-stu-id="1173e-248">No conversion required.</span></span><br /><span data-ttu-id="1173e-249">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-249">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="1173e-250">Visio</span><span class="sxs-lookup"><span data-stu-id="1173e-250">Visio</span></span>

- <span data-ttu-id="1173e-251">**新 Azure 图案和形状：** 我们添加了很多图案，以帮助创建最新的 Azure 图表。</span><span class="sxs-lookup"><span data-stu-id="1173e-251">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="1173e-252">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-252">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="1173e-253">Word</span><span class="sxs-lookup"><span data-stu-id="1173e-253">Word</span></span>

- <span data-ttu-id="1173e-254">**墨迹工具箱中的“套索和橡皮擦”：** 使用绘图工具时，现在“墨迹工具箱”中可以提供“套索” 和“橡皮擦”了。</span><span class="sxs-lookup"><span data-stu-id="1173e-254">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="1173e-255">在[博客文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-255">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="1173e-256">**保存到已固定的文件夹：** 固定文件夹可更轻松地保存 Office 文件。</span><span class="sxs-lookup"><span data-stu-id="1173e-256">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="1173e-257">我们收到了一些反馈，用户希望更好地控制保存新文件时的可用文件夹。</span><span class="sxs-lookup"><span data-stu-id="1173e-257">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="1173e-258">我们很高兴为你带来一个新功能：在“保存”对话中固定文件夹。</span><span class="sxs-lookup"><span data-stu-id="1173e-258">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="1173e-259">这个新功能将使你的 Word、Excel 和 PowerPoint 文件更容易保存。</span><span class="sxs-lookup"><span data-stu-id="1173e-259">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="1173e-260">了解更多</span><span class="sxs-lookup"><span data-stu-id="1173e-260">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="1173e-261">在[博客文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-261">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="1173e-262">**将 iPhone 照片直接插入 Office：** 手机中的 HEIC 照片现在可以无缝插入 Office。</span><span class="sxs-lookup"><span data-stu-id="1173e-262">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="1173e-263">无需转换。</span><span class="sxs-lookup"><span data-stu-id="1173e-263">No conversion required.</span></span><br /><span data-ttu-id="1173e-264">在[博客文章](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-264">See details in [blog post](https://insider.office.com/zh-CN/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="1173e-265">Office 套件</span><span class="sxs-lookup"><span data-stu-id="1173e-265">Office Suite</span></span>

- <span data-ttu-id="1173e-266">**制表符窗格：** 现在，可以使用应用程序右侧的选项卡 UI 在多个窗格之间进行切换。</span><span class="sxs-lookup"><span data-stu-id="1173e-266">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="1173e-267">UI 将只在当打开2个以上的窗格时才会可见。</span><span class="sxs-lookup"><span data-stu-id="1173e-267">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="1173e-268">在[博客文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="1173e-268">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="1173e-271">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-271">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1173e-272">Access</span><span class="sxs-lookup"><span data-stu-id="1173e-272">Access</span></span>

- <span data-ttu-id="1173e-273">我们修复了从非 Office 应用程序使用 DAO 时会导致应用程序意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-273">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="1173e-274">我们修复了用户收到错误对话”光标状态无效的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-274">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="1173e-275">Excel</span><span class="sxs-lookup"><span data-stu-id="1173e-275">Excel</span></span>

- <span data-ttu-id="1173e-276">我们修复了某些中断旧版 Excel 4.0 和 Excel 5.0 宏以及某些对 dialogsheets.show 的 VBA 调用的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-276">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="1173e-277">修复了使用数据透视表的“值显示方式”菜单时，Excel 可能意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-277">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="1173e-278">我们修复了一个阻止用户将 Excel 工作簿导出为 PDF 的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-278">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="1173e-279">我们修复了使用“粘贴链接图片”选项时导致图像小于预期的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-279">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="1173e-280">我们修复了保存为 .xls 或 .xlt 格式时导致某些数据透视表格式设置损坏工作簿的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-280">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="1173e-281">修复了打开包含 Excel 4.0 宏的 Excel 加载项文件时，Excel 可能会禁用宏而不提示的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-281">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="1173e-282">修复了以下问题：Excel 错误地显示新版本文件可用的消息栏，并强制用户将更改保存在工作簿副本中或放弃更改。</span><span class="sxs-lookup"><span data-stu-id="1173e-282">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="1173e-283">修复了以下问题：当某些用户共同创作时，会错误地向其显示存在新版本文件的消息栏通知。</span><span class="sxs-lookup"><span data-stu-id="1173e-283">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="1173e-284">修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-284">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="1173e-285">我们修复了在图表中选择数据系列后 Excel 停止响应的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-285">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="1173e-286">此更改解决了在公式中正确显示字体的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-286">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="1173e-287">Outlook</span><span class="sxs-lookup"><span data-stu-id="1173e-287">Outlook</span></span>

- <span data-ttu-id="1173e-288">解决了导致用户无法向其代理授予编辑器权限的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-288">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="1173e-289">我们解决了导致某些用户在特定搜索方案中遇到 Outlook 意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-289">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="1173e-290">修复了导致配置文件中具有较大层次结构的共享邮箱或委派邮箱的用户遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-290">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="1173e-291">解决了当主题行为空白时，某些自动生成的电子邮件将发送空白正文的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-291">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="1173e-292">解决了导致部分用户观察到 Outlook 在离线状态下意外启动的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-292">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="1173e-293">解决了导致代理在其他邮箱中打开共享文件夹时出现间歇性故障的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-293">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="1173e-294">我们修复了导致用户在选择搜索结果时遇到应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-294">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="1173e-295">我们修复了导致一些客户在加载日历时遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-295">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="1173e-296">我们修复了导致某些会议的原定与会者在其他与会者转发会议时收到取消通知的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-296">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="1173e-297">修复并解决了导致用户在创建新组后看到重复日历组的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-297">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="1173e-298">修复了导致“共享日历”改进用户无法将日历的颜色设置为黄色或棕色的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-298">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="1173e-299">我们修复了导致用户看到新添加的日历直到 Outlook 重新启动之后才会显示在导航窗格中的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-299">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="1173e-300">解决了在搜索未缓存的共享日历时，导致搜索不返回结果的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-300">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="1173e-301">我们修复了导致部分用户在关闭消息窗口时遇到关闭应用程序的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-301">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="1173e-302">我们修复了在发送任务状态报告时导致“收件人”字段为空的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-302">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="1173e-303">我们修复了导致 MailItem.BeforeAttachmentAdd 事件被破坏的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-303">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="1173e-304">我们修复了导致某些用户在特定搜索方案中遇到 Outlook 意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-304">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="1173e-305">我们修复了导致用户在 Outlook 中搜索时应用有时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-305">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="1173e-306">我们修复了一个导致云设置用户在更新设置时体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-306">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="1173e-307">我们修复了在提示用户保存后，已编辑的签名无法保存的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-307">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="1173e-308">我们已修复虽以配置一个或多个签名，但仍导致有的用户在签名下拉菜单中看不到签名的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-308">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="1173e-309">我们修复了导致默认情况下不会为用户打开云设置的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-309">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="1173e-310">我们修复了导致无法保存用户签名更改的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-310">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="1173e-311">我们修复了导致 Outlook 为已启用云设置的用户创建第二个空签名的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-311">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="1173e-312">我们修复了一个问题，该问题导致 OWA 中显示正确默认签名问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-312">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="1173e-313">修复了导致用户看到包含 unicode 内容的签名受损的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-313">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="1173e-314">修复了导致内联翻译用户无法提交反馈的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-314">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="1173e-315">解决了导致在答复或转发时中文电子邮件的标题不可阅读的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-315">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="1173e-316">我们修复了另存为 OFT 文件时汉字变成问号的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-316">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="1173e-317">我们添加了一个 regkey，允许客户在 IDataObject 操作中禁用附件的 filetime 包含（例如，拖放、剪贴板）。</span><span class="sxs-lookup"><span data-stu-id="1173e-317">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="1173e-318">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。</span><span class="sxs-lookup"><span data-stu-id="1173e-318">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="1173e-319">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="1173e-319">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="1173e-320">0 = filetimes 被排除。</span><span class="sxs-lookup"><span data-stu-id="1173e-320">0 = filetimes are excluded.</span></span>  <span data-ttu-id="1173e-321">1 = （默认）包含 filetime。</span><span class="sxs-lookup"><span data-stu-id="1173e-321">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="1173e-322">我们修复了以下问题：当回复带有来自 Azure 信息保护的保护标签的邮件时，将导致嵌入式图像消失。</span><span class="sxs-lookup"><span data-stu-id="1173e-322">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="1173e-323">修复了使用仅加密选项发送的电子邮件上无法显示加密图标的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-323">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="1173e-324">我们已修复了在用户取消选中该选项后导致邮件以数字签名发送的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-324">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1173e-325">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1173e-325">PowerPoint</span></span>

- <span data-ttu-id="1173e-326">修复了可能导致应用程序在文件保存失败时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-326">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="1173e-327">修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-327">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="1173e-328">此更改解决了使用特定几何图形对合并形状操作应用时路径填充的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-328">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="1173e-329">此更改解决了在公式中正确显示字体的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-329">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="1173e-330">此更改解决了处理视频加载过程中可能出现的错误的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-330">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="1173e-331">我们修复了 Slide.Shapes.AddMediaObject2 在使用传统视频格式（MPG-1、Mpeg-2）时会意外关闭的 VBA 问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-331">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="1173e-332">我们修复了 QAT 中添加的字号命令在更新时自动完成为最接近定义字号的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-332">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="1173e-333">我们修复了以下问题：复制包含新近录制音频的幻灯片后，保存文件时出现错误。</span><span class="sxs-lookup"><span data-stu-id="1173e-333">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="1173e-334">我们修复了表单内容加载项在插入后不显示，而要到用户单击另一张幻灯片来使其显示时才显示的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-334">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="1173e-335">我们修复了在受保护的视图中打开 PowerPoint 文件时禁用 IRM 保护的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-335">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="1173e-336">修复了在包含大量特定数据对象类型 (E2o) 的文件上导致共同创作速度下降的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-336">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="1173e-337">修复了在合并错误过程中使用 IRM/受保护的文档时遇到的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-337">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="1173e-338">这是针对以下问题的修补程序：关闭文档且存在侦听 PresentationBeforeClose 事件和检查作为事件处理程序一部分的 Presentation.Saved 属性的加载项时，“保存”提示会循环显示。</span><span class="sxs-lookup"><span data-stu-id="1173e-338">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="1173e-339">修复了一些损坏的 PowerPoint 文件即使在执行文档修复操作后也无法正常打开的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-339">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="1173e-340">解决了某些情况下选择设计创意会删除演示文稿数据分类标签的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-340">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="1173e-341">Project</span><span class="sxs-lookup"><span data-stu-id="1173e-341">Project</span></span>

- <span data-ttu-id="1173e-342">修复了以下问题：将项目从 PWA 保存到本地 mpp 文件时，用户实际上未更改的数据将触发 ProjectBeforeTaskChangeEvent。</span><span class="sxs-lookup"><span data-stu-id="1173e-342">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="1173e-343">修复了以下问题：如果在“任务窗体”类型视图中更改了滞后，ProjectBeforeTaskChange 事件中的 NewVal 没有正确的值。</span><span class="sxs-lookup"><span data-stu-id="1173e-343">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="1173e-344">修复了以下问题：如果你正在运行事件代码并尝试通过 “任务窗体”视图进行更改，单击“确定”按钮可能无法提交所做的更改。</span><span class="sxs-lookup"><span data-stu-id="1173e-344">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="1173e-345">解决了打开以特定方式指定资源分布的文件时，Project 可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-345">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="1173e-346">已修复项目文件加载到特定部分出现错误，导致可能打开特定项目的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-346">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="1173e-347">解决了视图中不显示任务边框的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-347">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="1173e-348">解决了“工作组规划器”视图中的拖放功能无法用于任务的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-348">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="1173e-349">修复了将成本资源分配给里程碑任务时，基线成本没有正确汇总的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-349">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="1173e-350">Visio</span><span class="sxs-lookup"><span data-stu-id="1173e-350">Visio</span></span>

- <span data-ttu-id="1173e-351">我们修复了一个问题，用户以后可以使用 Visio for Office 365 中的连接器创建自定义 Visio 模具和内置模板的直线。</span><span class="sxs-lookup"><span data-stu-id="1173e-351">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="1173e-352">Word</span><span class="sxs-lookup"><span data-stu-id="1173e-352">Word</span></span>

- <span data-ttu-id="1173e-353">修复了可能导致应用程序在文件保存失败时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-353">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="1173e-354">修复了将公式从 Word 复制/粘贴到 PowerPoint 的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-354">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="1173e-355">此更改解决了编辑文档时光标存在的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-355">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="1173e-356">我们修复了将颜色应用于图标和具有 3D 效果的 SVG 图形的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-356">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="1173e-357">我们修复了讲述人可能跳过某个段落的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-357">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="1173e-358">我们修复了富文本内容控件的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-358">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="1173e-359">我们修复了“样式库”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-359">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="1173e-360">我们已修复了在共同创作时解决冲突的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-360">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="1173e-361">我们修复了以模板中的其他样式替换文档样式的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-361">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="1173e-362">修复了影响 Word 的优化关口所暴露出的申明 bug。</span><span class="sxs-lookup"><span data-stu-id="1173e-362">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1173e-363">Office 套件</span><span class="sxs-lookup"><span data-stu-id="1173e-363">Office Suite</span></span>

- <span data-ttu-id="1173e-364">解决了尝试保存文件导致故障的问题，该文件从同步备份转换为仅支持服务器。</span><span class="sxs-lookup"><span data-stu-id="1173e-364">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="1173e-365">修复了在某些情况下尝试执行 SaveAs 操作时失败的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-365">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="1173e-366">我们修复了 SaveRequestManagerCam 导致应用程序关闭而不是返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-366">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="1173e-367">修复了文件关闭序列，以便完全关闭所有相互依赖组件。</span><span class="sxs-lookup"><span data-stu-id="1173e-367">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="1173e-368">修复了当来自缓存的 URL 和来自 OneDrive 的 URL 不匹配时，文件在打开时不同步的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-368">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="1173e-369">修复了 Skype for Business 消息中复制/粘贴导致出现"粘贴内容时出错"的对话框的 bug。</span><span class="sxs-lookup"><span data-stu-id="1173e-369">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="1173e-370">修复了将注释中的文本复制/粘贴到 Excel 时出错的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-370">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="1173e-371">修复了在包含数学公式的文本中使用讲述人时可能发生的崩溃。</span><span class="sxs-lookup"><span data-stu-id="1173e-371">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="1173e-p120">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。将信息更改为显示“碳粉/墨水不足”&“无碳粉/墨水”。</span><span class="sxs-lookup"><span data-stu-id="1173e-p120">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="1173e-374">修正了在某些旧版本上安装较新版本的Office，可能会因缺少注册表项而导致功能受损（例如无法使用Power Query）的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-374">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="1173e-375">修复了 Microsoft 365 终结点数据丢失防护无法对磁盘上的 Office 文档进行分类的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-375">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="1173e-376">我们修复了“压缩图片”对话框不保留某些用户设置的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-376">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="1173e-377">修复了与媒体控制器事件通知相关的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-377">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="1173e-378">修复了与媒体播放器引擎计时相关的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-378">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="1173e-379">经过优化的二进制大小。</span><span class="sxs-lookup"><span data-stu-id="1173e-379">Optimized binary size.</span></span>


- <span data-ttu-id="1173e-380">Anaheim WebView 尚不支持 Windows 信息保护(WIP)。</span><span class="sxs-lookup"><span data-stu-id="1173e-380">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="1173e-381">通过此修复，Office 插件平台可以在启用 WIP 的环境中回退到较低级别的 WebView。</span><span class="sxs-lookup"><span data-stu-id="1173e-381">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="1173e-382">根据客户的计算机环境，它可以是 Edge Spartan WebView 或 Trident WebView。</span><span class="sxs-lookup"><span data-stu-id="1173e-382">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="1173e-383">两个低级别 WebView 均支持 WIP。</span><span class="sxs-lookup"><span data-stu-id="1173e-383">Both down level WebViews support WIP.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-february-09"></a><span data-ttu-id="1173e-385">版本 2008：2 月 09 日</span><span class="sxs-lookup"><span data-stu-id="1173e-385">Version 2008: February 09</span></span>
<span data-ttu-id="1173e-386">*版本 2008（内部版本 13127.21216）*</span><span class="sxs-lookup"><span data-stu-id="1173e-386">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="1173e-387">此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="1173e-387">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="1173e-389">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-389">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1173e-390">Excel</span><span class="sxs-lookup"><span data-stu-id="1173e-390">Excel</span></span>

- <span data-ttu-id="1173e-391">修复了打开具有无效文件属性的 UNC 文件时 Excel 会意外关闭的问题（创建时间、修改时间等）</span><span class="sxs-lookup"><span data-stu-id="1173e-391">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="1173e-392">修复了将图表从 Excel 复制并粘贴到 Word 或 PowerPoint 时无法执行小数和千位分隔符设置的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-392">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="1173e-393">我们修复了这样一个问题，即每次运行宏时，涉及数据透视表区域格式的宏的性能会变差。</span><span class="sxs-lookup"><span data-stu-id="1173e-393">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="1173e-394">修复了在将工作表复制或移动到另一个工作簿时条件格式规则被删除的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-394">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="1173e-395">修复了禁用应用启动屏幕时，用户无法将敏感度标签应用到 Excel 文件这一问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-395">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="1173e-396">修复了从 OneDrive 同步文件夹打开云文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-396">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="1173e-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="1173e-397">Outlook</span></span>

- <span data-ttu-id="1173e-398">解决了导致 Outlook 在添加或保存附件时偶尔停止工作的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-398">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1173e-399">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1173e-399">PowerPoint</span></span>

- <span data-ttu-id="1173e-400">修复了 QAT 中添加的字号命令在更新时自动完成以最接近定义字号的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-400">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="1173e-401">修复了采用"保留源格式"选项的幻灯片复制和粘贴有时意外复制到新幻灯片母版上的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-401">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="1173e-402">Word</span><span class="sxs-lookup"><span data-stu-id="1173e-402">Word</span></span>

- <span data-ttu-id="1173e-403">修复了修订中的问题：有时打开 Word 文档可能会显示错误对话框。</span><span class="sxs-lookup"><span data-stu-id="1173e-403">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="1173e-404">修复了从 OneDrive 同步文件夹打开云文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-404">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1173e-405">Office 套件</span><span class="sxs-lookup"><span data-stu-id="1173e-405">Office Suite</span></span>

- <span data-ttu-id="1173e-406">解决了阻止在 Office 中成功打开文件的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-406">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="1173e-407">修复了通过格式刷将包含草图轮廓应用到连接线的文档可能会损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-407">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-2008-january-12"></a><span data-ttu-id="1173e-409">版本2008：1月12日</span><span class="sxs-lookup"><span data-stu-id="1173e-409">Version 2008: January 12</span></span>
<span data-ttu-id="1173e-410">*版本2008（内部版本13127.21064）*</span><span class="sxs-lookup"><span data-stu-id="1173e-410">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="1173e-411">此处列出了安全更新：[Microsoft Office 安全更新发行说明](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="1173e-411">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="1173e-413">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-413">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1173e-414">Excel</span><span class="sxs-lookup"><span data-stu-id="1173e-414">Excel</span></span>

- <span data-ttu-id="1173e-415">修正了只读书籍在打开时不再刷新数据透视表数据的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-415">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="1173e-416">此更改提供了对以下问题的修复：当从OneDrive本地同步文件夹插入文件时，Excel "插入对象 "不显示正确的图标。</span><span class="sxs-lookup"><span data-stu-id="1173e-416">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="1173e-417">修正了当客户在共同创作时，会错误地收到关于新版本文件通知的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-417">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="1173e-418">修正了在覆写模式下使用输入法编辑器会错误地推进额外字符的编辑问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-418">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="1173e-419">修正了在使用实时数据和多线程重新计算功能时所出现的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-419">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="1173e-420">修复了在使用某些 Windows 安全中心漏洞保护设置（SimExec、CallerCheck）时，Excel 无法启动或意外关闭的问题</span><span class="sxs-lookup"><span data-stu-id="1173e-420">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="1173e-421">Outlook</span><span class="sxs-lookup"><span data-stu-id="1173e-421">Outlook</span></span>

- <span data-ttu-id="1173e-422">我们修复了保存到草稿时，SmartLink 格式丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-422">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="1173e-423">修复了替代策略时为用户提供自定义对齐文本方法的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-423">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="1173e-424">我们修复了另存为 OFT 文件时汉字变成问号的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-424">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1173e-425">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1173e-425">PowerPoint</span></span>

- <span data-ttu-id="1173e-426">我们修正了 Slide.Shapes.AddMediaObject2 在使用传统视频格式（MPG-1,Mpeg-2）时会意外关闭的 VBA 问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-426">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="1173e-427">已修复一些损坏的 PowerPoint 文件无法正常打开的问题，即使在执行文档修复操作后也是如此。</span><span class="sxs-lookup"><span data-stu-id="1173e-427">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="1173e-428">Project</span><span class="sxs-lookup"><span data-stu-id="1173e-428">Project</span></span>

- <span data-ttu-id="1173e-429">修正了当以某种方式指定资源分布时，项目可能在打开文件时意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-429">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="1173e-430">Skype</span><span class="sxs-lookup"><span data-stu-id="1173e-430">Skype</span></span>

- <span data-ttu-id="1173e-431">修复了用户的 TLS-DSK 证书无法在预期时间内更新，而是在有效期剩余不到12小时时续订。</span><span class="sxs-lookup"><span data-stu-id="1173e-431">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="1173e-432">修复了当Office尚未获得授权时，Skype for Business用户界面在登录后显示为空白的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-432">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1173e-433">Office 套件</span><span class="sxs-lookup"><span data-stu-id="1173e-433">Office Suite</span></span>

- <span data-ttu-id="1173e-434">此更改解决了与打开包含遗留图的文件相关的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-434">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="1173e-435">此更改解决 SVG 回退代理导致访问违规的问题。</span><span class="sxs-lookup"><span data-stu-id="1173e-435">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)



[//]: # (请勿移除错误详细信息内容结尾)

> [!NOTE]
> <span data-ttu-id="1173e-438">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="1173e-438">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (不修改管理中心元数据内容启动)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13801.20738|版本2102 年-6 月-8 日|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13801.20638|版本 2102-5-11|)
[//]: # (|Win32|FRDC|预览体验| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13801.20294|版本2102 年-march-09|)
[//]: # (|Win32|FRDC|预览体验成员| |16.0.13127.21216 | 版本-2008年2月09日|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.21064 | 版本-2008年1月12日|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20910|2008 年 12 月 8 日版|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20760|2008 年 11 月 10 日版|)
[//]: # (|Win32|FRDC|预览体验计划| |16.0.13127.20638|2008 年 10 月 13 日版|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (不修改管理中心元数据内容结束)
