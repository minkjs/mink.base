# Mink Base

> This base repository serves as the platform for all core-modules and plugins. 

[![Build Status](https://travis-ci.org/minkjs/mink.base.svg?branch=master)](https://travis-ci.org/minkjs/mink.base)
[![Coverage Status](https://coveralls.io/repos/github/minkjs/mink.base/badge.svg?branch=master)](https://coveralls.io/github/minkjs/mink.base?branch=master)
[![Known Vulnerabilities](https://snyk.io/test/github/minkjs/mink.base/badge.svg?targetFile=package.json)](https://snyk.io/test/github/minkjs/mink.base?targetFile=package.json)
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)

## Usage

Clone the repo for a feature.

```shell
git clone git@github.com/minkjs/mink.base mink.core.feature-name
```

Clone the repo for a plugin.

```shell
git clone git@github.com/minkjs/mink.base mink.plugin.feature-name
```

## Testing Tools

Testing tools for this project are:

- Linting / Codestyle
    + XO (ESLint)
- Unit Testing
    + Mocha
    + Chai
    + Chai as Promised 
- Coverage
    + Istanbul
    + lcov
    + Coveralls.io
- CI
    + Travis
- Other
    + Git Pre-Commit

## Editor Settings

Editor settings for this project are as follows:

- Semicolons: No
- Delimiter: Spaces, 4

- IDE - Sublime Text 3
    + Plugins
        * SublimeLinter
        * SublimeLinter-contrib-xo
        * Editor Config
        * JavaScript - ES6 Syntax
        * MarkdownHighlighting
