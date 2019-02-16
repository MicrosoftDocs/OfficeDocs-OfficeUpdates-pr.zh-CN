---
<span data-ttu-id="5661a-101">标题: "Office 预览体验成员体验的发行说明" ms. author: andrewmo author: mikho 管理器: andrewmo 毫秒。日期: 2/15/2019) 受众: Win32 Fast ms. 主题: reference ms. service: o365-专业增强版-使用: 关键毫秒. 集合: RelNotes_ProPlus说明: "通过最新的关键新功能、修补程序或已知问题的最新列表为内部人员提供快速访问群体</span><span class="sxs-lookup"><span data-stu-id="5661a-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 2/15/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="5661a-102">Office 预览体验成员的发行说明</span><span class="sxs-lookup"><span data-stu-id="5661a-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="5661a-p101">本文包含适用于 Word、Excel、PowerPoint、Outlook、Access 和 Project for Windows desktop 的内幕版版本的发行说明。我们将重点介绍有趣的新功能、重要修补程序以及我们想要了解的任何重大问题。请注意, 我们通常会在一段时间内将功能 (甚至有时是修复) 部署到内部人员。这使我们能够在向更广泛的访问群体发布功能前确保一切正常工作。因此, 如果看不到下面所述的内容, 请不要担心您最终会获得它。</span><span class="sxs-lookup"><span data-stu-id="5661a-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-12-2019-version-1902-build-1133020014"></a><span data-ttu-id="5661a-108">12 2019 年2月版本 1902 (内部版本 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="5661a-108">February 12 2019 Version 1902 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="5661a-109">新增功能:</span><span class="sxs-lookup"><span data-stu-id="5661a-109">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5661a-110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5661a-110">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="5661a-111">平滑转换增强-按名称的平滑</span><span class="sxs-lookup"><span data-stu-id="5661a-111">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="5661a-112">指定要进行变形的形状</span><span class="sxs-lookup"><span data-stu-id="5661a-112">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="5661a-113">入门:</span><span class="sxs-lookup"><span data-stu-id="5661a-113">Getting Started:</span></span>

- <span data-ttu-id="5661a-114">若要进行平滑处理以将两个对象作为同一个对象, 用户可以使用选择窗格重命名形状。</span><span class="sxs-lookup"><span data-stu-id="5661a-114">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="5661a-p102">名称必须以 "!!" 开头(两个感叹号) 用于进行变形以将其替换为默认匹配行为, 例如 "!!别名</span><span class="sxs-lookup"><span data-stu-id="5661a-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="5661a-p103">用户可以继续使用不以 "!!" 开头的任何名称重命名形状, 而无需担心它会改变平滑工作方式</span><span class="sxs-lookup"><span data-stu-id="5661a-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="5661a-119">要尝试的方案:</span><span class="sxs-lookup"><span data-stu-id="5661a-119">Scenarios to Try:</span></span>

- <span data-ttu-id="5661a-120">在幻灯片中插入形状, 让我们说出矩形</span><span class="sxs-lookup"><span data-stu-id="5661a-120">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="5661a-121">创建新幻灯片</span><span class="sxs-lookup"><span data-stu-id="5661a-121">Create a new slide</span></span>
- <span data-ttu-id="5661a-122">在第二张幻灯片中插入一个不同的形状, 让我们说出三角形</span><span class="sxs-lookup"><span data-stu-id="5661a-122">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="5661a-123">打开 SelectionPane, 将幻灯片1中的矩形重命名为 "!!形状 ", 然后将幻灯片2中的三角形重命名为"!!shape</span><span class="sxs-lookup"><span data-stu-id="5661a-123">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="5661a-124">在第二张幻灯片上应用变形</span><span class="sxs-lookup"><span data-stu-id="5661a-124">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="5661a-125">平滑转换增强-SmartArt</span><span class="sxs-lookup"><span data-stu-id="5661a-125">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="5661a-126">具有更平滑转换的 SmartArt 变形</span><span class="sxs-lookup"><span data-stu-id="5661a-126">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="5661a-127">入门:</span><span class="sxs-lookup"><span data-stu-id="5661a-127">Getting Started:</span></span>

<span data-ttu-id="5661a-128">使用与 SmartArt 相同的方式进行平滑处理</span><span class="sxs-lookup"><span data-stu-id="5661a-128">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="5661a-129">要尝试的方案:</span><span class="sxs-lookup"><span data-stu-id="5661a-129">Scenarios to Try:</span></span>

