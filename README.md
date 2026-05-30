# LongStudy

这是一个静态站点，目前使用 `index.html` 作为主入口页。

## 页面

- `index.html`：LongStudy 主框架页，包含主页、左侧导航和中间内容区
- `BrandonTask.html`：当前唯一接入的独立页面，由 `index.html` 通过 `iframe` 加载
- `styles.css`：主框架页样式

## 本地预览

直接打开 [index.html](./index.html) 即可。

如果需要通过本地服务预览，可以运行：

```powershell
python -m http.server 4173
```

然后访问：

```text
http://localhost:4173/
```

## 文件结构

```text
.
├── index.html
├── BrandonTask.html
├── styles.css
└── README.md
```
