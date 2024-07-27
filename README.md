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

# Data Cleaning Steps

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


# Data Visualization Steps
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

//

# Data Professional Survey Power BI Dashboard

## Project Overview
This project involves cleaning and visualizing the data from a data professional survey using Microsoft Power BI. The steps include deleting unwanted columns and cleaning essential data such as job titles, programming languages, and yearly salaries. The cleaned data is then visualized with an interactive Microsoft Power BI dashboard to display meaningful insights from the survey.

## Data Professional Survey Dashboard
![Screenshot 2024-07-22 152758](https://github.com/user-attachments/assets/6bd6abe4-8f72-4e3d-9b64-e8dcb7fdffc8)
[Data Professional Survey Dashboard](https://github.com/user-attachments/files/16340274/Data.Professional.Survey.Dashboard.pdf)

## Resources
1. **Data Source**:
   - [data_professional_survey.xlsx](data_professional_survey.xlsx)

2. **Software**:
   - Microsoft Power BI
   - Microsoft Excel

## Data Cleaning Steps

### 1. Open Data in Excel
- Add filters to all columns for easier data manipulation.

### 2. Open Power BI
- Import data from the Excel file.
- Open the Excel file in Power BI.
- Check and transform the data as needed.

### 3. Remove Unrelated Columns
- Identify and delete columns that are not relevant to the analysis.

### 4. Clean Job Titles
- Split the column by delimiter (e.g., parentheses) to isolate and clean the job titles.
- Remove the original column after cleaning.

### 5. Clean Programming Languages
- Split the column by delimiter (e.g., colons) to isolate and clean the programming languages.
- Remove the original column after cleaning.

### 6. Clean Yearly Salary
- Break down the salary ranges into low, high, and average values.
- Split the column by digits and non-digits.
- Replace values (e.g., "k") to standardize the salary format.
- Create a new column for the average salary using a custom column formula.

### 7. Break Out Countries and Industries
- Split and clean the country and industry fields for better analysis.

## Data Visualization Steps

### 1. Add Textbox
- Add a textbox with a blue background for project details or notes.

### 2. Count of Survey Takers and Average Age
- Use the card visualization to display the count of unique survey takers and the average age.
  ![Screenshot 2024-07-22 152435](https://github.com/user-attachments/assets/2655833c-2669-4277-8401-ae908dcfa8cf)

### 3. Job Titles vs. Salary
- Use a stacked bar chart to show the average salary by job title.
- Ensure salary data type is set to decimal.
- Set the title to "Average Salary By Job Title."
  ![Screenshot 2024-07-22 152412](https://github.com/user-attachments/assets/22c7a5ad-a49b-4afa-8322-8e149da9005b)

### 4. Programming Language Popularity
- Use a stacked column chart to display the popularity of programming languages, separated by job title.
  ![Screenshot 2024-07-22 152348](https://github.com/user-attachments/assets/f8ca4141-d3d1-4998-a42d-8f5c5b943dbd)

### 5. Country Breakdown
- Use a treemap visualization to show the distribution of survey respondents by country, highlighting different salary ranges and cost of living.
  ![Screenshot 2024-07-22 152314](https://github.com/user-attachments/assets/2d8382b2-1958-4d68-a02a-efb3e6cc95ed)

### 6. Work/Life Happiness Gauge
- Use a gauge visualization to display average happiness with work/life balance.
- Set min and max values based on the happiness scale.
  ![Screenshot 2024-07-22 152531](https://github.com/user-attachments/assets/54874ebf-5a2c-4cc7-bd94-1a6b7cc27dbd)

### 7. Salary Happiness Gauge
- Use a gauge visualization to display average happiness with salary.
- Set min and max values based on the happiness scale.
  ![Screenshot 2024-07-22 152552](https://github.com/user-attachments/assets/08233b2b-fef4-401a-8a46-d8881d7e405a)

### 8. Data Difficulty Breakdown
- Use a visualization to show the distribution of responses on data difficulty.
- Customize colors for better clarity and visual appeal.
  ![Screenshot 2024-07-22 152454](https://github.com/user-attachments/assets/83cf0367-51c1-47fa-a505-cb3ed5ce80e2)

### 9. Custom Filters and Themes
- Add interactive filters and customize the dashboard theme for specific colors and styles.

## Conclusion
By cleaning and visualizing the data professional survey in Power BI, we gain valuable insights into job titles, programming languages, salaries, and more. The interactive dashboard allows for easy exploration and analysis of the data, providing a comprehensive overview of the survey results.

//trial 3


# Data Professional Survey Power BI Dashboard

## Project Overview
This project aims to transform and visualize the data from a survey of data professionals, using Microsoft Power BI. The project includes thorough data cleaning and preprocessing steps to ensure data quality, followed by the creation of an interactive dashboard that provides key insights into job titles, programming languages, salaries, and other relevant factors. The end goal is to present the survey findings in a clear, concise, and visually appealing manner that can inform decision-making based on data-driven insights.

## Data Professional Survey Dashboard
![Screenshot 2024-07-22 152758](https://github.com/user-attachments/assets/6bd6abe4-8f72-4e3d-9b64-e8dcb7fdffc8)
[Data Professional Survey Dashboard](https://github.com/user-attachments/files/16340274/Data.Professional.Survey.Dashboard.pdf)

## Resources
1. **Data Source**:
   - [data_professional_survey.xlsx](data_professional_survey.xlsx)

2. **Software**:
   - Microsoft Power BI
   - Microsoft Excel

## Data Cleaning and Transformation

### 1. Data Preparation in Microsoft Excel
- Applied filters to all columns to facilitate data review and cleaning.
- Reviewed all columns to gauge what information to highlight (ie. programming languages, occupations)

### 2. Data Import and Transformation in Power BI
- Imported data from the Excel file into Power BI.
- Verified data integrity and performed necessary transformations.

### 3. Removing Unnecessary Columns
- Identified and removed columns that do not contribute to the analysis.

### 4. Standardizing Job Titles
- Cleaned the job title data by splitting and reformatting entries, ensuring consistency.

### 5. Programming Languages Cleanup
- Processed the programming languages column by isolating individual languages and removing extraneous data.

### 6. Salary Data Normalization
- Created custom columns to calculate average salaries by splitting the salary ranges into low and high values.
- Replaced text indicators (e.g., "k" for thousand) with numerical values to ensure consistency and accuracy.
- Calculated the average salary for each entry to facilitate analysis.

### 7. Extraction of Country Information
- Split and cleaned the country and industry fields to ensure accurate representation and better data analysis.

## Data Visualization

### 1. Count of Survey Takers and Average Age
- **Count of Survey Takers**: Displayed the total number of unique survey respondents using a card visualization.
- **Average Age**: Showed the average age of survey takers using a card visualization.
  ![Screenshot 2024-07-22 152435](https://github.com/user-attachments/assets/2655833c-2669-4277-8401-ae908dcfa8cf)

### 2. Job Titles vs. Salary
- Utilized a stacked bar chart to compare average salaries across different job titles.
- Ensured the salary data was in decimal format for precise calculations.
- Added a descriptive title, "Average Salary By Job Title."
  ![Screenshot 2024-07-22 152412](https://github.com/user-attachments/assets/22c7a5ad-a49b-4afa-8322-8e149da9005b)

### 3. Programming Language Popularity
- Used a stacked column chart to visualize the popularity of different programming languages, categorized by job title.
  ![Screenshot 2024-07-22 152348](https://github.com/user-attachments/assets/f8ca4141-d3d1-4998-a42d-8f5c5b943dbd)

### 4. Country Analysis
- Implemented a treemap visualization to display the distribution of survey respondents by country.
- This visualization highlights regional differences in salary ranges and cost of living.
  ![Screenshot 2024-07-22 152314](https://github.com/user-attachments/assets/2d8382b2-1958-4d68-a02a-efb3e6cc95ed)

### 5. Work/Life Happiness
- Created a gauge chart to display the average level of happiness with work/life balance.
- Set minimum and maximum values to reflect the survey's happiness scale.
  ![Screenshot 2024-07-22 152531](https://github.com/user-attachments/assets/54874ebf-5a2c-4cc7-bd94-1a6b7cc27dbd)

### 6. Salary Satisfaction
- Developed a gauge chart to represent average happiness with salary.
- Configured the gauge with appropriate minimum and maximum values.
  ![Screenshot 2024-07-22 152552](https://github.com/user-attachments/assets/08233b2b-fef4-401a-8a46-d8881d7e405a)

### 7. Data Difficulty Insights
- Used a visual to show how survey respondents rated the difficulty of data-related tasks.
- Applied color coding to enhance readability and interpretation.
  ![Screenshot 2024-07-22 152454](https://github.com/user-attachments/assets/83cf0367-51c1-47fa-a505-cb3ed5ce80e2)

### 8. Interactive Filters and Custom Themes
- Added interactive filters to enable users to explore different aspects of the data.
- Customized the dashboard theme to align with specific color schemes and visual preferences.
