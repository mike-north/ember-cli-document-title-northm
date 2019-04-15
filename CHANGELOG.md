## [1.0.3](https://github.com/mike-north/ember-cli-document-title-northm/compare/v1.0.2...v1.0.3) (2019-04-15)


### Bug Fixes

* "let" declaration in dev build for older browsers ([#64](https://github.com/mike-north/ember-cli-document-title-northm/issues/64)) ([9bcdbfe](https://github.com/mike-north/ember-cli-document-title-northm/commit/9bcdbfe))

## [1.0.2](https://github.com/mike-north/ember-cli-document-title-northm/compare/v1.0.1...v1.0.2) (2019-02-03)


### Bug Fixes

* wrap vendor file in an IIFE ([70196a6](https://github.com/mike-north/ember-cli-document-title-northm/commit/70196a6))

## [1.0.1](https://github.com/mike-north/ember-cli-document-title-northm/compare/v1.0.0...v1.0.1) (2018-11-24)


### Bug Fixes

* ESLint configuration fixes ([42ac1b8](https://github.com/mike-north/ember-cli-document-title-northm/commit/42ac1b8))

# 1.0.0 (2018-11-23)


### Bug Fixes

* add ember-1.13 compatibility to [@scalvert](https://github.com/scalvert)'s fix ([9d899b6](https://github.com/mike-north/ember-cli-document-title-northm/commit/9d899b6))


### chore

* reset version to 0.0.0-development for semantic-release ([e8b1633](https://github.com/mike-north/ember-cli-document-title-northm/commit/e8b1633))


### BREAKING CHANGES

* 1.0 release

## master

## 0.4.0
+ [BREAKING] Update dependencies and project/testing setup to match `ember-cli@2.15.0` [#56](https://github.com/kimroen/ember-cli-document-title/pull/56)
  `ember-cli-document-title` now requires Node 4 or greater.
+ Add support for returning a Promise from the `titleToken` function. [#55](https://github.com/kimroen/ember-cli-document-title/pull/55)

## 0.3.3
+ Fix support for the combination of Glimmer 2 and Fastboot [#53](https://github.com/kimroen/ember-cli-document-title/pull/53)

## 0.3.2
+ Add support for Glimmer 2 [#49](https://github.com/kimroen/ember-cli-document-title/pull/49)
+ Make it possible to use ember-cli-document-title inside another addon [#48](https://github.com/kimroen/ember-cli-document-title/pull/48)

### 0.3.1
+ Fix problem with returning an array from `titleToken` [#37](https://github.com/kimroen/ember-cli-document-title/pull/37)

## 0.3.0
+ Fix deprecation in ember 2.3 and above regarding containers. [#31](https://github.com/kimroen/ember-cli-document-title/pull/31)
+ Other small improvements [#29](https://github.com/kimroen/ember-cli-document-title/pull/29) and [#30](https://github.com/kimroen/ember-cli-document-title/pull/30).

## 0.2.0
+ Fixed deprecation warning regarding `_actions` in ember 2.0 and above. Thanks for the help, everyone! [#28](https://github.com/kimroen/ember-cli-document-title/pull/28)

## 0.1.0
+ Removed another use of prototype extensions [#12](https://github.com/kimroen/ember-cli-document-title/pull/12)
+ Made sure use with Fastboot doesn't explode [#13](https://github.com/kimroen/ember-cli-document-title/pull/13)
+ Added testing of more Ember versions (1.10 and up)[#13](https://github.com/kimroen/ember-cli-document-title/pull/13)

## 0.0.3
+ Re-did the addon structure to match newer addon conventions [#3](https://github.com/kimroen/ember-cli-document-title/pull/3)
+ Added tests [#3](https://github.com/kimroen/ember-cli-document-title/pull/3)
+ Fixed the context for the `title` and `titleToken` hooks on routes. [#5](https://github.com/kimroen/ember-cli-document-title/pull/5) and [#7](https://github.com/kimroen/ember-cli-document-title/pull/7)

## 0.0.2
+ Access route properties using getters [#2](https://github.com/kimroen/ember-cli-document-title/pull/2)

## 0.0.1
+ Initial release
