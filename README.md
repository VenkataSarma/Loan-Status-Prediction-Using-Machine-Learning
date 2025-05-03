 
````markdown
# Loan Status Prediction using Machine Learning

## 🔍 Project Overview
Loan approval is a critical task for financial institutions, involving the evaluation of a customer's financial history and risk factors. This project uses machine learning algorithms to predict whether a loan should be approved or rejected based on various features like income, credit score, employment status, etc.

By automating the loan approval process, this system aims to reduce human bias, improve accuracy, and save time for banks and financial organizations.

---

## 📌 Problem Statement
To develop a predictive system using machine learning techniques that determines whether a loan should be approved or not, based on applicant information. This addresses the need for faster, more consistent, and reliable loan decision-making processes in the finance industry.

---

## 💡 Proposed Solution
We used supervised learning algorithms to classify applications as Approved or Rejected. The solution consists of:

- Data Preprocessing: Handling missing values, encoding categorical features, feature scaling.
- Model Training: Multiple classification models including Logistic Regression, SVC, Decision Tree, Random Forest, Gradient Boosting.
- Hyperparameter Tuning: For improved model accuracy.
- Deployment: Model saved and served through a GUI for real-world use.

---

## 🧠 Algorithms Used

| Model                   | Accuracy (Before Tuning) | Accuracy (After Tuning) |
|------------------------|--------------------------|-------------------------|
| Logistic Regression     | 80.48%                   | 80.48%                  |
| Support Vector Classifier (SVC) | 79.38%           | 80.66%                  |
| Random Forest Classifier | 77.76%                  | 80.66%                  |

---

## ⚙️ System Approach

### 1. **System Requirements**
- Python 3.x
- Jupyter Notebook or any Python IDE
- Basic ML libraries

### 2. **Libraries Used**
```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
lightgbm
joblib
tkinter (for GUI)
````

---

## 🧪 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Loan-Status-Prediction.git
   cd Loan-Status-Prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Code :

   ```bash
   Run in jupyter notebook
   ```

---

## 📈 Results

* The best models (SVC and Random Forest with tuning) achieved **80.66%** accuracy.
* Improved performance through feature scaling, encoding, and hyperparameter tuning.
* GUI interface allows easy interaction with the trained model.

---

## 📌 Conclusion

This project demonstrates the power of machine learning in automating and improving the loan approval process. Despite data limitations, models achieved good accuracy. Further improvement can be done by integrating larger datasets and advanced ensemble methods.

---

## 🔮 Future Scope

* Integration with real-time APIs for live credit scores or financial records.
* Expansion to include fraud detection as a separate feature.
* Deployment on cloud platforms (e.g., AWS, GCP) with REST API for broader accessibility.
* Use of deep learning or advanced ensemble techniques.

---

## 📚 References

* [Kaggle: Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)
* [GeeksforGeeks: Loan Prediction using ML](https://www.geeksforgeeks.org/loan-approval-prediction-using-machine-learning/)
* [ResearchGate: Comparative Study of Loan Approval Prediction](https://www.researchgate.net/publication/381415188_A_Comparative_Study_of_Loan_Approval_Prediction_Using_Machine_Learning_Methods)

---

## 🙌 Acknowledgements

This project was built as part of a capstone data science course. Special thanks to open-source communities and dataset providers for enabling real-world projects like this.


 
