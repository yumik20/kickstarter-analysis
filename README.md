# kickstarter-analysis
My first project - performing analysis on Kickstarter data to uncover trends.This analysis can help our hopeful playwright, Louise, with her Kickstarter preparations. 


# Kickstarting with Excel
## Overview of Project

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. 
 
### Purpose

This project is to use Kickstarter datasets to visualize the campaign outcomes based on their launch dates and their funding goals for Louise. 


## Analysis and Challenges

When I use the CountIfs function, I did not fix the columns the function refers to from the start, so it took me a while to exam where could went wrong by comparing the functions and the original sheet. 



### Analysis of Outcomes Based on Launch Date

I used 1369 total campaigns in the theater category and performed the analysis. As we can tell from the chart “Theater Outcomes Based on Launch Date”, May seems to be the best month to start a Kickstarter Campaign as it had the most successful amount of campaign from the analyzed cohort, while December seems to be the worse month to start a campaign. 
Overall, May, June, July significantly outperformed the rest of the months in terms of the number of successful campaign. 

![outcomes based on launch date](https://raw.githubusercontent.com/yumik20/kickstarter-analysis/61fdec685d9b4f36466570ec53f63f252502fd98/resources/Theater_Outcomes_vs_Launch.png)



### Analysis of Outcomes Based on Goals

I separated the goals into 12 different ranges, from less than $1000, $1000-$4999, all the way to greater than $50000. As you can see from the chart Outcome Based on Goals, when the goal is less than $1000, the successful rate is the highest and the failed rate is the lowest. Between the range $15000 to $34999 and the range $45000 and above, failed rate is higher than successful rate. It is interesting to see that between $35000 to 44999, the successful rate was higher than the failed rate, and between $45000 to $49999, the successful rate became 0%, but above $50000, there is still less than 10% change of being successful.

![outcomes based on goals](https://raw.githubusercontent.com/yumik20/kickstarter-analysis/61fdec685d9b4f36466570ec53f63f252502fd98/resources/Outcomes_vs_Goals.png)



### Challenges and Difficulties Encountered

When I use the CountIfs function, I did not fix the columns the function refers to from the start, so it took me a while to exam where could went wrong by comparing the functions and the original sheet. 



## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

May seems to be the best month to start a Kickstarter Campaign as it had the most successful amount of campaign from the analyzed cohort, while December seems to be the worse month to start a campaign. 
Overall, May, June, July significantly outperformed the rest of the months in terms of the number of successful campaign. 



- What can you conclude about the Outcomes based on Goals?

When the goal is less than $1000, the successful rate is the highest and the failed rate is the lowest. Between the range $15000 to $34999 and the range $45000 and above, failed rate is higher than successful rate.



- What are some limitations of this dataset?

1. The datasets is somewhat small, only had 1369 samples. 
2. For the failed campaigns, even the pledged amount is quite close to the goal, but they are still counted as failed, there is no data to analyze the relationship & difference between those failed but almost successful campaign VS. successful ones. 



- What are some other possible tables and/or graphs that we could create?

For Outcomes based on Goals, bar chart could possibly worked; for Theater Outcomes Based on Launch Date, bar chart and pie chart might work. 



