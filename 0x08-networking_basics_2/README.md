# Networking Basics #1 Project

This project is part of the DevOps course and focuses on networking basics, including configuring IP addresses and working with network interfaces. The tasks involve creating Bash scripts to achieve specific networking configurations and functionalities.

## Table of Contents

- [Introduction](#introduction)
- [Resources](#resources)
- [Requirements](#requirements)
- [Tasks](#tasks)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, you will work with networking basics, including configuring IP addresses, displaying active network interfaces, and working with ports on localhost. You'll create Bash scripts to achieve various networking tasks.

## Resources

For this project, you may find the following resources helpful:

- [What is localhost](https://en.wikipedia.org/wiki/Localhost)
- [What is 0.0.0.0](https://en.wikipedia.org/wiki/0.0.0.0)
- [What is the hosts file](https://en.wikipedia.org/wiki/Hosts_(file))
- [Netcat examples](https://www.tecmint.com/netcat-nc-command-examples/)
- `ifconfig` - network interface configuration utility
- `telnet` - network protocol for establishing a TCP/IP connection
- `nc` - netcat, a versatile networking utility
- `cut` - remove sections from each line of files

## Requirements

- Allowed editors: vi, vim, emacs
- Files will be interpreted on Ubuntu 20.04 LTS
- Files should end with a new line
- A README.md file at the root of the project folder is mandatory
- All Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.7.0 via apt-get) without any errors
- The first line of all Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining what the script is doing

## Tasks

The project consists of the following tasks:

0. [Change Your Home IP](./0-change_your_home_IP): Create a Bash script that configures an Ubuntu server to change IP configurations.
1. [Show Attached IPs](./1-show_attached_IPs): Create a Bash script that displays all active IPv4 IPs on the machine it’s executed on.
2. [Port Listening on Localhost](./100-port_listening_on_localhost): Create a Bash script that listens on port 98 on localhost.

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/0x08-networking_basics_2.git
   cd 0x08-networking_basics_2

