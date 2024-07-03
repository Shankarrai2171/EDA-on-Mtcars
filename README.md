## Exploratory Data Analysis-on-Mtcars
#### Exploratory Data Analysis (EDA) on the mtcars dataset involves understanding its structure, characteristics, and relationships among variables using visual and statistical methods.
![cars](https://github.com/Shankarrai2171/EDA-on-Mtcars/assets/164284515/3ff77088-7690-413e-b443-57d75c02a16b)
### Tools
IDE: RStudio 📓

### Data Manipulation and Analysis:
dplyr 💡
magrittr
### Data Visualization:
ggplot2 📊
corrplot 📈
## Dataset Description
### Dataset description for the mtcars dataset:
#### Name: mtcars
#### Source: Motor Trend US magazine
#### Date: 1974
## Dataset Dimmmension :
### Total Columns: 11 variable, represents specific attributes or measurements related to different car models.
### Total Rows: 32 rows, each representing a different car model.

![head()](https://github.com/Shankarrai2171/EDA-on-Mtcars/assets/164284515/c16b22f6-5fb8-409c-8dec-558670847faa)
## Variables Contains in mtcars:
### Describing the alias names of variables:
#### mpg: Miles/(US) gallon
#### cyl: Number of cylinders
#### disp: Displacement (cu.in.)
#### hp: Gross horsepower
#### drat: Rear axle ratio
#### wt: Weight (1000 lbs)
#### qsec: 1/4 mile time
#### vs: Engine (0 = V-shaped, 1 = straight)
#### am: Transmission (0 = automatic, 1 = manual)
#### gear: Number of forward gears
#### carb: Number of carburetors
## Summary():
### Summary function provides a concise statistical summary of numerical variables in a dataset. Here's what the summary() function typically represents and how it is used:
## Purpose of Summary() Function
### Statistical Summary:
#### For Numerical Variables: summary() computes summary statistics such as minimum, 1st quartile (Q1), median (Q2), mean, 3rd quartile (Q3), and maximum values for each numerical variable in the dataset. It also provides the number of non-missing values (NA counts are omitted) and the summary() function provides a quick statistical overview of numerical variables, making it a fundamental tool for initial data exploration, quality assessment, and understanding the characteristics of the dataset before proceeding with further analysis or modeling.
![summary](https://github.com/Shankarrai2171/EDA-on-Mtcars/assets/164284515/202db2ec-719e-437e-9c28-e6f5e9e8019a)
### Checking the unique values in Dataset for each variable :
![unique value for each col](https://github.com/Shankarrai2171/EDA-on-Mtcars/assets/164284515/2118def7-150a-4279-9df4-321a50c20015)
### Counting the each unique values:
![count_unique](https://github.com/Shankarrai2171/EDA-on-Mtcars/assets/164284515/b0cac426-3778-4123-9314-7dbe2d64b828)
## Handling Missing values:
### The is.na() function returns a logical vector indicating TRUE for elements that are missing (NA) and FALSE otherwise.
### You can use this function to check for missing values in a dataset or a specific column. 
### As we got the the output of False means, this dataset doesn't contain any missing value, So if the output is True also we can handle missing value with mean() and median() for Numerical variables and mode() for Categorical variable
![missingvalues](https://github.com/Shankarrai2171/EDA-on-Mtcars/assets/164284515/80f99462-46a6-48c3-aed3-ad3deef245a5)


