# Prodigy_DS_02

#### Titanic Dataset Analysis 🚢📊

This repository contains a Python script utilizing Pandas, Matplotlib, and Seaborn to analyze and visualize the Titanic dataset. 
Here's a summary of the key findings:

1. **Data Overview:**
   - The Titanic dataset (`tnc`) provides information on passengers, including details such as survival status, class, name, sex, age, and more.
   - A quick examination using `tnc.head()` reveals the initial rows of the dataset.

2. **Missing Values:**
   - The script identifies and visualizes missing values using a heatmap (`tnc3`), highlighting columns with null values (e.g., 'Age', 'Cabin', 'Embarked').
   - The 'Age' column has 177 missing values, 'Cabin' has 687, and 'Embarked' has 2.

3. **Visualization:**
   - The script generates visualizations to provide insights into the dataset.
   - A countplot (`tnc5`) showcases the survival distribution among different passenger classes.
   - Another countplot (`tnc6`) explores the survival distribution based on gender.
   - A countplot (`tnc8`) depicts the distribution of passengers based on the number of siblings/spouses aboard.

4. **Boxplot Analysis:**
   - A boxplot (`sns.boxplot`) examines the distribution of ages across different passenger classes, highlighting potential age variations among classes.

5. **Conclusion:**
   - The dataset reveals a diverse range of information about Titanic passengers, including their survival status, class, gender, and family relationships.
   - Missing values, especially in the 'Cabin' column, could impact certain analyses and may require further handling.
   - Visualizations provide an accessible way to understand patterns and trends within the data.
