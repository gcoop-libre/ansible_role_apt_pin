# Ansible Role: gcoop-libre.apt_pin

This role, pinning apt packages

## Requirements

None.

## Role Variables

Available variables with default values in `defaults/main.yml`.

## Dependencies

None.

## Example Playbook

If you want to pinning apt packages.

```yaml
---

- name: install apt_pin
  hosts: [all]

  roles:
    - role: gcoop-libre.apt_pin
      apt_pin_packages:
        - name: proxmox-ve
          version: '6.2-2'
        - name: pve-manager
          version: '6.2-15'
```

## License

GNU General Public License, GPLv3.

## Author Information

This role was created in 2020 by
 [Osiris Alejandro Gomez](https://osiux.com/), worker cooperative of
 [gcoop Cooperativa de Software Libre](https://www.gcoop.coop/).
