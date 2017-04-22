# npmtest-string-format

#### basic test coverage for  [string-format (v0.5.0)](https://github.com/davidchambers/string-format)  [![npm package](https://img.shields.io/npm/v/npmtest-string-format.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-string-format) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-string-format.svg)](https://travis-ci.org/npmtest/node-npmtest-string-format)

#### Adds a `format` method to `String.prototype`. Inspired by Python's `str.format()`.

[![NPM](https://nodei.co/npm/string-format.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/string-format)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-string-format/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-string-format/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-string-format/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-string-format/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-string-format/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-string-format/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-string-format/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-string-format/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-string-format/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-string-format/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-string-format/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-string-format/build/test-report.html](https://npmtest.github.io/node-npmtest-string-format/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-string-format/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-string-format/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-string-format/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-string-format/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-string-format/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-string-format/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-string-format/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-string-format/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Chambers"
    },
    "bugs": {
        "url": "https://github.com/davidchambers/string-format/issues"
    },
    "dependencies": {},
    "description": "Adds a 'format' method to 'String.prototype'. Inspired by Python's 'str.format()'.",
    "devDependencies": {
        "coffee-script": "1.8.x",
        "mocha": "2.x.x",
        "ramda": "0.8.x",
        "xyz": "0.5.x"
    },
    "directories": {},
    "dist": {
        "shasum": "bfc4a69a250f17f273d97336797daf5dca6ecf30",
        "tarball": "https://registry.npmjs.org/string-format/-/string-format-0.5.0.tgz"
    },
    "files": [
        "README.md",
        "lib/string-format.js",
        "package.json"
    ],
    "gitHead": "e98595d385a460edb8fe9bd384fe1af3da307a31",
    "homepage": "https://github.com/davidchambers/string-format",
    "keywords": [
        "string",
        "formatting",
        "language",
        "util"
    ],
    "licenses": [
        {
            "type": "WTFPL",
            "url": "https://raw.github.com/davidchambers/string-format/master/LICENSE"
        }
    ],
    "main": "./lib/string-format",
    "maintainers": [
        {
            "name": "davidchambers"
        }
    ],
    "name": "string-format",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/davidchambers/string-format.git"
    },
    "scripts": {
        "prepublish": "make clean && make",
        "test": "make test"
    },
    "version": "0.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
