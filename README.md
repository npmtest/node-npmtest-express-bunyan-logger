# npmtest-express-bunyan-logger

#### basic test coverage for  [express-bunyan-logger (v1.3.1)](https://github.com/villadora/express-bunyan-logger#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-bunyan-logger.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-bunyan-logger) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-bunyan-logger.svg)](https://travis-ci.org/npmtest/node-npmtest-express-bunyan-logger)

#### a bunyan logger middleware for express

[![NPM](https://nodei.co/npm/express-bunyan-logger.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-bunyan-logger)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-bunyan-logger/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-bunyan-logger/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-bunyan-logger/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-bunyan-logger/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/test-report.html](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-bunyan-logger/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-bunyan-logger/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-bunyan-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-bunyan-logger/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-bunyan-logger/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "wei.gao"
    },
    "bugs": {
        "url": "https://github.com/villadora/express-bunyan-logger/issues"
    },
    "contributors": [
        {
            "name": "Wei Gao"
        },
        {
            "name": "Paris Holley"
        },
        {
            "name": "Ognian Tschakalov"
        },
        {
            "name": "Simon Wade"
        }
    ],
    "dependencies": {
        "bunyan": "^1.8.1",
        "lodash.has": "^4.5.1",
        "lodash.set": "^4.3.1",
        "node-uuid": "^1.4.7",
        "useragent": "^2.1.9"
    },
    "description": "a bunyan logger middleware for express",
    "devDependencies": {
        "body-parser": "^1.15.2",
        "express": "^4.14.0",
        "jshint": "^2.9.2",
        "mocha": "^3.0.1",
        "supertest": "^2.0.0",
        "through2": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "36ee66bbcf580f3085bc6a003f55b8421bbc2460",
        "tarball": "https://registry.npmjs.org/express-bunyan-logger/-/express-bunyan-logger-1.3.1.tgz"
    },
    "gitHead": "629ed821f9fbd64e32a0449ff08281ad5f3aa0ed",
    "homepage": "https://github.com/villadora/express-bunyan-logger#readme",
    "keywords": [
        "express",
        "logger",
        "bunyan"
    ],
    "license": "BSD",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ecoutu"
        },
        {
            "name": "marcbachmann"
        },
        {
            "name": "shutterstock"
        },
        {
            "name": "villadora"
        }
    ],
    "name": "express-bunyan-logger",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/villadora/express-bunyan-logger.git"
    },
    "scripts": {
        "lint": "jshint index.js test/*.js",
        "test": "npm run lint && ./node_modules/.bin/mocha -R spec"
    },
    "version": "1.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
