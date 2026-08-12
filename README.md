# Decurian Ltd — website

Static multi-page site for a medical imaging equipment brokerage.

Rebuild from ../build:
  node build/inject-deploy.mjs   # home
  node build/build-site.mjs      # all other pages + sitemap + robots

Deploy: connected to Vercel via GitHub (auto-deploys on push). Domain: decurianltd.com
Search indexing is controlled by SITE.index in build/seo.mjs (currently INDEXABLE).
