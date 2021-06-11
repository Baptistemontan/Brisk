# @xerafiu/brisk

> A library to gain time while developing in Javascript
[![NPM Version][npm-image]][npm-url]

## Install

```bash
npm i @xerafiu/brisk
```

## Usage

This tool has a kernel making it possible to load the different functions of the different categories which allows the community of developers to participate easily in improving this tool.

The structure is :
  - category (folder)
    - subcategory (file)
      - functions (code)

```js
const Brisk = require("@xerafiu/brisk")
//Access Math basic functions via the "math" category and the "basic" subcategory
let result = Brisk.Math.Basic.add(3, 6)

console.log(`The result of the addition is ${result} !`)

//You can directly access to a category like this :
const { Math } = require("@xerafiu/brisk")
```

While waiting for me to do some documentation, you can display the list of categories and subcategories like this :
```js
const brisk = require("@xerafiu/brisk")

```

## License

[MIT](http://vjpr.mit-license.org)

[npm-image]: https://img.shields.io/npm/v/live-xxx.svg
[npm-url]: https://www.npmjs.com/package/@xerafiu/brisk

