# Processes and Signals Project

## Overview
This project focuses on processes and signals in the context of DevOps, Shell, and Bash scripting. The project aims to improve your understanding of processes, their identification (PID), management, and how signals can be used to interact with processes.

## Learning Objectives
By completing this project, you are expected to be able to explain the following concepts without using external references:

- What is a PID?
- What is a process?
- How to find a process' PID?
- How to kill a process?
- What is a signal?
- Which are the two signals that cannot be ignored?

## Requirements
- Allowed editors: vi, vim, emacs
- All files will be interpreted on Ubuntu 20.04 LTS
- All files should end with a new line
- A `README.md` file at the root of the project folder is mandatory
- All Bash script files must be executable
- Bash scripts must pass Shellcheck (version 0.7.0 via apt-get) without any errors
- The first line of all Bash scripts should be `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining what the script does

## Project Tasks

### 0. What is my PID
Write a Bash script that displays its own PID.

### 1. List your processes
Write a Bash script that displays a list of currently running processes. The script should show all processes, for all users, including those which might not have a TTY. It should also display the process hierarchy.

### 2. Show your Bash PID
Write a Bash script that displays lines containing the word "bash," allowing you to easily get the PID of your Bash process. The script cannot use `pgrep`.

### 3. Show your Bash PID made easy
Write a Bash script that displays the PID, along with the process name, of processes whose name contains the word "bash." The script cannot use `ps`.

### 4. To infinity and beyond
Write a Bash script that displays "To infinity and beyond" indefinitely, with a sleep of 2 seconds between each iteration.

### 5. Don't stop me now!
Write a Bash script that stops the "To infinity and beyond" process started in the previous task.

### 6. Stop me if you can
Write a Bash script that stops the "To infinity and beyond" process started in Task 4. The script cannot use `kill` or `killall`.

### 7. Highlander
Write a Bash script that displays "To infinity and beyond" indefinitely, with a sleep of 2 seconds between each iteration. When receiving a SIGTERM signal, the script should display "I am invincible!!!"

### 8. Beheaded process
Write a Bash script that kills the "Highlander" process started in the previous task.

## Copyright and Plagiarism
Please note that plagiarism is strictly forbidden and will result in removal from the program. All solutions for the tasks should be developed by yourself to meet the learning objectives.


