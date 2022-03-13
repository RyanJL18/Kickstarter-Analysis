# 2222222)Analysis and Challenges
The overview of the analysis is well described with screenshots (2 pt).
Challenges or difficulties that were encountered, and how they were overcome, are well explained. If there were no difficulties, describe any possible challenges or difficulties that could be encountered (2 pt).
# 3333333)Results
Two conclusions are made about the Theater Outcomes by Launch Date (2 pt).
One conclusion is made about the Outcomes based on Goals (2 pt).
There is a summary of the limitations of the dataset, and there is a recommendation for additional tables or graphs (2 pt).
# Analysis of Kickstarter Campaigns in Entertainment
---
# Background 
With the data provided, we were able to analyze the results of kickstarter campaigns for entertaiment options such as film, games, technology, theater, etc. In this analysis we compared start dates, locations, goal amounts, pledged amounts, and a multitude other catagories to assist Louise in finding the best way to successfully fund her play, *Fever*, after initially coming close to her fundraising goal in a short amount of time.

# Process
In this analysis I worked to find new data values for the main kickstarter data sheet and worked to add aditional sheets to better help clean and evaluate the data.

---
Some of the first additional data that was calculated was finding the average donation and creating a new column. Using the formulas seen below: fig. 1 was used to calculate the average donation, and fig2 was used to apply the date created conversion to the initially offered Epoch Time in Cloumns I & J. 
![Formula Average.png](https://github.com/RyanJL18/Kickstarter-Analysis/blob/main/Formula%20Average.png)

Fig1 & Fig2

With these data cleaning steps we could evaluate the provided data better, but the overload of values present still offered a challenge in assessing the information that we found most important. From here we broke down the catagories into a second column labeled subcategories, which allowed us to better filter the information for Lousie's play. With these new parameters we could evaluate broad data like the number of successful, failed, and cancelled kickstarters based on the parent catagories, as well as find more specific information like the Outcomes Based on Launch Date (data that will be discussed in my conclusion). Below are some of the different graphs of information gathered from this step of the process.
Fig3
Fig4
Fig5

# Conclusion

Two Conclusions Based on Launch Date:
- The best time to launch a kickstarter for a play would be early summer.
- The most kickstarters for plays were launched between May and August, depicted by a large spike in the number of successful campaigns while the number of failed campaigns showed a slight increase, but often remained consistent.
Fig6
Conclusion Based on Goal:
- In general, the larger the goal was, the harder it was to successfully fund. The data shows a general increase in percentage failed as the goals grew, but there is a slight increase in percentage successful as we approced the 35000 to 44999 data range. However, there were much fewer total projects as the goal amount increased, leaving me to believe this change does not offer much contradiction for the previous assesment.
Fig7
The limitations that most affect both of these graphs, is that there is a much smaller amount of total projects as the goal amount was growing. While this lets us know it is much less common for this data to exist, we cannot make any firm conclusions on the later values without more data to pull. I would suggest more data for these values and potentially another column or catagory with information on how the amount pledged was collected (i.e. what fundraising tactics were used to reach their goal), to give us a better idea of what else Louise could attempt to receive the remaining amount for her goal. With the inclusion of a "Fundraising Tactic" column, a bar graph with the tactics as the x-axis and the amount raised as the y-axis could offer further insight on this topic.
