# Ansible Role for Kernel

## 2.1.0 - TBC

### Major Changes

  - CI with ansible-lint and galaxy-lint-rules
  - Use shell only when shell functionality is required
  - Replace tests from Docker to LXD
  - Assume ELRepo already enabled

## 2.0.0 - 2018-11-18

  - Initial release for Ansible 2.6 or higher
  - Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
  - Install HWE kernel on Ubuntu 16.04 from official repository
  - Install standard kernel on Ubuntu 18.04 from official repository
  - Install mainline kernel on CentOS 6/7 from ELRepo
