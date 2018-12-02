# An ansible role for setting up a package repo [![Build Status](https://travis-ci.com/mafalb/ansible-package_repo.svg?branch=master)](https://travis-ci.com/mafalb/ansible-package_repo)

## Basic Usage

```
- hosts: localhost
  - role: package_repo
      package_repo_name: epel
```

## Variables

```
package_repo_name: epel
```

the name of the package
```
package_repo_is_enabled: true|false
```

override the repo specific default value

```
package_repo_gpgcheck: true
```

you can disable the default signature checking

## License

GPLv3

