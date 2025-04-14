# 🚢 Titanic Dataset – Exploratory Data Analysis (EDA)
This project presents a comprehensive Exploratory Data Analysis (EDA) on the Titanic dataset using Python. It explores how different factors such as passenger class, age, gender, and fare impacted survival, using visual and statistical methods.

## 📁 Repository Contents
- `Titanic_EDA.ipynb` - Main Jupyter notebook with all analysis, visualizations, and observations.
- `raw_data` - Folder containing 3 raw datasets:
- `preprocessed_data` - Folder containing 2 preprocessed datasets
- `README.md` - This project documentation.

## 🎯 Objective
- Perform data cleaning and preprocessing.
- Identify patterns, trends, and correlations affecting survival.
- Visualize feature relationships with respect to the target variable (Survived).
- Handle missing values and outliers.

## 🧰 Tools & Libraries Used
- Python (Jupyter Notebook)
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔍 Exploratory Analysis Highlights
- Data inspection: `.info()`, `.describe()`, `.value_counts()`
- Visual analysis:
  - Histograms, boxplots, scatterplots
  - Pair plots and heatmaps
  - Count plots by class and gender
- Survival rate comparisons by:
  - Passenger Class
  - Gender
  - Age Groups
  - Fare Ranges

## 💡 Key Findings
- Females had a significantly higher survival rate than males.
- 1st Class passengers had the highest survival probability.
- Children (under 10) were more likely to survive than adults.
- Fare was positively correlated with survival.
- Outliers were identified in the Fare and Age columns.
- Missing values were found in the Age and Embarked columns.

## ✅ How to Run the Project
- Clone the repository:  
```
git clone https://github.com/yourusername/titanic-eda.git`
```
```
cd titanic-eda
```
- Install dependencies:  
```
pip install pandas numpy matplotlib seaborn
```
- Launch the notebook:  
```
jupyter notebook Titanic_EDA.ipynb
```

## 📬 Contact
For feedback or questions, feel free to reach out.
