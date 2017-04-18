# npmtest-reflux

#### test coverage for  [reflux (v6.4.1)](https://github.com/reflux/refluxjs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-reflux.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-reflux) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-reflux.svg)](https://travis-ci.org/npmtest/node-npmtest-reflux)

#### A simple library for uni-directional dataflow application architecture inspired by ReactJS Flux

[![NPM](https://nodei.co/npm/reflux.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reflux)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-reflux/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-reflux/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-reflux/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-reflux/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-reflux/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-reflux/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-reflux/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-reflux/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-reflux/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-reflux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-reflux/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-reflux/build/test-report.html](https://npmtest.github.io/node-npmtest-reflux/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-reflux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-reflux/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-reflux/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reflux/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reflux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reflux/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-reflux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-reflux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikael Brassman"
    },
    "bugs": {
        "url": "https://github.com/reflux/refluxjs/issues"
    },
    "dependencies": {
        "eventemitter3": "^1.1.1",
        "reflux-core": "^1.0.0"
    },
    "description": "A simple library for uni-directional dataflow application architecture inspired by ReactJS Flux",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "browserify": "~10.2.3",
        "chai": "latest",
        "chai-as-promised": "latest",
        "es6-promise": "^2.3.0",
        "grunt": "^0.4.5",
        "grunt-browserify": "3.8.0",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-jshint": "^0.11.2",
        "grunt-contrib-uglify": "^0.5.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-karma": "latest",
        "grunt-mocha-test": "~0.12.7",
        "karma": "latest",
        "karma-browserify": "latest",
        "karma-commonjs": "latest",
        "karma-mocha": "latest",
        "karma-phantomjs-launcher": "latest",
        "karma-sauce-launcher": "latest",
        "karma-spec-reporter": "latest",
        "matchdep": "^0.3.0",
        "mocha": "latest",
        "q": "^1.0.1",
        "react-dom": "^15.0.2",
        "sinon": "^1.10.3"
    },
    "directories": {},
    "dist": {
        "shasum": "8bbbabaff54cf1b82233d67dd2542fdad2a8d678",
        "tarball": "https://registry.npmjs.org/reflux/-/reflux-6.4.1.tgz"
    },
    "gitHead": "8f40fb8cf45c133af855459d9e425cb744ad77da",
    "homepage": "https://github.com/reflux/refluxjs#readme",
    "keywords": [
        "reflux",
        "react",
        "flux",
        "architecture",
        "dataflow",
        "action",
        "event",
        "data"
    ],
    "license": "BSD-3-Clause",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "bryangrezeszak"
        },
        {
            "name": "devinivy"
        },
        {
            "name": "spoike"
        }
    ],
    "name": "reflux",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0.2"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/reflux/refluxjs.git"
    },
    "scripts": {
        "benchmark": "node test/benchmarks",
        "build": "grunt build",
        "test": "grunt test",
        "test:sauce": "grunt karma:sauce"
    },
    "version": "6.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
