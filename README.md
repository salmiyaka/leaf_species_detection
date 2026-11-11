
#  Leaf Species Detection

## 📌 Project Overview

This project demonstrates a Machine Learning approach to classifying Iris flower species using a Decision Tree Classifier.

The model predicts the species of an Iris flower (Setosa, Versicolor, or Virginica) based on four measurements:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 🎯 Project Objectives

- Load and explore the Iris dataset.
- Understand data distribution using visualization.
- Train a Decision Tree classification model.
- Evaluate model performance using accuracy.
- Understand the effect of tree depth on prediction accuracy.
- Predict the species of a new flower.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🤖 Machine Learning Algorithm

**Decision Tree Classifier**

The model is trained using 80% of the dataset and tested using the remaining 20%.

The project also compares different tree depths to understand model performance and overfitting.

## 📂 Project Structure

```text
leaf_species_detection/
│
├── 01_leaf_species_detection.ipynb
├── README.md
└── data/
    └── iris.csv
```

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/salmiyaka/leaf_species_detection.git
```

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

3. Make sure the Iris dataset is available at the expected `data/iris.csv` path.

4. Open the notebook:

```bash
jupyter notebook
```

5. Run `01_leaf_species_detection.ipynb`.

## 📊 Expected Output

- Iris species distribution.
- Data visualization.
- Decision Tree model accuracy.
- Accuracy comparison for different tree depths.
- Prediction for a new flower.

## 👨‍🏫 Credits

Original project provided by our instructor for educational purposes and learning.

## 📚 Learning Outcome

This project helped explore the fundamentals of Machine Learning, data preprocessing, classification, model evaluation, and prediction.
