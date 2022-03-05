# Kickstarting with Excel

## Overview of Project

### Purpose
The objective of this project was to perform an analysis of data on kickstarter projects to determine any relationships between the outcomes and launch dates of those projects, with a particular focus on theatre play projects. The results and findings of this analysis will help determine what the best dates to launch a kickstarter campaign for theater plays are in order to increase the chances of a  successful outcome. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis was performed by creating a pivot chart with the outcome and launch date data. The launch date data was used for the row indexes and was grouped by months. The outcome data was used as column headers. The parent category data was used as a filter to only include data on theater projects. The count of outcomes was used as the values to populate the table in order to show the total amounts of successful, failed and canceled theater projects by month. The table also shows the total amount of projects by each column and the grand total of all theater projects. 

![Theater_Outcomes_and_Launch_Table](https://user-images.githubusercontent.com/97644424/156867971-e5048212-1515-44dc-8af4-a9f373cfa0db.png) 

The following line graph was created from the pivot table. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/97644424/156645704-cc9c84b6-c0f8-45f5-ac14-54814e058bee.png)

The graph shows a visual of the number of successful, failed and canceled theatre kickstarter projects over the months that the projects were launched. The lines represent the different outcomes. 

### Analysis of Outcomes Based on Goals
This analysis was performed using conditional and math functions to analyze the relationship between the goal amount and the outcome of kickstarter projects for plays. Using the conditional COUNTIF statement, the columns were populated with the count of plays that matched the outcome in the columns and the goal amounts in the row indexes. In the "Total Projects" column, the sum of each row was calculated to get the total amount of play kickstarter projects within a certain goal amount. The percentage values for the outcomes was calculated by dividing the number of play projects in an outcome by the total number of play projects for that row. 

![Outcomes_vs_Goals_DataRange](https://user-images.githubusercontent.com/97644424/156867982-79f24b6e-0f63-4c09-bdb9-060eecf8fe20.png)

Based on the percentage data a line graph was created with the goal amount ranges in the x-axis and the percentage values in the y-value. The lines represent the different outcomes. The graph provides an easy visualization of the relationship between goal amounts and the outcomes of the play projects. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/97644424/156867993-27a6d811-a42f-4877-8fe1-54d8fd4d8ef3.png) 

### Challenges and Difficulties Encountered
The main challenge I encountered was using the COUNTIF formula. I struggled figuring out how to create a condition to select data between a range of two amounts. Initially, I tried putting two conditions together such as, >=1000<15000, but the calculation would not work. I eventually figured out with some troubleshooting and additional resources that each condition had to be listed separately. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The conclusions that can be drawn about the Outcomes based on Launch Date are that firstly, theater projects have more successful outcomes in all months over the canceled and failed outcomes. Secondly, theater projects saw the largest count of successful outcomes between the months of May and June. From this we can assume that overall a theater project will have a good chance to meet it's campaign goal and that the best time to launch a theater project is between May and June. 

- What can you conclude about the Outcomes based on Goals?
The conclusion that can be made about the Outcomes based on Goals are that play projects have the greatest chance of having a successful outcome if the goal amount is $5000 and under. The percentage of successful outcomes in this range is over 70%. The second goal amount bracket that play projects see the most successful outcomes are between the goal amounts $35 000 and $44 9999. The percentage of successful outcomes in this range is over 60%. However, the overall number of play projects drops significantly after the $25 000 bracket. 95% of all total plays have goal amounts of under $25 000. 

- What are some limitations of this dataset?
A limitation of this dataset is that the contains only data from 2009 to 2017 which aggregated into our line graph. How a kickstarter project will perform in an individual year can vary based on many circumstantial factors. From 2019 and onwards, the world has faced a global pandemic which would have very likely affected any theater projects and theater related project campaigns. 

- What are some other possible tables and/or graphs that we could create?
Other possible tables/graphs that could be created include bar charts that compare theater or play projects by country and tables that compare the goal amount and the amount pledged for theater and plays based on outcome. 
