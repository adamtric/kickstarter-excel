# kickstarter-excel
Excel project for analyzing kickstarter data



## Overview of the Project

The purpose of this project is to understand how different campaigns fared in relation to their launch date and funding goals. By creating visualizations we can see the correlation between these factors and campaigns that either succeeded, failed, or were canceled. Two visualizations (2 Line graphs) were created to showcase these correlations. The analysis of this data will help create impactful decisions for *Fever*.

## Analysis and Challenges

Below is the line graph depicting the correlation between Launch Data and Outcomes of productions.

<img width="240" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/102189324/163723206-612c42dd-33bd-42f4-bb7c-5a6da12e5906.png">

The line graph above showcases the Months on the x-axis and the number of successful/failed/canceled projects on the y-axis. There are 3 lines on the graph to differentiate the successful (blue), failed (orange), and canceled (gray) outcomes. The graph shows a rapid incline of successful shows once May hits followed by a steady decline in the months after May. The failed and canceled lines stay consistent throughout the duration of the graph.

Below is the line graph depicting the correlation between Financial Goal and Outcomes of productions.

<img width="608" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/102189324/163723198-0e7f57ab-d3a0-4cf3-bf7c-1cd3bc6ae459.png">

The line graph above showcases the ranges of Financial Goals on the x-axis and the percentage of successful/failed/canceled projects on the y-axis. There are 3 lines on the graph to differentiate the successful (blue), failed (orange), and canceled (gray) outcomes. The data creates a hex shape between the successful and failed outcomes, consistently showing alternating peaks and valleys between the two outcomes. The highest percentage of successful shows come with shows with goals less than $1,000 and the lowest percentage of successful shows comes with goals between $45,000 and $49,999.

### Challenges

Some challenges could be presented when organizing and analyzing this data. The challenges and difficulties with this data come from the sheer size of the dataset as well as the number of different criteria that was analyzed. For example, when analyzing the goals v. outcomes there are 36 unique COUNTIFS statements used to gather the data needed, with differences in the ranges selected and the outcomes for each. With this editing it can become easy to input a wrong value in the criteria being used. Using the wrong goal range, or using "success" instead of "successful" as a criteria can create errors in the analysis and create a different picture than what is truly happening.
 
## Results
 
### Conclusions based on Theater Outcomes v. Launch Date
 
Based on the graph, it can be concluded that the ideal month to launch a production is May. The month of May has yielded the greatest number of successful shows of any month as evident by the peak in the graph. The ideal time to launch a show is in May. It can also be concluded that there is no correlation between launch date and the likelihood that a production fails or is canceled. The lines representing those two outcomes remain fairly consistent with limited peaks and valleys, indicating that failed and canceled shows are not a byproduct of launch date.

### Conclusions based on Theater Outcomes v. Goal

Based on the graph, it can be concluded that shows with lofty, or high goals have a higher chance to fail than those with more modest goals. We can see based on the graph that shows that had a goal within the 45000 and 49999 range failed 100% of the time and those with goals at or above $50000 failed at a clip of 88%. However, we can see that productions with goals under $1,000 succeeded 76% of the time and failed only 24% of the time. It can also be concluded that shows with a goal in between $1,000 and $4,9999 succeeded at a 73% clip. This range had the greatest number of shows as well with 533 shows. This was 347 shows more than the next closest goal range (Under $1,000). Based on the law of large numbers it can be concluded that productions with goal ranges between $1,000 and $4,999 have a higher likelihood to succeed than any other goal range.

### Limitations of the Dataset

There are some limitations with this dataset, however. As previously mentioned the law of large of numbers can play a big factor in understanding which goal range would yield a higher likelihood for success. However, some of the data we have is very limited due to an under representation from other goal ranges. Although it appears that productions with higher goals fail at a higher percentage, this can be misleading due to the limited number of shows that actually had goals within these ranges. For example, only 20 shows had a goal greater than $40,000. When you take a deeper dive into the data, the graphs can be a bit misleading. If there were more datapoints to speak to the effectiveness of having lofty goals, a true conclusion could be drawn about what goals yield the best chance for success.

 ### Other Tables/Graphs

There are so many graphs and tables that we could create. One that I think would be very beneficial to create would be a graph that would showcase the correlation between the pledged amount and successful, failed, and canceled shows. This could also be created alongside another graph that correlates the percentage funded and the type of outcome. With this data, we could see if these productions set accurate goals and how much money it would take for a show to become successful. This could help provide conclusions about what would constitute as a realistic and highly successful goal.
