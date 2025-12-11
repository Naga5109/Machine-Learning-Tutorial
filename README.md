# Logistic Regression vs Naive Bayes: A Comparative Study on Banknote Authentication

A comprehensive machine learning project comparing Logistic Regression and Gaussian Naive Bayes classifiers on the UCI Banknote Authentication dataset.

## 📋 Project Overview

This project implements and compares two popular classification algorithms:
- **Logistic Regression**: A linear model that uses the sigmoid function to model probabilities
- **Gaussian Naive Bayes**: A probabilistic classifier based on Bayes' theorem with Gaussian feature distributions

The study evaluates both models on the Banknote Authentication dataset to classify banknotes as genuine or forged based on image features.

## 🎯 Dataset

- **Source**: UCI Machine Learning Repository
- **Dataset**: Banknote Authentication Dataset
- **Features**: 
  - Variance
  - Skewness
  - Curtosis
  - Entropy
- **Target**: Binary classification (0 = genuine, 1 = forged)
- **Size**: 1,372 samples

## 🔧 Requirements

- Python 3.7+
- Jupyter Notebook
- Required packages (see `requirements.txt`)

## 📦 Installation

1. Clone this repository:
```bash
git clone <your-repo-url>
cd <repository-name>
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook notebook.ipynb
```

2. Run all cells to execute the complete analysis.

##  Key Results

- **Logistic Regression Accuracy**: 97.82%
- **Gaussian Naive Bayes Accuracy**: 86.41%
- Both models achieve strong performance with Logistic Regression showing superior results on this dataset

## 📈 Analysis Includes

- Exploratory Data Analysis (EDA)
- Principal Component Analysis (PCA) visualization
- Model training and evaluation
- Confusion matrices
- ROC curves and AUC scores
- Decision boundary visualizations in PCA space
- Comparative performance analysis

## 🛠️ Technologies Used

- **Python**: Core programming language
- **NumPy**: Numerical computations
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms and metrics

## 📝 Methodology

1. Data loading and preprocessing
2. Exploratory data analysis
3. Feature standardization
4. Dimensionality reduction using PCA
5. Model training on standardized features
6. Performance evaluation using multiple metrics
7. Visualization of results and decision boundaries

## 👤 Author

Lakshmi Nagaraju Manthri

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
