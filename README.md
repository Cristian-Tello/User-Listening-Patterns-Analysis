## USER LISTENING PATTERNS ANALYSIS
**Project Type: Data Wrangling** 

**Role: Data Analyst** 

**Programming Language: Python**

## Tools & Technologies
I worked with real-world music streaming data to explore and analyze listening habits among users from two cities: Springfield and Shelbyville.

The main objective was to clean, organize, and examine the dataset to identify patterns in user behavior, compare music preferences between cities, and evaluate how listening activity varies across different days and times. Using Python, the data was processed and analyzed to generate insights that support data-driven conclusions about user engagement and music consumption trends.

Through this project, I applied fundamental data analysis techniques, including data cleaning, filtering, aggregation, and exploratory data analysis (EDA), while developing practical skills in working with real-world datasets.

| Function | Purpose|
| --- | --- |
| **print()** | Display cleaned data, results, and validation outputs |
| **type()** | Check the data type of variables |
| **int()** | Convert age values into integers |
| **sum()** | Calculate the total spending across categories |
| **len()** | Count the number of registered customers |
	
## String Methods Used
| Method | Purpose|
| --- | --- |
| **.strip()** | Remove unnecessary spaces from the beginning and end of names |
| **.replace()** | Replace underscores (_) with spaces |
| **.split()** | Separate customer names into individual elements |
| **.sort()** | 	Sort customer records by user ID |
| **.append()** | Add cleaned customer records to the new usuarios_limpio list |
| **List indexing** | Access customer IDs, names, ages, categories, and spending values |

## Other Python Concepts
**For Loops**

Used to iterate through lists and datasets, allowing efficient inspection, transformation, and cleaning of data records.

**Custom Functions (def)**

Created reusable functions to automate repetitive data-cleaning tasks, improve code organization, and enhance readability.

## Project Overview
this project focuses on transforming raw customer and purchase data into a reliable dataset for business analysis.

The primary objective was to clean, process, and validate customer information using Python-based data cleaning techniques. After preparing the dataset, the analysis was used to answer key business questions, including:
* Identifying loyal and high-value customers.
* Analyzing revenue performance across product categories.
* Detecting data quality issues and inconsistencies.
* Discovering opportunities for targeted marketing campaigns.
* Supporting data-driven business decisions through accurate and reliable data.

* This project demonstrates practical data-cleaning skills, including data validation, missing-value handling, list iteration with for loops, and the development of reusable Python functions to automate repetitive tasks and improve workflow efficiency.

## Data entry

Store 1 stores user information in nested lists. Each sublist contains:

- `user_id`: unique identifier
- `user_name`: first and last name in a single string
- `user_age`: age
- `fav_categories`: favorite shopping categories (uppercase)
- `total_spendings`: amounts corresponding to each category

## Result
The project successfully transformed raw customer data into a clean and structured dataset ready for business analysis. Through the implementation of data cleaning and preprocessing techniques, several key outcomes were achieved:

# Data Quality Improvements
Standardized customer names by removing inconsistencies such as extra spaces, underscores, and formatting issues.
Converted data types to their appropriate formats, including customer ages from strings to integers.
Normalized product categories by converting all values to lowercase, ensuring consistency across the dataset.
Automated the cleaning process through reusable Python functions, making the workflow scalable and efficient.

# Data Processing Achievements
Cleaned and validated the entire customer database using a custom clean_user() function.
Applied iterative processing with for loops to transform multiple customer records efficiently.
Created reusable logic that can be applied to future datasets with similar structures.

# Business Insights Generated
Calculated the company's total revenue based on customer purchase history.
Identified customers under 30 years old for potential youth-focused marketing campaigns.
Detected high-value young customers with spending above established thresholds.
Analyzed purchasing behavior by category, including customers who purchased clothing products.
Developed a category-based filtering function to quickly retrieve customers according to their purchase preferences.

# Skills Demonstrated
Data Cleaning & Preprocessing
Python Programming
For Loops
Custom Functions (def)
Data Validation
Data Transformation
Business-Oriented Data Analysis
Customer Segmentation
Revenue Analysis
