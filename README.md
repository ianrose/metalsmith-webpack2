**Not maintained. Suggest taking a look at [metalsmith-webpack-suite](https://github.com/axe312ger/metalsmith-webpack-suite) for example of integrating Metalsmith and Webpack.**

# metalsmith-webpack2

A [webpack 2][webpack] plugin for [Metalsmith][metalsmith].

## Installation

```
npm install metalsmith-webpack2
```

## Usage

```js
var webpack = require('metalsmith-webpack2')

Metalsmith(__dirname)
  .use(webpack('./webpack.config.js'))
  .build()
```
## License

MIT License, see [LICENSE](https://github.com/blakeandrewwood/metalsmith-webpack2/blob/master/LICENSE.md) for details.

[metalsmith]: http://www.metalsmith.io/
[webpack]: http://webpack.github.io/
[webpack configuration]: http://webpack.github.io/docs/configuration.html
