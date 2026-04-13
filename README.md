# 📊 Telecom Operator Efficiency Analysis

## 📌 Objective
Analyze telecom operator performance to identify inefficiencies and improve customer experience.

---

## 📂 Dataset
- Call records including:
  - Call direction (incoming / outgoing)
  - Call duration
  - Wait time
  - Operator ID
  - Missed calls

---

## 🔍 Key Insights

- Incoming calls have a higher missed rate than outgoing calls.
- A subset of operators concentrates inefficiency.
- Internal calls represent a very small portion of total volume.
- Clients contacted early (0–3 days) show significantly higher interaction.
- Some clients are repeatedly exposed to inefficient operators, indicating systemic issues.

---

## ⚠️ Data Quality Issue

- A large portion of calls is associated with an `unknown` operator_id.
- This may indicate:
  - Lack of proper call tracking
  - Lost accountability
  - Poor internal traceability
  - Potential negative impact on customer experience

---

## 📊 Dashboard

🔗 Tableau Public (interactive):
https://public.tableau.com/app/profile/marco.mart.nez2361/viz/TelecomOperatorEfficiencyAnalysis/KPIs?publish=yes

![Dashboard](images/dashboard.png)

---

## 🛠 Tools Used

- Python (Pandas, Matplotlib)
- Jupyter Notebook
- Tableau Public

---

## 📁 Project Structure
- data/ # raw data
- data_export/ # cleaned data
- notebooks/ # analysis
- images/ # dashboard(png)
