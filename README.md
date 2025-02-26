# 🚑 Prediction of Admission of Confirmed COVID-19 Cases to ICU  

## 📌 Project Overview  
This project aims to predict whether a **COVID-19 patient requires ICU admission** using **machine learning algorithms**. Given the increasing burden on healthcare systems, early detection of ICU requirements can help in **resource allocation** and **patient triage**.  

The dataset, sourced from **Kaggle**, consists of **patient demographics, past medical conditions, vital signs, and lab results**. The project compares the performance of different **classification models** to determine the best approach for **accurate predictions**.  

## 🚀 Features  
- **Data Preprocessing**  
  - Handling missing values  
  - Feature selection and engineering  
- **Machine Learning Models Implemented**  
  - **Logistic Regression**  
  - **Gaussian Naïve Bayes**  
  - **Stochastic Gradient Descent (SGD) Classifier**  
  - **Extreme Gradient Boosting (XGB) Regressor**  
  - **Ensemble Model for improved performance**  
- **Evaluation Metrics Used**  
  - **Accuracy**  
  - **Confusion Matrix**  
  - **ROC Curve and AUC Score**  
- **Graphical Insights**  
  - Comparative study using **box plots** and **bar charts**  
  - ICU admission trends over time  

## 📊 Dataset  
- **Source:** Kaggle (COVID-19 ICU Admission Data)  
- **Features:**  
  - **Demographic data** (age, gender)  
  - **Comorbidities** (diabetes, hypertension, etc.)  
  - **Vital signs & lab results** (blood pressure, oxygen levels)  
  - **ICU admission status** (binary classification: **1 = ICU admission, 0 = No ICU admission**)  

## 🔬 Experimental Results  
| Algorithm | Accuracy |
|-----------|----------|
| Logistic Regression | **86%** |
| Gaussian Naïve Bayes | **77%** |
| SGD Classifier | **79%** |
| XGB Regressor | **89%** |
| Ensemble Model | **Highest Accuracy** |

## 🏆 Conclusion  
- **XGB Regressor outperformed** other models in predicting ICU admissions.  
- **Ensemble learning further improved prediction accuracy**, suggesting a hybrid approach is beneficial.  
- **Early prediction of ICU needs can significantly aid hospitals** in better planning and resource allocation.  

## 🔮 Future Scope  
- **Web Interface:** Developing a UI for real-time patient data input and ICU admission prediction.  
- **Integration with Healthcare Systems:** Deploying the model as an **API** for hospitals to automate risk assessment.  
- **Feature Optimization:** Enhancing data preprocessing to refine prediction accuracy.  

## ⚙️ Installation & Setup  
### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/your-repo-url/covid-icu-prediction.git
cd covid-icu-prediction


