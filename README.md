# Kickstarter_Challenge
Kickstarting with Excel focuses on applying Excel functions and visualizations to a large crowd funding dataset.  
## Overview of Project
Play write, Louise, aims to fund her play “Fever” using crowd funding for the first time.  To assist her in kicking off a successful funding campaign, an analysis was performed on a data set from Kickstarter.  Kickstarter is crowd funding company with more than 4,000 crowd funded projects recorded globally.  
### Purpose
After analyzing the original data retrieved from Kickstarter, filter the data set to relevant projects to provide meaningful insight to Louise.  Louise is preparing to setup her first crowd funded play “Fever”. Use data analysis to guide Louise in mirroring a successful crowd funded campaign.  Louise is specifically looking to understand the relationship of outcomes based on launch date and funding goals.   
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date 
At the beginning of the project we are told Louise has already met most of her funding goals. Before she launches the “Fever” funding campaign, it is important to understand if the launch date could influence the success of the campaign.  Instead of looking at the entire dataset, a focused analysis on the performance of other plays within the Theater parent category was done.  This focused analysis is depicted in the line chart name “Theater Outcomes Based on Launch Date”.

![](Kickstarter%20Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
A second analysis into the outcomes of projects based on initial goal funding requested was completed.   We keep our analysis focused on plays with the Theater parent category.  The projects goal funding had a large range from less than $1000 to greater than $50,000.  We binned the goal funding into 12 bins to clearly see patterns.    

![](Kickstarter%20Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Data set included more than 4000 crowd funding projects spanning multiple project categories globally.  It was important to understand what data was given and which had an impact in the final recommendations.  Most of the data was straightforward and easy to interpret.  The only challenge I had was learning about Unix timestamps and conversions.  Once I became familiar with Unix timestamps, I was able to perform the conversions. 

## Results
As we can see from the line chart “Theater_Outcomes_vs_Launch”, a higher volume of successful projects are launched in May and June.  It is also important to note projects launched in November and December have the lowest number of successful projects.  It is recommended Louise launches “Fever” in May.  

Chart “Outcomes Based on Goals” gives us a snapshot of success rate across different project goal funding targets.  With a goal funding target of $10,000, “Fever” runs a 54% chance of being successful. While the data we were given does look globally at crowd funding, it is missing information which can help us determine why projects fail. 
