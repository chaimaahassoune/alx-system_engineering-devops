# Project: Firewall

## Overview

This project focuses on implementing firewall rules on the web servers to enhance security and control incoming traffic. The tasks involve configuring the `ufw` firewall on the `web-01` server.

## Concepts

- Web stack debugging
- Firewall configuration

## Tasks

### Task 0: Block all incoming traffic but (Mandatory)

- Description: Install and configure the `ufw` firewall on `web-01` to block all incoming traffic except for specific TCP ports (22, 80, and 443).
- File: [0-block_all_incoming_traffic_but](./0x13-firewall/0-block_all_incoming_traffic_but)

### Task 1: Port forwarding (Advanced)

- Description: Configure `web-01` to forward traffic from port 8080/TCP to port 80/TCP using the firewall.
- File: [100-port_forwarding](./0x13-firewall/100-port_forwarding)

## Usage

### Task 0:

1. SSH into `web-01` server.
2. Execute the following commands to configure the firewall:

