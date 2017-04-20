# npmtest-electron-json-storage

#### basic test coverage for  [electron-json-storage (v3.0.5)](https://github.com/jviotti/electron-json-storage)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-json-storage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-json-storage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-json-storage.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-json-storage)

#### Easily write and read user settings in Electron apps

[![NPM](https://nodei.co/npm/electron-json-storage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-json-storage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-json-storage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-json-storage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-json-storage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-json-storage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-json-storage/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-json-storage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-json-storage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-json-storage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-json-storage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-json-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-json-storage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-json-storage/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-json-storage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-json-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-json-storage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-json-storage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-json-storage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-json-storage",
    "version": "3.0.5",
    "description": "Easily write and read user settings in Electron apps",
    "main": "lib/storage.js",
    "homepage": "https://github.com/jviotti/electron-json-storage",
    "repository": {
        "type": "git",
        "url": "git://github.com/jviotti/electron-json-storage.git"
    },
    "directories": {
        "test": "tests"
    },
    "scripts": {
        "test": "electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec",
        "lint": "jshint --config .jshintrc --reporter unix lib tests",
        "readme": "jsdoc2md --template doc/README.hbs lib/storage.js > README.md"
    },
    "keywords": [
        "electron",
        "json",
        "storage",
        "user",
        "app",
        "data"
    ],
    "author": "Juan Cruz Viotti <jviottidc@gmail.com>",
    "license": "MIT",
    "devDependencies": {
        "electron-mocha": "^3.3.0",
        "electron-prebuilt": "^1.2.7",
        "jsdoc-to-markdown": "^2.0.1",
        "jshint": "^2.9.1",
        "mochainon": "^1.0.0",
        "tmp": "0.0.31"
    },
    "dependencies": {
        "async": "^2.0.0",
        "lodash": "^4.0.1",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
