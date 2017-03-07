# ascii-whitespace

A [Node.js](https://nodejs.org/) module containing a regular expression for ASCII/HTML whitespace, as defined by W3C and WHATWG.

ASCII whitespace means any combination of U+0009, U+000A, U+000C, U+000D, or U+0020.

## Installation

```bash
npm install ascii-whitespace --save
```

## Usage

```javascript
const asciiWhitespace = require('ascii-whitespace')()

asciiWhitespace instanceof RegExp // true
asciiWhitespace.test(' ') // true
```

## Spec References

[W3C’s definition](https://www.w3.org/TR/html5/infrastructure.html#space-character), from the HTML5 specification (retrieved 2017-03-07):

> The space characters, for the purposes of this specification, are U+0020 SPACE, "tab" (U+0009), "LF" (U+000A), "FF" (U+000C), and "CR" (U+000D).

[WHATWG's definition](https://infra.spec.whatwg.org/#ascii-whitespace) (retrieved 2017-03-07):

> An ASCII whitespace is U+0009, U+000A, U+000C, U+000D, or U+0020.
