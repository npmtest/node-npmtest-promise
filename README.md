# npmtest-promise

#### test coverage for  [promise (v7.1.1)](https://github.com/then/promise)  [![npm package](https://img.shields.io/npm/v/npmtest-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-promise.svg)](https://travis-ci.org/npmtest/node-npmtest-promise)

#### Bare bones Promises/A+ implementation

[![NPM](https://nodei.co/npm/promise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/promise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-promise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-promise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-promise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-promise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-promise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-promise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-promise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-promise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-promise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-promise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-promise/build/test-report.html](https://npmtest.github.io/node-npmtest-promise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-promise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-promise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-promise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-promise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ForbesLindesay"
    },
    "bugs": {
        "url": "https://github.com/then/promise/issues"
    },
    "dependencies": {
        "asap": "~2.0.3"
    },
    "description": "Bare bones Promises/A+ implementation",
    "devDependencies": {
        "acorn": "^1.0.1",
        "better-assert": "*",
        "istanbul": "^0.3.13",
        "mocha": "*",
        "promises-aplus-tests": "*",
        "rimraf": "^2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "489654c692616b8aa55b0724fa809bb7db49c5bf",
        "tarball": "https://registry.npmjs.org/promise/-/promise-7.1.1.tgz"
    },
    "gitHead": "90757a38c86975f36893012581b72315b352d482",
    "homepage": "https://github.com/then/promise",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "forbeslindesay"
        },
        {
            "name": "nathan7"
        }
    ],
    "name": "promise",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/then/promise.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/mocha/bin/_mocha -- --bail --timeout 200 --slow 99999 -R dot",
        "prepublish": "node build",
        "pretest": "node build",
        "pretest-extensions": "node build",
        "pretest-memory-leak": "node build",
        "pretest-resolve": "node build",
        "test": "mocha --bail --timeout 200 --slow 99999 -R dot && npm run test-memory-leak",
        "test-extensions": "mocha test/extensions-tests.js --timeout 200 --slow 999999",
        "test-memory-leak": "node --expose-gc test/memory-leak.js",
        "test-resolve": "mocha test/resolver-tests.js --timeout 200 --slow 999999"
    },
    "version": "7.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
