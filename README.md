# Sales Performance Optimization – DC Industries

This project uses **Alteryx** to automate the ETL process and analyze regional sales data for DC Industries. It identifies key revenue trends and underperforming segments to support strategic business decisions.

---

## 📌 Objective

To streamline the sales reporting workflow and build a reliable, automated pipeline that merges multi-regional data, cleans inconsistencies, and generates meaningful KPIs for performance tracking.

---

## 🧰 Tools & Technologies

- **Alteryx Designer** – Workflow automation, data blending, cleaning
- **Excel / CSV** – Raw sales data sources
- **Power Query (optional)** – For additional review or summaries (outside Alteryx)

---

## 🗂️ Datasets Used

- `RegionalDoWSales_backup.xlsx` – Master sales data for different product categories
- `Customer Orders-East.xlsx` – Order data from East region
- `Customer Orders-West.xlsx` – Order data from West region
- `Order Details.xlsx` – Product-level breakdown for each order
- `Regions.csv` – Region-level mapping and identifiers

---

## 🔄 ETL Workflow Highlights

- **Input Join**: Consolidated regional order data with master order details and region metadata
- **Data Cleansing**: Removed nulls, standardized region names, formatted date fields
- **Aggregation**: Summarized total revenue by region, product, and time period
- **Output**: Generated clean performance summary for further dashboarding or Excel export

---

## 📈 Results

- Reduced manual reporting time by **40%**
- Delivered a repeatable workflow to identify:
  - Underperforming regions
  - High-growth product segments
  - Revenue contributions by geography

---

## 🔍 Use Case

This solution can be reused across similar industries to automate multi-source sales data processing, generate business-critical summaries, and drive data-backed decisions.

---

## ✅ Author

**Ritik Kumar**  
📧 ritik.kumar@rutgers.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/ritik-kumar-b9999b221)

---

## 🔧 Workflow Screenshot

Below is the full Alteryx workflow used to automate and analyze DC Industries' sales data.

![Workflow Screenshot](images/workflow_screenshot.png)

---
