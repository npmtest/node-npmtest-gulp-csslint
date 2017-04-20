# npmtest-gulp-csslint

#### basic test coverage for  [gulp-csslint (v1.0.0)](https://github.com/lazd/gulp-csslint#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-csslint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-csslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-csslint.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-csslint)

#### CSSLint plugin for gulp

[![NPM](https://nodei.co/npm/gulp-csslint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-csslint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-csslint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-csslint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-csslint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-csslint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-csslint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-csslint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-csslint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-csslint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-csslint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-csslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-csslint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-csslint/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-csslint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-csslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-csslint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-csslint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-csslint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-csslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-csslint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-csslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-csslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Larry Davis"
    },
    "bugs": {
        "url": "https://github.com/lazd/gulp-csslint/issues"
    },
    "dependencies": {
        "csslint": "^1.0.2",
        "gulp-util": "^3.0.7",
        "rcloader": "^0.2.1",
        "through2": "^2.0.1"
    },
    "description": "CSSLint plugin for gulp",
    "devDependencies": {
        "coveralls": "^2.11.12",
        "csslint-stylish": "0.0.4",
        "eslint": "^3.2.2",
        "eslint-config-semistandard": "^7.0.0-beta.0",
        "eslint-config-standard": "^6.0.0-beta.2",
        "eslint-plugin-promise": "^2.0.1",
        "eslint-plugin-standard": "^2.0.0",
        "mocha": "^3.0.2",
        "node-version-check": "^2.1.0",
        "nyc": "^7.1.0",
        "rimraf": "^2.5.4",
        "should": "^11.0.0",
        "sinon": "^1.17.5"
    },
    "directories": {},
    "dist": {
        "shasum": "d95a56f7719466147fa9a07302fdba1690391523",
        "tarball": "https://registry.npmjs.org/gulp-csslint/-/gulp-csslint-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "371a4ce3825be7cc92e0f2dc789afe48bcfce091",
    "homepage": "https://github.com/lazd/gulp-csslint#readme",
    "keywords": [
        "csslint",
        "gulpplugin"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "lazd"
        }
    ],
    "name": "gulp-csslint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/lazd/gulp-csslint.git"
    },
    "scripts": {
        "clean": "rimraf coverage/ .nyc_output/",
        "cover": "nyc mocha",
        "lint": "node-version-gte-4 && eslint index.js test/main.js || node-version-lt-4",
        "postcover": "nyc report --reporter lcov",
        "precover": "npm run lint && npm run clean",
        "pretest": "npm run lint",
        "test": "mocha"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
