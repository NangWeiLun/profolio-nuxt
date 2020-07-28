# profolio-nuxt-vuter

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Note
1. The formatter hard/can't configurate to use nuxtjs recommended settings on vscode. This repo not using the recommended plugin, settings are on .eslintrc.js.

2. The generate command for static target change to 'npm run export', nuxtjs no update it in README.

3. Render facing issue on deploy with nodejs, the 'nuxt' not found, it's look like using cache npm package which no update. So, use command npm install && npm run build && npm export, to reinstall and build. Static site (render and vercel) do well on this.