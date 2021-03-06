# npmdoc-yuidocjs

#### basic api documentation for  [yuidocjs (v0.10.2)](https://github.com/yui/yuidoc#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-yuidocjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yuidocjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yuidocjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yuidocjs)

#### YUIDoc, YUI's JavaScript Documentation engine.

[![NPM](https://nodei.co/npm/yuidocjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yuidocjs)

- [https://npmdoc.github.io/node-npmdoc-yuidocjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yuidocjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yuidocjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yuidocjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yuidocjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yuidocjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dav Glass"
    },
    "bin": {
        "yuidoc": "./lib/cli.js"
    },
    "bugs": {
        "url": "http://github.com/yui/yuidoc/issues"
    },
    "contributors": [
        {
            "name": "Adam Moore"
        },
        {
            "name": "Ryan Grove"
        },
        {
            "name": "Eric Ferraiuolo"
        },
        {
            "name": "Felipe Gasper"
        },
        {
            "name": "Evan Goer"
        },
        {
            "name": "Alberto Gragera"
        },
        {
            "name": "Pat Cavit"
        },
        {
            "name": "Kazuhito Hokamura"
        },
        {
            "name": "prodaea"
        },
        {
            "name": "Wei Wang"
        },
        {
            "name": "Thomas Boyt"
        }
    ],
    "dependencies": {
        "express": "^4.13.1",
        "graceful-fs": "^4.1.2",
        "markdown-it": "^4.3.0",
        "mdn-links": "^0.1.0",
        "minimatch": "^3.0.2",
        "rimraf": "^2.4.1",
        "yui": "^3.18.1"
    },
    "description": "YUIDoc, YUI's JavaScript Documentation engine.",
    "devDependencies": {
        "eslint": "^1.10.3",
        "istanbul": "^0.3.16",
        "selleck": "^0.1.18",
        "ytestrunner": "^0.3.3",
        "yuitest": "^0.7.9"
    },
    "directories": {},
    "dist": {
        "shasum": "33924967ce619024cd70ef694e267d2f988f73f6",
        "tarball": "https://registry.npmjs.org/yuidocjs/-/yuidocjs-0.10.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "193a7d200ed555fcea6e75a659fab1d0d49e3ee2",
    "homepage": "https://github.com/yui/yuidoc#readme",
    "keywords": [
        "yui",
        "jsdoc",
        "coffeescript",
        "api",
        "documentation",
        "javadoc",
        "docs",
        "apidocs"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "andrewnicols"
        },
        {
            "name": "caridy"
        },
        {
            "name": "davglass"
        },
        {
            "name": "ericf"
        },
        {
            "name": "okuryu"
        },
        {
            "name": "stefanpenner"
        }
    ],
    "name": "yuidocjs",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yui/yuidoc.git"
    },
    "scripts": {
        "pretest": "eslint lib/*.js tests/*.js",
        "test": "istanbul cover --print=both --yui ytestrunner -- --include ./tests/options.js --include ./tests/builder.js --include ./tests/parser.js --include ./tests/parser_coffee.js --include ./tests/files.js --include ./tests/utils.js --include ./tests/preprocessor.js"
    },
    "version": "0.10.2",
    "yuidoc": {
        "name": "YUIDoc",
        "options": {
            "external": {
                "data": "http://yuilibrary.com/yui/docs/api/data.json"
            },
            "linkNatives": "true",
            "attributesEmit": "true",
            "paths": [
                "./lib"
            ],
            "outdir": "./output/api"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
