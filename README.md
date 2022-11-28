# Surfs Up

### Advanced Data Retrieval Techniques

## Objective

W. Avy wanted the compare two specific months, June and December. These two months are six months apart and are in summer and winter. Looking at the information on difference in temperatures during these two time frames will allow W. Avy to determine if an ice cream and or a surdboard shop would be a good investment. In addition, if this first shop is profitable, the business would scale to other locations so this code would need to scale as well. 

We use SQL Alchemy to use the power that is in this tool to see if the temperature review can scale as much as we need it to. Refactoring the already processed code allows us to perform a larger analysis in a small amount time.  

## Weather Results

The data for June and December were converted to a dataframe. Then we put the dataframe into a statistical analysis using the .describe function.

The differences between the weather of June and December were: 
  - June has more data collected over December
  - The mean temperature is 75 in June, which is warmer by close to four degrees than in December
  - The minimum temperatures are a lot more spread apart, with it being 64 in June and 56 in December This may cause some issues of traffic in December. 
  - The standard deviation is .5 greater in December than in June, meaning that the temperatures in December would flucuate more than in June. 
  - The mean for both June and December are fairly similar to its 50th percentile, meaning that even though the temperatures would flucuate they remain consistent. 

## Summary

With the temperatures are nice during June and December, being cold for most days would not be a problem when opening a surf shop that serves ice cream all year round. December would be expected to have lesss sales due to how low the temperatures can get this month. However at the average temperatures an ice cream would always be enjoyable. 

Weather is not just the temperuature and there are many factors that could effect the surf shop's profitability. In conclusion if analysis could be done in the following areas when it comes to the weather.
 - Precipitation
 - Cloud Cover
 - Wind/ Windspeeds
 - Average Storms per Month