# Kickstarting with Excel

## Overview of Project
In this challenge we analysed Kickstarter Campaigns to uncover trends for Louise who is looking to raise a campaign to fund her play
### Purpose
The purpose of the analysis is to uncover how campaigns perform in relation to their launch date and and funding goals
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To understand how campaigns performed in relation to their launch date and funding goals, I used Pivot tables.
The Pivot Table helped to summarise, sort, reorganise, and the table in rows and colums.
The Pivot table was graphed to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date, using months to understand the trend.
<img width="240" alt="Theater Outcome Vs Launch" src="https://user-images.githubusercontent.com/57429123/156898920-f31ee27c-fc87-46b7-9038-f86954c0f2ab.png">

### Analysis of Outcomes Based on Goals
To understand how campaigns for play performed, the COUNTIFS function in Excel was used to analyze the percentage of plays that were successful, failed, and/or canceled based on the funding goal amount. 
Campaign goals were grouped into ranges and the number and percentages of successful, failed and canceled plays were calculated and graphed to visualize the trend and performance
<img width="244" alt="Outcomes Based on Goals" src="https://user-images.githubusercontent.com/57429123/156899275-468fbc2f-773f-4039-9a9b-bd0956908be8.png">

### Challenges and Difficulties Encountered
On the use of the Pivot table, the category to use so we could see performance based on date was a challenge. 
I became confused on which categories should go to the columns, row, and value sections. There was also a challenge as to how to get the date in Months since they were in years and quarters
On the use of COUNTIFs, I initially was using COUNTIF instead of COUNTIFS function and was recording errors. Even after getting the function correct, I encountered a challenge populating the other columns of the table

## Results
Analysis of the data revealed that, campaigns launched between April and July are more likely to acchieve their goals that those launched in the beginning and end of the year
campaigns launched in May are more successful
From the analysis, campaign goals ranging from USD 5000 - 45,000 are more likely to be successful

### Limitations
The dataset is limited in scope because there are no data on other sources of crowdfunding campaigns/companies to compare and to draw more significant insights

### Other Considerations
The data could be analysed by country to see a trend of which country have Kickstarters with the highest rates of success and which ones have the lowest rate of success.

