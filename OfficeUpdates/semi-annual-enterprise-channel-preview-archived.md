---
title: 有关 2019 年半年频道（已设定目标）发行的已存档发行说明
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2019 年 Office 365 专业增强版半年频道（已设定目标）发行的发行说明
ms.openlocfilehash: 72e2402dff445b9ec4b03c7241f93ee85b16bee2
ms.sourcegitcommit: 596cdb3423140df0324a952157fbc39ebedc12b9
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/07/2021
ms.locfileid: "52278119"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="26b59-103">有关半年企业频道（预览）的已存档发行说明</span><span class="sxs-lookup"><span data-stu-id="26b59-103">Archived Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="26b59-104">这些发行说明提供了 Office 365 专业增强版、Visio Pro for Office 365、Project Online 桌面客户端和 Office 365 商业版的半年企业频道（预览）更新中所包含的新功能和非安全更新的相关信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates to Office 365 ProPlus, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="26b59-105">我们经常会过一段时间就将功能（有时甚至是修补程序）发布到半年企业频道（预览）。</span><span class="sxs-lookup"><span data-stu-id="26b59-105">We often roll out features (and sometimes even fixes) to Semi-Annual Enterprise Channel (Preview) over a period of time.</span></span> <span data-ttu-id="26b59-106">如果没有立即看到下述内容，则很快就会看到的。</span><span class="sxs-lookup"><span data-stu-id="26b59-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="26b59-107">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)


## <a name="version-2008-december-08"></a><span data-ttu-id="26b59-108">版本 2008：12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="26b59-108">Version 2008: December 08</span></span>
<span data-ttu-id="26b59-109">*版本 2008（内部版本 13127.20910）*</span><span class="sxs-lookup"><span data-stu-id="26b59-109">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="26b59-110">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-110">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-112">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-112">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="26b59-113">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-113">Access</span></span>

- <span data-ttu-id="26b59-114">我们修复了在尝试使用 ODBC DSN 生成器时的一个错误问题</span><span class="sxs-lookup"><span data-stu-id="26b59-114">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="26b59-115">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-115">Excel</span></span>

- <span data-ttu-id="26b59-116">修复了以下问题：无法编辑从 Project 计划导出的数据透视表，并且无法保存相同情况下的工作簿。</span><span class="sxs-lookup"><span data-stu-id="26b59-116">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="26b59-117">我们修复了以下问题：在某些情况下，在只读模式下打开文件时，会显示多个消息栏。</span><span class="sxs-lookup"><span data-stu-id="26b59-117">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="26b59-118">我们修复了以下问题：当存在多个重复的列标题值时，大纲小计可能会停止运转。</span><span class="sxs-lookup"><span data-stu-id="26b59-118">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="26b59-119">我们修复了以下问题：当发生组策略对象更新（例如，通过远程组策略刷新）时，Excel 会停止运行。</span><span class="sxs-lookup"><span data-stu-id="26b59-119">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="26b59-120">我们修复了以下问题：当用户在超过 255 个列中使用小计函数时，Excel 会停止运行。</span><span class="sxs-lookup"><span data-stu-id="26b59-120">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="26b59-121">当从 Excel 中复制内容并使用“嵌入”选项粘贴到 PowerPoint 时，改进了 PowerPoint 中的文本间距调整。</span><span class="sxs-lookup"><span data-stu-id="26b59-121">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="26b59-122">修复了导致在 PowerPivot 中无法从“表预览”和“查询编辑器”进行切换的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-122">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="26b59-123">修复了用户无法直接从 SharePoint 打开 atomsvc (UTF8+BOM) 文件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-123">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="26b59-124">我们修复了一个问题，现在 Power Pivot 将能够成功识别制表符分隔符。</span><span class="sxs-lookup"><span data-stu-id="26b59-124">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="26b59-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-125">Outlook</span></span>

- <span data-ttu-id="26b59-126">我们修复了在发送任务状态报告时导致“收件人:”字段为空的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-126">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="26b59-127">我们修复了导致 MailItem.BeforeAttachmentAdd 事件被破坏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-127">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="26b59-128">我们修复了导致某些用户在从 Outlook 以外的应用程序中发送 Outlook 邮件时遇到应用程序意外关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-128">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="26b59-129">我们修复了以下问题：在联机模式下，当用户在文件夹之间移动多个邮件项目时，性能会下降。</span><span class="sxs-lookup"><span data-stu-id="26b59-129">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="26b59-130">我们添加了一个 regkey，允许客户在 IDataObject 操作（例如，拖放、剪贴板）中禁用附件的 filetime 包含。</span><span class="sxs-lookup"><span data-stu-id="26b59-130">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="26b59-131">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = 排除 filetime  1 =（默认）包含 filetime</span><span class="sxs-lookup"><span data-stu-id="26b59-131">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="26b59-132">我们修复了以下问题：当回复带有来自 Azure 信息保护的保护标签的邮件时，将导致嵌入式图像消失。</span><span class="sxs-lookup"><span data-stu-id="26b59-132">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="26b59-133">我们修复了以下问题：在发送受 Azure 保护的语音邮件时，用户名显示为电话号码，从而导致 Outlook 桌面用户无法打开来自外部用户的语音邮件。</span><span class="sxs-lookup"><span data-stu-id="26b59-133">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="26b59-134">我们修复了以下问题：设置 OME 配置时会在邮件项目上添加一个无关的附件，这会迫使 Outlook 对邮件进行加密，即使在服务端设置了 DecryptAttachmentsForEncryptOnly 选项也是如此。</span><span class="sxs-lookup"><span data-stu-id="26b59-134">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="26b59-135">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-135">PowerPoint</span></span>

- <span data-ttu-id="26b59-136">修复了以下问题：当用户将源路径更改为本地 OneDrive 文件夹时，链接的 excel 图表出现错误地更改为 excel 工作表。</span><span class="sxs-lookup"><span data-stu-id="26b59-136">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="26b59-137">我们修复了导致功能“欢迎回来!</span><span class="sxs-lookup"><span data-stu-id="26b59-137">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="26b59-138">从在办公室中离开的位置开始”在 PowerPoint 中不起作用的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-138">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="26b59-139">Visio</span><span class="sxs-lookup"><span data-stu-id="26b59-139">Visio</span></span>

- <span data-ttu-id="26b59-140">我们修复了一个问题，用户以后可以使用 Visio for Office 365 中的连接器创建自定义 Visio 模具和内置模板的直线。</span><span class="sxs-lookup"><span data-stu-id="26b59-140">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="26b59-141">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-141">Word</span></span>

- <span data-ttu-id="26b59-142">我们修复了将文档保存为 HTML 格式时长链接无法换行的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-142">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="26b59-143">我们修复了以下问题：如果你回复在扩展列表中具有未知扩展的父级评论，则回复将获得这些相同的扩展。</span><span class="sxs-lookup"><span data-stu-id="26b59-143">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="26b59-144">我们修复了 Outlook 邮件设置为“不要转发”的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-144">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="26b59-145">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-145">Office Suite</span></span>

- <span data-ttu-id="26b59-146">解决了导致用户在已禁用 ADAL 时无法导入 SPO 列表的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-146">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-november-10"></a><span data-ttu-id="26b59-148">版本 2008：11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="26b59-148">Version 2008: November 10</span></span>
<span data-ttu-id="26b59-149">*版本 2008（内部版本 13127.20760）*</span><span class="sxs-lookup"><span data-stu-id="26b59-149">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="26b59-150">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-150">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-152">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-152">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="26b59-153">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-153">Excel</span></span>

- <span data-ttu-id="26b59-154">解决了某些函数在加载工作簿后可能出现错误结果的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-154">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="26b59-155">解决了与 XLAM 加载项引用和命名范围相关的应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-155">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="26b59-156">我们解决了以下问题：使用宏设置区域的 FormulaR1C1 属性时，如果图表工作表是活动工作表，则单元格引用将不正确。</span><span class="sxs-lookup"><span data-stu-id="26b59-156">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="26b59-157">解决了可能导致“Excel 在尝试计算一个或多个公式时用尽资源”错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-157">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="26b59-158">修复了将 Office 语言设置为西班牙语时出现的问题，在有问题的情况下，数据验证列表可能不会显示列表中的所有项目。</span><span class="sxs-lookup"><span data-stu-id="26b59-158">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="26b59-159">解决了在刷新 OLAP 数据透视表时可能会导致挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-159">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-160">Outlook</span></span>

