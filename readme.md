# Wii IOS Backup
This repo contains everything you need to make a legal backup
of all the Wii IOS from NUS (Nintendo's Update Servers).

## Why
Moslty nostalgia preservation + I'm some kind of "backup freak"

## What
This repo contains:
 - The original [NUS Downloader v1.9](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/nusdownloader/NUSDownloader_v19.zip)
   `.exe` (md5: 9a151e4c2a7349b447418dd427297c8c)
 - The [last database file](https://web.archive.org/web/20180909145900/http://wiibrew.org/wiki/NUS_Downloader/database)
   available on wiibrew.org [before it broke](https://wiibrew.org/wiki/NUS_Downloader/database).
 - A custom `.nus` script I wrote using this database: it tells NUSD to download
   all the versions of all the IOS for all the regions.

## How
 - Run nusd.exe under Window$ and tick all the checkboxes at the bottom.
   This will tell NUSD to pack everything in `WAD` files for easy installation,
   while keeping the original encrypted files around just in case you need them.
 - Click on `Scripts` > `Local Scripts` > `full_backup.nus`
 - Everything is downloaded in the `Scripts` folder.

## Warning
*The Wii is getting old, make backups now*. Some IOS listed in Wiibrew's database
are already missing from NUS: if you own a Korean Wii you're out of luck for the
(required) EULA system title, and the (optional but very useful) Mii channel.
