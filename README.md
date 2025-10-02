# 🏦 Loan Approval Prediction

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"/></a>&nbsp;&nbsp;
  <a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" alt="Pandas"/></a>&nbsp;&nbsp;
  <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white" alt="Scikit-learn"/></a>&nbsp;&nbsp;
  <a href="https://seaborn.pydata.org/"><img src="https://img.shields.io/badge/Seaborn-4C72B0?logo=plotly&logoColor=white" alt="Seaborn"/></a>
</p>

---

## 📌 Overview

The rising number of loan applications around the world is putting a lot of pressure
on banks to process and approve loans quickly and accurately. Unfortunately, this
often leads to delays and inconsistencies, making it harder for banks to properly
assess applicants. This also causes the employees at the bank to be under so much
stress and always occupied which in result causes the banks to be always crowded
all the time.


To solve this, we’ve developed a machine learning model that predicts the chances
of a loan being approved based on different factors. This model helps banks speed
up their approval process, make better decisions, and lower the risk of defaults.
It includes:
- **Data cleaning**
- **Exploratory data analysis (EDA)**
- **Machine learning model training**
- **Model Evaluation**

---

## 🚀 Features

- **Data Preprocessing** — Handles missing values, encodes categorical variables, and scales features.
- **EDA** — Visualizes correlations and trends in loan approval data.
- **Model Training** — Uses machine learning algorithms to predict loan approval.
- **Model Evaluation** — Evaluate all trained models and identifying the best model.

---

## 📊 Dataset

- **File:** `Loan approval prediction.csv`  
- **Contents:** Applicant demographic & financial details along with loan approval status.
- **Target variable:** `Loan_Status` (Approved / Not Approved)

---

## 🏗️ Project Structure

```
.
├── Loan approval prediction.csv   # Dataset
├── solution.ipynb                 # Main Jupyter Notebook
├── requirnemts.txt                 # Project instructions
├── README.md                       # Documentation
```

---

## ⚙️ Installation

1. **Clone the repository**:
```bash
git clone https://github.com/ZeyadMohamad/Loan-Approval-Prediction.git
cd Loan-Approval-Prediction
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

---

## 🖥️ Usage

**Run the Jupyter Notebook**:
```bash
jupyter notebook solution.ipynb
```

## 📈 Example Flow

1. Upload loan applicant data (or enter manually).
2. Model predicts **Approval** or **Rejection**.
3. View probability scores and insights.

---

## 📜 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
