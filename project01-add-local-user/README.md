# Project 01 – add-local-user

Creates a local Linux user with a comment and password handling.

## Run
1. `vagrant up && vagrant ssh`
2. `cd /vagrant`
3. `./add-local-user.sh USERNAME "Full Name or Comment"`

## Notes
- Requires sudo privileges inside the VM.
- Script prints username/host on success; exits non-zero on failure.
