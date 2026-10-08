# 个人简历网页

单文件静态简历页面，基于 three.js 的粒子动效版。

## 技术栈

- 原生 HTML / CSS / JavaScript（单文件 `index.html`，约 2.5 MB）
- three.js 与字体均走 CDN，无本地依赖

## 本地运行

直接用浏览器打开 `index.html` 即可；如需走 HTTP：

```bash
python -m http.server 8000
# 访问 http://localhost:8000
```

## 仓库说明

- 仅发布 `index.html` 与本 README
- 备份、截图、源素材等通过 `.gitignore` 屏蔽，不上传
- 部署方式：GitHub Pages（分支 `main` / 根目录）
