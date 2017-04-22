# npmtest-ansi-to-html

#### basic test-coverage for  [ansi-to-html (v0.6.0)](https://github.com/rburns/ansi-to-html#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ansi-to-html.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ansi-to-html) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ansi-to-html.svg)](https://travis-ci.org/npmtest/node-npmtest-ansi-to-html)

#### Convert ansi escaped text streams to html.

[![NPM](https://nodei.co/npm/ansi-to-html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ansi-to-html)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ansi-to-html/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ansi-to-html/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ansi-to-html/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ansi-to-html/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ansi-to-html/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ansi-to-html/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ansi-to-html/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ansi-to-html/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ansi-to-html/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ansi-to-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ansi-to-html/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ansi-to-html/build/test-report.html](https://npmtest.github.io/node-npmtest-ansi-to-html/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ansi-to-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ansi-to-html/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ansi-to-html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ansi-to-html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ansi-to-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ansi-to-html/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ansi-to-html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ansi-to-html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rob Burns",
        "url": "http://rburns.paiges.net/"
    },
    "bin": {
        "ansi-to-html": "./bin/ansi-to-html"
    },
    "bugs": {
        "url": "https://github.com/rburns/ansi-to-html/issues"
    },
    "contributors": [
        {
            "name": "Dane Stuckel"
        },
        {
            "name": "Michael"
        },
        {
            "name": "Thorsten Kohnhorst"
        },
        {
            "name": "Yoram Grahame"
        }
    ],
    "dependencies": {
        "entities": "^1.1.1"
    },
    "description": "Convert ansi escaped text streams to html.",
    "devDependencies": {
        "chai": "~3.5.0",
        "eslint": "^3.13.1",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "719a6b5a9c11178fdb7faead28c604ea90cf8eed",
        "tarball": "https://registry.npmjs.org/ansi-to-html/-/ansi-to-html-0.6.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "07a720736ce09e2e9b8557e31e67088516e1ff65",
    "homepage": "https://github.com/rburns/ansi-to-html#readme",
    "keywords": [
        "ansi",
        "html"
    ],
    "license": "MIT",
    "main": "lib/ansi_to_html.js",
    "maintainers": [
        {
            "name": "rburns"
        }
    ],
    "name": "ansi-to-html",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rburns/ansi-to-html.git"
    },
    "scripts": {
        "lint": "./node_modules/eslint/bin/eslint.js lib test",
        "test": "./node_modules/mocha/bin/mocha --reporter tap"
    },
    "version": "0.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
