# Internship-task6
KNN Classification using Iris.csv
# 🌸 Task 6 - K-Nearest Neighbors (KNN) Classification

This task is part of the AI & ML Internship and focuses on implementing the **K-Nearest Neighbors (KNN)** algorithm using the **Iris dataset**.

---

## ✅ Objective

To implement the KNN algorithm for classification and understand:
- Instance-based learning
- Importance of feature normalization
- K value selection
- Role of distance metrics

---

## 📁 Dataset Used

- **Name:** Iris Dataset
- **File:** `Iris.csv`
- **Target Column:** `Species`

---

## 🛠 Tools and Libraries

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib

---

## 🔍 What I Did

1. Loaded and explored the **Iris.csv** dataset.
2. Removed unnecessary columns like `Id`.
3. Label Encoded the `Species` column.
4. Normalized the features using **StandardScaler**.
5. Split the dataset into training and testing sets.
6. Trained the **KNeighborsClassifier** with different K values.
7. Evaluated the model using **Accuracy** and **Confusion Matrix**.
8. Visualized the **Decision Boundary** using first two features.

---

## 📊 Output

- Best accuracy achieved at K = 3 to 5
- Clear visualization of decision regions
- Confusion Matrix showing perfect or near-perfect predictions

---

## 🔁 Experiments

I tested the model with K values from 1 to 10:

| K Value | Accuracy |
|---------|----------|
| 1       | 1.00     |
| 2       | 0.97     |
| 3       | 1.00     |
| ...     | ...      |

---

## 📈 Visualization

The decision boundary was plotted using the first two features for a better understanding of how KNN classifies data based on proximity.

![Decision Boundary Example](path_to_image_if_any)

---

## 📦 Files Included

- `Iris.csv` – Dataset
- `knn_task6.ipynb` – Notebook with full code
- `README.md` – This file

---

## 🧠 Concepts Learned

- KNN is a lazy learner and stores training data.
- Feature scaling is essential in distance-based algorithms.
- Confusion matrix gives deeper performance insights than accuracy alone.
- KNN is simple but powerful for small datasets.

---

## 🔗 Submission

[🔗 Internship Submission Link](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

## 🙌 Thanks!

This task helped me practically understand how classification works using distance-based logic in machine learning.

