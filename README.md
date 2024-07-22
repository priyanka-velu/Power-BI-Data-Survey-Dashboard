# Data Professional Survey Power BI Dashboard

## Project Overview
Performed data cleaning in Power BI
Creating an Data Professional Survey Dashboard using Microsoft Power BI

## Resources
1. Data Source:
- data_professional_survey.xlsx

2. Software:
- Microsoft Power BI
- Microsoft Excel

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


## build dashboard
- add textbox
- effects: blue background

## first
- visualization: card
- unique ID
- field: count of unique ID
- rename: Count of Survey Takers

## age
- visualization: card
- age
- field: average of age
- rename: Average Age of Survey Takers

## job titles vs salary
- viz: stacked bar chart
- go back to table in left column
- change salary data type to decimal type
- do AVG of average salary (title is average)
- legend: job title
- format your visual ICON: general: title: Average Salary By Job Title

## programming language with unique IDs
- stacked column chart
- popularity of programming language for each ID
- seperate by job
- legend: job title
- change charts to see if you like it

## Break down country
- viz: treemap
- value: country (distinct)
- the purpose of this could be to see different salary ranges since other places could have different prices for price of living

## Gauge for happiness with work/life
- value: happiness (average)
- min: happiness (min)
- max: happiness (max)

## Gauge for happiness with salary
- value: happiness (average)
- min: happiness (min)
- max: happiness (max)

## breaking into data difficulty
- value: how easy
- legend: how easy
- visual to change colors

## view
- choose different filters
- customize theme as well for specific colors


  
