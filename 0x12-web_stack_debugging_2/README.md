# Web Stack Debugging #2

This project involves debugging tasks related to web server configuration and user privileges.

## Table of Contents
* [General Info](#general-info)
* [Tasks](#tasks)
  * [Task 0: Run Software as Another User](#task-0-run-software-as-another-user)
  * [Task 1: Run Nginx as Nginx](#task-1-run-nginx-as-nginx)
* [Setup](#setup)
* [Usage](#usage)
* [Scripts](#scripts)
* [License](#license)

## General Info

In this project, we aim to fix specific issues related to web server setup and user privileges. Each task has its own set of requirements that need to be met.

## Tasks

### Task 0: Run Software as Another User

* Description: This task involves writing a Bash script that accepts one argument and runs the `whoami` command under the user passed as an argument.
* Example Usage: `./0-iamsomeoneelse www-data`

### Task 1: Run Nginx as Nginx

* Description: This task focuses on configuring Nginx to run as the less privileged `nginx` user instead of the root user. Additionally, Nginx should be listening on all active IPs on port 8080.
* Requirements:
  - Nginx must be running as `nginx` user
  - Nginx must be listening on all active IPs on port 8080
  - Cannot use `apt-get remove`

## Setup

All tasks are designed to be completed on an Ubuntu 20.04 LTS system. Ensure you have the necessary permissions to execute scripts.

## Usage

1. Clone this repository to your local machine.
2. Navigate to the respective task directory.
3. Execute the Bash script using the command `./script_name argument` where `script_name` is the name of the script and `argument` is the user (for Task 0) or no arguments needed (for Task 1).

## Scripts

* `0-iamsomeoneelse`: Bash script for Task 0.
* `1-run_nginx_as_nginx`: Bash script for Task 1.

## License

This project is licensed under the [MIT License](LICENSE).

