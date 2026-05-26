# Employee Attrition Prediction

## Project Overview
This project predicts whether an employee is likely to leave the company or not using Machine Learning classification algorithms.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Feature Scaling
- Model Training
- Model Evaluation

---

## Dataset Information
- [DownloadDataset](WA_Fn-UseC_-HR-Employee-Attrition.csv)
The dataset contains employee-related information such as:
- Age
- Gender
- Job Role
- Monthly Income
- Overtime
- Work Experience
- Attrition Status etc

Target Variable:
- Attrition (Yes/No)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Exploratory Data Analysis

### Attrition Distribution
Employees who stayed in the company are significantly higher than employees who left, indicating class imbalance in the dataset.

### Overtime vs Attrition
Employees who work overtime tend to have a higher attrition rate compared to employees who do not work overtime.

### Gender vs Attrition
Male employees have slightly higher attrition compared to female employees.

### Correlation Heatmap
Most features show weak correlation, Strong positive correlations are observed between JobLevel and MonthlyIncome, as well as YearsAtCompany and YearsWithCurrManager.

## Sample Visualizations

### Overtime vs Attrition
![Overtime](Overtime%20vs%20Attrition.png)

### Attrition Distribution
![Attrition](Attrition%20distribution.png)

### Age Distribution
![Age](Age%20distribution.png)

### Gender vs Attrition
![Gender](Gender%20vs%20Attrition.png)

### Job vs Attrition
![Job](Job%20vs%20Attrition.png)

### Monthly Income Distribution
![MonthlyIncome](Monthly%20Income%20distribution.png)

### Correlation Heatmap
![Heatmap](Correlation%20Heatmap.png)

### Model Comparision based on F1_score
![Comparision](Model%20comparision%20based%20on%20F1_score.png)

---

## Machine Learning Models Used
- Logistic Regression
- KNN
- Kernel SVM
- Naive Bayes
- Decision Tree
- Random Forest

---

## Best Model
Logistic Regression performed best overall for this dataset based on:
- Accuracy
- Precision
- Recall
- F1-Score

---

## Conclusion
This project successfully analyzed employee attrition patterns and built classification models to predict attrition. Overtime, income, and job-related features showed significant impact on employee attrition.
