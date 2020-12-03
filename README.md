# ansible-roles-centos

<!-- shields.io -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![BSD License][license-shield]][license-url]

## Index

* [About](#about)
  * [Features](#features)
  * [Support](#support)
  * [Dependencies](#dependencies)
* [Setup](#setup)
  * [Requirements](#requirements)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Credits](#credits)
* [Appendix](#appendix)

## About

`ansible-roles-centos` is a collection of well curated Ansible roles for the CentOS Linux distribution. The Ansible roles are licensed under the Simplified BSD License.

### Features

* Configurations follow the secure-by-default principle
* Roles are mostly self-contained and dependencies avoided
* Roles and services support multiple states (install, remove, enable, disable, inactive)
* Scripts and cronjobs support multiple states (enable, disable)
* Services can be monitored with Monit and exported via monit_exporter to Prometheus
* Scripts support Email and Prometheus monitoring
* Logs can be forwarded with syslog to Loki
* Prometheus has built-in alerting rules and Grafana dashboards
* Loki has built-in alerting rules and Grafana dashboards
* Restic and rest-server can be used to backup machines
* Time can be synchronized with NTP client
* Host-based firewall restricts ingress and egress traffic by default
* Roles can proxy HTTP/HTTPS traffic through Squid forward proxy
* Parameters are documented with examples and marked when implemented
* Changes adhere to semantic versioning guidelines
* Roles contain changelog

### Support

The Ansible roles support the following operating systems:
* CentOS 7
* CentOS 8

### Dependencies

The Ansible control machine depends on:
* [Ansible](https://github.com/ansible/ansible) >= 2.8

The Ansible managed node depends on:
* [Python](https://github.com/python/cpython) >= 2.7

## Setup

### Requirements

### Installation

## Usage

## Roadmap

* Add Ansible roles to manage certificates and ca_trust
* Add Ansible role to manage logrotate
* Add Ansible roles configure network interfaces and routes
* Support monitoring via Coremon

## Contributing

## License

Distributed under the Simplified BSD License.

See `LICENSE` file for more information.

## Contact

Author: l@liv.io

Project: [ansible-roles-centos](https://github.com/liv-io/ansible-roles-centos)

## Credits

See `CREDITS` file for more information.

## Appendix

<!-- shields.io -->
[contributors-shield]: https://img.shields.io/github/contributors/liv-io/ansible-roles-centos.svg?style=flat
[contributors-url]: https://github.com/liv-io/ansible-roles-centos/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/liv-io/ansible-roles-centos.svg?style=flat
[forks-url]: https://github.com/liv-io/ansible-roles-centos/network/members
[stars-shield]: https://img.shields.io/github/stars/liv-io/ansible-roles-centos.svg?style=flat
[stars-url]: https://github.com/liv-io/ansible-roles-centos/stargazers
[issues-shield]: https://img.shields.io/github/issues/liv-io/ansible-roles-centos.svg?style=flat
[issues-url]: https://github.com/liv-io/ansible-roles-centos/issues
[license-shield]: https://img.shields.io/github/license/liv-io/ansible-roles-centos.svg?style=flat
[license-url]: https://github.com/liv-io/ansible-roles-centos/blob/master/LICENSE
