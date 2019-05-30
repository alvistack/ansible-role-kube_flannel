# Ansible Role for Flannel on Kubernetes

## 3.1.0 - TBC

### Major Changes

  - Always include default variables from `vars/main.yml`
  - Always use `become: true` with molecule, especially for vagrant
  - Replace `inventory_hostname` with `ansible_hostname`
  - Abstract `cni-conf.json` and `net-conf.json` with `to_nice_json()`

## 3.0.0 - 2019-05-20

  - Initial release for Ansible 2.8 or higher
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 7 or openSUSE Leap 15
