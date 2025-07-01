## 🤝 Iris Classification using K-Nearest Neighbors (Task 6)
This project implements K-Nearest Neighbors (KNN) to classify iris flower species. It includes distance-based prediction, normalization, model evaluation, and K-value tuning. Part of the AI & ML Internship Task - 6

---

## 📁 Dataset
Source: Iris Dataset (Kaggle)

Target: species (Setosa, Versicolor, Virginica)

Features: Sepal length, sepal width, petal length, petal width

---

## 🎯 Objectives
Normalize feature values

Implement KNN classifier from sklearn

Experiment with different values of K

Evaluate using accuracy and confusion matrix

Visualize decision boundaries

---

## 🧰 Tools Used
Tool	Purpose
Pandas	Data manipulation
Scikit-learn	Modeling, scaling, evaluation
Matplotlib	Visualization
Seaborn	Distribution plots, styling

---

## 🔄 Workflow
Data Exploration

Checked class distribution, feature range, and dataset shape

Preprocessing

Used StandardScaler to normalize input features

Split data into training and test sets

Modeling

Trained KNN classifier using KNeighborsClassifier

Compared model accuracy across multiple values of K

Evaluation

Accuracy score

Confusion matrix and classification report

Visualized decision boundaries using 2D feature projection

---

## 📊 Key Visuals
Confusion matrix heatmap

Accuracy vs. K graph

Decision boundary plot for 2 features

---

## 💡 Key Insights
K=3 or K=5 usually gives the best accuracy on Iris dataset.

Normalization is critical for KNN due to distance sensitivity.

Setosa is easily separable; most confusion happens between Versicolor and Virginica.

KNN is simple yet powerful for small, clean datasets like Iris.

---

## 📂 Project Structure

📁 knn-iris-classification
│
├── iris.csv                  # Dataset
├── knn_iris_classifier.ipynb # Notebook
├── README.md                # This file

---

## 🚀 How to Run
Clone this repo

Install dependencies:
pip install pandas scikit-learn matplotlib seaborn

Run:
knn_iris_classifier.ipynb in Jupyter or Colab

