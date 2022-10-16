# n’ize.css

<a href="https://github.com/smnscp/n-ize.css"><img
  src="logo.svg" alt="n’ize.css logo"
  width="80" height="80" align="right"></a>

> Add some spice to _normalize_.

[![license][license-image]][license-url]
[![changelog][changelog-image]][changelog-url]

**Download**

Here’s the [raw CSS file](https://raw.githubusercontent.com/smnscp/n-ize.css/main/n’ize.css).

## What does it do?

- Rely on [normalize.css](https://github.com/csstools/normalize.css).
- Add “slots” to inject design tokens on the normalizer layer.
  - Those slots are nothing but references to CSS custom properties (using `var()`).
  - This prevents setting hard-coded “standard” values, e. g. `40px` indent, that are likely to be overwritten, anyways.

## Browser support

Browser that support:

- [CSS custom properties](https://caniuse.com/css-variables),
- [CSS `:is()`](https://caniuse.com/css-matches-pseudo).

[changelog-image]: https://img.shields.io/badge/changelog-md-blue.svg?style=flat-square
[changelog-url]: CHANGELOG.md
[license-image]: https://img.shields.io/badge/license-MIT-green.svg?style=flat-square
[license-url]: LICENSE.md
