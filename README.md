# LM Design — SV16.4

这是适用于 GitHub 仓库与 GitHub Pages 的 SV16.4 静态发布包。

## 仓库结构

```text
LM-Design-SV16.4/
├── index.html
├── portfolio-sv16.4.html
├── README.md
├── .nojekyll
├── assets/
└── media/
```

- `index.html`：仓库根目录和 GitHub Pages 默认入口。
- `portfolio-sv16.4.html`：可单独访问的版本页面。
- `assets/`：构建后的 CSS 与 JavaScript。
- `media/`：页面实际使用的图片、视频和二维码等资源。

## 上传方式

### 推荐：GitHub Desktop 或 Git

将 `LM-Design-SV16.4` 文件夹内的全部内容复制到仓库根目录后提交并推送。

### 拆包上传

`LM-Design-SV16.4-Upload-Packs` 中的压缩包按编号拆分：

1. 先上传 `01-CORE` 的内容。
2. 再依次上传所有 `02-MEDIA-PART-*` 的内容。
3. 每个媒体包都保留完整的 `media/...` 相对目录；解压到同一仓库根目录即可合并。

GitHub 网页不会自动解压 ZIP。使用网页上传时，请先在本地解压对应分包，再上传其中内容并保持目录层级。

## GitHub Pages

在仓库 `Settings → Pages` 中选择部署分支和根目录。发布后默认由 `index.html` 打开页面。
