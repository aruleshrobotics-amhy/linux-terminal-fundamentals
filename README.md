# 📘 Linux Terminal Fundamentals

A structured beginner-friendly guide to mastering essential Linux
terminal commands. This repository is part of a daily Linux grind toward
Robotics & System Development mastery.

------------------------------------------------------------------------

#  Linux Terminal Fundamentals

## 📍 Navigation Commands

  Section               Command            What It Does                    Example
  --------------------- ------------------ ------------------------------- ----------------
  Show Current Folder   `pwd`              Prints your current directory   `pwd`
  
  List Files            `ls`               Shows files & folders           `ls`
  
  Detailed List         `ls -l`            Shows permissions & details     `ls -l`
  
  Show Hidden Files     `ls -a`            Shows hidden files              `ls -a`
  
  Change Folder         `cd folder_name`   Enter a folder                  `cd ros2_day1`
  
  Go Back               `cd ..`            Go one level up                 `cd ..`
  
  Go Home               `cd ~`             Go to home directory            `cd ~`

------------------------------------------------------------------------

## 📁 File & Directory Management

  ------------------------------------------------------------------------------
  Section          Command            What It Does           Example
  ---------------- ------------------ ---------------------- -------------------
  
  Create Folder    `mkdir name`       Creates new directory  `mkdir ros2_day1`

  Create File      `touch file.txt`   Creates empty file     `touch test.txt`

  Delete File      `rm file.txt`      Deletes file           `rm test.txt`

  Delete Folder    `rm -r folder`     Deletes folder &       `rm -r my_folder`
                                      contents               
  ------------------------------------------------------------------------------

⚠️ **Warning:** `rm -r` is permanent. No recycle bin.

------------------------------------------------------------------------

## 📂 Copy & Move

  -------------------------------------------------------------------------------
  Section          Command            What It Does           Example
  ---------------- ------------------ ---------------------- --------------------
  Copy File        `cp source dest`   Copies file            `cp a.txt b.txt`

  Move/Rename      `mv old new`       Moves or renames file  `mv a.txt new.txt`
  -------------------------------------------------------------------------------

------------------------------------------------------------------------

## ✍️ File Viewing & Editing

  Section     Command           What It Does            Example
  ----------- ----------------- ----------------------- ------------------
  Edit File   `nano file.txt`   Opens file editor       `nano hello.txt`
  View File   `cat file.txt`    Displays file content   `cat hello.txt`

### Nano Save & Exit

CTRL + O → Enter\
CTRL + X → Exit

------------------------------------------------------------------------

## 📦 Package Management (Ubuntu/Debian)

  ------------------------------------------------------------------------------------------
  Section          Command                   What It Does           Example
  ---------------- ------------------------- ---------------------- ------------------------
  Update Packages  `sudo apt update`         Updates package list   `sudo apt update`

  Install Package  `sudo apt install name`   Installs software      `sudo apt install git`
  ------------------------------------------------------------------------------------------

------------------------------------------------------------------------

## 🧠 System Commands

  -------------------------------------------------------------------------
  Section          Command          What It Does           Example
  ---------------- ---------------- ---------------------- ----------------
  Show Home Path   `echo $HOME`     Prints home directory  `echo $HOME`
                                    path                   

  Show Processes   `ps`             Lists running          `ps`
                                    processes              

  Live Monitor     `top`            Shows live system      `top`
                                    usage                  

  Kill Process     `kill PID`       Stops a process        `kill 1234`
  -------------------------------------------------------------------------

------------------------------------------------------------------------

# 🎯 Demo:

``` bash
cd ~
mkdir ros2_day1
cd ros2_day1
touch practice.txt
nano practice.txt
cat practice.txt
```

------------------------------------------------------------------------

# 🧪 What we Learnt?

-   How Linux file system works
-   How to navigate directories
-   How to create, delete, move files
-   How to install software
-   How to monitor running processes
-   Basic terminal confidence

------------------------------------------------------------------------

# 🚀 Why This Matters

Linux is the backbone of:

-   ROS2
-   Robotics systems
-   Embedded systems
-   Cloud servers
-   DevOps pipelines
-   AI infrastructure

Mastering terminal fundamentals is step one toward becoming a powerful
robotics/system engineer.

------------------------------------------------------------------------

