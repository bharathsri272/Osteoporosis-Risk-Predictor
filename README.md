# 🦴 Osteoporosis Risk Predictor

This project predicts the risk of **osteoporosis** using health and
lifestyle factors.\
It includes: - A **Jupyter Notebook**
(`Osteoporosis_Risk_Predictor.ipynb`) for data exploration, feature
engineering, and model training. - A **Streamlit web app**
(`Osteoporosis_Risk_app.py`) that lets users interactively enter patient
information and get predictions. - Saved models (`.pkl` files) for
deployment.

------------------------------------------------------------------------

## 📊 Dataset

The dataset includes health and lifestyle attributes such as: -
**Age** - **Hormonal Changes** - **Body Weight** - **Calcium Intake** -
**Vitamin D Intake** - **Physical Activity** - **Medical Conditions** -
**Medications** - **Prior Fractures**

The target variable is **Osteoporosis (Yes/No)**.

------------------------------------------------------------------------

## 🚀 Workflow

1.  **Data Preprocessing**: Handle missing values, encode categorical
    features, and scale numerical ones.
2.  **Exploratory Data Analysis (EDA)**: Visualize distributions,
    correlations, and feature relationships.
3.  **Model Training**: Compare models (Logistic Regression, Decision
    Tree, Random Forest, SVM).
4.  **Evaluation**: Accuracy, Precision, Recall, F1-score, Confusion
    Matrices.
5.  **Deployment**: Save the trained Decision Tree model and use it in a
    **Streamlit app**.

------------------------------------------------------------------------

## 💻 Usage

### 1. Clone this repository

``` bash
git clone https://github.com/your-username/osteoporosis-risk-predictor.git
cd osteoporosis-risk-predictor
```

### 2. Install dependencies

``` bash
pip install -r requirements.txt
```

### 3. Run the notebook (optional, for training & analysis)

``` bash
jupyter notebook Osteoporosis_Risk_Predictor.ipynb
```

### 4. Run the Streamlit app

``` bash
streamlit run Osteoporosis_Risk_app.py
```

------------------------------------------------------------------------

## 🛠 Tech Stack

-   **Python 3.8+**
-   **Pandas, NumPy** -- data processing
-   **Matplotlib, Seaborn** -- visualization
-   **Scikit-learn** -- machine learning
-   **Streamlit** -- web app interface

------------------------------------------------------------------------

## 📈 Results

-   The **Decision Tree Classifier** was selected as the best-performing
    model.
-   Important predictors: **Age, Hormonal Changes, Nutrition,
    Medications, Medical Conditions**.

------------------------------------------------------------------------

## 🔮 Next Steps

-   Add cross-validation and ROC/AUC metrics.
-   Expand the Streamlit app with probability outputs (not just binary).
-   Deploy the app online (e.g., Streamlit Cloud, Heroku).

------------------------------------------------------------------------

## 📂 Project Structure

    .
    ├── data/                      # dataset (if public)
    ├── models/                    # saved .pkl models
    ├── Osteoporosis_Risk_Predictor.ipynb   # Jupyter Notebook (EDA + training)
    ├── Osteoporosis_Risk_app.py           # Streamlit App
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## 📜 License

This project is licensed under the MIT License.
