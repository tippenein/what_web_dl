what_bandcamp
=============

This script is used to process bandcamp purchases.  It will
1) backup the directory you run it on just in case it doesn't do what you thought
2) unzip the albums to a directory of the same name
3) rename all the wrongly named files within each album
        - %artist% - %album% - 01 track.mp3
            --- gets renamed to ---
          01 track.mp3
4) prints out the mktorrent command required to make the .torrent file

          
