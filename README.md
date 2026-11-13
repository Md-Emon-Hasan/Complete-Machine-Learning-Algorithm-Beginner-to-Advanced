<div align="center">

# Complete Machine Learning Algorithms — Beginner to Advanced

**A hands-on, notebook-driven path through machine learning: from statistics and data handling to feature engineering, classical algorithms, and from-scratch implementations.**

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)](https://scipy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)](https://seaborn.pydata.org/)

<br>

<img src="./Machine%20Learning.png" alt="Complete Machine Learning Algorithms — Beginner to Advanced" width="100%">

</div>

---

## Table of Contents

- [Overview](#overview)
- [Highlights](#highlights)
- [Repository Structure](#repository-structure)
- [Learning Tracks](#learning-tracks)
  - [Track 1 — ML Fundamentals with scikit-learn (W3Schools)](#track-1--ml-fundamentals-with-scikit-learn-w3schools)
  - [Track 2 — Core ML Algorithms (WsCube Tech)](#track-2--core-ml-algorithms-wscube-tech)
  - [Track 3 — 100 Days of Machine Learning (CampusX)](#track-3--100-days-of-machine-learning-campusx)
- [Algorithms and Techniques Covered](#algorithms-and-techniques-covered)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Suggested Learning Path](#suggested-learning-path)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)
- [Connect With Me](#-connect-with-me)

---

## Overview

This repository is a structured collection of Jupyter notebooks that documents a complete machine-learning learning journey — starting with the statistics and data-handling basics and progressing through feature engineering, regression, classification, clustering, model evaluation, and optimization.

It brings together three complementary learning tracks in one place. Each notebook pairs short explanations with runnable code, visualizations, and the datasets needed to reproduce the results. Several algorithms are also **implemented from scratch** with NumPy, so the math behind the library calls is visible.

| | |
|---|---|
| **Notebooks** | 59 |
| **Datasets included** | 40+ CSV / TSV / JSON files |
| **Learning tracks** | 3 |
| **Level** | Beginner → Advanced |

## Highlights

- **End-to-end coverage** — data loading, EDA, preprocessing, feature engineering, modelling, and evaluation.
- **From-scratch implementations** — multiple linear regression, batch / stochastic / mini-batch gradient descent, ridge regression, and the perceptron trick.
- **Visual intuition** — animated and 3D gradient-descent visualizations.
- **Self-contained** — datasets live next to the notebooks that use them; no external downloads needed.
- **Production habits** — `ColumnTransformer` and `Pipeline` workflows, with side-by-side "with pipeline vs. without pipeline" comparisons.

## Repository Structure

```text
Complete-Machine-Learning-Algorithm-Beginner-to-Advanced/
├── Machine Learning From W3Schools/
│   ├── machine learning with scikit-learn.ipynb   # Statistics → models → evaluation
│   ├── data.csv, data1.csv                        # Datasets
│   └── test.py
├── Machine Learning From WsCube Tech/
│   ├── Machine Learning Algorithm.ipynb           # 9 core algorithms in one notebook
│   └── *.csv                                      # Iris, income, insurance, salaries, ...
├── 100-Days-of-Machine-Learning-CampusX/
│   ├── 15 Working with CSV files/
│   ├── ...                                        # 38 numbered lesson folders
│   ├── 58 Logistic Regression/
│   └── README.md                                  # Detailed lesson-by-lesson index
├── LICENSE
└── README.md
```

## Learning Tracks

### Track 1 — ML Fundamentals with scikit-learn (W3Schools)

📂 [`Machine Learning From W3Schools/`](./Machine%20Learning%20From%20W3Schools/)

A single, progressive notebook that builds up from descriptive statistics to full models.

| Area | Topics |
|---|---|
| **Statistics** | Mean, median, mode · standard deviation and variance · percentiles |
| **Data distributions** | Uniform and normal distributions · histograms · scatter plots |
| **Regression** | Linear regression · polynomial regression · multiple regression · R² · feature scaling |
| **Classification** | Decision trees · logistic regression · K-nearest neighbours |
| **Clustering** | K-means · hierarchical (agglomerative) clustering with dendrograms |
| **Ensembles** | Bootstrap aggregation (bagging) |
| **Evaluation** | Train/test split · confusion matrix · accuracy, precision, recall, specificity, F-score · AUC–ROC |
| **Model selection** | Grid search · K-Fold, Stratified K-Fold, Leave-One-Out, Leave-P-Out, Shuffle Split |
| **Preprocessing** | Categorical data and one-hot (dummy) encoding |

### Track 2 — Core ML Algorithms (WsCube Tech)

📂 [`Machine Learning From WsCube Tech/`](./Machine%20Learning%20From%20WsCube%20Tech/)

Nine essential algorithms, each applied to a real dataset.

| # | Algorithm | Type |
|---|---|---|
| 1 | Linear Regression (single and multiple variables) | Regression |
| 2 | Polynomial Regression | Regression |
| 3 | Logistic Regression (binary and multiclass) | Classification |
| 4 | Decision Tree | Classification |
| 5 | Random Forest | Ensemble |
| 6 | Naive Bayes Classifier | Classification |
| 7 | Support Vector Machine (SVM) | Classification |
| 8 | K-Nearest Neighbours (KNN) | Classification |
| 9 | K-Means Clustering | Clustering |

### Track 3 — 100 Days of Machine Learning (CampusX)

📂 [`100-Days-of-Machine-Learning-CampusX/`](./100-Days-of-Machine-Learning-CampusX/) · 57 notebooks across 38 lessons

The deepest track, following the CampusX curriculum day by day. See the [track README](./100-Days-of-Machine-Learning-CampusX/README.md) for links to every lesson.

| Stage | Days | Topics |
|---|---|---|
| **Data access and EDA** | 15 – 22 | CSV, JSON, and SQL data · understanding your data · univariate, bivariate, and multivariate analysis · Pandas Profiling |
| **Feature scaling and encoding** | 24 – 27 | Standardization · normalization · ordinal, label, and one-hot encoding |
| **Pipelines and transformers** | 28 – 32 | `ColumnTransformer` · ML pipelines · function and power transformers (Box–Cox, Yeo–Johnson) · binning and binarization |
| **Feature engineering** | 33 – 34, 45 | Mixed variables · date and time features · feature construction and splitting |
| **Missing data** | 35 – 40 | Complete-case analysis · simple imputation · missing indicators · random-sample imputation · KNN imputer · MICE |
| **Outliers** | 42 – 44 | Z-score, IQR, and percentile methods |
| **Dimensionality reduction** | 47 | Principal Component Analysis (PCA), step by step and applied |
| **Regression** | 48 – 53 | Simple, multiple, and polynomial regression · regression metrics (MAE, MSE, RMSE, R², adjusted R²) |
| **Optimization** | 51 – 52 | Gradient descent from scratch · batch, stochastic, and mini-batch variants · animations |
| **Regularization** | 55 – 57 | Ridge (L2) · Lasso (L1) · Elastic Net |
| **Classification** | 58 | Logistic regression · perceptron trick · sigmoid · gradient descent |

## Algorithms and Techniques Covered

| Category | Covered |
|---|---|
| **Regression** | Simple Linear · Multiple Linear · Polynomial · Ridge · Lasso · Elastic Net |
| **Classification** | Logistic Regression · Decision Tree · Naive Bayes · SVM · KNN · Perceptron |
| **Ensemble** | Random Forest · Bagging |
| **Clustering** | K-Means · Hierarchical Clustering |
| **Dimensionality reduction** | PCA |
| **Optimization** | Batch GD · Stochastic GD · Mini-Batch GD |
| **Preprocessing** | Scaling · Encoding · Imputation · Outlier handling · Transformations · Binning |
| **Evaluation** | R² · MAE / MSE / RMSE · Confusion Matrix · Precision / Recall / F-score · AUC–ROC · Cross-validation · Grid Search |

## Tech Stack

| Purpose | Tools |
|---|---|
| **Language** | Python 3.9+ |
| **Environment** | Jupyter Notebook / JupyterLab / VS Code |
| **Data handling** | NumPy · pandas |
| **Machine learning** | scikit-learn · SciPy |
| **Visualization** | Matplotlib · Seaborn |
| **Profiling** | ydata-profiling (Pandas Profiling) |

## Getting Started

### Prerequisites

- Python 3.9 or newer
- Basic familiarity with Python syntax

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Md-Emon-Hasan/Complete-Machine-Learning-Algorithm-Beginner-to-Advanced.git
   cd Complete-Machine-Learning-Algorithm-Beginner-to-Advanced
   ```

2. **Create and activate a virtual environment** (recommended)

   ```bash
   python -m venv .venv

   # Windows
   .venv\Scripts\activate

   # macOS / Linux
   source .venv/bin/activate
   ```

3. **Install the dependencies**

   ```bash
   pip install numpy pandas scipy scikit-learn matplotlib seaborn jupyter ydata-profiling
   ```

4. **Launch Jupyter**

   ```bash
   jupyter notebook
   ```

   Open any notebook and run the cells from top to bottom. Datasets are loaded with relative paths, so start each notebook from its own folder.

## Suggested Learning Path

New to machine learning? Follow the tracks in this order:

1. **W3Schools track** — build the statistical foundation and get a first look at every major concept.
2. **WsCube Tech track** — apply the nine core algorithms to real datasets.
3. **CampusX track** — go deep on data preparation, feature engineering, and the math behind the models, lesson by lesson.

## Roadmap

This repository grows as new topics are studied. Planned additions:

- [ ] Classification metrics and the remaining logistic-regression lessons
- [ ] Decision trees, ensemble learning, bagging, and boosting (AdaBoost, Gradient Boosting, XGBoost)
- [ ] SVM, KNN, and Naive Bayes in depth
- [ ] Clustering (K-Means, DBSCAN, hierarchical) in depth
- [ ] End-to-end projects with deployment

## Contributing

Contributions, corrections, and suggestions are welcome.

1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-improvement`
3. Commit your changes: `git commit -m "Add your improvement"`
4. Push the branch: `git push origin feature/your-improvement`
5. Open a pull request.

Found a bug or an unclear explanation? Please [open an issue](https://github.com/Md-Emon-Hasan/Complete-Machine-Learning-Algorithm-Beginner-to-Advanced/issues).

## Acknowledgements

These notebooks are personal study notes built while following these excellent free resources:

- [CampusX — 100 Days of Machine Learning](https://www.youtube.com/@campusx-official)
- [W3Schools — Python Machine Learning](https://www.w3schools.com/python/python_ml_getting_started.asp)
- [WsCube Tech](https://www.youtube.com/@wscubetech)

## License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.

---

## 📬 Connect With Me

- 🌐 **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- 💻 **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- 💼 **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- 🤗 **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- 📧 **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- 📱 **WhatsApp:** [+8801834363533](https://wa.me/8801834363533)

<div align="center">

**If this repository helps you, please consider giving it a ⭐**

Made with ❤️ by [Md Emon Hasan](https://github.com/Md-Emon-Hasan)

</div>