- <span data-ttu-id="5661a-130">在幻灯片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="5661a-130">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="5661a-131">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="5661a-131">Duplicate the Slide</span></span>
- <span data-ttu-id="5661a-132">调整大小/更改/移动复制的幻灯片上的 SmartArt</span><span class="sxs-lookup"><span data-stu-id="5661a-132">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="5661a-133">对重复的幻灯片应用变形</span><span class="sxs-lookup"><span data-stu-id="5661a-133">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="5661a-134">平滑转换增强功能-表</span><span class="sxs-lookup"><span data-stu-id="5661a-134">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="5661a-135">具有更平滑转换的表变形</span><span class="sxs-lookup"><span data-stu-id="5661a-135">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="5661a-136">入门:</span><span class="sxs-lookup"><span data-stu-id="5661a-136">Getting Started:</span></span>
<span data-ttu-id="5661a-137">像对待表那样使用平滑处理方式</span><span class="sxs-lookup"><span data-stu-id="5661a-137">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="5661a-138">要尝试的方案:</span><span class="sxs-lookup"><span data-stu-id="5661a-138">Scenarios to Try:</span></span>

- <span data-ttu-id="5661a-139">在幻灯片中插入表格</span><span class="sxs-lookup"><span data-stu-id="5661a-139">Insert a Table in a slide</span></span>
- <span data-ttu-id="5661a-140">复制幻灯片</span><span class="sxs-lookup"><span data-stu-id="5661a-140">Duplicate the slide</span></span>
- <span data-ttu-id="5661a-141">调整大小/更改/移动复制的幻灯片上的表格</span><span class="sxs-lookup"><span data-stu-id="5661a-141">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="5661a-142">对重复的幻灯片应用变形</span><span class="sxs-lookup"><span data-stu-id="5661a-142">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="5661a-143">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher & Visio</span><span class="sxs-lookup"><span data-stu-id="5661a-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="5661a-144">在帐户之间无缝切换</span><span class="sxs-lookup"><span data-stu-id="5661a-144">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="5661a-p104">新帐户管理器将所有工作和个人帐户都显示在一个位置, 并使您可以控制这些帐户之间的切换。此更新体验使您可以清楚地登录的方式, 现在您可以在工作和个人帐户之间进行切换, 而无需首先注销或处理复杂对话框。</span><span class="sxs-lookup"><span data-stu-id="5661a-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>



