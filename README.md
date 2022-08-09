# Heart Stroke Prediction using Data Science with Python:

# Introduction:
  * **Problem Statement:** Predict wheather a patient has risk of getting a heart stroke using the stroke dataset that is publicly availabe on Kaggle.
# About Dataset:
* ## Context:
  According to the World Health Organization (WHO) heart stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.
* ## Attributes:
  - id: unique identifier
  - gender: "Male", "Female" or "Other"
  - age: age of the patient
  - hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
  - heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
  - ever_married: "No" or "Yes"
  - work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
  - Residence_type: "Rural" or "Urban"
  - avg_glucose_level: average glucose level in blood
  - bmi: body mass index
  - smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
  - stroke: 1 if the patient had a stroke or 0 if not
  
  **Note: "Unknown" in smoking_status means that the information is unavailable for this patient**
 * Source:
The dataset is publically available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has the chance of future heart stroke.The dataset provides the patients’ information. It includes over 4,000 records and 12 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.

Target variable to predict:
risk of getting heart stroke - (binary: “1”, means “Yes”, “0” means “No”)
