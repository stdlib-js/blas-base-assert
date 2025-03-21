<!--

@license Apache-2.0

Copyright (c) 2024 The Stdlib Authors.

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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Assert

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Base BLAS assertion utilities.

<section class="installation">

## Installation

```bash
npm install @stdlib/blas-base-assert
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var ns = require( '@stdlib/blas-base-assert' );
```

#### ns

Base BLAS assertion utilities.

```javascript
var o = ns;
// returns {...}
```

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`isDiagonalType( value )`][@stdlib/blas/base/assert/is-diagonal-type]</span><span class="delimiter">: </span><span class="description">test if an input value is a BLAS diagonal type.</span>
-   <span class="signature">[`isLayout( value )`][@stdlib/blas/base/assert/is-layout]</span><span class="delimiter">: </span><span class="description">test if an input value is a BLAS memory layout.</span>
-   <span class="signature">[`isMatrixTriangle( value )`][@stdlib/blas/base/assert/is-matrix-triangle]</span><span class="delimiter">: </span><span class="description">test if an input value is a BLAS matrix triangle.</span>
-   <span class="signature">[`isOperationSide( value )`][@stdlib/blas/base/assert/is-operation-side]</span><span class="delimiter">: </span><span class="description">test if an input value is a BLAS operation side.</span>
-   <span class="signature">[`isTransposeOperation( value )`][@stdlib/blas/base/assert/is-transpose-operation]</span><span class="delimiter">: </span><span class="description">test if an input value is a BLAS transpose operation.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var ns = require( '@stdlib/blas-base-assert' );

console.log( objectKeys( ns ) );
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

Copyright &copy; 2016-2025. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/blas-base-assert.svg
[npm-url]: https://npmjs.org/package/@stdlib/blas-base-assert

[test-image]: https://github.com/stdlib-js/blas-base-assert/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/blas-base-assert/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/blas-base-assert/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/blas-base-assert?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/blas-base-assert.svg
[dependencies-url]: https://david-dm.org/stdlib-js/blas-base-assert/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/blas-base-assert/tree/deno
[deno-readme]: https://github.com/stdlib-js/blas-base-assert/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/blas-base-assert/tree/umd
[umd-readme]: https://github.com/stdlib-js/blas-base-assert/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/blas-base-assert/tree/esm
[esm-readme]: https://github.com/stdlib-js/blas-base-assert/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/blas-base-assert/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/blas-base-assert/main/LICENSE

<!-- <toc-links> -->

[@stdlib/blas/base/assert/is-diagonal-type]: https://github.com/stdlib-js/blas-base-assert-is-diagonal-type

[@stdlib/blas/base/assert/is-layout]: https://github.com/stdlib-js/blas-base-assert-is-layout

[@stdlib/blas/base/assert/is-matrix-triangle]: https://github.com/stdlib-js/blas-base-assert-is-matrix-triangle

[@stdlib/blas/base/assert/is-operation-side]: https://github.com/stdlib-js/blas-base-assert-is-operation-side

[@stdlib/blas/base/assert/is-transpose-operation]: https://github.com/stdlib-js/blas-base-assert-is-transpose-operation

<!-- </toc-links> -->

</section>

<!-- /.links -->