#### <a name="scenarios-to-try"></a><span data-ttu-id="5661a-147">要尝试的方案:</span><span class="sxs-lookup"><span data-stu-id="5661a-147">Scenarios to Try:</span></span>
- <span data-ttu-id="5661a-148">在帐户之间切换</span><span class="sxs-lookup"><span data-stu-id="5661a-148">Switch between accounts</span></span>
- <span data-ttu-id="5661a-149">添加新帐户 [注意: 你可能需要先转到 "文件" | "帐户 |连接的服务并删除任何连接到工作帐户的个人服务, 反之亦然]</span><span class="sxs-lookup"><span data-stu-id="5661a-149">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="5661a-150">从帐户注销</span><span class="sxs-lookup"><span data-stu-id="5661a-150">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="5661a-151">显著修补程序:</span><span class="sxs-lookup"><span data-stu-id="5661a-151">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="5661a-152">Word</span><span class="sxs-lookup"><span data-stu-id="5661a-152">Word</span></span> 
- <span data-ttu-id="5661a-153">我们修复了有关表 & 图像的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="5661a-153">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="5661a-154">Excel</span><span class="sxs-lookup"><span data-stu-id="5661a-154">Excel</span></span>
- <span data-ttu-id="5661a-155">我们修复了以下问题: 自动筛选搜索字段中的文本是黑色主题中的白色</span><span class="sxs-lookup"><span data-stu-id="5661a-155">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="5661a-156">我们通过新的 Office 加载项修复了一个同意 UI 问题</span><span class="sxs-lookup"><span data-stu-id="5661a-156">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5661a-157">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5661a-157">PowerPoint</span></span>
- <span data-ttu-id="5661a-158">我们修复了在笔记本或平板电脑上呈现适用幻灯片时自动扩展显示的问题。</span><span class="sxs-lookup"><span data-stu-id="5661a-158">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="5661a-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="5661a-159">Outlook</span></span>
- <span data-ttu-id="5661a-160">我们修复了 "发送到 OneNote" 按钮显示的问题</span><span class="sxs-lookup"><span data-stu-id="5661a-160">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="5661a-161">访问</span><span class="sxs-lookup"><span data-stu-id="5661a-161">Access</span></span>
- <span data-ttu-id="5661a-162">各种性能和稳定性修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-162">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="5661a-163">Project</span><span class="sxs-lookup"><span data-stu-id="5661a-163">Project</span></span>
- <span data-ttu-id="5661a-164">各种性能和稳定性修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-164">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1902-build-1133020014"></a><span data-ttu-id="5661a-165">9 2019 年2月版本 1902 (内部版本 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="5661a-165">February 9 2019 Version 1902 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="5661a-166">显著修补程序:</span><span class="sxs-lookup"><span data-stu-id="5661a-166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="5661a-167">Word</span><span class="sxs-lookup"><span data-stu-id="5661a-167">Word</span></span> 
- <span data-ttu-id="5661a-168">我们修复了以下问题: 某些自定义样式无法应用于 word online</span><span class="sxs-lookup"><span data-stu-id="5661a-168">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="5661a-169">我们在 Word 中解决了与富对象相关的上下文预览问题</span><span class="sxs-lookup"><span data-stu-id="5661a-169">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="5661a-170">我们修复了以下问题: 粘贴列表会导致 Word 崩溃</span><span class="sxs-lookup"><span data-stu-id="5661a-170">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="5661a-171">Excel</span><span class="sxs-lookup"><span data-stu-id="5661a-171">Excel</span></span>
- <span data-ttu-id="5661a-172">我们修复了以下问题: 当没有货币符号时, 数字格式后面的附加空格将不再显示</span><span class="sxs-lookup"><span data-stu-id="5661a-172">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="5661a-173">我们在自动检测股票时解决了问题</span><span class="sxs-lookup"><span data-stu-id="5661a-173">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5661a-174">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5661a-174">PowerPoint</span></span>
- <span data-ttu-id="5661a-175">各种性能和稳定性修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-175">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="5661a-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="5661a-176">Outlook</span></span>
- <span data-ttu-id="5661a-177">各种性能和稳定性修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-177">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="5661a-178">访问</span><span class="sxs-lookup"><span data-stu-id="5661a-178">Access</span></span>
- <span data-ttu-id="5661a-179">各种性能和稳定性修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-179">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="5661a-180">Project</span><span class="sxs-lookup"><span data-stu-id="5661a-180">Project</span></span>
- <span data-ttu-id="5661a-181">各种性能和稳定性修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-181">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="5661a-182">2019年1月30日版本 1902 (内部版本 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="5661a-182">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="5661a-183">显著修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-183">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="5661a-184">Word</span><span class="sxs-lookup"><span data-stu-id="5661a-184">Word</span></span> 
- <span data-ttu-id="5661a-185">我们解决了在嵌入的 Excel 表中调整单元格的大小的问题</span><span class="sxs-lookup"><span data-stu-id="5661a-185">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="5661a-186">我们解决了在绘图画布中复制/粘贴形状时遇到的问题</span><span class="sxs-lookup"><span data-stu-id="5661a-186">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="5661a-187">Excel</span><span class="sxs-lookup"><span data-stu-id="5661a-187">Excel</span></span>
- <span data-ttu-id="5661a-188">我们解决了从 Excel Web app 打开文件时遇到的问题</span><span class="sxs-lookup"><span data-stu-id="5661a-188">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="5661a-189">我们修复了将 CSV 文件另存为的问题。由于文件名大小, .xlsx 失败</span><span class="sxs-lookup"><span data-stu-id="5661a-189">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="5661a-190">修复了上下文菜单, 以显示上下文菜单选项</span><span class="sxs-lookup"><span data-stu-id="5661a-190">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5661a-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5661a-191">PowerPoint</span></span>
- <span data-ttu-id="5661a-192">我们修复了用户无法使用键盘快捷方式 ctrl + alt + 7/ctrl + alt + 8 以输入方括号的已发出的情况</span><span class="sxs-lookup"><span data-stu-id="5661a-192">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="5661a-193">我们修复了以下问题: 将本地视频插入 PPT 会减少 "C" 驱动器磁盘空间</span><span class="sxs-lookup"><span data-stu-id="5661a-193">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="5661a-194">我们修复了 "发布到 Microsoft Stream" 按钮, 但未向某些用户显示</span><span class="sxs-lookup"><span data-stu-id="5661a-194">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="5661a-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="5661a-195">Outlook</span></span>
- <span data-ttu-id="5661a-196">我们修复了以下问题: "日历" 中的任务视图未正确显示任务主题</span><span class="sxs-lookup"><span data-stu-id="5661a-196">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="5661a-197">访问</span><span class="sxs-lookup"><span data-stu-id="5661a-197">Access</span></span>
- <span data-ttu-id="5661a-198">我们解决了图表的扩展问题</span><span class="sxs-lookup"><span data-stu-id="5661a-198">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="5661a-199">Project</span><span class="sxs-lookup"><span data-stu-id="5661a-199">Project</span></span>
- <span data-ttu-id="5661a-200">各种性能和稳定性修补程序</span><span class="sxs-lookup"><span data-stu-id="5661a-200">Various performance and stability fixes</span></span>
