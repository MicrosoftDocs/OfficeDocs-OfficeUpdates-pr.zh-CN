---
title: 有关半年频道发行的已存档发行说明
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 Office 365 专业增强版半年频道发行的发行说明
ms.openlocfilehash: 983782e92fbcaeebe5bbcfceee691fee57134da3
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026337"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="2ddd8-103">有关半年企业频道的已存档发行说明</span><span class="sxs-lookup"><span data-stu-id="2ddd8-103">Archived Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="2ddd8-104">这些发行说明提供了 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 商业版的半年企业频道更新中所包含的新功能和非安全更新的相关信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates to Office 365 ProPlus, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="2ddd8-105">我们经常会过一段时间就将功能（有时甚至是修补程序）发布到半年企业频道。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-105">We often roll out features (and sometimes even fixes) to Semi-Annual Enterprise Channel over a period of time.</span></span> <span data-ttu-id="2ddd8-106">即使没有立即看到下述内容，也会很快就能看到的。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-106">If you don't see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="2ddd8-107">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
> - <span data-ttu-id="2ddd8-108">如果半年企业频道上的用户从 Office 门户在 Windows 10 上下载并安装 Office 365，则默认情况下不会包括 OneNote 2016。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-108">OneNote 2016 will not be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Office 365 on Windows 10 from the Office Portal.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-december-08"></a><span data-ttu-id="2ddd8-110">版本 2002：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-110">Version 2002: December 08</span></span>
<span data-ttu-id="2ddd8-111">*版本 2002（内部版本 12527.21416）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-111">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="2ddd8-112">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-112">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-114">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-115">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-115">Excel</span></span>

- <span data-ttu-id="2ddd8-116">当从 Excel 中复制内容并使用“嵌入”选项粘贴到 PowerPoint 时，改进了 PowerPoint 中的文本间距调整。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-116">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="2ddd8-117">我们修复了 Excel 在重新计算期间停止运行的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-117">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="2ddd8-118">修复了用户无法直接从 SharePoint 打开 atomsvc (UTF8+BOM) 文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-118">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="2ddd8-119">修复了导致在 PowerPivot 中无法从“表预览”和“查询编辑器”进行切换的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-119">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="2ddd8-120">改进了使用许多最近发布的功能的文件的性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-120">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="2ddd8-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-121">Outlook</span></span>

- <span data-ttu-id="2ddd8-122">我们修复了以下问题：设置 OME 配置时会在邮件项目上添加一个无关的附件，这会迫使 Outlook 对邮件进行加密，即使在服务端设置了 DecryptAttachmentsForEncryptOnly 选项也是如此。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-122">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2ddd8-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-123">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-124">修复了以下问题：当用户将源路径更改为本地 OneDrive 文件夹时，链接的 excel 图表出现错误地更改为 excel 工作表。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-124">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="2ddd8-125">Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-125">Project</span></span>

- <span data-ttu-id="2ddd8-126">我们修复了以下问题：如果 URL 以 .com 结尾，则无法通过 Project Web App 在 Project 桌面客户端中打开项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-126">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-december-08"></a><span data-ttu-id="2ddd8-128">版本 1908：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-128">Version 1908: December 08</span></span>
<span data-ttu-id="2ddd8-129">*版本 1908（内部版本 11929.20984）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-129">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="2ddd8-130">[此处](./microsoft365-apps-security-updates.md)列出了安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-130">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="2ddd8-131">版本 2002：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-131">Version 2002: November 10</span></span>
<span data-ttu-id="2ddd8-132">*版本 2002（内部版本 12527.21330）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-132">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="2ddd8-133">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-133">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-135">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-136">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-136">Excel</span></span>

- <span data-ttu-id="2ddd8-137">修复了将 Office 语言设置为西班牙语时出现的问题，在有问题的情况下，数据验证列表可能不会显示列表中的所有项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-137">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="2ddd8-138">修复了在刷新 OLAP 数据透视表时可能会导致挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-138">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="2ddd8-139">修复了某些函数在加载工作簿后结果不正确的错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-139">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="2ddd8-140">解决了与 XLAM 加载项引用和命名范围相关的应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-140">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="2ddd8-141">修正了运行高级筛选器宏时错误报告错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-141">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="2ddd8-142">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-142">Outlook</span></span>

- <span data-ttu-id="2ddd8-143">我们修复了在禁用可选连接体验时导致内部加载项意外禁用的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-143">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="2ddd8-144">我们修复了导致用户无法作为或代表全局地址列表中隐藏的通讯组列表发送的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-144">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-10"></a><span data-ttu-id="2ddd8-146">版本 1908：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-146">Version 1908: November 10</span></span>
<span data-ttu-id="2ddd8-147">*版本 1908（内部版本 11929.20974）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-147">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="2ddd8-148">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-148">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="2ddd8-149">版本 2002：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-149">Version 2002: October 13</span></span>
<span data-ttu-id="2ddd8-150">*版本 2002（内部版本 12527.21236）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-150">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="2ddd8-151">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-151">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-153">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-153">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-154">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-154">Access</span></span>

- <span data-ttu-id="2ddd8-155">只要满足 Access 数据库的指导原则和要求，应该就不会再在 64 位版本的 Access 上收到“查询太复杂”或有关超出系统资源的错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-155">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="2ddd8-156">当你决定在查询设计器之后使用过滤器功能时，数据库应该就不会再崩溃了。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-156">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="2ddd8-157">请进行相应检查。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-157">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="2ddd8-158">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-158">Excel</span></span>

- <span data-ttu-id="2ddd8-159">修复了用户无法修改数据透视表筛选器的问题，因为它被设置为在 Analysis Services 数据库中已不存在的值。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-159">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2ddd8-160">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-160">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-161">通过模板创建的新演示文稿可能会继承妨碍良好的共同创作体验的设置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-161">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="2ddd8-162">此修补程序可确保在这种情况下清除该设置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-162">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="2ddd8-163">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-163">Word</span></span>

- <span data-ttu-id="2ddd8-164">我们解决了以下问题：打开包含分页符和列的文档时，用户可能遇到错误消息“你已超出 Microsoft Word 所支持的最大页面数目，或文档可能已损坏”</span><span class="sxs-lookup"><span data-stu-id="2ddd8-164">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="2ddd8-165">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-165">Office Suite</span></span>

- <span data-ttu-id="2ddd8-166">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-166">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2ddd8-167">将信息更改为显示 "碳粉/墨水不足" & "无碳粉/墨水"。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-167">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-october-13"></a><span data-ttu-id="2ddd8-169">版本 1908：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-169">Version 1908: October 13</span></span>
<span data-ttu-id="2ddd8-170">*版本 1908（内部版本 11929.20966）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-170">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="2ddd8-171">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-171">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-173">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-173">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2ddd8-174">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-174">Office Suite</span></span>

- <span data-ttu-id="2ddd8-175">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-175">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2ddd8-176">将信息更改为显示 "碳粉/墨水不足" & "无碳粉/墨水"。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-176">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-2002-september-08"></a><span data-ttu-id="2ddd8-178">版本 2002：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-178">Version 2002: September 08</span></span>
<span data-ttu-id="2ddd8-179">*版本 2002（内部版本 12527.21104）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-179">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="2ddd8-180">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-180">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-182">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-182">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-183">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-183">Excel</span></span>

- <span data-ttu-id="2ddd8-184">这解决了以下问题：由 SQL 数据提供程序在 Office 的较早版本中创建的连接将内部表属性设置为与 Office 365 不同。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-184">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="2ddd8-185">这会导致对于包含在旧版本的 Office 中创建的连接的文件，使用 Office 365 打开时，表预览/查询编辑器下拉列表被禁用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-185">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="2ddd8-186">解决了墨迹书写可能会导致 Excel 停止响应的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-186">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2ddd8-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-187">Outlook</span></span>

- <span data-ttu-id="2ddd8-188">修复了导致用户无法在添加共享邮箱后连接到公用文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-188">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2ddd8-189">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-189">Office Suite</span></span>

- <span data-ttu-id="2ddd8-190">此更改解决了“压缩图片”对话框不保留某些用户设置的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-190">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (请勿删除 Bug 详细信息内容结尾)

## <a name="version-1908-september-08"></a><span data-ttu-id="2ddd8-192">版本 1908：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-192">Version 1908: September 08</span></span>
<span data-ttu-id="2ddd8-193">*版本 1908（内部版本 11929.20946）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-193">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="2ddd8-194">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-194">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="2ddd8-195">版本2002:8月11日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-195">Version 2002: August 11</span></span>
<span data-ttu-id="2ddd8-196">*版本2002（内部版本12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-196">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="2ddd8-197">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-197">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-199">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-199">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-200">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-200">Excel</span></span>

- <span data-ttu-id="2ddd8-201">修复了以 "建议只读 "打开的文件无法切换到编辑的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-201">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="2ddd8-202">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ddd8-202">OneNote</span></span>

- <span data-ttu-id="2ddd8-203">已删除多余的身份调用，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-203">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="2ddd8-204">改进对共同创作状态的检测，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-204">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="2ddd8-205">提高检测错误的能力和同步体验的质量。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-205">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-206">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-206">Outlook</span></span>

- <span data-ttu-id="2ddd8-207">解决了某些租户启动Outlook时出现重大性能问题的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-207">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="2ddd8-208">Skype</span><span class="sxs-lookup"><span data-stu-id="2ddd8-208">Skype</span></span>

- <span data-ttu-id="2ddd8-209">修复了32位Skype for Business客户端在运行数天后启动屏幕共享时可能出现失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-209">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-210">Office Suite</span><span class="sxs-lookup"><span data-stu-id="2ddd8-210">Office Suite</span></span>

- <span data-ttu-id="2ddd8-211">修复了一个问题：如果通过组策略关闭自动保存，一些文档可能在打开时不会显示最新的服务器内容，直到用户点击 "可用更新"。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-211">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-august-11"></a><span data-ttu-id="2ddd8-213">版本1908:8月11日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-213">Version 1908: August 11</span></span>
<span data-ttu-id="2ddd8-214">*版本 1908（内部版本 11929..20934）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-214">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="2ddd8-215">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-215">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="2ddd8-216">版本1902:8月11日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-216">Version 1902: August 11</span></span>
<span data-ttu-id="2ddd8-217">*版本 1902（内部版本 11328.20644）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-217">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="2ddd8-218">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-218">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-july-14"></a><span data-ttu-id="2ddd8-221">版本 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-221">Version 2002: July 14</span></span>
<span data-ttu-id="2ddd8-222">*版本 2002（内部版本 12527.20880）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-222">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="2ddd8-223">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-223">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ddd8-225">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-225">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-226">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-226">Access</span></span>

- <span data-ttu-id="2ddd8-227">**快速查找链接的表格：** 新的“搜索”框使查找链接的表格成为一项轻松的乐事。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-227">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="2ddd8-228">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-228">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="2ddd8-229">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-229">Excel</span></span>

