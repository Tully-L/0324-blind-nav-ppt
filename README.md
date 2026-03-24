# 视障辅助导航系统 - 毕业设计答辩 PPT (原生 HTML 版)

[![Built with HTML5](https://img.shields.io/badge/Built%20with-HTML5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![Built with CSS3](https://img.shields.io/badge/Built%20with-CSS3-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/CSS3)
[![No Framework](https://img.shields.io/badge/Framework-None-green.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

这是一个专门为“视障辅助导航系统”毕业设计答辩制作的**原生 HTML/CSS 幻灯片**。它摆脱了传统 PowerPoint 的束缚，采用现代 Web 技术，旨在为工科答辩提供硬核、极客风格的演示体验。

## 🌟 项目亮点 (Key Features)

- **原生技术驱动**：完全使用原生 HTML5 和 CSS3 编写，无第三方框架（如 Reveal.js）依赖，加载速度极快，具有极佳的跨平台性。
- **深度内容重构**：深入解析仓库代码，涵盖了 STM32F103 主控、SIM900A GPRS 链路、Flutter 状态管理以及 MQTT 通信协议等核心技术细节。
- **可视化架构图**：内置多张原生 SVG 绘制的系统架构图、硬件连接图及避障决策流程图，直观展现项目逻辑。
- **现代美学 UI**：采用深色科技感主题（Dracula 配色），结合毛玻璃效果（Glassmorphism）和流体布局，所有内容完美居中显示。
- **交互式演示**：支持键盘（方向键/空格）翻页、鼠标滚轮导航，并配有实时滚动的顶部进度条。

## 📂 项目结构 (Project Structure)

```text
blind-nav-ppt/
├── index.html   # 核心幻灯片代码 (单文件集成 HTML/CSS/JS/SVG)
└── README.md    # 项目说明文档
```

## 🛠️ 技术栈 (Tech Stack)

- **Layout**: CSS Grid (place-items: center), Flexbox
- **Graphics**: Inline SVG (System Topology, HW Pinouts, Flowcharts)
- **Interaction**: Vanilla JavaScript (Scroll-Snap, Event Listeners)
- **Styling**: Backdrop-filter, Linear-gradients, Custom Keyframe Animations

## 🚀 如何运行 (How to Run)

1. 克隆或下载本仓库：
   ```bash
   git clone https://github.com/Tully-L/blind-nav-ppt.git
   ```
2. 在任意现代浏览器中打开 `index.html`。
3. **演示快捷键**：
   - **空格 / 向下方向键**：下一页
   - **向上方向键**：上一页
   - **F 键**：进入/退出全屏

## 🔗 相关项目 (Related Project)

本幻灯片所演示的核心项目源码请访问：[0319-blind-nav-app](https://github.com/Tully-L/0319-blind-nav-app)

---
© 2026 Tully-L. 本项目遵循 MIT 开源协议。
