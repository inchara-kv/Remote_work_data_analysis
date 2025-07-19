# Remote_work_data_analysis
A data analysis project exploring remote work trends using Python, Pandas, and visualization libraries. Includes EDA reports, charts, and a data-cleaning pipeline.

# Remote Work Data Analysis Report

## Introduction

This report presents an exploratory data analysis of the provided remote work dataset. The objective is to understand the characteristics of the workforce, analyze patterns related to work location, and identify potential relationships between various factors such as experience, hours worked, and geographical region.

## Data Cleaning and Preparation

Based on the initial inspection and profiling of the data, the following steps were taken to clean and prepare the dataset for analysis:

*   **Handling Missing Values:** Missing values in the 'mental_health_condition' and 'physical_activity' columns were filled using the forward-fill method. This approach assumes that missing values are likely similar to the preceding non-missing values.
*   **Removing Duplicates:** Duplicate rows were identified and removed to ensure each record represents a unique observation.
*   **Standardizing Column Names:** Column names were converted to lowercase and spaces replaced with underscores for consistency and ease of use in analysis.

## Exploratory Data Analysis and Key Findings

The following visualizations shows data and insights explored during the process:

### Work Location Distribution

The bar chart showing the distribution of work locations indicates the proportion of employees working in Hybrid, Remote, and Onsite settings. Observing the heights of the bars helps understand which work location is most prevalent in this dataset.

### Average Hours Worked Per Week by Work Location

This bar plot compares the average number of hours worked per week across the different work locations (Hybrid, Remote, and Onsite). By looking at the heights of these bars, we can see if there are notable differences in average working hours based on where employees work.

### Correlation Heatmap

The correlation heatmap visualizes the relationships between the numerical variables in the dataset. The colors indicate the strength and direction of the correlation (positive or negative). This helps identify which numerical variables tend to increase or decrease together.

### Top regions for remote work

This bar chart shows the distribution of employees across the top continents represented in the dataset. It provides an overview of the geographical representation of the employees.

### Hours Worked Per Week Comparison by Work Location (Box Plot)

The box plot offers a more detailed view of the distribution of 'Hours Worked Per Week' for each work location. It shows the median, quartiles, and potential outliers, giving a better sense of the spread and central tendency of working hours within Hybrid, Remote, and Onsite groups.

### Years of Experience vs Hours Worked Per Week by Work Location (Scatter Plot)

This scatter plot explores the relationship between an employee's years of experience and the number of hours they work per week, colored by their work location. It helps visualize if there is a trend between experience and working hours and if this trend differs across Hybrid, Remote, and Onsite roles. The size of the points also indicates the years of experience.

## Conclusion 

This exploratory analysis has provided initial insights into the remote work dataset, highlighting distributions of work locations, average working hours, geographical representation, and relationships between experience and hours worked.
