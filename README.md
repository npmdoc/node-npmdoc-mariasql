# npmdoc-mariasql

#### basic api documentation for  [mariasql (v0.2.6)](https://github.com/mscdex/node-mariasql#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mariasql.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mariasql) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mariasql.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mariasql)

#### A node.js binding to MariaDB's non-blocking (MySQL-compatible) client library

[![NPM](https://nodei.co/npm/mariasql.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mariasql)

- [https://npmdoc.github.io/node-npmdoc-mariasql/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mariasql/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mariasql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mariasql/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mariasql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mariasql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian White"
    },
    "bugs": {
        "url": "https://github.com/mscdex/node-mariasql/issues"
    },
    "dependencies": {
        "lru-cache": "^2.7.0",
        "nan": "^2.0.9"
    },
    "description": "A node.js binding to MariaDB's non-blocking (MySQL-compatible) client library",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "ab78b0671172f0eaf4e80ddad029b803f35cf77a",
        "tarball": "https://registry.npmjs.org/mariasql/-/mariasql-0.2.6.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gypfile": true,
    "homepage": "https://github.com/mscdex/node-mariasql#readme",
    "keywords": [
        "mysql",
        "sql",
        "client",
        "mariadb",
        "async",
        "nonblocking"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/mscdex/node-mariasql/raw/master/LICENSE"
        }
    ],
    "main": "./lib/Client",
    "maintainers": [
        {
            "name": "mscdex"
        }
    ],
    "name": "mariasql",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mscdex/node-mariasql.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node test/test.js"
    },
    "version": "0.2.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
