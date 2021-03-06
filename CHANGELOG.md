## 0.6.1 (1.1.2017)

**[compare](https://github.com/Deraen/less4clj/compare/0.6.0...0.6.1)**

- Hide stack trace of Less compilation errors [boot-clj/boot#532](https://github.com/boot-clj/boot/pull/532)

## 0.6.0 (18.10.2016)

**[compare](https://github.com/Deraen/less4clj/compare/0.5.0...0.6.0)**

- Handle URL normalization and joining in hopefully more robust way (fixes [#8](https://github.com/Deraen/less4clj/issues/8))
- Run tests on Windows CI
- Fixed Webjars import on Windows
- Update less4j
- Fix logging errors with "%"

## 0.5.0 (24.12.2015)

**[compare](https://github.com/Deraen/less4clj/compare/0.4.1...0.5.0)**

- Synchronized versions between all packages
- Boot and Lein packages are now maintained in less4clj repository

## 0.4.1 (23.12.2015)

- Drop dependency on slf4j no-op implementation

## 0.4.0 (23.12.2015)

- Updated less4j to 1.15.4
- Uses [webjars-locator](https://github.com/webjars/webjars-locator) for
finding Webjar assets
- Added support for inline javascript through [less4j-javascript](https://github.com/SomMeri/less4j-javascript)
    - Enable using `:inline-javascript` option

## 0.3.3 (31.8.2015)

- Add `:verbosity` option to `less-compile`

## 0.3.2 (16.8.2015)

- Update less4j to 1.14.0

## 0.3.1 (13.6.2015)

- Fix

## 0.3.0 (13.6.2015)

- Update less4j to 1.12.0
- *BREAKING CHANGE*: `less-compile` now returns a map with
  resulting css and source-map as strings
- `less-compile-to-file` creates output files
- `less-compile` input can be either a File or String (used as Less source)

## 0.2.1 (21.3.2015)

- Fixed error logging for non boot use

## 0.2.0 (3.3.2015)

- Replaced WebjarsAsset locator with a simple clojure implementation
  - Might be missing some stuff but I have tested this to work with Boostrap
  - Doesn't require java logging lib
- Updated to less4j 1.9.0
