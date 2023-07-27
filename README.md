# Analysis of Kickstarter Campaigns in Entertainment
---
# Background 
With the data provided, we were able to analyze the results of Kickstarter campaigns for entertainment options such as film, games, technology, theater, etc. In this analysis we compared start dates, locations, goal amounts, pledged amounts, and a multitude other categories to assist Louise in finding the best way to successfully fund her play, *Fever*, after initially coming close to her fundraising goal in a short amount of time.

# Process
In this analysis I worked to find new data values for the main Kickstarter data sheet and worked to add additional sheets to better help clean and evaluate the data.

---
Some of the first additional data that was calculated was finding the average donation and creating a new column. Using the formulas seen below: fig. 1 was used to calculate the average donation, and fig2 was used to apply the date created conversion to the initially offered Epoch Time in Cloumns I & J. 

---
**Fig1:**
![Formula Average.png](https://github.com/RyanJL18/Kickstarter-Analysis/blob/main/Resources/Formula%20Average.png)
**Fig2:**
![Formula Epoch Time.png](https://github.com/RyanJL18/Kickstarter-Analysis/blob/main/Resources/Formula%20Epoch%20Time.png)

---
With these data cleaning steps, we could evaluate the provided data better, but the overload of values present still offered a challenge in assessing the information that we found most important. From here we broke down the categories into a second column labeled subcategories, which allowed us to better filter the information for Louise's play. With these new parameters we could evaluate broad data like the number of successful, failed, and cancelled Kickstarters based on the parent categories, as well as find more specific information like the Outcomes Based on Launch Date (data that will be discussed in my conclusion). Below are some of the different graphs of information gathered from this step of the process.

---
**Fig3:**
![Parent Category Outcomes.png](https://github.com/RyanJL18/Kickstarter-Analysis/blob/main/Resources/Parent%20Catagory.png)
In this chart, you can see overwhelmingly that hitting goals for categories such as Film & Video, Music, and Theater were more consistently successful as opposed to categories such as Food, Games, and Publishing.

---
**Fig4:**
![Subcategory Chart.png](https://github.com/RyanJL18/Kickstarter-Analysis/blob/main/Resources/Subcatagory%20Chart.png)
From this chart, you can see that we are presented with the most information on the subcategory of plays, offering a lot of good information for comparison with Louise's fundraising goal.


---

One challenge that I faced when working with this data set, was something that I ran into because of the size of the formulas for one of the later data sets. In the chart created for *Outcomes Based on Goals* the data set being pulled to calculate the outcomes was actually being pulled from the "pledged amount" category. This gave me very skewed and incorrect data based on the information I was trying to present. With this challenge I was forced to go through the formula line and compare based on the original chart, at which point I then had to redo all the formulas to reflect column *D* as opposed to column *E*. Working in Excel with long lines of formulas can offer as a challenge just based on typing or input error, so focusing and making sure the formula is correct before copying it into all cells can help save some time in creation of a chart for the data set.
# Conclusion

Two Conclusions Based on Launch Date:
- The best time to launch a Kickstarter for a play would be early summer.
- The most Kickstarters for plays were launched between May and August, depicted by a large spike in the number of successful campaigns while the number of failed campaigns showed a slight increase, but often remained consistent.
---
**Fig6:**
![Outcomes Based on Launch Date.png](https://github.com/RyanJL18/Kickstarter-Analysis/blob/main/Resources/Outcomes%20Based%20on%20Launch%20Date.png)

---
Conclusion Based on Goal:
- In general, the larger the goal was, the harder it was to successfully fund. The data shows a general increase in percentage failed as the goals grew, but there is a slight increase in percentage successful as we approaced the 35000 to 44999 data range. However, there were much fewer total projects as the goal amount increased, leaving me to believe this change does not offer much contradiction for the previous assessment.

---
**Fig7:**
![Outcomed Based on Goals](https://github.com/RyanJL18/Kickstarter-Analysis/blob/main/Resources/Outcomes%20Based%20on%20Goals.png)

---
The limitations that most affect both of these graphs, is that there is a much smaller amount of total projects as the goal amount was growing. While this lets us know it is much less common for this data to exist, we cannot make any firm conclusions on the later values without more data to pull. I would suggest more data for these values and potentially another column or category with information on how the amount pledged was collected (i.e. what fundraising tactics were used to reach their goal), to give us a better idea of what else Louise could attempt to receive the remaining amount for her goal. With the inclusion of a "Fundraising Tactic" column, a bar graph with the tactics as the x-axis and the amount raised as the y-axis could offer further insight on this topic.
