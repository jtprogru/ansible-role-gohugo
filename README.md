# jtprogru.gohugo

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-gohugo/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-gohugo/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-gohugo)
[![Ansible Role](https://img.shields.io/ansible/role/60383)](https://galaxy.ansible.com/jtprogru/gohugo/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/ansible-role-gohugo.svg)](https://github.com/jtprogru/ansible-role-gohugo/tags)

Simple role for install [Hugo](https://gohugo.io)

## Role Variables

See [`defaults/main.yml`](defaults/main.yml).

## Example Playbook

Example playbook:

```yaml
---
- name: Installing gohugo
  hosts: all
  become: true

  vars:
    gohugo_version: '0.103.1'

  roles:
    - jtprogru.gohugo
```

## License

See [LICENSE](LICENSE.md)
