# Cursor Rules 整理工具

这个项目用于整理和收集来自不同项目的Cursor规则文件，提供多种编程语言和框架的规则支持。

## 项目简介

Cursor是一款AI辅助编程工具，它使用规则文件来指导其行为。本项目的目标是收集、整理和标准化这些规则文件，使开发者能够更有效地利用Cursor进行开发工作。

参考文章教程：

[Cursor Rules 的一次全面总结，希望能够帮助到你！](https://mp.weixin.qq.com/s/l8r2lJlEv5fKWJRSsSd1kQ)

[Cursor 0.49.x 自动化生成 Project Rules 实用指南](https://mp.weixin.qq.com/s/1yTkzYzOFjty1D0gtYHuHA)

[Cursor Rules 进阶指南：打造企业级多语言开发规范](https://mp.weixin.qq.com/s/rfanrMtMMuyUTwsDYmlxSg)

[Cursor Rules 最佳实践总结](https://mp.weixin.qq.com/s/-J_LwfwH9rmFy4dzEy0RXg)

参考视频教程：
https://www.bilibili.com/video/BV1S3VhzpEqL/

## 当前支持的规则类型

### 通用规则
- **一般性编程规则** (general.mdc)
- **Git相关规则** (git.mdc)
- **Git Flow工作流规则** (gitflow.mdc)
- **文档编写规则** (document.mdc)

### 编程语言
- **Python** (python.mdc)
- **Java** (java.mdc)
- **TypeScript** (typescript.mdc)
- **Go** (golang.mdc)
- **C++** (c++.mdc)
- **CSS** (css.mdc)
- **WXML** (wxml.mdc) - 微信小程序标记语言
- **WXSS** (wxss.mdc) - 微信小程序样式表

### 框架支持

#### 前端框架
- **React** (react.mdc) - React 应用开发
- **Vue.js** (vuejs.mdc) - Vue.js 应用开发
- **Next.js** (nextjs.mdc) - React 全栈框架
- **Tailwind CSS** (tailwind.mdc) - 实用优先的 CSS 框架

#### 后端框架
- **Django** (django.mdc) - Python Web 框架
- **Flask** (flask.mdc) - Python 轻量级 Web 框架
- **FastAPI** (fastapi.mdc) - Python 现代 API 框架
- **Spring Boot** (springboot.mdc) - Java 企业级框架

#### 移动开发框架
- **Flutter** (flutter.mdc) - 跨平台移动应用开发
- **SwiftUI** (swiftui.mdc) - iOS 原生 UI 框架
- **React Native** (react-native.mdc) - 跨平台移动应用开发

## 功能特点

- 收集不同项目中的Cursor规则文件
- 对规则文件进行分类和整理
- 提供标准化的规则模板
- 便于在不同项目间共享和复用规则
- 支持多种编程语言和框架
- 包含备份和历史版本管理

## 使用方法

1. 克隆本仓库
2. 浏览相应语言和框架的规则
3. 将适用的规则应用到您的项目中
4. 贡献您自己的规则回馈社区

## 项目结构

```
cursor-rules/
├── common/              # 通用规则
│   ├── general.mdc      # 一般性编程规则
│   ├── git.mdc          # Git相关规则
│   ├── gitflow.mdc      # Git Flow工作流规则
│   └── document.mdc     # 文档编写规则
├── languages/           # 编程语言特定规则
│   ├── python.mdc       # Python语言规则
│   ├── java.mdc         # Java语言规则
│   ├── typescript.mdc   # TypeScript语言规则
│   ├── golang.mdc       # Go语言规则
│   ├── c++.mdc          # C++语言规则
│   ├── css.mdc          # CSS样式规则
│   ├── wxml.mdc         # 微信小程序标记语言规则
│   └── wxss.mdc         # 微信小程序样式表规则
├── frameworks/          # 框架相关规则
│   ├── # 前端框架
│   ├── react.mdc        # React框架规则
│   ├── vuejs.mdc        # Vue.js框架规则
│   ├── nextjs.mdc       # Next.js框架规则
│   ├── # 后端框架
│   ├── django.mdc       # Django框架规则
│   ├── flask.mdc        # Flask框架规则
│   ├── fastapi.mdc      # FastAPI框架规则
│   ├── springboot.mdc   # Spring Boot框架规则
│   ├── # 移动开发框架
│   ├── flutter.mdc      # Flutter框架规则
│   ├── swiftui.mdc      # SwiftUI框架规则
│   ├── react-native.mdc # React Native框架规则
│   └── # 样式框架
│   └── tailwind.mdc     # Tailwind CSS规则
└── backup/              # 备份文件夹
    ├── python/          # Python相关备份
    └── vue/             # Vue相关备份
```

## 贡献指南

欢迎提交Pull Request来分享您的Cursor规则。请确保您的规则文件遵循项目的命名约定和结构。规则可以使用Markdown(.mdc)或JSON格式。

### 贡献步骤
1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 许可证

MIT
