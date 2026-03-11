# DropSort Pro (智能文件归类工具)

![DropSort Pro](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-blueviolet)
![Tech Stack](https://img.shields.io/badge/Stack-Electron%20%2B%20Vue%203%20%2B%20Vite-green)

**拖拽之间，秩序井然。** 下一代桌面文件整理利器，让您的数字工作空间瞬间回归整洁。

---

## 🚀 核心特性

- **⚡ Electron 强力驱动**：成熟的跨平台架构，极致的 UI 交互体验，让文件整理变得赏心悦目。
- **🧠 智能规则引擎**：自动识别图片、视频、音频、文档等多种类型，按预设规则毫秒级归类。
- **📋 剪切板一键整理**：完美解决钉钉、微信等应用截图无法直接拖拽的问题，点击即可识别归类。
- **🛡️ 安全零丢失**：原子化移动操作，智能冲突检测，确保您的珍贵数据万无一失。
- **🎨 原生体验**：完美融入系统设计语言，支持深色模式、系统托盘集成及开机自启。
- **🔄 操作日志与撤销**：详细记录每一次移动，支持一键撤销，随时还原文件状态。

## 🛠️ 技术架构

本项目采用现代化的桌面应用开发栈：

- **Framework**: [Electron 28+](https://www.electronjs.org/) (核心跨平台框架)
- **Frontend**: [Vue 3](https://vuejs.org/) (响应式界面开发)
- **Build Tool**: [Vite 5](https://vitejs.dev/) (极速开发与打包体验)
- **State Management**: [Pinia](https://pinia.vuejs.org/) (持久化配置与日志管理)
- **Styling**: Tailwind-inspired CSS (自适应、毛玻璃效果、动态渐变背景)

## 📖 使用说明

1. **配置路径**：首次启动请前往“设置”界面，为不同类型的文件指定存放目录。
2. **拖拽整理**：将需要整理的文件（支持多选）直接拖入主窗口，程序将自动识别并移动。
3. **处理剪切板**：若遇到无法直接拖拽的截图，点击主界面的“识别并整理剪切板图片”即可。

## 📦 打包与发布

### Windows
```bash
npm run build:win
```

### macOS
```bash
npm run build:mac
```

---

## 🌐 宣传页预览

项目包含一个精心设计的 **[产品展示页](./index.html)**，具备：
- 动态浮动背景球体动画
- 自动识别操作系统并切换下载按钮
- 响应式网格布局（适配手机/平板/桌面）
- 元素淡入上移动画效果

---
© 2026 DropSort Pro - 开启高效办公新时代
