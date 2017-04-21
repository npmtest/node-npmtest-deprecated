# npmtest-deprecated

#### basic test coverage for  [deprecated (v0.0.1)](http://github.com/wearefractal/deprecated)  [![npm package](https://img.shields.io/npm/v/npmtest-deprecated.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-deprecated) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-deprecated.svg)](https://travis-ci.org/npmtest/node-npmtest-deprecated)

#### Tool for deprecating things

[![NPM](https://nodei.co/npm/deprecated.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/deprecated)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-deprecated/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-deprecated/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-deprecated/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-deprecated/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-deprecated/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-deprecated/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-deprecated/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-deprecated/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-deprecated/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-deprecated/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-deprecated/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-deprecated/build/test-report.html](https://npmtest.github.io/node-npmtest-deprecated/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-deprecated/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-deprecated/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-deprecated/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-deprecated/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deprecated/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deprecated/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-deprecated/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-deprecated/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fractal",
        "url": "http://wearefractal.com/"
    },
    "bugs": {
        "url": "https://github.com/wearefractal/deprecated/issues"
    },
    "dependencies": {},
    "description": "Tool for deprecating things",
    "devDependencies": {
        "coveralls": "~2.6.1",
        "istanbul": "~0.2.3",
        "jshint": "~2.4.1",
        "mocha": "~1.17.0",
        "mocha-lcov-reporter": "~0.0.1",
        "rimraf": "~2.2.5",
        "should": "~3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f9c9af5464afa1e7a971458a8bdef2aa94d5bb19",
        "tarball": "https://registry.npmjs.org/deprecated/-/deprecated-0.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.9"
    },
    "homepage": "http://github.com/wearefractal/deprecated",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/wearefractal/deprecated/raw/master/LICENSE"
        }
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "fractal"
        }
    ],
    "name": "deprecated",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/wearefractal/deprecated.git"
    },
    "scripts": {
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "test": "mocha --reporter spec && jshint"
    },
    "version": "0.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
