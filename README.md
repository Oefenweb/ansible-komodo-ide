## komodo-ide

[![Build Status](https://travis-ci.org/Oefenweb/ansible-komodo-ide.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-komodo-ide)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-komodo--ide-blue.svg)](https://galaxy.ansible.com/Oefenweb/ansible-komodo-ide)

Set up [Komodo IDE](http://komodoide.com/) by ActiveState in Debian-like systems.

#### Requirements

* `unzip` (will be installed)

#### Variables

* `komodo_ide_version` [default: `8.5.4`]: Version to install
* `komodo_ide_build` [default: `86985`]: Build to install
* `komodo_ide_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - komodo-ide
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-komodo-ide/issues)!
