# Dutch Tweets Analysis

This repository is intended to be used for Dutch Social Media Analysis.

# Problem Statement

Dutch Social media analysis dataset has been taken from Kaggle and some assumptions have been made for this analysis. Four cities from Netherlands have been chosen from the dataset for finding the mean sentiment score across 4 cities and also for time series analysis as well. 

## Executive Summary
The workflow of the project is as follows:

- Importing packages
- Reading JSON files for all the tweets and creating a tweets dataframe
- Analyzing tweets for missing values and visualizing it in a bar chart
- Analyzing tweets for unique values and visualizing it in a bar chart
- Analyzing the distribution of users who have enabled thier location using a bar chart.
- Visualizing top 20 screenames who tweeted the most dutch tweets using a bar chart
- Visualizing tweet's HISCO standards with their frequency using a bar chart
- Finding the mean sentiment score across 4 regions in Netherlands
- Correlation matrix using heatmap
- Mean sentiment of tweets over time across Netherlands and across 4 regions of Netherlands 
- Word cloud of top 20 users who tweeted the most in this dataset
- Key Takeaways

### Key takeways

1. The columns hisco standard and hisco code in tweets dataframe have the most missing values.
2. The columns text translation and created_at in tweets dataframe had the most number of unique values.
3. 60% of the users have not provided their location in their bios ( 161/271)
4. Users who provided their location along with their tweets, majortiy of them have a neutral sentiment.
5. The top 20 screennames who tweeted the most dutch tweets in Netherlands include s_akkrati, marco_kerkhofs and coronawordlstat.
6. There is a bar chart in this notebook showing the mean sentiment score across 4 major regions in netherlands (we assume that the 4 major regions are amsterdam, hague, rotterdam and utertch. Rotterdam has the highest mean sentiment across all region. Hague has the lowest mean sentiment across these 4 regions
7. It can be seen from a heatmap in this notebook that there is a positive correlation between weeksofyear and subjective pattern and sentiment pattern. It can also be seen from the heatmap that there is a positive correlation between the subjective pattern and the industry as well.
8. Majority of the people living in Amsterdam were tweeting with a positive sentiment shown by two peaks in a time series. 
9.  Majority of the people from the whole Netherlands in some weeks were tweeting with a positive sentiment shown by two peaks in a time series.
10. The word cloud for top 20 users who tweeted in Netherlands, shows that tweets were focused on topics of covid-19 and corona virus, meaning people were focused on tweeting about covid.
