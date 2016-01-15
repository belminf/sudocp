# sudocp

Bash script to copy files to a location that is writable by a user you only have `sudo` access to.

**Warning:** This will clobber files in the destination.

## Requirements
* `bash`
* `tar`

## Example
```
$ sudocp apache foo/ README.md webpage.html notes.txt /var/www/sites/nat_wiki
[sudo] password for belmin:
foo/
foo/bar.1.html
foo/bar.2.html
README.md
webpage.html
notes.txt
```
