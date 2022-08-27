# Kickstarter_Challenge
Module 1 Challenge 
# Kickstarting with Excel

## Overview of Project

### Review and Analyze kickstarter success for Theater Kickstarters based on Launch Date and subcategory Play Kickstarters based on goal and success category. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
#### A review was completed with the following steps: created a new column on the kickstarter data using the Year formula, created a Pivot table with the kickstarter data, added filters to the pivot table to allow us to filter by the parent category of theater and year, used pivot table groups to summarize the dates by month, selected only the three categories of successful, failed, and canceled, and sorted the columns in descending order. A line chart was created using pivotcharts to display outcomes by month for theater kickstarters based on the categories of successful, failed, and canceled. 

### Analysis of Outcomes Based on Goals
#### A review was completed to analyze kickstarters with the sub category of plays based on outcomes. In order to complete this review, we created a new sheet within the workbook with columns for goal ranges, outcomes, total projects, and percentage by outcome. Goals were broken down based on amount in groups of less than 1000, 1000 to 4999, 5000 to 9999, 10000 to 14999...continuing through 49999. A goal amount grouping of greater than 50000 was added to capture all additional kickstarters. The excel Countifs formula was then used to determine the amount of kickstarters within each goal range for the outcome of successful, failed, and canceled within the subcategory of plays. Absolute references were added to the Countifs formulas to ensure the columns referenced did not move when dragging the formulas across columns. The sum formula was used to calculate the total amount of projects in each goal range. We then added a percentage of total projects by each outcome. The percentages calculated were then updated to the number format of percentage. A line graph was then created to visually display the percentage outcomes by goal.  

### Challenges and Difficulties Encountered
#### The biggest challenge encountered from a technical excel stand point was to utilize the pivot table grouping in the first analysis based on lauch date. I had not previously used this method for grouping a pivot table. In the second analysis, my biggest challenge was reading the instructions completely. I initially failed to add the sub category of plays to my countifs formula. Once added the line graph created match the expected result. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
-- The highest amount of successful kickstarters start in May. The next two highest months are June and then July. May also has the highest successful percentage at 67%. December has the lowest volume of kickstarters in total and also the lowest amount of successful kickstarters. December also has the highest failed percentage by month of total at 47% failed.  
![Theater_Outcomes_vs_Launch](https://github.com/codfjenn/Kickstarter_Challenge/blob/main/Theater_Outcomes_vs_Launch.png) 

- What can you conclude about the Outcomes based on Goals?
-- The highest amount of play goals were within the range of 1000 to 4999. The goal with the highest successful percentage was less than 1000; however, the range of 1000 to 4999 was second and had almost 3 times as many projects and almost 3 times as many successful. Based on volume and success, the range of 1000 to 4999 seems to be the most ideal window. See visual below.
![Outcomes_vs_Goals](https://github.com/codfjenn/Kickstarter_Challenge/blob/main/Outcomes_vs_Goals.png)

- What are some limitations of this dataset?
-- The data set for reviewing plays is was broken 12 different goal ranges. The lowest three ranges of less than 1000, 1000 to 4999, and 5000 to 9999 make up 85% of the total dataset. Therefore, the percentage in the graphs for success of goals greater than 10000 have minimal data to review. I have added a visual below in the other tables section to support this statement. Another potential area for review would be what is the current success for projects that are currently live. 

- What are some other possible tables and/or graphs that we could create?
For Outcomes Based on Launch date, I have converted this view to a Stacked Column chart combo with a line to allow us to add totals to each stacked column. This view allows you to easily see the amount month with the outcomes. 
![Theater_Outcomes_Stacked_Bar](https://github.com/codfjenn/Kickstarter_Challenge/blob/main/Theater_Outcomes_Stacked_Bar.png)

Below is a pie chart for the outcomes based on goals for play. As noted in the limitations, this chart shows how the sample is mostly goals of less than 15000. 
![Percent_of_Total](https://github.com/codfjenn/Kickstarter_Challenge/blob/main/Percent%20of%20Total.png)
