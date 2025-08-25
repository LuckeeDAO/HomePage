# GitHub Pages 部署说明

## 📋 目录结构

```
src/home/
├── index.html              # 主页面文件
├── README.md               # 项目主页说明
├── DEPLOY.md               # 详细部署指南
├── .nojekyll               # 禁用Jekyll处理
├── docs/                   # 文档目录
│   ├── 项目总览.html
│   ├── 需求说明书.html
│   ├── 技术白皮书.html
│   ├── 概要设计说明书.html
│   ├── 详细设计说明书.html
│   ├── 可行性分析报告.html
│   ├── 项目术语表.html
│   └── 技术选型/          # 技术选型文档
│       ├── Rust智能合约开发指南.html
│       ├── IPFS存储策略设计说明书.html
│       ├── iAgent自动化功能设计说明书.html
│       ├── 多应用场景支持设计说明书.html
│       ├── 多目标选择技术实现方案.html
│       └── 技术脉络总结.html
```

## 🚀 部署步骤

### 1. 创建GitHub仓库
1. 在GitHub上创建新的仓库
2. 仓库名称建议：`decentralized-voting-system` 或 `bit-commitment-voting`

### 2. 上传文件
将 `src/home/` 目录下的所有文件上传到GitHub仓库的根目录：
- `index.html`
- `README.md`
- `DEPLOY.md`
- `.nojekyll`
- `docs/` 目录及其所有内容

### 3. 配置GitHub Pages
1. 进入仓库设置页面 (Settings)
2. 找到 "Pages" 选项
3. 在 "Source" 部分选择 "Deploy from a branch"
4. 选择分支（通常是 `main` 或 `master`）
5. 选择文件夹为 `/ (root)`
6. 点击 "Save"

### 4. 访问网站
部署完成后，您的网站将在以下地址可用：
- `https://your-username.github.io/your-repo-name/`

## 📚 文档说明

### 核心文档
- **项目总览.html** - 项目完整概述，包含系统介绍、技术架构、开发计划和风险评估
- **需求说明书.html** - 详细的功能需求说明，包含所有应用场景和技术要求
- **技术白皮书.html** - 技术实现方案和架构设计，包含核心技术选型和实现细节
- **概要设计说明书.html** - 系统架构设计和详细技术设计，包含数据库设计和接口规范

### 技术选型文档
- **Rust智能合约开发指南.html** - 基于CosmWasm框架的智能合约开发指南
- **IPFS存储策略设计说明书.html** - 去中心化存储策略设计，包含CID验证、Merkle树和数据完整性保证
- **iAgent自动化功能设计说明书.html** - 自动化功能设计说明书，包含自动承诺/揭示、审计日志和智能触发机制
- **多应用场景支持设计说明书.html** - 多应用场景支持设计说明书，包含NFT类型驱动架构和统一技术框架
- **多目标选择技术实现方案.html** - 多目标选择技术实现方案，包含n选k算法、防冲突机制和序号分配策略
- **技术脉络总结.html** - 技术脉络总结文档，梳理整个系统的技术架构和实现路径

### 其他文档
- **可行性分析报告.html** - 项目可行性分析报告，包含技术可行性、经济可行性和风险评估
- **项目术语表.html** - 项目术语表，统一技术术语和概念定义，确保文档一致性

## 🔧 自定义配置

### 修改GitHub链接
在 `index.html` 文件中，将以下链接替换为您的实际GitHub仓库地址：
```html
<a href="https://github.com/your-username/your-repo" class="btn btn-secondary">GitHub</a>
```

### 修改Open Graph标签
在 `index.html` 文件的 `<head>` 部分，更新以下meta标签：
```html
<meta property="og:url" content="https://your-username.github.io/your-repo/">
<meta property="og:image" content="https://your-username.github.io/your-repo/assets/og-image.png">
```

## 📝 注意事项

1. **文件路径**：所有文档链接已更新为相对路径，指向 `docs/` 目录
2. **中文文件名**：GitHub Pages支持中文文件名，无需担心编码问题
3. **文档完整性**：所有技术文档都已包含，确保完整的技术文档体系
4. **SEO优化**：页面已包含完整的meta标签和Open Graph标签
5. **响应式设计**：页面支持移动端和桌面端访问

## 🎯 页面特色

- **现代化设计**：使用渐变背景、卡片布局和emoji图标
- **技术专业性**：详细展示比特承诺协议、NFT类型驱动架构等核心技术
- **完整文档体系**：从项目概述到技术实现的完整文档覆盖
- **用户友好**：清晰的导航结构和直观的信息架构
- **SEO优化**：完整的meta标签和结构化内容

## 🔗 相关链接

- [GitHub Pages官方文档](https://pages.github.com/)
- [GitHub Pages自定义域名](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [GitHub Pages Jekyll配置](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

---

> 💡 **提示**：部署完成后，建议测试所有文档链接，确保都能正常访问。如果遇到问题，请检查文件路径和GitHub Pages设置。
