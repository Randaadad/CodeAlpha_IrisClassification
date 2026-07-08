# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📖 About the Project

This project is part of my Machine Learning journey and was completed as a task for the CodeAlpha Data Science Internship.

The goal of this project is to build a classification model that can identify the species of an Iris flower based on its physical measurements. I used the K-Nearest Neighbors (KNN) algorithm, one of the most popular and beginner-friendly supervised machine learning algorithms.

Throughout this project, I followed the complete machine learning workflow—from understanding and preparing the dataset to training, evaluating, and testing the model.

---

## 🎯 Project Objective

The objective is to classify an Iris flower into one of the following three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The prediction is made using four measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 📊 Dataset

This project uses the famous **Iris Dataset**, which is widely used for learning and practicing machine learning classification.

The dataset contains:

- 150 flower samples
- 4 numerical features
- 3 different species

Before training the model, I explored the dataset to understand its structure, checked for missing values, and removed unnecessary columns.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Project Workflow

### 1. Importing Libraries

Imported all the required Python libraries for data analysis, visualization, preprocessing, and machine learning.

---

### 2. Loading the Dataset

Loaded the dataset using Pandas and displayed its basic information to understand the data.

---

### 3. Data Cleaning

- Removed the unnecessary **Id** column.
- Checked for missing values.
- Verified data types.

---

### 4. Exploratory Data Analysis (EDA)

To better understand the dataset, I created several visualizations, including:

- Species distribution
- Pair Plot
- Correlation Heatmap

These helped me explore the relationships between different flower measurements before training the model.

---

### 5. Data Preprocessing

Before training the model, I prepared the data by:

- Separating the features and target variable.
- Encoding the flower species into numerical values using `LabelEncoder`.
- Splitting the dataset into training and testing sets.
- Scaling the features using `StandardScaler` to improve the performance of the KNN algorithm.

---

### 6. Choosing the Best K Value

Instead of selecting a random value for **K**, I tested multiple values and compared their accuracy.

This allowed me to choose the value that produced the best performance on the test data.

---

### 7. Training the Model

I trained the model using the **K-Nearest Neighbors (KNN)** algorithm.

KNN classifies a flower by looking at the nearest flowers in the training dataset and predicting the most common species among them.

---

### 8. Model Evaluation

To evaluate the model, I used:

- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics helped me understand how well the model performed on unseen data.

---

### 9. Making Predictions

Finally, I tested the trained model by providing new flower measurements and predicting the corresponding species.

---

## 📚 What I Learned

Working on this project helped me strengthen my understanding of:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Label Encoding
- Feature Scaling
- Train/Test Split
- K-Nearest Neighbors (KNN)
- Model evaluation
- Building a complete machine learning workflow using Scikit-learn

---

## 👩‍💻 Author by **Randa Adadoua**
- LinkedIn:https://www.linkedin.com/in/randa-a-68591a410/
