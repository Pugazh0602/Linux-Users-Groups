# Linux-Users-Groups

## Introduction
**Linux is an open-source operating system that allows users to manage files, users, and system processes through commands. These commands are executed in a terminal.**

---------------------------------------------
| Command      | Description                 |
|-------------|-----------------------------|
| ls          | To list files or directories|
| cd          | To change/open a directory  |
| pwd         | To show current directory   |
| mkdir       | To create a new directory   |
| rmdir       | To remove an empty directory|
| touch       | To create an empty file     |
| cat         | To display file content     |
| echo        | To create file with content |
| cp          | To copy files or directories|
| mv          | To move/rename files        |
| rm          | To delete files             |
| whoami      | To show current user        |
| id          | To display user ID, group ID|
| groups      | To list groups of a user    |
| chmod       | To change file permissions  |
| chown       | To change file ownership    |
| su          | To switch user              |
| sudo        | To run commands as root     |
---------------------------------------------

## What is a user in linux ?

**A user in Linux is an account that allows a person or a process to log in and use the system.**

*Each user has:*

1. Their own username

2. A unique ID number (called UID)

3. A home directory (example: /home/centos)

4. Their own permissions and access rights to files

## Types of Users in Linux

| Type                            | Description                                                                        | Example                      |
| ------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------- |
| **Root User (Superuser)**       | Has full control of the system. Can install, remove, or modify anything.           | `root`                       |
| **Normal User**                 | Can use the system but has limited permissions.                                    | `centos`, `pugazh`           |
| **System/User Daemon Accounts** | Created by Linux for running background services like databases, web servers, etc. | `daemon`, `mail`, `www-data` |

