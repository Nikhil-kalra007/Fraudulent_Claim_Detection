# Fraudulent Claim Detection

**Team Members:**  
- Nikhil Kalra  
- Vaibhav Jhade  

## 🔍 Objective

To analyze historical insurance claim data using machine learning techniques in order to:

- Identify patterns indicative of fraudulent behavior  
- Build predictive models that flag suspicious claims  
- Improve the efficiency of the fraud detection process  

---

## 📁 Contents of the Zip Folder

- 📓 `Fraudulent_Claim_Detection_Nikhil_Kalra_Vaibhav_Jhade.ipynb`  
  *Interactive Python notebook with complete code implementation*

- 📄 `Fraudulent_Claim_Detection_Starter_Nikhil_Kalra_Vaibhav_Jhade.docx`  
  *Detailed report covering analysis, methodology, results, and insights*

- 📊 `Fraudulent_Claim_Detection_Starter_Nikhil_Kalra_Vaibhav_Jhade.pptx`  
  *Presentation with executive summary, recommendations, and business implications*

---

## 🧠 Key Questions Answered

1. **How can historical data be used to detect fraud?**  
   → By analyzing patterns across features like incident severity, customer behavior, and claim conditions.

2. **Which features are most predictive of fraud?**  
   → `Insured Hobbies`, `Incident Severity`, `Witness`, `Umbrella Limit`.

3. **Can fraud likelihood be predicted for incoming claims?**  
   → Yes. Logistic regression model provides a reliable prediction with **81% recall**.

4. **What actionable insights emerged from the model?**  
   → Use high-importance features for early alerts, reducing manual effort and enabling proactive investigation.

---

## ✅ Summary of Results

| Model               | Accuracy | Recall | Precision | F1 Score |
|---------------------|----------|--------|-----------|----------|
| Logistic Regression | 0.83     | 0.81   | 0.62      | 0.70     |
| Random Forest       | 0.82     | 0.74   | 0.61      | 0.67     |

- **Logistic Regression** selected for deployment due to higher recall (sensitive to fraud detection).
- Feature selection and scaling were used to improve model robustness.

---

## 🚀 Business Implications

- Faster fraud detection = reduced claim leakage
- Model can be integrated into claim processing pipeline
- Improves customer trust by reducing false positives

---

## 📌 Notes

- All code and outputs are generated using the starter files provided.
- Team names and assignment title are embedded in all files.
- Assumptions, methods, and decisions are documented in the report.

