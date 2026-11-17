# Design Team Sprint Wins

Static page, no build step. Everything the page needs is in this folder.

## Deploy with the Vercel CLI

    npm i -g vercel
    cd vercel-site
    vercel          # first time: log in, accept the defaults (no framework, no build command)
    vercel --prod   # publish to your production URL

## Or deploy from GitHub

1. Push this folder to a new GitHub repository.
2. In Vercel: Add New > Project > import the repository.
3. Framework preset: Other. Leave the build and output settings empty. Deploy.

## Files

- index.html: the page
- assets/: images, the video, both PDFs and the Motion Kit SVG
- vercel.json: caching for assets and inline PDFs
