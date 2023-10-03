# SSH Project

This project focuses on SSH (Secure Shell) and covers various aspects of using SSH for secure remote access to servers. It includes scripts and configurations to help you understand and implement SSH-related tasks.

## Table of Contents

- [General Information](#general-information)
- [Tasks](#tasks)
- [Files](#files)


## General Information

SSH is a protocol used for secure remote access to servers. This project aims to provide a hands-on learning experience for various SSH-related tasks, including creating SSH key pairs, configuring SSH clients, and setting up SSH access to a server.

## Tasks

This project consists of the following tasks:

1. [Use a private key](./0-use_a_private_key): Connect to your server using a private key.
2. [Create an SSH key pair](./1-create_ssh_key_pair): Generate an RSA key pair.
3. [Client configuration file](./2-ssh_config): Configure the SSH client to use a private key and refuse password authentication.
4. [Let me in!](./3-let_me_in): Add a public key to the server to allow access.

## Files

- `0-use_a_private_key`: Bash script to connect to a server using a private key.
- `1-create_ssh_key_pair`: Bash script to generate an RSA key pair.
- `2-ssh_config`: SSH client configuration file.
- `3-let_me_in`: SSH public key to be added to the server.
