# 审计工作台 Demo

基于 Vue 3 + Element Plus 开发的审计工作台及离职合作方账号使用核查工具。

## 🌐 在线预览

部署后访问地址：`https://742801049-lianglihong.github.io/audit-workbench-demo/`

## 📋 功能说明

### 工作台界面
- 左侧可折叠导航栏
- 欢迎头部（用户头像、欢迎语）
- 分类 Tab（全部工具、活动检查、安全检查、文档检查、制度检查、重复检查）
- 工具卡片网格布局

### 离职合作方账号使用核查工具
- 压缩包/单文件上传
- 拖拽上传功能
- 上传与检验结果列表
- 三栏式结果查看页面

## 🚀 部署步骤

### 方法一：使用 GitHub Actions 自动部署（推荐）

1. 在 GitHub 创建新仓库，命名为 `audit-workbench-demo`
2. 将本目录所有文件上传到仓库
3. 进入仓库 Settings → Pages → Source 选择 "GitHub Actions"
4. 等待自动部署完成（约 1-2 分钟）
5. 访问 `https://742801049-lianglihong.github.io/audit-workbench-demo/`

### 方法二：手动部署

1. 进入仓库 Settings → Pages
2. Source 选择 "Deploy from a branch"
3. Branch 选择 "main"，文件夹选择 "/ (root)"
4. 保存后等待部署

## 📦 技术栈

- Vue 3
- Element Plus
- TypeScript
- Vite

## 📄 文件说明

本项目为静态构建文件，可直接部署到任意静态托管服务：
- GitHub Pages
- Gitee Pages
- Vercel
- Netlify
- 腾讯云/阿里云对象存储
