# An Analysis of Kickstarter Campaigns
### Objective
A comprehensive analysis of kickstarter data and trends,to infer the factors that contribute to a successful launch. Through analysis the contributing factors for success as well as those leading to failure were uncovered and visulaized. 

### Succesful Campaigns

1. The most successful category as it pertains to kickstarters was the Theater Parent Category)

![Parent_Category_Outcomes](https://github.com/Jonjos95/Kickstarter-analysis/blob/e60606f27c1898edbaac3357abbe2afe160f9215/Parent%20Category%20Outcomes.png)

Further drilling down into the data we are able to see that Plays highly successful with more than half of all plays meeting their initial goal. This is great news and leads us to dive a bit further into the driving factors for such success and oppurtunities to avoid failure.
![Play Outcomes](https://github.com/Jonjos95/Kickstarter-analysis/blob/b59c451dae31bd9a40574dfcea6b05799eb42829/Play%20Outcomes.png)

### Launching for Success
 Findings were clear that trends were heavily influenced by not only the timing of the campaign but also the length of the campaign. We agregated the data and created a pivot that would total the values ouf campaign outcomes by the launch date and if there was success, failure, cancellation or if the kickstarter was still live. The trend highlighted that of all the Theatre campaigns The best time to launch was in June, the rate of success is at its peak and subsequently drops significantly thereafter. Culminating with the lowest point of success falling in December.
 ![Theater Outcomes](https://github.com/Jonjos95/Kickstarter-analysis/blob/b34e59ccb205a4fe5897a8cb184cdc72d87403ad/Theater%20Outcomes.png)

### Conclusion
Ultimately the data showed that of all the categories quantitativily assessed Theater was the most successful parent category. Futhermore plays were highly successgul in meeting their campaign goals, the key contributing factors to this success were predominately timing of year as well as the size of the goal. Per statiscal analysis and measuring the central tendancies we found that many of the failed campaigns had goals extraordinaly larger than their counterparts. To the point of skewing the dataset to the right of the mean (average). This highlighted a key component in the model that suggests a large goal may have not been attainable considering the average donations were much smaller than the campaigns seeking less funds. To conclude, the analysis suggests that optimal success would be reached with a goal of $4,000.00-$5,000.00 and a kickstarter launch in early June.


# Kickstarter Challenge
### Purpose
This weekly challenge provided an opportunity to build on the skills learned in the module.
1.By combining the analytical skills learned throughout the module it allowed for a challenging assessment of what was retained and gave actionable insghts into the data set.

Deliverable 1: Outcomes Based on Launch Date Chart
Deliverable 2: Outcomes Based on Goals Chart

### Analysis 

The methods used in this challenge were to start by adding the year column using the year formula whihc would would allow us to pivot for that field moving forward. With this new column we were able to then creat a table (Pivot chart) that would be filtered by year. To better visualize the data we created a line graph summarizing the launch dates. This further demonstrated the trend that successful campaigns launched typically in late May to early June. 
![Theater_Outcomes_vs_Launch](https://github.com/Jonjos95/Kickstarter-analysis/blob/f02efa527cfbca721e0334567ecf2ffdd5c29feb/Theater_Outcomes_vs_Launch.png)

### Analysis Based on Launch Date
*Ultimately Launches in the beginning of summer are the most successful and there for drive the metric to indicate that to succeed one major key is to launch in June.

The Next step was to create a table with the COUNTIFS formula. This would allow us to create multiple criteria to pull data from different sheets and quatify the results respectively. This was a great way to test the ability to refactor and grasp a concept that wasnt covered in the lecture. I found this aspect to be the most difficult part becausse of the length of the formula and nesting so many criterias ( IT TOOK ME A WHILE). But the results were very eye opening Plays had Zero cancellation and the trend seemed to support that the larger the goal the liklier the campaign would fail. The more measured goals had a much higher percentage for success.
![Outcomes_vs_Goals](https://github.com/Jonjos95/Kickstarter-analysis/blob/3d3c9bb0b2af08c1c8f3cad2cc62444a29844a10/Outcomes_vs_Goals.png)

### Analysis Based on Goals
*The size of the goal is an indicator as to the percentage rate for success. The more measured the goal the higher the possibility is to achieve it. The tendency in the data revealed that failure was at a higher percentage for the large goals.

## Results
The major findings of this analysis was that the contributing factors for success and failure were largely due to timing of the launch and the size of the goal although there is no correlation between the two, both of these dimensions influence the percent of success and failure. For the highest rate of success the launch should be timed in June and the Goal should be around $5000 for higher chances of success. Although there is a lot of insights here, there is no possiblity to model the contributions of campaigning to certains age groups or demographics, this is unfortunate because you would be able to better target certain audiences that tend to have greater appeal towards a certain category. Furthermore although line graphs and bar graphs were used primarily to visulaize this data a combo-chart or stacked bar graph could have also been used. 
