# `Array#lastItem` polyfill for TypeScript

This package includes the [core-js](https://github.com/zloirock/core-js) polyfill for `Array#lastItem`, along with TypeScript typings.

The `lastItem` property is defined in [this TC39 proposal](https://github.com/tc39/proposal-array-last).

## Installation

```sh
npm install --save ts-last-item
```

## Usage

```typescript
import 'ts-last-item'

const list = [1, 2, 3]

console.log(list.lastItem)
//=> 3

list.lastItem = 5
console.log(list)
//=> [ 1, 2, 5 ]
```

## API

The API specification is available in [the TC39 proposal](https://github.com/tc39/proposal-array-last).
