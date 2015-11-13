# Ansible FACL installer
[![Ansible Role](https://img.shields.io/ansible/role/3973.svg)](https://galaxy.ansible.com/detail#/role/3973)
[![Build Status](https://travis-ci.org/shrikeh/ansible-facl.svg)](https://travis-ci.org/shrikeh/ansible-facl)

Role to install [FACL][facl] on multiple *nix-based OSes.

## Role Variables
---

####[`facl_pkg_state_latest`][facl_pkg_state_latest]
Default: `false`

Whether to use the latest version of the package or just ensure it is present.


## Example playbook
---

```YAML
---
- hosts: production
  vars:
    facl_pkg_state_latest: no
  roles:
    - { role: shrikeh.facl }
...
```

## License
-------

[MIT][licence]

## Author Information
------------------
Contact me on Twitter @[barney_hanlon][twitter]

[facl]: https://help.ubuntu.com/community/FilePermissionsACLs
[facl_pkg_state_latest]: https://github.com/shrikeh/ansible-facl/blob/master/defaults/main.yml#L3
[licence]: https://raw.githubusercontent.com/shrikeh/ansible-jumpcloud/master/LICENSE
[twitter]: https://twitter.com/barney_hanlon "Link to my Twitter page"
