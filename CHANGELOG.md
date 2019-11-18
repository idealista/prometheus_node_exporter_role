# Prometheus Node Exporter Role changelog

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/) and [Keep a changelog](https://github.com/olivierlacan/keep-a-changelog).

## [Unreleased](https://github.com/idealista/prometheus_node_exporter_role/tree/develop)
## [4.0.1](https://github.com/idealista/prometheus_node_exporter_role/tree/4.0.1)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/4.0.0...4.0.1)
- *Fixed typos in vars* @frantsao
-
## [4.0.0](https://github.com/idealista/prometheus_node_exporter_role/tree/4.0.0)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/3.0.0...4.0.0)
- *[#32](https://github.com/idealista/prometheus_node_exporter_role/issues/32) Fixed systemd service configuration (changes default behaviour)* @frantsao
- *Linting and updated tests* @frantsao

## [3.0.0](https://github.com/idealista/prometheus_node_exporter_role/tree/3.0.0)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/2.2.0...3.0.0)
### Changed
- *[#25](https://github.com/idealista/prometheus_node_exporter_role/issues/25) Using '_' instead of '-' in role name* @jperera
### Added
- *Update node_exporter version, adding compatibility with 0.14 broken changes* @jmonterrubio
- *Add molecule 2 for testing purposes* @jmonterrubio

## [2.2.0](https://github.com/idealista/prometheus_node_exporter_role/tree/2.2.0)
### Changed
- *[#22](https://github.com/idealista/prometheus_node_exporter_role/issues/22) Add filefd collector by default* @jperera

## [2.1.0](https://github.com/idealista/prometheus_node_exporter_role/tree/2.1.0)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/2.0.0...2.1.0)
### Added
- *[#20](https://github.com/idealista/prometheus_node_exporter_role/pull/20) Add node_exporter_manage_service toggle to control service management* @kostyrev

## [2.0.0](https://github.com/idealista/prometheus_node_exporter_role/tree/2.0.0)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.2.6...2.0.0)
### Changed
- *[#17](https://github.com/idealista/prometheus_node_exporter_role/issues/17) Update imports (deprecation warnings)* @jmonterrubio

## [1.2.6](https://github.com/idealista/prometheus_node_exporter_role/tree/1.2.6)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.2.5...1.2.6)
### Fixed
- *[#15](https://github.com/idealista/prometheus_node_exporter_role/pull/15) Explicitly set get_url dest file name* @mvollman

## [1.2.5](https://github.com/idealista/prometheus_node_exporter_role/tree/1.2.5)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.2.4...1.2.5)
### Fixed
- *[#12](https://github.com/idealista/prometheus_node_exporter_role/issues/12) Group variable is not used when skeleton paths are created* @sorobon

## [1.2.4](https://github.com/idealista/prometheus_node_exporter_role/tree/1.2.4)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.2.3...1.2.4)
### Fixed
- *[#9](https://github.com/idealista/prometheus_node_exporter_role/issues/9) Fix PID logrotate check* @jmonterrubio

### Added
- *Add CI with Travis*

## [1.2.3](https://github.com/idealista/prometheus_node_exporter_role/tree/1.2.3)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.2.2...1.2.3)
### Fixed
- *[#5](https://github.com/idealista/prometheus_node_exporter_role/issues/5) Fix check version* @jmonterrubio

## [1.2.2](https://github.com/idealista/prometheus_node_exporter_role/tree/1.2.2)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.2.1...1.2.2)
### Fixed
- *[#2](https://github.com/idealista/prometheus_node_exporter_role/issues/2) Fix user shell* @jmonterrubio

## [1.2.1](https://github.com/idealista/prometheus_node_exporter_role/tree/1.2.1)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.2.0...1.2.1)
### Fixed
- *Fix logrotate* @jmonterrubio

## [1.2.0](https://github.com/idealista/prometheus_node_exporter_role/tree/1.2.0)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.1.1...1.2.0)
### Added
- *[PLATFORM-295] Parametrizado de puerto y path*

## [1.1.1](https://github.com/idealista/prometheus_node_exporter_role/tree/1.1.1)
[Full Changelog](https://github.com/idealista/prometheus_node_exporter_role/compare/1.1.0...1.1.1)
### Added
- *[PLATFORM-162] Cambiar los "collectors" activos por defecto y filtrar sus características, subir de versión node_exporter*

## [1.1.0]
### Added
- *Utilizar systemd con ansible*
