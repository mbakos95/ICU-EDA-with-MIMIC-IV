
# 🏥 ICU Exploratory Data Analysis with MIMIC-IV

This repository contains my final project for **AIDL03 - Exploratory Data Analysis (EDA)**, where I worked with the **MIMIC-IV clinical dataset**.  
The goal of this project is to explore ICU stays and prescriptions, analyze patient outcomes, and answer meaningful research questions using **data science techniques**.

---

## 📂 Repository Structure
```

ICU-EDA-MIMIC-IV/
│── notebooks/
│   └── Zampakos\_Christos\_0096.ipynb     # Main Jupyter Notebook with full code
│
│── reports/
│   └── Zampakos\_Christos\_0096.pdf       # Final report in PDF format
│
│── requirements.txt                     # Python dependencies
│── README.md                            # Project documentation

```

---

## 🎯 Research Questions
1. **Top Diagnoses**  
   - Which diagnoses are most frequent among ICU patients?  
   - Analysis performed using diagnosis codes and clinical descriptions.  
   - Visualized with bar plots showing the top 10 diagnoses.

2. **Prescription Patterns**  
   - What are the most commonly prescribed drugs across the top diagnoses?  
   - Drug frequencies analyzed and visualized using a **heatmap** for clear comparison.

3. **Length of Stay (LOS)**  
   - How does the **Length of Stay** vary across diagnoses and DRG codes?  
   - Calculated LOS from admission/discharge timestamps.  
   - Visualized using **boxplots** and **statistical summaries (mean, median, std)**.

---

## ⚙️ Technologies Used
- **Python**: Data manipulation and analysis
- **pandas**: Merging large-scale medical datasets
- **numpy**: Numerical calculations
- **matplotlib & seaborn**: Data visualization
- **Google Colab**: Cloud-based notebook execution
- **MIMIC-IV Dataset**: Real ICU patient data (physionet.org)

---

## 📊 Key Insights
- Hypertension and hyperlipidemia are among the most common diagnoses.  
- Certain drugs appear disproportionately across frequent diagnoses, showing prescription patterns.  
- Length of Stay (LOS) varies significantly by diagnosis and DRG codes, with some diagnoses leading to much longer ICU stays.

---

## 📑 Report
The full PDF report is available in:  
[`reports/Zampakos_Christos_0096.pdf`](reports/Zampakos_Christos_0096.pdf)


---

## 📈 Example Visualizations

- **Top 10 Diagnoses**  
  ![Top 10 Diagnoses](https://github.com/mbakos95/ICU-EDA-with-MIMIC-IV/blob/main/Top%2010%20Diagnoses%20(Bar%20Chart).png)

- **Drug Prescriptions Across Diagnoses (Heatmap)**  
  ![Drug Prescriptions Heatmap](https://github.com/mbakos95/ICU-EDA-with-MIMIC-IV/blob/main/Drug%20Prescriptions%20Across%20Diagnoses%20(Heatmap).png)

- **Length of Stay by Diagnosis and DRG (Boxplots)**  
  ![LOS by Diagnosis and DRG](https://github.com/mbakos95/ICU-EDA-with-MIMIC-IV/blob/main/Length%20of%20Stay%20by%20Diagnosis%20and%20DRG%20(Boxplots).png)


---

## 📌 Notes

* The analysis was limited to the **first 100,000 rows** of each CSV for performance reasons.
* All visualizations were customized for readability (color palettes, font sizes, axis formatting).
* AI tools (ChatGPT) were used minimally and **only for improving visualization aesthetics** (e.g., choosing color palettes), while all analysis, merging, and logic were fully implemented by me.

---

## 👨‍💻 Author

**Christos Zampakos**
Master’s in Artificial Intelligence & Deep Learning (AIDL03)
GitHub: [mbakos95](https://github.com/mbakos95)



---

## ⚠️ Important Notice on Data Privacy
This project uses the **MIMIC-IV clinical dataset**, which contains sensitive health information.  
Due to data privacy and access restrictions:
- The raw dataset **cannot** be shared in this repository.
- The notebook is provided **only for demonstration purposes** to showcase the methodology, code structure, and logic of my analysis.
- Anyone wishing to replicate the results must request access to MIMIC-IV via [PhysioNet](https://physionet.org/), complete the required data use agreements, and download the data independently.

Therefore, this repository should be considered a **technical showcase of the analysis pipeline** (EDA process, data cleaning, feature engineering, and visualization), rather than a fully runnable project out-of-the-box.




