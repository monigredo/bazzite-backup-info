# Bazzite Backup

Bazzite Backup is a private backup utility used by its owner to protect game saves and settings on a Bazzite KDE computer.

It uses Restic to encrypt backup contents locally and rclone to upload the encrypted repository to the owner's Google Drive. Automated uploads are limited to 2 MiB/s; the initial upload may run without this limit.

The application requests the Google Drive `drive.file` permission to create and manage files used by this backup application. It is not offered as a public service.

[Privacy policy](privacy.html) · [Terms of use](terms.html)

For questions, contact the owner through [their GitHub profile](https://github.com/monigredo).
