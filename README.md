# npmtest-image-webpack-loader

#### test coverage for  [image-webpack-loader (v3.3.0)](https://github.com/tcoopman/image-webpack-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-image-webpack-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-image-webpack-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-image-webpack-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-image-webpack-loader)

#### Image loader module for webpack

[![NPM](https://nodei.co/npm/image-webpack-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/image-webpack-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-image-webpack-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-image-webpack-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-image-webpack-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-image-webpack-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-image-webpack-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-image-webpack-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-image-webpack-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-image-webpack-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-image-webpack-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-image-webpack-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thomas Coopman @tcoopman"
    },
    "bugs": {
        "url": "https://github.com/tcoopman/image-webpack-loader/issues"
    },
    "dependencies": {
        "imagemin": "^5.2.2",
        "imagemin-gifsicle": "^5.1.0",
        "imagemin-mozjpeg": "^6.0.0",
        "imagemin-optipng": "^5.2.1",
        "imagemin-pngquant": "^5.0.0",
        "imagemin-svgo": "^5.2.1",
        "loader-utils": "^1.1.0",
        "object-assign": "^4.1.1"
    },
    "description": "Image loader module for webpack",
    "devDependencies": {
        "file-loader": "^0.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e377ed58b1418b8db20267b17d8fcbbfe6b0de63",
        "tarball": "https://registry.npmjs.org/image-webpack-loader/-/image-webpack-loader-3.3.0.tgz"
    },
    "gitHead": "7a29e0a61e2cb6dec5151aed943be2ab81a902e6",
    "homepage": "https://github.com/tcoopman/image-webpack-loader#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "tcoopman"
        }
    ],
    "name": "image-webpack-loader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/tcoopman/image-webpack-loader.git"
    },
    "scripts": {
        "test": "npm run test:webpack1 && npm run test:webpack2",
        "test:clean": "rm -rf test/public/assets",
        "test:webpack1": "npm install -q webpack@1.x && npm run test:clean && webpack --config test/webpack1.config.js",
        "test:webpack2": "npm install -q webpack@2.x && npm run test:clean && webpack --config test/webpack2.config.js"
    },
    "version": "3.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
