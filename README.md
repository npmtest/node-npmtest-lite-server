# test coverage for  [lite-server (v2.3.0)](https://github.com/johnpapa/lite-server#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-lite-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lite-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lite-server.svg)](https://travis-ci.org/npmtest/node-npmtest-lite-server)
#### Lightweight development node server for serving a web app, providing a fallback for browser history API, loading in the browser, and injecting scripts on the fly.

[![NPM](https://nodei.co/npm/lite-server.png?downloads=true)](https://www.npmjs.com/package/lite-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lite-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lite-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lite-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lite-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lite-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lite-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lite-server/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lite-server/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-lite-server/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-lite-server/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-lite-server%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lite-server/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lite-server/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-lite-server%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lite-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lite-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lite-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "lite-server": "./bin/lite-server"
    },
    "bugs": {
        "url": "https://github.com/johnpapa/lite-server/issues"
    },
    "contributors": [
        {
            "name": "John Papa",
            "email": "john@johnpapa.net"
        },
        {
            "name": "Christopher Martin",
            "email": "cgmartin@gmail.com"
        }
    ],
    "dependencies": {
        "browser-sync": "^2.18.5",
        "connect-history-api-fallback": "^1.2.0",
        "connect-logger": "0.0.1",
        "lodash": "^4.11.1",
        "minimist": "1.2.0"
    },
    "description": "Lightweight development node server for serving a web app, providing a fallback for browser history API, loading in the browser, and injecting scripts on the fly.",
    "devDependencies": {
        "eslint": "^2.8.0",
        "istanbul": "^0.4.3",
        "mocha": "^3.2.0",
        "mockery": "^1.6.2",
        "sinon": "^1.17.3"
    },
    "directories": {},
    "dist": {
        "shasum": "5b4cc8f5d5fd4836105480ab2ac48a3a0de2b0c8",
        "tarball": "https://registry.npmjs.org/lite-server/-/lite-server-2.3.0.tgz"
    },
    "gitHead": "9d0a040858e6a1f8f28a899750e1b8f9754d0814",
    "homepage": "https://github.com/johnpapa/lite-server#readme",
    "keywords": [
        "angular",
        "spa",
        "static",
        "server",
        "development"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "johnpapa",
            "email": "john@johnpapa.net"
        }
    ],
    "name": "lite-server",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/johnpapa/lite-server.git"
    },
    "scripts": {
        "test": "eslint *.js lib/*.js && istanbul cover _mocha -- -R spec"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
