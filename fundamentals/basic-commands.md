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

**Example:**
```bash
cd /etc
bash:/etc  $cd ..   : to move one level from /etc to the root directory
bash:/etc  $cd ../.. :to move up two levels
bash:/etc  $cd ../../.. :to move uo three levels and so on
```
---------------------------------------------------------------







