# nuxt-typescript-starter

This boilerplate built with [Nuxt.js](https://nuxtjs.org/) showcasing how to add [TypeScript](https://www.typescriptlang.org/) support. It features integrations with ESLint (linting), Prettier (code formatting), Jest (testing), Axios (http calls on steroids), PWA (Progressive Web App) and Automatically run eslint and jest before git commit.

- View intergration details from git history.
- ~~Use [create-nuxt-ts-app](https://github.com/Youmenomi/create-nuxt-ts-app) cli to create your own project.~~

## Quick Start
``` shell
# Clone the repo
git clone https://github.com/Youmenomi/nuxt-typescript-starter.git

cd nuxt-typescript-starter
# Install dependencies
yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

## Typescript Support
- [x] Nuxt (Vue)
- [x] Jest
- [x] lint-staged

## VSCode
### Prerequisites
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
### Autofix and format codes on save
- [settings.json](https://gist.github.com/Youmenomi/16d79436c4f9003e9adac155110c0c27)
### Custom eslint rule in prettier
- For example, for 4-space indentation: [.prettierrc](https://gist.github.com/Youmenomi/ee754af1fed38db6b6613b8bb777370c/revisions)

## Resources
- [Nuxt Typescript](https://typescript.nuxtjs.org/guide/setup.html#installation)
- [ts-jest](https://kulshekhar.github.io/ts-jest/)
- [lint-staged](https://github.com/okonet/lint-staged)
- [Prettier](https://prettier.io/docs/en/install.html)
