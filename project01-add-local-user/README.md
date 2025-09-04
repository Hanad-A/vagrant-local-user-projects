# Project 01 – Add Local User

This project contains a Bash script to create a new local user on a Linux system.
The script includes error handling and requires sudo/root privileges.

# Features

Creates a local user with a username and full name

Sets a password for the new user

Forces password change at first login

Displays account details after creation

Exits with error messages if any step fails

# Requirements

Linux system with Bash

Sudo or root privileges

Usage
# Clone the repository
git clone https://github.com/<your-user>/vagrant-local-user-projects.git
cd vagrant-local-user-projects/project01-add-local-user

# Make the script executable
chmod +x add-local-user.sh

# Run the script with sudo
sudo ./add-local-user.sh


You will be prompted for:

Username

Full name

Password

Example Output
USERNAME : jdoe
COMMENT  : John Doe
HOST     : myhost.example.com

About

This script is part of my Linux scripting practice projects to build hands-on skills in user management, automation, and error handling.
