# api documentation for  [bleno (v0.4.2)](https://github.com/sandeepmistry/bleno)  [![npm package](https://img.shields.io/npm/v/npmdoc-bleno.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bleno) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bleno.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bleno)
#### A Node.js module for implementing BLE (Bluetooth Low Energy) peripherals

[![NPM](https://nodei.co/npm/bleno.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bleno)

- [https://npmdoc.github.io/node-npmdoc-bleno/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bleno/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bleno/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bleno/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bleno/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bleno/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sandeep Mistry"
    },
    "bugs": {
        "url": "https://github.com/sandeepmistry/bleno/issues"
    },
    "dependencies": {
        "bluetooth-hci-socket": "^0.5.1",
        "bplist-parser": "0.0.6",
        "debug": "^2.2.0",
        "xpc-connection": "~0.1.4"
    },
    "description": "A Node.js module for implementing BLE (Bluetooth Low Energy) peripherals",
    "devDependencies": {
        "jshint": "~2.9.4",
        "mocha": "~1.14.0",
        "node-blink1": "~0.2.2",
        "should": "~2.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "21eb0ad743bce74794e392f4a61e13b07393dbaa",
        "tarball": "https://registry.npmjs.org/bleno/-/bleno-0.4.2.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "fc962259f2577ad77ca4d8e96a00136e4424aebc",
    "homepage": "https://github.com/sandeepmistry/bleno",
    "keywords": [
        "BLE",
        "Bluetooth",
        "Bluetooth Low Energy",
        "Bluetooth Smart",
        "peripheral"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "sandeepmistry"
        }
    ],
    "name": "bleno",
    "optionalDependencies": {
        "bluetooth-hci-socket": "^0.5.1",
        "bplist-parser": "0.0.6",
        "xpc-connection": "~0.1.4"
    },
    "os": [
        "darwin",
        "linux",
        "android",
        "freebsd",
        "win32"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sandeepmistry/bleno.git"
    },
    "scripts": {
        "pretest": "jshint *.js lib/. test/. examples/.",
        "test": "mocha -R spec test/*.js"
    },
    "version": "0.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
