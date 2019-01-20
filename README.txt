===============================================================================
BANDCAMP-DL                                                      Jam, not jelly
===============================================================================

A simple script that can download a Bandcamp album or track.
(Streaming is for nerds anyway >o>)



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
Author is Jenga Phoenix <jadedctrl@teknik.io>
Sauce is at https://git.eunichx.us/bandcamp-dl
