# 🎓 Student Dropout Analysis & Prediction

This project analyzes and predicts student dropout risks using data-driven insights and machine learning models. Built using Python, Pandas, Scikit-learn, XGBoost, and visualized with Seaborn and Matplotlib.

## 📂 Project Structure

- `dataset.csv` + lookup files (`tA1_*` to `tA10_yes_no.csv`): Raw data and attribute mappings.
- `processed_student_data.csv`: Cleaned and encoded data used for training.
- `project_with_markdown_findings.ipynb`: Annotated notebook with EDA, model results, and insights.
- `student_dropout_model.pkl`: Trained model (Random Forest).
- `report.pdf`: Summary report for presentation.

## 📊 Key Insights

- Dropout students tend to have:
  - Lower academic performance
  - Inconsistent attendance
  - Financial challenges (tuition/debt)
  - More variation in enrollment age

- Features like:
  - **Grades**
  - **Curricular units approved**
  - **Tuition paid**
  are strong predictors of dropout behavior.

## 🧠 Models Used

| Model           | Accuracy | ROC AUC |
|----------------|----------|---------|
| Random Forest   | 83%      | 0.90    |
| XGBoost         | 83%      | 0.90    |
| Decision Tree   | 75%      | 0.75    |

✅ **Random Forest and XGBoost** performed best in terms of identifying at-risk students.

## 🛠️ Future Development

A **Streamlit dashboard** could be integrated for:

- Real-time predictions
- Educator/admin notifications
- Early intervention alerts focused on likely dropouts (Class 1)

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Rohit-2-0/student-dropout.git
   cd student-dropout
