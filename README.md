# Analysis of DQ Stock Perfomance 

## **Overview of Project**

The following is an analysis conducted for Steve to compare the performance of DQ stock in the years 2017-2018 and provide his parents with a good understanding of which company to invest their money and guarantee a better return of investment. A user friendly button was inserted into the excel spreadsheet to allow Steve to analyze whichever year of stock he desired and for the analysis to be conducted efficiently.  

## **Results**

After coding a loop into VBA to calculate the Total Daily Volume and Return of all stock data provided by Steve, we were able to run an analysis of DQ’s performance compared to 11 other companies for the year 2017 and 2018. DQ had an astronomical return of **199.4%** for the year of 2017 in comparison to the 11 other companies, please reference the screenshot below to view the data.  

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Analysis%20for%202017%20Stocks.png "Analysis for 2017 Stocks")

However, in 2018 DQ’s performance significantly plummeted to a **-62.6%** making it the worst performing company of that year in comparison to the rest, who also went into the negatives for exception of ENPH and RUN. Please reference the screenshot below to view the data.  

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Analysis%20for%202018%20Stocks.png "Analysis for 2018 Stocks")

The analysis was programmed in VBA, the first script was a thorough step-by-step progress of the code needed to analyze the data of both years, not taking into consideration efficiency and performance of the code. As you will see in the screenshots below, the running time is significantly longer, which is not the most ideal for larger data sets. 

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Run%20Time%20on%20Original%20Code%202017.png "Run Time on Original Code 2017")

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/Run%20Time%20on%20Original%20Code%202018.png "Run Time on Original Code 2018")

Once the script was refactored to run in a single macro, we were able to reduce the run time which will help Steve run his future analysis more efficiently when the datasets are much larger. The screenshots below show that for both 2017 and 2018 the run time has decreased to 0.20sec respectively. 

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png "VBA_Challenge_2017")

![alt text](https://github.com/Karenjakins/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png "VBA_Challenge_2018")

## **Summary**

Overall there are clear advantages to refactoring code for this analysis, it not only saves processing time, it also makes the VBA macro screen look more structured, easier to read and functional. However, the process does take a higher degree of understanding of the logic and functions of the programming language which can be hard to comprehend as a beginner, it certainly was more time consuming as one needs to figure out ways to simplify the script written initially. I believe with practice and perhaps more clear instructions refactoring is the best and most efficient method. 

The notes provided as guidance for the final VBA script certainly made the process simpler, and were a useful guide to achieve the end results. Adding notes to code can certainly clarify the process for future endeavours but an understanding of the logic and functions certainly always needs to be the case for refactoring script to be the most useful. 