# Customer-Service-Satisfaction

## Problem Statement

This dashboard contains files which helps the Customer Service to understand their customers better. It helps them to know if their customers are satisfied with their services through different channels, surveys and other factors. 


## Steps followed

Step 1 : Load the data into Power BI Desktop, dataset is a csv file. 

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

Step 4 : Added new measures for CSAT and CSAT % and also added new column to gain the insights of the data.

Step 5 : In the report view, under the view tab, theme was selected.

Step 7 : Visual filters (Slicers) were added for two fields named "Agent Shift" and "Tenure Bucket"

Step 8 : Three card visuals were added to the canvas, it represents total CSATs , Average CSAT score and AHT in seconds. 

Step 9 : Bar chart was also added to the report design area representing top 5 and bottom 5 agents on basis of CSAT and also to represent trend of CSAT and score with time. 

Step 11: Donut chart used to represent AHT of different Tenure Bucket. 

Step 12: Using New measures, three measures were created which used in report to calculate the total CSAT Score percentage. 

![Screenshot 2025-03-18 131359](https://github.com/user-attachments/assets/fc1d4c9d-281c-429f-a4fd-d6498af9adb8)


## Insights
A one page report was created on Power BI Desktop.

Following inferences can be drawn from the dashboard;

Average CSAT Score = 4.24, CSAT Percentage = 82.5 %, Average AHT in Seconds = 462.4

AHT is maximum for On Job Training agents and minimum for 0-30 days Agent which indicates that agent trying to reduce and maintain their AHT in first 30 days which was their learning phase. 

Maximum CSAT % Score of Agent = 99.13 %

Maximum count of CSAT achevieved = 111

Minimum CSAT % Score of Agent = 36.19 %

Out of all three channels Email, Inbound and Outbound maximum CSAT score % is for Outbound call i.e 85.40 %

FTR day wise is showing normal except day 28th where FTR showing as decreased. 

Regarding CSAT Trend and CSAT % Score trend, day wise, there is increase in the CSAT percentage from 83% to 85%. Highest CSAT % is on day 29th with Score 87.22% 







