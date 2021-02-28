# Kickstarting with Excel

## Overview of Project
This project started as a set of data with over 4,000 kickstarter campaigns in which Louise would like to compare to her new play called, Fever. She has a $10,000 goal set for this play and would like to see other plays goals/ outcomes for comparison. I have narrowed down the data by color coding the success of each play, separating categories, providing visual charts to aide in presenting the data, converting the time into a more readable format, separating specific data that Louise has interest in, and calculating average and median pledges/goals of plays that Louise has other interests in. 

### Purpose

This set of Kickstarter Crowdfunding campaigns will help Louise with her play she wrote called Fever, in comparing it to other funded campaigns and their success based on launch date, funding goals, and location in which the play was held. 

## Analysis and Challenges
1.	The outcomes of the data were color coded to make it easy to visualize successful campaigns from failed or cancelled ones.
2.	Adding additional columns to the original set of data to allow a better breakdown such as percentage funded, separating the parent categories and subcategories, and calculating the average donation (=ROUND) was necessary to give Louise a better idea on how to approach campaigning her play, I ran into “error” codes due to the dividing by zero and solved it by using the IFERROR function.
3.	Reformatted the Unix time stamp to easily show how long each campaign was active for.
4.	Separating the successful and the failed campaigns into smaller sets of data allowed me to calculate the statistics of the successful and failed campaigns to give Louise an idea of the =MEAN pledged/goal, =MEDIAN pledge/goal, and the quartiles(=QUARTILE.EXC), standard deviation(=STDEV.P), and IQR of both. 
5.	Created pivot charts to demonstrate the outcomes of theater and plays in the US and GB. Also created a line chart to easily visualize which months of the year had higher successful theater outcomes.
6.	Used VLOOKUP to find specific campaigns Louise is interested in from the Edinburgh Festival fringe.
7.	Used the Find function to search two plays Louise was particularly interested in: Foresight and Walken on Sunshine.
8.	A Box and Whisker plot was very valuable with this set of data to show Louise the mean goal of campaigns along with medians and where the outliers lay in comparison.  

### Analysis of Outcomes Based on Launch Date
This pivot chart demonstrates that May is the best month for successful campaigns and December being the least successful. 
 
![image](https://user-images.githubusercontent.com/78769464/109411714-a57ea700-7969-11eb-99ad-0fd11d2e5b69.png)

### Analysis of Outcomes Based on Goals

1.	This pivot chart shows in comparison to other funded campaigns that plays have a significantly higher amounts of campaigns tried and more than 1.5x the failed amounts of campaigns were successful in the US. 
 
![image](https://user-images.githubusercontent.com/78769464/109411741-cd6e0a80-7969-11eb-94c0-61adea5bd54a.png)

2.	Foresights in GB play was pledged at $2004 which is $4 over their goal and Walken on Sunshine US play was similar to Fevers goal at $10,000 and surpassed it at a pledge of $12,325. 
3.Although Walken on Sunshine is a US play, has the same goal, and was successful at reaching it- the mean goal and pledges of successful plays is around the $5,000 range. According to the statistics based on the successful and failed plays, the average higher goals closer to the $10,000 goal like Fevers, failed. 
 
![image](https://user-images.githubusercontent.com/78769464/109411749-d959cc80-7969-11eb-93ee-03371bd347be.png)

4.	The Edinburgh Festival Fringe plays that Louis was interested in were all funded by Kickstarter and were all successful. It does show that the lower average donations have more backers compared to the higher priced donations. 
 
![image](https://user-images.githubusercontent.com/78769464/109411753-e1197100-7969-11eb-974f-e2cae81a4c60.png)

5.	Based on the Box and Whisker plot – The mean goal is about $4000 but the successful campaigns have a pledged amount of about $1500. 

 ![image](https://user-images.githubusercontent.com/78769464/109411765-f2fb1400-7969-11eb-83f3-277222fcd43b.png)

## Results
There were many results that can be drawn from this data: 
1.	May is the most successful campaign month and December has the lowest number of successful campaigns with January following with the higher number of failed campaigns. 
2.	Outcomes based on goals showed that the higher the goal, the higher chance of a failed outcome. It also showed that the largest number of projects goals range between $1,000-$4,999.
3.	The limitation that was already listed in the assignment was noted that some of the funding is specific to theater building but none of the data specifies what the funding is applied to. So some of the larger goals that cause outliers could be due to building expenses.
4.	We could make a chart to compare backers to pledge amounts to give Louise an idea of how many people she would need to target to meet her goal.


![image](https://user-images.githubusercontent.com/78769464/109411679-70725480-7969-11eb-81a0-06c46cfd5ef1.png)
