# Ansible General Centos8
General Configuration for all Centos 8 systems.

### Summary
* Set the Hosname
* Set the Timezone
* Repositories
  * Add EPEL repository
  * Update all packages
* Optionally mount and format any block devices
* Optionally adjust the security cipher levels

### Variables
* hostname
* time_zone(default value -- US/Central)
* crypto_security_level(default value -- DEFAULT)

