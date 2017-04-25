# npmtest-babel-cli

#### basic test coverage for  [babel-cli (v6.24.1)](https://babeljs.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-cli)

#### Babel command line.

[![NPM](https://nodei.co/npm/babel-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-babel-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-babel-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian McKenzie"
    },
    "bin": {
        "babel-doctor": "./bin/babel-doctor.js",
        "babel": "./bin/babel.js",
        "babel-node": "./bin/babel-node.js",
        "babel-external-helpers": "./bin/babel-external-helpers.js"
    },
    "dependencies": {
        "babel-core": "^6.24.1",
        "babel-polyfill": "^6.23.0",
        "babel-register": "^6.24.1",
        "babel-runtime": "^6.22.0",
        "chokidar": "^1.6.1",
        "commander": "^2.8.1",
        "convert-source-map": "^1.1.0",
        "fs-readdir-recursive": "^1.0.0",
        "glob": "^7.0.0",
        "lodash": "^4.2.0",
        "output-file-sync": "^1.1.0",
        "path-is-absolute": "^1.0.0",
        "slash": "^1.0.0",
        "source-map": "^0.5.0",
        "v8flags": "^2.0.10"
    },
    "description": "Babel command line.",
    "devDependencies": {
        "babel-helper-fixtures": "^6.22.0"
    },
    "directories": {},
    "dist": {
        "shasum": "207cd705bba61489b2ea41b5312341cf6aca2283",
        "tarball": "https://registry.npmjs.org/babel-cli/-/babel-cli-6.24.1.tgz"
    },
    "homepage": "https://babeljs.io/",
    "keywords": [
        "6to5",
        "babel",
        "es6",
        "transpile",
        "transpiler",
        "babel-cli",
        "compiler"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "amasad"
        },
        {
            "name": "hzoo"
        },
        {
            "name": "jmm"
        },
        {
            "name": "loganfsmyth"
        },
        {
            "name": "sebmck"
        },
        {
            "name": "thejameskyle"
        }
    ],
    "name": "babel-cli",
    "optionalDependencies": {
        "chokidar": "^1.6.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/babel/babel/tree/master/packages/babel-cli"
    },
    "scripts": {},
    "version": "6.24.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
