# Red Wine Quality Prediction

This project focuses on analyzing and predicting the quality of red wine using various machine learning models. The dataset used in this project contains physicochemical properties of red wine samples and their corresponding quality ratings.

## 📁 Project Structure

- `red_wine.ipynb`: Main Jupyter notebook containing data preprocessing, EDA (Exploratory Data Analysis), and model training.
- `wineQualityReds.csv`: Dataset containing 1599 red wine samples with 11 physicochemical attributes and a quality score.

## 📊 Dataset Description

The dataset (`wineQualityReds.csv`) includes the following columns:

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (target variable: score between 0–10)

## 🔍 Features

- Data cleaning and preprocessing
- Visualization and correlation analysis
- Model training using algorithms like:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- Model evaluation using metrics like accuracy, confusion matrix, and classification report

## 📈 Results

The best performing model(s) are compared based on accuracy and other evaluation metrics to determine the most effective method for predicting wine quality.

## 💡 Requirements

To run this project, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 How to Run

1. Clone the repository or download the notebook and dataset.
2. Ensure the dataset file `wineQualityReds.csv` is in the same directory as the notebook.
3. Open `red_wine.ipynb` in Jupyter Notebook or any compatible environment.
4. Run all cells to perform the analysis and see the results.

## 📚 References

- UCI Machine Learning Repository: [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
