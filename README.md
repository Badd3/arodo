# arodo


## Installatie zoals ik deze heb doorlopen:

```
yarn create nuxt-app arodo
```

- Project name: arodo
- Programming language: JavaScript
- Package manager: Yarn
- UI Framework: Tailwind CSS
- Nuxtjs modules: /
- Linting tools: /
- Testing framework: None
- Rendering mode: Universal (SSR / SSG)
- Deployment Target: Server (Node.js hosting)
- Development tools: / 

Om de tailwind.config.js te installeren volgende command uitgevoerd:
```
npx tailwindcss init
```

Ik had in eerste instantie nog Statamic in deze nuxt directory geinstalleerd in een map genaamd arodo-cms. Heb het uiteindelijk verwijderd omdat ik het idee had dat het niet correct was. Onderstaand de commands die ik had uitgevoerd. Voor nu ga ik even aan de slag met Nuxtjs & Tailwind. Zal eerst proberen de homepage statisch op te zetten met Nuxt & Tailwindcss. Dat is voor nu al een mooi leerdoel denk ik.


## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.

### `assets`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).

### `components`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).

### `layouts`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).


### `pages`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

### `plugins`

The plugins directory contains JavaScript plugins that you want to run before instantiating the root Vue.js Application. This is the place to add Vue plugins and to inject functions or constants. Every time you need to use `Vue.use()`, you should create a file in `plugins/` and add its path to plugins in `nuxt.config.js`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins).

### `static`

This directory contains your static files. Each file inside this directory is mapped to `/`.

Example: `/static/robots.txt` is mapped as `/robots.txt`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/static).

### `store`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).



