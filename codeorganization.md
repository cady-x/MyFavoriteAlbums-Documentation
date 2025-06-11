# How is MyFavoriteAlbums's code organized?

MyFavoriteAlbums is an open-source project, meaning that its original source code is publicly available. 
Developers who are interested in building off of the existing code for MyFavoriteAlbums can use its 
features to generate their own web pages and add new functionalities or analyses to this software.

The data being used for analysis is stored in the ```data``` folder, inside the ```album-rankings.csv``` file.

If multiple distinct sets of data are desired, developers can also add and integrate additional .csv files into this software.
These additional .csv files should also be added to the ```data``` folder.

The project’s source code is written in R; this R code grabs the data from the .csv 
file to use for its analyses. 
```app_server.R``` contains the server-side code.
```albums_by_band.R```, ```albums_by_year.R```, ```compare_bands.R```, ```number_one_albums.R```, and ```vinyl.R``` all 
contain the code that performs the analysis of the data in ```album-rankings.csv```. Each of these analysis files are
represented by a separate page in the MyFavoriteAlbums UI, which is organized by the application-side code 
(```app_ui.R``` and ```app.R```).

> Developers who haven't used R before should set up R and RStudio.

### Related resources:
  * [What are .csv files?](csvwhatis.md)
  * [Working with .csv files](csv.md)
  * [Setting up R and RStudio](rrstudio.md)
