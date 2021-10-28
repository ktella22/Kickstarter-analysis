# An Analysis of Kickstarter Campaigns

## Overview of Project

### Purpose

This project is to get familiar with different functions, formulas and graphs from the module 1 and using those to filter some data of interests from main Kickstarter dataset spreadsheet. Using that knowledge to evaluate the results in relation to the launch dates and the funding goals of Theatre and Play category and to determine their successful, failed, or cancelled campaign. 

## Analysis and Challenges
All the datasets from the main kickstarter spreadsheet are well organized by so many different groups and categories which include the outcomes, funding goal, country that raise funding, launch date, different categories and so on. In this project, most of the analysis can be accomplished by filtering the outcomes’ goal and launch data respect to Theatre and Play category from main data spreadsheet and carefully examine their trends. 

### Analysis of Outcomes Based on Launch Date 
For this analysis, I made a pivot table that allows me to filter out the outcomes based on the Parent category and the Year of the launch date. I renamed the spreadsheet by “Theater Outcomes by Launch Date”. The data tables included Rows and Columns where rows showed the month of the campaign launch date, and the columns showed the status of the campaign according to our interest in Theater category. A line chart was created based on the datasets from the pivot table that showed Launch Date on X-axis and the counts of outcomes on Y-axis. The image below is the screenshot of the pivot table of a Theater category after the filter.

<img width="250" alt="TheaterOutcomes_LaunchDate-1" src="https://user-images.githubusercontent.com/92502292/139186231-fe432be6-a06e-4d75-b397-af8d8d17c871.PNG">

### Analysis of Outcomes Based on Goals
To determine the outcomes based on Goals, I created a table that includes different number of outcomes based on different set of funding goals. I used Countifs( ) function to get the correct count of each outcomes. While using this formula, I put together different criteria of Play category in multiple columns that includes different range of Goal, counts of individual outcome and percentage of each campaign outcomes. The screenshot of the data table looked like it below:

<img width="511" alt="OutcomesBasedonGoals" src="https://user-images.githubusercontent.com/92502292/139186378-36e733f9-fcd4-4921-86ef-58306ebc93e1.PNG"> 

### Challenges and Difficulties Encountered

One challenge I faced was to include a specific criterion when using Countifs statement. I thought it would be enough to count the numbers by using the Countifs formula directly from main kickerstarter spreadsheet. I did not specify condition of each criteria so I had more counts number of outcome than I should have. After that, I made sure to include the range and each criteria such as successful, failed and play category in the formula. 

## Results

- While looking at the generated line chart of Theater Outcomes by Launch Data plot, the number of successful outcomes varies with different launch date. The failed outcomes are stable and steady with a few fluctuations.  Canceled outcomes are low and consistent throughout the whole year. One conclusion is that the success rate is the highest for based on Theater category Launch date to hit the goal during the month of May. As holiday seasons approaches from October, there is a steady decline in the success rate. Second conclusion will be that as December gets by, the chance of getting successful outcomes will be as close as the failing it. 
- According to the line chart of Outcomes based on Goal, it is a high risk setting the higher goals and the outcomes will be a higher failing rate. To get at least consistent 50% success rate, the funding goal should be set less than $20,000. 
- On Theater Outcomes by Launch Date spreadsheet, the canceled outcomes for Theater category was not available for the month of October. With the missing data for the October month, it will be limited to make an educated decisions whether if this missing information will impact on other outcomes for further analysis. 
- It is also interesting to see a graph of percentage funded based on Parent category. So that it will be helpful for viewers to organize and see which category was funded higher or lower. Additional pivot table that filters the data of funding goal based on country. A plot like this can give an idea of setting the funding goal based on the population or the size of the country. 
