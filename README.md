# npmdoc-homebrew

#### api documentation for  homebrew (v0.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-homebrew.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-homebrew) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-homebrew.svg)](https://travis-ci.org/npmdoc/node-npmdoc-homebrew)

#### The missing package manager for OS X

[![NPM](https://nodei.co/npm/homebrew.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/homebrew)

- [https://npmdoc.github.io/node-npmdoc-homebrew/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-homebrew/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebrew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebrew/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-homebrew/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-homebrew/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "homebrew",
    "version": "0.1.0",
    "description": "The missing package manager for OS X",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/afc163/homebrew"
    },
    "scripts": {
        "postinstall": "ruby -e \"$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)\""
    },
    "author": "afc163 <afc163@gmail.com>",
    "license": "ISC",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
