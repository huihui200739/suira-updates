# 当前产品界面 · 0.2.40

本轮更新取色预览、任务按钮与最近内容入口的展示图。最近内容默认收在顶栏，点击后展开，键盘区不再受卡片挤压。图片来自当前源码启动的真实 Electron 页面，使用独立的临时资料、虚构文档、日程与剪贴板，不读取用户正文或剪贴板，不注册系统快捷键。

| 页面 | 截图 |
| --- | --- |
| 随手面板 | [实时玻璃与 38 键](panel.png) |
| 组合动作 | [编辑并绑定多个步骤](recipes.png) |
| 取色器 | [放大镜显示 HEX 与 RGB](color-picker.png) |
| 最近内容与划词 | [普通面板](selection-panel.png) · [全屏面板](selection-fullscreen.png) |
| 全屏键位与菜单 | [同一套玻璃控件](keyboard-menu.png) |
| 应用启动台 | [本机应用搜索与原生图标](apps.png) |
| 处理轨迹 | [内容详情中的步骤与失败恢复](trace.png) |
| 文字工具 | [翻译与文本转换合并窗口](text-tools.png) |
| 任务匣 | [任务索引与内容整理](workbench.png) |
| Markdown | [文档编辑与分栏预览](markdown.png) |
| 日历 | [月视图、农历与重要日期](calendar.png) |
| 速记 | [实时背景玻璃](notes.png) |
| 工具箱 | [工具图标与统一控件](toolbox.png) |
| 剪贴板 | [筛选、预览与复制粘贴](clipboard.png) |

面板和速记图由 Windows 原生合成器与受控背景窗口一起采集。受控背景只用于演示及验证，不包含在应用中；实际使用会模糊窗口后方的本机真实内容。其余图片捕获 Electron 页面，展示排版、图标和操作，不包含桌面合成层。

玻璃在减少透明度、高对比度或不支持原生合成的系统上使用稳定底色。应用列表的名称与图标来自 Windows 开始菜单；文档、日程和文字均为虚构演示数据。

设计审视参考 Damir Sokolovsky 的 [unslop](https://github.com/heydamir/unslop)（CC BY 4.0）；玻璃分层参考 [wave2234/liquid-glass-recipes](https://github.com/wave2234/liquid-glass-recipes)（MIT）。

文字工具的展示使用固定中英文样例与测试翻译响应；实际翻译使用用户自行配置的服务。

最近内容与划词图使用固定英文与隔离剪贴板／前台窗口模拟，捕获 Electron 页面，不包含桌面合成层；实机验收范围见 selection-manual-0.2.38.json。
