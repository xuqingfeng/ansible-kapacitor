## Ansible-Kapacitor
> an ansible role to install, configure and manage [Kapacitor](https://www.influxdata.com/time-series-platform/kapacitor/)

[![xuqingfeng.kapacitor](https://img.shields.io/badge/role-xuqingfeng.kapacitor-blue.svg?style=flat-square)](https://galaxy.ansible.com/xuqingfeng/kapacitor/)

### Installation

`ansible-galaxy install xuqingfeng.kapacitor -p roles`

### Role Variables

```yaml
# vars/main.yml
kapacitor_version: 1.0.2 # kapacitor version number

# default/main.yml
# ...
```
### Dependencies

### Example Playbook

```yaml
- hosts: server
  roles:
    - xuqingfeng.kapacitor
```





