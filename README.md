# EDA-on-Iris-dataset
# Iris Dataset - Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the famous Iris dataset using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.

The goal of this project is to understand the dataset through:

* Data cleaning and inspection
* Statistical summaries
* Data visualization
* Feature relationships
* Species comparison

The Iris dataset is commonly used for beginner machine learning and data analysis projects.

---

## Dataset Information

The Iris dataset contains measurements of iris flowers from three different species:

* Setosa
* Versicolor
* Virginica

### Features

| Column Name       | Description         |
| ----------------- | ------------------- |
| sepal length (cm) | Length of the sepal |
| sepal width (cm)  | Width of the sepal  |
| petal length (cm) | Length of the petal |
| petal width (cm)  | Width of the petal  |
| species           | Flower species      |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Project Workflow

### 1. Import Libraries

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.datasets import load_iris
```

### 2. Load Dataset

```python
iris_data = load_iris()
```

### 3. Create DataFrame

```python
iris = pd.DataFrame(
    iris_data.data,
    columns=iris_data.feature_names
)
```

### 4. Data Exploration

* Viewing dataset
* Checking shape
* Checking missing values
* Checking data types
* Statistical summary

### 5. Data Visualization

Different graphs were created using Matplotlib and Seaborn:

* Scatter plots
* Histograms
* Box plots
* Pair plots
* Count plots
* Pie charts
* Heatmaps

---

## Sample Visualizations

### Scatter Plot

Used to compare relationships between features.

### Histogram

Shows distribution of feature values.

### Box Plot

Used to detect outliers and compare distributions.

### Heatmap

Shows correlation between numerical features.

### Pairplot

Displays pairwise relationships among all features.

---

## Key Insights

* Setosa species is clearly separable from the other two species.
* Petal length and petal width are highly correlated.
* Versicolor and Virginica have overlapping feature distributions.
* No missing values were found in the dataset.


```

---

## Results

The EDA helped in understanding:

* Feature distributions
* Correlation between variables
* Species patterns
* Dataset quality

These insights can later help in building machine learning classification models.

---

## Future Improvements

* Apply machine learning models
* Perform feature scaling
* Compare classification algorithms
* Create advanced visualizations

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook in Jupyter Notebook or Google Colab.

---

## Author

Created by afeera sagheer

---

## License

This project is open-source and available for learning purposes.

