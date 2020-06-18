# Python_Advanced_Pandas_Features_2_HypothesisTesting

Hypothesis: University towns have their mean housing prices less effected by recessions. 
H0: Mean housing prices before and after recession (here Q32008) do not vary based on location in University towns
H1: Mean housing prices before and after recession (here Q32008) are less affected by Recession in University towns

Data Used:

1. https://www.zillow.com/research/data/
City_Zhvi_AllHomes.csv has median home sale prices at a fine grained level

2. https://en.wikipedia.org/wiki/List_of_college_towns#College_towns_in_the_United_States
List of University towns in United States

3. https://www.bea.gov/data/gdp/gross-domestic-product#gdp
quarterly GDP Data

Key activities:
Data cleaning using Python Pandas
Merging Pandas Databses for data analysis
Hypothesis Testing

Test Results:
We reject the Null Hypothesis H0 with a p-value of 0.0027. Thus, Mean housing prices before and after recession (here Q32008) are less affected by Recession in University towns
