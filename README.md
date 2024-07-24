# LIFE EXPECTANCY DATA CLEANING AND ANALYSIS– PYTHON JUPYTER NOTEBOOK (Pandas)  

### Project Overview

This project was inspired by my background as a BLS (Basic Life Support) responder and my passion for health. Delving into the intricate process of data cleaning and exploratory data analysis (EDA), I utilized the powerful Pandas library within a Python Jupyter Notebook environment. The primary objective was to prepare and analyze a life expectancy dataset to uncover insights and trends related to global health metrics. Life expectancy is a vital statistical measure indicating the average number of years a person can expect to live, based on current age and mortality rates. It serves as a crucial indicator of the overall health and well-being of a population, reflecting factors such as healthcare access, socioeconomic conditions, and public health initiatives.

### Table of Contents

1.	[Data Source](#data-source)
2.	[Tools Used](#tools-used)
3.	[Data Preparation](#data-preparation)
4.	[Exploratory Data Analysis](#exploratory-data-analysis)
5.	[Insights](#insights)
6.	[Recommendations](#recommendations)
   
### Data Source

The dataset employed for this project I retrieved itfrom Kaggle. The dataset is available as a CSV file and can be accessed via the following URL: https://www.kaggle.com/datasets/maryalebron/life-expectancy-data

##### Dataset Description
The dataset comprises various health-related indicators for different countries over multiple years. The key columns in the dataset are as follows:

•	Country: The name of the country to which the data corresponds.

•	Year: The year during which the data was recorded.

•	Status: The classification of the country as either "Developing" or "Developed."

•	Life expectancy: The average number of years a person is expected to live in that country for the given year.

•	Adult Mortality: The mortality rate among adults in that country for the given year.

•	Infant deaths: The number of infant deaths in that country for the given year.

•	Alcohol: Per capita alcohol consumption (in liters of pure alcohol) in that country for the given year.

•	Percentage expenditure: Health expenditure as a percentage of Gross Domestic Product (GDP) per capita.

•	Hepatitis B: Hepatitis B vaccination coverage among adults, expressed as a percentage.

•	Measles: Number of reported cases of measles in that country for the given year.

•	BMI: Average Body Mass Index of the population in that country.

•	Under-five deaths: The number of deaths occurring in children under the age of five.

•	Polio: Immunization coverage for Polio (Pol3) among 1-year-olds, expressed as a percentage.

•	Total expenditure: General government expenditure on health as a percentage of total government expenditure.

•	Diphtheria: Immunization coverage for Diphtheria, Tetanus, and Pertussis (DTP3) among 1-year-olds, expressed as a percentage.

•	HIV/AIDS: Deaths per 1,000 live births due to HIV/AIDS for children aged 0-4 years.

•	GDP: Gross Domestic Product per capita, measured in USD.

•	Population: The total population of the country.

•	Thinness 1-19 years: The prevalence of thinness among children and adolescents aged 10 to 19 years, expressed as a percentage.

•	Thinness 5-9 years: The prevalence of thinness among children aged 5 to 9 years, expressed as a percentage.

•	Income composition of resources: Human Development Index in terms of income composition, ranging from 0 to 1.

•	Schooling: Average number of years of schooling in the country.

### Tools Used

The project was executed using Python Jupyter Notebook, leveraging the Pandas library for data manipulation and analysis. Pandas is a robust data analysis tool that provides efficient structures for managing and analyzing large datasets.

### Data Preparation

The data preparation phase was crucial for setting the stage for meaningful analysis. The following steps were undertaken to prepare the dataset for exploration:

##### 1.	Importing the Dataset:
o	Imported the Pandas library to leverage its data manipulation capabilities.

o	Loaded the CSV file containing the dataset into a Pandas DataFrame.

o	Assigned the DataFrame to a variable for further analysis.

o	Displayed basic information about the DataFrame, including the number of rows and columns, and reviewed the initial and final records for a preliminary overview.

##### 2.	Data Cleaning:

o	Duplicate Check: Verified that there were no duplicate records in the dataset.

o	Null Values Assessment: Identified and quantified the presence of missing values. The dataset exhibited 2,563 null values distributed across various columns:

	Life expectancy: 10 missing values

	Adult Mortality: 10 missing values

	Alcohol: 194 missing values

	Hepatitis B: 553 missing values

	BMI: 34 missing values

	Polio: 19 missing values

	Total expenditure: 226 missing values

	Diphtheria: 19 missing values

	GDP: 448 missing values

	Population: 652 missing values

	Thinness 1-19 years: 34 missing values

	Thinness 5-9 years: 34 missing values

	Income composition of resources: 167 missing values

	Schooling: 163 missing values

o	Decimal Precision: Ensured that all decimal values were formatted to two decimal places for consistency.

### Exploratory Data Analysis

The exploratory data analysis (EDA) phase involved an in-depth examination of the dataset to uncover patterns, trends, and anomalies. Key activities included:

•	Descriptive Statistics: Computed summary statistics for each column, including count, mean, standard deviation, minimum, percentiles, and maximum values.

### Insights

##### •  Life Expectancy:
o	Average: 69.22 years.

o	Range: 36.30 to 89.00 years.

##### • Mortality Rates:

o	Adult Mortality: Average of 164.80 deaths per 1000 adults.

o	Infant Deaths: Average of 30.30 per 1000 live births.

o	Under-five Deaths: Average of 42.04 per 1000 live births.

##### • Health Expenditure:

o	Alcohol Consumption: Average of 4.60 units per person per year.

o	Health Expenditure: Average of 738.25% of GDP.

o	Total Health Expenditure: Average of 82.55% of GDP.

##### • Vaccination and Disease Rates:

o	Hepatitis B Vaccination: 80.94% coverage.

o	Polio Vaccination: 82.55% coverage.

o	Diphtheria Vaccination: 82.32% coverage.

o	Measles Incidence: Average of 2419.59 cases.

##### • Nutritional Status and Education:

o	BMI: Average of 38.32.

o	Thinness (ages 1-19): 4.84%.

o	Thinness (ages 5-9): 4.87%.

o	Schooling: Average of 11.99 years.

##### • Economic Indicators:

o	GDP: Average of $7483.16.

o	Population: Average of 12.75 million, with a maximum of 1.29 billion.

### Recommendations

To increase life expectancy in the countries involved, I developed the following recommendations based on the collected insights:

##### 1. Increase Health Expenditure:
   Optimize and increase health spending, focusing on primary care and preventive services.

##### 2. Enhance Vaccination Programs:
   Improve vaccination coverage through awareness campaigns and mobile units.

##### 3. Address Malnutrition:
Invest in nutritional programs and public health campaigns to combat child malnutrition.

##### 4. Expand Education: 
Increase access to education, especially for disadvantaged groups, and integrate health education.

##### 5. Stimulate Economic Growth: 
Implement policies to boost economic growth and reduce income inequality.

##### 6. Reduce Mortality Rates: 
Improve maternal and child health services and promote healthy lifestyles for adults.

##### 7. Combat HIV/AIDS: 
Enhance awareness, prevention, and support services for individuals affected by HIV/AIDS.

