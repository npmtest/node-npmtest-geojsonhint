# npmtest-geojsonhint

#### basic test coverage for  geojsonhint (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-geojsonhint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-geojsonhint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-geojsonhint.svg)](https://travis-ci.org/npmtest/node-npmtest-geojsonhint)

#### validate and sanity-check geojson files

[![NPM](https://nodei.co/npm/geojsonhint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/geojsonhint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-geojsonhint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-geojsonhint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-geojsonhint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-geojsonhint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-geojsonhint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-geojsonhint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-geojsonhint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-geojsonhint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-geojsonhint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-geojsonhint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-geojsonhint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-geojsonhint/build/test-report.html](https://npmtest.github.io/node-npmtest-geojsonhint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-geojsonhint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-geojsonhint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-geojsonhint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-geojsonhint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-geojsonhint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-geojsonhint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-geojsonhint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-geojsonhint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "geojsonhint",
    "description": "validate and sanity-check geojson files",
    "version": "2.0.0",
    "author": "Tom MacWright",
    "bin": {
        "geojsonhint": "./bin/geojsonhint"
    },
    "bugs": {
        "url": "https://github.com/mapbox/geojsonhint/issues"
    },
    "files": [
        "geojsonhint.js",
        "bin",
        "lib"
    ],
    "dependencies": {
        "concat-stream": "~1.5.1",
        "jsonlint-lines": "1.7.1",
        "minimist": "1.2.0",
        "vfile": "2.0.0",
        "vfile-reporter": "3.0.0"
    },
    "devDependencies": {
        "benchmark": "^2.1.0",
        "browserify": "13.1.0",
        "eslint": "^3.0.1",
        "fuzzer": "~0.2.0",
        "glob": "~7.0.5",
        "tap": "7.0.0"
    },
    "directories": {
        "test": "test"
    },
    "keywords": [
        "geojson",
        "hint"
    ],
    "license": "ISC",
    "main": "lib/index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/mapbox/geojsonhint.git"
    },
    "scripts": {
        "test": "eslint . && tap test/*.js --coverage",
        "prepublish": "browserify . --standalone geojsonhint > geojsonhint.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
