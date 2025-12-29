# Bandit Level 22 → Level 23

## What I did
Checked the cron job script and found where it stores the password.

## Commands I used
ls /etc/cron.d
cat /etc/cron.d/cronjob_bandit23
cat /usr/bin/cronjob_bandit23.sh
cat /tmp/[generated_file]

## Result
Found the password for Level 23 (not shared here).

## What I learned
- How scripts generate filenames dynamically
- How cron jobs can leak credentials
