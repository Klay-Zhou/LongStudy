# Salesforce 2026 New Features

这是一个用于展示 Salesforce 2026 年以来新功能的静态网页站点。

## 页面

- `index.html`：Salesforce Spring '26 / Summer '26 新功能总览
- `ai.html`：Salesforce AI、Agentforce、Tableau MCP、AI agents 相关功能专页

## GitHub Pages 发布方式

1. 在 GitHub 新建一个仓库。
2. 把本地仓库推送到 GitHub。
3. 进入仓库 `Settings -> Pages`。
4. 在 `Build and deployment` 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. 保存后等待 GitHub Pages 生成公开访问链接。

## 本地预览

```powershell
python -m http.server 4173
```

然后打开：

```text
http://localhost:4173/
```

## 文件结构

```text
.
├── index.html
├── ai.html
├── styles.css
├── assets/
│   └── salesforce-release-map.svg
├── .nojekyll
└── README.md
```
