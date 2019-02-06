# An ansible role for setting up a package repo [![Build Status](https://travis-ci.com/mafalb/ansible-package_repo.svg?branch=master)](https://travis-ci.com/mafalb/ansible-package_repo)

## Basic Usage

```
# install epel
#
- hosts: localhost
  roles:
    - role: package_repo/epel
```

```
# install zabbix repo for zabbix 3.4
#
- hosts: localhost
  roles:
    - role: mafalb.package_repo/zabbix
      package_repo_version: 3.4
```

## Variables


the name of the package
```
package_repo_is_enabled: true|false
```

override the repo specific default value


## License

GPLv3

