# Gmail Backups

I run scheduled Gmail backups directly from computer on a scheduled basis using [GAM Team's Got Your Back tool](https://github.com/GAM-team/got-your-back). I store my email backups in `~/Documents/Email/%my-email-address%/`.

The instructions in the tool define how to perform an initial backup (slow) and then cron incremental backups on top (fast).

A one-time backup to catch up with the previous:

`gyb --email %my-email-address% --local-folder ~/Documents/Email/%my-email-address%`.

Note: Advanced protection must be disabled to use this tool.
