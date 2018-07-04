A demonstration of esm+jest bug with console.warn().

Run `npm run test` to see output without errors.

Run `npm run test-esm` to see output with `TypeError: stream.removeListener is not a function.` error.

The bug requires at least two `.test.js` files.
