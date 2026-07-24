这是一个为你的个人主页项目量身定制的 README.md 文件。它既包含了项目的技术亮点，也突出了你作为人工智能专业学生的个人特色。

你可以直接将以下内容保存为项目根目录下的 README.md 文件：

🚀 杨世琪的个人主页 (Personal Portfolio)

一个现代、优雅且完全响应式的单页个人介绍网站。  
基于纯 HTML/CSS/JS 构建，无需框架依赖，开箱即用。

✨ 在线预览

🔗 访问地址: https://rongrong114.github.io

📋 项目简介

这是天津工业大学 2025级人工智能专业本科生 杨世琪 的个人数字名片。网站旨在以视觉化、交互友好的方式展示我的学术背景、技能树、个人成就及社交媒体联系方式。

🎯 核心特性

🎨 现代化 UI 设计: 采用 CSS Variables 定义主题色，支持圆角卡片、渐变光晕、毛玻璃质感阴影等流行视觉元素。
📱 完美响应式: 针对桌面端、平板及移动端进行了深度适配，小屏幕下自动调整布局与字号。
⚡ 零依赖轻量级: 仅使用原生 Web 技术，加载速度极快，无构建步骤。
🎭 微交互动画: 
    头像旋转光环动画
    卡片悬停上浮 + 阴影增强
    页面载入时的交错淡入动画 (fadeInUp)
    心跳 Footer 动画
🔗 智能社交链接: 
    微信/邮箱悬停显示联系方式（桌面端）
    移动端点击切换显示弹窗（解决 hover 不兼容问题）
    Bilibili / GitHub 等平台品牌色悬停效果
♿ 无障碍友好: 语义化标签、合理的 ARIA 属性、平滑滚动锚点导航。

🛠️ 技术栈
类别         技术
结构         HTML5 (语义化标签)

样式         CSS3 (Variables, Grid, Flexbox, Animations)

交互         Vanilla JavaScript

图标         Font Awesome 6.5.1 (CDN)

字体         Inter + Noto Sans SC (Google Fonts CDN)

部署         GitHub Pages

📂 项目结构

├── index.html          # 主页面（包含所有 HTML/CSS/JS）
├── README.md           # 项目说明文档
└── LICENSE             # MIT 许可证

💡 设计说明: 为便于部署和维护，本项目采用单文件架构。所有样式和脚本均内联于 index.html 中，避免多文件请求，确保在 GitHub Pages 上的极致加载性能。

🚀 快速开始

本地运行

bash
克隆仓库
git clone https://github.com/rongrong114/rongrong114.github.io.git

进入目录
cd rongrong114.github.io

直接在浏览器中打开
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux

自定义修改

编辑 index.html 顶部的 CSS 变量即可全局换肤：

css
:root {
    --color-primary: #4f46e5;      /* 主色调 */
    --color-accent: #f59e0b;       /* 强调色 */
    --color-bg: #f1f5f9;           /* 背景色 */
    --radius-lg: 20px;             /* 大圆角半径 */
}

👤 关于作者

姓名   杨世琪

学校   天津工业大学 · 2025级本科生

专业   人工智能

坐标   中国 · 洛阳

技能   C语言 / Python / AI编程 / 视频剪辑 / 离散数学

B站   个人空间 (累计播放 177万+)

GitHub   @rongrong114

🏆 里程碑

✅ 独立完成带华丽UI、动感界面和BGM的贪吃蛇游戏（AI辅助开发实践）
✅ Bilibili 个人剪辑视频总播放量突破 177万
✅ 掌握剪映、Premiere 等专业剪辑工具

📄 开源许可

本项目基于 MIT License 开源，欢迎参考、学习和二次创作。

<div align="center">

用 ❤️ 和代码构建 · © 2026 杨世琪
如果这个项目对你有帮助，请给一个 ⭐ Star 支持一下！

</div>

📝 使用说明

创建文件：在项目根目录新建 README.md，粘贴上述内容
LICENSE 文件：建议同时创建一个 LICENSE 文件（MIT 协议），这样 README 中的许可证徽章才能正常显示
GitHub 自动渲染：推送到 GitHub 后，该 README 会自动显示在仓库首页
徽章更新：Stars 徽章会随仓库星标数自动更新，无需手动修改

💡 额外建议

如果你后续想进一步提升项目专业度，可以考虑：
添加 screenshot.png 网站截图到 README 中（）
将单文件拆分为 style.css + script.js + index.html，更利于长期维护
添加 GitHub Actions 自动部署工作流
