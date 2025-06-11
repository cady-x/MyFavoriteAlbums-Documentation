# What are .csv files?

A .csv file is a file in which data is organized by commas and new lines, where each line 
represents a single data record. For example, an album called _Best Album Ever_ by artist Bob Sun,
and another album called _Tomatoes_ by artist Blue Sky can be  represented by:

```
Album,Artist
Best Album Ever,Bob Sun
Tomatoes,Blue Sky
```

MyFavoriteAlbums uses csv files to
store and analyze data. To modify what data is being analyzed or customize it to your own music preferences, 
you will have to edit the existing ```album_rankings.csv```, or create a new .csv file of your own.

.csv files are quick and relatively straightforward to work with due to their simple structure. 
They are also compact and able to store large amounts of data efficiently – 
optimal for analyzing a large number of music albums. Another strong point for .csv files is their human-readability. 
Since data is stored as plaintext (normal words that aren’t code and also aren’t specially formatted), 
it is easy to search for a specific record in the .csv file. 
Developers and users can easily and quickly add new data to .csv files by simply typing 
(or otherwise inserting) in the new data. 

The ```album_rankings.csv``` file contains info on the year, ranking, album name, artist, rating, vinyl, EP, and live
status of albums. Consider the following code sample:

```
Year,Ranking,Album,Artist,Rating,Vinyl,EP,Live
1993,1,August and Everything After,Counting Crows,10,v,,
1993,2,Siamese Dream,The Smashing Pumpkins,9,v,,
1993,3,Cure for Pain,Morphine,9,v,,
1993,4,"Everybody Else Is Doing It, So Why Can't We?",The Cranberries,8,v,,
1993,5,Debut,Bjork,8,v,,
...
```

In the code sample above, we see from the first line the information that we can expect to find in the rest of the file. 
In the following lines, we see some pieces of data separated by commas. In some cases, there may be no data between commas. 
This means that there is no inputted data for that specific value; 
in this example, the album _August and Everything After_ has no inputted EP or Live data.

For more information on how to create or modify your own .csv files, check out [Working with .csv files](csv.md).
