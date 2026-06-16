# 👥 Employee Attrition Prediction using Machine Learning

A Streamlit web application for predicting employee attrition using a pre-trained KNN model. The app collects employee information through an interactive form and predicts whether an employee is likely to leave or stay at the company — helping HR departments proactively address retention.

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

## ✨ Features

- **📊 Multiple ML Models Compared** — Naive Bayes, XGBoost, KNN, and Gradient Boosting Machine
- **🏆 Best Model Selected** — KNN chosen for highest accuracy after comparison
- **🖥️ Interactive Web App** — Streamlit-based form with sliders, dropdowns, and radio buttons
- **📈 Comprehensive EDA** — Pie charts, violin plots, box plots, histograms, correlation matrices
- **🎨 Custom Styled UI** — Enhanced styling with custom CSS, background patterns, and colored results

---

## 📋 Dataset

**Source**: [Employee Attrition Data](https://www.kaggle.com/datasets/mrsimple07/employee-attrition-data-prediction) on Kaggle

| Feature | Description |
|---------|-------------|
| `Age` | Employee age (18–70) |
| `Gender` | Male / Female |
| `Department` | Marketing, Sales, Engineering, Finance, HR |
| `Job_Title` | Manager, Engineer, Analyst, HR Specialist, Accountant |
| `Years_at_Company` | Years of tenure (0–30) |
| `Satisfaction_Level` | Employee satisfaction (0–100) |
| `Average_Monthly_Hours` | Monthly hours worked (50–300) |
| `Promotion_Last_5Years` | Whether promoted in last 5 years |
| `Salary` | Annual salary |

### Data Preprocessing

1. Feature scaling and column reinitialization
2. Outlier removal using box plots
3. Missing values handling and regularization
4. Duplicate removal and normalization
5. Oversampling for class balance

---

## 🔍 Methodology

1. **Data Preprocessing & Feature Engineering** — Cleaning, encoding, scaling
2. **Exploratory Data Analysis (EDA)** — Comprehensive visualizations:
   - Pie charts, violin plots, box plots
   - Count plots, histograms
   - Model comparison graphs
   - Confusion matrices, correlation matrices
3. **Model Training & Evaluation** — Four models compared:
   - Naive Bayes
   - XGBoost
   - K-Nearest Neighbors (KNN) ← **Best performer**
   - Gradient Boosting Machine
4. **Deployment** — Best model deployed via Streamlit web app

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Language** | Python 3.9+ |
| **ML Framework** | Scikit-learn |
| **Web App** | Streamlit |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Model Serialization** | Joblib |

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.9+** installed

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/sujitha-kotyada/Employee_attrition_prediction_using_ML.git
   cd Employee_attrition_prediction_using_ML
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**

   ```bash
   cd model
   streamlit run app.py
   ```

4. **Open in browser** — Streamlit will automatically open at [http://localhost:8501](http://localhost:8501)

---

## 📖 Usage

1. Fill in the employee details using the interactive form:
   - Select gender, department, and job title
   - Adjust sliders for age, years at company, satisfaction level, and monthly hours
   - Indicate promotion history and enter salary
2. Click **"Predict"**
3. View the prediction result — whether the employee is likely to **leave** or **stay**

---

## 📁 Project Structure

```
Employee_attrition_prediction_using_ML/
├── dataset/
│   └── employee_attrition_data.csv       # Raw dataset
├── images/                                # EDA visualizations
├── model/
│   ├── app.py                             # Streamlit web application
│   ├── employee_attrition_prediction.ipynb # Full ML pipeline notebook
│   └── knn_model.pkl                      # Trained KNN model
├── webapp/
│   └── webapp.mp4                         # Demo video
├── requirements.txt                       # Python dependencies
└── README.md
```

---

## 🎬 Demo

https://github.com/user-attachments/assets/d7f232d6-ac43-4075-8691-eba04b99a5d4

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Sujitha Kotyada** — [@sujitha-kotyada](https://github.com/sujitha-kotyada)
