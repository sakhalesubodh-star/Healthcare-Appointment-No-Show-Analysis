# Healthcare Appointment No-Show Analysis

## Project Overview

Healthcare appointments are often missed by patients, which can affect hospital efficiency, doctor availability, and patient care.

This project analyzes a healthcare appointment dataset to identify the key factors associated with patient no-shows.

The project follows a complete **Data Analytics workflow**, starting with data exploration and cleaning in **Python/Jupyter Notebook**, followed by analysis and interactive visualization using **Tableau**.

---

## Objectives

The main objectives of this project are:

- Analyze healthcare appointment attendance patterns.
- Identify the number of appointments that were completed and missed.
- Calculate the overall no-show rate.
- Analyze no-shows based on gender, age, SMS reminders, neighbourhood, and weekdays.
- Identify patterns that may contribute to missed appointments.
- Build an interactive dashboard for easy exploration of the results.

---

##🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Tableau Public**
- **GitHub**

---

##  Project Workflow

The project was completed in the following stages:

### 1. Data Collection
The healthcare appointment dataset was obtained and loaded into Jupyter Notebook for analysis.

### 2. Data Cleaning & Preprocessing

Python and Pandas were used to:

- Load the dataset.
- Inspect the dataset structure.
- Check data types.
- Check for missing values.
- Check for duplicate records.
- Rename columns where required.
- Convert and format relevant columns.
- Check categorical values.
- Prepare the dataset for analysis.

### 3. Exploratory Data Analysis

The dataset was analyzed to understand:

- Appointment outcomes.
- Gender distribution.
- Age distribution.
- SMS reminder patterns.
- Neighbourhood-wise appointments.
- Weekday-wise appointments.
- No-show patterns.

Visualizations were created using Python to understand the data before creating the final dashboard.

### 4. Tableau Dashboard

After completing the analysis in Jupyter Notebook, the cleaned dataset was used in Tableau to create an interactive dashboard.

The dashboard contains:

- Total Appointments
- Total No-Shows
- Total Showed
- No-Show Rate
- Appointment Outcome
- No-Show by Gender
- SMS Reminder vs Appointment Outcome
- Age Analysis
- Neighbourhood Analysis
- Appointment Outcome by Weekday

Interactive filters were also added to allow users to explore the data based on different categories.

---

##  Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Appointments | 110,527 |
| Total No-Shows | 22,319 |
| Total Showed | 88,208 |
| No-Show Rate | 20.19% |

---

##  Dashboard

The Tableau dashboard provides an interactive view of healthcare appointment attendance and no-show patterns.

### Dashboard Features

- Interactive Gender filter
- No-show filter
- SMS received filter
- Age group filter
- Neighbourhood filter
- Appointment day filter
- Interactive charts
- KPI cards
- Appointment outcome analysis

---

## 🔍 Key Analysis

### Appointment Outcome

Out of 110,527 appointments:

- **88,208 appointments were attended**
- **22,319 appointments were missed**
- Overall no-show rate was **20.19%**

### Gender Analysis

The dashboard compares appointment outcomes between male and female patients to identify differences in attendance patterns.

### SMS Reminder Analysis

Appointments were analyzed based on whether patients received SMS reminders, helping understand the relationship between reminders and appointment attendance.

### Age Analysis

Patients were grouped into age ranges to identify patterns in appointment attendance and no-shows.

### Neighbourhood Analysis

Appointment outcomes were analyzed across different neighbourhoods to identify areas with higher appointment volumes and no-show patterns.

### Weekday Analysis

Appointments were analyzed by weekday to identify differences in attendance across the week.

---

## 📁 Project Structure

```text
Healthcare-Appointment-No-Show-Analysis/
│
├── data/
│   └── medical_appointments.csv
│
├── notebook/
│   └── Healthcare_Appointment_No_Show_Analysis.ipynb
│
├── tableau/
│   └── Healthcare_Appointment_No_Show_Analysis.twbx
│
├── dashboard/
│   └── dashboard_screenshot.png
│
└── README.md