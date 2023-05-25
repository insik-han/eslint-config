# @insik-han/eslint-config-react

## Installation

```zsh
npm i -D eslint @insik-han/eslint-config-react
```

## Config

```js
// .eslintrc.cjs

/** @type {import('eslint').Linter.BaseConfig} */
const config = {
  extends: [
    // ...
    "@insik-han/react",
  ],
};

module.exports = config;
```
