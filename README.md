# borg-homedir-excludes (previously rsync-homedir-excludes)

## Usage:

Edit the file rsync-homedir-excludes.txt to suit your home directory.

Then pass the file to [borg](https://borgbackup.readthedocs.io/):

    $ borg --exclude-from path/to/rsync-homedir-excludes.txt
