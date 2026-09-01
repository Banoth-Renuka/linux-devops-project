# Linux DevOps Project 🐧
## 📌 Project Overview
This project demonstrates a simulated Linux-based application server environment.
The objective of this project is to understand how application resources, configuration files, logs, backups, and operational scripts can be organized and managed on a Linux server using the command line.
This project was completed as part of my hands-on DevOps learning and internship practice.
---
## 🎯 Project Objectives
- Understand Linux file and directory organization
- Practice absolute and relative paths
- Create and manage application directories
- Create, copy, move, rename, and remove files
- Create and inspect application logs
- Search files and information using Linux commands
- Practice file permissions
- Create and manage backups
- Develop basic Bash scripts
- Understand basic Linux operations used in DevOps workflows
---
## 🏗️ Project Structure
```text
linux-devops-project/
│
├── application/
│   ├── source/
│   │   ├── app.py
│   │   └── README.md
│   │
│   ├── public/
│   │   ├── index.html
│   │   └── style.css
│   │
│   └── data/
│       ├── users.txt
│       └── products.txt
│
├── config/
│   ├── app.conf
│   └── database.conf
│
├── logs/
│   ├── application.log
│   ├── error.log
│   └── access.log
│
├── backup/
│   └── application-backup.tar.gz
│
└── scripts/
    ├── start.sh
    ├── stop.sh
    └── backup.sh
## 🛠️ Technologies & Tools

- Linux / Kali Linux
- Bash / Shell Scripting
- Git
- GitHub

## 🔧 Tasks Performed
- Created and organized application directories
- Managed files and directories using Linux commands
- Created application and configuration files
- Created and analyzed application logs
- Used `grep` and `find` for searching and troubleshooting
- Practiced file permissions using `chmod`
- Created compressed backups using `tar`
- Created and executed basic Bash scripts

## 📋 Linux Commands Practiced
```bash
mkdir
cd
pwd
ls
tree
touch
cp
mv
rm
cat
find
grep
tail
chmod
tar
df
du

🛠️ Technologies and Skills Used
Linux
Bash Scripting
Linux File System
File and Directory Management
Absolute and Relative Paths
Linux File Permissions
Log Management
File Search and Inspection
Disk Usage Monitoring
Backup and Archive Management
Command-Line Operations
Git
GitHub

1.Application Directory
The application/ directory contains the files and resources required for the simulated application.
Source
The source/ directory contains:
app.py – Sample application source file
README.md – Application-related documentation
Public
The public/ directory contains:
index.html – Sample HTML page
style.css – Sample CSS stylesheet
Data
The data/ directory contains:
users.txt – Sample user data
products.txt – Sample product data

2. Configuration Management
The config/ directory contains application configuration files.
app.conf – Application configuration
database.conf – Database configuration
This demonstrates how configuration files can be organized separately from application source code.

3.Log Management
The logs/ directory contains different types of application logs.
application.log – General application activity
error.log – Error-related messages
access.log – Application access information
Linux commands such as cat, tail, and grep were used to inspect and search log information.
 File Search and Inspection
Linux find and grep commands were used to search for files and information.
Examples:
find . -name "*.log"
find . -name "*.conf"
find . -name "*.txt"
find . -type d

4. Linux Navigation and Disk Usage
The following Linux commands were practiced:
pwd
cd
ls
df -h
du -sh .
These commands help with directory navigation and checking system and directory disk usage.

5. Backup Management
A compressed application backup was created using the tar command.
The application and config directories were archived into:
backup/application-backup.tar.gz
Example:
tar -czf backup/application-backup.tar.gz application config
The backup was verified using:
ls -lh backup/

6. Bash Automation Scripts
The scripts/ directory contains basic Bash scripts for application operations.
start.sh – Simulates starting the application
stop.sh – Simulates stopping the application
backup.sh – Automates the application backup process

The scripts were made executable using:
chmod +x scripts/*.sh
They can be executed using:
./scripts/start.sh
./scripts/stop.sh
./scripts/backup.sh

7. File Permissions
Linux file permissions were practiced using commands such as:
chmod +x scripts/*.sh
ls -l scripts/

 Key Learning Outcomes
Through this project, I gained hands-on experience with fundamental Linux and DevOps-related operations.
I learned how to:
Organize application files and directories
Work with absolute and relative paths
Create and manage files from the command line
Manage configuration files
Create and inspect log files
Search for files using Linux commands
Check disk and directory usage
Create compressed application backups
Understand Linux file permissions
Create and execute basic Bash scripts
Manage a project using Git and GitHub
