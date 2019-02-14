---
title: 有关 2019 年半年频道（定向）发行的发行说明
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 为 IT 专业人士提供有关 2019 年 Office 365 专业增强版半年频道（定向）发行的发行说明
ms.openlocfilehash: d9ace400fb5f3c92d1e0089c851f51109dfc2228
ms.sourcegitcommit: 659d2bbb04f8ccfc7e03a9a23758e3feed9d5075
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/12/2019
ms.locfileid: "29953994"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a><span data-ttu-id="57aef-103">有关 2019 年半年频道（定向）发行的发行说明</span><span class="sxs-lookup"><span data-stu-id="57aef-103">Release notes for Semi-Annual Channel (Targeted) releases in 2019</span></span>

<span data-ttu-id="57aef-104">这些发行说明提供了有关 2019 年 Office 365 专业增强版半年频道（定向）更新中所包含的新功能、安全更新和非安全更新的信息。</span><span class="sxs-lookup"><span data-stu-id="57aef-104">These release notes provide information about new features, security updates, and non-security updates that are included in Semi-Annual Channel (Targeted) updates to Office 365 ProPlus in 2019.</span></span>
 
> [!NOTE]
> - <span data-ttu-id="57aef-105">以下说明还提供了有关 Visio Pro for Office 365 和 Project Online 桌面客户端的新功能、安全更新和非安全更新的信息。</span><span class="sxs-lookup"><span data-stu-id="57aef-105">The following also provides information about new features, security updates, and non-security updates for Visio Pro for Office 365 and Project Online Desktop Client.</span></span>
> - <span data-ttu-id="57aef-106">此信息还适用于 Office 365 商业版，即随附一些 Office 365 计划的 Office 版本（如企业高级版）。</span><span class="sxs-lookup"><span data-stu-id="57aef-106">This information also applies to Office 365 Business, which is the version of Office that comes with some Office 365 plans, such as Business Premium.</span></span>

 
> [!NOTE]
> - <span data-ttu-id="57aef-107">Office 365 专业增强版中每个更新频道的安全更新信息将开始在[安全更新](office365-proplus-security-updates.md)中单独列出。</span><span class="sxs-lookup"><span data-stu-id="57aef-107">The security updates information for each update channel of Office 365 ProPlus will start being listed separately at [Security Updates](office365-proplus-security-updates.md).</span></span>

## <a name="version-1808-february-12"></a><span data-ttu-id="57aef-108">版本 1808：2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="57aef-108">Version 1808: February 12</span></span>
<span data-ttu-id="57aef-109">版本 1808（内部版本 10730.20280）\*\*</span><span class="sxs-lookup"><span data-stu-id="57aef-109">*Version 1808 (Build 10730.20102)*</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="57aef-110">Access：非安全更新</span><span class="sxs-lookup"><span data-stu-id="57aef-110">Access: Non-security updates</span></span> 

- <span data-ttu-id="57aef-111">此更新将对新日本和历的支持添加到 Access。</span><span class="sxs-lookup"><span data-stu-id="57aef-111">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="57aef-112">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="57aef-112">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="57aef-113">解决以下问题：具有引用不再存在的文件夹规则的用户在尝试管理规则时看到错误，以及看到客户端规则运行失败。</span><span class="sxs-lookup"><span data-stu-id="57aef-113">Addresses an issue that caused users with rules that refer to a folder that no longer exist to see an error when trying to manage rules and to see client-side rules fail to run.</span></span>
- <span data-ttu-id="57aef-114">处理以下问题：具有缓存委托邮箱的用户在不可预测的时间间隔遇到频繁挂起。</span><span class="sxs-lookup"><span data-stu-id="57aef-114">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="57aef-115">处理以下问题：由于会议结束时间设置为第二天的午夜，在一些视图中，全天会议似乎超过预期的一天时间。</span><span class="sxs-lookup"><span data-stu-id="57aef-115">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="57aef-116">修复了创建引用日本和历的新约会或会议时的挂起。</span><span class="sxs-lookup"><span data-stu-id="57aef-116">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="57aef-117">Office 套件：非安全更新程序</span><span class="sxs-lookup"><span data-stu-id="57aef-117">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="57aef-118">修复以下问题：使用 [O365 Office 集中式部署](https://docs.microsoft.com/zh-CN/office/dev/add-ins/publish/centralized-deployment)部署的外接程序被冻结且不可用。</span><span class="sxs-lookup"><span data-stu-id="57aef-118">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/zh-CN/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="57aef-119">版本 1808：1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="57aef-119">Version 1808: January 8</span></span>
<span data-ttu-id="57aef-120">*版本 1808（内部版本 10730.20264）*</span><span class="sxs-lookup"><span data-stu-id="57aef-120">*Version 1808 (Build 10730.20264)*</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="57aef-121">Outlook：非安全更新</span><span class="sxs-lookup"><span data-stu-id="57aef-121">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="57aef-122">修复了导致用户遇到日历同步错误的问题。</span><span class="sxs-lookup"><span data-stu-id="57aef-122">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="57aef-123">Word：非安全更新</span><span class="sxs-lookup"><span data-stu-id="57aef-123">Word: Non-security updates</span></span>

- <span data-ttu-id="57aef-124">提高打开性能。</span><span class="sxs-lookup"><span data-stu-id="57aef-124">Improve open performance.</span></span>


> [!NOTE]
> <span data-ttu-id="57aef-125">如果在使用 Office 时遇到问题且需要帮助，建议在 [Microsoft 问答论坛](https://answers.microsoft.com/)或[技术社区](https://techcommunity.microsoft.com/)上发布问题，也可以联系[支持部门](https://support.microsoft.com/contactus)。</span><span class="sxs-lookup"><span data-stu-id="57aef-125">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>