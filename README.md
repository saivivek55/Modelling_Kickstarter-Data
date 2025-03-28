# 🎯 Kickstarter Campaign Success Classification

**This repository focuses on predicting the success or failure** of Kickstarter campaigns using supervised machine learning models. It involves **Exploratory Data Analysis (EDA)**, feature engineering, model evaluation, and comparison using classification algorithms.

## 📌 Overview
Using cleaned Kickstarter data, the project:

- Performs binary classification (successful vs. not successful)  
- Applies **Recursive Feature Elimination (RFE)** for feature selection  
- Trains and evaluates models:  
  - ✅ Logistic Regression  
  - ✅ Decision Tree  
  - ✅ K-Nearest Neighbors  
  - ✅ Random Forest  
  - ✅ Support Vector Machine (SVM)  
- Implements **cross-validation** for robust accuracy comparison

## 📊 Classifier Comparison
| Model                 | Accuracy (± Std) |
|-----------------------|------------------|
| 🟢 Random Forest       | 0.97 ± 0.01      |
| 🟢 K-Nearest Neighbors | 0.97 ± 0.01      |
| 🟡 Decision Tree       | 0.90 ± 0.03      |
| 🟠 Logistic Regression | 0.87 ± 0.07      |
| 🔴 SVM                 | 0.80 ± 0.05      |


## ⚙️ Features
- ⚙️ Feature Selection using **RFE**  
- 🔁 Pre-Cross-Validation vs. Cross-Validated Accuracy Comparison  
- 📏 Model performance evaluated using accuracy & standard deviation  
- 📉 Accuracy distributions visualized using **box plots**

## 🛠️ Tech Stack
- **Python**  
- **scikit-learn**  
- **Matplotlib & Seaborn**  
- **RFE (Recursive Feature Elimination)**  
- **Jupyter Notebook**

## 🚀 How to Run
1. **Clone the repository**  
   ```bash
   git clone https://github.com/saivivek55/Modelling_Kickstarter-Data.git
   cd Modelling_Kickstarter-Data

2. **Install dependencies**
3. **Launch the notebook**

## 🔍 Key Insights                                                                                                                                                                                                                      
✅ Random Forest and KNN outperformed all models with 97% accuracy                                                                                                                                                                                         
✅ RFE helped reduce noise and improve classification reliability                                                                                                                                                             
🔁 SVM struggled with generalization and had the lowest accuracy                                                                                                                                                              
📊 Box plots revealed clear variance trends among classifiers                                                                                                                                                                                          
                                                
## 📄 License                                                                                                                                                                                                                                                                                                                                                                                       
Licensed under the Apache 2.0 License – see the LICENSE file for details.
