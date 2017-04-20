# npmtest-react-responsive

#### basic test coverage for  [react-responsive (v1.2.10)](http://github.com/contra/react-responsive)  [![npm package](https://img.shields.io/npm/v/npmtest-react-responsive.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-responsive) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-responsive.svg)](https://travis-ci.org/npmtest/node-npmtest-react-responsive)

#### Media queries in react for responsive design

[![NPM](https://nodei.co/npm/react-responsive.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-responsive)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-responsive/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-responsive/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-responsive/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-responsive/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-responsive/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-responsive/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-responsive/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-responsive/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-responsive/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-responsive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-responsive/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-responsive/build/test-report.html](https://npmtest.github.io/node-npmtest-react-responsive/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-responsive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-responsive/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-responsive/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-responsive/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-responsive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-responsive/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-responsive/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-responsive/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Contra",
        "url": "http://contra.io"
    },
    "babel": {
        "presets": [
            "es2015",
            "react",
            "stage-0"
        ],
        "plugins": [
            "add-module-exports"
        ]
    },
    "bugs": {
        "url": "https://github.com/contra/react-responsive/issues"
    },
    "dependencies": {
        "hyphenate-style-name": "^1.0.0",
        "matchmedia": "^0.1.2",
        "prop-types": "^15.5.7"
    },
    "description": "Media queries in react for responsive design",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-core": "^6.18.0",
        "babel-eslint": "^7.1.0",
        "babel-loader": "^6.2.7",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-es2015-loose": "^8.0.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-register": "^6.18.0",
        "chai": "^3.5.0",
        "eslint": "^3.9.0",
        "eslint-config-rackt": "^1.1.1",
        "github-changes": "^1.0.4",
        "jsdom": "^8.4.0",
        "mocha": "^2.4.5",
        "react": "^15.0.1",
        "react-addons-test-utils": "^15.0.1",
        "react-dom": "^0.14.0 || ^15.0.0",
        "should": "^8.0.2",
        "sinon": "^1.17.3",
        "webpack": "^1.13.3",
        "webpack-dev-server": "^1.16.2"
    },
    "directories": {},
    "dist": {
        "shasum": "279746d7846f58ec9374aee910119d0351edb1b8",
        "tarball": "https://registry.npmjs.org/react-responsive/-/react-responsive-1.2.10.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "eslintConfig": {
        "parser": "babel-eslint",
        "extends": "rackt",
        "env": {
            "browser": true,
            "node": true,
            "es6": true
        },
        "ecmaFeatures": {
            "modules": true
        },
        "rules": {
            "semi": [
                2,
                "never"
            ]
        }
    },
    "files": [
        "dist"
    ],
    "gitHead": "ab7ff5cddcba1f22f3ace26dd777bbc530449c6c",
    "homepage": "http://github.com/contra/react-responsive",
    "keywords": [
        "css",
        "react-component",
        "viewport",
        "react",
        "mobile",
        "media queries",
        "respond",
        "media query",
        "matchMedia",
        "responsive",
        "component"
    ],
    "license": "MIT",
    "main": "./dist/react-responsive.js",
    "maintainers": [
        {
            "name": "contra"
        },
        {
            "name": "fractal"
        }
    ],
    "name": "react-responsive",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "*"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/contra/react-responsive.git"
    },
    "scripts": {
        "build": "$(npm bin)/webpack",
        "build:watch": "npm run build -- --watch",
        "changelog": "github-changes -o contra -r react-responsive -b master -f ./CHANGELOG.md --order-semver --use-commit-body",
        "clean": "rimraf dist",
        "docs": "npm run docs:pre && npm run docs:build && npm run docs:publish",
        "docs:build": "gitbook build -g contra/react-responsive",
        "docs:pre": "gitbook install && rimraf _book",
        "docs:publish": "cd _book && git init && git commit --allow-empty -m 'update book' && git checkout -b gh-pages && touch .nojekyll && git add . && git commit -am 'update book' && git push git@github.com:contra/react-responsive gh-pages --force",
        "lint": "$(npm bin)/eslint src",
        "postversion": "npm run changelog",
        "preversion": "npm run clean && npm run build && npm docs",
        "start": "$(npm bin)/webpack-dev-server --config webpack.config.samples.js  --content-base samples/sandbox/src --host 0.0.0.0 --hot --inline --port 3333",
        "test": "NODE_PATH=$NODE_PATH:$PWD/src $(npm bin)/mocha -R spec --compilers js:babel-register --require ./test/setup.js test/*_test.js"
    },
    "version": "1.2.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
