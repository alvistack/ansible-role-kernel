# Ansible Role for Kernel

## 2.4.0 - TBC

### Major Changes

  - Add openSUSE Leap 15 support

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
