# npmtest-chairo

#### basic test coverage for  [chairo (v3.0.0)](https://github.com/hapijs/chairo#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-chairo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-chairo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-chairo.svg)](https://travis-ci.org/npmtest/node-npmtest-chairo)

#### Seneca micro-services plugin for hapi

[![NPM](https://nodei.co/npm/chairo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chairo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-chairo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-chairo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-chairo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-chairo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-chairo/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-chairo/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-chairo/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-chairo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-chairo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-chairo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-chairo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-chairo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-chairo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-chairo/build/test-report.html](https://npmtest.github.io/node-npmtest-chairo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-chairo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-chairo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-chairo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chairo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chairo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chairo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-chairo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-chairo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/chairo/issues"
    },
    "dependencies": {
        "boom": "4.x.x",
        "hoek": "4.x.x",
        "items": "2.x.x",
        "joi": "10.x.x",
        "jsonic": "0.2.x",
        "seneca": "3.x.x"
    },
    "description": "Seneca micro-services plugin for hapi",
    "devDependencies": {
        "code": "4.x.x",
        "coveralls": "2.x.x",
        "handlebars": "4.x.x",
        "hapi": "15.x.x",
        "lab": "11.x.x",
        "vision": "4.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "80cf6c1b9906236d95731100ee198775e05695dd",
        "tarball": "https://registry.npmjs.org/chairo/-/chairo-3.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "df6287e609e96bdcb15f162c51933f2ea54ab176",
    "homepage": "https://github.com/hapijs/chairo#readme",
    "keywords": [
        "hapi",
        "plugin",
        "microservices",
        "seneca"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "chairo",
    "optionalDependencies": {},
    "peerDependencies": {
        "hapi": ">=11.x.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/chairo.git"
    },
    "scripts": {
        "cover": "lab -s -r lcov | coveralls",
        "test": "node node_modules/lab/bin/lab -a code -t 100 -L",
        "test-cov-html": "node node_modules/lab/bin/lab -a code -r html -o coverage.html"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
