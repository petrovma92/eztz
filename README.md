### This is a fork of [eztz](https://github.com/TezTech/eztz), deployed on [npm repository](https://www.npmjs.com/package/eztz-lib)

![npm](https://img.shields.io/npm/v/eztz-lib.svg?logo=npm&color=blue)

#### Getting Started
```js
npm install eztz-lib
```
You can checkout our [Documentation](https://github.com/stephenandrews/eztz/wiki/Documentation), or follow installation below.

## Usage
Import eztz-lib to your project:
```js
import eztz from 'eztz-lib'
```
Now you can use it, for example:
```
eztz.rpc.getBalance("tz1LSAycAVcNdYnXCy18bwVksXci8gUC2YpA").then(function(res) {
    alert("Your balance is " + res);
}).catch(function(e) {
    console.log(e);
});
```

## License
MIT
