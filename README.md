# npmtest-vis

#### basic test coverage for  [vis (v4.19.1)](http://visjs.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-vis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vis.svg)](https://travis-ci.org/npmtest/node-npmtest-vis)

#### A dynamic, browser-based visualization library.

[![NPM](https://nodei.co/npm/vis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vis/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vis/build/test-report.html](https://npmtest.github.io/node-npmtest-vis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "vis",
    "version": "4.19.1",
    "description": "A dynamic, browser-based visualization library.",
    "homepage": "http://visjs.org/",
    "license": "(Apache-2.0 OR MIT)",
    "repository": {
        "type": "git",
        "url": "git://github.com/almende/vis.git"
    },
    "keywords": [
        "vis",
        "visualization",
        "web based",
        "browser based",
        "javascript",
        "chart",
        "linechart",
        "timeline",
        "graph",
        "network",
        "browser"
    ],
    "main": "./dist/vis.js",
    "scripts": {
        "test": "mocha",
        "build": "gulp",
        "lint": "eslint lib",
        "watch": "gulp watch",
        "watch-dev": "gulp watch --bundle"
    },
    "dependencies": {
        "emitter-component": "^1.1.1",
        "moment": "^2.17.1",
        "propagating-hammerjs": "^1.4.6",
        "hammerjs": "^2.0.8",
        "keycharm": "^0.2.0"
    },
    "devDependencies": {
        "async": "^2.1.4",
        "babel-core": "^6.6.5",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.4",
        "babel-polyfill": "^6.22.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.22.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.22.0",
        "babel-preset-es2015": "^6.6.0",
        "babel-runtime": "^6.22.0",
        "babelify": "^7.3.0",
        "clean-css": "^4.0.2",
        "eslint": "^3.15.0",
        "gulp": "^3.9.1",
        "gulp-clean-css": "^2.3.2",
        "gulp-concat": "^2.6.1",
        "gulp-rename": "^1.2.2",
        "gulp-util": "^3.0.8",
        "jsdom": "9.9.1",
        "jsdom-global": "^2.1.1",
        "mocha": "^3.2.0",
        "mocha-jsdom": "^1.1.0",
        "rimraf": "^2.5.4",
        "uglify-js": "^2.7.5",
        "uuid": "^3.0.1",
        "webpack": "^1.14.0",
        "yargs": "^6.6.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
