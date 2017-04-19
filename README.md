# npmtest-nw-gyp

#### test coverage for  [nw-gyp (v3.4.0)](https://github.com/nwjs/nw-gyp#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nw-gyp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nw-gyp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nw-gyp.svg)](https://travis-ci.org/npmtest/node-npmtest-nw-gyp)

#### NW.js (node-webkit) native addon build tool

[![NPM](https://nodei.co/npm/nw-gyp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nw-gyp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nw-gyp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nw-gyp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nw-gyp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nw-gyp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nw-gyp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nw-gyp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nw-gyp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nw-gyp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nw-gyp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nw-gyp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nw-gyp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nw-gyp/build/test-report.html](https://npmtest.github.io/node-npmtest-nw-gyp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nw-gyp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nw-gyp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nw-gyp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nw-gyp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nw-gyp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nw-gyp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nw-gyp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nw-gyp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roger Wang",
        "url": "based on node-gyp"
    },
    "bin": {
        "nw-gyp": "./bin/nw-gyp.js"
    },
    "bugs": {
        "url": "https://github.com/nwjs/nw-gyp/issues"
    },
    "dependencies": {
        "fstream": "^1.0.0",
        "glob": "^7.0.3",
        "graceful-fs": "^4.1.2",
        "minimatch": "^3.0.2",
        "mkdirp": "^0.5.0",
        "nopt": "2 || 3",
        "npmlog": "0 || 1 || 2 || 3",
        "osenv": "0",
        "path-array": "^1.0.0",
        "request": "2",
        "rimraf": "2",
        "semver": "2.x || 3.x || 4 || 5",
        "tar": "^2.0.0",
        "which": "1"
    },
    "description": "NW.js (node-webkit) native addon build tool",
    "devDependencies": {
        "bindings": "~1.2.1",
        "nan": "^2.0.0",
        "require-inject": "~1.3.0",
        "tape": "~4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "18a9dcdede0ba14225d9c258196b29981f8b6293",
        "tarball": "https://registry.npmjs.org/nw-gyp/-/nw-gyp-3.4.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "c6148610e15c5563a0d0d8e9915d572484e57fa0",
    "homepage": "https://github.com/nwjs/nw-gyp#readme",
    "installVersion": 9,
    "keywords": [
        "native",
        "addon",
        "module",
        "c",
        "c++",
        "bindings",
        "gyp"
    ],
    "license": "MIT",
    "main": "./lib/nw-gyp.js",
    "maintainers": [
        {
            "name": "rogerwang"
        }
    ],
    "name": "nw-gyp",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nwjs/nw-gyp.git"
    },
    "scripts": {
        "test": "tape test/test-*"
    },
    "version": "3.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
