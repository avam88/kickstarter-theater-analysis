# Overview
### While theater and play campaigns experience relative success on the kickstarter platform there are a few key elements about these campaigns that greatly impact the outcome. Through this analysis we will drill down into two specific areas of campaign design to help our client determine how best to craft a theater campaign using the kickstarter platform.
### While many elements impact the outcome, here we will be exploring the success rate of theater campaigns based on their launch date and funding goal.

# Analysis
### Our data represented a wide array of data points compiled from kickstarter campaigns, some of which did not pertain to our query. The first thing we wanted to do was to filter out any information that would not directly inform our outcomes. We achieved this in two ways : first we used excels table and chart filtering mechanism and second we used conditional functions (=if and =countifs statements) to eliminate categories of campaigns outside the theatre set and play subset.
### We also needed to analyze datapoints that were not in the original dataset to create compelling arguments for or against certain campaign design elements. We manipulated the data through simple excel functions (=sum(data set) to deliver a total count of successful theater/play campaigns within a specific goal funding range)

# Challenges and Further Consideration
### We believe that this is a healthy and robust data set to pull recommendations from, the data is historically relevant (pulling from the last 10 years mostly) with plenty of data points.
### By setting our extreme funding ranges as <$1,000 and >$50,000 we account for the outliers in the set. Our queries made here however are limited in scope and only tell part of the picture. We made recommendations in the “Recommendations” section about further analysis to help our client define more queries to deliver a picture with better focus.

# Results
### Our project was defined by 2 main wide lens questions: which campaigns have the highest likelihood of success based on their funding goal and which campaigns have the highest likelihood of success based on launch date. In this analysis we will dive into these queries one at a time
## Campaign outcomes based on Funding Goal
### We wanted to determine if there was a relationship between campaign success and the initial funding goal. We asked the data to return only information on theater and play campaigns and we wanted the total count of campaigns that experienced either success, failure, or canceled their venture in goal ranges of $5,000 increments. We gathered and synthesized this data and it returned this chart.
![Outcomes_Vs_Goals](https://user-images.githubusercontent.com/107326987/174421850-46db95c4-0a97-4a07-a108-a04e8c3ee36d.png)
### This chart represents a percentage of failed, successful or canceled campaigns against the total amount of campaigns that fall within the funding range. The first finding worth noting is that no theater/play campaigns were canceled in any goal range. Next, We can see a few relationships visualized here. You can see a general trend that as the funding goal increases, the percent likelihood of success general goes down (with the exception of campaigns with fundings goals between $35,000 - $45,000). Campaigns with funding goals below $15,000 are more likely to succeed than fail. 
	NEED 1 CONCLUSION	

## Campaign Outcomes Based on Launch Date
### Here again we wanted to determine if there was a relationship between campaign success and launch date. We asked the data to return only information on theater campaigns. This chart visualizes the . The count of successful campaigns peaks at May. You can also see that there is a general trend where the kickstarter market is flooded during the summer and wanes in the winter. So it is also important to note that May and June are where you see the largest disparity between successfully launched campaigsn and failed campaigns. 
![Theater_Outcomes_Vs_Launch](https://user-images.githubusercontent.com/107326987/174421879-efefb84e-b3b3-4d34-8586-1e70ad5bc9a1.png)
	NEED 2 CONCLUSIONS

# Recommendations
### It is worth digging deeper in the data 
- Validate that June is the best launch month by creating a chart that shows the percent difference between successful and failed by month, and make sure you’re actually more likely to succeed. Right now you can read graph as just a lot of people launch in June, successful and failed.
- Tease apart this data by year to see if there are year of year trends that reveal themselves. Has there been a rise in successful campaigns that have more aggressive funding goals?
- Tease apart for geography.
- Largest limitation might be that we have not accounted for currency exchange. Not compairing dollars to dollars
- A box whisker chart that accommodates for outliers so that extreme campaigns don’t pollute our data set. 
- Further research to determine what makes campaigns during 35 and 45 follow general trend.




