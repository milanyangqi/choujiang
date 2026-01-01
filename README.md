# Log Lottery

一个基于 Vue 3 + TypeScript 开发的现代化抽奖应用。

## 技术栈

- **前端框架**: Vue 3
- **开发语言**: TypeScript
- **构建工具**: Vite
- **UI 组件**: Tailwind CSS + daisyUI
- **状态管理**: Pinia
- **路由管理**: Vue Router
- **国际化**: Vue I18n
- **容器化**: Docker

## 功能特性

- 🎲 多种抽奖模式支持
- 📊 实时数据统计
- 🎨 自定义主题和样式
- 🌍 多语言支持
- 💾 本地数据持久化
- 📱 响应式设计，适配各种设备
- 🚀 Docker 一键部署

## 快速开始

### 环境要求

- Node.js >= 22.x
- pnpm >= 10.x

### 安装依赖

```bash
pnpm install
```

### 开发模式

```bash
pnpm dev
```

访问 `http://localhost:5173` 查看应用

### 构建生产版本

```bash
pnpm build
```

构建产物将生成在 `dist` 目录

## Docker 部署

### 构建镜像

```bash
docker-compose build
```

### 启动服务

```bash
docker-compose up -d
```

### 访问应用

访问 `http://localhost:8088` 查看应用

### 停止服务

```bash
docker-compose down
```

## 项目结构

```
log-lottery/
├── src/                 # 源代码目录
│   ├── assets/          # 静态资源
│   ├── components/      # 组件
│   ├── locales/         # 国际化配置
│   ├── router/          # 路由配置
│   ├── stores/          # 状态管理
│   ├── types/           # TypeScript 类型定义
│   ├── utils/           # 工具函数
│   ├── views/           # 页面组件
│   ├── App.vue          # 根组件
│   └── main.ts          # 入口文件
├── public/              # 公共资源
├── src-tauri/           # Tauri 桌面应用配置
├── Dockerfile           # Docker 构建文件
├── docker-compose.yml   # Docker Compose 配置
├── package.json         # 项目依赖
├── tsconfig.json        # TypeScript 配置
├── vite.config.ts       # Vite 配置
└── tailwind.config.js   # Tailwind CSS 配置
```

## 许可证

MIT License
