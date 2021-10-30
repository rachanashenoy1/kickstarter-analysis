# Kickstarting with Excel

## Overview of Project
An analysis of kickstarter campaigns. Vlookups, Pivot tables, mean, median and mode, along with outlier analyses were used to uncover trends for the given data. 

### Purpose  
This analysis was performed on the kickstarter campaign data to unlock underlying trends to create succesful Kickstarter campaigns. 

## Analysis and Challenges
*The analysis was done on Louise's kickstarters campaigns for theaters and analysed based on time of launch and the goal of the campaign.  

### Analysis of Outcomes Based on Launch Date
*Created an analysis of the kickstarter campaigns by the month it was launched. The goal of this analysis was to determine the campaign outcomes over time for theater related kickstarters. 
*Results can be found here. ![Theater_Outcomes_vs_Launch](https://github.com/rachanashenoy1/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
*Used pivot tables and a line chart to complete the analysis. The pivot table also had to be sorted and filtered to get the right results.

### Analysis of Outcomes Based on Goals
*Created an analysis of kickstart campaigns to determine the success rate based on the goal amount. 
*Results can be found here. ![Outcomes_vs_Goals](https://github.com/rachanashenoy1/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
*Used countifs formula to create the underlying data table and created a line chart to determine the % of campaigns that were successful, failed and canceled.

### Challenges and Difficulties Encountered
*I faced a challenge with the syntax of the countifs formula; I received an error several times before I realized I needed to use countifs for multiple if conditions instead of countif. The issue was solved by using countifs.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
* Campaigns that were launched during May were the most successful. 
* The month of December had the most number of failed campaigns. 

- What can you conclude about the Outcomes based on Goals?
*Campaigns with a goal of between $1000 to $5000 were the most successful.

- What are some limitations of this dataset?
All the goal and pledged values are in multiple currencies. This might cause some of the analyses to be inaccurate. 


- What are some other possible tables and/or graphs that we could create?
*Campaign outcomes by country
*Campaign outcomes by category
