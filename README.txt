===============================================================================
BANDCAMP-DL                                                      Jam, not jelly
===============================================================================

A simple script that can download a Bandcamp album or track.
(Streaming is for nerds anyway >o>)

Note: This is a fairly old script, it’s almost certain not to work anymore.
I highly recommend using, instead, either yt-dlp or bandcamp-downloader:

	https://github.com/yt-dlp/yt-dlp
	https://github.com/iheanyi/bandcamp-dl


----------------------------------------
PRE-REQUISITES
----------------------------------------
You'll need:
	* "gendl" in your $PATH
	* a POSIX-compatible shell (tested with `pdksh` and `bash`)
	* "curl", "wget", or "ftp" installed



----------------------------------------
USAGE
----------------------------------------
Just run "bandcamp-dl" like so:

	bandcamp-dl -a album_url
	bandcamp-dl -t track_url

If you're downloading an album, use "-a".
If it's a track, use "-t".

Pretty self-explanatory =w=



----------------------------------------
BORING STUFF
----------------------------------------
License is CC-0 (though, "gendl" is GPLv3)
Author is Jenga Phoenix <jadedctrl@posteo.at>
Sauce is at https://hak.xwx.moe/jadedctrl/bandcamp-dl
