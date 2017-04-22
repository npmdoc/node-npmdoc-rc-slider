# npmdoc-rc-slider

#### api documentation for  [rc-slider (v7.0.2)](http://github.com/react-component/slider)  [![npm package](https://img.shields.io/npm/v/npmdoc-rc-slider.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rc-slider) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rc-slider.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rc-slider)

#### Slider UI component for React

[![NPM](https://nodei.co/npm/rc-slider.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rc-slider)

- [https://npmdoc.github.io/node-npmdoc-rc-slider/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rc-slider/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rc-slider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rc-slider/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rc-slider/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rc-slider/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "rc-slider",
    "version": "7.0.2",
    "description": "Slider UI component for React",
    "keywords": [
        "react",
        "react-component",
        "react-slider",
        "slider"
    ],
    "homepage": "http://github.com/react-component/slider",
    "author": "sima.zhang1990@gmail.com",
    "repository": {
        "type": "git",
        "url": "git@github.com:react-component/slider.git"
    },
    "bugs": {
        "url": "http://github.com/react-component/slider/issues"
    },
    "files": [
        "assets/*.css",
        "lib",
        "dist"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "entry": {
        "rc-slider": [
            "./assets/index.less",
            "./src/index.js"
        ]
    },
    "style": "./assets/index.css",
    "config": {
        "port": 8005
    },
    "scripts": {
        "build": "rc-tools run build",
        "gh-pages": "rc-tools run gh-pages",
        "start": "rc-tools run server",
        "pub": "rc-tools run pub --babel-runtime",
        "lint": "rc-tools run lint",
        "karma": "rc-tools run karma",
        "saucelabs": "rc-tools run saucelabs",
        "test": "jest",
        "chrome-test": "rc-tools run chrome-test",
        "coverage": "jest --coverage && cat ./coverage/lcov.info | coveralls"
    },
    "jest": {
        "collectCoverageFrom": [
            "src/*"
        ]
    },
    "devDependencies": {
        "coveralls": "^2.11.15",
        "enzyme": "^2.7.0",
        "enzyme-to-json": "^1.4.5",
        "jest": "^18.1.0",
        "pre-commit": "1.x",
        "rc-tools": "^5.6.8",
        "react": "^15.2.1",
        "react-addons-test-utils": "^15.2.1",
        "react-dom": "^15.2.1"
    },
    "pre-commit": [
        "lint"
    ],
    "dependencies": {
        "babel-runtime": "6.x",
        "classnames": "^2.2.5",
        "prop-types": "^15.5.4",
        "rc-tooltip": "^3.4.2",
        "rc-util": "^4.0.0",
        "warning": "^3.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
