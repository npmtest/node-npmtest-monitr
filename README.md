# npmtest-monitr

#### basic test coverage for  monitr (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-monitr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-monitr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-monitr.svg)](https://travis-ci.org/npmtest/node-npmtest-monitr)

#### Node process monitoring tool

[![NPM](https://nodei.co/npm/monitr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/monitr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-monitr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-monitr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-monitr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-monitr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-monitr/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-monitr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-monitr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-monitr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-monitr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-monitr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-monitr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-monitr/build/test-report.html](https://npmtest.github.io/node-npmtest-monitr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-monitr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-monitr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-monitr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-monitr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-monitr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-monitr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-monitr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-monitr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "monitr",
    "description": "Node process monitoring tool",
    "version": "1.0.0",
    "author": "Rohini Harendra <rohini.raghav@gmail.com>",
    "contributors": [
        {
            "name": "ET"
        }
    ],
    "os": [
        "linux"
    ],
    "cpu": [
        "x64",
        "ia32"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/yahoo/monitr.git"
    },
    "bugs": {
        "url": "http://github.com/yahoo/monitr/issues"
    },
    "keywords": [
        "node-monitoring",
        "node-status"
    ],
    "licenses": [
        {
            "type": "BSD",
            "url": "https://github.com/yahoo/monitr/blob/master/LICENSE"
        }
    ],
    "engines": {
        "node": ">=0.12"
    },
    "dependencies": {
        "bindings": "*",
        "nan": "^2.0.9"
    },
    "devDependencies": {
        "unix-dgram": "~0.2.0",
        "jshint": "*",
        "yui-lint": "~0.2.0",
        "istanbul": "*",
        "vows": "*"
    },
    "main": "./lib/monitor.js",
    "scripts": {
        "pretest": "jshint --config ./node_modules/yui-lint/jshint.json ./lib/",
        "test": "node --expose-gc 'which istanbul' cover --print both vows -- --spec ./tests/*.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
