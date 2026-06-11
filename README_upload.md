# GitHub Pages 上传说明

把本目录 `github_pages_site` 里的文件全部上传到仓库 `FightingXgg.github.io` 的根目录：

- `index.html`：PC 演示入口，页面右下角有扫码体验按钮
- `pc.html`：PC 在线监测大屏
- `mobile.html`：手机扫码体验页
- `qr.png`：指向 `https://fightingxgg.github.io/mobile.html` 的二维码，用于观众手机扫码体验
- `.nojekyll`：让 GitHub Pages 原样发布静态文件

上传后请确认 GitHub Pages 设置为：

1. `Settings` -> `Pages`
2. `Source` 选择 `Deploy from a branch`
3. 分支选择 `main`，目录选择 `/root`
4. 等待 1-3 分钟后访问 `https://fightingxgg.github.io/`

如果网页还是空白，请打开仓库里的 `index.html`，确认文件大小不是 0 或 2 字节。
