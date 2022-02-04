# PyBer_Analysis

## Purpose and Objectives 

In this repository, ride sharing data was analyzed using pandas and Matplotlib to ontain insights according to city type. The analysis was then used to make suggestions about improving the business model and improve profit margins.

## Analysis and Results

![Fig1](https://user-images.githubusercontent.com/92544151/152470383-d6498ab6-fcd6-46b2-9368-8ecf8e606288.png)

Figure 1 was a scatterplot snapshot of the dataset. The image shows us the relationship between the average fares and the total number of rides (per city) for each type, rural, suburban and urban. Circle sizes correlate with the driver count for each city. Easy to see the difference in driver count between urban and rural cities. The plot also shows us that the average fares are higher for most rural cities when compared to urban ones. 

![Fig2](https://user-images.githubusercontent.com/92544151/152470921-03d3dd27-4aa1-4237-a317-fe31365c345a.png)

Figure 2 lets us see how the number of rides differ per city type.

![Fig3](https://user-images.githubusercontent.com/92544151/152470978-f58eac19-3a0f-4357-a568-8a870eb59134.png)

Figure 3 highlights the fare ($USD) differences between the three city types. Rural city type has the largest interquaartile range of the three, as well as having the highest median value. 

![Fig4](https://user-images.githubusercontent.com/92544151/152473645-c82159f5-d6f0-4afd-ad5b-6d0d03e30ac7.png)

Figure 4 shows us the disparity in the number of drivers available per city type. 

![Fig5](https://user-images.githubusercontent.com/92544151/152472182-f22a723d-ce9d-42e0-b127-1f52af9eedb5.png)

This figure is a representation of % total fares and it's clear that majority of the total fares are urban cities. 

![Fig6](https://user-images.githubusercontent.com/92544151/152472351-75eda4c0-c8ef-48f3-a497-ff1af883fd73.png)

Figure 6 shows that vast majority of the % total rides come from urban cities too (68.4%). Rural cities have a measly 5.3% of total rides. 

![Fig7](https://user-images.githubusercontent.com/92544151/152473667-0c99767c-ac49-4663-a8a3-76d3e8c1342c.png)

The disparity is even greater in figure 7 for % of total drivers. Rural cities only account for 2.6% of total drivers. 

In "PyBer_Challenge.ipynb", I was able to create the following summary DataFrame:

<img width="609" alt="Summary_df_challenge" src="https://user-images.githubusercontent.com/92544151/152473988-0dac5c2f-a918-4519-8194-efc46f2c613e.png">

The average fare per ride and per driver was the highest in rural cities, followed by suburban and urban cities respectively. 

Then, down the line, OOP Matplotlib method was used to create a plot of weekly changes on fares for each city type from Jan 2019 to April 2019. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/92544151/152474227-9e4ffa88-86b8-4991-9f72-0ac6e7d2c16d.png)

This shows us that the third week of February 2019 was good for all three city types, with urban and suburban cities having the highest fare of any week during that 4 month period. 

### Summary 

Looking at the results and the summary DataFrame, it can be deduced that the urban cities have lower average fare per ride as cities tend to have a lot more shorter rides. The average fare per driver also makes sense as urban cities have greater population densities and hence a higher number for available drivers. Vice versa for the rural cities. 

A comprehensive look at the analysis leads to the following suggestions for the business:

1) The rural rides are more profitable and it would be beneficial to increase the number of drivers in rural cities, either by diverting some from nearby surburbs or using promotions to attract new rural drivers. 

2) The total rides / total drivers ratios for the three city types are : 

Urban - 0.676 (More drivers than rides)

Suburban - 1.276

Rural - 1.603

Given the fact that suburban and rural rides are more profitable than urban ones, the company should aim to bring the total rides / total drivers ratios closer to 1 for each city type. 

3) Once the total rides / total drivers ratio for urban cities is closer to 1, the company should look into improving the average fare for rides in urban cities.
