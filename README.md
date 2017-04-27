# npmtest-eonasdan-bootstrap-datetimepicker

#### basic test coverage for  [eonasdan-bootstrap-datetimepicker (v4.17.47)](http://eonasdan.github.io/bootstrap-datetimepicker/)  [![npm package](https://img.shields.io/npm/v/npmtest-eonasdan-bootstrap-datetimepicker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eonasdan-bootstrap-datetimepicker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eonasdan-bootstrap-datetimepicker.svg)](https://travis-ci.org/npmtest/node-npmtest-eonasdan-bootstrap-datetimepicker)

#### A date/time picker component designed to work with Bootstrap 3 and Momentjs. For usage, installation and demos see Project Site on GitHub

[![NPM](https://nodei.co/npm/eonasdan-bootstrap-datetimepicker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eonasdan-bootstrap-datetimepicker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eonasdan-bootstrap-datetimepicker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eonasdan-bootstrap-datetimepicker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/test-report.html](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eonasdan-bootstrap-datetimepicker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eonasdan-bootstrap-datetimepicker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eonasdan-bootstrap-datetimepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eonasdan-bootstrap-datetimepicker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eonasdan-bootstrap-datetimepicker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Peterson"
    },
    "bugs": {
        "url": "https://github.com/eonasdan/bootstrap-datetimepicker/issues"
    },
    "dependencies": {
        "bootstrap": "^3.3",
        "jquery": "^1.8.3 || ^2.0 || ^3.0",
        "moment": "^2.10",
        "moment-timezone": "^0.4.0"
    },
    "description": "A date/time picker component designed to work with Bootstrap 3 and Momentjs. For usage, installation and demos see Project Site on GitHub",
    "devDependencies": {
        "grunt": "latest",
        "grunt-contrib-connect": "^1.0.1",
        "grunt-contrib-jasmine": "^1.0.3",
        "grunt-contrib-jshint": "latest",
        "grunt-contrib-less": "latest",
        "grunt-contrib-uglify": "latest",
        "grunt-env": "^0.4.4",
        "grunt-jscs": "latest",
        "grunt-nuget": "^0.1.5",
        "grunt-string-replace": "latest",
        "load-grunt-tasks": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "7a49970044065276e7965efd16f822735219e735",
        "tarball": "https://registry.npmjs.org/eonasdan-bootstrap-datetimepicker/-/eonasdan-bootstrap-datetimepicker-4.17.47.tgz"
    },
    "gitHead": "646299ff633307c0375048efd3169631ba49c0b3",
    "homepage": "http://eonasdan.github.io/bootstrap-datetimepicker/",
    "keywords": [
        "twitter-bootstrap",
        "bootstrap",
        "datepicker",
        "datetimepicker",
        "timepicker",
        "moment"
    ],
    "license": "MIT",
    "main": "src/js/bootstrap-datetimepicker.js",
    "maintainers": [
        {
            "name": "eonasdan"
        }
    ],
    "name": "eonasdan-bootstrap-datetimepicker",
    "optionalDependencies": {},
    "peerDependencies": {
        "bootstrap": "^3.3",
        "jquery": "^1.8.3 || ^2.0 || ^3.0",
        "moment": "^2.10",
        "moment-timezone": "^0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eonasdan/bootstrap-datetimepicker.git"
    },
    "scripts": {},
    "version": "4.17.47",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
