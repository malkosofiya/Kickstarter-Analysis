# Kickstarting with Excel
## Overview of Project
The purpose of this analysis is to determine outcomes based on the launch date and goals. As well as uncover trends and provide data in an easy-to-read format.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
The first step of this analysis was to create a pivot table that helps determine the number of campaigns that were successful, failed and cancelled based on the month they launched. Filters for the parent category and years have also been added to facilitate the search and allow versatility.

<img width="412" alt="Screen Shot 2022-08-16 at 10 56 58 PM" src="https://user-images.githubusercontent.com/110862261/185031748-ea20a16d-8a52-4af3-b7ad-d06e82f89571.png">

### Analysis of Outcomes Based on Goals
To perform this analysis, a table has been created to compare the goal amount and the campaign outcome. We have divided goals into different categories (such as less than $1000 and $50000 or more) which allowed to drill deeper into the data. COUNTIFS formula has been used to successfully identity the number of campaigns that were successful, failed and cancelled. Additionally, this data has been converted to percentages to allow an easy and effortless view.

<img width="819" alt="Screen Shot 2022-08-16 at 11 15 10 PM" src="https://user-images.githubusercontent.com/110862261/185033399-dd707e52-32b2-4d7c-96b3-0fa3730a2864.png">
<img width="540" alt="Screen Shot 2022-08-16 at 11 15 18 PM" src="https://user-images.githubusercontent.com/110862261/185033416-bbb22f3b-ae0a-49f1-b441-5af062a82c3d.png">

### Challenges and Difficulties Encountered
When using large sets of data, the biggest challenge can be ensuring the accuracy of the analysis. Meaning that all the formulas are using correct values and displaying error-free results. This can be especially observed in Outcomes Based on Goals Analysis since it uses a variety of different criteria. In my personal experience, breaking up formulas into smaller parts was very helpful since it provided smaller and easier sections to inspect. Creating additional total formulas was also greatly beneficial since it provided additional ways of checking data and ensuring all the formulas ran correctly. 

## Results
### What are two conclusions you can draw about the Outcomes based on Launch Date?
After Completing Launch Date analysis two conclusions can be made. Firstly, we can observe a clear trend based on the month a campaign was launched and the campaign's outcome, with May being the month with the highest number of successful campaigns. Additionally, this analysis shows that there were very few campaigns cancelled, with about 97% of all theater campaigns concluded. This can help strategically plan future campaigns to ensure success. 
### What can you conclude about the Outcomes based on Goals?
When looking at Goal Analysis we can conclude that campaigns with the lower goals were more successful, where 76% of campaigns with a goal of less than $1,000 were successful, which is the highest success rate observed. While majority (88%) of campaigns with a goal of $50,000 failed. This observation helps to set data driven goals for future campaigns to avoid a chance of failure. 
### What are some limitations of this dataset?
The current dataset is a snapshot of past statistics which has its limitations. For example, the data is only based on years 2009 to 2017, where having more up-to-date information could help creating more dynamic analysis. Additionally, it would be beneficial to explore other elements which contribute to the campaign's outcome, such as a number of team members working to meet the goal. 
### What are some other possible tables and/or graphs that we could create?
There are a few different possible tables and/or graphs that could be created. For example, it might be very interesting to see outcomes based on average donation amount. Morover, creating a comparison between launch date and deadline could also be beneficial to determine the duration of a campaign and then further compare it to the campaign's outcome.  
