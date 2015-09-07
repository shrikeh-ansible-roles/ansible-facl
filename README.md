# Ansible FACL installer
Role to install [FACL][facl] on multiple *nix-based OSes.

## Role Variables
---

####[`facl_pkg_state_latest`][facl_pkg_state_latest]
Default: `false`

Whether to use the latest version of the package or just ensure it is present.


## Example playbook
---

```YAML
%YAML 1.2
---
- hosts: production
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
