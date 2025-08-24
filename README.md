# Vagrant Local User Projects

This repository contains three small Vagrant/Bash labs for creating local Linux users in different scenarios.

## Projects
- **Project 01**: add-local-user
- **Project 02**: add-new-local-user
- **Project 03**: add-newer-local-user

### How to run any project
1. `cd projectXX-*`
2. `vagrant up && vagrant ssh`
3. Inside the VM: `cd /vagrant` and run the script, e.g. `./add-local-user.sh USER "Comment"`

Each folder includes its own `Vagrantfile` and script.
