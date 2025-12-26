# FABE推销话术训练平台

这是一个帮助用户练习和提升FABE推销技巧的训练平台，用户可以通过随机生成的产品和客户场景进行模拟练习，并获得AI评价和优秀话术示例。

## 功能特点

- 随机生成产品信息和客户情况，提供多样化的练习场景
- 录音功能，记录用户的推销练习过程
- AI智能评价，提供多维度的分析和改进建议
- 优秀话术示例，帮助用户学习专业的推销技巧
- 练习记录管理，追踪用户的成长轨迹
- 响应式设计，支持移动端和桌面端使用

## 技术栈

- React 18+
- TypeScript
- Tailwind CSS
- Vite
- Framer Motion（动画效果）
- React Router（路由管理）
- Sonner（提示信息）
- Local Storage（数据存储）

## 快速开始

以下是针对小白用户的简易部署指南，按照步骤操作即可完成项目的本地运行和部署。

### 第一步：准备环境

1. 首先，您需要安装Node.js（包含npm）
   - 访问 [Node.js官网](https://nodejs.org/)
   - 下载并安装LTS版本（长期支持版）
   - 安装完成后，打开命令提示符（Windows）或终端（Mac/Linux）
   - 输入 `node -v` 和 `npm -v` 检查是否安装成功

2. 安装pnpm（项目使用的包管理器）
   - 在命令提示符/终端中输入：
   - `npm install -g pnpm`

### 第二步：获取代码

1. 下载本项目的代码压缩包
2. 解压到您想要存放的文件夹

### 第三步：本地运行项目

1. 打开命令提示符/终端
2. 进入项目文件夹（使用`cd`命令，例如：`cd 解压后的文件夹路径`）
3. 安装依赖：
   - 输入 `pnpm install` 并按回车
   - 等待安装完成（可能需要几分钟）
4. 启动开发服务器：
   - 输入 `pnpm dev` 并按回车
5. 打开浏览器，访问显示的本地地址（通常是 http://localhost:3000）

### 第四步：构建项目（准备部署文件）

1. 在命令提示符/终端中，确保您在项目文件夹内
2. 输入 `pnpm build` 并按回车
3. 等待构建完成
4. 构建完成后，项目文件夹中会生成一个 `dist` 文件夹，包含了所有需要部署的文件

### 第五步：部署到互联网（推荐以下简单方法）

#### 方法一：使用Vercel（最简单）

1. 访问 [Vercel官网](https://vercel.com/) 并注册账号
2. 登录后，点击"New Project"
3. 点击"Import Project"
4. 选择"Import Git Repository"（如果您的代码在GitHub上）或"Upload"（上传本地`dist`文件夹）
5. 按照提示完成部署
6. 部署完成后，Vercel会提供一个可访问的网址

#### 方法二：使用Netlify

1. 访问 [Netlify官网](https://www.netlify.com/) 并注册账号
2. 登录后，点击"Add new site" -> "Deploy manually"
3. 拖放项目的`dist`文件夹到上传区域
4. 等待部署完成
5. 部署完成后，Netlify会提供一个可访问的网址

#### 方法三：使用GitHub Pages（需要GitHub账号）

1. 将代码上传到GitHub仓库
2. 在GitHub上打开您的仓库
3. 点击"Settings" -> "Pages"
4. 在"Build and deployment"部分，选择"Deploy from a branch"
5. 选择"main"分支（或您的主分支）
6. 在"Folder"下拉菜单中，选择"/dist"
7. 点击"Save"
8. 等待部署完成，GitHub会提供一个可访问的网址

## 项目结构

```
src/
├── components/       # 可复用组件
├── contexts/         # React上下文
├── hooks/            # 自定义钩子
├── lib/              # 工具函数和模拟数据
├── pages/            # 页面组件
├── types/            # TypeScript类型定义
├── App.tsx           # 应用入口组件
├── index.css         # 全局样式
└── main.tsx          # 程序入口文件
```

## 注意事项

- 项目使用Local Storage存储练习记录，数据仅保存在本地浏览器中
- 录音功能需要浏览器麦克风权限
- 如需修改主题，可在个人中心页面切换深色/浅色模式

祝您使用愉快！如果有任何问题，请参考技术文档或寻求帮助。