# node-tiny
the tiniest npm module

Reference: https://medium.freecodecamp.org/how-to-make-a-beautiful-tiny-npm-package-and-publish-it-2881d4307f78

Removes all spaces from a string.

## Install

```
$ npm install @shudongzhang/tiny
```

## Usage

```js
const tiny = require("@shudongzhang/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
