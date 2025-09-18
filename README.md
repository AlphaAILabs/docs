# AlphaLabs 文档

AlphaLabs 产品文档，包含安装指南、使用说明和功能介绍。

文档包含以下内容：

- 快速开始指南
- 产品功能介绍
- 工具使用说明
- 核心概念解释

## 开发环境

### 环境要求

确保使用 Node.js v22，推荐使用 nvm 管理 Node.js 版本：

```bash
nvm use v22
```

### 本地预览

安装 [Mintlify CLI](https://www.npmjs.com/package/mint) 来本地预览文档：

```bash
npm i -g mint
```

在文档根目录（包含 `docs.json` 的目录）运行：

```bash
mint dev
```

在浏览器中访问 `http://localhost:3000` 查看本地预览。

## 发布更改

通过 [Mintlify 控制台](https://dashboard.mintlify.com/settings/organization/github-app) 安装 GitHub 应用来同步代码仓库的更改到部署环境。推送到默认分支后，更改会自动部署到生产环境。

## 需要帮助？

### 故障排除

- 如果开发环境无法运行：运行 `mint update` 确保使用最新版本的 CLI
- 如果页面显示 404：确保在包含有效 `docs.json` 的文件夹中运行

### 获取支持

如需技术支持，请访问：https://t.co/ZNnay6dnxz

### 相关资源
- [Mintlify 官方文档](https://mintlify.com/docs)
- [Mintlify 社区](https://mintlify.com/community)
