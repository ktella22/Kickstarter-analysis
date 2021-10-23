
# An Analysis of Kickstarter Campaigns
## Overview of Project
### Purpose
This project is to get familiar with different functions, formulas and graphs from the module 1 and using those to filter some data of interests from main Kickstarter dataset spreadsheet. 
In directory 1, pivot table filtered out some data of interests such as the outcomes based on the launch date of Theatre from parent category. Using a line graph can visualize the trends of Theater outcomes like success, failure or cancellation based on their month of launch date. 
Outcome Based on Goals analysis is to see how many numbers of outcomes of “Play” from subcategory has met their funding goal. The goal is divided into so many groups and each groups with the increments of $5000. countifs( ) function allows to calculate the number of success, failure and cancellations of Play subcategory. All the number of each outcome are separated according to the group of funding goal in column A. Total projects is the sum of all the outcomes. Using Sum formula, total projects can be calculated respect to each goal group. A line chart of Outcomes Based on Goal represents funding goal of each group with the increments of $5000 on X-axis and the percentage of outcomes on Y-axis. 

## Analysis and Challenges
Directory 1 is straightforward and all the instructions on module challenge is clear enough to follow through. The line plot of outcomes based on Launch date of Theatre was generated. To be able to see just the month of the Launch Date on X-axis and in Column A on the line plot, I must remove the “Years2” and “Quarters” from Axis (categories) on PivotChart Fields. 
The video of how to use Countifs() function in the video was really helpful. When I typed in Excel, the two options such as Countif and Countifs appeared, but I chose to work with Countif( ) function by mistake instead of using Countifs( ). The outputs was rejected everytime I hit enter. After researching by googling, I understand the difference between two function in which Countifs( ) is used to apply on cells with multiple ranges. After getting all the right formula and code, generating the line chart is very straightforward.  

## Results
- While looking at the generated line chart of Theater Outcomes by Launch Data plot, the number of successful outcomes varies with different launch date. The failed outcomes are stable and steady with a few fluctuations.  Canceled outcomes are low and consistent throughout the whole year. One conclusion is that the success rate is the highest for based on Theater category Launch date to hit the goal during the month of May. As holiday seasons approaches from October, there is a steady decline in the success rate. Second conclusion will be that as December gets by, the chance of getting successful outcomes will be as close as the failing it. 
- According to the line chart of Outcomes based on Goal, it is a high risk setting the higher goals and the outcomes will be a higher failing rate. In order to get at least consistent 50% success rate, the funding goal should be set less than $20,000. 
- On Theater Outcomes by Launch Date spreadsheet, the canceled outcomes for Theater category was not available for the month of October. With the missing data for the October month, it will be limited to make an educated decisions whether if this missing information will impact on other outcomes for further analysis. 
- It is also interesting to see a graph of percentage funded based on Parent category. So that it will be helpful for viewers to organize and see which category was funded higher or lower. Additional pivot table that filters the data of funding goal based on country. A plot like this can give an idea of setting the funding goal based on the population or the size of the country. 
=======
This Excel project introducted data analysis and visualization by introducting useful functions and formulas such as Countif or Filter function to narrow down the targeted values and parameters from large datasets spreadsheet. Also generating charts and graphs, and interpretting pivot tables to visualize the relationship between two models are helpful for data analysis purposes.

- familiar with different functions and Excel formulas for data analysis. To read the new columns, filter the value of interests and formatting the cells.    

## Analysis and Challenges
Modules 1 lectures are very informative and prepared me to peform for the required analysis. 
code and graphs
explain and write about what challenges.  

The lectures cover most of the challenge directory. The only diffuculities I met was Countif but the video was helpful to understand and create the formula to get the solutions very quickly. It took a while to understand the specific formula and syntax like "$" or "!" in order or else the error responds will return it back right away. 


## Results
- According to the theater Outcomes by Launch Data plot, the month of May has the highest success outcomes for Theater category from the Kickstarter spreadsheet. However, December month would not be a good time for Theater to launch because the failed rate is as close as their success rate in December so that 

During the month of May, the success rate is the highest based on the percentage funded. It is the most ideal time for the Theater launch date. As holiday seasons approaches from October, there is a steady decline in the success rate. In the month of December, the chance of hitting the goal will be as close as the failing it. 

Second and third quarter, fialed rate is very stable. Easy to predict the time to lauch ??

- The plots representing percentage success rate and failed rates are inverted to each other. It is a high risk setting the higher goals and the outcomes will be a higher failing rate. In order to get at least 50% success rate, the goal should be set between  $35,000 to 45,000 or less than $15,000. 

- Theater outcomes based on Launch data plot tells us that there are no regard to Canceling event on October month. With this missing data, the useful information can be left out from the analysis.

- It is also interesting to add the graph about percentage funded based on Parent category. It would help the viewers to see which category was funded higher or lower. Additonal pivot table such as the goals according to the country  
>>>>>>> 7d1f31eee603109c5eb435bc5a51be3cc03aeb5e
