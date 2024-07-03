## Prodigy Infotech Internship: Titanic Dataset Exploratory Analysis

### Overview
This README file documents the exploratory data analysis (EDA) performed on the Titanic dataset as part of the Prodigy Infotech internship. The analysis aims to uncover insights about the passengers and the factors influencing their survival during the tragic event.

### Files in this Repository
- `README.md`: This file, providing an overview of the project.
- `titanic_exploratory_analysis.ipynb`: The Jupyter Notebook containing the exploratory data analysis.
- `titanic.csv`: The dataset used for analysis (if included, otherwise instructions for obtaining the dataset are provided).

### Dataset Description
The Titanic dataset contains information about the passengers aboard the Titanic, including details such as age, sex, passenger class, fare, and whether they survived. The main columns in the dataset are:
- `PassengerId`: Unique identifier for each passenger.
- `Survived`: Survival status (0 = No, 1 = Yes).
- `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).
- `Name`: Name of the passenger.
- `Sex`: Gender of the passenger.
- `Age`: Age of the passenger.
- `SibSp`: Number of siblings/spouses aboard the Titanic.
- `Parch`: Number of parents/children aboard the Titanic.
- `Ticket`: Ticket number.
- `Fare`: Passenger fare.
- `Cabin`: Cabin number.
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

### Objectives
The main objectives of this exploratory analysis are:
1. To understand the structure and distribution of the dataset.
2. To identify any patterns or correlations between features.
3. To provide insights into the factors that may have influenced the survival of passengers.

### Steps Performed
1. **Data Loading and Overview**:
   - Loaded the dataset using Pandas.
   - Displayed the first few rows of the dataset to understand its structure.
   - Checked for missing values and data types.

2. **Data Cleaning**:
   - Handled missing values appropriately (e.g., imputing, dropping).
   - Converted categorical features to numerical values if necessary.

3. **Data Visualization**:
   - Created visualizations to understand the distribution of features (e.g., histograms, bar plots).
   - Analyzed the relationship between features and the survival rate using visual tools like box plots, scatter plots, and heatmaps.

4. **Statistical Analysis**:
   - Performed basic statistical analysis to derive insights.
   - Used correlation coefficients to identify relationships between numerical features.

5. **Feature Engineering**:
   - Created new features if necessary to enhance the analysis.
   - Grouped similar features to simplify the dataset.

### Key Findings
1. **Survival Rates**:
   - The overall survival rate was around 38%.
   - Women had a higher survival rate compared to men.
   - Passengers in 1st class had a higher survival rate compared to those in 2nd and 3rd classes.

2. **Age Distribution**:
   - Children (aged below 16) had a higher survival rate.
   - The majority of passengers were between 20 and 40 years old.

3. **Fare and Survival**:
   - Passengers who paid higher fares had a better chance of survival.
   - There was a significant fare difference between the classes.

4. **Embarkation Points**:
   - Passengers who embarked at Cherbourg had a higher survival rate compared to those who embarked at Southampton or Queenstown.

### Conclusion
The exploratory analysis of the Titanic dataset provided valuable insights into the factors affecting passenger survival. This analysis serves as a foundation for building predictive models and further studies on the Titanic dataset.
