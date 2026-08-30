# Superstore Sales Analytics & AWS Pipeline

**About The Project**
This project presents an end-to-end data analytics solution and technical pipeline built to evaluate sales performance, profit margins, regional growth, and discounting impacts for the global Superstore dataset.

The primary goal of this capstone project was to ingest raw sales data, clean and format the records, store the dataset securely on cloud infrastructure using AWS S3, build interactive executive dashboards in Google Sheets and Amazon QuickSight, and deliver actionable business recommendations.

**Key Findings**

* **Consistent Annual Growth:** Total annual sales steadily expanded from $484,247.52 (2011) to $733,947.13 (2014), accompanied by profit growth from $49,543.99 to $93,507.51.
* **Furniture Margin Erosion:** Despite generating high sales ($741,999.76), the Furniture category yielded only a 2.49% profit margin due to aggressive discounting on Tables (-$17,725.47 net profit; 26.13% avg discount) and Bookcases (-$3,472.55 net profit; 21.11% avg discount).
* **Regional Discount Impact:** The Central region experienced significant margin suppression (7.92% margin) due to a high average discount rate (24.04%), whereas the West region maintained lower discounting (10.93%) and achieved the highest regional margin (14.94%).
* **Top Performers & Revenue Champions:** The *Canon imageCLASS 2200 Advanced Copier* was the single most profitable product catalog item ($61,599.98 sales; $25,199.94 profit). High-margin champions included the *Ativa V4110MDD Micro-Cut Shredder* (49% profit margin).
* **Strong Seasonality:** Sales activity exhibits a predictable end-of-year surge, peaking significantly during the fall and winter months (Q4).

**Repository Contents**

* `Superstore.csv` — Raw dataset downloaded from Kaggle.
* `FinalCapstoneProject_NgonidzasheRoselyneKazonda.pdf` — Complete capstone project documentation, data preparation methodology, and technical architecture details.
* `Architecture Diagram.png` — Conceptual visualization outlining data flow from Kaggle → AWS S3 / Google Sheets → Amazon QuickSight / Google Sheets Dashboards → Final Report.

**Remediation & Recommendations**

1. **Implement Disciplined Discount Policies:** Review Furniture category pricing, specifically reducing aggressive promotions on Tables and Bookcases to protect operational margins.
2. **Focus on High-Efficiency Products:** Prioritize marketing and inventory resources for products that demonstrate high revenue-to-profit conversion (such as top-performing copiers and shredders).
3. **Capitalize on Seasonal Trends:** Scale inventory levels, warehouse staffing, and customer support resources ahead of Q4 to maximize revenue capture without service degradation.
4. **Standardize Regional Guardrails:** Implement discount caps in the Central region to prevent margin compression relative to overall sales volume.

