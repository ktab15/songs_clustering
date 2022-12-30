# About
This is a project for Data Science Pro Bootcamp doing in Python.

I work on song lyrics from 2 sources: 

  * https://github.com/wdw21/songbook

453 xml files with songs mainly in Polish, all these files come from the 21WDW (scouts group) songbook written over the years by various guitarists.

  * https://github.com/qamil95/spiewnik

1006 latex files with songs mainly in Polish come from Cracow's songbook of "around the mountains" songs

I extract interesting data from .xml and .tex files.
I work with the text, clean it, remove stopwords, do stemming, etc. 
Then I pull out some statistics. I remove duplicates. 

I'm trying to combine into clusters.


# Repository structure

## Songs.ipynb

Jupyter Notebook with my code and description.


## Data

Contains 2 subfolders Songs and Songs2 with files from both sources and .csv files with cleanup bases obtained by executing code from the notebook/

## images 

Contains images that are saved while executing code from the notebook.
