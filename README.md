# SVM-Based Data Classification and Dimensionality Reduction

## 📌 Project Overview

This project explores data classification and dimensionality reduction techniques using Support Vector Machines (SVM), t-SNE, MDS, and LDA. The main objective is to analyze different datasets, reduce their dimensionality for visualization, and classify them using SVM models with various kernels.

## 🚀 Features

**Data Preprocessing:** Loading, cleaning, and normalizing datasets.

**Dimensionality Reduction:**

- t-SNE (t-Distributed Stochastic Neighbor Embedding) for non-linear visualization.

- MDS (Multidimensional Scaling) for preserving distances.

- LDA (Linear Discriminant Analysis) for supervised dimensionality reduction.

- Classification with SVM:
  - Linear SVM for evaluating separability.

  - SVM with RBF kernel for improved classification.

  - Comparison with polynomial kernel SVM.

**Decision Boundary Visualization:** Displaying decision regions for classification tasks.

## 🛠️ Installation & Setup

1️⃣ Clone the repository

```bash
git clone https://github.com/YourUsername/SVM-Dimensionality-Reduction.git
cd SVM-Dimensionality-Reduction
```

2️⃣ Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3️⃣ Install dependencies
```
pip install -r requirements.txt
```
4️⃣ Run the scripts

Execute the main scripts individually or open the Jupyter notebooks for interactive analysis:
```python
python src/data_preprocessing.py
python src/dimensionality_reduction.py
python src/svm_classification.py
python src/decision_boundary.py
```
Alternatively, run Jupyter Notebook:
```
jupyter notebook
```
## 📊 Results & Visualizations

- **Dimensionality Reduction:** Various transformation techniques applied to visualize dataset structures.

- **SVM Classification:** Performance evaluation of different SVM kernels.

- **Decision Boundaries:** Clear representation of classification decisions.
