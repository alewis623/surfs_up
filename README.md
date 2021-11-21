# surfs_up

## Overview of Analysis
Surf's Up is an idea of a compbined surf icecream shop in Hawaii. The current propsal is to build on the island of Oahu and expand to other islands as resources permit. This analysis is to address concerns by principles and investors on tempurature swings. Tempuratures could effect traffic and income into the buisness. June and December will be compared

## Resources
Data: hawaii.sqlite was used to parse out the 2 months for review. 
Software: Juypter Notebook 6.3.0, Python Virtual environment 3.7.10 named PythonData. Numpy, pandas and datetime dependencies were utilized. Python SQL toolkit and Object Relational Mapper were imported. 

## Results 
9 weather stations gathered the data for this analysis. All temperatures in this study are in fahrenheit. 
  June temperatures ranged from a low of 64 degrees to a maximum tempurature of 85 degrees. The mean temperature of 74.944118 degrees was calculated. There are 1700 data points for the month of June. The difference from June mean to June median is .06 degrees.
  
  <img width="81" alt="June_temperature" src="https://user-images.githubusercontent.com/90878901/142768693-19944cba-6e3f-4a4e-bb1d-5786c31583f3.png">

  December temperatures ranged from a low of 56 degrees to a maximum temperature of 83 degrees. The mean temperature of 71.0141529 was calcuated from this data set. There are 1517 data points collected for the month of December. This is a 10.8% reduction in the number of data points. The difference from December mean to median is .04 degrees. 
  
  <img width="91" alt="December_temperature" src="https://user-images.githubusercontent.com/90878901/142768900-f94f19a7-a5c8-4e46-9277-b60ab2f6de9c.png">

## Summary 
  Comparison of the two data sets reveals the following information:
The interquartile range varied between June (4) and December (5). Comparing standard deviations by using the F test resulted in .243812. In both months the mean and the median varied little.  High temperatures varied by only 2 degrees while the low temperatures varied by 8 degrees. While there is a 10.8% decrease in the collection points between the 2 data sets, there still are 1700 and 1517 data points collected. Based on the analysis, the temperature differences between June and December do not demonstrate a significant obstacle to opening Surf's Up.
