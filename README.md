# Kickstarting with Excel

## Overview of Project

### Purpose: The purpose of the project is to perform data analysis on several thousand crowdfunding projects to determine factors and uncover any hidden trends to make the fundraising campaign successful.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The campaigns that are launched from April to June are successful and peak in May.The campaigns that are launched during winter months have higher chance of failing. The below chart shows the theater campaign have higher chance of being successful if they are launched during summer.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/84524153/121760578-7f84a900-caf9-11eb-9728-efcf2f9d3c0d.png)

### Analysis of Outcomes Based on Goals

The number of successful campaigns increase if the goal amount is less. The campaign will be successful if it has reasonable goal of less than $10,000.We can see in the chart below that as the goal amount increases there is less chance of campaign being successful.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/84524153/121760603-9d520e00-caf9-11eb-88e1-90a07edcc515.png)

### Challenges and Difficulties Encountered

The challenge was to find average donations for each campaign, so we had to divide the pledged amount by number of backers, but since some campaigns did not have any backers, there was an error which was fixed by using IFERROR formula, which returns value such as ‘0’ if the main formula attempts to divide by 0.
-Reference provided to the excel sheet through the following link.
[Kickstarter_Challenge.xlsx](https://github.com/Ayesha-da/kickstarter-analysis/files/6641451/Kickstarter_Challenge.xlsx)

## Results 

- What are two conclusions you can draw about the Outcomes based on Launch Date?

   *If the campaign is launched between April and June, it will have higher success rate.
   *There is higher chance of campaign failing if launched from October to December.

- What can you conclude about the Outcomes based on Goals?

   *Low-cost campaigns have higher success rate.

- What are some limitations of this dataset?

  *The data does not specifically show how and why certain campaigns are successful even though they have larger goal amount.                    
  
  *The data is missing crucial information such as recent trends.

- What are some other possible tables and/or graphs that we could create?

  *We can create a chart showing percentage of successful and failed campaign based on country and subcategories to understand if people in certain regions shows more interest towards particular subcategory.
