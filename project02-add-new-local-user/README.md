# Project 02 – Add New Local User (Arguments Version)

This project contains a Bash script to create a new local user on a Linux system.
Unlike Project 01 (interactive input), this script takes arguments directly from the command line.
The script includes error handling and requires sudo/root privileges.

# Features

Creates a local user with a username (argument)

Optionally sets a full name/comment (argument)

Automatically generates a random password

Forces password change at first login

Displays account details after creation

Exits with error messages if any step fails

# Requirements

Linux system with Bash

Sudo or root privileges

# Usage
# Clone the repository (download the project from GitHub)
git clone https://github.com/<your-user>/vagrant-local-user-projects.git

# Go into the project folder
cd vagrant-local-user-projects/project02-add-new-local-user

# Make the script executable
chmod +x add-new-local-user.sh

# Run the script with sudo and pass arguments
sudo ./add-new-local-user.sh <username> "<comment>"

Example
sudo ./add-new-local-user.sh jdoe "John Doe"


Output:

USERNAME : jdoe
COMMENT  : John Doe
PASSWORD : 8hd9dj3ksl29
HOST     : myhost.example.com

About

This script is part of my Linux scripting practice projects to build hands-on skills in automation, arguments handling, and error checking.

👉 Same as before: replace <your-user> with your actual GitHub username.
