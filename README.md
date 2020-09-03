# V2ray Ansible Role

[![Travis (.com)](https://img.shields.io/travis/com/Ghermezi/ansible-role-v2ray?logo=travis&style=flat-square)](https://travis-ci.com/github/Ghermezi/ansible-role-v2ray)

## Introduction

Ansible rule based on [fhs-install-v2ray](https://github.com/v2fly/fhs-install-v2ray) for installing v2ray.
v2ray is a core of Project V.

## Usage

Define v2ray as requirement in your playbook then you can use it.

```yml
# requirements.yaml
- src: git@github.com:Ghermezi/ansible-role-v2ray.git
  scm: git
  version: master
  name: v2ray
```
