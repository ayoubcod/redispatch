<!-- README_DEPLOY.md -->
# REdispatch Engine — Static Site (GitHub Pages)

## Deploy (GitHub Pages)
1) Create a GitHub repo (example: `redispatchengine-site`)
2) Put these files in the repo root
3) Push to GitHub
4) Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)

## Custom domain
- Add a `CNAME` file at repo root with the domain on one line
- Update `sitemap.xml`, `robots.txt`, and `og:url` to the real domain
