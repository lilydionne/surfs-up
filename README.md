# Surfs Up: Investing In Waves & Ice Cream

## Overview
In this analysis, we were tasked to calculate temperature statistics for June and December to see if running a surf shop is sustainable year around. In order to get this information, we need to run two seperate queries for the months of June and December. After complteling our queries, we can store the temperature data in a list, convert them into a dataframe, and perform statiscial analysis. 

## Results
To create our summary statistics, we will use the .describe() method on our data frames. From this we are able to compared June and December temperatures. From this we can see: 
 - June temperatures are typically higher, as June's average temperature is 75, compared to December's average tempature of 71
 - December has a minimum temperature that is 8 degress lower than June's lowest temperature
 - We have fewer days in our comparision for December than we do for June, even though December has more days in the month than June 

![June](https://user-images.githubusercontent.com/100808834/166280292-8fc8cd68-0cdc-4cf8-a725-7a9a431dfef2.png)

![December](https://user-images.githubusercontent.com/100808834/166279860-8a01841e-f5fa-40f0-82fb-075b96889d36.png)


## Summary
Given that the standard deviation for both is around 3, I believe this tempeature analysis concludes that the shop would perform well year-round as the variances in temperature range is not too great. For additional analysis and shop recommendations, we'd recommend running a summary statistical analysis on precipiation, as rainfall can also play a factor in location and sales performance. 
