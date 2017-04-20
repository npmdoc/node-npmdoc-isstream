# npmdoc-isstream

#### api documentation for  [isstream (v0.1.2)](https://github.com/rvagg/isstream)  [![npm package](https://img.shields.io/npm/v/npmdoc-isstream.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-isstream) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-isstream.svg)](https://travis-ci.org/npmdoc/node-npmdoc-isstream)

#### Determine if an object is a Stream

[![NPM](https://nodei.co/npm/isstream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/isstream)

- [https://npmdoc.github.io/node-npmdoc-isstream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-isstream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-isstream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-isstream/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-isstream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-isstream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "isstream",
    "version": "0.1.2",
    "description": "Determine if an object is a Stream",
    "main": "isstream.js",
    "scripts": {
        "test": "tar --xform 's/^package/readable-stream-1.0/' -zxf readable-stream-1.0.*.tgz && tar --xform 's/^package/readable-stream-1.1/' -zxf readable-stream-1.1.*.tgz && node test.js; rm -rf readable-stream-1.?/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/rvagg/isstream.git"
    },
    "keywords": [
        "stream",
        "type",
        "streams",
        "readable-stream",
        "hippo"
    ],
    "devDependencies": {
        "tape": "~2.12.3",
        "core-util-is": "~1.0.0",
        "isarray": "0.0.1",
        "string_decoder": "~0.10.x",
        "inherits": "~2.0.1"
    },
    "author": "Rod Vagg <rod@vagg.org>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/rvagg/isstream/issues"
    },
    "homepage": "https://github.com/rvagg/isstream"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
