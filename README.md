# Anime-Project

###  Problem Statement 
- The goal of this project is to perform a detail analysis of anime dataset and to dicover the different factors that affect the rating of an Anime.

###  Data Description
- The dataset is an excel file that contains over 14,000 titles, media types, duration, start yr, finish yr, season of release and other columns to be analyzed.
- The dataset is messy and most columns need to be cleaned before it can be analyzed.
- The different titles are categorized by media types.


###  Data Preprocessing
- Converted the dataset from to an excel table for easy cleaning by higlighting the dataset and cntrl + T
- Classified all the missing media types as "Unknown"
- Converted duration from hour to minutes
- For all the titles with missing duration, Filled it with the average or median of each media type whichever was lower
- Filled missing season of Release with "Unknown"
- Removed the column "description" as it will not be useful for the analysis
- Removed the special characters in the studio names
- Dropped the rows that didn't have a "Start Year"
- Filled Blank "Finish Year" with unknown since production is still ongoing


###  Insights
The factors affecting the ratings of anime are:
-   Season of release:  People tend to drop shows during the spring and fall times than they do in other seasons and watch more during the Winter and Summer time
-   Duration:  More people are watching TV than other media types, people are more likely to rate shows with shorter duration
-   Ongoing- More people are likely to watch if show is no longer ongoing and that also affects the rating
-   Media type - The audience tend to watch more TV compared to the rest of the media type 


###  Recommendation
- More 
