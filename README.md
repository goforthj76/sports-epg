# Sports EPG for Sparkle TV

Sports-only XMLTV guide using channel IDs from the IPTV-org sports playlist.
The GitHub Actions workflow refreshes the guide daily and can also be run manually.
Schedules depend on third-party sources; not every playlist channel is covered.

Use the public raw URL for `sports-guide.xml` in Sparkle TV's XMLTV EPG field.
The initial guide covers 141 channels with 6,419 listings for September 12–13, 2026.
Channel selection is stored in `sports.channels.xml` and does not automatically
add newly introduced playlist channels.

Downloader: https://github.com/iptv-org/epg
Playlist: https://iptv-org.github.io/iptv/categories/sports.m3u
