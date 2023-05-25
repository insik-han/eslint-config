# @insik-han/eslint-config-base

## Installation

```zsh
npm i -D eslint @insik-han/eslint-config-base
```

## Config

```js
// .eslintrc.cjs

/** @type {import('eslint').Linter.BaseConfig} */
const config = {
  extends: [
    // ...
    "@insik-han/base",
  ],
};

module.exports = config;
```
