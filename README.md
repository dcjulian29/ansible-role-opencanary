# Ansible Role: opencanary

[![Lint](https://github.com/dcjulian29/ansible-role-opencanary/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-opencanary/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-opencanary.svg)](https://github.com/dcjulian29/ansible-role-opencanary/issues)

This an Ansible role to install and configure an OpenCanary honeypot.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.opencanary
  src: https://github.com/dcjulian29/ansible-role-opencanary.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
