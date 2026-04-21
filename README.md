# Peek Effect Login Page / 偷看效果登录页

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Structure-E34F26?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-Interaction-F7DF1E?logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

<p align="center">
  A polished, interactive login experience built with pure HTML, CSS, and JavaScript.<br/>
  一个使用原生 HTML、CSS 和 JavaScript 构建的高完成度动态登录页。
</p>

<p align="center">
  <strong>A playful and polished animated login experience.</strong><br/>
  <strong>一个兼具趣味性与完成度的动态登录体验。</strong>
</p>

---

## Introduction / 项目简介

**Animated Characters Login Page** is a high-fidelity animated authentication interface that transforms a conventional login screen into a playful and memorable product experience.

**Animated Characters Login Page** 是一个高保真动画登录界面项目，它将传统登录页重新设计为一个更有趣、更有品牌感、也更容易让人记住的交互体验。

The project features expressive geometric characters, real-time mouse tracking, blinking behavior, password visibility reactions, and a clean responsive layout. It is intentionally implemented as a **single self-contained HTML file**, making it easy to run, study, customize, and deploy.

该项目包含几何角色动画、鼠标实时跟随、随机眨眼、密码可见状态联动，以及简洁的响应式布局。整体被刻意设计为 **单文件 HTML 实现**，方便直接运行、学习、二次开发与部署。

---

## Preview / 预览特点

### English

This project is designed to feel more like a modern product landing-login hybrid than a traditional static form. The visual identity is carried by a split-screen layout:

* a vibrant brand section on the left
* an elegant login form on the right
* animated characters reacting to user behavior
* smooth transitions and subtle motion-driven storytelling

### 中文

这个项目并不是一个普通静态表单，而更像是一个结合了品牌展示与登录交互的现代产品界面。整体采用左右分栏设计：

* 左侧是充满品牌感的视觉展示区
* 右侧是简洁克制的登录表单区
* 角色会随着用户行为产生互动反馈
* 通过细腻的动态过渡营造更强的页面生命力

---

## Features / 功能特性

### English

* High-fidelity animated login page
* Real-time mouse-following eye movement
* Random blinking for natural character behavior
* Password visibility interaction with playful “peeking” animation
* Input-focus-driven character response
* Responsive desktop and mobile layout
* Single-file architecture, easy to distribute and integrate
* No build step, no package manager, no framework required

### 中文

* 高还原度动态登录页
* 多个角色支持鼠标实时注视跟随
* 随机眨眼，让角色动作更自然
* 显示密码时触发“偷看”式趣味交互
* 聚焦输入框时角色会做出响应
* 支持桌面端与移动端响应式布局
* 单文件结构，方便传播、集成与演示
* 无需构建、无需依赖、无需框架即可运行

---

## Tech Stack / 技术栈

* HTML5
* CSS3
* Vanilla JavaScript / 原生 JavaScript

> No npm install required.
> No framework setup required.
> 无需安装 npm 依赖，也无需额外框架配置。

---

## Project Structure / 项目结构

