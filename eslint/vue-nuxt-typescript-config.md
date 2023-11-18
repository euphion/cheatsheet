# ESlint config for Vue, Nuxt and Typescript

### ESlint
`yarn add -D eslint`

### Vue 3
`yarn add -D eslint-plugin-vue`

### TypeScript for Vue 3 
`yarn add -D @vue/eslint-config-typescript`

### Nuxt 3
`yarn add -D @nuxtjs/eslint-config`

### TypeScript for Nuxt 3
`yarn add -D @nuxtjs/eslint-config-typescript`

```javascript
// .eslintrc.js

module.exports = {
  env: {
    "browser": true,
    "node": true
  },
  extends: [
    "eslint:recommended",
    "plugin:vue/vue3-recommended",
    "@vue/eslint-config-typescript",
    "@nuxtjs/eslint-config",
    "@nuxtjs/eslint-config-typescript"
  ]
}
```

```
// package.json

"scripts": {
    "eslint:fix": "eslint --fix .",
    "eslint": "eslint ."
}
```
