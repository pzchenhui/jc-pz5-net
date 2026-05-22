# AI智能体教师教程

[![Website](https://img.shields.io/badge/网站-jc.pz5.net-4f46e5?style=for-the-badge&logo=vitepress)](https://jc.pz5.net)
![License](https://img.shields.io/badge/公益网站-免费使用-brightgreen?style=for-the-badge)
![Chapters](https://img.shields.io/badge/章节-9章42节-orange?style=for-the-badge)

> **学好AI智能体，做轻松智慧好老师**
> 
> 从零代码搭建到全校智能体生态，一步步打造你的AI教学助手

---

## 📖 教程简介

本教程面向**零代码基础**的教师，通过**可视化AI平台**，教你一步步搭建专属AI智能体。

- **30分钟** 完成第一个智能体
- **9章42节** 系统学习，含实操步骤和练习题
- **38+真实案例** 来自一线教师的使用经验
- **40+可复用模板** 人设模板、工作流模板、公文模板等

**🌐 在线阅读**：[https://jc.pz5.net](https://jc.pz5.net)

---

## 🎯 适合谁？

| 你是 | 你将获得 |
|------|---------|
| **零基础教师** | 从零开始搭建第一个AI智能体，30分钟上手 |
| **有经验教师** | 学习工作流和高级功能，效率提升6倍以上 |
| **教研组长/教务主任** | 掌握学校级AI推广方案，构建智能体生态 |
| **班主任** | 搭建班主任助手，从评语到家校沟通全面提效 |

---

## 📋 目录结构

```
docs/
├── .vitepress/              # VitePress 配置
│   ├── config.mjs           # 站点配置（导航、侧边栏等）
│   └── theme/
│       ├── index.js         # 自定义主题入口
│       └── style.css        # 自定义CSS样式
├── public/
│   └── logo.svg             # 网站Logo
├── guide/
│   └── toc.md               # 教程目录页
├── index.md                 # 首页
├── ch01/                    # 第1章 AI智能体基础
│   ├── intro.md             # 1.1 普通AI工具 vs AI智能体
│   ├── features.md          # 1.2 AI智能体功能
│   ├── teacher-use.md       # 1.3 教师如何有效利用
│   ├── platforms.md         # 1.4 主流平台对比
│   └── exercises.md         # 练习题
├── ch02/                    # 第2章 零代码搭建
│   ├── intro.md             # 2.1 测一测：你急需哪类智能体？
│   ├── build.md             # 2.2 从零到一搭建智能体
│   ├── persona.md           # 2.3 人设与回复逻辑
│   ├── capability.md        # 2.4 能力编排
│   ├── debug.md             # 2.5 预览与调试
│   ├── publish.md           # 2.6 发布
│   └── exercises.md         # 练习题
├── ch03/                    # 第3章 工作流进阶
│   ├── intro.md             # 3.1 什么是工作流？
│   ├── advantages.md        # 3.2 工作流的优势
│   ├── build-steps.md       # 3.3 工作流搭建步骤
│   ├── call-workflow.md     # 3.4 智能体调用工作流
│   └── exercises.md         # 练习题
├── ch04/                    # 第4章 备课助手
│   ├── intro.md             # 4.1 日常备课融入智能体
│   ├── lesson-plan.md       # 4.2 教案生成助手
│   ├── instructional-design.md  # 4.3 教学设计助手
│   ├── exam.md              # 4.4 考试测评助手
│   ├── courseware.md        # 4.5 快速生成课件
│   └── exercises.md         # 练习题
├── ch05/                    # 第5章 学科助手（智慧学伴）
│   ├── intro.md             # 5.1 了解智慧学伴
│   ├── persona.md           # 5.2 人设与回复逻辑
│   ├── plugins.md           # 5.3 插件选择与配置
│   ├── knowledge-base.md    # 5.4 知识库建设
│   ├── details.md           # 5.5 细节设置
│   ├── test-publish.md      # 5.6 测试与发布
│   ├── tools.md             # 5.7 巧用AI工具
│   └── exercises.md         # 练习题
├── ch06/                    # 第6章 活动助手
│   ├── intro.md             # 6.1 了解活动助手
│   ├── persona.md           # 6.2 人设与回复逻辑
│   ├── creative.md          # 6.3 活动创意策划
│   ├── poster.md            # 6.4 海报生成
│   ├── review.md            # 6.5 活动复盘
│   ├── details.md           # 6.6 细节设置
│   ├── test-publish.md      # 6.7 测试与发布
│   ├── tools.md             # 6.8 巧用AI工具
│   └── exercises.md         # 练习题
├── ch07/                    # 第7章 行政助手
│   ├── intro.md             # 7.1 了解行政助手
│   ├── persona.md           # 7.2 人设与回复设置
│   ├── plugins.md           # 7.3 插件选择与配置
│   ├── details.md           # 7.4 细节设置
│   ├── test-publish.md      # 7.5 测试与发布
│   ├── tools.md             # 7.6 巧用AI工具
│   └── exercises.md         # 练习题
├── ch08/                    # 第8章 班主任助手
│   ├── intro.md             # 8.1 了解班主任助手
│   ├── dialogue.md          # 8.2 对话流模式
│   ├── design.md            # 8.3 对话流设计
│   ├── details.md           # 8.4 细节设置
│   ├── test-publish.md      # 8.5 测试与发布
│   ├── tools.md             # 8.6 巧用AI工具
│   └── exercises.md         # 练习题
├── ch09/                    # 第9章 全校智能体生态
│   ├── intro.md             # 9.1 学校AI工作台（多平台对比）
│   ├── customization.md     # 9.2 场景化定制
│   └── exercises.md         # 练习题
└── package.json             # 项目依赖配置
```

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| [VitePress](https://vitepress.dev/) | 静态网站生成器（Vue 3驱动） |
| Markdown | 内容编写格式 |
| 自定义CSS | 首页美化、卡片样式、暗色模式适配 |
| Nginx | Web服务器（生产环境部署） |
| Let's Encrypt | SSL证书自动续期 |

---

## 🚀 本地开发

### 前置条件

- Node.js >= 18
- npm 或 pnpm

### 安装依赖

```bash
npm install
```

### 本地预览

```bash
npx vitepress dev docs
```

打开浏览器访问 `http://localhost:5173`

### 构建生产版本

```bash
npx vitepress build docs
```

构建产物输出到 `docs/.vitepress/dist/`

### 部署

将 `docs/.vitepress/dist/` 目录下的文件部署到任意静态服务器（Nginx、GitHub Pages等）。

---

## 📊 站点数据

| 指标 | 数值 |
|------|------|
| 总HTML页面 | 60个 |
| 总文件数 | 200+ |
| 章节数 | 9章 |
| 小节数 | 42节 |
| 总内容量 | 201 KB |
| 真实案例 | 38+ 个 |
| 可复用模板 | 40+ 个 |
| 练习题 | 9套 |

---

## 🌐 部署方式

### 方式一：Nginx（推荐）

```bash
# 构建
npx vitepress build docs

# 复制到Nginx目录
sudo cp -r docs/.vitepress/dist/* /var/www/jc.pz5.net/

# 配置Nginx（参考 /etc/nginx/sites-available/jc.pz5.net）
sudo nginx -t && sudo systemctl reload nginx
```

### 方式二：GitHub Pages

1. Push 代码到 GitHub
2. Settings → Pages → Source: `main` branch, `/docs/.vitepress/dist` folder
3. 自动构建部署

---

## 📝 涉及的平台

本教程以以下AI平台为例进行教学：

| 平台 | 类型 | 教程中的角色 |
|------|------|-------------|
| **Coze（扣子）** | 智能体搭建平台 | 主力教学平台（零代码+工作流） |
| **Dify** | 开源智能体平台 | 自建方案推荐 |
| **智谱清言（GLM）** | AI对话平台 | 高质量文本生成场景 |
| **Kimi** | AI对话平台 | 长文档分析场景 |
| **通义千问** | AI对话平台 | 阿里生态集成场景 |

> 教程中的智能体搭建方法通用性强，可迁移至其他类似平台。

---

## ⭐ 核心功能

| 功能 | 说明 |
|------|------|
| 🤖 **零代码搭建** | 通过可视化平台搭建AI智能体，无需编程 |
| 🔧 **工作流编排** | 多步骤任务自动化，效率提升6倍以上 |
| 📝 **备课助手** | 教案生成、出题、课件大纲一键生成 |
| 🎓 **智慧学伴** | 24小时为学生答疑的学习伙伴 |
| 🎉 **活动助手** | 策划校园活动、生成海报文案 |
| 📄 **行政助手** | 高效撰写公文、会议纪要、新闻稿 |
| 👨‍👩‍👧‍👦 **班主任助手** | 批量评语、家校沟通话术 |
| 🏫 **全校生态** | 多平台协同，构建学校级AI工作台 |

---

## 📄 许可证

本网站为**公益培训网站**，免费使用，所有代码已公开。

Copyright © 2026 AI智能体教师教程 陈辉制作

---

## 🙏 致谢

感谢所有先行试用本教程的教师，你们的反馈让教程更加完善。

---

**🌐 立即访问**：[https://jc.pz5.net](https://jc.pz5.net)
