# Fail2Ban Role

Installs and starts Fail2Ban (Ubuntu only)

## Installation

To install the role:

```
ansible-galaxy role install chrissayon.fail2ban
```

## Role Variables

| Variable   | Description           |
| ---------- | --------------------- |
| remote_dir | Directory of Fail2Ban |

## Example Playbook

```
- hosts: all
  roles:
  - chrissayon.fail2ban
```
