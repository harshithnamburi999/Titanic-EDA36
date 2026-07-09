# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The objective is to understand the structure of the dataset, identify missing values, analyze feature distributions, explore relationships between variables, and perform basic data cleaning.

The project uses the Titanic dataset available in the Seaborn library and demonstrates common EDA techniques that are widely used in data science and machine learning.

---

## Objectives

- Load and inspect the Titanic dataset.
- Understand the dataset structure.
- Analyze missing values and duplicate records.
- Generate descriptive statistics.
- Perform univariate and bivariate analysis.
- Visualize data using different plots.
- Study feature correlations.
- Handle missing values.
- Summarize important insights from the analysis.

---

## Dataset

The dataset is loaded directly from the Seaborn library.

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```

### Dataset Information

- Number of Rows: **891**
- Number of Columns: **15**

The dataset contains information such as:

- Passenger Class
- Name
- Sex
- Age
- Fare
- Cabin Deck
- Embarkation Port
- Survival Status

---

## Technologies Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (optional)

---

## Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## Project Workflow

### 1. Import Libraries

The required Python libraries are imported for data manipulation and visualization.

### 2. Load Dataset

The Titanic dataset is loaded using Seaborn.

### 3. Data Inspection

The following operations are performed:

- Display first five rows
- Display dataset information
- Check dataset shape
- Display column names
- Generate statistical summary

### 4. Missing Value Analysis

The project checks:

- Number of missing values
- Percentage of missing values

### 5. Duplicate Check

Duplicate records are identified.

### 6. Data Type Analysis

The data type of every column is displayed.

---

# Exploratory Data Analysis

## Univariate Analysis

The following visualizations are created:

### Survival Count

Displays the number of passengers who survived and those who did not.

### Passenger Class Distribution

Shows the distribution of passengers across different classes.

### Gender Distribution

Displays the number of male and female passengers.

### Age Distribution

Histogram with Kernel Density Estimation (KDE).

### Fare Distribution

Shows how ticket fares are distributed.

### Age Boxplot

Used to identify age outliers.

### Fare Boxplot

Used to identify fare outliers.

---

## Bivariate Analysis

The following relationships are explored.

### Survival vs Gender

Compares survival rates between male and female passengers.

### Survival vs Passenger Class

Shows survival across passenger classes.

### Age vs Fare

Scatter plot showing the relationship between age and fare.

---

## Correlation Analysis

Numeric columns are selected and analyzed using a correlation matrix.

A heatmap is generated to visualize correlations.

A pairplot is also created to study relationships among selected variables.

---

## Data Cleaning

Missing values are handled using the following methods.

### Age

Missing values are replaced using the median.

### Embarked

Missing values are replaced using the mode.

### Embark Town

Missing values are replaced using the mode.

### Deck

The Deck column is removed because it contains a large number of missing values.

---

## Final Dataset

After cleaning:

- Missing values are significantly reduced.
- Deck column is removed.
- Dataset is ready for further analysis or machine learning.

---

## Visualizations Included

- Count Plot
- Histogram
- Box Plot
- Scatter Plot
- Correlation Heatmap
- Pairplot

---

## Key Findings

- The dataset contains 891 passenger records.
- Several columns contain missing values.
- The Deck column has the highest number of missing values.
- Most passengers belonged to Third Class.
- Male passengers outnumbered female passengers.
- Female passengers had a higher survival rate.
- First Class passengers had better survival chances.
- Fare contains several outliers.
- Most passengers were between 20 and 40 years old.
- Fare shows a positive relationship with survival.
- Passenger Class has a negative relationship with survival.

---

## Future Improvements

Possible extensions of this project include:

- Feature Engineering
- Outlier Treatment
- Machine Learning Models
- Survival Prediction
- Interactive Dashboards
- Advanced Statistical Analysis

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/harshithnamburi999/Titanic-EDA36.git
```

### Navigate to the project folder

```bash
cd Titanic-EDA36
```

### Install dependencies

```bash
pip install numpy pandas matplotlib seaborn
```

### Run the project

```bash
python titanic_eda.py
```

or open the notebook

```bash
jupyter notebook
```

---

## Project Structure

```
Titanic-EDA36/
│
├── titanic_eda.py
├── Titanic_EDA.ipynb
├── README.md
└── requirements.txt
```

---

## Learning Outcomes

This project demonstrates:

- Data loading
- Data exploration
- Data visualization
- Missing value handling
- Correlation analysis
- Basic data preprocessing
- Exploratory Data Analysis using Python

---

## Author

**Harshith Namburi**

GitHub: https://github.com/harshithnamburi999

---

## License

This project is released under the Apache License 2.0 License.
