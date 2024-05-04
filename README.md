# Ansible role kubevirt

The Ansible role to install kubevirt.

## Example playbook

```yaml
- name: Install kubevirt
  hosts: all
  roles:
    - role: devops13242.kubevirt
```

## Parameters

* `kubevirt_version` - set the version of kubevirt. Default value - v1.2.0.
* `cdi_version` - set the version of cdi. Default value - v1.59.0.



