# npmtest-rx-angular

#### basic test coverage for  [rx-angular (v1.1.3)](https://github.com/Reactive-Extensions/rx.angular.js)  [![npm package](https://img.shields.io/npm/v/npmtest-rx-angular.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rx-angular) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rx-angular.svg)](https://travis-ci.org/npmtest/node-npmtest-rx-angular)

#### Library for bridging between RxJS and AngularJS.

[![NPM](https://nodei.co/npm/rx-angular.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rx-angular)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rx-angular/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rx-angular/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rx-angular/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rx-angular/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rx-angular/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rx-angular/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rx-angular/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rx-angular/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rx-angular/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rx-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rx-angular/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rx-angular/build/test-report.html](https://npmtest.github.io/node-npmtest-rx-angular/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rx-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rx-angular/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rx-angular/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rx-angular/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rx-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rx-angular/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rx-angular/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rx-angular/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "rx-angular",
    "title": "The Reactive Extensions Bindings for the AngularJS.",
    "description": "Library for bridging between RxJS and AngularJS.",
    "version": "1.1.3",
    "homepage": "https://github.com/Reactive-Extensions/rx.angular.js",
    "author": {
        "name": "Microsoft"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Reactive-Extensions/rx.angular.js.git"
    },
    "license": "Apache-2.0",
    "dependencies": {
        "rx": "*"
    },
    "devDependencies": {
        "angular": "^1.4.9",
        "grunt": "*",
        "grunt-cli": "*",
        "grunt-contrib-concat": "*",
        "grunt-contrib-jshint": "*",
        "grunt-contrib-qunit": "*",
        "grunt-contrib-uglify": "*",
        "grunt-ng-annotate": "^0.10.0",
        "load-grunt-tasks": "*",
        "tsd": "^0.6.5"
    },
    "jam": {
        "main": "dist/rx.angular.js"
    },
    "keywords": [
        "Reactive",
        "FRP",
        "Rx",
        "RxJS",
        "AngularJS",
        "Angular"
    ],
    "main": "index.js",
    "scripts": {
        "test": "grunt"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
