# 长春望月｜给世龙

静态网页，可直接部署到 GitHub Pages 或 Vercel。

## 文件
- `index.html`：网页主体
- `voice.mp3`：语音留言占位文件，请用你的真实录音覆盖
- `.nojekyll`：GitHub Pages 静态发布辅助文件

## GitHub Pages
将整个目录上传到 GitHub 仓库后，在 Settings → Pages 中选择从 `main` 分支根目录发布。

## Vercel
Import Git Repository，Framework Preset 选择 Other，Build Command 和 Output Directory 留空后直接 Deploy。

## 语音
录音建议导出为 MP3，并命名为 `voice.mp3`，与 `index.html` 放在同一目录。
