# This is ansible playbook for Apache Ambari 2.6.1.5 for Ubuntu Xenial. #

## How to use ##

1. Modify `hosts` file for your own connection way.
   Remember define `connection_interface` for every host to specify network interface which host used to connect to each other.

2. Execute playbook, `main.yml`.