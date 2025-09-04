# Project 03 – Add Newer Local User (Improved Version)

This project contains a Bash script to create a new local user on a Linux system.
It builds on Project 02 by improving error handling and logging.
The script takes arguments (username and optional comment), generates a random password, and requires sudo/root privileges.

# Features

Creates a local user with a username (argument)

Optionally sets a full name/comment (argument)

Automatically generates a random password

Forces password change at first login

Redirects command output to /dev/null for cleaner logs

Displays account details after creation

Exits with error messages if any step fails

# Requirements

Linux system with Bash

Sudo or root privileges

# Usage
# Clone the repository (download the project from GitHub)
git clone https://github.com/<your-user>/vagrant-local-user-projects.git

# Go into the project folder
cd vagrant-local-user-projects/project03-add-newer-local-user

# Make the script executable
chmod +x add-newer-local-user.sh

# Run the script with sudo and pass arguments
sudo ./add-newer-local-user.sh <username> "<comment>"

# Example
sudo ./add-newer-local-user.sh jdoe "John Doe"


# Output:

USERNAME : jdoe
COMMENT  : John Doe
PASSWORD : h9d8s7f6as1
HOST     : myhost.example.com

# About

This script is part of my Linux scripting practice projects to build hands-on skills in automation, arguments handling, error checking, and clean logging.

👉 As before, replace <your-user> with your actual GitHub username.
