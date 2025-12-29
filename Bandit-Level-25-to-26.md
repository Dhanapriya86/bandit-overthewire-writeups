# Bandit Level 25 → Level 26

## What I did
Used an SSH private key and escaped from a restricted shell.

## Commands I used
ssh -i bandit26.sshkey bandit26@localhost
ls
cat /etc/bandit_pass/bandit26

## Result
Found the password for Level 26 (not shared here).

## What I learned
- How SSH key authentication works
- How restricted shells limit users
