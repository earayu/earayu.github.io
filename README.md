# Bryce Yu's Blog

## Deploy with local node.js runtime
Please overwrite `next.config.js` with `next.config.js.nodejs` to deploy on node.js runtime.
```zsh
yarn install
yarn dev
```

## Deploy with local static files
Please overwrite `next.config.js` with `next.config.js.static` to deploy as a static site.
```zsh
yarn build
npx serve out
```

## Deploy on Github Pages
This blog is deployed on Github Pages. The CI/CD is powered by Github Actions.
Note: Github Pages only supports static files.


## Deploy on Vercel
Vercel supports Next.js out of the box, so we can use node.js runtime to deploy this blog.

