# Netflix Engagement Analysis: Do Films losing it's popularity?
## 1. Introduction
According to 2024 annual report, at the end of 2024 period Netflix has over 300 million membership. This makes Netflix as one of the biggest streaming service company in the world. Due to membership as their business model, customer engagement become a critical point for the business. In this report, I am going to do a simple analysis of Netflix's engagement using their engagement data which published in their half-year engagement report. Using this data, I will create a simple analysis and try to gain some insight that hopefully will be useful as a reference for Netflix customer engagement or at least to the general audience that curious about this topic.

This analysis report specifically analyzing the data from 2023 to 2024 in half-year period. The data that will be used in this analysis is from Netflix's own engagement report which contains all the titles (Film and TV Shows) that Netflix has with several information/attributes on each titles, that is: 
1. name of the title;
2. the type of the titles (Film of TV Shows); 
3. is the title available globally (Yes/No); 
4. release date;
5. hours viewed (HV);
6. views; and
7. runtime;

It is important to note that not every report data from Netflix has all this attribute. For example, in the first semester of 2023 data, there's only information about the title names, release date, global availability of the titles, and the HV of the titles. This issue limits the scope of the analysis. After considering the severity of the missing data/attributes (several attribute entirely missing from the report data), the significance of the missing data and to generalize each report data, it is decided that 3 attributes will be used, name; type; and hours viewed. The metric that will be used to measure the engagement of the audience is hours viewed (HV) which is the number of a hours a title is watched by the audience. 


## 2. General Summary
The overall half-year trend of Netflix engagement using Hours Viewed (HV) metric is fluctuating through the first half of 2023 to the second half of 2024. Although it can be said it's in a positive trajectory but there is several caveats that needs to be discussed. Firstly, there is a 3.7% dip in HV in the second half of 2023, analysis suggest that this is due to the reduced number of titles especially in Film titles (while number of TV Shows is growing). Throughout 2024 HV is growing postively, 4,4% in the first half but only 0.1% in the second half. 

The two drivers based on type of titles is Film and TV Show. Film titles growth in 2024 is 2.7% and 0.6% while  TV Shows growth in 2024 is 5% and 0.0%.

## 3. Insights
### a. Trend & Growth Rate
Throughout 2023 - 2024, the number of Hours Viewed (HV) grows positively but with a decline of -3.6% in second semester of 2023. but Netflix able to recover with 4.4% and 0.12% of positive growth in the first and second semester of 2024. 

![hv-total](https://github.com/user-attachments/assets/fe5f696e-dad8-4e84-a395-3a32027e41d8)
![hv-type](https://github.com/user-attachments/assets/d6554dc0-aa5a-44c0-adb4-0b9cb85655ad)

The above graph shows the overall number of HV of Netflix from 2023 - 2024. In the first semester of 2023 we see that there's about 93.3B hours of spent by the users watching netflix titles then in the next period it dropped to 90B hours but able to recover in the first semester of 2024 to 94B and increased to 94.1B in the second semester.

One interesting point is the decline in the second semester of 2024. Looking at the preceding period and the following period, it might indicate that there's an anomaly. In the next section, we will discuss the probable cause of this decline.

### b. Cause of Decline
| Semester | Num of Title  [Film] | Sum of HV [Film] |  
|--|--|--|
| **2023-II** | -22%  | -25%  |
| **2024-I** | 0%  | 3%  |
| **2024-II** | -7%  | 1% |

What is the cause of the decline in Film titles HV the second semester of 2023? is it really because of the declining popularity of the Film titles? To answer this, we can use one simple variable which is the number of titles. One possible reason for this sudden decline is that Netflix just happen to be reducing the number of Film titles which could directly decrease the number of HV on those titles. From the growth table, we can see that when the Films HV growth dropped by about 25% in 2023-II, the number of Film titles also dropped by about 21% which shows that it is likely that this drop in HV is due to **Netflix reducing the number of it's Film titles**. Assuming all other variables is constant.

Another observation we can analyze is that through 2024, the number of Film titles keeps dropping. Meanwhile, interestingly the number of HV is increasing. What can we derive from this observation? One possibilities is that the popularity of Netflix films in increasing. If the number of titles is decreasing but the number of HV is increasing, this means that with less Films the audience is watching more Films. If the HV remains constant through the period but the number of titles is declining, it means that there is an increase of interest in the audience on watching the titles, let alone an increasing HV. Assuming all other variables is constant, this means that Netflix has manage to cut back their number of Film titles but still manage to increase their HV. Or in simple words, **Netflix manage to optimize their Film titles**.

In conclusion, by examining the two points of observation mentioned above and assuming all other variables is constant, we can **reject** our assumption that the decline in 2023-II is due to the audience decreasing popularity in Film titles. Further observation also indicate that Netflix is able to optimize their Film titles by reducing it's number but still manages to increase it's popularity.

### c. Conclusion
The audience engagement trend on Netflix titles is fluctuating over the course of 2023 - 2024 with a slowed growth. Furthermore, there's a decline in the second semester of 2023, further analysis suggest that this is not due to declining popularity of the titles but rather due to the decreased number of titles in one of the main driver which is the Film titles. Although decreased, the popularity of the Film titles still increases and able to recover in the next period. Other concern that also need to be addresed is the growth stagnation in the second semester of 2024 with only 0.1% of growth in HV while in the previous period there's a 4.4% of growth in HV. If this trend continue, Netflix could experience a negative growth that can threaten customer engagement. In conclusion, analysis result can be presented in these 3 points:
 - Overall engagement trend is positive with a slowed growth.
 - Growth decline in 2023-II is not to be concerned, because it's likely due to reduced number of Film titles and Netflix has proven to be able to recover from this decline.
 - The drop from 4.4% growth to 0.1% growth in 2024 need to be addressed because if this continue it could result in negative growth.

## 4. Recommendation

 - Increase popularity of both TV Show and Film titles due to the recent slowed/decline in growth of HV.
 - Optimizing the Film titles has proven to be successful, the same can be done in TV Show titles if necessary.


