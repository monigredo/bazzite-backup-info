# Privacy policy

Last updated: 2 October 2026

Bazzite Backup is used solely by its owner for personal backups of game saves and settings.

## Data and access

The application reads the owner's selected local backup files. Restic encrypts file contents and backup metadata on the computer before uploading the encrypted repository to Google Drive through rclone.

The application uses the Google Drive `drive.file` permission to create and manage its own backup files, including uploading, reading, listing, and deleting files as needed for backup and recovery. Google stores these files under the owner's Google account. Google may also receive ordinary service information such as request times, file sizes, and network addresses.

The Google authorization token is stored locally to allow automated backups. The encryption password is stored locally and is not intentionally uploaded to Google Drive.

## Sharing and retention

The owner does not sell backup data, share it with other users, or use it for advertising. Google processes the stored encrypted files under its own service terms and privacy policy.

Backups remain in the owner's Google Drive until removed by the owner or the configured backup retention process. Retained snapshots may contain older versions of files that have been deleted locally.

## Control and contact

The owner can stop automated backups, delete the backup files from Google Drive, and revoke this application's access through [Google Account connections](https://myaccount.google.com/connections). Revoking access does not automatically delete existing backup files.

For questions, contact the owner through [their GitHub profile](https://github.com/monigredo).

[Home](index.html) · [Terms of use](terms.html)
