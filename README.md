# Python Final Project

## Introduction

The recent election inspired me to take a closer look at election data. I realized that I'm relatively unfamiliar with the patterns and trends in election data for the House of Representatives. I wanted to take a look at how election patterns changed over time and what districts have shown the most change.



## Libraries
The following libraries were used: Pandas and Seaborn



## Data Source
MIT and Harvard provide a wide variety of election data sources which can be accessed here: https://electionlab.mit.edu/data. The House of Representatives election data source that was used contained data between 1976 and 2018 and can be accessed here: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/IG0UN2.



## Data Cleaning
In order to get the data ready for visualization and analysis, I deleted unnecessary columns, created a variable to capture % vote, and pivoted the table so that I could have the % vote for Democrats and % vote for Republicans be two separate columns. I also restricted that data source to just general election data and Democrat and Republican candidates.



## Data Exploration
The first part of my data exploration involved using data visualization to see patterns and trends over time. I initially was thinking of trying to map the data to see changes over time but that proved to be too complicated. I then switched to using heatmaps to observe change in % of Republican and % of Democrat votes in each district.

In addition to the data visualization, I also posed some questions that I used prexisting functions and methods to answer:
1. Which election was the closest between Democrats and Republicans?
2. What district had the biggest drop in % vote for Democrats between 1976 and 2018? 
3. What district had the biggest gain in % vote for Republicans between 1976 and 2018? Was it the same as the answer to 2?
4. What district had the biggest drop in % vote for Republicans between 1976 and 2018? 
5. What district had the biggest gain in % vote for Democrats between 1976 and 2018? Was it the same as the answer to 4?



## Findings
The heatmaps didn't show any obvious trends or patterns. Most of the districts had variation from year to year even if they leaned heavily towards one party. The heatmaps did provide a great way of seeing which states had gained and lost districts over the years, which was an interesting way of seeing how populations grew and shrank over the years. States like Washington, California, and Texas have gained districts while states like Illinois and New York have lost districts. 

Over the years, Minnesota district 8 had the biggest drop in % vote for Democrats, Georgia district 8 had the biggest gain in % vote for Republicans, California district 20 had the biggest drop in % vote for Republicans and Florida district 10 had the biggest gain in % vote for Democrats.



## Summary
Overall, there are no clear cut patterns or trends in most districts, but there are certainly ones that have changed a lot (unsurprisingly) within 42 years. 

While this was certainly an interesting data source to look at, the analysis that was done barely scratched the surface of what could have been achieved. In the futue, it would be interesting to take a deeper look into certain states and to also look at votes for third parties.


