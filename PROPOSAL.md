Project Proposal
===

**The Economics of Film**

Ariana Rozsnyoi, Caitlin Apcar, Misha Pavlov and Zachary Ash

In this project we aim to analyse the production and consumption of film and examine how this has changed overtime. Due to the development and increasing saturation of online streaming services, we are interested to see how this has affected the movie industry economically. 
In our project, we hope to answer the following:
- Can we can predict a film’s success (box office or Oscar) based on its budget or genre?
- Does social media have an impact on movie success? Do more social media likes lead to more profit generated?
- Looking at the patterns of budget spend over time - is there a noticeable increase or decrease. If so why?
- Predicting budget spend based on the genre of the movie
- Does the time of year a movie is released impact profit?
- Does a director’s IMDB score have any impact on popularity or profit ?
- Overall do economic impacts lead to a decrease in film uniqueness and originality?

**Datasets:**
The datasets that we are planning to use include: 

    - IMDB dataset - 28 variables and 5043 movies
        .csv format
    - Movie Budgets and Box Office Earnings (Up to Autumn 2018) - 6 variables and 5222 movies
      This dataset will need to be manually copied into a .csv file
    - Movie revenue dataset  (up until 2017) - includes information about production companies and film popularity
        .csv file is available here however it is formatted poorly with all variables in one column. 
        For more recent data an API key will need to be retrieved from The Movie Database. Data is in JSON format and will need to be converted to .csv format.
    - IMDbPY - although not a dataset, this Python package can be used to retrieve film data directly from the Internet Movie Database (IMDB) website. 
    
As we are using multiple datasets we will need to first clean the data. Cleaning will involve using movies that are consistent among each dataset to ensure completeness of the final dataset. This will also involve determining the time frame bounds of the data based on the year the movie was released. 

We will also need to determine how to join the datasets, identifying the most appropriate variable by which the data can be joined. As there are many variables present in each dataset, it may be appropriate to split the raw datasets into smaller subsets allowing us to work with data that has been categorised by a specific variable (e.g. genre or film studio). Certain variables may also serve no purpose i.e. “movie_imdb_link”. Therefore, each variable will be assessed according to our research goal and any irrelevant variables will be dropped.

**Analysis Techniques:**

In this project we plan on using several techniques to explore and analyse the data. We plan on using visualisation techniques to present the data in digestible graphs with analysis. Several modelling techniques including, Clustering algorithms to find patterns in the data to show grouping and Logistic regression to predict categorical outcomes e.g. Can we predict a films success? We will also apply several predictive algorithms to train and test sets and explore which has the highest predictive accuracy relevant to our data. Exploration between K-Nearest Neighbours vs Logistic regression.

**Project Plan:**

Milestone 1 - Week 9: 

    - Complete data preparation and cleaning
    - Analysis of appropriate variables to be used 
    - Joining of datasets
    - Evaluating the merged dataframes to ensure completeness and accuracy 
    - Initial exploring of the data
    
Milestone 2 - Week 11: 

    - Begin model building and analysis
    
Milestone 3 - Week 12: 

    - Finalise tests and run model
    - Evaluate model
    - Final analysis 