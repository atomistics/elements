# elements

A table of information about the chemical elements. Currently includes symbol, name, mass, radius, number, and a color.

The radius and color are primarily for rendering purposes, and don't have any documented basis.

## Install

```
npm i --save @atomistics/elements
```

## Example

```js
const e = require('@atomistics/elements');

> e.Be

{ symbol: 'Be',
  name: 'beryllium',
  mass: 9.012182,
  radius: 0.96,
  color: [ 0.761, 1, 0 ],
  number: 4 }

> e['Be'].color

[ 0.761, 1, 0 ]

> e[4]

{ symbol: 'Be',
  name: 'beryllium',
  mass: 9.012182,
  radius: 0.96,
  color: [ 0.761, 1, 0 ],
  number: 4 }
```
