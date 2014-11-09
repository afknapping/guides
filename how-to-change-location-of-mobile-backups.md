# How to change the location of your mobile backups on OS X

- find `cd ~/Library/Application Support/MobileSync`
- in there is `Backup`
- move backup to (new location)/MobileBackups

(new location)/MobileBackups

    $ ln -s "/Volumes/<THE_VOLUME>/MobileBackups/Backup" "$HOME/Library/Application Support/MobileSync/Backup"

