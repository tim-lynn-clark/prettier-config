# @tim-lynn-clark/prettier-config
> My personal [Prettier](https://prettier.io/docs/en/configuration.html) config

## Usage

### Install:

```bash
$ npm install @schleichermann/prettier-config --save-dev
```

```bash
$ yarn add --dev @schleichermann/prettier-config
```

### Config Setup:

Two options for setup in your project.

**Option 1: Edit `package.json`**

```jsonc
{
  // ...
  "prettier": "@schleichermann/prettier-config"
}
```

**Option 2: Edit `.prettierrc.js`**

```javascript
module.exports = {
  ...require("@schleichermann/prettier-config"),
  semi: false,
};
```