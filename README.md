# npmtest-yeoman

#### basic test coverage for  [yeoman (v0.9.6)](http://yeoman.io)  [![npm package](https://img.shields.io/npm/v/npmtest-yeoman.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yeoman) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yeoman.svg)](https://travis-ci.org/npmtest/node-npmtest-yeoman)

#### The Yeoman CLI is deprecated. See http://yeoman.io/migrate.html for more info.

[![NPM](https://nodei.co/npm/yeoman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yeoman)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yeoman/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yeoman/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yeoman/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yeoman/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yeoman/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yeoman/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yeoman/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yeoman/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yeoman/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yeoman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yeoman/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yeoman/build/test-report.html](https://npmtest.github.io/node-npmtest-yeoman/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yeoman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yeoman/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yeoman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yeoman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yeoman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yeoman/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yeoman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yeoman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yeoman",
    "version": "0.9.6",
    "description": "The Yeoman CLI is deprecated. See http://yeoman.io/migrate.html for more info.",
    "keywords": [
        "front-end",
        "development",
        "dev",
        "build",
        "web",
        "tool",
        "cli",
        "scaffold",
        "stack"
    ],
    "homepage": "http://yeoman.io",
    "bugs": "https://github.com/yeoman/yeoman/issues",
    "author": "Chrome Developer Relations",
    "main": "./yeoman",
    "bin": {
        "yeoman": "./bin/yeoman",
        "_yeomaninsight": "./bin/yeomaninsight.py"
    },
    "directories": {
        "man": "./man"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/yeoman/yeoman.git"
    },
    "scripts": {
        "test": "node node_modules/mocha/bin/mocha test/test-*.js",
        "manpages": "./scripts/docs-build"
    },
    "dependencies": {
        "grunt": "http://github.com/cowboy/grunt/archive/0ba6d4b529.tar.gz",
        "yeoman-generators": "http://github.com/yeoman/generators/archive/0.9.5.tar.gz",
        "bower": "~0.3.0",
        "open": "0.0.2",
        "rimraf": "~2.0.1",
        "mkdirp": "~0.3.1",
        "requirejs": "~2.0.2",
        "clean-css": "~0.3.2",
        "connect": "~2.2.1",
        "request": "~2.9.200",
        "html-minifier": "~0.4.5",
        "which": "~1.0.5",
        "cheerio": "~0.9.2",
        "fstream": "~0.1.18",
        "fstream-ignore": "0.0.5",
        "tar": "~0.1.13",
        "coffee-script": "~1.3.3",
        "grunt-jasmine-task": "~0.2.2",
        "faye-websocket": "~0.4.2",
        "shelljs": "~0.0.6",
        "prompt": "~0.1.12",
        "colors": "~0.6.0",
        "grunt-mocha": "~0.1.3",
        "es6-collections": ">=0.2.0",
        "grunt-contrib-coffee": "~0.3.1"
    },
    "devDependencies": {
        "mocha": "~1.4.0",
        "ronn": "~0.3.8"
    },
    "engines": {
        "node": ">=0.8.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
