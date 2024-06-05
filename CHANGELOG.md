# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- [#26](https://github.com/green-code-initiative/ecoCode-python/issues/26) [EC89] Avoid unlimited cache

### Changed

### Deleted

## [1.4.3] - 2024-05-15

### Added

- [#18](https://github.com/green-code-initiative/ecoCode-python/issues/18) Add support for SonarQube 10.4 "DownloadOnlyWhenRequired" feature

### Changed

- [#17](https://github.com/green-code-initiative/ecoCode-python/issues/17) EC7 - correction setter problem on constructor method
- check Sonarqube 10.4.1 compatibility + update docker files and README.md / NOT OK with 10.5.x (issue created)

## [1.4.2] - 2024-01-11

### Changed

- [#14](https://github.com/green-code-initiative/ecoCode-python/issues/14) Correction of error with deprecated EC34 rule
- Update ecocode-rules-specifications to 1.4.7

## [1.4.1] - 2024-01-05

### Added

- Add 10.3 SonarQube compatibility

### Changed

- [#5](https://github.com/green-code-initiative/ecoCode-python/pull/5) Upgrade licence system and licence headers of Java files
- [#6](https://github.com/green-code-initiative/ecoCode-python/pull/6) Adding EC35 rule : EC35 rule replaces EC34 with a specific use case ("file not found" sepcific)
- [#7](https://github.com/green-code-initiative/ecoCode-python/issues/7) Add build number to manifest
- [#123](https://github.com/green-code-initiative/ecoCode/issues/123) Improve unit tests for EC7 rule
- Update ecocode-rules-specifications to 1.4.6
- README.md upgrade : docker test environment
- [#10](https://github.com/green-code-initiative/ecoCode-python/issues/10) Correction of NullPointException in EC2 rule

### Deleted

- [#4](https://github.com/green-code-initiative/ecoCode-python/issues/4) Deprecate rule EC66 for Python because not applicable (see details inside issue)

## [1.4.0] - 2023-08-08

### Added

- Python rules moved from `ecoCode` repository to current repository
- [#142](https://github.com/green-code-initiative/ecoCode/issues/142) new Python rule : Multiple if-else statement + refactoring implementation
- [#205](https://github.com/green-code-initiative/ecoCode/issues/205) compatibility with SonarQube 10.1

## Comparison list

[unreleased](https://github.com/green-code-initiative/ecoCode-python/compare/1.4.3...HEAD)
[1.4.3](https://github.com/green-code-initiative/ecoCode-python/compare/1.4.2...1.4.3)
[1.4.2](https://github.com/green-code-initiative/ecoCode-python/compare/1.4.1...1.4.2)
[1.4.1](https://github.com/green-code-initiative/ecoCode-python/compare/1.4.0...1.4.1)
[1.4.0](https://github.com/green-code-initiative/ecoCode-python/releases/tag/1.4.0)
