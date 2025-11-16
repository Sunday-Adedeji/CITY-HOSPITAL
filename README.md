# 🏥 City Hospital Data Analysis Project 
A data-driven analytics project focused on improving financial performance, operational efficiency, and workforce insights for a modern healthcare institution.

### *A Power BI project for financial and operational intelligence*
---

## 📘 Project Overview  
City Hospital, a renowned medical institution, recognised the growing need to **leverage data for better financial and operational decision-making**.  
For years, strategic choices were driven by intuition and historical trends, leaving room for inefficiencies, resource imbalance, and lost opportunities.  

This project uses **Microsoft Power BI** to transform their Excel-based transaction data into **interactive, data-driven dashboards** that reveal financial health, doctor and patient performance, and hospital-wide insights.  

---

## 🧩 Tools & Data  
- **Tool Used:** Power BI  
- **Data Source:** Excel (Hospital Transaction Dataset)  
- **Core Process:**
  1️⃣ Data Cleaning and Integration  
  2️⃣ Data Modelling and Relationship Building  
  3️⃣ DAX Calculations for Key Metrics  
  4️⃣ Interactive Dashboard Creation  

---

## 🗂️ Dataset Structure  
The dataset included financial, procedural, and demographic information for both **doctors and patients**, with columns such as:

| Column Name | Description |
|--------------|-------------|
| TransactionID | Unique identifier for each hospital transaction |
| Date | Date of the transaction |
| RevenueAmount | Total revenue from a procedure |
| ExpensesAmount | Total cost of the procedure |
| Doctor_FirstName / LastName | Doctor’s name |
| Doctor_Gender | Gender of the doctor |
| Specialty | Doctor’s medical specialty |
| PatientID | Unique identifier for each patient |
| Patients_FirstName / LastName | Patient’s name |
| Patients_Gender | Gender of the patient |
| ProcedureName | Name of the medical procedure |
| Category | Procedure category (e.g., Surgery, Radiology) |
| Country / City / State | Hospital location |
| PostalCode | Postal code of the hospital branch |

---

## 🎯 Project Objectives  
The goal was to equip City Hospital with **real-time, data-backed visibility** into its operations by addressing the following questions:

1️⃣ What are the **total revenue, expenses, and profit margins** over time?  
 2️⃣ Which **specialties and procedure categories** generate the most revenue or income?  
3️⃣ Who are the **top-performing doctors and high-impact patients**?  
4️⃣ How do **gender, specialty, and state** influence performance?  
5️⃣ What is the **trend of patient visits and doctor distribution** over time?  

---

## 📊 Dashboard 1: Hospital Transaction Dashboard  
### *Focus: Financial Health and Revenue Trends*

**Key KPIs:**
- 💰 **Total Revenue:** $274K  
- 💸 **Total Expenses:** $189K  
- 💹 **Total Profit:** $84.14K  
- 📈 **Profit Margin:** 30.8%  
- 👨‍⚕️ **No. of Doctors:** 81  
- 🧍‍♂️ **No. of Patients:** 86  

**Insights:**  
- Profit margin remains stable at ~31%, indicating efficient cost control.  
- Dermatology, Cardiology, and Neurology are the most profitable specialties.  
- Wellness and Radiology categories lead total revenue generation.  
- Year 2022 marked the **highest quarterly growth**, followed by a dip in 2023, signaling possible operational slowdowns.  

**Dashboard Preview:**  
[Hospital Transaction Dashboard - Main](<img width="1377" height="746" alt="image" src="https://github.com/user-attachments/assets/0f19eb09-96d3-4ad2-9456-23eb42b07a3b" />)

**Filter Highlights:**  
| Filter | Dashboard Preview | Observation |
|--------|-------------------|----------------|
| 👩‍⚕️ Doctor Gender – Female | ![Female Doctors Filter](<img width="1280" height="695" alt="image" src="https://github.com/user-attachments/assets/edb1ff6e-b790-4396-8797-b9b16fef2aaa" />
) | Female doctors generated ~$130K revenue (~47% share). |
| 👨‍⚕️ Doctor Gender – Male | ![Male Doctors Filter](<img width="1280" height="691" alt="image" src="https://github.com/user-attachments/assets/3221e38f-e92e-4e1b-8df9-8cecf0e83660" />
) | Male doctors led with ~$144K revenue, slightly higher profit margin. |
| 👩 Patients – Female | ![Female Patients Filter](<img width="1280" height="693" alt="image" src="https://github.com/user-attachments/assets/9674edaf-2aff-433b-aa2e-b61b472d9847" />
) | Strong engagement in Dermatology and Cardiology. |
| 👨 Patients – Male | ![Male Patients Filter](<img width="1280" height="692" alt="image" src="https://github.com/user-attachments/assets/fac11766-aeb6-4fd3-96b6-b2e2e79bff14" />
) | Neurology procedures dominated male patient revenue. |
| 📍 California | ![California State Filter](<img width="1280" height="692" alt="image" src="https://github.com/user-attachments/assets/7f062b1e-20c3-4ece-89a6-62fa6b9d6102" />
) | Outperformed New York in overall revenue and efficiency. |
| 📍 New York | ![New York State Filter](<img width="1280" height="690" alt="image" src="https://github.com/user-attachments/assets/ccf85cf7-d07c-4745-8ce0-c5aad013e0dc" />
) | Dermatology was the leading department. |
| 📅 2021 | ![Year 2021 Filter](<img width="1280" height="695" alt="image" src="https://github.com/user-attachments/assets/b8fcabd4-764a-4dcc-9ce1-ace940cbbe6f" />
) | Post-pandemic recovery, lowest annual revenue. |
| 📅 2022 | ![Year 2022 Filter](<img width="1280" height="690" alt="image" src="https://github.com/user-attachments/assets/544521ea-0194-43ac-bd3e-429a5dd09572" />
) | Peak operational performance. |
| 📅 2023 | ![Year 2023 Filter](<img width="1280" height="699" alt="image" src="https://github.com/user-attachments/assets/58c42ffb-ff06-4895-b5d9-bdf0c2384f4c" />
) | Noticeable decline, warrants investigation. |

