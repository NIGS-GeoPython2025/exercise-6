# Exercise 6: Further practice with pandas from actual data
In this exercise, you will be practicing what you did during the lesson, but now you will be doing the data scraping yourself.

You need to calculate the average number of earthquakes recorded by the PHIVOLCS catalog [https://earthquake.phivolcs.dost.gov.ph](https://earthquake.phivolcs.dost.gov.ph) for a specific month assigned to you.

## Completing the exercise

- **Remember to save and commit your changes locally, and push your changes to GitHub after each major change**!
- **This exercise will be INDIVIDUAL**, so make sure you do your own analysis.
- You can use the exact same code that you learned for this lesson, or modify that code to fit how you scrape the data form the PHIVOLCS website.

## Before you start

### Start a Binder or Jupyter Lab instance 

Before starting to work with the problems for this week, you should start a new JupyterLab instance in Binder (o ryour preferred Jupyter Lab application) and start form an empty notebook there.

### Input data

You will use data from the PHIVOLCS website on earthquake monitoring [here](https://earthquake.phivolcs.dost.gov.ph/))). Scroll all the way down to select the month that you ahve been assigned.

You will need to manually copy the data from the website, save as csv file (or any ASCII format), that you will then process in Python with pandas.

The output should be similar to the last part of Lesson 6:

'''
MONTH: January 2021
NUMBER OF EVENTS RECORDED: 783
Average number of earthquakes per day: 25.3
            Mw_mean   DEP_mean  Mw_min  DEP_min  Mw_max  DEP_max  N_events
MONTH_DAY                                                                 
0101       3.713333  43.185185    3.07        2    4.19      142        27
0102       3.863125  28.062500    3.43        1    4.45      165        16
0103       3.830000  30.217391    3.31        1    4.52      141        23
0104       3.939130  33.260870    3.37        2    4.93      126        23
0105       3.730952  37.190476    3.25        1    4.19      139        21
            Mw_mean   DEP_mean  Mw_min  DEP_min  Mw_max  DEP_max  N_events
MONTH_DAY                                                                 
0124       3.798605  28.534884    3.25        1    5.51      125        43
0122       4.041628  52.883721    3.37        1    5.36      160        43
0125       3.735610  32.487805    3.07        1    4.86      381        41
0121       3.813529  45.941176    3.13        1    7.14      153        34
0126       3.870909  39.909091    3.07        1    5.00      445        33
'''
