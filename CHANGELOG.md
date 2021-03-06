# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [0.3.0](https://github.com/puppetlabs/puppetlabs-package/tree/0.3.0) (2018-09-27)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-package/compare/0.2.0...0.3.0)

### Added

- pdksync - \(FM-7392\) - Puppet 6 Testing Changes [\#88](https://github.com/puppetlabs/puppetlabs-package/pull/88) ([pmcmaw](https://github.com/pmcmaw))
- \(DI-3260\) Adding agentless windows task \(for choco\) [\#81](https://github.com/puppetlabs/puppetlabs-package/pull/81) ([HairyMike](https://github.com/HairyMike))
- \(DI-2373\) Adding agentless linux task [\#77](https://github.com/puppetlabs/puppetlabs-package/pull/77) ([tphoney](https://github.com/tphoney))
- \(FM-7263\) - Addition of support for ubuntu 18.04 [\#70](https://github.com/puppetlabs/puppetlabs-package/pull/70) ([david22swan](https://github.com/david22swan))
- \[FM-7058\] Addition of support for Debian 9 to package [\#69](https://github.com/puppetlabs/puppetlabs-package/pull/69) ([david22swan](https://github.com/david22swan))

## 0.2.0
Updates the module to be compatible with PDK 1.4.1, adds beaker task helper and relevant functionality.

### Added
- Beaker_task_helper added.
- Rubygems path for Beaker Task Helper.

### Changed
- Module converted using version 1.4.1 of the PDK.

## Release 0.1.5

### Changed
- Nothing, we needed a release.

## Release 0.1.4

### Fixed
- Readme updates.
- Tests work on PE and Bolt.
- Package attribute is now name.

## Release 0.1.3

### Fixed
- Updated readme.
- Fixed locales project name.
- Fixed cli description.

## Release 0.1.2

### Fixed
- Handle providers that return multiple versions (gem)
- Handle providers that don't have latest (windows)
- Handle providers that exit 1 when absent (yum)

## Release 0.1.1
This is the initial release of the package task.

## Features
- Provides the following actions install, status, uninstall and upgrade.
- Upgrade allows specifying a version.
- Provider can optionally be specified, eg gem or apt. 


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
