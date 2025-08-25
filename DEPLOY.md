# GitHub Pages 部署说明

## 部署步骤

### 1. 准备仓库
确保您的GitHub仓库包含以下文件：
- `src/home/index.html` - 主页面文件
- `src/home/.nojekyll` - 禁用Jekyll处理
- `doc/html/` - 文档HTML文件

### 2. 配置GitHub Pages
1. 进入GitHub仓库设置页面
2. 找到 "Pages" 选项
3. 在 "Source" 部分选择 "Deploy from a branch"
4. 选择分支（通常是 `main` 或 `master`）
5. 选择文件夹为 `/ (root)`
6. 点击 "Save"

### 3. 设置自定义域名（可选）
如果您有自定义域名：
1. 在 "Custom domain" 字段中输入您的域名
2. 勾选 "Enforce HTTPS"
3. 在您的域名提供商处添加CNAME记录指向 `your-username.github.io`

### 4. 访问网站
部署完成后，您的网站将在以下地址可用：
- `https://your-username.github.io/your-repo-name/`
- 如果设置了自定义域名，则使用您的域名

## 文件结构
```
your-repo/
├── src/
│   └── home/
│       ├── index.html          # 主页面
│       ├── .nojekyll           # 禁用Jekyll
│       └── DEPLOY.md           # 部署说明
└── doc/
    └── html/                   # 文档HTML文件
        ├── 项目总览.html
        ├── 需求说明书.html
        ├── 技术白皮书.html
        └── ...
```

## 注意事项
1. 确保所有文档链接路径正确
2. 图片和资源文件需要放在正确的相对路径下
3. 如果使用相对路径链接到其他HTML文件，确保路径正确
4. GitHub Pages可能需要几分钟时间来部署更改

## 故障排除
- 如果页面显示404错误，检查文件路径和分支设置
- 如果样式没有加载，检查CSS路径
- 如果链接不工作，检查相对路径设置

## 更新网站
每次推送代码到GitHub后，GitHub Pages会自动重新部署网站。您可以在仓库的 "Actions" 标签页查看部署状态。
