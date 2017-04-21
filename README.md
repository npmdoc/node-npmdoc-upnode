# npmdoc-upnode

#### api documentation for  upnode (v0.5.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-upnode.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-upnode) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-upnode.svg)](https://travis-ci.org/npmdoc/node-npmdoc-upnode)

#### transactional connection queue for dnode

[![NPM](https://nodei.co/npm/upnode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/upnode)

- [https://npmdoc.github.io/node-npmdoc-upnode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-upnode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-upnode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-upnode/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-upnode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-upnode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "upnode",
    "description": "transactional connection queue for dnode",
    "version": "0.5.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/upnode.git"
    },
    "main": "index.js",
    "keywords": [
        "dnode",
        "queue",
        "message",
        "reconnect",
        "transaction",
        "interruption"
    ],
    "directories": {
        "example": "example",
        "test": "test"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "dependencies": {
        "dnode": ">= 1.2.2"
    },
    "devDependencies": {
        "tap": "~0.2.6"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "license": "MIT",
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
