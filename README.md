# Kickstarting with Excel

## Overview of Project
This purpose of this project was to analyze the success rate of Louise's fundraising and observing the what factors contribute to the success or the failure. Louise is depending on the results of this data in order to figure out the best method to promote her new play. Some of the deciding factors would be the goal set for the money that needs to be raised, when to launch the campaign, and which country she should launch her campaign.
### Purpose
When first starting the analysis of the data provided by Louise, the first challenge was to interpret the dates in which Louise's past campaigns have been. Below is a picture that shows the format of the dates in the columns labeled "deadline and "launched".Date Formatting in deadline and launch columns.

New Columns were then made in order to use the Year (Links to an external site.) function to have a readable date.
#### Formatting Columns
After the date was in a format that could be properly interpreted. The categories and subcategories column was split in two using the Text to Column (Links to an external site.) feature. This gave us two columns one holding the parent categories and the other holding the subcategories. Which can be seen Below.Display of Category and Sub Category column split into separate columns.
#### Visualization
Now that the data was formatted in a more user friendly interpretation, the real work could begin. A pivot chart was then created that showed the success, failure, and cancellation of past campaigns by the month they were launched. From the pivot table a line chart was created that marked the highs and lows for each success, failure, and cancellation based on the month.

Many new worksheets and graphs were created in order to bring attention to particular details of how past campaigns performed. This even included using traditional statistics. Eventually a new worksheet was created that would allow me to visualize what percentage of campaigns for plays had been successful, failed, or cancelled. In order to get such a particular set of data from such a wide array of information, I had to rely on the Countifs (Links to an external site.) formula in Excel. Below is a graphic of the resulting data.
## Analysis and Challenges




### Analysis of Outcomes Based on Launch Date.
### Analysis of Outcomes Based on Goals
The end result allows for Louise to see that generally there is a higher success rate for campaigns that raise less than $25,000. However, there is still a high likelihood of having a successful campaign if the amount that needs to be raised is between $35,000 and $45,000.
### Challenges and Difficulties Encountered
The most difficult part of this challenge for me was using the countifs function when there is a range that needs to be included. For example when using the countifs to find values between 1000 and 5000 I was initially using ">=1000, <=4999". I was not yielding any results from this, so I eventually realized that I need to format my range to read ">=1000, < 5000". This slight change in my formula helped me find the results I was looking for.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The two outcomes I observed from the Outcomes Based on Launch Date tab was that for Louise to have the most chance of having a successful campaign she should start her campaign in May. On the other side of that, launching her campaign in December would give her the least likely chance of having a successful campaign.
- What can you conclude about the Outcomes based on Goals?
When looking at the Outcomes Based on Goals it is fairly obvious to come to the conclusion that the lower set goal amounts have the highest success rate. However, what I noticed the most was that measuring the percentage of cancellations was not relevant to tracking the success rate of the play campaigns.
- What are some limitations of this dataset?
One of the limitations of this data set is the wide variety of data initially provided. There are sets of data that are not useful in measuring any of the desired outcomes. It would be more efficient to work with information that only has to deal with desired end results.
- What are some other possible tables and/or graphs that we could create?
One of the other graphs that could be created would be showing how well certain subcategories did in a particular month compared to the parent category at whole.
