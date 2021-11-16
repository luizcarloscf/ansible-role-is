# ansible-role-kubernetes

Create or reset a kubernetes cluster using `kubeadm`.

## Role variables

Check [defaults/main.yaml](./defaults/main.yaml) to see configuration variables and default values. Default value are configure to create a control-plane node without isolation.

## Tests

Tested on:
  * ubuntu 20.04 LTS/amd64

## Example Playbook

```yaml
- hosts: all
  roles:
    - kubernetes
```

## References

* [Ansible role kubernetes](https://github.com/geerlingguy/ansible-role-kubernetes);