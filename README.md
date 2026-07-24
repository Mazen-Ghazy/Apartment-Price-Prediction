# Apartment Price Prediction

## Overview

This project predicts apartment prices using Machine Learning techniques. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## Dataset

The dataset contains different apartment features such as:

- Area
- Bedrooms
- Bathrooms
- Furnishing Status
- Parking
- Air Conditioning
- Location Features
- Price (Target)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Data Preprocessing

The following preprocessing steps were applied:

- Handling missing values
- Encoding categorical features
- Feature scaling using Normalization
- Train/Test Split

---

## Exploratory Data Analysis (EDA)

Performed several visualizations including:

- Histograms
- Pie Charts
- Correlation Heatmap
- Distribution Plots

---

## Model

Regression model for predicting apartment prices.

---

## Results

### Before Normalization

Model Loss:

```
5.676867
```

### After Normalization

Model Loss:

```
CURRENT_LOSS
```

The normalization process significantly improved the model performance by reducing the training loss.

---

## Evaluation Metrics

- Loss
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# Project Structure

```
Apartment-Price-Prediction/
│
├── Apartment_Price_Prediction.ipynb
├── Housing.csv
├── README.md
├── requirements.txt
└── images/
```

---

# Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Apartment-Price-Prediction.git
```

Move into the project folder

```bash
cd Apartment-Price-Prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

---

# How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Apartment-Price-Prediction.git
```

### 2. Open the project folder

```bash
cd Apartment-Price-Prediction
```

### 3. Install all required packages

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

or

Open the notebook directly in Google Colab.

### 5. Open

```
Apartment_Price_Prediction.ipynb
```

### 6. Upload the dataset

Place the dataset file in the project folder or upload it to Google Colab.

### 7. Run the notebook

Run all cells from top to bottom.

The notebook will automatically:

- Load the dataset
- Clean the data
- Encode categorical variables
- Normalize the features
- Train the model
- Evaluate the model
- Display graphs and final metrics

---

## Author

Developed by Mazen Ghazy