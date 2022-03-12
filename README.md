# **Best Kickstarter Strategies Based on Data**

## Project Overview

### Purpose
The purpose of this project is to show our client, Louise, how different Kickstarter campaigns faired in relation to their launch dates and funding goals.  Louise's play *Fever* came close to its fundraising goal in a short amount of time, and she wanted to know of any correlations between launch dates and funding goals and if they were successful or not.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99417460/158001966-cab91a5e-c6c6-443e-ac75-2d97732d9ce2.png)

In Excel, I used a Pivot Table to filter the data for Theater camapaigns based on their launch date.  I filtered the Pivot Table based on the Parent Category and Years.  I filtered the columns to show "successful," "failed," and "canceled."  From there, I used a line graph to visualize the results.  

Based on the data for theatrical Kickstarters, the months with the hightest successful Kickstarter campaigns in a "Theater" genre are May, June, and July.  However, the months with the highest failed Kickstarter campaigns are also May, June, July, along with October.  

The most likely reason for this correlation is that the majority of campaings start at the same time.  Throughout the majority of the year, the campaigns that were successful and the campaigns that failed followed the same chart trajectory for the same months.  The same rate of successful campaings is similar to the rate of failed campaigns during the same months.

Canceled campaigns remained at the same rate throughout the year, near zero.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99417460/158002222-1b56a07a-73da-4c0e-9466-6dbd127e2d25.png)

With this analysis, filtered the data to the "plays" in the Subcategory column.  I used the "COUNTIFS()" function to count the number of "Successful," "Failed," and "Canceled" plays, and categorized the data based on the goal range.  I then used the "SUM()" function to determine the total projects of each goal category.  I then used the number of successful, failed, or canceled plays, based on the goal range, and divided it by the "Total Projects" column to determine the percentage of the successful, failed, or canceled projects.  I then used a line chart to visualize the goal amount ranges and the percentage of successful, canceled, or failed projects.

Based on the data for plays, 72% of plays with a goal of $1,000 or less failed.  87% of plays that started with a goal of $1,000 to $4,999 were successful.  $100 of Kickstarters with a goal of $10,000 to $14,999 and $35,000 to $39,999 were successful.

### Challenges and Difficulties Encountered

One challenge regarding analyzing this data set is the lack of information regarding Kickstarter campaigns that were canceled.  A potential way to overcome this could be to expand our data set to include more Kickstarter campaigns that were canceled.  Another challenge to sift through was that the overwhelming majority of plays had fundraising goals less that $5,000.  It could be that the majority of Kickstarter campaigns havve goals less that $5,000, but a way to overcome this could be to expand the data set captured.  It could also be that canceled campaigns are outliers of kickstarter campaigns, meaning that there are so few, we should not truly consider them in our analysis.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1.  The months with the highest successful Kickstarter campaigns for the "Theater" category are May, June, and July.
  2.  The months with the highes failed Kickstarter campaigns are also May, June, July, along with October.

- What one conclusion can you make about the Outcomes based on Goals?
  - 87% of plays that started their campaign with a goal of $1,000 to $4,999 were successful.

- What are some limitations of this dataset?
  - Due to filtering down the data set, we went from a large sample size to a small sample size.  This could have hindered our results by limiting our data sample.  
- What are some other possible tables and/or graphs that we could create?
  - A potential graph we could use would be a bar graph to visualize the percentages of Outcomes Based on Goals.
  - Box and Whiskeer plots could be used to show the outliers that have skewed our data.
  












