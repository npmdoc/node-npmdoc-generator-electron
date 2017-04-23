# npmdoc-generator-electron

#### api documentation for  generator-electron (v1.20.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-electron.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-electron) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-electron.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-electron)

#### Scaffold out an Electron app boilerplate

[![NPM](https://nodei.co/npm/generator-electron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-electron)

- [https://npmdoc.github.io/node-npmdoc-generator-electron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-electron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-electron/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-electron/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-electron/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-electron",
    "version": "1.20.0",
    "description": "Scaffold out an Electron app boilerplate",
    "license": "MIT",
    "repository": "sindresorhus/generator-electron",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "xo && mocha"
    },
    "files": [
        "app"
    ],
    "keywords": [
        "yeoman-generator",
        "boilerplate",
        "template",
        "scaffold",
        "node",
        "desktop",
        "app",
        "application",
        "electron"
    ],
    "dependencies": {
        "humanize-url": "^1.0.1",
        "normalize-url": "^1.2.0",
        "superb": "^1.1.3",
        "underscore.string": "^3.0.3",
        "yeoman-generator": "^0.22.5"
    },
    "devDependencies": {
        "mocha": "*",
        "xo": "*",
        "yeoman-assert": "^2.0.0",
        "yeoman-test": "^1.1.0"
    },
    "xo": {
        "envs": [
            "node",
            "mocha"
        ],
        "ignores": [
            "app/templates/**"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
