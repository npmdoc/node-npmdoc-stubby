# npmdoc-stubby

#### basic api documentation for  [stubby (v4.0.0)](http://stub.by)  [![npm package](https://img.shields.io/npm/v/npmdoc-stubby.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stubby) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stubby.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stubby)

#### a lightweight server for stubbing external systems and endpoints

[![NPM](https://nodei.co/npm/stubby.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stubby)

- [https://npmdoc.github.io/node-npmdoc-stubby/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stubby/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stubby/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stubby/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stubby/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stubby/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Mrak"
    },
    "bin": {
        "stubby": "bin/stubby"
    },
    "bugs": {
        "url": "https://github.com/mrak/stubby4node/issues"
    },
    "contributors": [
        {
            "name": "Eric Mrak"
        }
    ],
    "dependencies": {
        "async": ">=0.2.7",
        "ejs": ">=0.8.4",
        "isutf8": ">=1.0.11",
        "js-yaml": ">=1.0.1",
        "node-static": ">=0.6.4"
    },
    "description": "a lightweight server for stubbing external systems and endpoints",
    "devDependencies": {
        "buffer-equal": "^1.0.0",
        "eslint": "^1.2.1",
        "mocha": "^3.1.2",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "455122882133edd4ceb7371a80e0e0fb1ebec929",
        "tarball": "https://registry.npmjs.org/stubby/-/stubby-4.0.0.tgz"
    },
    "engine": {
        "node": ">=0.10"
    },
    "files": [
        "src",
        "package.json",
        "bin",
        "tls",
        "man",
        "webroot"
    ],
    "gitHead": "99c80c236ba55ca7d78268627375f74ebd43a0ac",
    "homepage": "http://stub.by",
    "keywords": [
        "server",
        "stub",
        "mock",
        "testing",
        "service",
        "endpoint",
        "http",
        "https",
        "api",
        "rest"
    ],
    "license": "Apache-2.0",
    "main": "src/main.js",
    "maintainers": [
        {
            "name": "afmrak"
        }
    ],
    "name": "stubby",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mrak/stubby4node.git"
    },
    "scripts": {
        "lint": "eslint src test",
        "start": "bin/stubby",
        "test": "npm run lint && mocha --recursive test --reporter dot"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
