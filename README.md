# api documentation for  [bleno (v0.4.2)](https://github.com/sandeepmistry/bleno)  [![npm package](https://img.shields.io/npm/v/npmdoc-bleno.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bleno) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bleno.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bleno)
#### A Node.js module for implementing BLE (Bluetooth Low Energy) peripherals

[![NPM](https://nodei.co/npm/bleno.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bleno)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bleno/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bleno/build/apidoc.html)

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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module bleno](#apidoc.module.bleno)
1.  number <span class="apidocSignatureSpan">bleno.</span>mtu
1.  number <span class="apidocSignatureSpan">bleno.</span>rssi
1.  object <span class="apidocSignatureSpan">bleno.</span>_bindings
1.  object <span class="apidocSignatureSpan">bleno.</span>_bindings._events
1.  object <span class="apidocSignatureSpan">bleno.</span>_bindings._gatt
1.  string <span class="apidocSignatureSpan">bleno.</span>address
1.  string <span class="apidocSignatureSpan">bleno.</span>platform
1.  string <span class="apidocSignatureSpan">bleno.</span>state

#### [module bleno._bindings](#apidoc.module.bleno._bindings)
1.  boolean <span class="apidocSignatureSpan">bleno._bindings.</span>_advertising
1.  [function <span class="apidocSignatureSpan">bleno._bindings.</span>onSigIntBinded ()](#apidoc.element.bleno._bindings.onSigIntBinded)
1.  number <span class="apidocSignatureSpan">bleno._bindings.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">bleno._bindings.</span>_aclStream
1.  object <span class="apidocSignatureSpan">bleno._bindings.</span>_address
1.  object <span class="apidocSignatureSpan">bleno._bindings.</span>_events
1.  object <span class="apidocSignatureSpan">bleno._bindings.</span>_gap
1.  object <span class="apidocSignatureSpan">bleno._bindings.</span>_gatt
1.  object <span class="apidocSignatureSpan">bleno._bindings.</span>_handle
1.  object <span class="apidocSignatureSpan">bleno._bindings.</span>_hci
1.  string <span class="apidocSignatureSpan">bleno._bindings.</span>_state

#### [module bleno._bindings._events](#apidoc.module.bleno._bindings._events)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>accept ()](#apidoc.element.bleno._bindings._events.accept)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>addressChange ()](#apidoc.element.bleno._bindings._events.addressChange)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>advertisingStart ()](#apidoc.element.bleno._bindings._events.advertisingStart)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>advertisingStop ()](#apidoc.element.bleno._bindings._events.advertisingStop)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>disconnect ()](#apidoc.element.bleno._bindings._events.disconnect)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>mtuChange ()](#apidoc.element.bleno._bindings._events.mtuChange)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>platform ()](#apidoc.element.bleno._bindings._events.platform)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>rssiUpdate ()](#apidoc.element.bleno._bindings._events.rssiUpdate)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>servicesSet ()](#apidoc.element.bleno._bindings._events.servicesSet)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._events.</span>stateChange ()](#apidoc.element.bleno._bindings._events.stateChange)

#### [module bleno._bindings._gatt](#apidoc.module.bleno._bindings._gatt)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>onAclStreamDataBinded ()](#apidoc.element.bleno._bindings._gatt.onAclStreamDataBinded)
1.  [function <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>onAclStreamEndBinded ()](#apidoc.element.bleno._bindings._gatt.onAclStreamEndBinded)
1.  number <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>_eventsCount
1.  number <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>_mtu
1.  number <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>maxMtu
1.  object <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>_events
1.  object <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>_handles
1.  object <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>_preparedWriteRequest



# <a name="apidoc.module.bleno"></a>[module bleno](#apidoc.module.bleno)



# <a name="apidoc.module.bleno._bindings"></a>[module bleno._bindings](#apidoc.module.bleno._bindings)

#### <a name="apidoc.element.bleno._bindings.onSigIntBinded"></a>[function <span class="apidocSignatureSpan">bleno._bindings.</span>onSigIntBinded ()](#apidoc.element.bleno._bindings.onSigIntBinded)
- description and source-code
```javascript
onSigIntBinded = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bleno._bindings._events"></a>[module bleno._bindings._events](#apidoc.module.bleno._bindings._events)

#### <a name="apidoc.element.bleno._bindings._events.accept"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>accept ()](#apidoc.element.bleno._bindings._events.accept)
- description and source-code
```javascript
accept = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.addressChange"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>addressChange ()](#apidoc.element.bleno._bindings._events.addressChange)
- description and source-code
```javascript
addressChange = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.advertisingStart"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>advertisingStart ()](#apidoc.element.bleno._bindings._events.advertisingStart)
- description and source-code
```javascript
advertisingStart = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.advertisingStop"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>advertisingStop ()](#apidoc.element.bleno._bindings._events.advertisingStop)
- description and source-code
```javascript
advertisingStop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.disconnect"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>disconnect ()](#apidoc.element.bleno._bindings._events.disconnect)
- description and source-code
```javascript
disconnect = function () { [native code] }
```
- example usage
```shell
...

bleno.setServices(services[, callback(error)]);
'''

#### Disconnect client

'''javascript
bleno.disconnect(); // Linux only
'''

#### Update RSSI

'''javascript
bleno.updateRssi([callback(error, rssi)]); // not available in OS X 10.9
'''
...
```

#### <a name="apidoc.element.bleno._bindings._events.mtuChange"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>mtuChange ()](#apidoc.element.bleno._bindings._events.mtuChange)
- description and source-code
```javascript
mtuChange = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.platform"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>platform ()](#apidoc.element.bleno._bindings._events.platform)
- description and source-code
```javascript
platform = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.rssiUpdate"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>rssiUpdate ()](#apidoc.element.bleno._bindings._events.rssiUpdate)
- description and source-code
```javascript
rssiUpdate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.servicesSet"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>servicesSet ()](#apidoc.element.bleno._bindings._events.servicesSet)
- description and source-code
```javascript
servicesSet = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._events.stateChange"></a>[function <span class="apidocSignatureSpan">bleno._bindings._events.</span>stateChange ()](#apidoc.element.bleno._bindings._events.stateChange)
- description and source-code
```javascript
stateChange = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bleno._bindings._gatt"></a>[module bleno._bindings._gatt](#apidoc.module.bleno._bindings._gatt)

#### <a name="apidoc.element.bleno._bindings._gatt.onAclStreamDataBinded"></a>[function <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>onAclStreamDataBinded ()](#apidoc.element.bleno._bindings._gatt.onAclStreamDataBinded)
- description and source-code
```javascript
onAclStreamDataBinded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bleno._bindings._gatt.onAclStreamEndBinded"></a>[function <span class="apidocSignatureSpan">bleno._bindings._gatt.</span>onAclStreamEndBinded ()](#apidoc.element.bleno._bindings._gatt.onAclStreamEndBinded)
- description and source-code
```javascript
onAclStreamEndBinded = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
