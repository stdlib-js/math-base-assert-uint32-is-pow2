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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# isPow2Uint32

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test whether an unsigned integer is a power of 2.

<section class="installation">

## Installation

```bash
npm install @stdlib/math-base-assert-uint32-is-pow2
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
var isPow2Uint32 = require( '@stdlib/math-base-assert-uint32-is-pow2' );
```

#### isPow2Uint32( x )

Tests whether `x` is a power of 2.

```javascript
var bool = isPow2Uint32( 2 );
// returns true

bool = isPow2Uint32( 5 );
// returns false
```

</section>

<!-- /.usage -->

<section class="notes">

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var isPow2Uint32 = require( '@stdlib/math-base-assert-uint32-is-pow2' );

var i;

for ( i = 0; i < 100; i++ ) {
    console.log( 'isPow2( %d ) = %s', i, isPow2Uint32( i ) );
}
```

</section>

<!-- /.examples -->

<!-- C interface documentation. -->

* * *

<section class="c">

## C APIs

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- C usage documentation. -->

<section class="usage">

### Usage

```c
#include "stdlib/math/base/assert/uint32_is_pow2.h"
```

#### stdlib_base_uint32_is_pow2( x )

Tests whether an unsigned integer is a power of 2.

```c
#include <stdbool.h>

bool out = stdlib_base_uint32_is_pow2( 5 );
// returns false

out = stdlib_base_uint32_is_pow2( 2 );
// returns true
```

The function accepts the following arguments:

-   **x**: `[in] uint32_t` input value.

```c
bool stdlib_base_uint32_is_pow2( const uint32_t x );
```

</section>

<!-- /.usage -->

<!-- C API usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- C API usage examples. -->

<section class="examples">

### Examples

```c
#include "stdlib/math/base/assert/uint32_is_pow2.h"
#include <stdio.h>
#include <stdbool.h>
#include <stdint.h>

int main( void ) {
    const uint32_t x[] = { 0, 1, 2, 3, 4, 5, 8, 10, 16, 1024 };
    bool b;
    int i;

    for ( i = 0; i < 10; i++ ) {
        b = stdlib_base_uint32_is_pow2( x[ i ] );
        printf( "Value: %u. is a power of 2? %s.\n", x[ i ], ( b ) ? "True" : "False" );
    }
}
```

</section>

<!-- /.examples -->

</section>

<!-- /.c -->

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

[npm-image]: http://img.shields.io/npm/v/@stdlib/math-base-assert-uint32-is-pow2.svg
[npm-url]: https://npmjs.org/package/@stdlib/math-base-assert-uint32-is-pow2

[test-image]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/math-base-assert-uint32-is-pow2/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/math-base-assert-uint32-is-pow2?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/math-base-assert-uint32-is-pow2.svg
[dependencies-url]: https://david-dm.org/stdlib-js/math-base-assert-uint32-is-pow2/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/tree/deno
[deno-readme]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/tree/umd
[umd-readme]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/tree/esm
[esm-readme]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/math-base-assert-uint32-is-pow2/main/LICENSE

</section>

<!-- /.links -->
