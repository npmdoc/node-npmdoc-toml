# npmdoc-toml

#### api documentation for  toml (v2.3.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-toml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-toml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-toml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-toml)

#### TOML parser for Node.js (parses TOML spec v0.4.0)

[![NPM](https://nodei.co/npm/toml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/toml)

- [https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-toml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-toml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-toml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-toml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "toml",
    "version": "2.3.2",
    "description": "TOML parser for Node.js (parses TOML spec v0.4.0)",
    "main": "index.js",
    "types": "index.d.ts",
    "scripts": {
        "build": "pegjs --cache src/toml.pegjs lib/parser.js",
        "test": "jshint lib/compiler.js && nodeunit test/test_*.js",
        "prepublish": "npm run build"
    },
    "repository": "git://github.com/BinaryMuse/toml-node.git",
    "keywords": [
        "toml",
        "parser"
    ],
    "author": "Michelle Tilley <michelle@michelletilley.net>",
    "license": "MIT",
    "devDependencies": {
        "jshint": "*",
        "nodeunit": "~0.9.0",
        "pegjs": "~0.8.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
