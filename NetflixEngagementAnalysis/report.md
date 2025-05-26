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


## 2. Executive Summary
The overall half-year trend of Netflix engagement using Hours Viewed (HV) metric is fluctuating through the 2023-I to 2024-II. Although it can be said it's in a positive trajectory but there is several caveats that needs to be discussed. 
Firstly, there is a 3.7% dip in HV in the second half of 2023, analysis suggest that this shouldn't be a concern because this is likely due to reduced number of Film titles in that period. 
Secondly, throughout 2024 HV is growing postively, 4,4% in the 2024-I but only 0.1% in 2024-II. This is might indicate that there's a declining trend in growth of popularity in the titles.
Thirdly, this growth decline in 2024-II is mostly contributed by TV Show titles with growth decline and stagnation in both HV metric and Views metric. In 2024-II, TV Show titles grows -0.07% in HV and 0.00% in Views. This is a strong indication that TV Show titles is losing popularity. Meanwhile, Film titles HV grows positively by 0.6% in 2024-II although it reached 2.7% HV growth in 2024-I. The same goes for Views metric with positive 0.6% growth in 2024-II and 1.5% in 2024-I.

## 3. Insights
### a. Trend & Growth Rate
![hv-total](https://github.com/user-attachments/assets/fe5f696e-dad8-4e84-a395-3a32027e41d8) 
> **Graph 3.1 Hours Viewed trend in total**


The above graph shows the overall number of HV of Netflix from 2023 - 2024. In the first semester of 2023 we see that there's about 93.3B hours of spent by the users watching netflix titles then in the next period it dropped to 90B hours but able to recover in the first semester of 2024 to 94B and increased to 94.1B in the second semester.

| Show Type | **2023-II** | **2024-I** | **2024-II** |
|--|--|--|--|
| **Film** | -25,4%  | -2.7%  | 0.6% |
| **TV Show** | 8.5%  | 5.1%  | -0.1% |
| **_Grand Total_** | -3.7%  | 4.4%  | 0.1% |
> **Table 3.1 Hours Viewed growth**

Throughout 2023 - 2024, the growth of Hours Viewed (HV) fluctuate. In the second semester of 2023 there's a decline of -3.6%  but Netflix able to recover with 4.4% and 0.12% of positive growth in the first and second semester of 2024. Notice that in the second semester of 2024 there's quite a significant decline in growth (from 4.4% to 0.12%). As shown in Graph 3.1, further analysis shows that there's a decline of growth in HV by -0.1% in TV Shows while Film titles has positive growth of 0.63%. Although we cannot compare the value of HV from Film and TV Shows, but at least this can indicate that there's a declining popularity of TV Show titles. Furthermore, if we compare the growth in 2024-II from previous period (5% in 2024-I and 8.5% in 2023-II), we can see that there's noticeable decline which further strengthen our assumption that TV Shows titles is declining in popularity. 

<img width="450" alt="image" src="https://github.com/user-attachments/assets/f7712d64-b39b-4d78-9547-a067a98eb25e" />

> **Table 3.2 Hours Viewed growth**

Another evidence we can use is if we use another metric such as Views to further prove that there's popularity decline in TV Show titles. In Graph 3.2, we can see that in the second semester of 2024 the number of TV Show Views in stagnating from 9.72B in the first semester to 9.72 again in the second semester while Film title increased by 90M Views in the second semester of 2024. This further indicate that there's a **decline or at least a stagnation of popularity in TV Show titles**. This matter needs to be addressed to prevent customer engagement decline.

![hv-type](https://github.com/user-attachments/assets/d6554dc0-aa5a-44c0-adb4-0b9cb85655ad) 
> **Graph 3.3 Hours Viewed trend by show type**

Due to it's nature of having longer total duration than Film/Movies, it's not surprising that TV series has higher HV than Film. TV Show titles is averaging around 65B HV while Film titles is averaging around 28B. If we use another metric that doesn't affected by the title duration, like Views, TV Show titles is averaging around 14B Views and Film titles is averaging around 10B Views (excluding 2023-I).



### b. Cause of Decline
| Semester | Num of Title  [Film] | Sum of HV [Film] |  
|--|--|--|
| **2023-II** | -22%  | -25%  |
| **2024-I** | 0%  | 3%  |
| **2024-II** | -7%  | 1% |
> **Table 3.2 Title count and HV growth**

What is the cause of the decline in Film titles HV the second semester of 2023? is it really because of the declining popularity of the Film titles? To answer this, we can use one simple variable, the number of titles. One possible reason for this sudden decline is that Netflix just happen to be reducing the number of Film titles which could directly decrease the number of HV on those titles. From the growth table, we can see that when the Films HV growth dropped by about -25% in 2023-II, the number of Film titles also dropped by about -21% which shows that it is likely that this drop in HV is due to **Netflix reducing the number of it's Film titles**. Assuming all other variables is constant.

Another observation we can analyze is that through 2024, the number of Film titles keeps dropping. Meanwhile, interestingly the number of HV is increasing. What can we derive from this observation? One possibilities is that the popularity of Netflix films in increasing. If the number of titles is decreasing but the number of HV is increasing, this means that with less Films the audience is watching more Films. If the HV remains constant through the period but the number of titles is declining, it means that there is an increase of interest in the audience on watching the titles, let alone an increasing HV. Assuming all other variables is constant, this means that Netflix has manage to cut back their number of Film titles but still manage to increase their HV. Or in simple words, **Netflix manage to optimize their Film titles**.

In conclusion, by examining the two points of observation mentioned above and assuming all other variables is constant, we can **reject** our assumption that the decline in 2023-II is due to the audience decreasing popularity in Film titles. Further observation also indicate that Netflix is able to optimize their Film titles by reducing it's number but still manages to increase it's popularity.

### c. Conclusion
In conclusion, analysis result can be presented in these 3 points:
 - Overall engagement trend is positive with a slowed growth in recent period.
 - The HV decline in 2023-II is not to be concerned, because it's likely due to reduced number of Film titles and Netflix has proven to be able to recover from this decline.
 - There is an indication that there's a declining/slowed growth in customer engagement based on declining growth in both HV metric and Views metric in 2024-II and TV Show titles is the main driver of this decline.

## 4. Recommendation

 - Recent data shows there's a declining trend in the titles popularity, strategic measure need to be taken to prevent further loss.
 - Increase popularity of TV Show titles due to it being the main driver of the recent slowed/decline in titles popularity.
 - Optimizing the Film titles has proven to be successful, the same can be done in TV Show titles if necessary.


