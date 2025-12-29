# Bandit Level 26 → Level 27

## What I did
Escaped a restricted shell and accessed the password file.

## Commands I used
ssh -i bandit26.sshkey bandit26@localhost
:set shell=/bin/bash
:shell
cat /etc/bandit_pass/bandit27

## Result
Found the password for Level 27 (not shared here).

## What I learned
- How restricted environments can be bypassed
- How text editors can be used to escape shells
