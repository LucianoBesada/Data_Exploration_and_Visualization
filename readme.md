# Ford GoBike System Data - San Francisco Bay Area

Tools useful for analysis: *Python* and *Jupyter Notebook.* <br>
Final analysis from two parts:
**1.** [Data Expoloration and Cleaning](https://github.com/LucianoBesada/Data_Exploration_and_Visualization/blob/main/Data%20exploration.ipynb) <br>
**2.** [Data Explanation and Visualization](https://github.com/LucianoBesada/Data_Exploration_and_Visualization/blob/main/Data%20explanation.ipynb)

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
It is composed by 17 columns and 183,412 rows from users based in San Francisco. It gives information about 4,646 number of bikes and 329 start and end stations.
To make better analysis I discarded users that have or have declared an age over 80. And took into consideration only trips that had different start and ending stations, all this due to geolocalization reasons. <br>
Some data wrangling was necessary to clean up the data, to extract the age all users and to know the distance they have been using their bikes.

## Summary of Findings

During the exploratory analysis, I have found that one of the reasons for success for the rental service is due to their locations in different main points in San Francisco, locations that sum up to 329 stations, and the availability of 4,646 bikes. <br>
In addition, I notice how the service is used mostly by men with an age between 27 and 33 years old. <br>
However, even if the service is taken mostly by men, in general women seem to enjoy more their rides by covering longer distances per ride.

### References
- Dataset [Ford GoBike System Data](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub?embedded=True)
