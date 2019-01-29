![Logo](https://raw.githubusercontent.com/idealista/node_exporter_role/master/logo.gif)

[![Build Status](https://travis-ci.org/idealista/node_exporter_role.png)](https://travis-ci.org/idealista/node_exporter_role)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-idealista.node_exporter_role-B62682.svg)](https://galaxy.ansible.com/idealista/node_exporter_role)

# Prometheus Node Exporter Ansible role

This ansible role installs a Prometheus Node Exporter in a Debian environment.

- [Getting Started](#getting-started)
	- [Prerequisities](#prerequisities)
	- [Installing](#installing)
- [Usage](#usage)
- [Testing](#testing)
- [Built With](#built-with)
- [Versioning](#versioning)
- [Authors](#authors)
- [License](#license)
- [Contributing](#contributing)

## Getting Started

These instructions will get you a copy of the role for your Ansible playbook. Once launched, it will install an [Prometheus Node Exporter](https://github.com/prometheus/node_exporter) server in a Debian system.

### Prerequisities

Ansible 2.4.5.0 version installed.
Inventory destination should be a Debian environment.

For testing purposes, [Molecule](https://molecule.readthedocs.io/) with [Docker](https://www.docker.com/) as driver.

### Installing

Create or add to your roles dependency file (e.g requirements.yml):

```
- src: idealista.prometheus_node_exporter_role
  version: 1.0.0
  name: prometheus_node_exporter
```

Install the role with ansible-galaxy command:

```
ansible-galaxy install -p roles -r requirements.yml -f
```

Use in a playbook:

```
---
- hosts: someserver
  roles:
    - role: prometheus_node_exporter
```

## Usage

Look to the [defaults](defaults/main.yml) properties file to see the possible configuration properties.

## Testing

```
molecule test
```

## Built With

![Ansible](https://img.shields.io/badge/ansible-2.4.3.0-green.svg)
![Molecule](https://img.shields.io/badge/molecule-2.19.0-green.svg)

## Versioning

For the versions available, see the [tags on this repository](https://github.com/idealista/prometheus_node_exporter_role/tags).

Additionaly you can see what change in each version in the [CHANGELOG.md](CHANGELOG.md) file.

## Authors

* **Idealista** - *Work with* - [idealista](https://github.com/idealista)

See also the list of [contributors](https://github.com/idealista/prometheus_node_exporter_role/contributors) who participated in this project.

## License

![Apache 2.0 License](https://img.shields.io/hexpm/l/plug.svg)

This project is licensed under the [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) license - see the [LICENSE](LICENSE) file for details.

## Contributing

Please read [CONTRIBUTING.md](.github/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
