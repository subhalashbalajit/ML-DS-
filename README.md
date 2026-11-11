# Machine Learning & NLP Mini-Projects

A collection of four end-to-end Machine Learning and NLP projects built in Python using `scikit-learn`, `pandas`, `numpy`, `matplotlib`, and `seaborn`.

## 📂 Projects Included

1. **Iris Species Classification**
   * **Models:** Logistic Regression & Decision Tree Classifier
   * **Highlights:** Pairplot EDA, confusion matrices, and 2D PCA decision boundary visualization.
   * **Result:** 93.33% Accuracy on both models.

2. **California Housing Price Prediction**
   * **Model:** Random Forest Regressor (100 estimators)
   * **Highlights:** Automated `ColumnTransformer` preprocessing pipeline with median imputation and one-hot encoding.
   * **Result:** $R^2$ Score of `0.8169` | RMSE of `$48,977.06`.

3. **Telco Customer Churn Prediction**
   * **Model:** Random Forest Classifier
   * **Highlights:** Data cleaning, feature scaling, confusion matrix, and Top 10 feature importance visualization.
   * **Result:** `78.57%` Accuracy | `0.8246` ROC-AUC Score.

4. **Product Review Sentiment Analysis**
   * **Models:** Multinomial Naive Bayes & Logistic Regression
   * **Highlights:** Regex text cleaning, custom stopword removal, TF-IDF vectorization, and live custom phrase prediction.

## 🛠️ Tech Stack
* Python 3.x
* `pandas`, `numpy`
* `scikit-learn`
* `matplotlib`, `seaborn`

## 🚀 Quick Start

1. **Install dependencies:**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```
2. **Update file paths:** Change the local dataset paths in `pd.read_csv()` to match your directory.
3. **Run the notebook:**
   ```bash
   jupyter notebook
   ```
