# [`commitlint-config`](https://github.com/arbetsmyra/commitlint-config)

Arbetsmyra's [commitlint config](https://commitlint.js.org/#/concepts-shareable-config)

[![latest git version](https://img.shields.io/github/v/tag/arbetsmyra/commitlint-config?label=version)](https://github.com/arbetsmyra/commitlint-config)
[![latest npm version](https://img.shields.io/npm/v/@arbetsmyra/commitlint-config)](https://www.npmjs.com/package/@arbetsmyra/commitlint-config)
[![license](https://img.shields.io/github/license/arbetsmyra/commitlint-config)](https://github.com/arbetsmyra/commitlint-config/blob/master/LICENSE)

## Installation

### Requirements

- `node` >= v10
- `npm` >= v5

```bash
npm install --save-dev @arbetsmyra/commitlint-config
```

## Usage

Once the `@arbetsmyra/commitlint-config` package is installed, you can use it by specifying the `@arbetsmyra` config for the [`extends`](https://commitlint.js.org/#/reference-configuration?id=shareable-configuration) property in the [commitlint configuration](https://commitlint.js.org/#/reference-configuration?id=shareable-configuration).

`commitlint.config.js`:

```js
module.exports = {
  extends: ['@arbetsmyra'],
};
```

`package.json`:

```json
{
  "commitlint": {
    "extends": ["@arbetsmyra"]
  }
}
```

### Running commitlint with husky

Install husky:

```bash
npm install --save-dev husky
```

Update `package.json` with:

```json
{
  "husky": {
    "hooks": {
      "commit-msg": "commitlint -E HUSKY_GIT_PARAMS"
    }
  }
}
```

## Contributing

If you want to contribute and make our project better, your help is very welcome.

## License

[MIT © Arbetsmyra](https://choosealicense.com/licenses/mit/)
