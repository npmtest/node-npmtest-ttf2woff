# npmtest-ttf2woff

#### basic test coverage for  ttf2woff (v2.0.1)  [![npm package](https://img.shields.io/npm/v/npmtest-ttf2woff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ttf2woff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ttf2woff.svg)](https://travis-ci.org/npmtest/node-npmtest-ttf2woff)

#### Convert TTF font to WOFF

[![NPM](https://nodei.co/npm/ttf2woff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ttf2woff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ttf2woff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ttf2woff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ttf2woff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ttf2woff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ttf2woff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ttf2woff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ttf2woff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ttf2woff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ttf2woff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ttf2woff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ttf2woff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ttf2woff/build/test-report.html](https://npmtest.github.io/node-npmtest-ttf2woff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ttf2woff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ttf2woff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ttf2woff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ttf2woff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ttf2woff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ttf2woff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ttf2woff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ttf2woff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ttf2woff",
    "version": "2.0.1",
    "description": "Convert TTF font to WOFF",
    "keywords": [
        "font",
        "ttf",
        "woff",
        "convertor"
    ],
    "author": "Viktor Semykin <thesame.ml@gmail.com>",
    "license": "MIT",
    "repository": "fontello/ttf2woff",
    "bin": {
        "ttf2woff": "./ttf2woff.js"
    },
    "files": [
        "index.js",
        "ttf2woff.js"
    ],
    "scripts": {
        "lint": "./node_modules/.bin/eslint .",
        "test": "npm run lint && ./node_modules/.bin/mocha"
    },
    "dependencies": {
        "argparse": "^1.0.6",
        "microbuffer": "^1.0.0",
        "pako": "^1.0.0"
    },
    "devDependencies": {
        "eslint": "^2.3.0",
        "mocha": "^2.4.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
