<h1 align="center">TS-Array-Ext</h1>
<p align="center">
Fast <b>&lt;2kB</b> array utility library with a modern API
<br/>
<i>by IT Minds </i>
</p>
<br/>

[![](https://badgen.net/bundlephobia/minzip/ts-array-ext?color=blue)](https://bundlephobia.com/result?p=ts-array-ext)
[![](https://badgen.net/npm/dt/ts-array-ext?color=blue)](https://npm-stat.com/charts.html?package=ts-array-ext)
[![](https://badgen.net/npm/license/ts-array-ext?color=blue)](./LICENSE)
![](https://badgen.net/npm/types/ts-array-ext?color=blue)
[![](https://badgen.net/david/dev/IT-Minds-opensource/ts-array-ext?color=blue)](https://david-dm.org/it-minds-opensource/ts-array-ext?type=dev&view=tree)
[![](https://badgen.net/david/dep/IT-Minds-opensource/ts-array-ext?color=blue)](https://david-dm.org/it-minds-opensource/ts-array-ext)
[![](https://badgen.net/codecov/c/github/IT-Minds-opensource/ts-array-ext/main?color=blue)](https://codecov.io/gh/IT-Minds-opensource/ts-array-ext)

> TS-Array-Ext is a minimalist TypeScript library that provides a few utility functions to the Array prototype class.
> Inspired by LINQ functionality we aim to bring a few easy to use functions that we keep rewriting over and over. No longer. It is time to extend base JavaScript Array functions.

- 🧠 Familiar LINQ operations & patterns
- 💪 Strongly typed
- 🔥 Chainable
- 📦 <2kB mini library
- 👫 Individual imports for optimization
- 💯 100% coverage. No less.

---

## Getting started

### Installation

```sh
npm i ts-array-ext --save
```

Then either import the entire lib:

```typescript
import "ts-array-ext";
```

Or the individual functions.

```typescript
import "ts-array-ext/min";
import "ts-array-ext/sum";
```

Your arrays will have the functions.

```typescript
const totalScore = myArr.sum(x => x.score);
```

### Demo

Checkout [this playground](https://stackblitz.com/edit/ts-array-ext?devtoolsheight=75&file=index.ts) with all examples of usage from below.

---

### API

| function                                         | description                                                            |
| ------------------------------------------------ | ---------------------------------------------------------------------- |
| [average](./src/average/README.md)               | Calculate the average values of an attribute                           |
| [chunkByCount](./src/chunkByCount/README.md)     | Split array into amount of chunks by input                             |
| [chunkBySize](./src/chunkBySize/README.md)       | Split array into amount of chunks by size                              |
| [distinct](./src/distinct/README.md)             | Get distinct elements by attribute                                     |
| [findAndReplace](./src/findAndReplace/README.md) | Find and replace or create value                                       |
| [groupBy](./src/groupBy/README.md)               | Group array into arrays by difference value of attribute               |
| [max](./src/max/README.md)                       | Find the element with the max value of selected attribute              |
| [median](./src/median/README.md)                 | Find the element with the median value of selected attribute           |
| [min](./src/min/README.md)                       | Find the element with the min value of selected attribute              |
| [reduceAsync](./src/reduceAsync/README.md)       | Clean async version of `.reduce`                                       |
| [shuffle](./src/shuffle/README.md)               | Shuffles the array                                                     |
| [sortByAttr](./src/sortByAttr/README.md)         | Sort the array by a selected attribute                                 |
| [sum](./src/sum/README.md)                       | Summation of values of a selected attribute                            |
| [unionSplit](./src/unionSplit/README.md)         | Split the array by a given array and comparator into left/middle/right |
