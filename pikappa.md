pikappa0208 comandi bash
1. lprm
Remove something from the printer queue.

lprm jobnumber
2. ls
Lists your files. ls has many options: -l lists files in 'long format', which contains the exact size of the file, who owns the file, who has the right to look at it, and when it was last modified. -a lists all files, including hidden files. For more information on this command check this link.

ls option
Example:

$ ls -la
rwxr-xr-x   33 adnan  staff    1122 Mar 27 18:44 .
drwxrwxrwx  60 adnan  staff    2040 Mar 21 15:06 ..
-rw-r--r--@  1 adnan  staff   14340 Mar 23 15:05 .DS_Store
-rw-r--r--   1 adnan  staff     157 Mar 25 18:08 .bumpversion.cfg
-rw-r--r--   1 adnan  staff    6515 Mar 25 18:08 .config.ini
-rw-r--r--   1 adnan  staff    5805 Mar 27 18:44 .config.override.ini
drwxr-xr-x  17 adnan  staff     578 Mar 27 23:36 .git
-rwxr-xr-x   1 adnan  staff    2702 Mar 25 18:08 .gitignore

3. more
Shows the first part of a file (move with space and type q to quit).

more filename