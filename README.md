# @devtea2027/doloribus-molestias-deleniti-dolore [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Meet%20this%20awesome%20library&url=https://github.com/devtea2027/doloribus-molestias-deleniti-dolore&via=nicolasvanhoren&hashtags=javascript,asyncawait,async,libraries,programming)

![logo](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/raw/master/img/facebook_cover_photo_2_680.png)

[![GitHub Repo stars](https://img.shields.io/github/stars/nicolas-van/@devtea2027/doloribus-molestias-deleniti-dolore?style=social)](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/stargazers) [![Website](https://img.shields.io/website.svg?url=http%3A%2F%2Fnicolas-van.github.io%2F@devtea2027/doloribus-molestias-deleniti-dolore)](https://nicolas-van.github.io/@devtea2027/doloribus-molestias-deleniti-dolore)
[![Node.js CI](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/workflows/Node.js%20CI/badge.svg)](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/actions) [![npm](https://img.shields.io/npm/v/@devtea2027/doloribus-molestias-deleniti-dolore)](https://www.npmjs.com/package/@devtea2027/doloribus-molestias-deleniti-dolore) [![Coverage Status](https://coveralls.io/repos/github/nicolas-van/@devtea2027/doloribus-molestias-deleniti-dolore/badge.svg?branch=master)](https://coveralls.io/github/nicolas-van/@devtea2027/doloribus-molestias-deleniti-dolore?branch=master) [![](https://data.jsdelivr.com/v1/package/npm/@devtea2027/doloribus-molestias-deleniti-dolore/badge)](https://www.jsdelivr.com/package/npm/@devtea2027/doloribus-molestias-deleniti-dolore)

A modern JavaScript tooling library for asynchronous operations using async/await, promises and async generators.

This library is a modernized alternative to a lot of libraries like [Async.js](https://caolan.github.io/async/v3/) that were created using the legacy callback style to handle asynchronous operations. Its goal is to be as complete as any of those libraries while being built from the very beginning with async/await and promises in mind.

[See the documentation](https://nicolas-van.github.io/@devtea2027/doloribus-molestias-deleniti-dolore).

* Exclusively uses async/await, promises and async generators in its code, tests and documentation.
* Has low bundle size.
* Has 100% code coverage.
* Bundled for ESM modules, CommonJS and UMD.
* Works in node >= 8 and in the vast majority of browsers (very old browser compatibility can be achieved using Babel and shims).
* Has Typescript support.

[![Stargazers repo roster for @nicolas-van/@devtea2027/doloribus-molestias-deleniti-dolore](https://reporoster.com/stars/nicolas-van/@devtea2027/doloribus-molestias-deleniti-dolore)](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/stargazers)

## Installation

```bash
npm install --save @devtea2027/doloribus-molestias-deleniti-dolore
```

Or use [jsDelivr](https://www.jsdelivr.com/package/npm/@devtea2027/doloribus-molestias-deleniti-dolore) to get the UMD version. The content of the library will be available under the `modernAsync` global variable.

## Usage

```javascript
import { asyncMap, asyncSleep } from '@devtea2027/doloribus-molestias-deleniti-dolore'

const array = [1, 2, 3]
const result = await asyncMap(array, async (v) => {
  await asyncSleep(10)
  return v * 2
})
console.log(result)
```

[See the documentation for the rest](https://nicolas-van.github.io/@devtea2027/doloribus-molestias-deleniti-dolore).

## Migrating from version 1.X to version 2.X

[See the migration guide](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/blob/master/version-1-to-2-guide.md).

## Changelog

[The changelog](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/blob/master/CHANGELOG.md).

## Contribution Guide

[The contribution guide](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/blob/master/CONTRIBUTING.md)

## License

[The license](https://github.com/devtea2027/doloribus-molestias-deleniti-dolore/blob/master/LICENSE.md).
