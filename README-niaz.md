# project_4_air_quality_machine_learning

Parking Violation Analysis
This project analyzes parking violation data to understand patterns in ticket issuance, fine amounts, and other key variables. The analysis includes visualizations to explore trends by issuing agency, violation type, and other dimensions. The following sections outline the steps and code used in this analysis.

Table of Contents
Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training
Visualizations
Requirements

Data Preprocessing
Loading the Data: The dataset is loaded using pandas, with the required encoding and data types specified to handle any potential formatting issues.

Data Cleaning: Missing values are identified and addressed where necessary to ensure smooth analysis.

Exploratory Data Analysis (EDA)
Descriptive Statistics: Key metrics, such as the distribution of Fine_Amount and counts by ViolationType, are calculated to understand the dataset’s composition.
Grouping Data: Data is grouped by variables like IssuingAgency and ViolationType to understand frequency and patterns.

Visualizations: Initial bar charts and line graphs are created to display the data distribution and relationships across variables.
Feature Engineering
DayType Column: A new feature is created to distinguish tickets issued on weekends versus weekdays, allowing for comparison between these two groups.
Datetime Conversion: The date column is converted to a datetime format, facilitating analysis by time-related dimensions such as hour, day, or month.

Model Training
Machine Learning Models: Various machine learning models, such as Random Forest, Decision Tree, and Logistic Regression, are trained to predict parking violation types based on features like Location, Time, and IssuingAgency.
Hyperparameter Tuning: Parameters are adjusted to optimize model accuracy, and models are evaluated using metrics such as accuracy score.

Visualizations
Fine Amount by Violation Type: A bar chart is generated to show the average fine amount for each violation type.
Fine Amount by Issuing Agency: A similar visualization is created for each issuing agency, highlighting which agencies generate higher or lower fines on average.
Weekday vs. Weekend Analysis: A comparison of total and average fines on weekdays versus weekends to identify any significant differences.
