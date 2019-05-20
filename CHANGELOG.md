# Ansible Role for Kernel

## 3.1.0 - TBC

### Major Changes

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

### CentOS

  - Manually enable ELRepo
  - Install `kernel-lt`

## 2.1.0 - 2018-12-06

### Major Changes

  - CI with yamllint, ansible-lint and ansible-playbook --syntax-check
  - CI with LXD, improve systemd support
  - Use shell only when shell functionality is required

### CentOS

  - Don't install elrepo-release, assume yum already handle it

## 2.0.0 - 2018-11-18

  - Initial release for Ansible 2.6 or higher
  - Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
  - Install HWE kernel on Ubuntu 16.04 from official repository
  - Install standard kernel on Ubuntu 18.04 from official repository
  - Install mainline kernel on CentOS 6/7 from ELRepo
