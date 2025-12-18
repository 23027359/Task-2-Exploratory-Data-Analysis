## Project Overview
This project performs comprehensive data cleaning and exploratory data analysis on the famous Titanic passenger dataset. The goal is to understand the factors that influenced passenger survival and uncover meaningful patterns through statistical summaries and visualizations.

## Dataset
- **Source:** Titanic Dataset (publicly available on Kaggle / loaded directly from a reliable online source)
- **Rows:** 891 passengers
- **Key Features:**  
  - Survived (0 = No, 1 = Yes)  
  - Pclass (Ticket class: 1 = 1st, 2 = 2nd, 3 = 3rd)  
  - Sex  
  - Age  
  - SibSp (Number of siblings/spouses aboard)  
  - Parch (Number of parents/children aboard)  
  - Fare  
  - Embarked (Port of Embarkation: C = Cherbourg, Q = Queenstown, S = Southampton)  
  - Additional derived features (FamilySize, IsAlone, Title, HasCabin)

## Tools & Libraries Used
- Python
- Pandas (data manipulation & cleaning)
- NumPy
- Seaborn & Matplotlib (visualization)

## Data Cleaning & Feature Engineering
- Filled missing **Age** values with the median.
- Filled missing **Embarked** values with the mode.
- Created **HasCabin** binary feature (1 if cabin info present, 0 otherwise) and dropped original Cabin column.
- Engineered **FamilySize** = SibSp + Parch + 1.
- Created **IsAlone** flag (1 if traveling alone).
- Extracted **Title** from Name and grouped rare titles.
- Dropped irrelevant columns: PassengerId, Name, Ticket.
- Encoded categorical variables (Sex, Embarked) for correlation analysis
