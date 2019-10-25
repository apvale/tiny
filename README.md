@apvale/tiny

![npm (scoped)](https://img.shields.io/npm/v/@apvale/tiny)

Removes all spaces from a string.

# Install

```sh
npm install @apvale/tiny
```

# Usage

```js
const tiny = require("@apvale/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1

```
