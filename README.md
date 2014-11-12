mp3tffn - MP3 tags from filename
================================

Description
-----------

This bash script tags a batch of MP3 files in a directory based on command line arguments and deducing their track number and title from the file name.

**mp3tffn** expects files to have the following name:

    ##-TITLE.mp3

where **##** is the track number, and after the *-* goes the title.

Currently **mp3tffn** has been tested on *OS X*, though it also should run on *Linux*.

Usage
-----

    $ mp3tffn [artist] [album name]

Dependencies
------------

**mp3tffn** uses the **id3lib** library for tagging files. This is available via various package managers. 

