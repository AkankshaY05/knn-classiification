# knn-classiification
Load Dataset

We use the Iris dataset directly from GitHub:

https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv

2️⃣ Preprocess & Normalize Data

Select features

Convert species labels to numbers

Normalize using StandardScaler

3️⃣ Train KNN Model

Try different values of K

Choose K based on accuracy

4️⃣ Evaluate Model

We calculate:

Accuracy

Confusion Matrix

5️⃣ Visualize Decision Boundary

Using only two features, we:

Train KNN

Build a meshgrid

Predict classes

Plot decision boundaries using contourf

📊 Output

Accuracy scores for multiple values of K

Confusion matrix heatmap

A full decision boundary plot showing how KNN separates classes

📦 Requirements

Install required libraries:

pip install numpy pandas matplotlib seaborn scikit-learn

📁 Files

knn_model.py → main code

README.md → documentation

🧠 Concepts Covered

KNN algorithm

Standardization

Confusion matrix

Decision boundary visualization

Effect of changing K
