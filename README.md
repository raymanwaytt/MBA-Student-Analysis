# MBA Students Analysis
This project involves analyzing a dataset of MBA students to explore various factors such as GPA, GMAT scores, work experience, and demographics. The analysis aims to uncover insights regarding  academic performance, and potential areas for improvement in MBA programs.

## Table of Contents
Installation
Dataset
Data Exploration
Data Cleaning and Feature Engineering
Data Analysis Questions
Data Visualization
Conclusion

## Installation
To run this project, ensure you have Python 3.6 or newer and the following libraries installed:

pandas

seaborn

matplotlib

## Dataset
The dataset used in this analysis is MBA.csv, which contains 6194 entries and 10 columns. Key columns include:

application_id: Unique identifier for each application

gender: Gender of the applicant

international: Boolean indicating if the applicant is international

gpa: Grade Point Average of the applicant

major: Field of study

race: Race of the applicant

gmat: GMAT score

work_exp: Years of work experience

work_industry: Industry of prior work experience

admission: Admission status (contains significant missing values)

## Data Exploration
The initial exploration of the dataset includes:

-Displaying the first 5 rows of the dataset

-Checking data types and information

-Identifying missing values

-Summary statistics of the dataset

## Data Cleaning and Feature Engineering

The following steps were taken to clean and prepare the data for analysis:

Dropped the admission column due to over 80% missing values.

Created new classification columns based on GPA and work experience:

GPA Classification:

Fail, Third Class, Second Class Lower, Second Class Upper, First Class
Work Experience Classification:

1-3 years, 4-6 years, 7-9 years

## Data Analysis Questions
The analysis seeks to answer several questions, including:

How does work experience affect GPA?

What is the distribution of GMAT scores?

Which majors tend to have the highest GMAT scores?

What are the GPA differences between international and domestic students?

Are there differences in GPA between genders?

Which majors perform better in terms of GPA?

What is the distribution of students across different work industries?

How do GPA classifications differ in terms of GMAT scores and work experience?

How does race correlate with GPA?

How do GMAT scores vary across different work experience ranges?


## Data Visualization

### The analysis includes various visualizations, such as:

Heatmaps for the effect of work experience on GPA

Histograms for GMAT score distribution

Bar plots comparing GPA among different demographics (e.g., gender, international status)

Insights on the distribution of students across various work industries

Example Visualization

## Conclusion
The analysis provides insights into the academic performance and demographic factors influencing MBA admissions. It identifies trends in GPA and GMAT scores across different classifications and highlights the importance of work experience and major choice in students' success.
