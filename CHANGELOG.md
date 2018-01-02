# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2017-01-03
### Added
- 'hyphenate' option in settings - hyphenation the resulting class name
- 'methodName' option in settings - name of the method for generating the class name

### Changed
- New build system with Rollup. Now, only two types of distributed files - ES6 module for modern build systems and UMD.
- Reducing build size ( less than 1 KB with minification and gzip )
- Changed the structure of the settings object (more in the [API section](#api))
- Updated README.md. New "[Default settings](#default-settings)" section
- Fixed typos in CHANGELOG.md

### Removed
- CommonJS module build

## [0.1.1] - 2017-01-03

### Added
- This CHANGELOG file

### Removed
- `module` from `package.json` (#2)

[1.0.0]: https://github.com/c01nd01r/vue-bem-cn/compare/v0.1.1...v1.0.0
[0.1.1]: https://github.com/c01nd01r/vue-bem-cn/compare/v0.1.0...v0.1.1
