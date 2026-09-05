# 🌐 WebCollect · 优雅的 Web 收录与导航站点

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Vue 3](https://img.shields.io/badge/Vue-3.4-42b883)](https://vuejs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.0-646cff)](https://vitejs.dev/)

> **WebCollect** 是一款开源、轻量、可定制的 Web 收录与导航工具。它帮助个人或团队高效管理常用网址、优质资源、在线工具，并以清晰、美观的卡片式布局呈现，让收藏与发现变得简单而愉悦。

---

## 📖 项目简介

在信息爆炸的时代，我们每天都会遇到大量有价值的网站、文档、工具和灵感来源。然而，浏览器的书签栏往往杂乱无章，跨设备同步麻烦，分享也不够便捷。**WebCollect** 正是为解决这些痛点而生。

- **核心定位**：个人/团队的书签管理器 + 轻量级导航站。
- **设计理念**：极简、高效、可扩展。
- **适用场景**：
  - 个人常用网址收藏与分类
  - 团队内部资源库（设计素材、开发文档、协作工具）
  - 公开导航站（如“前端学习导航”、“AI 工具合集”）

---

## ✨ 功能特性

### 核心功能
- 🔖 **收录管理**  
  - 支持添加、编辑、删除收录项（标题、URL、图标、描述、标签）
  - 支持拖拽排序，自由调整布局
  - 支持批量导入/导出（JSON / HTML 书签格式）

- 📂 **分类与标签**  
  - 无限级分类（可嵌套子分类）
  - 多标签系统，支持快速筛选
  - 分类/标签颜色标识，视觉区分更清晰

- 🔍 **智能搜索**  
  - 实时模糊搜索（标题、描述、URL、标签）
  - 支持拼音搜索（适用于中文用户）

- 🌙 **主题与布局**  
  - 亮色/暗色模式，自动跟随系统偏好
  - 卡片/列表双视图切换
  - 响应式设计，完美适配桌面、平板、手机

- 👥 **多用户与协作（可选）**  
  - 基于 JWT 的用户认证
  - 个人私有收藏 + 公共收藏夹
  - 收藏夹分享链接（公开/加密）

### 扩展能力
- 📊 **数据统计**：收录总数、点击排行、分类占比
- 🧩 **插件机制**：支持自定义渲染组件（例如嵌入 iframe 预览）
- 🌍 **国际化**：内置中/英文，可扩展多语言

---

## 🛠️ 技术栈

| 层面 | 技术选型 |
|------|----------|
| **前端框架** | Vue 3 (Composition API) |
| **构建工具** | Vite |
| **UI 组件库** | Naive UI / Element Plus（可替换） |
| **状态管理** | Pinia |
| **路由** | Vue Router 4 |
| **数据持久化** | 前端：localStorage / IndexedDB；后端（可选）：Node.js + Express + SQLite/PostgreSQL |
| **HTTP 客户端** | Axios |
| **图标库** | Iconify + Font Awesome |
| **样式方案** | SCSS + CSS Variables（动态主题） |

---

## 📦 快速开始

### 前置条件
- Node.js >= 18
- npm / yarn / pnpm（推荐 pnpm）

### 克隆与安装

```bash
# 克隆仓库
git clone https://github.com/your-username/webcollect.git
cd webcollect

# 安装依赖（使用 pnpm）
pnpm install

# 或者使用 npm
npm install
