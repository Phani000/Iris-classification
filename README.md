# 🌸 Iris Species Classification

This project demonstrates a simple machine learning pipeline to classify iris flowers into three species (*Setosa*, *Versicolor*, *Virginica*) using the famous [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris).

## 📊 Dataset

The Iris dataset consists of 150 samples with 4 features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Each sample belongs to one of the following species:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

## 📦 Project Structure

```
iris-classification/
├── __pycache__/ 
├── static/ an image for website
├── app.py
├── model.pkl
├── iris.ipynb 
├── README.md # Project overview
└── templates/├── index.html/
              ├── layout.html/
              └── predict.html/
```

## 🚀 Quickstart

### Clone and Install

```bash
git clone https://github.com/Phani000/Iris-classification.git
cd iris-classification
```
### 🛠 Requirements
```
Flask
Numpy
Pandas
Matplotlib
Seaborn
Scikit-Learn
Joblib
```


## 🧪 How It Works

1. Load the dataset
2. Perform exploratory data analysis (EDA)
3. Split the data into training and testing sets
4. Train a classification model (Logistic Regression, SVM, etc.)
5. Evaluate model accuracy
6. Save and load the trained model for inference
