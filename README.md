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
| :------ | ------: |
| January | 6.95 |
| February | 6.49 |
| March | 7.12 |
| April | 6.83 |
| May | 7.15 |
| June | 7.1 |
| July | 7.5 |
| August | 7.6 |
| September | 7.41 |
| October | 7.26 |
| Novmeber | 6.85 |
| December | 7.12 |

About 45% more births occurred on weekdays than Saturday or Sunday.

| Day of Week | Births (mm) |
| :------ | ------: |
| Saturday | 9.42 |
| Sunday | 8.34 |
| Monday | 12.67 |
| Tuesday | 14.02 |
| Wednesday | 13.78 |
| Thursday | 13.69 |
| Friday | 13.47 |

Annual birth rates were flat from 1994 to 2014.

| Year | Births (mm) |
| :------ | ------: |
| 1994 | 3.95 |
| 1995 | 3.9 |
| 1996 | 3.89 |
| 1997 | 3.88 |
| 1998 | 3.94 |
| 1999 | 3.96 |
| 2000 | 4.06 |
| 2001 | 4.03 |
| 2002 | 4.02 |
| 2003 | 4.09 |
| 2004 | 4.19 |
| 2005 | 4.21 |
| 2006 | 4.34 |
| 2007 | 4.38 |
| 2008 | 4.31 |
| 2009 | 4.19 |
| 2010 | 4.06 |
| 2011 | 4.01 |
| 2012 | 4.0 |
| 2013 | 3.97 |
| 2014 | 4.01 |

Seemingly no birth date of month preference exists. Note: lower births on the 31st date of month are due to only half of the months in the year having a 31st date.

| Date of Month | Births (mm) |
| :------ | ------: |
| 1 | 2.76 |
| 2 | 2.79 |
| 3 | 2.8 |
| 4 | 2.76 |
| 5 | 2.79 |
| 6 | 2.8 |
| 7 | 2.83 |
| 8 | 2.83 |
| 9 | 2.81 |
| 10 | 2.84 |
| 11 | 2.82 |
| 12 | 2.84 |
| 13 | 2.75 |
| 14 | 2.85 |
| 15 | 2.84 |
| 16 | 2.83 |
| 17 | 2.85 |
| 18 | 2.85 |
| 19 | 2.83 |
| 20 | 2.85 |
| 21 | 2.85 |
| 22 | 2.83 |
| 23 | 2.79 |
| 24 | 2.75 |
| 25 | 2.71 |
| 26 | 2.75 |
| 27 | 2.79 |
| 28 | 2.82 |
| 29 | 2.64 |
| 30 | 2.58 |
| 31 | 1.59 |

Looking at the births on 9/11, The data shows a slight decline in the average births after 2001 compared to before 2002. The result is inconclusive due to the volatility of births rates for any specific date of the year. But the births on 9/11/11, a Wednesday, are worth noting: at 7.5k, this is the lowest number of births on 9/11 in the entire 21 year set. Maybe the 10 year anniversary of 9/11/01 was intentionally avoided by many.

| Year | Births on 9/11 (000s) |
| :------ | ------: |
| 1994 | 8.4 |
| 1995 | 11.5 |
| 1996 | 12.4 |
| 1997 | 12.5 |
| 1998 | 12.9 |
| 1999 | 9.6 |
| 2000 | 12.1 |
| 2001 | 13.2 |
| 2002 | 12.4 |
| 2003 | 12.9 |
| 2004 | 9.3 |
| 2005 | 8.0 |
| 2006 | 12.9 |
| 2007 | 14.1 |
| 2008 | 13.4 |
| 2009 | 13.0 |
| 2010 | 8.8 |
| 2011 | 7.5 |
| 2012 | 12.5 |
| 2013 | 12.1 |
| 2014 | 12.1 |

## About Dataquest
Dataquest ([dataquest.io](https://www.dataquest.io/home)) is an online code academy which offers educational content relating to Data Science.
