#  Logistic Regression
A clean, from-scratch implementation and walkthrough of **Logistic Regression** — one of the most fundamental classification algorithms in machine learning.
---

##  Overview

Logistic Regression is a supervised learning algorithm used for **binary classification** tasks. Despite its name, it is a classification algorithm, not a regression one. It estimates the probability that a given input belongs to a particular class using the **sigmoid function**.

This project covers:
- The mathematical intuition behind logistic regression
- Implementation using Python (from scratch and with scikit-learn)
- Model training, evaluation, and visualization

##  Concepts Covered

- Sigmoid / Logistic Function
- Binary Cross-Entropy Loss (Log Loss)
- Gradient Descent Optimization
- Decision Boundary
- Confusion Matrix, Precision, Recall, F1-Score, ROC-AUC

---

##  Project Structure

```
Logistic_Regression/
│
├── Logistic_Regression.ipynb   # Main Jupyter Notebook
├── README.md                   # Project documentation
└── LICENSE                     # MIT License
```

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Programming language |
| NumPy | Numerical computations |
| Pandas | Data manipulation |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | ML model & evaluation metrics |

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/harshad-rahangdale/Logestic_regrestion.git
cd Logestic_regrestion
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 3. Run the Notebook

```bash
jupyter notebook Logistic_Regression.ipynb
```

---

##  Model Evaluation Metrics

The model is evaluated using:

- **Accuracy** — Overall correctness of the model
- **Confusion Matrix** — True/False Positives and Negatives
- **Precision & Recall** — Relevant for imbalanced datasets
- **F1 Score** — Harmonic mean of Precision and Recall
- **ROC-AUC Curve** — Measures discrimination ability of the model

---



##  How Logistic Regression Works

The logistic regression model predicts the probability of the positive class using:

```
P(y=1 | X) = 1 / (1 + e^(-(w·X + b)))
```

Where:
- `w` = weight vector
- `b` = bias
- `e` = Euler's number (~2.718)

If `P ≥ 0.5`, the sample is classified as **class 1**, otherwise **class 0**.

---

##  Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Harshad Rahangdale**
- GitHub: [@harshad-rahangdale](https://github.com/harshad-rahangdale)

---

⭐ If you found this helpful, consider giving the repo a star!
