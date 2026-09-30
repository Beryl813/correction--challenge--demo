# 改错挑战赛 Demo

一个无需构建工具的静态 HTML Demo。上传到 GitHub 后，可直接通过 GitHub Pages 发布。

## 本地预览

直接双击 `index.html` 即可打开。

也可以在项目目录运行：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `correction-challenge`。
2. 上传 `index.html`、`README.md` 和 `.gitignore`。
3. 打开仓库的 `Settings` → `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 选择默认分支和 `/ (root)`，点击 `Save`。
6. 等待 GitHub Pages 完成部署，页面地址通常是：

   `https://你的用户名.github.io/correction-challenge/`

## 文件说明

- `index.html`：完整的单文件 Demo，包含样式和交互逻辑。
