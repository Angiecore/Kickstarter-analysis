# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to convert the data to make it readable. Organizing the data for a better understanding in order to perform the analysis to be able to make decisions. 
The background of the data is that we have some entertainment data with categories which includes plays, movies, documentaries, etc. each line has a goal and pledge, deadline and launched date. 
Louise is interested on two analyses. The first one is about theater outcomes based on launch date and the other one is outcomes based on goal. 


## Analysis and Challenges

The first analysis is about the theater category. The tab is called Theater Outcomes by Launch Date. In this tab, I created a pivot table with two filters, parent category which is sourced by theater, and the second filter is years. In the rows we can see the month of the year, and the columns are the outcomes: successful, failed and cancelled. Then a line chart was created for a visual presentation of the data. This chart is filled with accumulative data from 2009 to 2016. We can see by month how many were successful, failed and canceled. 
In the second analysis tab called Outcomes Based on Goals, you can find a table with goal ranges, number of successful, number of failed, and number of canceled. In these cells a COUNTIFS formula was applied in order to get the information requested. Then, in column E we can see a sum of the total projects. Finally, in the table there are percentages of successful, failed and canceled. 
A line chart was included in the analysis for a visual presentation of the data. In summary, this analysis is to show the percentage of successful and failed plays in a determined range of goal. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. A conclusion made about the Theater Outcomes by Launch Date is that there is a trend up from March to May in quantity of successful plays, being May, the best month. Also, May is the month with more plays in total. Additionally, the no cancellations in October, even the data show a higher number of failed plays, the plays are worth enough to continue performing.
2.	The second conclusion is the trending down of successful plays staring in June until September. Even the failed plays keep flat during those months, this represents a significant reduction of successful new plays during those months.

- What can you conclude about the Outcomes based on Goals?
A conclusion made about the “Outcomes based on Goals” is that the most successful plays go in the ranges with lower goals. For example, the ranges: less than $1000 and between $1000 and $4999, they have 75.8% and 72.7% of successful performance respectively. Also, the plays that failed most have the ones with higher goal. For example, the range between $45,000 to $49,999 shows a 100% of failure.

- What are some limitations of this dataset? What are some other possible tables and/or graphs that we could create?
I think we could create a graph to show the total quantity of theater outcomes in a percentage way, so with that data we can determinate which months are more efficient, not only for total quantity. For example, December shows 35 failed plays in our current chart, but if we create the new one, we can see that it is the month with the highest failed percentage plays during the year. 
I could recommend to create a stacked column chart in “outcomes base on Goals” to show in an easy way which months are the worst. 
Finally, it will be great to have a table that shows for how long those plays were on stage, to see if there is a correlation between the time on performance and the successful/failure categories plus the request quantity of attendance by play. As result, with that data we could see if the cost of the entrance will be a factor to consider or not.   
