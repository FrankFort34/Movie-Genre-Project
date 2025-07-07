# Movie Genre Analysis
Author: Frank Fortunati

# Overview and Business Understanding
The company is looking to expand into the film industry and create its own film studio! I have been tasked to analyze which film genres and types are most successful currently. My challenge was to determine what types of movies and creative talent would be best for our new studio.

# Data Understanding
I utilized data sets from IMDB and Box Office Mojo to perform my analysis. The IMDB data was stored as a SQLIte database and contained information on average movie ratings, directors, actors, locations, runtimes, genres, and titles. Box Office Mojo contained the info on which studios produced which movies, how much gross revenue each title generated, and year of release.

## Data Preparation
My primary data preparation before analysis was merging the data tables from the IMDB folder with the data in the Box Office Mojo data frame. I did this so I could easily compare the gross revenue of the movie titles against the other relevant fields included in the Movie Data ERD from IMDB.

# Data Analysis
I began my analysis by ascertaining which genres and combinations of genres generated the highest revenue. Action and adventure movies were by far the highest revenue earning genres. I determined that of the 25 highest grossing films, 40.9% were in the action genre, and 16% were in the adventure genre. Focusing on those two genres, I honed in on potential directors. I narrowed my parameters to include individuals who had directed at least 10 action and/or adventure films and had received consistently high ratings. I repeated this search for actors and actresses, and developed a list of potential suitable actors and directors. 

# Conclusion
Action and adventure films have performed well at the box office. The high grossing performance of these films indicates a large audience of viewers who enjoy these genres. The company can do well in this industry by working with the right individuals to direct and star in our films. 

## Limitations

## Recommendations
I recommend the company review the list of potential directors and actors, and then develop an initial budget for the studio. Once we determine how much we are willing to spend on production and on procuring talent, we can examine the costs of hiring directors and actors suggested from the analysis and generate a more accurate candidate list. 

## Next Steps 
Following this initial analysis, we can search for potential writers and producers using these same data sources. 
