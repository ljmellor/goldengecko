# Home Media Server Scripts

Here you will find a collection of scripts as and when I write them that help me with day to day activities on my Debian based home server.

Expect bugs, bad coding practices, etc. Edits/suggestions are welcomed however bare in mind that I'm not actively developing any of this as it stands.

# Services

This script uses systemctl to batch start, stop, restart or display the status of any installed services. Useful for running before/after a filesystem backup to ensure that files don't change during the backup process.

# Tempcheck

This script takes the cpu temp of my media server and injects it into a mysql database for inclusion on a web page later on.
