# MySQL Project

## Table of Contents
- [Description](#description)
- [Tasks](#tasks)
- [Requirements](#requirements)
- [Usage](#usage)
- [Files](#files)
- [Author](#author)

---

## Description

This project focuses on MySQL installation, configuration, and management. It covers tasks such as setting up a primary-replica infrastructure, creating databases and tables, and implementing backup strategies.

---

## Tasks

1. [Install MySQL](./0x14-mysql/0-install_mysql)
   - Install MySQL 5.7.x on both web-01 and web-02 servers.

2. [Let us in!](./0x14-mysql/1-let_us_in)
   - Create a MySQL user named `holberton_user` on both web-01 and web-02 with the host name set to `localhost` and the password `projectcorrection280hbtn`.

3. [If only you could see what I've seen with your eyes](./0x14-mysql/2-what_i_see)
   - Create a database named `tyrell_corp` and a table named `nexus6` with at least one entry.

4. [Quite an experience to live in fear, isn't it?](./0x14-mysql/3-experience_of_fear)
   - Create a new user `replica_user` on web-01 for the replica server.

5. [Setup a Primary-Replica infrastructure using MySQL](./0x14-mysql/4-primary_replica_infrastructure)
   - Set up replication for the MySQL database named `tyrell_corp`.

6. [MySQL backup](./0x14-mysql/5-mysql_backup)
   - Write a Bash script that generates a MySQL dump and creates a compressed archive.

---

## Requirements

- Allowed editors: vi, vim, emacs
- All files are interpreted on Ubuntu 16.04 LTS
- All files should end with a new line
- Bash scripts must be executable
- Bash scripts must pass Shellcheck without any error
- The first line of all Bash scripts should be `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining what the script is doing

---

## Usage

1. Clone this repository:

```bash
git clone https://github.com/username/alx-system_engineering-devops.git

## Files

1. [0-install_mysql](./0x14-mysql/0-install_mysql): Install MySQL
2. [1-let_us_in](./0x14-mysql/1-let_us_in): Let us in!
3. [2-what_i_see](./0x14-mysql/2-what_i_see): If only you could see what I've seen with your eyes
4. [3-experience_of_fear](./0x14-mysql/3-experience_of_fear): Quite an experience to live in fear, isn't it?
5. [4-primary_replica_infrastructure](./0x14-mysql/4-primary_replica_infrastructure): Setup a Primary-Replica infrastructure using MySQL
6. [5-mysql_backup](./0x14-mysql/5-mysql_backup): MySQL backup

## Author
CHAIMAA HASSOUNE
