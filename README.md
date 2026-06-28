# 🌸 Flower Prediction Using K-Nearest Neighbors (KNN)

# 📌 Project Overview

This project uses the K-Nearest Neighbors (KNN) Machine Learning algorithm to classify flower species from the famous Iris Dataset.

The model predicts the flower category based on four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The project demonstrates data preprocessing, model training, prediction, performance evaluation, and visualization using Python and Scikit-learn.

---

# 🚀 Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

# 📂 Dataset

The project uses the Iris Dataset provided by Scikit-learn.

```python
from sklearn.datasets import load_iris
```

### Dataset Features

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

### Target Classes

- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

# 🛠️ Project Workflow

## 1. Import Required Libraries

Required libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn are imported.

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
from sklearn.preprocessing import StandardScaler, MinMaxScaler
```

---

## 2. Load Dataset

The Iris Dataset is loaded using Scikit-learn.

---

## 3. Create DataFrame

The dataset is converted into a Pandas DataFrame for easier analysis and visualization.

---

## 4. Data Analysis

The dataset is explored by:

- Viewing feature names
- Checking dataset dimensions
- Displaying sample records
- Examining target classes

---

## 5. Data Preprocessing

Feature scaling techniques are applied:

- StandardScaler
- MinMaxScaler

These methods help normalize the data before model evaluation.

---

## 6. Train-Test Split

The dataset is divided into:

- Training Data (80%)
- Testing Data (20%)

```python
train_test_split(
    x,
    y,
    test_size=0.2,
    random_state=42
)
```

---

## 7. Model Training

A K-Nearest Neighbors classifier is trained using:

```python
KNeighborsClassifier(n_neighbors=5)
```

---

## 8. Prediction

The trained model predicts flower species on unseen test data.

---

## 9. Model Evaluation

Performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

```python
accuracy_score(y_test, y_pred)
confusion_matrix(y_test, y_pred)
classification_report(y_test, y_pred)
```

---

# 📊 Evaluation Metrics

The model performance is measured using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 📈 Visualization

## Heatmap

A heatmap is generated using Seaborn to visualize the confusion matrix and compare actual versus predicted flower classifications.

(Add your heatmap screenshot here)

```md
![Heatmap](images/heatmap.png)
```

---

# ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/Pattammal06/Flower-Prediction-Using-KNN.git
```

### Install Required Libraries

```bash
pip install pandas matplotlib seaborn scikit-learn
```

### Open Notebook

```bash
jupyter notebook
```

### Run the Project

Open:

```text
FlowerPrediction_using_KNN.ipynb
```

Run all cells to view predictions and evaluation results.

---

# 🎯 Project Outcome

The KNN model successfully classifies Iris flower species using flower measurements and achieves high classification performance. The project demonstrates a complete machine learning workflow including preprocessing, training, prediction, evaluation, and visualization.

---

# 🔮 Future Enhancements

- Hyperparameter Tuning
- Cross Validation
- Model Comparison
- GUI Development
- Web Deployment using Streamlit or Flask

---

# 👩‍💻 Author

**Pattammal M**

B.E. Computer Science and Engineering (AIML)
github - https://github.com/Pattammal06
