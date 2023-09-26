# Web Server Configuration Project

Welcome to the Web Server Configuration Project. In this project, you will learn how to set up and configure a web server using Ubuntu 16.04 and Nginx. This project consists of several tasks, each with its own set of requirements.

## Table of Contents
1. [Task 0: Transfer a File to Your Server](#task-0-transfer-a-file-to-your-server)
2. [Task 1: Install Nginx Web Server](#task-1-install-nginx-web-server)
3. [Task 2: Setup a Domain Name](#task-2-setup-a-domain-name)
4. [Task 3: Redirection](#task-3-redirection)
5. [Task 4: Not Found Page 404](#task-4-not-found-page-404)

## Task 0: Transfer a File to Your Server
- Write a Bash script that transfers a file from your client to a server.
- Requirements:
  - Accepts 4 parameters: the path to the file, the server's IP, the username for SCP, and the path to the SSH private key.
  - Display usage if fewer than 3 parameters are passed.
  - Use SCP to transfer the file to the user's home directory.
  - Disable strict host key checking when using SCP.

## Task 1: Install Nginx Web Server
- Install Nginx on your web-01 server.
- Nginx should listen on port 80.
- A GET request to the root path should return a page containing the string "Hello World!"
- Write a Bash script to configure a new Ubuntu machine to meet these requirements.

## Task 2: Setup a Domain Name
- Provide a domain name (e.g., yourdomain.tech).
- Configure DNS records with an A entry pointing to your web-01 server's IP.
- Enter your domain in the Project website URL field.
- Wait for DNS propagation (typically 1-2 hours).

## Task 3: Redirection
- Configure Nginx to redirect /redirect_me to another page with a "301 Moved Permanently" status.
- Write a Bash script to automate this configuration on a new Ubuntu machine.

## Task 4: Not Found Page 404
- Configure Nginx to have a custom 404 page containing the string "Ceci n'est pas une page."
- Write a Bash script to automate this configuration on a new Ubuntu machine.

## Resources
- [How the web works](#)
- [Nginx Documentation](#)
- [Child Process Concept](#)
- [DNS Basics](#)
- [RFC 7231 (HTTP/1.1)](#)
- [RFC 7540 (HTTP/2)](#)
- [SCP Documentation](#)
- [curl Documentation](#)

## Important Notes
- Make sure to follow the project requirements and instructions for each task.
- All Bash scripts should be executable and well-commented.
- Use Ubuntu 16.04 LTS for all tasks.
- Ensure your scripts pass Shellcheck without errors.
- You are not allowed to use systemctl for restarting processes.

## Author
- [Chaimaa Hassoune]

**Copyright © 2023 ALX, All rights reserved.**

