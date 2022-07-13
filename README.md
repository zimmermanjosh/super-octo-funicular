[![GitHub issues](https://img.shields.io/github/issues/zimmermanjosh/super-octo-funicular)](https://github.com/zimmermanjosh/super-octo-funicular/issues)

# super-octo-funicular
the tiniest of tiny npm packages(modules)


Removes all spaces from a string.

## Install

```
$ npm install @joshua.zimmerman/tiny
```

## Usage

```js
const tiny = require("@joshua.zimmerman/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
