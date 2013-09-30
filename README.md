# reverse-duplicity Version 0.0.1 Alpha

A utility that does the opposite of duply/duplicity: backing up a remote source to the local filesystem.

**Warning:**
Please note that this software is still in an experimental stage. USE AT OWN RISK!

## Features

* Creating new backup profiles.
* Backing up over FTP using `curlftpfs`.

## Planned features

* No more random FTP mount points. Just unique ones.
* `chmod` the output folder (is now root only).
* Managing the backup scheme.
* Managing the PRE and POST scripts.
* Daemon with multi-threading.