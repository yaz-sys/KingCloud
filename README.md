# KingCloud - 私有云前端

KingCloud 是一个私有云存储系统的 Web 前端界面，致力于提供直观的用户体验，方便用户管理文件、照片和系统设置。它的设计理念是在浏览器中模拟出类似桌面的操作环境。

## 功能特性

- **类桌面界面**：整洁清爽的图标式导航系统。
- **文件管理**：将文件分类为远程空间、相册、保险箱和系统设置等模块。
- **远程空间**：管理云端文件的核心区域，提供个人空间、团队空间、外接硬盘和共享文件的快捷导航。
- **响应式设计**：适配多种屏幕尺寸。
- **交互体验**：包含悬停效果、下拉菜单和流畅的过渡动画。

## 项目结构

```
KingCloud/
├── src/                # 源代码
│   ├── css/            # 样式表
│   ├── html/           # HTML 模板
│   ├── images/         # 图片资源
│   ├── js/             # JavaScript 文件 (如有)
│   └── remote_space/   # 远程空间模块
├── docs/               # 文档
├── tests/              # 单元测试
├── .github/            # GitHub 配置 (Actions 等)
├── .editorconfig       # 编辑器配置
├── .eslintrc.json      # ESLint 配置
├── package.json        # Node.js 依赖配置
└── README.md           # 项目说明文档
```

## 快速开始

### 先决条件

- 现代网页浏览器（Chrome, Firefox, Edge, Safari）。
- [Node.js](https://nodejs.org/)（可选，用于开发工具）。

### 安装指南

1.  克隆仓库：
    ```bash
    git clone https://github.com/yourusername/KingCloud.git
    ```
2.  进入项目目录：
    ```bash
    cd KingCloud
    ```
3.  安装开发依赖（可选）：
    ```bash
    npm install
    ```

### 使用说明

直接在浏览器中打开 `src/index.html` 即可启动应用。

```bash
# 如果您使用本地服务器（例如 VS Code 的 Live Server）
# 打开 src/index.html
```

## 开发指南

### 代码检查 (Linting)

运行 ESLint 检查代码风格问题：

```bash
npm run lint
```

### 测试 (Testing)

使用 Jest 运行测试：

```bash
npm test
```

## 贡献指南

欢迎提交贡献！请遵循以下步骤：

1.  Fork 本仓库。
2.  创建新的分支 (`git checkout -b feature/YourFeature`)。
3.  提交您的更改 (`git commit -m 'Add some feature'`)。
4.  推送到该分支 (`git push origin feature/YourFeature`)。
5.  提交 Pull Request。
