# Tableu Challenge

## Description

This project was to visualize data from the [New York Citi Bike Program](https://en.wikipedia.org/wiki/Citi_Bike) using data found [here](https://www.citibikenyc.com/system-data). The visualizations may be viewed by following the links in the Dashboard 1, 2, and 3 sections below.

## Technologies Employed

* Tableu
* Python
    - pandas
    - os


## Data prep

Though I prepared many more files for use, I was only able to use the past two years worth of data.  The gathered data was about 754 Mb.  The jupyter notebook file ``data_prep.ipynb`` was used to automate extraction of zip files, standardize data column labels, and gather data into a single csv file (``gathered_bike_data.csv``) to be loaded in Tableu. 

 In a Tableu work book, I made three stories corresponding to the three dashboards.  The captions for these are under the next three headings.

## Dashboard 1

[Story 1](https://tabsoft.co/2CzTrkP "Story 1")

It is surprising to see that there are fewer riders under 25. It is also interesting that female trip duration stays roughly the same height above that for males for most age ranges.  Also, it is surprising that median trip duration stays roughly flat accorss all ages.


## Dashboard 2

[Story 2](https://tabsoft.co/3hWFBsI "Story 2")



It is not surprising that the number of riders decreases in the winter months.  There seems to have been a growth in stations in the southwest.  I was suprised that there are many riders now, given the COVID 19 outbreak.

## Dashboard 3

[Story 3](https://tabsoft.co/3fPkZAR "Story 3")

Older people are not using the new stations located further from the city center.  It is difficult to tell wheter there is a difference in how each gender uses stations.  There were fewer than 10 who indicated unknown gender.  The longest trips seem to be taken by commuters leaving the city center.

