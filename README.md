# Insurance Coverage Classifier

## Background

Whats thedeal with insurance? Why's it important? How many people are uninsured?

The issue of health insurance is top of mind for many Americans. Prior to the Affordable Care Act of 2016, over 20% of the country was uninsured, a failure by any measure. The rate of uninsured has decreased since that time but but can still be alarmingly high on a county by county basis.

> *"In 2019, 33.6% (or 1,054) of U.S. counties had an estimated uninsured rate below 10%, down from 38.6% in 2016, 38.4% in 2017, and 37.7% a year earlier but up from 2013 when only 4.1% or 130 counties had uninsured rates under 10%. "
> 
> "Estimated county uninsured rates ranged from 2.4% to 35.8%, with a median county uninsured rate of 11.0%."
>        - [*US Census Bureau*](https://www.census.gov/newsroom/press-releases/2021/uninsured-health-coverage-rates-decline.html)*

For non-profit or commercial businesses, reaching out to the uninsured can be difficult as there is no single data source, or collection of sources, that can identify uninsured individuals. That said, this is not an uncommon business problem and can be addressed with data science and econometric modeling.

##  Business Case / Task at Hand

Using the available sample data we've set out to identify traits that index high or low for 'rate of uninsured' and ultimately build a model that can predict, at scale, the likelyhood of an individual to have health insurance. 

With this knowedge in hand, outreach efforts can be more targeted and more impactful.

**The task at hand:** 
- Perform EDA on the data to capture summary statistics, outliers, insights and relationships between feature data and 'rate of uninsured' 
- Determine the relevant performance metrics and test a range of classification models to establish benchmarks.
- Iteratively improve model performance until it is GA ready.

## Data
Data dictionary [here](https://github.com/campbel94/insurance_classifier/blob/main/data_dictionary.txt)
The features available in the data include income:
- age
- citizen_status
- nativity_status',
- weekly_hours_worked, worked_last_week & when_last_worked
- total_income, self_employed_income, wage_income, interest_income & other_income
- marital_status
- school_status
- sex
- language
- race

For the sake of this exercise we'll assume that the 0s or 1s in the 'uninsured' column were collected from surveys.

## Python Libraries
The imported libraries listed below were essential to the project's workflow:
###### Data Cleaning & Vizualizing
Pandas, Matplotlib and Numpy allowed for the standard data cleaning, feature engineering and visualization procedures. 
- `import pandas as pd`
- `import numpy as np`
- `import matplotlib.pyplot as plt`
- `import seaborn as sns`
###### Modeling
All models and performance metrics were called from the `sklearn` library
- `from sklearn.neighbors import KNeighborsClassifier`
- `from sklearn.linear_model import LogisticRegression`
- `from sklearn.tree import DecisionTreeClassifier`
- `from sklearn.ensemble import BaggingClassifier, RandomForestClassifier, ExtraTreesClassifier`
## Workflow
### Exploratory Data Analysis
### Modeling


## Key Learnings