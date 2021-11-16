# Ansible role: Swap

Simple ansible role that disables or re-enables swap on a linux machine.

## Tests

Tested on:
    - ubuntu 20.04 LTS

## Example Playbook

```yaml
- hosts: all
  vars:
    swap_state: 'enable'
  roles:
    - swap
```
