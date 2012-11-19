what_web_dl
=============


This script is used to process web release purchases (bandcamp & boomkat at
the moment).  

1) It will backup the directory you run it on in case it doesn't do what you thought
2) unzip the albums to a directory of the same name
3) rename all the wrongly named files within each album
    Bandcamp
        - %artist% - %album% - 01 track.mp3
            --- gets renamed to ---
          01 track.mp3
    Boomkat
        directory needs renaming from [encode]-album to album
        
4) prints out the mktorrent command required to make the .torrent file

##TODO:
    rename album directories properly ex. [year] (encoding)
        -- boomkat has zips named flac-*
    flag for making torrent file after processing ( -t --torrent )
          
##Disclaimer
This is for my personal use.  If you mess up your download directories, it's on
you.  I've made the backup to avoid this problem but things happen.
