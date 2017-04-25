# npmtest-node-schedule

#### basic test coverage for  [node-schedule (v1.2.1)](https://github.com/node-schedule/node-schedule#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-schedule.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-schedule) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-schedule.svg)](https://travis-ci.org/npmtest/node-npmtest-node-schedule)

#### A cron-like and not-cron-like job scheduler for Node.

[![NPM](https://nodei.co/npm/node-schedule.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-schedule)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-schedule/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-schedule/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-schedule/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-schedule/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-schedule/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-schedule/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-schedule/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-schedule/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-schedule/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-schedule/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-schedule/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-schedule/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-schedule/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-schedule/build/test-report.html](https://npmtest.github.io/node-npmtest-node-schedule/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-schedule/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-schedule/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-schedule/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-schedule/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-schedule/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-schedule/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-schedule/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-schedule/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Patenaude",
        "url": "http://mattpatenaude.com"
    },
    "bugs": {
        "url": "https://github.com/node-schedule/node-schedule/issues"
    },
    "dependencies": {
        "cron-parser": "1.1.0",
        "long-timeout": "0.1.1",
        "sorted-array-functions": "^1.0.0"
    },
    "description": "A cron-like and not-cron-like job scheduler for Node.",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "eslint": "^0.15.1",
        "istanbul": "^0.4.5",
        "nodeunit": "^0.10.2",
        "sinon": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "8800b34d0cceb0ff0318432ef9f20b2499630e36",
        "tarball": "https://registry.npmjs.org/node-schedule/-/node-schedule-1.2.1.tgz"
    },
    "gitHead": "aa45a76109f3968c8f7a2d63363f8b44ce3f493a",
    "homepage": "https://github.com/node-schedule/node-schedule#readme",
    "keywords": [
        "schedule",
        "task",
        "job",
        "cron"
    ],
    "license": "MIT",
    "main": "./lib/schedule.js",
    "maintainers": [
        {
            "name": "mattpat"
        },
        {
            "name": "tejasmanohar"
        },
        {
            "name": "sgimeno"
        },
        {
            "name": "jonhester"
        }
    ],
    "name": "node-schedule",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/node-schedule/node-schedule.git"
    },
    "scripts": {
        "lint": "eslint lib",
        "test": "nodeunit"
    },
    "version": "1.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
