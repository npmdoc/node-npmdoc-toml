# npmdoc-toml

#### basic api documentation for  [toml (v2.3.2)](https://github.com/BinaryMuse/toml-node#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-toml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-toml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-toml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-toml)

#### TOML parser for Node.js (parses TOML spec v0.4.0)

[![NPM](https://nodei.co/npm/toml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/toml)

- [https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-toml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-toml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-toml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michelle Tilley"
    },
    "bugs": {
        "url": "https://github.com/BinaryMuse/toml-node/issues"
    },
    "dependencies": {},
    "description": "TOML parser for Node.js (parses TOML spec v0.4.0)",
    "devDependencies": {
        "jshint": "*",
        "nodeunit": "~0.9.0",
        "pegjs": "~0.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5eded5ca42887924949fd06eb0e955656001e834",
        "tarball": "https://registry.npmjs.org/toml/-/toml-2.3.2.tgz"
    },
    "gitHead": "ab4ed8fce1c74ed4cca4b9462d2135d4f21c6772",
    "homepage": "https://github.com/BinaryMuse/toml-node#readme",
    "keywords": [
        "toml",
        "parser"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "binarymuse"
        }
    ],
    "name": "toml",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/BinaryMuse/toml-node.git"
    },
    "scripts": {
        "build": "pegjs --cache src/toml.pegjs lib/parser.js",
        "prepublish": "npm run build",
        "test": "jshint lib/compiler.js && nodeunit test/test_*.js"
    },
    "types": "index.d.ts",
    "version": "2.3.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
