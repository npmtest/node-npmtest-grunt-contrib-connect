# test coverage for  [grunt-contrib-connect (v1.0.2)](https://github.com/gruntjs/grunt-contrib-connect#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-contrib-connect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-contrib-connect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-contrib-connect.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-contrib-connect)
#### Start a connect web server

[![NPM](https://nodei.co/npm/grunt-contrib-connect.png?downloads=true)](https://www.npmjs.com/package/grunt-contrib-connect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-contrib-connect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-contrib-connect/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-grunt-contrib-connect%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-contrib-connect/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-grunt-contrib-connect%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-contrib-connect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-contrib-connect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "appveyor_id": "3bp93hbs2rd5lwfd",
    "author": {
        "name": "Grunt Team",
        "url": "http://gruntjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gruntjs/grunt-contrib-connect/issues"
    },
    "contributors": [
        {
            "name": "\"Cowboy\" Ben Alman",
            "url": "http://benalman.com"
        },
        {
            "name": "Tyler Kellen",
            "url": "http://goingslowly.com"
        },
        {
            "name": "Sindre Sorhus",
            "url": "http://sindresorhus.com"
        },
        {
            "name": "Kyle Robinson Young"
        },
        {
            "name": "Jared Stehler"
        },
        {
            "name": "Vlad Filippov"
        },
        {
            "name": "Stepan Stolyarov"
        },
        {
            "name": "Samori Gorse"
        },
        {
            "name": "Nicolas Gryman"
        },
        {
            "name": "Lachèze Alexandre"
        },
        {
            "name": "Jubal Mabaquiao"
        },
        {
            "name": "Eddie Monge Jr"
        },
        {
            "name": "Christopher Joslyn"
        },
        {
            "name": "Ates Goral"
        },
        {
            "name": "Alex Treppass"
        },
        {
            "name": "Aaron Lampros"
        },
        {
            "name": "Philipp Söhnlein"
        }
    ],
    "dependencies": {
        "async": "^1.5.2",
        "connect": "^3.4.0",
        "connect-livereload": "^0.5.0",
        "http2": "^3.3.4",
        "morgan": "^1.6.1",
        "opn": "^4.0.0",
        "portscanner": "^1.0.0",
        "serve-index": "^1.7.1",
        "serve-static": "^1.10.0"
    },
    "description": "Start a connect web server",
    "devDependencies": {
        "grunt": "^1.0.0",
        "grunt-contrib-internal": "^1.1.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5cf933b91a67386044273c0b2444603cd98879ba",
        "tarball": "https://registry.npmjs.org/grunt-contrib-connect/-/grunt-contrib-connect-1.0.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "tasks"
    ],
    "gitHead": "03fa06ecc22a285c1ef458ca2222e85a880051d4",
    "homepage": "https://github.com/gruntjs/grunt-contrib-connect#readme",
    "keywords": [
        "gruntplugin",
        "server",
        "connect",
        "http"
    ],
    "license": "MIT",
    "main": "tasks/connect.js",
    "maintainers": [
        {
            "name": "cowboy",
            "email": "cowboy@rj3.net"
        },
        {
            "name": "tkellen",
            "email": "tyler@sleekcode.net"
        },
        {
            "name": "shama",
            "email": "kyle@dontkry.com"
        },
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "vladikoff",
            "email": "vlad@vladikoff.com"
        },
        {
            "name": "jmeas",
            "email": "jellyes2@gmail.com"
        }
    ],
    "name": "grunt-contrib-connect",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gruntjs/grunt-contrib-connect.git"
    },
    "scripts": {
        "test": "grunt test --verbose"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
