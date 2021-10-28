# An Analysis of Kickstarter Campaigns

## Overview of Project

### Purpose

The purpose of this project is to provide Louise with an analysis and insights into the outcomes of past Kickstarter campaigns so that she may make more informed decisions about how to maximize the probability of success for her own campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Dates

An analysis was performed based on the date that each campaign belonging to the "theater" parent category was launched. The potential outcomes that were considered for this analysis were successful, failed and canceled. These outcomes were compaired to the month that the campaign was launched in to provide the following result.

![Theater Outcomes vs Launch](./assets/images/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

An analysis was performed based on the initial goal amount of all the campaigns belonging to the "plays" subcategory. The potential outcomes that were considered for this analysis were successful, failed and canceled. The amounts of the goals were subdivided into 12 buckets for ease of analysis, and the percentage of the respective bucket for each outcome was calculated with the following result. 

![Outcomes vs Goals](./assets/images/Outcomes_vs_Goals.png) 

### Challenges and Difficulties Encountered

A difficulty was encountered when performing the analysis of outcomes based on goals. When the number of successful campaigns was calculated for each bucket (column B) a validation check of the formulas was made. This was done by comparing the sum of the successful results in column B against the calculation of all successful plays with goals greater than 0. The results of these two figures should be the same, however in this case the sum of the successful results was 1 less. This discrepancy was resolved by debugging the formulas used in column B to calulate the number of successful plays. It was discovered that an = was missing from a single formula resulting in one result being missed. With this corrected the validation check matched and the analysis could proceed.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
