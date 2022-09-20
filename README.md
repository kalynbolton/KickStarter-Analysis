# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends for Louise. 
## Overview of Project
Louise is looking to start a crowdfunding campaign to help fund her play, Fever. She wants to raise money for production with a budget of $10,000. Louise wants to know how other similar plays resulted with their campaigns based on their launch dates and fundraising goals. 
### Purpose of Analysis
For this analysis, we wanted to find the most successful time of year for Louise to launch a production of her play and determine a realistic fundraising goal for plays based on the failure and success of other play productions. 
## Analysis and Challenges
To perform my analysis, I analyzed the data of other crowdfunding campaigns for theater and play productions. The first step I took was creating a pivot table and graph to visualize successful, failed, and cancled kickstarter campaigns. To create the pivot table, I filtered it to show me the amount of each successful, failed, and canceled play throughout each month. This would show me which month would be best to start the kickstarter campaign. 

The second step was creating a chart of outcomes based on different goals different campiagns had made. To do this, I used my Excel skills to calculate the percentages of successful, failed, and canceled plays based on funding goal amounts ranging from less than 1000 dollars to more then 50000 dollars. I used the COUNTIFS() function to collect the outcome of each goal range based on the 'plays' subcategory. I created a line graph from the data I calculated.
### The Analysis of Theater Outcomes Based on Launch Date
My first analysis showed the amount of productions on the y-axis and the months throughout the year on the x-axis. The graph shows that theater productions launched in the middle of the year, mainly spring season, were the most successful. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/97268254/155908925-eff596ab-b484-40e9-a880-daf4c830b539.png)
### The Analysis of Outcomes Based on Goals
My second analysis showed the percentage of successful, failed, or canceled projects on the y-axis and the relationships between the goal-amount ranges on the x-axis. This graph shows that the higher the fundraising goal was, the higher percent chance of failure there was. Overall, plays that had lower goals were more successful.
![Outcomes_Based_on_Goal](https://user-images.githubusercontent.com/97268254/155909768-4ce077fb-6ea0-4159-9861-abd9e110d2d1.png)
### Challenges Along the Way
In my first analysis, I struggled to correctly filter the dates to show me month to month results. At first it only showed me years and then quarters. After spending some time looking through the different filters I was able to get the correct filter for my graph visualization.

In my second analysis, I had trouble figuring out how to get the correct COUNTIF() formula for each cell. There was at least 3 criteria for each cell, therefore a lot of room for error. I overcame this by double-checking all of my work and comparing my final graph to the graph provided to us. 
## Results
### Results of Theater Outcomes by Launch Date
The results of this analysis showed that the worst month to conduct a kickstarter crowdfunding campaign for theater productions is in Ocotber. The best months to start one would be from April to June. 
### Results of Outcomes Based on Goals
This analysis showed that the most successful plays had goals of less than 1000 dollars or between 35000 dollars and 45000 dollars. 
### Limitations and Recommendations
I noticed a couple limitations while conducting this analysis. First, where did our original data come from and how do we now it has all the data needed to make a valid argument for Louise? Second, we did not filter by country in the Outcomes Based on Goals table so I believe there could be different currencies involved, which in turn would cause the data to possibly look different. 

Some other tables to be made for further analysis could be to do a similar Outcomes Based on Goals table but with the filter usng where Louise wanted to have her play, whether that be Great Britain or the U.S.. Also, if possible to gather data on genre-specfic plays and figure out if Louise's play Fever would be more popular based on its genre in certain areas. 

Module #1 in Data Analytics Bootcamp.
