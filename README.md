# @hutechwebsite/porro-velit-nam-alias <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@hutechwebsite/porro-velit-nam-alias');
const Eval = require('@hutechwebsite/porro-velit-nam-alias/eval');
const Range = require('@hutechwebsite/porro-velit-nam-alias/range');
const Ref = require('@hutechwebsite/porro-velit-nam-alias/ref');
const Syntax = require('@hutechwebsite/porro-velit-nam-alias/syntax');
const Type = require('@hutechwebsite/porro-velit-nam-alias/type');
const URI = require('@hutechwebsite/porro-velit-nam-alias/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@hutechwebsite/porro-velit-nam-alias
[npm-version-svg]: https://versionbadg.es/ljharb/@hutechwebsite/porro-velit-nam-alias.svg
[deps-svg]: https://david-dm.org/ljharb/@hutechwebsite/porro-velit-nam-alias.svg
[deps-url]: https://david-dm.org/ljharb/@hutechwebsite/porro-velit-nam-alias
[dev-deps-svg]: https://david-dm.org/ljharb/@hutechwebsite/porro-velit-nam-alias/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hutechwebsite/porro-velit-nam-alias#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hutechwebsite/porro-velit-nam-alias.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hutechwebsite/porro-velit-nam-alias.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hutechwebsite/porro-velit-nam-alias.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hutechwebsite/porro-velit-nam-alias
[codecov-image]: https://codecov.io/gh/ljharb/@hutechwebsite/porro-velit-nam-alias/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hutechwebsite/porro-velit-nam-alias/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hutechwebsite/porro-velit-nam-alias
[actions-url]: https://github.com/hutechwebsite/porro-velit-nam-alias/actions
