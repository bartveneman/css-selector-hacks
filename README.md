# css-selector-hacks

A list of tests to determine whether a selector is a browser hack

## Installation

```bash
npm install css-selector-hacks

# or

yarn add css-selector-hacks
```

## Usage

```js
const isBrowserHack = require('css-selector-hacks')

console.log(isBrowserHack('* html'))
// => true

console.log(isBrowserHack('.my-selector'))
// => false
```

## Related projects

- [CSS Analyzer](https://github.com/projectwallace/css-analyzer) - CSS
  statistics module
- [Wallace CLI](https://github.com/bartveneman/wallace-cli) - CSS statistics in
  your CLI
- [CSS Analyzer Diff](https://github.com/bartveneman/css-analyzer-diff) -
  Calculates the diff between two sets of CSS analysis
- [Color Sorter](https://github.com/bartveneman/color-sorter) - Sort CSS colors
  by hue, saturation, lightness and opacity
- [Gromit CLI](https://github.com/bartveneman/gromit-cli) - A test framework to
  assert that CSS statistics don't exceed certain thresholds.

## License

MIT © Bart Veneman
