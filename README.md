# 📊 Student Performance Regression Project

This project applies regression techniques to predict student performance using academic and demographic data. The goal is to identify key factors influencing students' final grades and build a predictive model using linear regression and other algorithms.

## 🗂️ Project Structure

- `Project Regression Student Performance.ipynb` – Jupyter Notebook containing the complete analysis, preprocessing, model training, and evaluation.
- `Regression_Project_Student_Performance.csv` – Dataset with student-related information and academic records.

## 🎯 Objective

To develop a regression model capable of predicting students' final grades (`G3`) based on input features such as:

- Prior grades
- Study time
- Sleeping hours
- Sample Question paper solved
- Demographic attributes

## 🧾 Dataset Description

The dataset contains various attributes related to student demographics, academic performance, and background. A few important columns include:

| Column       | Description                          |
|--------------  |--------------------------------------|
| `Hours Studied`| Hours studied by the student         |
| `Previous Scores`| Marks scored by the student in the previous exam|
| `Extracurricular Activities`   | If the student is enrolled in any extracurricular activities|
| `Sleep Hours`     | Sleeping time for the particular student|
| `Sample Question Papers Practiced`| Sample question paper practiced by the student|
| `Performance Index`   | target Variable |

## 🧪 Methodology

### 1. Data Preprocessing
- Handling missing values
- Encoding categorical variables (Label Encoding / One-Hot)
- Feature scaling

### 2. Exploratory Data Analysis (EDA)
- Correlation matrix
- Feature distribution
- Pairplots and scatterplots

### 3. Model Building
- Linear Regression
- Ridge & Lasso Regression (Regularization)
- Evaluation using:
  - R² Score
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

### 4. Feature Importance
- Identification of key predictors contributing to academic success

## 📈 Results & Insights

- `G1` and `G2` (past grades) are highly correlated with final performance.
- Study time and absences also significantly impact outcomes.
- Regularized regression models helped reduce overfitting and improved interpretability.

## 🧰 Technologies Used

- Python 3.x
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn (Regression models, metrics)

## 🚀 Future Enhancements

- Experiment with ensemble models (Random Forest, XGBoost)
- Apply cross-validation and grid search for hyperparameter tuning
- Develop a web interface using Flask/Streamlit for live predictions

## 🙋‍♂️ Author

**Sourav Mondal**  
📧 msourav222@gmail.com

---

