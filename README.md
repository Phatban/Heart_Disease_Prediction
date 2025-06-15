# ❤️ Heart Disease Prediction using Machine Learning

This project uses the **Cleveland Heart Disease Dataset** to predict the presence of heart disease using various machine learning algorithms. It includes data preprocessing, visualization, model training, evaluation, and ensemble learning through stacking.

## 📂 Project Structure

- `heart_disease_prediction.ipynb`: Main Jupyter notebook implementing the full pipeline.
- `cleveland.csv`: Raw dataset used for training and testing.

## 🔍 Dataset Overview

The dataset consists of 303 samples with 14 features related to heart health, such as:
- Age, Sex, Chest pain type, Resting blood pressure, Serum cholesterol
- Fasting blood sugar, Resting ECG, Max heart rate achieved, Exercise-induced angina
- ST depression, Slope, Number of vessels, Thalassemia, and Target (0/1)

## 🔧 Implementation Outline

### 1. Data Loading
Reads the dataset and assigns proper column names.

### 2. Exploratory Data Analysis
Visualizes distributions and relationships between age, sex, and disease status.

### 3. Data Preprocessing
Handles missing values and applies feature scaling.

### 4. Model Training & Evaluation

#### 4.1 Individual Models
Trains and evaluates the following classifiers:
- K-Nearest Neighbors
- Support Vector Machine (RBF kernel)
- Naive Bayes
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost

#### 4.2 Stacking Ensemble Model
Builds a stacked model using multiple base learners and a logistic regression meta-model.

### 5. Visualization
Compares the accuracy of all models using a horizontal bar chart.

## 📈 How to Run

1. Ensure `cleveland.csv` is present in the same directory.
2. Open `heart_disease_prediction.ipynb` with Jupyter Notebook or VSCode.
3. Run all cells sequentially.

## 🧰 Requirements

- Python ≥ 3.8  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`

Install requirements:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## 🏁 Results

The notebook reports training and testing accuracy for each model, helping to compare performance and select the best approach for heart disease prediction.
