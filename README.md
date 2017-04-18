# npmdoc-react-webpack

#### api documentation for  [react-webpack (v0.4.1)](https://github.com/ThomasDeutsch/react-webpack)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-webpack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-webpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-webpack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-webpack)

#### React + Webpack Starter Template

[![NPM](https://nodei.co/npm/react-webpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-webpack)

- [https://npmdoc.github.io/node-npmdoc-react-webpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-webpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-webpack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-webpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-webpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thomas Deutsch"
    },
    "bugs": {
        "url": "https://github.com/ThomasDeutsch/react-webpack/issues"
    },
    "dependencies": {
        "css-loader": "~0.6.8",
        "envify": "~1.2.1",
        "jsx-loader": "~0.9.0",
        "less-loader": "~0.7.1",
        "react": "~0.9.0",
        "script-loader": "~0.5.2",
        "style-loader": "~0.6.2",
        "webpack": "~1.0.1"
    },
    "description": "React + Webpack Starter Template",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "07c6f7d74528af9cd82aac3e2df51e1cb7264958",
        "tarball": "https://registry.npmjs.org/react-webpack/-/react-webpack-0.4.1.tgz"
    },
    "files": [
        "devserver/",
        "source/",
        "build/",
        "server.config",
        "webpack.config"
    ],
    "homepage": "https://github.com/ThomasDeutsch/react-webpack",
    "keywords": [
        "webpack",
        "react"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "thomas-deutsch"
        }
    ],
    "name": "react-webpack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ThomasDeutsch/react-webpack.git"
    },
    "scripts": {
        "devserver": "webpack-dev-server --config server.config.js --content-base ./devserver_files --port 9500 --colors",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "0.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