- <span data-ttu-id="26b59-161">我们修复了以下问题：现在用户可以禁用 Outlook 的 IRM （信息权限管理），而无需在其他 Office 应用程序中禁用它。</span><span class="sxs-lookup"><span data-stu-id="26b59-161">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="26b59-162">解决了导致用户无法向其代理授予编辑器权限的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-162">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="26b59-163">解决了导致用户在选择搜索结果时遇到应用程序意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-163">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="26b59-164">解决了导致在组日历中搜索无法返回任何结果的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-164">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="26b59-165">解决了导致代理在其他邮箱中打开共享文件夹时出现间歇性故障的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-165">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="26b59-166">解决了当主题行为空白时，某些自动生成的电子邮件将发送空白正文的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-166">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="26b59-167">解决了导致在答复或转发时中文电子邮件的标题出现乱码的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-167">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="26b59-168">解决了可选的连接体验阻止加载 Web 加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-168">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="26b59-169">在[博客文章](https://developer.microsoft.com/zh-CN/office/blogs/outlook-add-ins-and-optional-connected-experiences/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-169">See details in [blog post](https://developer.microsoft.com/zh-CN/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="26b59-170">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-170">PowerPoint</span></span>

- <span data-ttu-id="26b59-171">解决了 Forms 内容加载项在插入后不显示，而要到用户单击另一张幻灯片来使其放映时才显示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-171">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="26b59-172">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-172">Office Suite</span></span>

- <span data-ttu-id="26b59-173">解决了使用 Microsoft 365 端点数据丢失防护利用 System Center Configuration Manager 或其他 Office Update 管理工具的商业客户的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-173">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="26b59-174">解决了 Office 加载项的消息传递 API 无法正常工作的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-174">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (请勿删除错误详细信息内容结尾)

## <a name="version-2008-october-13"></a><span data-ttu-id="26b59-176">版本 2008：10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="26b59-176">Version 2008: October 13</span></span>
<span data-ttu-id="26b59-177">*版本 2008（内部版本 13127.20638）*</span><span class="sxs-lookup"><span data-stu-id="26b59-177">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="26b59-178">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-178">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-180">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-180">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-181">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-181">Excel</span></span>

- <span data-ttu-id="26b59-182">修复了 PivotDateFilter API 中“Before”和“After”筛选条件被颠倒的错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-182">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="26b59-183">修复了用户无法修改数据透视表筛选器的问题，因为它被设置为在 Analysis Services 数据库中已不存在的值。</span><span class="sxs-lookup"><span data-stu-id="26b59-183">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="26b59-184">修复了以下问题：在冻结工作表首行后使用快速分析时，Excel 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-184">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="26b59-185">修复了以下问题：如果工作簿包含使用 IFNA() 的公式，则可能导致有关损坏的工作簿的警告。</span><span class="sxs-lookup"><span data-stu-id="26b59-185">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="26b59-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-186">Outlook</span></span>

- <span data-ttu-id="26b59-187">解决了以下问题：用户单击角落的“X”无法关闭共享日历。</span><span class="sxs-lookup"><span data-stu-id="26b59-187">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="26b59-188">解决了导致“打开共享的日历改进项”设置有时无法应用于现有共享日历的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-188">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="26b59-189">解决了导致用户在打开云附件时在安全链接页面（而不是试图打开的文档）上看到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-189">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="26b59-190">解决附件上传的性能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-190">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="26b59-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-191">PowerPoint</span></span>

- <span data-ttu-id="26b59-192">此更改解决了单击“导出到动态 GIF”功能的“导出”按钮后，并未成功导出的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-192">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="26b59-193">安全性修补程序解决了在受保护视图中打开 PowerPoint 文件时禁用 IRM 保护的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-193">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="26b59-194">我们修复了操作设置对话框中导致 PowerPoint 应用崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-194">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="26b59-195">Visio</span><span class="sxs-lookup"><span data-stu-id="26b59-195">Visio</span></span>

- <span data-ttu-id="26b59-196">修复了导致 Live 预览在文本对齐时崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-196">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="26b59-197">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-197">Word</span></span>

- <span data-ttu-id="26b59-198">修复了用户打开某些很大的邮件时会遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-198">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="26b59-199">我们修复了用户在打开文档时可能遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-199">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="26b59-200">解决了可能在启动 Word 时导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-200">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="26b59-201">我们修复了“样式库”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-201">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="26b59-202">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-202">Office Suite</span></span>

- <span data-ttu-id="26b59-p104">当用户在办公室的喷墨打印机上打印任何文档/文件，并且打印机墨水不足时，即使喷墨打印机不需要碳粉，也会显示 "碳粉不足 "或 "无碳粉 "的信息。将信息更改为显示“碳粉/墨水不足”&“无碳粉/墨水”。</span><span class="sxs-lookup"><span data-stu-id="26b59-p104">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="26b59-205">修复了使用 GIF/动画模型 3D 时空闲的高 CPU 使用率</span><span class="sxs-lookup"><span data-stu-id="26b59-205">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="26b59-206">此更改解决了启动 Office 应用时由于无法加载 d2d1 而出现的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-206">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2008-september-08"></a><span data-ttu-id="26b59-208">版本 2008：9 月 8 日</span><span class="sxs-lookup"><span data-stu-id="26b59-208">Version 2008: September 08</span></span>
<span data-ttu-id="26b59-209">*版本 2008（内部版本 13127.20408）*</span><span class="sxs-lookup"><span data-stu-id="26b59-209">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="26b59-210">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-210">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="26b59-212">功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-212">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="26b59-213">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-213">Access</span></span>

- <span data-ttu-id="26b59-214">**在“查询设计器”、“SQL 视图”和“关系”窗口中更高效地工作：** 右键单击表格，以对其进行打开、设计、调整大小和隐藏操作。</span><span class="sxs-lookup"><span data-stu-id="26b59-214">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="26b59-215">在 SQL 视图中搜索和替换文本。</span><span class="sxs-lookup"><span data-stu-id="26b59-215">Search and replace text in SQL View.</span></span> <span data-ttu-id="26b59-216">在“关系”窗口中选择多个表。</span><span class="sxs-lookup"><span data-stu-id="26b59-216">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="26b59-217">**单击几下即可添加表：** 使用“添加表”任务窗格（在你工作时一直打开）向关系和查询添加表。</span><span class="sxs-lookup"><span data-stu-id="26b59-217">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="26b59-218">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-218">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="26b59-219">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-219">Excel</span></span>

- <span data-ttu-id="26b59-220">**改进的地图图表：** 我们改进了地图图表，将其与 Excel 的地理数据类型相集成，可显示有关地图位置的丰富信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-220">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="26b59-221">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-221">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="26b59-222">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="26b59-222">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="26b59-223">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-223">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="26b59-224">**在 Excel 中从 Power BI 中的数据集创建数据透视表：** 你可以在 Excel 中创建连接到 Power BI 中存储的数据集的数据透视表，只需点击几下鼠标。</span><span class="sxs-lookup"><span data-stu-id="26b59-224">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="26b59-225">这样做可以让你更好地利用数据透视表和 Power BI。</span><span class="sxs-lookup"><span data-stu-id="26b59-225">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="26b59-226">使用数据透视表从你的安全的 Power BI 数据集计算、总结和分析数据。</span><span class="sxs-lookup"><span data-stu-id="26b59-226">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="26b59-227">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-227">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="26b59-228">在[博客文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-228">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="26b59-229">**你喜爱的 Excel 函数运行速度更快：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函数运行速度比以往更快。</span><span class="sxs-lookup"><span data-stu-id="26b59-229">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="26b59-230">更快达到底线。</span><span class="sxs-lookup"><span data-stu-id="26b59-230">Get to the bottom line more quickly.</span></span> <span data-ttu-id="26b59-231">立即试用。</span><span class="sxs-lookup"><span data-stu-id="26b59-231">Try one now.</span></span>

- <span data-ttu-id="26b59-232">**Realtimedata (RTD) 改进：** 在 Office 365 版本 2002 每月频道或更高版本中，Excel 的 RealTimeData (RTD) 函数要比 Excel 2010 计算电子表格中的数据的速度快得多。</span><span class="sxs-lookup"><span data-stu-id="26b59-232">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="26b59-233">我们在其基本内存和数据结构中删除瓶颈，并使其变得线程安全，这能允许其在 多线程计算 (MTR) 的所有可用线程上进行计算。</span><span class="sxs-lookup"><span data-stu-id="26b59-233">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-234">Outlook</span></span>

- <span data-ttu-id="26b59-235">**共享日历更新速度更快：** 对于 Office 365 中的共享日历，Outlook 可以使用 REST API 更新这些日历。</span><span class="sxs-lookup"><span data-stu-id="26b59-235">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="26b59-236">打开预览，更快速、更可靠地更新共享日历。</span><span class="sxs-lookup"><span data-stu-id="26b59-236">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="26b59-237">**更好的结果 - 瞬间完成：** 我们更新了搜索体验，使其更加智能、更快速，并且比以往更可靠。</span><span class="sxs-lookup"><span data-stu-id="26b59-237">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="26b59-238">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-238">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="26b59-239">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="26b59-239">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="26b59-240">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-240">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="26b59-241">**将电子邮件拖动到你拥有的组：** 通过从收件箱中拖动来移动和复制邮件和对话。</span><span class="sxs-lookup"><span data-stu-id="26b59-241">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="26b59-242">将与所有组成员共享你拖动的消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-242">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="26b59-243">在[博客文章](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-243">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="26b59-244">**改进日历：** 可查看视觉对象更新，以便更轻松地扫描日历。</span><span class="sxs-lookup"><span data-stu-id="26b59-244">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="26b59-245">了解更多详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-245">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="26b59-246">在[博客文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-246">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="26b59-247">**不退出收件箱加入会议：** 无需切换至日历以加入联机会议。</span><span class="sxs-lookup"><span data-stu-id="26b59-247">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="26b59-248">通过固定日历至待办事项窗格，只需单机一次即可加入任何会议。</span><span class="sxs-lookup"><span data-stu-id="26b59-248">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="26b59-249">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-249">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="26b59-250">**强制 wifi 网络新体验：** 是否已加入需要使用网页登录的 wifi 网络？</span><span class="sxs-lookup"><span data-stu-id="26b59-250">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="26b59-251">现在，Outlook 检测到这一点，帮助你进行连接。</span><span class="sxs-lookup"><span data-stu-id="26b59-251">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="26b59-252">在[博客文章](https://insider.office.com/zh-CN/blog/outlook-on-public-wi-fi-networks-just-got-easier)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-252">See details in [blog post](https://insider.office.com/zh-CN/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="26b59-253">**搜索某个人时获取电子邮件建议：** 在“搜索”框中键入某人姓名时，最相关的电子邮件信息将包含在搜索建议中。</span><span class="sxs-lookup"><span data-stu-id="26b59-253">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="26b59-254">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-254">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="26b59-255">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-255">PowerPoint</span></span>

- <span data-ttu-id="26b59-p118">**通过 \@提及吸引同事的注意力：** 在注释中使用 @提及，以在需要同事的意见时让他们知悉。[了解详细信息](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="26b59-p118">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>

- <span data-ttu-id="26b59-258">**改进的地图图表：** 我们改进了地图图表，将其与 Excel 的地理数据类型相集成，可显示有关地图位置的丰富信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-258">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="26b59-259">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-259">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="26b59-260">**GIF 瞬间完成：** 一幻灯片、一帧。</span><span class="sxs-lookup"><span data-stu-id="26b59-260">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="26b59-261">轻松在 PowerPoint 中创建循环 GIF。</span><span class="sxs-lookup"><span data-stu-id="26b59-261">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="26b59-262">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-262">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="26b59-263">在[博客文章](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-263">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="26b59-264">**更好的图表：** 有了更好的连接器和更流程的墨迹转换过程，你可以更轻松用墨迹表达你的想法。</span><span class="sxs-lookup"><span data-stu-id="26b59-264">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="26b59-265">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-265">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="26b59-266">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="26b59-266">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="26b59-267">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-267">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="26b59-268">**批注**：PowerPoint 中新的批注体验使你可以快速、轻松地发现批注并将其添加到文档中。</span><span class="sxs-lookup"><span data-stu-id="26b59-268">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="26b59-269">通过批注锚定、解决、任务、改进的提及通知等新功能实现协作工作流现代化。</span><span class="sxs-lookup"><span data-stu-id="26b59-269">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="26b59-270">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-270">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="26b59-271">**演示时同步所做的更改：** 即使演示文稿处于幻灯片放映模式，只要进行了更改就同步这些更改。</span><span class="sxs-lookup"><span data-stu-id="26b59-271">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="26b59-272">了解更多详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-272">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="26b59-273">在[博客文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-273">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="26b59-274">**指向幻灯片的链接：** 让同事参与幻灯片的创作，让其直接转到你需要帮助的幻灯片上。</span><span class="sxs-lookup"><span data-stu-id="26b59-274">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="26b59-275">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-275">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="26b59-276">在[博客文章](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-276">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="26b59-277">**改进了 PowerPoint 的流视频性能：** 我们对 Microsoft Stream 视频的回放性能进行了改进，以最小化视频加载时间，创造流畅的观看体验。</span><span class="sxs-lookup"><span data-stu-id="26b59-277">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="26b59-278">使用来自 Microsoft Stream 的企业视频来创建更好的演示文稿。</span><span class="sxs-lookup"><span data-stu-id="26b59-278">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="26b59-279">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-279">Word</span></span>

- <span data-ttu-id="26b59-280">**改进的地图图表：** 我们改进了地图图表，将其与 Excel 的地理数据类型相集成，可显示有关地图位置的丰富信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-280">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="26b59-281">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-281">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="26b59-282">**用套索选择墨迹：**“绘图”选项卡上的“套索”工具可帮助你选择用墨迹绘制的对象。</span><span class="sxs-lookup"><span data-stu-id="26b59-282">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="26b59-283">选择单独的笔划或整个字。</span><span class="sxs-lookup"><span data-stu-id="26b59-283">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="26b59-284">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-284">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="26b59-285">**选取完美颜色：** 使用十六进制颜色代码选择字体和文本突出显示等所需的精确颜色。</span><span class="sxs-lookup"><span data-stu-id="26b59-285">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="26b59-286">在[博客文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-286">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="26b59-287">**屏幕阅读器中的操作确认：** 操作的确认是辅助功能一项重要的要求。</span><span class="sxs-lookup"><span data-stu-id="26b59-287">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="26b59-288">随着 Windows 引入新的通知 API ，我们现在可以提醒屏幕阅读器用户的操作成功情况。</span><span class="sxs-lookup"><span data-stu-id="26b59-288">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="26b59-289">剪切、复制、粘贴、加粗、斜体、下划线、撤消、重做、自动更正、自动大小写等功能，现在都已向Win32 Word"讲述人"用户公布。</span><span class="sxs-lookup"><span data-stu-id="26b59-289">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="26b59-290">若要启用此功能，请按 windows + ctrl + enter 启用 "讲述人"。</span><span class="sxs-lookup"><span data-stu-id="26b59-290">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="26b59-291">在[博客文章](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)中查看详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-291">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-292">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-292">Office Suite</span></span>

- <span data-ttu-id="26b59-293">**敏感度标签：** 你现在可以应用组织已配置的敏感度标签来提示自定义权限。</span><span class="sxs-lookup"><span data-stu-id="26b59-293">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-296">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-296">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="26b59-297">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-297">Access</span></span>

- <span data-ttu-id="26b59-298">解决了插入包含身份（例如自动编号）字段的关联 SQL 表的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-298">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="26b59-299">我们修复了一个问题，即执行查询大约花费两倍于预期完成时间。</span><span class="sxs-lookup"><span data-stu-id="26b59-299">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="26b59-300">修正了一个问题，以便能够在应用不会出现任何故障的情况下将日期/时间扩展数据类型调用到代码中。</span><span class="sxs-lookup"><span data-stu-id="26b59-300">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="26b59-301">修正了一个问题，现在可以还原到最近更新的 Access 版本，并可使用 DAO/VBA 管理和编辑十进制数据类型。</span><span class="sxs-lookup"><span data-stu-id="26b59-301">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="26b59-302">此修复解决了之前尝试运行某些查询时产生 "查询太复杂 "的错误信息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-302">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="26b59-303">Access 已修复此当前问题，但将通过调查我们的其他界面来确保不会持续出现此问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-303">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="26b59-304">团队将向你通报未来的更新；非常感谢你的耐心等待。</span><span class="sxs-lookup"><span data-stu-id="26b59-304">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="26b59-305">这个问题已经得到解决 - 现在，你可以在 Office 的即点即用应用程序之外使用我们的 ODBC 驱动程序。</span><span class="sxs-lookup"><span data-stu-id="26b59-305">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="26b59-306">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-306">Excel</span></span>

- <span data-ttu-id="26b59-307">处于只读模式的工作簿可能已发生自动文档分类。</span><span class="sxs-lookup"><span data-stu-id="26b59-307">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="26b59-308">修复了当你已从帐户注销时尝试创建数据连接时可能发生的故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-308">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="26b59-309">解决了在试图将数据透视表插入图表工作表时 Excel 可能故障的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-309">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="26b59-310">尝试使用 LET() 函数保存包含公式的文件时，可能会出现错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-310">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="26b59-311">解决了某些情况下使用格式刷时 Excel 可能会崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-311">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="26b59-312">修正了以下问题：保存到 SharePoint / OneDrive 时，自定义功能区标签的CustomUI XML被删除。</span><span class="sxs-lookup"><span data-stu-id="26b59-312">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="26b59-313">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-313">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="26b59-314">修复了以下问题：在某些情况下，单击指向同一工作簿内某个位置的超链接将导致工作簿被隐藏。</span><span class="sxs-lookup"><span data-stu-id="26b59-314">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="26b59-315">修复了以下问题：在文件重新打开后，如果文件路径太长，外部链接会停止工作。</span><span class="sxs-lookup"><span data-stu-id="26b59-315">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="26b59-316">Application.Evaluate (VBA) 在某些情况下不能用于用户定义的功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-316">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="26b59-317">在当前版本的 Excel 中打开在 Excel 2016 保存含有数字签名的工作簿时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="26b59-317">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="26b59-318">修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-318">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="26b59-319">这解决了以下问题：由 SQL 数据提供程序在 Office 的较早版本中创建的连接将内部表属性设置为与 Office 365 不同。</span><span class="sxs-lookup"><span data-stu-id="26b59-319">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="26b59-320">这会导致对于包含在旧版本的 Office 中创建的连接的文件，使用 Office 365 打开时，表预览/查询编辑器下拉列表被禁用。</span><span class="sxs-lookup"><span data-stu-id="26b59-320">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="26b59-321">解决了如果关闭了源代码簿，则外部链接不会在填充时更新的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-321">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="26b59-322">解决了墨迹书写可能会导致 Excel 停止响应的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-322">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="26b59-323">OneNote</span><span class="sxs-lookup"><span data-stu-id="26b59-323">OneNote</span></span>

- <span data-ttu-id="26b59-324">通知用户有关 Microsoft OneNote 中的暂时调整的信息栏，可有助于提升全球范围内使用期间的同步和服务可用性。</span><span class="sxs-lookup"><span data-stu-id="26b59-324">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="26b59-325">通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-325">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="26b59-326">改进对共同创作状态的检测，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="26b59-326">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="26b59-327">在 OneNote 2016 中，通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-327">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="26b59-328">对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入OneNote。</span><span class="sxs-lookup"><span data-stu-id="26b59-328">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="26b59-329">通过暂时禁用 OneNote 2016 中的应用内视频录制功能，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-329">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="26b59-330">本地笔记本不受此措施影响。</span><span class="sxs-lookup"><span data-stu-id="26b59-330">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="26b59-331">通过临时更改页面版本历史记录的创建频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-331">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="26b59-332">通过暂时禁用将页面移动到回收站来提升同步和服务器稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-332">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="26b59-333">希望删除页面的用户将改为显示一个对话框，询问用户是否想要永久删除页面。</span><span class="sxs-lookup"><span data-stu-id="26b59-333">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-334">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-334">Outlook</span></span>

- <span data-ttu-id="26b59-335">修复了导致尝试从添加到其个人资料的辅助帐户创建会议请求的用户看不到空白的“发件人：”字段，而是看到自己的电子邮件地址的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-335">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="26b59-336">修复了导致用户无法在添加共享邮箱后连接到公用文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-336">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="26b59-337">解决了导致在某些情况下，无法在代理拒绝会议时将其从经理的日历中删除的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-337">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="26b59-338">解决了共享日历改进功能的部分用户无法查看新添加的共享日历的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-338">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="26b59-339">修复了导致用户在与云附件交互时偶尔出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-339">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="26b59-340">解决了导致 CLP 用户在将回复的地址从受保护的上下文切换到不受保护的上下文时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-340">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="26b59-341">解决了针对 Outlook 未能向使用M365 Business Plus计划的付费用户启用数据丢失保护策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-341">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="26b59-342">解决了关于回复/转发标签的clp审核事件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-342">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="26b59-343">解决了导致文件夹窗格宽度意外改变的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-343">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="26b59-344">解决了导致用户看到通过拖放复制到其文件系统的附件的创建日期设置为 4501 年 1 月 1 日的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-344">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="26b59-345">解决了导致某些字符集的用户在向 SharePoint 文件添加智能链接时无法正确显示文件名的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-345">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="26b59-346">解决了导致用户在更新 Outlook 中的“规则”时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-346">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="26b59-347">解决了导致 Outlook 无法检索搜索建议的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-347">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="26b59-348">解决了导致共享日历改进用户看到日历故障的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-348">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="26b59-349">解决了导致用户在某些情况下遇到间歇性挂起和崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-349">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="26b59-350">解决了通过选中 "仅下载邮件头" 选项删除来自 POP 帐户的4个或更多电子邮件时导致用户遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-350">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="26b59-351">解决了未选中“下载共享”文件夹时导致共享日历会议“响应选项”中缺少“允许转发”选项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-351">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="26b59-352">解决了导致在编辑经理日历上的现有日历约会时，代表收到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-352">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="26b59-353">解决了用户在第三方 MAPI 应用程序中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-353">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="26b59-354">解决了 Windows 更新后导致 Outlook 在打开本地保存的 .msg 或 .oft 文件时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-354">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="26b59-355">解决了导致 Outlook 在某些版本的 Windows 上崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-355">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="26b59-356">解决了导致 Windows 10 服务器版本的用户看到警告“防病毒状态：无效”的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-356">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="26b59-357">此版本的 Windows 支持防病毒检测，但没有发现防病毒”，尽管这些用户已正确安装防病毒。</span><span class="sxs-lookup"><span data-stu-id="26b59-357">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="26b59-358">解决了 Windows 更新后导致 Outlook 在打开本地保存的 .msg 或 .oft 文件时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-358">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="26b59-359">解决了导致 Outlook 在某些版本的 Windows 上崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-359">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="26b59-360">解决了导致用户看到 Outlook 不断提示他们运行收件箱修复工具的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-360">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="26b59-361">解决了在使用鼠标上的 "X" 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-361">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="26b59-362">解决了用户在安全对话框中选择”save” 选项时无法将 OneDrive 附件从租户外部保存到本地计算机的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-362">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="26b59-363">解决了导致日程安排助理页面无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-363">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="26b59-364">解决了导致“日程安排助理”页面无法显示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-364">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="26b59-365">解决了导致用户在检索角色信息时偶尔会崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-365">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="26b59-366">修复了导致用户在编辑收件人时偶尔出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-366">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="26b59-367">修复了导致用户在使用压缩视图时出现异常的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-367">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="26b59-368">解决了导致 Outlook 用户在紧凑视图中导航时出现错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-368">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="26b59-369">解决了导致右键单击上下文菜单无法在搜索控件中显示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-369">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="26b59-370">解决了导致用户在答复或撰写新的电子邮件时收到错误的问题，其中该错误显示“此网页中的部分文件不在预期位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-370">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="26b59-371">是否仍要下载它们？</span><span class="sxs-lookup"><span data-stu-id="26b59-371">Do you want to download them anyway?</span></span> <span data-ttu-id="26b59-372">如果确定此网页来自可靠来源，请单击‘是’”</span><span class="sxs-lookup"><span data-stu-id="26b59-372">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="26b59-373">解决了导致用户在退出 Outlook 时遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-373">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="26b59-374">解决导致在中搜索功能的问题，该问题建议一项功能返回没有结果，使用户没有选择提交一个新功能想法。</span><span class="sxs-lookup"><span data-stu-id="26b59-374">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="26b59-375">解决了导致事件通知警报出现格式问题的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-375">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="26b59-376">解决了用户在提交来自管理通知的反馈时故障的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-376">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="26b59-377">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-377">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="26b59-378">修复了导致用户在编辑收件人时偶尔出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-378">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="26b59-379">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-379">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="26b59-380">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-380">PowerPoint</span></span>

- <span data-ttu-id="26b59-381">解决了当用户在文件中同时拥有现代和遗留评论时的故障，从而触发对评论的升级。</span><span class="sxs-lookup"><span data-stu-id="26b59-381">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="26b59-382">修复了 PowerPoint 应用崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-382">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="26b59-383">我们已修正了“建议”窗格崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-383">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="26b59-384">Project</span><span class="sxs-lookup"><span data-stu-id="26b59-384">Project</span></span>

- <span data-ttu-id="26b59-385">解决了以下问题：在窗体视图中编辑前置/后续数据时，会触发额外的 ProjectBeforeTaskChangeevent 事件。</span><span class="sxs-lookup"><span data-stu-id="26b59-385">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="26b59-386">解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-386">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="26b59-387">修复了下列问题：启用保护实际工作的设置后，用户无法输入按时间分段的基准工作。</span><span class="sxs-lookup"><span data-stu-id="26b59-387">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="26b59-388">解决了以下问题：在标记为完成后，任务完成百分比错误地更改为小于 100% 完成。</span><span class="sxs-lookup"><span data-stu-id="26b59-388">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="26b59-389">修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。</span><span class="sxs-lookup"><span data-stu-id="26b59-389">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="26b59-390">修复了有时无法正确计算摘要任务日期的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-390">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="26b59-391">解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="26b59-391">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="26b59-392">修复了以下问题：如果你使用的是连接到 Project Web App 的 Project，并且小数分隔符是逗号，则当你尝试向依赖项添加延迟时，TaskDependencies Add 方法将失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-392">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="26b59-393">修复了以下问题：如果 URL 以 ".com" 结尾，则无法在 Project 桌面端 Project Web App 中打开项目。</span><span class="sxs-lookup"><span data-stu-id="26b59-393">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="26b59-394">修复了如果粘贴具有多个依赖项的任务，并不能正确复制所有依赖项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-394">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="26b59-395">修正了无法将PDF/XPS从项目保存到 SharePoint 文档库的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-395">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="26b59-396">修正了当任务被错误地标记为100%完成，将其更改为小于100%完成的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-396">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="26b59-397">修正了当项目摘要任务(项目开始/任务字段)发生更改时，ProjectBeforeTaskChange事件没有触发的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-397">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="26b59-398">修复了在资源定义了多个成本费率表时，其余成本有时计算有误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-398">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="26b59-399">修复了与 SharePoint 任务列表连接的项目的项目完成日期无法更新的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-399">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="26b59-400">修复了以下问题：分配资源对话框中，选择的任务与任务板视图中选择的任务不一样。</span><span class="sxs-lookup"><span data-stu-id="26b59-400">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="26b59-401">修复了无法打开已进入错误状态的项目的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-401">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="26b59-402">Skype</span><span class="sxs-lookup"><span data-stu-id="26b59-402">Skype</span></span>

- <span data-ttu-id="26b59-403">当用户被告知只能使用团队的策略时，他们仍然可以使用Skype for Business Outlook 插件来安排会议。</span><span class="sxs-lookup"><span data-stu-id="26b59-403">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="26b59-404">在此更新之后，当客户端读取指示用户为仅限团队的策略并进入仅限会议加入模式后，你将不再能够为Skype安排商务会议。</span><span class="sxs-lookup"><span data-stu-id="26b59-404">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="26b59-405">另外，如果 Skype for Business Outlook 插件在启动时看到 Skype for Business客户端处于会议加入模式，它将不会激活自己。</span><span class="sxs-lookup"><span data-stu-id="26b59-405">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="26b59-406">已将跳舞表情符号肤色改为中性。</span><span class="sxs-lookup"><span data-stu-id="26b59-406">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-407">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-407">Word</span></span>

- <span data-ttu-id="26b59-408">解决了当URL包含查询组件时从自定义文档传递(aspx)打开Word文档的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-408">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="26b59-409">此更改修复了以下问题：在上一次共同创作会话后，Office 应用程序可能会陷入静默的保存失败状态。</span><span class="sxs-lookup"><span data-stu-id="26b59-409">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="26b59-410">解决了用户在答复电子邮件或撰写新电子邮件时软件崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-410">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="26b59-411">解决了在使用鼠标上的 "X" 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-411">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="26b59-412">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-412">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="26b59-413">解决了以下问题：在调整形状的大小时，用户可能会丢失内容。</span><span class="sxs-lookup"><span data-stu-id="26b59-413">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="26b59-414">我们修复了未使用普通样式更新基准样式的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-414">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="26b59-415">我们修复了宏 AutoOpen 在 AutoExec 之前运行的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-415">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="26b59-416">我们修复了有关复制和粘贴 SVG 图像的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-416">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="26b59-417">解决了可能导致在拖动应用中的某些内容时发生故障的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-417">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="26b59-418">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-418">Office Suite</span></span>

- <span data-ttu-id="26b59-p137">对于旧的、非基于网络服务的共享窗格，在共享窗格处于打开时关闭文档可能会导致崩溃。此问题已修复。</span><span class="sxs-lookup"><span data-stu-id="26b59-p137">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.</span></span>

- <span data-ttu-id="26b59-421">修复了关闭 Office 文件时可能会导致崩溃的计时问题</span><span class="sxs-lookup"><span data-stu-id="26b59-421">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="26b59-422">我们通过设置Bing插件安装验证默认为真实，并使MSI返回成功视为安装成功，解决了ValidateInstall失败率问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-422">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="26b59-423">我们对新的 AppV51 进行了备份，以修复之前 AppV51 中的回归问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-423">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="26b59-424">解决了尝试硬链接符号链接时导致更新失败的即点即用问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-424">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="26b59-425">修复了即使完成向完整产品的转换也导致显示运行时消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-425">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="26b59-426">解决此问题的方法是确保服务会正确计算添加的产品。</span><span class="sxs-lookup"><span data-stu-id="26b59-426">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="26b59-427">我们筛选掉了新添加的产品（确保这些产品同时存在于新配置中），并将其添加到现有产品发布 ID 的末尾。</span><span class="sxs-lookup"><span data-stu-id="26b59-427">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="26b59-428">解决了用户发现 UI 元素或内容在某些条件下（尤其是在进出演示者视图或使用多个显示器时）不显示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-428">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="26b59-429">此更改解决了加载和播放动画内容（如 Gif 或 3D 模型）时可能挂起的情况。</span><span class="sxs-lookup"><span data-stu-id="26b59-429">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="26b59-430">此更改解决了“压缩图片”对话框不保留某些用户设置的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-430">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="26b59-431">此更新修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-431">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="26b59-432">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="26b59-432">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="26b59-433">此修复程序解决了阻止同时使用密码限制访问和保护文件的错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-433">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="26b59-434">解决了 TabProcGrowth 注册表值为 REG_SZ 类型启用加载项时，windows 上的 office 主机会出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-434">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="26b59-p139">当注册表键HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth被设置为零时，正在激活一个外接程序时，windows中的office主机故障。此更改可修复此问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-p139">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-august-11"></a><span data-ttu-id="26b59-438">版本2002:8月11日</span><span class="sxs-lookup"><span data-stu-id="26b59-438">Version 2002: August 11</span></span>
<span data-ttu-id="26b59-439">*版本2002（内部版本12527.20988）*</span><span class="sxs-lookup"><span data-stu-id="26b59-439">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="26b59-440">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-440">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-442">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-442">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-443">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-443">Excel</span></span>

- <span data-ttu-id="26b59-444">修复了以 "建议只读 "打开的文件无法切换到编辑的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-444">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="26b59-445">OneNote</span><span class="sxs-lookup"><span data-stu-id="26b59-445">OneNote</span></span>

- <span data-ttu-id="26b59-446">已删除多余的身份调用，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="26b59-446">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="26b59-447">改进对共同创作状态的检测，以减少资源利用率。</span><span class="sxs-lookup"><span data-stu-id="26b59-447">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="26b59-448">提高检测错误的能力和同步体验的质量。</span><span class="sxs-lookup"><span data-stu-id="26b59-448">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-449">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-449">Outlook</span></span>

- <span data-ttu-id="26b59-450">解决了某些租户启动Outlook时出现重大性能问题的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-450">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="26b59-451">Skype</span><span class="sxs-lookup"><span data-stu-id="26b59-451">Skype</span></span>

- <span data-ttu-id="26b59-452">修复了32位Skype for Business客户端在运行数天后启动屏幕共享时可能出现失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-452">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-453">Office Suite</span><span class="sxs-lookup"><span data-stu-id="26b59-453">Office Suite</span></span>

- <span data-ttu-id="26b59-454">修复了一个问题：如果通过组策略关闭自动保存，一些文档可能在打开时不会显示最新的服务器内容，直到用户点击 "可用更新"。</span><span class="sxs-lookup"><span data-stu-id="26b59-454">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-july-14"></a><span data-ttu-id="26b59-456">版本 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="26b59-456">Version 2002: July 14</span></span>
<span data-ttu-id="26b59-457">*版本 2002（内部版本 12527.20880）*</span><span class="sxs-lookup"><span data-stu-id="26b59-457">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="26b59-458">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-458">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-460">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-460">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-461">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-461">Excel</span></span>

- <span data-ttu-id="26b59-462">加快本地 OneDrive 文件夹上可用文件的加载速度。</span><span class="sxs-lookup"><span data-stu-id="26b59-462">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="26b59-463">修正了以下问题：保存到 SharePoint / OneDrive 时，自定义功能区标签的CustomUI XML被删除。</span><span class="sxs-lookup"><span data-stu-id="26b59-463">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="26b59-464">解决了以下问题：由于加载程序是按字母顺序加载的，而不是按用户指定的顺序加载，因此会出现“此工作簿目前由另一个工作簿引用，无法关闭”的错误信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-464">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="26b59-465">修复了单击超链接到已打开的工作簿中某个位置时，工作簿可能被隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-465">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="26b59-466">我们解决了某些复制粘贴图表链接使用映射驱动器地址而不是通用地址的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-466">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="26b59-467">解决删除含合并单元格的列时的性能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-467">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="26b59-468">修复了在“打印”对话框中的打印机列表中可以重复打印机名称的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-468">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="26b59-469">我们修复了包含多个已定义名称的公式的工作表在保存文件时导致时间延长的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-469">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="26b59-470">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-470">Outlook</span></span>

- <span data-ttu-id="26b59-471">我们解决了当使用多个不同分辨率的显示器时，IME（输入法编辑器）窗口会重叠通过IME输入的底层文本的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-471">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="26b59-472">解决了在接近时区定义更改时导致在错误时间显示重复约会或会议的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-472">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="26b59-473">解决了导致用户在更新 Outlook 中的“规则”时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-473">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="26b59-474">解决了未选中“下载共享”文件夹时导致共享日历会议“响应选项”中缺少“允许转发”选项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-474">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="26b59-475">解决了导致类别偶尔从电子邮件中消失的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-475">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="26b59-476">解决了导致代理人在不同计算机上看到共享邮箱的不同文件夹层次结构的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-476">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="26b59-477">解决了导致在编辑经理日历上的现有日历约会时，代表收到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-477">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="26b59-478">修复了在编辑主题后导致 NDR 邮件的正文从 Unicode 更改为 ASCII 的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-478">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="26b59-479">解决了两个加载项将按钮添加到同一功能区组时导致用户崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-479">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="26b59-480">解决了导致用户无法向个人通讯组列表发送电子邮件地址的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-480">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="26b59-481">解决了将租户默认权限配置为“任何人”时，导致链接无法以正确的租户默认权限添加到电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-481">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="26b59-482">解决了用户在安全对话框中选择”save” 选项时无法将 OneDrive 附件从租户外部保存到本地计算机的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-482">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-483">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-483">Word</span></span>

- <span data-ttu-id="26b59-484">解决了启用 FileBlick\Word2007Files 策略时出现的协调问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-484">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="26b59-485">我们修复了添加已重命名的查找字段时，无法使用 Word QuickPart 的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-485">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-486">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-486">Office Suite</span></span>

- <span data-ttu-id="26b59-487">解决了用户在共同编辑大型 PowerPoint 文件时会遇到过多的网络和CPU使用率的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-487">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="26b59-488">我们对新的 AppV51 进行了备份，以修复之前 AppV51 中的回归问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-488">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="26b59-489">解决了 TabProcGrowth 注册表值为 REG_SZ 类型启用加载项时，windows 上的 office 主机会出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-489">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-june-09"></a><span data-ttu-id="26b59-491">版本 2002：6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="26b59-491">Version 2002: June 09</span></span>
<span data-ttu-id="26b59-492">*版本 2002（内部版本 12527.20720）*</span><span class="sxs-lookup"><span data-stu-id="26b59-492">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="26b59-493">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-493">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-495">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-495">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-496">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-496">Excel</span></span>

- <span data-ttu-id="26b59-497">修复了以下问题：在文件重新打开后，如果文件路径太长，外部链接会停止工作。</span><span class="sxs-lookup"><span data-stu-id="26b59-497">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="26b59-498">修正了团队共享 Excel 窗口时，使用Ctrl+Shift+箭头键滚动后Excel可能会无法响应的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-498">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="26b59-499">修复了打印时窗体控件中的复选框缩放的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-499">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="26b59-500">尝试在新工作表上为使用旧版“共享工作簿”模式的工作簿列出更改时，可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-500">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="26b59-501">在筛选列表中插入列所需的时间可能比预期更长。</span><span class="sxs-lookup"><span data-stu-id="26b59-501">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="26b59-502">修复了以下问题：将以公式开头的@符号被视为隐式交集运算符。</span><span class="sxs-lookup"><span data-stu-id="26b59-502">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-503">Outlook</span></span>

- <span data-ttu-id="26b59-504">启用直接通过本机 Teams 客户端加入 Teams 会议。</span><span class="sxs-lookup"><span data-stu-id="26b59-504">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="26b59-505">解决了针对 Outlook 未能向使用M365 Business Plus计划的付费用户启用数据丢失保护策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-505">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="26b59-506">解决了导致用户无法完成 Gmail 身份验证提示时使用错误的浏览器仿真设置的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-506">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="26b59-507">解决了导致服务器操作系统上的 Outlook 用户无法看到错误的问题，"防病毒状态：无效。</span><span class="sxs-lookup"><span data-stu-id="26b59-507">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="26b59-508">此版本的 Windows 支持防病毒检测，但没有发现防病毒，尽管已正确配置防病毒。</span><span class="sxs-lookup"><span data-stu-id="26b59-508">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-509">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-509">Word</span></span>

- <span data-ttu-id="26b59-510">修复了以下问题：在使用“快速打印”打印后尝试进行编辑时，文档中的字词对齐方式会被打乱。</span><span class="sxs-lookup"><span data-stu-id="26b59-510">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-511">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-511">Office Suite</span></span>

- <span data-ttu-id="26b59-512">我们通过将后台的频道名称更新为 2020 年 1 月的分支中的新频道名称来解决此问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-512">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="26b59-513">我们已修复此问题，接下来，如果设备是由策略管理的，则不会调用 DMS Audience API。</span><span class="sxs-lookup"><span data-stu-id="26b59-513">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="26b59-514">解决了在单个事务中添加和删除应用时删除不完整的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-514">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="26b59-p141">当注册表键HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth被设置为零时，正在激活一个外接程序时，windows中的office主机故障。此更改可修复此问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-p141">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-may-12"></a><span data-ttu-id="26b59-518">版本 2002：5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="26b59-518">Version 2002: May 12</span></span>
<span data-ttu-id="26b59-519">*版本 2002（内部版本 12527.20612）*</span><span class="sxs-lookup"><span data-stu-id="26b59-519">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="26b59-520">[此处](./microsoft365-apps-security-updates.md)列出了安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-520">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-522">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-522">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="26b59-523">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-523">Excel</span></span>

- <span data-ttu-id="26b59-524">打开包含对许多其他工作簿（尤其是隐藏窗口）的引用的工作簿将比预期的慢。</span><span class="sxs-lookup"><span data-stu-id="26b59-524">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="26b59-525">在某些情况下，打开 CSV 文件所花费的时间比预期的长。</span><span class="sxs-lookup"><span data-stu-id="26b59-525">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="26b59-526">在具有不同缩放级别的工作簿之间切换时，在某些情况下 Excel 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-526">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="26b59-527">修复了一个有关 VBA 的问题：将值写入某个区域可能比预期的要慢。</span><span class="sxs-lookup"><span data-stu-id="26b59-527">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="26b59-528">从按颜色筛选的列复制的数据有时无法正确粘贴。</span><span class="sxs-lookup"><span data-stu-id="26b59-528">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="26b59-529">修复了导致以下情形的问题：复制包含数据透视表的工作表后，在某些情况下 Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-529">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="26b59-530">含有数字签名且在 Excel 2016 中保存的工作簿在当前版本的 Excel 中打开时，可能会使签名无效。</span><span class="sxs-lookup"><span data-stu-id="26b59-530">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="26b59-531">解决了保存并重新打开文件时图表坐标轴上的“值交叉点”属性意外发生更改的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-531">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="26b59-532">使用 Range.Value 和 Range.Value2 (VBA) 会导致公式作为动态数组输入。</span><span class="sxs-lookup"><span data-stu-id="26b59-532">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="26b59-533">OneNote</span><span class="sxs-lookup"><span data-stu-id="26b59-533">OneNote</span></span>

- <span data-ttu-id="26b59-534">对一条通知进行了本地化，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="26b59-534">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="26b59-535">显示了一条通知，该通知有助于用户详细了解为提高同步和服务稳定性而在 OneNote 用户体验中实施的临时措施。</span><span class="sxs-lookup"><span data-stu-id="26b59-535">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="26b59-536">通过暂时减少 OneNote 2016 中版本历史记录页面的数量和同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-536">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="26b59-p142">通过临时禁用 OneNote 2016 中的回收站，改进了同步和服务稳定性。当用户尝试删除通常发送到回收站的数据时，将询问用户是否希望保留或永久删除数据。</span><span class="sxs-lookup"><span data-stu-id="26b59-p142">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016. When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="26b59-539">通过临时调整 OneNote 2016 中的同步频率，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-539">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="26b59-540">在 OneNote 2016 中，通过暂时将联机笔记本中的嵌入式文件和图像的下载推迟到用户导航到相应页面时进行，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-540">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="26b59-541">通过暂时禁用 OneNote 2016 中的应用内视频录制功能，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-541">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="26b59-542">本地笔记本不受此措施影响。</span><span class="sxs-lookup"><span data-stu-id="26b59-542">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="26b59-543">在 OneNote 2016 中，通过暂时将新的嵌入式附件的最大允许大小降低到 50 MB，提升了同步和服务稳定性。</span><span class="sxs-lookup"><span data-stu-id="26b59-543">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="26b59-544">对于超出此限制的文件，用户可以选择将文件上传到 OneDrive 并将链接插入 OneNote。</span><span class="sxs-lookup"><span data-stu-id="26b59-544">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-545">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-545">Outlook</span></span>

- <span data-ttu-id="26b59-546">解决了导致文件夹窗格宽度意外改变的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-546">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="26b59-547">解决了导致用户在某次 Windows 更新后打开 .msg 和 .oft 文件时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-547">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="26b59-548">解决了在转发大型 HTML 邮件时导致用户看到邮件正文截断的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-548">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="26b59-549">此更新修复了 Microsoft Outlook 在用户查看或撰写邮件时不显示当前敏感度标签的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-549">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="26b59-550">解决了导致用户无法向个人通讯组列表发送电子邮件地址的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-550">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="26b59-551">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-551">PowerPoint</span></span>

- <span data-ttu-id="26b59-552">修复了在用户打开的文件副本中含有改进的批注时为用户中继正确消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-552">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-553">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-553">Word</span></span>

- <span data-ttu-id="26b59-554">解决了可能无法正确启动 Access 和 Publisher（具体取决于安装的语言）的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-554">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="26b59-555">修复了受编辑保护的文档的“比较”功能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-555">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="26b59-556">我们修复了将 2 个文档合并为一个文档时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-556">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-557">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-557">Office Suite</span></span>

- <span data-ttu-id="26b59-558">这是一个修复程序，用于解决在客户端缓存文件时，Project 应用不应阻止网络的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-558">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="26b59-559">我们已经解决了内部操作在失败时引发异常而不是进行记录并继续的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-559">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="26b59-560">受影响的用户将不再被阻止接收更新。</span><span class="sxs-lookup"><span data-stu-id="26b59-560">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="26b59-561">此更改可确保草绘轮廓在功能区中正常工作。</span><span class="sxs-lookup"><span data-stu-id="26b59-561">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="26b59-562">修复了从具有某些特定代理配置的本地位置打开文件时出现的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-562">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="26b59-563">此更新修复了 Microsoft Office 中 Visual Basic for Applications 的以下问题：某些引用库名称或库路径中包含 DBSC 字符的代码库的 VBA 项目会被 Office 应用程序视为加载时损坏。</span><span class="sxs-lookup"><span data-stu-id="26b59-563">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="26b59-564">此更新修复了 Microsoft Office 中的一个问题，即在运行时可能无法正确找到所含引用可通过搜索 PATH 环境变量中指定的位置找到的 Visual Basic for Applications 项目，从而导致 VBA 运行时错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-564">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="26b59-565">此更新修复了 Microsoft Word 中的一个问题，即如果某个敏感度标签策略应用了页眉、页脚或水印，则在应用该标签时插入的长度超过 255 个字符的文本随后将无法通过更改或删除该标签来标识和删除。</span><span class="sxs-lookup"><span data-stu-id="26b59-565">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="26b59-566">修复了可在 Office 切换会话期间防止崩溃并提高用户体验可靠性的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-566">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="26b59-567">此 bug 将更新增强型配置服务 (ECS) url 终结点。</span><span class="sxs-lookup"><span data-stu-id="26b59-567">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="26b59-568">调用此较新的终结点可以提高从 ECS 获取数据的成功率。</span><span class="sxs-lookup"><span data-stu-id="26b59-568">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-april-14"></a><span data-ttu-id="26b59-570">版本 2002：4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="26b59-570">Version 2002: April 14</span></span>
<span data-ttu-id="26b59-571">*版本 2002（内部版本 12527.20442）*</span><span class="sxs-lookup"><span data-stu-id="26b59-571">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="26b59-572">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-572">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="26b59-573">功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-573">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-574">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-574">Excel</span></span>

- <span data-ttu-id="26b59-575">**键入可返回多个值的公式：** 现可键入返回多个值的公式，它们将自动溢出到相邻的单元格中。</span><span class="sxs-lookup"><span data-stu-id="26b59-575">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="26b59-576">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-576">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="26b59-577">**6 个强大的函数：** 我们添加了六个新函数来增强你的电子表格：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。</span><span class="sxs-lookup"><span data-stu-id="26b59-577">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="26b59-578">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-578">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="26b59-579">**向左看，向右看… XLOOKUP 在此！** 使用 XLOOKUP 在表或区域中逐行查找所需内容。</span><span class="sxs-lookup"><span data-stu-id="26b59-579">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="26b59-580">
  [了解更多](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="26b59-580">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-582">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-582">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-583">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-583">Excel</span></span>

- <span data-ttu-id="26b59-584">在某些情况下，重新打开嵌入 Word 或 PowerPoint 的工作簿时，Excel 会崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-584">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="26b59-585">当另存为 CSV 文件时，在某些情况下，Excel 可能将所有列合并为一个列。</span><span class="sxs-lookup"><span data-stu-id="26b59-585">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="26b59-586">在受保护工作表中的某个区域内使用 Range.ClearContents 的时间可能比预期的要长。</span><span class="sxs-lookup"><span data-stu-id="26b59-586">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="26b59-587">修复了在“打印预览”中显示时表单控件中的文本缩放问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-587">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="26b59-588">与功能区交互的 VBA 宏可能在 ScreenUpdating 意外设置为 True 的情况下运行。</span><span class="sxs-lookup"><span data-stu-id="26b59-588">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="26b59-589">解决了如果关闭了源代码簿，则外部链接不会在填充（向下填充、横跨填充等）时更新的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-589">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="26b59-590">使用 VBA 的应用程序。在某些情况下，评估无法用于用户定义的功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-590">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="26b59-591">解决了从模板创建图表时出现的性能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-591">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="26b59-592">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-592">Outlook</span></span>

- <span data-ttu-id="26b59-593">解决了在某些方案中导致组页眉意外展开的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-593">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="26b59-594">解决了导致用户在选择某些搜索结果时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-594">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="26b59-595">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-595">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="26b59-596">解决了导致附件工具中缺少“保存到云”按钮的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-596">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="26b59-597">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-597">PowerPoint</span></span>

- <span data-ttu-id="26b59-598">改进了复制粘贴方案：即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-598">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="26b59-599">Project</span><span class="sxs-lookup"><span data-stu-id="26b59-599">Project</span></span>

- <span data-ttu-id="26b59-600">解决了以下问题：保存使用 Project 早期版本创建的项目时，Project 可能会崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-600">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="26b59-601">解决了以下问题：通过“停用”按钮停用/激活任务后，无法检测到 ProjectBeforeTaskChange 事件。</span><span class="sxs-lookup"><span data-stu-id="26b59-601">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-602">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-602">Word</span></span>

- <span data-ttu-id="26b59-603">解决了在使用鼠标上的 X 按钮时导致用户偶尔遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-603">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="26b59-604">我们修复了表格中文本适应的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-604">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="26b59-605">我们修复了插入水平线不短且居中的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-605">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-2002-march-10"></a><span data-ttu-id="26b59-607">版本 2002：3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="26b59-607">Version 2002: March 10</span></span>
<span data-ttu-id="26b59-608">*版本 2002（生成号 12527.20278）*</span><span class="sxs-lookup"><span data-stu-id="26b59-608">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="26b59-609">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-609">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="26b59-611">功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-611">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="26b59-612">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-612">Access</span></span>

- <span data-ttu-id="26b59-613">**快速查找链接的表格：** 新的“搜索”框使查找链接的表格成为一项轻松的乐事。</span><span class="sxs-lookup"><span data-stu-id="26b59-613">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="26b59-614">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-614">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="26b59-615">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-615">Excel</span></span>

- <span data-ttu-id="26b59-p151">**通过 \@提及吸引同事的注意力：** 在注释中使用 @提及，以在需要同事的意见时让他们知悉。[了解详细信息](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="26b59-p151">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>

- <span data-ttu-id="26b59-618">**查找要找的内容：** 搜索命令、人员、文件、照片、Web 文章等等。</span><span class="sxs-lookup"><span data-stu-id="26b59-618">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="26b59-619">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-619">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="26b59-620">**手绘：** 让工作簿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="26b59-620">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="26b59-621">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-621">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="26b59-622">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-622">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="26b59-623">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="26b59-623">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="26b59-624">**关注剩余待办事项：** 选择“解决”可折叠评论并突出显示待处理的项目。</span><span class="sxs-lookup"><span data-stu-id="26b59-624">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="26b59-625">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-625">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="26b59-626">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-626">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="26b59-627">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="26b59-627">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="26b59-628">**数据可视化工具加载项：** 从 Excel 中快速创建 Visio 流程图。</span><span class="sxs-lookup"><span data-stu-id="26b59-628">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="26b59-629">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-629">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="26b59-630">**随时随地阅读和答复：** 无需打开工作簿即可直接从电子邮件响应评论和提及。</span><span class="sxs-lookup"><span data-stu-id="26b59-630">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="26b59-631">**获取工作簿统计信息：** 工作簿统计信息提供工作簿内容的概述，可帮助你更轻松地发现内容。</span><span class="sxs-lookup"><span data-stu-id="26b59-631">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="26b59-632">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-632">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="26b59-633">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="26b59-633">Find them at Insert > Icons.</span></span> [<span data-ttu-id="26b59-634">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-634">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="26b59-635">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-635">Outlook</span></span>

- <span data-ttu-id="26b59-636">**将 LinkedIn 网络连接到 Outlook：** 以安全的方式将 LinkedIn 帐户连接到 Microsoft 帐户，直接在“人员”卡片中查看 LinkedIn 中的信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-636">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="26b59-637">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-637">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="26b59-p158">**所有加密选项都在一个位置：** 只需转到“选项”>“加密”以选择如何保护电子邮件。[了解更多](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="26b59-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="26b59-640">**Outlook 中的插入链接菜单将插入包含租户管理员定义的权限的链接：** Outlook 插入链接 MRU 中的链接将插入仅对已经拥有权限的用户有效的链接。</span><span class="sxs-lookup"><span data-stu-id="26b59-640">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="26b59-641">这通常会导致请求获得文档访问权限的用户之间发生往来电子邮件。</span><span class="sxs-lookup"><span data-stu-id="26b59-641">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="26b59-642">我们已更新了此体验，现在该链接将通过租户管理员设置的默认权限进行插入。对于 MSIT，这“可供组织编辑”，因此收到以此方式共享的链接的所有内部用户都可以访问它。</span><span class="sxs-lookup"><span data-stu-id="26b59-642">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="26b59-643">**在有拼写错误的情况下进行搜索：** 即使你的拼写有误，Outlook 仍将找到你在查找的内容。</span><span class="sxs-lookup"><span data-stu-id="26b59-643">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="26b59-644">**轻松发现网络钓鱼邮件：** 垃圾邮件和网络钓鱼邮件具有不同的外观，因此你可以轻松从收件箱中识别并删除它们。</span><span class="sxs-lookup"><span data-stu-id="26b59-644">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="26b59-645">**针对攻击的高级防护：** 通过 Office 365 高级威胁防护, 可通过电子邮件主题中的超链接、附加邮件、签名邮件、网络路径等的方式抵御攻击。</span><span class="sxs-lookup"><span data-stu-id="26b59-645">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="26b59-646">**让我把它画出来：** 在图片上进行涂鸦或添加绘图画布以使用墨迹表达你的想法。</span><span class="sxs-lookup"><span data-stu-id="26b59-646">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="26b59-647">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-647">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="26b59-648">**查看搜索结果中的相关消息：** Outlook 会分析搜索词，并在搜索结果顶部显示最相关的电子邮件信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-648">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="26b59-649">还会在“热门搜索结果”部分看到按日期排序的所有搜索结果。</span><span class="sxs-lookup"><span data-stu-id="26b59-649">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="26b59-650">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-650">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="26b59-651">**获取位置建议：** 在安排约会和会议时，开始键入位置，Outlook 就会推荐会议室、地址和其他邻近位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-651">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="26b59-652">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-652">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="26b59-653">**在屏幕上显示更多邮件：** 选择“视图”>“使用更紧密的间距”来调整邮件之间的间距。</span><span class="sxs-lookup"><span data-stu-id="26b59-653">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="26b59-654">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-654">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="26b59-655">**以不同的亮度查看邮件：** 使用“太阳”/“月亮”按钮在阅读窗格中的明暗背景之间切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-655">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="26b59-656">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-656">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="26b59-657">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-657">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="26b59-658">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="26b59-658">Find them at Insert > Icons.</span></span> [<span data-ttu-id="26b59-659">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-659">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="26b59-660">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-660">PowerPoint</span></span>

- <span data-ttu-id="26b59-661">**PowerPoint 中的快速实时协作：** 在 PowerPoint 中快速展开实时协作</span><span class="sxs-lookup"><span data-stu-id="26b59-661">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="26b59-662">**新增校对工具：** 无需在语言方面倍感压力。</span><span class="sxs-lookup"><span data-stu-id="26b59-662">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="26b59-663">PowerPoint 现在可提供语法和写作建议。</span><span class="sxs-lookup"><span data-stu-id="26b59-663">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="26b59-664">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-664">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="26b59-665">**实时字幕和对白字幕：** 演示者的文字会作为字幕自动显示在屏幕上或翻译成你所选语言的对白字幕。</span><span class="sxs-lookup"><span data-stu-id="26b59-665">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="26b59-666">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-666">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="26b59-p168">**你来计算，我们来设置格式：** 我们将书写数学表达式更改成标准字符。只需选择“将墨迹转换为数学公式”，再选择手写笔记即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="26b59-p168">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="26b59-670">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="26b59-670">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="26b59-671">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-671">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="26b59-672">**查找并修复缺失的幻灯片标题：** 幻灯片标题可为你的推销词增色添彩，并使所有用户都可以访问你的幻灯片。</span><span class="sxs-lookup"><span data-stu-id="26b59-672">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="26b59-673">辅助功能检查器显示标题缺失位置，以便你可以快速添加标题。</span><span class="sxs-lookup"><span data-stu-id="26b59-673">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="26b59-674">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-674">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="26b59-675">**手绘：** 让演示文稿中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="26b59-675">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="26b59-676">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-676">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="26b59-677">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="26b59-678">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="26b59-678">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="26b59-679">**将插图另存为 SVG**：将图表、形状或其他插图另存为可缩放矢量图形，这样做可以调整其大小，而不会降低图像质量。</span><span class="sxs-lookup"><span data-stu-id="26b59-679">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="26b59-680">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-680">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="26b59-681">**打印讲义上的幻灯片编号：** 幻灯片编号将会自动包括在讲义上。</span><span class="sxs-lookup"><span data-stu-id="26b59-681">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="26b59-682">打开或是关闭它们，全都取决于你。</span><span class="sxs-lookup"><span data-stu-id="26b59-682">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="26b59-683">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-683">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="26b59-684">**墨迹即时重播：** 在幻灯片上使用墨迹时，可应用重播动画，在幻灯片放映期间重播墨迹的实际绘制过程。</span><span class="sxs-lookup"><span data-stu-id="26b59-684">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="26b59-685">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-685">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="26b59-686">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-686">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="26b59-687">**全面优化你的演示文稿：** 辅助功能检查器可帮助你在使用屏幕阅读器时排列幻灯片上的对象。</span><span class="sxs-lookup"><span data-stu-id="26b59-687">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="26b59-688">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="26b59-688">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="26b59-689">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="26b59-689">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="26b59-690">**如果可以重复使用，为何还要重新创建呢？：** 通过重新使用你创建的幻灯片或其他人与你共享的幻灯片来节省时间。</span><span class="sxs-lookup"><span data-stu-id="26b59-690">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="26b59-691">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-691">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="26b59-692">**在 PowerPoint for Office 365 中将手写墨迹更改为形状、文本或数学公式：** 从自由格式的墨迹转到几条笔划中的 Office 形状、文本或数学表达式。</span><span class="sxs-lookup"><span data-stu-id="26b59-692">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="26b59-693">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-693">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="26b59-p177">**用墨迹绘制精彩绝伦的幻灯片：** 将墨迹转换为标准形状和文本，然后从 PowerPoint 设计器获取智能幻灯片设计灵感。[了解更多](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span><span class="sxs-lookup"><span data-stu-id="26b59-p177">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer. [Learn more](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span></span>

- <span data-ttu-id="26b59-696">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-696">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="26b59-697">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="26b59-697">Find them at Insert > Icons.</span></span> [<span data-ttu-id="26b59-698">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-698">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="26b59-699">Visio</span><span class="sxs-lookup"><span data-stu-id="26b59-699">Visio</span></span>

- <span data-ttu-id="26b59-700">**返回到“犯罪”的场景：** 使用“犯罪场景调查模板”中的新证据、室内和户外模具，仔细地重新创建罪犯的犯罪场景。</span><span class="sxs-lookup"><span data-stu-id="26b59-700">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="26b59-701">**在 Excel 中制作优美的 Visio 图表：** 通过将数据置于工作表上来创建流程图或组织结构图。</span><span class="sxs-lookup"><span data-stu-id="26b59-701">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="26b59-702">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-702">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="26b59-703">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-703">Word</span></span>

- <span data-ttu-id="26b59-704">**简历编辑器加入 LinkedIn 简历助手：** 简历编辑器提供了一系列专为简历量身定制的语法和样式检查，以使你的写作更加精确和专业。</span><span class="sxs-lookup"><span data-stu-id="26b59-704">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="26b59-705">**修复了 3D 对象合并导致的文档损坏问题：** 修复了 3D 对象合并导致的文档损坏问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-705">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="26b59-706">**查找要找的内容：** 使用搜索框查找文本、命令和帮助等等。</span><span class="sxs-lookup"><span data-stu-id="26b59-706">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="26b59-707">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-707">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="26b59-708">**色彩丰富的协作：** 批注和修订由参与者进行颜色编码，以便你能够轻松看到协作者是谁。</span><span class="sxs-lookup"><span data-stu-id="26b59-708">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="26b59-709">**协同编辑启用宏的文档：** 将 docm 文件保存在 OneDrive for Business 上，并与协作者实时进行编辑。</span><span class="sxs-lookup"><span data-stu-id="26b59-709">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="26b59-710">**合著改进**：提高了在具有修订的文档中进行合著时的 Word 性能。</span><span class="sxs-lookup"><span data-stu-id="26b59-710">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="26b59-711">**更多符合你心情的图标：** 我们添加了 300 多个新图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-711">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="26b59-712">可在“插入”>“图标”中找到它们。</span><span class="sxs-lookup"><span data-stu-id="26b59-712">Find them at Insert > Icons.</span></span> [<span data-ttu-id="26b59-713">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-713">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="26b59-714">**其他人可以快速查看你所做的更改：** 共同创作改进意味着你的协作者可以比以往更快地查看你所做的更改。</span><span class="sxs-lookup"><span data-stu-id="26b59-714">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="26b59-715">**手绘：** 让文档中的 Office 形状呈现随意的手绘外观。</span><span class="sxs-lookup"><span data-stu-id="26b59-715">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="26b59-716">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-716">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="26b59-717">**精确擦除：** 从两个橡皮擦尺寸中进行选择以修复小墨迹缺陷。</span><span class="sxs-lookup"><span data-stu-id="26b59-717">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="26b59-718">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-718">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="26b59-719">**更快的文件共享：** 直接从最近使用的文件列表中共享文档，而无需打开文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-719">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="26b59-720">**不再跳转到浏览器：** 由你决定如何打开 Office 文档链接：在浏览器还是在应用中打开。</span><span class="sxs-lookup"><span data-stu-id="26b59-720">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="26b59-721">了解更多详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-721">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="26b59-722">**合著改进：** 提高了合著时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="26b59-722">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="26b59-723">**创建更易于访问的 PDF：** 创建一个 PDF，辅助功能检查器将会在你进行保存前指出要修复的辅助功能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-723">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="26b59-724">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-724">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="26b59-725">**将文件转换为改进辅助功能：** 将文件升级到新式格式，使其更易于所有人访问。</span><span class="sxs-lookup"><span data-stu-id="26b59-725">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="26b59-726">**更安全的视频体验：** 安全增强意味着更安全的联机视频体验。</span><span class="sxs-lookup"><span data-stu-id="26b59-726">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="26b59-727">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-727">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-730">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-730">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="26b59-731">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-731">Access</span></span>

- <span data-ttu-id="26b59-732">此更新修复了 Microsoft Access 中的一个问题，该问题可能会导致运行更新查询或在 SQL 中使用 UPDATE 语句时出现“查询已损坏”错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-732">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="26b59-733">此更新修复了可能会导致 Microsoft Access 无法识别链接 SQL Server 表中的标识列的问题，该问题可能会导致行错误地被报告为已删除。</span><span class="sxs-lookup"><span data-stu-id="26b59-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="26b59-p187">此更新修复了使用 ADODB 的问题。VB 代码中的录制器对象可能会误报错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-p187">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="26b59-736">Access 模板将不会再导致数据库中的附件列出现故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-736">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="26b59-737">在实例化模板后，你现在应该可以将附件字段添加到数据库中。</span><span class="sxs-lookup"><span data-stu-id="26b59-737">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="26b59-738">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-738">Excel</span></span>

- <span data-ttu-id="26b59-739">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-739">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="26b59-740">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-740">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="26b59-741">修复了一个问题，该问题导致某些用户在将文本转换为包含单元格（具有溢出数组）的列时遇到崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-741">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="26b59-742">此更新修复了导致公式栏以不同于预期的字体显示文本的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-742">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="26b59-743">某些区域设置的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-743">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="26b59-744">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-744">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="26b59-745">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="26b59-745">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="26b59-746">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-746">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="26b59-747">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-747">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="26b59-748">某些本地化版本的“文本分列”功能可能会失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-748">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="26b59-749">访问隐藏命名区域时，用户可能会遇到错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-749">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="26b59-750">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="26b59-750">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="26b59-751">修复了某些用户可能遇到的嵌入和链接对象 (OLE) 问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-751">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="26b59-752">我们修复了数据透视图的右键单击菜单，以便启用“显示详细信息”选项。</span><span class="sxs-lookup"><span data-stu-id="26b59-752">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="26b59-753">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-753">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="26b59-754">修复了当工作簿中存在外部链接时某些用户可能遇到多个弹出窗口的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-754">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="26b59-755">修复了未显示上下文菜单中的批注命令的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-755">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="26b59-756">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-756">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="26b59-757">修复了 CUBEVALUE 函数有时会返回错误结果的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-757">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-758">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-758">Outlook</span></span>

- <span data-ttu-id="26b59-759">解决了导致“搜索反馈”体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-759">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="26b59-760">解决了导致用户在检索云设置时在 Outlook 中遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-760">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="26b59-761">解决了导致搜索框在高 dpi 模式下未正确对齐的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-761">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="26b59-762">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-762">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="26b59-763">解决了在某些情况下导致用户看到电子邮件发送地址与显示的 SMTP 地址不匹配的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-763">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="26b59-764">此更改恢复了在邮件头中查看多行主题的功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-764">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="26b59-765">我们修复了可能会阻止文件保存到 WebDAV 位置的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-765">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="26b59-766">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-766">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="26b59-767">解决了导致第三方应用程序无法发送电子邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-767">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="26b59-768">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“确定”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-768">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="26b59-769">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-769">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="26b59-770">解决了导致 Outlook 在同步滑块设置为较小的设置时出现意外同步所有邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-770">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="26b59-771">解决了导致使用Black Theme的用户在 "From "下拉菜单在白色背景上显示白色文本的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-771">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="26b59-772">解决了导致用户在取消帐户设置时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-772">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="26b59-773">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-773">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="26b59-774">解决了一个问题，该问题导致在某些情况下无法使用相关选项来禁用标记项目突出显示。</span><span class="sxs-lookup"><span data-stu-id="26b59-774">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="26b59-775">解决了导致用户在打开规则对话框时看到“此计算机上的规则与 Microsoft Exchange 上的规则不匹配”提示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-775">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="26b59-776">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-776">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="26b59-777">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-777">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="26b59-778">解决了在多个窗口中查看同一项目时可能会导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-778">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="26b59-779">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-779">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="26b59-780">解决了导致用户无法打开某些定期日历项目实例的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-780">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="26b59-781">解决了导致 Exchange 2010 服务器上的邮箱用户在将附件添加到日历项目时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-781">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="26b59-782">解决了导致用户在答复数字签名邮件时遇到问题的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-782">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="26b59-783">解决了导致会议中的“位置”字段意外更新的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-783">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="26b59-784">解决了在会议的位置字段中导致逗号变为分号的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-784">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="26b59-785">解决了导致会议位置在清除后意外添加回会议的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-785">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="26b59-786">解决了与巴西时区中设置的会议和约会有关的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-786">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="26b59-787">解决了关闭辅助功能检查器窗格后按 "S "键时，用户会看到邮件意外发送的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-787">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="26b59-788">这将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="26b59-788">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="26b59-789">解决了导致 Web 加载项访问数字权限管理邮件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-789">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="26b59-790">解决了导致用户在配置文件创建过程中遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-790">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="26b59-791">解决了导致用户在对签名进行重命名时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-791">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="26b59-792">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-792">PowerPoint</span></span>

- <span data-ttu-id="26b59-793">我们修复了 Shape.Paste 方法的问题：当用户使用 Shape.Paste 方法复制和粘贴形状时，它会将所选内容更改为粘贴的形状。</span><span class="sxs-lookup"><span data-stu-id="26b59-793">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="26b59-794">解决了在旧版 PPT 批注中使用上下文菜单时可能导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-794">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="26b59-795">Project</span><span class="sxs-lookup"><span data-stu-id="26b59-795">Project</span></span>

- <span data-ttu-id="26b59-796">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-796">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="26b59-797">修复了以下问题：固定持续时间类型的 100％ 任务可能会错误地将其完成百分比计算为小于 100％ 完成。</span><span class="sxs-lookup"><span data-stu-id="26b59-797">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="26b59-798">修复了有时无法正确计算摘要任务日期的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-798">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="26b59-799">修复了以下问题：如果不首先运行 OpenUndoTransaction 方法，则不会触发 OnUndoOrRedo 事件。</span><span class="sxs-lookup"><span data-stu-id="26b59-799">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-800">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-800">Word</span></span>

- <span data-ttu-id="26b59-801">我们修复了以下问题：在某些情况下，保存现有文件始终会导致显示“另存为”对话框，而该文件从不实际保存。</span><span class="sxs-lookup"><span data-stu-id="26b59-801">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="26b59-802">构建基块管理器可能显示无效的警报：“你已更改样式、构建基块”。</span><span class="sxs-lookup"><span data-stu-id="26b59-802">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-803">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-803">Office Suite</span></span>

- <span data-ttu-id="26b59-804">此更改解决了某些包含标记的散点图呈现缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-804">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="26b59-805">此更改解决了所报告的使用 Intel 集成 GPU 的图形适配器的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-805">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="26b59-806">修复了 ODT 和 GPO 更新截止时间设置中相对截止日期仅在第一次设置时起作用，而修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-806">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="26b59-807">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-807">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="26b59-808">修复了从同一 SharePoint 库在 Word/Excel/PowerPoint 中打开多个文件时，只能打开第一个文件进行策略符合性扫描的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-808">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-february-11"></a><span data-ttu-id="26b59-810">版本 1908：2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="26b59-810">Version 1908: February 11</span></span>
<span data-ttu-id="26b59-811">*版本 1908（内部版本 11929.20606）*</span><span class="sxs-lookup"><span data-stu-id="26b59-811">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="26b59-812">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-812">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-814">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-814">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-815">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-815">Excel</span></span>

- <span data-ttu-id="26b59-816">此更新修复了以下问题：当使用 VBA 向图表的页眉/页脚添加图像时，将会导致出现错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-816">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="26b59-817">修复了在打印预览中或打印时分组框控件的边框不可见的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-817">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="26b59-818">用户在使用部分非英文字符集保存更改时可能会出错。</span><span class="sxs-lookup"><span data-stu-id="26b59-818">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="26b59-819">修复了以下问题：在保存包含图表的工作簿时，图表标题中的图像文件大小增加。</span><span class="sxs-lookup"><span data-stu-id="26b59-819">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="26b59-820">修复了以下问题：在使所选区域与交叉引用的工作簿保持同步时，导致交叉引用工作簿中的 DBCS 字符出现损坏。</span><span class="sxs-lookup"><span data-stu-id="26b59-820">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="26b59-821">解决了使用自动调整功能调整行高时复选框控件缩小的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-821">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="26b59-822">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-822">Outlook</span></span>

- <span data-ttu-id="26b59-823">解决了导致用户在指定无效的发件人地址时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-823">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="26b59-824">解决了导致用户在处理冲突消息时遇到同步失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-824">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="26b59-825">解决了导致用户在启动 Outlook 时在“正在加载个人资料”屏幕上遇到挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-825">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="26b59-826">解决了导致用户在更改视图时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-826">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="26b59-827">解决了导致用户在 Citrix 环境中查看 30 个以上日历时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-827">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="26b59-828">[此处](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是单个 KB，包含针对先前版本记录的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-828">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="26b59-829">解决了一个问题，该问题导致用户在将共享日历文件夹同步到 OST 时遇到问题，这导致他们与这些文件夹进行交互时出现权限错误。</span><span class="sxs-lookup"><span data-stu-id="26b59-829">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="26b59-830">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-830">PowerPoint</span></span>

- <span data-ttu-id="26b59-831">改进了复制粘贴方案，即将 PowerPoint 幻灯片中的形状复制并粘贴到其他幻灯片可能会因异常而失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-831">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="26b59-832">修复了导致协作用户之间的效率降低的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-832">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="26b59-833">修复了以下问题：当逐步打开文件时，如果其中一张幻灯片包含多个嵌入式媒体流，则可能会出现问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-833">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="26b59-834">我们修复了以下问题：首次启动 PowerPoint 时，不受信任的加载项可能不会显示安全警告消息栏。</span><span class="sxs-lookup"><span data-stu-id="26b59-834">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="26b59-835">Project</span><span class="sxs-lookup"><span data-stu-id="26b59-835">Project</span></span>

- <span data-ttu-id="26b59-836">修复了以下问题：由于基准日历发生更改时未更新资源日历，时间表与项目计划之间的实际工时可能不同。</span><span class="sxs-lookup"><span data-stu-id="26b59-836">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-837">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-837">Word</span></span>

- <span data-ttu-id="26b59-838">通过移出已弃用的 API，修复了 Word 中的崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-838">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-839">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-839">Office Suite</span></span>

- <span data-ttu-id="26b59-840">此更改解决了打开损坏的文件后正确渲染图像的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-840">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-january-14"></a><span data-ttu-id="26b59-842">版本 1908：1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="26b59-842">Version 1908: January 14</span></span>
<span data-ttu-id="26b59-843">*版本 1908（内部版本 11929.20562）*</span><span class="sxs-lookup"><span data-stu-id="26b59-843">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="26b59-844">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-844">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-846">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-846">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-847">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-847">Excel</span></span>

- <span data-ttu-id="26b59-848">荷兰语文档标题快捷键提示已更改为 Alt-G。</span><span class="sxs-lookup"><span data-stu-id="26b59-848">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="26b59-849">解决了打开嵌入式工作簿时，未加载功能区自定义项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-849">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="26b59-850">发生问题时，将无法从加载项打开的 WPF （Windows Presentation Foundation）窗体的组合框中选择项目。</span><span class="sxs-lookup"><span data-stu-id="26b59-850">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-851">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-851">Outlook</span></span>

- <span data-ttu-id="26b59-852">解决了导致用户在通过键盘快捷方式与其邮箱文件夹交互时出现明显延迟的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-852">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="26b59-853">解决了在使用备用发件人时导致无法显示策略提示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-853">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="26b59-854">解决了导致用户在更新状态信息时遇到间歇性崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-854">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="26b59-855">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-855">PowerPoint</span></span>

- <span data-ttu-id="26b59-856">我们修复了将一个幻灯片从一个演示文稿复制到另一个演示文稿时，可能创建重复母版的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-856">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="26b59-857">如果在不支持的版本中打开，采用新批注的文件将显示黄色警告</span><span class="sxs-lookup"><span data-stu-id="26b59-857">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-858">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-858">Office Suite</span></span>

- <span data-ttu-id="26b59-859">修复了 Office 更新消息以与预期不同的语言显示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-859">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="26b59-860">今后，Office 更新消息将正确匹配 Windows 显示语言。</span><span class="sxs-lookup"><span data-stu-id="26b59-860">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="26b59-861">解决了以下问题：在某些情况下，如果不是管理员，并且系统帐户没有网络连接，则不会应用更新。</span><span class="sxs-lookup"><span data-stu-id="26b59-861">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>



## <a name="version-1908-december-10"></a><span data-ttu-id="26b59-862">版本 1908：12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="26b59-862">Version 1908: December 10</span></span>
<span data-ttu-id="26b59-863">*版本 1908（内部版本 11929.20516）*</span><span class="sxs-lookup"><span data-stu-id="26b59-863">*Version 1908 (Build 11929.20516)*</span></span>

<span data-ttu-id="26b59-864">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-864">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-866">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-866">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="26b59-867">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-867">Access</span></span>

- <span data-ttu-id="26b59-868">修复了包含对远程表（例如 SQL Server 表）的引用的联合查询可能导致 Access 关闭并重新启动的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-868">Fixed an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="26b59-869">修复了诸如“总和”等聚合可能将结果截断为整数值的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-869">Fixed an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

### <a name="excel"></a><span data-ttu-id="26b59-870">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-870">Excel</span></span>

- <span data-ttu-id="26b59-871">解决了在滚动后选择单元格时可能导致选择错误单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-871">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="26b59-872">我们修复了当 OLAP 数据透视表的筛选器设置为已从多维数据集中删除的值时的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-872">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="26b59-873">此更改通过利用软件呈现避免了某些 Intel 图形驱动程序的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-873">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="26b59-874">解决了 Lookup 函数可能返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-874">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="26b59-875">显著提高了删除包含合并单元格的列时的性能。</span><span class="sxs-lookup"><span data-stu-id="26b59-875">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="26b59-876">解决了导致激活最小化窗口的宏运行时错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-876">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-877">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-877">Outlook</span></span>

- <span data-ttu-id="26b59-878">解决了 SMIME 算法选择方面的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-878">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="26b59-879">解决了导致用户在打开“规则”对话框时看到&quot;此计算机上的规则与 Microsoft Exchange 上的规则不匹配&quot;提示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-879">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="26b59-880">解决了导致 Web 加载项在不应该访问“数字版权管理”消息时访问它们的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-880">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-881">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-881">Word</span></span>

- <span data-ttu-id="26b59-882">我们修复了跟踪更改有时会陷入无限循环的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-882">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-883">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-883">Office Suite</span></span>

- <span data-ttu-id="26b59-884">修复了在 PowerPoint 中的竖排文本框中，半角片假名字符未正确旋转的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-884">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="26b59-885">解决了 Office 更新可能已意外地从 Office CDN 而不是计划源（例如本地/网络共享或 Configuration Manager 提供的位置）下载文件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-885">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="26b59-886">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="26b59-886">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>



[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-22"></a><span data-ttu-id="26b59-888">版本 1908：11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="26b59-888">Version 1908: November 22</span></span>
<span data-ttu-id="26b59-889">*版本 1908（内部版本 11929.20494）*</span><span class="sxs-lookup"><span data-stu-id="26b59-889">*Version 1908 (Build 11929.20494)*</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-891">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-891">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="26b59-892">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-892">Access</span></span>

- <span data-ttu-id="26b59-893">已修复关于运行更新查询会错误地给出“查询已损坏”错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-893">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="excel"></a><span data-ttu-id="26b59-894">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-894">Excel</span></span>

- <span data-ttu-id="26b59-895">当文件具有大量条件格式时，单击“字体颜色”按钮时会出现性能较低的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-895">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="26b59-896">我们修复了打印预览中的打印区域不正确的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-896">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="26b59-897">Excel 可能会在编辑不受信任的网络共享中的受保护文件时遇到问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-897">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="26b59-898">解决了在无工作簿打开的情况下搜索最近使用的文件时可能导致出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-898">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-899">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-899">Outlook</span></span>

- <span data-ttu-id="26b59-900">解决了导致用户在尝试从“帐户创建”上下文联系支持人员时看到带有“&quot;确定&quot;”按钮的空白消息框的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-900">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="26b59-p191">进行了一项更改，使管理员能够启用一个策略，使管理员能够偏好自动发现身份验证提示中提供的帐户电子邮件，而超过 UPN。默认情况下，自动发现喜欢帐户 UPN（如果可用）。</span><span class="sxs-lookup"><span data-stu-id="26b59-p191">Made a change that allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN. By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="26b59-903">解决了导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-903">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="26b59-904">解决了导致用户尝试从&quot;错过的对话&quot;消息创建规则时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-904">Addressed an issue that caused users to experience a crash when attempting to create a rule from a &quot;Missed Conversation&quot; message.</span></span>

- <span data-ttu-id="26b59-905">解决导致用户无法在现代组中查看搜索的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-905">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-906">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-906">Word</span></span>

- <span data-ttu-id="26b59-907">我们修复了在使用 Deskjet 打印机打印时可能导致缩放问题的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-907">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-908">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-908">Office Suite</span></span>

- <span data-ttu-id="26b59-909">修复了防止 PowerPoint 用户在尝试联机演示时遇到错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-909">Fixed an issue to prevent PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="26b59-910">改进了有关注册表完整性的 Office 更新进程的可靠性。</span><span class="sxs-lookup"><span data-stu-id="26b59-910">Improved reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="26b59-911">更正了按流量计费的网络上可能意外阻止更新的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-911">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="26b59-912">修复了 ODT 和 GPO Updae Deadline 设置中相对截止日期仅在第一次设置时起作用，修复程序为后续更新启用相对截止日期的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-912">Fixed an issue in ODT and GPO Updae Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-november-12"></a><span data-ttu-id="26b59-914">版本 1908：11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="26b59-914">Version 1908: November 12</span></span>
<span data-ttu-id="26b59-915">*版本 1908（内部版本 11929.20436）*</span><span class="sxs-lookup"><span data-stu-id="26b59-915">*Version 1908 (Build 11929.20436)*</span></span>

<span data-ttu-id="26b59-916">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-916">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="resolved-issues"></a><span data-ttu-id="26b59-918">已解决的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-918">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="26b59-919">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-919">Excel</span></span>

- <span data-ttu-id="26b59-920">修复了使用图表模板插入图表时预览中所用颜色的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-920">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>
- <span data-ttu-id="26b59-921">我们修复了在更改系列集合时可能导致散点图和折线图无法正确呈现的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-921">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>
- <span data-ttu-id="26b59-922">解决了在使用运行的宏更改自定义属性时导致共同创作中断的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-922">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>
- <span data-ttu-id="26b59-923">我们解决了异步用户定义函数的性能问题，该问题导致它们同步运行。</span><span class="sxs-lookup"><span data-stu-id="26b59-923">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>
- <span data-ttu-id="26b59-924">我们显著提高了按颜色筛选的性能。</span><span class="sxs-lookup"><span data-stu-id="26b59-924">We have significantly improved the performance of filtering by color.</span></span>
- <span data-ttu-id="26b59-925">解决了一个问题，当创建于早期版本的 Office 中的工作簿在当前版本的 Office 中打开时，可能会导致 Excel 挂起。</span><span class="sxs-lookup"><span data-stu-id="26b59-925">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>
- <span data-ttu-id="26b59-926">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="26b59-926">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-927">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-927">Outlook</span></span>

- <span data-ttu-id="26b59-928">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="26b59-928">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="26b59-929">解决了在将用户主日历中的项复制到组日历时出现导致用户遇到权限错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-929">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>
- <span data-ttu-id="26b59-930">解决了导致非常长的 Outlook 会话出现内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-930">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>
- <span data-ttu-id="26b59-931">解决了导致用户在 Outlook 中与特定安全链接交互时遇到失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-931">Addressed an issue that would cause users to experience a failure in Outlook when interacting with certain safelinks.</span></span>
- <span data-ttu-id="26b59-932">解决了导致用户在处理某些自动发现响应时遇到失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-932">Addressed an issue that caused users to experience a failure when processing some AutoDiscover responses.</span></span>
- <span data-ttu-id="26b59-933">解决了导致某些用户在添加辅助 Exchange 帐户时会看到创建重复的特殊文件夹的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-933">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>
- <span data-ttu-id="26b59-934">解决了导致搜索反馈体验挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-934">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="26b59-935">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-935">PowerPoint</span></span>

- <span data-ttu-id="26b59-936">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="26b59-936">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="26b59-937">可靠性修复：修复了第三方加载项可能导致 PowerPoint 失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-937">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="project"></a><span data-ttu-id="26b59-938">Project</span><span class="sxs-lookup"><span data-stu-id="26b59-938">Project</span></span>

- <span data-ttu-id="26b59-939">修复了“全部调配”命令无法正确解决资源过度分配的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-939">Fixed an issue where the Level All command wasn't properly resolving a resource overallocation.</span></span>
- <span data-ttu-id="26b59-940">修复了以下问题：如果你的任务分配为零工作，该任务可能无法标记为已完成，并且始终显示为 99％。</span><span class="sxs-lookup"><span data-stu-id="26b59-940">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>
- <span data-ttu-id="26b59-941">发现了用户在打开只读项目时可能会收到几则消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-941">Identified an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-942">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-942">Word</span></span>

- <span data-ttu-id="26b59-943">Outlook 邮件中的 cid: images 链接现在可以在请求时成功断开。</span><span class="sxs-lookup"><span data-stu-id="26b59-943">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="26b59-944">修复了应用可能会在关闭时挂起的各种问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-944">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="26b59-945">此外，修复了某些与加载项相关的失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-945">Also fixed certain add-in related failures.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-946">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-946">Office Suite</span></span>

- <span data-ttu-id="26b59-947">解决了与第三方插件中的“文本框/形状自动调整”属性相关的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-947">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="october-15"></a><span data-ttu-id="26b59-949">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="26b59-949">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="26b59-950">非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-950">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-951">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-951">Office Suite</span></span>
- <span data-ttu-id="26b59-p193">我们暂时禁用了"云保存"对话框以解决我们 2019 年 10 月 14 日针对 16.0.11929.20396 版本发布保存问题。将很快重新启用此功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-p193">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 16.0.11929.20396. This feature will be re-enabled soon.</span></span>

## <a name="version-1908-october-14"></a><span data-ttu-id="26b59-954">版本 1908：10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="26b59-954">Version 1908: October 14</span></span>
<span data-ttu-id="26b59-955">*版本 1908（内部版本 11929.20396）*</span><span class="sxs-lookup"><span data-stu-id="26b59-955">*Version 1908 (Build 11929.20396)*</span></span>


[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="26b59-957">非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-957">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-958">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-958">Excel</span></span>

- <div><span data-ttu-id="26b59-959">解决了一个“查找和替换”问题，即在找到第一个项目后它改变了对话框中焦点的位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-959">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span></div>

### <a name="office-suite"></a><span data-ttu-id="26b59-960">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-960">Office Suite</span></span>

- <span data-ttu-id="26b59-p194">解决了用户无法为版本低于 16.0.11929.20396 的 Word、Excel 和 PowerPoint 2019 文档这一问题。 此问题会影响创建新文件的用户，以及单击"保存"图标或按 Ctrl + S 之后出现"另存为"对话框。</span><span class="sxs-lookup"><span data-stu-id="26b59-p194">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 16.0.11929.20396.  This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="26b59-963">解决了一个问题，即在某些情况下，Office 快捷方式可能会在更新后消失。</span><span class="sxs-lookup"><span data-stu-id="26b59-963">Resolved an issue where in certain circumstances, Office shortcuts may disappear following an update.</span></span>  <span data-ttu-id="26b59-964">此更新改进了发布 Office 快捷方式的可靠性。</span><span class="sxs-lookup"><span data-stu-id="26b59-964">This update improves reliability when publishing of Office shortcuts.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-october-08"></a><span data-ttu-id="26b59-966">版本 1908：10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="26b59-966">Version 1908: October 08</span></span>
<span data-ttu-id="26b59-967">*版本 1908（内部版本 11929.20388）*</span><span class="sxs-lookup"><span data-stu-id="26b59-967">*Version 1908 (Build 11929.20388)*</span></span>

<span data-ttu-id="26b59-968">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-968">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="26b59-970">非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-970">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-971">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-971">Excel</span></span>

- <span data-ttu-id="26b59-972">解决了一个阻止将超链接粘贴到某些受保护工作表中的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-972">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="26b59-973">修复了在加载项管理器中浏览时允许显示超过 16 个加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-973">Fixed an issue to enable more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="26b59-974">修复了在 Excel 创意功能中发现一个的问题，即通过单击 Win32 客户端中的“创意”按钮加载加载项时出错。</span><span class="sxs-lookup"><span data-stu-id="26b59-974">Fixed issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-975">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-975">Outlook</span></span>

- <span data-ttu-id="26b59-976">解决了导致简单悬停 URL 无法显示某些安全链接的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-976">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="26b59-977">已将 Outlook 中的附件阻止逻辑更新为也阻止 Python 附件。</span><span class="sxs-lookup"><span data-stu-id="26b59-977">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="26b59-978">解决了导致用户在 Outlook 进程中观察到内存泄漏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-978">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="26b59-979">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-979">PowerPoint</span></span>

- <span data-ttu-id="26b59-980">修复了可能会导致 PowerPoint 中涉及共同创作和脱机编辑的会话中数据丢失的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-980">Fixed an issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="26b59-981">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-981">Office Suite</span></span>

- <span data-ttu-id="26b59-982">修复了用户打开文件时可能遇到的崩溃问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-982">Fixed an issue for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="26b59-983">修复了在后台的信息放置面板中未显示可访问性信息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-983">Fixed an issue where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="26b59-984">通过恢复以前可能已中断的下载，增强了下载 Office 更新时的可靠性。</span><span class="sxs-lookup"><span data-stu-id="26b59-984">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="26b59-985">为了保护 Office 客户的安全，现在仅使用 SHA-2 算法对 Microsoft Office 更新进行签名。</span><span class="sxs-lookup"><span data-stu-id="26b59-985">To protect Office customer’s security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1908-september-10"></a><span data-ttu-id="26b59-987">版本 1908：9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="26b59-987">Version 1908: September 10</span></span>
<span data-ttu-id="26b59-988">*版本 1908（内部版本 11929.20300）*</span><span class="sxs-lookup"><span data-stu-id="26b59-988">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="26b59-989">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-989">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (请勿移除功能详细信息内容开头)

### <a name="feature-updates"></a><span data-ttu-id="26b59-991">功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-991">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="26b59-992">Access</span><span class="sxs-lookup"><span data-stu-id="26b59-992">Access</span></span>

- <span data-ttu-id="26b59-p196">**缩放更多空间：** 让缩放框变大，更改字体，缩放功能会记住一切。[了解详细信息](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)</span><span class="sxs-lookup"><span data-stu-id="26b59-p196">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all. [Learn more](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)</span></span>

- <span data-ttu-id="26b59-995">**密切关注数据库对象：** 可以清楚地看到活动选项卡，轻松拖动选项卡以重新排列它们，并且只需单击一下即可关闭数据库对象。</span><span class="sxs-lookup"><span data-stu-id="26b59-995">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="26b59-996">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="26b59-996">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="26b59-997">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-997">Switching between them has never been easier.</span></span> [<span data-ttu-id="26b59-998">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-998">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a><span data-ttu-id="26b59-999">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-999">Excel</span></span>

- <span data-ttu-id="26b59-p198">**深入发掘数据：** 全新的“想法”按钮可查找数据中的模式并使用这些模式创建智能、个性化的建议。[了解详细信息](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="26b59-p198">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="26b59-1002">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="26b59-1002">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="26b59-1003">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1003">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="26b59-1004">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="26b59-1004">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="26b59-1005">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="26b59-1005">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="26b59-1006">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="26b59-1006">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="26b59-1007">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="26b59-1007">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="26b59-1008">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-1008">Switching between them has never been easier.</span></span> [<span data-ttu-id="26b59-1009">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1009">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="26b59-1010">**见证工作表生动起来的过程：** 插入动态 3D 图形，观看心跳、行星轨道和霸王龙在整个工作簿中四处跳动。</span><span class="sxs-lookup"><span data-stu-id="26b59-1010">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="26b59-1011">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-1011">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="26b59-1012">**协作更简单：** 共同创作改进意味着使用条件格式、单元格样式等时，所做的更改将与协作者无缝合并。</span><span class="sxs-lookup"><span data-stu-id="26b59-1012">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="26b59-1013">**在类似列上连接表：** 在比较用于合并表的列时，获取和转换 (Power Query) 现在具有近似文本匹配逻辑（也称为模糊匹配）。</span><span class="sxs-lookup"><span data-stu-id="26b59-1013">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="26b59-1014">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1014">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="26b59-1015">**使用 Power Query 增强功能快速编码：** 使用自动完成和语法着色快速完成代码编写。</span><span class="sxs-lookup"><span data-stu-id="26b59-1015">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="26b59-1016">也可以轻松发现函数、列和参数。</span><span class="sxs-lookup"><span data-stu-id="26b59-1016">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="26b59-1017">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-1017">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="26b59-1018">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="26b59-1018">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="26b59-1019">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1019">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="26b59-1020">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-1020">Outlook</span></span>

- <span data-ttu-id="26b59-1021">**移动邮件时继续工作：** Outlook 现在在后台移动邮件，因此你可以在文件夹之间移动大量邮件时继续工作。</span><span class="sxs-lookup"><span data-stu-id="26b59-1021">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="26b59-1022">**在连续召开的会议之间提供时间：** 默认将会议设置为提前 5-10 分钟结束，让与会者有时间喘口气或来往于不同地点。</span><span class="sxs-lookup"><span data-stu-id="26b59-1022">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="26b59-p206">**清晰呈现思路：** 当文本或静态图像不起作用时，请使用动态 GIF 来发表你的观点。[了解详细信息](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="26b59-p206">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="26b59-1025">**我们已经为你更新了 Outlook 用户体验：** 简化的体验，以前可供预览，现即将推出，旨在帮助你关注最重要的内容。</span><span class="sxs-lookup"><span data-stu-id="26b59-1025">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="26b59-1026">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1026">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="26b59-1027">**更紧凑还是更宽松的布局？由你决定：**“更紧凑的间距”让你能够决定是希望项目之间间距更大，还是希望布局更紧凑以显示更多内容。</span><span class="sxs-lookup"><span data-stu-id="26b59-1027">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="26b59-1028">**还可自定义的简化功能区：** 最常用的按钮排成一行，带给你简化体验。</span><span class="sxs-lookup"><span data-stu-id="26b59-1028">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="26b59-1029">可在经典视图和简化视图之间轻松切换，还可固定/取消固定命令。</span><span class="sxs-lookup"><span data-stu-id="26b59-1029">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="26b59-1030">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-1030">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="26b59-1031">**添加帐户的更快捷方式：** 由于帐户设置改进，现在可以更轻松地将使用双重身份验证的 Outlook.com 和 Gmail 帐户添加到 Outlook。</span><span class="sxs-lookup"><span data-stu-id="26b59-1031">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="26b59-1032">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1032">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="26b59-1033">**挑选你喜欢的操作：** 不要使用“标志”和“删除”？</span><span class="sxs-lookup"><span data-stu-id="26b59-1033">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="26b59-1034">“存档”或“标记为已读”呢？</span><span class="sxs-lookup"><span data-stu-id="26b59-1034">How about Archive or Mark as Read?</span></span> <span data-ttu-id="26b59-1035">使用你最常用的命令自定义快速操作菜单。</span><span class="sxs-lookup"><span data-stu-id="26b59-1035">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="26b59-1036">**告别同步限制：** Outlook 改进意味着文件夹限制已取消，因此请继续操作并同步共享邮箱。</span><span class="sxs-lookup"><span data-stu-id="26b59-1036">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="26b59-1037">**搜索和享受：** 我们添加了“搜索”来插入图标，以便轻松找到所需的图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-1037">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="26b59-1038">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="26b59-1038">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="26b59-1039">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1039">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="26b59-1040">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-1040">PowerPoint</span></span>

- <span data-ttu-id="26b59-p212">**邀请受众参加测验或调查：** 幻灯片上放入测验或调查。Office 为你收集并存储该响应。[了解详细信息](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="26b59-p212">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="26b59-1044">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="26b59-1044">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="26b59-1045">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1045">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="26b59-1046">**增加内容的覆盖面：** 需要让你的演示文稿易于访问？</span><span class="sxs-lookup"><span data-stu-id="26b59-1046">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="26b59-1047">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="26b59-1047">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="26b59-1048">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="26b59-1048">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="26b59-1049">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="26b59-1049">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="26b59-p215">**比以往更轻松地插入联机视频：** 想要将 Vimeo 或 YouTube 中的视频放到幻灯片上？只需使用视频页面链接即可。[了解详细信息](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="26b59-p215">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="26b59-1053">**切换效果更好：** 对形状命名，以更好地掌控其平滑效果。</span><span class="sxs-lookup"><span data-stu-id="26b59-1053">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="26b59-1054">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-1054">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="26b59-1055">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="26b59-1055">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="26b59-1056">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-1056">Switching between them has never been easier.</span></span> [<span data-ttu-id="26b59-1057">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1057">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="26b59-1058">**联机视频获得新的存储位置：** 将视频保存到 Microsoft Stream，以便组织中的任何人都可以看到它。</span><span class="sxs-lookup"><span data-stu-id="26b59-1058">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="26b59-1059">插入视频链接，只需占用相当于相应文件大小的一小部分的空间，即可享受多媒体演示。</span><span class="sxs-lookup"><span data-stu-id="26b59-1059">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="26b59-1060">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1060">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="26b59-1061">**搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-1061">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="26b59-1062">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="26b59-1062">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="26b59-1063">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1063">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="26b59-1064">Project</span><span class="sxs-lookup"><span data-stu-id="26b59-1064">Project</span></span>

- <span data-ttu-id="26b59-1065">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="26b59-1065">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="26b59-1066">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-1066">Switching between them has never been easier.</span></span> [<span data-ttu-id="26b59-1067">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1067">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="26b59-1068">Visio</span><span class="sxs-lookup"><span data-stu-id="26b59-1068">Visio</span></span>

- <span data-ttu-id="26b59-p221">**告别断开的 Excel 链接：** 找不到链接到 Data Visualizer 图表的 Excel 工作簿？ 重新链接，你又可以开工了。[了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="26b59-p221">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="26b59-p222">**内置 Azure 模具：** 使用数十个 Azure 模具设计云应用或规划基础结构。[了解详细信息](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)</span><span class="sxs-lookup"><span data-stu-id="26b59-p222">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils. [Learn more](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)</span></span>

- <span data-ttu-id="26b59-1074">**数据流程图上的 Double-take：** 数据可视化工具流程图上引入注目的新布局干净、清爽且易于理解。</span><span class="sxs-lookup"><span data-stu-id="26b59-1074">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="26b59-1075">单击“设计”选项卡可查看选项。</span><span class="sxs-lookup"><span data-stu-id="26b59-1075">Click the Design tab for options.</span></span>

- <span data-ttu-id="26b59-1076">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="26b59-1076">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="26b59-1077">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-1077">Switching between them has never been easier.</span></span> [<span data-ttu-id="26b59-1078">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1078">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="26b59-1079">**将流程图导出至 Word：** 向 Word 文档自动添加流程图内容，如形状和元数据。</span><span class="sxs-lookup"><span data-stu-id="26b59-1079">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="26b59-1080">然后自定义文档以创建过程指南和操作手册。</span><span class="sxs-lookup"><span data-stu-id="26b59-1080">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="26b59-1081">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1081">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="26b59-1082">**从 Power BI 导出 Visio 视觉对象：** 将 Power BI 导出为 PDF、PowerPoint 文件等时，Power BI 的 Visio 视觉对象现在将会正常显示。</span><span class="sxs-lookup"><span data-stu-id="26b59-1082">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="26b59-1083">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1083">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="26b59-1084">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-1084">Word</span></span>

- <span data-ttu-id="26b59-p227">**使用笔迹编辑器随心编辑：** 使用单个笔划、拆分或连接字词、添加新行或使用手写笔插入字词。[了解详细信息](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="26b59-p227">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="26b59-p228">**将文档从静态转换为惊艳：** 将文档转换为易于共享的交互式网页，使其在任何设备上都看起来很棒。[了解更多](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="26b59-p228">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="26b59-1089">**使用 \@提及功能引起他人的注意：** 在批注中使用 @提及，以在需要他人的意见时让他们知悉。</span><span class="sxs-lookup"><span data-stu-id="26b59-1089">**Get Their Attention with \@Mentions:** Use @mentions in comments to let others know when you need their input.</span></span> [<span data-ttu-id="26b59-1090">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-1090">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="26b59-p230">**使用 Line Focus 提高理解力：** 专心地逐行浏览文档。调整焦点，一目一行、三行或五行。[了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="26b59-p230">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="26b59-1094">**快速找到文件：** 正在寻找你最近使用过的文件？</span><span class="sxs-lookup"><span data-stu-id="26b59-1094">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="26b59-1095">只需在“文件”>“主页”上的“搜索”框中输入，即可查找要寻找的文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1095">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="26b59-1096">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="26b59-1096">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="26b59-1097">**增加内容的覆盖面：** 需要让你的文档易于访问？</span><span class="sxs-lookup"><span data-stu-id="26b59-1097">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="26b59-1098">让辅助功能检查器随时进行关注，但不妨碍到你。</span><span class="sxs-lookup"><span data-stu-id="26b59-1098">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="26b59-1099">通过单击“审查”>“检查辅助功能”进行尝试 - 我们在状态栏中找到你需要查看的内容时会通知你。</span><span class="sxs-lookup"><span data-stu-id="26b59-1099">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="26b59-1100">**“学习工具”模式可额外支持更多页面颜色：** Word 中的“学习工具”添加了对更多页面主题颜色的支持，从而允许更改页面的背景色。</span><span class="sxs-lookup"><span data-stu-id="26b59-1100">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="26b59-1101">许多人在全黑或全白背景中阅读存在着困难，因此，我们扩展了电脑和 Mac 上的 Word 中的颜色选择。</span><span class="sxs-lookup"><span data-stu-id="26b59-1101">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="26b59-1102">**无缝切换：** 新的帐户管理器在同一个位置显示你的所有 Office 365 工作和个人帐户。</span><span class="sxs-lookup"><span data-stu-id="26b59-1102">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="26b59-1103">帐户之间可轻松自如切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-1103">Switching between them has never been easier.</span></span> [<span data-ttu-id="26b59-1104">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1104">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- <span data-ttu-id="26b59-1105">**搜索和享受：** 我们添加了“搜索以插入图标”，让你能轻松找到所需图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-1105">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="26b59-1106">选择时，“插入”按钮会显示已选数目。</span><span class="sxs-lookup"><span data-stu-id="26b59-1106">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="26b59-1107">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1107">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="26b59-1108">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-1108">Office Suite</span></span>

- <span data-ttu-id="26b59-1109">**Microsoft Teams 的安装：** 向 Office 365 专业增强版的现有安装添加了 Teams。</span><span class="sxs-lookup"><span data-stu-id="26b59-1109">**Installation of Microsoft Teams:** Teams is added to existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="26b59-1110">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1110">Learn more</span></span>](/deployoffice/teams-install)

- <span data-ttu-id="26b59-1111">**在更改时进行保存：** 将文件上传到 OneDrive，以确保所有更新均自动保存。</span><span class="sxs-lookup"><span data-stu-id="26b59-1111">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="26b59-1112">**隐私控制：** 对诊断数据和连接体验的全新、更新和改进控制。</span><span class="sxs-lookup"><span data-stu-id="26b59-1112">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="26b59-1113">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1113">Learn more</span></span>](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- <span data-ttu-id="26b59-1114">**Office 图标具有新的外观：** Office 图标经过重新设计，可体现简单、强大和智能的 Office 体验。</span><span class="sxs-lookup"><span data-stu-id="26b59-1114">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="26b59-1115">**Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="26b59-1115">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="26b59-1116">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1116">Learn more</span></span>](/DeployOffice/teams-install)


[//]: # (请勿移除功能详细信息内容结尾)

<br/>

[//]: # (请勿移除错误详细信息内容开头)

### <a name="non-security-updates"></a><span data-ttu-id="26b59-1119">非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1119">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="26b59-1120">Excel</span><span class="sxs-lookup"><span data-stu-id="26b59-1120">Excel</span></span>

- <span data-ttu-id="26b59-1121">修复了 Excel 中的问题，其中分配给形状或表单控件的宏可能显示不正确的错误消息，或者可能在不正确的目标区域中工作。</span><span class="sxs-lookup"><span data-stu-id="26b59-1121">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="26b59-1122">修复了以下问题：在更改数据透视表的排序方式并在与其他用户进行共同创作会话期间刷新它时可能会导致其失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-1122">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could cause it to fail.</span></span>

- <span data-ttu-id="26b59-1123">解决了导致瀑布图和漏斗图无法在插入或删除单元格时与表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1123">Fixed an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="26b59-1124">已修复了 Excel 中的合并冲突问题，该问题会导致系统提示用户重新打开工作簿以使更改生效。</span><span class="sxs-lookup"><span data-stu-id="26b59-1124">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="26b59-1125">解决了在与其他人共同创作时表旁边的剪切和粘贴操作失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1125">Fixed an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook"></a><span data-ttu-id="26b59-1126">Outlook</span><span class="sxs-lookup"><span data-stu-id="26b59-1126">Outlook</span></span>

- <span data-ttu-id="26b59-1127">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得与其 Outlook 配置文件关联的错误帐户的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1127">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="26b59-1128">解决了导致部分 POP3 用户看到无论设置如何，其所有电子邮件均采用纯文本格式的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1128">Fixed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="26b59-1129">此修补程序将还原 HTML 格式邮件的视图。</span><span class="sxs-lookup"><span data-stu-id="26b59-1129">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="26b59-1130">解决了导致用户无法通过屏幕阅读器访问位置建议的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1130">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="26b59-1131">已修复导致某些用户在尝试检索 Outlook 的云设置时遇到身份验证错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1131">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="26b59-1132">解决了导致经理不清楚代理人是否已响应指定的会议请求的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1132">Fixed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="26b59-1133">修复了导致 Outlook 用户在某些情况下“需要密码”的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1133">Fixed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="26b59-1134">解决导致当前文件夹搜索间歇性失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1134">Fixed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="26b59-1135">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="26b59-1135">Fixed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="26b59-1136">修复了导致用户在使用云附件时看到错误“无法找到此文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1136">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="26b59-1137">验证路径和文件名是否正确”的临时服务问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1137">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="26b59-1138">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1138">Learn More</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="26b59-1139">修复了以下问题：用户看到从 Outlook 上传到 OneDrive 或 Sharepoint 的文件名已更改，其中多个字符替换为下划线。</span><span class="sxs-lookup"><span data-stu-id="26b59-1139">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

- <span data-ttu-id="26b59-1140">已修复非英语用户邮件中的主题行非常小的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1140">Fixed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="26b59-1141">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="26b59-1141">PowerPoint</span></span>

- <span data-ttu-id="26b59-1142">修复了某些加载项会在图表中的形状周围引发意外错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1142">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="26b59-1143">修复了还原 PowerPoint 视频控件易于访问的名称的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1143">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="26b59-1144">修复了可能阻止某些动画启动的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-1144">Fixed an issue which could prevent some animations from starting</span></span>

### <a name="project"></a><span data-ttu-id="26b59-1145">Project</span><span class="sxs-lookup"><span data-stu-id="26b59-1145">Project</span></span>

- <span data-ttu-id="26b59-1146">修复了 Windows 7 上的用户能够从 Project Web App 和 SharePoint 网站打开项目的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1146">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>


### <a name="visio"></a><span data-ttu-id="26b59-1147">Visio</span><span class="sxs-lookup"><span data-stu-id="26b59-1147">Visio</span></span>

- <span data-ttu-id="26b59-1148">从 Visio 导出到 SVG 的操作无法用于各种形状。</span><span class="sxs-lookup"><span data-stu-id="26b59-1148">Export to SVG from Visio was not working for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="26b59-1149">Word</span><span class="sxs-lookup"><span data-stu-id="26b59-1149">Word</span></span>

- <span data-ttu-id="26b59-1150">修复了用户在 Word 文档中与他人协作时收到错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1150">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

- <span data-ttu-id="26b59-1151">修复了一个问题，该问题导致用户在尝试共享存储在 SharePoint 2016 上的文件时收到消息“抱歉，无法我们共享此内容”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1151">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>


### <a name="office-suite"></a><span data-ttu-id="26b59-1152">Office 套件</span><span class="sxs-lookup"><span data-stu-id="26b59-1152">Office Suite</span></span>

- <span data-ttu-id="26b59-1153">解决了以下问题：在某些情况下，同步引擎支持的 sharepoint 文件可能显示“已保存”，但并未真正保存任何更改。</span><span class="sxs-lookup"><span data-stu-id="26b59-1153">Fixed an issue where in some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes.</span></span>

- <span data-ttu-id="26b59-1154">修复了大型树视图失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1154">Fixed an issue where large tree views were failing.</span></span>

- <span data-ttu-id="26b59-1155">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1155">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>


[//]: # (请勿移除错误详细信息内容结尾)

## <a name="version-1902-august-13"></a><span data-ttu-id="26b59-1157">版本 1902：8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1157">Version 1902: August 13</span></span>
<span data-ttu-id="26b59-1158">*版本 1902（内部版本 11328.20392）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1158">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="26b59-1159">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1159">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1160">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1160">Excel: Non-security updates</span></span>
- <span data-ttu-id="26b59-1161">修复了表中针对已筛选切片器和未筛选切片器均显示清除筛选器图标的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1161">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1162">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1162">Outlook: Non-security updates</span></span>
- <span data-ttu-id="26b59-1163">修复了将邮箱从基本身份验证升级到新式身份验证的用户最终获得错误的关联帐户的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-1163">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1164">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1164">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="26b59-1165">修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1165">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1166">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1166">Word: Non-security updates</span></span>
- <span data-ttu-id="26b59-1167">修复了 VBA 更新字段的速度缓慢的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1167">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="26b59-1168">修复了打开某个 DOC 文件时系统表示该文件已损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1168">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="26b59-1169">修复了在与其他用户协作处理文档的情况下应用程序可能意外终止的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1169">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1170">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1170">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="26b59-1171">修复了在某些情况下设置 API 在 Office JavaScript 库中无法正常工作的问题[了解更多](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="26b59-1171">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1902-july-09"></a><span data-ttu-id="26b59-1172">版本 1902：7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1172">Version 1902: July 09</span></span>
<span data-ttu-id="26b59-1173">*版本 1902（内部版本 11328.20368）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1173">*Version 1902 (Build 11328.20368)*</span></span>

<span data-ttu-id="26b59-1174">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1174">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1175">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1175">Excel: Non-security updates</span></span>
- <span data-ttu-id="26b59-1176">修复了删除已筛选的 excel 行时速度极慢的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1176">Fixed extreme slowness Issue in deleting filtered excel rows.</span></span>
- <span data-ttu-id="26b59-1177">修复了双指滚动时会在工作表上留下灰色矩形印及 Excel 无响应的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1177">Fixed two finger scrolling causes grey rectangles to be drawn over worksheet and Excel to hang.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1178">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1178">Outlook: Non-security updates</span></span>
- <span data-ttu-id="26b59-1179">解决了以下问题：用户偶尔看到 Outlook 插入英语拼音字母, 而不是将 IME 字符窗口保持打开状态以供选择中文字词。</span><span class="sxs-lookup"><span data-stu-id="26b59-1179">Addresses an issue that caused users to occasionally see Outlook inserting English pinyin letters rather than keeping the IME candidate window open to allow the selection of Chinese words.</span></span>
- <span data-ttu-id="26b59-1180">解决了以下问题：用户看到房间被推荐为会议室，然而会议却被安排在会议室不可用时。</span><span class="sxs-lookup"><span data-stu-id="26b59-1180">Addresses an issue that caused users to see rooms being suggested for meetings that were scheduled outside of that room's availability.</span></span>
- <span data-ttu-id="26b59-1181">解决了导致用户尝试打开会议系列而不是打开主系列异常的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1181">Addresses an issue that caused users attempting to open an exception to a meeting series to instead open the master series.</span></span>
- <span data-ttu-id="26b59-1182">解决了导致用户看到“已删除项”文件夹中的项的到期日期计算错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1182">Addresses an issue that caused users to see expiry dates being calculated incorrectly for items in Deleted Items folder.</span></span>


### <a name="teams-non-security-updates"></a><span data-ttu-id="26b59-1183">Teams：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1183">Teams: Non-security updates</span></span>

- <span data-ttu-id="26b59-1184">安装完成后，Teams 安装程序现在已有用于关闭自动启动的策略。</span><span class="sxs-lookup"><span data-stu-id="26b59-1184">Teams installer has now available Policy to turn off auto-launch after installation is completed.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="26b59-1185">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1185">Visio: Non-security updates</span></span>

- <span data-ttu-id="26b59-1186">解决了 Visio 无法与 Office 365 搭配使时与 ActiveX 解决方案相关的问题，错误信息指示无法找到 riched20.dll。</span><span class="sxs-lookup"><span data-stu-id="26b59-1186">Addresses issue related to ActiveX solutions for Visio not working with Office 365, expressed as an error message stating that riched20.dll can't be found.</span></span>


### <a name="word--non-security-updates"></a><span data-ttu-id="26b59-1187">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1187">Word:  Non-security updates</span></span>

- <span data-ttu-id="26b59-1188">修复了用于禁用模板搜索栏的 GPO 设置</span><span class="sxs-lookup"><span data-stu-id="26b59-1188">Fixed GPO setting to disable template search bar</span></span>
- <span data-ttu-id="26b59-1189">修复了以下问题：在脱机并编辑仅限服务器的文档之后，用户丢失了部分更改。</span><span class="sxs-lookup"><span data-stu-id="26b59-1189">Fixed an issue where users could lose some of their changes after being offline and editing a document that was server-only.</span></span>
- <span data-ttu-id="26b59-1190">改善了启用“文档属性”中“文档部件”时的性能</span><span class="sxs-lookup"><span data-stu-id="26b59-1190">Improved performance when enabling Quick Parts for Document properties</span></span>
- <span data-ttu-id="26b59-1191">修复了从服务器首次下载修订可能失败的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-1191">Fixed an issue where first download revision from the server might fail</span></span>


### <a name="office-suite--non-security-updates"></a><span data-ttu-id="26b59-1192">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1192">Office Suite:  Non-security updates</span></span>

- <span data-ttu-id="26b59-1193">解决了以下问题：在安装其他 Office 产品或语言包时，使用共享计算机激活的设备可能会意外恢复成基于用户的激活。</span><span class="sxs-lookup"><span data-stu-id="26b59-1193">Addressed an issue where devices using shared computer activation may unexpectedly revert to user-based activation upon installation of additional Office products or language packs.</span></span>
- <span data-ttu-id="26b59-1194">修复了代理身份验证作为 SYSTEM 运行时 Office 更新受阻的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1194">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>
- <span data-ttu-id="26b59-1195">修复解决了 Office 加载项在用户配置文件更改时消失的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1195">Fixes to address Office add-ins disappearing on user profile changes.</span></span>


## <a name="version-1902-june-11"></a><span data-ttu-id="26b59-1196">版本 1902：6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1196">Version 1902: June 11</span></span>
<span data-ttu-id="26b59-1197">*版本 1902（内部版本 11328.20318）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1197">*Version 1902 (Build 11328.20318)*</span></span>
<br/><span data-ttu-id="26b59-1198">[此处](./microsoft365-apps-security-updates.md)列出安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1198">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1199">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1199">Excel: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1200">解决了将包含 XML 映射的文件保存为 PDF 时导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1200">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
 - <span data-ttu-id="26b59-1201">解决了在加载包含无效工作表名称的工作簿时导致外部链接被删除的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1201">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
 - <span data-ttu-id="26b59-1202">解决了在 Excel 中使用照相机工具会导致电子表格挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1202">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="26b59-1203">解决了导致瀑布图和漏斗图无法与插入或删除单元格时的表格同步的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1203">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
 - <span data-ttu-id="26b59-1204">解决了在工作表计算期间使用另一张工作表上的数组公式（具体取决于表）重新计算数据表时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1204">Resolved a crash when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
 - <span data-ttu-id="26b59-1205">解决了在未先签出文件的情况下阻止从 SharePoint 打开受密码保护的工作簿的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1205">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
 - <span data-ttu-id="26b59-1206">已进行更改，以确保在共享或切换“自动保存”时处理 BeforeSave 事件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1206">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1207">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1207">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1208">解决了在向“分组依据”添加第 2 个条件时导致客户看到其任务似乎消失的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1208">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1209">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1209">Word: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1210">修复了在共享当前处于协作状态的文档时生成扩展名为 .asd 的附件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1210">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="26b59-1211">修复了将评论归因于随机作者的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1211">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="26b59-1212">修复了在签出文档时删除签名的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1212">Fixed an issue in the remove signature when checking out a document.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1213">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1213">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1214">修复了在执行“撤消”操作后 VBA 报告错误形状填充状态的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1214">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>


## <a name="version-1902-may-14"></a><span data-ttu-id="26b59-1215">版本 1902：5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1215">Version 1902: May 14</span></span>
<span data-ttu-id="26b59-1216">*版本 1902（内部版本 11328.20286）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1216">*Version 1902 (Build 11328.20286)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1217">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1217">Excel: Non-security updates</span></span>
 -  <span data-ttu-id="26b59-1218">解决了在 Excel 中使用照相机工具会导致电子表格挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1218">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="26b59-1219">修复了在带有图表工作表的活动窗口中使用鼠标滚轮时导致崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1219">An issue that caused a crash when using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
 - <span data-ttu-id="26b59-1220">解决了在 SharePoint 中导入电子表格时出现“意外错误”消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1220">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
 - <span data-ttu-id="26b59-1221">解决了在打开包含使用其规则的名称和应用了自定义视图的条件格式的工作簿时导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1221">A problem that caused Excel to crash when opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
 - <span data-ttu-id="26b59-p241">使用公式超过 255 个字符的数据验证的宏可能会导致运行时错误。此问题现已更正。</span><span class="sxs-lookup"><span data-stu-id="26b59-p241">Macros using data validation with formulas longer than 255 characters may have produced run-time errors. This issue has now been corrected.</span></span>
 - <span data-ttu-id="26b59-p242">导致包含链接到其他工作簿的数据透视表的文件加载速度缓慢的问题。此问题已解决。</span><span class="sxs-lookup"><span data-stu-id="26b59-p242">A problem which caused files containing PivotTables linked to other workbooks to load slowly. This issue has been resolved.</span></span>
 - <span data-ttu-id="26b59-1226">解决了打开 HTML 文件和接收“文件格式和扩展名不匹配”错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1226">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
 - <span data-ttu-id="26b59-1227">已经进行了更改以解决在非活动窗口上滚动鼠标滚轮的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1227">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>  

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1228">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1228">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1229">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1229">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1230">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1230">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="26b59-1231">解决了 PowerPoint 停止上传用户更改到云端的问题（此情况极不常见）。</span><span class="sxs-lookup"><span data-stu-id="26b59-1231">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="26b59-1232">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1232">Skype for Business: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1233">修复了以下问题：Lync (Skype for Business) 中对于任何有 7 个以上参与者的在线会议，会议窗口可能会消失。</span><span class="sxs-lookup"><span data-stu-id="26b59-1233">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
 - <span data-ttu-id="26b59-1234">使用登录其他 Office 应用程序时所用的凭据登录 Skype for Business。</span><span class="sxs-lookup"><span data-stu-id="26b59-1234">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
 - <span data-ttu-id="26b59-1235">在安装有共享计算机激活时正确激活 Skype for Business 应用。</span><span class="sxs-lookup"><span data-stu-id="26b59-1235">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="26b59-1236">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1236">Visio: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1237">解决了导致第三方解决方案通过禁用动态 DPI 功能来扩展 Visio 时出现窗口层次结构损坏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1237">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1238">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1238">Word: Non-Security updates</span></span>
 - <span data-ttu-id="26b59-1239">解决了在编辑由 SharePoint 添加的相关人员时出现崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1239">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="26b59-1240">解决了在 Word 启动时出现“未能加载资源”对话框的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1240">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1241">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1241">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="26b59-1242">这是文件无法保存至 Apache WebDAV 文件夹问题的修复。</span><span class="sxs-lookup"><span data-stu-id="26b59-1242">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="26b59-1243">修复了在客户打开某些云存储文件时 Office 突然关闭的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1243">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="26b59-1244">修复了将采用平假名和日语汉字的新纪元名称“Reiwa”错误地标识为拼写错误或不符合语法的表达式的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1244">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="26b59-1245">解决了 Windows 10 上貌似已清除多位用户的“最近使用的文件”列表这一问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1245">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="26b59-1246">解决了即使站在进行管理器触发的更新，最终用户仍会看到“Office 更新”业务栏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1246">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="26b59-1247">解决了与登录提示间歇性空白相关的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1247">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 

## <a name="version-1902-april-9"></a><span data-ttu-id="26b59-1248">版本 1902：4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1248">Version 1902: April 9</span></span>
<span data-ttu-id="26b59-1249">*版本 1902（内部版本 11328.20230）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1249">*Version 1902 (Build 11328.20230)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1250">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1250">Excel: Non-Security updates</span></span>

- <span data-ttu-id="26b59-1251">解决了在包含以定义名称结尾的公式的单元格中按 Tab 键不会移动到下一个单元格的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1251">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="26b59-1252">解决了单元格格式化导致文件大小不必要增长的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1252">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="26b59-1253">解决了在工作簿之间剪切和粘贴数据透视表可能导致数据被粘贴的问题，不包含与你正在协作的其他人的数据透视表。</span><span class="sxs-lookup"><span data-stu-id="26b59-1253">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1254">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1254">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="26b59-1255">修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1255">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="26b59-1256">解决了导致客户在联系人卡片上加载图片时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1256">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="26b59-1257">解决了导致某些客户在启动 Office 应用程序时遇到崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1257">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="26b59-1258">修复了当系统任务栏保留在屏幕左侧或顶部时窗口不会出现在正确位置的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1258">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="26b59-1259">解决了导致客户无法在已迁移的项目上编辑部分字段的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1259">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="26b59-1260">Visio：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1260">Visio: Non-Security updates</span></span>

- <span data-ttu-id="26b59-1261">修复了以下问题：导致通过禁用动态 DPI 功能扩展 Visio 的第 3 方解决方案的窗口层次结构损坏问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1261">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling the Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1262">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1262">Word: Non-Security updates</span></span>

- <span data-ttu-id="26b59-1263">如果文件以只读模式打开，并且你从“信息”窗格中单击“另存为”，则修复问题以便显示“保存 UI”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1263">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1264">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1264">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="26b59-1265">修复了以下问题：Office 更新的某些部分不使用传递优化对等缓存。</span><span class="sxs-lookup"><span data-stu-id="26b59-1265">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="26b59-1266">了解详细信息</span><span class="sxs-lookup"><span data-stu-id="26b59-1266">Learn more</span></span>](/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="26b59-1267">修复了如果使用 Office 部署工具安装 Office 且存在不匹配的情况时，可能导致产品被删除或未激活的 bug。</span><span class="sxs-lookup"><span data-stu-id="26b59-1267">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="26b59-1268">修复了导致 Windows 10（版本 1803 或更高版本）设备上出现过多登录提示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1268">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="26b59-1269">修复了下载链接图片时导致挂起的回归。</span><span class="sxs-lookup"><span data-stu-id="26b59-1269">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="26b59-1270">修复了粘贴在 Word、Excel、PowerPoint 中的大型 EMF 文件的模糊性。</span><span class="sxs-lookup"><span data-stu-id="26b59-1270">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="26b59-1271">修复了版本历史记录解析逻辑中的 bug，这些 bug 在少数情况下会导致文档以只读方式打开。</span><span class="sxs-lookup"><span data-stu-id="26b59-1271">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="26b59-1272">版本 1902：3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1272">Version 1902: March 12</span></span>
<span data-ttu-id="26b59-1273">*版本 1902（内部版本 11328.20158）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1273">*Version 1902 (Build 11328.20158)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="26b59-1274">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1274">Access: Feature updates</span></span>

- <span data-ttu-id="26b59-p244">**刷新、重新链接或删除链接表** 更新的链接表管理器可用于管理所有数据源和链接表。[了解详细信息](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span><span class="sxs-lookup"><span data-stu-id="26b59-p244">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables. [Learn more](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span></span>
- <span data-ttu-id="26b59-p245">**将其涂成黑色，将其涂成灰色：** 根据需要随时更改 Access 的外观。四种主题可供选择：彩色、深灰色、黑色和白色。[了解详细信息](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="26b59-p245">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="26b59-1280">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1280">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="26b59-1281">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1281">Excel: Feature updates</span></span>

- <span data-ttu-id="26b59-1282">**更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-1282">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="26b59-1283">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1283">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="26b59-p247">**通过注释进行协作：** 使用内置回复框在电子表格中保持正常对话。[了解详细信息](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="26b59-p247">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>
- <span data-ttu-id="26b59-p248">**功能区图标具有新外观** 不用担心，一切功能和以前一样。这些图标在所有大小的屏幕上都很美观。[了解详细信息](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p248">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="26b59-p249">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p249">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="26b59-p250">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p250">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="26b59-p251">**呼叫所有“获取和转换”功能的粉丝** 如果你经常使用“获取和转换”功能，那么对于“从示例中添加列”功能已得到改进的消息一定兴奋不已。此外还改进了许多连接器。[了解详细信息](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span><span class="sxs-lookup"><span data-stu-id="26b59-p251">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved. And, many connectors have been improved as well. [Learn more](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span></span>
- <span data-ttu-id="26b59-p252">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p252">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>
- <span data-ttu-id="26b59-p253">**快速查找** 已极大地提升了 VLOOKUP、HLOOKUP 和 MATCH 计算速度，以便能够更快地获取答案。[了解详细信息](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span><span class="sxs-lookup"><span data-stu-id="26b59-p253">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster. [Learn more](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="26b59-1301">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1301">Outlook: Feature updates</span></span>

- <span data-ttu-id="26b59-p254">**使用“大声朗读”来收听你的电子邮件：** Outlook 可以大声朗读你的电子邮件，并突出显示正在阅读的文本。要打开大声朗读功能，请转到“轻松访问”设置。[了解详细信息](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="26b59-p254">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="26b59-1305">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="26b59-1305">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="26b59-1306">单击“听写”，即可看到 Outlook 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="26b59-1306">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="26b59-1307">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1307">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="26b59-p256">**功能区图标具有新外观** 不用担心，一切功能和以前一样。这些图标在所有大小的屏幕上都很美观。[了解详细信息](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p256">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="26b59-p257">**默认阻止下载 SMIME 加密和签名的电子邮件中的外部内容：** 鉴于 SMIME 协议中的漏洞，Outlook 将阻止下载由 SMIME 加密或签名的邮件上的外部内容。用户将无法通过 Outlook UI 单击下载外部内容，以防止受到安全漏洞的危害。“选项”对话框提供了一个新选项，用户可使用它还原至旧行为。</span><span class="sxs-lookup"><span data-stu-id="26b59-p257">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME. Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability. There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="26b59-p258">**禁用会议转发** 阻止与会者将会议转发给其他人。只需转到功能区并单击“答复选项”。[了解详细信息](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span><span class="sxs-lookup"><span data-stu-id="26b59-p258">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others. Just go to the ribbon and click Response Options. [Learn more](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span></span>
- <span data-ttu-id="26b59-p259">**日程安排助理中的人员建议：** 安排会议时查看有关要添加的与会者的建议。无需在日程安排助理和收件人行之间来回切换。[了解详细信息](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="26b59-p259">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="26b59-1320">**保留会议室变得更加容易：** 使用多个会议室列表查找会议室，切换列表时不会丢失所选的会议室。</span><span class="sxs-lookup"><span data-stu-id="26b59-1320">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="26b59-p260">**重复周期范围的新默认值：** 对于“重复周期”对话框，在过去重复周期范围的默认值为“无结束日期”。这有助于创建长期运行的定期系列，随着时间的推移可能会损坏。我们将“重复周期”对话框的默认值更新为“结束日期”，以便我们的默认值与建议的日历最佳做法相匹配。</span><span class="sxs-lookup"><span data-stu-id="26b59-p260">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date". This facilitated the creation of long-running recurring series, which can become corrupted over time. We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="26b59-p261">**从“Outlook 提醒”对话框加入团队会议：** 当 Outlook 提醒用户参加即将召开的会议时，如果即将召开的会议是团队在线会议，则它将显示一个“联机加入”按钮。这与从“Outlook 提醒”对话框加入 Skype for Business 会议的体验类似。</span><span class="sxs-lookup"><span data-stu-id="26b59-p261">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="26b59-p262">**停止查看过去活动的提醒：** 可以将日历设置为在活动结束后自动关闭活动提醒。[了解详细信息](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="26b59-p262">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
- <span data-ttu-id="26b59-1328">**查看安全链接背后的 URL：** 安全链接有助于保护你免受电子邮件中收到的恶意 URL 的攻击，但它们会隐藏原始 URL。</span><span class="sxs-lookup"><span data-stu-id="26b59-1328">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="26b59-1329">若要查看原始 URL，请将鼠标悬停在 URL上。</span><span class="sxs-lookup"><span data-stu-id="26b59-1329">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="26b59-1330">需要高级威胁防护许可证。</span><span class="sxs-lookup"><span data-stu-id="26b59-1330">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="26b59-1331">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1331">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="26b59-p264">**缩放和粘贴：** 选择默认设置用于所有邮件，而无需在每次阅读邮件时调整缩放。[了解详细信息](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span><span class="sxs-lookup"><span data-stu-id="26b59-p264">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages. [Learn more](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span></span>
- <span data-ttu-id="26b59-1334">**邮件加密：仅加密 IRM 策略：** 新的仅加密选项显示在 Office 365 邮件加密用户的“选项”>“权限”菜单中。</span><span class="sxs-lookup"><span data-stu-id="26b59-1334">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="26b59-1335">此选项允许你加密邮件并将其发送给组织内部或外部的任何人。</span><span class="sxs-lookup"><span data-stu-id="26b59-1335">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="26b59-1336">**密件抄送 (BCC) 警告：** BCC 信息提示会在你意外对被密件抄送的邮件全部答复之前发出警告。</span><span class="sxs-lookup"><span data-stu-id="26b59-1336">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="26b59-1337">**更智能的“收件人:”行：** 在单击“收件人:”行处理邮件时，会提示用户可能要选择的收件人。</span><span class="sxs-lookup"><span data-stu-id="26b59-1337">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="26b59-1338">此外，还可以看到收件人的照片，这样用户便知道将要向其发送邮件的收件人正确无误。</span><span class="sxs-lookup"><span data-stu-id="26b59-1338">Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> [<span data-ttu-id="26b59-1339">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1339">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="26b59-p267">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p267">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="26b59-p268">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p268">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="26b59-1344">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1344">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="26b59-1345">**更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-1345">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="26b59-1346">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1346">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="26b59-1347">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="26b59-1347">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="26b59-1348">单击“听写”，即可看到 PowerPoint 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="26b59-1348">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="26b59-1349">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1349">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="26b59-p271">**功能区图标具有新外观** 不用担心，一切功能和以前一样。这些图标在所有大小的屏幕上都很美观。[了解详细信息](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p271">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="26b59-p272">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p272">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>
- <span data-ttu-id="26b59-1355">**使用其他生动颜色显示超链接：** 超链接不再只是蓝色的。</span><span class="sxs-lookup"><span data-stu-id="26b59-1355">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="26b59-1356">可以根据需要应用任何字体颜色。</span><span class="sxs-lookup"><span data-stu-id="26b59-1356">Apply any font color you like.</span></span> [<span data-ttu-id="26b59-1357">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1357">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="26b59-p274">**查看栩栩如生的幻灯片：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个屏幕中横冲直撞的霸王龙。[了解详细信息](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="26b59-p274">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="26b59-p275">**用户绘制草图，我们来润色：** 我们将手绘文本和形状变为精致的图表。只需选择笔划墨迹即可开始。[了解详细信息](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="26b59-p275">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="26b59-p276">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p276">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="26b59-1366">**发布到 Microsoft Stream：** 通过使用 Microsoft Stream 在组织中更为安全地将演示文稿作为视频进行共享。 </span><span class="sxs-lookup"><span data-stu-id="26b59-1366">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="26b59-1367">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1367">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="26b59-1368">**导出为 4K 视频：** 将演示文稿导出为视频时，现在可以选择 4K 分辨率。</span><span class="sxs-lookup"><span data-stu-id="26b59-1368">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="26b59-1369">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1369">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="26b59-p279">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p279">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="26b59-1372">**大文件现在可以更快地打开：** 打开存储在 OneDrive 或 SharePoint 中的文件时，图像、视频和其他大文件现在可以在后台下载。</span><span class="sxs-lookup"><span data-stu-id="26b59-1372">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="26b59-1373">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1373">Word: Feature updates</span></span>

- <span data-ttu-id="26b59-1374">**更快开始** 新设计的“开始”页面将最近打开的文档置于前面的中心位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-1374">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="26b59-1375">减少访问文件所需的单击次数，通过“开始”页面即可打开“帐户设置”或“选项”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1375">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="26b59-1376">**无需键入，解放双手：** 有麦克风？</span><span class="sxs-lookup"><span data-stu-id="26b59-1376">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="26b59-1377">单击“听写”，即可看到 Word 随着你说话而键入文字。</span><span class="sxs-lookup"><span data-stu-id="26b59-1377">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="26b59-1378">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1378">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="26b59-p282">**查看栩栩如生的文档：** 插入动态 3D 图形，观看心跳、行星轨道以及在整个页面中横冲直撞的霸王龙。[了解详细信息](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="26b59-p282">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="26b59-p283">**功能区图标具有新外观** 不用担心，一切功能和以前一样。这些图标在所有大小的屏幕上都很美观。[了解详细信息](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p283">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="26b59-p284">**显示图片背后的内容：** 将图片置于工作表中，选择预设，然后观察透明度的变化。就是这样！[了解详细信息](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p284">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="26b59-p285">**能够插入应用了滤镜的 SVG：** Office 用户现在能够插入应用了滤镜的 SVG。[了解详细信息](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p285">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="26b59-p286">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p286">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>
- <span data-ttu-id="26b59-p287">**在 LinkedIn 的帮助下编写你的出色简历：** 通过简历助手查看工作经验、建议技能及给定角色的详细信息。 [了解详细信息](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="26b59-p287">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="26b59-1393">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1393">Project: Feature updates</span></span>

- <span data-ttu-id="26b59-p288">**在任务板卡片上了解更多信息** 如果单独的标题无法描述详情，可以自定义任务板卡片以显示所有最重要的详细信息。[了解详细信息](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="26b59-p288">**See more info on Task Board cards:** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>
- <span data-ttu-id="26b59-1396">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1396">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="26b59-1397">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1397">Publisher: Feature updates</span></span>

- <span data-ttu-id="26b59-1398">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1398">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="26b59-1399">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1399">Visio: Feature updates</span></span>

- <span data-ttu-id="26b59-1400">**在下一个图表中享受全新图标时刻：** 从 26 个新的模具中挑选，其中包含用于分析、艺术、庆祝、人脸、运动等的图标。</span><span class="sxs-lookup"><span data-stu-id="26b59-1400">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="26b59-1401">**Office 的外观焕然一新：** Office 应用程序现在具有更简单且更易于访问的新式图标，并且功能区具有更新的视觉效果，突出显示 Office 应用程序中可用的丰富协作功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1401">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="26b59-1402">Office 套件：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1402">Office Suite: Feature updates</span></span>

- <span data-ttu-id="26b59-p289">**Office 第三方应用程序现已支持通过 office.js API 插入 SVG：** 第三方应用程序也称为 Office 中的加载项，它们现可插入 SVG。用户现可将其个人的 SVG 集合连接到 Office。而开发人员可通过 Office.js API 使用该项功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-p289">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="26b59-1406">**Microsoft Teams 安装：** 默认情况下，将为现已安装的 Office 365 专业增强版安装 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="26b59-1406">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="26b59-1407">了解更多</span><span class="sxs-lookup"><span data-stu-id="26b59-1407">Learn more</span></span>](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="26b59-1408">Skype for Business：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1408">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="26b59-p291">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p291">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="teams-feature-updates"></a><span data-ttu-id="26b59-1411">Teams：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1411">Teams: Feature updates</span></span>

- <span data-ttu-id="26b59-p292">**增强了对高清晰度显示器的支持**：现在，如果用户使用多个显示器或笔记本电脑基座配件，Office 应用在每个显示器上都会有清晰画面，即使显示器有不同的缩放设置也是如此。 [了解更多](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="26b59-p292">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

## <a name="version-1808-february-12"></a><span data-ttu-id="26b59-1414">版本 1808：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1414">Version 1808: February 12</span></span>
<span data-ttu-id="26b59-1415">版本 1808（内部版本 10730.20280）</span><span class="sxs-lookup"><span data-stu-id="26b59-1415">*Version 1808 (Build 10730.20280)*</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="26b59-1416">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1416">Access: Non-Security updates</span></span> 

- <span data-ttu-id="26b59-1417">此更新将对新日本和历的支持添加到 Access。</span><span class="sxs-lookup"><span data-stu-id="26b59-1417">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1418">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1418">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="26b59-1419">解决以下问题：具有引用不再存在的文件夹规则的用户在尝试管理规则时看到错误，以及看到客户端规则运行失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-1419">Addresses an issue that caused users with rules that refer to a folder that no longer exist to see an error when trying to manage rules and to see client-side rules fail to run.</span></span>
- <span data-ttu-id="26b59-1420">处理以下问题：具有缓存委托邮箱的用户在不可预测的时间间隔遇到频繁挂起。</span><span class="sxs-lookup"><span data-stu-id="26b59-1420">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="26b59-1421">处理以下问题：由于会议结束时间设置为第二天的午夜，在一些视图中，全天会议似乎超过预期的一天时间。</span><span class="sxs-lookup"><span data-stu-id="26b59-1421">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="26b59-1422">修复了创建引用日本和历的新约会或会议时的挂起。</span><span class="sxs-lookup"><span data-stu-id="26b59-1422">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1423">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1423">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="26b59-1424">修复以下问题：使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的外接程序被冻结且不可用。</span><span class="sxs-lookup"><span data-stu-id="26b59-1424">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="26b59-1425">版本 1808：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1425">Version 1808: January 8</span></span>
<span data-ttu-id="26b59-1426">*版本 1808（内部版本 10730.20264）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1426">*Version 1808 (Build 10730.20264)*</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1427">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1427">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="26b59-1428">修复了导致用户遇到日历同步错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1428">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1429">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1429">Word: Non-security updates</span></span>

- <span data-ttu-id="26b59-1430">提高打开性能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1430">Improve open performance.</span></span>

## <a name="version-1808-december-11"></a><span data-ttu-id="26b59-1431">版本 1808：12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1431">Version 1808: December 11</span></span>
<span data-ttu-id="26b59-1432">*版本 1808（内部版本 10730.20262）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1432">*Version 1808 (Build 10730.20262)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1433">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1433">Excel: Security updates</span></span> 

-   <span data-ttu-id="26b59-1434">[CVE-2018-8597](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1434">[CVE-2018-8597](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1435">[CVE-2018-8598](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1435">[CVE-2018-8598](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1436">[CVE-2018-8627](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1436">[CVE-2018-8627](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1437">[CVE-2018-8636](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1437">[CVE-2018-8636](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1438">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1438">Outlook: Security updates</span></span> 

-   <span data-ttu-id="26b59-1439">[CVE-2018-8587](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1439">[CVE-2018-8587](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="26b59-1440">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1440">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="26b59-1441">[CVE-2018-8628](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1441">[CVE-2018-8628](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1442">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1442">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="26b59-1443">修复了以下问题：在合著会话中，当其他用户对切片器中的数据应用列筛选之后，切片器无法正确更新。</span><span class="sxs-lookup"><span data-stu-id="26b59-1443">Fixed an issue in coauthoring sessions where a slicer is not properly updated after another user applies a column filter to the data in that slicer.</span></span>
- <span data-ttu-id="26b59-1444">修复了以下问题：在合著会话中，如果其中一个用户清除了某个切片器的标题，则会导致合著会话中的其他用户遇到 Excel 崩溃的情况。</span><span class="sxs-lookup"><span data-stu-id="26b59-1444">Fixed an issue in a coauthoring session where one of the users clears the caption for a slicer and this causes another user in the coauthoring session to experience an Excel crash.</span></span>
- <span data-ttu-id="26b59-1445">修复了以下问题：将创建的多个表切片器绑定到同一数据列，然后再删除该数据列时，可能会出现崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-1445">Fixed possible crash when creating multiple table slicers bound to the same column of data and then deleting that column of data.</span></span>
- <span data-ttu-id="26b59-1446">修复了以下问题：自动调整列宽选项关闭时，如果刷新单元格中包含换行文本的已筛选查询表，Excel 有时会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-1446">Fixed an issue where Excel would sometimes crash while refreshing a filtered query table that contains wrapped text in cells when the option to automatically adjust column widths was off.</span></span>
- <span data-ttu-id="26b59-1447">修复了以下问题：当切片器中显示的项数改变时，如果在更高版本的 Excel 中打开在 Excel 2007 中保存的切片器，将会触发崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-1447">Fixed an issue where slicers saved in Excel 2007 can trigger a crash when opened in newer versions of Excel if the number of items shown in the slicer changes.</span></span>
- <span data-ttu-id="26b59-1448">引入了对“获取诊断”按钮的支持，以简化对支持请求的调查。</span><span class="sxs-lookup"><span data-stu-id="26b59-1448">Introduces support for the Get Diagnostics button to simplify the investigation of support requests.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1449">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1449">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="26b59-1450">修复了导致用户在启动“管理规则和警报”对话框时看到错误消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1450">Fixed an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="26b59-1451">修复了导致用户在使用按流量计费的连接时无法通过 DirectAccess 连接到其邮箱的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1451">Fixed an issue that caused users to be unable to connect to their mailboxes over DirectAccess when using a metered connection.</span></span>
- <span data-ttu-id="26b59-1452">修复了导致用户看到“公用文件夹”中保存的免费文本在“受保护的视图”中错误打开的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1452">Fixed an issue that caused users to see free docs stored in Public Folders erroneously open in "Protected View".</span></span>
- <span data-ttu-id="26b59-1453">修复了导致用户在转发带有内嵌附件的项目时意外看到附件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1453">Fixed an issue that caused users to see unexpected attachments when forwarding items with inline attachments.</span></span>
- <span data-ttu-id="26b59-1454">修复了导致 OFT 文件在作为附件发送之后呈现效果欠佳的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1454">Fixed an issue that caused OFT files to render poorly after being sent as an attachment.</span></span>
- <span data-ttu-id="26b59-1455">修复了导致部分使用加载项的用户在向共享日历添加会议时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1455">Fixed an issue that caused some add in users to experience crashes when adding a meeting to a shared calendar.</span></span>
- <span data-ttu-id="26b59-1456">修复了导致用户在打开“对话历史记录”文件夹时发生挂机的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1456">Fixed an issue that caused users to experience hangs when opening the Conversation History folder.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1457">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1457">Project: Non-Security updates</span></span>

- <span data-ttu-id="26b59-1458">修复了与 Project 中新增委内瑞拉货币支持相关的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1458">Fixed an issue around supporting a new Venezuelan currency in Project.</span></span>
- <span data-ttu-id="26b59-1459">修复了以下问题：使用连接到外部监视器的 Surface 4 时，Project 可能会挂机。</span><span class="sxs-lookup"><span data-stu-id="26b59-1459">Fixed an issue where Project may hang when using a Surface 4 that is connected to an external monitor.</span></span>
- <span data-ttu-id="26b59-1460">修复了以下问题：将项目保存为 XML 格式时，Project 可能会发生崩溃。</span><span class="sxs-lookup"><span data-stu-id="26b59-1460">Fixed an issue where Project may crash when saving the project to the XML format.</span></span>
- <span data-ttu-id="26b59-1461">修复了以下问题：编辑某个资源的日历之后，企业资源自定义字段可能会被删除。</span><span class="sxs-lookup"><span data-stu-id="26b59-1461">Fixed an issue where enterprise resource custom fields may be deleted after editing a resource's calendar.</span></span>
- <span data-ttu-id="26b59-1462">修复了导致用户在搜索韩语显示名称时发生崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1462">Fixed an issue that caused users to experience crashes when searching for Korean display names.</span></span>

## <a name="version-1808-november-13"></a><span data-ttu-id="26b59-1463">版本 1808：11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1463">Version 1808: November 13</span></span>
<span data-ttu-id="26b59-1464">*版本 1808（内部版本 10730.20205）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1464">*Version 1808 (Build 10730.20205)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1465">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1465">Excel: Security updates</span></span>

-   <span data-ttu-id="26b59-1466">[CVE-2018-8574](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1466">[CVE-2018-8574](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1467">[CVE-2018-8577](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1467">[CVE-2018-8577](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1468">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1468">Outlook: Security updates</span></span> 

-   <span data-ttu-id="26b59-1469">[CVE-2018-8522](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1469">[CVE-2018-8522](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1470">[CVE-2018-8524](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1470">[CVE-2018-8524](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1471">[CVE-2018-8558](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1471">[CVE-2018-8558](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1472">[CVE-2018-8576](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1472">[CVE-2018-8576](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1473">[CVE-2018-8579](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1473">[CVE-2018-8579](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1474">[CVE-2018-8582](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1474">[CVE-2018-8582](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="26b59-1475">Project：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1475">Project: Security updates</span></span> 

-   <span data-ttu-id="26b59-1476">[CVE-2018-8575](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1476">[CVE-2018-8575](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="26b59-1477">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1477">Word: Security updates</span></span> 

-   <span data-ttu-id="26b59-1478">[CVE-2018-8573](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1478">[CVE-2018-8573](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="26b59-1479">Skype for Business：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1479">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="26b59-1480">[CVE-2018-8546](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8546)：Microsoft Skype for Business 拒绝服务漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1480">[CVE-2018-8546](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1481">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1481">Excel: Non-security updates</span></span> 

- <span data-ttu-id="26b59-1482">已修复以下问题：某些内部版本/版本中不显示 Power Pivot。</span><span class="sxs-lookup"><span data-stu-id="26b59-1482">Fixed a bug where Power Pivot did not appear in some builds/versions.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1483">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1483">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="26b59-1484">已修复以下问题：用户无法成功使用帐户控制按钮在自定义窗体上的帐户之间切换。</span><span class="sxs-lookup"><span data-stu-id="26b59-1484">Fixed an issue that caused users to be unable to successfully use the Accounts control button to switch between accounts on custom forms.</span></span>
- <span data-ttu-id="26b59-1485">已修复以下问题：用户使用 ScanPST 修复 OST/PST 文件时，遇到故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1485">Fixed an issue that caused users to experience a crash when using ScanPST to repair an OST/PST file.</span></span>
- <span data-ttu-id="26b59-1486">已修复以下问题：某些邮件上的“抄送:”字段无法显示具有联机模式配置文件的用户。</span><span class="sxs-lookup"><span data-stu-id="26b59-1486">Fixed an issue that caused the CC: field on certain mail messages to fail to display for users with online mode profiles.</span></span>

### <a name="onenote-non-security-updates"></a><span data-ttu-id="26b59-1487">OneNote：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1487">OneNote: Non-security updates</span></span> 

- <span data-ttu-id="26b59-1488">修复了涉及同步和导航到已删除分区时可能出现的稳定性问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1488">Fixed a stability issue that can occur involving sync and navigating to a deleted section.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1489">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1489">Project: Non-security updates</span></span> 

- <span data-ttu-id="26b59-1490">已修复以下问题：如果在新现代体验中的 SharePoint 文档库中处理 Project 文件，“要求签出”和“只读”操作不会正确执行。</span><span class="sxs-lookup"><span data-stu-id="26b59-1490">Fixed an issue where if you were working with Project files on a SharePoint document library that was in the new modern experience, the Check-Out Required and Read-Only actions aren't being correctly followed.</span></span>


## <a name="version-1808-october-9"></a><span data-ttu-id="26b59-1491">版本 1808：10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1491">Version 1808: October 9</span></span>
<span data-ttu-id="26b59-1492">*版本 1808（内部版本 10730.20155）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1492">*Version 1808 (Build 10730.20155)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1493">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1493">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-1494">[CVE-2018-8502](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1494">[CVE-2018-8502](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1495">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1495">Outlook: Security updates</span></span> 
-   <span data-ttu-id="26b59-1496">[ADV180026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1496">[ADV180026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="26b59-1497">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1497">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="26b59-1498">[CVE-2018-8501](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1498">[CVE-2018-8501](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="26b59-1499">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1499">Word: Security updates</span></span> 
-   <span data-ttu-id="26b59-1500">[CVE-2018-8504](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1500">[CVE-2018-8504](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1501">[ADV180026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180026)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1501">[ADV180026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-1502">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1502">Office suite: Security updates</span></span> 
-   <span data-ttu-id="26b59-1503">[CVE-2018-8432](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 组件远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1503">[CVE-2018-8432](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1504">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1504">Excel: Non-Security updates</span></span> 
-   <span data-ttu-id="26b59-p293">已修复以下问题：范围 2190...2194 中的符号切换为 Cambria Math 时，Excel 单元格高度增加 3 倍。</span><span class="sxs-lookup"><span data-stu-id="26b59-p293">Fixed the issue when symbols in the range 2190...2194 are switched to Cambria Math. This is causing the Excel cell height to increase by 3 times.</span></span>
-   <span data-ttu-id="26b59-1507">已修复以下问题：当用户将鼠标悬停在具有许多定义名称的工作簿中的格式化选项上时，Excel 可能无响应，当在选项中禁用实时预览时，Excel 可能在快速分析工具中无响应。</span><span class="sxs-lookup"><span data-stu-id="26b59-1507">This fixes the issue in Excel wherein Excel may become unresponsive when the user hovers over formatting options in a workbook with many defined names, and where Excel may become unresponsive in the Quick Analysis tool even when Live Preview was disabled in options.</span></span>
-   <span data-ttu-id="26b59-p294">我们现在正在调查将 Excel 应用程序窗口从一个桌面移动到另一个桌面时性能缓慢的原因。在此期间，如果你发现了此性能缓慢，可以考虑使用以下变通方法：在“文件选项”对话框的“通用”选项卡中，针对“使用多个显示器时”选择“优化兼容性”。</span><span class="sxs-lookup"><span data-stu-id="26b59-p294">We are currently investigating slow performance when moving the Excel Application Window from one desktop to another. In the meantime, if you do notice this slowness then a work around to consider is to select "Optimize for compatibility" for "When using multiple displays" in the "General" tab in the File Options dialog.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1510">PowerPoint：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1510">PowerPoint: Non-Security updates</span></span>
-   <span data-ttu-id="26b59-1511">已修复以下问题：保存包含 ActiveX 内容的文件时，文件可能损坏。</span><span class="sxs-lookup"><span data-stu-id="26b59-1511">Fixed an issue of potential file corruptions when saving files with ActiveX content.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1512">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1512">Word: Non-Security updates</span></span>
-   <span data-ttu-id="26b59-1513">已修复以下问题：插入 Word 文档对象时，会显示公式编辑器。</span><span class="sxs-lookup"><span data-stu-id="26b59-1513">Fixed an issue that when inserting a Word Document object, the equation editor would appear.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1514">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1514">Project: Non-Security updates</span></span>
-   <span data-ttu-id="26b59-1515">已修复以下问题：如果为打印内容设置页眉或页脚，下一次打印项目时，此更改可能不会保持。</span><span class="sxs-lookup"><span data-stu-id="26b59-1515">Fixed an issue where if you set a header or footer for a print-out, the change wasn't persisted the next time you went to print your project.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1516">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1516">Office Suite: Non-Security updates</span></span>
-   <span data-ttu-id="26b59-1517">修复了以下问题：即使通过辅助功能和性能设置关闭动画，应用仍显示动画。</span><span class="sxs-lookup"><span data-stu-id="26b59-1517">Fixed issue of apps showing animations despite turning off animations through accessibility and performance settings.</span></span> 
-   <span data-ttu-id="26b59-1518">修复了以下问题：使用荧光笔绘图工具时，背景变成空白。</span><span class="sxs-lookup"><span data-stu-id="26b59-1518">Fixed issue of background turning blank when using highlighter drawing tool.</span></span>

## <a name="version-1808-september-11"></a><span data-ttu-id="26b59-1519">版本 1808：9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1519">Version 1808: September 11</span></span>
<span data-ttu-id="26b59-1520">*版本 1808（内部版本 10730.20102）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1520">*Version 1808 (Build 10730.20102)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="26b59-1521">Access：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1521">Access: Feature Updates</span></span>
 - <span data-ttu-id="26b59-p295">**利用新图表实现数据的可视化效果：** 从 11 个图表中选择一个图表并将其添加到窗体和报表，更好地实现数据的可视化效果，并做出明智的决策。[了解详细信息](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span><span class="sxs-lookup"><span data-stu-id="26b59-p295">**Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span></span>
 
 ### <a name="access-security-updates"></a><span data-ttu-id="26b59-1524">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1524">Access: Security updates</span></span>
-   <span data-ttu-id="26b59-1525">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1525">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="26b59-1526">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1526">Excel: Feature updates</span></span>
 - <span data-ttu-id="26b59-p296">**协作编辑：** 与其他人同时协作处理工作簿。[了解详细信息](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span><span class="sxs-lookup"><span data-stu-id="26b59-p296">**Collaborative editing:** Work with others at the same time in your workbook. [Learn more](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span></span>
 - <span data-ttu-id="26b59-p297">**现在，默认情况下启用云文件自动保存：** 在 2018 年 9 月半年频道（定向）发布中默认启用自动保存。此更改意味着用户无需担心丢失存储在 OneDrive 或 SharePoint Online 中的文档的更改。更改将自动保存在云端，用户无需显式按 Ctrl+S 或“保存”按钮。但是，用户必须了解此行为更改，以便不会对文档作出意外更改。注意，用户可使用屏幕顶部的“自动保存”切换关闭“自动保存”。我们建议你向用户告知此即将推出的更改，让其了解如何利用此 Office 365 新功能。[详细了解自动保存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [详细了解 IT 管理员应知晓的自动保存内容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="26b59-p297">**AutoSave for cloud files is now enabled by default:** AutoSave is enabled by default in the September 2018 Semi-Annual Channel (Targeted) release. This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to documents. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="26b59-p298">**改进了单元格和编辑栏编辑：** 现在可以按 CTRL+A 选择单元格或编辑栏中的文本。同时还改进了对表情符号和其他复杂字符的支持。[了解详细信息](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p298">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters.[Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="26b59-p299">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的工作簿更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p299">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your workbooks more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="26b59-p300">**避免不需要的编辑：** 将工作簿设置为以只读方式打开，避免意外更改。转到“文件”>“信息”>“保护工作簿”>“始终以只读方式打开”</span><span class="sxs-lookup"><span data-stu-id="26b59-p300">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1542">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1542">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-1543">[CVE-2018-8331](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1543">[CVE-2018-8331](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1544">[CVE-2018-8429](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1544">[CVE-2018-8429](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1545">[CVE-2018-8375](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1545">[CVE-2018-8375](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1546">[CVE-2018-8379](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1546">[CVE-2018-8379](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1547">[CVE-2018-8382](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1547">[CVE-2018-8382](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1548">[CVE-2018-8246](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1548">[CVE-2018-8246](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1549">[CVE-2018-8248](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1549">[CVE-2018-8248](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1550">[CVE-2018-8147](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1550">[CVE-2018-8147](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1551">[CVE-2018-8148](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1551">[CVE-2018-8148](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1552">[CVE-2018-8162](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1552">[CVE-2018-8162](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1553">[CVE-2018-8163](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1553">[CVE-2018-8163](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1554">[CVE-2018-1029](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1554">[CVE-2018-1029](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1555">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1555">Excel: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1556">已修复以下问题：从图表源数据的原始单元格集更改图表源数据时，Excel 可能出现故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1556">Fix an issue where Excel may crash when changing a chart's source data from its original set of cells.</span></span>
-   <span data-ttu-id="26b59-1557">已修复以下问题：即使已设置 FullCalcOnLoad 属性，打开时也可能不会进行重新计算。</span><span class="sxs-lookup"><span data-stu-id="26b59-1557">Fix an issue where recalculation may not happen on open even if the FullCalcOnLoad property is set.</span></span>  
-   <span data-ttu-id="26b59-1558">修复了在日期单元格格式中使用日本和历日历时显示错误年份的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1558">Fix an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
-   <span data-ttu-id="26b59-p301">将数据导入 Excel 数据模型时，传入的负零值将导致错误。此次修复将此类值导入为零。</span><span class="sxs-lookup"><span data-stu-id="26b59-p301">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>
-   <span data-ttu-id="26b59-1561">修复了以下问题：Excel 数据透视表中的组合（或取消组合）操作有时可能会触发故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1561">Fix an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>
-   <span data-ttu-id="26b59-1562">修复了制作图表操作可能导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1562">Fix an issue where charting actions could cause Excel to crash.</span></span>
-   <span data-ttu-id="26b59-1563">修复了对某些用户无意禁用 Power View 加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1563">Fix an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
-   <span data-ttu-id="26b59-1564">修复了在文档恢复期间创建的临时自动恢复文件从未清理的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1564">Fix an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
-   <span data-ttu-id="26b59-1565">修复了以下问题：尝试对受保护的工作簿中的文本文件建立新连接时收到“工作簿处于受保护状态，无法更改”的错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1565">Fix an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.</span></span>
-   <span data-ttu-id="26b59-1566">修复了以下问题：无法快速打印附加到 Outlook 电子邮件的 Excel 工作簿。</span><span class="sxs-lookup"><span data-stu-id="26b59-1566">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="26b59-1567">修复了以下问题：单击超链接可能会导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1567">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="26b59-1568">修复了以下问题：使用多维数据集函数导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1568">Fix an issue where using cube functions causes Excel to crash.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="26b59-1569">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1569">Outlook: Feature updates</span></span>
 - <span data-ttu-id="26b59-p302">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的邮件更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p302">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
 - <span data-ttu-id="26b59-p303">**从配置文件选取器管理配置文件：** 如果启动 Outlook 时使用配置文件选取器，现在可以在无需转到控制面板的情况下进行更改。可通过配置文件选取器进行创建和删除配置文件、更改设置等操作。</span><span class="sxs-lookup"><span data-stu-id="26b59-p303">**Manage Profiles from the Profile Picker:** If you use the Profile Picker when Outlook starts up, you can now make changes without going to the control panel. Create and delete profiles, change settings, all from the Profile Picker.</span></span>
- <span data-ttu-id="26b59-1574">**内置辅助功能：** 通过将说明性可选文字添加到图像，使所有人都可访问你的邮件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1574">**Accessibility built right in:** Make your messages accessible to everyone by adding descriptive alt text to your images.</span></span>
- <span data-ttu-id="26b59-p304">**Outlook 加载项警告：** Outlook COM 加载项有时会遇到导致 Outlook 其余部分运行速度变慢的问题。这些问题可能是由事件延迟导致的，例如在 Outlook 文件夹之间切换、新邮件的到达、正在打开日历项目等。出现此类问题时，Outlook 将在通知栏中显示一条警告。</span><span class="sxs-lookup"><span data-stu-id="26b59-p304">**Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.</span></span>
- <span data-ttu-id="26b59-1577">**知道将与谁一起开会：** 即使你不是组织者，现在也可以看到其他人对会议请求的响应。</span><span class="sxs-lookup"><span data-stu-id="26b59-1577">**Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.</span></span>
- <span data-ttu-id="26b59-p305">**绝不错过任何提醒：** 设置在工作窗口中弹出的提醒。如果不设置，Outlook 会在任务栏中闪烁，以引起用户注意。[了解详细信息](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="26b59-p305">**Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention.[Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
- <span data-ttu-id="26b59-p306">**将已删除邮件标记为已读：** 现在可以将任何已删除邮件设置为已读。启用方法为，依次转到“文件”\>“选项”\>“邮件”\>“其他”。</span><span class="sxs-lookup"><span data-stu-id="26b59-p306">**Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.</span></span>
- <span data-ttu-id="26b59-p307">**查看 3 个时区：** 需要跨时区安排会议？将多个时区添加到日历，轻松地查看每个人的空闲时间并选择适合所有人的时间。[了解详细信息](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span><span class="sxs-lookup"><span data-stu-id="26b59-p307">**View three time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span></span>
- <span data-ttu-id="26b59-1585">**优化创建组的用户体验：** 已优化创建组的用户体验，使其更现代、更简便。[了解详细信息](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span><span class="sxs-lookup"><span data-stu-id="26b59-1585">**Refined user experience for creating a group:** We have refined the user experience for the create group to make it look more modern and clutter-free.[Learn more](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1586">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1586">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-1587">[CVE-2018-8310](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 篡改漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1587">[CVE-2018-8310](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>
-   <span data-ttu-id="26b59-1588">[CVE-2018-8244](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1588">[CVE-2018-8244](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="26b59-1589">[CVE-2018-8150](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1589">[CVE-2018-8150](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="26b59-1590">[ADV180021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1590">[ADV180021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1591">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1591">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1592">已修复以下问题：如果将系统语言切换为日语并且尝试将日语字符键入 VBA IDE，在 Outlook 中加载时，可能会冻结。</span><span class="sxs-lookup"><span data-stu-id="26b59-1592">Fix an issue where if you switch the system language to Japanese and attempt to type Japanese characters into the VBA IDE when loaded within Outlook, it freezes.</span></span>
-   <span data-ttu-id="26b59-1593">修复了切换到发件箱或已发送邮件文件夹会导致 Outlook 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1593">Fix an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
-   <span data-ttu-id="26b59-1594">修复了当会议正文或附件更改时，所有与会者都会收到会议更新（而不是向与会者发送会议更新）属于可选项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1594">Fix an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
-   <span data-ttu-id="26b59-1595">修复了由于 User-Agent 字符串的更改，导致用户无法连接到 EWS 和 REST 终结点的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1595">Fix an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>
-   <span data-ttu-id="26b59-1596">修复了以下问题：对与会者更新的会议地点显示旧位置，而不是新位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-1596">Fix an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
-   <span data-ttu-id="26b59-1597">修复了以下问题：用户在阅读窗格中预览附件时看到错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1597">Fix an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
-   <span data-ttu-id="26b59-1598">修复了以下问题：在用户撰写电子邮件期间，Outlook 将显示名称解析为电子邮件地址时发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1598">Fix an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
-   <span data-ttu-id="26b59-1599">修复了以下问题：一些用户没有收到租户管理员已启用的支持功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1599">Fix an issue where some users don't receive support features that have been enabled by their tenant admin.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="26b59-1600">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1600">PowerPoint: Feature updates</span></span> 
- <span data-ttu-id="26b59-p308">**现在，默认情况下启用云文件自动保存：** 在 2018 年 9 月半年频道（定向）发布中默认启用自动保存。此更改意味着用户无需担心丢失存储在 OneDrive 或 SharePoint Online 中的文档的更改。更改将自动保存在云端，用户无需显式按 Ctrl+S 或“保存”按钮。但是，用户必须了解此行为更改，以便不会对演示文稿作出意外更改。注意，用户可使用屏幕顶部的“自动保存”切换关闭“自动保存”。我们建议你向用户告知此即将推出的更改，让其了解如何利用此 Office 365 新功能。[详细了解自动保存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [详细了解 IT 管理员应知晓的自动保存内容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="26b59-p308">**AutoSave for cloud files is now enabled by default:** AutoSave is enabled by default in the September 2018 Semi-Annual Channel (Targeted) release. This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="26b59-p309">**转换墨迹：** 获取自由曲线备注和绘图，并将它们转换为可读文本和清晰形状，以创建完善的演示文稿。[了解详细信息](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span><span class="sxs-lookup"><span data-stu-id="26b59-p309">**Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span></span>
- <span data-ttu-id="26b59-p310">**改进了 SVG 支持：** 可以插入应用了筛选器的 SVG。[了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p310">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="26b59-p311">**使用手写笔为幻灯片添加标题：** 使用手写笔撰写标题，然后 PowerPoint 会将它转换为文本。[了解更多](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="26b59-p311">**Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="26b59-p312">**避免不需要的编辑：** 将工作簿设置为以只读方式打开，避免意外更改。转到“文件”>“信息”>“保护工作簿”>“始终以只读方式打开”</span><span class="sxs-lookup"><span data-stu-id="26b59-p312">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>
- <span data-ttu-id="26b59-p313">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使演示文稿更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p313">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your presentations more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1618">PowerPoint：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1618">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1619">修复了表格显示不正常并带有粗边框的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1619">Fix an issue where tables are rendered incorrectly with thick borders.</span></span>
-   <span data-ttu-id="26b59-1620">修复了以下问题：更改 Shape.Visibile 属性时，可能会发生潜在故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1620">Fix an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
-   <span data-ttu-id="26b59-1621">修复了以下问题：无法合并合著文档中的更改。</span><span class="sxs-lookup"><span data-stu-id="26b59-1621">Fix an issue where changes in co-authored documents fail to merge.</span></span>
-   <span data-ttu-id="26b59-1622">修复了以下问题：包含 ActiveX 控件的文档会导致合著失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-1622">Fix an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>
-   <span data-ttu-id="26b59-1623">修复了在形状中使用拼写更正导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1623">Fix an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>
-   <span data-ttu-id="26b59-1624">修复了从 SharePoint Online 打开文件时 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1624">Fix an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="26b59-1625">修复了当自动保存处于打开状态时，恢复窗格错误打开的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1625">Fix an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
-   <span data-ttu-id="26b59-1626">修复了不显示登录，从而阻止用户访问文件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1626">Fix an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>
-   <span data-ttu-id="26b59-1627">修复了以下问题：多个用户在同一个演示文稿中共同创作导致幻灯片母板复制不正确。</span><span class="sxs-lookup"><span data-stu-id="26b59-1627">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="26b59-1628">修复了以下问题：打开保存在 OneDrive 上的文件导致 PowerPoint 在退出受保护的视图时出现故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1628">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="26b59-1629">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1629">Project: Feature updates</span></span> 
- <span data-ttu-id="26b59-1630">**冲刺 (sprint) 管理：** 快速添加、更新或删除敏捷冲刺 (sprint)。</span><span class="sxs-lookup"><span data-stu-id="26b59-1630">**Sprint management:** Quickly add, update, or delete agile sprints.</span></span>
- <span data-ttu-id="26b59-1631">**任务板筛选：** 通过筛选主要资源或摘要任务来简化任务板。</span><span class="sxs-lookup"><span data-stu-id="26b59-1631">**Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.</span></span>
- <span data-ttu-id="26b59-1632">**在任务板中设置完成百分比：** 为每列都选择一个完成百分比，再通过拖放操作来更新任务完成进度。</span><span class="sxs-lookup"><span data-stu-id="26b59-1632">**Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.</span></span>
- <span data-ttu-id="26b59-1633">**冲刺 (sprint) 导航：** 从一个冲刺 (sprint) 视图切换到另一个，并在两个冲刺 (sprint) 视图之间快速移动任务。</span><span class="sxs-lookup"><span data-stu-id="26b59-1633">**Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.</span></span>
- <span data-ttu-id="26b59-p314">**管理冲刺 (sprint) 的新方法：** 采用敏捷方法来处理任务板。转到管理冲刺 (sprint) ，随着你的项目演进添加和删除冲刺 (sprint)。</span><span class="sxs-lookup"><span data-stu-id="26b59-p314">**A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.</span></span>
- <span data-ttu-id="26b59-p315">**最近保存位置有条理：** Project 通过可不断扩充的列表列出了其他项目的保存位置。准备保存项目时，只需选择最近保存位置之一，即可继续工作。</span><span class="sxs-lookup"><span data-stu-id="26b59-p315">**Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1638">Project 非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1638">Project non-security updates</span></span>
- <span data-ttu-id="26b59-1639">修复了以下问题：通过主项目的上下文处理子项目时，无法保存子项目。</span><span class="sxs-lookup"><span data-stu-id="26b59-1639">Fix an issue where you are blocked from saving a sub project when working with them through the context of a master project.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="26b59-1640">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1640">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="26b59-p316">修复了与 TLS 1.2 支持相关的问题。（注意：这是 4 月 10 日说明中提到的同一个修补程序。在这里作为 9 月汇总的一部分再次提到。）</span><span class="sxs-lookup"><span data-stu-id="26b59-p316">Fix an issue related to TLS 1.2 support. (Note: This is the same fix that was mentioned in the April 10 notes and is mentioned here again as part of the September rollup.)</span></span>
-   <span data-ttu-id="26b59-1643">修复了在会议中通过选择“Skype 通话”来添加用户导致出错的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1643">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="26b59-1644">如果 Skype 会议室已被添加为位置且会议已包含 Teams 会议协调人，则删除要求用户向会议添加 Skype 协调人的提示。</span><span class="sxs-lookup"><span data-stu-id="26b59-1644">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
-   <span data-ttu-id="26b59-1645">修复了以下问题：即使将 UseLocationForE911Only 设置为 true，位置也会被填充。</span><span class="sxs-lookup"><span data-stu-id="26b59-1645">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="26b59-1646">修复了以下问题：通过“使用会议中心呼叫”选项邀请名单中的用户时，Skype for Business 挂起。</span><span class="sxs-lookup"><span data-stu-id="26b59-1646">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="26b59-1647">修复了以下问题：创建 Skype for Business 会议期间，终端服务器上运行的 Outlook 冻结。</span><span class="sxs-lookup"><span data-stu-id="26b59-1647">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="26b59-1648">将 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的默认值更改为 TRUE。</span><span class="sxs-lookup"><span data-stu-id="26b59-1648">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="26b59-1649">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1649">Visio: Feature updates</span></span>
- <span data-ttu-id="26b59-1650">**保持图表和源同步：** 在 Visio 中编辑数据可视化工具图表时，可以视需要根据最新图表内容，更新链接的 Excel 源数据。</span><span class="sxs-lookup"><span data-stu-id="26b59-1650">**Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.</span></span>
- <span data-ttu-id="26b59-1651">**数据可视化工具审核模板：** 从 Excel 导入内容，并创建财务交易记录、库存管理等的审计图。</span><span class="sxs-lookup"><span data-stu-id="26b59-1651">**Data Visualizer audit template:** Import content from Excel and create audit diagrams for financial transactions, inventory management, and more.</span></span>
- <span data-ttu-id="26b59-1652">**入门图表：** 组织结构图、头脑风暴和 SDL 模板具有新的入门图表，让你能够快速使用起来。</span><span class="sxs-lookup"><span data-stu-id="26b59-1652">**Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.</span></span>
 - <span data-ttu-id="26b59-p317">**利用 Visio 形状生成 Word 文档：** 自动向 Word 文档添加关系图内容（包括形状和元数据）。然后对文档进行自定义，以创建过程准则和操作手册。[了解详细信息](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="26b59-p317">**Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="26b59-1656">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1656">Word: Feature updates</span></span>
- <span data-ttu-id="26b59-p318">**现在，默认情况下启用云文件自动保存：** 在 2018 年 9 月半年频道（定向）发布中默认启用自动保存。此更改意味着用户无需担心丢失存储在 OneDrive 或 SharePoint Online 中的文档的更改。更改将自动保存在云端，用户无需显式按 Ctrl+S 或“保存”按钮。但是，用户必须了解此行为更改，以便不会对演示文稿作出意外更改。注意，用户可使用屏幕顶部的“自动保存”切换关闭“自动保存”。我们建议你向用户告知此即将推出的更改，让其了解如何利用此 Office 365 新功能。[详细了解自动保存](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [详细了解 IT 管理员应知晓的自动保存内容]</span><span class="sxs-lookup"><span data-stu-id="26b59-p318">**AutoSave for cloud files is now enabled by default:** AutoSave is enabled by default in the September 2018 Semi-Annual Channel (Targeted) release. This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Learn more about what IT admins should know about AutoSave]</span></span>
- <span data-ttu-id="26b59-p319">**辅助功能检查器改进：** 辅助功能检查器已更新了对国际标准与推荐的支持，以使你的文档更易于访问。[了解详细信息](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p319">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your documents more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="26b59-p320">**改进了 SVG 支持：** 可以插入应用了筛选器的 SVG。[了解更多](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="26b59-p320">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="26b59-1668">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1668">Word: Security updates</span></span>
-   <span data-ttu-id="26b59-1669">[CVE-2018-8430](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8430)：Word PDF 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1669">[CVE-2018-8430](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1670">[CVE-2018-0919](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1670">[CVE-2018-0919](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1671">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1671">Word: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1672">修复了导致出现内存不足消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1672">Fix an issue that causes an insufficient memory message to appear.</span></span>
-   <span data-ttu-id="26b59-1673">修复了阻止某些用户打开由其他组织中的人员与其共享的受 IRM 保护的文档和电子邮件的一系列问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1673">Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.</span></span>
-   <span data-ttu-id="26b59-1674">修复了一些性能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1674">Fixed some performance issues.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-1675">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1675">Office Suite: Security updates</span></span>
-   <span data-ttu-id="26b59-1676">[CVE-2018-8332](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8332)：Win32k Graphics 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1676">[CVE-2018-8332](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1677">[CVE-2018-8378](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1677">[CVE-2018-8378](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1678">[CVE-2018-8281](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1678">[CVE-2018-8281](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1679">[CVE-2018-8157](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1679">[CVE-2018-8157](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1680">[CVE-2018-8158](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1680">[CVE-2018-8158](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1681">[CVE-2018-0950](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1681">[CVE-2018-0950](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1682">[CVE-2018-1026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1682">[CVE-2018-1026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1683">[CVE-2018-1030](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1683">[CVE-2018-1030](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-p321">
  \*\*出于安全考虑，禁止在 Office 中激活 Flash、Silverlight 和 Shockwave 控件：\*\* 出于安全考虑，Windows 上的 Microsoft Office for Office 365 新版本阻止激活 Flash、Silverlight 和 Shockwave 控件。可通过[此处](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和[此处](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)了解详细信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-p321">**Flash, Silverlight and Shockwave controls blocked from activating in Office for security reasons:** For security reasons new builds of Microsoft Office for Office 365 on Windows block activation of Flash, Silverlight, and Shockwave controls. Learn more [here](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) and [here](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1686">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1686">Office Suite: Non-security updates</span></span>
-  <span data-ttu-id="26b59-1687">修复了在某些场景中导致更新安装所用时间过长的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1687">Fixed an issue that caused update install to take a long time in certain scenarios.</span></span>
-  <span data-ttu-id="26b59-1688">修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1688">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
-  <span data-ttu-id="26b59-1689">修复了一些性能问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1689">Fixed some performance issues.</span></span>

## <a name="version-1803-august-14"></a><span data-ttu-id="26b59-1690">版本 1803：8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1690">Version 1803: August 14</span></span>
<span data-ttu-id="26b59-1691">*版本 1803（内部版本 9126.2275）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1691">*Version 1803 (Build 9126.2275)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="26b59-1692">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1692">Access: Security updates</span></span>
-   <span data-ttu-id="26b59-1693">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1693">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1694">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1694">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-1695">[CVE-2018-8375](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1695">[CVE-2018-8375](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1696">[CVE-2018-8379](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1696">[CVE-2018-8379](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="26b59-1697">[CVE-2018-8382](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1697">[CVE-2018-8382](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1698">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1698">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-1699">[ADV180021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1699">[ADV180021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-1700">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1700">Office Suite: Security updates</span></span>
-   <span data-ttu-id="26b59-1701">[CVE-2018-8378](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1701">[CVE-2018-8378](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 

## <a name="version-1803-july-10"></a><span data-ttu-id="26b59-1702">版本 1803：7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1702">Version 1803: July 10</span></span>
<span data-ttu-id="26b59-1703">*版本 1803（内部版本 9126.2259）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1703">*Version 1803 (Build 9126.2259)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="26b59-1704">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1704">Access: Security updates</span></span>
-   <span data-ttu-id="26b59-1705">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 远程代码执行释放后使用漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1705">[CVE-2018-8312](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1706">Outlook：安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1706">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-1707">[CVE-2018-8310](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 篡改漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1707">[CVE-2018-8310](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-1708">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1708">Office Suite: Security updates</span></span>
-   <span data-ttu-id="26b59-1709">[CVE-2018-8281](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1709">[CVE-2018-8281](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1710">Excel：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1710">Excel: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1711">修复了在日期单元格格式中使用日本和历日历时显示错误年份的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1711">Fix an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
-   <span data-ttu-id="26b59-p322">将数据导入 Excel 数据模型时，传入的负零值将导致错误。此次修复将此类值导入为零。</span><span class="sxs-lookup"><span data-stu-id="26b59-p322">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1714">PowerPoint：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1714">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1715">修复了表格显示不正常并带有粗边框的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1715">Fixes issue where tables are rendered incorrectly with thick borders.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1716">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1716">Project: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1717">修复了以下问题：如果使用成本资源对任务进行拆分，则成本资源无法正确更新且成本丢失。</span><span class="sxs-lookup"><span data-stu-id="26b59-1717">Fixed an issue where if a task is split with a cost resource, the cost resource isn't correctly updated and the cost is lost.</span></span>
-   <span data-ttu-id="26b59-1718">修复了以下问题：“日程表”视图中的“将现有任务添加到日程表”对话框仅显示第一个摘要任务中的任务。</span><span class="sxs-lookup"><span data-stu-id="26b59-1718">Fixed an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>
-   <span data-ttu-id="26b59-1719">修复了以下问题：将 Project Online 或 Project Server 中的主项目另存为 XML 可能会失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-1719">Fixed an issue where saving as XML may fail for master projects from Project Online or Project Server.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1720">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1720">Office Suite: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1721">修复了在某些应用场景中导致更新安装所用时间过长的 bug。</span><span class="sxs-lookup"><span data-stu-id="26b59-1721">Fix a bug that caused update install to take a long time in certain scenarios.</span></span> 
-   <span data-ttu-id="26b59-1722">修复了 SVG 测试失败的问题</span><span class="sxs-lookup"><span data-stu-id="26b59-1722">Fix an issue where SVG tests are failing</span></span>
-   <span data-ttu-id="26b59-1723">修复了以下问题：使用 Configuration Manager 将更新部署到运行 Office 应用程序的客户端时，在 Office 应用程序正在运行的情况下重启设备后更新未应用。</span><span class="sxs-lookup"><span data-stu-id="26b59-1723">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>


## <a name="version-1803-june-12"></a><span data-ttu-id="26b59-1724">版本 1803：6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1724">Version 1803: June 12</span></span>
<span data-ttu-id="26b59-1725">*版本 1803（生成号 9126.2227）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1725">*Version 1803 (Build 9126.2227)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1726">Excel：安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1726">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-1727">[CVE-2018-8246](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1727">[CVE-2018-8246](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1728">[CVE-2018-8248](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1728">[CVE-2018-8248](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1729">Excel：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1729">Excel: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1730">修复了以下问题：Excel 数据透视表中的组合（或取消组合）操作有时可能会触发故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1730">Fix an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1731">Outlook：安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1731">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-1732">[CVE-2018-8244](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1732">[CVE-2018-8244](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1733">PowerPoint：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1733">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1734">修复了以下问题：更改 Shape.Visibile 属性时，可能会发生潜在故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1734">Fix an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
-   <span data-ttu-id="26b59-1735">修复了以下问题：无法合并合著文档中的更改。</span><span class="sxs-lookup"><span data-stu-id="26b59-1735">Fix an issue where changes in co-authored documents fail to merge.</span></span>
-   <span data-ttu-id="26b59-1736">修复了以下问题：包含 ActiveX 控件的文档会导致合著失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-1736">Fix an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1737">Project：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="26b59-1737">Project: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1738">修复了以下问题：“日程表”视图“将现有任务添加到日程表”对话框仅显示第一个摘要任务中的任务。</span><span class="sxs-lookup"><span data-stu-id="26b59-1738">Fix an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1739">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1739">Office Suite: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1740">修复了以下问题：使用 Configuration Manager 将更新部署到运行 Office 应用程序的客户端时，在 Office 应用程序正在运行的情况下重启设备后更新未应用。</span><span class="sxs-lookup"><span data-stu-id="26b59-1740">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>



## <a name="version-1803-may-18"></a><span data-ttu-id="26b59-1741">版本 1803：5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1741">Version 1803: May 18</span></span>
<span data-ttu-id="26b59-1742">*版本 1803（内部版本 9126.2210）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1742">*Version 1803 (Build 9126.2210)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1743">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1743">Excel: Non-security updates</span></span>
- <span data-ttu-id="26b59-1744">修复了制作图表操作可能导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1744">Fix an issue where charting actions could cause Excel to crash.</span></span>
- <span data-ttu-id="26b59-1745">修复了对某些用户无意禁用 Power View 加载项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1745">Fix an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
- <span data-ttu-id="26b59-1746">修复了在文档恢复期间创建的临时自动恢复文件从未清理的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1746">Fix an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
- <span data-ttu-id="26b59-1747">修复了以下问题：尝试对受保护的工作簿中的文本文件建立新连接时收到“工作簿处于受保护状态，无法更改”的错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1747">Fix an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1748">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1748">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="26b59-1749">修复了在形状中使用拼写更正导致 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1749">Fix an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-1750">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1750">Office suite: Non-security updates</span></span>
- <span data-ttu-id="26b59-1751">修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1751">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>



## <a name="version-1803-may-8"></a><span data-ttu-id="26b59-1752">版本 1803：5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1752">Version 1803: May 8</span></span>
<span data-ttu-id="26b59-1753">*版本 1803（内部版本 9126.2191）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1753">*Version 1803 (Build 9126.2191)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1754">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1754">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-1755">[CVE-2018-8147](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1755">[CVE-2018-8147](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1756">[CVE-2018-8148](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1756">[CVE-2018-8148](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1757">[CVE-2018-8162](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1757">[CVE-2018-8162](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1758">[CVE-2018-8163](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1758">[CVE-2018-8163](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1759">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1759">Excel: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1760">修复了从 SharePoint Online 打开文件时 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1760">Fix an issue where Excel crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="26b59-1761">修复了打印或打印预览只打印或显示工作表部分，内容被工作表上的切片器截断的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1761">Fix a problem where print or print preview only prints or displays a portion of the worksheet, with the content being truncated at a slicer on the worksheet.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1762">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1762">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-1763">[CVE-2018-8150](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1763">[CVE-2018-8150](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1764">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1764">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1765">修复了切换到发件箱或已发送邮件文件夹会导致 Outlook 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1765">Fix an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
-   <span data-ttu-id="26b59-1766">修复了当会议正文或附件更改时，所有与会者都会收到会议更新（而不是向与会者发送会议更新）属于可选项的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1766">Fix an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
-   <span data-ttu-id="26b59-1767">修复了由于 User-Agent 字符串的更改，导致用户无法连接到 EWS 和 REST 终结点的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1767">Fix an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1768">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1768">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1769">修复了从 SharePoint Online 打开文件时 PowerPoint 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1769">Fix an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="26b59-1770">修复了当自动保存处于打开状态时，恢复窗格错误打开的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1770">Fix an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
-   <span data-ttu-id="26b59-1771">修复了不显示登录，从而阻止用户访问文件的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1771">Fix an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1772">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1772">Project: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1773">修复了在日期列使用自动筛选下拉菜单导致 Project 中的所有任务被隐藏的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1773">Fix an issue where using the AutoFilter dropdown on a date column causes all tasks in the project to be hidden.</span></span>
-   <span data-ttu-id="26b59-1774">修复了在日程表视图中时，当将现有任务添加到日程表时，只有第一个摘要任务中的任务会显示在对话框中的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1774">Fix an issue where only tasks from the first summary task show up in the dialog box when adding existing tasks to a timeline when in Timeline view.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1775">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1775">Word: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1776">修复了从 SharePoint Online 打开文件时 Word 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1776">Fix an issue where Word crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="26b59-1777">修复了小写罗马数字页码 被错误地更改为大写的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1777">Fix an issue where lower-case Roman number page numbers are incorrectly changed to upper case.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-1778">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1778">Office suite: Security updates</span></span>
-   <span data-ttu-id="26b59-1779">[CVE-2018-8157](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1779">[CVE-2018-8157](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1780">[CVE-2018-8158](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1780">[CVE-2018-8158](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1803-april-10"></a><span data-ttu-id="26b59-1781">版本 1803：4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1781">Version 1803: April 10</span></span>
<span data-ttu-id="26b59-1782">*版本 1803（内部版本 9126.2152）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1782">*Version 1803 (Build 9126.2152)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1783">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1783">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-1784">[CVE-2018-1029](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1784">[CVE-2018-1029](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1785">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1785">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1786">修复了以下问题：多个用户在同一个演示文稿中共同创作导致幻灯片母板复制不正确。</span><span class="sxs-lookup"><span data-stu-id="26b59-1786">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="26b59-1787">修复了以下问题：打开保存在 OneDrive 上的文件导致 PowerPoint 在退出受保护的视图时出现故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1787">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="26b59-1788">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1788">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1789">修复了与 TLS 1.2 支持相关的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1789">Fix an issue related to TLS 1.2 support.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1790">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1790">Word: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1791">修复了导致出现内存不足消息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1791">Fix an issue that causes an insufficient memory message to appear.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-1792">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1792">Office suite: Security updates</span></span>
-   <span data-ttu-id="26b59-1793">[CVE-2018-0950](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1793">[CVE-2018-0950](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1794">[CVE-2018-1026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1794">[CVE-2018-1026](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1795">[CVE-2018-1030](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1795">[CVE-2018-1030](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1803-march-20"></a><span data-ttu-id="26b59-1796">版本 1803：3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1796">Version 1803: March 20</span></span>
<span data-ttu-id="26b59-1797">*版本 1803（内部版本 9126.2098）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1797">*Version 1803 (Build 9126.2098)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1798">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1798">Excel: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1799">修复了以下问题：无法快速打印附加到 Outlook 电子邮件的 Excel 工作簿。</span><span class="sxs-lookup"><span data-stu-id="26b59-1799">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="26b59-1800">修复了以下问题：单击超链接可能会导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1800">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="26b59-1801">修复了以下问题：使用多维数据集函数导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1801">Fix an issue where using cube functions causes Excel to crash.</span></span>

### <a name="onedrive-for-business-non-security-updates"></a><span data-ttu-id="26b59-1802">OneDrive for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1802">OneDrive for Business: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1803">修复了以下问题：OneDrive for Business (Groove.exe) 在任务管理器中长时间使用 CPU 的一个 CPU 内核资源（例如，4 核 CPU 的 25%）。</span><span class="sxs-lookup"><span data-stu-id="26b59-1803">Fix an issue where OneDrive for Business (Groove.exe) consumes one CPU core’s worth of CPU (for example, 25% on a 4 core CPU) in Task Manager for extended periods of time.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1804">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1804">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1805">修复了以下问题：对与会者更新的会议地点显示旧位置，而不是新位置。</span><span class="sxs-lookup"><span data-stu-id="26b59-1805">Fix an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
-   <span data-ttu-id="26b59-1806">修复了以下问题：用户在阅读窗格中预览附件时看到错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1806">Fix an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
-   <span data-ttu-id="26b59-1807">修复了以下问题：在用户撰写电子邮件期间，Outlook 将显示名称解析为电子邮件地址时发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1807">Fix an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
-   <span data-ttu-id="26b59-1808">修复了以下问题：一些用户没有收到租户管理员已启用的支持功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1808">Fix an issue where some users don't receive support features that have been enabled by their tenant admin.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-1809">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1809">Word: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1810">修复了以下问题：如果运行 Windows 7 的计算机未安装 [客户体验和诊断遥测更新](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)，无法打开 Word。</span><span class="sxs-lookup"><span data-stu-id="26b59-1810">Fix an issue where Word won’t open on a computer running Windows 7 that doesn't have the [update for customer experience and diagnostic telemetry](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry) installed.</span></span>
-   <span data-ttu-id="26b59-1811">修复了以下问题：无法打印列表中的项目符号。</span><span class="sxs-lookup"><span data-stu-id="26b59-1811">Fix an issue where bullets in lists don’t print.</span></span>



## <a name="version-1803-march-13"></a><span data-ttu-id="26b59-1812">版本 1803：3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="26b59-1812">Version 1803: March 13</span></span>
<span data-ttu-id="26b59-1813">*版本 1803（内部版本 9126.2072）*</span><span class="sxs-lookup"><span data-stu-id="26b59-1813">*Version 1803 (Build 9126.2072)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="26b59-1814">Access：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1814">Access: Security updates</span></span>
-   <span data-ttu-id="26b59-1815">[CVE-2018-0903](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1815">[CVE-2018-0903](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="26b59-1816">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1816">Access: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1817">修复了以下问题：打开 Access 运行时应用程序 (.accde file) 导致“无法识别此数据库的格式”错误消息出现，且应用程序无法打开。</span><span class="sxs-lookup"><span data-stu-id="26b59-1817">Fix an issue where opening an Access runtime application (.accde file) results in a "This database is in an unrecognized format" error message and the application won’t open.</span></span>
-   <span data-ttu-id="26b59-1818">修复了以下问题：尝试选择文本框或组合框中的文本时，似乎会选择所有文本，而不是指示的选择内容。</span><span class="sxs-lookup"><span data-stu-id="26b59-1818">Fix an issue where attempting to select text in a text box or combo box appears to select all the text, rather than the indication selection.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="26b59-1819">Excel：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1819">Excel: Feature updates</span></span>
-   <span data-ttu-id="26b59-p323">**Microsoft Translator：** 使用 Microsoft Translator 将字词、短语或句子翻译成其他语言。可以在功能区的“审阅”选项卡中执行此操作。</span><span class="sxs-lookup"><span data-stu-id="26b59-p323">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="26b59-1822">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。</span><span class="sxs-lookup"><span data-stu-id="26b59-1822">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="26b59-1823">**取消选中单元格：** 在工作表中进行选择，并取消选中不小心单击的单元格，而不必重新开始。</span><span class="sxs-lookup"><span data-stu-id="26b59-1823">**Deselect cells:** Make selections in your worksheet and deselect cells that you accidentally clicked without having to start over.</span></span>
-   <span data-ttu-id="26b59-1824">**快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。</span><span class="sxs-lookup"><span data-stu-id="26b59-1824">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="26b59-p324">**数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。</span><span class="sxs-lookup"><span data-stu-id="26b59-p324">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="26b59-p325">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="26b59-p325">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="26b59-p326">**3D 模型：** 使用 3D 增强工作簿的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="26b59-p326">**3D models:** Use 3D to increase the visual and creative impact of your workbooks.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="26b59-1832">**新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。</span><span class="sxs-lookup"><span data-stu-id="26b59-1832">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="26b59-p327">**共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。</span><span class="sxs-lookup"><span data-stu-id="26b59-p327">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="26b59-p328">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="26b59-p328">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="26b59-p329">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p329">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="26b59-1842">**按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。</span><span class="sxs-lookup"><span data-stu-id="26b59-1842">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="26b59-p330">**触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。</span><span class="sxs-lookup"><span data-stu-id="26b59-p330">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-1845">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1845">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-1846">[CVE-2017-11877](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1846">[CVE-2017-11877](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11877): Microsoft Excel Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="26b59-1847">[CVE-2017-11878](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1847">[CVE-2017-11878](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11878): Microsoft Excel Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-1848">[CVE-2017-11884](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1848">[CVE-2017-11884](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11884): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-1849">[CVE-2018-0796](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1849">[CVE-2018-0796](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1850">[CVE-2018-0841](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1850">[CVE-2018-0841](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1851">[CVE-2018-0907](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全功能规避漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1851">[CVE-2018-0907](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>
-   <span data-ttu-id="26b59-1852">[公告 170021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1852">[Advisory 170021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-1853">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1853">Excel: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1854">修复了以下问题：如果编辑语言是日语、中文或韩语，那么尝试在“开始”选项卡上选择新字体或进行编辑时，Excel 可能会冻结。</span><span class="sxs-lookup"><span data-stu-id="26b59-1854">Fix an issue where, if your editing language is Japanese, Chinese, or Korean, Excel may freeze when you try to choose a new font on the Home tab or when you edit.</span></span>
-   <span data-ttu-id="26b59-1855">修复了以下问题：在最小化 Excel 后打开工作簿时，缺少滚动条。</span><span class="sxs-lookup"><span data-stu-id="26b59-1855">Fix an issue where the scroll bars are missing when a workbook is opened when Excel is minimized.</span></span>
-   <span data-ttu-id="26b59-1856">修复了以下问题：在文件资源管理器中双击文件名打开多个工作簿时，工作簿引用失败。</span><span class="sxs-lookup"><span data-stu-id="26b59-1856">Fix an issue where workbook references fail when opening multiple workbooks by double-clicking on the file names in File Explorer.</span></span>
-   <span data-ttu-id="26b59-1857">修复了以下问题：以编程方式依次创建数据透视表和刷新导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1857">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="26b59-1858">修复了以下问题：以编程方式调用 Workbook.Open() 可能会导致 Excel 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1858">Fix an issue where programmatically calling Workbook.Open() may cause Excel to crash.</span></span>
-   <span data-ttu-id="26b59-1859">修复了以下问题：使用宏打开 Office 2007 或更低版本工作簿（.xls 或 .xla）时，用户错误地看到“灾难性故障”错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1859">Fix an issue where the user incorrectly sees a "catastrophic failure" error message when opening an Office 2007 or older workbook (.xls or .xla) with macros.</span></span>
-   <span data-ttu-id="26b59-1860">修复了以下问题：Excel 可能会在用户打开关联菜单时发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1860">Fix an issue where Excel might crash when a user opens a context menu.</span></span>
-   <span data-ttu-id="26b59-1861">修复了以下问题：当用户尝试在现有的工作簿中插入对象时，用户单击“浏览”导致 Excel 发生故障的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1861">Fix an issue where, when the user tries to insert an object in an existing workbook, Excel crashes when the user clicks Browse.</span></span>
-   <span data-ttu-id="26b59-1862">修复了以下问题：如果使用密码保护区域，看不到用于输入密码以解锁区域的对话框。</span><span class="sxs-lookup"><span data-stu-id="26b59-1862">Fix an issue where, when protecting a range with a password, the dialog box to enter the password to unlock the range isn't visible.</span></span>
-   <span data-ttu-id="26b59-1863">修复了以下问题：当文件名包含方括号时，用户无法关闭受保护的视图中的工作簿。</span><span class="sxs-lookup"><span data-stu-id="26b59-1863">Fix an issue where the user can't close a workbook in protected view when the file name contains square brackets.</span></span>
-   <span data-ttu-id="26b59-1864">修复了以下问题：拖动或拖动填充时，工具提示的位置未对齐。</span><span class="sxs-lookup"><span data-stu-id="26b59-1864">Fix an issue where placement of the tooltip is misaligned when dragging or drag filling.</span></span>
-   <span data-ttu-id="26b59-1865">修复了以下问题：使用“文件”\>“另存为”保存工作簿时，包含句点的文件名在文件保存对话框中显示为空白或被截断。</span><span class="sxs-lookup"><span data-stu-id="26b59-1865">Fix an issue where, when saving a workbook by using File \> Save As, a file name that contains periods appears blank or truncated in the file save dialog.</span></span>
-   <span data-ttu-id="26b59-p331">修复了以下问题：保存支持同步的文件时，Office 无法写入磁盘，但 Office 仍然将该文件上传到 OneDrive。使用此修复程序后，用户现在将看到一条错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="26b59-p331">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="26b59-1868">Outlook：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1868">Outlook: Feature updates</span></span>
-   <span data-ttu-id="26b59-1869">**轻松排序电子邮件：** 感谢提供反馈，我们已为未使用重点收件箱的用户，在邮件列表和未读邮件筛选器上方恢复了排序功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-1869">**Sort your email with ease:** Thanks to your feedback, we've brought back sorting above the message list and the Unread filter for people who don't use Focused Inbox.</span></span>
-   <span data-ttu-id="26b59-1870">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，以便可更改其颜色、大小或纹理。</span><span class="sxs-lookup"><span data-stu-id="26b59-1870">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="26b59-1871">**Office 365 群组的改进：** 阅读和回复群组对话比以往更加简便，因为可以双击群组消息，在它自己的窗口中打开消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1871">**Improvements to Office 365 groups:** It’s easier than ever to read and reply to group conversations because you can double-click on a group message to open it in its own window.</span></span>
-   <span data-ttu-id="26b59-p332">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="26b59-p332">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="26b59-p333">**3D 模型：** 使用 3D 增强电子邮件的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="26b59-p333">**3D models:** Use 3D to increase the visual and creative impact of your email.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="26b59-1877">**个人资料卡片：** 无论是桌面版、Web 版还是使用移动应用，都显示与人员和群组最相关的详细信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1877">**Profile card:** Shows you the most relevant details about people and groups, whether you’re on the desktop, the web, or using a mobile app.</span></span>
-   <span data-ttu-id="26b59-1878">**将约会添加到群组日历中：** 现在无需以电子邮件方式发送会议安排，即可让群组中的所有人都知道你何时离开。</span><span class="sxs-lookup"><span data-stu-id="26b59-1878">**Add an appointment to a group calendar:** Now you can let everyone in your group know when you’ll be away without sending a meeting in email.</span></span>
-   <span data-ttu-id="26b59-1879">**下载云附件：** 将 OneDrive 附件保存或拖放到计算机后，我们会为用户下载文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1879">**Downloading cloud attachments:** When you save or drag and drop OneDrive attachments to your computer, we download the file for you.</span></span>
-   <span data-ttu-id="26b59-p334">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p334">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="26b59-p335">**重点收件箱：** 收件箱分为两个选项卡 – 重点和其他。邮件根据邮件内容以及最常与之交互的联系人进行排序。 [了解更多](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span><span class="sxs-lookup"><span data-stu-id="26b59-p335">**Focused Inbox:** The Inbox is separated into two tabs – Focused and Other. Messages are sorted based on the content of the message and who you interact with most often. [Learn more](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span></span>
-   <span data-ttu-id="26b59-1887">**快速访问最常用的组：** 最常与之交互的组现在显示在“文件夹”窗格的“组”下方列表的顶部。</span><span class="sxs-lookup"><span data-stu-id="26b59-1887">**Quickly access the groups you use most:** Groups you're most likely to interact with now appear at the top of the list under Groups in the Folder pane.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-1888">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1888">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-1889">[CVE-2017-11939](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1889">[CVE-2017-11939](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11939): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-1890">[CVE-2018-0791](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1890">[CVE-2018-0791](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1891">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1891">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-1892">[CVE-2018-0850](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1892">[CVE-2018-0850](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="26b59-1893">[CVE-2018-0852](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1893">[CVE-2018-0852](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="26b59-1894">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1894">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1895">修复了以下问题：在搜索范围为全部邮箱时，搜索失败且看到“找不到匹配”错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1895">Fix an issue where search fails with “No matches found” when search is scoped to All Mailboxes.</span></span>
-   <span data-ttu-id="26b59-1896">修复了以下问题：如果在使用可访问事件观察程序 (AccEvent.exe) 进行监视时切换文件夹，导致 Outlook 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1896">Fix an issue where, when monitoring using Accessible Event Watcher (AccEvent.exe), Outlook crashes when switching folders.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="26b59-1897">PowerPoint：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1897">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="26b59-p336">**Microsoft Translator：** 使用 Microsoft Translator 将字词、短语或句子翻译成其他语言。可以在功能区的“审阅”选项卡中执行此操作。</span><span class="sxs-lookup"><span data-stu-id="26b59-p336">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="26b59-1900">**3D 动画：** 通过添加轻轻摇摆、跳跃和旋转等动画效果，让你的 3D 模型活起来。</span><span class="sxs-lookup"><span data-stu-id="26b59-1900">**3D animations:** Bring your 3D models to life with animations such as swinging gently or jumping and turning.</span></span>
-   <span data-ttu-id="26b59-1901">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。</span><span class="sxs-lookup"><span data-stu-id="26b59-1901">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="26b59-1902">**修订跟踪信息漫游：** 突出显示其他人修改的共享幻灯片的已读/未读状态，现在存储在漫游服务中（而不是存储在用户本地计算机上），这样就可以跨多个设备或平台同步此类信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1902">**Roaming of revision tracking info:** The read/unread status for highlighting shared slides that have been modified by others is now stored in a roaming service (instead of on the user's local computer) so that this information can be synchronized across multiple devices or platforms.</span></span>
-   <span data-ttu-id="26b59-1903">**快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。</span><span class="sxs-lookup"><span data-stu-id="26b59-1903">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="26b59-p337">**数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。</span><span class="sxs-lookup"><span data-stu-id="26b59-p337">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="26b59-p338">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="26b59-p338">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="26b59-p339">**使用数控笔执行幻灯片放映：** 使用 Surface 触控笔或其他带有蓝牙按钮的触笔切换幻灯片。需要安装 Windows 10 Fall Creators Update。 [了解更多](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span><span class="sxs-lookup"><span data-stu-id="26b59-p339">**Run a slide show with your digital pen:** Use your Surface Pen, or other pen with a Bluetooth button, to advance your slides. Windows 10 Fall Creators Update is required. [Learn more](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span></span>
-   <span data-ttu-id="26b59-p340">**3D 模型：** 使用 3D 增强演示文稿的视觉效果和创意效果。使用切换效果（例如可在幻灯片之间打造电影动画效果的“平滑”）使演示文稿中的 3D 模型栩栩如生。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="26b59-p340">**3D models:** Use 3D to increase the visual and creative impact of your presentations. Bring 3D models to life in your presentations with transitions like Morph that create cinematic animations between slides. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="26b59-1914">**新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。</span><span class="sxs-lookup"><span data-stu-id="26b59-1914">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="26b59-p341">**共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。</span><span class="sxs-lookup"><span data-stu-id="26b59-p341">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="26b59-p342">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="26b59-p342">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="26b59-1920">**修订突出显示：** 突出显示由其他用户已修改的幻灯片。</span><span class="sxs-lookup"><span data-stu-id="26b59-1920">**Revision highlighting:** Slides that have been modified by other users are highlighted.</span></span>
-   <span data-ttu-id="26b59-1921">**离开期间：** PowerPoint 显示自你上次访问以后对共享演示文稿进行过编辑的用户。</span><span class="sxs-lookup"><span data-stu-id="26b59-1921">**While you were away:** PowerPoint shows you who edited your shared presentation since your last visit.</span></span>
-   <span data-ttu-id="26b59-1922">**设计器改进：** 现在，设计器会推荐有关项目符号列表中日程表的设计灵感。</span><span class="sxs-lookup"><span data-stu-id="26b59-1922">**Designer improvement:** Designer now recommends design ideas for timelines in a bulleted list.</span></span>
-   <span data-ttu-id="26b59-p343">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p343">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="26b59-1927">**按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。</span><span class="sxs-lookup"><span data-stu-id="26b59-1927">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="26b59-p344">**触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。</span><span class="sxs-lookup"><span data-stu-id="26b59-p344">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="26b59-1930">**设计器改进：** 设计器现在为幻灯片中添加的图表提供设计灵感建议。</span><span class="sxs-lookup"><span data-stu-id="26b59-1930">**Designer improvement:** Designer now recommends design ideas for charts added to your slides.</span></span>
-   <span data-ttu-id="26b59-p345">**快速启动：** 自动生成大纲，帮助用户开始研究他们所选的主题。[了解详细信息](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span><span class="sxs-lookup"><span data-stu-id="26b59-p345">**QuickStarter:** Automatically builds an outline to help users get started researching a subject of their choosing. [Learn more](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span></span>
-   <span data-ttu-id="26b59-p346">**数字标尺：** 在具有触摸屏的设备上，转到“绘图”\>“标尺”，然后使用笔或手指绘制直线或对齐一组对象。 [了解更多](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span><span class="sxs-lookup"><span data-stu-id="26b59-p346">**Digital ruler:** On devices that have touch screens, go to Draw \> Ruler, then use your pen or finger to draw straight lines or to align a set of objects. [Learn more](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span></span>

### <a name="powerpoint-security-updates"></a><span data-ttu-id="26b59-1935">PowerPoint：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1935">PowerPoint: Security updates</span></span>
-   <span data-ttu-id="26b59-1936">[CVE-2017-11934](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-1936">[CVE-2017-11934](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint Information Disclosure Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="26b59-1937">PowerPoint：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1937">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1938">修复了以下问题：删除文档属性和个人信息导致无法保存到 SharePoint。</span><span class="sxs-lookup"><span data-stu-id="26b59-1938">Fix an issue where removing document properties and personal information causes saving to SharePoint to fail.</span></span>
-   <span data-ttu-id="26b59-p347">修复了以下问题：引用基于 Flash Player 的 YouTube 嵌入代码，导致打开新窗口来播放视频。旧嵌入代码现已升级为，引用基于 HTML5 的 YouTube 视频，以便正确就地播放这些视频。</span><span class="sxs-lookup"><span data-stu-id="26b59-p347">Fix an issue where references to Flash Player based YouTube embed codes result in a new window opening to play the video. Old embed codes are now upgraded to reference HTML5 based YouTube videos so that they correctly play in place.</span></span>
-   <span data-ttu-id="26b59-p348">修复了以下问题：保存支持同步的文件时，Office 无法对磁盘执行写入操作，但 Office 仍继续将文件上传到 OneDrive。修复此问题后，用户现在会看到错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="26b59-p348">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="26b59-1943">Project：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1943">Project: Feature updates</span></span>
-   <span data-ttu-id="26b59-p349">**“任务板”视图：** 在“任务板”视图中，对卡片上的任务进行排序。在任务板上的各栏之间重新排序和移动卡片，就跟在敏捷项目中一样。</span><span class="sxs-lookup"><span data-stu-id="26b59-p349">**Task Board view:** Sort tasks on cards in the Task Board view. Reorder and move cards between columns on the board just like in Agile projects.</span></span>
-   <span data-ttu-id="26b59-p350">**敏捷项目：** 使用积压工作 (backlog)、任务板、冲刺 (sprint) 等管理敏捷项目。支持使用 Scrum 或看板方法。[了解详细信息](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="26b59-p350">**Agile projects:** Manage your Agile projects using backlogs, task boards, sprints, and more. Both Scrum or Kanban methodologies are supported. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>  
-   <span data-ttu-id="26b59-p351">**在规划器中管理任务：** 将项目任务关联到规划器，并为任务创建计划。将任务分解为子任务，添加团队，分配任务，并管理任务板上的工时。</span><span class="sxs-lookup"><span data-stu-id="26b59-p351">**Manage a task in Planner:** Link a Project task to Planner and create a plan for it. Break the task into subtasks, add a team, assign tasks, and manage the work on a task board.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="26b59-1951">Project：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1951">Project: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1952">修复了以下问题：在会话中设置多个基线会将 MOD\_DATE 值设为相同的值。</span><span class="sxs-lookup"><span data-stu-id="26b59-1952">Fix an issue where setting more than one baseline in a session sets the MOD\_DATE value as the same.</span></span>
-   <span data-ttu-id="26b59-1953">修复了以下问题：在“​​保存以共享”会话中删除“实际工时”后，它仍显示在报表中。</span><span class="sxs-lookup"><span data-stu-id="26b59-1953">Fix an issue where Actual Work is still shown in the reporting tables after being removed in a Save for Sharing session.</span></span>
-   <span data-ttu-id="26b59-1954">修复了进行日程安排时在德语版本中使用“星期”日期格式返回错误的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1954">Fix an issue in the German language version where using a Weeks date format returns an error when scheduling.</span></span>
-   <span data-ttu-id="26b59-1955">修复了在日程安排 Web 部件中编辑完成日期时任务每天停留 8 小时而不随着时间推移的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1955">Fix an issue where, when editing finish dates in Schedule Web Part, tasks stay at 8 hours per day instead of being spread over time.</span></span>
-   <span data-ttu-id="26b59-1956">修复了以下问题：在意外位置绘制“进度点形状”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1956">Fix an issue where "Progress point shape" is drawn at an unexpected location.</span></span>
-   <span data-ttu-id="26b59-1957">修复了以下问题：VBA 代码从项目中丢失。</span><span class="sxs-lookup"><span data-stu-id="26b59-1957">Fix an issue where VBA code gets lost from projects.</span></span>
-   <span data-ttu-id="26b59-1958">修复了以下问题：即使还有剩余工时，任务也仍显示为已完成。</span><span class="sxs-lookup"><span data-stu-id="26b59-1958">Fix an issue where tasks show as complete even when there is remaining work.</span></span>
-   <span data-ttu-id="26b59-1959">修复了在使用任务路径功能时项目挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1959">Fix an issue where Project hangs when using the Task Path feature.</span></span>
-   <span data-ttu-id="26b59-1960">修复了时间刻度不显示时间刻度标签的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1960">Fix an issue where the timescale doesn't show the timescale labels.</span></span>
-   <span data-ttu-id="26b59-1961">修复了视觉对象报表显示信息不完整或完全无法显示信息的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1961">Fix an issue where visual reports show incomplete information or fail completely.</span></span>
-   <span data-ttu-id="26b59-1962">修复了以下问题：如果保存失败，则会损坏文件，并导致 Project 在打开时发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1962">Fix an issue where a failed save can corrupt a file and cause Project to crash on open.</span></span>
-   <span data-ttu-id="26b59-1963">修复了以下问题：无法在“日程表和工作组规划器”视图中拖动任务。</span><span class="sxs-lookup"><span data-stu-id="26b59-1963">Fix an issue where you can't drag tasks in the Timeline and Team Planner view.</span></span>
-   <span data-ttu-id="26b59-1964">修复了以下问题：工作组生成器中不显示资源可用性。</span><span class="sxs-lookup"><span data-stu-id="26b59-1964">Fix an issue where resource availability isn't shown in Team Builder.</span></span>
-   <span data-ttu-id="26b59-1965">修复了图形指示器未正确显示的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1965">Fix an issue where graphical indicators aren't displaying correctly.</span></span>
-   <span data-ttu-id="26b59-1966">修复了在按小时或按天的基础上调配时项目挂起的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1966">Fix an issue where Project hangs while leveling on hour-by-hour or day-by-day basis.</span></span>
-   <span data-ttu-id="26b59-1967">修复了从 SharePoint 文档库使用主项目/子项目的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1967">Fix an issue for working with master/sub projects from a SharePoint Document library.</span></span>
-   <span data-ttu-id="26b59-1968">修复了在将作业添加到固定工期任务时，最终可能获得无名资源的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1968">Fix an issue where, when you add assignments to a fixed duration task, you may end up with a nameless resource.</span></span>
-   <span data-ttu-id="26b59-1969">修复了以下问题：更改受保护的工时看到不正确的错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1969">Fix an issue that produces an incorrect error message of change on protected work.</span></span>
-   <span data-ttu-id="26b59-1970">修复了以下问题：转到包含多个图像的报表时，Project 可能会发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-1970">Fix an issue where Project might crash when going to reports that contain several images.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="26b59-1971">Publisher：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1971">Publisher: Feature updates</span></span>
-   <span data-ttu-id="26b59-p352">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="26b59-p352">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="publisher-non-security-updates"></a><span data-ttu-id="26b59-1975">Publisher：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1975">Publisher: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1976">修复了以下问题：运行“邮件合并”向导时，无法筛选包含 null（空）值的数据源字段。</span><span class="sxs-lookup"><span data-stu-id="26b59-1976">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="26b59-1977">Skype for Business：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-1977">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="26b59-1978">修复了在会议中通过选择“Skype 通话”来添加用户导致出错的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1978">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="26b59-1979">如果 Skype 会议室已被添加为位置且会议已包含 Teams 会议协调人，则删除要求用户向会议添加 Skype 协调人的提示。</span><span class="sxs-lookup"><span data-stu-id="26b59-1979">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
-   <span data-ttu-id="26b59-1980">修复了以下问题：即使将 UseLocationForE911Only 设置为 true，位置也会被填充。</span><span class="sxs-lookup"><span data-stu-id="26b59-1980">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="26b59-1981">修复了以下问题：通过“使用会议中心呼叫”选项邀请名单中的用户时，Skype for Business 挂起。</span><span class="sxs-lookup"><span data-stu-id="26b59-1981">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="26b59-1982">修复了以下问题：创建 Skype for Business 会议期间，终端服务器上运行的 Outlook 冻结。</span><span class="sxs-lookup"><span data-stu-id="26b59-1982">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="26b59-1983">将 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的默认值更改为 TRUE。</span><span class="sxs-lookup"><span data-stu-id="26b59-1983">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>
-   <span data-ttu-id="26b59-1984">修复了以下问题：当会议处于全屏模式时，“更多选项”和“邀请更多人”按钮隐藏。</span><span class="sxs-lookup"><span data-stu-id="26b59-1984">Fix an issue where "More Options" and "Invite More People" buttons are hidden when a meeting is in full-screen mode.</span></span>
-   <span data-ttu-id="26b59-1985">修复了尝试加入时 P2P 音频呼叫窗口或电话会议窗口变成透明的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1985">Fix an issue where the P2P audio call window or conference call window becomes transparent when you attempt to join.</span></span>
-   <span data-ttu-id="26b59-1986">修复了即将开始的 Skype 会议不出现在“会议”选项卡中的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1986">Fix an issue where upcoming Skype meetings do not show up in the meetings tab.</span></span>
-   <span data-ttu-id="26b59-1987">修复了在没有音频的情况下配置 Skype for Business 以加入会议时，添加音频到会议会对用户本人启动一个新的 P2P 呼叫，而不是添加音频到现有会议的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1987">Fix an issue where, when Skype for Business is configured to join meetings without audio, adding audio to a meeting initiates a new P2P call to the user itself rather than adding audio to the existing meeting.</span></span>
-   <span data-ttu-id="26b59-1988">修复了以下问题：在 Outlook 中单击会议请求内的“加入 Skype 会议”链接时，用户看到“找不到此 Skype 会议”错误消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1988">Fix an issue where user receives the error message "We couldn't find this Skype meeting" when clicking 'Join Skype Meeting' link in a meeting request from Outlook.</span></span>
-   <span data-ttu-id="26b59-1989">在用于传入 PSTN 呼叫的 Toast UI 中添加呼叫转移按钮。</span><span class="sxs-lookup"><span data-stu-id="26b59-1989">Add call transfer button in the toast UI for incoming PSTN calls.</span></span>
-   <span data-ttu-id="26b59-1990">当 ChatDefaultClient 和 CallDefaultClient 设置为“团队”时，通知用户呼叫和聊天正在发送到“团队”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1990">Notify users that calls and chat are being sent to Teams when ChatDefaultClient and CallDefaultClient are set to Teams.</span></span>
-   <span data-ttu-id="26b59-1991">当用户不在会议中时，显示用户为“离线”状态，并禁用 Skype for Business，同时会议加入体验设置为“本机有限客户端”。</span><span class="sxs-lookup"><span data-stu-id="26b59-1991">Show user's presence as Offline when user is not in a meeting and disabled from Skype for Business and meeting join experience is set to Native Limited Client.</span></span>
-   <span data-ttu-id="26b59-1992">当 Skype for Business 最小化到通知区域时，禁用除“打开”和“退出”外的所有选项。</span><span class="sxs-lookup"><span data-stu-id="26b59-1992">Disable all options except Open and Exit when Skype for Business is minimized to the notification area.</span></span>
-   <span data-ttu-id="26b59-1993">当启用与 Aries 手机和 RedirectClient 配对时，禁止新的呼叫和对话。</span><span class="sxs-lookup"><span data-stu-id="26b59-1993">Suppress new calls and conversations when paired with Aries phones and RedirectClient is enabled.</span></span>
-   <span data-ttu-id="26b59-1994">修复了日期格式不是美国格式 (mm/dd/yy) 时，按日期在 PChat 中搜索消息失败的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-1994">Fix an issue where searching messages in PChat by date fails when the date format is other than US format (mm/dd/yy).</span></span>
-   <span data-ttu-id="26b59-1995">修复了以下问题：当 EnableExternalP2PFileTransfer 策略设置为 false 时，用户仍能在会议中附加文件。</span><span class="sxs-lookup"><span data-stu-id="26b59-1995">Fix an issue where, when EnableExternalP2PFileTransfer policy is set to false, users are still able to attach files in meetings.</span></span>
-   <span data-ttu-id="26b59-p353">修复了以下问题：对话历史记录中显示的是呼叫方，而不是被叫方。如果使用 Active Directory 修改被叫方的工作电话号码，就会出现此问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-p353">Fix an issue where, in Conversation History, the caller is shown instead of the called person. This happens when the called person's work number is modified using Active Directory.</span></span>
-   <span data-ttu-id="26b59-1998">修复了以下问题：对于向手机号码拨出的传出 PSTN 呼叫，对话历史记录中的呼叫历史记录内缺少接听人信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-1998">Fix an issue where, for outgoing PSTN calls to mobile numbers, recipient information is missing in the call history in conversation history.</span></span>
-   <span data-ttu-id="26b59-1999">修复了以下问题：从 Outlook 中的电子邮件启动 IM 时，IM 的主题中没有电子邮件的主题行。</span><span class="sxs-lookup"><span data-stu-id="26b59-1999">Fix an issue where, when initiating an IM from an email in Outlook, the subject line of the email is not included in the subject of the IM.</span></span>
-   <span data-ttu-id="26b59-2000">修复了以下问题：当 IM 对话窗口贴靠到一侧时，对话出现双层堆叠。</span><span class="sxs-lookup"><span data-stu-id="26b59-2000">Fix an issue where, when IM conversation windows are snapped to one side, conversations appear double stacked.</span></span>
-   <span data-ttu-id="26b59-2001">修复了以下问题：在 VDIv2 环境中，VbSS 屏幕共享请求显示为 基于 RDP 的请求。</span><span class="sxs-lookup"><span data-stu-id="26b59-2001">Fix an issue where, in a VDIv2 environment, VbSS screen sharing requests appear as RDP-based requests.</span></span>
-   <span data-ttu-id="26b59-2002">修复了以下问题：当呼叫转移失败时，失败通知中列出的是呼叫方，而不是未接来电的接听人。</span><span class="sxs-lookup"><span data-stu-id="26b59-2002">Fix an issue where, in a failed call transfer, the caller is listed in the failure notification, instead of the missed recipient.</span></span>
-   <span data-ttu-id="26b59-2003">修复了以下问题：客户端升级重定向横幅中隐藏“开始使用 Teams”按钮。</span><span class="sxs-lookup"><span data-stu-id="26b59-2003">Fix an issue where the "Start using Teams" button is hidden within the client upgrade redirect banner.</span></span>
-   <span data-ttu-id="26b59-2004">修复了以下问题：IM 窗口中的 DPI 缩放问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-2004">Fix DPI scaling issues in IM windows.</span></span>
-   <span data-ttu-id="26b59-2005">修复了以下问题：Skype for Business 联系人卡片中不显示 LinkedIn 数据。</span><span class="sxs-lookup"><span data-stu-id="26b59-2005">Fix an issue where LinkedIn data does not appear in the Skype for Business Contact Card.</span></span>
-   <span data-ttu-id="26b59-2006">用户现在可以代表智能寻线停止接听电话。</span><span class="sxs-lookup"><span data-stu-id="26b59-2006">Add the ability for users to stop receiving calls on behalf of a hunt group.</span></span>
-   <span data-ttu-id="26b59-2007">如果 Skype for Business 或 Teams 中有通话正在进行中，且接听或启动了新电话，现在可以自动保持呼叫。</span><span class="sxs-lookup"><span data-stu-id="26b59-2007">Add the ability to automatically hold calls when a call is active in Skype for Business or Teams and a new call is received or initiated.</span></span>
-   <span data-ttu-id="26b59-2008">修复了以下问题：用户在共享全屏后无法发送 IM。</span><span class="sxs-lookup"><span data-stu-id="26b59-2008">Fix an issue where users are unable to IM after full screen sharing.</span></span>
-   <span data-ttu-id="26b59-2009">修复了以下问题：会议厅中的用户在被拒绝进入会议时收不到通知。</span><span class="sxs-lookup"><span data-stu-id="26b59-2009">Fix an issue where users in the lobby aren't notified when they're denied from entering the meeting.</span></span>
-   <span data-ttu-id="26b59-2010">修复了以下问题：在通话期间，自动增益控制的增加不受控。</span><span class="sxs-lookup"><span data-stu-id="26b59-2010">Fix an issue where automatic gain control increases uncontrollably during calls.</span></span>
-   <span data-ttu-id="26b59-2011">修复了以下问题：如果会议室资源邮箱已添加到会议邀请，用户无法在“会议选项”中选择演示者。</span><span class="sxs-lookup"><span data-stu-id="26b59-2011">Fix an issue where users are unable to select a presenter in Meeting Options when a conference room resource mailbox is added to a meeting invite.</span></span>
-   <span data-ttu-id="26b59-2012">修复了以下问题：如果 AllowlPVideo 设置为 False，桌面共享按钮在对等视频呼叫期间灰显。</span><span class="sxs-lookup"><span data-stu-id="26b59-2012">Fix an issue where the desktop sharing button is dimmed during a peer-to-peer video call if AllowlPVideo is set to False.</span></span>
-   <span data-ttu-id="26b59-2013">修复了以下问题：将“会议选项”设置更改为对使用“禁用 IM”创建的现有会议启用 IM 后，IM 仍处于禁用状态。</span><span class="sxs-lookup"><span data-stu-id="26b59-2013">Fix an issue where IM stays disabled after changing the Meeting Option setting to Enable IM for existing meetings created with Disable IM.</span></span>
-   <span data-ttu-id="26b59-2014">修复了以下问题：在聊天窗口中将鼠标悬停在“插入链接”按钮之上时，工具提示不显示，并且在选择此按钮后看不到辅助功能名称。</span><span class="sxs-lookup"><span data-stu-id="26b59-2014">Fix an issue where the tooltip isn't shown when hovering over the "Insert Link" button in the chat window, and there isn't an accessibility name when the button is selected.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="26b59-2015">Visio：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2015">Visio: Feature updates</span></span>
-   <span data-ttu-id="26b59-p354">**内置数据库模型图：** 使用新增的数据库模型图模板，可以将数据库准确建模为 Visio 图。不需要加载项。</span><span class="sxs-lookup"><span data-stu-id="26b59-p354">**Built-in database model diagrams:** Use the new Database Model Diagram template to accurately model your database as a Visio diagram. No add-in required.</span></span>
-   <span data-ttu-id="26b59-2018">**更多适用于业务图表的模具：** 使用新式形状，通过维恩图比较和对比数据，或绘制循环图、矩阵图或棱锥图来帮助传达信息。</span><span class="sxs-lookup"><span data-stu-id="26b59-2018">**More stencils for business diagrams:** Using modern shapes, compare and contrast data with a Venn diagram, or draw Cycle, Matrix, or Pyramid diagrams to help tell your story.</span></span>
-   <span data-ttu-id="26b59-p355">**创建网站的线框图表：** 快速创建网站的线框图表，其中包含界面、导航及其协作方式。 [了解更多](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="26b59-p355">**Create a wireframe diagram for a website:** Quickly create a wireframe diagram of a website including interface, navigation, and how they work together. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="26b59-p356">**创建移动应用程序的线框：** 使用模板创建移动应用程序的线框。[了解详细信息](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="26b59-p356">**Create a wireframe of your mobile application:** Use a template to create a wireframe of your mobile application. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="26b59-p357">**将数据图形应用到数据可视化工具图表：** 通过自动将形状数据应用为数据图形，从而在创建数据可视化工具图表时节省时间。 [了解更多](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span><span class="sxs-lookup"><span data-stu-id="26b59-p357">**Apply data graphics to Data Visualizer diagrams:** Save time when you create a Data Visualizer diagram by automatically applying shape data as data graphics. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span></span>
-   <span data-ttu-id="26b59-p358">**协作绘图：** 通过在 OneDrive for Business 或 SharePoint Online 上共享绘图，可以与人协作绘图。可以查看谁正在处理绘图，也可以添加注释和查看文件活动。 [了解更多](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span><span class="sxs-lookup"><span data-stu-id="26b59-p358">**Collaborate on drawings:** Work with others by sharing your drawings on OneDrive for Business or SharePoint Online. You can see who is working on the drawing, add comments, and see file activity. [Learn more](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span></span>
-   <span data-ttu-id="26b59-p359">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="26b59-p359">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="26b59-2031">Word：功能更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2031">Word: Feature updates</span></span>
-   <span data-ttu-id="26b59-2032">**将 SVG 图标转换为形状：** 将所有 SVG 图片和图标都转换为 Office 形状，这样就可以更改它们的颜色、尺寸或纹理。</span><span class="sxs-lookup"><span data-stu-id="26b59-2032">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="26b59-p360">**字符计数：** 在输入过程中，可以在状态栏上看到字符计数。可以通过“自定义状态栏”菜单启用此功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-p360">**Character count:** Display the character count on the status bar as you type. You can enable this from the Customize Status Bar menu.</span></span>
-   <span data-ttu-id="26b59-2035">**快速访问网站和组：** 使用“文件”菜单处理常用网站和组中存储的文档。</span><span class="sxs-lookup"><span data-stu-id="26b59-2035">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="26b59-p361">**Microsoft Translator：** 在 Word 中直接使用 Microsoft Translator 将字词、短语或整篇文档翻译成其他语言。[了解详细信息](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span><span class="sxs-lookup"><span data-stu-id="26b59-p361">**Microsoft Translator:** Translate words, phrases, or the whole document into another language using Microsoft Translator, right in Word. [Learn more](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span></span>
-   <span data-ttu-id="26b59-p362">**数字铅笔：** 使用我们新的铅笔纹理记录或勾画创意灵感。只需倾斜支持的数字铅笔即可绘制底纹。</span><span class="sxs-lookup"><span data-stu-id="26b59-p362">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="26b59-p363">**LinkedIn 功能设置：** 转到“文件”\>“选项”\>“常规”，以控制是否在 Office 应用程序中显示 LinkedIn 功能。[了解详细信息](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="26b59-p363">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="26b59-p364">**SharePoint 属性面板：** 在文档中显示和编辑 SharePoint 文档库列值。借助“视图”选项卡上的功能区按钮，可以轻松地访问面板，并且 SharePoint 管理员能够使用文档库设置自动打开属性面板。</span><span class="sxs-lookup"><span data-stu-id="26b59-p364">**SharePoint property panel:** Display and edit SharePoint document library column values from within a document. A ribbon button on the View tab provides easy access to the panel and SharePoint admins can use a document library setting to automatically open the property panel.</span></span>
-   <span data-ttu-id="26b59-p365">**3D 模型：** 使用 3D 增强文档的视觉效果和创意效果。轻松插入 3D 模型，然后可以在 360 度的范围内旋转它。 [了解更多](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="26b59-p365">**3D models:** Use 3D to increase the visual and creative impact of your documents.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="26b59-2047">**新墨迹效果：** 使用金属笔和墨迹效果（例如彩虹、星系、岩浆、海洋、金色、银色等）以独特的风格表达自己的想法。</span><span class="sxs-lookup"><span data-stu-id="26b59-2047">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="26b59-p366">**共享文件 UI：** 对于 OneDrive for Business 或 SharePoint 文件，单击功能区右上角的“共享”按钮或依次转到“文件”\>“共享”会启动已简化和改进的“共享”对话框。对于新文件或本地保存的文件，UI 可方便用户将文件轻松上传到 OneDrive，从而开始协作。</span><span class="sxs-lookup"><span data-stu-id="26b59-p366">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="26b59-p367">**阻止危险扩展：** 默认阻止激活被视为高风险且作为 OLE 包对象嵌入的扩展。例如，.exe、.vbs 和 .js。[了解更多](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="26b59-p367">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="26b59-p368">**使用学习工具进行编辑：** 学习工具现适用于 Word 的 Web 布局。编辑时，可以调整文字间距，并显示音节。在任意视图中，大声朗读文档时，每个单词都会突出显示。 [了解更多](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="26b59-p368">**Edit using Learning Tools:** Learning Tools is now available in Word's Web Layout. Adjust your text spacing and show syllables while you edit. In any view, see each word highlighted as the document is read aloud. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
-   <span data-ttu-id="26b59-2057">**LaTeX 语法：** 使用 LaTeX 语法创建和编辑数学公式。</span><span class="sxs-lookup"><span data-stu-id="26b59-2057">**LaTeX syntax:** Create and edit math equations using LaTeX syntax.</span></span>
-   <span data-ttu-id="26b59-p369">**实用的语音提示改进了辅助功能：** 打开音频提示后，可指导用户完成工作。可以在“文件”\>“选项”\>“辅助功能”中找到此功能。不需要加载项。 [了解更多](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="26b59-p369">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="26b59-2062">**按帐户组织的文件位置：** 打开或保存文件时，位置列表是按与位置关联的帐户进行组织。</span><span class="sxs-lookup"><span data-stu-id="26b59-2062">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="26b59-p370">**触笔自定义：** 选择一组自己的触笔和荧光笔进行墨迹书写。自定义组适用于所有 Windows 电脑。</span><span class="sxs-lookup"><span data-stu-id="26b59-p370">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="26b59-p371">**通过“编辑器”窗格增强了书写帮助：** “编辑器”窗格可用于提供高级拼写、语法和写作风格建议。对辅助技术的支持已经过改进，可以访问此窗格。</span><span class="sxs-lookup"><span data-stu-id="26b59-p371">**Enhanced writing assistance with Editor pane:** Use the Editor pane for advanced spelling, grammar and writing style recommendations. It’s built to be accessible with improved support for assistive technologies.</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="26b59-2067">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2067">Word: Security updates</span></span>
-   <span data-ttu-id="26b59-2068">[CVE-2018-0792](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2068">[CVE-2018-0792](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2069">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2069">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2070">[CVE-2018-0794](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2070">[CVE-2018-0794](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2071">[CVE-2018-0798](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2071">[CVE-2018-0798](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2072">[CVE-2018-0801](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2072">[CVE-2018-0801](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2073">[CVE-2018-0802](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2073">[CVE-2018-0802](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2074">[CVE-2018-0804](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2074">[CVE-2018-0804](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2075">[CVE-2018-0805](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2075">[CVE-2018-0805](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2076">[CVE-2018-0806](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2076">[CVE-2018-0806](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2077">[CVE-2018-0807](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2077">[CVE-2018-0807](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2078">[CVE-2018-0812](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2078">[CVE-2018-0812](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2079">[CVE-2018-0919](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2079">[CVE-2018-0919](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-2080">[公告 170020](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV170020)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2080">[Advisory 170020](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV170020): Microsoft Office Defense in Depth Update</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="26b59-2081">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2081">Word: Non-security updates</span></span>
-   <span data-ttu-id="26b59-2082">修复了以下问题：如果用户尝试对 OneDrive for Business 上的现有文档执行“另存为”操作，然后又取消保存或尝试合并现有更改，Word 发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-2082">Fix an issue where Word crashes when a user tries to do a Save As to an existing document on OneDrive for Business and then cancels the save or tries to merge existing changes.</span></span>
-   <span data-ttu-id="26b59-2083">修复了以下问题：运行“邮件合并”向导时，无法筛选包含 null（空）值的数据源字段。</span><span class="sxs-lookup"><span data-stu-id="26b59-2083">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>
-   <span data-ttu-id="26b59-p372">修复了以下问题：保存支持同步的文件时，Office 无法对磁盘执行写入操作，但 Office 仍继续将文件上传到 OneDrive。修复此问题后，用户现在会看到错误消息，且上传不会继续执行。</span><span class="sxs-lookup"><span data-stu-id="26b59-p372">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="26b59-2086">修复了以下问题：无法撤消对文档的 IRM 保护。</span><span class="sxs-lookup"><span data-stu-id="26b59-2086">Fix an issue where removing IRM protection on a document doesn’t remove the protection.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-2087">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2087">Office suite: Security updates</span></span>
-   <span data-ttu-id="26b59-2088">[CVE-2017-11882](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2088">[CVE-2017-11882](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2017-11882): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2089">[CVE-2018-0795](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2089">[CVE-2018-0795](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2090">[CVE-2018-0851](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2090">[CVE-2018-0851](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2091">[CVE-2018-0853](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2091">[CVE-2018-0853](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="26b59-2092">[公告 180003](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180003)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2092">[Advisory 180003](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-2093">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2093">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="26b59-2094">修复以下问题：在打开应用程序时，用户可能会看到关于以安全模式启动而应用程序无法打开的消息。</span><span class="sxs-lookup"><span data-stu-id="26b59-2094">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
-   <span data-ttu-id="26b59-2095">启用 Office COM 对象时，“文件 \> 帐户 \> 更新选项”中的“立即更新”选项处于隐藏状态，以便 Configuration Manager 能够管理 Office 365 客户端更新。</span><span class="sxs-lookup"><span data-stu-id="26b59-2095">The Update Now option is hidden from File \> Account \> Update Options when an Office COM object is enabled so that Office 365 client updates are managed by Configuration Manager.</span></span>
-   <span data-ttu-id="26b59-2096">修复了以下问题：当用户尝试使用“激活 Office”对话框激活 Office 时，Office 应用程序发生故障。</span><span class="sxs-lookup"><span data-stu-id="26b59-2096">Fix an issue where the Office app crashes when the user tries to activate Office using the Activate Office dialog box.</span></span>
-   <span data-ttu-id="26b59-2097">修复了以下问题：在动态 DPI 环境下 Office 加载项存在的缩放问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-2097">Fix an issue with zooming and scaling in Office Add-ins under dynamic DPI environment.</span></span>
-   <span data-ttu-id="26b59-2098">修复了以下问题：即使当前安装了 Office 365 专业增强版，Office 配置服务提供程序 (CSP) 的 CurrentStatus 节点也会返回空字符串。</span><span class="sxs-lookup"><span data-stu-id="26b59-2098">Fix an issue where the CurrentStatus node of the Office configuration service provider (CSP) returns an empty string even if Office 365 ProPlus is currently installed.</span></span>
-   <span data-ttu-id="26b59-2099">修复了导致 .box 文件格式更改的问题，这些更改会影响安装在同一台计算机上的旧版 Office 的功能，因为 .box 文件在同一台计算机上的所有 Office 应用版本之间共享。</span><span class="sxs-lookup"><span data-stu-id="26b59-2099">Fix an issue that causes .box file format changes, which impacts functionality of older versions of Office installed on the same computer, because .box files are shared across all versions of an Office app on the same computer.</span></span>



## <a name="version-1708-february-13"></a><span data-ttu-id="26b59-2100">版本 1708：2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="26b59-2100">Version 1708: February 13</span></span>
<span data-ttu-id="26b59-2101">*版本 1708（内部版本 8431.2215）*</span><span class="sxs-lookup"><span data-stu-id="26b59-2101">*Version 1708 (Build 8431.2215)*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="26b59-2102">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2102">Access: Non-security updates</span></span>
-   <span data-ttu-id="26b59-2103">修复了以下问题：在使用多项目窗体时，调整鼠标滚轮的位置或滚动条缩略图不更改窗体中显示的项目。</span><span class="sxs-lookup"><span data-stu-id="26b59-2103">Fix an issue where, when using a multiple items form, adjusting the position of the mouse wheel or the scrollbar thumb doesn't change the items that are displayed in the form.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-2104">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2104">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-2105">[CVE-2018-0841](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2105">[CVE-2018-0841](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-2106">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2106">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-2107">[CVE-2018-0850](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 特权提升漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2107">[CVE-2018-0850](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="26b59-2108">[CVE-2018-0852](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2108">[CVE-2018-0852](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-2109">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2109">Office suite: Security updates</span></span>
-   <span data-ttu-id="26b59-2110">[CVE-2018-0851](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2110">[CVE-2018-0851](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2111">[CVE-2018-0853](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 信息泄漏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2111">[CVE-2018-0853](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1708-january-9"></a><span data-ttu-id="26b59-2112">版本 1708：1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="26b59-2112">Version 1708: January 9</span></span>
<span data-ttu-id="26b59-2113">*版本 1708（内部版本 8431.2153）*</span><span class="sxs-lookup"><span data-stu-id="26b59-2113">*Version 1708 (Build 8431.2153)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="26b59-2114">Excel：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2114">Excel: Security updates</span></span>
-   <span data-ttu-id="26b59-2115">[CVE-2018-0796](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2115">[CVE-2018-0796](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2116">[公告 170021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV170021)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2116">[Advisory 170021](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="26b59-2117">Excel：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2117">Excel: Non-security updates</span></span>
-   <span data-ttu-id="26b59-2118">修复了在编程创建数据透视表后，编程刷新导致 Excel 崩溃的问题。</span><span class="sxs-lookup"><span data-stu-id="26b59-2118">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="26b59-2119">Outlook：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2119">Outlook: Security updates</span></span>
-   <span data-ttu-id="26b59-2120">[CVE-2018-0791](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2120">[CVE-2018-0791](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2121">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2121">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="26b59-2122">Word：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2122">Word: Security updates</span></span>
-   <span data-ttu-id="26b59-2123">[CVE-2018-0792](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2123">[CVE-2018-0792](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2124">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2124">[CVE-2018-0793](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2125">[CVE-2018-0794](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2125">[CVE-2018-0794](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2126">[CVE-2018-0798](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2126">[CVE-2018-0798](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2127">[CVE-2018-0801](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 远程执行代码漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2127">[CVE-2018-0801](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2128">[CVE-2018-0802](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2128">[CVE-2018-0802](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="26b59-2129">[CVE-2018-0804](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2129">[CVE-2018-0804](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2130">[CVE-2018-0805](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2130">[CVE-2018-0805](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2131">[CVE-2018-0806](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2131">[CVE-2018-0806](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2132">[CVE-2018-0807](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2132">[CVE-2018-0807](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2133">[CVE-2018-0812](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 内存损坏漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2133">[CVE-2018-0812](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="26b59-2134">Office 套件：安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2134">Office suite: Security updates</span></span>
-   <span data-ttu-id="26b59-2135">[CVE-2018-0795](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 远程代码执行漏洞</span><span class="sxs-lookup"><span data-stu-id="26b59-2135">[CVE-2018-0795](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="26b59-2136">[公告 180003](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180003)：Microsoft Office 深度防御更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2136">[Advisory 180003](https://portal.msrc.microsoft.com/zh-CN/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="26b59-2137">Office 套件：非安全更新</span><span class="sxs-lookup"><span data-stu-id="26b59-2137">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="26b59-2138">针对 Office 365 德国计划，为身份与本地 Active Directory 联合的域用户添加了单一登录 (SSO) 的支持。</span><span class="sxs-lookup"><span data-stu-id="26b59-2138">Add support for single sign-on (SSO) for domain users for Office 365 Germany plans where the identity is federated with an on-premises Active Directory.</span></span>
-   <span data-ttu-id="26b59-2139">添加了防止未成年人获取和激活来自 Office 应用商店的 Office 外接程序的功能。</span><span class="sxs-lookup"><span data-stu-id="26b59-2139">Add functionality to prevent minors from acquiring and activating Office Add-ins that come from the Office Store.</span></span>


> [!NOTE]
> <span data-ttu-id="26b59-2140">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="26b59-2140">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
