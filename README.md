# ZfcAdmin Module for Zend Framework 2
Version 0.1.0 created by [Jurian Sluiman](http://juriansluiman.nl/en) and [Martin Shwalbe](https://github.com/Hounddog).

## Introduction
ZfcAdmin is a minimal admin interface for generic administrative purposes. It is a common screen with navigation that hides behind authentication and authorization.

## Installation
ZfcAdmin is enabled to be installed via composer. Load `zf-commons/zfc-admin` in your `composer.json` file. You can specify its version (currently only 0.1.0 is recommended) or use `dev-master` to load the latest version from master. Enable ZfcAdmin in your `application.config.php` configuration file.

If you do not want to use composer, clone this project (either as a git submodule or not) into `./vendor/` directory.

## Usage
ZfcAdmin allows you to create routes under a single parent "admin" route. You can also use it to enable navigation in your admin layout. Furthermore integration of [BjyAuthorize](https://github.com/bjyoungblood/BjyAuthorize) and [ZfcRbac](https://github.com/spiffyjr/ZfcRbac) is provided.

The complete configuration is flexible, so you can update the zfcadmin parent route, its children, the navigation and all default provided view scripts. Read more in the [documentation](docs/1.Introduction.md) about usage and customization of ZfcAdmin.

## Development
ZfcAdmin is currently under development. The authors feel ZfcAdmin is stable enough for production versions and you can always fix your ZfcAdmin version to a specific tag. Feel free to report bugs in the [issue tracker](https://github.com/ZF-Commons/ZfcAdmin/issues) or come by on IRC at the Freenode channel `#zftalk`.