# Deployment status

- GitHub: https://github.com/Wonlyglobal/render-gallery
- Live: https://wonly-render-gallery.pages.dev
- Cloudflare Pages project: wonly-render-gallery
- Custom domain registered: gallery.foreverdoodle.com
- Aliyun DNS configured: CNAME `gallery` → `wonly-render-gallery.pages.dev`, TTL 10 minutes.
- Domain ownership verification passed; HTTPS certificate provisioning checked after DNS setup.
- 70 render views, each with composite and transparent PNG.
- No CAD or Blender sources published.

Deploy updates: `wrangler pages deploy public --project-name wonly-render-gallery --branch main`
