# Bandit Level 9 → Level 10

## What I did
Logged into Bandit Level 9 and searched for the password file with unusual permissions.

## Commands I used
ls
cat data.txt
strings data.txt | grep "="

## Result
Found the password for Level 10 (not shared here).

## What I learned
- How to search for files owned by a specific user and group using find  
- How to ignore permission errors using 2>/dev/null  
- How to read files with cat even if they have unusual permissions
