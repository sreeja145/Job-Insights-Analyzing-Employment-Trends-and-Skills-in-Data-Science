# Job-Insights-Analyzing-Employment-Trends-and-Skills-in-Data-Science
*****************************************************************************

## Problem Statement
Analyzing a job dataset can provide valuable insights and benefits for both organizations and
individuals.For individuals, analyzing job datasets can provide valuable information for career
planning and decision-making. By understanding job market trends, skill requirements, and
salary ranges, individuals can make informed choices about their career paths, skill
development, and job search strategies. Taking this information, analyze the data and give the
solutions to the below mentioned problems

About Data:

Context
This is a dataset of data science jobs posted in job portals.
The columns explanation are as follows,
1. Job Title: Title of the job posting
2. Salary Estimation: Salary range for that particular job
3. Job Description: This contains the full description of that job
4. Rating: Rating of that post
5. Company: Name of company
6. Location: Location of the company
7. Headquarter: Location of the headquarter
8. Size: Total employee in that company
9. Founded: The year company was founded
10. Type of ownership: Describes the company type i.e non-profit/public/private farm etc
11. Industry, Sector: Field applicant will work in
12. Revenue: Total revenue of the company
13. Competitors: Competitors of the company
*****************************************************************************************
## Data Cleaning
The following changes was made:

Basic cleanings:

1. Drop duplicates and fill NaN values.
2. Remove first column (false index) and rows without salary.
3. Reset Index
4. Parsed numeric data out of salary column as min, max and avg _salary:

* Taken into account the hourly given salaries. Changed into annual salaries
* Added columns for employer provided salary and hourly wages. Can be used later in models.
* Parsed rating out of company text and removed undesired characters.

* Made a new column for company state and cleaned it.

* Transformed founded date into age of company

* Made columns for different skills, they were listed in the job description:

* Python, Spark, AWS, Excel, SQL, SAS, Julia, Keras, MatPlotLib, PyTorch etc.
* Column for simplified Job Title.

* Column for Seniority:by Jobs Title info and by Jobs Descriptoin info.
* Cleaned other columns:

    Size,
    Type of ownership,
    Revenue,
    Made a Degree column:

* from Job Description column
    It accounts for any experience credit or requirement for Masters or a Ph.D. degree
*************************************************************************************************

## Exploratory Data Analysis

1. Number of different Job titles
2. Spread of job locations in the USA

Rating of companies

![image](https://github.com/sreeja145/Job-Insights-Analyzing-Employment-Trends-and-Skills-in-Data-Science/assets/73514771/8ddf53e7-57ad-4f52-9268-e6debd134554)


 Jobs by Industries
![image](https://github.com/sreeja145/Job-Insights-Analyzing-Employment-Trends-and-Skills-in-Data-Science/assets/73514771/ca0c03f3-a5a9-4f3e-8c0f-9ad4b503b15c)




***************************************************************************************************************
## tools used
* Python 
* Fraeworks -  Google colab
* Packages - numpy, pandas, matplotlib, seaborn, nltk
  
 
