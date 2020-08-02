# Week-1-Challenge
Analysis of Kickstarter data for Week 1 Challenge
# Kickstarting with Excel

## Overview of Project
This project is an analysis of Kickstarter data from 2010 to 2017 using Microsoft Excel 2016.  The campaigns covered multiple categories and subcategories.  The focus of this analysis is on theater campaigns.  The two analyses conducted were on outcomes based upon launch date and outcomes based upon fundig goals.  Analysis was conducted using various descriptive statistics, Excel functions, pivot tables and pivot charts.

### Purpose
The purpose of this analysis is to visualize and understand the relationship between campaign launch dates and the campaign's funding goals.  The client would like to know how successful other campaigns were relative to their launch dates and funding goals.

## Analysis and Challenges
As previously mentioned, two different analyses were conducted both using outcomes as the dependent variable.

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes Based on Launch Date](https://github.com/smulhern03-bootcamp/Week-1-Challenge/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)

The above chart shows, by month, shows how many theater campaigns are successful.  Based upon the data, May is the ideal month to launch a campaign with its very clear spike in successful campaigns relative to other months (111 successes).  This May launch time is a small window to launch campaigns, as the data also shows a very steep, steady decline over time with a year low of 37 campaign successess.  In contrast, the failed campaigns hold steady over time within a range between 30 and 55.  There was a low of 31 failed campaigns in November and a high of 52 failed campaigns in May.  Overall, May was the busiest month of the year with both the highest amount of successful campaigns and the highest amount of failed campaigns.  

Needs analysis over success/failure rates to determine porportionality of successes/failures relative to total campaigns.

### Analysis of Outcomes Based on Goals
![Outcome Based on Goal](https://github.com/smulhern03-bootcamp/Week-1-Challenge/blob/master/Outcome%20Based%20on%20Goal.png)

On the impact of goals on outcomes, the data shows that campaigns that are less than $4,999 have the highest percentage of successes (76% for less than $1,000; 73% for between $1,000 and $4,999).  The chart shows a direct relationship between goal amount and success/failure rate - as the goal amount goes up, the failure rate goes up.  The area between $35,000 to $44,999 shows a deviation from this consistent relationship.  However, the number of total campaigns in that price range was 9 total campaigns (4 and 2 successes relatively).  The success of those campaigns should be looked at as an exception.  In contrast, the more steady, above 70% success rate for the $0 to $4,999 brackets had a total of 720 campaigns, with 529 successes.  Thus, keeping a theater campaign's goal below $4,999 is a safer, more likely to succeed funding goal.
### Challenges and Difficulties Encountered
While no real data processing or analytical difficulties were encountered, I did have an (easily fixed) issue with the autofill down the column. Autofilling the formula for the Outcome Based on Goals analysis was the most time consuming part.  I did not use the $ for the needed column and rows so each cell had to be individually changed from the autofill's assumed column to the correct column.  Unfortunately, I did the brute force path where each was changed individually, but I now know about adding the $ to create the formula to only use the designated columns.  This could have also been overcome by creating a separate worksheet containing only the two columns I needed instead of trying to keep the formula within the larger worksheet that have multiple columns of data I was not going to use.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
May is the best month to launch a campaign; however, it is also the most failing of months.
While not included in the graphic, December was the only month with a less than 56% success rate.  While May is the most successful month, 11 out of 12 months in the year have better than 50% chances of success.

- What can you conclude about the Outcomes based on Goals?
Having smaller campaigns is the safer option.  Keeping the goal below $4,999 gives you above 70% chance of success with your campaign.  There is a very clear negative relationship between success and targeted goal.

- What are some limitations of this dataset?
The data does not (and really cannot) factor in the qualitiative aspects of the campaigns.  Did the creator market their product well?  Was the creator engaging with the contributors to answer questions?  If so, this could result in more contributions from people already contributing or new contributors seeing that their money would be well spent.  Refined data analysis is useful but it cannot bring into the more subtle aspects of human engagement - or at least this dataset does not.

- What are some other possible tables and/or graphs that we could create?
Present the porportionality of successes to failures relative to the total numbers of campaigns - 4 successful campaigns out of 6 total campaigns gives the illusion that between $35,000 and $44,999 can be easily done as more than half of campaigns were successful, but that number does not include any extra effort the creators put into their campaigns - marketing, engagement, stretch goals, etc...

Number of backers for each successful campaign and their donations.  What percentage of successful campaigns have lots of small donations vs a few large donations.

Donations over time relative to launch date, goal date and goal achieved date.  Do campaigns that run for six months see more success over time or less success?  How long does it take for these campaigns to hit there target goal?  Is there anything about campaigns that hit their goal within days or hours?
