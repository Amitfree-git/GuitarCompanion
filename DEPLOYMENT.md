# 弦伴 v0.2 · 静态网站发布

本仓库用于发布「弦伴 v0.2 · 和弦 Loop 版」。网站入口为根目录的 `index.html`，静态部署标记为 `.nojekyll`。

## GitHub Pages 首次设置

在仓库 Settings → Pages 中设置：

- Source：Deploy from a branch
- Branch：main
- Folder：/ (root)

保存后，以 Pages 设置页的实际部署结果和 Visit site 地址为准。仅提交代码不代表网站已上线。

## 发布文件校验

首页应与对话中交付的 v0.2 HTML 完全一致：

- 文件大小：144450 字节
- SHA-256：`91e03ea48c1fcf7212b2d6b1d831c781b94ac9658b40db78ac82b9d531f1fb89`
- Git blob SHA：`18d6b5cd1d3044b895618859929c6cd2c174540e`

## 使用边界

手动 Loop 在浏览器本地生成和播放伴奏，不依赖麦克风；仍需点击「开始循环」才能发声。原有自动识别功能仍为实验功能，发布到网站并不会提高其识别准确率。原本地页面保存的方案可通过 JSON 导出、导入迁移。
