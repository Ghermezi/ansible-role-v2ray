# V2ray Ansible Role

[![Travis (.com)](https://img.shields.io/travis/com/Ghermezi/ansible-role-v2ray?logo=travis&style=flat-square)](https://travis-ci.com/github/Ghermezi/ansible-role-v2ray)

## Introduction

Ansible Role based on [fhs-install-v2ray](https://github.com/v2fly/fhs-install-v2ray) for installing v2ray.
v2ray is a core of Project V.

## Installation

```yml
# requirements.yaml
- src: git@github.com:Ghermezi/ansible-role-v2ray.git
  scm: git
  version: master
  name: v2ray
```

## Role Variables

``` yaml
v2ray_version: v4.27.5
v2ray_config_template: "{{ playbook_dir }}/templates/config.json.j2"
```

## Example Playbook

``` yaml
- hosts: servers
  roles:
    - v2ray
```
