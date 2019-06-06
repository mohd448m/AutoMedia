# TODO
1. Periodically check and remove in_progress files and their directories. This can happen if the computer crashes while adding rss.
2. Automatically remove torrents that have finished seeding, to reduce memory usage and startup time of transmission.
# Requirements
## System
transmission-cli
## Python
feedparser, tldextract, transmissionrpc
# Requirements when using read_manga.py
## System
rofi, sxiv
# Important
Do not move files inside the download directory. If you want to move them, move the whole download directory
when automedia is not running and then set the download directory to the new location when using sync command.
