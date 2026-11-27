# 🚢 First Machine Learning Classifier – Titanic Survival Prediction

## 📌 Project Overview
This project focuses on building a Machine Learning classification model to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, passenger class, and ticket fare.

A **Decision Tree Classifier** from Scikit-Learn is used to train the model and evaluate its performance on unseen data.

## 🎯 Project Objectives
- Understand the fundamentals of supervised machine learning.
- Load and preprocess the Titanic dataset.
- Split data into training and testing sets.
- Build a Decision Tree classification model.
- Evaluate model performance using accuracy and a confusion matrix.
- Understand baseline accuracy and overfitting.
- Identify important features influencing predictions.

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## 📊 Dataset
The Titanic dataset is loaded using Seaborn.

The following features are selected:

| Feature | Description |
|---|---|
| survived | Survival status (Target) |
| pclass | Passenger class |
| sex | Passenger gender |
| age | Passenger age |
| fare | Ticket fare |

## ⚙️ Project Workflow

1. **Data Collection:** Load the Titanic dataset.
2. **Data Preprocessing:** Handle missing values and convert gender into numerical values.
3. **Feature Selection:** Select relevant input features and define the target variable.
4. **Train-Test Split:** Divide the dataset into 80% training and 20% testing data.
5. **Baseline Calculation:** Calculate baseline accuracy for comparison.
6. **Model Training:** Train a Decision Tree Classifier.
7. **Model Evaluation:** Evaluate predictions using accuracy and a confusion matrix.
8. **Feature Importance:** Identify the most influential features.
9. **Overfitting Analysis:** Compare training and testing accuracy at different tree depths.

## 🤖 Machine Learning Algorithm

**Decision Tree Classifier**

A Decision Tree is a supervised machine learning algorithm used for classification and regression tasks. It makes predictions by splitting data into smaller branches based on feature values.

## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Baseline Accuracy
- Training Accuracy
- Testing Accuracy
- Feature Importance

## 📉 Visualizations
The project includes:
- Confusion Matrix Heatmap
- Feature Importance Graph
- Training vs Testing Accuracy Graph

## 💻 Installation and Execution

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Open the Jupyter Notebook and run the cells sequentially.

## ⚠️ Limitations
- The model uses only four selected input features.
- Rows containing missing values are removed.
- The dataset is relatively small.
- Predictions may not represent every passenger accurately.
- Model performance depends on the selected features and tree depth.

## 🎓 Learning Outcomes
Through this project, I learned:
- Fundamentals of supervised machine learning.
- Data preprocessing and feature selection.
- Model training and testing.
- Classification evaluation techniques.
- Baseline comparison.
- Overfitting and model performance analysis.

## 👩‍💻 Project Information

**Project:** Project 04 – First Machine Learning Classifier  
**Domain:** Data Science & Artificial Intelligence  
**Dataset:** Titanic  
**Algorithm:** Decision Tree Classifier  
**Platform:** InternCircle

---

⭐ This project was completed as part of the InternCircle Data Science & AI learning program.
