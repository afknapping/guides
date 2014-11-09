# How to change the location of your mobile backups on OS X

- find `cd ~/Library/Application Support/MobileSync`
- in there is `Backup`

(new location)/MobileBackups

    $ ln -s "/Volumes/<THE_VOLUME>/MobileBackups/Backup" "$HOME/Library/Application Support/MobileSync/Backup"

