# 🇮🇳 Aadhaar Operations Dashboard: Identifying Compliance Gaps & Infrastructure Bottlenecks

### 🚀 Project Overview
This project analyzes **3 Million+ biometric records** to identify critical inefficiencies in the Aadhaar update ecosystem. We discovered a massive disparity between "Enrollment-Heavy" states (Scholarship Blockers) and "Update-Heavy" states (Operational Tsunamis).

**Live Dashboard:** [Link to your Power BI Dashboard or Screenshot]

---

### 🔍 Key Problem Statements
**1. The "Operational Tsunami" (Infrastructure Overload)**
* **Context:** States like Uttar Pradesh and Bihar are facing a 15x surge in biometric updates compared to new enrollments.
* **Impact:** Centers are crashing due to mixed queues (Updates vs. Enrollments).
* **Solution:** Proposed "Express Update Kiosks" to offload 90% of the traffic.

**2. The "Scholarship Blockers" (Compliance Risk)**
* **Context:** Border states like Sikkim and J&K show <1% update compliance for students aged 5-17.
* **Impact:** Students are at high risk of scholarship rejection due to outdated biometrics.
* **Solution:** Proposed "Mobile Awareness Camps" in schools for targeted intervention.

---

### 📊 Data Insights
* **Total Records Analyzed:** 31 Million Updates vs. 2 Million Enrollments.
* **The "July Effect":** Identified a 400% spike in updates during July, correlating with the school admission cycle.
* **Critical Gaps:** Sikkim and J&K identified as "Zero Compliance Zones" (0.00% - 0.35% Workload Ratio).

---

### 🛠️ Tech Stack
* **Data Processing:** Python (Pandas) for cleaning and merging 36 state datasets.
* **Visualization:** Power BI (Custom Measures, Top N Filtering, KPI Cards).
* **Data Source:** UIDAI Public Datasets (2017-2018).

---

### 📂 File Structure
* `enrollment_data.csv` - Raw data for new enrollments (0-5, 5-18, 18+).
* `biometric_data.xlsx` - Biometric update logs by state and district.
* `dashboard_v1.pbix` - The final Power BI file.

---

### 💡 How to Run
1.  Download the `.pbix` file.
2.  Open in **Power BI Desktop**.
3.  Refresh the data source to view the interactive visuals.
