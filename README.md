# Ansible Role: onedrive

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.onedrive.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.onedrive) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-onedrive-blue.svg)](https://galaxy.ansible.com/sbaerlocher/onedrive)

## Description

Disables or removes Microsoft OneDrive on a Windows 10 device.

## Installation

```bash
ansible-galaxy install sbaerlocher.onedrive
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| onedrive_disable | true | Disables OneDrive in the registry. |
| onedrive_remove | false | Uninstalls OneDrive on the device. |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.onedrive
```

## Changelog

### 1.0

* inital commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher