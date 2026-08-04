 Iris Flower Classification using K-Nearest Neighbors (KNN)

 Project Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** classification algorithm using the famous **Iris Dataset** from Scikit-learn. The objective is to classify iris flowers into one of three species based on their physical characteristics.

The project follows a complete Machine Learning workflow, including data loading, preprocessing, train-test splitting, model training, prediction, and evaluation.

---

## Dataset

The project uses the built-in **Iris Dataset** available in the `sklearn.datasets` module.

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes

- Setosa
- Versicolor
- Virginica

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## 📚 Machine Learning Workflow

### 1. Load Dataset

The Iris dataset is loaded using Scikit-learn and converted into Pandas DataFrame and Series objects.

### 2. Data Preprocessing

Feature scaling is performed using **StandardScaler** to normalize all input features.

```python
StandardScaler()
```

### 3. Train-Test Split

The dataset is divided into:

- 80% Training Data
- 20% Testing Data

using

```python
train_test_split(test_size=0.2, random_state=42)
```

### 4. Model Training

A **K-Nearest Neighbors (KNN)** classifier is created with:

- Number of Neighbors (K) = **5**

```python
KNeighborsClassifier(n_neighbors=5)
```

### 5. Prediction

The trained model predicts the species of flowers in the test dataset.

### 6. Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## 📈 Performance Metrics

The project evaluates the classifier using:

- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ F1-Score
- ✅ Confusion Matrix

---

## 📁 Project Structure

```
Iris-KNN-Classification/
│
├── iris_knn.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YourUsername/Iris-KNN-Classification.git
```

Navigate to the project folder

```bash
cd Iris-KNN-Classification
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook

```bash
jupyter notebook
```

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```
numpy
pandas
scikit-learn
jupyter
```

---

## 📷 Sample Output

The notebook displays:

- Accuracy Score
- Confusion Matrix
- Classification Report

You may also add screenshots of the output inside the `screenshots` folder.

---

## 🎯 Future Improvements

- Experiment with different values of K
- Perform hyperparameter tuning
- Visualize decision boundaries
- Compare KNN with other classification algorithms such as:
  - Logistic Regression
  - Decision Tree
  - Support Vector Machine (SVM)
  - Random Forest

---

## 👨‍💻 Author

**Ahmed Yar Khan**

Machine Learning Internship Project  
DecodeLabs Internship

--- Iris Dataset by Ronald A. Fisher
- DecodeLabs Internship Program
