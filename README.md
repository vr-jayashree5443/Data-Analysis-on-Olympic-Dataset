# Data-Analysis-on-Olympic-Dataset

This project involves an analysis of Olympic datasets, consisting of athlete information and National Olympic Committee (NOC) regions. The goal is to explore the data, perform data cleaning, and conduct various analyses to gain insights into the Olympic participation trends.

## Datasets

The project utilizes two main datasets:

1. **Athlete Dataset**: Contains over 270,000 datapoints with information about athletes participating in the Olympics.
2. **NOC Dataset**: Provides information about National Olympic Committees (NOCs) and their corresponding regions.

## Workflow

1. **Importing Libraries**: Necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and regular expressions are imported.
2. **Reading the Dataset**: Both the athlete and NOC datasets are read into the notebook.
3. **Data Exploration**: Initial exploration of the datasets including checking for basic information like the number of entries, data types, and missing values.
4. **Data Cleaning**: Cleaning steps involve handling missing values, creating new columns, and removing unnecessary columns.
5. **Data Analysis**: Various analyses are performed on the cleaned dataset to extract meaningful insights about Olympic participation.

## Data Cleaning

- **Handling Null Values**: Missing values in columns such as Age, Height, Weight, and Medal are handled by filling them with mean values or appropriate replacements.
- **Creating Region Column**: A new column "region" is added to the athlete dataset based on the NOC information.
- **Cleaning Event Column**: Unwanted phrases in the "Event" column are removed using regular expressions.

## Data Analysis

1. **Height vs. Weight Relationship**: The relationship between athletes' height and weight is visualized to understand any correlations.
2. **Gender Participation Over Time**: Analysis is conducted to determine the number of male and female participants in the Olympics between 1876 and 2016.
3. **Summer vs. Winter Olympics Participation**: The participation of male and female athletes in both Summer and Winter Olympics is compared to identify any differences.

## Exporting Cleaned Data

The cleaned dataset is exported to CSV, JSON, and Excel formats for further use or sharing.

## Usage

The notebook serves as a comprehensive guide to analyzing the Olympic dataset. Users can replicate the analysis, modify it, or utilize the provided code snippets for their own projects.

Feel free to explore the notebook further and delve deeper into the fascinating world of Olympic data analysis!
