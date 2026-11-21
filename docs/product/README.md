# 产品界面 · 正式版 0.2.56

本轮更新剪贴板、速记和 Markdown 的展示图。图片来自真实 Electron 页面，使用独立的临时资料、虚构文档、日程与剪贴板，不读取用户正文或剪贴板，不注册系统快捷键。

| 页面 | 截图 |
| --- | --- |
| 随手面板 | [实时玻璃与 38 键](panel.png) |
| 组合动作 | [编辑并绑定多个步骤](recipes.png) |
| 取色器 | [微信式绿色十字线、坐标与色值](color-picker.png) |
| 最近内容与划词 | [普通面板](selection-panel.png) · [全屏面板](selection-fullscreen.png) |
| 全屏键位与菜单 | [同一套玻璃控件](keyboard-menu.png) |
| 应用启动台 | [本机应用搜索与原生图标](apps.png) |
| 处理轨迹 | [内容详情中的步骤与失败恢复](trace.png) |
| 文字工具 | [翻译与文本转换合并窗口](text-tools.png) |
| 任务匣 | [任务索引与内容整理](workbench.png) |
| 工作台侧边栏（0.2.44） | [展开导航](sidebar-expanded.png) · [收起为图标栏](sidebar-collapsed.png) |
| Markdown | [三栏文档编辑](markdown.png) |
| 日历 | [月视图、农历与重要日期](calendar.png) |
| 速记 | [白色写作面与圆角外框](notes.png) |
| 工具箱 | [工具图标与统一控件](toolbox.png) |
| 剪贴板 | [浅色](clipboard.png) · [深色](clipboard-dark.png) |

面板图由 Windows 原生合成器与受控背景窗口一起采集。受控背景只用于演示及验证，不包含在应用中；实际使用会模糊窗口后方的本机真实内容。速记保留白色写作面，圆角外沿透出透明窗口底色。其余图片捕获 Electron 页面，展示排版、图标和操作。剪贴板示例展示统一玻璃背景、置顶入口、卡片大小和链接预览。

玻璃在减少透明度、高对比度或不支持原生合成的系统上使用稳定底色。应用列表的名称与图标来自 Windows 开始菜单；文档、日程和文字均为虚构演示数据。

设计审视参考 Damir Sokolovsky 的 [unslop](https://github.com/heydamir/unslop)（CC BY 4.0）；玻璃分层参考 [wave2234/liquid-glass-recipes](https://github.com/wave2234/liquid-glass-recipes)（MIT）。

文字工具的展示使用固定中英文样例与测试翻译响应；实际翻译使用用户自行配置的服务。

最近内容与划词图使用固定英文与隔离剪贴板／前台窗口模拟，捕获 Electron 页面，不包含桌面合成层。
