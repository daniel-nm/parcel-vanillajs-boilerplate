# **PARCEL - VANILLA JS - BOILERPLATE**

Boilerplate for vanilla JS projects with Parcel.

## *Transpiler*

* Babel

```json
{
  "presets": [
    [
      "@babel/preset-env",
      {
        "useBuiltIns": "entry"
      }
    ]
  ]
}
```

## *Styling*

* PostCSS
  * Autoprefixer

```js
module.exports = {
  plugins: [
    require('autoprefixer')
  ]
};
```

* SCSS


## *Linting*

* ESLint

```json
{
  "env": {
    "browser": true,
    "es6": true
  },
  "extends": ["eslint:recommended", "plugin:prettier/recommended"],
  "globals": {
    "Atomics": "readonly",
    "SharedArrayBuffer": "readonly"
  },
  "parserOptions": {
    "ecmaVersion": 2018,
    "sourceType": "module"
  },
  "rules": {}
}
```

# **HOW TO USE**

To install dependencies

```cmd
npm install
```

Run development mode

```cmd
npm run dev
```

Build app for production
```cmd
npm run buildß
```