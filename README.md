# @hishprorg/dolore-modi-aspernatur <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@hishprorg/dolore-modi-aspernatur');
const Eval = require('@hishprorg/dolore-modi-aspernatur/eval');
const Range = require('@hishprorg/dolore-modi-aspernatur/range');
const Ref = require('@hishprorg/dolore-modi-aspernatur/ref');
const Syntax = require('@hishprorg/dolore-modi-aspernatur/syntax');
const Type = require('@hishprorg/dolore-modi-aspernatur/type');
const URI = require('@hishprorg/dolore-modi-aspernatur/uri');

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

[package-url]: https://npmjs.org/package/@hishprorg/dolore-modi-aspernatur
[npm-version-svg]: https://versionbadg.es/ljharb/@hishprorg/dolore-modi-aspernatur.svg
[deps-svg]: https://david-dm.org/ljharb/@hishprorg/dolore-modi-aspernatur.svg
[deps-url]: https://david-dm.org/ljharb/@hishprorg/dolore-modi-aspernatur
[dev-deps-svg]: https://david-dm.org/ljharb/@hishprorg/dolore-modi-aspernatur/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hishprorg/dolore-modi-aspernatur#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/dolore-modi-aspernatur.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/dolore-modi-aspernatur.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/dolore-modi-aspernatur.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/dolore-modi-aspernatur
[codecov-image]: https://codecov.io/gh/ljharb/@hishprorg/dolore-modi-aspernatur/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hishprorg/dolore-modi-aspernatur/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hishprorg/dolore-modi-aspernatur
[actions-url]: https://github.com/hishprorg/dolore-modi-aspernatur/actions
