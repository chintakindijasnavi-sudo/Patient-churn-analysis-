# Patient_Churn_Analysis 
Patient Churn Analysis using Python and EDA

# Dataset Link 
https://www.kaggle.com/datasets/nudratabbas/patient-churn-prediction-dataset-for-healthcare

Objective :
Exploratory analysis of patient churn patterns to identify key factors influencing patient retention in healthcare services.

Problem Statement :
Patient churn — when patients stop visiting or switch away from a healthcare provider this becomes a major challenge in healthcare management. Losing patients leads to direct revenue loss, poor health outcomes, and damaged provider reputation.
This project analyzes a real-world patient dataset to uncover why patients leave and what factors are most responsible for churn, using Python-based exploratory data analysis.

Dataset :
Download : https://www.kaggle.com/datasets/nudratabbas/patient-churn-prediction-dataset-for-healthcare

Why Patient Churn Happens
Based on the EDA conducted in this project, churn is driven by the following key factors:
1 Low Satisfaction :
Patients with overall satisfaction of 1 or 2 churn at the highest rate. Poor staff behavior and long wait times are the biggest contributors to dissatisfaction.
2 Billing Issues :
Patients who face billing problems are significantly more likely to churn. A single bad billing experience can permanently damage patient trust.
3 High Out-of-Pocket Costs :
Patients in the top 25% of out-of-pocket spending show elevated churn rates. Financial burden is a key reason patients discontinue care.
4 Missed Appointments :
More missed appointments strongly predict eventual churn. It is an early warning signal of patient disengagement.
5 Distance to Facility :
Patients living farther from the facility tend to churn more. Geographic accessibility is a structural barrier to continued care.
6 Age Group :
Younger patients (18–30) churn the most. This demographic is more mobile and more likely to switch providers through digital health platforms.
7 Insurance Type :
Uninsured patients show the highest churn rate. Without financial coverage, patients deprioritize non-emergency and follow-up visits.
8 Medical Specialty :
Elective specialties like Orthopedics show higher churn than ongoing-care specialties, as patients stop returning once their condition is treated.

Key Insights from charts :
Churned vs Retained  :  Dataset is relatively balanced between churned and retained patients . 
Churn by Gender  :  Gender has minimal impact — both groups behave similar churn rate . 
Churn by Age  :   Youngergroup patients (18–30) churn the most . 
Churn by Distance  :  Patients farther from the facility are more likely to stop visiting . 
Churn by Wait  :  Wait time experience is strongly linked to higher churn . 
Churn vs Satisfaction  :  Lower satisfaction scores directly correspond to higher churn rates . 
Churn by Insurance  :  Uninsured patients churn the most due to financial burden . 
Churn by Specialty  :  Elective specialties see higher churn than ongoing-care specialties . 
Churn by Missed Appointments  :  More missed appointments strongly predict eventual churn . 
Billing Issues vs Churn  :  Patients with billing problems churn at a significantly higher rate . 
Specialty vs Churn  :  Churned patients are present across all specialties, varying by visit volume . 
Correlation Heatmap  :  Satisfaction scores negatively correlate with churn billing issues, missed appointments, and high costs positively correlate .confirming they are the primary drivers of patient disengagement.

Recommendations to Reduce Churn :
- Improve patient experience — act on satisfaction feedback, train staff on communication and empathy
- Reduce wait times — better scheduling systems and digital check-in options
- Fix billing transparency — provide clear, itemized bills and offer flexible payment plans
- Re-engage missed appointment patients — automated reminders and follow-up calls
- Expand telehealth — reduce geographic barriers for distant patients
- Target younger patients — digital-first engagement programs for the 18–30 group
- Support uninsured patients — financial counseling and assistance programs

Technologies Used : 
Python 3
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook 

Author 
Chintakindi Jasnavi Email: chintakindijasnavi@gmail.com 
linkedin: www.linkedin.com/in/chintakindi-jasnavi
GitHub: https://github.com/chintakindijasnavi-sudo/Patient-churn-analysis-/edit/main/README.md
