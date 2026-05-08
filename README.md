# Iris Flower Classification - Machine Learning Project

This project is a complete Machine Learning pipeline built in Google Colab.
It classifies iris flowers into 3 species:

* Setosa
* Versicolor
* Virginica

using sepal and petal measurements.

![Iris Species Header](https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Iris_dataset_scatterplot.svg/1200px-Iris_dataset_scatterplot.svg.png)

The project now includes a comparison between:

* Random Forest Classifier
* XGBoost Classifier

to evaluate the performance of ensemble machine learning models.

---

# Understanding the Features

The dataset relies on measuring the:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

of iris flowers.

---

# Features

✅ Data Loading
✅ Exploratory Data Analysis (EDA)
✅ Data Visualization
✅ Pairplots
✅ Train/Test Split
✅ Random Forest Classifier
✅ XGBoost Classifier
✅ Accuracy Evaluation
✅ Confusion Matrix
✅ Classification Report
✅ Feature Importance Visualization
✅ Model Comparison Graph
✅ Save & Load Models (`.pkl`)

---

# Tech Stack

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-Learn
* XGBoost
* Google Colab / Jupyter Notebook

---

# Dataset

The Iris dataset is a built-in dataset available in Seaborn and Scikit-Learn.

It contains:

* 150 flower samples
* 3 flower species
* 4 numerical features

---

# Model Accuracy

Both Random Forest and XGBoost achieved very high accuracy (~95–100%).

In the latest notebook:

```text
iris_model_comparison_randomforest_and_XGboost.ipynb
```

both models achieved almost the same accuracy.

### Why is the accuracy similar?

The Iris dataset is:

* very small
* clean
* highly structured
* easy to classify

Because of this, even simpler ML models can achieve near-perfect performance.

XGBoost usually performs much better on:

* larger datasets
* complex datasets
* noisy real-world data

The purpose of this comparison is to understand:

* ensemble learning
* boosting vs bagging
* model evaluation
* practical ML workflows

---

# Visualizations Included

📊 Pairplots
📊 Accuracy Comparison Graph
📊 Feature Importance Graph
📊 Confusion Matrix

---

# How to Run the Notebook

1. Open the notebook in Google Colab
2. Run all cells
3. Explore visualizations
4. Compare Random Forest and XGBoost outputs
5. Experiment with hyperparameters

---

# Files Included

### Main Beginner Notebook

```text
iris_ml_project.ipynb
```

### Advanced Comparison Notebook

```text
iris_model_comparison_randomforest_and_XGboost.ipynb
```

---

# Future Improvements

* Streamlit Web App
* Hyperparameter Tuning
* Model Deployment
* Larger Real-World Dataset
* Additional ML Algorithms Comparison

---

# Author

## Pulkit
