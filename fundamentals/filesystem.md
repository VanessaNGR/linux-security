# Linux Filesystem

## Why this matters in security
Understanding the Linux filesystem is essential for detecting misconfigurations,
analyzing logs, and identifying potential attack vectors.
Expand filesystem notes from Linux Basics for Hackers


## Key directories
- /etc generally contains the linux configuration files
- /var  
- /home : users home directory
- /tmp 

Expand filesystem notes from Linux Basics for Hackers
- /      :the root is the top of the tree
- /root  :the home directory of the all-powerful root user
- /mnt   :where other fyles are attached to the filesystem
- /media :where CD and USB are attached
- /bin   :where application binaries reside
-/usr ---/lib   :where we can find libraries
- |------/proc  :view of internal kernel data
- /dev   :special devices files
- /sbin  :binaries
- /sys   :kernel's view of the hardware

## Security perspective
- Sensitive configuration files
- Log locations
- Common abuse points

Add filesystem fundamentals notes
