
# AICollabGallery

AICollabGallery 是一个智能、可协同的图库项目，支持图片的上传、下载、在线编辑以及多人协作。用户可以方便地管理和共享自己的图片，同时可以与团队成员共同编辑和修改。

## 项目功能

- **图片管理**：上传、下载和管理个人图库中的图片。
- **在线编辑**：提供强大的图片编辑功能，支持裁剪、调整大小、旋转等操作。
- **多人协同**：支持多人同时在线编辑图片，团队成员可以实时查看和修改。
- **分析功能**：基于图片内容提供分类、标签等数据分析。

## 安装与使用

### 安装依赖

首先，克隆该仓库并安装依赖：

```bash
git clone https://github.com/RuiqiYing/AICollabGallery.git
cd AICollabGallery
npm install
```

### 启动开发环境

```bash
npm run dev
```

开发服务器启动后，您可以在浏览器中访问 [http://localhost:3000](http://localhost:3000) 来查看项目。

### 构建项目

```bash
npm run build
```

该命令会生成生产环境的代码，存放在 `dist/` 文件夹中。

### 预览构建后的项目

```bash
npm run preview
```

### 项目目录结构

```
AICollabGallery/
│
├── dist/                       # 构建后的文件
├── node_modules/               # 项目的依赖
├── public/                     # 公共文件
│   └── logo.png                # 项目 logo
│
├── src/                        # 源代码
│   ├── api/                    # API 请求接口
│   ├── components/             # 项目组件
│   ├── constants/              # 常量定义
│   ├── layouts/                # 布局组件
│   ├── pages/                  # 页面
│   ├── router/                 # 路由配置
│   ├── stores/                 # 状态管理
│   └── utils/                  # 工具函数
│
├── package.json                # 项目配置文件
└── README.md                   # 项目说明文件
```

## 技术栈

- **Vue 3**：构建用户界面
- **Pinia**：状态管理
- **Axios**：HTTP 请求
- **Ant Design Vue**：UI 组件库
- **ECharts**：数据可视化

## 贡献

欢迎提交 Pull Request 来贡献代码，或者报告 Bug。我们非常欢迎大家的参与！

