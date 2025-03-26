# 📈 Understanding Dynamics of Diabetes and Hyperlipidemia in the US Population

## 🏥 Project Overview
This project explores the **prevalence and relationship between diabetes and hyperlipidemia** in the US population using data from the **National Health Interview Survey (NHIS) (2017-2021)**. The interactive **Tableau dashboard** allows users to analyze trends by filtering key demographic variables like **age and sex**.

## 🔍 Motivation
This was an **exploratory self-project** to gain hands-on experience in **healthcare data science** and develop a **data-driven approach** to understanding a well-researched medical topic.

## 📂 Dataset Details
- **Source:** National Health Interview Survey (NHIS) (2017-2021)
- **Key Variables Analyzed:**
  - **Age:** Continuous variable (capped at 85 for anonymity)
  - **Sex:** 0 = Female, 1 = Male
  - **Diabetes Status:**
    - 0 = No Diabetes  
    - 1 = Diagnosed with Diabetes  
    - 2 = Prediabetic  
  - **Hyperlipidemia (High Cholesterol):**
    - 0 = No  
    - 1 = Yes  
- **Data Cleaning & Transformations:**
  - Adjusted variable names for **better readability**.
  - Recoded categorical responses for **clarity and consistency**.
  - **Excluded invalid responses** (e.g., refused to answer, unknown responses) to maintain accuracy in the analysis.

## 📁 Project Structure
| Files | Description |
|------|------------|
| `NHIS Dashboard.twb` | Tableau Workbook containing **two worksheets** and **one interactive dashboard**. |
| `snapshots/` | Folder with **various screenshots** of the dashboard in different filtering conditions (e.g., by sex, by age). |
| `README.md` | This documentation file explaining the project. |

## 📊 Tableau Dashboard Overview
The **interactive dashboard** provides insights into diabetes and hyperlipidemia trends in the US:
- **Worksheet 1**: Basic demographic variables - **age and sex**.
- **Worksheet 2**: A **horizontal line graph** depicting the number of people with diabetes, further broken down by hyperlipidemia status.
- **Dashboard**: Users can **interactively filter** by demographics (e.g., selecting only males or a specific age group) to see how diabetes and high cholesterol distribution change.

---

## 📸 Dashboard Snapshots  

Below are different visual perspectives of the Tableau dashboard:  

### 🗂 **General Overview**  
![General Overview(screenshots/General Overview.png)](https://github.com/Aakash-U/Tableau-Dashboard-For-National-Health-Interview-Survey/blob/main/screenshots/General%20Overview.png?raw=true)

### 📊 **Workbook Views**  
- **Workbook 1:**  
  ![Workbook 1(screenshots/Workbook 1.png)](https://github.com/Aakash-U/Tableau-Dashboard-For-National-Health-Interview-Survey/blob/main/screenshots/Workbook%201.png?raw=true)  

- **Workbook 2:**  
  ![Workbook 2(screenshots/Workbook 2.png)](https://github.com/Aakash-U/Tableau-Dashboard-For-National-Health-Interview-Survey/blob/main/screenshots/Worrkbook%202.png?raw=true)

### 👩‍⚕️ **Gender-Based Analysis**  
- **Only Females:**  
  ![Only Females(screenshots/Only Females.png)](https://github.com/Aakash-U/Tableau-Dashboard-For-National-Health-Interview-Survey/blob/main/screenshots/Only%20Females.png?raw=true)  

- **Only Males:**  
  ![Only Males(screenshots/Only Males.png)](https://github.com/Aakash-U/Tableau-Dashboard-For-National-Health-Interview-Survey/blob/main/screenshots/Only%20Males.png?raw=true)  

### 🎯 **Age-Specific Analysis**  
- **Age = 26:**  
![Age 26(screenshots/Age 26.png)](https://github.com/Aakash-U/Tableau-Dashboard-For-National-Health-Interview-Survey/blob/main/screenshots/Age%3D%2026.png)

- **Age = 57:**  
  ![Age 57(screenshots/Age 57.png)](https://github.com/Aakash-U/Tableau-Dashboard-For-National-Health-Interview-Survey/blob/main/screenshots/Age=%2057.png?raw=true)  

---

### 🖥️ How to View the Dashboard
1. **If you have Tableau Desktop**:
   - Download `NHIS Dashboard.twb` from the repo.
   - Open it in **Tableau Desktop**.

2. **If you don’t have Tableau**:
   - View the **screenshots** in the `screenshots/` folder.
   - Or use **Tableau Public** (if applicable).

## 📌 Acknowledgments
**Credit to NHIS** for conducting a comprehensive health survey and providing valuable data for research and analysis.

---
💡 *Feel free to reach out if you have any questions or suggestions for future improvements!* 🚀

