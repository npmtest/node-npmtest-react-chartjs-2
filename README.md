# npmtest-react-chartjs-2

#### basic test coverage for  [react-chartjs-2 (v2.0.5)](https://github.com/gor181/react-chartjs-2)  [![npm package](https://img.shields.io/npm/v/npmtest-react-chartjs-2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-chartjs-2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-chartjs-2.svg)](https://travis-ci.org/npmtest/node-npmtest-react-chartjs-2)

#### react-chartjs-2

[![NPM](https://nodei.co/npm/react-chartjs-2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-chartjs-2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-chartjs-2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-chartjs-2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-chartjs-2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-chartjs-2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-chartjs-2/build/test-report.html](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-chartjs-2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-chartjs-2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-chartjs-2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-chartjs-2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-chartjs-2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-chartjs-2",
    "version": "2.0.5",
    "description": "react-chartjs-2",
    "main": "lib/index.js",
    "author": "Goran Udosic",
    "homepage": "https://github.com/gor181/react-chartjs-2",
    "repository": {
        "type": "git",
        "url": "https://github.com/gor181/react-chartjs-2.git"
    },
    "bugs": {
        "url": "https://github.com/gor181/react-chartjs-2/issues"
    },
    "dependencies": {
        "lodash.isequal": "^4.4.0"
    },
    "devDependencies": {
        "babel-core": "^6.18.2",
        "babel-eslint": "^4.1.3",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-react": "^6.11.1",
        "babel-preset-stage-1": "^6.13.0",
        "babel-register": "^6.18.0",
        "babelify": "^7.3.0",
        "brfs": "^1.4.3",
        "canvas": "^1.6.2",
        "chai": "^3.5.0",
        "chart.js": "^2.3.0",
        "debug": "^2.4.1",
        "enzyme": "^2.6.0",
        "eslint": "^1.6.0",
        "eslint-plugin-react": "^3.5.1",
        "gulp": "^3.9.0",
        "jsdom": "^9.8.3",
        "mocha": "^3.1.2",
        "react": "^0.14 || ^15.0.0-rc || ^15.0",
        "react-addons-test-utils": "^15.3.2",
        "react-component-gulp-tasks": "git+https://github.com/gor181/react-component-gulp-tasks.git",
        "react-dom": "^0.14 || ^15.0.0-rc || ^15.0",
        "sinon": "^1.17.6"
    },
    "peerDependencies": {
        "chart.js": "^2.3",
        "react": "^0.14 || ^15.0.0-rc || ^15.0",
        "react-dom": "^0.14 || ^15.0.0-rc || ^15.0"
    },
    "browserify-shim": {
        "react": "global:React",
        "react-dom": "global:ReactDOM",
        "chart.js": "global:Chart"
    },
    "scripts": {
        "build": "gulp clean && NODE_ENV=production gulp build",
        "examples": "gulp dev:server",
        "lint": "eslint ./; true",
        "publish:site": "NODE_ENV=production gulp publish:examples",
        "release": "NODE_ENV=production gulp release",
        "start": "gulp dev",
        "test": "mocha test/config/setup.js test/__tests__/**/*",
        "watch": "gulp watch:lib"
    },
    "keywords": [
        "chart",
        "chart-js",
        "chart.js",
        "react-chartjs-2",
        "react chart.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
