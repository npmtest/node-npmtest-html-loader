# npmtest-html-loader

#### basic test coverage for  [html-loader (v0.4.5)](https://github.com/webpack/html-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-html-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-html-loader)

#### html loader module for webpack

[![NPM](https://nodei.co/npm/html-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-html-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bugs": {
        "url": "https://github.com/webpack/html-loader/issues"
    },
    "dependencies": {
        "es6-templates": "^0.2.2",
        "fastparse": "^1.1.1",
        "html-minifier": "^3.0.1",
        "loader-utils": "^1.0.2",
        "object-assign": "^4.1.0"
    },
    "description": "html loader module for webpack",
    "devDependencies": {
        "beautify-lint": "^1.0.4",
        "codecov.io": "^0.1.6",
        "eslint": "^3.1.1",
        "istanbul": "^0.4.4",
        "js-beautify": "^1.6.3",
        "mocha": "^2.5.3",
        "should": "^10.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5fbcd87cd63a5c49a7fce2fe56f425e05729c68c",
        "tarball": "https://registry.npmjs.org/html-loader/-/html-loader-0.4.5.tgz"
    },
    "gitHead": "90c7b60d41a0af76019dbefa91d45dab90fbdd1e",
    "homepage": "https://github.com/webpack/html-loader#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "bebraw"
        },
        {
            "name": "d3viant0ne"
        },
        {
            "name": "ericclemmons"
        },
        {
            "name": "hemanth"
        },
        {
            "name": "jhnns"
        },
        {
            "name": "peerigon"
        },
        {
            "name": "sokra"
        },
        {
            "name": "thelarkinn"
        }
    ],
    "name": "html-loader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/webpack/html-loader.git"
    },
    "scripts": {
        "beautify": "beautify-rewrite lib/**/*.js hot/**/*.js bin/**/*.js benchmark/*.js test/*.js",
        "beautify-lint": "beautify-lint lib/**/*.js hot/**/*.js bin/**/*.js benchmark/*.js test/*.js",
        "cover": "istanbul cover -x *.runtime.js node_modules/mocha/bin/_mocha",
        "lint": "eslint lib bin hot",
        "postcover": "npm run lint && npm run beautify-lint",
        "pretest": "npm run lint && npm run beautify-lint",
        "publish-patch": "npm run lint && npm run beautify-lint && mocha && npm version patch && git push && git push --tags && npm publish",
        "test": "mocha --harmony --full-trace --check-leaks",
        "travis": "npm run cover -- --report lcovonly"
    },
    "version": "0.4.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
