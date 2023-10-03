# Load Balancer Project

This project focuses on setting up a load balancer to improve the redundancy and reliability of our web servers. It involves configuring Nginx with custom HTTP headers and installing and configuring HAProxy on the load balancer server.

## Table of Contents

- [General Information](#general-information)
- [Background Context](#background-context)
- [Resources](#resources)
- [Requirements](#requirements)
- [Tasks](#tasks)
- [Usage](#usage)
- [Files](#files)

## General Information

In this project, we will set up redundancy for our web servers by adding a second web server and placing them behind a load balancer. This will allow us to handle more traffic and increase the reliability of our infrastructure.

## Background Context

You have been provided with two additional servers:

- gc-[STUDENT_ID]-web-02-XXXXXXXXXX
- gc-[STUDENT_ID]-lb-01-XXXXXXXXXX

## Resources

- [Introduction to load-balancing and HAproxy](#)
- [HTTP header](#)
- [Debian/Ubuntu HAProxy packages](#)

## Requirements

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.3.7) without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Tasks

### Task 0: Double the number of webservers

- Configure web-02 to be identical to web-01.
- Add a custom Nginx response header with the name X-Served-By containing the hostname of the server.
- Write a Bash script to automate this process.

### Task 1: Install your load balancer

- Install and configure HAProxy on lb-01 server.
- Configure HAProxy to send traffic to web-01 and web-02 using a round-robin algorithm.
- Ensure HAProxy can be managed via an init script.
- Make sure servers are configured with the right hostnames: [STUDENT_ID]-web-01 and [STUDENT_ID]-web-02.

## Usage

Follow the instructions provided in each task's directory to complete the tasks. You can use the provided scripts and configuration files to achieve the desired results.

## Files

- `0-custom_http_response_header`: Bash script to configure Nginx with a custom HTTP header on web-01 and web-02.
- `1-install_load_balancer`: Bash script to install and configure HAProxy on lb-01.
