# 100 Days of Machine Learning — CampusX

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB.svg?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Track-Machine%20Learning-6A5ACD)
![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Status](https://img.shields.io/badge/Status-Learning%20in%20Progress-orange)

A hands-on collection of Jupyter notebooks documenting my journey through **CampusX's 100 Days of Machine Learning**. The repository currently includes **notebooks** covering data handling, exploratory data analysis, feature engineering, preprocessing, and foundational machine-learning algorithms.

The notebooks combine explanations, experiments, visualizations, and implementations—including selected algorithms built from scratch. This is a learning repository that grows as topics are studied; the numbered folders reflect the lessons currently included.

## Contents

- [Learning roadmap](#learning-roadmap)
- [Repository structure](#repository-structure)
- [Getting started](#getting-started)
- [Tools and libraries](#tools-and-libraries)
- [How to use the notebooks](#how-to-use-the-notebooks)
- [Learning goals](#learning-goals)
- [Contributing](#contributing)
- [License](#license)
- [Connect with me](#connect-with-me)

## Learning roadmap

Each linked item opens the corresponding lesson folder. Notebooks inside a folder may cover multiple exercises or variations on that topic.

### Data access and exploratory analysis

| Lesson | Topics |
|---|---|
| [15 · Working with CSV files](./15%20Working%20with%20CSV%20files/) | Reading, exploring, and working with CSV data using pandas. |
| [16 · Working with JSON and SQL](./16%20Working%20with%20JSONSQL/) | Loading JSON data and working with SQL-backed data. |
| [19 · Understanding your data](./19%20Understanding%20Your%20Data/) | Inspecting dataset structure, columns, types, and summary information. |
| [20 · Univariate EDA](./20%20EDA%20using%20Univariate%20Analysis/) | Examining individual variables and their distributions. |
| [21 · Bivariate and multivariate EDA](./21%20EDA%20using%20Bivariate%20and%20Multivariate%20Analysis/) | Exploring relationships among two or more variables. |
| [22 · Pandas Profiling](./22%20Pandas%20Profiling/) | Generating and reviewing automated dataset profiles. |

### Data preparation and feature engineering

| Lesson | Topics |
|---|---|
| [24 · Standardization](./24%20Feature%20Scaling%20-%20Standardization/) | Standard scaling and its effect on numeric features. |
| [25 · Feature scaling](./25%20Feature%20Scaling/) | Comparing common feature-scaling approaches. |
| [26 · Ordinal and label encoding](./26%20Encoding%20Categorical%20Data%20%20Ordinal%20Encoding%20%20Label%20Encoding/) | Representing categorical values with integer encodings. |
| [27 · One-hot encoding](./27%20One%20Hot%20Encoding%20%20Handling%20Categorical%20Data/) | Encoding nominal categories as indicator columns. |
| [28 · ColumnTransformer](./28%20Column%20Transformer%20in%20Machine%20Learning/) | Applying different transformations to different columns. |
| [29 · Machine-learning pipelines](./29%20Machine%20Learning%20Pipelines%20A-Z/) | Building and using preprocessing and prediction pipelines. |
| [30 · FunctionTransformer](./30%20FunctionTransformer%20Log%20Square%20Root%20Transform/) | Applying log and square-root transformations. |
| [31 · Power transformations](./31%20Power%20Transformer%20%20Box%20-%20Cox%20Transform%20%20Yeo%20-%20Johnson%20Transform/) | Box–Cox and Yeo–Johnson transformations. |
| [32 · Binning and discretization](./32%20Binning%20and%20Binarization%20%20Discretization%20%20Quantile%20Binning%20%20KMeans%20Binning/) | Binarization, quantile bins, and K-means-based bins. |
| [33 · Mixed variables and feature engineering](./33%20Handling%20Mixed%20Variables%20%20Feature%20Engineering/) | Working with mixed data types and engineered features. |
| [34 · Date and time variables](./34%20Handling%20Date%20and%20Time%20Variables/) | Extracting and preparing information from date/time fields. |
| [35 · Missing data: foundations](./35%20Handling%20Missing%20Data%20%20Part%201/) | Understanding missing values and strategies for handling them. |
| [36 · Numerical imputation](./36%20Handling%20missing%20data%20%20Numerical%20Data%20%20Simple%20Imputer/) | Simple imputation for numeric columns. |
| [37 · Categorical imputation](./37%20Handling%20Missing%20Categorical%20Data%20%20Simple%20Imputer%20%20Most%20Frequent%20Imputation%20%20Missing%20Category/) | Most-frequent and missing-category approaches. |
| [38 · Missing indicators and random samples](./38%20Missing%20Indicator%20%20Random%20Sample%20Imputation%20%20Handling%20Missing%20Data%20Part%204/) | Missingness indicators and random-sample imputation. |
| [39 · KNN imputation](./39%20KNN%20Imputer%20%20Multivariate%20Imputation%20%20Handling%20Missing%20Data%20Part%205/) | Neighbour-based multivariate imputation. |
| [40 · Iterative imputation](./40%20Multivariate%20Imputation%20by%20Chained%20Equations%20for%20Missing%20Value/) | Multivariate imputation by chained equations. |
| [42 · Z-score outlier detection](./42%20Outlier%20Detection%20and%20Removal%20using%20Z-score%20Method/) | Identifying and handling outliers with Z-scores. |
| [43 · IQR outlier detection](./43%20Outlier%20Detection%20and%20Removal%20using%20the%20IQR%20Method/) | Using the interquartile range to find outliers. |
| [44 · Percentile outlier detection](./44%20Outlier%20Detection%20using%20the%20Percentile%20Method/) | Percentile-based outlier thresholds. |
| [45 · Feature construction and splitting](./45%20Feature%20Construction%20%20Feature%20Splitting/) | Constructing features and splitting existing fields. |
| [47 · Principal Component Analysis](./47%20Principle%20Component%20Analysis%20%28PCA%29/) | PCA concepts and dimensionality reduction exercises. |

### Supervised learning and optimization

| Lesson | Topics |
|---|---|
| [48 · Simple linear regression](./48%20Simple%20Linear%20Regression/) | Fitting and interpreting a one-feature regression model. |
| [50 · Multiple linear regression](./50%20Multiple%20Linear%20Regression/) | Regression with multiple input features, including a from-scratch exercise. |
| [51 · Gradient descent](./51%20Gradient%20Descent/) | Step-by-step optimization, visualizations, and implementations. |
| [52 · Types of gradient descent](./52%20Types%20of%20Gradient%20Descent/) | Batch, stochastic, and mini-batch gradient descent. |
| [53 · Polynomial regression](./53%20Polynomial%20Regression/) | Modeling nonlinear relationships with polynomial features. |
| [55 · Ridge regression](./55%20Ridge%20Regularization/) | L2 regularization and ridge-regression implementations. |
| [56 · Lasso regression](./56%20Lasso%20Regression/) | L1 regularization and lasso-regression exercises. |
| [57 · Elastic Net](./57%20Elasticnet%20Regression/) | Combining L1 and L2 regularization. |
| [58 · Logistic regression](./58%20Logistic%20Regression/) | Perceptron, sigmoid, and gradient-descent concepts for classification. |

## Repository structure

```text
.
├── 15 Working with CSV files/
├── 16 Working with JSONSQL/
├── ...
├── 58 Logistic Regression/
├── LICENSE
└── README.md
```

Lessons are kept in separate, numbered folders, with one or more `.ipynb` notebooks in each. The numbers follow the source learning sequence; gaps indicate lessons that are not currently represented in this repository.

## Getting started

### Requirements

- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- Git (to clone the repository)

The repository does not currently include a dependency lockfile or a single shared `requirements.txt`. Individual notebooks may need additional packages, and their data files or external services may be specific to the exercise.

### Install and launch

```bash
git clone https://github.com/Md-Emon-Hasan/100-Days-of-Machine-Learning-CampusX.git
cd 100-Days-of-Machine-Learning-CampusX

python -m venv .venv
```

Activate the virtual environment:

```bash
# Windows PowerShell
.venv\Scripts\Activate.ps1

# macOS / Linux
source .venv/bin/activate
```

Install the notebook environment and start Jupyter:

```bash
python -m pip install --upgrade pip
python -m pip install jupyter pandas numpy matplotlib seaborn scikit-learn
jupyter lab
```

Open a lesson folder and run its notebook. If a notebook reports a missing package, install that package in the active environment before continuing. Some lessons may expect a dataset or service described inside the notebook.

## Tools and libraries

The notebook collection is built around the Python data-science ecosystem. Common tools include:

- **Python** for programming and experimentation.
- **Jupyter Notebook / JupyterLab** for interactive lessons.
- **pandas and NumPy** for tabular data and numerical computing.
- **Matplotlib and Seaborn** for visual exploration.
- **scikit-learn** for preprocessing, pipelines, decomposition, and machine-learning workflows.

Exact imports and dependencies can vary by notebook.

## How to use the notebooks

1. Choose a topic from the roadmap and open its folder.
2. Read the markdown cells before running the code cells.
3. Run cells in order, then change examples to explore how the results respond.
4. Check each notebook for dataset paths and package requirements before starting.
5. Record questions or follow-up experiments as you work through the material.

The notebooks are educational examples. Review assumptions, data preparation, and model evaluation before applying an approach to a separate dataset or real-world task.

## Learning goals

- Inspect datasets and communicate patterns with exploratory analysis.
- Prepare numeric, categorical, date/time, and mixed-type features.
- Handle missing values and outliers using multiple techniques.
- Build reproducible transformations with scikit-learn pipelines.
- Understand linear models, regularization, logistic regression, and optimization.
- Compare regression models using appropriate evaluation metrics.
- Strengthen intuition by implementing selected methods from scratch.

## Contributing

This is a personal learning repository, and thoughtful suggestions are welcome. If you find an issue or want to propose an improvement, open a GitHub issue or pull request with the affected notebook and a short explanation. Please keep examples reproducible and mention any added data or package requirements.

## License

This repository is distributed under the **Apache License 2.0**. See [LICENSE](./LICENSE) for the full terms.

## Connect with me

- 🌐 **Portfolio:** [emonlabs-ai.hitechparks.com](https://emonlabs-ai.hitechparks.com)
- 💻 **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)
- 💼 **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/)
- 🤗 **Hugging Face:** [emonHasan01](https://huggingface.co/emonHasan01)
- 📧 **Email:** [emon.mlengineer@gmail.com](mailto:emon.mlengineer@gmail.com)
- 📱 **WhatsApp:** [+8801834363533](https://wa.me/8801834363533)
