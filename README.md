# npmtest-socketio-auth

#### basic test coverage for  [socketio-auth (v0.1.0)](https://github.com/facundoolano/socketio-auth)  [![npm package](https://img.shields.io/npm/v/npmtest-socketio-auth.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-socketio-auth) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-socketio-auth.svg)](https://travis-ci.org/npmtest/node-npmtest-socketio-auth)

#### Authentication for socket.io

[![NPM](https://nodei.co/npm/socketio-auth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/socketio-auth)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-socketio-auth/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-socketio-auth/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-socketio-auth/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-socketio-auth/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-socketio-auth/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-socketio-auth/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-socketio-auth/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-socketio-auth/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-socketio-auth/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-socketio-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-socketio-auth/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-socketio-auth/build/test-report.html](https://npmtest.github.io/node-npmtest-socketio-auth/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-socketio-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-socketio-auth/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-socketio-auth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-socketio-auth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-socketio-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-socketio-auth/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-socketio-auth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-socketio-auth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "socketio-auth",
    "version": "0.1.0",
    "description": "Authentication for socket.io",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "scripts": {
        "jscs": "jscs lib/ test/",
        "jshint": "jshint lib/ test/",
        "lint": "npm run jshint && npm run jscs",
        "pretest": "npm run lint",
        "test": "mocha"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/facundoolano/socketio-auth"
    },
    "keywords": [
        "socket",
        "socket.io",
        "authentication",
        "auth",
        "invisible.js"
    ],
    "author": "Facundo Olano and Martín Paulucci",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/facundoolano/socketio-auth/issues"
    },
    "homepage": "https://github.com/facundoolano/socketio-auth",
    "dependencies": {
        "debug": "^2.1.3",
        "lodash": "^3.8.0"
    },
    "devDependencies": {
        "jscs": "~1.8.0",
        "jshint": "~2.5.10",
        "mocha": "^1.21.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
