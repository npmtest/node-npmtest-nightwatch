# test coverage for  [nightwatch (v0.9.14)](http://nightwatchjs.org)  [![npm package](https://img.shields.io/npm/v/npmtest-nightwatch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nightwatch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nightwatch.svg)](https://travis-ci.org/npmtest/node-npmtest-nightwatch)
#### A node.js bindings implementation for selenium 2.0/webdriver

[![NPM](https://nodei.co/npm/nightwatch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nightwatch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nightwatch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nightwatch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nightwatch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nightwatch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nightwatch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nightwatch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nightwatch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nightwatch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nightwatch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nightwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nightwatch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nightwatch/build/test-report.html](https://npmtest.github.io/node-npmtest-nightwatch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nightwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nightwatch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nightwatch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nightwatch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nightwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nightwatch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nightwatch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nightwatch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrei Rusu"
    },
    "bin": {
        "nightwatch": "./bin/nightwatch"
    },
    "bugs": {
        "url": "https://github.com/nightwatchjs/nightwatch/issues"
    },
    "dependencies": {
        "chai-nightwatch": "~0.1.x",
        "ejs": "0.8.3",
        "lodash.clone": "3.0.3",
        "lodash.defaultsdeep": "4.3.2",
        "minimatch": "3.0.3",
        "mkpath": "1.0.0",
        "mocha-nightwatch": "3.2.1",
        "optimist": "0.6.1",
        "proxy-agent": "2.0.0",
        "q": "1.4.1"
    },
    "description": "A node.js bindings implementation for selenium 2.0/webdriver",
    "devDependencies": {
        "chai": "^3.2.0",
        "coveralls": "latest",
        "grunt": "~0.4.4",
        "grunt-complexity": "^0.1.7",
        "grunt-contrib-jshint": "~0.10.0",
        "grunt-jsonlint": "~1.0.4",
        "grunt-npm-release": "latest",
        "jscoverage": "latest",
        "jshint": "~2.4.4",
        "jsonlint": "~1.6.0",
        "mocha": "^2.3.4",
        "mocha-lcov-reporter": "^1.2.0",
        "mock-spawn": "^0.2.1",
        "mockery": "~1.4.0",
        "nock": "~0.45.0"
    },
    "directories": {},
    "dist": {
        "shasum": "897eb2e418b75492c3671e28e8e413abe17cc268",
        "tarball": "https://registry.npmjs.org/nightwatch/-/nightwatch-0.9.14.tgz"
    },
    "files": [
        "bin",
        "examples",
        "lib",
        "README.md",
        "LICENSE.md",
        "index.js"
    ],
    "gitHead": "491b8b89467d9140b473e4f07bae9e62dc369aac",
    "homepage": "http://nightwatchjs.org",
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "beatfactor"
        }
    ],
    "man": "",
    "name": "nightwatch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nightwatchjs/nightwatch.git"
    },
    "scripts": {
        "jshint": "jshint --verbose --config .jshintrc lib/",
        "mocha-coverage": "jscoverage lib --exclude *.ejs,*.json && NIGHTWATCH_COV=1 ./node_modules/.bin/mocha test/src --reporter html-cov > coverage.html",
        "mocha-lcov-coverage": "jscoverage lib --exclude *.ejs,*.json && NIGHTWATCH_COV=1 ./node_modules/.bin/mocha test/src --reporter mocha-lcov-reporter > lib-cov/coverage.lcov",
        "test": "mocha test/src",
        "unit-tests": "./bin/nightwatch -c test/nightwatch.json"
    },
    "version": "0.9.14"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
