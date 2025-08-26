# ✈️ Customer Booking Prediction – British Airways Simulation

This project analyses **50,000 airline booking records** to predict whether a booking will be completed or not.  
It was developed as part of the **British Airways Job Simulation on Forage** and demonstrates both technical and business communication skills.  

---

## 📌 Project Overview
- Goal: Understand customer booking behaviour and predict booking completion.  
- Dataset: 50,000 records with 14 features (e.g., purchase lead, length of stay, route, booking origin, flight details).  
- Task: Build and evaluate a predictive model, extract insights, and communicate findings in a business context.  

---

## 🛠️ Steps Performed
1. **Data Exploration & Cleaning**  
   - Checked missing values, distributions, and data types.  
   - Encoded categorical features using `LabelEncoder`.  

2. **Model Development**  
   - Trained a **Random Forest Classifier** on the dataset.  
   - Performed train/test split for model evaluation.  

3. **Evaluation**  
   - Achieved **~85% accuracy** on the test set.  
   - Strong performance in predicting non-completions, but lower recall for completed bookings due to class imbalance.  

4. **Insights & Visualizations**  
   - Identified key drivers of booking behaviour:  
     - **Purchase lead**  
     - **Length of stay**  
     - **Flight hour**  
     - **Route**  
     - **Sales channel**  
   - Created feature importance chart and summary PowerPoint slide for business communication.  

---

## 📊 Results
- **Accuracy**: 85%  
- **Challenges**: Class imbalance led to weaker recall for completed bookings.  
- **Next Steps**: Apply techniques like SMOTE, resampling, or class weights to improve minority class performance.  

---

## 📂 Files in this Repository
- `Notebook.ipynb` → Jupyter Notebook with full analysis & model.  
- `Model_Evaluation_Summary.pptx` → Presentation slide summarising findings.  
- `requirements.txt` → List of dependencies (pandas, scikit-learn, matplotlib, seaborn).  

---

## 🚀 Skills Demonstrated
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)  
- Data Preprocessing & Feature Engineering  
- Random Forest Classifier  
- Model Evaluation (Accuracy, Precision, Recall, F1-Score)  
- Data Visualization  
- Business Communication (PowerPoint Insights)  

---

## 💡 Key Takeaway
This project provided valuable experience in applying **data science techniques** to real-world airline booking data and highlighted the importance of handling class imbalance when building predictive models.  

