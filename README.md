# Data Professional Survey Power BI Dashboard

## Project Overview
This project involves performing cleaning the data professional survey in Microsoft Power BI by deleting unwanted columns and cleaning wanted data, such as Job Title, programing language, yearly salary, and more. Then, we visualized the data with an interactive Microsoft Power BI dashboard displaying meaningful insights from the data professional survey.

## Data Professional Survey Dashboard
![Screenshot 2024-07-22 152758](https://github.com/user-attachments/assets/6bd6abe4-8f72-4e3d-9b64-e8dcb7fdffc8)
[Data Professional Survey Dashboard](https://github.com/user-attachments/files/16340274/Data.Professional.Survey.Dashboard.pdf) 

## Resources
1. Data Source:
- [data_professional_survey.xlsx](data_professional_survey.xlsx)

2. Software:
- Microsoft Power BI
- Microsoft Excel

# 1. Data cleaning in Microsoft Power BI

## Open data in Excel
- data: add filters to all

## Open Power BI 
- import from excel
- open excel
- check excel
- transform data

## What do i get out of this data?
- get rid of unrelated columns

## need job title, need to clean it with the other option
- split column by delimiter
- other had (
- so custom: (
- left-most
- seperated by column
- remove that column

## need programming language
- get rid of other languages

- split column by delimiter
- other had :
- so custom: :
- left-most
- seperated by column
- remove that column

## salary yearly
need to break up number and get the average
- break up with low end, high end, and another column to find average

- duplicate column (at the end)
- SPLIT COLUMN: digit to non-digit
- creates first digit to number
- second column: right click: replace values: k
- repeat above with -
- to only get the numbers
- replace + with 225 so average is 225

- add column tab: custom column
- CHANGE VARIBALES TO WHOLE NUMBER in columns
- average salary
- = (low + high) / 2
- now you have average salary column!

- break out countries and industry


# 2. Visualizing data in Microsoft Power BI
- add textbox
- effects: blue background

## count of survey takers and average age
- visualization: card
- unique ID
- field: count of unique ID
- rename: Count of Survey Takers
  
- visualization: card
- age
- field: average of age
- rename: Average Age of Survey Takers
![Screenshot 2024-07-22 152435](https://github.com/user-attachments/assets/2655833c-2669-4277-8401-ae908dcfa8cf)

## job titles vs salary
- viz: stacked bar chart
- go back to table in left column
- change salary data type to decimal type
- do AVG of average salary (title is average)
- legend: job title
- format your visual ICON: general: title: Average Salary By Job Title
![Screenshot 2024-07-22 152412](https://github.com/user-attachments/assets/22c7a5ad-a49b-4afa-8322-8e149da9005b)

## programming language with unique IDs
- stacked column chart
- popularity of programming language for each ID
- seperate by job
- legend: job title
- change charts to see if you like it
![Screenshot 2024-07-22 152348](https://github.com/user-attachments/assets/f8ca4141-d3d1-4998-a42d-8f5c5b943dbd)

## Break down country
- viz: treemap
- value: country (distinct)
- the purpose of this could be to see different salary ranges since other places could have different prices for price of living
![Screenshot 2024-07-22 152314](https://github.com/user-attachments/assets/2d8382b2-1958-4d68-a02a-efb3e6cc95ed)

## Gauge for happiness with work/life
- value: happiness (average)
- min: happiness (min)
- max: happiness (max)
![Screenshot 2024-07-22 152531](https://github.com/user-attachments/assets/54874ebf-5a2c-4cc7-bd94-1a6b7cc27dbd)

## Gauge for happiness with salary
- value: happiness (average)
- min: happiness (min)
- max: happiness (max)
![Screenshot 2024-07-22 152552](https://github.com/user-attachments/assets/08233b2b-fef4-401a-8a46-d8881d7e405a)

## breaking into data difficulty
- value: how easy
- legend: how easy
- visual to change colors
![Screenshot 2024-07-22 152454](https://github.com/user-attachments/assets/83cf0367-51c1-47fa-a505-cb3ed5ce80e2)

## view
- choose different filters
- customize theme as well for specific colors


  
