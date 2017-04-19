# npmdoc-cold-brew

#### api documentation for  [cold-brew (v1.0.36)](https://github.com/team-jwd/cold-brew)  [![npm package](https://img.shields.io/npm/v/npmdoc-cold-brew.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cold-brew) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cold-brew.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cold-brew)

#### A testing module for TDD with apps that use the RTCPeerConnection API

[![NPM](https://nodei.co/npm/cold-brew.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cold-brew)

- [https://npmdoc.github.io/node-npmdoc-cold-brew/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cold-brew/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cold-brew/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cold-brew/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cold-brew/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cold-brew/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Team JWD"
    },
    "bugs": {
        "url": "https://github.com/team-jwd/cold-brew/issues"
    },
    "dependencies": {
        "chromedriver": "^2.24.1",
        "selenium-webdriver": "^3.0.0-beta-3"
    },
    "description": "A testing module for TDD with apps that use the RTCPeerConnection API",
    "devDependencies": {
        "babel-preset-es2015": "^6.18.0",
        "babelify": "^7.3.0",
        "browserify": "^13.1.1",
        "bufferutil": "^1.2.1",
        "chai": "^3.5.0",
        "express": "^4.14.0",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-minify": "0.0.14",
        "gulp-notify": "^2.2.0",
        "gulp-uglify": "^2.0.0",
        "gulp-watch": "^4.3.10",
        "jquery": "^3.1.1",
        "jsdoc": "^3.4.2",
        "jwt-decode": "^2.1.0",
        "mocha": "^3.1.2",
        "selenium-webdriver": "^3.0.0-beta-3",
        "socket.io": "^1.5.0",
        "socket.io-client": "^1.5.0",
        "uglifyjs": "^2.4.10",
        "utf-8-validate": "^1.2.1",
        "vinyl-source-stream": "^1.1.0",
        "vinyl-transform": "^1.0.0",
        "watchify": "^3.7.0",
        "webrtc-adapter": "^2.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "1b274ae43341acc725d14017f6e470660109198a",
        "tarball": "https://registry.npmjs.org/cold-brew/-/cold-brew-1.0.36.tgz"
    },
    "gitHead": "f376ebc7e0b5619decde41dbd905a4bc17f13a46",
    "homepage": "https://github.com/team-jwd/cold-brew",
    "keywords": [
        "testing",
        "TDD",
        "WebRTC",
        "RTCPeerConnection",
        "selenium"
    ],
    "license": "ISC",
    "main": "src/cold-brew-test.js",
    "maintainers": [
        {
            "name": "cold-brew"
        }
    ],
    "name": "cold-brew",
    "optionalDependencies": {},
    "scripts": {
        "bundle-client:watch": "./node_modules/gulp/bin/gulp.js",
        "generate-docs": "jsdoc ./cold-brew-test.js -d ./docs",
        "test": "mocha test/*.spec.js"
    },
    "version": "1.0.36"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