- <span data-ttu-id="2ddd8-230">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-230">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2ddd8-231">**数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-231">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="2ddd8-232">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-232">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2ddd8-233">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-233">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2ddd8-234">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-234">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2ddd8-235">在[博客文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-235">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2ddd8-236">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-236">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2ddd8-237">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-237">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ddd8-238">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-238">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2ddd8-239">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-239">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2ddd8-240">在[博客文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-240">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2ddd8-241">**关注剩余待办事项：** 选择“解决”可折叠评论并突出显示待处理的项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-241">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="2ddd8-242">**键入可返回多个值的公式：** 现可键入返回多个值的公式，它们将自动溢出到相邻的单元格中。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-242">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="2ddd8-243">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-243">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="2ddd8-244">在[博客文章](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-244">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="2ddd8-245">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-245">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2ddd8-246">**手绘：** 让工作簿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-246">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="2ddd8-247">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-247">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2ddd8-248">在[博客文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-248">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2ddd8-249">**查找要找的内容：** 搜索命令、人员、文件、照片、Web 文章等等。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-249">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="2ddd8-250">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-250">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2ddd8-251">**6 个强大的函数：** 我们添加了六个新函数来增强你的电子表格：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-251">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="2ddd8-252">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-252">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="2ddd8-253">**向左看，向右看… XLOOKUP 在此！** 使用 XLOOKUP 在表或区域中逐行查找所需内容。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-253">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="2ddd8-254">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-254">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="2ddd8-255">在[博客文章](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-255">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="2ddd8-256">**管理你的大工作簿：** 单元格、公式、图表、表格... 获取包含工作簿统计信息的工作簿的快照。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-256">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="2ddd8-257">**随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-257">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2ddd8-258">**使用\@提及** 功能引起他人的注意：在批注中使用 @提及，以在需要同事的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-258">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2ddd8-259">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-259">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="2ddd8-260">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-260">Outlook</span></span>

- <span data-ttu-id="2ddd8-261">**在屏幕上显示更多邮件：** 选择“视图”>“使用更紧密的间距”来调整邮件之间的间距。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-261">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="2ddd8-262">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-262">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="2ddd8-263">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-263">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2ddd8-264">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-264">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ddd8-265">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-265">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2ddd8-266">**让我把它画出来：** 在图片上进行涂鸦或添加绘图画布以使用墨迹表达你的想法。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-266">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="2ddd8-267">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-267">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="2ddd8-268">**获取位置建议：** 在安排约会和会议时，开始键入位置，Outlook 就会推荐会议室、地址和其他邻近位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-268">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="2ddd8-269">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-269">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="2ddd8-270">在[博客文章](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-270">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="2ddd8-271">**针对攻击的高级防护：** 通过 Office 365 高级威胁防护, 可通过电子邮件主题中的超链接、附加邮件、签名邮件、网络路径等的方式抵御攻击。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-271">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="2ddd8-272">**Outlook 中的插入链接菜单将插入包含租户管理员定义的权限的链接：** Outlook 插入链接 MRU 中的链接将插入仅对已经拥有权限的用户有效的链接。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-272">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="2ddd8-273">这通常会导致请求获得文档访问权限的用户之间发生往来电子邮件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-273">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="2ddd8-274">我们已更新了此体验，现在该链接将通过租户管理员设置的默认权限进行插入。对于 MSIT，这“可供组织编辑”，因此收到以此方式共享的链接的所有内部用户都可以访问它。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-274">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="2ddd8-275">**以不同的亮度查看邮件：** 使用“太阳”/“月亮”按钮在阅读窗格中的明暗背景之间切换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-275">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="2ddd8-276">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-276">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="2ddd8-277">**轻松发现网络钓鱼邮件：** 垃圾邮件和网络钓鱼邮件具有不同的外观，因此你可以轻松从收件箱中识别并删除它们。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-277">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="2ddd8-p123">**所有加密选项都在一个位置：** 只需转到“选项”>“加密”以选择如何保护电子邮件。[了解更多](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="2ddd8-280">**在有拼写错误的情况下进行搜索：** 即使你的拼写有误，Outlook 仍将找到你在查找的内容。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-280">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="2ddd8-281">**将 LinkedIn 网络连接到 Outlook：** 以安全的方式将 LinkedIn 帐户连接到 Microsoft 帐户，直接在“人员”卡片中查看 LinkedIn 中的信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-281">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="2ddd8-282">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-282">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="2ddd8-283">**查看搜索结果中的相关消息：** Outlook 会分析搜索词，并在搜索结果顶部显示最相关的电子邮件信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-283">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="2ddd8-284">还会在“热门搜索结果”部分看到按日期排序的所有搜索结果。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-284">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="2ddd8-285">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-285">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-286">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-286">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-p126">**你来计算，我们来设置格式：** 我们将书写数学表达式更改成标准字符。只需选择“将墨迹转换为数学公式”，再选择手写笔记即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="2ddd8-290">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-290">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2ddd8-291">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-291">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2ddd8-292">**用墨迹绘制精彩绝伦的幻灯片：** 将墨迹转换为标准形状和文本，然后从 PowerPoint 设计器获取智能幻灯片设计灵感。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-292">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="2ddd8-293">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-293">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="2ddd8-294">**手绘：** 让演示文稿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-294">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="2ddd8-295">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-295">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2ddd8-296">在[博客文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-296">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2ddd8-297">**墨迹即时重播：** 在幻灯片上使用墨迹时，可应用重播动画，在幻灯片放映期间重播墨迹的实际绘制过程。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-297">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="2ddd8-298">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-298">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="2ddd8-299">在[博客文章](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-299">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="2ddd8-300">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-300">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="2ddd8-301">**将插图另存为 SVG**：将图表、形状或其他插图另存为可缩放矢量图形，这样做可以调整其大小，而不会降低图像质量。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-301">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="2ddd8-302">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-302">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2ddd8-303">**打印讲义上的幻灯片编号：** 幻灯片编号将会自动包括在讲义上。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-303">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="2ddd8-304">打开或是关闭它们，全都取决于你。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-304">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="2ddd8-305">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-305">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="2ddd8-306">**查找并修复缺失的幻灯片标题：** 幻灯片标题可为你的推销词增色添彩，并使所有用户都可以访问你的幻灯片。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-306">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="2ddd8-307">辅助功能检查器显示标题缺失位置，以便你可以快速添加标题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-307">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="2ddd8-308">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-308">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="2ddd8-309">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-309">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2ddd8-310">在[博客文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-310">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2ddd8-311">**更多符合你心情的图标：** 我们添加了超过 300 个新图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-311">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="2ddd8-312">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-312">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ddd8-313">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-313">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2ddd8-314">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-314">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="2ddd8-315">在[博客文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-315">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2ddd8-316">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-316">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2ddd8-317">**PowerPoint 中的快速实时协作：** 在 PowerPoint 中快速展开实时协作</span><span class="sxs-lookup"><span data-stu-id="2ddd8-317">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="2ddd8-318">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-318">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2ddd8-319">**新增校对工具：** 无需在语言方面倍感压力。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-319">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="2ddd8-320">PowerPoint 现在可提供语法和写作建议。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-320">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="2ddd8-321">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-321">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="2ddd8-322">**实时字幕和对白字幕：** 演示者的文字会作为字幕自动显示在屏幕上或翻译成你所选语言的对白字幕。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-322">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="2ddd8-323">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-323">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="2ddd8-324">**全面优化你的演示文稿：** 辅助功能检查器可帮助你在排列幻灯片上的对象时考虑到屏幕阅读器。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-324">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="2ddd8-325">在[博客文章](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-325">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="2ddd8-326">**如果可以重复使用，为何还要重新创建呢？：** 通过重新使用你创建的幻灯片或其他人与你共享的幻灯片来节省时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-326">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="2ddd8-327">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-327">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="2ddd8-328">Visio</span><span class="sxs-lookup"><span data-stu-id="2ddd8-328">Visio</span></span>

- <span data-ttu-id="2ddd8-329">**在 Excel 中制作优美的 Visio 图表：** 通过将数据置于工作表上来创建流程图或组织结构图。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-329">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="2ddd8-330">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-330">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2ddd8-331">**返回到“犯罪”的场景：** 使用“犯罪场景调查模板”中的新证据、室内和户外模具，仔细地重新创建罪犯的犯罪场景。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-331">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-332">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-332">Word</span></span>

- <span data-ttu-id="2ddd8-333">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-333">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="2ddd8-334">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-334">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="2ddd8-335">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-335">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2ddd8-336">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-336">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2ddd8-337">在[博客文章](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-337">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2ddd8-338">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-338">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2ddd8-339">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-339">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2ddd8-340">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-340">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ddd8-341">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-341">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="2ddd8-342">在[博客文章](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-342">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="2ddd8-343">**精确擦除：** 从两个橡皮擦尺寸中进行选择以修复小墨迹缺陷。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-343">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="2ddd8-344">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-344">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="2ddd8-345">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-345">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2ddd8-346">在[博客文章](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-346">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2ddd8-347">**手绘：** 让文档中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-347">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="2ddd8-348">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-348">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2ddd8-349">在[博客文章](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-349">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2ddd8-350">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-350">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2ddd8-351">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-351">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2ddd8-352">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-352">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="2ddd8-353">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-353">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="2ddd8-354">**简历编辑器加入 LinkedIn 简历助手：** 简历编辑器提供了一系列专为简历量身定制的语法和样式检查，以使你的写作更加精确和专业。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-354">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="2ddd8-355">**其他人可以快速查看你所做的更改：** 共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-355">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="2ddd8-356">**修复了 3D 对象合并导致的文档损坏问题：** 修复了 3D 对象合并导致的文档损坏问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-356">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="2ddd8-357">**合著改进**：提高了在具有修订的文档中进行合著时的 Word 性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-357">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="2ddd8-358">**合著改进：** 提高了合著时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-358">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="2ddd8-359">**色彩丰富的协作：** 批注和修订由参与者进行颜色编码，以便你能够轻松看到协作者是谁。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-359">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="2ddd8-360">**协同编辑启用宏的文档：** 将 docm 文件保存在 OneDrive for Business 上，并与协作者实时进行编辑。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-360">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-361">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-361">Office Suite</span></span>

- <span data-ttu-id="2ddd8-362">**在 PowerPoint for Office 365 中将手写墨迹更改为形状、文本或数学公式：** 从自由格式的墨迹转到几条笔划中的 Office 形状、文本或数学表达式。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-362">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="2ddd8-363">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-363">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-366">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-366">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-367">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-367">Access</span></span>

- <span data-ttu-id="2ddd8-368">此更新修复了使用 ADODB 的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-368">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2ddd8-369">VB 代码中的记录器对象可能会错误地报告错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-369">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2ddd8-370">Access 模板将不会再导致数据库中的附件列出现故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-370">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2ddd8-371">在实例化模板后，你现在应该可以将附件字段添加到数据库中。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-371">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="2ddd8-372">此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-372">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="2ddd8-373">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现“查询已损坏”错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-373">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2ddd8-374">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-374">Excel</span></span>

- <span data-ttu-id="2ddd8-375">加速加载本地 OneDrive 文件夹中提供的文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-375">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="2ddd8-376">修复了 CUBEVALUE 函数有时会返回错误结果的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-376">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="2ddd8-377">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-377">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ddd8-378">在某些情况下，重新打开嵌入 Word 或 PowerPoint 的工作簿时，Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-378">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="2ddd8-379">修复了未显示上下文菜单中的批注命令的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-379">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="2ddd8-380">我们修复了数据透视图的右键单击菜单，以便启用“显示详细信息”选项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-380">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="2ddd8-381">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-381">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2ddd8-382">我们解决了在同一工作簿中单击带有书签的超链接会导致工作簿隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-382">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2ddd8-383">当另存为 CSV 文件时，在某些情况下，Excel 可能将所有列合并为一个列。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-383">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="2ddd8-384">在受保护工作表中的某个区域内使用 Range.ClearContents 的时间可能比预期的要长。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-384">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="2ddd8-385">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-385">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2ddd8-386">与功能区交互的 VBA 宏可能在 ScreenUpdating 意外设置为 True 的情况下运行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-386">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="2ddd8-387">修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-387">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2ddd8-388">在某些情况下，打开 CSV 文件所花费的时间比预期的长。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-388">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="2ddd8-389">在具有不同缩放级别的工作簿之间切换时，在某些情况下 Excel 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-389">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="2ddd8-390">修复了一个有关 VBA 的问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-390">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2ddd8-391">从按颜色筛选的列复制的数据有时无法正确粘贴。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-391">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="2ddd8-392">打开包含对许多其他工作簿（尤其是隐藏窗口）的引用的工作簿将比预期的慢。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-392">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2ddd8-393">解决了如果关闭了源代码簿，则外部链接不会在填充（向下填充、横跨填充等）时更新的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-393">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="2ddd8-394">修复了当通过 Teams 共享 Excel 窗口时，使用 Ctrl+Shift+箭头键滚动后 Excel 可能变得无响应的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-394">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2ddd8-395">含有数字签名且在 Excel 2016 中保存的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-395">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2ddd8-396">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-396">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2ddd8-397">修正了以下问题：保存到 SharePoint/OneDrive 时，自定义功能区标签的 CustomUI XML 被删除。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-397">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="2ddd8-398">使用合并单元格删除列时性能得到改善。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-398">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="2ddd8-399">修复了 "打印" 对话框中打印机列表中的打印机名称可能重复的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-399">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="2ddd8-400">修复了以下问题：在文件重新打开后，如果文件路径太长，外部链接会停止工作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-400">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2ddd8-401">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-401">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2ddd8-402">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-402">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2ddd8-403">在筛选列表中插入列所需的时间可能比预期更长。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-403">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2ddd8-404">我们解决了某些复制粘贴图表链接使用映射驱动器地址而不是通用地址的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-404">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="2ddd8-405">我们解决了以下问题：由于加载程序是按字母顺序加载的，而不是按用户指定的顺序加载，因此会出现“此工作簿目前由另一个工作簿引用，无法关闭”的错误信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-405">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="2ddd8-406">解决了在单击已打开的工作簿中的指向某个位置的超链接时，工作簿可能会隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-406">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="2ddd8-407">打开包含对许多其他工作簿（尤其是隐藏窗口）的引用的工作簿将比预期的慢。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-407">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2ddd8-408">使用 VBA 的应用程序。在某些情况下，评估无法用于用户定义的功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-408">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2ddd8-409">修复了某些用户可能遇到的嵌入和链接对象 (OLE) 问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-409">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="2ddd8-410">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-410">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ddd8-411">此更新修复了导致公式栏以不同于预期的字体显示文本的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-411">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="2ddd8-412">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-412">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ddd8-413">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-413">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2ddd8-414">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-414">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2ddd8-415">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-415">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2ddd8-416">某些本地化版本的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-416">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="2ddd8-417">解决了从模板创建图表时出现的性能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-417">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="2ddd8-418">修复了一个问题，该问题导致某些用户在将文本转换为包含单元格（具有溢出数组）的列时遇到崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-418">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="2ddd8-419">使用 Range.Value 和 Range.Value2 (VBA) 会导致公式作为动态数组输入。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-419">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="2ddd8-420">修复了以下问题：将以公式开头的@符号被视为隐式交集运算符。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-420">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="2ddd8-421">我们修复了包含多个已定义名称的公式的工作表在保存文件时导致时间延长的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-421">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="2ddd8-422">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-422">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2ddd8-423">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-423">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="2ddd8-424">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ddd8-424">OneNote</span></span>

- <span data-ttu-id="2ddd8-425">通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-425">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="2ddd8-426">在 OneNote 2016 中，通过暂时将联机笔记本中的嵌入式文件和图像的下载推迟到用户导航到相应页面时进行，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-426">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="2ddd8-427">通过暂时禁用 OneNote 2016 中的回收站，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-427">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="2ddd8-428">当用户尝试删除通常将发送到回收站中的数据时，系统会询问用户是希望保留还是永久删除数据。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-428">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="2ddd8-429">通过暂时减少 OneNote 2016 中版本历史记录页面的数量和同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-429">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="2ddd8-430">显示了一条通知，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-430">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="2ddd8-431">在 OneNote 2016 中，通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-431">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="2ddd8-432">对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-432">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="2ddd8-433">通过暂时禁用 OneNote 2016 中的应用内视频录制功能，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-433">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="2ddd8-434">本地笔记本不受此措施影响。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-434">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="2ddd8-435">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-435">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-436">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-436">Outlook</span></span>

- <span data-ttu-id="2ddd8-437">我们解决了当使用多个不同分辨率的显示器时，IME（输入法编辑器）窗口会重叠通过IME输入的底层文本的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-437">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="2ddd8-438">解决了导致用户在 Outlook 中偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-438">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2ddd8-439">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-439">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2ddd8-440">解决了导致 Web 加载项访问数字权限管理邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-440">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="2ddd8-441">解决了导致定期约会或会议在达到时区定义更改时出现错误的时间时显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-441">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="2ddd8-442">如果在 2019 年使用巴西利亚时区，则定期会议和约会将显示在 2020 年的错误时间段内。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-442">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="2ddd8-443">此更改涉及到在巴西利亚时区设置的客户端以及在该时区设置的会议和约会。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-443">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="2ddd8-444">通过此更改，Outlook 可覆盖 Outlook 使用的特定时区设置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-444">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="2ddd8-445">若要调用时区覆盖，你必须为当前用户设置注册表项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-445">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="2ddd8-446">注册表项名称必须与时区的内部名称相匹配。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-446">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="2ddd8-447">该值表示将使用时区规则的年份代替有效年份。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-447">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="2ddd8-448">例如，下面的注册表项替代值将使用 2020 年的 Brazilia 时区规则作为有效规则。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-448">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="2ddd8-449">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="2ddd8-449">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="2ddd8-450">南美洲标准时间"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="2ddd8-450">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="2ddd8-451">解决了导致用户看到会议中的位置字段意外更改的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-451">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="2ddd8-452">解决了导致会议中的“位置”字段意外更新的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-452">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="2ddd8-453">解决了导致会议位置在清除后意外添加回会议的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-453">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="2ddd8-454">解决了导致会议位置字段中的逗号变为分号的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-454">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="2ddd8-455">启用直接通过本机 Teams 客户端加入 Teams 会议。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-455">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="2ddd8-456">解决了导致 Exchange 2010 服务器上的邮箱用户在将附件添加到日历项目时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-456">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="2ddd8-457">解决了导致用户在答复数字签名邮件时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-457">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="2ddd8-458">解决了导致用户无法打开某些定期日历项目实例的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-458">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="2ddd8-459">解决了在某些情况下导致组页眉意外展开的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-459">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="2ddd8-460">解决了导致文件夹窗格宽度意外改变的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-460">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2ddd8-461">解决了 Outlook 无法启用“数据丢失保护”策略的提示问题，这些提示用户针对使用 M365 Business Plus 计划付费的用户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-461">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="2ddd8-462">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-462">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2ddd8-463">解决了在多个窗口中查看同一项目时可能会导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-463">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="2ddd8-464">解决了导致用户在 Outlook 中更新其规则时出现 "此计算机上的规则与 Microsoft Exchange 的规则不匹配" 消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-464">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="2ddd8-465">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-465">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2ddd8-466">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-466">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2ddd8-467">解决了导致用户在打开“规则”对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-467">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2ddd8-468">解决了一个问题，该问题导致在某些情况下无法使用相关选项来禁用标记项目突出显示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-468">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2ddd8-469">解决了在关闭辅助功能检查器窗格后按 S 键时导致用户看到邮件意外发送的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-469">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="2ddd8-470">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-470">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2ddd8-471">解决了导致用户在取消帐户设置时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-471">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="2ddd8-472">解决了导致 Outlook 在同步滑块设置为较小的设置时出现意外同步所有邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-472">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="2ddd8-473">解决了具有黑色主题的用户在“发件人”下拉列表中看到白色背景上显示白色文本的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-473">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="2ddd8-474">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-474">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2ddd8-475">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-475">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ddd8-476">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-476">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ddd8-477">解决了导致第三方应用程序无法发送电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-477">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="2ddd8-478">解决了导致类别偶尔从电子邮件中消失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-478">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="2ddd8-479">解决了导致服务器操作系统上的 Outlook 用户看到错误“防病毒状态：无效”的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-479">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="2ddd8-480">此版本的 Windows 支持防病毒检测，但没有发现防病毒，尽管已正确配置防病毒。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-480">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="2ddd8-481">解决了导致代理人在不同计算机上看到共享邮箱的不同文件夹层次结构的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-481">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="2ddd8-482">解决了导致代理在经理的日历上编辑现有日历约会时收到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-482">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="2ddd8-483">解决了导致浏览器仿真设置错误的用户无法完成 Gmail 身份验证提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-483">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="2ddd8-484">我们解决了以下问题：如果未选中下载共享文件夹，则共享日历会议 "答复选项" 中缺少 "允许转发" 选项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-484">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="2ddd8-485">解决了导致用户在某次 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-485">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="2ddd8-486">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-486">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2ddd8-487">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-487">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2ddd8-488">修复了以下问题：附件工具中缺少“保存到云”按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-488">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2ddd8-489">此更改恢复了在邮件标题中查看多行主题的功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-489">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="2ddd8-490">解决了导致用户在两个加载项向同一功能区组添加按钮时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-490">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="2ddd8-491">解决了在将租户默认权限配置为 "任何人" 的情况下，导致无法将链接添加到具有正确租户默认权限的电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-491">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="2ddd8-492">解决了导致用户无法将电子邮件发送到个人通讯组列表的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-492">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="2ddd8-493">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-493">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2ddd8-494">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-494">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2ddd8-495">我们修复了可能会阻止文件保存到 WebDAV 位置的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-495">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="2ddd8-496">解决了在安全性对话框中选择“保存”选项时，导致用户无法将其租户外部的 OneDrive 附件保存到本地计算机的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-496">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2ddd8-497">我们解决了在编辑主题后导致 NDR 邮件的正文从 Unicode 更改为 ASCII 的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-497">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="2ddd8-498">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-498">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2ddd8-499">解决了在某些情况下导致用户看到电子邮件发送地址与显示的 SMTP 地址不匹配的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-499">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="2ddd8-500">解决了导致搜索框在高 dpi 模式下未正确对齐的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-500">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="2ddd8-501">解决了导致用户在检索云设置时在 Outlook 中遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-501">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="2ddd8-502">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-502">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2ddd8-503">解决了导致用户在 Outlook 中偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-503">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2ddd8-504">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-504">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2ddd8-505">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-505">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2ddd8-506">解决了导致用户在 Outlook 中偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-506">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-507">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-508">解决了在旧版 PPT 批注中使用上下文菜单时可能导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-508">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="2ddd8-509">改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-509">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2ddd8-510">修复了为打开注释已改进的文件副本的用户中继正确消息传递的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-510">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="2ddd8-511">Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-511">Project</span></span>

- <span data-ttu-id="2ddd8-512">修复了有时无法正确计算摘要任务日期的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-512">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2ddd8-513">修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-513">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2ddd8-514">解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-514">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="2ddd8-515">解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-515">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2ddd8-516">发现了用户在打开只读项目时可能会收到几则消息的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-516">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="2ddd8-517">修复了以下问题：固定持续时间类型的 100％ 任务可能会错误地将其完成百分比计算为小于 100％ 完成。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-517">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-518">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-518">Word</span></span>

- <span data-ttu-id="2ddd8-519">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-519">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2ddd8-520">修复了以下问题：在使用“快速打印”打印后尝试进行编辑时，文档中的字词对齐方式会被打乱。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-520">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="2ddd8-521">我们修复了表格中文本适应的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-521">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="2ddd8-522">我们修复了插入水平线不短且居中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-522">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="2ddd8-523">构建基块管理器可能显示无效的警报：“你已更改样式、构建基块”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-523">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="2ddd8-524">解决了启用 FileBlick\Word2007Files 策略时出现的协调问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-524">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="2ddd8-525">我们修复了添加已重命名的 lookup 字段时 Word QuickPart 无法正常工作的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-525">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="2ddd8-526">我们修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-526">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2ddd8-527">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-527">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2ddd8-528">此更新修复了 Microsoft Word 中的一个问题，即如果某个敏感度标签策略应用了页眉、页脚或水印，则在应用该标签时插入的长度超过 255 个字符的文本随后将无法通过更改或删除该标签来标识和删除。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-528">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-529">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-529">Office Suite</span></span>

- <span data-ttu-id="2ddd8-530">修复了一个问题，即用户在大型 PowerPoint 文件上进行共同创作时遇到过多的网络和 CPU 使用情况。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-530">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="2ddd8-531">这是一个修复程序，用于解决在客户端缓存文件时，Project 应用不应阻止网络的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-531">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="2ddd8-532">我们通过将后台的频道名称更新为 2020 年 1 月的分支中的新频道名称来解决此问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-532">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="2ddd8-533">我们已修复此问题，接下来，如果设备是由策略管理的，则不会调用 DMS Audience API。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-533">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="2ddd8-534">解决了在单个事务中添加和删除应用时删除不完整的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-534">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="2ddd8-535">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-535">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ddd8-536">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-536">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2ddd8-537">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-537">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ddd8-538">我们对新的 AppV51 进行了备份，以修复之前 AppV51 中的回归问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-538">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2ddd8-539">我们已经解决了内部操作在失败时引发异常而不是进行记录并继续的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-539">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="2ddd8-540">受影响的用户将不再被阻止接收更新。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-540">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="2ddd8-541">我们的团队增加了客户端支持，可在半年度企业预览版中报告 Office CDN 域上的遥测。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-541">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="2ddd8-542">此更改解决了利用 Intel 集成 GPU 的图形适配器所报告的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-542">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="2ddd8-543">此更改可确保草绘轮廓在功能区中正常工作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-543">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="2ddd8-544">修复了从具有某些特定代理配置的本地位置打开文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-544">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="2ddd8-545">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-545">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2ddd8-546">修复了可在 Office 切换会话期间防止崩溃并提高用户体验可靠性的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-546">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="2ddd8-547">此 bug 将更新增强型配置服务 (ECS) url 终结点。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-547">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="2ddd8-548">调用此较新的终结点可以提高从 ECS 获取数据的成功率。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-548">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="2ddd8-549">此更新修复了 Microsoft Outlook 在用户查看或撰写邮件时不显示当前敏感度标签的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-549">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="2ddd8-550">修复了从同一 SharePoint 库在 Word/Excel/PowerPoint 中打开多个文件时，只能打开第一个文件进行策略符合性扫描的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-550">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="2ddd8-551">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-551">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2ddd8-552">当注册表键HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth被设置为零并且另外一个外接程序正在被激活时，windows中的office主机关闭。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-552">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2ddd8-553">此更改可修复此问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-553">This change would fix this issue.</span></span>

- <span data-ttu-id="2ddd8-554">解决了可能无法正确启动 Access 和 Publisher（具体取决于安装的语言）的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-554">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (请勿移除错误详细信息内容开头)





[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-july-14"></a><span data-ttu-id="2ddd8-557">版本1908：7月14日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-557">Version 1908: July 14</span></span>
<span data-ttu-id="2ddd8-558">*版本 1908（内部版本 11929.20904）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-558">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="2ddd8-559">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-559">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-561">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-561">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-562">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-562">Access</span></span>

- <span data-ttu-id="2ddd8-563">该更新修复了诸如“总和”等聚合可能将结果截断为整数值的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-563">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2ddd8-564">该更新修复了包含对远程表（例如 SQL Server 表）的引用的联合查询可能导致 Access 关闭并重新启动的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-564">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2ddd8-565">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现“查询已损坏”错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-565">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2ddd8-566">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-566">Excel</span></span>

- <span data-ttu-id="2ddd8-567">荷兰语文档标题快捷键提示已更改为 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-567">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2ddd8-568">修复了 Excel 中的问题，其中分配给形状或表单控件的宏可能显示不正确的错误消息，或者可能在不正确的目标区域中工作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-568">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2ddd8-569">解决了一个“查找和替换”问题，即在找到第一个项目后它改变了对话框中焦点的位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-569">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2ddd8-570">修复了在更改数据透视表的排序方式并在与其他用户进行共同创作会话期间刷新它时可能触发崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-570">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2ddd8-571">我们修复了当 OLAP 数据透视表的筛选器设置为已从多维数据集中删除的值时的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-571">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2ddd8-572">此更新修复了以下问题：当使用 VBA 向图表的页眉/页脚添加图像时，将会导致出现错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-572">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2ddd8-573">我们修复了在更改系列集合时可能导致散点图无法正确呈现的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-573">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="2ddd8-574">修复了使用图表模板插入图表时预览中所用颜色的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-574">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2ddd8-575">解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-575">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2ddd8-576">已修复了 Excel 中的合并冲突问题，该问题会导致系统提示用户重新打开工作簿以使更改生效。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-576">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2ddd8-577">解决了导致激活最小化窗口的宏运行时错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-577">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2ddd8-578">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-578">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ddd8-579">解决了在与其他人共同创作时导致表旁边的剪切和粘贴操作失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-579">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2ddd8-580">解决了在使用运行的宏更改自定义属性时导致共同创作中断的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-580">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2ddd8-581">发生问题时，将无法从加载项打开的 WPF （Windows Presentation Foundation）窗体的组合框中选择项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-581">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2ddd8-582">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-582">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2ddd8-583">修复了在打印预览中或打印时分组框控件的边框不可见的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-583">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2ddd8-584">修复了当工作簿中存在外部链接时某些用户可能遇到多个弹出窗口的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-584">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="2ddd8-585">修复了用户在使用 VBA 宏清除某区域中的内容时可能遇到的性能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-585">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2ddd8-586">修复了一个有关 VBA 的问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-586">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2ddd8-587">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-587">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2ddd8-588">含有数字签名且在 Excel 2016 中保存的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-588">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2ddd8-589">修复了删除包含合并单元格的列时导致性能降低的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-589">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2ddd8-590">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-590">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2ddd8-591">将按颜色筛选的数据复制到具有不同宽度的列时，不会粘贴这些值。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-591">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="2ddd8-592">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-592">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2ddd8-593">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-593">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2ddd8-594">我们解决了在同一工作簿中单击带有书签的超链接会导致工作簿隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-594">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2ddd8-595">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-595">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2ddd8-596">某些区域设置的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-596">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="2ddd8-597">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-597">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2ddd8-598">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-598">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ddd8-599">修复了以下问题：在保存包含图表的工作簿时，图表标题中的图像文件大小增加。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-599">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="2ddd8-600">异步用户定义函数的性能问题，该问题导致它们同步运行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-600">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2ddd8-601">显著提高了删除包含合并单元格的列时的性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-601">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2ddd8-602">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-602">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2ddd8-603">解决了 Lookup 函数可能返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-603">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2ddd8-604">修复了以下问题：在使所选区域与交叉引用的工作簿保持同步时，导致交叉引用工作簿中的 DBCS 字符出现损坏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-604">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2ddd8-605">解决了使用自动调整功能调整行高时复选框控件缩小的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-605">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="2ddd8-606">当文件具有大量条件格式时，单击“字体颜色”按钮时会出现性能较低的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-606">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2ddd8-607">我们修复了打印预览中的打印区域不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-607">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2ddd8-608">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-608">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2ddd8-609">我们显著提高了按颜色筛选的性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-609">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2ddd8-610">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-610">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2ddd8-611">在加载项管理器中浏览时允许显示超过 16 个加载项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-611">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2ddd8-612">解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-612">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2ddd8-613">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-613">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2ddd8-614">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-614">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-615">此更新修复了 Office 文档可能无法上传到 OneDrive for business，同时显示“上传失败”消息的错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-615">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2ddd8-616">修复了在 Excel 创意功能中发现一个的问题，即通过单击 Win32 客户端中的“创意”按钮加载加载项时出错。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-616">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="2ddd8-617">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ddd8-617">OneNote</span></span>

- <span data-ttu-id="2ddd8-618">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-618">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-619">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-619">Outlook</span></span>

- <span data-ttu-id="2ddd8-620">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-620">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-621">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得与其 Outlook 配置文件关联的错误帐户的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-621">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2ddd8-622">解决了导致 Web 加载项在不应该访问“数字版权管理”消息时访问它们的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-622">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2ddd8-623">解决了导致简单悬停 URL 无法显示某些安全链接的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-623">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2ddd8-624">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-624">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2ddd8-625">解决了导致部分 POP3 用户看到无论设置如何，其所有电子邮件均采用纯文本格式的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-625">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2ddd8-626">此修补程序将还原 HTML 格式邮件的视图。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-626">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2ddd8-627">解决了在将用户主日历中的项复制到组日历时出现导致用户遇到权限错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-627">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2ddd8-628">解决了导致用户无法通过屏幕阅读器访问位置建议的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-628">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2ddd8-629">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-629">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2ddd8-630">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-630">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2ddd8-631">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-631">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2ddd8-632">解决了导致用户在打开“规则”对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-632">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2ddd8-633">解决了导致用户在 Outlook 中与特定安全链接交互时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-633">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2ddd8-634">解决了导致经理不清楚代理人是否已响应指定的会议请求的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-634">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2ddd8-635">解决了导致用户在处理某些自动发现响应时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-635">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ddd8-636">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-636">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ddd8-637">该更改能够让管理员能够启用策略以便在自动发现身份验证提示中首选提供的帐户电子邮件而不是 UPN。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-637">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2ddd8-638">默认情况下，自动发现优先于帐户 UPN（如果可用）。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-638">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2ddd8-639">解决导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-639">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2ddd8-640">解决了导致 Outlook 用户在某些情况下“需要密码”的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-640">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2ddd8-641">解决了导致用户在处理冲突消息时遇到同步失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-641">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2ddd8-642">解决了导致用户在应用最新的 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-642">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2ddd8-643">解决了导致用户在启动 Outlook 时在“正在加载个人资料”屏幕上遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-643">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2ddd8-644">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-644">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2ddd8-645">修复了以下问题：附件工具中缺少“保存到云”按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-645">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2ddd8-646">默认情况下，保留策略标签会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-646">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2ddd8-647">提供了一个注册表项，允许管理员指定只应显示策略名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-647">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2ddd8-648">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = 默认值 1 = 将仅显示保留策略文本的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-648">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="2ddd8-649">解决了导致用户在关闭 Outlook 时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-649">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2ddd8-650">解决了导致客户在某些场合中看到空会议室列表的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-650">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="2ddd8-651">解决了导致用户在更改视图时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-651">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="2ddd8-652">解决了一个问题，该问题导致用户在将共享日历文件夹同步到 OST 时遇到问题，这导致他们与这些文件夹进行交互时出现权限错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-652">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="2ddd8-653">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到系统崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-653">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2ddd8-654">这是[以前的版本中记录的单个 KB](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-654">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="2ddd8-655">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-655">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2ddd8-656">解决了在使用备用发件人时导致无法显示策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-656">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2ddd8-657">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-657">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2ddd8-658">解决了非英语用户邮件中的主题行非常小的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-658">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2ddd8-659">解决了导致用户尝试“从错过的对话”消息创建规则时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-659">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2ddd8-660">解决了导致某些用户在添加辅助 Exchange 帐户时会看到创建重复的特殊文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-660">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2ddd8-661">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-661">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2ddd8-662">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-662">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2ddd8-663">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-663">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2ddd8-664">解决导致当前文件夹搜索间歇性失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-664">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2ddd8-665">解决了导致某些用户在尝试检索 Outlook 的云设置时遇到身份验证错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-665">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2ddd8-666">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-666">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2ddd8-667">解决了导致用户在处理某些自动发现响应时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-667">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ddd8-668">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-668">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-669">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-669">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-670">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-670">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-671">该更改还原 PowerPoint 视频控件易于访问的名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-671">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2ddd8-672">我们修复了可能阻止某些动画启动的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-672">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="2ddd8-673">我们修复了将一个幻灯片从一个演示文稿复制到另一个演示文稿时，可能创建重复母版的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-673">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="2ddd8-674">改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-674">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2ddd8-675">修复了荧光笔问题：带有黑色荧光笔颜色的白色文本在打印后显示为灰度中的黑色。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-675">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="2ddd8-676">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-676">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="2ddd8-677">修复了导致协作用户之间的效率降低的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-677">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2ddd8-678">可靠性修复：修复了第三方加载项可能导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-678">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2ddd8-679">修复了以下问题：当逐步打开文件时，如果其中一张幻灯片包含多个嵌入式媒体流，则可能会出现问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-679">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2ddd8-680">我们修复了 Shape.Paste 方法的问题：当用户使用 Shape.Paste 方法复制和粘贴形状时，它会将所选内容更改为粘贴的形状。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-680">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="2ddd8-681">我们修复了第一次启动 PowerPoint 时可能不会显示不受信任的加载项的安全警告消息栏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-681">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="2ddd8-682">修复了某些加载项会在图表中的形状周围引发意外错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-682">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2ddd8-683">防止 PowerPoint 用户在尝试联机演示时遇到错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-683">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="2ddd8-684">Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-684">Project</span></span>

- <span data-ttu-id="2ddd8-685">修复了 Windows 7 上的用户能够从 Project Web App 和 SharePoint 网站打开项目的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-685">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2ddd8-686">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-686">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2ddd8-687">“全部调配”命令不能正确解决资源的过度分配。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-687">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2ddd8-688">如果你的任务分配为零工作，该任务可能无法标记为已完成，并且始终显示为 99%。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-688">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="2ddd8-689">修复了以下问题：由于基准日历发生更改时未更新资源日历，时间表与项目计划之间的实际工时可能不同。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-689">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="2ddd8-690">Skype</span><span class="sxs-lookup"><span data-stu-id="2ddd8-690">Skype</span></span>

- <span data-ttu-id="2ddd8-691">修复了一个对话正在进行时，选项卡式对话标题姓名的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-691">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="2ddd8-692">Visio</span><span class="sxs-lookup"><span data-stu-id="2ddd8-692">Visio</span></span>

- <span data-ttu-id="2ddd8-693">从 Visio 导出为 SVG 的操作无法用于各种形状。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-693">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-694">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-694">Word</span></span>

- <span data-ttu-id="2ddd8-695">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-695">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-696">我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-696">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="2ddd8-697">修复了使文本适应表格的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-697">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="2ddd8-698">我们修复了跟踪更改有时会陷入无限循环的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-698">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2ddd8-699">我们修复了以下问题：在某些情况下，保存现有文件始终会导致显示“另存为”对话框，而该文件从不实际保存。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-699">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="2ddd8-700">我们修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-700">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2ddd8-701">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-701">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2ddd8-702">修复了应用可能会在关闭时挂起的各种问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-702">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2ddd8-703">还修复了某些加载项相关的崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-703">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-704">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-704">Office Suite</span></span>

- <span data-ttu-id="2ddd8-705">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-705">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2ddd8-706">修复了一个问题，该问题导致用户在尝试共享存储在 SharePoint 2016 上的文件时收到消息“抱歉，无法我们共享此内容”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-706">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2ddd8-707">修复了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-707">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2ddd8-708">此修复可解决用户打开文件时可能遇到的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-708">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2ddd8-709">在某些情况下，同步引擎支持的 sharepoint 文件可能显示“已保存”，但并未真正保存任何更改，导致数据丢失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-709">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2ddd8-710">解决了用户可能无法保存 Word、Excel 和 PowerPoint 文档的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-710">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2ddd8-711">此问题会影响创建新文件并在单击“保存”图标或按 Ctrl + S 后显示“另存为对话框”选项的用户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-711">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2ddd8-712">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-712">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="2ddd8-713">修复了在 PowerPoint 中的竖排文本框中，半角片假名字符未正确旋转的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-713">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="2ddd8-714">修复了 Win7 中的性能问题，它导致所有应用中功能区内的“插入形状”库大约需要 4 秒钟才会显示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-714">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2ddd8-715">修复了在后台的信息放置面板中未显示可访问性信息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-715">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2ddd8-716">改进了有关注册表完整性的 Office 更新进程的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-716">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2ddd8-717">我们已将 2019 年 1 月和 7 月分支的频道名称更新为新频道名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-717">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2ddd8-718">更正了按流量计费的网络上可能意外阻止更新的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-718">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2ddd8-719">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-719">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ddd8-720">即在某些情况下，Office 快捷方式可能会在更新后消失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-720">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2ddd8-721">此更新改进了发布 Office 快捷方式的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-721">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2ddd8-722">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-722">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2ddd8-723">解决了以下问题：在某些情况下，如果不是管理员，并且系统帐户没有网络连接，则不会应用更新。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-723">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2ddd8-724">修复了 Office 更新消息以与预期不同的语言显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-724">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2ddd8-725">今后，Office 更新消息将正确匹配 Windows 显示语言。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-725">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2ddd8-726">通过恢复以前可能已中断的下载，增强了下载 Office 更新时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-726">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2ddd8-727">解决了与第三方插件中的“文本框/形状自动调整”属性相关的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-727">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2ddd8-728">此更改解决了打开损坏的文件后正确呈现图像的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-728">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="2ddd8-729">此更改解决了某些包含标记的散点图呈现缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-729">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="2ddd8-730">我们修复了大型树视图可能会导致崩溃的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-730">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="2ddd8-731">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-731">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2ddd8-732">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-732">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2ddd8-733">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-733">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-july-14"></a><span data-ttu-id="2ddd8-735">版本 1902：7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-735">Version 1902: July 14</span></span>
<span data-ttu-id="2ddd8-736">*版本 1902（内部版本 11328.20624）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-736">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="2ddd8-737">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-737">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="2ddd8-738">版本 1908：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-738">Version 1908: June 09</span></span>
<span data-ttu-id="2ddd8-739">*版本 1908（内部版本 11929.20838）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-739">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="2ddd8-740">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-740">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-742">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-742">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-743">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-743">Excel</span></span>

- <span data-ttu-id="2ddd8-744">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-744">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2ddd8-745">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-745">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2ddd8-746">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-746">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-747">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-747">Outlook</span></span>

- <span data-ttu-id="2ddd8-748">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-748">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-749">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-749">Office Suite</span></span>

- <span data-ttu-id="2ddd8-750">我们已将 2019 年 1 月和 7 月分支的频道名称更新为新频道名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-750">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-june-09"></a><span data-ttu-id="2ddd8-752">版本 1902：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-752">Version 1902: June 09</span></span>
<span data-ttu-id="2ddd8-753">*版本 1902（内部版本 11328.20602）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-753">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="2ddd8-754">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-754">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-756">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-756">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2ddd8-757">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-757">Office Suite</span></span>

- <span data-ttu-id="2ddd8-758">我们已将 2019 年 1 月和 7 月分支的频道名称更新为新频道名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-758">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2ddd8-759">我们从中断 C2R 构建的基线文件中删除了过时的引用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-759">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-may-12"></a><span data-ttu-id="2ddd8-761">版本 1908：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-761">Version 1908: May 12</span></span>
<span data-ttu-id="2ddd8-762">*版本 1908（内部版本 11929.20776）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-762">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="2ddd8-763">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-763">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-765">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-765">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-766">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-766">Excel</span></span>

- <span data-ttu-id="2ddd8-767">将按颜色筛选的数据复制到具有不同宽度的列时，不会粘贴这些值。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-767">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-768">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-768">Outlook</span></span>

- <span data-ttu-id="2ddd8-769">解决了导致用户在应用最新的 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-769">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-770">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-770">Word</span></span>

- <span data-ttu-id="2ddd8-771">修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-771">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2ddd8-772">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-772">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-may-12"></a><span data-ttu-id="2ddd8-774">版本 1902：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-774">Version 1902: May 12</span></span>
<span data-ttu-id="2ddd8-775">*版本 1902（内部版本 11328.20586）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-775">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="2ddd8-776">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-776">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-778">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-778">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ddd8-779">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-779">Outlook</span></span>

- <span data-ttu-id="2ddd8-780">解决了导致用户在应用最新的 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-780">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2ddd8-781">默认情况下，保留策略标签会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-781">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2ddd8-782">提供了一个注册表项，允许管理员指定只应显示策略名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-782">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2ddd8-783">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-783">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="2ddd8-784">0 = 默认值。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-784">0 = Default.</span></span>  <span data-ttu-id="2ddd8-785">1 = 仅显示保留策略文本的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-785">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-may-04"></a><span data-ttu-id="2ddd8-787">版本 1908：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-787">Version 1908: May 04</span></span>
<span data-ttu-id="2ddd8-788">*版本 1908（内部版本 11929.20752）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-788">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="2ddd8-789">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-789">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-790">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-790">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ddd8-791">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-791">Outlook</span></span>

- <span data-ttu-id="2ddd8-792">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-792">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2ddd8-793">解决了导致附件工具中缺少“保存到云”按钮的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-793">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2ddd8-794">默认情况下，保留策略标签会在括号中显示保留时间段。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-794">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2ddd8-795">提供了一个注册表项，允许管理员指定只应显示策略名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-795">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2ddd8-796">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-796">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="2ddd8-797">0 = 默认值 1 = 仅显示保留策略文本的 PolicyName。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-797">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-798">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-798">Office Suite</span></span>

- <span data-ttu-id="2ddd8-799">修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-799">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="2ddd8-800">版本 1902：5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-800">Version 1902: May 04</span></span>
<span data-ttu-id="2ddd8-801">*版本 1902（生成号 11328.20572）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-801">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-802">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-802">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2ddd8-803">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-803">Office Suite</span></span>

- <span data-ttu-id="2ddd8-804">修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-804">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="2ddd8-805">版本 1908：4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-805">Version 1908: April 26</span></span>
<span data-ttu-id="2ddd8-806">*版本1908（内部版本 11929.20736）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-806">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="2ddd8-807">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-807">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-808">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-808">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-809">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-809">Excel</span></span>

- <span data-ttu-id="2ddd8-810">修复了用户在使用 VBA 宏清除某区域中的内容时可能遇到的性能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-810">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2ddd8-811">修复了 VBA 中的一个问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-811">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2ddd8-812">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-812">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2ddd8-813">在 Excel 2016 中保存并且含有数字签名的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-813">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="2ddd8-814">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ddd8-814">OneNote</span></span>

- <span data-ttu-id="2ddd8-815">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-815">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="2ddd8-816">版本 1908：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-816">Version 1908: April 14</span></span>
<span data-ttu-id="2ddd8-817">*版本 1908 （内部版本 11929.20708）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-817">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="2ddd8-818">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-818">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-820">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-820">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-821">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-821">Excel</span></span>

- <span data-ttu-id="2ddd8-822">修复了删除包含合并单元格的列时导致性能降低的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-822">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2ddd8-823">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-823">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="2ddd8-824">Skype</span><span class="sxs-lookup"><span data-stu-id="2ddd8-824">Skype</span></span>

- <span data-ttu-id="2ddd8-825">修复了一个对话正在进行时，选项卡式对话标题姓名的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-825">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-826">Outlook</span></span>

- <span data-ttu-id="2ddd8-827">解决了导致用户在关闭 Outlook 时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-827">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2ddd8-828">解决了导致客户在某些场合中看到空会议室列表的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-828">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-829">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-829">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-830">修复了荧光笔问题：带有黑色荧光笔颜色的白色文本在打印后显示为灰度中的黑色。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-830">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-831">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-831">Word</span></span>

- <span data-ttu-id="2ddd8-832">修复了使文本适应表格的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-832">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="2ddd8-833">版本 1902：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-833">Version 1902: April 14</span></span>
<span data-ttu-id="2ddd8-834">*版本 1902 （内部版本 11328.20564）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-834">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="2ddd8-835">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-835">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-march-10"></a><span data-ttu-id="2ddd8-837">版本 1908：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-837">Version 1908: March 10</span></span>
<span data-ttu-id="2ddd8-838">*版本 1908（内部版本 11929.20648）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-838">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="2ddd8-839">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-839">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-841">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-841">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-842">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-842">Excel</span></span>

- <span data-ttu-id="2ddd8-843">修复了当工作簿中存在外部链接时某些用户可能遇到多个弹出窗口的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-843">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="2ddd8-844">某些区域设置的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-844">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="2ddd8-845">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-845">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2ddd8-846">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-846">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-847">我们修复了 Shape.Paste 方法的问题：当用户使用 Shape.Paste 方法复制和粘贴形状时，它会将所选内容更改为粘贴的形状。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-847">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="2ddd8-848">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-848">Word</span></span>

- <span data-ttu-id="2ddd8-849">我们修复了以下问题：在某些情况下，保存现有文件始终会导致显示“另存为”对话框，而该文件从不实际保存。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-849">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2ddd8-850">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-850">Office Suite</span></span>

- <span data-ttu-id="2ddd8-851">此更改解决了某些包含标记的散点图呈现缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-851">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="2ddd8-852">版本 1902：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-852">Version 1902: March 10</span></span>
<span data-ttu-id="2ddd8-853">*版本 1902（内部版本 11328.20554）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-853">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="2ddd8-854">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-854">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-february-11"></a><span data-ttu-id="2ddd8-856">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-856">Version 1908: February 11</span></span>
<span data-ttu-id="2ddd8-857">*版本 1908（内部版本 11929.20606）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-857">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="2ddd8-858">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-858">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-860">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-860">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-861">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-861">Excel</span></span>

- <span data-ttu-id="2ddd8-862">此更新修复了以下问题：当使用 VBA 向图表的页眉/页脚添加图像时，将会导致出现错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-862">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2ddd8-863">修复了在打印预览中或打印时分组框控件的边框不可见的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-863">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2ddd8-864">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-864">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ddd8-865">修复了以下问题：在保存包含图表的工作簿时，图表标题中的图像文件大小增加。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-865">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="2ddd8-866">修复了以下问题：在使所选区域与交叉引用的工作簿保持同步时，导致交叉引用工作簿中的 DBCS 字符出现损坏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-866">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2ddd8-867">解决了使用自动调整功能调整行高时复选框控件缩小的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-867">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="2ddd8-868">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-868">Outlook</span></span>

- <span data-ttu-id="2ddd8-869">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-869">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2ddd8-870">解决了导致用户在处理冲突消息时遇到同步失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-870">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2ddd8-871">解决了导致用户在启动 Outlook 时在“正在加载个人资料”屏幕上遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-871">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2ddd8-872">解决了导致用户在更改视图时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-872">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="2ddd8-873">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-873">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2ddd8-874">[此处](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是单个 KB，包含针对先前版本记录的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-874">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="2ddd8-875">解决了一个问题，该问题导致用户在将共享日历文件夹同步到 OST 时遇到问题，这导致他们与这些文件夹进行交互时出现权限错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-875">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2ddd8-876">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-876">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-877">改进了复制粘贴方案，即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-877">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="2ddd8-878">修复了导致协作用户之间的效率降低的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-878">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2ddd8-879">修复了以下问题：当逐步打开文件时，如果其中一张幻灯片包含多个嵌入式媒体流，则可能会出现问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-879">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2ddd8-880">我们修复了以下问题：首次启动 PowerPoint 时，不受信任的加载项可能不会显示安全警告消息栏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-880">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2ddd8-881">Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-881">Project</span></span>

- <span data-ttu-id="2ddd8-882">修复了以下问题：由于基准日历发生更改时未更新资源日历，时间表与项目计划之间的实际工时可能不同。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-882">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-883">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-883">Word</span></span>

- <span data-ttu-id="2ddd8-884">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-884">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-885">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-885">Office Suite</span></span>

- <span data-ttu-id="2ddd8-886">此更改解决了打开损坏的文件后正确渲染图像的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-886">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-february-11"></a><span data-ttu-id="2ddd8-888">版本 1902：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-888">Version 1902: February 11</span></span>
<span data-ttu-id="2ddd8-889">*版本 1902（内部版本 11328.20526）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-889">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="2ddd8-890">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-890">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-892">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-892">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ddd8-893">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-893">Outlook</span></span>

- <span data-ttu-id="2ddd8-894">解决了用户在发送加密电子邮件时遇到“不支持加密算法“错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-894">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="2ddd8-895">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-895">Word</span></span>

- <span data-ttu-id="2ddd8-896">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-896">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

[//]: # (请勿移除错误详细信息内容开头)

## <a name="version-1808-february-11"></a><span data-ttu-id="2ddd8-899">版本 1808：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-899">Version 1808: February 11</span></span>
<span data-ttu-id="2ddd8-900">*版本 1808（内部版本 10730.20438）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-900">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="2ddd8-901">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-901">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-january-14"></a><span data-ttu-id="2ddd8-903">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-903">Version 1908: January 14</span></span>
<span data-ttu-id="2ddd8-904">*版本 1908（内部版本 11929.20562）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-904">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="2ddd8-905">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-905">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="2ddd8-907">功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-907">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-908">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-908">Access</span></span>

- <span data-ttu-id="2ddd8-909">**密切关注数据库对象：** 可以清楚地看到活动选项卡，轻松拖动选项卡以重新排列它们，并且只需单击一下即可关闭数据库对象。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-909">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="2ddd8-910">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-910">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ddd8-911">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-911">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ddd8-912">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-912">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ddd8-913">**缩放更多空间：** 让缩放框变大，更改字体，缩放功能会记住一切。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-913">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="2ddd8-914">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-914">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="2ddd8-915">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-915">Excel</span></span>

- <span data-ttu-id="2ddd8-916">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-916">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ddd8-917">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-917">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ddd8-918">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-918">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ddd8-919">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-919">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2ddd8-920">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-920">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2ddd8-921">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-921">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2ddd8-922">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-922">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ddd8-923">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-923">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2ddd8-924">**见证工作表生动起来的过程：** 插入动态 3D 图形，观看心跳、行星轨道和霸王龙在整个工作簿中四处跳动。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-924">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="2ddd8-925">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-925">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="2ddd8-p175">**深入发掘数据：** 全新的“想法”按钮可查找数据中的模式并使用这些模式创建智能、个性化的建议。[了解详细信息](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="2ddd8-928">**协作更简单：** 共同创作改进意味着使用条件格式、单元格样式等时，所做的更改将与协作者无缝合并。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-928">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="2ddd8-929">**在类似列上连接表：** 在比较用于合并表的列时，获取和转换 (Power Query) 现在具有近似文本匹配逻辑（也称为模糊匹配）。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-929">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="2ddd8-930">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-930">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="2ddd8-931">**使用 Power Query 增强功能快速编码：** 使用自动完成和语法着色快速完成代码编写。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-931">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="2ddd8-932">也可以轻松发现函数、列和参数。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-932">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="2ddd8-933">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-933">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ddd8-934">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-934">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ddd8-935">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-935">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="2ddd8-936">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-936">Outlook</span></span>

- <span data-ttu-id="2ddd8-937">**我们已经为你更新了 Outlook 用户体验：** 简化的体验，以前可供预览，现即将推出，旨在帮助你关注最重要的内容。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-937">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="2ddd8-938">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-938">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="2ddd8-939">**还可自定义的简化功能区：** 最常用的按钮排成一行，带给你简化体验。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-939">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="2ddd8-940">可在经典视图和简化视图之间轻松切换，还可固定/取消固定命令。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-940">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="2ddd8-941">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-941">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="2ddd8-942">**移动邮件时继续工作：** Outlook 现在在后台移动邮件，因此你可以在文件夹之间移动大量邮件时继续工作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-942">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="2ddd8-943">**在连续召开的会议之间提供时间：** 默认将会议设置为提前 5-10 分钟结束，让与会者有时间喘口气或来往于不同地点。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-943">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="2ddd8-944">**挑选你喜欢的操作：** 不要使用“标志”和“删除”？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-944">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="2ddd8-945">“存档”或“标记为已读”呢？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-945">How about Archive or Mark as Read?</span></span> <span data-ttu-id="2ddd8-946">使用你最常用的命令自定义快速操作菜单。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-946">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="2ddd8-p182">**清晰呈现思路：** 当文本或静态图像不起作用时，请使用动态 GIF 来发表你的观点。[了解详细信息](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="2ddd8-949">**添加帐户的更快捷方式：** 由于帐户设置改进，现在可以更轻松地将使用双重身份验证的 Outlook.com 和 Gmail 帐户添加到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-949">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="2ddd8-950">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-950">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="2ddd8-951">**告别同步限制：** Outlook 改进意味着文件夹限制已取消，因此请继续操作并同步共享邮箱。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-951">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="2ddd8-952">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-952">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ddd8-953">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-953">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ddd8-954">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-954">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-955">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-955">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-956">**切换效果更好：** 对形状命名，以更好地掌控其平滑效果。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-956">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="2ddd8-957">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-957">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="2ddd8-958">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-958">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ddd8-959">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-959">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2ddd8-960">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-960">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2ddd8-961">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-961">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2ddd8-962">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-962">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2ddd8-963">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-963">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ddd8-964">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-964">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ddd8-965">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-965">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ddd8-966">**联机视频获得新的存储位置：** 将视频保存到 Microsoft Stream，以便组织中的任何人都可以看到它。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-966">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="2ddd8-967">插入视频链接，只需占用相当于相应文件大小的一小部分的空间，即可享受多媒体演示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-967">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="2ddd8-968">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-968">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="2ddd8-969">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-969">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2ddd8-p190">**邀请受众参加测验或调查：** 幻灯片上放入测验或调查。Office 为你收集并存储该响应。[了解详细信息](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="2ddd8-p191">**比以往更轻松地插入联机视频：** 想要将 Vimeo 或 YouTube 中的视频放到幻灯片上？只需使用视频页面链接即可。[了解详细信息](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="2ddd8-976">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-976">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ddd8-977">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-977">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ddd8-978">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-978">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="2ddd8-979">Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-979">Project</span></span>

- <span data-ttu-id="2ddd8-980">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-980">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ddd8-981">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-981">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ddd8-982">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-982">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="2ddd8-983">Visio</span><span class="sxs-lookup"><span data-stu-id="2ddd8-983">Visio</span></span>

- <span data-ttu-id="2ddd8-984">**将流程图导出至 Word：** 向 Word 文档自动添加流程图内容，如形状和元数据。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-984">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="2ddd8-985">然后自定义文档以创建过程指南和操作手册。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-985">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="2ddd8-986">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-986">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="2ddd8-987">**数据流程图上的 Double-take：** 数据可视化工具流程图上引入注目的新布局干净、清爽且易于理解。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-987">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="2ddd8-988">单击“设计”选项卡可查看选项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-988">Click the Design tab for options.</span></span>

- <span data-ttu-id="2ddd8-989">**内置 Azure 模具：** 使用数十个 Azure 模具设计云应用或规划基础结构。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-989">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="2ddd8-990">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-990">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="2ddd8-p197">**告别断开的 Excel 链接：** 找不到链接到 Data Visualizer 图表的 Excel 工作簿？ 重新链接，你又可以开工了。[了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="2ddd8-994">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-994">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ddd8-995">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-995">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ddd8-996">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-996">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ddd8-997">**从 Power BI 导出 Visio 视觉对象：** 将 Power BI 导出为 PDF、PowerPoint 文件等时，Power BI 的 Visio 视觉对象现在将会正常显示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-997">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="2ddd8-998">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-998">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="2ddd8-999">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-999">Word</span></span>

- <span data-ttu-id="2ddd8-1000">**“学习工具”模式可额外支持更多页面颜色：** Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1000">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="2ddd8-1001">许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1001">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="2ddd8-p201">**使用笔迹编辑器随心编辑：** 使用单个笔划、拆分或连接字词、添加新行或使用手写笔插入字词。[了解详细信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="2ddd8-p202">**将文档从静态转换为惊艳：** 将文档转换为易于共享的交互式网页，使其在任何设备上都看起来很棒。[了解更多](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="2ddd8-1006">**增加内容的覆盖面：** 需要让你的文档易于访问？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1006">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="2ddd8-1007">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1007">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2ddd8-1008">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1008">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2ddd8-1009">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1009">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ddd8-1010">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1010">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2ddd8-1011">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1011">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ddd8-1012">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1012">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ddd8-1013">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1013">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ddd8-p206">**使用 Line Focus 提高理解力：** 专心地逐行浏览文档。调整焦点，一目一行、三行或五行。[了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="2ddd8-1017">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1017">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2ddd8-1018">**使用\@提及** 功能引起他人的注意：在批注中使用 @提及，以在需要同事的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1018">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2ddd8-1019">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1019">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="2ddd8-1020">**搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1020">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ddd8-1021">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1021">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ddd8-1022">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1022">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="2ddd8-1023">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1023">Office Suite</span></span>

- <span data-ttu-id="2ddd8-1024">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1024">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ddd8-1025">只需在“文件”>“打开”选项卡上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1025">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="2ddd8-1026">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1026">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2ddd8-1027">**隐私控制：** 对诊断数据和连接体验的全新、更新和改进控制。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1027">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="2ddd8-1028">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1028">Learn more</span></span>](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- <span data-ttu-id="2ddd8-1029">**Office 图标具有新的外观：** Office 图标经过重新设计，可体现简单、强大和智能的 Office 体验。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1029">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="2ddd8-1030">**Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1030">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="2ddd8-1031">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1031">Learn more</span></span>](/DeployOffice/teams-install)

[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-1034">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1034">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-1035">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1035">Access</span></span>

- <span data-ttu-id="2ddd8-1036">该更新修复了诸如“总和”等聚合可能将结果截断为整数值的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1036">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2ddd8-1037">该更新修复了包含对远程表（例如 SQL Server 表）的引用的联合查询可能导致 Access 关闭并重新启动的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1037">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2ddd8-1038">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现&quot;查询已损坏&quot;错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1038">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2ddd8-1039">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1039">Excel</span></span>

- <span data-ttu-id="2ddd8-1040">荷兰语文档标题快捷键提示已更改为 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1040">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2ddd8-1041">修复了 Excel 中的问题，其中分配给形状或表单控件的宏可能显示不正确的错误消息，或者可能在不正确的目标区域中工作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1041">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2ddd8-1042">解决了一个“查找和替换”问题，即在找到第一个项目后它改变了对话框中焦点的位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1042">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2ddd8-1043">修复了在更改数据透视表的排序方式并在与其他用户进行共同创作会话期间刷新它时可能触发崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1043">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2ddd8-1044">我们修复了当 OLAP 数据透视表的筛选器设置为已从多维数据集中删除的值时的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1044">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2ddd8-1045">修复了使用图表模板插入图表时预览中所用颜色的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1045">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2ddd8-1046">我们修复了在更改系列集合时可能导致散点图和折线图无法正确呈现的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1046">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="2ddd8-1047">解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1047">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2ddd8-1048">已修复了 Excel 中的合并冲突问题，该问题会导致系统提示用户重新打开工作簿以使更改生效。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1048">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2ddd8-1049">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1049">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ddd8-1050">解决了导致激活最小化窗口的宏运行时错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1050">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2ddd8-1051">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1051">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ddd8-1052">解决了在与其他人共同创作时导致表旁边的剪切和粘贴操作失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1052">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2ddd8-1053">解决了在使用运行的宏更改自定义属性时导致共同创作中断的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1053">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2ddd8-1054">发生问题时，将无法从加载项打开的 WPF （Windows Presentation Foundation）窗体的组合框中选择项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1054">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2ddd8-1055">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1055">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2ddd8-1056">异步用户定义函数的性能问题，该问题导致它们同步运行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1056">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2ddd8-1057">显著提高了删除包含合并单元格的列时的性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1057">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2ddd8-1058">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1058">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2ddd8-1059">解决了 Lookup 函数可能返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1059">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2ddd8-1060">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1060">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2ddd8-1061">当文件具有大量条件格式时，单击“字体颜色”按钮时会出现性能较低的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1061">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2ddd8-1062">我们修复了打印预览中的打印区域不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1062">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2ddd8-1063">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1063">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2ddd8-1064">我们显著提高了按颜色筛选的性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1064">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2ddd8-1065">解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1065">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2ddd8-1066">在加载项管理器中浏览时允许显示超过 16 个加载项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1066">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2ddd8-1067">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1067">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2ddd8-1068">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1068">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-1069">此更新修复了 Office 文档可能无法上传到 OneDrive for business，同时显示“上传失败”消息的错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1069">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2ddd8-1070">修复了在 Excel 创意功能中发现一个的问题，即通过单击 Win32 客户端中的“创意”按钮加载加载项时出错。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1070">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1071">Outlook</span></span>

- <span data-ttu-id="2ddd8-1072">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1072">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-1073">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得与其 Outlook 配置文件关联的错误帐户的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1073">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2ddd8-1074">解决了导致 Web 加载项在不应该访问“数字版权管理”消息时访问它们的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1074">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2ddd8-1075">解决了导致简单悬停 URL 无法显示某些安全链接的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1075">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2ddd8-1076">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1076">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2ddd8-1077">解决了导致部分 POP3 用户看到无论设置如何，其所有电子邮件均采用纯文本格式的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1077">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2ddd8-1078">此修补程序将还原 HTML 格式邮件的视图。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1078">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2ddd8-1079">解决了在将用户主日历中的项复制到组日历时出现导致用户遇到权限错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1079">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2ddd8-1080">解决了导致用户无法通过屏幕阅读器访问位置建议的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1080">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2ddd8-1081">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1081">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2ddd8-1082">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1082">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2ddd8-1083">解决了导致用户在打开规则对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1083">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2ddd8-1084">解决了导致用户在 Outlook 中与特定安全链接交互时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1084">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2ddd8-1085">解决了导致经理不清楚代理人是否已响应指定的会议请求的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1085">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2ddd8-1086">解决了导致用户在处理某些自动发现响应时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1086">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ddd8-1087">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1087">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ddd8-1088">该更改能够让管理员能够启用策略以便在自动发现身份验证提示中首选提供的帐户电子邮件而不是 UPN。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1088">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2ddd8-1089">默认情况下，自动发现优先于帐户 UPN（如果可用）。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1089">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2ddd8-1090">解决了导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1090">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2ddd8-1091">解决了导致 Outlook 用户在某些情况下“需要密码”的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1091">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2ddd8-1092">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1092">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2ddd8-1093">解决了用户在发送加密电子邮件时遇到“不支持加密算法“错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1093">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="2ddd8-1094">解决了非英语用户邮件中的主题行非常小的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1094">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2ddd8-1095">解决了导致某些用户在添加辅助 Exchange 帐户时会看到创建重复的特殊文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1095">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2ddd8-1096">解决了导致用户尝试“从错过的对话”消息创建规则时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1096">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2ddd8-1097">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1097">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2ddd8-1098">解决了在使用备用发件人时导致无法显示策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1098">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2ddd8-1099">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1099">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2ddd8-1100">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1100">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2ddd8-1101">解决了导致当前文件夹搜索间歇性失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1101">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2ddd8-1102">解决了导致某些用户在尝试检索 Outlook 的云设置时遇到身份验证错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1102">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2ddd8-1103">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1103">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2ddd8-1104">解决了导致用户在处理某些自动发现响应时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1104">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ddd8-1105">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1105">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-1106">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1106">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-1107">修复了某些加载项会在图表中的形状周围引发意外错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1107">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2ddd8-1108">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1108">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-1109">该更改还原 PowerPoint 视频控件易于访问的名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1109">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2ddd8-1110">我们修复了可能阻止某些动画启动的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1110">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="2ddd8-1111">我们修复了将一个幻灯片从一个演示文稿复制到另一个演示文稿时，可能创建重复母版的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1111">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="2ddd8-1112">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1112">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="2ddd8-1113">可靠性修复：修复了第三方加载项可能导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1113">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2ddd8-1114">修复了在 PowerPoint 中的竖排文本框中，半角片假名字符未正确旋转的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1114">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2ddd8-1115">Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1115">Project</span></span>

- <span data-ttu-id="2ddd8-1116">修复了 Windows 7 上的用户能够从 Project Web App 和 SharePoint 网站打开项目的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1116">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2ddd8-1117">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1117">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2ddd8-1118">“全部调配”命令不能正确解决资源的过度分配。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1118">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2ddd8-1119">如果你的任务分配为零工作，该任务可能无法标记为已完成，并且始终显示为 99%。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1119">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="2ddd8-1120">Visio</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1120">Visio</span></span>

- <span data-ttu-id="2ddd8-1121">从 Visio 导出为 SVG 的操作无法用于各种形状。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1121">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-1122">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1122">Word</span></span>

- <span data-ttu-id="2ddd8-1123">此更改将提升使用 Word 打开文档的效率。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1123">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="2ddd8-1124">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1124">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ddd8-1125">我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1125">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="2ddd8-1126">我们修复了跟踪更改有时会陷入无限循环的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1126">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2ddd8-1127">修复了应用可能会在关闭时挂起的各种问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1127">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2ddd8-1128">还修复了某些加载项相关的崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1128">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-1129">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1129">Office Suite</span></span>

- <span data-ttu-id="2ddd8-1130">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1130">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2ddd8-1131">修复了一个问题，该问题导致用户在尝试共享存储在 SharePoint 2016 上的文件时收到消息“抱歉，无法我们共享此内容”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1131">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2ddd8-1132">修复了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1132">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2ddd8-1133">此修复可解决用户打开文件时可能遇到的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1133">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2ddd8-1134">防止 PowerPoint 用户在尝试联机演示时遇到错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1134">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="2ddd8-1135">在某些情况下，同步引擎支持的 sharepoint 文件可能显示“已保存”，但并未真正保存任何更改，导致数据丢失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1135">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2ddd8-1136">解决了用户可能无法保存 Word、Excel 和 PowerPoint 文档的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1136">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2ddd8-1137">此问题会影响创建新文件并在单击“保存”图标或按 Ctrl + S 后显示“另存为对话框”选项的用户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1137">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2ddd8-1138">修复了 Win7 中的性能问题，它导致所有应用中功能区内的“插入形状”库大约需要 4 秒钟才会显示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1138">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2ddd8-1139">修复了在后台的信息放置面板中未显示可访问性信息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1139">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2ddd8-1140">改进了有关注册表完整性的 Office 更新进程的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1140">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2ddd8-1141">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1141">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2ddd8-1142">修复了 Office 更新消息以与预期不同的语言显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1142">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2ddd8-1143">今后，Office 更新消息将正确匹配 Windows 显示语言。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1143">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2ddd8-1144">解决了以下问题：在某些情况下，如果不是管理员，并且系统帐户没有网络连接，则不会应用更新。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1144">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2ddd8-1145">即在某些情况下，Office 快捷方式可能会在更新后消失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1145">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2ddd8-1146">此更新改进了发布 Office 快捷方式的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1146">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2ddd8-1147">更正了按流量计费的网络上可能意外阻止更新的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1147">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2ddd8-1148">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1148">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ddd8-1149">通过恢复以前可能已中断的下载，增强了下载 Office 更新时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1149">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2ddd8-1150">解决了与第三方插件中的“文本框/形状自动调整”属性相关的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1150">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2ddd8-1151">我们修复了大型树视图可能会导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1151">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="2ddd8-1152">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1152">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-january-14"></a><span data-ttu-id="2ddd8-1154">版本 1902：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1154">Version 1902: January 14</span></span>
<span data-ttu-id="2ddd8-1155">*版本 1902（内部版本 11328.20512）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1155">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="2ddd8-1156">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1156">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-1158">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1158">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-1159">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1159">Excel</span></span>

- <span data-ttu-id="2ddd8-1160">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1160">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-1161">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1161">Outlook</span></span>

- <span data-ttu-id="2ddd8-1162">解决了用户在发送加密电子邮件时遇到“不支持加密算法“错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1162">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-1163">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1163">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-1164">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1164">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-1165">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1165">Word</span></span>

- <span data-ttu-id="2ddd8-1166">此更改将提升使用 Word 打开文档的效率。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1166">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1808-january-14"></a><span data-ttu-id="2ddd8-1168">版本 1808：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1168">Version 1808: January 14</span></span>
<span data-ttu-id="2ddd8-1169">*版本 1808（内部版本 10730.20432）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1169">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="2ddd8-1170">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1170">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-december-10"></a><span data-ttu-id="2ddd8-1172">版本 1902：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1172">Version 1902: December 10</span></span>
<span data-ttu-id="2ddd8-1173">*版本 1902（内部版本 11328.20492）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1173">*Version 1902 (Build 11328.20492)*</span></span>

<span data-ttu-id="2ddd8-1174">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1174">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-1176">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1176">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-1177">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1177">Excel</span></span>

- <span data-ttu-id="2ddd8-1178">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1178">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-1179">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1179">Outlook</span></span>

- <span data-ttu-id="2ddd8-1180">明年的日历项目在 Outlook 中可能显示错误的时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1180">Calendar items for next year may display an incorrect time in Outlook.</span></span> [<span data-ttu-id="2ddd8-1181">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1181">Learn More</span></span>](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

- <span data-ttu-id="2ddd8-1182">解决了导致客户尝试从&quot;错过的对话&quot;消息创建规则时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1182">Addresses an issue that caused customers to encounter a crash when attempting to create a rule from a &quot;missed conversation&quot; message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-1183">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1183">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-1184">修复了与备注页面中打印（某些情况下存在布局问题）有关的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1184">Fixed an issue related to printing in notes page that had layout issues in some cases.</span></span>

## <a name="version-1808-december-10"></a><span data-ttu-id="2ddd8-1185">版本 1808：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1185">Version 1808: December 10</span></span>
<span data-ttu-id="2ddd8-1186">*版本 1808（内部版本 10730.20426）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1186">*Version 1808 (Build 10730.20426)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-1187">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1187">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ddd8-1188">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1188">Outlook</span></span>

- <span data-ttu-id="2ddd8-1189">明年的日历项目在 Outlook 中可能显示错误的时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1189">Calendar items for next year may display an incorrect time in Outlook.</span></span> [<span data-ttu-id="2ddd8-1190">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1190">Learn More</span></span>](/outlook/troubleshoot/calendars/calendar-items-display-incorrect-time)

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-november-22"></a><span data-ttu-id="2ddd8-1192">版本 1902：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1192">Version 1902: November 22</span></span>
<span data-ttu-id="2ddd8-1193">*版本 1902（内部版本 11328.20480）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1193">*Version 1902 (Build 11328.20480)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-1195">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1195">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-1196">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1196">Access</span></span>

- <span data-ttu-id="2ddd8-1197">已修复关于运行更新查询会错误地给出“查询已损坏”错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1197">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-1198">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1198">Outlook</span></span>

- <span data-ttu-id="2ddd8-1199">解决了导致用户在启用 toast 通知时发现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1199">Addressed an issue that caused users to observe memory leaks when toast notifications were enabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-1200">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1200">Office Suite</span></span>

- <span data-ttu-id="2ddd8-1201">进行此更改后，对于与限制无关的同步错误，将不会限制同步。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1201">With this change, syncing will not be throttled for sync errors that are not related to throttling.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1808-november-22"></a><span data-ttu-id="2ddd8-1203">版本 1808：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1203">Version 1808: November 22</span></span>
<span data-ttu-id="2ddd8-1204">*版本 1808（内部版本 10730.20422）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1204">*Version 1808 (Build 10730.20422)*</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="access"></a><span data-ttu-id="2ddd8-1206">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1206">Access</span></span>

- <span data-ttu-id="2ddd8-1207">已修复关于运行更新查询会错误地给出“查询已损坏”错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1207">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-november-12"></a><span data-ttu-id="2ddd8-1209">版本 1902：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1209">Version 1902: November 12</span></span>
<span data-ttu-id="2ddd8-1210">*版本 1902（内部版本 11328.20468）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1210">*Version 1902 (Build 11328.20468)*</span></span>

<span data-ttu-id="2ddd8-1211">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1211">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-1213">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1213">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2ddd8-1214">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1214">Excel</span></span>

- <span data-ttu-id="2ddd8-1215">解决了导致删除区域后延迟显示键入值的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1215">Resolved an issue that was causing delays in displaying typed values after deleting a range.</span></span>
- <span data-ttu-id="2ddd8-1216">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1216">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-1217">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1217">Outlook</span></span>

- <span data-ttu-id="2ddd8-1218">解决了导致用户在启用 toast 通知时发现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1218">Addressed an issue that caused users to observe memory leaks when toast notifications were enabled.</span></span>
- <span data-ttu-id="2ddd8-1219">解决了导致用户在 Outlook 中发现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1219">Addressed an issue that caused customers to notice a memory leak in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ddd8-1220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1220">PowerPoint</span></span>

- <span data-ttu-id="2ddd8-1221">可靠性修复：修复了第三方加载项可能导致 PowerPoint 失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1221">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-1222">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1222">Word</span></span>

- <span data-ttu-id="2ddd8-1223">我们修复了在尝试确定某些特殊字符时字体变为 MS Mincho 的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1223">We fixed an issue with font changed to MS Mincho when trying to finalize some special characters.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-1224">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1224">Office Suite</span></span>

- <span data-ttu-id="2ddd8-1225">修复了 Win7 中的性能问题，它导致所有应用中功能区内的“插入形状”库大约需要 4 秒钟才会显示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1225">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>
- <span data-ttu-id="2ddd8-1226">修复了更新后“开始”菜单快捷方式和 Office 文件扩展名会意外消失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1226">Fixed an issue where Start Menu shortcuts and Office file extensions would unexpectedly disappear following an update.</span></span>
- <span data-ttu-id="2ddd8-1227">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1227">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1808-november-12"></a><span data-ttu-id="2ddd8-1229">版本 1808：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1229">Version 1808: November 12</span></span>
<span data-ttu-id="2ddd8-1230">*版本 1808（内部版本 10730.20416）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1230">*Version 1808 (Build 10730.20416)*</span></span>

<span data-ttu-id="2ddd8-1231">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1231">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="2ddd8-1233">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1233">Resolved issues</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-1234">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1234">Outlook</span></span>

- <span data-ttu-id="2ddd8-1235">解决了一个问题，该问题导致用户（具有除“全部”以外的任何“保持脱机的邮件”设置）在将项目从本地存储移动到 Exchange Online 邮箱的同步窗口之外时发现数据丢失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1235">Addresses an issue that caused users with a "mail to keep offline setting" of anything other than "All" to see data loss when moving items outside of the sync window from a local store to Exchange Online mailbox.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-1236">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1236">Office Suite</span></span>

- <span data-ttu-id="2ddd8-1237">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1237">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-october-08"></a><span data-ttu-id="2ddd8-1239">版本 1902：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1239">Version 1902: October 08</span></span>
<span data-ttu-id="2ddd8-1240">*版本 1902（内部版本 11328.20438）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1240">*Version 1902 (Build 11328.20438)*</span></span>

<span data-ttu-id="2ddd8-1241">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1241">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ddd8-1243">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1243">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="2ddd8-1244">Excel</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1244">Excel</span></span>

- <span data-ttu-id="2ddd8-1245">解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1245">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

### <a name="project"></a><span data-ttu-id="2ddd8-1246">Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1246">Project</span></span>

- <span data-ttu-id="2ddd8-1247">修复了以下情况下未创建 XPS 文件的 PDF 时出现的问题：</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1247">Fixed an issue when the PDF of XPS file is not created in the following scenario:</span></span><ul><li><span data-ttu-id="2ddd8-1248">打开项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1248">You open a project.</span></span></li><li><span data-ttu-id="2ddd8-1249">单击“文件”菜单，单击“导出”，然后单击“<b>创建 PDF/XPS</b>”按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1249">You click the File menu, click Export and click the<b> Create PDF/XPS</b> button.</span></span></li><li><span data-ttu-id="2ddd8-1250">在“浏览”对话框中，输入文件名，然后单击“确定”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1250">Within the Browse dialog box, you enter a file name and click OK.</span></span></li></ul>

### <a name="word"></a><span data-ttu-id="2ddd8-1251">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1251">Word</span></span>

- <span data-ttu-id="2ddd8-1252">修复了使用 Caps + 向右箭头时 Windows 当前内部版本上的 JAWS 不会朗读单词的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1252">Fixed an issue where JAWS on Windows current builds won't announce words when using Caps + Right arrow.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ddd8-1253">Office 套件</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1253">Office Suite</span></span>

- <span data-ttu-id="2ddd8-1254">现在，用户能够保存由 OneDrive 同步客户端同步的 Office 文件，但缺少所需的属性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1254">Users will now be able to save Office files synced by the OneDrive sync client with missing required properties.</span></span> <span data-ttu-id="2ddd8-1255">通过转到“文件>信息”，可继续通过文档后台查看和编辑文档属性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1255">The document properties will continue to be available for viewing and editing through the document backstage by going to File>Info.</span></span> <span data-ttu-id="2ddd8-1256">此更改将使性能提高。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1256">This change will lead to performance improvements.</span></span>

- <span data-ttu-id="2ddd8-1257">修复了登录成功后“&quot;修复我的帐户&quot;”通知未消失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1257">Fixed an issue where &quot;Fix my account&quot; notification does not disappear after signing-in successfully.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1808-october-08"></a><span data-ttu-id="2ddd8-1259">版本 1808：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1259">Version 1808: October 08</span></span>

<span data-ttu-id="2ddd8-1260">*版本 1808（内部版本 10730.20386）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1260">*Version 1808 (Build 10730.20386)*</span></span>

<span data-ttu-id="2ddd8-1261">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1261">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1902-september-10"></a><span data-ttu-id="2ddd8-1262">版本 1902：9月10日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1262">Version 1902: September 10</span></span>
<span data-ttu-id="2ddd8-1263">*版本 1902（内部版本 11328.20420）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1263">*Version 1902 (Build 11328.20420)*</span></span>

<span data-ttu-id="2ddd8-1264">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1264">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ddd8-1266">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1266">Non-security updates</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-1267">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1267">Access</span></span>

- <span data-ttu-id="2ddd8-1268">解决了导致 Microsoft Access 中的某些查询运行速度比先前版本慢的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1268">Fixed an issue that caused certain queries in Microsoft Access to run more slowly than in previous builds.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ddd8-1269">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1269">Outlook</span></span>

- <span data-ttu-id="2ddd8-1270">修复了导致用户在使用云附件时看到错误“无法找到此文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1270">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="2ddd8-1271">验证路径和文件名是否正确”的临时服务问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1271">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="2ddd8-1272">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1272">Learn more</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="2ddd8-1273">修复了以下问题：用户看到从 Outlook 上传到 OneDrive 或 Sharepoint 的文件名已更改，其中多个字符替换为下划线。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1273">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

### <a name="word"></a><span data-ttu-id="2ddd8-1274">Word</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1274">Word</span></span>

- <span data-ttu-id="2ddd8-1275">修复了用户在 Word 文档中与他人协作时收到错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1275">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1808-september-10"></a><span data-ttu-id="2ddd8-1277">版本 1808：9月10日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1277">Version 1808: September 10</span></span>
<span data-ttu-id="2ddd8-1278">*版本 1808（内部版本 10730.20380）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1278">*Version 1808 (Build 10730.20380)*</span></span>

<span data-ttu-id="2ddd8-1279">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1279">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="2ddd8-1281">非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1281">Non-security updates</span></span>
### <a name="access"></a><span data-ttu-id="2ddd8-1282">Access</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1282">Access</span></span>

- <span data-ttu-id="2ddd8-1283">解决了导致 Microsoft Access 中的某些查询运行速度比先前版本慢的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1283">Fixed an issue that caused certain queries in Microsoft Access to run more slowly than in previous builds.</span></span>

## <a name="version-1902-august-13"></a><span data-ttu-id="2ddd8-1284">版本 1902：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1284">Version 1902: August 13</span></span>
<span data-ttu-id="2ddd8-1285">*版本 1902（内部版本 11328.20392）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1285">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="2ddd8-1286">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1286">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="2ddd8-1287">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1287">Excel: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1288">修复了表中针对已筛选切片器和未筛选切片器均显示清除筛选器图标的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1288">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1289">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1289">Outlook: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1290">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得错误的关联帐户的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1290">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="2ddd8-1291">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1291">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1292">修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1292">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1293">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1293">Word: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1294">修复了 VBA 更新字段的速度缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1294">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="2ddd8-1295">修复了打开某个 DOC 文件时系统表示该文件已损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1295">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="2ddd8-1296">修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1296">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1297">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1297">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1298">修复了在某些情况下设置 API 在 Office JavaScript 库中无法正常工作的问题[了解更多](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1298">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1808-august-13"></a><span data-ttu-id="2ddd8-1299">版本 1808 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1299">Version 1808 August 13</span></span>
<span data-ttu-id="2ddd8-1300">*版本 1808（内部版本 10730.20370）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1300">*Version 1808 (Build 10730.20370)*</span></span>

<span data-ttu-id="2ddd8-1301">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1301">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1302">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1302">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1303">修复了在某些情况下设置 API 在 Office JavaScript 库中无法正常工作的问题[了解更多](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1303">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>


## <a name="version-1803-august-13"></a><span data-ttu-id="2ddd8-1304">版本 1803 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1304">Version 1803 August 13</span></span>
<span data-ttu-id="2ddd8-1305">*版本 1803（内部版本 9126.2432）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1305">*Version 1803 (Build 9126.2432)*</span></span>

<span data-ttu-id="2ddd8-1306">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1306">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1307">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1307">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1308">修复了在某些情况下设置 API 在 Office JavaScript 库中无法正常工作的问题[了解更多](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1308">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>


## <a name="version-1902-july-09"></a><span data-ttu-id="2ddd8-1309">版本 1902：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1309">Version 1902: July 09</span></span>
<span data-ttu-id="2ddd8-1310">*版本 1902（内部版本 11328.20368）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1310">*Version 1902 (Build 11328.20368)*</span></span>
<br/><span data-ttu-id="2ddd8-1311">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1311">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="access-feature-updates"></a><span data-ttu-id="2ddd8-1312">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1312">Access: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1313">**刷新、重新链接或删除链接表** 更新的链接表管理器可用于管理所有数据源和链接表。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1313">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables.</span></span> [<span data-ttu-id="2ddd8-1314">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1314">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- <span data-ttu-id="2ddd8-p223">**将其涂成黑色，将其涂成灰色：** 根据需要随时更改 Access 的外观。四种主题可供选择：彩色、深灰色、黑色和白色。[了解详细信息](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p223">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="2ddd8-1318">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1318">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="2ddd8-1319">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1319">Excel: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1320">**更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1320">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="2ddd8-1321">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1321">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="2ddd8-1322">**通过注释进行协作：** 使用内置回复框在电子表格中保持正常对话。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1322">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box.</span></span> [<span data-ttu-id="2ddd8-1323">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1323">Learn more</span></span>](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- <span data-ttu-id="2ddd8-1324">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1324">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="2ddd8-1325">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1325">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="2ddd8-1326">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1326">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="2ddd8-p227">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p227">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="2ddd8-p228">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p228">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="2ddd8-1332">**呼叫所有“获取和转换”功能的粉丝：** 如果你经常使用“获取和转换”功能，那么对于“从示例中添加列”功能已得到改进的消息一定兴奋不已。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1332">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved.</span></span> <span data-ttu-id="2ddd8-1333">另外，许多连接器也得到了改进。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1333">And, many connectors have been improved as well.</span></span> [<span data-ttu-id="2ddd8-1334">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1334">Learn more</span></span>](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- <span data-ttu-id="2ddd8-1335">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1335">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="2ddd8-1336">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1336">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="2ddd8-1337">**快速查找** 已极大地提升了 VLOOKUP、HLOOKUP 和 MATCH 计算速度，以便能够更快地获取答案。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1337">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster.</span></span> [<span data-ttu-id="2ddd8-1338">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1338">Learn more</span></span>](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a><span data-ttu-id="2ddd8-1339">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1339">Outlook: Feature updates</span></span>

- <span data-ttu-id="2ddd8-p232">**使用“大声朗读”来收听你的电子邮件：** Outlook 可以大声朗读你的电子邮件，并突出显示正在阅读的文本。要打开大声朗读功能，请转到“轻松访问”设置。[了解详细信息](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p232">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="2ddd8-1343">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1343">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="2ddd8-1344">单击“听写”，即可看到 Outlook 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1344">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="2ddd8-1345">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1345">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="2ddd8-1346">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1346">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="2ddd8-1347">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1347">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="2ddd8-1348">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1348">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="2ddd8-1349">**默认阻止下载 SMIME 加密和签名的电子邮件中的外部内容：** 鉴于 SMIME 协议中的漏洞，Outlook 将阻止下载由 SMIME 加密或签名的邮件上的外部内容。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1349">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME.</span></span> <span data-ttu-id="2ddd8-1350">用户将无法通过 Outlook UI 单击下载外部内容，以防止受到安全漏洞的危害。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1350">Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability.</span></span> <span data-ttu-id="2ddd8-1351">“选项”对话框提供了一个新选项，用户可使用它还原至旧行为。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1351">There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="2ddd8-1352">**禁用会议转发：** 阻止与会者将会议转发给其他人。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1352">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others.</span></span> <span data-ttu-id="2ddd8-1353">只需转到功能区，然后单击“响应选项”即可。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1353">Just go to the ribbon and click Response Options.</span></span> [<span data-ttu-id="2ddd8-1354">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1354">Learn more</span></span>](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- <span data-ttu-id="2ddd8-p237">**日程安排助理中的人员建议：** 安排会议时查看有关要添加的与会者的建议。无需在日程安排助理和收件人行之间来回切换。[了解详细信息](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p237">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="2ddd8-1358">**保留会议室变得更加容易：** 使用多个会议室列表查找会议室，切换列表时不会丢失所选的会议室。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1358">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="2ddd8-p238">**重复周期范围的新默认值：** 对于“重复周期”对话框，在过去重复周期范围的默认值为“无结束日期”。这有助于创建长期运行的定期系列，随着时间的推移可能会损坏。我们将“重复周期”对话框的默认值更新为“结束日期”，以便我们的默认值与建议的日历最佳做法相匹配。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p238">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date". This facilitated the creation of long-running recurring series, which can become corrupted over time. We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="2ddd8-p239">**从“Outlook 提醒”对话框加入团队会议：** 当 Outlook 提醒用户参加即将召开的会议时，如果即将召开的会议是团队在线会议，则它将显示一个“联机加入”按钮。这与从“Outlook 提醒”对话框加入 Skype for Business 会议的体验类似。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p239">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="2ddd8-1364">**停止查看过去活动的提醒：** 可以将日历设置为在活动结束后自动关闭活动提醒。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1364">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended.</span></span> [<span data-ttu-id="2ddd8-1365">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1365">Learn more</span></span>](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- <span data-ttu-id="2ddd8-1366">**查看安全链接背后的 URL：** 安全链接有助于保护你免受电子邮件中收到的恶意 URL 的攻击，但它们会隐藏原始 URL。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1366">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="2ddd8-1367">若要查看原始 URL，请将鼠标悬停在 URL上。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1367">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="2ddd8-1368">需要高级威胁防护许可证。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1368">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="2ddd8-1369">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1369">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="2ddd8-1370">**缩放和粘贴：** 选择默认设置用于所有邮件，而无需在每次阅读邮件时调整缩放。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1370">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.</span></span> [<span data-ttu-id="2ddd8-1371">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1371">Learn more</span></span>](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- <span data-ttu-id="2ddd8-1372">**邮件加密：仅加密 IRM 策略：** 新的仅加密选项显示在 Office 365 邮件加密用户的“选项”>“权限”菜单中。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1372">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="2ddd8-1373">此选项允许你加密邮件并将其发送给组织内部或外部的任何人。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1373">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="2ddd8-1374">**密件抄送 (BCC) 警告：** BCC 信息提示会在你意外对被密件抄送的邮件全部答复之前发出警告。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1374">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="2ddd8-1375">**更智能的“收件人:”行：** 在单击“收件人:”行处理邮件时，会提示用户可能要选择的收件人。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1375">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="2ddd8-1376">此外，还可以看到收件人的照片，这样用户便能知道自己将要向其发送邮件的收件人是否正确。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1376">Plus, you can see their picture, so you know yo're sending to the right person.</span></span> [<span data-ttu-id="2ddd8-1377">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1377">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="2ddd8-p245">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p245">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="2ddd8-1380">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1380">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="2ddd8-1381">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1381">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="2ddd8-1382">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1382">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1383">**更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1383">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="2ddd8-1384">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1384">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="2ddd8-1385">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1385">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="2ddd8-1386">单击“听写”，即可看到 PowerPoint 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1386">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="2ddd8-1387">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1387">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="2ddd8-1388">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1388">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="2ddd8-1389">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1389">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="2ddd8-1390">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1390">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="2ddd8-1391">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1391">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="2ddd8-1392">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1392">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="2ddd8-1393">**使用其他生动颜色显示超链接：** 超链接不再只是蓝色的。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1393">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="2ddd8-1394">可以根据需要应用任何字体颜色。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1394">Apply any font color you like.</span></span> [<span data-ttu-id="2ddd8-1395">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1395">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="2ddd8-1396">**查看栩栩如生的幻灯片：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个屏幕中横冲直撞的霸王龙。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1396">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.</span></span> [<span data-ttu-id="2ddd8-1397">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1397">Learn more</span></span>](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- <span data-ttu-id="2ddd8-p253">**用户绘制草图，我们来润色：** 我们将手绘文本和形状变为精致的图表。只需选择笔划墨迹即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p253">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="2ddd8-p254">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p254">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="2ddd8-1404">**发布到 Microsoft Stream：** 通过使用 Microsoft Stream 在组织中更为安全地将演示文稿作为视频进行共享。 </span><span class="sxs-lookup"><span data-stu-id="2ddd8-1404">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="2ddd8-1405">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1405">Learn more</span></span>](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- <span data-ttu-id="2ddd8-1406">**导出为 4K 视频：** 将演示文稿导出为视频时，现在可以选择 4K 分辨率。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1406">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="2ddd8-1407">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1407">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="2ddd8-p257">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p257">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="2ddd8-1410">**大文件现在可以更快地打开：** 打开存储在 OneDrive 或 SharePoint 中的文件时，图像、视频和其他大文件现在可以在后台下载。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1410">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="2ddd8-1411">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1411">Word: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1412">**更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1412">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="2ddd8-1413">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1413">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="2ddd8-1414">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1414">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="2ddd8-1415">单击“听写”，即可看到 Word 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1415">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="2ddd8-1416">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1416">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="2ddd8-p260">**查看栩栩如生的文档：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个页面中横冲直撞的霸王龙。[了解详细信息](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p260">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="2ddd8-1419">**功能区图标具有新的外观：** 请不要担心，所有功能的工作方式不变。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1419">**Your ribbon icons have a new look:** Don't worry, everything works the same.</span></span> <span data-ttu-id="2ddd8-1420">此外，这些图标在各种尺寸的屏幕上看起来都很美观。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1420">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="2ddd8-1421">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1421">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="2ddd8-p262">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p262">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="2ddd8-p263">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p263">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="2ddd8-1427">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1427">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="2ddd8-1428">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1428">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="2ddd8-p265">**在 LinkedIn 的帮助下编写你的出色简历：** 通过简历助手查看工作经验、建议技能及给定角色的详细信息。 [了解详细信息](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p265">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="2ddd8-1431">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1431">Project: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1432">**在任务板卡片上了解更多信息：** 如果单独的标题无法描述详情，可以自定义任务板卡片以显示所有最重要的详细信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1432">**See more info on Task Board cards:** When the title alone doesn't tell the story, customize your Task Board cards to show all the most important details.</span></span> [<span data-ttu-id="2ddd8-1433">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1433">Learn more</span></span>](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- <span data-ttu-id="2ddd8-1434">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1434">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="2ddd8-1435">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1435">Publisher: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1436">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1436">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="2ddd8-1437">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1437">Visio: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1438">**在下一个图表中享受全新图标时刻：** 从 26 个新的模具中挑选，其中包含用于分析、艺术、庆祝、人脸、运动等的图标。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1438">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="2ddd8-1439">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1439">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="2ddd8-1440">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1440">Office Suite: Feature updates</span></span>

- <span data-ttu-id="2ddd8-p267">**Office 第三方应用程序现已支持通过 office.js API 插入 SVG：** 第三方应用程序也称为 Office 中的加载项，它们现可插入 SVG。用户现可将其个人的 SVG 集合连接到 Office。而开发人员可通过 Office.js API 使用该项功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p267">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="2ddd8-1444">**Microsoft Teams 安装：** 默认情况下，将为新安装的 Office 365 ProPlus 安装 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1444">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for NEW installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="2ddd8-1445">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1445">Learn more</span></span>](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="2ddd8-1446">Skype for Business：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1446">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="2ddd8-1447">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1447">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="2ddd8-1448">了解更多</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1448">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)


### <a name="excel-non-security-updates"></a><span data-ttu-id="2ddd8-1449">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1449">Excel: Non-security updates</span></span>

- <span data-ttu-id="2ddd8-1450">解决了将包含 XML 映射的文件保存为 PDF 时导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1450">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
- <span data-ttu-id="2ddd8-1451">解决了在加载包含无效工作表名称的工作簿时导致外部链接被删除的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1451">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
- <span data-ttu-id="2ddd8-1452">解决了在 Excel 中使用照相机工具会导致电子表格挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1452">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
- <span data-ttu-id="2ddd8-1453">解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1453">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
- <span data-ttu-id="2ddd8-1454">解决了在工作表计算期间使用另一张工作表上的数组公式（具体取决于表）重新计算数据表时发生的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1454">Resolved an issue when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
- <span data-ttu-id="2ddd8-1455">解决了在未先签出文件的情况下阻止从 SharePoint 打开受密码保护的工作簿的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1455">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
- <span data-ttu-id="2ddd8-1456">已进行更改，以确保在共享或切换“自动保存”时处理 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1456">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span> 
- <span data-ttu-id="2ddd8-1457">修复了在带有图表工作表的活动窗口中使用鼠标滚轮时的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1457">An issue using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
- <span data-ttu-id="2ddd8-1458">解决了在 SharePoint 中导入电子表格时出现“意外错误”消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1458">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
- <span data-ttu-id="2ddd8-1459">解决了在打开包含使用其规则的名称的条件格式且应用了自定义视图的工作簿时的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1459">A problem that opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
- <span data-ttu-id="2ddd8-1460">使用长度超过 255 个字符的公式进行数据验证的宏可能会产生运行时错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1460">Macros using data validation with formulas longer than 255 characters may have produced run-time errors.</span></span> <span data-ttu-id="2ddd8-1461">此问题现已得到更正。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1461">This issue has now been corrected.</span></span>
- <span data-ttu-id="2ddd8-1462">导致包含链接到其他工作簿的数据透视表的文件加载缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1462">A problem which caused files containing PivotTables linked to other workbooks to load slowly.</span></span> <span data-ttu-id="2ddd8-1463">此问题已解决。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1463">This issue has been resolved.</span></span>
- <span data-ttu-id="2ddd8-1464">解决了打开 HTML 文件和接收“文件格式和扩展名不匹配”错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1464">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
- <span data-ttu-id="2ddd8-1465">已经进行了更改，以解决在非活动窗口上滚动鼠标滚轮的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1465">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>
- <span data-ttu-id="2ddd8-1466">解决了在包含以定义名称结尾的公式的单元格中按 Tab 键不会移动到下一个单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1466">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="2ddd8-1467">解决了单元格格式化导致文件大小不必要增长的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1467">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="2ddd8-1468">解决了在工作簿之间剪切和粘贴数据透视表可能导致数据被粘贴的问题，不包含与你正在协作的其他人的数据透视表。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1468">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1469">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1469">Outlook: Non-security updates</span></span>

- <span data-ttu-id="2ddd8-1470">解决了在向“分组依据”添加第 2 个条件时导致客户看到其任务似乎消失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1470">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>
- <span data-ttu-id="2ddd8-1471">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1471">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>
- <span data-ttu-id="2ddd8-1472">修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1472">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="2ddd8-1473">解决了导致客户在联系人卡片上加载图片时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1473">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="2ddd8-1474">解决了导致某些客户在启动 Office 应用程序时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1474">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="2ddd8-1475">修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1475">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="2ddd8-1476">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1476">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>


### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="2ddd8-1477">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1477">PowerPoint: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1478">解决了 PowerPoint 停止上传用户更改到云端的问题（此情况极不常见）。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1478">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>


### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="2ddd8-1479">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1479">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="2ddd8-1480">修复了以下问题：Lync (Skype for Business) 中对于任何有 7 个以上参与者的在线会议，会议窗口可能会消失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1480">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
- <span data-ttu-id="2ddd8-1481">使用登录其他 Office 应用程序时所用的凭据登录 Skype for Business。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1481">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
- <span data-ttu-id="2ddd8-1482">在安装有共享计算机激活时正确激活 Skype for Business 应用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1482">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="2ddd8-1483">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1483">Visio: Non-security updates</span></span>

- <span data-ttu-id="2ddd8-1484">解决了导致第三方解决方案通过禁用动态 DPI 功能来扩展 Visio 时出现窗口层次结构损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1484">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>


### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1485">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1485">Word: Non-security updates</span></span>

 - <span data-ttu-id="2ddd8-1486">修复了在共享当前处于协作状态的文档时生成扩展名为 .asd 的附件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1486">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="2ddd8-1487">修复了将评论归因于随机作者的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1487">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="2ddd8-1488">修复了在签出文档时删除签名的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1488">Fixed an issue in the remove signature when checking out a document.</span></span>
 - <span data-ttu-id="2ddd8-1489">解决了在编辑由 SharePoint 添加的相关人员时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1489">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="2ddd8-1490">解决了在 Word 启动时出现“未能加载资源”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1490">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>
 - <span data-ttu-id="2ddd8-1491">如果文件以只读模式打开，并且你从“信息”窗格中单击“另存为”，则修复问题以便显示“保存 UI”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1491">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>


### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1492">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1492">Office Suite: Non-security updates</span></span>

 - <span data-ttu-id="2ddd8-1493">修复了在执行“撤消”操作后 VBA 报告错误形状填充状态的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1493">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>
 - <span data-ttu-id="2ddd8-1494">这是文件无法保存至 Apache WebDAV 文件夹问题的修复。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1494">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="2ddd8-1495">修复了在客户打开某些云存储文件时 Office 突然关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1495">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="2ddd8-1496">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1496">Fixed an issue of incorrectly identifying the new era name "Reiwa" in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="2ddd8-1497">解决了 Windows 10 上貌似已清除多位用户的“最近使用的文件”列表这一问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1497">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="2ddd8-1498">解决了即使站在进行管理器触发的更新，最终用户仍会看到“Office 更新”业务栏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1498">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="2ddd8-1499">解决了与登录提示间歇性空白相关的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1499">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 - <span data-ttu-id="2ddd8-1500">修复了以下问题：Office 更新的某些部分不使用传递优化对等缓存。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1500">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="2ddd8-1501">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1501">Learn more</span></span>](/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="2ddd8-1502">修复了如果使用 Office 部署工具安装 Office 且存在不匹配的情况时，可能导致产品被删除或未激活的 bug。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1502">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="2ddd8-1503">修复了导致 Windows 10（版本 1803 或更高版本）设备上出现过多登录提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1503">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="2ddd8-1504">修复了下载链接图片时导致挂起的回归。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1504">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="2ddd8-1505">修复了粘贴在 Word、Excel、PowerPoint 中的大型 EMF 文件的模糊性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1505">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="2ddd8-1506">修复了版本历史记录解析逻辑中的 bug，这些 bug 在少数情况下会导致文档以只读方式打开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1506">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>


## <a name="version-1808-july-09"></a><span data-ttu-id="2ddd8-1507">版本 1808：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1507">Version 1808: July 09</span></span>
<span data-ttu-id="2ddd8-1508">*版本 1808（内部版本 10730.20360）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1508">*Version 1808 (Build 10730.20360)*</span></span>
<br/><span data-ttu-id="2ddd8-1509">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1509">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1510">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1510">Word: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1511">改善了为“文档属性”启用“文档部件”时的性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1511">Improved performance when enabling Quick Parts for Document properties.</span></span>
- <span data-ttu-id="2ddd8-1512">修复了在签出文件时删除签名的相关问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1512">Fixed an issue about remove signature when checking out a file.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1513">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1513">Office Suite: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1514">修复了影响在虚拟化 Windows 上运行的 Office 应用程序的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1514">Fixed an issue affecting Office applications running on virtualized Windows.</span></span>


## <a name="version-1803-july-09"></a><span data-ttu-id="2ddd8-1515">版本 1803：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1515">Version 1803: July 09</span></span>
<span data-ttu-id="2ddd8-1516">*版本 1803（内部版本 9126.2428）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1516">*Version 1803 (Build 9126.2428)*</span></span>
<br/><span data-ttu-id="2ddd8-1517">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1517">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


## <a name="version-1808-june-11"></a><span data-ttu-id="2ddd8-1518">版本 1808：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1518">Version 1808: June 11</span></span>
<span data-ttu-id="2ddd8-1519">*版本 1808（内部版本 10730.20348）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1519">*Version 1808 (Build 10730.20348)*</span></span>
<br/><span data-ttu-id="2ddd8-1520">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1520">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1521">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1521">Word: Non-Security updates</span></span>
 - <span data-ttu-id="2ddd8-1522">修复了在签出文件时删除签名的相关问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1522">Fixed an issue about remove signature when checking out a file.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1523">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1523">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="2ddd8-1524">解决了可能会导致在虚拟化 Windows 上运行的 Office 应用程序崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1524">Fixed an issue that could crash Office applications running on virtualized Windows.</span></span>

## <a name="version-1803-june-11"></a><span data-ttu-id="2ddd8-1525">版本 1803：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1525">Version 1803: June 11</span></span>
<span data-ttu-id="2ddd8-1526">*版本 1803（内部版本 9126.2388）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1526">*Version 1803 (Build 9126.2388)*</span></span>
<br/><span data-ttu-id="2ddd8-1527">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1527">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span> 

## <a name="version-1808-may-14"></a><span data-ttu-id="2ddd8-1528">版本 1808：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1528">Version 1808: May 14</span></span>
<span data-ttu-id="2ddd8-1529">*版本 1808（内部版本 10730.20344）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1529">*Version 1808 (Build 10730.20344)*</span></span>   

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1530">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1530">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="2ddd8-1531">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1531">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="2ddd8-1532">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1532">Visio: Non-security updates</span></span>
 - <span data-ttu-id="2ddd8-1533">解决了导致第三方解决方案通过禁用动态 DPI 功能来扩展 Visio 时出现窗口层次结构损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1533">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1534">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1534">Word: Non-Security updates</span></span>
 - <span data-ttu-id="2ddd8-1535">解决了在编辑由 SharePoint 添加的相关人员时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1535">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1536">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1536">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="2ddd8-1537">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1537">Fixed an issue of incorrectly identifying the new era name "Reiwa" in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
  
## <a name="version-1803-may-14"></a><span data-ttu-id="2ddd8-1538">版本 1803：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1538">Version 1803: May 14</span></span>
<span data-ttu-id="2ddd8-1539">*版本1803（内部版本 9126.2387）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1539">*Version 1803 (Build 9126.2387)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1540">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1540">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="2ddd8-1541">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1541">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1542">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1542">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="2ddd8-1543">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1543">Fixed an issue of incorrectly identifying the new era name "Reiwa" in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

## <a name="version-1808-april-9"></a><span data-ttu-id="2ddd8-1544">版本 1808：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1544">Version 1808: April 9</span></span>
<span data-ttu-id="2ddd8-1545">*版本 1808（内部版本 10730.20334）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1545">*Version 1808 (Build 10730.20334)*</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="2ddd8-1546">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1546">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-1547">修复了以下问题：Lync (Skype for Business) 中对于任何有 7 个以上参与者的在线会议，会议窗口可能会消失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1547">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1548">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1548">Word: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1549">修复了以下问题：用户可以在 IE 或 Edge 中匿名打开文档。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1549">Fixed an issue where the user can open documents anonymously in IE or Edge.</span></span>
- <span data-ttu-id="2ddd8-1550">修复了以下问题：应用于任何 Word 文档页眉/页脚 PAGE 和/或 NUMPAGES 字段的文本高亮颜色格式将字段呈现为黑色而不是应用的文本突出显示颜色。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1550">Fixed an issue where text highlight color formatting applied to any Word document header/footer PAGE and/or NUMPAGES field renders the field as black instead of the applied text highlight color.</span></span>
- <span data-ttu-id="2ddd8-1551">我们添加了对 Word 日语明信片向导加载项的支持，用于日本新时代。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1551">We added support to Word Japanese postcard wizard add-in for the Japanese new era.</span></span> 

## <a name="version-1803-april-9"></a><span data-ttu-id="2ddd8-1552">版本 1803：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1552">Version 1803: April 9</span></span>
- <span data-ttu-id="2ddd8-1553">[此处](microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1553">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1808-march-12"></a><span data-ttu-id="2ddd8-1554">版本 1808：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1554">Version 1808: March 12</span></span>
<span data-ttu-id="2ddd8-1555">*版本 1808（内部版本 10730.20304）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1555">*Version 1808 (Build 10730.20304)*</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1556">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1556">Word: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1557">已修复 VBA 返回不正确页码问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1557">Fixed an issue when VBA returns incorrect page number.</span></span>
- <span data-ttu-id="2ddd8-1558">缩短保存本地 Word 文件的时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1558">Improve time to save on local Word file.</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1559">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1559">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1560">提供了 regkey 以禁用 Office 365 邮件加密菜单中的“仅加密”选项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1560">Provided regkey to disable the "Encrypt Only" option in the Office 365 Message Encryption menu.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1561">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1561">Office Suite: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1562">已修复 Office 更新可能会在尝试下载时停滞一段时间的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1562">Fixed an issue where Office update may get stuck for some time trying to download.</span></span>

## <a name="version-1803-march-12"></a><span data-ttu-id="2ddd8-1563">版本 1803：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1563">Version 1803: March 12</span></span> 
- <span data-ttu-id="2ddd8-1564">[此处](microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1564">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1808-february-12"></a><span data-ttu-id="2ddd8-1565">版本 1808：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1565">Version 1808: February 12</span></span>
<span data-ttu-id="2ddd8-1566">版本 1808（内部版本 10730.20280）</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1566">*Version 1808 (Build 10730.20280)*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="2ddd8-1567">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1567">Access: Non-Security updates</span></span> 

- <span data-ttu-id="2ddd8-1568">此更新将对新日本和历的支持添加到 Access。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1568">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1569">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1569">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="2ddd8-p273">解决以下问题：具有引用不再存在的文件夹规则的用户在尝试管理规则时 1. 看到错误，2. 看到客户端规则运行失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p273">Addresses an issue that caused users with rules that refer to a folder that no longer exist to 1. See an error when trying to manage rules and 2. See client-side rules fail to run.</span></span>
- <span data-ttu-id="2ddd8-1573">处理以下问题：具有缓存委托邮箱的用户在不可预测的时间间隔遇到频繁挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1573">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="2ddd8-1574">处理以下问题：由于会议结束时间设置为第二天的午夜，在一些视图中，全天会议似乎超过预期的一天时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1574">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="2ddd8-1575">修复了创建引用日本和历的新约会或会议时的挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1575">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1576">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1576">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="2ddd8-1577">修复以下问题：使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的外接程序被冻结且不可用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1577">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1803-february-12"></a><span data-ttu-id="2ddd8-1578">版本 1803：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1578">Version 1803: February 12</span></span>
<span data-ttu-id="2ddd8-1579">版本 1803（内部版本 9126.2356）</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1579">*Version 1803 (Build 9126.2356)*</span></span>

<span data-ttu-id="2ddd8-1580">这是自 2018 年 7 月起就已发布的半年频道版本。2019 年 9 月前，此版本会继续获得支持，并接收安全更新。不过，新版半年频道（即版本 1808，内部版本 10730.20280）现已推出，其中包含新增功能、安全更新和非安全更新。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1580">*This is the Semi-Annual Channel release that's been available since July 2018. It will continue to be supported and receive security updates until September 2019. But, a new Semi-Annual Channel release is now available — Version 1808 (Build 10730.20280) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="2ddd8-1581">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1581">Access: Non-Security updates</span></span> 

- <span data-ttu-id="2ddd8-1582">此更新将对新日本和历的支持添加到 Access。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1582">This update adds support for new Japanese eras to Access.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="2ddd8-1583">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1583">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="2ddd8-1584">此更新将对新日本和历的支持添加到 Excel。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1584">This update adds support for new Japanese eras to Excel.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1585">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1585">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1586">修复了创建引用日本和历的新约会或会议时的挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1586">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="2ddd8-1587">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1587">Project: Non-Security updates</span></span>
- <span data-ttu-id="2ddd8-1588">此更新将对新日本和历的支持添加到 Project</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1588">This update adds support for new Japanese eras to Project</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1589">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1589">Word: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1590">此更新将对新日本和历的支持添加到 Word。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1590">This update adds support for new Japanese eras to Word.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="2ddd8-1591">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1591">Visio: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1592">此更新将对新日本和历的支持添加到 Visio。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1592">This update adds support for new Japanese eras to Visio.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1593">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1593">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="2ddd8-1594">修复以下问题：使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的外接程序被冻结且不可用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1594">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>

## <a name="version-1708-february-12"></a><span data-ttu-id="2ddd8-1595">版本 1708：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1595">Version 1708: February 12</span></span>
<span data-ttu-id="2ddd8-1596">*版本 1708（内部版本 8431.2372）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1596">*Version 1708 (Build 8431.2372)*</span></span>

<span data-ttu-id="2ddd8-1597">这是自 2018 年 1 月起就已发布的半年频道版本。2019 年 3 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1808，内部版本 10730.20280）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1597">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1808 (Build 10730.20280) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1598">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1598">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="2ddd8-1599">修复以下问题：使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的外接程序被冻结且不可用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1599">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="2ddd8-1600">版本 1808：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1600">Version 1808: January 8</span></span>
<span data-ttu-id="2ddd8-1601">*版本 1808（内部版本 10730.20264）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1601">*Version 1808 (Build 10730.20264)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="2ddd8-1602">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1602">Access: Feature Updates</span></span>

 - <span data-ttu-id="2ddd8-p274">**利用新图表实现数据的可视化效果：** 从 11 个图表中选择一个图表并将其添加到窗体和报表，更好地实现数据的可视化效果，并做出明智的决策。[了解详细信息](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p274">**Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="2ddd8-1605">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1605">Excel: Feature updates</span></span>
 - <span data-ttu-id="2ddd8-p275">**协作编辑：** 与其他人同时协作处理工作簿。[了解详细信息](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p275">**Collaborative editing:** Work with others at the same time in your workbook. [Learn more](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span></span>
 - <span data-ttu-id="2ddd8-1608">**云文件“自动保存”功能现已默认启用：** 此更改意味着用户无需担心会丢失对 OneDrive 或 SharePoint Online 上存储的文档所做的更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1608">**AutoSave for cloud files is now enabled by default:** This change means users won't have to worry about losing their changes in documents stored on OneDrive or SharePoint Online.</span></span> <span data-ttu-id="2ddd8-1609">更改将自动保存到云中，用户将不再需要显式按 Ctrl + S 或“保存”按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1609">Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button.</span></span> <span data-ttu-id="2ddd8-1610">但是，他们必须理解这种行为上的变化，以免意外更改文档。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1610">However, they will have to understand this change in behavior so they don't make accidental changes to documents.</span></span> <span data-ttu-id="2ddd8-1611">请注意，用户可以使用屏幕顶部的“自动保存”切换来关闭“自动保存”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1611">Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen.</span></span> <span data-ttu-id="2ddd8-1612">建议你向用户通知即将进行的更改，并让他们了解如何充分利用 Office 365 中的新功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1612">We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365.</span></span> <span data-ttu-id="2ddd8-1613">[了解有关“自动保存”的更多信息](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)和[了解有关 IT 管理员应了解的有关“自动保存”的更多信息](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1613">[Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="2ddd8-p277">**改进了单元格和编辑栏编辑：** 现可按 Ctrl+A 选择单元格或编辑栏中的文本。同时还改进了对表情符号和其他复杂字符的支持。[了解详细信息](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p277">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="2ddd8-p278">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的工作簿更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p278">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your workbooks more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="2ddd8-p279">**避免不需要的编辑：** 将工作簿设置为以只读方式打开，避免意外更改。转到“文件”>“信息”>“保护工作簿”>“始终以只读方式打开”</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p279">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="2ddd8-1621">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1621">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="2ddd8-1622">修复了以下问题：在合著会话中，当其他用户对切片器中的数据应用列筛选之后，切片器无法正确更新。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1622">Fixed an issue in coauthoring sessions where a slicer is not properly updated after another user applies a column filter to the data in that slicer.</span></span>
- <span data-ttu-id="2ddd8-1623">修复了以下问题：在合著会话中，如果其中一个用户清除了某个切片器的标题，则会导致合著会话中的其他用户遇到 Excel 崩溃的情况。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1623">Fixed an issue in a coauthoring session where one of the users clears the caption for a slicer and this causes another user in the coauthoring session to experience an Excel crash.</span></span>
- <span data-ttu-id="2ddd8-1624">修复了以下问题：将创建的多个表切片器绑定到同一数据列，然后再删除该数据列时，可能会出现崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1624">Fixed possible crash when creating multiple table slicers bound to the same column of data and then deleting that column of data.</span></span>
- <span data-ttu-id="2ddd8-1625">修复了以下问题：自动调整列宽选项关闭时，如果刷新单元格中包含换行文本的已筛选查询表，Excel 有时会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1625">Fixed an issue where Excel would sometimes crash while refreshing a filtered query table that contains wrapped text in cells when the option to automatically adjust column widths was off.</span></span>
- <span data-ttu-id="2ddd8-1626">修复了以下问题：当切片器中显示的项数改变时，如果在更高版本的 Excel 中打开在 Excel 2007 中保存的切片器，将会触发崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1626">Fixed an issue where slicers saved in Excel 2007 can trigger a crash when opened in newer versions of Excel if the number of items shown in the slicer changes.</span></span>
- <span data-ttu-id="2ddd8-1627">引入了对“获取诊断”按钮的支持，以简化对支持请求的调查。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1627">Introduces support for the Get Diagnostics button to simplify the investigation of support requests.</span></span>
- <span data-ttu-id="2ddd8-1628">已修复以下问题：某些内部版本/版本中不显示 Power Pivot。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1628">Fixed a bug where Power Pivot did not appear in some builds/versions.</span></span>
- <span data-ttu-id="2ddd8-1629">已修复 Excel 中的问题：当用户将鼠标悬停在具有许多定义名称的工作簿中的格式化选项上时，Excel 可能无响应，当在选项中禁用实时预览时，Excel 可能在快速分析工具中无响应。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1629">Fixed the issue in Excel wherein Excel may become unresponsive when the user hovers over formatting options in a workbook with many defined names, and where Excel may become unresponsive in the Quick Analysis tool even when Live Preview was disabled in options.</span></span>
- <span data-ttu-id="2ddd8-p280">我们现在正在调查将 Excel 应用程序窗口从一个桌面移动到另一个桌面时性能缓慢的原因。在此期间，如果你发现了此性能缓慢，可以考虑使用以下变通方法：在“文件选项”对话框的“通用”选项卡中，针对“使用多个显示器时”选择“优化兼容性”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p280">We are currently investigating slow performance when moving the Excel Application Window from one desktop to another. In the meantime, if you do notice this slowness then a work around to consider is to select "Optimize for compatibility" for "When using multiple displays" in the "General" tab in the File Options dialog.</span></span>
- <span data-ttu-id="2ddd8-1632">已修复以下问题：从图表源数据的原始单元格集更改图表源数据时，Excel 可能出现故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1632">Fixed an issue where Excel may crash when changing a chart's source data from its original set of cells.</span></span>
- <span data-ttu-id="2ddd8-1633">已修复以下问题：即使已设置 FullCalcOnLoad 属性，打开时也可能不会进行重新计算。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1633">Fixed an issue where recalculation may not happen on open even if the FullCalcOnLoad property is set.</span></span>  
- <span data-ttu-id="2ddd8-1634">修复了在日期单元格格式中使用日本和历日历时显示错误年份的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1634">Fixed an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
- <span data-ttu-id="2ddd8-p281">将数据导入 Excel 数据模型时，传入的负零值将导致错误。此次修复将此类值导入为零。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p281">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>
- <span data-ttu-id="2ddd8-1637">修复了以下问题：Excel 数据透视表中的组合（或取消组合）操作有时可能会触发故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1637">Fixed an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>
- <span data-ttu-id="2ddd8-1638">修复了制作图表操作可能导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1638">Fixed an issue where charting actions could cause Excel to crash.</span></span>
- <span data-ttu-id="2ddd8-1639">修复了对某些用户无意禁用 Power View 加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1639">Fixed an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
- <span data-ttu-id="2ddd8-1640">修复了在文档恢复期间创建的临时自动恢复文件从未清理的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1640">Fixed an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
- <span data-ttu-id="2ddd8-1641">修复了以下问题：尝试对受保护的工作簿中的文本文件建立新连接时收到“工作簿处于受保护状态，无法更改”的错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1641">Fixed an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.</span></span>
- <span data-ttu-id="2ddd8-1642">修复了以下问题：无法快速打印附加到 Outlook 电子邮件的 Excel 工作簿。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1642">Fixed an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
- <span data-ttu-id="2ddd8-1643">修复了以下问题：单击超链接可能会导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1643">Fixed an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
- <span data-ttu-id="2ddd8-1644">修复了以下问题：使用多维数据集函数导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1644">Fixed an issue where using cube functions causes Excel to crash.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="2ddd8-1645">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1645">Outlook: Feature updates</span></span>
 - <span data-ttu-id="2ddd8-p282">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的邮件更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p282">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
 - <span data-ttu-id="2ddd8-p283">**从配置文件选取器管理配置文件：** 如果启动 Outlook 时使用配置文件选取器，现在可以在无需转到控制面板的情况下进行更改。可通过配置文件选取器进行创建和删除配置文件、更改设置等操作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p283">**Manage Profiles from the Profile Picker:** If you use the Profile Picker when Outlook starts up, you can now make changes without going to the control panel. Create and delete profiles, change settings, all from the Profile Picker.</span></span>
- <span data-ttu-id="2ddd8-1650">**内置辅助功能：** 通过将说明性可选文字添加到图像，使所有人都可访问你的邮件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1650">**Accessibility built right in:** Make your messages accessible to everyone by adding descriptive alt text to your images.</span></span>
- <span data-ttu-id="2ddd8-p284">**Outlook 加载项警告：** Outlook COM 加载项有时会遇到导致 Outlook 其余部分运行速度变慢的问题。这些问题可能是由事件延迟导致的，例如在 Outlook 文件夹之间切换、新邮件的到达、正在打开日历项目等。出现此类问题时，Outlook 将在通知栏中显示一条警告。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p284">**Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.</span></span>
- <span data-ttu-id="2ddd8-1653">**知道将与谁一起开会：** 即使你不是组织者，现在也可以看到其他人对会议请求的响应。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1653">**Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.</span></span>
- <span data-ttu-id="2ddd8-p285">**绝不错过任何提醒：** 设置在工作窗口中弹出的提醒。如果不设置，Outlook 会在任务栏中闪烁，以引起用户注意。[了解详细信息](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p285">**Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
- <span data-ttu-id="2ddd8-p286">**将已删除邮件标记为已读：** 现在可以将任何已删除邮件设置为已读。启用方法为，依次转到“文件”\>“选项”\>“邮件”\>“其他”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p286">**Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.</span></span>
- <span data-ttu-id="2ddd8-p287">**查看 3 个时区：** 需要跨时区安排会议？将多个时区添加到日历，轻松地查看每个人的空闲时间并选择适合所有人的时间。[了解详细信息](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p287">**View three time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span></span>
- <span data-ttu-id="2ddd8-p288">**优化创建组的用户体验：** 已优化创建组的用户体验，使其更现代、更简便。[了解详细信息](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p288">**Refined user experience for creating a group:** We have refined the user experience for the create group to make it look more modern and clutter-free. [Learn more](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1664">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1664">Outlook: Non-Security updates</span></span>
- <span data-ttu-id="2ddd8-1665">修复了导致用户遇到日历同步错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1665">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>
- <span data-ttu-id="2ddd8-1666">修复了导致用户在启动“管理规则和警报”对话框时看到错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1666">Fixed an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="2ddd8-1667">修复了导致用户在使用按流量计费的连接时无法通过 DirectAccess 连接到其邮箱的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1667">Fixed an issue that caused users to be unable to connect to their mailboxes over DirectAccess when using a metered connection.</span></span>
- <span data-ttu-id="2ddd8-1668">修复了导致用户看到“公用文件夹”中保存的免费文本在“受保护的视图”中错误打开的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1668">Fixed an issue that caused users to see free docs stored in Public Folders erroneously open in "Protected View".</span></span>
- <span data-ttu-id="2ddd8-1669">修复了导致用户在转发带有内嵌附件的项目时意外看到附件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1669">Fixed an issue that caused users to see unexpected attachments when forwarding items with inline attachments.</span></span>
- <span data-ttu-id="2ddd8-1670">修复了导致 OFT 文件在作为附件发送之后呈现效果欠佳的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1670">Fixed an issue that caused OFT files to render poorly after being sent as an attachment.</span></span>
- <span data-ttu-id="2ddd8-1671">修复了导致部分使用加载项的用户在向共享日历添加会议时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1671">Fixed an issue that caused some add in users to experience crashes when adding a meeting to a shared calendar.</span></span>
- <span data-ttu-id="2ddd8-1672">修复了导致用户在打开“对话历史记录”文件夹时发生挂机的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1672">Fixed an issue that caused users to experience hangs when opening the Conversation History folder.</span></span>
- <span data-ttu-id="2ddd8-1673">修复了以下问题：如果将系统语言切换为日语并且尝试将日语字符键入 VBA IDE，在 Outlook 中加载时，可能会冻结。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1673">Fixed an issue where if you switch the system language to Japanese and attempt to type Japanese characters into the VBA IDE when loaded within Outlook, it freezes.</span></span>
- <span data-ttu-id="2ddd8-1674">修复了切换到发件箱或已发送邮件文件夹会导致 Outlook 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1674">Fixed an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
- <span data-ttu-id="2ddd8-1675">修复了当会议正文或附件更改时，所有与会者都会收到会议更新（而不是向与会者发送会议更新）属于可选项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1675">Fixed an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
- <span data-ttu-id="2ddd8-1676">修复了由于 User-Agent 字符串的更改，导致用户无法连接到 EWS 和 REST 终结点的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1676">Fixed an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>
- <span data-ttu-id="2ddd8-1677">修复了以下问题：对与会者更新的会议地点显示旧位置，而不是新位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1677">Fixed an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
- <span data-ttu-id="2ddd8-1678">修复了以下问题：用户在阅读窗格中预览附件时看到错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1678">Fixed an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
- <span data-ttu-id="2ddd8-1679">修复了以下问题：在用户撰写电子邮件期间，Outlook 将显示名称解析为电子邮件地址时发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1679">Fixed an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
- <span data-ttu-id="2ddd8-1680">修复了以下问题：一些用户没有收到租户管理员已启用的支持功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1680">Fixed an issue where some users don't receive support features that have been enabled by their tenant admin.</span></span>

### <a name="onenote-non-security-updates"></a><span data-ttu-id="2ddd8-1681">OneNote：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1681">OneNote: Non-security updates</span></span> 

- <span data-ttu-id="2ddd8-1682">修复了涉及同步和导航到已删除分区时可能出现的稳定性问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1682">Fixed a stability issue that can occur involving sync and navigating to a deleted section.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="2ddd8-1683">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1683">PowerPoint: Feature updates</span></span> 
- <span data-ttu-id="2ddd8-1684">**云文件“自动保存”功能现已默认启用：** 此更改意味着用户无需担心会丢失对 OneDrive 或 SharePoint Online 上存储的文档所做的更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1684">**AutoSave for cloud files is now enabled by default:** This change means users won't have to worry about losing their changes in documents stored on OneDrive or SharePoint Online.</span></span> <span data-ttu-id="2ddd8-1685">更改将自动保存到云中，用户将不再需要显式按 Ctrl + S 或“保存”按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1685">Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button.</span></span> <span data-ttu-id="2ddd8-1686">但是，他们必须理解这种行为上的变化，以免意外更改演示文稿。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1686">However, they will have to understand this change in behavior so they don't make accidental changes to presentations.</span></span> <span data-ttu-id="2ddd8-1687">请注意，用户可以使用屏幕顶部的“自动保存”切换来关闭“自动保存”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1687">Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen.</span></span> <span data-ttu-id="2ddd8-1688">建议你向用户通知即将进行的更改，并让他们了解如何充分利用 Office 365 中的新功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1688">We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365.</span></span> <span data-ttu-id="2ddd8-1689">[了解有关“自动保存”的更多信息](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)和[了解有关 IT 管理员应了解的有关“自动保存”的更多信息](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1689">[Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="2ddd8-p290">**改进了单元格和编辑栏编辑：** 现可按 Ctrl+A 选择单元格或编辑栏中的文本。同时还改进了对表情符号和其他复杂字符的支持。[了解详细信息](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p290">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="2ddd8-p291">**转换墨迹：** 获取自由曲线备注和绘图，并将它们转换为可读文本和清晰形状，以创建完善的演示文稿。[了解详细信息](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p291">**Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span></span>
- <span data-ttu-id="2ddd8-p292">**改进了 SVG 支持：** 可以插入应用了筛选器的 SVG。[了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p292">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="2ddd8-p293">**使用手写笔为幻灯片添加标题：** 使用手写笔撰写标题，然后 PowerPoint 会将它转换为文本。[了解更多](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p293">**Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="2ddd8-p294">**避免不需要的编辑：** 将工作簿设置为以只读方式打开，避免意外更改。转到“文件”>“信息”>“保护工作簿”>“始终以只读方式打开”</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p294">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>
- <span data-ttu-id="2ddd8-p295">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使演示文稿更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p295">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your presentations more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>


### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="2ddd8-1703">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1703">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="2ddd8-1704">修复了以下问题：保存包含 ActiveX 内容的文件时，文件可能损坏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1704">Fixed an issue of potential file corruptions when saving files with ActiveX content.</span></span>
- <span data-ttu-id="2ddd8-1705">修复了表格显示不正常并带有粗边框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1705">Fixed an issue where tables are rendered incorrectly with thick borders.</span></span>
- <span data-ttu-id="2ddd8-1706">修复了以下问题：更改 Shape.Visibile 属性时，可能会发生潜在故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1706">Fixed an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
- <span data-ttu-id="2ddd8-1707">修复了以下问题：无法合并合著文档中的更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1707">Fixed an issue where changes in co-authored documents fail to merge.</span></span>
- <span data-ttu-id="2ddd8-1708">修复了以下问题：包含 ActiveX 控件的文档会导致合著失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1708">Fixed an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>
- <span data-ttu-id="2ddd8-1709">修复了在形状中使用拼写更正导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1709">Fixed an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>
- <span data-ttu-id="2ddd8-1710">修复了从 SharePoint Online 打开文件时 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1710">Fixed an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
- <span data-ttu-id="2ddd8-1711">修复了当自动保存处于打开状态时，恢复窗格错误打开的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1711">Fixed an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
- <span data-ttu-id="2ddd8-1712">修复了不显示登录，从而阻止用户访问文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1712">Fixed an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>
- <span data-ttu-id="2ddd8-1713">修复了以下问题：多个用户在同一个演示文稿中进行共同创作导致幻灯片母板复制不正确。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1713">Fixed an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
- <span data-ttu-id="2ddd8-1714">修复了以下问题：打开保存在 OneDrive 上的文件导致 PowerPoint 在退出受保护的视图时出现故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1714">Fixed an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="2ddd8-1715">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1715">Project: Feature updates</span></span> 
- <span data-ttu-id="2ddd8-1716">**冲刺 (sprint) 管理：** 快速添加、更新或删除敏捷冲刺 (sprint)。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1716">**Sprint management:** Quickly add, update, or delete agile sprints.</span></span>
- <span data-ttu-id="2ddd8-1717">**任务板筛选：** 通过筛选主要资源或摘要任务来简化任务板。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1717">**Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.</span></span>
- <span data-ttu-id="2ddd8-1718">**在任务板中设置完成百分比：** 为每列都选择一个完成百分比，再通过拖放操作来更新任务完成进度。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1718">**Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.</span></span>
- <span data-ttu-id="2ddd8-1719">**冲刺 (sprint) 导航：** 从一个冲刺 (sprint) 视图切换到另一个，并在两个冲刺 (sprint) 视图之间快速移动任务。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1719">**Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.</span></span>
- <span data-ttu-id="2ddd8-p296">**管理冲刺 (sprint) 的新方法：** 采用敏捷方法来处理任务板。转到管理冲刺 (sprint) ，随着你的项目演进添加和删除冲刺 (sprint)。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p296">**A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.</span></span>
- <span data-ttu-id="2ddd8-p297">**最近保存位置有条理：** Project 通过可不断扩充的列表列出了其他项目的保存位置。准备保存项目时，只需选择最近保存位置之一，即可继续工作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p297">**Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="2ddd8-1724">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1724">Project: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1725">修复了与 Project 中新增委内瑞拉货币支持相关的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1725">Fixed an issue around supporting a new Venezuelan currency in Project.</span></span>
- <span data-ttu-id="2ddd8-1726">修复了以下问题：使用连接到外部监视器的 Surface 4 时，Project 可能会挂机。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1726">Fixed an issue where Project may hang when using a Surface 4 that is connected to an external monitor.</span></span>
- <span data-ttu-id="2ddd8-1727">修复了以下问题：将项目保存为 XML 格式时，Project 可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1727">Fixed an issue where Project may crash when saving the project to the XML format.</span></span>
- <span data-ttu-id="2ddd8-1728">修复了以下问题：编辑某个资源的日历之后，企业资源自定义字段可能会被删除。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1728">Fixed an issue where enterprise resource custom fields may be deleted after editing a resource's calendar.</span></span>
- <span data-ttu-id="2ddd8-1729">修复了导致用户在搜索韩语显示名称时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1729">Fixed an issue that caused users to experience crashes when searching for Korean display names.</span></span>
- <span data-ttu-id="2ddd8-1730">修复了以下问题：通过主项目的上下文处理子项目时，无法保存子项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1730">Fixed an issue where you are blocked from saving a sub project when working with them through the context of a master project.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="2ddd8-1731">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1731">Word: Feature updates</span></span>
- <span data-ttu-id="2ddd8-1732">**云文件“自动保存”功能现已默认启用：** 此更改意味着用户无需担心会丢失对 OneDrive 或 SharePoint Online 上存储的文档所做的更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1732">**AutoSave for cloud files is now enabled by default:** This change means users won't have to worry about losing their changes in documents stored on OneDrive or SharePoint Online.</span></span> <span data-ttu-id="2ddd8-1733">更改将自动保存到云中，用户将不再需要显式按 Ctrl + S 或“保存”按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1733">Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button.</span></span> <span data-ttu-id="2ddd8-1734">但是，他们必须理解这种行为上的变化，以免意外更改演示文稿。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1734">However, they will have to understand this change in behavior so they don't make accidental changes to presentations.</span></span> <span data-ttu-id="2ddd8-1735">请注意，用户可以使用屏幕顶部的“自动保存”切换来关闭“自动保存”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1735">Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen.</span></span> <span data-ttu-id="2ddd8-1736">建议你向用户通知即将进行的更改，并让他们了解如何充分利用 Office 365 中的新功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1736">We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365.</span></span> <span data-ttu-id="2ddd8-1737">[了解有关“自动保存”的更多信息](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)和[了解有关 IT 管理员应了解的有关“自动保存”的更多信息](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1737">[Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="2ddd8-p299">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的文档更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p299">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your documents more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="2ddd8-p300">**改进了 SVG 支持：** 可以插入应用了筛选器的 SVG。[了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p300">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-1742">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1742">Word: Non-Security updates</span></span>
- <span data-ttu-id="2ddd8-1743">修复了导致出现内存不足消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1743">Fix an issue that causes an insufficient memory message to appear.</span></span>
- <span data-ttu-id="2ddd8-1744">修复了阻止某些用户打开由其他组织中的人员与其共享的受 IRM 保护的文档和电子邮件的一系列问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1744">Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.</span></span>
- <span data-ttu-id="2ddd8-1745">修复了一些性能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1745">Fixed some performance issues.</span></span>
- <span data-ttu-id="2ddd8-1746">提高打开性能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1746">Improve open performance.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="2ddd8-1747">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1747">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="2ddd8-p301">修复了与 TLS 1.2 支持相关的问题。（注意：这是 4 月 10 日说明中提到的同一个修补程序。在这里作为 9 月汇总的一部分再次提到。）</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p301">Fix an issue related to TLS 1.2 support. (Note: This is the same fix that was mentioned in the April 10 notes and is mentioned here again as part of the September rollup.)</span></span>
- <span data-ttu-id="2ddd8-1750">修复了在会议中通过选择“Skype 通话”来添加用户导致出错的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1750">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
- <span data-ttu-id="2ddd8-1751">如果 Skype 会议室已被添加为位置且会议已包含 Teams 会议协调人，则删除要求用户向会议添加 Skype 协调人的提示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1751">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
- <span data-ttu-id="2ddd8-1752">修复了以下问题：即使将 UseLocationForE911Only 设置为 true，位置也会被填充。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1752">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
- <span data-ttu-id="2ddd8-1753">修复了以下问题：通过“使用会议中心呼叫”选项邀请名单中的用户时，Skype for Business 挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1753">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
- <span data-ttu-id="2ddd8-1754">修复了以下问题：创建 Skype for Business 会议期间，终端服务器上运行的 Outlook 冻结。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1754">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
- <span data-ttu-id="2ddd8-1755">将 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的默认值更改为 TRUE。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1755">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="2ddd8-1756">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1756">Visio: Feature updates</span></span>
- <span data-ttu-id="2ddd8-1757">**保持图表和源同步：** 在 Visio 中编辑数据可视化工具图表时，可以视需要根据最新图表内容，更新链接的 Excel 源数据。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1757">**Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.</span></span>
- <span data-ttu-id="2ddd8-1758">**数据可视化工具审核模板：** 从 Excel 导入内容，并创建财务交易记录、库存管理等的审计图。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1758">**Data Visualizer audit template:** Import content from Excel and create audit diagrams for financial transactions, inventory management, and more.</span></span>
- <span data-ttu-id="2ddd8-1759">**入门图表：** 组织结构图、头脑风暴和 SDL 模板具有新的入门图表，让你能够快速使用起来。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1759">**Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.</span></span>
- <span data-ttu-id="2ddd8-p302">**利用 Visio 形状生成 Word 文档：** 自动向 Word 文档添加关系图内容（包括形状和元数据）。然后对文档进行自定义，以创建过程准则和操作手册。[了解详细信息](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p302">**Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>

### <a name="office-suite-security-update"></a><span data-ttu-id="2ddd8-1763">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1763">Office Suite: Security update</span></span>

- <span data-ttu-id="2ddd8-p303">
  \*\*出于安全考虑，禁止在 Office 中激活 Flash、Silverlight 和 Shockwave 控件：\*\* 出于安全考虑，Windows 上的 Microsoft Office for Office 365 新版本阻止激活 Flash、Silverlight 和 Shockwave 控件。可通过[此处](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和[此处](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1)了解详细信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p303">**Flash, Silverlight and Shockwave controls blocked from activating in Office for security reasons:** For security reasons new builds of Microsoft Office for Office 365 on Windows block activation of Flash, Silverlight, and Shockwave controls. Learn more [here](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) and [here](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1).</span></span>
 
### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1766">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1766">Office Suite: Non-Security updates</span></span>
- <span data-ttu-id="2ddd8-1767">修复了在某些场景中导致更新安装所用时间过长的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1767">Fixed an issue that caused update install to take a long time in certain scenarios.</span></span>
- <span data-ttu-id="2ddd8-1768">修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1768">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
- <span data-ttu-id="2ddd8-1769">修复了一些性能问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1769">Fixed some performance issues.</span></span>


## <a name="version-1803-january-8"></a><span data-ttu-id="2ddd8-1770">版本 1803：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1770">Version 1803: January 8</span></span>
<span data-ttu-id="2ddd8-1771">*版本 1803（内部版本 9126.2351）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1771">*Version 1803 (Build 9126.2351)*</span></span>

<span data-ttu-id="2ddd8-1772">*这是自 2018 年 7 月起就已发布的半年频道版本。2019 年 9 月前，此版本会继续获得支持，并接收安全更新。不过，新版半年频道（即版本 1808）现已推出，其中包含新增功能、安全更新和非安全更新。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1772">*This is the Semi-Annual Channel release that's been available since July 2018. It will continue to be supported and receive security updates until September 2019. But, a new Semi-Annual Channel release is now available — Version 1808 — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="2ddd8-1773">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1773">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="2ddd8-1774">修复了确保 Office 应用程序之间 LinkedIn 选项的功能奇偶一致性的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1774">Fixed an issue to ensure feature parity of the LinkedIn option between Office applications.</span></span>

## <a name="version-1803-december-11"></a><span data-ttu-id="2ddd8-1775">版本 1803：12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1775">Version 1803: December 11</span></span>
<span data-ttu-id="2ddd8-1776">*版本 1803（内部版本 9126.2336）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1776">*Version 1803 (Build 9126.2336)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1777">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1777">Excel: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1778">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1778">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1779">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1779">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1780">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1780">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1781">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1781">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1782">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1782">Outlook: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1783">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1783">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="2ddd8-1784">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1784">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1785">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1785">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 


### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1786">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1786">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1787">修复了导致 Outlook 在更新某些联系人字段时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1787">Fixed an issue that caused Outlook to close unexpectedly when updating certain contact fields.</span></span>
- <span data-ttu-id="2ddd8-1788">解决了导致用户在启动“管理规则和警报”对话框时看到错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1788">Addresses an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="2ddd8-1789">解决了导致 Outlook 用户在运行某些外接程序时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1789">Addresses an issue that caused Outlook users to experience crashes while running some add ins.</span></span>


## <a name="version-1708-december-11"></a><span data-ttu-id="2ddd8-1790">版本 1708：12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1790">Version 1708: December 11</span></span>
<span data-ttu-id="2ddd8-1791">*版本 1708（内部版本 8431.2351）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1791">*Version 1708 (Build 8431.2351)*</span></span>

<span data-ttu-id="2ddd8-1792">*这是自 2018 年 1 月起就已发布的半年频道版本。2019 年 3 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1803，内部版本 16.0.9126.2336）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1792">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2336) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1793">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1793">Excel: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1794">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1794">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1795">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1795">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1796">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1796">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1797">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1797">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1798">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1798">Outlook: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1799">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1799">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="2ddd8-1800">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1800">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1801">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1801">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1802">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1802">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="2ddd8-1803">修复了导致 Outlook 在更新某些联系人字段时意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1803">Fixed an issue that caused Outlook to close unexpectedly when updating certain contact fields.</span></span>
- <span data-ttu-id="2ddd8-1804">解决了导致用户在启动“管理规则和警报”对话框时看到错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1804">Addresses an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="2ddd8-1805">解决了导致 Outlook 用户在运行某些外接程序时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1805">Addresses an issue that caused Outlook users to experience crashes while running some add ins.</span></span>


## <a name="version-1803-november-13"></a><span data-ttu-id="2ddd8-1806">版本 1803：11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1806">Version 1803: November 13</span></span>
<span data-ttu-id="2ddd8-1807">*版本 1803（内部版本 9126.2315）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1807">*Version 1803 (Build 9126.2315)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1808">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1808">Excel: Security updates</span></span>

-   <span data-ttu-id="2ddd8-1809">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1809">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1810">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1810">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1811">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1811">Outlook: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1812">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1812">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1813">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1813">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1814">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1814">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1815">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1815">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1816">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1816">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1817">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1817">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="2ddd8-1818">Project：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1818">Project: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1819">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1819">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-1820">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1820">Word: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1821">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1821">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="2ddd8-1822">Skype for Business：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1822">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1823">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546)：Microsoft Skype for Business 拒绝服务漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1823">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1824">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1824">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="2ddd8-1825">此更改允许用户将物理文件“全部保存”到网络共享，包括映射网络驱动器。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1825">This change allows users to Save All for physical files to a network share, including a mapped network drive.</span></span> 

## <a name="version-1708-november-13"></a><span data-ttu-id="2ddd8-1826">版本 1708：11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1826">Version 1708: November 13</span></span>
<span data-ttu-id="2ddd8-1827">*版本 1708（内部版本 8431.2329）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1827">*Version 1708 (Build 8431.2329)*</span></span>

<span data-ttu-id="2ddd8-1828">*这是自 2018 年 1 月起就已发布的半年频道版本。2019 年 3 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1803，内部版本 16.0.9126.2315）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1828">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2315) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1829">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1829">Excel: Security updates</span></span>

-   <span data-ttu-id="2ddd8-1830">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1830">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1831">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1831">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1832">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1832">Outlook: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1833">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1833">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1834">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1834">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1835">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1835">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1836">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1836">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1837">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1837">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1838">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1838">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="2ddd8-1839">Project：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1839">Project: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1840">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1840">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-1841">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1841">Word: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1842">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1842">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="2ddd8-1843">Skype for Business：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1843">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="2ddd8-1844">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546)：Microsoft Skype for Business 拒绝服务漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1844">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-1845">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1845">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="2ddd8-1846">此更改允许用户将物理文件“全部保存”到网络共享，包括映射网络驱动器。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1846">This change allows users to Save All for physical files to a network share, including a mapped network drive.</span></span> 


## <a name="version-1803-october-9"></a><span data-ttu-id="2ddd8-1847">版本 1803：10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1847">Version 1803: October 9</span></span>
<span data-ttu-id="2ddd8-1848">*版本 1803（内部版本 9126.2295）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1848">*Version 1803 (Build 9126.2295)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1849">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1849">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1850">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1850">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1851">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1851">Outlook: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1852">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1852">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="2ddd8-1853">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1853">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1854">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1854">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-1855">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1855">Word: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1856">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1856">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1857">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1857">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-1858">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1858">Office suite: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1859">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 组件远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1859">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-1860">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1860">Office Suite: Non-Security updates</span></span>
-   <span data-ttu-id="2ddd8-1861">修复了以下问题：即使通过辅助功能和性能设置关闭动画，应用仍显示动画。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1861">Fixed issue of apps showing animations despite turning off animations through accessibility and performance settings.</span></span>
-   <span data-ttu-id="2ddd8-1862">修复了以下问题：使用荧光笔绘图工具时，背景变成空白。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1862">Fixed issue of background turning blank when using highlighter drawing tool.</span></span>

## <a name="version-1708-october-9"></a><span data-ttu-id="2ddd8-1863">版本 1708：10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1863">Version 1708: October 9</span></span>
<span data-ttu-id="2ddd8-1864">*版本 1708（内部版本 8431.2316）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1864">*Version 1708 (Build 8431.2316)*</span></span>

<span data-ttu-id="2ddd8-1865">*这是自 2018 年 1 月起就已发布的半年频道版本。2019 年 3 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1803，内部版本 16.0.9126.2282）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1865">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2282) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1866">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1866">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1867">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1867">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1868">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1868">Outlook: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1869">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1869">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="2ddd8-1870">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1870">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1871">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1871">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-1872">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1872">Word: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1873">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1873">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1874">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1874">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-1875">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1875">Office suite: Security updates</span></span> 
-   <span data-ttu-id="2ddd8-1876">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 组件远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1876">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 


## <a name="version-1803-september-11"></a><span data-ttu-id="2ddd8-1877">版本 1803：9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1877">Version 1803: September 11</span></span>
<span data-ttu-id="2ddd8-1878">*版本 1803（内部版本 9126.2282）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1878">*Version 1803 (Build 9126.2282)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1879">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1879">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1880">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1880">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1881">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1881">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-1882">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1882">Word: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1883">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430)：Word PDF 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1883">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-1884">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1884">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1885">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332)：Win32k Graphics 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1885">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>


## <a name="version-1708-september-11"></a><span data-ttu-id="2ddd8-1886">版本 1708：9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1886">Version 1708: September 11</span></span>
<span data-ttu-id="2ddd8-1887">*版本 1708（内部版本 8431.2309）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1887">*Version 1708 (Build 8431.2309)*</span></span>

<span data-ttu-id="2ddd8-1888">*这是自 2018 年 1 月起就已发布的半年频道版本。2019 年 3 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1803，内部版本 16.0.9126.2282）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1888">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2282) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1889">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1889">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1890">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1890">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1891">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1891">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-1892">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1892">Word: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1893">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430)：Word PDF 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1893">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-1894">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1894">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1895">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332)：Win32k Graphics 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1895">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>


## <a name="version-1803-august-14"></a><span data-ttu-id="2ddd8-1896">版本 1803：8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1896">Version 1803: August 14</span></span>
<span data-ttu-id="2ddd8-1897">*版本 1803（内部版本 9126.2275）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1897">*Version 1803 (Build 9126.2275)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="2ddd8-1898">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1898">Access: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1899">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1899">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1900">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1900">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1901">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1901">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1902">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1902">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1903">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1903">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1904">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1904">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1905">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1905">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-1906">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1906">Office Suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1907">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1907">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 


## <a name="version-1708-august-14"></a><span data-ttu-id="2ddd8-1908">版本 1708：8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1908">Version 1708: August 14</span></span>
<span data-ttu-id="2ddd8-1909">*版本 1708（内部版本 8431.2299）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1909">*Version 1708 (Build 8431.2299)*</span></span>

<span data-ttu-id="2ddd8-1910">*这是自 2018 年 1 月起就已发布的半年频道版本。2019 年 3 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1803，内部版本 16.0.9126.2275）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1910">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 16.0.9126.2275) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="2ddd8-1911">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1911">Access: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1912">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1912">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1913">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1913">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1914">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1914">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1915">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1915">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1916">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1916">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-1917">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1917">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1918">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1918">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-1919">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1919">Office Suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1920">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1920">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 


## <a name="version-1803-july-10"></a><span data-ttu-id="2ddd8-1921">版本 1803：7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1921">Version 1803: July 10</span></span>
<span data-ttu-id="2ddd8-1922">*版本 1803（内部版本 9126.2259）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1922">*Version 1803 (Build 9126.2259)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="2ddd8-1923">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1923">Access: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1924">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1924">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1925">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1925">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="2ddd8-1926">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1926">Access: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-1927">修复了以下问题：打开 Access 运行时应用程序 (.accde file) 导致“无法识别此数据库的格式”错误消息出现，且应用程序无法打开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1927">Fix an issue where opening an Access runtime application (.accde file) results in a "This database is in an unrecognized format" error message and the application won’t open.</span></span>
-   <span data-ttu-id="2ddd8-1928">修复了以下问题：尝试选择文本框或组合框中的文本时，似乎会选择所有文本，而不是指示的选择内容。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1928">Fix an issue where attempting to select text in a text box or combo box appears to select all the text, rather than the indication selection.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="2ddd8-1929">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1929">Excel: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-p304">**Microsoft Translator：** 使用 Microsoft Translator 将字词、短语或句子翻译成其他语言。可以在功能区的“审阅”选项卡中执行此操作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p304">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="2ddd8-1932">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1932">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="2ddd8-1933">**取消选中单元格：** 在工作表中进行选择，并取消选中不小心单击的单元格，而不必重新开始。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1933">**Deselect cells:** Make selections in your worksheet and deselect cells that you accidentally clicked without having to start over.</span></span>
-   <span data-ttu-id="2ddd8-1934">**快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1934">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="2ddd8-p305">**数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p305">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="2ddd8-p306">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p306">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="2ddd8-p307">**3D 模型：** 使用 3D 增强工作簿的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p307">**3D models:** Use 3D to increase the visual and creative impact of your workbooks.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="2ddd8-1942">**新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1942">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="2ddd8-p308">**共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p308">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="2ddd8-p309">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p309">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="2ddd8-p310">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p310">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="2ddd8-1952">**按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1952">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="2ddd8-p311">**触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p311">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-1955">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1955">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-1956">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1956">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1957">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1957">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1958">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1958">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1959">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1959">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1960">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1960">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1961">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1961">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>
-   <span data-ttu-id="2ddd8-1962">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1962">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1963">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1963">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1964">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1964">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1965">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1965">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1966">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1966">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="2ddd8-1967">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1967">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1968">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1968">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-1969">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1969">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>
-   <span data-ttu-id="2ddd8-1970">[公告 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1970">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="2ddd8-1971">Excel：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1971">Excel: Non-security updates</span></span>

-   <span data-ttu-id="2ddd8-1972">修复了在日期单元格格式中使用日本和历日历时显示错误年份的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1972">Fix an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
-   <span data-ttu-id="2ddd8-p312">将数据导入 Excel 数据模型时，传入的负零值将导致错误。此次修复将此类值导入为零。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p312">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>
-   <span data-ttu-id="2ddd8-1975">修复了以下问题：Excel 数据透视表中的组合（或取消组合）操作有时可能会触发故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1975">Fix an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>
-   <span data-ttu-id="2ddd8-1976">修复了制作图表操作可能导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1976">Fix an issue where charting actions could cause Excel to crash.</span></span>
-   <span data-ttu-id="2ddd8-1977">修复了对某些用户无意禁用 Power View 加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1977">Fix an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
-   <span data-ttu-id="2ddd8-1978">修复了在文档恢复期间创建的临时自动恢复文件从未清理的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1978">Fix an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
-   <span data-ttu-id="2ddd8-1979">修复了从 SharePoint Online 打开文件时 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1979">Fix an issue where Excel crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="2ddd8-1980">修复了以下问题：无法快速打印附加到 Outlook 电子邮件的 Excel 工作簿。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1980">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="2ddd8-1981">修复了以下问题：单击超链接可能会导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1981">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="2ddd8-1982">修复了以下问题：使用多维数据集函数导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1982">Fix an issue where using cube functions causes Excel to crash.</span></span>
-   <span data-ttu-id="2ddd8-1983">修复了打印或打印预览只打印或显示工作表部分，内容被工作表上的切片器截断的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1983">Fix a problem where print or print preview only prints or displays a portion of the worksheet, with the content being truncated at a slicer on the worksheet.</span></span>
-   <span data-ttu-id="2ddd8-1984">修复了以下问题：在尝试对受保护的工作簿中的文本文件建立新连接时，收到“工作簿处于保护状态，无法更改”错误消息。修复了以下问题：如果编辑语言为日语、中文或韩语，那么当尝试在“主页”选项卡上选择新字体或进行编辑时，Excel 可能会卡住。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1984">Fix an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.Fix an issue where, if your editing language is Japanese, Chinese, or Korean, Excel may freeze when you try to choose a new font on the Home tab or when you edit.</span></span>
-   <span data-ttu-id="2ddd8-1985">修复了以下问题：在最小化 Excel 后打开工作簿时，缺少滚动条。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1985">Fix an issue where the scroll bars are missing when a workbook is opened when Excel is minimized.</span></span>
-   <span data-ttu-id="2ddd8-1986">修复了以下问题：在文件资源管理器中双击文件名打开多个工作簿时，工作簿引用失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1986">Fix an issue where workbook references fail when opening multiple workbooks by double-clicking on the file names in File Explorer.</span></span>
-   <span data-ttu-id="2ddd8-1987">修复了以下问题：以编程方式依次创建数据透视表和刷新导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1987">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="2ddd8-1988">修复了以下问题：以编程方式调用 Workbook.Open() 可能会导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1988">Fix an issue where programmatically calling Workbook.Open() may cause Excel to crash.</span></span>
-   <span data-ttu-id="2ddd8-1989">修复了以下问题：使用宏打开 Office 2007 或更低版本工作簿（.xls 或 .xla）时，用户错误地看到“灾难性故障”错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1989">Fix an issue where the user incorrectly sees a "catastrophic failure" error message when opening an Office 2007 or older workbook (.xls or .xla) with macros.</span></span>
-   <span data-ttu-id="2ddd8-1990">修复了以下问题：Excel 可能会在用户打开关联菜单时发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1990">Fix an issue where Excel might crash when a user opens a context menu.</span></span>
-   <span data-ttu-id="2ddd8-1991">修复了以下问题：当用户尝试在现有的工作簿中插入对象时，用户单击“浏览”导致 Excel 发生故障的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1991">Fix an issue where, when the user tries to insert an object in an existing workbook, Excel crashes when the user clicks Browse.</span></span>
-   <span data-ttu-id="2ddd8-1992">修复了以下问题：如果使用密码保护区域，看不到用于输入密码以解锁区域的对话框。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1992">Fix an issue where, when protecting a range with a password, the dialog box to enter the password to unlock the range isn't visible.</span></span>
-   <span data-ttu-id="2ddd8-1993">修复了以下问题：当文件名包含方括号时，用户无法关闭受保护的视图中的工作簿。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1993">Fix an issue where the user can't close a workbook in protected view when the file name contains square brackets.</span></span>
-   <span data-ttu-id="2ddd8-1994">修复了以下问题：拖动或拖动填充时，工具提示的位置未对齐。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1994">Fix an issue where placement of the tooltip is misaligned when dragging or drag filling.</span></span>
-   <span data-ttu-id="2ddd8-1995">修复了以下问题：使用“文件”\>“另存为”保存工作簿时，包含句点的文件名在文件保存对话框中显示为空白或被截断。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1995">Fix an issue where, when saving a workbook by using File \> Save As, a file name that contains periods appears blank or truncated in the file save dialog.</span></span>
-   <span data-ttu-id="2ddd8-p313">修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p313">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="2ddd8-1998">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1998">Outlook: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-1999">**轻松排序电子邮件：** 感谢提供反馈，我们已为未使用重点收件箱的用户，在邮件列表和未读邮件筛选器上方恢复了排序功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-1999">**Sort your email with ease:** Thanks to your feedback, we've brought back sorting above the message list and the Unread filter for people who don't use Focused Inbox.</span></span>
-   <span data-ttu-id="2ddd8-2000">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，以便可更改其颜色、大小或纹理。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2000">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="2ddd8-2001">**Office 365 群组的改进：** 阅读和回复群组对话比以往更加简便，因为可以双击群组消息，在它自己的窗口中打开消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2001">**Improvements to Office 365 groups:** It’s easier than ever to read and reply to group conversations because you can double-click on a group message to open it in its own window.</span></span>
-   <span data-ttu-id="2ddd8-p314">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p314">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="2ddd8-p315">**3D 模型：** 使用 3D 增强电子邮件的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p315">**3D models:** Use 3D to increase the visual and creative impact of your email.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="2ddd8-2007">**个人资料卡片：** 无论是桌面版、Web 版还是使用移动应用，都显示与人员和群组最相关的详细信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2007">**Profile card:** Shows you the most relevant details about people and groups, whether you’re on the desktop, the web, or using a mobile app.</span></span>
-   <span data-ttu-id="2ddd8-2008">**将约会添加到群组日历中：** 现在无需以电子邮件方式发送会议安排，即可让群组中的所有人都知道你何时离开。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2008">**Add an appointment to a group calendar:** Now you can let everyone in your group know when you’ll be away without sending a meeting in email.</span></span>
-   <span data-ttu-id="2ddd8-2009">**下载云附件：** 将 OneDrive 附件保存或拖放到计算机后，我们会为用户下载文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2009">**Downloading cloud attachments:** When you save or drag and drop OneDrive attachments to your computer, we download the file for you.</span></span>
-   <span data-ttu-id="2ddd8-p316">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p316">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="2ddd8-p317">**重点收件箱：** 收件箱分为两个选项卡 – 重点和其他。邮件根据邮件内容以及最常与之交互的联系人进行排序。 [了解更多](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p317">**Focused Inbox:** The Inbox is separated into two tabs – Focused and Other. Messages are sorted based on the content of the message and who you interact with most often. [Learn more](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span></span>
-   <span data-ttu-id="2ddd8-2017">**快速访问最常用的组：** 最常与之交互的组现在显示在“文件夹”窗格的“组”下方列表的顶部。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2017">**Quickly access the groups you use most:** Groups you're most likely to interact with now appear at the top of the list under Groups in the Folder pane.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2018">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2018">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2019">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2019">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2020">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2020">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2021">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2021">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2022">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2022">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2023">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2023">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2024">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2024">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2025">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2025">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2026">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 篡改漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2026">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-2027">Outlook：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2027">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2028">修复了切换到发件箱或已发送邮件文件夹会导致 Outlook 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2028">Fix an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
-   <span data-ttu-id="2ddd8-2029">修复了当会议正文或附件更改时，所有与会者都会收到会议更新（而不是向与会者发送会议更新）属于可选项的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2029">Fix an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
-   <span data-ttu-id="2ddd8-2030">修复了由于 User-Agent 字符串的更改，导致用户无法连接到 EWS 和 REST 终结点的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2030">Fix an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>
-   <span data-ttu-id="2ddd8-2031">修复了以下问题：对与会者更新的会议地点显示旧位置，而不是新位置。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2031">Fix an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
-   <span data-ttu-id="2ddd8-2032">修复了以下问题：用户在阅读窗格中预览附件时看到错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2032">Fix an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
-   <span data-ttu-id="2ddd8-2033">修复了以下问题：在用户撰写电子邮件期间，Outlook 将显示名称解析为电子邮件地址时发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2033">Fix an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
-   <span data-ttu-id="2ddd8-2034">修复了以下问题：一些用户没有收到租户管理员已启用的支持功能</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2034">Fix an issue where some users don't receive support features that have been enabled by their tenant admin</span></span>
-   <span data-ttu-id="2ddd8-2035">修复了以下问题：在搜索范围为全部邮箱时，搜索失败且看到“找不到匹配”错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2035">Fix an issue where search fails with “No matches found” when search is scoped to All Mailboxes.</span></span>
-   <span data-ttu-id="2ddd8-2036">修复了以下问题：如果在使用可访问事件观察程序 (AccEvent.exe) 进行监视时切换文件夹，导致 Outlook 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2036">Fix an issue where, when monitoring using Accessible Event Watcher (AccEvent.exe), Outlook crashes when switching folders.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="2ddd8-2037">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2037">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-p318">**Microsoft Translator：** 使用 Microsoft Translator 将字词、短语或句子翻译成其他语言。可以在功能区的“审阅”选项卡中执行此操作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p318">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="2ddd8-2040">**3D 动画：** 通过添加轻轻摇摆、跳跃和旋转等动画效果，让你的 3D 模型活起来。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2040">**3D animations:** Bring your 3D models to life with animations such as swinging gently or jumping and turning.</span></span>
-   <span data-ttu-id="2ddd8-2041">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2041">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="2ddd8-2042">**修订跟踪信息漫游：** 突出显示其他人修改的共享幻灯片的已读/未读状态，现在存储在漫游服务中（而不是存储在用户本地计算机上），这样就可以跨多个设备或平台同步此类信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2042">**Roaming of revision tracking info:** The read/unread status for highlighting shared slides that have been modified by others is now stored in a roaming service (instead of on the user's local computer) so that this information can be synchronized across multiple devices or platforms.</span></span>
-   <span data-ttu-id="2ddd8-2043">**快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2043">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="2ddd8-p319">**数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p319">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="2ddd8-p320">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p320">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="2ddd8-p321">**使用数控笔执行幻灯片放映：** 使用 Surface 触控笔或其他带有蓝牙按钮的触笔切换幻灯片。需要安装 Windows 10 Fall Creators Update。 [了解更多](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p321">**Run a slide show with your digital pen:** Use your Surface Pen, or other pen with a Bluetooth button, to advance your slides. Windows 10 Fall Creators Update is required. [Learn more](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span></span>
-   <span data-ttu-id="2ddd8-p322">**3D 模型：** 使用 3D 增强演示文稿的视觉效果和创意效果。使用切换效果（例如可在幻灯片之间打造电影动画效果的“平滑”）使演示文稿中的 3D 模型栩栩如生。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p322">**3D models:** Use 3D to increase the visual and creative impact of your presentations. Bring 3D models to life in your presentations with transitions like Morph that create cinematic animations between slides. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="2ddd8-2054">**新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2054">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="2ddd8-p323">**共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p323">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="2ddd8-p324">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p324">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="2ddd8-2060">**修订突出显示：** 突出显示由其他用户已修改的幻灯片。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2060">**Revision highlighting:** Slides that have been modified by other users are highlighted.</span></span>
-   <span data-ttu-id="2ddd8-2061">**离开期间：** PowerPoint 显示自你上次访问以后对共享演示文稿进行过编辑的用户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2061">**While you were away:** PowerPoint shows you who edited your shared presentation since your last visit.</span></span>
-   <span data-ttu-id="2ddd8-2062">**设计器改进：** 现在，设计器会推荐有关项目符号列表中日程表的设计灵感。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2062">**Designer improvement:** Designer now recommends design ideas for timelines in a bulleted list.</span></span>
-   <span data-ttu-id="2ddd8-p325">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p325">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="2ddd8-2067">**按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2067">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="2ddd8-p326">**触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p326">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="2ddd8-2070">**设计器改进：** 设计器现在为幻灯片中添加的图表提供设计灵感建议。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2070">**Designer improvement:** Designer now recommends design ideas for charts added to your slides.</span></span>
-   <span data-ttu-id="2ddd8-p327">**快速启动：** 自动生成大纲，帮助用户开始研究他们所选的主题。[了解详细信息](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p327">**QuickStarter:** Automatically builds an outline to help users get started researching a subject of their choosing. [Learn more](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span></span>
-   <span data-ttu-id="2ddd8-p328">**数字标尺：** 在具有触摸屏的设备上，转到“绘图”\>“标尺”，然后使用笔或手指绘制直线或对齐一组对象。 [了解更多](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p328">**Digital ruler:** On devices that have touch screens, go to Draw \> Ruler, then use your pen or finger to draw straight lines or to align a set of objects. [Learn more](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span></span>

### <a name="powerpoint-security-updates"></a><span data-ttu-id="2ddd8-2075">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2075">PowerPoint: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2076">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2076">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint Information Disclosure Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="2ddd8-2077">PowerPoint：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2077">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2078">修复了表格显示不正常并带有粗边框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2078">Fix an issue where tables are rendered incorrectly with thick borders.</span></span>
-   <span data-ttu-id="2ddd8-2079">修复了以下问题：更改 Shape.Visibile 属性时，可能会发生潜在故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2079">Fix an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
-   <span data-ttu-id="2ddd8-2080">修复了以下问题：无法合并合著文档中的更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2080">Fix an issue where changes in co-authored documents fail to merge.</span></span>
-   <span data-ttu-id="2ddd8-2081">修复了以下问题：包含 ActiveX 控件的文档会导致合著失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2081">Fix an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>
-   <span data-ttu-id="2ddd8-2082">修复了在形状中使用拼写更正导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2082">Fix an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>
-   <span data-ttu-id="2ddd8-2083">修复了从 SharePoint Online 打开文件时 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2083">Fix an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="2ddd8-2084">修复了当自动保存处于打开状态时，恢复窗格错误打开的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2084">Fix an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
-   <span data-ttu-id="2ddd8-2085">修复了不显示登录，从而阻止用户访问文件的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2085">Fix an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>
-   <span data-ttu-id="2ddd8-2086">修复了以下问题：多个用户在同一个演示文稿中共同创作导致幻灯片母板复制不正确。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2086">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="2ddd8-2087">修复了以下问题：在退出受保护的视图时，打开保存在 OneDrive 上的文件导致 PowerPoint 故障。修复了以下问题：删除文档属性和个人信息导致保存到 SharePoint 失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2087">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.Fix an issue where removing document properties and personal information causes saving to SharePoint to fail.</span></span>
-   <span data-ttu-id="2ddd8-p329">修复了以下问题：引用基于 Flash Player 的 YouTube 嵌入代码，导致打开新窗口来播放视频。旧嵌入代码现已升级为，引用基于 HTML5 的 YouTube 视频，以便正确就地播放这些视频。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p329">Fix an issue where references to Flash Player based YouTube embed codes result in a new window opening to play the video. Old embed codes are now upgraded to reference HTML5 based YouTube videos so that they correctly play in place.</span></span>
-   <span data-ttu-id="2ddd8-p330">修复了以下问题：保存支持同步的文件时，Office 无法对磁盘执行写入操作，但 Office 仍继续将文件上传到 OneDrive。修复此问题后，用户现在会看到错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p330">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="2ddd8-2092">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2092">Project: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-p331">**“任务板”视图：** 在“任务板”视图中，对卡片上的任务进行排序。在任务板上的各栏之间重新排序和移动卡片，就跟在敏捷项目中一样。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p331">**Task Board view:** Sort tasks on cards in the Task Board view. Reorder and move cards between columns on the board just like in Agile projects.</span></span>
-   <span data-ttu-id="2ddd8-p332">**敏捷项目：** 使用积压工作 (backlog)、任务板、冲刺 (sprint) 等管理敏捷项目。支持使用 Scrum 或看板方法。[了解详细信息](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p332">**Agile projects:** Manage your Agile projects using backlogs, task boards, sprints, and more. Both Scrum or Kanban methodologies are supported. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>  
-   <span data-ttu-id="2ddd8-p333">**在规划器中管理任务：** 将项目任务关联到规划器，并为任务创建计划。将任务分解为子任务，添加团队，分配任务，并管理任务板上的工时。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p333">**Manage a task in Planner:** Link a Project task to Planner and create a plan for it. Break the task into subtasks, add a team, assign tasks, and manage the work on a task board.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="2ddd8-2100">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2100">Project: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2101">修复了以下问题：如果使用成本资源对任务进行拆分，则成本资源无法正确更新且成本丢失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2101">Fix an issue where if a task is split with a cost resource, the cost resource isn't correctly updated and the cost is lost.</span></span>
-   <span data-ttu-id="2ddd8-2102">修复了以下问题：“日程表”视图“将现有任务添加到日程表”对话框仅显示第一个摘要任务中的任务。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2102">Fix an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>
-   <span data-ttu-id="2ddd8-2103">修复了以下问题：将 Project Online 或 Project Server 中的主项目另存为 XML 可能会失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2103">Fix an issue where saving as XML may fail for master projects from Project Online or Project Server.</span></span>
-   <span data-ttu-id="2ddd8-2104">修复了以下问题：“日程表”视图“将现有任务添加到日程表”对话框仅显示第一个摘要任务中的任务。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2104">Fix an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>
-   <span data-ttu-id="2ddd8-2105">修复了在日期列使用自动筛选下拉菜单导致 Project 中的所有任务被隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2105">Fix an issue where using the AutoFilter dropdown on a date column causes all tasks in the project to be hidden.</span></span>
-   <span data-ttu-id="2ddd8-2106">修复了在日程表视图中时，当将现有任务添加到日程表时，只有第一个摘要任务中的任务会显示在对话框中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2106">Fix an issue where only tasks from the first summary task show up in the dialog box when adding existing tasks to a timeline when in Timeline view.</span></span>
-   <span data-ttu-id="2ddd8-2107">修复了以下问题：在会话中设置多个基线会将 MOD\_DATE 值设为相同的值。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2107">Fix an issue where setting more than one baseline in a session sets the MOD\_DATE value as the same.</span></span>
-   <span data-ttu-id="2ddd8-2108">修复了以下问题：在“​​保存以共享”会话中删除“实际工时”后，它仍显示在报表中。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2108">Fix an issue where Actual Work is still shown in the reporting tables after being removed in a Save for Sharing session.</span></span>
-   <span data-ttu-id="2ddd8-2109">修复了进行日程安排时在德语版本中使用“星期”日期格式返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2109">Fix an issue in the German language version where using a Weeks date format returns an error when scheduling.</span></span>
-   <span data-ttu-id="2ddd8-2110">修复了在日程安排 Web 部件中编辑完成日期时任务每天停留 8 小时而不随着时间推移的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2110">Fix an issue where, when editing finish dates in Schedule Web Part, tasks stay at 8 hours per day instead of being spread over time.</span></span>
-   <span data-ttu-id="2ddd8-2111">修复了以下问题：在意外位置绘制“进度点形状”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2111">Fix an issue where "Progress point shape" is drawn at an unexpected location.</span></span>
-   <span data-ttu-id="2ddd8-2112">修复了以下问题：VBA 代码从项目中丢失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2112">Fix an issue where VBA code gets lost from projects.</span></span>
-   <span data-ttu-id="2ddd8-2113">修复了以下问题：即使还有剩余工时，任务也仍显示为已完成。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2113">Fix an issue where tasks show as complete even when there is remaining work.</span></span>
-   <span data-ttu-id="2ddd8-2114">修复了在使用任务路径功能时项目挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2114">Fix an issue where Project hangs when using the Task Path feature.</span></span>
-   <span data-ttu-id="2ddd8-2115">修复了时间刻度不显示时间刻度标签的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2115">Fix an issue where the timescale doesn't show the timescale labels.</span></span>
-   <span data-ttu-id="2ddd8-2116">修复了视觉对象报表显示信息不完整或完全无法显示信息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2116">Fix an issue where visual reports show incomplete information or fail completely.</span></span>
-   <span data-ttu-id="2ddd8-2117">修复了以下问题：如果保存失败，则会损坏文件，并导致 Project 在打开时发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2117">Fix an issue where a failed save can corrupt a file and cause Project to crash on open.</span></span>
-   <span data-ttu-id="2ddd8-2118">修复了以下问题：无法在“日程表和工作组规划器”视图中拖动任务。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2118">Fix an issue where you can't drag tasks in the Timeline and Team Planner view.</span></span>
-   <span data-ttu-id="2ddd8-2119">修复了以下问题：工作组生成器中不显示资源可用性。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2119">Fix an issue where resource availability isn't shown in Team Builder.</span></span>
-   <span data-ttu-id="2ddd8-2120">修复了图形指示器未正确显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2120">Fix an issue where graphical indicators aren't displaying correctly.</span></span>
-   <span data-ttu-id="2ddd8-2121">修复了在按小时或按天的基础上调配时项目挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2121">Fix an issue where Project hangs while leveling on hour-by-hour or day-by-day basis.</span></span>
-   <span data-ttu-id="2ddd8-2122">修复了从 SharePoint 文档库使用主项目/子项目的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2122">Fix an issue for working with master/sub projects from a SharePoint Document library.</span></span>
-   <span data-ttu-id="2ddd8-2123">修复了在将作业添加到固定工期任务时，最终可能获得无名资源的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2123">Fix an issue where, when you add assignments to a fixed duration task, you may end up with a nameless resource.</span></span>
-   <span data-ttu-id="2ddd8-2124">修复了以下问题：更改受保护的工时看到不正确的错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2124">Fix an issue that produces an incorrect error message of change on protected work.</span></span>
-   <span data-ttu-id="2ddd8-2125">修复了以下问题：转到包含多个图像的报表时，Project 可能会发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2125">Fix an issue where Project might crash when going to reports that contain several images.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="2ddd8-2126">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2126">Publisher: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-p334">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p334">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="publisher-non-security-updates"></a><span data-ttu-id="2ddd8-2130">Publisher：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2130">Publisher: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2131">修复了以下问题：运行“邮件合并”向导时，无法筛选包含 null（空）值的数据源字段。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2131">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="2ddd8-2132">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2132">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2133">修复了与 TLS 1.2 支持相关的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2133">Fix an issue related to TLS 1.2 support.</span></span>
-   <span data-ttu-id="2ddd8-2134">修复了以下问题：在会议中通过选择“Skype 通话”来添加用户导致出错</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2134">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error</span></span>
-   <span data-ttu-id="2ddd8-2135">修复了在会议中通过选择“Skype 通话”来添加用户导致出错的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2135">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="2ddd8-2136">如果 Skype 会议室已被添加为位置且会议已包含 Teams 会议协调人，则删除要求用户向会议添加 Skype 协调人的提示。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2136">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
-   <span data-ttu-id="2ddd8-2137">修复了以下问题：即使将 UseLocationForE911Only 设置为 true，位置也会被填充。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2137">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="2ddd8-2138">修复了以下问题：通过“使用会议中心呼叫”选项邀请名单中的用户时，Skype for Business 挂起。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2138">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="2ddd8-2139">修复了以下问题：创建 Skype for Business 会议期间，终端服务器上运行的 Outlook 冻结。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2139">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="2ddd8-2140">将 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的默认值更改为 TRUE。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2140">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>
-   <span data-ttu-id="2ddd8-2141">修复了以下问题：当会议处于全屏模式时，“更多选项”和“邀请更多人”按钮隐藏。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2141">Fix an issue where "More Options" and "Invite More People" buttons are hidden when a meeting is in full-screen mode.</span></span>
-   <span data-ttu-id="2ddd8-2142">修复了尝试加入时 P2P 音频呼叫窗口或电话会议窗口变成透明的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2142">Fix an issue where the P2P audio call window or conference call window becomes transparent when you attempt to join.</span></span>
-   <span data-ttu-id="2ddd8-2143">修复了即将开始的 Skype 会议不出现在“会议”选项卡中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2143">Fix an issue where upcoming Skype meetings do not show up in the meetings tab.</span></span>
-   <span data-ttu-id="2ddd8-2144">修复了在没有音频的情况下配置 Skype for Business 以加入会议时，添加音频到会议会对用户本人启动一个新的 P2P 呼叫，而不是添加音频到现有会议的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2144">Fix an issue where, when Skype for Business is configured to join meetings without audio, adding audio to a meeting initiates a new P2P call to the user itself rather than adding audio to the existing meeting.</span></span>
-   <span data-ttu-id="2ddd8-2145">修复了以下问题：在 Outlook 中单击会议请求内的“加入 Skype 会议”链接时，用户看到“找不到此 Skype 会议”错误消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2145">Fix an issue where user receives the error message "We couldn't find this Skype meeting" when clicking 'Join Skype Meeting' link in a meeting request from Outlook.</span></span>
-   <span data-ttu-id="2ddd8-2146">在用于传入 PSTN 呼叫的 Toast UI 中添加呼叫转移按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2146">Add call transfer button in the toast UI for incoming PSTN calls.</span></span>
-   <span data-ttu-id="2ddd8-2147">当 ChatDefaultClient 和 CallDefaultClient 设置为“团队”时，通知用户呼叫和聊天正在发送到“团队”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2147">Notify users that calls and chat are being sent to Teams when ChatDefaultClient and CallDefaultClient are set to Teams.</span></span>
-   <span data-ttu-id="2ddd8-2148">当用户不在会议中时，显示用户为“离线”状态，并禁用 Skype for Business，同时会议加入体验设置为“本机有限客户端”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2148">Show user's presence as Offline when user is not in a meeting and disabled from Skype for Business and meeting join experience is set to Native Limited Client.</span></span>
-   <span data-ttu-id="2ddd8-2149">当 Skype for Business 最小化到通知区域时，禁用除“打开”和“退出”外的所有选项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2149">Disable all options except Open and Exit when Skype for Business is minimized to the notification area.</span></span>
-   <span data-ttu-id="2ddd8-2150">当启用与 Aries 手机和 RedirectClient 配对时，禁止新的呼叫和对话。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2150">Suppress new calls and conversations when paired with Aries phones and RedirectClient is enabled.</span></span>
-   <span data-ttu-id="2ddd8-2151">修复了日期格式不是美国格式 (mm/dd/yy) 时，按日期在 PChat 中搜索消息失败的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2151">Fix an issue where searching messages in PChat by date fails when the date format is other than US format (mm/dd/yy).</span></span>
-   <span data-ttu-id="2ddd8-2152">修复了以下问题：当 EnableExternalP2PFileTransfer 策略设置为 false 时，用户仍能在会议中附加文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2152">Fix an issue where, when EnableExternalP2PFileTransfer policy is set to false, users are still able to attach files in meetings.</span></span>
-   <span data-ttu-id="2ddd8-p335">修复了以下问题：对话历史记录中显示的是呼叫方，而不是被叫方。如果使用 Active Directory 修改被叫方的工作电话号码，就会出现此问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p335">Fix an issue where, in Conversation History, the caller is shown instead of the called person. This happens when the called person's work number is modified using Active Directory.</span></span>
-   <span data-ttu-id="2ddd8-2155">修复了以下问题：对于向手机号码拨出的传出 PSTN 呼叫，对话历史记录中的呼叫历史记录内缺少接听人信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2155">Fix an issue where, for outgoing PSTN calls to mobile numbers, recipient information is missing in the call history in conversation history.</span></span>
-   <span data-ttu-id="2ddd8-2156">修复了以下问题：从 Outlook 中的电子邮件启动 IM 时，IM 的主题中没有电子邮件的主题行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2156">Fix an issue where, when initiating an IM from an email in Outlook, the subject line of the email is not included in the subject of the IM.</span></span>
-   <span data-ttu-id="2ddd8-2157">修复了以下问题：当 IM 对话窗口贴靠到一侧时，对话出现双层堆叠。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2157">Fix an issue where, when IM conversation windows are snapped to one side, conversations appear double stacked.</span></span>
-   <span data-ttu-id="2ddd8-2158">修复了以下问题：在 VDIv2 环境中，VbSS 屏幕共享请求显示为 基于 RDP 的请求。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2158">Fix an issue where, in a VDIv2 environment, VbSS screen sharing requests appear as RDP-based requests.</span></span>
-   <span data-ttu-id="2ddd8-2159">修复了以下问题：当呼叫转移失败时，失败通知中列出的是呼叫方，而不是未接来电的接听人。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2159">Fix an issue where, in a failed call transfer, the caller is listed in the failure notification, instead of the missed recipient.</span></span>
-   <span data-ttu-id="2ddd8-2160">修复了以下问题：客户端升级重定向横幅中隐藏“开始使用 Teams”按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2160">Fix an issue where the "Start using Teams" button is hidden within the client upgrade redirect banner.</span></span>
-   <span data-ttu-id="2ddd8-2161">修复了以下问题：IM 窗口中的 DPI 缩放问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2161">Fix DPI scaling issues in IM windows.</span></span>
-   <span data-ttu-id="2ddd8-2162">修复了以下问题：Skype for Business 联系人卡片中不显示 LinkedIn 数据。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2162">Fix an issue where LinkedIn data does not appear in the Skype for Business Contact Card.</span></span>
-   <span data-ttu-id="2ddd8-2163">用户现在可以代表智能寻线停止接听电话。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2163">Add the ability for users to stop receiving calls on behalf of a hunt group.</span></span>
-   <span data-ttu-id="2ddd8-2164">如果 Skype for Business 或 Teams 中有通话正在进行中，且接听或启动了新电话，现在可以自动保持呼叫。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2164">Add the ability to automatically hold calls when a call is active in Skype for Business or Teams and a new call is received or initiated.</span></span>
-   <span data-ttu-id="2ddd8-2165">修复了以下问题：用户在共享全屏后无法发送 IM。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2165">Fix an issue where users are unable to IM after full screen sharing.</span></span>
-   <span data-ttu-id="2ddd8-2166">修复了以下问题：会议厅中的用户在被拒绝进入会议时收不到通知。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2166">Fix an issue where users in the lobby aren't notified when they're denied from entering the meeting.</span></span>
-   <span data-ttu-id="2ddd8-2167">修复了以下问题：在通话期间，自动增益控制的增加不受控。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2167">Fix an issue where automatic gain control increases uncontrollably during calls.</span></span>
-   <span data-ttu-id="2ddd8-2168">修复了以下问题：如果会议室资源邮箱已添加到会议邀请，用户无法在“会议选项”中选择演示者。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2168">Fix an issue where users are unable to select a presenter in Meeting Options when a conference room resource mailbox is added to a meeting invite.</span></span>
-   <span data-ttu-id="2ddd8-2169">修复了以下问题：如果 AllowlPVideo 设置为 False，桌面共享按钮在对等视频呼叫期间灰显。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2169">Fix an issue where the desktop sharing button is dimmed during a peer-to-peer video call if AllowlPVideo is set to False.</span></span>
-   <span data-ttu-id="2ddd8-2170">修复了以下问题：将“会议选项”设置更改为对使用“禁用 IM”创建的现有会议启用 IM 后，IM 仍处于禁用状态。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2170">Fix an issue where IM stays disabled after changing the Meeting Option setting to Enable IM for existing meetings created with Disable IM.</span></span>
-   <span data-ttu-id="2ddd8-2171">修复了以下问题：在聊天窗口中将鼠标悬停在“插入链接”按钮之上时，工具提示不显示，并且在选择此按钮后看不到辅助功能名称。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2171">Fix an issue where the tooltip isn't shown when hovering over the "Insert Link" button in the chat window, and there isn't an accessibility name when the button is selected.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="2ddd8-2172">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2172">Visio: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-p336">**内置数据库模型图：** 使用新增的数据库模型图模板，可以将数据库准确建模为 Visio 图。不需要加载项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p336">**Built-in database model diagrams:** Use the new Database Model Diagram template to accurately model your database as a Visio diagram. No add-in required.</span></span>
-   <span data-ttu-id="2ddd8-2175">**更多适用于业务图表的模具：** 使用新式形状，通过维恩图比较和对比数据，或绘制循环图、矩阵图或棱锥图来帮助传达信息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2175">**More stencils for business diagrams:** Using modern shapes, compare and contrast data with a Venn diagram, or draw Cycle, Matrix, or Pyramid diagrams to help tell your story.</span></span>
-   <span data-ttu-id="2ddd8-p337">**创建网站的线框图表：** 快速创建网站的线框图表，其中包含界面、导航及其协作方式。 [了解更多](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p337">**Create a wireframe diagram for a website:** Quickly create a wireframe diagram of a website including interface, navigation, and how they work together. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="2ddd8-p338">**创建移动应用程序的线框：** 使用模板创建移动应用程序的线框。[了解详细信息](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p338">**Create a wireframe of your mobile application:** Use a template to create a wireframe of your mobile application. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="2ddd8-p339">**将数据图形应用到数据可视化工具图表：** 通过自动将形状数据应用为数据图形，从而在创建数据可视化工具图表时节省时间。 [了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p339">**Apply data graphics to Data Visualizer diagrams:** Save time when you create a Data Visualizer diagram by automatically applying shape data as data graphics. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span></span>
-   <span data-ttu-id="2ddd8-p340">**协作绘图：** 通过在 OneDrive for Business 或 SharePoint Online 上共享绘图，可以与人协作绘图。可以查看谁正在处理绘图，也可以添加注释和查看文件活动。 [了解更多](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p340">**Collaborate on drawings:** Work with others by sharing your drawings on OneDrive for Business or SharePoint Online. You can see who is working on the drawing, add comments, and see file activity. [Learn more](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span></span>
-   <span data-ttu-id="2ddd8-p341">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p341">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="2ddd8-2188">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2188">Word: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-2189">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2189">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="2ddd8-p342">**字符计数：** 在输入过程中，可以在状态栏上看到字符计数。可以通过“自定义状态栏”菜单启用此功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p342">**Character count:** Display the character count on the status bar as you type. You can enable this from the Customize Status Bar menu.</span></span>
-   <span data-ttu-id="2ddd8-2192">**快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2192">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="2ddd8-p343">**Microsoft Translator：** 在 Word 中直接使用 Microsoft Translator 将字词、短语或整篇文档翻译成其他语言。[了解详细信息](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p343">**Microsoft Translator:** Translate words, phrases, or the whole document into another language using Microsoft Translator, right in Word. [Learn more](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span></span>
-   <span data-ttu-id="2ddd8-p344">**数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p344">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="2ddd8-p345">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p345">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="2ddd8-p346">**SharePoint 属性面板：** 在文档中显示和编辑 SharePoint 文档库列值。借助“视图”选项卡上的功能区按钮，可以轻松地访问面板，并且 SharePoint 管理员能够使用文档库设置自动打开属性面板。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p346">**SharePoint property panel:** Display and edit SharePoint document library column values from within a document. A ribbon button on the View tab provides easy access to the panel and SharePoint admins can use a document library setting to automatically open the property panel.</span></span>
-   <span data-ttu-id="2ddd8-p347">**3D 模型：** 使用 3D 增强文档的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p347">**3D models:** Use 3D to increase the visual and creative impact of your documents.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="2ddd8-2204">**新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2204">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="2ddd8-p348">**共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p348">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="2ddd8-p349">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p349">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="2ddd8-p350">**使用学习工具进行编辑：** 学习工具现适用于 Word 的 Web 布局。编辑时，可以调整文字间距，并显示音节。在任意视图中，大声朗读文档时，每个单词都会突出显示。 [了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p350">**Edit using Learning Tools:** Learning Tools is now available in Word's Web Layout. Adjust your text spacing and show syllables while you edit. In any view, see each word highlighted as the document is read aloud. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
-   <span data-ttu-id="2ddd8-2214">**LaTeX 语法：** 使用 LaTeX 语法创建和编辑数学公式。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2214">**LaTeX syntax:** Create and edit math equations using LaTeX syntax.</span></span>
-   <span data-ttu-id="2ddd8-p351">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p351">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="2ddd8-2219">**按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2219">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="2ddd8-p352">**触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p352">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="2ddd8-p353">**通过“编辑器”窗格增强了书写帮助：** “编辑器”窗格可用于提供高级拼写、语法和写作风格建议。对辅助技术的支持已经过改进，可以访问此窗格。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p353">**Enhanced writing assistance with Editor pane:** Use the Editor pane for advanced spelling, grammar and writing style recommendations. It’s built to be accessible with improved support for assistive technologies.</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-2224">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2224">Word: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2225">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2225">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2226">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2226">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2227">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2227">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2228">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2228">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2229">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2229">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2230">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2230">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2231">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2231">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2232">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2232">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2233">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2233">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2234">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2234">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2235">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2235">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2236">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2236">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2237">[公告 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2237">[Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office Defense in Depth Update</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-2238">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2238">Word: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2239">修复了从 SharePoint Online 打开文件时 Word 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2239">Fix an issue where Word crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="2ddd8-2240">修复了小写罗马数字页码 被错误地更改为大写的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2240">Fix an issue where lower-case Roman number page numbers are incorrectly changed to upper case.</span></span>
-   <span data-ttu-id="2ddd8-2241">修复了导致出现内存不足消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2241">Fix an issue that causes an insufficient memory message to appear.</span></span>
-   <span data-ttu-id="2ddd8-2242">修复了以下问题：如果运行 Windows 7 的计算机未安装 客户体验和诊断遥测更新，无法打开 Word。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2242">Fix an issue where Word won’t open on a computer running Windows 7 that doesn't have the update for customer experience and diagnostic telemetry installed.</span></span>
-   <span data-ttu-id="2ddd8-2243">修复了以下问题：无法打印列表中的项目符号。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2243">Fix an issue where bullets in lists don’t print.</span></span>
-   <span data-ttu-id="2ddd8-2244">修复了以下问题：如果用户尝试对 OneDrive for Business 上的现有文档执行“另存为”操作，然后又取消保存或尝试合并现有更改，Word 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2244">Fix an issue where Word crashes when a user tries to do a Save As to an existing document on OneDrive for Business and then cancels the save or tries to merge existing changes.</span></span>
-   <span data-ttu-id="2ddd8-2245">修复了以下问题：运行“邮件合并”向导时，无法筛选包含 null（空）值的数据源字段。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2245">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>
-   <span data-ttu-id="2ddd8-p354">修复了以下问题：保存支持同步的文件时，Office 无法对磁盘执行写入操作，但 Office 仍继续将文件上传到 OneDrive。修复此问题后，用户现在会看到错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p354">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="2ddd8-2248">修复了以下问题：无法撤消对文档的 IRM 保护。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2248">Fix an issue where removing IRM protection on a document doesn’t remove the protection.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2249">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2249">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2250">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2250">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2251">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2251">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2252">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2252">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2253">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2253">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2254">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2254">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2255">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2255">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2256">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2256">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2257">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2257">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2258">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2258">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2259">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2259">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2260">[公告 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2260">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-2261">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2261">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2262">修复了以下问题：使用 Configuration Manager 将更新部署到运行 Office 应用程序的客户端时，在 Office 应用程序正在运行的情况下重启设备后更新未应用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2262">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>
-   <span data-ttu-id="2ddd8-2263">修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2263">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
-   <span data-ttu-id="2ddd8-2264">启用 Office COM 对象时，“文件 \> 帐户 \> 更新选项”中的“立即更新”选项处于隐藏状态，以便 Configuration Manager 能够管理 Office 365 客户端更新。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2264">The Update Now option is hidden from File \> Account \> Update Options when an Office COM object is enabled so that Office 365 client updates are managed by Configuration Manager.</span></span>
-   <span data-ttu-id="2ddd8-2265">修复了以下问题：当用户尝试使用“激活 Office”对话框激活 Office 时，Office 应用程序发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2265">Fix an issue where the Office app crashes when the user tries to activate Office using the Activate Office dialog box.</span></span>
-   <span data-ttu-id="2ddd8-2266">修复了以下问题：在动态 DPI 环境下 Office 加载项存在的缩放问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2266">Fix an issue with zooming and scaling in Office Add-ins under dynamic DPI environment.</span></span>
-   <span data-ttu-id="2ddd8-2267">修复了以下问题：即使当前安装了 Office 365 专业增强版，Office 配置服务提供程序 (CSP) 的 CurrentStatus 节点也会返回空字符串。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2267">Fix an issue where the CurrentStatus node of the Office configuration service provider (CSP) returns an empty string even if Office 365 ProPlus is currently installed.</span></span>
-   <span data-ttu-id="2ddd8-2268">修复了以下问题：.box 文件格式更改，影响安装在同一台计算机上的旧版 Office 的功能，因为 .box 文件在同一台计算机上所有版本的 Office 应用程序之间共享。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2268">Fix an issue that causes .box file format changes, which impacts functionality of older versions of Office installed on the same computer, because .box files are shared across all versions of an Office app on the same computer.</span></span>
-   <span data-ttu-id="2ddd8-2269">修复了在某些应用场景中导致更新安装所用时间过长的 bug。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2269">Fix a bug that caused update install to take a long time in certain scenarios.</span></span> 
-   <span data-ttu-id="2ddd8-2270">修复了 SVG 测试失败的问题</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2270">Fix an issue where SVG tests are failing</span></span>
-   <span data-ttu-id="2ddd8-2271">修复了以下问题：使用 Configuration Manager 将更新部署到运行 Office 应用程序的客户端时，在 Office 应用程序正在运行的情况下重启设备后更新未应用。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2271">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>


## <a name="version-1708-july-10"></a><span data-ttu-id="2ddd8-2272">版本 1708：7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2272">Version 1708: July 10</span></span>
<span data-ttu-id="2ddd8-2273">*版本 1708（内部版本 8431.2280）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2273">*Version 1708 (Build 8431.2280)*</span></span>

<span data-ttu-id="2ddd8-2274">*这是自 2018 年 1 月起就已发布的半年频道版本。2019 年 3 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1803，内部版本 9126.2259）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2274">*This is the Semi-Annual Channel release that's been available since January 2018. It will continue to be supported and receive security updates until March 2019. But, a new Semi-Annual Channel release is now available — Version 1803 (Build 9126.2259) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="2ddd8-2275">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2275">Access: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2276">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2276">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2277">Outlook：安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2277">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2278">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 篡改漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2278">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2279">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2279">Office Suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2280">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2280">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>


## <a name="version-1708-june-12"></a><span data-ttu-id="2ddd8-2281">版本 1708：6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2281">Version 1708: June 12</span></span>
<span data-ttu-id="2ddd8-2282">*版本 1708（生成号 8431.2270）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2282">*Version 1708 (Build 8431.2270)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2283">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2283">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2284">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2284">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2285">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2285">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2286">Outlook：安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2286">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2287">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2287">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-2288">Outlook：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2288">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2289">修复了以下问题：Windows 7 SP1 用户无法将成员添加到新式组。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2289">Fix an issue that caused users of Windows 7 SP1 to be unable to add members to Modern Groups.</span></span>



## <a name="version-1705-june-12"></a><span data-ttu-id="2ddd8-2290">版本 1705：6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2290">Version 1705: June 12</span></span>
<span data-ttu-id="2ddd8-2291">*版本 1705（生成号 8201.2294）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2291">*Version 1705 (Build 8201.2294)*</span></span>

<span data-ttu-id="2ddd8-2292">*这是自 2017 年 9 月起就已发布的延期频道版本。2018 年 7 月前，此版本会继续获得支持，并接收安全更新程序。不过，新版半年频道（即版本 1708，生成号 8431.2270）现已推出，其中包含新增功能、安全更新程序和非安全更新程序。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2292">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2270) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2293">Excel：安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2293">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2294">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2294">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2295">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2295">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2296">Outlook：安全更新程序</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2296">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2297">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2297">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>



## <a name="version-1708-may-8"></a><span data-ttu-id="2ddd8-2298">版本 1708：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2298">Version 1708: May 8</span></span>
<span data-ttu-id="2ddd8-2299">*版本 1708（内部版本 8431.2250）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2299">*Version 1708 (Build 8431.2250)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2300">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2300">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2301">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2301">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2302">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2302">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2303">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2303">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2304">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2304">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2305">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2305">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2306">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2306">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2307">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2307">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2308">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2308">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2309">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2309">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1705-may-8"></a><span data-ttu-id="2ddd8-2310">版本 1705：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2310">Version 1705: May 8</span></span>
<span data-ttu-id="2ddd8-2311">*版本 1705（内部版本 8201.2278）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2311">*Version 1705 (Build 8201.2278)*</span></span>

<span data-ttu-id="2ddd8-2312">*这是自 2017 年 9 月起就已发布的延期频道版本。2018 年 7 月前，此版本会继续获得支持，并接收安全更新。不过，新版半年频道（即版本 1708，内部版本 8431.2250）现已推出，其中包含新增功能、安全更新和非安全更新。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2312">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2250) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2313">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2313">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2314">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2314">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2315">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2315">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2316">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2316">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2317">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2317">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2318">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2318">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2319">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2319">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2320">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2320">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2321">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2321">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2322">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2322">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1708-april-10"></a><span data-ttu-id="2ddd8-2323">版本 1708：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2323">Version 1708: April 10</span></span>
<span data-ttu-id="2ddd8-2324">*版本 1708（内部版本 8431.2242）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2324">*Version 1708 (Build 8431.2242)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2325">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2325">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2326">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2326">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="2ddd8-2327">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2327">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2328">修复了与 TLS 1.2 支持相关的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2328">Fix an issue related to TLS 1.2 support.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2329">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2329">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2330">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2330">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2331">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2331">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2332">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2332">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1705-april-10"></a><span data-ttu-id="2ddd8-2333">版本 1705：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2333">Version 1705: April 10</span></span>
<span data-ttu-id="2ddd8-2334">*版本 1705（内部版本 8201.2272）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2334">*Version 1705 (Build 8201.2272)*</span></span>

<span data-ttu-id="2ddd8-2335">*这是自 2017 年 9 月起就已发布的延期频道版本。2018 年 7 月前，此版本会继续获得支持，并接收安全更新。不过，新版半年频道（即版本 1708，内部版本 8431.2242）现已推出，其中包含新增功能、安全更新和非安全更新。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2335">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2242) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2336">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2336">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2337">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2337">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2338">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2338">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2339">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2339">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2340">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2340">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2341">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2341">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1708-march-13"></a><span data-ttu-id="2ddd8-2342">版本 1708：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2342">Version 1708: March 13</span></span>
<span data-ttu-id="2ddd8-2343">*版本 1708（内部版本 8431.2236）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2343">*Version 1708 (Build 8431.2236)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="2ddd8-2344">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2344">Access: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2345">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2345">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2346">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2346">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2347">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2347">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-2348">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2348">Word: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2349">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2349">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1705-march-13"></a><span data-ttu-id="2ddd8-2350">版本 1705：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2350">Version 1705: March 13</span></span>
<span data-ttu-id="2ddd8-2351">*版本 1705（内部版本 8201.2265）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2351">*Version 1705 (Build 8201.2265)*</span></span>

<span data-ttu-id="2ddd8-2352">*这是自 2017 年 9 月起就已发布的延期频道版本。2018 年 7 月前，此版本会继续获得支持，并接收安全更新。不过，新版半年频道（即版本 1708，内部版本 8431.2236）现已推出，其中包含新增功能、安全更新和非安全更新。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2352">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2236) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="2ddd8-2353">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2353">Access: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2354">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2354">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2355">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2355">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2356">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2356">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-2357">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2357">Word: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2358">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2358">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1708-february-13"></a><span data-ttu-id="2ddd8-2359">版本 1708：2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2359">Version 1708: February 13</span></span>
<span data-ttu-id="2ddd8-2360">*版本 1708（内部版本 8431.2215）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2360">*Version 1708 (Build 8431.2215)*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="2ddd8-2361">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2361">Access: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2362">修复了以下问题：在使用多项目窗体时，调整鼠标滚轮的位置或滚动条缩略图不更改窗体中显示的项目。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2362">Fix an issue where, when using a multiple items form, adjusting the position of the mouse wheel or the scrollbar thumb doesn't change the items that are displayed in the form.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2363">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2363">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2364">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2364">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2365">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2365">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2366">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2366">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2367">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2367">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2368">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2368">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2369">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2369">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2370">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2370">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1705-february-13"></a><span data-ttu-id="2ddd8-2371">版本 1705：2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2371">Version 1705: February 13</span></span>
<span data-ttu-id="2ddd8-2372">*版本 1705（内部版本 8201.2258）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2372">*Version 1705 (Build 8201.2258)*</span></span>

<span data-ttu-id="2ddd8-2373">*这是自 2017 年 9 月起就已发布的延期频道版本。2018 年 7 月前，此版本会继续获得支持，并接收安全更新。不过，新版半年频道（即版本 1708，内部版本 8431.2215）现已推出，其中包含新增功能、安全更新和非安全更新。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2373">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2215) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2374">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2374">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2375">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2375">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2376">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2376">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2377">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2377">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2378">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2378">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2379">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2379">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2380">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2380">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2381">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2381">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1708-january-9"></a><span data-ttu-id="2ddd8-2382">版本 1708：1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2382">Version 1708: January 9</span></span>
<span data-ttu-id="2ddd8-2383">*版本 1708（内部版本 8431.2153）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2383">*Version 1708 (Build 8431.2153)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="2ddd8-2384">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2384">Access: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-2385">**标签名称属性：** 通过将标签与窗体上的控件相关联，增强了辅助功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2385">**Label Name property:** Enhance accessibility by associating a label with a control on a form.</span></span>
-   <span data-ttu-id="2ddd8-2386">**编辑新项更加容易：** 使用键盘快捷方式 (Ctrl+E) 通过组合框或列表框编辑新项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2386">**Editing a new item is more accessible:** Use a quick keyboard shortcut (Ctrl+E) to edit a new item from a Combo Box or List Box.</span></span>
-   <span data-ttu-id="2ddd8-p355">**Dynamics 连接器：** 导入 Microsoft Dynamics 中的数据，或链接到其中存储的数据。[更多信息](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p355">**Dynamics connector:** Import data from or link to data stored in Microsoft Dynamics. [More information](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)</span></span>
-   <span data-ttu-id="2ddd8-p356">**Salesforce 连接器：** 导入 Salesforce 中的数据，或链接到其中存储的数据。[详细信息](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p356">**Salesforce connector:** Import data from or link to data stored in Salesforce. [More information](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="2ddd8-2391">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2391">Access: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2392">修复了以下问题：尝试选择文本框或组合框中的文本时似乎会选择所有文本，而不是指示的选择内容。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2392">Fix an issue where attempting to select text in a text box or combo box appears to select all the text, rather than the indication selection.</span></span>
-   <span data-ttu-id="2ddd8-2393">修复了当查询与 Microsoft Dynamics 链接表中的主键存在连接时，查询不执行的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2393">Fix an issue where a query won't execute if the query has a join with a primary key from a Microsoft Dynamics linked table.</span></span>
-   <span data-ttu-id="2ddd8-2394">修复了以下问题：Microsoft Dynamics 表中货币值不显示小数位数。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2394">Fix an issue where decimal places aren't shown for currency values in a Microsoft Dynamics table.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="2ddd8-2395">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2395">Excel: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-2396">**“从示例中添加列”增强功能：** 支持更多的日期/时间、数学和索引列转换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2396">**“Add Column from Examples” enhancements:** Supports more Date/Time, Math, and Index Column transformations.</span></span>
-   <span data-ttu-id="2ddd8-2397">**性能改进：** Excel 将以更快的速度打开包含多个工作表的复杂工作簿，以便可以更快地处理包含大片区域的公式、筛选多个行或进行复制和粘贴。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2397">**Performance improvements:** Excel opens complex workbooks with multiple sheets faster, so you can crunch formulas with large ranges, filter lots of rows, or copy and paste quicker.</span></span>
-   <span data-ttu-id="2ddd8-2398">**插入联机图片：** 自动将图像插入用于选择图像和属性信息的新登录页。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2398">**Insert online pictures:** New landing page for selecting images and attribution information is automatically inserted with the image.</span></span>
-   <span data-ttu-id="2ddd8-2399">**Azure Data Lake Store 连接器：** 用户现在可以从 Azure Data Lake Store 导入数据。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2399">**Azure Data Lake Store connector:** Users can now import data from Azure Data Lake Store.</span></span>
-   <span data-ttu-id="2ddd8-2400">**“从示例中添加列”增强功能：** 支持建议、更多的日期/时间操作和其他转换。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2400">**"Add column from Examples" enhancements:** Supports suggestions, more Date/Time operations, and additional transformations.</span></span>
-   <span data-ttu-id="2ddd8-2401">**“数据”选项卡**：“数据”选项卡上的功能区按钮已被重排到两个新组中：“获取和转换数据”以及“查询和连接”。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2401">**Data tab**: Ribbon buttons on the Data tab have been rearranged into two new groups: Get & Transform Data and Queries & Connections.</span></span>
-   <span data-ttu-id="2ddd8-2402">**共享查询**：可以将任意查询定义导出到 Office 数据库连接 (ODC) 文件中，然后跨工作簿共享或与其他人共享。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2402">**Share queries**: Export any query definition into an Office Database Connection (ODC) file, and then share it across workbooks or with others.</span></span>
-   <span data-ttu-id="2ddd8-2403">**加载数据：** 可以将查询中的数据直接加载到数据透视表或数据透视图中，而无需将数据保存到数据模型中。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2403">**Load data:** Load data from a query directly into PivotTables or PivotCharts without having to save the data into the Data Model.</span></span>
-   <span data-ttu-id="2ddd8-2404">**共享文件活动：** 选择文件右上角的“活动”按钮，可以查看在 OneDrive for Business 或 SharePoint 中共享的文经共享、编辑、重命名或恢复的时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2404">**Shared file activity:** Choose the Activity button in the upper right corner of the file to see when a file shared in OneDrive for Business or SharePoint was shared, edited, renamed, or restored.</span></span>
-   <span data-ttu-id="2ddd8-p357">**安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p357">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>
-   <span data-ttu-id="2ddd8-p358">**增强的数据导入功能：** 可从各种源轻松导入并形成数据。通过“查询和连接”侧窗格管理工作簿查询和连接，并通过 ODC 文件与他人共享查询。 [更多信息](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p358">**Enhanced data import functionality:** Easily import and shape data from various sources. Manage workbook queries and connections with the Queries & Connection side pane, and share queries with others via ODC files. [More information](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)</span></span>
-   <span data-ttu-id="2ddd8-p359">**对共享文件做出的更改**：查看共享工作簿的更改人，并还原旧版工作簿。[更多信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p359">**Changes in shared files**: View who has made changes in shared workbooks, and restore earlier versions. [More information](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span></span>
-   <span data-ttu-id="2ddd8-2413">**含有笔按钮的套索选择：** 无需访问功能区，即可使用套索选择墨迹带的支持数字笔按钮。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2413">**Lasso Select with a pen button:** Use supported digital pen buttons to Lasso Select ink without visiting the ribbon.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2414">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2414">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2415">[CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2415">[CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2416">[CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2416">[CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2417">[CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2417">[CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2418">[CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2418">[CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2419">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全功能绕过漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2419">[CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2420">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2420">[CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2421">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2421">[CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2422">[CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2422">[CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2423">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2423">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2424">[公告 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2424">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="2ddd8-2425">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2425">Excel: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2426">修复了在编程创建数据透视表后，编程刷新导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2426">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="2ddd8-2427">修复了在使用宏打开 Office 2007 或更低版本工作簿（.xls 或 .xla）时，用户错误地看到“灾难性故障”错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2427">Fix an issue where the user incorrectly sees a "catastrophic failure" error message when opening an Office 2007 or older workbook (.xls or .xla) with macros.</span></span>
-   <span data-ttu-id="2ddd8-2428">修复了通过命令行打开工作簿可能会导致单元格中 RTF 格式丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2428">Fix an issue where opening a workbook from the command line might result in the loss of rich text formatting in a cell.</span></span>
-   <span data-ttu-id="2ddd8-2429">修复了当文件名包含方括号时，用户无法在受保护视图中关闭工作簿的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2429">Fix an issue where the user can't close a workbook in protected view when the file name contains square brackets.</span></span>
-   <span data-ttu-id="2ddd8-2430">修复了以下问题：当用户尝试在现有的工作簿中插入对象时，用户单击“浏览”导致 Excel 发生故障的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2430">Fix an issue where, when the user tries to insert an object in an existing workbook, Excel crashes when the user clicks Browse.</span></span>
-   <span data-ttu-id="2ddd8-2431">修复了以下问题：（在“设置形状格式”窗格的“文本选项/文本框”部分中）选择“调整形状大小以修复文本”不会产生任何形状更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2431">Fix an issue where selecting "Resize shape to fix text" (in the Text Options/Text Box portion of the Format Shape pane) results in no change to the shape.</span></span>
-   <span data-ttu-id="2ddd8-2432">修复了以下问题：通过双击工作簿将其打开时，不加载单元格文本字体和格式或为单个模板打开两个相同的工作簿。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2432">Fix an issue where, when opening a workbook by double-clicking on it, the cell text fonts and formats don't get loaded or two identical workbooks are opened for a single template.</span></span>
-   <span data-ttu-id="2ddd8-2433">修复了在打开或创建新工作簿时，Excel 启动时创建的第一个工作簿将不会关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2433">Fix an issue where the first workbook created when Excel starts won't close when a new workbook is opened or created.</span></span>
-   <span data-ttu-id="2ddd8-2434">修复了以下问题：拖动或拖动填充时，工具提示的位置未对齐。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2434">Fix an issue where placement of the tooltip is misaligned when dragging or drag filling.</span></span>
-   <span data-ttu-id="2ddd8-2435">修复了以下问题：使用“文件”\>“另存为”保存工作簿时，包含句点的文件名在文件保存对话框中显示为空白或被截断。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2435">Fix an issue where, when saving a workbook by using File \> Save As, a file name that contains periods appears blank or truncated in the file save dialog.</span></span>
-   <span data-ttu-id="2ddd8-p360">修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p360">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="2ddd8-2438">修复了由于图形驱动程序错误导致出现黑线和标题的呈现问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2438">Fix an issue with rendering where black lines and headers appear due to a faulty graphics driver.</span></span>
-   <span data-ttu-id="2ddd8-2439">修复了在插入图表后 Excel 发生故障或无法保存工作簿的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2439">Fix an issue where Excel crashes or is unable to save the workbook after a chart is inserted.</span></span>
-   <span data-ttu-id="2ddd8-2440">修复了在分页预览下页面分隔线定位不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2440">Fix an issue where the page break line in page break preview is incorrectly positioned.</span></span>
-   <span data-ttu-id="2ddd8-2441">修复了打开 .XLL 文件时 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2441">Fix an issue where Excel crashes when opening an .XLL file.</span></span>
-   <span data-ttu-id="2ddd8-2442">修复了以下问题：在“页面布局”视图中添加页眉或页脚后，单元格的图案样式显示不正确。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2442">Fix an issue where the pattern style of a cell doesn’t render correctly after adding a header or footer in Page Layout view.</span></span>
-   <span data-ttu-id="2ddd8-2443">修复了以下问题：将数据透视表的一个副本粘贴到另一个工作簿时，可能会导致崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2443">Fix an issue where pasting a copy of a PivotTable into another workbook could result in a crash.</span></span>
-   <span data-ttu-id="2ddd8-2444">修复了以下问题：选择“替换”命令并且“查找和替换”对话框打开时，对话框的焦点位于“查找”选项卡上，而非“替换”选项卡上。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2444">Fix an issue where, when you choose the Replace command and the Find and Replace dialog box opens, the focus of the dialog box is on the Find tab instead of the Replace tab.</span></span>
-   <span data-ttu-id="2ddd8-2445">修复了以下问题：打开工作薄（它从版本早于 SharePoint Server 2016 的 SharePoint Server 打开）的“活动”窗格时 Excel 崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2445">Fix an issue where Excel crashes when opening the Activity pane for a workbook opened from a SharePoint server older than SharePoint Server 2016.</span></span>
-   <span data-ttu-id="2ddd8-2446">修复了以下问题：启用一个或多个 XLL 外接程序时，Excel 打开并显示空白窗口。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2446">Fix an issue where Excel opens and displays a blank window when one or more XLL add-ins are enabled.</span></span>
-   <span data-ttu-id="2ddd8-2447">修复了以下问题：在已关闭的工作簿中使用“窗体”按钮后，Excel 崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2447">Fix an issue where Excel crashes after having used the Forms button in an already closed workbook.</span></span>
-   <span data-ttu-id="2ddd8-2448">修复了以下问题：在使用 SheetBeforeRightClick 事件时，插入与合并单元格相交的列不会展开合并的单元格。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2448">Fix an issue where, when using the SheetBeforeRightClick event, inserting a column that intersects merged cells doesn't expand the merged cells.</span></span>
-   <span data-ttu-id="2ddd8-2449">修复了在展开或折叠数据透视表时，Excel 会暂时挂起，并且数据透视表标题移动到屏幕之外的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2449">Fix an issue where Excel temporarily hangs when you expand or collapse a PivotTable and the PivotTable headers move off the screen.</span></span>
-   <span data-ttu-id="2ddd8-2450">修复了从 Word 复制并粘贴制表符分隔的文本时制表符被忽略，进而导致文本无法解析到列中的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2450">Fix an issue where tabs are ignored when copying and pasting tab delimited text from Word, resulting in the text not being parsed into columns.</span></span>
-   <span data-ttu-id="2ddd8-2451">修复了以下问题：以网页对话框形式打开发布时 Excel 出现故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2451">Fix an issue where Excel crashes when opening the Publish as Web Page dialog box.</span></span>
-   <span data-ttu-id="2ddd8-2452">修复了以下问题：使用 SQL Server Analysis Services 服务器中的数据，且 Excel 与 SQL Server Analysis Services 服务器的区域设置不同时，数据刷新无法成功或 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2452">Fix an issue where a data refresh doesn't succeed or Excel crashes when using data from a SQL Server Analysis Services server, and the locale of Excel and the locale of the SQL Server Analysis Services server differ.</span></span>
-   <span data-ttu-id="2ddd8-2453">修复了以下问题：在尝试将更改保存到与 OneDrive 客户端同步的文档时出现错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2453">Fix an issue where errors appear when trying to save changes to documents synchronized with the OneDrive client.</span></span>
-   <span data-ttu-id="2ddd8-2454">修复了以下问题：在筛选区中存在具有字段的数据透视表，但在其他任何位置没有字段时，无法在工作表的任何位置进行更改。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2454">Fix an issue where changes can't be made anywhere in a worksheet when there is a PivotTable with fields in the Filter area, but no fields anywhere else.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="2ddd8-2455">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2455">Outlook: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-2456">**辅助功能改进：** 简化了使用屏幕阅读器读取和编辑电子邮件中的文本、表、列表和图像的方式。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2456">**Accessibility improvements:** We've made it easier to read and edit text, tables, lists, and images in email when you're using a screen reader.</span></span>
-   <span data-ttu-id="2ddd8-2457">**新帐户配置：** 使用新向导设置一个手动操作步骤较少的新帐户。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2457">**New account configuration:** Set up new accounts with a new wizard that requires fewer manual steps.</span></span>
-   <span data-ttu-id="2ddd8-p361">**链接附加对话框：** 使用功能区上的“附加文件”附加链接时，可以选择是将它添加为链接，还是添加为附件。如果不想每次都看到此对话框，请依次转到“文件”\>“选项”\>“常规”，并在“附件选项”下指定所需的链接附加方式。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p361">**Attach dialog for links:** When attaching a link using Attach File on the ribbon, you can select whether to add it as a link or as an attachment. If you don’t want to see this dialog each time, go to File \> Options \> General and specify how you want links to be attached under “Attachment options.”</span></span>
-   <span data-ttu-id="2ddd8-2460">**支持本地附件：** 本地 SharePoint Server 中的文件显示为“邮件”\>“附加文件”下的最近使用的文件，本地 OneDrive for Business 和 SharePoint 团队网站显示在“附加文件”\>“浏览 Web 位置”下，本地文件可以上传到本地的 OneDrive for Business 站点。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2460">**Support for on-premises attachments:** Files from on-premises SharePoint Server show up as recent files under Message \> Attach File, on-premises OneDrive for Business and SharePoint team sites appear under Attach File \> Browse Web Locations, and local files can be uploaded to on-premises OneDrive for Business sites.</span></span>
-   <span data-ttu-id="2ddd8-2461">**组业务分类：**  可在创建或编辑组时分配由租户管理员定义的业务分类级别，例如“机密”，并且分类会显示在组标头中。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2461">**Business classifications for groups:**  A business classification level defined by the tenant admin, such as Confidential, can be assigned when creating or editing a group, and that classification appears in the group header.</span></span>
-   <span data-ttu-id="2ddd8-p362">**Office 365 组的来宾访问：** 向组织外的用户授予组对话、文件、日历邀请和组笔记本的访问权限，并与他们进行协作。 [更多信息](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p362">**Guest access to Office 365 groups:** Collaborate with people outside the organization by granting them access to group conversations, files, calendar invitations, and the group notebook. [More information](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)</span></span>
-   <span data-ttu-id="2ddd8-p363">**可操作邮件：** 开发人员可以创建能够轻松地使用户直接从 Outlook 执行简单或快速操作而无需切换到外部网站或单独应用的邮件。[更多信息](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p363">**Actionable messages:** Developers can create messages to make it easy for users to take simple or quick actions right from Outlook without having to switch to an external web site or separate app. [More information](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2466">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2466">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2467">[CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)：Microsoft Office Outlook 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2467">[CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2468">[CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)：Microsoft Office Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2468">[CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2469">[CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)：Microsoft Office Outlook 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2469">[CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2470">[CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774)：Microsoft Outlook 安全功能绕过漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2470">[CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2471">[CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776)：Microsoft Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2471">[CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Microsoft Outlook Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2472">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2472">[CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2473">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2473">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2474">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2474">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="2ddd8-2475">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2475">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2476">修复了用户在删除邮件时看到邮件列表中的焦点意外跳转的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2476">Fix an issue where the user sees the focus in the message list jump unexpectedly when deleting messages.</span></span>
-   <span data-ttu-id="2ddd8-2477">修复了用户在对附件执行操作时看到身份验证提示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2477">Fix an issue that causes the user to see authentication prompts when interacting with attachments</span></span>
-   <span data-ttu-id="2ddd8-2478">修复了在使用深灰色主题时，策略提示中的“了解更多”链接不可见的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2478">Fix an issue where the "Learn more" link in Policy Tips isn't visible when using the Dark Gray theme.</span></span>
-   <span data-ttu-id="2ddd8-2479">修复了以下问题：用户尝试设置新帐户和在完成帐户设置之前关闭窗口时，Outlook 崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2479">Fix an issue where Outlook crashes when the user is trying to set up a new account and they close the window without completing the account setup.</span></span>
-   <span data-ttu-id="2ddd8-2480">修复了以下问题：“标记为已读”和“标记为未读”显示为群组共享收件箱中的邮件选项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2480">Fix an issue where Mark as Read and Mark as Unread show as options for messages in the shared inbox for a group.</span></span>
-   <span data-ttu-id="2ddd8-2481">修复了无法在 Outlook 中配置 IMAP 帐户的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2481">Fix an issue where you're unable to configure an IMAP account in Outlook.</span></span>
-   <span data-ttu-id="2ddd8-2482">修复了以下问题：打开 Outlook 时，发生间歇性故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2482">Fix an issue that causes an intermittent crash when opening Outlook.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="2ddd8-2483">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2483">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-2484">**插入联机图片：** 自动将图像插入用于选择图像和属性信息的新登录页。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2484">**Insert online pictures:** New landing page for selecting images and attribution information is automatically inserted with the image.</span></span>
-   <span data-ttu-id="2ddd8-p364">**视频的隐藏式字幕：** 可以在视频中添加隐藏式字幕，使其更易于访问。[详细信息](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p364">**Closed captions for videos:** Add closed captions to a video to make it more accessible. [More information](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)</span></span>
-   <span data-ttu-id="2ddd8-p365">**对记录添加旁白：** 录制演示文稿时，请将自己旁白的视频包括在内。录制的内容可以包括动画、墨迹、音频和视频。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p365">**Narrate a recording:** Include video of yourself narrating when you make a recording of a presentation. Recordings can include animations, ink, audio, and video.</span></span>
-   <span data-ttu-id="2ddd8-2489">**共享文件活动：** 选择文件右上角的“活动”按钮，可以查看在 OneDrive for Business 或 SharePoint 中共享的文经共享、编辑、重命名或恢复的时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2489">**Shared file activity:** Choose the Activity button in the upper right corner of the file to see when a file shared in OneDrive for Business or SharePoint was shared, edited, renamed, or restored.</span></span>
-   <span data-ttu-id="2ddd8-2490">**替换文字创建：** 基于云的服务自动生成演示文稿中的图片的可选文字。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2490">**Alt text creation:** A cloud-based service automatically generates alternative text for pictures in a presentation.</span></span>
-   <span data-ttu-id="2ddd8-p366">**安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p366">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>
-   <span data-ttu-id="2ddd8-2494">**设计器改进：** 推荐面向操作的列表的专业设计灵感。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2494">**Designer improvements:** Recommends professional design ideas for action-oriented lists.</span></span>
-   <span data-ttu-id="2ddd8-p367">**对共享文件做出的更改：** 查看共享演示文稿的更改人，并还原旧版演示文稿。[更多信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p367">**Changes in shared files:** View who has made changes in shared presentations, and restore earlier versions. [More information](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span></span>

### <a name="powerpoint-security-updates"></a><span data-ttu-id="2ddd8-2497">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2497">PowerPoint: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2498">[CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742)：PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2498">[CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): PowerPoint Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2499">[CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743)：PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2499">[CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): PowerPoint Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2500">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2500">[CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint Information Disclosure Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="2ddd8-2501">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2501">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-p368">修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p368">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="2ddd8-2504">修复了在表格中执行撤销操作后编辑和格式化的文本导致 PowerPoint 发生故障的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2504">Fix an issue where editing and formatting text after an undo in a table causes PowerPoint to crash.</span></span>
-   <span data-ttu-id="2ddd8-p369">修复了对基于 Flash Player 的 YouTube 嵌入代码进行引用导致打开新窗口播放视频的问题。旧嵌入代码现已升级以引用基于 HTML5 的 YouTube 视频，以便正确播放这些视频。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p369">Fix an issue where references to Flash Player based YouTube embed codes result in a new window opening to play the video. Old embed codes are now upgraded to reference HTML5 based YouTube videos so that they correctly play in place.</span></span>
-   <span data-ttu-id="2ddd8-2507">修复了以下问题：从版本早于 SharePoint Server 2016 的 SharePoint Server 打开演示文稿时，PowerPoint 崩溃。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2507">Fix an issue where PowerPoint crashes when opening a presentation from a SharePoint server older than SharePoint Server 2016.</span></span>
-   <span data-ttu-id="2ddd8-2508">修复了以下问题：无法显示与字体关联的最终用户定义字符 (EUDC)。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2508">Fix an issue where end-user defined characters (EUDCs) that are linked to fonts fail to display.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="2ddd8-2509">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2509">Project: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2510">修复了以下问题：项目级自定义字段数据可能会在保存时丢失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2510">Fix an issue an issue where project level custom field data can get lost on save.</span></span>
-   <span data-ttu-id="2ddd8-2511">修复了以下问题：如果保存失败，则会损坏文件，并导致 Project 在打开时发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2511">Fix an issue where a failed save can corrupt a file and cause Project to crash on open.</span></span>
-   <span data-ttu-id="2ddd8-2512">修复了以下问题：打开项目计划可能会导致故障发生。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2512">Fix an issue where opening a project plan could lead to a crash.</span></span>
-   <span data-ttu-id="2ddd8-2513">修复了从 Project Online 打开某些文件会导致项目出现故障的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2513">Fix an issue where opening certain files from Project Online causes Project to crash.</span></span>
-   <span data-ttu-id="2ddd8-2514">修复了设置剩余工时时可能会错误地将实际开始时间清除的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2514">Fix an issue where Actual Start may be wrongly cleared when you set remaining work.</span></span>
-   <span data-ttu-id="2ddd8-2515">修复了工作分配实际开始日期显示的数据可能与通过 Project Web App 进展状况中的资源报告的数据不同的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2515">Fix an issue where Assignment Actual Start Date may show different data than was reported by the resource through statusing in Project Web App.</span></span>
-   <span data-ttu-id="2ddd8-2516">修复了更改任务的完成日期后可能会重排实际工时的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2516">Fix an issue where actual work may be rescheduled if the task's finish date is changed.</span></span>
-   <span data-ttu-id="2ddd8-2517">修复了复制并粘贴成本字段时由于舍入问题粘贴值可能与复制值不完全一致的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2517">Fix an issue where if you copy and paste cost fields, the pasted values might not exactly match the copied values due to a rounding issue.</span></span>
-   <span data-ttu-id="2ddd8-2518">修复了从一个基线保存到另一个基线时无法复制预算资源的时间分段数据的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2518">Fix an issue where timephased data for Budget resources isn't copied when you save from one baseline into another one.</span></span>
-   <span data-ttu-id="2ddd8-2519">修复了无法始终正确计算摘要任务的状态字段的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2519">Fix an issue where the status field doesn't always calculate correctly for summary tasks.</span></span>
-   <span data-ttu-id="2ddd8-2520">修复了在替换本地资源并启用受保护的工作时，将实际工作错误地转移到企业资源的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2520">Fix an issue where actual work wrongly gets transferred to an enterprise resource when it replaces a local resource and protected work is enabled.</span></span>
-   <span data-ttu-id="2ddd8-2521">修复了如果拥有一个第一列为“任务名称”的表，该列已锁定，单击某项任务后，Project 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2521">Fix an issue where Project crashes if you have a table where the first column is Task Name, the column is locked, and you click on a task.</span></span>
-   <span data-ttu-id="2ddd8-2522">修复了可以通过“任务分配状况”视图将同一资源多次分配到相同任务的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2522">Fix an issue where you can assign the same resource multiple times to the same task through the Task Usage view.</span></span>
-   <span data-ttu-id="2ddd8-2523">修复了打开 XML 文件时，数字自定义字段中的值可能会丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2523">Fix an issue where values in the number custom fields may be lost when opening XML files.</span></span>
-   <span data-ttu-id="2ddd8-2524">修复了顶级任务缩进不正确地从 Project 同步到 SharePoint 任务列表的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2524">Fix an issue where top-level task indentation doesn't sync properly from Project to a SharePoint tasks list.</span></span>
-   <span data-ttu-id="2ddd8-2525">修复了如果从 Excel 工作簿导入任务、资源或分配信息，工作字段中的值可能会被忽略的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2525">Fix an issue where if you import task, resource, or assignment information from an Excel workbook, the values in the work field may be ignored.</span></span>
-   <span data-ttu-id="2ddd8-2526">修复了以下问题：在以 XML 文件格式保存项目时，时间分段的基准值与初始值不匹配。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2526">Fix an issue where timephased Baseline values don't match the initial values when you save a project to the XML file format.</span></span>
-   <span data-ttu-id="2ddd8-2527">修复了以下问题：Project 客户端不会打开项目，因为它认为项目已签出，而实际上并非如此。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2527">Fix an issue where the Project client won't open a project since it thinks the project is checked out when it really isn't.</span></span>
-   <span data-ttu-id="2ddd8-2528">修复了一个问题，使得从高延迟文件服务器打开 Project 文件的速度更快。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2528">Fix an issue so that opening Project files from a file server with high latency open faster.</span></span>

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="2ddd8-2529">Skype for Business：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2529">Skype for Business: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2530">[CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676)：Windows GDI+ 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2530">[CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Windows GDI+ Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2531">[CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695)：图形组件信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2531">[CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): Graphics Component Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2532">[CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696)：Microsoft 图形组件远程代码执行</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2532">[CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Microsoft Graphics Component Remote Code Execution</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="2ddd8-2533">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2533">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2534">添加对话框，解释当阻止特定端口或不允许 IP 时，用户为何无法加入某个会议。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2534">Add dialog explaining why a user is unable to join a meeting when certain ports are blocked or IPs are not allowed.</span></span>
-   <span data-ttu-id="2ddd8-2535">修复了在单击即时消息对话标签页时，持久聊天室中的未读消息会标记为已读的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2535">Fix an issue where unread messages in persistent chat rooms are marked as read when you click IM conversation tabs.</span></span>
-   <span data-ttu-id="2ddd8-2536">修复了传入即时消息 Toast 发生数秒钟延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2536">Fix an issue where incoming IM toasts experience a several second delay.</span></span>
-   <span data-ttu-id="2ddd8-2537">修复了当禁用与 Exchange 同步时，AD 联系人显示为电话号码，而非联系人姓名的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2537">Fix an issue where an AD contact is displayed as a phone number instead of contact name when sync with Exchange is disabled.</span></span>
-   <span data-ttu-id="2ddd8-2538">修复了当禁用联盟，且会议组织者未明确阻止匿名加入时，阻止匿名加入用户加入的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2538">Fix an issue where anonymous join users are blocked from joining when federation is disabled and anonymous join is not explicitly blocked by meeting organizer.</span></span>
-   <span data-ttu-id="2ddd8-2539">修复了对于超出限制的会议，被邀请者人数未正确显示给会议组织者的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2539">Fix an issue where the number of invitees is incorrectly displayed to meeting organizer for meetings that exceed the limit.</span></span>
-   <span data-ttu-id="2ddd8-2540">修复了电话号码未在入站 PSTN 通话上的 Toast 中显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2540">Fix an issue where phone number is not displayed in toast on inbound PSTN calls.</span></span>
-   <span data-ttu-id="2ddd8-2541">修复了在重命名联系人列表组的同时使用 Delete 键时，会删除整个组的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2541">Fix an issue where, when using the Delete key while renaming a contact list group, the entire group is deleted.</span></span>
-   <span data-ttu-id="2ddd8-2542">修复了在共享停止之前，即时消息对话中的共享通知消除的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2542">Fix an issue where the sharing notification in an IM conversation is dismissed before sharing stops.</span></span>
-   <span data-ttu-id="2ddd8-2543">修复了某些非英语语言的登录屏幕为空的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2543">Fix an issue where the sign-in screen is blank for some non-English languages.</span></span>
-   <span data-ttu-id="2ddd8-2544">修复了聊天和聊天历史记录中的非英语字符乱码问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2544">Fix an issue where non-English characters in chat and chat history are garbled.</span></span>
-   <span data-ttu-id="2ddd8-2545">显示组织自动助理处理的来电的呼叫者电话号码（如果用户名未知的话）。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2545">Display the caller's phone number for an incoming call handled by the Organizational Auto Attendant if the user's name isn't known.</span></span>
-   <span data-ttu-id="2ddd8-2546">新增了一个带内设置，允许“任何人(无限制)”限制作为“这些人不必在大厅等待”的选项。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2546">Add an inband setting allowing restriction of "Anyone (no restrictions)"as an option for "These people don't have to wait in the lobby."</span></span>
-   <span data-ttu-id="2ddd8-2547">新增了在 VDIv2 中为 P2P 视频呼叫启用或禁用自拍视频的功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2547">Add ability to turn on or off self-video for P2P video calls in VDIv2.</span></span>
-   <span data-ttu-id="2ddd8-2548">修复了以下问题：呼叫下拉菜单中显示联系人的重复号码。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2548">Fix an issue where duplicate numbers display for contacts in the call drop-down menu.</span></span>
-   <span data-ttu-id="2ddd8-2549">修复了以下问题：删除了在 Skype for Business 和 Skype for Business Basic 之间移动的用户的代理。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2549">Fix an issue where delegates are removed for users who move between Skype for Business and Skype for Business Basic.</span></span>
-   <span data-ttu-id="2ddd8-2550">修复了以下问题：使用“启用显示脱机和自定义状态 URL”客户端策略时，“显示脱机”不可见。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2550">Fix an issue where Appear Offline is not visible when using the Enable Appear Offline and Custom State URL client policies.</span></span>
-   <span data-ttu-id="2ddd8-2551">扩大“会议加入”按钮来修复某些本地化语言的截断问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2551">Widen the Meeting Join button to fix truncation of some localized languages.</span></span>
-   <span data-ttu-id="2ddd8-2552">更加突出显示聊天中重要级别高的消息。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2552">Increase the prominence of High Importance messages in chat.</span></span>
-   <span data-ttu-id="2ddd8-2553">将 Office 和 Skype for Business 文件扩展名类型添加到允许的文件传输阻止列表。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2553">Add Office and Skype for Business file extension types to allowable file transfer blocklists.</span></span>
-   <span data-ttu-id="2ddd8-2554">Outlook 会议邀请中用于会议页脚文本的本地化更正设置为非英语语言。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2554">Localization corrections in Outlook meeting invitations for meeting footer text set in non-English.</span></span>
-   <span data-ttu-id="2ddd8-2555">修复了在多个用户的对话中可切换发送者名称的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2555">Fix an issue where sender names can be switched in conversations of multiple users.</span></span>
-   <span data-ttu-id="2ddd8-2556">修复了在成功加入会议前空白会话窗口无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2556">Fix an issue where the blank conversation window fails to appear until a meeting is joined successfully.</span></span>
-   <span data-ttu-id="2ddd8-2557">修复了以下问题：如果标题字段为空，则联系人卡片中的部门字段信息在搜索结果中为空。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2557">Fix an issue where the department field information in a contact card is empty in search results if the title field is empty.</span></span>
-   <span data-ttu-id="2ddd8-2558">修复了以下问题：防火墙规则导致从本地迁移到在线环境的用户登录失败。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2558">Fix sign-in failures for users migrated from on-premises to online due to firewall rules.</span></span>
-   <span data-ttu-id="2ddd8-2559">添加了新的 DWORD 注册表项以修复以下问题：当用户登录到执行 LyncAutoD 的外部网络上的客户端时，客户端将 OAuthUsed 注册表项重置为 False。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2559">Add a new DWORD registry key to fix an issue where, when a user signs into the client on an external network performing LyncAutoD, the client resets the OAuthUsed registry key to false.</span></span> <span data-ttu-id="2ddd8-2560">若要修复此问题，请将 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>下的 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的值设置为 1。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2560">To fix the issue, set the value to 1 for EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket under HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="2ddd8-2561">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2561">Visio: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-p371">**使用 Excel 数据制作图表：** 通过使用新的数据可视化工具模板，从 Excel 数据自动创建基本流程图或跨职能流程图。 [更多信息](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p371">**Make diagrams from Excel data:** Automatically create a Basic Flowchart or a Cross-Functional Flowchart from Excel data by using new Data Visualizer templates. [More information](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>
-   <span data-ttu-id="2ddd8-p372">**安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p372">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="2ddd8-2567">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2567">Visio: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2568">修复了以下问题：当通过双击文件图标或文件名打开 Visio 文件时，COM 外接程序不接收文档打开事件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2568">Fix an issue where COM add-ins don't receive document opened events when a Visio file is opened by a double-click on a file icon or file name.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="2ddd8-2569">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2569">Word: Feature updates</span></span>
-   <span data-ttu-id="2ddd8-2570">**插入联机图片：** 自动将图像插入用于选择图像和属性信息的新登录页。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2570">**Insert online pictures:** New landing page for selecting images and attribution information is automatically inserted with the image.</span></span>
-   <span data-ttu-id="2ddd8-2571">**替换文字创建：** 基于云的服务在文档中自动生成图片可选文字（替换文字）。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2571">**Alt text creation:** A cloud-based service automatically generates alternative text (alt text) for pictures in a document.</span></span>
-   <span data-ttu-id="2ddd8-2572">**共享文件活动：** 选择文件右上角的“活动”按钮，可以查看在 OneDrive for Business 或 SharePoint 中共享的文经共享、编辑、重命名或恢复的时间。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2572">**Shared file activity:** Choose the Activity button in the upper right corner of the file to see when a file shared in OneDrive for Business or SharePoint was shared, edited, renamed, or restored.</span></span>
-   <span data-ttu-id="2ddd8-p373">**安全链接：** 当用户单击链接时，Office 365 高级威胁防护 (ATP) 会检查此链接并判断它是否是恶意链接。如果认为此链接是恶意链接，则将用户重定向到警告页面而不是原始目标 URL。 [详细信息](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p373">**Safe links:** When a user clicks on a link, Office 365 Advanced Threat Protection (ATP) inspects the link to see if it’s malicious. If the link is deemed malicious, the user is redirected to a warning page instead of the original target URL. [More information](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)</span></span>
-   <span data-ttu-id="2ddd8-p374">**对共享文件做出的更改：** 查看共享文档的更改人，并还原旧版文档。[更多信息](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p374">**Changes in shared files:**  View who has made changes in shared documents, and restore earlier versions. [More information](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-2578">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2578">Word: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2579">[CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2579">[CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2580">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2580">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2581">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2581">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2582">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2582">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2583">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2583">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2584">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2584">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2585">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2585">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2586">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2586">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2587">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2587">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2588">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2588">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2589">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2589">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2590">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2590">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2591">[公告 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2591">[Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office Defense in Depth Update</span></span>
-   <span data-ttu-id="2ddd8-2592">[公告 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2592">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="2ddd8-2593">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2593">Word: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2594">修复了以下问题：如果用户尝试对 OneDrive for Business 上的现有文档执行“另存为”操作，然后又取消保存或尝试合并现有更改，Word 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2594">Fix an issue where Word crashes when a user tries to do a Save As to an existing document on OneDrive for Business and then cancels the save or tries to merge existing changes.</span></span>
-   <span data-ttu-id="2ddd8-p375">修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-p375">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="2ddd8-2597">修复了在用户打开 Word 后立即导航到“插入”选项卡时 Word 挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2597">Fix an issue where Word can hang if the user navigates to the Insert tab shortly after opening Word.</span></span>
-   <span data-ttu-id="2ddd8-2598">修复了在单击边距后，若输入字符，字符会显示在屏幕左上角的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2598">Fix an issue where, after clicking the margin, characters are displayed in the upper left of the screen when entering characters.</span></span>
-   <span data-ttu-id="2ddd8-2599">修复了在打开文档（从版本早于 SharePoint Server 2016 的 SharePoint 服务器打开）的“活动”窗格时，Word 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2599">Fix an issue where Word crashes when opening the Activity pane for a document opened from a SharePoint server older than SharePoint Server 2016.</span></span>
-   <span data-ttu-id="2ddd8-2600">修复了在加载 Grammarly 外接程序时，Word 意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2600">Fix an issue where Word closes unexpectedly while loading the Grammarly add-in.</span></span>
-   <span data-ttu-id="2ddd8-2601">修复了以下问题：在某些情况下，当尝试恢复基于云的文件时，Word 发生故障。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2601">Fix an issue where, under certain conditions, Word crashes while trying to recover cloud-based files.</span></span>
-   <span data-ttu-id="2ddd8-2602">修复了画布中的形状无法旋转的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2602">Fix an issue where shapes within drawing canvas can't be rotated.</span></span>
-   <span data-ttu-id="2ddd8-2603">修复了以下问题：键入朝鲜语时，辅音和元音分隔错误。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2603">Fix an issue where, when typing in Korean, consonants and vowels are incorrectly separated.</span></span>
-   <span data-ttu-id="2ddd8-2604">如果将文档另存为 PDF，则可另存为 PDF 1.7 版本。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2604">Saving a document as a PDF saves the document as a version 1.7 PDF.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2605">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2605">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2606">[CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2606">[CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2607">[CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2607">[CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2608">[CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2608">[CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2609">[CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2609">[CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2610">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2610">[CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2611">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2611">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2612">[公告 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2612">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="2ddd8-2613">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2613">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="2ddd8-2614">针对 Office 365 德国计划，为身份与本地 Active Directory 联合的域用户添加了单一登录 (SSO) 的支持。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2614">Add support for single sign-on (SSO) for domain users for Office 365 Germany plans where the identity is federated with an on-premises Active Directory.</span></span>
-   <span data-ttu-id="2ddd8-2615">添加了防止未成年人获取和激活来自 Office 应用商店的 Office 外接程序的功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2615">Add functionality to prevent minors from acquiring and activating Office Add-ins that come from the Office Store.</span></span>
-   <span data-ttu-id="2ddd8-2616">修复了在动态 DPI 环境下 Office 外接程序缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2616">Fix an issue with zooming and scaling in Office Add-ins under dynamic DPI environment.</span></span>
-   <span data-ttu-id="2ddd8-2617">修复了以下问题：即使当前安装了 Office 365 专业增强版，Office 配置服务提供程序 (CSP) 的 CurrentStatus 节点也会返回空字符串。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2617">Fix an issue where the CurrentStatus node of the Office configuration service provider (CSP) returns an empty string even if Office 365 ProPlus is currently installed.</span></span>
-   <span data-ttu-id="2ddd8-2618">修复了导致 .box 文件格式更改的问题，这些更改会影响安装在同一台计算机上的旧版 Office 的功能，因为 .box 文件在同一台计算机上的所有 Office 应用版本之间共享。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2618">Fix an issue that causes .box file format changes, which impacts functionality of older versions of Office installed on the same computer, because .box files are shared across all versions of an Office app on the same computer.</span></span>
-   <span data-ttu-id="2ddd8-2619">修复了以下问题：在使用共享计算机激活的某些情况下，出现一条错误消息，指示应用遇到错误，阻止其正常工作并询问用户是否运行修复。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2619">Fix an issue where, under certain circumstances when using shared computer activation, an error message appears saying that the app has run into an error that is preventing it from working correctly and asking if the user wants to run a repair.</span></span>
-   <span data-ttu-id="2ddd8-2620">修复了不向用户显示联机修复进度的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2620">Fix an issue where Online Repair progress isn't shown to the user.</span></span>
-   <span data-ttu-id="2ddd8-2621">修复了文件资源管理器中不显示 Office 文件属性的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2621">Fix an issue where Office file properties aren't displayed in File Explorer.</span></span>
-   <span data-ttu-id="2ddd8-2622">修复了以下问题：打开第二个文档时，Office 外接程序按钮从功能区消失。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2622">Fix an issue where Office add-in buttons disappear from the ribbon when there is a second document opened.</span></span>
-   <span data-ttu-id="2ddd8-2623">修复了无法打开一些名称为双字节字符的 VBA 模块的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2623">Fix an issue where some VBA modules which have names with double-byte characters can't be opened.</span></span>
-   <span data-ttu-id="2ddd8-2624">修复了无法显示“新增功能”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2624">Fix an issue that prevents the What's New dialog from appearing.</span></span>
-   <span data-ttu-id="2ddd8-2625">修复了单击“绘图”选项卡导致某些用户的应用程序崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2625">Fix an issue where clicking on the Draw tab causes the application to crash for some users.</span></span>
-   <span data-ttu-id="2ddd8-2626">修复了当鼠标悬停在具有工具提示的公共控件上会导致应用程序崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2626">Fix an issue where hovering over a Common Control that has a tooltip on it causes the application to crash.</span></span>
-   <span data-ttu-id="2ddd8-2627">修复了使用公共控件时出现授权错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2627">Fix an issue where a licensing error message appears when using Common Controls.</span></span>
-   <span data-ttu-id="2ddd8-2628">修复了以下问题：一些程序文件的签名方式存在问题，导致防病毒程序标记这些文件，并且 Windows 信息保护 (WIP) 无法保护或访问数据。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2628">Fix an issue with how some program files are signed, causing anti-virus programs to flag those files as well as problems protecting or accessing data under Windows Information Protection (WIP).</span></span>
-   <span data-ttu-id="2ddd8-2629">添加支持，以允许用户使用 64 位版本的 Office 打开包含 mscomctl.ocx 控件的宏文件。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2629">Add support.to allow users working in 64-bit versions of Office to open macro files that contain mscomctl.ocx controls.</span></span>
-   <span data-ttu-id="2ddd8-2630">改进 mscomctl.ocx 中所使用控件的辅助功能。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2630">Improve accessibility of controls used in mscomctl.ocx.</span></span>
-   <span data-ttu-id="2ddd8-2631">修复了功能区或快速访问工具栏自定义对话框中缺失命令的问题。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2631">Fix an issue where commands are missing from the Ribbon or the Quick Access Toolbar customization dialogs.</span></span>



## <a name="version-1705-january-9"></a><span data-ttu-id="2ddd8-2632">版本 1705：1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2632">Version 1705: January 9</span></span>
<span data-ttu-id="2ddd8-2633">*版本 1705（内部版本 8201.2217）*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2633">*Version 1705 (Build 8201.2217)*</span></span>

<span data-ttu-id="2ddd8-2634">*这是自 2017 年 9 月起就已发布的延期频道版本。2018 年 7 月前，此版本会继续获得支持，并接收安全更新。不过，新版半年频道（即版本 1708，内部版本 8431.2153）现已推出，其中包含新增功能、安全更新和非安全更新。*</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2634">*This is the Deferred Channel release that's been available since September 2017. It will continue to be supported and receive security updates until July 2018. But, a new Semi-Annual Channel release is now available — Version 1708 (Build 8431.2153) — which contains new features, security updates, and non-security updates.*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="2ddd8-2635">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2635">Excel: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2636">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2636">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2637">[公告 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2637">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="2ddd8-2638">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2638">Outlook: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2639">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2639">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2640">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2640">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="2ddd8-2641">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2641">Word: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2642">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2642">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2643">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2643">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2644">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2644">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2645">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2645">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2646">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2646">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2647">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2647">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2648">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2648">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2649">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2649">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2650">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2650">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2651">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2651">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2652">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2652">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="2ddd8-2653">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2653">Office suite: Security updates</span></span>
-   <span data-ttu-id="2ddd8-2654">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2654">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="2ddd8-2655">[公告 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2655">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>


> [!NOTE]
> <span data-ttu-id="2ddd8-2656">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="2ddd8-2656">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>