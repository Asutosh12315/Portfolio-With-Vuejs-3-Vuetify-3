# portfolio

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Steps to start this project -

`vue create portfolio`

`cd portfolio`

`vue add vuetify`

`npm install @fortawesome/fontawesome-free -D`

`npm run serve`

## Package Json -

`{
  "name": "portfolio",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "serve": "vue-cli-service serve",
    "build": "vue-cli-service build",
    "lint": "vue-cli-service lint"
  },
  "dependencies": {
    "@mdi/font": "5.9.55",
    "core-js": "^3.8.3",
    "roboto-fontface": "*",
    "vue": "^3.2.13",
    "vue-router": "^4.0.3",
    "vuetify": "^3.0.0-beta.0",
    "vuex": "^4.0.0",
    "webfontloader": "^1.0.0"
  },
  "devDependencies": {
    "@babel/core": "^7.12.16",
    "@babel/eslint-parser": "^7.12.16",
    "@fortawesome/fontawesome-free": "^6.2.1",
    "@vue/cli-plugin-babel": "~5.0.0",
    "@vue/cli-plugin-eslint": "~5.0.0",
    "@vue/cli-plugin-router": "~5.0.0",
    "@vue/cli-plugin-vuex": "~5.0.0",
    "@vue/cli-service": "~5.0.0",
    "eslint": "^7.32.0",
    "eslint-plugin-vue": "^8.0.3",
    "vue-cli-plugin-vuetify": "~2.5.8",
    "webpack-plugin-vuetify": "^2.0.0-alpha.0"
  },
  "eslintConfig": {
    "root": true,
    "env": {
      "node": true
    },
    "extends": [
      "plugin:vue/vue3-essential",
      "eslint:recommended"
    ],
    "parserOptions": {
      "parser": "@babel/eslint-parser"
    },
    "rules": {}
  },
  "browserslist": [
    "> 1%",
    "last 2 versions",
    "not dead",
    "not ie 11"
  ]
}
`