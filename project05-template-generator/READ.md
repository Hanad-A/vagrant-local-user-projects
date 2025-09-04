# Project 04 – Ping Script (Multiple Hosts)

This project contains a Bash script that pings multiple remote hosts from a list.
It checks network connectivity and prints whether each host is reachable.

# Features

Reads a list of IPs/hostnames from a file

Pings each host one by one

Prints OK if the host is reachable, NOT OK if it is not

Redirects ping output to /dev/null for cleaner logs

# Requirements

Linux system with Bash

A text file containing the list of hosts/IPs (one per line)

# Usage

Create a host file (example: myhosts):

8.8.8.8
1.1.1.1
example.com


Update the script variable to point to your file:

hosts="/home/<your-user>/myhosts"


Run the script:

chmod +x ping-script-all
./ping-script-all

Example Output
8.8.8.8 OK
1.1.1.1 OK
example.com NOT OK

# About

This script is part of my Linux scripting practice projects to build hands-on skills in network troubleshooting and automation.

👉 Replace <your-user> with your Linux username in the script path.
