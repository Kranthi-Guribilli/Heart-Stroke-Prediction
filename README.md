# Heart Stroke Prediction using Data Science with Python:
# Abstract:
<p> The process of discovering or mining information from a huge volume of data is known as
data mining technology. Today data mining has lots of application in every aspects of human life.
Applications of data mining are wide and diverse. Among this health care is a major application of
data mining. Medical field has get benefited more from data mining. Heart Stroke is the most
dangerous life-threatening chronic disease globally. The objective of the work is to predicts the
occurrence of heart stroke of a patient using algorithms like random forest algorithm. The dataset was accessed from
Kaggle site. The dataset contains 5110 samples and 12 attributes are taken for features of the dataset.
Then it was processed using python open access software in jupyter notebook. The datasets are
classified and processed using machine learning algorithms like Random forest. The outcomes of the
dataset are expressed in terms of accuracy, sensitivity and specificity in percentage. Using XGBClassifier, we obtained accuracy of 91% for prediction of heart stroke. The XGBClassifier has proven to be the most efficient algorithm for classification of heart stroke and therefore
it is used in the proposed system.</p>

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
The dataset is publicly available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has the chance of future heart stroke.The dataset provides the patients’ information. It includes over 4,000 records and 12 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.

Target variable to predict:
risk of getting heart stroke - (binary: “1”, means “Yes”, “0” means “No”)
