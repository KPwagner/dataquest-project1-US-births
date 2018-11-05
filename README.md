# Dataquest Guided Project 1: Explore U.S. Births.
This project is from the Python Programming: Beginner course of Dataquest's Data Analyst path. The programming and analysis that I performed in the Jupyter Notebook utilizes only basic Python functionality and no external modules. I only used techniques covered throughout this Dataquest course.

## Files
- [US_births.ipynb](https://github.com/KPwagner/dataquest-project1-US-births/blob/master/US_births.ipynb) Jupyter Notebook showing the functions I created to explore the datasets along with examples of usage and a few findings. Since Jupyter Notebooks render as HTML on Github (if they render at all), you can't interact with the Notebook unless you download the files.
- [US_births_1994-2003_CDC_NCHS.csv](https://github.com/KPwagner/dataquest-project1-US-births/blob/master/US_births_1994-2003_CDC_NCHS.csv) CSV dataset with data for U.S. births from 1994 to 2003. Source: Centers for Disease Control and Prevention.
- [US_births_2000-2014_SSA.csv](https://github.com/KPwagner/dataquest-project1-US-births/blob/master/US_births_2000-2014_SSA.csv) CSV dataset with data for U.S. births from 2000 to 2014. Source: United States Social Security Administration.

## Findings from Data Exploration
After combining the CDC and SSA data, the resulting dataset spans all dates from 1994 to 2014.

Below the number of births by month from 1994 to 2014 are collected. There were not significantly more or fewer births in any given month. February, even taking into account fewer days, was a slightly less popular month with a total of 6.5mm births, and July and August were slightly more populars months with births of 7.5mm and 7.6mm respectively.

| Month | Births (mm) |
| :---- | -----: |
| January | 7.0 |
| February | 6.5 |
| March | 7.1 |
| April | 6.8 |
| May | 7.2 |
| June | 7.1 |
| July | 7.5 |
| August | 7.6 |
| September | 7.4 |
| October | 7.3 |
| November | 6.9 |
| December | 7.1 |

About 45% more births occurred on weekdays than Saturday or Sunday.

| Day of Week | Births (mm) |
| :---------- | ----------: |
| Sunday | 8.3 |
| Monday | 12.7 |
| Tuesday | 14.0 |
| Wednesday | 13.8 |
| Thursday | 13.7 |
| Friday | 13.4 |
| Saturday | 9.4 | 

## About Dataquest
Dataquest ([dataquest.io](https://www.dataquest.io/home)) is an online code academy which offers educational content relating to Data Science.
