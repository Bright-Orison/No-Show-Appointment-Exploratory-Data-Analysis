# No-Show-Appointment-Exploratory-Data-Analysis

## **Overview of the Project**
This project analyses the No-Show Appointment Dataset. The original source of the dataset is from Kaggle.com. The purpose of this analysis is to identify the relationship between probability of showing up at appointment days and some variables that could affect it.

## **Questions for analysis**
- Which patient categories are more?
- What is the turn-up rate with respect to Gender and AgeGroup?
- How prone is gender and age group categories to specific diagnosis?
- Which month and day are patients more likely to turn-up at the hospital?
- What is the correlation between varriables and the dependent variable [No-Show]?

## **Overview of Variables**
The variables in the dataset are:

- PatientID: This is a unique identifier of every patient that books an appointment
- AppointmentID: A unique identifier of a patient's slot when they book an appointment
- Gender: Whether patient is male or female
- SheduleDay: The day the patient called the facility to book an appointment
- AppointmentDay: The actual day given to the client to meet a doctor
- Age: Patient's age
- Neighbourhood:location of the hospital
- Scholarship: This indicates if the patient is enrolled on a Brazilian welfare program or not
- Hypertention: whether or not the patient has the disease
- Diabetes: whether or not the patient has the disease
- Alcoholism: whether or not the patient has an issue of alcoholism
- Handicap: The level of handicap rated from 0 to 4
- SMS_Received: shows whether the patient has received an SMS reminder or not
- No_Show: 'No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

## **Summary of the findings**
From the analysis, it can be concluded that:

- About 79.8% of the total number of patients who booked appointment showed up on schedule and 20.2% of them did not show up
- About 65% of patients are females whereas 35% are males
- Comparatively, both males and females have an almost equal turn up rate on appointment days. ie 79.67% and 79.69% respectively. However, more females visit the hospital more often than males
- Patients between the ages of 0-17 are the highest to show up during appointments whereas 18-36 age groups are the highest who do not turn up on appointment days
- More patients seems to be diagnosed of not having diabetes, alcoholism and handicap than men. Out of the 110521 patients diagnosed for Diabetes, 92.81% of them do not have. Again, out of the 102578 diabetes patients that scheduled appointment, only 79.64% showed up.
- 96.95% of patients tested for alcoholism do not have and only 3.05% have. 79.81% of the total patients who do not suffer alcoholism were present on schedule however 79.85% of those diagnosed to have issues with alcoholism turned up on the appointment day
- More females than men were diagnosed of diabetes.
- The age group of 55-80 are the highest positive diabetes patients followed by the agegroup of 37-54
- Wednesdays have seen the highest level of turn-up on appointment days. Tuesdays on the other hand recorded the day patients do not show up for appointment the most
- May recorded the highest month where most patients showed up for their appointment

## **Limitations**
The following limitations were identified in the dataset

1. The data did not provide information about the location of patient neither their distance from the hospital so it was difficult to analyse the nighbourhood variable.
2. Much details was not provided about the the handicap variable so it was difficult to explain the levels
3. Most of column variables were categorical which limits further analysis of the variables and how they may affect the dependent variable
