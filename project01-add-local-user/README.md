# Project 01 – Add Local User

This project contains a Bash script to create a new local user on a Linux system with a username, comment (full name or description), and password.  
The script ensures proper error handling and requires `sudo` privileges.

## Features
- Creates a local user with a username and full name/comment
- Sets a password for the new user
- Forces the user to change the password at first login
- Displays username, password, and host after successful creation
- Exits with error messages if any step fails

## Requirements
- Linux system with `bash` shell
- `sudo` privileges to run the script

## Usage
1. Open your terminal and navigate to the project directory:
   ```bash
   cd project01-add-local-user
