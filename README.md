# 🏡 Deep Learning for Real Estate Price Prediction with TensorFlow

This project demonstrates how to build an **Artificial Neural Network (ANN)** using **TensorFlow** and **Keras** to predict real estate prices based on property characteristics. The notebook follows a complete supervised deep learning workflow, including data exploration, preprocessing, feature scaling, model development, training, evaluation, and price prediction.

The project highlights how deep learning can be applied to **tabular real estate data** to estimate property values from numerical features.

---

## 📌 Features

- Real estate price prediction
- Regression using Artificial Neural Networks (ANN)
- Data preprocessing
- Feature scaling with MinMaxScaler
- Exploratory Data Analysis (EDA)
- Data visualization
- Train/Test split
- TensorFlow/Keras Sequential model
- Multi-layer fully connected neural network
- Regression model evaluation
- Performance metrics visualization

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📚 Libraries

```python
tensorflow
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyterthemes
```

---

## 📖 Project Overview

Accurately estimating property values is an important task in the real estate industry. Machine learning and deep learning models can learn complex relationships between property characteristics and market prices, providing automated price predictions.

In this notebook, a **feed-forward Artificial Neural Network (ANN)** is trained to perform a **regression task**, where the output is a continuous house price rather than a class label.

---

## 🏠 Dataset

The notebook works with structured real estate data containing numerical property attributes used to estimate house prices.

Typical features may include:

- Property size
- Number of bedrooms
- Number of bathrooms
- Location-related attributes
- Additional numerical housing characteristics

**Target Variable**

- Property Sale Price

---

## 🔍 Exploratory Data Analysis

Before training the neural network, the notebook performs exploratory data analysis to better understand the dataset.

The analysis includes:

- Dataset inspection
- Feature distributions
- Correlation analysis
- Statistical summaries
- Visual exploration using Seaborn and Matplotlib

---

## ⚙️ Data Preprocessing

The notebook prepares the data by:

- Scaling numerical features using **MinMaxScaler**
- Scaling the target variable
- Splitting the dataset into training and testing sets
- Preparing the data for neural network training

Feature scaling is particularly important for deep learning models because it improves convergence during optimization.

---

## 🧠 Deep Learning Model

The project uses a **TensorFlow/Keras Sequential** model composed entirely of fully connected (`Dense`) layers.

The notebook demonstrates multiple ANN architectures, including:

### Model 1

- Dense (100 neurons, ReLU)
- Dense (100 neurons, ReLU)
- Dense (100 neurons, ReLU)
- Dense (200 neurons, ReLU)
- Output Layer (1 neuron, Linear activation)

### Model 2

- Dense (10 neurons, ReLU)
- Dense (10 neurons, ReLU)
- Output Layer (1 neuron, Linear activation)

Both models are designed for **regression**, predicting continuous real estate prices.

---

## 📈 Model Evaluation

The notebook evaluates model performance using several regression metrics:

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**
- **Adjusted R² Score**

These metrics provide a comprehensive assessment of prediction accuracy.

---

## ⚙️ Deep Learning Workflow

The notebook follows these steps:

1. Load the real estate dataset
2. Explore and visualize the data
3. Scale features using MinMaxScaler
4. Split the dataset into training and testing sets
5. Build a TensorFlow/Keras ANN
6. Train the neural network
7. Generate predictions
8. Evaluate regression performance

---

## 🚀 Getting Started


### Install dependencies

```bash
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn jupyterthemes
```

Or install them using a requirements file:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
DeepLearningforRealEstatePricePrediction.ipynb
```

Run the notebook cells sequentially to reproduce the complete deep learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Build regression models using TensorFlow and Keras
- Create Artificial Neural Networks for tabular data
- Scale features using MinMaxScaler
- Perform exploratory data analysis
- Train deep learning models for regression
- Evaluate regression performance using multiple metrics
- Apply deep learning techniques to real estate valuation
