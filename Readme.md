# Titanic Dataset-- Exploratory Data Analysis
This project explores the Titanic passenger dataset to uncover survival patterns based on gender, embarkation port, family relationships, and class.
The process involves cleaning messy raw data using Excel, further refinement using Python, and generating key insights through visual exploration.

#⚙️ Tech Stack
Excel — Initial data cleaning

Python — Data analysis and visualization

Pandas

Matplotlib

Seaborn

Jupyter Notebook — Coding and report generation

#🧹 Data Cleaning Process
In Excel:

- Splitted combined columns if necessary.
- Renamed headers for better readability.
- Replaced values (e.g., 0/1 ➔ No/Yes).
- Handled missing values (blank cells, NA)
- Changed data types appropriately (Text, Number).- Removed duplicate rows.

# In Python:
-Checked for missing values, null types.
- Cleaned categorical fields (Embarked, Sex, etc.).
- Handled outliers if necessary.
- Ensured consistency before starting EDA.

 #📊 EDA Process
  
 - Univariate Analysis (Distribution of features like Age, Fare, etc.)
- Bivariate Analysis (Survival vs Gender, Survival vs Embarkation Port)
- Correlation Analysis (Heatmap)
- Family size impact (SibSp and Parch combined)

#📈 Visualizations
- Countplots — Gender vs Survival, Embarked vs Survival
-  Boxplots — Fare vs Survival
- Histograms — Age Distribution, Fare Distribution
- Heatmap — Correlation Matrix

Each visualization is accompanied by short, clear observations.

