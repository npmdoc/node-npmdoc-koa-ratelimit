# npmdoc-koa-ratelimit

#### api documentation for  koa-ratelimit (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-ratelimit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-ratelimit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-ratelimit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-ratelimit)

#### Rate limiter middleware for koa

[![NPM](https://nodei.co/npm/koa-ratelimit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-ratelimit)

- [https://npmdoc.github.io/node-npmdoc-koa-ratelimit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-ratelimit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-ratelimit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-ratelimit/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-ratelimit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-ratelimit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-ratelimit",
    "description": "Rate limiter middleware for koa",
    "repository": "koajs/ratelimit",
    "version": "4.0.0",
    "keywords": [
        "koa",
        "middleware",
        "ratelimiter",
        "ratelimit",
        "rate"
    ],
    "files": [
        "index.js"
    ],
    "dependencies": {
        "debug": "^2.2.0",
        "ms": "^0.7.1",
        "ratelimiter": "^3.0.2",
        "thenify": "^3.2.0"
    },
    "devDependencies": {
        "koa": "^2.0.1",
        "mocha": "^3.2.0",
        "ioredis": "^3.0.0-0",
        "should": "^11.2.0",
        "supertest": "^3.0.0"
    },
    "scripts": {
        "test": "NODE_ENV=test mocha --reporter spec"
    },
    "engines": {
        "node": ">= 7"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