```text
.
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

The project is intentionally minimal. All UI, interaction logic, layout rules, and animations live inside `index.html`.
项目结构被刻意保持极简。所有 UI、交互逻辑、布局样式与动画都集中在 `index.html` 中，便于理解和快速迁移。

---

## Getting Started / 快速开始

### 1. Clone the repository / 克隆仓库

```bash
https://github.com/dwkejiPeng/Peek-effect-login-page.git
```

### 2. Enter the project directory / 进入项目目录

```bash
cd Peek-effect-login-page
```

### 3. Open the file directly / 直接打开文件

Open `index.html` in your browser.
直接用浏览器打开 `index.html` 即可运行。

---

## Local Development / 本地开发

You can run the project directly, but using a local server is recommended for a cleaner workflow.
虽然直接双击 HTML 文件即可运行，但开发时更推荐使用本地服务器，以获得更稳定的调试体验。

```bash
python -m http.server 8000
```

Then visit / 然后访问：

```text
http://localhost:8000
```

---

## Interaction Details / 交互细节

* Characters subtly lean toward the cursor / 角色会轻微朝鼠标方向倾斜
* Eye pupils track pointer movement in real time / 眼球会实时追踪鼠标位置
* Purple and black characters blink randomly / 紫色和黑色角色会随机眨眼
* Email field focus triggers character attention changes / 聚焦邮箱输入框时角色会改变观察状态
* Password reveal mode changes the gaze logic and creates a playful “peeking” reaction / 显示密码后，角色视线逻辑会切换并触发“偷看”效果
* Form submission simulates a lightweight authentication flow / 提交表单时会模拟一个轻量级登录流程

---

## Demo Credentials / 演示账号

For the built-in mock login logic / 当前演示使用内置的模拟登录逻辑：

* **Email / 邮箱:** `erik@gmail.com`
* **Password / 密码:** `1234`

> Replace this logic before using the page in a real production environment.
> 如果要用于真实项目，请先替换掉示例登录逻辑。

---

## Customization / 自定义方式

### Brand / 品牌定制

You can replace / 你可以替换：

* `YourBrand`
* footer links / 页脚链接
* heading and form copy / 标题与表单文案
* hero gradient colors / 左侧主视觉渐变配色

### Theme / 主题样式

Update the CSS variables inside `:root` to quickly reskin the page.
修改 `:root` 中的 CSS 变量即可快速完成整体主题换肤。

### Motion / 动画行为

Inside the script, you can adjust / 在脚本中你可以调节：

* blink timing / 眨眼时间间隔
* peek delay / 偷看触发延迟
* body skew strength / 身体倾斜幅度
* face movement range / 面部位移幅度
* eye tracking distance / 眼球跟随距离

---

## Responsive Design / 响应式设计

On desktop, the page uses a split-screen presentation with a large animated visual area. On smaller screens, the left panel is hidden to prioritize clarity and focus.
在桌面端，页面采用左右分栏布局；在平板和手机等小屏设备上，左侧视觉区会被隐藏，以保证表单的清晰度与可用性。

---

## Accessibility / 可访问性

The project already includes semantic inputs, visible focus feedback, explicit labels, and a button-based password toggle.
项目目前已经具备语义化输入框、明显的焦点反馈、清晰的表单标签，以及按钮式密码显隐切换。

Recommended next improvements / 后续建议增强：

* `prefers-reduced-motion` support
* better keyboard flow
* ARIA refinement
* accessible validation announcements

---

## Roadmap / 后续计划

* React version / React 版本
* Next.js version / Next.js 版本
* Tailwind CSS refactor / Tailwind CSS 重构版
* shadcn/ui adaptation / shadcn/ui 适配版
* reusable component extraction / 组件化拆分
* reduced-motion mode / 低动态模式
* stronger validation / 更完善的表单校验

---

## Project Reference / 项目参考

### English

This project is a front-end recreation and adaptation inspired by the following component reference:

- [animated-characters-login-page by erikx on 21st.dev](https://21st.dev/community/components/erikx/animated-characters-login-page)

The implementation in this repository focuses on recreating the visual style, interaction logic, and playful user experience in a standalone HTML, CSS, and JavaScript version for learning, demonstration, and customization purposes.

### 中文

本项目为一个前端复刻与改写版本，灵感与参考来源如下：

- [21st.dev - erikx / animated-characters-login-page](https://21st.dev/community/components/erikx/animated-characters-login-page)

本仓库中的实现主要聚焦于使用原生 HTML、CSS 与 JavaScript 复刻其视觉风格、交互逻辑与趣味化体验，便于学习、展示与二次开发。

---

## License / 许可证

This project is released under the **MIT License**.
本项目基于 **MIT License** 开源。

See the [`LICENSE`](./LICENSE) file for details.
具体请查看仓库中的 [`LICENSE`](./LICENSE) 文件。

---

## Repository Description / GitHub 仓库简介文案

**EN**: An animated login page built with HTML, CSS, and JavaScript, featuring responsive layout, mouse-tracking characters, blinking interactions, and playful password reveal behavior.

**中文**：一个使用 HTML、CSS 和 JavaScript 构建的动态登录页，包含响应式布局、角色鼠标跟随、眨眼动画，以及有趣的密码显隐联动效果。

---
