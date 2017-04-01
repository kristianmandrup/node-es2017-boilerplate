# My module

[![Greenkeeper badge](https://badges.greenkeeper.io/kristianmandrup/node-es2017-boilerplate.svg)](https://greenkeeper.io/)

## Usage
- install/configure
- run

### Install

- clone this repo
- `npm install` - install dependencies

### Build

`npm run build` - builds `/src` folder and puts resulting ES5 `.js` files in `/dist`

### Auto build

`npm run watch` - builds `/src` and watches for changes to `/src` files for auto-build!

### Troubleshooting

If you still get an error, try removing the `dist` folder:

`rm -r dist`

Then recompile via `build` or `watch` task and start server again.

### Run Test or Test suite

To run the tests, the Koa server app must be running...

`npm test` (runs test command in `Makefile`)

## License

MIT