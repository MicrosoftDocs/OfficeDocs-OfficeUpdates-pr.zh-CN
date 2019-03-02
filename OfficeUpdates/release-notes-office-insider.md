---
标题: "Office 预览体验成员体验的发行说明" ms. author: andrewmo author: mikho 管理器: andrewmo 毫秒。日期: 3/1/2019) 受众: Win32 Fast ms. 主题: reference ms. service: o365-专业增强版-使用: 关键毫秒. 集合: RelNotes_ProPlus说明: "通过最新的关键新功能、修补程序或已知问题的最新列表为内部人员提供快速访问群体
---

# <a name="release-notes-for-office-insiders"></a>Office 预览体验成员的发行说明

本文包含适用于 Word、Excel、PowerPoint、Outlook、Access 和 Project for Windows desktop 的内幕版版本的发行说明。我们将重点介绍有趣的新功能、重要修补程序以及我们想要了解的任何重大问题。请注意, 我们通常会在一段时间内将功能 (甚至有时是修复) 部署到内部人员。这使我们能够在向更广泛的访问群体发布功能前确保一切正常工作。因此, 如果看不到下面所述的内容, 请不要担心您最终会获得它。  

## <a name="february-25-2019-version-1903-build-1133020014"></a>2019年2月25日版本 1903 (内部版本 11330.20014)


## <a name="notable-fixes"></a>显著修补程序:

### <a name="word"></a>Word 
- 我们修复了在选项中按 "ESC" 时发生的崩溃问题
- 我们修复了复制 & 从 Word 粘贴到 PowerPoint Online 的问题

### <a name="excel"></a>Excel
- 我们修复了以下问题: 在 Excel 中复制单元格时, 在打开受保护的文档和可编辑文档时, 会导致 CPU 使用率较高

### <a name="powerpoint"></a>PowerPoint
- 在 PowerPoint 中使用 @Mentions 时, 我们修复了幻灯片图像大小的问题

### <a name="outlook"></a>Outlook
- 我们修复了以下问题: Outlook 搜索不接受所选的按时间顺序排序
- 我们修复了以下问题: "打开此任务" 工作流功能区按钮对某些电子邮件没有响应
- 我们修复了以下问题: 用户在会议室查找器中选择了可用聊天室后, Outlook 在本地聊天室中未清除。

### <a name="access"></a>访问
- 我们更新了在使用 datasource 确认重新链接表时显示的提示文本
- 我们修复了白色背景为深色主题的已保存的导入/导出对话框
- 我们修复了以下问题: 用户无法将 "是/否" 字段的显示控件属性设置为表设计中的 Textbox

### <a name="project"></a>Project
- 各种性能和稳定性修补程序

</BR></BR>



## <a name="february-12-2019-version-1903-build-1133020014"></a>12 2019 年2月版本 1903 (内部版本 11330.20014)

## <a name="whats-new"></a>新增功能:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>平滑转换增强-按名称的平滑

指定要进行变形的形状

#### <a name="getting-started"></a>入门:

- 若要进行平滑处理以将两个对象作为同一个对象, 用户可以使用选择窗格重命名形状。
- 名称必须以 "!!" 开头(两个感叹号) 用于进行变形以将其替换为默认匹配行为, 例如 "!!别名
- 用户可以继续使用不以 "!!" 开头的任何名称重命名形状, 而无需担心它会改变平滑工作方式

#### <a name="scenarios-to-try"></a>要尝试的方案:

- 在幻灯片中插入形状, 让我们说出矩形
- 创建新幻灯片
- 在第二张幻灯片中插入一个不同的形状, 让我们说出三角形
- 打开 SelectionPane, 将幻灯片1中的矩形重命名为 "!!形状 ", 然后将幻灯片2中的三角形重命名为"!!shape
- 在第二张幻灯片上应用变形

</BR>

### <a name="morph-transition-enhancements---smartart"></a>平滑转换增强-SmartArt

具有更平滑转换的 SmartArt 变形

#### <a name="getting-started"></a>入门:

使用与 SmartArt 相同的方式进行平滑处理

#### <a name="scenarios-to-try"></a>要尝试的方案:

- 在幻灯片中插入 SmartArt
- 复制幻灯片
- 调整大小/更改/移动复制的幻灯片上的 SmartArt
- 对重复的幻灯片应用变形

