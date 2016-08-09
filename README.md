#FORE MORE INFORMATION, PLEASE VISIT
[babel-plugin-ui5](https://github.com/MagicCube/babel-plugin-ui5)


# babel-preset-ui5
An UNOFFICIAL preset for building SAP UI5 application with Babel.



## Document
Please take a look at [https://github.com/MagicCube/babel-plugin-ui5](https://github.com/MagicCube/babel-plugin-ui5)

## Install

```sh
$ npm install --save-dev babel-preset-ui5
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["ui5"]
}
```

### Via CLI

```sh
$ babel script.js --presets ui5
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["ui5"]
});
```
