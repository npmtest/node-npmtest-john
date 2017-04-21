# npmtest-john

#### basic test coverage for  john (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-john.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-john) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-john.svg)](https://travis-ci.org/npmtest/node-npmtest-john)

#### Make npm3's flat dependencies easier to find and sort

[![NPM](https://nodei.co/npm/john.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/john)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-john/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-john/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-john/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-john/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-john/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-john/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-john/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-john/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-john/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-john/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-john/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-john/build/test-report.html](https://npmtest.github.io/node-npmtest-john/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-john/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-john/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-john/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-john/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-john/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-john/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-john/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-john/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "john",
    "version": "1.1.0",
    "description": "Make npm3's flat dependencies easier to find and sort",
    "license": "MIT",
    "os": [
        "darwin",
        "win32"
    ],
    "repository": "davej/john",
    "author": {
        "name": "DaveJ",
        "url": "twitter.com/DaveJ"
    },
    "contributors": [
        {
            "name": "Enzo Martin"
        }
    ],
    "bin": "cli.js",
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "files": [
        "lib",
        "index.js",
        "cli.js"
    ],
    "keywords": [
        "cli-app",
        "cli",
        "npm",
        "npm3",
        "node_modules",
        "flatdeps",
        "osx",
        "tag",
        "tags",
        "color",
        "colour",
        "finder",
        "windows",
        "explorer",
        "mavericks",
        "yosemite",
        "mac"
    ],
    "dependencies": {
        "chalk": "^1.1.1",
        "meow": "^3.6.0",
        "pify": "^2.3.0",
        "read-pkg-up": "^1.0.1"
    },
    "optionalDependencies": {
        "finder-tag": "^1.0.2",
        "fswin": "^2.15.1031"
    },
    "devDependencies": {
        "ava": "^0.11.0",
        "xo": "^0.12.1"
    },
    "xo": {
        "space": 2,
        "rules": {
            "linebreak-style": 0
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
