# entry-hash-webpack-plugin
A webpack plugin to add entry js to index.html

## Installation
```
npm install entry-hash-webpack-plugin --save-dev
```

## Example Webpack Config

``` javascript
var entryHashWebpackPlugin = require('entry-hash-webpack-plugin');

module.exports = {
  plugins: [
    new entryHashWebpackPlugin({isProduction:true, entryName:'__main_entry__'})
  ]
}
```
