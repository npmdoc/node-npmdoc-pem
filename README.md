# npmdoc-pem

#### api documentation for  pem (v1.9.4)  [![npm package](https://img.shields.io/npm/v/npmdoc-pem.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pem) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pem.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pem)

#### Create private keys and certificates with node.js and io.js

[![NPM](https://nodei.co/npm/pem.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pem)

- [https://npmdoc.github.io/node-npmdoc-pem/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pem/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pem/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pem/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pem/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Andris Reinman <andris@kreata.ee>",
    "contributors": [
        {
            "name": "Josef Fröhle",
            "url": "https://www.josef-froehle.de/"
        }
    ],
    "name": "pem",
    "description": "Create private keys and certificates with node.js and io.js",
    "version": "1.9.4",
    "repository": {
        "type": "git",
        "url": "https://github.com/Dexus/pem.git"
    },
    "main": "lib/pem",
    "scripts": {
        "test": "grunt",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post"
    },
    "dependencies": {
        "os-tmpdir": "^1.0.1",
        "which": "^1.2.4"
    },
    "devDependencies": {
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^1.1.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "nodeunit": "^0.10.2",
        "semantic-release": "^6.3.2",
        "semantic-release-tamia": "^1.0.0"
    },
    "optionalDependencies": {},
    "engines": {
        "node": "*",
        "iojs": "*"
    },
    "release": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
