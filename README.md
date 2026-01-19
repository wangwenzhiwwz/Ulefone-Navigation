# Ulefone Navigation | 极简书签导航

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

一个基于纯 HTML/CSS/JS 构建的静态个人书签导航页。主打**黑白极简美学**、**无边框设计**与**流畅的交互体验**。包含一个可视化的管理后台，无需数据库即可轻松管理书签数据。

---

## ✨ 设计理念 (Design Philosophy)

* **极致简约**：摒弃多余的阴影与边框，完全依靠**色块层级**（白/浅灰/深灰）构建界面。
* **胶囊美学**：侧边栏、按钮、输入框统一采用**胶囊形（Pill Shape）**或大圆角矩形设计，视觉柔和。
* **交互优先**：
    * 左侧导航与右侧内容**双向联动**。
    * **单击标题**即可打开该分类下所有链接。
    * 顶部 Welcome 模块提供日期、问候语及数据统计。
    * 全局**平滑滚动**与**交错入场动画**。

## 🚀 功能特性 (Features)

### 🖥️ 前台 (index.html)
* **响应式布局**：完美适配桌面端（左右布局）与移动端（单栏布局）。
* **深色模式**：自动跟随系统偏好，支持手动一键切换（🌞/🌙）。
* **智能搜索**：实时过滤书签，支持**关键词高亮**显示。
* **自动图标**：集成 Google Favicon API，自动获取网站图标。
* **沉浸体验**：顶部高斯模糊导航栏，右下角全局刷新按钮。

### ⚙️ 后台管理 (admin.html)
* **可视化编辑**：直观的增、删、改操作（支持自定义图标 URL）。
* **拖拽排序**：支持卡片拖拽调整顺序。
* **数据导出**：一键生成并下载 `data.js` 配置文件。
* **数据仓库跳转**：快捷跳转至 GitHub 仓库进行文件托管。

---

## 📂 项目结构

```text
/
├── index.html      # 前台主页
├── admin.html      # 后台管理页
├── data.js         # 数据文件 (存储所有书签数据)
├── images/         # 本地图片资源 (Logo 等)
└── README.md       # 说明文档