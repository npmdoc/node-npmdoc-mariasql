# api documentation for  [mariasql (v0.2.6)](https://github.com/mscdex/node-mariasql#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mariasql.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mariasql) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mariasql.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mariasql)
#### A node.js binding to MariaDB's non-blocking (MySQL-compatible) client library

[![NPM](https://nodei.co/npm/mariasql.png?downloads=true)](https://www.npmjs.com/package/mariasql)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mariasql/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-mariasql_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mariasql/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mariasql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mariasql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian White",
        "email": "mscdex@mscdex.net"
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
            "name": "mscdex",
            "email": "mscdex@mscdex.net"
        }
    ],
    "name": "mariasql",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mscdex/node-mariasql.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node test/test.js"
    },
    "version": "0.2.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module mariasql](#apidoc.module.mariasql)
1.  [function <span class="apidocSignatureSpan">mariasql.</span>escape ()](#apidoc.element.mariasql.escape)
1.  [function <span class="apidocSignatureSpan">mariasql.</span>super_ ()](#apidoc.element.mariasql.super_)
1.  [function <span class="apidocSignatureSpan">mariasql.</span>version ()](#apidoc.element.mariasql.version)
1.  number <span class="apidocSignatureSpan">mariasql.</span>AUTO_INCREMENT_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>BINARY_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>BLOB_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>ENUM_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>MULTIPLE_KEY_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>NOT_NULL_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>NO_DEFAULT_VALUE_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>NUM_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>ON_UPDATE_NOW_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>PART_KEY_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>PRI_KEY_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>SET_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>TIMESTAMP_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>UNIQUE_KEY_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>UNSIGNED_FLAG
1.  number <span class="apidocSignatureSpan">mariasql.</span>ZEROFILL_FLAG



# <a name="apidoc.module.mariasql"></a>[module mariasql](#apidoc.module.mariasql)

#### <a name="apidoc.element.mariasql.escape"></a>[function <span class="apidocSignatureSpan">mariasql.</span>escape ()](#apidoc.element.mariasql.escape)
- description and source-code
```javascript
escape = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mariasql.super_"></a>[function <span class="apidocSignatureSpan">mariasql.</span>super_ ()](#apidoc.element.mariasql.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mariasql.version"></a>[function <span class="apidocSignatureSpan">mariasql.</span>version ()](#apidoc.element.mariasql.version)
- description and source-code
```javascript
version = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
