# An Ubuntu, Ansible, and AppDynamics Configuration

The purpose of this repo is to provide a template for rapidly configuring an Ubuntu 18.04 machine with AppDynamics using Ansible.

You are free to copy the initial configurations, add your variables to the project, and extend the playbook as you see fit to accomplish your objectives.

## Minimal Configuration

1. Have a target host configured running Ubuntu 18.04.
2. Copy `ansible/inventory.ini.dist` to `ansible/inventory.ini`.
3. Update your `inventory.ini` according to your host details.
4. Copy `ansible/variables.json.dist` to `ansible/variables.json`. 
5. Add or remove any specific data you'd like to in `ansible/variables.json`.
6. Ensure `bin/ap` is executable, and run it!
