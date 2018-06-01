# babel-preset-sxt-engine v1.0.1
Collection of Babel presets and plugins for all the development environments

## Installation

You'll install `babel-preset-sxt-engine`:

```
$ npm install babel-preset-sxt-engine --save-dev
```

## Usage

Add `sxt-engine` to the plugins section of your `.babelrc` configuration file. You can omit the `babel-preset-` prefix:

## For Nodejs

```json
{
    "presets": [
        "sxt-engine"
    ]
}
```

## For flowjs

```json
{
    "presets": [
        "sxt-engine/flow"
    ]
}
```

## For React with transform-runtime

```json
{
    "presets": [
        "sxt-engine/react"
    ]
}
```


## For Webpack with React & transform-runtime & enabled the Tree shaking

```json
{
    "presets": [
        "sxt-engine/reactWebpack"
    ]
}
```

## For Webpack & transform-runtime & enabled the Tree shaking

```json
{
    "presets": [
        "sxt-engine/webpack"
    ]
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)





