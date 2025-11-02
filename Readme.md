# 🏦 Home Credit Scorecard Model
> Final Task - Rakamin Virtual Internship Program (Data Science Track)  
> Created by **Ghozi Alvin Karim**

---

## 📘 Project Overview
This project was developed as part of the **Home Credit Indonesia – Rakamin Data Science Virtual Internship Program**.  
The objective of this project is to build a **credit scoring model** that predicts the probability of a loan applicant being able to repay their debt, based on historical customer and financial data.

The notebook contains the full end-to-end data science pipeline: from data preprocessing and EDA, to model training and evaluation.

---

## 📂 Project Structure
```

Final-Task-Home-Credit-Scorecard-Model/
│
├── DS_(HCI_Rakamin).ipynb          # Main notebook (end-to-end process)
└── README.md                        # Project documentation

````

---

## 🧠 Key Steps in Analysis
### 1. Data Preprocessing
- Handling missing values  
- Removing outliers  
- Feature engineering and encoding categorical variables  
- Scaling numerical features for model compatibility

### 2. Exploratory Data Analysis (EDA)
- Univariate and bivariate analysis  
- Distribution visualization using histograms, boxplots, and correlation heatmaps  
- Identifying key variables affecting repayment ability

### 3. Modeling
- Baseline model: **Logistic Regression**  
- Advanced model: **Random Forest Classifier**  
- Model evaluation using:
  - Accuracy, Precision, Recall, F1-score  
  - ROC-AUC Curve  
  - Confusion Matrix  

### 4. Model Interpretation
- Feature importance visualization  
- Business insights from top predictive features  

---

## 🧰 Tech Stack
- **Python 3.8+**
- **Libraries:**  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`, `imbalanced-learn`

---

## 🚀 How to Run the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/Ghozialvin/Final-Task-Home-Credit-Scorecard-Model.git
   cd Final-Task-Home-Credit-Scorecard-Model
    ````
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook DS_(HCI_Rakamin).ipynb
   ```
4. Run all cells to reproduce the results.

---

## 📊 Results Summary

* **Best performing model:** Random Forest Classifier
* **Key metrics:** High ROC-AUC and balanced precision-recall tradeoff
* The model demonstrates good predictive power for identifying high-risk applicants.
---

## ✨ Author
**Ghozi Alvin Karim**
💼 Rakamin x Home Credit Indonesia - Data Science Virtual Internship Program
---