# eslint-config-react-nd [![travis][travis-image]][travis-url] [![npm][npm-image]][npm-url] [![downloads][downloads-image]][downloads-url] [![javascript style guide][standard-image]][standard-url]

[travis-image]: https://img.shields.io/travis/feross/eslint-config-standard-react/master.svg
[travis-url]: https://travis-ci.org/feross/eslint-config-standard-react
[npm-image]: https://img.shields.io/npm/v/eslint-config-standard-react.svg
[npm-url]: https://npmjs.org/package/eslint-config-standard-react
[downloads-image]: https://img.shields.io/npm/dm/eslint-config-standard-react.svg
[downloads-url]: https://npmjs.org/package/eslint-config-standard-react
[standard-image]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[standard-url]: https://standardjs.com

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for React/JSX support in [JavaScript Standard Style](https://github.com/feross/standard)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

## Install

This module is for advanced users. You probably want to use [`standard`](https://github.com/feross/standard) instead :)

```bash
npm install eslint-config-react-nd
```

## Usage

add this to your .eslintrc file:

```
{
  "extends": ["react-nd"]
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## License

MIT. Copyright (c) [Feross Aboukhadijeh](http://feross.org).
