# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.3] - 2024-10-29

This update introduces a critical bug fix

### Fixed
 - Fixed issue where if global $argv is not available, a check to see if `$_SERVER['argv']` is set
   before accessing it due to a potential 'undefined' error.


## [1.1.2] - 2024-10-13

Updated Build System


## [1.1.1] - 2024-09-24

Updated OptsLib to work with php 8.3+ & ncc 2.1.0+

### Changed
 - Introduced typed properties to OptsLib

### Fixed
 - Fixed code-smell from OptsLib



## [1.1.0] - 2023-10-10

Updated optslib to work with ncc 2.+.

### Fixed
 - Fixed code-smell from optslib.



## [1.0.0] - 2023-01-29

Initial release of ConfigLib.