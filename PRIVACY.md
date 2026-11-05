# Privacy Policy — Time Machine (ilya fork)

Last updated: 2026-11-05

Time Machine is a personal backup tool that runs entirely on your own computer.
The Google OAuth app "omarchy_backup" exists only so that the open-source tool
[rclone](https://rclone.org) can write backups into the Google Drive of the
person who signs in.

**What it accesses.** Only the `drive.file` scope: files and folders that this
app itself created in your Google Drive. It cannot see, read, or change any
other file in your Drive.

**What it stores, and where.** Your backups are encrypted on your computer
with a password only you hold (restic), and uploaded to your own Google Drive.
The OAuth token stays in a local configuration file on your computer.

**What it shares.** Nothing. There is no server, no analytics, no telemetry,
and no third party. The developer never receives your data, your files, or
your token.

**Removing access.** Revoke it at any time at
https://myaccount.google.com/permissions, and delete the backup folder from
your Drive.

**Contact.** Open an issue at https://github.com/bjrn0/omarchy-time-machine/issues.
