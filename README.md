# 📚 Ulefone Bookmark Navigation

一个极简、响应式、支持分类管理的书签导航系统，适合团队内部协作或个人高效信息管理。无后端依赖，仅基于 HTML/JS/CSS 实现，支持本地或静态部署。

## ✨ 功能亮点

### ✅ 用户导航界面（index.html）
- 分类书签卡片式展示
- 双击分类名可一键打开所有书签
- 快速搜索：支持标题或链接关键词过滤
- 响应式布局：适配桌面与移动端
- 一键切换暗黑/浅色主题

### ✅ 管理后台页面（admin.html）
- 支持添加、删除、重命名分类
- 每个分类下可添加多个书签
- 拖拽排序：分类 & 书签均支持
- 书签信息快速编辑
- 自动生成并预览数据文件（`data.js`）
- 一键复制或下载 `data.js` 文件

## 🗂 文件结构

```
📁 项目根目录
├── index.html      # 主页面：用户访问书签导航
├── admin.html      # 管理后台：添加/编辑/排序书签
├── data.js         # 所有书签数据，以 JS 对象形式保存
```

## 🚀 快速使用

1. 克隆或下载项目：
```bash
git clone https://github.com/your-name/bookmark-navigation.git
```

2. 打开 `index.html` 使用导航页；
3. 使用 `admin.html` 管理书签数据；
4. 所有书签信息保存在 `data.js`，可手动或自动更新。

## 📦 部署建议

支持 GitHub Pages、Vercel、Netlify 等任意静态托管平台部署。无需服务器，无依赖。

## 📝 License

MIT License © 2025 [Your Name]