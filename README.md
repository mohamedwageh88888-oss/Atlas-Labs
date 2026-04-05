# Atlas Labs: HR Analytics Dashboard

![Dashboard Overview](https://via.placeholder.com/800x400?text=Atlas+Labs+Dashboard+Preview) 

## 📌 Project Overview
This repository contains the data model and report configuration for the **Atlas Labs HR Analytics Dashboard**. The project focuses on monitoring **Employee Attrition** and demographic trends to help HR leaders make data-driven decisions regarding retention and workplace culture.

The dashboard provides a comprehensive view of why employees leave, identifying high-risk groups based on job roles, travel requirements, and overtime frequency.

---

## 📊 Key Insights & Metrics

### 1. Attrition Overview
*   **Total Attrition Rate:** Currently standing at **16%**.
*   **Active vs. Inactive:** The organization maintains **1,233 active employees** against **237 inactive** records.
*   **Departmental Split:** The **Technology** department holds the largest share of the workforce (828 employees), followed by Sales (354) and HR (51).

### 2. High-Risk Indicators
*   **Overtime Impact:** Employees working overtime face a **31% attrition rate**, nearly triple the rate of those who do not (10%).
*   **Job Roles:** **Sales Representatives (40%)** and **Recruiters (38%)** exhibit the highest turnover levels.
*   **Tenure:** The "New Hire" phase is critical; employees with **less than 1 year** of seniority have a **34%** likelihood of leaving.
*   **Travel:** **Frequent Travelers** have a significantly higher attrition rate (**25%**) than those who travel rarely or not at all.

### 3. Demographics
*   **Age Range:** Employees range from **18 to 51 years old**.
*   **Diversity:** The dashboard tracks salary and headcount across various ethnicities, with the **White** and **Black/African American** groups representing the largest cohorts.
*   **Marital Status:** **Married** employees make up the largest portion of the workforce at **42%**.

---

## 🛠️ Technical Stack
*   **Platform:** Power BI Desktop
*   **Data Source:** Internal HR Management System (HRMS)
*   **Theme:** Custom JSON Base Theme (`CY26SU02.json`)
*   **Data Modeling:** Star Schema with centralized `DataModel` bindings.

---

## 📂 File Structure
*   `[Content_Types].xml`: Content type definitions for the Power BI package.
*   `Report/Layout`: Contains the visual coordinates and properties for all charts.
*   `Report/StaticResources`: Contains the branding assets and theme files.
*   `DataModel`: The underlying relationship schema and DAX measures.
*   `SecurityBindings`: User access and row-level security configurations.

---

## 🚀 How to Use
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/atlas-labs-hr-analytics.git](https://github.com/your-username/atlas-labs-hr-analytics.git)
    ```
2.  **Open in Power BI:** Open the `.pbix` file (reconstructed from source) in Power BI Desktop.
3.  **Data Refresh:** Ensure your credentials are set in *Data Source Settings* to pull the latest employee records.
4.  **Interact:** Use the navigation header (**Overview, Demographics, Performance, Attrition**) to filter the data.

---

## 💡 Recommendations for HR
*   **Retention Program:** Target Sales Reps and Recruiters with specialized retention bonuses or career pathing.
*   **Overtime Audit:** Review workloads in departments where overtime is mandatory to reduce burnout-driven exits.
*   **Onboarding:** Enhance the 90-day onboarding experience to address the high attrition seen in the first year of tenure.

---
*Created by the Atlas Labs Data Team.*
