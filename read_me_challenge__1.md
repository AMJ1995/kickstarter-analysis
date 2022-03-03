# Kickstarting with Excel

## Overview of Project
-This project was created in order to analyze different Kickstarters for films. Our client named Louise is a filmmaker and wanted us to take a look at different categories of international films, the monetary goals of these films as well as whether or not they were successful in reaching their goals. Additional information about each film is also included in our spreadsheet.

### Purpose
-The purpose of our first Deliverable was to analyze then different outcomes of campaigns to see how many of them failed and how many were successful or canceled based on their launch date. I focused only on the Theater category while retrieving this data. 

-The purpose of our second Deliverable was to analyze the percentage of plays that were failed, successful or canceled based on their monetary goals.

## Analysis and Challenges
-Using several formulas and features of Microsoft Excel I was able to successfully get the data I need. Some challenges were faced, although with enough patience I was able to solve these problems with ease.

### Analysis of Outcomes Based on Launch Date
-I began this analysis by extracting the years from each film so it could go cleanly into my pivot chart. To do this extraction I used the YEAR() function, referencing the following link: https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9?ui=en-us&rs=en-us&ad=us

-Once I successfully pulled the year from each film, I created a pivot chart titled **Theater Outcomes by Launch Date**. Filtering the chart to only show the Theater category, I created a chart that displayed each month and the number of successful, failed and canceled campaigns for each month. We then created a line chart that we titled **Theater Outcomes Based on Launch Date**. This chart makes it easier to see in which months the films tended to be either successful, failed or canceled.

### Analysis of Outcomes Based on Goals
-To begin this analysis, I first created a new sheet that I used to calculate the numbers and percentages of successful, failed and canceled plays. I used a function called COUNTIFS() to help me extract this information from the main sheet. I also used the SUM() function to find the total number of projects once we determined how many fell into the 3 categories of success. A line chart was then created which I titled **Outcomes Based on Goal**. This chart shows us the different outcomes of each play based on what their monetary goals were. 

### Challenges and Difficulties Encountered
-The first challenge I came across was making sure that my pivot chart was set up correctly in our first analysis. The row labels that were supposed to read as months were only reading as years, and then as 4 quarters with the months broken up beneath them. I did some arranging until my chart gave me the information I was looking for. 
-Another challenge I faced was becoming familiar with the COUNTIFS() function. This took me quite some time. Because the function contained so much information in order to successfully execute, I found myself getting confused and leaving important information out of the function. Once I was able to successfully run the function and modify each cell to give me the desired numbers, I became more and more confident.
-When creating the second chart, I had to tweak the information it was displaying on each axis so that it read more easily. This was a minor challenge and I resolved it in little time.

## Results

**Two Conclusions I can make about Theater Outcomes by Launch Date**
1) The chart I created shows that the month of May had the highest number of Successful outcomes by far. May and October were the two months that there seems to be the highest amount of failed campaigns.
2) The line in our chart representing canceled outcomes stayed pretty consistent, with the peak being in the first month that they were launched. 

**Conclusion About Outcomes based on Goals**
- There was nearly an 80% success rate on plays with goals of $4999 and under. 
-100%  of plays with a goal of $45,000 to $50,0000 were failed.
-There wasn't a single play that was canceled based on our data.
-As the goals get larger, the success rate decreases while the number of failed plays increases.

**Dataset Limitations**
-We are only looking at the data from the Theater/Plays category. This data could be much different depending on which category we are looking at.
-We are only looking at 1 year of data. Perhaps in previous years or upcoming years the data could be different.
-This data is representative of one film festival. A film festival with more publicity and popularity (or vice versa) could skew this data.

*Other Possibles Tables/Charts That Could be Created**
-I could have used a few other types of charts instead of line charts for my data, although a line chart seems to be the best for the data we are using since we are tracking data that is changing over time. Bar charts, for instance, are useful when we want to visualize data from a snapshot of time. 
