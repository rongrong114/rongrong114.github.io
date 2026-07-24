# 🚀 杨世琪的个人主页 (Personal Portfolio)

> 一个现代、优雅且完全响应式的单页个人介绍网站。  
> 基于纯 HTML/CSS/JS 构建，无需框架依赖，开箱即用。

[![GitHub stars](https://img.shields.io/github/stars/rongrong114/rongrong114.github.io?style=social)](https://github.com/rongrong114/rongrong114.github.io)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

## ✨ 在线预览

🔗 **访问地址**: [https://rongrong114.github.io](https://rongrong114.github.io)

## 📋 项目简介

这是天津工业大学 2025级人工智能专业本科生 **杨世琪** 的个人数字名片。网站旨在以视觉化、交互友好的方式展示我的学术背景、技能树、个人成就及社交媒体联系方式。

### 🎯 核心特性

-   **🎨 现代化 UI 设计**: 采用 CSS Variables 定义主题色，支持圆角卡片、渐变光晕、毛玻璃质感阴影等流行视觉元素。
-   **📱 完美响应式**: 针对桌面端、平板及移动端进行了深度适配，小屏幕下自动调整布局与字号。
-   **⚡ 零依赖轻量级**: 仅使用原生 Web 技术，加载速度极快，无构建步骤。
-   **🎭 微交互动画**: 
    - 头像旋转光环动画
    - 卡片悬停上浮 + 阴影增强
    - 页面载入时的交错淡入动画 (`fadeInUp`)
    - 心跳 Footer 动画
-   **🔗 智能社交链接**: 
    - 微信/邮箱悬停显示联系方式（桌面端）
    - 移动端点击切换显示弹窗（解决 hover 不兼容问题）
    - Bilibili / GitHub 等平台品牌色悬停效果
-   **♿ 无障碍友好**: 语义化标签、合理的 ARIA 属性、平滑滚动锚点导航。

## 🛠️ 技术栈

| 类别       | 技术                                      |
| ---------- | ----------------------------------------- |
| 结构       | HTML5 (语义化标签)                         |
| 样式       | CSS3 (Variables, Grid, Flexbox, Animations) |
| 交互       | Vanilla JavaScript                        |
| 图标       | Font Awesome 6.5.1 (CDN)                  |
| 字体       | Inter + Noto Sans SC (Google Fonts CDN)   |
| 部署       | GitHub Pages                              |

## 📂 项目结构├── index.html # 主页面（包含所有 HTML/CSS/JS）
├── README.md # 项目说明文档
└── LICENSE # MIT 许可证

> 💡 **设计说明**: 为便于部署和维护，本项目采用单文件架构。所有样式和脚本均内联于 `index.html` 中，避免多文件请求，确保在 GitHub Pages 上的极致加载性能。

## 🚀 快速开始

### 本地运行

```bash
# 克隆仓库
git clone https://github.com/rongrong114/rongrong114.github.io.git

# 进入目录
cd rongrong114.github.io

# 直接在浏览器中打开
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
