
# Diabetes Dataset Exploratory Data Analysis (EDA)

This repository contains a simple exploratory data analysis (EDA) performed on the [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). The goal of this analysis is to gain insights into the distribution and relationships of key medical attributes and the diabetes outcome.

## Files

- `diabetes.csv`: The dataset used for analysis, containing medical diagnostic information of female patients.
- `eda.py`: Python script for performing EDA on the dataset. It includes summary statistics, visualizations, and correlation analysis.

## Features Analyzed

The dataset includes the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (1 indicates diabetes, 0 indicates no diabetes)

## Analysis Performed

The `eda.py` script includes the following steps:

- Loading and inspecting the data
- Checking for null values and data types
- Calculating descriptive statistics for **Glucose** and **BMI**
- Histogram of **Age** distribution
- Heatmap of feature correlations
- Boxplot of **Insulin** levels grouped by **Outcome**

## Visualizations

- **Age Distribution**: Histogram showing how age is distributed in the dataset.
- **Correlation Heatmap**: Displays relationships between features.
- **Insulin vs Outcome**: Boxplot comparing insulin levels between diabetic and non-diabetic patients.

## Requirements

The script uses the following Python libraries:

```bash
pandas
matplotlib
seaborn
```

Install them using:

```bash
pip install pandas matplotlib seaborn
```

## Usage

To run the analysis:

```bash
python eda.py
```

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
