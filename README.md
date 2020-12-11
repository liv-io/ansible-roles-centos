# ansible-roles-centos

<!-- shields.io -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![BSD License][license-shield]][license-url]

## Index

* [Announcement](#announcement)
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

## Announcement

Since [RedHat](https://www.redhat.com/de/blog/centos-stream-building-innovative-future-enterprise-linux) :middle_finger: is [destorying CentOS](https://blog.centos.org/2020/12/future-is-centos-stream/), it is about time to migrate to [Debian](https://github.com/liv-io/ansible-roles-debian) and contribute the a fully community-driven Linux distribution.

Please find the Debian Ansible roles [here](https://github.com/liv-io/ansible-roles-debian).

## About

`ansible-roles-centos` is a collection of well curated Ansible roles for the CentOS Linux distribution. All Ansible roles are licensed under the Simplified BSD License.

### Features

* Configurations follow the secure-by-default principle
* Roles are mostly self-contained and dependencies avoided
* Roles and services support multiple states (install, remove, enable, disable, inactive)
* Scripts and cronjobs support multiple states (enable, disable)
* Services can be monitored with Monit and exported via monit_exporter to Prometheus
* Scripts support Email and Prometheus monitoring
* Logs can be forwarded with syslog to Loki
* Roles can proxy HTTP/HTTPS traffic through Squid forward proxy
* Host-based firewall restricts ingress and egress traffic by default
* Restic and rest-server are available as backup solution
* Chrony is configurable as NTP client and server
* Unbound is available as resolving DNS server
* NSD is available as authoritative DNS server
* Prometheus has built-in alerting rules and Grafana dashboards
* Loki has built-in alerting rules and Grafana dashboards
* Parameters are documented with examples and marked when implemented
* Changes adhere to semantic versioning guidelines
* Roles contain changelog

### Support

The following operating systems are supported:
* CentOS 7
* CentOS 8

### Dependencies

The Ansible control machine depends on:
* [Ansible](https://github.com/ansible/ansible) >= 2.8.0

The Ansible managed node depends on:
* [Python](https://github.com/python/cpython) >= 2.7.0

## Setup

### Requirements

### Installation

## Usage

## Roadmap

* Add Ansible roles (certificates, ca_trust, logrotate, networking, routes)
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

### Loki/Grafana Dashboards

| Suricata |
| --- |
| <img src=https://user-images.githubusercontent.com/19646270/101278206-40784280-37ba-11eb-8108-54231ae62679.png height="200" title="Suricata"> |

### Prometheus/Grafana Dashboards

| System Status | Script Status |
| --- | --- |
| <img src=https://user-images.githubusercontent.com/19646270/101277238-57fffd00-37b3-11eb-8fc4-3dc013536e37.png height="200" title="System Status"> | <img src=https://user-images.githubusercontent.com/19646270/101277235-546c7600-37b3-11eb-8561-303f2b62d178.png height="200" title="Script Status"> |

| Network Traffic | Ping Prober |
| --- | --- |
| <img src=https://user-images.githubusercontent.com/19646270/101277644-32282780-37b6-11eb-9131-5a58aae74f42.png height="200" title="Network Traffic"> | <img src=https://user-images.githubusercontent.com/19646270/101277645-33595480-37b6-11eb-841f-68738ca45693.png height="200" title="Ping Prober"> |

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
