---
title: 有关 2020 年半年企业频道发行的发行说明
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2020 年 Microsoft 365 应用版半年频道发行的发行说明
ms.openlocfilehash: 893b5374a24fefdbe1fbdc7788370dd5a87e0251
ms.sourcegitcommit: 96185aa6c5a06095c58b57ac36cb2800add8bea0
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/06/2021
ms.locfileid: "49760696"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="c9100-103">有关半年企业频道的发行说明</span><span class="sxs-lookup"><span data-stu-id="c9100-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="c9100-104">我们为 Microsoft 365 企业应用版、Microsoft 365 商业应用版以及 Project 和 Visio 桌面应用的订阅版本提供了半年企业频道更新。这些发行说明提供了有关这些更新中所含新功能和非安全更新的信息。</span><span class="sxs-lookup"><span data-stu-id="c9100-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="c9100-105">我们正在对 Microsoft 365 应用的更新频道进行一些更改，包括添加新的更新频道（月度企业版频道）和更改现有更新频道的名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="c9100-106">若要了解详细信息，请[阅读这篇文章](https://go.microsoft.com/fwlink/p/?linkid=2127441)。</span><span class="sxs-lookup"><span data-stu-id="c9100-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="c9100-107">如果半年企业频道上的用户从 Office 门户下载并在 Windows 10 上安装 Microsoft 365 应用版，现在默认情况下会包括 OneNote 2016。</span><span class="sxs-lookup"><span data-stu-id="c9100-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-2002-december-08"></a><span data-ttu-id="c9100-109">版本 2002：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="c9100-109">Version 2002: December 08</span></span>
<span data-ttu-id="c9100-110">*版本 2002（内部版本 12527.21416）*</span><span class="sxs-lookup"><span data-stu-id="c9100-110">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="c9100-111">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-113">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-114">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-114">Excel</span></span>

- <span data-ttu-id="c9100-115">当从 Excel 中复制内容并使用“嵌入”选项粘贴到 PowerPoint 时，改进了 PowerPoint 中的文本间距调整。</span><span class="sxs-lookup"><span data-stu-id="c9100-115">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="c9100-116">我们修复了 Excel 在重新计算期间停止运行的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-116">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="c9100-117">修复了用户无法直接从 SharePoint 打开 atomsvc (UTF8+BOM) 文件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-117">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="c9100-118">修复了导致在 PowerPivot 中无法从“表预览”和“查询编辑器”进行切换的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-118">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="c9100-119">改进了使用许多最近发布的功能的文件的性能。</span><span class="sxs-lookup"><span data-stu-id="c9100-119">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="c9100-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-120">Outlook</span></span>

- <span data-ttu-id="c9100-121">我们修复了以下问题：设置 OME 配置时会在邮件项目上添加一个无关的附件，这会迫使 Outlook 对邮件进行加密，即使在服务端设置了 DecryptAttachmentsForEncryptOnly 选项也是如此。</span><span class="sxs-lookup"><span data-stu-id="c9100-121">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c9100-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-122">PowerPoint</span></span>

- <span data-ttu-id="c9100-123">修复了以下问题：当用户将源路径更改为本地 OneDrive 文件夹时，链接的 excel 图表出现错误地更改为 excel 工作表。</span><span class="sxs-lookup"><span data-stu-id="c9100-123">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="c9100-124">Project</span><span class="sxs-lookup"><span data-stu-id="c9100-124">Project</span></span>

- <span data-ttu-id="c9100-125">我们修复了以下问题：如果 URL 以 .com 结尾，则无法通过 Project Web App 在 Project 桌面客户端中打开项目。</span><span class="sxs-lookup"><span data-stu-id="c9100-125">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-december-08"></a><span data-ttu-id="c9100-127">版本 1908：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="c9100-127">Version 1908: December 08</span></span>
<span data-ttu-id="c9100-128">*版本 1908（内部版本 11929.20984）*</span><span class="sxs-lookup"><span data-stu-id="c9100-128">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="c9100-129">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出了安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-129">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="c9100-130">版本 2002：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c9100-130">Version 2002: November 10</span></span>
<span data-ttu-id="c9100-131">*版本 2002（内部版本 12527.21330）*</span><span class="sxs-lookup"><span data-stu-id="c9100-131">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="c9100-132">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-132">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-134">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-134">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-135">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-135">Excel</span></span>

- <span data-ttu-id="c9100-136">修复了将 Office 语言设置为西班牙语时出现的问题，在有问题的情况下，数据验证列表可能不会显示列表中的所有项目。</span><span class="sxs-lookup"><span data-stu-id="c9100-136">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="c9100-137">修复了在刷新 OLAP 数据透视表时可能会导致挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-137">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="c9100-138">修复了某些函数在加载工作簿后结果不正确的错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-138">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="c9100-139">解决了与 XLAM 加载项引用和命名范围相关的应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-139">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="c9100-140">修正了运行高级筛选器宏时错误报告错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-140">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="c9100-141">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-141">Outlook</span></span>

- <span data-ttu-id="c9100-142">我们修复了在禁用可选连接体验时导致内部加载项意外禁用的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-142">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="c9100-143">我们修复了导致用户无法作为或代表全局地址列表中隐藏的通讯组列表发送的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-143">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-10"></a><span data-ttu-id="c9100-145">版本 1908：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c9100-145">Version 1908: November 10</span></span>
<span data-ttu-id="c9100-146">*版本 1908（内部版本 11929.20974）*</span><span class="sxs-lookup"><span data-stu-id="c9100-146">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="c9100-147">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-147">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="c9100-148">版本 2002：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="c9100-148">Version 2002: October 13</span></span>
<span data-ttu-id="c9100-149">*版本 2002（内部版本 12527.21236）*</span><span class="sxs-lookup"><span data-stu-id="c9100-149">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="c9100-150">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-152">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-152">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c9100-153">Access</span><span class="sxs-lookup"><span data-stu-id="c9100-153">Access</span></span>

- <span data-ttu-id="c9100-154">只要满足 Access 数据库的指导原则和要求，应该就不会再在 64 位版本的 Access 上收到“查询太复杂”或有关超出系统资源的错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-154">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="c9100-155">当你决定在查询设计器之后使用过滤器功能时，数据库应该就不会再崩溃了。</span><span class="sxs-lookup"><span data-stu-id="c9100-155">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="c9100-156">请进行相应检查。</span><span class="sxs-lookup"><span data-stu-id="c9100-156">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="c9100-157">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-157">Excel</span></span>

- <span data-ttu-id="c9100-158">修复了用户无法修改数据透视表筛选器的问题，因为它被设置为在 Analysis Services 数据库中已不存在的值。</span><span class="sxs-lookup"><span data-stu-id="c9100-158">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c9100-159">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-159">PowerPoint</span></span>

- <span data-ttu-id="c9100-160">通过模板创建的新演示文稿可能会继承妨碍良好的共同创作体验的设置。</span><span class="sxs-lookup"><span data-stu-id="c9100-160">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="c9100-161">此修补程序可确保在这种情况下清除该设置。</span><span class="sxs-lookup"><span data-stu-id="c9100-161">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="c9100-162">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-162">Word</span></span>

- <span data-ttu-id="c9100-163">我们解决了以下问题：打开包含分页符和列的文档时，用户可能遇到错误消息“你已超出 Microsoft Word 所支持的最大页面数目，或文档可能已损坏”</span><span class="sxs-lookup"><span data-stu-id="c9100-163">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="c9100-164">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-164">Office Suite</span></span>

- <span data-ttu-id="c9100-165">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。</span><span class="sxs-lookup"><span data-stu-id="c9100-165">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c9100-166">将信息更改为显示 "碳粉/墨水不足" & "无碳粉/墨水"。</span><span class="sxs-lookup"><span data-stu-id="c9100-166">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-october-13"></a><span data-ttu-id="c9100-168">版本 1908：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="c9100-168">Version 1908: October 13</span></span>
<span data-ttu-id="c9100-169">*版本 1908（内部版本 11929.20966）*</span><span class="sxs-lookup"><span data-stu-id="c9100-169">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="c9100-170">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-170">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-172">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-172">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c9100-173">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-173">Office Suite</span></span>

- <span data-ttu-id="c9100-174">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。</span><span class="sxs-lookup"><span data-stu-id="c9100-174">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c9100-175">将信息更改为显示 "碳粉/墨水不足" & "无碳粉/墨水"。</span><span class="sxs-lookup"><span data-stu-id="c9100-175">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-2002-september-08"></a><span data-ttu-id="c9100-177">版本 2002：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="c9100-177">Version 2002: September 08</span></span>
<span data-ttu-id="c9100-178">*版本 2002（内部版本 12527.21104）*</span><span class="sxs-lookup"><span data-stu-id="c9100-178">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="c9100-179">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-181">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-182">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-182">Excel</span></span>

- <span data-ttu-id="c9100-183">这解决了以下问题：由 SQL 数据提供程序在 Office 的较早版本中创建的连接将内部表属性设置为与 Office 365 不同。</span><span class="sxs-lookup"><span data-stu-id="c9100-183">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="c9100-184">这会导致对于包含在旧版本的 Office 中创建的连接的文件，使用 Office 365 打开时，表预览/查询编辑器下拉列表被禁用。</span><span class="sxs-lookup"><span data-stu-id="c9100-184">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="c9100-185">解决了墨迹书写可能会导致 Excel 停止响应的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-185">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="c9100-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-186">Outlook</span></span>

- <span data-ttu-id="c9100-187">修复了导致用户无法在添加共享邮箱后连接到公用文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-187">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c9100-188">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-188">Office Suite</span></span>

- <span data-ttu-id="c9100-189">此更改解决了“压缩图片”对话框不保留某些用户设置的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-189">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-1908-september-08"></a><span data-ttu-id="c9100-191">版本 1908：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="c9100-191">Version 1908: September 08</span></span>
<span data-ttu-id="c9100-192">*版本 1908（内部版本 11929.20946）*</span><span class="sxs-lookup"><span data-stu-id="c9100-192">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="c9100-193">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-193">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="c9100-194">版本2002:8月11日</span><span class="sxs-lookup"><span data-stu-id="c9100-194">Version 2002: August 11</span></span>
<span data-ttu-id="c9100-195">*版本2002（内部版本12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="c9100-195">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="c9100-196">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-198">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-199">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-199">Excel</span></span>

- <span data-ttu-id="c9100-200">修复了以 "建议只读 "打开的文件无法切换到编辑的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-200">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="c9100-201">OneNote</span><span class="sxs-lookup"><span data-stu-id="c9100-201">OneNote</span></span>

- <span data-ttu-id="c9100-202">已删除多余的身份调用，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="c9100-202">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="c9100-203">改进对共同创作状态的检测，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="c9100-203">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="c9100-204">提高检测错误的能力和同步体验的质量。</span><span class="sxs-lookup"><span data-stu-id="c9100-204">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-205">Outlook</span></span>

- <span data-ttu-id="c9100-206">解决了某些租户启动Outlook时出现重大性能问题的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-206">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="c9100-207">Skype</span><span class="sxs-lookup"><span data-stu-id="c9100-207">Skype</span></span>

- <span data-ttu-id="c9100-208">修复了32位Skype for Business客户端在运行数天后启动屏幕共享时可能出现失败的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-208">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-209">Office Suite</span><span class="sxs-lookup"><span data-stu-id="c9100-209">Office Suite</span></span>

- <span data-ttu-id="c9100-210">修复了一个问题：如果通过组策略关闭自动保存，一些文档可能在打开时不会显示最新的服务器内容，直到用户点击 "可用更新"。</span><span class="sxs-lookup"><span data-stu-id="c9100-210">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-august-11"></a><span data-ttu-id="c9100-212">版本1908:8月11日</span><span class="sxs-lookup"><span data-stu-id="c9100-212">Version 1908: August 11</span></span>
<span data-ttu-id="c9100-213">*版本 1908（内部版本 11929..20934）*</span><span class="sxs-lookup"><span data-stu-id="c9100-213">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="c9100-214">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-214">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="c9100-215">版本1902:8月11日</span><span class="sxs-lookup"><span data-stu-id="c9100-215">Version 1902: August 11</span></span>
<span data-ttu-id="c9100-216">*版本 1902（内部版本 11328.20644）*</span><span class="sxs-lookup"><span data-stu-id="c9100-216">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="c9100-217">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-july-14"></a><span data-ttu-id="c9100-220">版本 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c9100-220">Version 2002: July 14</span></span>
<span data-ttu-id="c9100-221">*版本 2002（内部版本 12527.20880）*</span><span class="sxs-lookup"><span data-stu-id="c9100-221">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="c9100-222">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-222">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="c9100-224">功能更新</span><span class="sxs-lookup"><span data-stu-id="c9100-224">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c9100-225">Access</span><span class="sxs-lookup"><span data-stu-id="c9100-225">Access</span></span>

- <span data-ttu-id="c9100-226">**快速查找链接的表格：** 新的“搜索”框使查找链接的表格成为一项轻松的乐事。</span><span class="sxs-lookup"><span data-stu-id="c9100-226">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="c9100-227">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-227">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="c9100-228">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-228">Excel</span></span>

- <span data-ttu-id="c9100-229">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-229">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="c9100-230">**数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。</span><span class="sxs-lookup"><span data-stu-id="c9100-230">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="c9100-231">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-231">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="c9100-232">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-232">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="c9100-233">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-233">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="c9100-234">在[博客文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-234">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="c9100-235">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-235">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="c9100-236">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="c9100-236">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c9100-237">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-237">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="c9100-238">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="c9100-238">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="c9100-239">在[博客文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-239">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="c9100-240">**关注剩余待办事项：** 选择“解决”可折叠评论并突出显示待处理的项目。</span><span class="sxs-lookup"><span data-stu-id="c9100-240">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="c9100-241">**键入可返回多个值的公式：** 现可键入返回多个值的公式，它们将自动溢出到相邻的单元格中。</span><span class="sxs-lookup"><span data-stu-id="c9100-241">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="c9100-242">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-242">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="c9100-243">在[博客文章](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-243">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="c9100-244">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="c9100-244">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="c9100-245">**手绘：** 让工作簿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="c9100-245">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="c9100-246">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-246">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="c9100-247">在[博客文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-247">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="c9100-248">**查找要找的内容：** 搜索命令、人员、文件、照片、Web 文章等等。</span><span class="sxs-lookup"><span data-stu-id="c9100-248">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="c9100-249">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-249">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="c9100-250">**6 个强大的函数：** 我们添加了六个新函数来增强你的电子表格：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="c9100-250">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="c9100-251">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-251">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="c9100-252">**向左看，向右看… XLOOKUP 在此！** 使用 XLOOKUP 在表或区域中逐行查找所需内容。</span><span class="sxs-lookup"><span data-stu-id="c9100-252">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="c9100-253">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-253">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="c9100-254">在[博客文章](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-254">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="c9100-255">**管理你的大工作簿：** 单元格、公式、图表、表格... 获取包含工作簿统计信息的工作簿的快照。</span><span class="sxs-lookup"><span data-stu-id="c9100-255">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="c9100-256">**随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。</span><span class="sxs-lookup"><span data-stu-id="c9100-256">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="c9100-257">**使用\@提及** 功能引起他人的注意：在批注中使用 @提及，以在需要同事的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="c9100-257">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="c9100-258">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-258">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="c9100-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-259">Outlook</span></span>

- <span data-ttu-id="c9100-260">**在屏幕上显示更多邮件：** 选择“视图”>“使用更紧密的间距”来调整邮件之间的间距。</span><span class="sxs-lookup"><span data-stu-id="c9100-260">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="c9100-261">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-261">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="c9100-262">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-262">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="c9100-263">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="c9100-263">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c9100-264">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-264">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="c9100-265">**让我把它画出来：** 在图片上进行涂鸦或添加绘图画布以使用墨迹表达你的想法。</span><span class="sxs-lookup"><span data-stu-id="c9100-265">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="c9100-266">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-266">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="c9100-267">**获取位置建议：** 在安排约会和会议时，开始键入位置，Outlook 就会推荐会议室、地址和其他邻近位置。</span><span class="sxs-lookup"><span data-stu-id="c9100-267">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="c9100-268">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-268">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="c9100-269">在[博客文章](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-269">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="c9100-270">**针对攻击的高级防护：** 通过 Office 365 高级威胁防护, 可通过电子邮件主题中的超链接、附加邮件、签名邮件、网络路径等的方式抵御攻击。</span><span class="sxs-lookup"><span data-stu-id="c9100-270">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="c9100-271">**Outlook 中的插入链接菜单将插入包含租户管理员定义的权限的链接：** Outlook 插入链接 MRU 中的链接将插入仅对已经拥有权限的用户有效的链接。</span><span class="sxs-lookup"><span data-stu-id="c9100-271">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="c9100-272">这通常会导致请求获得文档访问权限的用户之间发生往来电子邮件。</span><span class="sxs-lookup"><span data-stu-id="c9100-272">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="c9100-273">我们已更新了此体验，现在该链接将通过租户管理员设置的默认权限进行插入。对于 MSIT，这“可供组织编辑”，因此收到以此方式共享的链接的所有内部用户都可以访问它。</span><span class="sxs-lookup"><span data-stu-id="c9100-273">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="c9100-274">**以不同的亮度查看邮件：** 使用“太阳”/“月亮”按钮在阅读窗格中的明暗背景之间切换。</span><span class="sxs-lookup"><span data-stu-id="c9100-274">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="c9100-275">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-275">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="c9100-276">**轻松发现网络钓鱼邮件：** 垃圾邮件和网络钓鱼邮件具有不同的外观，因此你可以轻松从收件箱中识别并删除它们。</span><span class="sxs-lookup"><span data-stu-id="c9100-276">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="c9100-p123">**所有加密选项都在一个位置：** 只需转到“选项”>“加密”以选择如何保护电子邮件。[了解更多](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="c9100-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="c9100-279">**在有拼写错误的情况下进行搜索：** 即使你的拼写有误，Outlook 仍将找到你在查找的内容。</span><span class="sxs-lookup"><span data-stu-id="c9100-279">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="c9100-280">**将 LinkedIn 网络连接到 Outlook：** 以安全的方式将 LinkedIn 帐户连接到 Microsoft 帐户，直接在“人员”卡片中查看 LinkedIn 中的信息。</span><span class="sxs-lookup"><span data-stu-id="c9100-280">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="c9100-281">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-281">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="c9100-282">**查看搜索结果中的相关消息：** Outlook 会分析搜索词，并在搜索结果顶部显示最相关的电子邮件信息。</span><span class="sxs-lookup"><span data-stu-id="c9100-282">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="c9100-283">还会在“热门搜索结果”部分看到按日期排序的所有搜索结果。</span><span class="sxs-lookup"><span data-stu-id="c9100-283">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="c9100-284">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-284">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="c9100-285">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-285">PowerPoint</span></span>

- <span data-ttu-id="c9100-p126">**你来计算，我们来设置格式：** 我们将书写数学表达式更改成标准字符。只需选择“将墨迹转换为数学公式”，再选择手写笔记即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="c9100-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="c9100-289">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="c9100-289">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="c9100-290">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-290">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="c9100-291">**用墨迹绘制精彩绝伦的幻灯片：** 将墨迹转换为标准形状和文本，然后从 PowerPoint 设计器获取智能幻灯片设计灵感。</span><span class="sxs-lookup"><span data-stu-id="c9100-291">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="c9100-292">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-292">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="c9100-293">**手绘：** 让演示文稿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="c9100-293">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="c9100-294">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-294">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="c9100-295">在[博客文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-295">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="c9100-296">**墨迹即时重播：** 在幻灯片上使用墨迹时，可应用重播动画，在幻灯片放映期间重播墨迹的实际绘制过程。</span><span class="sxs-lookup"><span data-stu-id="c9100-296">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="c9100-297">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-297">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="c9100-298">在[博客文章](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-298">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="c9100-299">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="c9100-299">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="c9100-300">**将插图另存为 SVG**：将图表、形状或其他插图另存为可缩放矢量图形，这样做可以调整其大小，而不会降低图像质量。</span><span class="sxs-lookup"><span data-stu-id="c9100-300">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="c9100-301">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-301">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="c9100-302">**打印讲义上的幻灯片编号：** 幻灯片编号将会自动包括在讲义上。</span><span class="sxs-lookup"><span data-stu-id="c9100-302">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="c9100-303">打开或是关闭它们，全都取决于你。</span><span class="sxs-lookup"><span data-stu-id="c9100-303">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="c9100-304">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-304">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="c9100-305">**查找并修复缺失的幻灯片标题：** 幻灯片标题可为你的推销词增色添彩，并使所有用户都可以访问你的幻灯片。</span><span class="sxs-lookup"><span data-stu-id="c9100-305">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="c9100-306">辅助功能检查器显示标题缺失位置，以便你可以快速添加标题。</span><span class="sxs-lookup"><span data-stu-id="c9100-306">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="c9100-307">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-307">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="c9100-308">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="c9100-308">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="c9100-309">在[博客文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-309">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="c9100-310">**更多符合你心情的图标：** 我们添加了超过 300 个新图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-310">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="c9100-311">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="c9100-311">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c9100-312">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-312">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="c9100-313">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-313">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="c9100-314">在[博客文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-314">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="c9100-315">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-315">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="c9100-316">**PowerPoint 中的快速实时协作：** 在 PowerPoint 中快速展开实时协作</span><span class="sxs-lookup"><span data-stu-id="c9100-316">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="c9100-317">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="c9100-317">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="c9100-318">**新增校对工具：** 无需在语言方面倍感压力。</span><span class="sxs-lookup"><span data-stu-id="c9100-318">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="c9100-319">PowerPoint 现在可提供语法和写作建议。</span><span class="sxs-lookup"><span data-stu-id="c9100-319">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="c9100-320">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-320">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="c9100-321">**实时字幕和对白字幕：** 演示者的文字会作为字幕自动显示在屏幕上或翻译成你所选语言的对白字幕。</span><span class="sxs-lookup"><span data-stu-id="c9100-321">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="c9100-322">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-322">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="c9100-323">**全面优化你的演示文稿：** 辅助功能检查器可帮助你在排列幻灯片上的对象时考虑到屏幕阅读器。</span><span class="sxs-lookup"><span data-stu-id="c9100-323">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="c9100-324">在[博客文章](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-324">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="c9100-325">**如果可以重复使用，为何还要重新创建呢？：** 通过重新使用你创建的幻灯片或其他人与你共享的幻灯片来节省时间。</span><span class="sxs-lookup"><span data-stu-id="c9100-325">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="c9100-326">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-326">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="c9100-327">Visio</span><span class="sxs-lookup"><span data-stu-id="c9100-327">Visio</span></span>

- <span data-ttu-id="c9100-328">**在 Excel 中制作优美的 Visio 图表：** 通过将数据置于工作表上来创建流程图或组织结构图。</span><span class="sxs-lookup"><span data-stu-id="c9100-328">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="c9100-329">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-329">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="c9100-330">**返回到“犯罪”的场景：** 使用“犯罪场景调查模板”中的新证据、室内和户外模具，仔细地重新创建罪犯的犯罪场景。</span><span class="sxs-lookup"><span data-stu-id="c9100-330">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-331">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-331">Word</span></span>

- <span data-ttu-id="c9100-332">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="c9100-332">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="c9100-333">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-333">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="c9100-334">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-334">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="c9100-335">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-335">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="c9100-336">在[博客文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-336">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="c9100-337">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-337">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="c9100-338">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-338">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="c9100-339">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="c9100-339">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c9100-340">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-340">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="c9100-341">在[博客文章](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-341">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="c9100-342">**精确擦除：** 从两个橡皮擦尺寸中进行选择以修复小墨迹缺陷。</span><span class="sxs-lookup"><span data-stu-id="c9100-342">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="c9100-343">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-343">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="c9100-344">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="c9100-344">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="c9100-345">在[博客文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-345">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="c9100-346">**手绘：** 让文档中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="c9100-346">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="c9100-347">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-347">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="c9100-348">在[博客文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-348">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="c9100-349">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="c9100-349">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="c9100-350">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-350">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="c9100-351">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="c9100-351">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="c9100-352">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-352">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="c9100-353">**简历编辑器加入 LinkedIn 简历助手：** 简历编辑器提供了一系列专为简历量身定制的语法和样式检查，以使你的写作更加精确和专业。</span><span class="sxs-lookup"><span data-stu-id="c9100-353">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="c9100-354">**其他人可以快速查看你所做的更改：** 共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="c9100-354">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="c9100-355">**修复了 3D 对象合并导致的文档损坏问题：** 修复了 3D 对象合并导致的文档损坏问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-355">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="c9100-356">**合著改进**：提高了在具有修订的文档中进行合著时的 Word 性能。</span><span class="sxs-lookup"><span data-stu-id="c9100-356">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="c9100-357">**合著改进：** 提高了合著时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c9100-357">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="c9100-358">**色彩丰富的协作：** 批注和修订由参与者进行颜色编码，以便你能够轻松看到协作者是谁。</span><span class="sxs-lookup"><span data-stu-id="c9100-358">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="c9100-359">**协同编辑启用宏的文档：** 将 docm 文件保存在 OneDrive for Business 上，并与协作者实时进行编辑。</span><span class="sxs-lookup"><span data-stu-id="c9100-359">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-360">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-360">Office Suite</span></span>

- <span data-ttu-id="c9100-361">**在 PowerPoint for Office 365 中将手写墨迹更改为形状、文本或数学公式：** 从自由格式的墨迹转到几条笔划中的 Office 形状、文本或数学表达式。</span><span class="sxs-lookup"><span data-stu-id="c9100-361">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="c9100-362">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-362">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-365">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-365">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c9100-366">Access</span><span class="sxs-lookup"><span data-stu-id="c9100-366">Access</span></span>

- <span data-ttu-id="c9100-367">此更新修复了使用 ADODB 的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-367">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="c9100-368">VB 代码中的记录器对象可能会错误地报告错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-368">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="c9100-369">Access 模板将不会再导致数据库中的附件列出现故障。</span><span class="sxs-lookup"><span data-stu-id="c9100-369">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="c9100-370">在实例化模板后，你现在应该可以将附件字段添加到数据库中。</span><span class="sxs-lookup"><span data-stu-id="c9100-370">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="c9100-371">此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。</span><span class="sxs-lookup"><span data-stu-id="c9100-371">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="c9100-372">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现“查询已损坏”错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-372">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c9100-373">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-373">Excel</span></span>

- <span data-ttu-id="c9100-374">加速加载本地 OneDrive 文件夹中提供的文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-374">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="c9100-375">修复了 CUBEVALUE 函数有时会返回错误结果的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-375">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="c9100-376">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-376">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c9100-377">在某些情况下，重新打开嵌入 Word 或 PowerPoint 的工作簿时，Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-377">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="c9100-378">修复了未显示上下文菜单中的批注命令的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-378">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="c9100-379">我们修复了数据透视图的右键单击菜单，以便启用“显示详细信息”选项。</span><span class="sxs-lookup"><span data-stu-id="c9100-379">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="c9100-380">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-380">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c9100-381">我们解决了在同一工作簿中单击带有书签的超链接会导致工作簿隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-381">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="c9100-382">当另存为 CSV 文件时，在某些情况下，Excel 可能将所有列合并为一个列。</span><span class="sxs-lookup"><span data-stu-id="c9100-382">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="c9100-383">在受保护工作表中的某个区域内使用 Range.ClearContents 的时间可能比预期的要长。</span><span class="sxs-lookup"><span data-stu-id="c9100-383">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="c9100-384">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-384">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="c9100-385">与功能区交互的 VBA 宏可能在 ScreenUpdating 意外设置为 True 的情况下运行。</span><span class="sxs-lookup"><span data-stu-id="c9100-385">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="c9100-386">修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-386">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="c9100-387">在某些情况下，打开 CSV 文件所花费的时间比预期的长。</span><span class="sxs-lookup"><span data-stu-id="c9100-387">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="c9100-388">在具有不同缩放级别的工作簿之间切换时，在某些情况下 Excel 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-388">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="c9100-389">修复了一个有关 VBA 的问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="c9100-389">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="c9100-390">从按颜色筛选的列复制的数据有时无法正确粘贴。</span><span class="sxs-lookup"><span data-stu-id="c9100-390">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="c9100-391">打开包含对许多其他工作簿（尤其是隐藏窗口）的引用的工作簿将比预期的慢。</span><span class="sxs-lookup"><span data-stu-id="c9100-391">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="c9100-392">解决了如果关闭了源代码簿，则外部链接不会在填充（向下填充、横跨填充等）时更新的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-392">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="c9100-393">修复了当通过 Teams 共享 Excel 窗口时，使用 Ctrl+Shift+箭头键滚动后 Excel 可能变得无响应的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-393">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c9100-394">含有数字签名且在 Excel 2016 中保存的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="c9100-394">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="c9100-395">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-395">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="c9100-396">修正了以下问题：保存到 SharePoint/OneDrive 时，自定义功能区标签的 CustomUI XML 被删除。</span><span class="sxs-lookup"><span data-stu-id="c9100-396">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="c9100-397">使用合并单元格删除列时性能得到改善。</span><span class="sxs-lookup"><span data-stu-id="c9100-397">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="c9100-398">修复了 "打印" 对话框中打印机列表中的打印机名称可能重复的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-398">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="c9100-399">修复了以下问题：在文件重新打开后，如果文件路径太长，外部链接会停止工作。</span><span class="sxs-lookup"><span data-stu-id="c9100-399">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="c9100-400">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-400">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="c9100-401">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-401">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="c9100-402">在筛选列表中插入列所需的时间可能比预期更长。</span><span class="sxs-lookup"><span data-stu-id="c9100-402">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="c9100-403">我们解决了某些复制粘贴图表链接使用映射驱动器地址而不是通用地址的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-403">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="c9100-404">我们解决了以下问题：由于加载程序是按字母顺序加载的，而不是按用户指定的顺序加载，因此会出现“此工作簿目前由另一个工作簿引用，无法关闭”的错误信息。</span><span class="sxs-lookup"><span data-stu-id="c9100-404">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="c9100-405">解决了在单击已打开的工作簿中的指向某个位置的超链接时，工作簿可能会隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-405">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="c9100-406">打开包含对许多其他工作簿（尤其是隐藏窗口）的引用的工作簿将比预期的慢。</span><span class="sxs-lookup"><span data-stu-id="c9100-406">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="c9100-407">使用 VBA 的应用程序。在某些情况下，评估无法用于用户定义的功能。</span><span class="sxs-lookup"><span data-stu-id="c9100-407">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="c9100-408">修复了某些用户可能遇到的嵌入和链接对象 (OLE) 问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-408">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="c9100-409">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="c9100-409">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c9100-410">此更新修复了导致公式栏以不同于预期的字体显示文本的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-410">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="c9100-411">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="c9100-411">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c9100-412">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-412">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c9100-413">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-413">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="c9100-414">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-414">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c9100-415">某些本地化版本的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="c9100-415">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="c9100-416">解决了从模板创建图表时出现的性能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-416">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="c9100-417">修复了一个问题，该问题导致某些用户在将文本转换为包含单元格（具有溢出数组）的列时遇到崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-417">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="c9100-418">使用 Range.Value 和 Range.Value2 (VBA) 会导致公式作为动态数组输入。</span><span class="sxs-lookup"><span data-stu-id="c9100-418">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="c9100-419">修复了以下问题：将以公式开头的@符号被视为隐式交集运算符。</span><span class="sxs-lookup"><span data-stu-id="c9100-419">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="c9100-420">我们修复了包含多个已定义名称的公式的工作表在保存文件时导致时间延长的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-420">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="c9100-421">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-421">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c9100-422">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-422">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="c9100-423">OneNote</span><span class="sxs-lookup"><span data-stu-id="c9100-423">OneNote</span></span>

- <span data-ttu-id="c9100-424">通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="c9100-424">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="c9100-425">在 OneNote 2016 中，通过暂时将联机笔记本中的嵌入式文件和图像的下载推迟到用户导航到相应页面时进行，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="c9100-425">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="c9100-426">通过暂时禁用 OneNote 2016 中的回收站，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="c9100-426">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="c9100-427">当用户尝试删除通常将发送到回收站中的数据时，系统会询问用户是希望保留还是永久删除数据。</span><span class="sxs-lookup"><span data-stu-id="c9100-427">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="c9100-428">通过暂时减少 OneNote 2016 中版本历史记录页面的数量和同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="c9100-428">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="c9100-429">显示了一条通知，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="c9100-429">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="c9100-430">在 OneNote 2016 中，通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="c9100-430">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="c9100-431">对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="c9100-431">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="c9100-432">通过暂时禁用 OneNote 2016 中的应用内视频录制功能，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="c9100-432">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="c9100-433">本地笔记本不受此措施影响。</span><span class="sxs-lookup"><span data-stu-id="c9100-433">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="c9100-434">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="c9100-434">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-435">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-435">Outlook</span></span>

- <span data-ttu-id="c9100-436">我们解决了当使用多个不同分辨率的显示器时，IME（输入法编辑器）窗口会重叠通过IME输入的底层文本的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-436">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="c9100-437">解决了导致用户在 Outlook 中偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-437">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="c9100-438">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="c9100-438">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c9100-439">解决了导致 Web 加载项访问数字权限管理邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-439">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="c9100-440">解决了导致定期约会或会议在达到时区定义更改时出现错误的时间时显示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-440">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="c9100-441">如果在 2019 年使用巴西利亚时区，则定期会议和约会将显示在 2020 年的错误时间段内。</span><span class="sxs-lookup"><span data-stu-id="c9100-441">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="c9100-442">此更改涉及到在巴西利亚时区设置的客户端以及在该时区设置的会议和约会。</span><span class="sxs-lookup"><span data-stu-id="c9100-442">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="c9100-443">通过此更改，Outlook 可覆盖 Outlook 使用的特定时区设置。</span><span class="sxs-lookup"><span data-stu-id="c9100-443">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="c9100-444">若要调用时区覆盖，你必须为当前用户设置注册表项。</span><span class="sxs-lookup"><span data-stu-id="c9100-444">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="c9100-445">注册表项名称必须与时区的内部名称相匹配。</span><span class="sxs-lookup"><span data-stu-id="c9100-445">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="c9100-446">该值表示将使用时区规则的年份代替有效年份。</span><span class="sxs-lookup"><span data-stu-id="c9100-446">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="c9100-447">例如，下面的注册表项替代值将使用 2020 年的 Brazilia 时区规则作为有效规则。</span><span class="sxs-lookup"><span data-stu-id="c9100-447">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="c9100-448">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="c9100-448">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="c9100-449">南美洲标准时间"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="c9100-449">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="c9100-450">解决了导致用户看到会议中的位置字段意外更改的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-450">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="c9100-451">解决了导致会议中的“位置”字段意外更新的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-451">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="c9100-452">解决了导致会议位置在清除后意外添加回会议的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-452">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="c9100-453">解决了导致会议位置字段中的逗号变为分号的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-453">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="c9100-454">启用直接通过本机 Teams 客户端加入 Teams 会议。</span><span class="sxs-lookup"><span data-stu-id="c9100-454">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="c9100-455">解决了导致 Exchange 2010 服务器上的邮箱用户在将附件添加到日历项目时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-455">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="c9100-456">解决了导致用户在答复数字签名邮件时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-456">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="c9100-457">解决了导致用户无法打开某些定期日历项目实例的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-457">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="c9100-458">解决了在某些情况下导致组页眉意外展开的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-458">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="c9100-459">解决了导致文件夹窗格宽度意外改变的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-459">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="c9100-460">解决了 Outlook 无法启用“数据丢失保护”策略的提示问题，这些提示用户针对使用 M365 Business Plus 计划付费的用户。</span><span class="sxs-lookup"><span data-stu-id="c9100-460">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="c9100-461">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-461">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c9100-462">解决了在多个窗口中查看同一项目时可能会导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-462">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="c9100-463">解决了导致用户在 Outlook 中更新其规则时出现 "此计算机上的规则与 Microsoft Exchange 的规则不匹配" 消息的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-463">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="c9100-464">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-464">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c9100-465">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-465">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c9100-466">解决了导致用户在打开“规则”对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-466">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c9100-467">解决了一个问题，该问题导致在某些情况下无法使用相关选项来禁用标记项目突出显示。</span><span class="sxs-lookup"><span data-stu-id="c9100-467">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="c9100-468">解决了在关闭辅助功能检查器窗格后按 S 键时导致用户看到邮件意外发送的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-468">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="c9100-469">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-469">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="c9100-470">解决了导致用户在取消帐户设置时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-470">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="c9100-471">解决了导致 Outlook 在同步滑块设置为较小的设置时出现意外同步所有邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-471">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="c9100-472">解决了具有黑色主题的用户在“发件人”下拉列表中看到白色背景上显示白色文本的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-472">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="c9100-473">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-473">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="c9100-474">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-474">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c9100-475">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-475">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c9100-476">解决了导致第三方应用程序无法发送电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-476">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="c9100-477">解决了导致类别偶尔从电子邮件中消失的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-477">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="c9100-478">解决了导致服务器操作系统上的 Outlook 用户看到错误“防病毒状态：无效”的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-478">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="c9100-479">此版本的 Windows 支持防病毒检测，但没有发现防病毒，尽管已正确配置防病毒。</span><span class="sxs-lookup"><span data-stu-id="c9100-479">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="c9100-480">解决了导致代理人在不同计算机上看到共享邮箱的不同文件夹层次结构的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-480">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="c9100-481">解决了导致代理在经理的日历上编辑现有日历约会时收到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-481">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="c9100-482">解决了导致浏览器仿真设置错误的用户无法完成 Gmail 身份验证提示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-482">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="c9100-483">我们解决了以下问题：如果未选中下载共享文件夹，则共享日历会议 "答复选项" 中缺少 "允许转发" 选项。</span><span class="sxs-lookup"><span data-stu-id="c9100-483">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="c9100-484">解决了导致用户在某次 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-484">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="c9100-485">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-485">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="c9100-486">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-486">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="c9100-487">修复了以下问题：附件工具中缺少“保存到云”按钮。</span><span class="sxs-lookup"><span data-stu-id="c9100-487">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="c9100-488">此更改恢复了在邮件标题中查看多行主题的功能。</span><span class="sxs-lookup"><span data-stu-id="c9100-488">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="c9100-489">解决了导致用户在两个加载项向同一功能区组添加按钮时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-489">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="c9100-490">解决了在将租户默认权限配置为 "任何人" 的情况下，导致无法将链接添加到具有正确租户默认权限的电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-490">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="c9100-491">解决了导致用户无法将电子邮件发送到个人通讯组列表的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-491">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="c9100-492">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-492">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="c9100-493">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-493">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c9100-494">我们修复了可能会阻止文件保存到 WebDAV 位置的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-494">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="c9100-495">解决了在安全性对话框中选择“保存”选项时，导致用户无法将其租户外部的 OneDrive 附件保存到本地计算机的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-495">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="c9100-496">我们解决了在编辑主题后导致 NDR 邮件的正文从 Unicode 更改为 ASCII 的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-496">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="c9100-497">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-497">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c9100-498">解决了在某些情况下导致用户看到电子邮件发送地址与显示的 SMTP 地址不匹配的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-498">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="c9100-499">解决了导致搜索框在高 dpi 模式下未正确对齐的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-499">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="c9100-500">解决了导致用户在检索云设置时在 Outlook 中遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-500">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="c9100-501">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-501">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c9100-502">解决了导致用户在 Outlook 中偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-502">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="c9100-503">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-503">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="c9100-504">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-504">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="c9100-505">解决了导致用户在 Outlook 中偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-505">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c9100-506">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-506">PowerPoint</span></span>

- <span data-ttu-id="c9100-507">解决了在旧版 PPT 批注中使用上下文菜单时可能导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-507">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="c9100-508">改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="c9100-508">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="c9100-509">修复了为打开注释已改进的文件副本的用户中继正确消息传递的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-509">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="c9100-510">Project</span><span class="sxs-lookup"><span data-stu-id="c9100-510">Project</span></span>

- <span data-ttu-id="c9100-511">修复了有时无法正确计算摘要任务日期的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-511">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="c9100-512">修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。</span><span class="sxs-lookup"><span data-stu-id="c9100-512">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="c9100-513">解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="c9100-513">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="c9100-514">解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-514">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="c9100-515">发现了用户在打开只读项目时可能会收到几则消息的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-515">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="c9100-516">修复了以下问题：固定持续时间类型的 100％ 任务可能会错误地将其完成百分比计算为小于 100％ 完成。</span><span class="sxs-lookup"><span data-stu-id="c9100-516">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-517">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-517">Word</span></span>

- <span data-ttu-id="c9100-518">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-518">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="c9100-519">修复了以下问题：在使用“快速打印”打印后尝试进行编辑时，文档中的字词对齐方式会被打乱。</span><span class="sxs-lookup"><span data-stu-id="c9100-519">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="c9100-520">我们修复了表格中文本适应的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-520">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="c9100-521">我们修复了插入水平线不短且居中的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-521">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="c9100-522">构建基块管理器可能显示无效的警报：“你已更改样式、构建基块”。</span><span class="sxs-lookup"><span data-stu-id="c9100-522">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="c9100-523">解决了启用 FileBlick\Word2007Files 策略时出现的协调问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-523">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="c9100-524">我们修复了添加已重命名的 lookup 字段时 Word QuickPart 无法正常工作的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-524">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="c9100-525">我们修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-525">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="c9100-526">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-526">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="c9100-527">此更新修复了 Microsoft Word 中的一个问题，即如果某个敏感度标签策略应用了页眉、页脚或水印，则在应用该标签时插入的长度超过 255 个字符的文本随后将无法通过更改或删除该标签来标识和删除。</span><span class="sxs-lookup"><span data-stu-id="c9100-527">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-528">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-528">Office Suite</span></span>

- <span data-ttu-id="c9100-529">修复了一个问题，即用户在大型 PowerPoint 文件上进行共同创作时遇到过多的网络和 CPU 使用情况。</span><span class="sxs-lookup"><span data-stu-id="c9100-529">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="c9100-530">这是一个修复程序，用于解决在客户端缓存文件时，Project 应用不应阻止网络的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-530">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="c9100-531">我们通过将后台的频道名称更新为 2020 年 1 月的分支中的新频道名称来解决此问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-531">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="c9100-532">我们已修复此问题，接下来，如果设备是由策略管理的，则不会调用 DMS Audience API。</span><span class="sxs-lookup"><span data-stu-id="c9100-532">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="c9100-533">解决了在单个事务中添加和删除应用时删除不完整的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-533">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="c9100-534">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-534">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c9100-535">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-535">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c9100-536">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-536">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c9100-537">我们对新的 AppV51 进行了备份，以修复之前 AppV51 中的回归问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-537">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="c9100-538">我们已经解决了内部操作在失败时引发异常而不是进行记录并继续的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-538">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="c9100-539">受影响的用户将不再被阻止接收更新。</span><span class="sxs-lookup"><span data-stu-id="c9100-539">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="c9100-540">我们的团队增加了客户端支持，可在半年度企业预览版中报告 Office CDN 域上的遥测。</span><span class="sxs-lookup"><span data-stu-id="c9100-540">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="c9100-541">此更改解决了利用 Intel 集成 GPU 的图形适配器所报告的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-541">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="c9100-542">此更改可确保草绘轮廓在功能区中正常工作。</span><span class="sxs-lookup"><span data-stu-id="c9100-542">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="c9100-543">修复了从具有某些特定代理配置的本地位置打开文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-543">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="c9100-544">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="c9100-544">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="c9100-545">修复了可在 Office 切换会话期间防止崩溃并提高用户体验可靠性的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-545">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="c9100-546">此 bug 将更新增强型配置服务 (ECS) url 终结点。</span><span class="sxs-lookup"><span data-stu-id="c9100-546">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="c9100-547">调用此较新的终结点可以提高从 ECS 获取数据的成功率。</span><span class="sxs-lookup"><span data-stu-id="c9100-547">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="c9100-548">此更新修复了 Microsoft Outlook 在用户查看或撰写邮件时不显示当前敏感度标签的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-548">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="c9100-549">修复了从同一 SharePoint 库在 Word/Excel/PowerPoint 中打开多个文件时，只能打开第一个文件进行策略符合性扫描的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-549">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="c9100-550">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="c9100-550">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="c9100-551">在注册表项 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 设置为零的情况下激活加载项时，办公室主机在 Windows 中崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-551">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="c9100-552">此更改可修复此问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-552">This change would fix this issue.</span></span>

- <span data-ttu-id="c9100-553">解决了 TabProcGrowth 注册表值为 REG_SZ 类型启用加载项时，windows 上的 office 主机会出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-553">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="c9100-554">此更新修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-554">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="c9100-555">解决了可能无法正确启动 Access 和 Publisher（具体取决于安装的语言）的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-555">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (请勿移除错误详细信息内容开头)





[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-july-14"></a><span data-ttu-id="c9100-558">版本1908：7月14日</span><span class="sxs-lookup"><span data-stu-id="c9100-558">Version 1908: July 14</span></span>
<span data-ttu-id="c9100-559">*版本 1908（内部版本 11929.20904）*</span><span class="sxs-lookup"><span data-stu-id="c9100-559">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="c9100-560">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-560">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-562">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-562">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c9100-563">Access</span><span class="sxs-lookup"><span data-stu-id="c9100-563">Access</span></span>

- <span data-ttu-id="c9100-564">该更新修复了诸如“总和”等聚合可能将结果截断为整数值的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-564">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="c9100-565">该更新修复了包含对远程表（例如 SQL Server 表）的引用的联合查询可能导致 Access 关闭并重新启动的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-565">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="c9100-566">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现“查询已损坏”错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-566">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c9100-567">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-567">Excel</span></span>

- <span data-ttu-id="c9100-568">荷兰语文档标题快捷键提示已更改为 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="c9100-568">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="c9100-569">修复了 Excel 中的问题，其中分配给形状或表单控件的宏可能显示不正确的错误消息，或者可能在不正确的目标区域中工作。</span><span class="sxs-lookup"><span data-stu-id="c9100-569">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="c9100-570">解决了一个“查找和替换”问题，即在找到第一个项目后它改变了对话框中焦点的位置。</span><span class="sxs-lookup"><span data-stu-id="c9100-570">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="c9100-571">修复了在更改数据透视表的排序方式并在与其他用户进行共同创作会话期间刷新它时可能触发崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-571">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="c9100-572">我们修复了当 OLAP 数据透视表的筛选器设置为已从多维数据集中删除的值时的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-572">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="c9100-573">此更新修复了以下问题：当使用 VBA 向图表的页眉/页脚添加图像时，将会导致出现错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-573">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="c9100-574">我们修复了在更改系列集合时可能导致散点图无法正确呈现的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-574">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="c9100-575">修复了使用图表模板插入图表时预览中所用颜色的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-575">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="c9100-576">解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-576">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="c9100-577">已修复了 Excel 中的合并冲突问题，该问题会导致系统提示用户重新打开工作簿以使更改生效。</span><span class="sxs-lookup"><span data-stu-id="c9100-577">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="c9100-578">解决了导致激活最小化窗口的宏运行时错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-578">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="c9100-579">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-579">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c9100-580">解决了在与其他人共同创作时导致表旁边的剪切和粘贴操作失败的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-580">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="c9100-581">解决了在使用运行的宏更改自定义属性时导致共同创作中断的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-581">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="c9100-582">发生问题时，将无法从加载项打开的 WPF （Windows Presentation Foundation）窗体的组合框中选择项目。</span><span class="sxs-lookup"><span data-stu-id="c9100-582">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="c9100-583">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-583">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c9100-584">修复了在打印预览中或打印时分组框控件的边框不可见的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-584">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="c9100-585">修复了当工作簿中存在外部链接时某些用户可能遇到多个弹出窗口的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-585">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="c9100-586">修复了用户在使用 VBA 宏清除某区域中的内容时可能遇到的性能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-586">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="c9100-587">修复了一个有关 VBA 的问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="c9100-587">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="c9100-588">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-588">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="c9100-589">含有数字签名且在 Excel 2016 中保存的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="c9100-589">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="c9100-590">修复了删除包含合并单元格的列时导致性能降低的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-590">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="c9100-591">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-591">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="c9100-592">将按颜色筛选的数据复制到具有不同宽度的列时，不会粘贴这些值。</span><span class="sxs-lookup"><span data-stu-id="c9100-592">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="c9100-593">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-593">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c9100-594">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-594">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="c9100-595">我们解决了在同一工作簿中单击带有书签的超链接会导致工作簿隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-595">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="c9100-596">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-596">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="c9100-597">某些区域设置的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="c9100-597">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="c9100-598">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-598">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="c9100-599">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="c9100-599">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c9100-600">修复了以下问题：在保存包含图表的工作簿时，图表标题中的图像文件大小增加。</span><span class="sxs-lookup"><span data-stu-id="c9100-600">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="c9100-601">异步用户定义函数的性能问题，该问题导致它们同步运行。</span><span class="sxs-lookup"><span data-stu-id="c9100-601">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="c9100-602">显著提高了删除包含合并单元格的列时的性能。</span><span class="sxs-lookup"><span data-stu-id="c9100-602">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="c9100-603">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-603">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c9100-604">解决了 Lookup 函数可能返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-604">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="c9100-605">修复了以下问题：在使所选区域与交叉引用的工作簿保持同步时，导致交叉引用工作簿中的 DBCS 字符出现损坏。</span><span class="sxs-lookup"><span data-stu-id="c9100-605">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="c9100-606">解决了使用自动调整功能调整行高时复选框控件缩小的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-606">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="c9100-607">当文件具有大量条件格式时，单击“字体颜色”按钮时会出现性能较低的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-607">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="c9100-608">我们修复了打印预览中的打印区域不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-608">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="c9100-609">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-609">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c9100-610">我们显著提高了按颜色筛选的性能。</span><span class="sxs-lookup"><span data-stu-id="c9100-610">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="c9100-611">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。</span><span class="sxs-lookup"><span data-stu-id="c9100-611">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="c9100-612">在加载项管理器中浏览时允许显示超过 16 个加载项。</span><span class="sxs-lookup"><span data-stu-id="c9100-612">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="c9100-613">解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-613">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="c9100-614">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-614">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c9100-615">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-615">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-616">此更新修复了 Office 文档可能无法上传到 OneDrive for business，同时显示“上传失败”消息的错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-616">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="c9100-617">修复了在 Excel 创意功能中发现一个的问题，即通过单击 Win32 客户端中的“创意”按钮加载加载项时出错。</span><span class="sxs-lookup"><span data-stu-id="c9100-617">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="c9100-618">OneNote</span><span class="sxs-lookup"><span data-stu-id="c9100-618">OneNote</span></span>

- <span data-ttu-id="c9100-619">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="c9100-619">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-620">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-620">Outlook</span></span>

- <span data-ttu-id="c9100-621">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-621">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-622">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得与其 Outlook 配置文件关联的错误帐户的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-622">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="c9100-623">解决了导致 Web 加载项在不应该访问“数字版权管理”消息时访问它们的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-623">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="c9100-624">解决了导致简单悬停 URL 无法显示某些安全链接的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-624">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="c9100-625">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="c9100-625">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c9100-626">解决了导致部分 POP3 用户看到无论设置如何，其所有电子邮件均采用纯文本格式的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-626">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="c9100-627">此修补程序将还原 HTML 格式邮件的视图。</span><span class="sxs-lookup"><span data-stu-id="c9100-627">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="c9100-628">解决了在将用户主日历中的项复制到组日历时出现导致用户遇到权限错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-628">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="c9100-629">解决了导致用户无法通过屏幕阅读器访问位置建议的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-629">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="c9100-630">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-630">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c9100-631">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-631">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c9100-632">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-632">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c9100-633">解决了导致用户在打开“规则”对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-633">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c9100-634">解决了导致用户在 Outlook 中与特定安全链接交互时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-634">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="c9100-635">解决了导致经理不清楚代理人是否已响应指定的会议请求的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-635">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="c9100-636">解决了导致用户在处理某些自动发现响应时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-636">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c9100-637">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-637">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c9100-638">该更改能够让管理员能够启用策略以便在自动发现身份验证提示中首选提供的帐户电子邮件而不是 UPN。</span><span class="sxs-lookup"><span data-stu-id="c9100-638">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="c9100-639">默认情况下，自动发现优先于帐户 UPN（如果可用）。</span><span class="sxs-lookup"><span data-stu-id="c9100-639">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="c9100-640">解决导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-640">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="c9100-641">解决了导致 Outlook 用户在某些情况下“需要密码”的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-641">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="c9100-642">解决了导致用户在处理冲突消息时遇到同步失败的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-642">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="c9100-643">解决了导致用户在应用最新的 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-643">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="c9100-644">解决了导致用户在启动 Outlook 时在“正在加载个人资料”屏幕上遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-644">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="c9100-645">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-645">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="c9100-646">修复了以下问题：附件工具中缺少“保存到云”按钮。</span><span class="sxs-lookup"><span data-stu-id="c9100-646">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="c9100-647">默认情况下，保留策略标签会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="c9100-647">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="c9100-648">提供了一个注册表项，允许管理员指定只应显示策略名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-648">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="c9100-649">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = 默认值 1 = 将仅显示保留策略文本的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="c9100-649">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="c9100-650">解决了导致用户在关闭 Outlook 时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-650">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="c9100-651">解决了导致客户在某些场合中看到空会议室列表的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-651">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="c9100-652">解决了导致用户在更改视图时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-652">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="c9100-653">解决了一个问题，该问题导致用户在将共享日历文件夹同步到 OST 时遇到问题，这导致他们与这些文件夹进行交互时出现权限错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-653">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="c9100-654">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到系统崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-654">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="c9100-655">这是[以前的版本中记录的单个 KB](https://support.microsoft.com/zh-CN/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="c9100-655">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/zh-CN/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="c9100-656">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-656">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c9100-657">解决了在使用备用发件人时导致无法显示策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-657">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="c9100-658">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="c9100-658">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="c9100-659">解决了非英语用户邮件中的主题行非常小的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-659">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="c9100-660">解决了导致用户尝试“从错过的对话”消息创建规则时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-660">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="c9100-661">解决了导致某些用户在添加辅助 Exchange 帐户时会看到创建重复的特殊文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-661">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="c9100-662">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-662">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="c9100-663">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-663">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c9100-664">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-664">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="c9100-665">解决导致当前文件夹搜索间歇性失败的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-665">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="c9100-666">解决了导致某些用户在尝试检索 Outlook 的云设置时遇到身份验证错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-666">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="c9100-667">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-667">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c9100-668">解决了导致用户在处理某些自动发现响应时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-668">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c9100-669">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-669">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c9100-670">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-670">PowerPoint</span></span>

- <span data-ttu-id="c9100-671">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-671">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-672">该更改还原 PowerPoint 视频控件易于访问的名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-672">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="c9100-673">我们修复了可能阻止某些动画启动的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-673">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="c9100-674">我们修复了将一个幻灯片从一个演示文稿复制到另一个演示文稿时，可能创建重复母版的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-674">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="c9100-675">改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="c9100-675">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="c9100-676">修复了荧光笔问题：带有黑色荧光笔颜色的白色文本在打印后显示为灰度中的黑色。</span><span class="sxs-lookup"><span data-stu-id="c9100-676">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="c9100-677">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告。</span><span class="sxs-lookup"><span data-stu-id="c9100-677">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="c9100-678">修复了导致协作用户之间的效率降低的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-678">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="c9100-679">可靠性修复：修复了第三方加载项可能导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-679">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="c9100-680">修复了以下问题：当逐步打开文件时，如果其中一张幻灯片包含多个嵌入式媒体流，则可能会出现问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-680">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="c9100-681">我们修复了 Shape.Paste 方法的问题：当用户使用 Shape.Paste 方法复制和粘贴形状时，它会将所选内容更改为粘贴的形状。</span><span class="sxs-lookup"><span data-stu-id="c9100-681">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="c9100-682">我们修复了第一次启动 PowerPoint 时可能不会显示不受信任的加载项的安全警告消息栏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-682">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="c9100-683">修复了某些加载项会在图表中的形状周围引发意外错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-683">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="c9100-684">防止 PowerPoint 用户在尝试联机演示时遇到错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-684">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="c9100-685">Project</span><span class="sxs-lookup"><span data-stu-id="c9100-685">Project</span></span>

- <span data-ttu-id="c9100-686">修复了 Windows 7 上的用户能够从 Project Web App 和 SharePoint 网站打开项目的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-686">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="c9100-687">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-687">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="c9100-688">“全部调配”命令不能正确解决资源的过度分配。</span><span class="sxs-lookup"><span data-stu-id="c9100-688">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="c9100-689">如果你的任务分配为零工作，该任务可能无法标记为已完成，并且始终显示为 99%。</span><span class="sxs-lookup"><span data-stu-id="c9100-689">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="c9100-690">修复了以下问题：由于基准日历发生更改时未更新资源日历，时间表与项目计划之间的实际工时可能不同。</span><span class="sxs-lookup"><span data-stu-id="c9100-690">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="c9100-691">Skype</span><span class="sxs-lookup"><span data-stu-id="c9100-691">Skype</span></span>

- <span data-ttu-id="c9100-692">修复了一个对话正在进行时，选项卡式对话标题姓名的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-692">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="c9100-693">Visio</span><span class="sxs-lookup"><span data-stu-id="c9100-693">Visio</span></span>

- <span data-ttu-id="c9100-694">从 Visio 导出为 SVG 的操作无法用于各种形状。</span><span class="sxs-lookup"><span data-stu-id="c9100-694">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-695">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-695">Word</span></span>

- <span data-ttu-id="c9100-696">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-696">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-697">我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-697">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="c9100-698">修复了使文本适应表格的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-698">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="c9100-699">我们修复了跟踪更改有时会陷入无限循环的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-699">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="c9100-700">我们修复了以下问题：在某些情况下，保存现有文件始终会导致显示“另存为”对话框，而该文件从不实际保存。</span><span class="sxs-lookup"><span data-stu-id="c9100-700">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="c9100-701">我们修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-701">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="c9100-702">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-702">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="c9100-703">修复了应用可能会在关闭时挂起的各种问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-703">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="c9100-704">还修复了某些加载项相关的崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-704">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-705">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-705">Office Suite</span></span>

- <span data-ttu-id="c9100-706">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-706">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="c9100-707">修复了一个问题，该问题导致用户在尝试共享存储在 SharePoint 2016 上的文件时收到消息“抱歉，无法我们共享此内容”。</span><span class="sxs-lookup"><span data-stu-id="c9100-707">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="c9100-708">修复了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-708">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="c9100-709">此修复可解决用户打开文件时可能遇到的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-709">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="c9100-710">在某些情况下，同步引擎支持的 sharepoint 文件可能显示“已保存”，但并未真正保存任何更改，导致数据丢失。</span><span class="sxs-lookup"><span data-stu-id="c9100-710">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="c9100-711">解决了用户可能无法保存 Word、Excel 和 PowerPoint 文档的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-711">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="c9100-712">此问题会影响创建新文件并在单击“保存”图标或按 Ctrl + S 后显示“另存为对话框”选项的用户。</span><span class="sxs-lookup"><span data-stu-id="c9100-712">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="c9100-713">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-713">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="c9100-714">修复了在 PowerPoint 中的竖排文本框中，半角片假名字符未正确旋转的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-714">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="c9100-715">修复了 Win7 中的性能问题，它导致所有应用中功能区内的“插入形状”库大约需要 4 秒钟才会显示。</span><span class="sxs-lookup"><span data-stu-id="c9100-715">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="c9100-716">修复了在后台的信息放置面板中未显示可访问性信息的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-716">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="c9100-717">改进了有关注册表完整性的 Office 更新进程的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c9100-717">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="c9100-718">我们已将 2019 年 1 月和 7 月分支的频道名称更新为新频道名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-718">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="c9100-719">更正了按流量计费的网络上可能意外阻止更新的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-719">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="c9100-720">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-720">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c9100-721">即在某些情况下，Office 快捷方式可能会在更新后消失。</span><span class="sxs-lookup"><span data-stu-id="c9100-721">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="c9100-722">此更新改进了发布 Office 快捷方式的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c9100-722">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="c9100-723">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-723">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c9100-724">解决了以下问题：在某些情况下，如果不是管理员，并且系统帐户没有网络连接，则不会应用更新。</span><span class="sxs-lookup"><span data-stu-id="c9100-724">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="c9100-725">修复了 Office 更新消息以与预期不同的语言显示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-725">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c9100-726">今后，Office 更新消息将正确匹配 Windows 显示语言。</span><span class="sxs-lookup"><span data-stu-id="c9100-726">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="c9100-727">通过恢复以前可能已中断的下载，增强了下载 Office 更新时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c9100-727">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="c9100-728">解决了与第三方插件中的“文本框/形状自动调整”属性相关的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-728">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="c9100-729">此更改解决了打开损坏的文件后正确呈现图像的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-729">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="c9100-730">此更改解决了某些包含标记的散点图呈现缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-730">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="c9100-731">我们修复了大型树视图可能会导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-731">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="c9100-732">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="c9100-732">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="c9100-733">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="c9100-733">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="c9100-734">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="c9100-734">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-july-14"></a><span data-ttu-id="c9100-736">版本 1902：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c9100-736">Version 1902: July 14</span></span>
<span data-ttu-id="c9100-737">*版本 1902（内部版本 11328.20624）*</span><span class="sxs-lookup"><span data-stu-id="c9100-737">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="c9100-738">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-738">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="c9100-739">版本 1908：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="c9100-739">Version 1908: June 09</span></span>
<span data-ttu-id="c9100-740">*版本 1908（内部版本 11929.20838）*</span><span class="sxs-lookup"><span data-stu-id="c9100-740">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="c9100-741">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-741">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-743">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-743">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-744">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-744">Excel</span></span>

- <span data-ttu-id="c9100-745">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-745">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c9100-746">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-746">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="c9100-747">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-747">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-748">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-748">Outlook</span></span>

- <span data-ttu-id="c9100-749">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-749">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-750">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-750">Office Suite</span></span>

- <span data-ttu-id="c9100-751">我们已将 2019 年 1 月和 7 月分支的频道名称更新为新频道名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-751">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-june-09"></a><span data-ttu-id="c9100-753">版本 1902：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="c9100-753">Version 1902: June 09</span></span>
<span data-ttu-id="c9100-754">*版本 1902（内部版本 11328.20602）*</span><span class="sxs-lookup"><span data-stu-id="c9100-754">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="c9100-755">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-755">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-757">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-757">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c9100-758">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-758">Office Suite</span></span>

- <span data-ttu-id="c9100-759">我们已将 2019 年 1 月和 7 月分支的频道名称更新为新频道名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-759">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="c9100-760">我们从中断 C2R 构建的基线文件中删除了过时的引用。</span><span class="sxs-lookup"><span data-stu-id="c9100-760">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-may-12"></a><span data-ttu-id="c9100-762">版本 1908：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="c9100-762">Version 1908: May 12</span></span>
<span data-ttu-id="c9100-763">*版本 1908（内部版本 11929.20776）*</span><span class="sxs-lookup"><span data-stu-id="c9100-763">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="c9100-764">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-764">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-766">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-766">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-767">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-767">Excel</span></span>

- <span data-ttu-id="c9100-768">将按颜色筛选的数据复制到具有不同宽度的列时，不会粘贴这些值。</span><span class="sxs-lookup"><span data-stu-id="c9100-768">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-769">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-769">Outlook</span></span>

- <span data-ttu-id="c9100-770">解决了导致用户在应用最新的 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-770">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-771">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-771">Word</span></span>

- <span data-ttu-id="c9100-772">修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-772">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="c9100-773">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-773">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-may-12"></a><span data-ttu-id="c9100-775">版本 1902：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="c9100-775">Version 1902: May 12</span></span>
<span data-ttu-id="c9100-776">*版本 1902（内部版本 11328.20586）*</span><span class="sxs-lookup"><span data-stu-id="c9100-776">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="c9100-777">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-777">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-779">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-779">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c9100-780">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-780">Outlook</span></span>

- <span data-ttu-id="c9100-781">解决了导致用户在应用最新的 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-781">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="c9100-782">默认情况下，保留策略标签会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="c9100-782">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="c9100-783">提供了一个注册表项，允许管理员指定只应显示策略名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-783">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="c9100-784">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="c9100-784">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="c9100-785">0 = 默认值。</span><span class="sxs-lookup"><span data-stu-id="c9100-785">0 = Default.</span></span>  <span data-ttu-id="c9100-786">1 = 仅显示保留策略文本的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="c9100-786">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-may-04"></a><span data-ttu-id="c9100-788">版本 1908：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="c9100-788">Version 1908: May 04</span></span>
<span data-ttu-id="c9100-789">*版本 1908（内部版本 11929.20752）*</span><span class="sxs-lookup"><span data-stu-id="c9100-789">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="c9100-790">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-790">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c9100-791">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-791">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c9100-792">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-792">Outlook</span></span>

- <span data-ttu-id="c9100-793">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-793">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="c9100-794">解决了导致附件工具中缺少“保存到云”按钮的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-794">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="c9100-795">默认情况下，保留策略标签会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="c9100-795">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="c9100-796">提供了一个注册表项，允许管理员指定只应显示策略名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-796">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="c9100-797">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="c9100-797">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="c9100-798">0 = 默认值 1 = 仅显示保留策略文本的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="c9100-798">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-799">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-799">Office Suite</span></span>

- <span data-ttu-id="c9100-800">修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="c9100-800">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="c9100-801">版本 1902：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="c9100-801">Version 1902: May 04</span></span>
<span data-ttu-id="c9100-802">*版本 1902（生成号 11328.20572）*</span><span class="sxs-lookup"><span data-stu-id="c9100-802">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c9100-803">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-803">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c9100-804">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-804">Office Suite</span></span>

- <span data-ttu-id="c9100-805">修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="c9100-805">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="c9100-806">版本 1908：4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="c9100-806">Version 1908: April 26</span></span>
<span data-ttu-id="c9100-807">*版本1908（内部版本 11929.20736）*</span><span class="sxs-lookup"><span data-stu-id="c9100-807">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="c9100-808">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-808">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c9100-809">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-809">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-810">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-810">Excel</span></span>

- <span data-ttu-id="c9100-811">修复了用户在使用 VBA 宏清除某区域中的内容时可能遇到的性能问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-811">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="c9100-812">修复了 VBA 中的一个问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="c9100-812">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="c9100-813">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-813">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="c9100-814">在 Excel 2016 中保存并且含有数字签名的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="c9100-814">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="c9100-815">OneNote</span><span class="sxs-lookup"><span data-stu-id="c9100-815">OneNote</span></span>

- <span data-ttu-id="c9100-816">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="c9100-816">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="c9100-817">版本 1908：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c9100-817">Version 1908: April 14</span></span>
<span data-ttu-id="c9100-818">*版本 1908 （内部版本 11929.20708）*</span><span class="sxs-lookup"><span data-stu-id="c9100-818">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="c9100-819">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-819">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-821">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-821">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-822">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-822">Excel</span></span>

- <span data-ttu-id="c9100-823">修复了删除包含合并单元格的列时导致性能降低的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-823">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="c9100-824">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-824">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="c9100-825">Skype</span><span class="sxs-lookup"><span data-stu-id="c9100-825">Skype</span></span>

- <span data-ttu-id="c9100-826">修复了一个对话正在进行时，选项卡式对话标题姓名的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-826">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-827">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-827">Outlook</span></span>

- <span data-ttu-id="c9100-828">解决了导致用户在关闭 Outlook 时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-828">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="c9100-829">解决了导致客户在某些场合中看到空会议室列表的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-829">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c9100-830">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-830">PowerPoint</span></span>

- <span data-ttu-id="c9100-831">修复了荧光笔问题：带有黑色荧光笔颜色的白色文本在打印后显示为灰度中的黑色。</span><span class="sxs-lookup"><span data-stu-id="c9100-831">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-832">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-832">Word</span></span>

- <span data-ttu-id="c9100-833">修复了使文本适应表格的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-833">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="c9100-834">版本 1902：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c9100-834">Version 1902: April 14</span></span>
<span data-ttu-id="c9100-835">*版本 1902 （内部版本 11328.20564）*</span><span class="sxs-lookup"><span data-stu-id="c9100-835">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="c9100-836">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-836">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-march-10"></a><span data-ttu-id="c9100-838">版本 1908：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c9100-838">Version 1908: March 10</span></span>
<span data-ttu-id="c9100-839">*版本 1908（内部版本 11929.20648）*</span><span class="sxs-lookup"><span data-stu-id="c9100-839">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="c9100-840">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-840">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-842">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-842">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-843">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-843">Excel</span></span>

- <span data-ttu-id="c9100-844">修复了当工作簿中存在外部链接时某些用户可能遇到多个弹出窗口的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-844">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="c9100-845">某些区域设置的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="c9100-845">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="c9100-846">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-846">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c9100-847">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-847">PowerPoint</span></span>

- <span data-ttu-id="c9100-848">我们修复了 Shape.Paste 方法的问题：当用户使用 Shape.Paste 方法复制和粘贴形状时，它会将所选内容更改为粘贴的形状。</span><span class="sxs-lookup"><span data-stu-id="c9100-848">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="c9100-849">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-849">Word</span></span>

- <span data-ttu-id="c9100-850">我们修复了以下问题：在某些情况下，保存现有文件始终会导致显示“另存为”对话框，而该文件从不实际保存。</span><span class="sxs-lookup"><span data-stu-id="c9100-850">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c9100-851">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-851">Office Suite</span></span>

- <span data-ttu-id="c9100-852">此更改解决了某些包含标记的散点图呈现缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-852">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="c9100-853">版本 1902：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c9100-853">Version 1902: March 10</span></span>
<span data-ttu-id="c9100-854">*版本 1902（内部版本 11328.20554）*</span><span class="sxs-lookup"><span data-stu-id="c9100-854">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="c9100-855">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-855">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-february-11"></a><span data-ttu-id="c9100-857">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c9100-857">Version 1908: February 11</span></span>
<span data-ttu-id="c9100-858">*版本 1908（内部版本 11929.20606）*</span><span class="sxs-lookup"><span data-stu-id="c9100-858">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="c9100-859">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-859">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-861">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-861">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-862">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-862">Excel</span></span>

- <span data-ttu-id="c9100-863">此更新修复了以下问题：当使用 VBA 向图表的页眉/页脚添加图像时，将会导致出现错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-863">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="c9100-864">修复了在打印预览中或打印时分组框控件的边框不可见的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-864">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="c9100-865">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="c9100-865">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c9100-866">修复了以下问题：在保存包含图表的工作簿时，图表标题中的图像文件大小增加。</span><span class="sxs-lookup"><span data-stu-id="c9100-866">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="c9100-867">修复了以下问题：在使所选区域与交叉引用的工作簿保持同步时，导致交叉引用工作簿中的 DBCS 字符出现损坏。</span><span class="sxs-lookup"><span data-stu-id="c9100-867">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="c9100-868">解决了使用自动调整功能调整行高时复选框控件缩小的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-868">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="c9100-869">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-869">Outlook</span></span>

- <span data-ttu-id="c9100-870">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-870">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c9100-871">解决了导致用户在处理冲突消息时遇到同步失败的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-871">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="c9100-872">解决了导致用户在启动 Outlook 时在“正在加载个人资料”屏幕上遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-872">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="c9100-873">解决了导致用户在更改视图时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-873">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="c9100-874">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-874">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="c9100-875">[此处](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是单个 KB，包含针对先前版本记录的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-875">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="c9100-876">解决了一个问题，该问题导致用户在将共享日历文件夹同步到 OST 时遇到问题，这导致他们与这些文件夹进行交互时出现权限错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-876">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c9100-877">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-877">PowerPoint</span></span>

- <span data-ttu-id="c9100-878">改进了复制粘贴方案，即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="c9100-878">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="c9100-879">修复了导致协作用户之间的效率降低的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-879">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="c9100-880">修复了以下问题：当逐步打开文件时，如果其中一张幻灯片包含多个嵌入式媒体流，则可能会出现问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-880">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="c9100-881">我们修复了以下问题：首次启动 PowerPoint 时，不受信任的加载项可能不会显示安全警告消息栏。</span><span class="sxs-lookup"><span data-stu-id="c9100-881">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c9100-882">Project</span><span class="sxs-lookup"><span data-stu-id="c9100-882">Project</span></span>

- <span data-ttu-id="c9100-883">修复了以下问题：由于基准日历发生更改时未更新资源日历，时间表与项目计划之间的实际工时可能不同。</span><span class="sxs-lookup"><span data-stu-id="c9100-883">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-884">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-884">Word</span></span>

- <span data-ttu-id="c9100-885">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-885">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-886">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-886">Office Suite</span></span>

- <span data-ttu-id="c9100-887">此更改解决了打开损坏的文件后正确渲染图像的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-887">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-february-11"></a><span data-ttu-id="c9100-889">版本 1902：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c9100-889">Version 1902: February 11</span></span>
<span data-ttu-id="c9100-890">*版本 1902（内部版本 11328.20526）*</span><span class="sxs-lookup"><span data-stu-id="c9100-890">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="c9100-891">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-891">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-893">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-893">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c9100-894">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-894">Outlook</span></span>

- <span data-ttu-id="c9100-895">解决了用户在发送加密电子邮件时遇到“不支持加密算法“错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-895">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="c9100-896">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-896">Word</span></span>

- <span data-ttu-id="c9100-897">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-897">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

[//]: # (请勿移除错误详细信息内容开头)

## <a name="version-1808-february-11"></a><span data-ttu-id="c9100-900">版本 1808：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c9100-900">Version 1808: February 11</span></span>
<span data-ttu-id="c9100-901">*版本 1808（内部版本 10730.20438）*</span><span class="sxs-lookup"><span data-stu-id="c9100-901">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="c9100-902">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-902">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-january-14"></a><span data-ttu-id="c9100-904">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c9100-904">Version 1908: January 14</span></span>
<span data-ttu-id="c9100-905">*版本 1908（内部版本 11929.20562）*</span><span class="sxs-lookup"><span data-stu-id="c9100-905">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="c9100-906">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-906">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="c9100-908">功能更新</span><span class="sxs-lookup"><span data-stu-id="c9100-908">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c9100-909">Access</span><span class="sxs-lookup"><span data-stu-id="c9100-909">Access</span></span>

- <span data-ttu-id="c9100-910">**密切关注数据库对象：** 可以清楚地看到活动选项卡，轻松拖动选项卡以重新排列它们，并且只需单击一下即可关闭数据库对象。</span><span class="sxs-lookup"><span data-stu-id="c9100-910">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="c9100-911">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="c9100-911">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c9100-912">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="c9100-912">Switching between them has never been easier.</span></span> [<span data-ttu-id="c9100-913">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-913">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c9100-914">**缩放更多空间：** 让缩放框变大，更改字体，缩放功能会记住一切。</span><span class="sxs-lookup"><span data-stu-id="c9100-914">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="c9100-915">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-915">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="c9100-916">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-916">Excel</span></span>

- <span data-ttu-id="c9100-917">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="c9100-917">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c9100-918">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="c9100-918">Switching between them has never been easier.</span></span> [<span data-ttu-id="c9100-919">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-919">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c9100-920">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="c9100-920">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c9100-921">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="c9100-921">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c9100-922">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="c9100-922">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c9100-923">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="c9100-923">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c9100-924">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-924">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c9100-925">**见证工作表生动起来的过程：** 插入动态 3D 图形，观看心跳、行星轨道和霸王龙在整个工作簿中四处跳动。</span><span class="sxs-lookup"><span data-stu-id="c9100-925">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="c9100-926">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-926">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="c9100-p175">**深入发掘数据：** 全新的“想法”按钮可查找数据中的模式并使用这些模式创建智能、个性化的建议。[了解详细信息](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="c9100-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="c9100-929">**协作更简单：** 共同创作改进意味着使用条件格式、单元格样式等时，所做的更改将与协作者无缝合并。</span><span class="sxs-lookup"><span data-stu-id="c9100-929">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="c9100-930">**在类似列上连接表：** 在比较用于合并表的列时，获取和转换 (Power Query) 现在具有近似文本匹配逻辑（也称为模糊匹配）。</span><span class="sxs-lookup"><span data-stu-id="c9100-930">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="c9100-931">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-931">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="c9100-932">**使用 Power Query 增强功能快速编码：** 使用自动完成和语法着色快速完成代码编写。</span><span class="sxs-lookup"><span data-stu-id="c9100-932">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="c9100-933">也可以轻松发现函数、列和参数。</span><span class="sxs-lookup"><span data-stu-id="c9100-933">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="c9100-934">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-934">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c9100-935">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="c9100-935">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c9100-936">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-936">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="c9100-937">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-937">Outlook</span></span>

- <span data-ttu-id="c9100-938">**我们已经为你更新了 Outlook 用户体验：** 简化的体验，以前可供预览，现即将推出，旨在帮助你关注最重要的内容。</span><span class="sxs-lookup"><span data-stu-id="c9100-938">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="c9100-939">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-939">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="c9100-940">**还可自定义的简化功能区：** 最常用的按钮排成一行，带给你简化体验。</span><span class="sxs-lookup"><span data-stu-id="c9100-940">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="c9100-941">可在经典视图和简化视图之间轻松切换，还可固定/取消固定命令。</span><span class="sxs-lookup"><span data-stu-id="c9100-941">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="c9100-942">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-942">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="c9100-943">**移动邮件时继续工作：** Outlook 现在在后台移动邮件，因此你可以在文件夹之间移动大量邮件时继续工作。</span><span class="sxs-lookup"><span data-stu-id="c9100-943">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="c9100-944">**在连续召开的会议之间提供时间：** 默认将会议设置为提前 5-10 分钟结束，让与会者有时间喘口气或来往于不同地点。</span><span class="sxs-lookup"><span data-stu-id="c9100-944">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="c9100-945">**挑选你喜欢的操作：** 不要使用“标志”和“删除”？</span><span class="sxs-lookup"><span data-stu-id="c9100-945">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="c9100-946">“存档”或“标记为已读”呢？</span><span class="sxs-lookup"><span data-stu-id="c9100-946">How about Archive or Mark as Read?</span></span> <span data-ttu-id="c9100-947">使用你最常用的命令自定义快速操作菜单。</span><span class="sxs-lookup"><span data-stu-id="c9100-947">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="c9100-p182">**清晰呈现思路：** 当文本或静态图像不起作用时，请使用动态 GIF 来发表你的观点。[了解详细信息](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="c9100-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="c9100-950">**添加帐户的更快捷方式：** 由于帐户设置改进，现在可以更轻松地将使用双重身份验证的 Outlook.com 和 Gmail 帐户添加到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="c9100-950">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="c9100-951">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-951">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="c9100-952">**告别同步限制：** Outlook 改进意味着文件夹限制已取消，因此请继续操作并同步共享邮箱。</span><span class="sxs-lookup"><span data-stu-id="c9100-952">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="c9100-953">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-953">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c9100-954">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="c9100-954">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c9100-955">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-955">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="c9100-956">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-956">PowerPoint</span></span>

- <span data-ttu-id="c9100-957">**切换效果更好：** 对形状命名，以更好地掌控其平滑效果。</span><span class="sxs-lookup"><span data-stu-id="c9100-957">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="c9100-958">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-958">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="c9100-959">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="c9100-959">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c9100-960">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-960">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c9100-961">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="c9100-961">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c9100-962">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="c9100-962">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c9100-963">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="c9100-963">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c9100-964">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="c9100-964">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c9100-965">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="c9100-965">Switching between them has never been easier.</span></span> [<span data-ttu-id="c9100-966">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-966">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c9100-967">**联机视频获得新的存储位置：** 将视频保存到 Microsoft Stream，以便组织中的任何人都可以看到它。</span><span class="sxs-lookup"><span data-stu-id="c9100-967">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="c9100-968">插入视频链接，只需占用相当于相应文件大小的一小部分的空间，即可享受多媒体演示。</span><span class="sxs-lookup"><span data-stu-id="c9100-968">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="c9100-969">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-969">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="c9100-970">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="c9100-970">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c9100-p190">**邀请受众参加测验或调查：** 幻灯片上放入测验或调查。Office 为你收集并存储该响应。[了解详细信息](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="c9100-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="c9100-p191">**比以往更轻松地插入联机视频：** 想要将 Vimeo 或 YouTube 中的视频放到幻灯片上？只需使用视频页面链接即可。[了解详细信息](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="c9100-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="c9100-977">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-977">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c9100-978">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="c9100-978">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c9100-979">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-979">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="c9100-980">Project</span><span class="sxs-lookup"><span data-stu-id="c9100-980">Project</span></span>

- <span data-ttu-id="c9100-981">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="c9100-981">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c9100-982">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="c9100-982">Switching between them has never been easier.</span></span> [<span data-ttu-id="c9100-983">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-983">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="c9100-984">Visio</span><span class="sxs-lookup"><span data-stu-id="c9100-984">Visio</span></span>

- <span data-ttu-id="c9100-985">**将流程图导出至 Word：** 向 Word 文档自动添加流程图内容，如形状和元数据。</span><span class="sxs-lookup"><span data-stu-id="c9100-985">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="c9100-986">然后自定义文档以创建过程指南和操作手册。</span><span class="sxs-lookup"><span data-stu-id="c9100-986">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="c9100-987">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-987">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="c9100-988">**数据流程图上的 Double-take：** 数据可视化工具流程图上引入注目的新布局干净、清爽且易于理解。</span><span class="sxs-lookup"><span data-stu-id="c9100-988">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="c9100-989">单击“设计”选项卡可查看选项。</span><span class="sxs-lookup"><span data-stu-id="c9100-989">Click the Design tab for options.</span></span>

- <span data-ttu-id="c9100-990">**内置 Azure 模具：** 使用数十个 Azure 模具设计云应用或规划基础结构。</span><span class="sxs-lookup"><span data-stu-id="c9100-990">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="c9100-991">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-991">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="c9100-p197">**告别断开的 Excel 链接：** 找不到链接到 Data Visualizer 图表的 Excel 工作簿？ 重新链接，你又可以开工了。[了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="c9100-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="c9100-995">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="c9100-995">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c9100-996">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="c9100-996">Switching between them has never been easier.</span></span> [<span data-ttu-id="c9100-997">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-997">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c9100-998">**从 Power BI 导出 Visio 视觉对象：** 将 Power BI 导出为 PDF、PowerPoint 文件等时，Power BI 的 Visio 视觉对象现在将会正常显示。</span><span class="sxs-lookup"><span data-stu-id="c9100-998">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="c9100-999">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-999">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="c9100-1000">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-1000">Word</span></span>

- <span data-ttu-id="c9100-1001">**“学习工具”模式可额外支持更多页面颜色：** Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。</span><span class="sxs-lookup"><span data-stu-id="c9100-1001">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="c9100-1002">许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。</span><span class="sxs-lookup"><span data-stu-id="c9100-1002">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="c9100-p201">**使用笔迹编辑器随心编辑：** 使用单个笔划、拆分或连接字词、添加新行或使用手写笔插入字词。[了解详细信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="c9100-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="c9100-p202">**将文档从静态转换为惊艳：** 将文档转换为易于共享的交互式网页，使其在任何设备上都看起来很棒。[了解更多](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="c9100-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="c9100-1007">**增加内容的覆盖面：** 需要让你的文档易于访问？</span><span class="sxs-lookup"><span data-stu-id="c9100-1007">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="c9100-1008">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="c9100-1008">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c9100-1009">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="c9100-1009">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c9100-1010">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="c9100-1010">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c9100-1011">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-1011">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c9100-1012">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="c9100-1012">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c9100-1013">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="c9100-1013">Switching between them has never been easier.</span></span> [<span data-ttu-id="c9100-1014">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-1014">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c9100-p206">**使用 Line Focus 提高理解力：** 专心地逐行浏览文档。调整焦点，一目一行、三行或五行。[了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="c9100-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="c9100-1018">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="c9100-1018">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c9100-1019">**使用\@提及** 功能引起他人的注意：在批注中使用 @提及，以在需要同事的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="c9100-1019">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="c9100-1020">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-1020">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="c9100-1021">**搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。</span><span class="sxs-lookup"><span data-stu-id="c9100-1021">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c9100-1022">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="c9100-1022">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c9100-1023">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="c9100-1023">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="c9100-1024">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-1024">Office Suite</span></span>

- <span data-ttu-id="c9100-1025">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="c9100-1025">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c9100-1026">只需在“文件”>“打开”选项卡上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="c9100-1026">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="c9100-1027">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="c9100-1027">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c9100-1028">**隐私控制：** 对诊断数据和连接体验的全新、更新和改进控制。</span><span class="sxs-lookup"><span data-stu-id="c9100-1028">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="c9100-1029">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-1029">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="c9100-1030">**Office 图标具有新的外观：** Office 图标经过重新设计，可体现简单、强大和智能的 Office 体验。</span><span class="sxs-lookup"><span data-stu-id="c9100-1030">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="c9100-1031">**Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="c9100-1031">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="c9100-1032">了解更多</span><span class="sxs-lookup"><span data-stu-id="c9100-1032">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-1035">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-1035">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c9100-1036">Access</span><span class="sxs-lookup"><span data-stu-id="c9100-1036">Access</span></span>

- <span data-ttu-id="c9100-1037">该更新修复了诸如“总和”等聚合可能将结果截断为整数值的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1037">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="c9100-1038">该更新修复了包含对远程表（例如 SQL Server 表）的引用的联合查询可能导致 Access 关闭并重新启动的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1038">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="c9100-1039">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现&quot;查询已损坏&quot;错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-1039">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c9100-1040">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-1040">Excel</span></span>

- <span data-ttu-id="c9100-1041">荷兰语文档标题快捷键提示已更改为 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="c9100-1041">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="c9100-1042">修复了 Excel 中的问题，其中分配给形状或表单控件的宏可能显示不正确的错误消息，或者可能在不正确的目标区域中工作。</span><span class="sxs-lookup"><span data-stu-id="c9100-1042">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="c9100-1043">解决了一个“查找和替换”问题，即在找到第一个项目后它改变了对话框中焦点的位置。</span><span class="sxs-lookup"><span data-stu-id="c9100-1043">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="c9100-1044">修复了在更改数据透视表的排序方式并在与其他用户进行共同创作会话期间刷新它时可能触发崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1044">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="c9100-1045">我们修复了当 OLAP 数据透视表的筛选器设置为已从多维数据集中删除的值时的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1045">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="c9100-1046">修复了使用图表模板插入图表时预览中所用颜色的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1046">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="c9100-1047">我们修复了在更改系列集合时可能导致散点图和折线图无法正确呈现的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1047">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="c9100-1048">解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1048">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="c9100-1049">已修复了 Excel 中的合并冲突问题，该问题会导致系统提示用户重新打开工作簿以使更改生效。</span><span class="sxs-lookup"><span data-stu-id="c9100-1049">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="c9100-1050">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1050">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c9100-1051">解决了导致激活最小化窗口的宏运行时错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1051">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="c9100-1052">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1052">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c9100-1053">解决了在与其他人共同创作时导致表旁边的剪切和粘贴操作失败的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1053">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="c9100-1054">解决了在使用运行的宏更改自定义属性时导致共同创作中断的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1054">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="c9100-1055">发生问题时，将无法从加载项打开的 WPF （Windows Presentation Foundation）窗体的组合框中选择项目。</span><span class="sxs-lookup"><span data-stu-id="c9100-1055">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="c9100-1056">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1056">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c9100-1057">异步用户定义函数的性能问题，该问题导致它们同步运行。</span><span class="sxs-lookup"><span data-stu-id="c9100-1057">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="c9100-1058">显著提高了删除包含合并单元格的列时的性能。</span><span class="sxs-lookup"><span data-stu-id="c9100-1058">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="c9100-1059">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1059">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c9100-1060">解决了 Lookup 函数可能返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1060">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="c9100-1061">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。</span><span class="sxs-lookup"><span data-stu-id="c9100-1061">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="c9100-1062">当文件具有大量条件格式时，单击“字体颜色”按钮时会出现性能较低的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1062">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="c9100-1063">我们修复了打印预览中的打印区域不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1063">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="c9100-1064">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1064">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c9100-1065">我们显著提高了按颜色筛选的性能。</span><span class="sxs-lookup"><span data-stu-id="c9100-1065">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="c9100-1066">解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1066">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="c9100-1067">在加载项管理器中浏览时允许显示超过 16 个加载项。</span><span class="sxs-lookup"><span data-stu-id="c9100-1067">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="c9100-1068">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1068">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c9100-1069">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-1069">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-1070">此更新修复了 Office 文档可能无法上传到 OneDrive for business，同时显示“上传失败”消息的错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-1070">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="c9100-1071">修复了在 Excel 创意功能中发现一个的问题，即通过单击 Win32 客户端中的“创意”按钮加载加载项时出错。</span><span class="sxs-lookup"><span data-stu-id="c9100-1071">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-1072">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-1072">Outlook</span></span>

- <span data-ttu-id="c9100-1073">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-1073">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-1074">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得与其 Outlook 配置文件关联的错误帐户的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1074">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="c9100-1075">解决了导致 Web 加载项在不应该访问“数字版权管理”消息时访问它们的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1075">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="c9100-1076">解决了导致简单悬停 URL 无法显示某些安全链接的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1076">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="c9100-1077">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="c9100-1077">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c9100-1078">解决了导致部分 POP3 用户看到无论设置如何，其所有电子邮件均采用纯文本格式的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1078">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="c9100-1079">此修补程序将还原 HTML 格式邮件的视图。</span><span class="sxs-lookup"><span data-stu-id="c9100-1079">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="c9100-1080">解决了在将用户主日历中的项复制到组日历时出现导致用户遇到权限错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1080">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="c9100-1081">解决了导致用户无法通过屏幕阅读器访问位置建议的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1081">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="c9100-1082">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1082">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c9100-1083">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1083">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c9100-1084">解决了导致用户在打开规则对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1084">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c9100-1085">解决了导致用户在 Outlook 中与特定安全链接交互时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1085">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="c9100-1086">解决了导致经理不清楚代理人是否已响应指定的会议请求的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1086">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="c9100-1087">解决了导致用户在处理某些自动发现响应时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1087">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c9100-1088">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1088">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c9100-1089">该更改能够让管理员能够启用策略以便在自动发现身份验证提示中首选提供的帐户电子邮件而不是 UPN。</span><span class="sxs-lookup"><span data-stu-id="c9100-1089">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="c9100-1090">默认情况下，自动发现优先于帐户 UPN（如果可用）。</span><span class="sxs-lookup"><span data-stu-id="c9100-1090">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="c9100-1091">解决了导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1091">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="c9100-1092">解决了导致 Outlook 用户在某些情况下“需要密码”的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1092">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="c9100-1093">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="c9100-1093">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="c9100-1094">解决了用户在发送加密电子邮件时遇到“不支持加密算法“错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1094">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="c9100-1095">解决了非英语用户邮件中的主题行非常小的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1095">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="c9100-1096">解决了导致某些用户在添加辅助 Exchange 帐户时会看到创建重复的特殊文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1096">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="c9100-1097">解决了导致用户尝试“从错过的对话”消息创建规则时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1097">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="c9100-1098">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1098">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c9100-1099">解决了在使用备用发件人时导致无法显示策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1099">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="c9100-1100">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1100">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c9100-1101">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1101">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="c9100-1102">解决了导致当前文件夹搜索间歇性失败的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1102">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="c9100-1103">解决了导致某些用户在尝试检索 Outlook 的云设置时遇到身份验证错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1103">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="c9100-1104">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1104">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c9100-1105">解决了导致用户在处理某些自动发现响应时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1105">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c9100-1106">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1106">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c9100-1107">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-1107">PowerPoint</span></span>

- <span data-ttu-id="c9100-1108">修复了某些加载项会在图表中的形状周围引发意外错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1108">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="c9100-1109">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-1109">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-1110">该更改还原 PowerPoint 视频控件易于访问的名称。</span><span class="sxs-lookup"><span data-stu-id="c9100-1110">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="c9100-1111">我们修复了可能阻止某些动画启动的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1111">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="c9100-1112">我们修复了将一个幻灯片从一个演示文稿复制到另一个演示文稿时，可能创建重复母版的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1112">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="c9100-1113">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告</span><span class="sxs-lookup"><span data-stu-id="c9100-1113">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="c9100-1114">可靠性修复：修复了第三方加载项可能导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1114">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="c9100-1115">修复了在 PowerPoint 中的竖排文本框中，半角片假名字符未正确旋转的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1115">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c9100-1116">Project</span><span class="sxs-lookup"><span data-stu-id="c9100-1116">Project</span></span>

- <span data-ttu-id="c9100-1117">修复了 Windows 7 上的用户能够从 Project Web App 和 SharePoint 网站打开项目的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1117">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="c9100-1118">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1118">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="c9100-1119">“全部调配”命令不能正确解决资源的过度分配。</span><span class="sxs-lookup"><span data-stu-id="c9100-1119">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="c9100-1120">如果你的任务分配为零工作，该任务可能无法标记为已完成，并且始终显示为 99%。</span><span class="sxs-lookup"><span data-stu-id="c9100-1120">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="c9100-1121">Visio</span><span class="sxs-lookup"><span data-stu-id="c9100-1121">Visio</span></span>

- <span data-ttu-id="c9100-1122">从 Visio 导出为 SVG 的操作无法用于各种形状。</span><span class="sxs-lookup"><span data-stu-id="c9100-1122">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-1123">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-1123">Word</span></span>

- <span data-ttu-id="c9100-1124">此更改将提升使用 Word 打开文档的效率。</span><span class="sxs-lookup"><span data-stu-id="c9100-1124">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="c9100-1125">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="c9100-1125">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c9100-1126">我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1126">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="c9100-1127">我们修复了跟踪更改有时会陷入无限循环的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1127">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="c9100-1128">修复了应用可能会在关闭时挂起的各种问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1128">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="c9100-1129">还修复了某些加载项相关的崩溃。</span><span class="sxs-lookup"><span data-stu-id="c9100-1129">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c9100-1130">Office 套件</span><span class="sxs-lookup"><span data-stu-id="c9100-1130">Office Suite</span></span>

- <span data-ttu-id="c9100-1131">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1131">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="c9100-1132">修复了一个问题，该问题导致用户在尝试共享存储在 SharePoint 2016 上的文件时收到消息“抱歉，无法我们共享此内容”。</span><span class="sxs-lookup"><span data-stu-id="c9100-1132">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="c9100-1133">修复了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1133">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="c9100-1134">此修复可解决用户打开文件时可能遇到的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1134">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="c9100-1135">防止 PowerPoint 用户在尝试联机演示时遇到错误。</span><span class="sxs-lookup"><span data-stu-id="c9100-1135">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="c9100-1136">在某些情况下，同步引擎支持的 sharepoint 文件可能显示“已保存”，但并未真正保存任何更改，导致数据丢失。</span><span class="sxs-lookup"><span data-stu-id="c9100-1136">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="c9100-1137">解决了用户可能无法保存 Word、Excel 和 PowerPoint 文档的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1137">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="c9100-1138">此问题会影响创建新文件并在单击“保存”图标或按 Ctrl + S 后显示“另存为对话框”选项的用户。</span><span class="sxs-lookup"><span data-stu-id="c9100-1138">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="c9100-1139">修复了 Win7 中的性能问题，它导致所有应用中功能区内的“插入形状”库大约需要 4 秒钟才会显示。</span><span class="sxs-lookup"><span data-stu-id="c9100-1139">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="c9100-1140">修复了在后台的信息放置面板中未显示可访问性信息的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1140">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="c9100-1141">改进了有关注册表完整性的 Office 更新进程的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c9100-1141">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="c9100-1142">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1142">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c9100-1143">修复了 Office 更新消息以与预期不同的语言显示的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1143">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c9100-1144">今后，Office 更新消息将正确匹配 Windows 显示语言。</span><span class="sxs-lookup"><span data-stu-id="c9100-1144">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="c9100-1145">解决了以下问题：在某些情况下，如果不是管理员，并且系统帐户没有网络连接，则不会应用更新。</span><span class="sxs-lookup"><span data-stu-id="c9100-1145">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="c9100-1146">即在某些情况下，Office 快捷方式可能会在更新后消失。</span><span class="sxs-lookup"><span data-stu-id="c9100-1146">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="c9100-1147">此更新改进了发布 Office 快捷方式的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c9100-1147">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="c9100-1148">更正了按流量计费的网络上可能意外阻止更新的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1148">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="c9100-1149">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1149">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c9100-1150">通过恢复以前可能已中断的下载，增强了下载 Office 更新时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="c9100-1150">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="c9100-1151">解决了与第三方插件中的“文本框/形状自动调整”属性相关的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1151">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="c9100-1152">我们修复了大型树视图可能会导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1152">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="c9100-1153">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="c9100-1153">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-january-14"></a><span data-ttu-id="c9100-1155">版本 1902：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c9100-1155">Version 1902: January 14</span></span>
<span data-ttu-id="c9100-1156">*版本 1902（内部版本 11328.20512）*</span><span class="sxs-lookup"><span data-stu-id="c9100-1156">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="c9100-1157">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-1157">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="c9100-1159">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="c9100-1159">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c9100-1160">Excel</span><span class="sxs-lookup"><span data-stu-id="c9100-1160">Excel</span></span>

- <span data-ttu-id="c9100-1161">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1161">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="c9100-1162">Outlook</span><span class="sxs-lookup"><span data-stu-id="c9100-1162">Outlook</span></span>

- <span data-ttu-id="c9100-1163">解决了用户在发送加密电子邮件时遇到“不支持加密算法“错误的问题。</span><span class="sxs-lookup"><span data-stu-id="c9100-1163">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c9100-1164">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c9100-1164">PowerPoint</span></span>

- <span data-ttu-id="c9100-1165">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告。</span><span class="sxs-lookup"><span data-stu-id="c9100-1165">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="c9100-1166">Word</span><span class="sxs-lookup"><span data-stu-id="c9100-1166">Word</span></span>

- <span data-ttu-id="c9100-1167">此更改将提升使用 Word 打开文档的效率。</span><span class="sxs-lookup"><span data-stu-id="c9100-1167">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1808-january-14"></a><span data-ttu-id="c9100-1169">版本 1808：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c9100-1169">Version 1808: January 14</span></span>
<span data-ttu-id="c9100-1170">*版本 1808（内部版本 10730.20432）*</span><span class="sxs-lookup"><span data-stu-id="c9100-1170">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="c9100-1171">[此处](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="c9100-1171">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

> [!NOTE]
> <span data-ttu-id="c9100-1173">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="c9100-1173">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (不修改管理中心元数据内容启动)
[//]: # (|Win32|DC|生产| |16.0.12527.21416|2002 年 12 月 8 日版|)
[//]: # (|Win32|DC|生产| |16.0.12527.21330|2002 年 11 月 10 日版|)
[//]: # (|Win32|DC|生产| |16.0.12527.21236|2002 年 10 月 13 日版|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|版本-2002年8月11日|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (不修改管理中心元数据内容结束)
