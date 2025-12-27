# Bandit Level 6 → Level 7

## What I did
Logged into Bandit Level 6 and searched the system to find the file containing the password.

## Commands I used
find / -user bandit7 -group bandit6 -size 33c 
cat /var/lib/dpkg/info/bandit7.password

## Result
Found the password for Level 7 

## What I learned
- How to search files using the find command
- How to filter files by user, group, and size
