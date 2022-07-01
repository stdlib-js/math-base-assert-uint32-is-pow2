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

# isPow2Uint32

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test whether an unsigned integer is a power of 2.



<section class="usage">

## Usage

```javascript
import isPow2Uint32 from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-uint32-is-pow2@esm/index.mjs';
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

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import isPow2Uint32 from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-assert-uint32-is-pow2@esm/index.mjs';

var i;

for ( i = 0; i < 100; i++ ) {
    console.log( 'isPow2( %d ) = %s', i, isPow2Uint32( i ) );
}

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

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

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
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/tree/deno
[umd-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/tree/umd
[esm-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/tree/esm
[branches-url]: https://github.com/stdlib-js/math-base-assert-uint32-is-pow2/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/math-base-assert-uint32-is-pow2/main/LICENSE

</section>

<!-- /.links -->
