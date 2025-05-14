# Grupo03_Practica2

# 🌱 Seed Clustering (Unsupervised Learning)

This repository contains the full development of a **Machine Learning** project, focused on applying **unsupervised clustering techniques** to a dataset of seeds. Algorithms such as **K-Means**, **Hierarchical Clustering**, and **DBSCAN** were used, along with **PCA** for dimensionality reduction and result visualization.

---

## 📁 Repository Structure

- `notebook.ipynb`: Main notebook with all the development, analysis, visualizations, and conclusions.
- `data/semillas.csv`: Original seed dataset.
- `README.md`: This file.
- `requirements.txt`: Necessary packages to execute the notebook.

---

## 🧠 Objectives of the Practice

- Apply unsupervised clustering techniques to detect natural groupings in the data.
- Evaluate the quality of the generated clusters using visual analysis (PCA), silhouette scores, and comparison with the true classes.
- Interpret the results using statistical analysis (boxplots).
- Compare methods and make a reasoned decision on which one best represents the data structure.

---

## 🧪 Applied Algorithms

- 🔹 **K-Means**
- 🔹 **Agglomerative Clustering**
- 🔹 **DBSCAN**
- 🔹 **PCA** (for dimensionality reduction)

---

## 📊 Conclusions

- **K-Means with 3 clusters** was the most effective method to capture the underlying structure of the data.
- Hierarchical Clustering also provided solid results and facilitated interpretation via dendrograms.
- DBSCAN was useful for detecting outliers but showed greater sensitivity to parameter tuning (`eps` and `min_samples`).

---

## 👨‍💻 Author

- Name: Carlos Bravo Garrán
- University: Universidad Carlos III de Madrid
- Course: Machine Learning
- Year: 2025
