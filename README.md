# npmtest-passport-ldapauth

#### basic test coverage for  [passport-ldapauth (v1.0.0)](https://github.com/vesse/passport-ldapauth#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-ldapauth.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-ldapauth) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-ldapauth.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-ldapauth)

#### LDAP authentication strategy for Passport

[![NPM](https://nodei.co/npm/passport-ldapauth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-ldapauth)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-ldapauth/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-passport-ldapauth/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-ldapauth/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-ldapauth/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-ldapauth/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-ldapauth/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-ldapauth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-ldapauth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-ldapauth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-ldapauth/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-ldapauth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vesa Poikajärvi"
    },
    "bugs": {
        "url": "https://github.com/vesse/passport-ldapauth/issues"
    },
    "contributors": [
        {
            "name": "Simon Gaeremynck"
        },
        {
            "name": "Michael Bailly"
        },
        {
            "name": "Jason Gelinas"
        },
        {
            "name": "arumi"
        },
        {
            "name": "Anthony Hernandez"
        }
    ],
    "dependencies": {
        "ldapauth-fork": "~3.0.0",
        "passport-strategy": "1.x.x"
    },
    "description": "LDAP authentication strategy for Passport",
    "devDependencies": {
        "basic-auth": "1.1.x",
        "body-parser": "1.15.x",
        "chai": "3.5.x",
        "express": "4.14.x",
        "ldapjs": "1.0.x",
        "mocha": "3.2.x",
        "passport": "0.3.x",
        "supertest": "2.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "bdfd0d87adfee2179284c0e17891b287131e9e74",
        "tarball": "https://registry.npmjs.org/passport-ldapauth/-/passport-ldapauth-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "953a3192d1eb3120f8575977306d19bf150dc489",
    "homepage": "https://github.com/vesse/passport-ldapauth#readme",
    "keywords": [
        "ldap",
        "passport",
        "authentication",
        "ldapauth"
    ],
    "license": "MIT",
    "main": "./lib/passport-ldapauth",
    "maintainers": [
        {
            "name": "vesse"
        }
    ],
    "name": "passport-ldapauth",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vesse/passport-ldapauth.git"
    },
    "scripts": {
        "test": "NODE_PATH=lib mocha --reporter spec test/*-test.js"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
