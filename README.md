# linearmodels-NFL

## Analysis of The National Football League Data
![Alt text](http://www.stickpng.com/assets/images/5895deb9cba9841eabab6099.png)
Given in-game NFL statistics (besides scoring)...
* Predict point totals
* Predict winners and losers
* Identify statistics that are predictive of team success 

## Data Collection
* Leveraged nflscrapR package to scrape retrospective raw data from NFL JSON API
* Box scores, player statistics, play-by-play statistics, and drive summaries
* Seven CSV files, one for each individual year from 2009 through 2015
* 1,792 games played from 2009 to 2015

## Data Pre-processing and Feature Engineering
### Data Cleaning
* Scraping resulted in duplicate variables and NA values
* Duplicate variables were combined and duplicate variables aggregated
* Delete scoring variables (safeties, touchdown…)

### Feature Engineering
We created new variables that were suspected of being useful in predicting game output that were not already in the dataset.
![Alt text](https://raw.github.com/nickkimer/linearmodels-NFL/screenshots/feature_engineering.PNG)

