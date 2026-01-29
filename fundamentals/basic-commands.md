# Basic Linux Commands for Security

## ls
Lists directory contents.

# security relevance
Detect hidden files
Identify suspicious permissions

**Example:**
```bash
ls -l     :provides mor information an objects is, a file or directory, the number of links, the owner, the group, its size, when it was created or modified and its name
ls -la    :to show hidden files
```
--------------------------------------------------------------
## pwd  (present working directory or printworking directory)
Shows current diretory.

# security relevance 
Navigate system during investigations or enumeration

**Example:**
```bash
pwd
/root
or
/user
```
-------------------------------------------------------------
## whoami
Shows in which user we are

# security relevance
Identify the user privileges

**Example:**
```bash
whoami
root
or
user
```
---------------------------------------------------------------

# cd (change directory)
To change directories from the terminal

# security relevance
Allows navigation thought the file system.   It is

**Example:**
```bash
cd /etc
bash:/etc  $cd ..   : to move one level from /etc to the root directory
bash:/etc  $cd ../.. :to move up two levels
bash:/etc  $cd ../../.. :to move uo three levels and so on
```
---------------------------------------------------------------

# --help  /  -h  / -?
To have help about any command

# security relevance
Displays usage and option for a command

**Example:**
```bash
ls --help
```
----------------------------------------------------------------

# man 
Provides a command documentation for commands

# security relevance
To learn advanced options that affect permissions, processes or system configuration

**Example:**
```bash
man ssh
```
----------------------------------------------------------------

# locate
Finds files quickly using an indexed database

# security relevance
Used to locate configuration files, logs, or sensitive binaries

**Example:**
```bash
locate passwd
```
-----------------------------------------------------------------------------------

# whereis
Locates binaries, source code and man pages.

# security relevance
Useful for verifying commands paths and detecting suspicious or duplicate binaries

**Example:**
```bash
whereis python
```
------------------------------------------------------------------------------------

# which
Shows the path of the command that will be executed

# security relevance
To prevent execution of malicious binaries through PATH hijacking

**Example:**
```bash
which ls
```
-------------------------------------------------------------------------------

