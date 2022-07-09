<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Hypergeometric

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Hypergeometric distribution.



<section class="usage">

## Usage

To use in Observable,

```javascript
hypergeometric = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-hypergeometric@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var hypergeometric = require( 'path/to/vendor/umd/stats-base-dists-hypergeometric/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-hypergeometric@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
(function () {
    window.hypergeometric;
})();
})();
</script>
```

#### hypergeometric

Hypergeometric distribution.

```javascript
var dist = hypergeometric;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pmf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, N, K, n )`][@stdlib/stats/base/dists/hypergeometric/cdf]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution cumulative distribution function.</span>
-   <span class="signature">[`logpmf( x, N, K, n )`][@stdlib/stats/base/dists/hypergeometric/logpmf]</span><span class="delimiter">: </span><span class="description">evaluate the natural logarithm of the probability mass function (PMF) for a hypergeometric distribution.</span>
-   <span class="signature">[`pmf( x, N, K, n )`][@stdlib/stats/base/dists/hypergeometric/pmf]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution probability mass function (PMF).</span>
-   <span class="signature">[`quantile( p, N, K, n )`][@stdlib/stats/base/dists/hypergeometric/quantile]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`kurtosis( N, K, n )`][@stdlib/stats/base/dists/hypergeometric/kurtosis]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution excess kurtosis.</span>
-   <span class="signature">[`mean( N, K, n )`][@stdlib/stats/base/dists/hypergeometric/mean]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution expected value.</span>
-   <span class="signature">[`mode( N, K, n )`][@stdlib/stats/base/dists/hypergeometric/mode]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution mode.</span>
-   <span class="signature">[`skewness( N, K, n )`][@stdlib/stats/base/dists/hypergeometric/skewness]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution skewness.</span>
-   <span class="signature">[`stdev( N, K, n )`][@stdlib/stats/base/dists/hypergeometric/stdev]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution standard deviation.</span>
-   <span class="signature">[`variance( N, K, n )`][@stdlib/stats/base/dists/hypergeometric/variance]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [hypergeometric][hypergeometric-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`Hypergeometric( N, K, n )`][@stdlib/stats/base/dists/hypergeometric/ctor]</span><span class="delimiter">: </span><span class="description">hypergeometric distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var Hypergeometric = require( '@stdlib/stats-base-dists-hypergeometric' ).Hypergeometric;

var dist = new Hypergeometric( 8, 2, 4 );

var y = dist.cdf( 0.5 );
// returns ~0.214
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-hypergeometric@umd/browser.js"></script>
<script type="text/javascript">
(function () {
(function () {

console.log( objectKeys( hypergeometric ) );

})();
})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-hypergeometric.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-hypergeometric

[test-image]: https://github.com/stdlib-js/stats-base-dists-hypergeometric/actions/workflows/test.yml/badge.svg?branch=v0.0.7
[test-url]: https://github.com/stdlib-js/stats-base-dists-hypergeometric/actions/workflows/test.yml?query=branch:v0.0.7

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-hypergeometric/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-hypergeometric?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-hypergeometric.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-hypergeometric/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-hypergeometric/tree/deno
[umd-url]: https://github.com/stdlib-js/stats-base-dists-hypergeometric/tree/umd
[esm-url]: https://github.com/stdlib-js/stats-base-dists-hypergeometric/tree/esm
[branches-url]: https://github.com/stdlib-js/stats-base-dists-hypergeometric/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-hypergeometric/main/LICENSE

[hypergeometric-distribution]: https://en.wikipedia.org/wiki/Hypergeometric_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/hypergeometric/ctor]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-ctor/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/kurtosis]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-kurtosis/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/mean]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-mean/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/mode]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-mode/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/skewness]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-skewness/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/stdev]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-stdev/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/variance]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-variance/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/cdf]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-cdf/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/logpmf]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-logpmf/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/pmf]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-pmf/tree/umd/tree/umd

[@stdlib/stats/base/dists/hypergeometric/quantile]: https://github.com/stdlib-js/stats-base-dists-hypergeometric-quantile/tree/umd/tree/umd

<!-- </toc-links> -->

</section>

<!-- /.links -->
