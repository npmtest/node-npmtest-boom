# npmtest-boom

#### test coverage for  [boom (v4.3.1)](https://github.com/hapijs/boom#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-boom.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-boom) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-boom.svg)](https://travis-ci.org/npmtest/node-npmtest-boom)

#### HTTP-friendly error objects

[![NPM](https://nodei.co/npm/boom.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/boom)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-boom/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-boom/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-boom/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-boom/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-boom/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-boom/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-boom/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-boom/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-boom/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-boom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-boom/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-boom/build/test-report.html](https://npmtest.github.io/node-npmtest-boom/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-boom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-boom/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-boom/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-boom/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-boom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-boom/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-boom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-boom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/boom/issues"
    },
    "dependencies": {
        "hoek": "4.x.x"
    },
    "description": "HTTP-friendly error objects",
    "devDependencies": {
        "code": "4.x.x",
        "lab": "13.x.x",
        "markdown-toc": "0.12.x"
    },
    "directories": {},
    "dist": {
        "shasum": "4f8a3005cb4a7e3889f749030fd25b96e01d2e31",
        "tarball": "https://registry.npmjs.org/boom/-/boom-4.3.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "3d30c69faf6733a1604b400df71ed4781799a032",
    "homepage": "https://github.com/hapijs/boom#readme",
    "keywords": [
        "error",
        "http"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        },
        {
            "name": "arb"
        }
    ],
    "name": "boom",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/boom.git"
    },
    "scripts": {
        "test": "lab -a code -t 100 -L -v",
        "test-cov-html": "lab -a code -r html -o coverage.html -L",
        "toc": "node generate-toc.js",
        "version": "npm run toc && git add README.md"
    },
    "version": "4.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
