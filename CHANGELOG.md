# Ansible Role for Locales

## 4.2.0 - TBC

### Major Changes

  - `localectl set-locale` for CentOS/RHEL 7
  - `localectl set-locale` for openSUSE Leap 15.1

## 4.1.0 - 2020-01-16

### Major Changes

  - Default `interpreter_python` with `python3`
  - Bugfix `python3-xml` not exists for openSUSE Leap 15.1

## 4.0.0 - 2019-11-05

### Major Changes

  - Upgrade minimal Ansible support to 2.9.0
  - Upgrade Travis CI test as Ubuntu Bionic based

## 3.5.0 - 2019-10-06

### Major Changes

  - Support openSUSE Leap 15.1
  - Default with Python 3
  - Revamp molecule test with vagrant

## 3.4.0 - 2019-09-18

### Major Changes

  - Run molecule test manually on Travis CI

## 3.3.0 - 2019-08-27

### Major Changes

  - Update for RHEL 7
  - Add Vagrant test for RHEL 7

## 3.2.0 - 2019-07-08

### Major Changes

  - Update LXD test profile for Kubernetes v1.15.0 support
  - Fix molecule `group_vars` with links
  - Replace `with_items` with `loop`
  - Replace `with_dict` with `var`
  - Replace `with_first_found` with `lookup('first_found')`

## 3.1.0 - 2019-06-13

### Major Changes

  - Always include default variables from `vars/main.yml`
  - Always use `become: true` with molecule, especially for vagrant

## 3.0.0 - 2019-05-20

### Major Changes

  - Upgrade minimal Ansible support to 2.8.0

## 2.6.0 - 2019-05-04

### Major Changes

  - Refine Travis CI Molecue test cases

## 2.5.0 - 2019-04-17

### Major Changes

  - Run test with `travis_wait 120`

## 2.4.0 - 2019-03-03

### Major Changes

  - Add openSUSE Leap 15 support
  - Remove CentOS 6 support

## 2.3.0 - 2019-01-30

### Major Changes

  - Porting test to Molecule based

## 2.2.0 - 2019-01-25

  - Minor typo fix

## 2.1.0 - 2018-12-06

### Major Changes

  - CI with yamllint, ansible-lint and ansible-playbook --syntax-check
  - CI with LXD, improve systemd support
  - Use shell only when shell functionality is required
  - Source environment variables with `su -l -s /bin/bash -c`

## 2.0.0 - 2018-10-25

  - Ininitial release for Ansible 2.6
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 6/7
