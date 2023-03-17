# EFY-Album-Data
A data set about EFY albums and songs.

## What is EFY?

Especially for Youth (EFY) is an organization operated by Brigham Young University that runs retreats centered around standards of the Church of Jesus Christ of Latter-day Saints. These retreats are generally focused on youth ages 14-18. EFY has operated for decades and, until 2019, released religious songs (usually a full album) on a CD that attendees received as part of their admission to the program. These songs have a variety of writers, singers, and other contributors, all of which are documented in this data set.

## Files in this repo:

*README.md*: You're reading it right now. Congratulations!
*EFY-Album-Data-Acquisition.ipynb*: The iPython Notebook file I created to generate the data set of EFY songs. Uses pandas, numpy, BeautifulSoup, requests, and re. Data is scraped from two sources: [SingPraises.net](singpraises.net) and [YouTube](youtube.com).
*efy_tracks.csv*: The current version of the data set. Contains data on EFY albums from 1986 (missing the first two albums in 1984 and 1985) to 2019 (the most recent album, and possibly the final one due to standard EFY camps largely being supplanted by the Church of Jesus Christ of Latter-day Saints's FSY camps). Contains song titles, album, track number, and total number of tracks in the album; artist, words, music, and arrangement credit where applicable; and length of recording (according to the YouTube videos linked to the SingPraises.net entry for the song).

Currently, all credits of the same type are in one column (so, for example, if two people are credited as artists, they are in a single column in the data set); I may add a column for each credit in the future.
