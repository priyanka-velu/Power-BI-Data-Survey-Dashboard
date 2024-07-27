# Data Professional Survey Dashboard

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

## Data Cleaning Steps

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

## Data Visualization and Analysis

### 1. Count of Survey Takers and Average Age
- **Methods**:
   - Displayed the total number of unique survey respondents using a card visualization.
   -Showed the average age of survey takers using a card visualization.
- **Question: How many data professionals participated in the survey, and what is their average age?**
  - **Answer**: The **Count of Survey Takers** card displays the total number of unique respondents, giving a sense of the survey's reach and sample size. The **Average Age** card shows the mean age of the participants, which can help businesses understand the demographic profile of their data workforce. This information is useful for tailoring recruitment strategies and professional development programs to fit the age profile of the industry.
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













## Questions Answered

### 1. Count of Survey Takers and Average Age
- **Business Question: How many data professionals participated in the survey, and what is their average age?**
  - **Answer**: The **Count of Survey Takers** card displays the total number of unique respondents, giving a sense of the survey's reach and sample size. The **Average Age** card shows the mean age of the participants, which can help businesses understand the demographic profile of their data workforce. This information is useful for tailoring recruitment strategies and professional development programs to fit the age profile of the industry.

  ![Screenshot 2024-07-22 152435](https://github.com/user-attachments/assets/2655833c-2669-4277-8401-ae908dcfa8cf)

### 2. Job Titles vs. Salary
- **Business Question: What are the average salaries for different job titles in the data profession?**
  - **Answer**: The **Job Titles vs. Salary** stacked bar chart compares average salaries across various job titles, helping organizations identify salary trends and discrepancies. This information can inform compensation strategies, salary negotiations, and budget planning for hiring or salary increases. It also helps in benchmarking against industry standards and ensuring competitive pay structures.

  ![Screenshot 2024-07-22 152412](https://github.com/user-attachments/assets/22c7a5ad-a49b-4afa-8322-8e149da9005b)

### 3. Programming Language Popularity
- **Business Question: Which programming languages are most commonly used by data professionals, and how does this vary by job title?**
  - **Answer**: The **Programming Language Popularity** stacked column chart reveals which programming languages are prevalent among different job titles. This insight is valuable for businesses to understand the skill sets their teams possess or need. It can guide training programs, inform technology stack decisions, and help in recruiting by identifying key skills that are in high demand.

  ![Screenshot 2024-07-22 152348](https://github.com/user-attachments/assets/f8ca4141-d3d1-4998-a42d-8f5c5b943dbd)

### 4. Country Analysis
- **Business Question: How does the distribution of data professionals vary by country, and what are the regional differences in salary ranges?**
  - **Answer**: The **Country Analysis** treemap shows the geographic distribution of survey respondents and highlights regional variations in salary and cost of living. This is useful for global companies to tailor their compensation packages and recruitment strategies based on regional data. It also helps in understanding market conditions and setting competitive salary benchmarks in different countries.

  ![Screenshot 2024-07-22 152314](https://github.com/user-attachments/assets/2d8382b2-1958-4d68-a02a-efb3e6cc95ed)

### 5. Work/Life Happiness
- **Business Question: What is the average level of satisfaction among data professionals regarding their work/life balance?**
  - **Answer**: The **Work/Life Happiness** gauge chart displays the average level of satisfaction with work/life balance among survey respondents. This metric provides insights into employee well-being and can guide organizations in improving workplace policies, benefits, and work environments to enhance overall job satisfaction and retention.

  ![Screenshot 2024-07-22 152531](https://github.com/user-attachments/assets/54874ebf-5a2c-4cc7-bd94-1a6b7cc27dbd)

### 6. Salary Satisfaction
- **Business Question: How satisfied are data professionals with their salaries?**
  - **Answer**: The **Salary Satisfaction** gauge chart illustrates the average satisfaction level with salaries. This insight helps organizations understand how well their compensation packages meet employee expectations. It can drive changes in salary structure or benefits to improve satisfaction and reduce turnover.

  ![Screenshot 2024-07-22 152552](https://github.com/user-attachments/assets/08233b2b-fef4-401a-8a46-d8881d7e405a)

### 7. Data Difficulty Insights
- **Business Question: What challenges do data professionals face in their roles, and how do they perceive the difficulty of these tasks?**
  - **Answer**: The **Data Difficulty Insights** visualization shows how survey respondents rate the difficulty of various data-related tasks. This information helps organizations identify common pain points and areas where additional support or training might be needed. It can also inform process improvements and resource allocation to better support data professionals.

  ![Screenshot 2024-07-22 152454](https://github.com/user-attachments/assets/83cf0367-51c1-47fa-a505-cb3ed5ce80e2)
