# 🏢 Predict Employee Turnover with Scikit-learn  

This project focuses on predicting **employee churn (turnover)** using **Decision Trees** and **Random Forests**. It involves data preprocessing, visualization, model training, and evaluation to identify which factors contribute most to employee attrition.  

---

## 📌 Project Workflow  

### **Task 1: Import Libraries**  
- Imported essential libraries: **NumPy, Pandas, Matplotlib, scikit-learn**.  
- Loaded helper functions for visualization and analysis.  

### **Task 2: Exploratory Data Analysis (EDA)**  
- Loaded the employee dataset with **pandas**.  
- Explored key trends and distributions.  
- Created visualizations to compare different features against the target variable (turnover).  

### **Task 3: Encode Categorical Features**  
- Encoded the categorical variables **Department** and **Salary** using **dummy variables**.  

### **Task 4: Visualize Class Imbalance**  
- Checked class balance using **Yellowbrick’s Class Balance Visualizer**.  
- Plotted class frequency to detect imbalance.  
- Insights guided the **sampling strategy** for splitting data.  

### **Task 5: Create Training and Validation Sets**  
- Split dataset into **80% training** and **20% validation**.  
- Applied **stratified sampling** to maintain class distribution.  

### **Task 6 & 7: Decision Tree Classifier**  
- Built a **Decision Tree Classifier** with interactive parameter tuning using `interact()`.  
- Trained the model and calculated **training vs. validation accuracy**.  
- Visualized the fitted decision tree structure.  

### **Task 8: Random Forest Classifier**  
- Built a **Random Forest Classifier** with `interact()` for tuning hyperparameters.  
- Overcame **overfitting/variance** issues seen in decision trees.  
- Evaluated training and validation performance.  
- Displayed one fitted tree for interpretability.  

### **Task 9: Feature Importance & Model Evaluation**  
- Extracted **feature importances** from both Decision Tree and Random Forest models.  
- Ranked and plotted features contributing most to churn prediction.  
- Compared models with evaluation metrics.  

---

## 🚀 Key Learnings  
- Handling categorical variables with dummy encoding.  
- Visualizing and addressing **class imbalance**.  
- Comparing **Decision Trees vs. Random Forests**.  
- Using **interactive controls** for model experimentation.  
- Interpreting **feature importance** in employee turnover prediction.  

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Yellowbrick**  
- **scikit-learn**  

---

## 📊 Results  
- Decision Trees provide interpretability but risk overfitting.  
- Random Forests improve accuracy and generalization.  
- Feature importance reveals which employee attributes strongly influence turnover.  

---

## 📌 Next Steps  
- Test additional models (e.g., Gradient Boosting, XGBoost).  
- Apply **SMOTE or undersampling** to handle imbalance.  
- Deploy the model with a simple **web dashboard**.  

---

✨ With this project, you gain practical experience in **classification, model interpretability, and churn analysis** using scikit-learn.  
