# Changelog
All notable changes to this project will be documented in this file.

The format is base on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.21.00.000] - 2024-09-04
### Added
- Grant `SECURITYADMIN` and `SYSADMIN` roles to the service account user.

## [0.20.00.000] - 2024-09-02
### Changed
- Renamed the repo.
- Refactored the repo to focus solely on creating/updating Snowflake admin service account user.

## [0.11.00.000] - 2024-08-28
### Changed
- Updated the script name.

## [0.10.00.000] - 2024-08-27
### Added
- Now create two RSA key pairs per Snowflake user.

### Changed
- Updated the `README.md` to be more instructive.

## [0.04.00.000] - 2024-08-24
### Added
- Describe the script execution in detail.
- Added to the script the `--tf_snowflake_user` argument.

## [0.03.00.000] - 2024-08-24
### Added
- Explained in the `README.md` why the script was developed in the first place, and how it should be used. 

## [0.02.00.000] - 2024-08-24
### Changed
- Updated the script, where we make the `--action` argument a command instead.

## [0.01.00.000] - 2024-08-23
### Added
- First release.