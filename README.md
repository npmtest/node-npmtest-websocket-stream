# test coverage for  [websocket-stream (v4.0.0)](https://github.com/maxogden/websocket-stream#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-websocket-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-websocket-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-websocket-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-websocket-stream)
#### Use websockets with the node streams API. Works in browser and node

[![NPM](https://nodei.co/npm/websocket-stream.png?downloads=true)](https://www.npmjs.com/package/websocket-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-websocket-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-websocket-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-websocket-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-websocket-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-websocket-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-websocket-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-websocket-stream/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-websocket-stream/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-websocket-stream/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-websocket-stream/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-websocket-stream%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-websocket-stream/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-websocket-stream/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-websocket-stream%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-websocket-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-websocket-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-websocket-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "browser": {
        "./echo-server.js": "./fake-server.js",
        "./index.js": "./stream.js",
        "ws": "./ws-fallback.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/websocket-stream/issues"
    },
    "dependencies": {
        "duplexify": "^3.2.0",
        "inherits": "^2.0.1",
        "readable-stream": "^2.2.0",
        "safe-buffer": "^5.0.1",
        "ws": "^2.2.3",
        "xtend": "^4.0.0"
    },
    "description": "Use websockets with the node streams API. Works in browser and node",
    "devDependencies": {
        "beefy": "^2.1.1",
        "browserify": "^14.0.0",
        "concat-stream": "^1.4.7",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "358386cab1b0070e17b32b437f74f1bc19e13890",
        "tarball": "https://registry.npmjs.org/websocket-stream/-/websocket-stream-4.0.0.tgz"
    },
    "gitHead": "a2c72276413461d68f2b5b2d66a6f72bf16ae0c6",
    "homepage": "https://github.com/maxogden/websocket-stream#readme",
    "keywords": [
        "websocket",
        "websockets",
        "stream",
        "streams",
        "realtime"
    ],
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "deanlandolt",
            "email": "dean@deanlandolt.com"
        },
        {
            "name": "jnordberg",
            "email": "code@johan-nordberg.com"
        },
        {
            "name": "mafintosh",
            "email": "mathiasbuus@gmail.com"
        },
        {
            "name": "matteo.collina",
            "email": "hello@matteocollina.com"
        },
        {
            "name": "maxogden",
            "email": "max@maxogden.com"
        }
    ],
    "name": "websocket-stream",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/maxogden/websocket-stream.git"
    },
    "scripts": {
        "start": "beefy test-client.js",
        "test": "node test.js"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
