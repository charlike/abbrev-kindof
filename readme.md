## [![npm][npmjs-img]][npmjs-url] [![mit license][license-img]][license-url] [![build status][travis-img]][travis-url] [![coverage status][coveralls-img]][coveralls-url] [![deps status][daviddm-img]][daviddm-url]

> `kind-of` with single letter abbreviations to javascript native types, like `kindof(val, 'soa')` will return true if `val` is string, object or array.


## Install
```
npm i --save abbrev-kindof
npm test
```


## Usage
> For more use-cases see the [tests](./test.js)

```js
var abbrevKindof = require('abbrev-kindof');

abbrevKindof(123, 'soa');
//=> false

abbrevKindof(['foo', 'bar'], 'soa');
//=> true

abbrevKindof('foo bar', 'soa');
//=> true

abbrevKindof({foo: 'bar'}, 'soa');
//=> true
```


## Author
**Charlike Mike Reagent**
+ [gratipay/tunnckoCore][author-gratipay]
+ [twitter/tunnckoCore][author-twitter]
+ [github/tunnckoCore][author-github]
+ [npmjs/tunnckoCore][author-npmjs]
+ [more ...][contrib-more]


## License [![MIT license][license-img]][license-url]
Copyright (c) 2015 [Charlike Mike Reagent][contrib-more], [contributors][contrib-graf].  
Released under the [`MIT`][license-url] license.


[npmjs-url]: http://npm.im/abbrev-kindof
[npmjs-img]: https://img.shields.io/npm/v/abbrev-kindof.svg?style=flat&label=abbrev-kindof

[coveralls-url]: https://coveralls.io/r/tunnckoCore/abbrev-kindof?branch=master
[coveralls-img]: https://img.shields.io/coveralls/tunnckoCore/abbrev-kindof.svg?style=flat

[license-url]: https://github.com/tunnckoCore/abbrev-kindof/blob/master/license.md
[license-img]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat

[travis-url]: https://travis-ci.org/tunnckoCore/abbrev-kindof
[travis-img]: https://img.shields.io/travis/tunnckoCore/abbrev-kindof.svg?style=flat

[daviddm-url]: https://david-dm.org/tunnckoCore/abbrev-kindof
[daviddm-img]: https://img.shields.io/david/tunnckoCore/abbrev-kindof.svg?style=flat

[author-gratipay]: https://gratipay.com/tunnckoCore
[author-twitter]: https://twitter.com/tunnckoCore
[author-github]: https://github.com/tunnckoCore
[author-npmjs]: https://npmjs.org/~tunnckocore

[contrib-more]: http://j.mp/1stW47C
[contrib-graf]: https://github.com/tunnckoCore/abbrev-kindof/graphs/contributors

***

_Proudly generated by [docks(1)](https://github.com/tunnckoCore), May 2, 2015_