# EDA(Eploratory Data Analysis) on Iris Dataset
This project performs an Exploratory Data Analysis (EDA) on the classic Iris flower dataset using Python. The goal is to understand the dataset through visualization, statistics, and feature analysis to reveal insights and patterns among different Iris species.

## Dataset Description

The Iris dataset contains 150 records of iris flowers from three different species:
- Setosa
- Versicolor
- Virginica

### Features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
- Species (target label)

---

## Libraries and Tools Used
- pandas – for data handling
- numpy – for numerical operations
- matplotlib.pyplot – for basic plots
- seaborn – for statistical visualizations
- sklearn.datasets – to load the Iris dataset

---

## EDA Workflow Summary

### Step 1: Loading the Data
- Loaded the dataset using `sklearn.datasets.load_iris`
- Converted it to a Pandas DataFrame for easier analysis

### Step 2: Data Cleaning
- Checked for missing/null values
- Verified data types and dimensions

### Step 3: Descriptive Statistics
- Used `.describe()` to view mean, std, min, max of each feature
- Grouped data by species for deeper insights

### Step 4: Data Visualization
- Histograms for feature distribution
- Box plots to detect outliers
- Pairplot to show relationships between features
- Heatmap to display feature correlations
- Violin plots to compare species distributions

### Step 5: Key Insights
- Petal Length and Width are strong indicators of species
- Setosa is linearly separable from other species
- Versicolor and Virginica show overlapping distributions

---

## Project Highlights

- Clean and beginner-friendly EDA using Python libraries
- Rich set of visualizations to explore the dataset
- Insightful comments and markdown for better understanding
- Suitable foundation for future ML model building

## Conclusion

This EDA serves as a comprehensive introduction to data analysis and visualization in Python using the Iris dataset — a favorite dataset in machine learning and data science education.
