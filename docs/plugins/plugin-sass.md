---
translateHelp: true
---
# @umijs/plugin-sass

Enabling `sass` Compilation support。

## Installing
Using npm:

`npm install --save-dev @umijs/plugin-sass`

or using yarn:

`yarn add @umijs/plugin-sass --dev`

## Activation method

Default is `ON`。
## Configuration
### Implementation
Default is [Dart Sass](https://sass-lang.com/dart-sass)。
If you want to switch to [Node Sass](https://github.com/sass/node-sass)，Install `node-sass` dependency and then configure as below.
```js
export default {
  sass: {
    implementation: require('node-sass'),
  },
}
```
### sassOptions
* Type: `Object|Function`
Pass to [Dart Sass](https://github.com/sass/dart-sass#javascript-api) or [Node Sass](https://github.com/sass/node-sass/#options) configuration items。
