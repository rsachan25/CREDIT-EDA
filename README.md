# **Credit EDA Case Study**

This project involves performing Exploratory Data Analysis (EDA) on credit application data to better understand the factors influencing loan default rates. By analyzing loan application data, the goal is to detect patterns that suggest potential defaults and help financial institutions mitigate risk.

## **Project Overview**

The assignment focuses on risk analytics within the banking and financial services sector. The objective is to apply EDA techniques to credit data and gain insights into customer behavior, enabling better loan approval decisions. The analysis also aims to help businesses avoid potential financial losses while ensuring deserving applicants are not rejected.

## **Key Objectives:**

Understand loan default patterns by examining client and loan attributes.
Identify key factors (driver variables) that influence loan repayment difficulties.
Mitigate financial risks by understanding the profile of likely defaulters.
Guide decisions such as loan approval, denial, and risk-based interest rates.

## **Workflow**

- **Data Understanding**
  
	Two datasets were used:\
		app_data.csv with 307,511 rows and 122 columns.\
		pre_app_data.csv with 1,670,214 rows and 37 columns.
- **Data Cleaning & Manipulation**
  
	Identified missing values and handled null data.\
	Removed irrelevant columns with over 40% missing data.\
	Imputed missing values using mean/mode based on context.
- **Outlier Detection & Handling**

	Applied capping and winsorization techniques to manage outliers.\
	Addressed negative values in fields like DAYS_BIRTH and DAYS_EMPLOYED.
- **Analysis Performed**
  
	Univariate analysis: Focused on numerical columns like AMT_INCOME_TOTAL, AMT_CREDIT, etc.\
	Bivariate analysis: Explored relationships between variables such as AMT_GOODS_PRICE and loan status.\
	Correlation analysis: Investigated correlations between key attributes like AMT_CREDIT, AMT_GOODS_PRICE, etc.
- **Integrated Data Analysis**
  
	Merged current and previous loan applications to analyze relationships between variables across datasets.\
	Examined default rates based on loan approval status, gender, age groups, and income types.
			
## **Key Insights**

* Income & Credit Patterns: Most applicants fall in the middle-income range, while the highest credit defaults occur in specific ranges.
* Default Rates: Males exhibit higher default rates compared to females. Younger applicants (20-30 years) also tend to default more frequently.
* Family & Loan Risk: Larger family sizes correlate with higher default risk, especially among married clients with multiple children.
* Correlation: A strong positive correlation exists between loan amount (AMT_CREDIT) and the price of goods financed (AMT_GOODS_PRICE).

## **Technologies Used**

Python: For data analysis and manipulation.\
Pandas: To load, clean, and explore the data.\
Seaborn & Matplotlib: For data visualization.\
NumPy: For numerical operations.
