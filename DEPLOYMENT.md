# Deployment status

- GitHub: https://github.com/Wonlyglobal/render-gallery
- Live: https://wonly-render-gallery.pages.dev
- Cloudflare Pages project: wonly-render-gallery
- Custom domain registered: gallery.foreverdoodle.com
- Pending: Aliyun DNS login, then add CNAME `gallery` → `wonly-render-gallery.pages.dev` (check existing records before adding).
- 30 render views, each with composite and transparent PNG.
- No CAD or Blender sources published.

Deploy updates: `wrangler pages deploy public --project-name wonly-render-gallery --branch main`
