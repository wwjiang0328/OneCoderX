# OneCoderX

one coder's life

## DropSort Pro (智能文件归类工具)

这是 DropSort Pro 的产品展示页面，一个基于 Rust 构建的下一代桌面文件整理工具。

### 功能特性

1. **拖拽交互演示**
   - 鼠标悬停时显示"释放鼠标，立即整理!"激活状态
   - 鼠标移开后恢复初始状态
   - 浮动文件动画效果，模拟文件飞入场景

2. **视觉效果**
   - 深色主题设计 (#0f172a 背景)
   - 动态浮动背景球体动画 (orb 元素)
   - 毛玻璃效果导航栏 (backdrop-filter: blur)
   - 渐变色 Logo 和按钮
   - 元素淡入上移动画 (IntersectionObserver)

3. **响应式布局**
   - 桌面端：3列网格展示特性卡片
   - 平板端 (≤1024px)：2列网格
   - 手机端 (≤768px)：单列布局
   - 弹性 CTA 按钮组

4. **页面结构**
   - 固定导航栏 (含功能、技术架构链接)
   - Hero 主视觉区域 (Slogan + CTA + 演示区)
   - 核心特性卡片网格 (6个特性)
   - 技术栈展示 (Rust, Tauri v2, Vue 3, Vite)
   - 页脚链接

### 技术栈

- 纯 HTML/CSS/JavaScript (无框架依赖)
- CSS Grid 响应式布局
- CSS 动画 (@keyframes)
- IntersectionObserver API
- CSS 变量实现主题一致性

### 预览

直接在浏览器中打开 `DropSort Pro.html` 即可预览。
