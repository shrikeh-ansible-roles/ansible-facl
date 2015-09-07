# Ansible FACL installer
Role to install FACL on multiple *nix-based OSes.

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
