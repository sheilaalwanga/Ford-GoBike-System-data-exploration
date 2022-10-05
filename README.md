# Ford Gobike system data exploration
## by Sheila Alwanga Olayo


## Dataset

This dataset includes information about individual rides made in a bike sharing system covering the greater San Francisco Bay area, for the month of February, 2019.

My dataset initially had 183,412 records and 16 columns. However after some wrangling which involved dropping records with null or inaccurate values and some feature engineering, the dataset now has 174,877 records and 21 columns. The five additional columns include **'date', 'day', 'day_period'** derived from the **'start_time'** column, **'age'** derived from **'member_birth_year'** column and **'duration_min'** derived from the **'duration_sec'** column.


## Summary of Findings

For the exploration, my main focus was on how different features of the dataset affected the number of bike rides as a whole or at any given point in time.
I found that the features of interest were largely independent with only slight variations when plotted against each other and in other instances, no variations at all. 
The ride duration showed slight variations when plotted against period of day, day of the week and gender and no correlation when plotted against age.
There were also slight variations in the number of rides logged for certain values of day period when plotted against days. However, there was no effect on the number of rides when the period of the day was plotted against gender, neither was there any effect when the days were plotted against gender.

## Key Insights for Presentation

For the presentation, I focus on time and demographic information and how they affect the numbers of bike rides. First, I introduce each of the features independently, showing their distributions and frequencies starting with **ride duration**, **period of day**, **day of the week**, **gender** then **age** in that order.
Afterwards, I show how combinations of these features affect the numbers of bike rides with respect to each other. By first  plotting **ride duration** against **period of day**, **day of the week** then **gender**. Then plotting **period of day** against **day** .








