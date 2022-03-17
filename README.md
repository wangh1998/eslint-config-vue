# eslint-config-vue

> eslint-config-vue for

## Install

1. `vue create your-app`

2. Install following dependency:

```json
"@vue/cli-plugin-eslint": "^4.2.0",
"eslint": "^6.7.2",
"eslint-plugin-vue": "^6.1.2",
"babel-eslint": "^10.0.3",
```

3. Install `@yearsy/eslint-config-vue`

```sh
npm install @yearsy/eslint-config-vue --save-dev
```

If using Yarn:

```sh
yarn add @yearsy/eslint-config-vue --dev
```

## Usage

.eslintrc.js

```js
module.exports = {
  root: true,
  env: {
    node: true,
  },
  extends: '@yearsy/eslint-config-vue',
  rules: {},
  parserOptions: {
    parser: 'babel-eslint',
  },
};
```