---

## 📊 Dashboard 2: Hospital Performance Dashboard  
### *Focus: Workforce, Patient Distribution, and Specialty Mix*

**Key KPIs:**
- 💰 **Total Revenue:** $274K  
- 💸 **Total Expenses:** $189K  
- 💹 **Total Profit:** $84.14K  
- 📊 **Profit Margin:** 30.8%  
- 👨‍⚕️ **Doctors:** 81 (39 Female, 42 Male)  
- 🧍‍♂️ **Patients:** 86 (47 Female, 39 Male)

**Top 5 Doctors (by Revenue):**
| Doctor | Revenue |
|--------|----------|
| Ava Adams | $25K |
| Liam Thompson | $20K |
| Benjamin Lee | $16K |
| Emma White | $13K |
| William Scott | $12K |

**Top 5 Patients (by Revenue):**
| Patient | Revenue |
|----------|----------|
| Harper Lewis | $17K |
| Ethan Clark | $15K |
| Mia Williams | $13K |
| Mia Anderson | $12K |
| Olivia Brown | $12K |

**Dashboard Preview:**  
**Hospital Performance Dashboard** <img width="1280" height="692" alt="image" src="https://github.com/user-attachments/assets/8f715a36-1db3-4569-a6db-3e38f5b6ece0" />

**Filter Highlights:**  
| Filter | Dashboard Preview | Observation |
|--------|-------------------|--------------|
| 👩‍⚕️ Female Doctors | <img width="1280" height="690" alt="image" src="https://github.com/user-attachments/assets/d31ef2e0-ba22-47eb-8338-dfb91373368e" /> | Ava Adams led with $25K revenue. |
| 👨‍⚕️ Male Doctors | <img width="1280" height="690" alt="image" src="https://github.com/user-attachments/assets/1b83cb16-12b6-4944-bff5-4235bbef303b" /> | Liam Thompson generated the highest $20K revenue. |
| 👩 Female Patients | <img width="1280" height="693" alt="image" src="https://github.com/user-attachments/assets/ecbd600f-b764-4918-ab8b-9a440ae6c297" /> | Female patients had higher visit frequency. |
| 👨 Male Patients | <img width="1280" height="688" alt="image" src="https://github.com/user-attachments/assets/88bf85dc-52fa-4649-96d2-029c5160c815" /> | Male patients contributed more to overall revenue. |
| 📍 California | <img width="1280" height="693" alt="image" src="https://github.com/user-attachments/assets/1a4f2c7c-ba02-4e5d-bd43-e9c6347df92f" /> | Most patient interactions from Neurology and Cardiology. |
| 📍 New York | <img width="1280" height="692" alt="image" src="https://github.com/user-attachments/assets/ad82a608-7d0c-45e7-a261-fe9be5b7845a" /> | Dermatology and Radiology dominated revenue. |
| 📅 2021 | <img width="1280" height="690" alt="image" src="https://github.com/user-attachments/assets/7fe5be1b-8cfe-4f12-8c94-374b5c8649ac" /> | Limited operations but balanced gender distribution. |
| 📅 2022 | <img width="1280" height="691" alt="image" src="https://github.com/user-attachments/assets/5e5be9ff-98cc-431b-817a-57b9c668b4d9" /> | Record-breaking year with highest profit. |
| 📅 2023 | <img width="1280" height="691" alt="image" src="https://github.com/user-attachments/assets/78de86e7-720e-4fee-9556-a3100a3e0f5d" /> | Decline in both doctor engagement and patient visits. |

---

## 📈 Key Insights & Recommendations  

### 🔹 Financial Insights  
- Maintain Dermatology, Cardiology, and Neurology as **core specialties** — they account for over 60% of total profit.  
- **Revisit underperforming categories** like General Medicine and Surgery.  
- **Monitor quarterly dips (2023)** for root-cause analysis — possibly linked to doctor capacity or patient churn.

### 🔹 Operational Insights  
- Gender balance is healthy, but **female doctors show higher patient retention**.  
- Encourage **cross-department referrals** among top-performing specialties.  
- Consider **targeted campaigns** in underperforming states (New York).

### 🔹 Strategic Recommendations  
1️⃣ Launch a performance-based incentive program for top doctors.  
2️⃣ Harness data-driven strategies and regular monitoring to reduce idle capacity.  
3️⃣ Expand marketing or ads for profitable procedures in high-margin departments.  
4️⃣ Automate reporting with Power BI to track monthly KPIs.  

---

## 🧠 Learning Outcome  
This project enhanced my proficiency in:
- Data cleaning, transformation, and DAX measures in Power BI.  
- Designing interactive dashboards that merge **financial** and **operational KPIs**.  
- Translating complex datasets into **clear, actionable healthcare insights**.  

---

⚠️ Disclaimer

This project is for educational and portfolio demonstration only. The data is simulated and does not represent any real organisation.

---

### 🔗 Connect With Me
Sunday A. Adedeji
📧 sundayadedeji001@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/sunday-adedeji/) 
📊 **Full Dashboard File:** *(https://app.powerbi.com/links/qD64UJkcln?ctid=009b81c9-9d54-4181-bd95-cf7f6d431b86&pbi_source=linkShare)*
