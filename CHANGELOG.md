# Change Log

All notable changes to the "samarium-language" extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/).

## [0.8.0] - 2022-03-20

### Changed
- Enriched highlighting for new function syntax (Samarium 0.2.0)

## [0.7.1] - 2022-03-08

### Changed
- Improved class recognition to work with decorated functions

## [0.7.0] - 2022-03-01

### Added
- Escape sequence highlighting

### Fixed
- Multiline string highlighting

### Changed
- Changed the marketplace icon
- Improved operator and keyword recognition
- Updated repository links

## [0.6.2] - 2022-02-03

### Fixed
- Class definitions are no longer highlighted as functions

## [0.6.1] - 2022-02-01

### Added
- Added support for digits in identifiers.

## [0.6.0] - 2022-01-28

### Added
- Marked `_` as a constant
- Added highlighting for `,.,`
- Added extension icon

### Fixed
- Fixed highlighting for
  - `?~>`
  - `?!`
  - `!?`
  - `##`
  - `@@`
  - `<>`
  - `..`
  - `...`

### Changed
- Improved the highlighting order

## [0.5.0] - 2022-01-22

### Added
- Punctuation highlighting
- Added a Changelog
- Marked `{{ }}` and `<< >>` as brackets

### Fixed
- Adjusted keyword and operator highlighting

### Changed
- Shortened regular expressions for classes and functions
- Updated README

### Removed
- Lambda function highlighting
- String interpolation

## [0.4.0] - 2021-12-26
### Fixed
- Incorrect `\` highlighting which emerged after fixing the [0.3.0](#030---2021-12-16) issue

## [0.3.0] - 2021-12-26

### Fixed
- Fixed a bug where escape sequences would stop highlighting a string properly (thanks @DarviL82)

## [0.2.0] - 2021-12-23

### Fixed
- Fixed a bug highlighting the opening parenthesis in a function call (e.g. in `function(call)`, `function(` would be treated as the function name (instead of just `function`))

## [0.1.0] - 2021-12-23

### Added
- Basic syntax highlighting

[0.1.0]: https://github.com/samarium-lang/vscode-samarium/releases/tag/0.1.0
[0.2.0]: https://github.com/samarium-lang/vscode-samarium/compare/0.1.0...0.2.0
[0.3.0]: https://github.com/samarium-lang/vscode-samarium/compare/0.2.0...0.3.0
[0.4.0]: https://github.com/samarium-lang/vscode-samarium/compare/0.3.0...0.4.0
[0.5.0]: https://github.com/samarium-lang/vscode-samarium/compare/0.4.0...0.5.0
[0.6.0]: https://github.com/samarium-lang/vscode-samarium/compare/0.5.0...0.6.0
[0.6.1]: https://github.com/samarium-lang/vscode-samarium/compare/0.6.0...0.6.1
[0.6.2]: https://github.com/samarium-lang/vscode-samarium/compare/0.6.1...0.6.2
[0.7.0]: https://github.com/samarium-lang/vscode-samarium/compare/0.6.2...0.7.0
[0.7.1]: https://github.com/samarium-lang/vscode-samarium/compare/0.7.0...0.7.1
[0.8.0]: https://github.com/samarium-lang/vscode-samarium/compare/0.7.1...0.8.0