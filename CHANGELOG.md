# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

### [Unreleased]

  * Changed: filenames now class constants of SpdxLicenses (`LICENSES_FILE` and `EXCEPTIONS_FILE`)
  * Changed: resources directory now available via static method SpdxLicenses::getResourcesDir()

### [1.0.0] 2015-07-15

  * Break: the following classes and namespaces were renamed:
    - Namespace: `Composer\Util` -> `Composer\Spdx`
    - Classname: `SpdxLicense` -> `SpdxLicenses`
    - Classname: `SpdxLicenseTest` -> `SpdxLicensesTest`
    - Classname: `Updater` -> `SpdxLicensesUpdater`
  * Changed: validation to regex implementation in favor of lexer.
  * Changed: code style using php-cs-fixer.