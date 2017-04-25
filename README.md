# npmtest-crx

#### basic test coverage for  [crx (v3.2.1)](https://github.com/oncletom/crx)  [![npm package](https://img.shields.io/npm/v/npmtest-crx.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-crx) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-crx.svg)](https://travis-ci.org/npmtest/node-npmtest-crx)

#### crx is a utility to package Google Chrome extensions via a Node API and the command line

[![NPM](https://nodei.co/npm/crx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/crx)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-crx/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-crx/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-crx/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-crx/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-crx/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-crx/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-crx/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-crx/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-crx/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-crx/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-crx/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-crx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-crx/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-crx/build/test-report.html](https://npmtest.github.io/node-npmtest-crx/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-crx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-crx/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-crx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-crx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-crx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-crx/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-crx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-crx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Schmidt",
        "url": "http://jed.is"
    },
    "bin": {
        "crx": "./bin/crx.js"
    },
    "bugs": {
        "url": "https://github.com/oncletom/crx/issues"
    },
    "dependencies": {
        "archiver": "^1.1.0",
        "commander": "^2.5.0",
        "es6-promise": "^3.0.0",
        "node-rsa": "^0.2.10"
    },
    "description": "crx is a utility to package Google Chrome extensions via a Node API and the command line",
    "devDependencies": {
        "adm-zip": "^0.4.7",
        "github-changes": "^1.0.0",
        "nyc": "^8.3.0",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "17293ee75efdd08c6d1c8b3e1749d2d5757cf42b",
        "tarball": "https://registry.npmjs.org/crx/-/crx-3.2.1.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "d65dc24d340078e48f918b2ebff44b580a40291a",
    "homepage": "https://github.com/oncletom/crx",
    "license": "MIT",
    "main": "./src/crx.js",
    "maintainers": [
        {
            "name": "jed"
        },
        {
            "name": "oncletom"
        },
        {
            "name": "joscha"
        }
    ],
    "name": "crx",
    "nyc": {
        "functions": 100,
        "statements": 100,
        "branches": 100,
        "check-coverage": true,
        "reporter": [
            "text",
            "html"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/oncletom/crx.git"
    },
    "scripts": {
        "changelog": "github-changes -o oncletom -r crx -n ${npm_package_version}  --only-pulls --use-commit-body",
        "test": "nyc tape ./test/*.js",
        "version": "npm run changelog && git add CHANGELOG.md"
    },
    "version": "3.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
