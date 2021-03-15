# Analysis of DQ Stock Perfomance 

## **Overview of Project**

The following is an analysis conducted for Steve to compare the performance of DQ stock in the years 2017-2018 and provide his parents with a good understanding of which company to invest their money and guarantee a better return of investment. A user friendly button was inserted into the excel spreadsheet to allow Steve to analyze whichever year of stock he desired and for the analysis to be conducted efficiently.  

## **Results**

After coding a loop into VBA to calculate the Total Daily Volume and Return of all stock data provided by Steve, we were able to run an analysis of DQ’s performance compared to 11 other companies for the year 2017 and 2018. DQ had an astronomical return of **199.4%** for the year of 2017 in comparison to the 11 other companies, please reference the screenshot below to view the data.  

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Analysis%20for%202017%20Stocks.png "Analysis for 2017 Stocks")

However, in 2018 DQ’s performance significantly plummeted to a **-62.6%** making it the worst performing company of that year in comparison to the rest, who also went into the negatives for exception of ENPH and RUN. Please reference the screenshot below to view the data.  

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Analysis%20for%202018%20Stocks.png "Analysis for 2018 Stocks")

The analysis was programmed in VBA, the first macro was a thorough step-by-step progress of the code needed to analyze the data of both years, not taking into consideration efficiency and performance of the code. As you will see in the screenshots below, the running time is significantly longer to run, which is not the most ideal for larger data sets. 

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Run%20Time%20on%20Original%20Code%202017.png "Run Time on Original Code 2017")

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Run%20Time%20on%20Original%20Code%202018.png "Run Time on Original Code 2018")

### Analysis of Outcomes Based on Launch Date

Based on the data we had on theatre fundraisers we created a pivot table to filter by successful, failed and cancelled fundraisers based on the month. Once the chart was generated, we were able to observe that campaigns launched during the summer months had a higher success rate compared to the rest of the year. The line graph can be referenced below:

![alt text](https://github.com/Karenjakins/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png "Outcomes Based on Launched Date")

### Analysis of Outcomes Based on Goals

For the analysis on Outcomes Based on Goals, we observed that the if the goal amount is within less than $1000 and up to $14999 the success rate is higher, and the number of failed fundraisers is low. Please reference the line graph below:

![alt text](https://github.com/Karenjakins/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png "Outcomes Based on Goal")

### Challenges and Difficulties Encountered

The biggest challenge I had was when conducting the analysis of Outcomes Based on Goals, when I entered the formula for **=COUNTSIFS** as I entered the wrong angle brackets which provided me with the wrong values. I spent a few hours trying to figure what was wrong so this actually wasted a lot if my time, so next time I will make sure to be more careful when entering my formulas. 

The second challenge was that at some point during the analysis I must have entered or altered some of the values on my spreadsheet and as a result I got the wrong values on one of my tables, so it’s very important to save your progress as you go in separate files to make sure you don’t have to do the ensure process from the beginning. 

## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date? 

Based on the data collected for Theatre Outcomes by Launch Date we can observe that fundraisers launched during the months of April to September have a greater success rate than at any other time during the year. This most likely can be that the summer months are better times to run campaigns are people are more interested in investing in activities. 

- What can you conclude about the Outcomes based on Goals?

Fundraisers with a goal lower than $15,000 tend to be more successful as the amount gets lower, the most successful being a 76% success rate for campaigns under $1000. 

- What are some limitations of this dataset?

There isn’t any data on the demographics of the people who pledged in the fundraiser, perhaps if we knew more about the investors, we could also know how to cater campaigns to target goals based on specific ages groups and interests. 

- What are some other possible tables and/or graphs that we could create?

We could create a table that displays the genre of the play and then create a graph that shows the correlation of success rate based on the genre. 