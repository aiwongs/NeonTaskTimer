NeonTaskTimer 🚀

NeonTaskTimer 是一款炫酷的任务定时器，采用 HTML、CSS 和 JavaScript 打造。它融合了科幻风格的霓虹星际背景和强大的任务管理功能，让用户可以轻松定时和播放音频任务。无论是开发者、爱好者，还是追求视觉震撼的用户，这款工具都将为你带来非凡体验！🌌
English README | 中文 README

##✨ 功能亮点

任务定时：
支持添加最多 10 个任务，可自定义任务名称和 MP3 文件。
通过精确的日期时间输入（YYYY-MM-DD HH:mm:ss）定时任务。
实时显示任务倒计时和状态更新。

音频播放：
内置预定义任务（如“烧水任务”、“炖煮任务”）或支持自定义 MP3 上传。
提供播放、暂停、继续和停止功能，操作流畅。
音频自动循环播放，确保持续提醒。

视觉特效：
星际背景：动态星云涡流、发光光晕和扩展隧道线框。
场景元素：随机漂浮的线框形状（圆形、方形、三角形、线条）。
粒子与流星：闪烁的小粒子、带光尾的流星和 UFO 光点。
任务动画：任务激活时，卡片呈现霓虹爆闪和呼吸光晕效果。

响应式设计：
自适应多种屏幕尺寸，布局流畅。
任务列表支持平滑滚动，配备自定义滚动条。

人性化界面：
支持任务卡最小化，节省空间。
实时显示系统时间。
交互式日期时间选择器，简化任务定时。

##🎥 演示
感受霓虹光晕与星际动画的震撼效果！
![NeonTaskTimer 截图](https://github.com/aiwongs/NeonTaskTimer/blob/main/pics/20250507202447.png)

##🛠️ 安装指南

按照以下步骤在本地运行 NeonTaskTimer：
前提条件
现代浏览器（Chrome、Firefox、Edge 或 Safari）。
本地 HTTP 服务器（例如 Python 的 http.server 或 Node.js 的 live-server）。
可选：用于自定义任务的 MP3 文件。

安装步骤

克隆仓库：
git clone https://github.com/aiwongs/NeonTaskTimer.git
cd NeonTaskTimer

准备 MP3 文件（可选）：
将 MP3 文件放入项目目录（例如 test.mp3）。
在 index.html 中更新默认音频路径（例如将 music/boiling_water.mp3 替换为 test.mp3改名为boiling_water.mp3），或通过界面上传 MP3。

启动本地服务器：
使用本地服务器避免 CORS 问题：python -m http.server 8000
或者使用 live-server：npm install -g live-server
live-server

访问应用：
打开浏览器，访问 http://localhost:8000

##🚀 使用方法

添加任务：
点击 添加任务 按钮，创建新的任务卡（最多 10 个）。
选择预定义任务（如“烧水任务”）或选择“自定义任务”上传 MP3 文件。

配置任务：
预定义任务会自动加载音频。
自定义任务需点击 加载 MP3 上传音频文件。
为自定义任务输入任务名称（例如“晨间提醒”）。

定时任务：
点击时间输入框，打开日期时间选择器。
设置未来时间（例如 2025-05-07 14:00:00），点击 任务执行。
任务将等待至设定时间，然后播放音频并触发霓虹光效。

控制任务：
暂停/继续：切换暂停或恢复音频播放。
停止：停止音频并重置任务。
关闭：删除任务卡。
最小化：点击任务卡或状态栏以折叠。

欣赏视觉效果：

沉浸于旋转的星云、飞驰的流星和漂浮的 UFO 光点。
观察任务卡在激活时的霓虹爆闪和呼吸动画。

##🤝 贡献指南
我们欢迎社区贡献，共同让 NeonTaskTimer 更出色！以下是参与方式：

Fork 仓库：
在 GitHub 上点击“Fork”按钮，克隆你的 Fork：git clone https://github.com/YOUR_USERNAME/NeonTaskTimer.git

创建分支：
git checkout -b feature/your-feature

提交更改：
添加新功能、修复 Bug 或改进文档。
确保代码风格一致（例如统一缩进、清晰注释）。

测试更改：
在本地运行应用，验证功能。
检查浏览器兼容性（Chrome、Firefox）。

提交 Pull Request：
推送更改：git push origin feature/your-feature

在 GitHub 上创建 PR，详细描述你的更改。

贡献建议

添加新背景动画（例如星空、闪电效果）。
支持更多音频格式（例如 WAV、OGG）。
使用 localStorage 实现任务持久化。
增强日期时间选择器，支持键盘输入。
优化低端设备的性能。

##📜 许可证
本项目采用 MIT 许可证，详情见 LICENSE 文件。

##🌟 致谢

由 aiwongs 用 ❤️ 打造。
灵感源自科幻 UI 设计与星际美学。
纯 HTML、CSS 和 JavaScript 构建，无需任何框架！

点亮一颗星 ⭐ 如果你喜欢这款霓虹风格的任务定时器！有问题或建议？请提交 Issue 或联系我们。
让我们一起将任务定时变得星际非凡！
