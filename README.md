# -Medical-Appointment-Task-1

# 🏥 Medical Appointment Data Cleaning

This project focuses on cleaning and preparing a dataset containing information about medical appointments. The primary goal is to make the data suitable for further analysis or modeling, such as predicting patient no-shows.

---

## 📁 Dataset Overview

The dataset contains information such as:
- Patient ID
- Appointment ID
- Gender
- Scheduled Date
- Appointment Date
- Age
- Neighbourhood
- Scholarship (Yes/No)
- Hypertension
- Diabetes
- Alcoholism
- SMS_received
- No-show (Target variable)

---

## 🧹 Cleaning Steps

The following steps were performed to clean the dataset:

1. **Loaded the Dataset**  
   - Used `pandas` to read the CSV file.

2. **Renamed Columns**  
   - Replaced confusing or inconsistent column names for clarity (e.g., `No-show` → `NoShow`, `ScheduledDay` → `ScheduledDate`).

3. **Handled Missing Data**  
   - Checked for and removed or filled missing values.

4. **Dropped Irrelevant Columns**  
   - Removed columns such as `PatientId` and `AppointmentID` that were not needed for analysis.

5. **Fixed Data Types**  
   - Converted date columns (`ScheduledDate`, `AppointmentDate`) to `datetime` format.

6. **Removed Duplicates**  
   - Checked and removed any duplicate records.

7. **Handled Invalid Entries**  
   - Removed rows with negative age values or unrealistic data.

8. **Formatted Categorical Columns**  
   - Converted strings like "Yes"/"No" to binary or lowercase values.

9. **Saved Cleaned Dataset**  
   - Exported the cleaned dataset to a new CSV file for further use.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 📊 Next Steps

After cleaning, the dataset is ready for:
- Exploratory Data Analysis (EDA)
- Visualization
- Machine Learning Model Building

---

## 📁 Files Included

- `medical_appointment_data.csv` – Original dataset
- `cleaned_medical_data.csv` – Cleaned dataset
- `data_cleaning_notebook.ipynb` – Jupyter Notebook with cleaning steps
- `README.md` – This file

---
