# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

# 2.0.0 (2023-02-19)


### Bug Fixes

* drop support for webpack 3 and below ([da9d580](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/da9d580))
* handle warnings which are plain strings instead of objects ([0849576](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/0849576))


### Features

* convert to typescript ([af1ad14](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/af1ad14))
* initial implementation ([aa64f57](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/aa64f57))
* support webpack 4 ([c80d831](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/c80d831))


### BREAKING CHANGES

* webpack 3 and below are no longer supported
* node 8 or higher is now required to use this package. 

commonjs users will now need to import the library as a named export instead. To migrate:

Before:
```
const FilterWarningsPlugin = require('webpack-filter-warnings-plugin');
```

After:
```
const { FilterWarningsPlugin } = require('webpack-filter-warnings-plugin');
```



<a name="1.2.1"></a>
## [1.2.1](https://github.com/mattlewis92/webpack-filter-warnings-plugin/compare/v1.2.0...v1.2.1) (2018-11-25)


### Bug Fixes

* handle warnings which are plain strings instead of objects ([0849576](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/0849576))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/mattlewis92/webpack-filter-warnings-plugin/compare/v1.1.0...v1.2.0) (2018-03-06)


### Features

* support webpack 4 ([c80d831](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/c80d831))



<a name="1.1.0"></a>
# 1.1.0 (2017-07-31)

### Documentation
* improved documentation

<a name="1.0.0"></a>
# 1.0.0 (2017-07-31)


### Features

* initial implementation ([aa64f57](https://github.com/mattlewis92/webpack-filter-warnings-plugin/commit/aa64f57))
