# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2019-05-12
### Added
- Added CoinGecko API support

### Changed
- Default API from CoinMarketCap to CoinGecko

## [1.1.6] - 2019-04-23
### Added
- Prompt for CoinMarketCap Pro API Key

## [1.1.5] - 2019-04-22
### Fixed
- Release archive to contain latest source code

## [1.1.4] - 2019-04-21
### Changed
- CoinMarketCap legacy V2 API to Pro V1 API

### Added
- Config option to use CoinMarketCap Pro V1 API KEY

## [1.1.3] - 2019-02-25
### Fixed
- Vendor dependencies

## [1.1.2] - 2018-12-30
### Fixed
- Paginate CoinMarketCap V1 API responses due to their backward-incompatible update

### Added
- `-clean` flag to clean cache
- `-reset` flag to clean cache and delete config
- `-config` flag to use a different specified config file

## [1.1.1] - 2018-12-26
### Changed
- Use go modules instead of dep

## [1.1.0] - 2018-12-25
### Added
- Basic portfolio functionality
- `P` keyboard shortcut to toggle portfolio view
- `e` keyboard shortcut to edit portfolio holdings
- `[portfolio]` TOML config holdings list
