# Amazon_Vine_Analysis

## Overview/Purpose

In this project, I was tasked with pulling a data set from Amazon reviews and then to organize that data into easy to use dataframes and tables.  After organizing the tables, I was able to use the tables to assist in analyzing the data within them.  I was specifically tasked with lookinginto the star ratings of both VINE and non VINE reviewers. I chose to work with the toy reviews.

## Results
In order to determine the vine and non vine reviews, I first created aand filtered a dataframe that included only reviews that had received 20 or more total votes, where a good number of those votes were considered helpful.  I then split that dataframe into 2 more dataframes (one with only the VINE reviewers and one with only non VINE users).  From here I was able to do some calculations to determine the total number of ratings, the number of 5 star ratings, and the percentage of 5 star ratings.

### Vine Reviews
- Total reviews: 1266
- 5 star reviews: 432
- Percentage of 5 star reviews: 34.12%
- Average Star Rating: 3.89

![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)

### Non Vine Reviews
- Total reviews: 62028
- 5 star reviews: 29982
- Percentage of 5 star reviews: 48.34%
- Average Star Rating: 3.70

![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)


## Summary
The results from the data presents an interesting picture.  The percentage of 5 star reviews was much higher among the non Vine reviews (about 14% more).  This shows that Vine members did not give 5 star ratings to the toys as often as the non Vine users.  I did notice, however, that the Vine members also seemed to be a bit more hesistant to give very poor reviews as well.  It looked as though the Vine reviews, on average, would actually end up being higher than non Vine reviews.  The high number of 3 and 4 star reviews in the Vine dataframe made me wonder.  To check into this, I found the average star rating of each category and did find that the average star rating for Vine reviews (3.89) was indeed higher than the non Vine (3.7).  In conclusion, the Vine reviewers showed bias in that they did not give very many bad reviews.  I do not believe that bias existed for 5 star reviews, as the non Vine reviewers gave a greater percentage.

![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)