</BR>

### <a name="morph-transition-enhancements---tables"></a>平滑转换增强功能-表

具有更平滑转换的表变形

#### <a name="getting-started"></a>入门:
像对待表那样使用平滑处理方式

#### <a name="scenarios-to-try"></a>要尝试的方案:

- 在幻灯片中插入表格
- 复制幻灯片
- 调整大小/更改/移动复制的幻灯片上的表格
- 对重复的幻灯片应用变形

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word、Excel、PowerPoint、OneNote、Access、Project、Publisher & Visio

### <a name="seamlessly-switch-between-accounts"></a>在帐户之间无缝切换

新帐户管理器将所有工作和个人帐户都显示在一个位置, 并使您可以控制这些帐户之间的切换。此更新体验使您可以清楚地登录的方式, 现在您可以在工作和个人帐户之间进行切换, 而无需首先注销或处理复杂对话框。


![MeMock](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>要尝试的方案:
- 在帐户之间切换
- 添加新帐户 [注意: 你可能需要先转到 "文件" | "帐户 |连接的服务并删除任何连接到工作帐户的个人服务, 反之亦然]
- 从帐户注销
</BR>

## <a name="notable-fixes"></a>显著修补程序:

### <a name="word"></a>Word 
- 我们修复了有关表 & 图像的上下文预览问题

### <a name="excel"></a>Excel
- 我们修复了以下问题: 自动筛选搜索字段中的文本是黑色主题中的白色
- 我们通过新的 Office 加载项修复了一个同意 UI 问题

### <a name="powerpoint"></a>PowerPoint
- 我们修复了在笔记本或平板电脑上呈现适用幻灯片时自动扩展显示的问题。

### <a name="outlook"></a>Outlook
- 我们修复了 "发送到 OneNote" 按钮显示的问题

### <a name="access"></a>访问
- 各种性能和稳定性修补程序

### <a name="project"></a>Project
- 各种性能和稳定性修补程序


</BR></BR>
## <a name="february-9-2019-version-1903-build-1133020014"></a>9 2019 年2月版本 1903 (内部版本 11330.20014)


## <a name="notable-fixes"></a>显著修补程序:

### <a name="word"></a>Word 
- 我们修复了以下问题: 某些自定义样式无法应用于 word online
- 我们在 Word 中解决了与富对象相关的上下文预览问题
- 我们修复了以下问题: 粘贴列表会导致 Word 崩溃

### <a name="excel"></a>Excel
- 我们修复了以下问题: 当没有货币符号时, 数字格式后面的附加空格将不再显示
- 我们在自动检测股票时解决了问题

### <a name="powerpoint"></a>PowerPoint
- 各种性能和稳定性修补程序

### <a name="outlook"></a>Outlook
- 各种性能和稳定性修补程序

### <a name="access"></a>访问
- 各种性能和稳定性修补程序

### <a name="project"></a>Project
- 各种性能和稳定性修补程序

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a>2019年1月30日版本 1902 (内部版本 11326.20000)


## <a name="notable-fixes"></a>显著修补程序

### <a name="word"></a>Word 
- 我们解决了在嵌入的 Excel 表中调整单元格的大小的问题
- 我们解决了在绘图画布中复制/粘贴形状时遇到的问题

### <a name="excel"></a>Excel
- 我们解决了从 Excel Web app 打开文件时遇到的问题
- 我们修复了将 CSV 文件另存为的问题。由于文件名大小, .xlsx 失败
- 修复了上下文菜单, 以显示上下文菜单选项

### <a name="powerpoint"></a>PowerPoint
- 我们修复了用户无法使用键盘快捷方式 ctrl + alt + 7/ctrl + alt + 8 以输入方括号的已发出的情况
- 我们修复了以下问题: 将本地视频插入 PPT 会减少 "C" 驱动器磁盘空间
- 我们修复了 "发布到 Microsoft Stream" 按钮, 但未向某些用户显示

### <a name="outlook"></a>Outlook
- 我们修复了以下问题: "日历" 中的任务视图未正确显示任务主题

### <a name="access"></a>访问
- 我们解决了图表的扩展问题

### <a name="project"></a>Project
- 各种性能和稳定性修补程序
