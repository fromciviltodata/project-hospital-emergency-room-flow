# Emergency-Room-Patient-Flow-Analysis (Interactive Dashboard Creation Using Power BI)

📊 This Power BI dashboard analyzes emergency room patient visits, wait times, admission rates, referral patterns, and demographic trends.
These insights help optimize resource allocation and improve patient care in the emergency department.

✅ Dataset Disclaimer:

Note: The original dashboard used a dataset with over 10,000 rows.
This version uses a sanitized dummy dataset for public sharing and learning purposes.

## Dataset Used
👉 [Dataset](https://github.com/fromciviltodata/project-hospital-emergency-room-flow/blob/main/Hospital_ER_dataset.csv)

## Question  (KPIs) 
    1. Measure the total number of patients visiting the ER daily.
    2. Calculate the average time a patient waits before being attended to medical professional.
    3. Analyze the average satisfaction score to evaluate service quality.
    4. Count the number of patients referred to specific departments.


## Charts to Develop 
    1. Track admitted vs. non-admitted patients (Admission Status).
    2. Group patients by 10-year age intervals (Age Distribution).
    3. Visualize referral trends across departments.
    4. Percentage of patients seen within 30 minutes.
    5. Distribution of patients by gender.
    6. Distribution of patients by race.
    7. Patient volume trends by day and hour.


## Steps Followed in Power BI:

    * Imported Excel dataset containing patient records and demographics.
    * Cleaned data in Power Query (renamed columns, removed nulls/blanks).
    * Created calculated columns and measures (e.g., Age Groups, Wait Time, Admission Status).
    * Built a separate Date Table for accurate time-based calculations (day, month, hour).
    * Replaced gender initials with full forms; added full name column.
    * Designed four report pages: Monthly View, Consolidated View, Patient Details, Analytical Highlights.
    * Replaced real data with dummy file for GitHub upload.
    * Updated dashboard visuals and summaries to match the dummy data.


## Dashboard
👉 [📊 View Dashboard](https://github.com/fromciviltodata/project-hospital-emergency-room-flow/blob/main/Dashboard_image)

## Project Insight
* Average patient wait time exceeds 30 minutes, indicating a need for process improvement.
* General Practice and Orthopedics are the most referred departments — may require more resources.
* Peak traffic times highlight critical staffing hours.
* Admission pattern is nearly evenly split between admitted and non-admitted patients.
* Age and racial distributions can inform patient care strategies for satisfaction and accessibility.


## Final Conclusion
Elderly patients reported slightly lower satisfaction scores, suggesting a need for better care practices or communication.  
Peak inflow patterns indicate that increasing staffing during high-demand periods could improve efficiency and patient experience.  

## Future Scope
This dashboard can be enhanced in the future by integrating Power BI’s built-in forecasting feature.  
Alternatively, predictive modeling techniques could be used to anticipate patient volume trends and support proactive staffing decisions.
