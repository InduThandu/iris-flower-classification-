# Iris Flower Classification using Streamlit

## Project Overview

This project uses **Machine Learning** to classify Iris flowers into three species:

* Setosa
* Versicolor
* Virginica

A **Random Forest Classifier** is trained using the Iris dataset, and **Streamlit** is used to create a simple web application for prediction.

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Joblib
* Streamlit

## Project Structure

```text
iris-classification/
│
├── app.py
├── train.py
├── requirements.txt
└── iris_model.pkl
```

## Dataset

The project uses the built-in **Iris dataset** from Scikit-learn.

It contains four input features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target classes are:

1. Setosa
2. Versicolor
3. Virginica

## Machine Learning Model

The project uses:

**Random Forest Classifier**

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

The trained model is saved as:

```text
iris_model.pkl
```

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Train the Model

Run:

```bash
python train.py
```

This will train the model and create:

```text
iris_model.pkl
```

## Run the Streamlit Application

Start the application using:

```bash
streamlit run app.py
```

The application allows the user to enter the four flower measurements and predicts the Iris species.

## Input Features

| Feature      | Unit |
| ------------ | ---- |
| Sepal Length | cm   |
| Sepal Width  | cm   |
| Petal Length | cm   |
| Petal Width  | cm   |

## Output

The application predicts one of the following:

```text
Setosa
Versicolor
Virginica
```

## Objective

The main objective of this project is to demonstrate how a **Machine Learning classification model can be trained and deployed as an interactive web application using Streamlit**.

## Author

BTech CSE (AI & ML) Student
