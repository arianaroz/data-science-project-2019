COMP257/ITEC657 Group Project
===

**Group:** Practical 1, Friday 11am - Group G
<br>
**Group Members:** Ariana Rozsnyoi, Caitlin Apcar, Misha Pavlov and Zachary Ash
<br>
**Project Title:** The Economics of Film
<br> 
**Dataset Transformation Notes:**
The datasets that we used for our analysis are: 

- [IMDB dataset](https://data.world/popculture/imdb-5000-movie-dataset) 
        - we did not need to make any mofifications to this data set before importing into the notebook
- [Movie revenue dataset  (up until 2017)](https://developers.themoviedb.org/3/movies/get-movie-details) 
        - .csv file is available [here](https://zenodo.org/record/1240586#.XX3dCy17FsO) 
        - This dataset required cleaning in excel before we were able to import for two reasons. Firstly, The .csv file was semi-colon deliminated which we chose to import into excel and convert to comma delimited. The oriignal file also had a size above the limit we could store in github, so we opeted to drop columns that would not be important to our analysis. The following columns were removed: tagline, overview, runtime, spokenlanguages and the various number of 'X' fields. We also chose to remove rows where the original language was not = 'en', and where the status of the movie did not = 'Released'. After this we also chose to delete the Status column. 

        