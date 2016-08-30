## strongswan

[![Build Status](https://travis-ci.org/Oefenweb/ansible-haproxy.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-haproxy) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-haproxy-blue.svg)](https://galaxy.ansible.com/tersmitten/haproxy)

Set up Strongswan [Strongswan](https://www.strongswan.org//) in Ubuntu systems.

#### Requirements

* `python-apt`

#### Variables

* `ikelifetime`: [default: `1h`]: Version to install (e.g. `1.5`, `1.6`)
* `lifetime`: [default: `20m`]: Version to install (e.g. `1.5`, `1.6`)
* `margintime`: [default: `3m`]: Version to install (e.g. `1.5`, `1.6`)
* `keyingtries`: [default: `1`]: Version to install (e.g. `1.5`, `1.6`)
* `authby`: [default: `secret`]: Version to install (e.g. `1.5`, `1.6`)
* `keyexchange`: [default: `ikev2`]: Version to install (e.g. `1.5`, `1.6`)
* `mobike`: [default: `no`]: Version to install (e.g. `1.5`, `1.6`)
* `left`: [default: `192.168.0.1`]: Version to install (e.g. `1.5`, `1.6`)
* `leftsubnet`: [default: `10.1.0.0/16`]: Version to install (e.g. `1.5`, `1.6`)
* `leftid`: [default: `@moon.strongswan.org`]: Version to install (e.g. `1.5`, `1.6`)
* `leftfirewall`: [default: `yes`]: Version to install (e.g. `1.5`, `1.6`)
* `right`: [default: `192.168.0.2`]: Version to install (e.g. `1.5`, `1.6`)
* `rightsubnet`: [default: `10.2.0.0/16`]: Version to install (e.g. `1.5`, `1.6`)
* `rightid`: [default: `@sun.strongswan.org`]: Version to install (e.g. `1.5`, `1.6`)
* `psk`: [default: `changeoninstall`]: Version to install (e.g. `1.5`, `1.6`)

## Dependencies

None

#### SSL Termination 1

* **Single core**
* Multiple certificates (SNI)
* Global monitoring
* Multiple web servers

#### License

MIT

#### Author Information

Janne Ojala

#### Issues

Are [welcome](https://github.com/janneojala/ansible-strongswan/issues)!
