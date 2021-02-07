# Kickstarting with Excel

## Overview of Project
This project analyzes Kickstarter data for playwrights. The intention is to gain a greater understanding of what makes Kickstarter campaigns truly successful, specifically in both the "plays" subcategory and "theater" parent category, looking at how different campaigns fared in relation to their launch dates and their funding goals.

### Purpose
The purpose of this project is to assist in the budgeting of Kickstarter data for practical application in planning. By analyzing what drives successful and failed campaigns, particularly in the "plays" subcategory, we can discover new ways to budget the project accordingly - setting appropriate goals and driving better funding to the campaign.

### Background
The dataset comes from Kickstarter, a site dedicated to crowdfunding. The year and method of collection was not noted, but the dataset was given to reflect some of the site's various collection of campaigns.  
<br>

## Analysis and Challenges
Since the data is indicative of either the "Theater" parent category or the "plays" subcategory, the analysis is not representative of all Kickstarter data. 

### Analysis of Theater Outcomes Based on Launch Date
Based on the "Outcomes Based on Launch Date" data, we can see that there are more successful campaigns than failed ones, which is promising for a new playwright to get their campaign funded. The canceled campaigns are very low through every month relative to the successful and failed campaigns, meaning that many campaigns stick until the end. The highs outcomes for success in the Theater parent category come in the months of May, June and July, while there is a clear low value of December. December is interesting, for it is the closest point to where successful and failed campaigns intersect (but do not), indicating that there is a lot less preference to successful campaigns in December. 

### Analysis of Outcomes Based on Goals
Based on the "Outcomes Based on Goals" data, there are some clear points about where funding drops off from being successful. In particular, this can be found with loftier goals, as goals in the subcategory "plays" with amounts over $45,000 do not seem to successful. As well as this, from goals at $15,000 and up, there seems to be more failures than not. Although between goals of $35,000 - $49,000 there seems to be more successful ones than not, there is not enough data to confidently say that there is a clear correlation (only 9 projects out of 1047 total were found here). For the sake of my analysis, it does not show a true trend in the data. In the lower range of goals, the number of projects evaluated is the largest. Therefore, based on the graph, we can clearly see that outcomes below $15,000 seem to have higher success rates than most of the population.  

### Challenges and Difficulties Encountered
Some challenges in the project I encountered were:
* Bracketing for Large Excel Functions: The problem with large data analysis with Excel functions is that, when it comes to monetary brackets, the way Excel interprets COUNTIFS() can be difficult to work with, especially when you are trying to find data that matches your criteria for particular goal values. I fixed this problem by taking the area and coming up with a standard formula that I could apply to the bucketed cells, and repeat the formula with slight changes each time.
* Challenges of spread: In the beginning, I had taken the dataset for granted, thinking all goal amounts were varied. I didn't notice the obvious spread towards lower goal amounts, which was only brought to me once I analyzed the "Outcomes Based on Goals" dataset. This was solved through more thorough investigation and descriptions of the dataset.<br>

## Results
Our results are separated by conclusions and a brief discussion about limitations of our study. The observations and conclusions that we've made can always be improved upon, as we will discuss after our findings. 

### Conclusions
- What are two conclusions you can draw about the Outcomes based on Launch Date?
<br>Based on the sheet "Outcomes based on Launch Date", which contains both a table and graph, we can infer the following:
    1. For sucessful Kickstarters in the "theater" parent category, May through July seem to be the best months to raise a successful campaign. In particular, May is the top month for Louise to start a campaign, since it has the highest amount of successful campaigns. Not only this, but the 2 other highest months are June and July, which are the following months. For a Kickstarter campaign, the duration may span over multiple months, and making one in this period of time may increase her liklihood of being fully funded.   
    2. It would be advisable for Louise to not schedule a campaign for December, since based on our data there is a much lower amount of successful campaigns during this timeframe.

- What can you conclude about the Outcomes based on Goals?
<br>Based on the "Outcomes based on Goals", we can reasonably advise Louise to not set her campaign goal too high. There is a fairly obvious trend from campaigns set at $15,000 - that success rate dips below failure rate. However, based on the volume of the data collected and the strength of the relationship illustrated in the graph, it seems as though the outcome may be more favorable for Louise's goal if she sets it lower.
<br>

### Limitations of the Data
To discuss limitations of the dataset, it would be first important to know the exact data we are dealing with. We do not know the exact method of extraction that the data was given to us through, so there is a possibility of bias or a skewed segment of the data being drawn. On top of this, from [Statista](https://www.statista.com/statistics/235405/kickstarter-project-funding-success-rate/#:~:text=This%20statistic%20shows%20the%20share,gone%20into%20successfully%20launched%20projects.), we know that $4.9 billion have been funded on Kickstarter campaigns. However, from this dataset, we only have only a little over $46 million in data of only pledges, which highlights a clear sampling from the larger population.
<br><br>In terms of the data itself, the latest year in our data was in 2017, which means the data we are analyzing may be outdated, as we are currently performing this study in 2021. External factors such as the COVID-19 pandemic may have altered the nature of Kickstarter campaigns, especially in an industry as hard hit as the theater industry.

- What are some other possible tables and/or graphs that we could create?
<br>To expand on the data further, we could add the following tables to enhance our analysis:

  - **Outcomes by Campaign Duration**: This graph would show us how long each campaign lasted, and what their outcomes were. This could enable us to see whether or not shorter campaigns create a greater sense of urgency, making people more motivated to help out.

  -  **Percent pledged relative to their goal by dollar value**: By analyzing the percentage of actual dollars that each campaign hit or missed their mark by, we may be able to gain a greater insight in just how well some campaigns could do.   

  - **Average pledge amount by country**: The purpose of this graph would be to see what countries may be more receptive to theater, and give more per capita as a result. For Louise, it could help her possibly set her stage up in a new location, or at least seek funding in different locations instead. 