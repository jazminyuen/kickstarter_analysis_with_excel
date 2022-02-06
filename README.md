# Kickstarter Analysis with Excel

## Overview of Project
This project involves the analysis of kickstarter data in order to reveal trends to help my client, Louise, determine her kickstarter plan for her play.

[My GitHub](https://github.com/jazminyuen/kickstarter_analysis_with_excel.git)

### Purpose
The goal is to analyze how two variables affect campaign outcomes to help Louise make an informed decision about her play campaign's launch date and goal. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In this part of the analysis, I organized the number of successful, failed, and canceled theater campaigns outcomes by the month that they were launched. I created a line chart from this information to show the trends month by month.

![chart 1](/Users/jaz/Desktop/module_1_kickstarter/resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

For this part of the analysis, I added the number of successful, failed, and canceled play campaigns to produce the total numbers for each goal range. I then calculated the percentage of each outcome organized by goal range in this line chart.

![chart 2](/Users/jaz/Desktop/module_1_kickstarter/resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

I encountered a challenge during my 'Outcomes Based on Goals' analysis. While writing the function for the number of each outcome based on goal range, I had to be sure to list the arguments in order. After research and trial and error, I wrote the "greater than or equal to" criteria, then separately at the end of the function, I wrote the "less than" function. I also encountered some difficulty when deciding how to write these criteria. In my table, I listed the goal column as bookended ranges. With a data set that doesn't have only integers, this would pose a problem. For example, it would exclude values between 4999 and 5000. So I decided to keep it simple and in my functions write "less than" to state upper boundary of the range.

## Results

###  What are two conclusions you can draw about the Outcomes based on Launch Date?

 The largest instance of growth in this chart is shown from April to May. While the number of failed outcomes also has a spike, the jump in the number of successful outcomes is much more significant. One can conclude that the month of May would be a good recommendation for launching a theater production. The chart shows that it is the peak time for successful theater outcomes. Another takeaway from this is shown in the uptick from September to October. While both outcomes increased, the number of failed outcomes increased at a higher rate compared to the number of successful outcomes. So one can conclude that even though the autumn season brought a new surge of campaigns, theater productions launched at that time were not as successful as those launched in the summer months.

### What can you conclude about the Outcomes based on Goals?

Since the lines showing percentage successful versus percentage failed are inverse, it is clear which goal ranges Louise should consider for her play campaign and which goal ranges should most likely be avoided.

### What are some limitations of this dataset?

The variables in either chart don't match. The analysis of 'Outcomes Based on Launch Date' covers the wider umbrella of all theater productions while the analysis of 'Outcomes Based on Goals' hones in on the subcategory of plays only. Because of this discrepancy, we cannot compare the two directly. If I did filter by plays only in the launch date study, we would see that all plays in this data set had a successful outcome. So a limitation of this dataset is that there is not enough data on plays that have a range of outcomes. 

 More broadly, I have not considered the present outliers in this data set. I have included all of the data for the goal category, when it may be helpful to disregard extreme goals and observe outcome trends without those.

### What are some other possible tables and/or graphs that we could create?

The number of successful and failed theater outcomes displayed in the 'Outcomes Based on Launch Date Chart' appear to have some correlation as the overall shape of the line charts look similar. It would be helpful to create a pie chart or bar chart to visualize a ratio relationship between these outcomes per launch month rather than just their overall trends over time.

To widen the picture, I could add another chart that shows another variable. A bar chart showing outcomes based on active campaign length (the time between launch date and deadline) will give Louise another piece to consider when planning her kickstarter.
