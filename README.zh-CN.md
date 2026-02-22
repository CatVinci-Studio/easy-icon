# Easy Icon（中文）

![私有可控](https://img.shields.io/badge/Private-Controllable-1f6f5f)
![稳定链接](https://img.shields.io/badge/Stable-CDN%20Links-0f766e)
![全程 GitHub](https://img.shields.io/badge/GitHub-Native-24292f?logo=github&logoColor=white)
![网页前端](https://img.shields.io/badge/Web-Frontend-2563eb)

[English](./README.md)

---

## ✨ Easy Icon 是什么

Easy Icon 是一个全基于 GitHub 的快速私有 icon 管理仓库。

你可以用它部署自己的稳定 icon 链接库，整个流程都在 GitHub 内完成，不需要额外配置基础设施。

---

## 🚀 核心亮点

- **私有可控**：图标资产保存在你自己的 GitHub 仓库中。
- **链接稳定**：支持长期可用、可版本化的 CDN 链接。
- **全程 GitHub + 网页前端**：导入和使用更方便，无需额外平台。

---

## 🧭 使用方法

### 1）网页端使用

- 搜索图标
- 分类筛选
- 一键复制链接
- 通过 URL 列表生成 `batch_json`
- 直接上传本地 SVG（支持多选）
- URL 与本地文件可混合批量导入

### 2）通过 GitHub Action 导入

- 打开仓库 **Actions**
- 运行 **Import Icon** 工作流
- 粘贴 `batch_json`
- 开始导入

---

## 🍴 Fork 后如何使用

Fork 本仓库后，请在你自己的仓库里完成一次初始化：

1. 进入 `Settings -> Pages`
2. 在 `Build and deployment -> Source` 选择 `GitHub Actions`
3. 进入 `Settings -> Actions -> General`
4. 将 `Workflow permissions` 设为 `Read and write permissions`
5. 打开 `Actions`，手动重跑一次 `Deploy Pages`

完成后，站点地址通常为：

- `https://<你的用户名或组织>.github.io/<你的 fork 仓库名>/`

说明：
- 如果 `Deploy Pages` 报 `Get Pages site failed` 或 `Resource not accessible by integration`，通常是 Pages 尚未启用，或 Workflow 写权限未开启。
- 如果你的账号或组织配置了自定义域名，最终地址可能显示为该域名，而不是 `github.io`。

---

## 🔗 引用方法

- 稳定版本（推荐）：
  - `https://cdn.jsdelivr.net/gh/<user>/<repo>@v1.0.0/icons/<name>.svg`
- 主分支最新：
  - `https://cdn.jsdelivr.net/gh/<user>/<repo>@main/icons/<name>.svg`

---

## 📮 联系方式

- `chengao_shen@ieee.org`
