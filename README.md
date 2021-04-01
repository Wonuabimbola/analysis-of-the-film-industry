# Movies: A Data Analysis
## A Phase 1 Project
**Authors**: Wonu , Edgar Gonzalez
![img](./images/Microsoft_Studios_Logo.png)

### Overview

our research seeks to analyze data on the movie industry, to glean any insights, and make recommendations to make Microsoft Studios: Film Division as profitable as possible.

### Business Problem

Microsoft wants to open a film division of Microsoft Studios but lacks any knowledge in creating profitable movies. 


### Our Data 

Original datasets used can be found in the folder `zippedData` which were provided by The Flatiron School.
Images and images of plots used in this README.md are in the folder `images`, and data used for analysis can be found in `clean_data.csv` and `aggregate.db`.


### Methods

We posed 3 questions to ourselves:

-Does release date have an effect on movie profits?
-Do certain genres tend to be more successful than others?
-Do certain directors have an effect on the profitabilty of movies?

We only considered movies released in 2010 and onward, as we felt these were the most relevant to current trends. We also did not consider movies without domestic or worldwide gross. We assessed how profitiable movies were based on the difference between domestic gross and production budget as our domestic profit, and worldwide gross and production budget as our worlwide profit.Next we seperated our data by genre, release month, and director

### Results
##### Movies tend to do better when released in at certain times of the year
![img](./images/mean_profit_by_month.png)



##### Certain genres of movies tend to me much more profitable
![img](./images/mean_profit_by_genre.png)
![img](./images/mean_production_budget_by_genre.png)



##### Few directors seem consistently successful on both domestic and worldwide markets
![img](./images/director_mean_dom_prof_num_of_movies.png)
![img](./images/director_mean_world_prof_num_of_movies.png)


### Conclusion

Based on our findings, we believe Microsoft Studios would find the most success hiring directors such as Joss Whedon, The Russo Brother, and Zane Burden, who have made movies that were both profitable and had both domestic and worldwide appeal. 
Movies that are produced should either musicals, animated or sci-fi. Though the production budget for these genres can be high, the profit is significantly higher. 
Our last recommendation is that movies should be released in May, June, or July. If that 3 month window is missed then November only other recommended time.

### Summary

-Hire directors with who have proven worldwide appeal (E.g. Joss Whedon, The Russo Brothers, Zane Burden)
-Create musicals, animated films, or sci-fi movies
-Ideally release movies between May - July

### Recommendations for Further Research

We do want to make a note that during our analysis we left many avenues of research unexplored due to lack of data or being out of scope of this project and we highly recommend another study into those avenues

-Since the pandemic started it would be wise to do another study of profitability into streaming services. Since movies released on streaming services do not have a traditional measure for gross profit, they could not be included in this project but their impact on the future should not be ignored.

-The role advertisement plays in monetary success of a movie should be explored and considered




