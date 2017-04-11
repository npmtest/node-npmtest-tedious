# test coverage for  [tedious (v2.0.0)](https://github.com/tediousjs/tedious)  [![npm package](https://img.shields.io/npm/v/npmtest-tedious.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tedious) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tedious.svg)](https://travis-ci.org/npmtest/node-npmtest-tedious)
#### A TDS driver, for connecting to MS SQLServer databases.

[![NPM](https://nodei.co/npm/tedious.png?downloads=true)](https://www.npmjs.com/package/tedious)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tedious/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tedious/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tedious/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tedious/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tedious/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tedious/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tedious/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tedious/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-tedious/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-tedious/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-tedious%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tedious/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tedious/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-tedious%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tedious/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tedious/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tedious/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike D Pilsbury",
        "email": "mike.pilsbury@gmail.com"
    },
    "babel": {
        "presets": [
            [
                "env",
                {
                    "targets": {
                        "node": 4
                    }
                }
            ]
        ],
        "plugins": [
            "transform-runtime"
        ]
    },
    "bugs": {
        "url": "https://github.com/tediousjs/tedious/issues"
    },
    "contributors": [
        {
            "name": "Alex Robson"
        },
        {
            "name": "Arthur Schreiber"
        },
        {
            "name": "Bret Copeland",
            "email": "bret@atlantisflight.org",
            "url": "https://github.com/bretcope"
        },
        {
            "name": "Bryan Ross",
            "email": "bryan@rossipedia.com",
            "url": "https://github.com/rossipedia"
        },
        {
            "name": "Ciaran Jessup",
            "email": "ciaranj@gmail.com"
        },
        {
            "name": "Cort Fritz",
            "email": "cfritz@caa.com"
        },
        {
            "name": "lastonesky"
        },
        {
            "name": "Patrik Simek",
            "email": "patrik@patriksimek.cz"
        },
        {
            "name": "Phil Dodderidge",
            "email": "pdodde@poyntz.com"
        },
        {
            "name": "Zach Aller"
        }
    ],
    "dependencies": {
        "babel-runtime": "^6.23.0",
        "big-number": "0.3.1",
        "bl": "^1.2.0",
        "iconv-lite": "^0.4.11",
        "readable-stream": "^2.2.6",
        "sprintf": "0.1.5"
    },
    "description": "A TDS driver, for connecting to MS SQLServer databases.",
    "devDependencies": {
        "async": "^1.4.0",
        "babel-cli": "^6.24.0",
        "babel-plugin-transform-runtime": "^6.23.0",
        "babel-preset-env": "^1.2.2",
        "babel-register": "^6.24.0",
        "benchmark": "^2.1.0",
        "coffee-script": "^1.9.3",
        "eslint": "^3.18.0",
        "mitm": "^1.3.2",
        "nodeunit": "^0.11.0",
        "sinon": "^1.17.5"
    },
    "directories": {},
    "dist": {
        "shasum": "2765e9c8684f62631d85e6a88055ebb82dc8f57d",
        "tarball": "https://registry.npmjs.org/tedious/-/tedious-2.0.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "3609d0bda1971724062a98c9d99353fc66f09da5",
    "homepage": "https://github.com/tediousjs/tedious",
    "keywords": [
        "sql",
        "database",
        "mssql",
        "sqlserver",
        "sql-server",
        "tds",
        "msnodesql",
        "azure"
    ],
    "license": "MIT",
    "main": "./lib/tedious.js",
    "maintainers": [
        {
            "name": "pekim",
            "email": "mike.pilsbury@gmail.com"
        },
        {
            "name": "patriksimek",
            "email": "patrik@patriksimek.cz"
        },
        {
            "name": "bretcope",
            "email": "bret@atlantisflight.org"
        },
        {
            "name": "rossipedia",
            "email": "bryan@rossipedia.com"
        },
        {
            "name": "arthurschreiber",
            "email": "schreiber.arthur@googlemail.com"
        }
    ],
    "name": "tedious",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tediousjs/tedious.git"
    },
    "scripts": {
        "prepublish": "coffee scripts/build.coffee",
        "pretest": "eslint src test",
        "pretest-all": "eslint src test",
        "pretest-integration": "eslint src test",
        "test": "nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer",
        "test-all": "nodeunit --reporter minimal test/setup.js test/unit/ test/unit/token/ test/unit/tracking-buffer test/integration/",
        "test-integration": "nodeunit --reporter minimal test/setup.js test/integration/"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
