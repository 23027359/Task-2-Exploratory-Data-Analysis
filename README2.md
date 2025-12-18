Titanic Dataset Analysis
OverviewThis project analyzes the Titanic dataset using Python, focusing on data cleaning, feature engineering, and visualization.

DatasetThe Titanic dataset is loaded from https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv.

Tools Used- Python (3.x)
- Pandas
- NumPy
- Seaborn
- Matplotlib

Requirements
bash
pip install pandas numpy seaborn matplotlib


AnalysisThe script performs:
- Data cleaning (handling missing values, dropping unnecessary columns)
- Feature engineering (FamilySize, IsAlone, Title)
- Visualizations (survival count, survival by sex, survival by Pclass, age/fare distributions, correlation heatmap)

VisualizationsThe script generates and saves the following PNG files:
- survival_count.png
- survival_by_sex.png
- survival_by_pclass.png
- age_distribution.png
- fare_distribution.png
- correlation_heatmap.png

How to Run1:
1. Save the script as titanic_analysis.py
2. Run: python titanic_analysis.py
