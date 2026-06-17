# 🌸 Iris Flower Classification - Machine Learning & Streamlit Dashboard

## Overview

This project demonstrates machine learning classification using the classic Iris dataset. The model predicts iris flower species based on sepal and petal measurements and provides an interactive Streamlit dashboard for live predictions and model performance visualization.

---

## Features

### Live Prediction

* Input sepal length, sepal width, petal length, and petal width using interactive sliders.
* Instantly predict the iris species:

  * Setosa
  * Versicolor
  * Virginica

### Model Performance Dashboard

* Accuracy Score visualization
* Confusion Matrix for classification analysis
* Feature Importance analysis using permutation importance

### Trained Model

* Random Forest Classifier trained on the Iris dataset
* Model saved as a `.pkl` file for fast loading
* Label Encoder saved for consistent predictions

---

## Technologies Used

* Python 3.x
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Streamlit
* Pickle

---

## Project Structure

```text
iris/
│
├── iris_app.py
├── iris_cleaned.csv
├── iris_model.pkl
├── label_encoder.pkl
├── Iris_Classification.ipynb
├── requirements.txt
└── README.md
```

---

## How It Works

### Data Preprocessing

* Cleaned and prepared the Iris dataset
* Standardized column names
* Encoded species labels for model training

### Model Training

* Trained a Random Forest Classifier
* Evaluated model accuracy
* Generated confusion matrix
* Saved model and encoder using Pickle

### Dashboard

* Loads trained model and label encoder
* Accepts user input through sliders
* Displays live predictions
* Visualizes model performance metrics

---

## Results

* Successfully classified Iris flower species using machine learning.
* Achieved high prediction accuracy using Random Forest Classification.
* Built an interactive Streamlit dashboard for real-time predictions.
* Visualized model performance using confusion matrices and feature importance plots.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/swethasuresh1905/iris_classification.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run iris_app.py
```

---

## Future Enhancements

* Compare multiple classification algorithms
* Deploy dashboard online
* Add advanced visualizations
* Enable batch predictions using CSV uploads

---

## Author

**Swetha Suresh**

B.Tech Artificial Intelligence & Data Science
