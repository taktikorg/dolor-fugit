# @taktikorg/dolor-fugit <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@taktikorg/dolor-fugit');
const Eval = require('@taktikorg/dolor-fugit/eval');
const Range = require('@taktikorg/dolor-fugit/range');
const Ref = require('@taktikorg/dolor-fugit/ref');
const Syntax = require('@taktikorg/dolor-fugit/syntax');
const Type = require('@taktikorg/dolor-fugit/type');
const URI = require('@taktikorg/dolor-fugit/uri');

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

[package-url]: https://npmjs.org/package/@taktikorg/dolor-fugit
[npm-version-svg]: https://versionbadg.es/ljharb/@taktikorg/dolor-fugit.svg
[deps-svg]: https://david-dm.org/ljharb/@taktikorg/dolor-fugit.svg
[deps-url]: https://david-dm.org/ljharb/@taktikorg/dolor-fugit
[dev-deps-svg]: https://david-dm.org/ljharb/@taktikorg/dolor-fugit/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@taktikorg/dolor-fugit#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/dolor-fugit.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/dolor-fugit.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/dolor-fugit.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/dolor-fugit
[codecov-image]: https://codecov.io/gh/ljharb/@taktikorg/dolor-fugit/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@taktikorg/dolor-fugit/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@taktikorg/dolor-fugit
[actions-url]: https://github.com/taktikorg/dolor-fugit/actions
