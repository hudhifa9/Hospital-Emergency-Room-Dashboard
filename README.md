# 🏥 Hospital Emergency Room Dashboard

## Overview

This project features an interactive **Hospital Emergency Room Dashboard** designed to provide critical insights into ER operations, patient flow, and key performance indicators. The dashboard aims to assist hospital administrators and medical staff in monitoring efficiency, improving patient experience, and optimizing resource allocation within the emergency department.

## Key Features & Insights

The dashboard is structured into three distinct views, offering different levels of granularity and focus:

### 1. Monthly View

This view provides a snapshot of ER performance for a selected month and year, allowing for month-over-month comparisons.

* **No. of Patients:** Total patient count for the selected month.
* **Avg Wait Time:** Average waiting time for patients.
* **Patient Satisfaction Score:** Key metric for patient experience.
* **No. of Patients Referred:** Count of patients referred from other departments or facilities.
* **Patient Admission Status:** Breakdown of admitted vs. not admitted patients.
* **% of Patient Seen Within 30 Min:** Compliance rate for rapid patient assessment, crucial for emergency care.
* **No. of Patients by Gender:** Distribution of patients by gender.
* **No. of Patient by Day & Hour:** Detailed heatmap-like view showing patient volume by day of the week and hour of the day, helping identify peak hours.
* **No. of Patient by Patient Race:** Demographic breakdown of patients.
* **No. of Patient by Department Referral:** Origin of patient referrals to the ER.
* **No. of Patient by Age Group:** Distribution of patients across different age categories.
* **Interactive Filter:** Allows selection of `Month & Year` for focused analysis.

### 2. Consolidated View

This view offers an aggregated perspective of ER performance over a broader date range, providing a macro-level understanding of trends.

* **Aggregated Metrics:** Similar core metrics as the Monthly View (No. of Patients, Avg Wait Time, Patient Satisfaction Score, No. of Patients Referred), but calculated for the entire selected period.
* **Overall Admission Status:** Total admitted vs. not admitted patients across the consolidated period.
* **Overall % of Patient Seen Within 30 Min:** Overall compliance with the 30-minute target.
* **Overall Patient Demographics:** Consolidated views of patients by Gender, Race, Department Referral, and Age Group.
* **No. of Patient by Day & Hour (Consolidated):** Provides an overall pattern of patient visits by day and hour across the entire period.
* **Interactive Filters:** Allows selection of a `Start Date` and `End Date` to define the consolidated period.

### 3. Patients Details

This section provides a tabular, detailed list of individual patient records, useful for granular lookups and data verification.

* **Comprehensive Patient Information:** Includes `Patient ID`, `Patient Name`, `Patient Gender`, `Patient Age`, `Patient Admin Date`, `Patient Race`, `Patient Waittime`, `Department Referral`, and `Admission Status`.
* **Data Table Format:** Presents raw data clearly, enabling specific patient queries.

## Technologies Used

* **Microsoft Power BI:** Utilized for data modeling, interactive visualizations, and dashboard creation.

## How to View the Dashboard

To interact with this Power BI dashboard:

1.  **Download Power BI Desktop:** Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed on your computer.
2.  **Clone this repository:**
    ```bash
    git clone [https://github.com/YourUsername/Hospital_ER_Dashboard.git](https://github.com/YourUsername/Hospital_ER_Dashboard.git)
    ```
    (Please replace `YourUsername/Hospital_ER_Dashboard.git` with your actual GitHub repository URL.)
3.  **Open the `.pbix` file:** Navigate to the cloned directory and open the `Hospital Emergency Room Dashboard.pbix` file using Power BI Desktop.

## Data Source

The analysis is based on a simulated or anonymized dataset containing emergency room visit records. This dataset includes information on patient demographics, admission details, wait times, and referral sources, crucial for operational analysis.
*(If your data source is public or has specific attributes you can share, you might want to add more detail here, e.g., "Data obtained from [source name/link]...")*

## Potential Future Enhancements (Optional)

* Integrate real-time data feeds for live monitoring.
* Implement predictive models for forecasting patient volume.
* Add more granular analysis on specific medical conditions or treatments.
* Develop an alert system for critical metrics deviations.

---

**Explore the insights and contribute to better emergency care management!**

---