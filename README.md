# Kickstarting with Excel 
Kickstarter Challenge #1 Data Analysis
## Overview of Project 
To assist Louise with complialing various data to show her the outcomes of different campaigns in connection regarding their launch dates and funding goals. 
### Purpose
The purpose of this analysis was to provide Louise specific data to assist them with planning their kickstarter campaign.
## Analysis and Challenges
In the next few paragraphs I will be detailing my process on my analysis and the challenges I encounted while going through the project. 
### Analysis of Outcomes Based on Launch Date
I performed my analysis by first using the YEAR () function to extract the year from the Date Created Conversion column. The year would then be added with the Parent Category to be the filters for the pivot table I created. I then filtered the rest of the pivot table to show the Theatre outcomes by launch date. I also added a line chart to further show my findings. I did not face any challenges in my first deliverable, I could see however, if you are not using the correct filters when creating a pivot chart, that could show inacurate data. 

### Analysis of Outcomes Based on Goals
Next,  I used the COUNTIFS() function to show Louise the number successful, failed and canceled plays. I set up goal amounts and used those to determine my function. For example, to find the number of succesful plays based on the goal amount of 1000 to 4999 I used the formula =COUNTIFS(Kickstarter!$D:$D, ">=1000", Kickstarter!$D:$D, "<=4999", Kickstarter!$F:$F, "successful", Kickstarter!$R:$R, "plays"). Using the data I collected from the plays I then was able to calculate the sum of all the outcomes and goal amounts. I then took the outcomes/total projects to find the percentages. 
### Challenges and Difficulties Encountered
Lastly, I created a corresponding line chart to further prove my findings. I did face a few challenges while completing the analysis, I had trouble using the COUNTIFS function in excel, each time I would attempt the COUNTIFS formula all of my data would come back as 0. I was able to correct this issue by watching back on the module and I realized that I was not using the correct columms. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Two conclusions I can draw about the outcomes based on launch date are that 
1) May and June were the most successful months for the kickstarter campaigns.
2) Most of the launch dates happened in the summer months.

- What can you conclude about the Outcomes based on Goals?

The highest success rate was when the goal amount was less than 5000. The majority of the campaigns had a low goal.

- What are some limitations of this dataset?

The data that I filtered only showed results for plays which does not give an overview of all kickstart campaigns. 
- What are some other possible tables and/or graphs that we could create?

You could create a table based on the percentage of successful and failed campaigns correlating to launch date. 