# WONLY Render Gallery

S936 产品渲染图库。静态网站，预览图使用 WebP，下载保留原始 PNG。

## 本地运行

`python3 -m http.server 8080 --directory public`

## 部署

`npx wrangler pages deploy public --project-name wonly-render-gallery`

内容位于 `public/gallery.json` 与 `public/assets/`。不包含 CAD、Blender 工程或凭据。产品渲染及品牌素材版权保留；背景为 AI 生成素材。
