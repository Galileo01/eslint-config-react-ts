# eslint-config-react-ts

custom ESLint config, for react and ts, depends on airbnb、plugin-react、plugin-prettier and so on

# usage

## install

```bash
npm i @galileo01/eslint-config-react-ts -D
```

## use config

```js
//file .eslintrc.js
{
  ...
  extends: ['@galileo01/eslint-config-react-ts'],
}
```

## recommend

It is recommended to create ”.prettierrc.js“ with the following config content

```js
// file: .prettierrc.js
module.exports = {
  semi: false,
  tabWidth: 2,
  singleQuote: true,
  trailingComma: 'es5',
};
```
