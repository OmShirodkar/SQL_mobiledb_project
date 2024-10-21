1. Project Title
Mobile Data Analysis Using SQL

2. Project Overview
Problem Statement:
Analyzing mobile usage behavior is critical for understanding how users interact with their devices. Metrics like app usage time, screen-on time, and data usage can provide insights into user engagement and battery performance. This analysis aims to identify patterns that contribute to efficient device usage, battery management, and app engagement.
Solution:
The project uses SQL to query and analyze a dataset consisting of mobile user data, focusing on metrics like app usage, battery drain, and data usage. By investigating these factors, businesses and developers can optimize app performance and improve user satisfaction.

3. Objectives
Data Collection:
Query and extract the dataset consisting of mobile user behaviors, focusing on device model, app usage, screen time, and battery consumption.
Data Cleaning:
Ensure that the dataset is clean by handling missing values, if any, and standardizing the columns for efficient querying.
Behavioral Analysis:
Analyze different user behavior classes based on app usage, screen-on time, and data consumption.
User Segmentation:
Group users based on their device usage patterns, battery consumption, and data usage, identifying high-use and low-use groups.
Recommendations:
Provide actionable insights to optimize battery life, app performance, and reduce data consumption.

4. Data Sources
Dataset: The project uses a publicly available dataset, Mobile device usage and user behaviour Dataset, from Kaggle. 
Dataset Columns:
User ID: Unique identifier for each user.
Device Model: Type of device the user is using.
Operating System: The OS on the device (iOS, Android, etc.).
App Usage Time (min/day): Total time spent on apps per day.
Screen On Time (hours/day): Total time the screen remains active per day.
Battery Drain (mAh/day): Average battery consumption in milliampere-hours per day.
Number of Apps Installed: Total apps installed on the user’s device.
Data Usage (MB/day): Average mobile data consumption in megabytes per day.
Age: Age of the user.
Gender: Gender of the user.
User Behavior Classification: Classification of user behavior (e.g., Light User, Heavy User, etc.).

5. Tools and Libraries
SQL: For querying the dataset.
Jupyter Notebook: To document and visualize the analysis.
Python : For analysis, dataset and visualisation for better insights including Model For Classification of User Behavior and Prediction of Battery Drain.

6. Project Workflow

6.1 Data Collection and Preprocessing
Load the Dataset:
Extract the dataset into a SQL environment for further analysis.


Handle Missing Values:
Ensure there are no missing values in important columns like "App Usage Time" and "Battery Drain".
Ensure Data Consistency:
Verify that numerical columns such as "Battery Drain" and "Data Usage" are correctly formatted.


6.2 Exploratory Data Analysis (EDA)
User Distribution by Device Model:
Analyze the distribution of users across various device models.



App Usage Time Analysis:
Calculate the average app usage time per user and compare it across different operating systems.


6.3 User Segmentation by Behavior
Heavy vs. Light Users:
Segment users into behavior categories based on app usage and screen-on time.




6.4 Battery Usage Analysis
Battery Drain Analysis:
Calculate the average battery drain across different device models and operating systems.



6.5 Data Usage Patterns
Data Usage Per Day:
Analyze the average data usage per user and identify heavy data consumers.


7. Actionable Insights
Optimize Battery Usage:
Suggest device-specific strategies to reduce battery drain based on the average usage and screen-on time.
Improve App Performance:
For heavy app users, developers could optimize apps to consume less power and reduce screen-on time.
Data Plan Optimization:
Recommend data plans tailored for heavy data users to reduce churn and provide better services.

8. Conclusion
This project provides an analysis of mobile user behavior using SQL. By focusing on key metrics such as app usage, screen time, and battery consumption, we can better understand user engagement and device performance. The insights gained can lead to improved customer satisfaction and optimized device usage.

