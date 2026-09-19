Logistics Data Collection, Cleaning & Preprocessing

This project demonstrates an end-to-end data collection, cleaning, and preprocessing workflow for logistics analysis using Python and Pandas. The project simulates a real-world logistics data preparation scenario in which raw shipment data may contain missing values, duplicate records, inconsistent categorical labels, incorrect data types, and extreme observations.

The dataset used in this project is a simulated logistics dataset inspired by the structure and characteristics of the publicly available DataCo Smart Supply Chain dataset. It contains operational information such as shipment ID, region, shipping mode, vehicle type, transportation distance, package weight, expected delivery time, actual delivery time, shipping cost, delivery rating, weather conditions, and delivery status.

The preprocessing workflow begins with data loading and exploratory inspection to understand the dataset structure and identify potential quality issues. Missing numerical values are handled using median imputation, while missing categorical values are replaced using the mode. Duplicate records are detected and removed to prevent inaccurate calculations. Categorical variables are standardized by removing unnecessary spaces and applying consistent capitalization.

Outliers in important numerical variables such as distance, package weight, shipping cost, and delivery duration are identified using the Interquartile Range (IQR) method and treated through capping. Date fields are converted into appropriate datetime formats for further analysis. Additional logistics features, including delivery delay and a late-delivery flag, are created to improve analytical usefulness.

Min-Max normalization is also applied to selected numerical variables so that features can be compared on a common 0–1 scale.

The final cleaned dataset is exported as a CSV file and documented along with the complete Python preprocessing code and a detailed project repoTechnologies

Python, Pandas, NumPy, Matplotlib, VS Code

Key Outcome

A structured and reliable logistics dataset prepared for further exploratory analysis, visualization, KPI development, and predictive analytics.

Author

Manish Singh
B.Tech CSE Student | Aspiring Data Analyst
