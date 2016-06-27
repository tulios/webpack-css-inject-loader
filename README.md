# Inject CSS loader

webpack.config.js

```js
{
  module: {
    preLoaders: [
      {
        test: /src\/index\.scss/, // the main scss/css file
        loader: 'webpack-inject-css-loader?appPath=./src&debug=false'
      }
    ]
  }
}
```
