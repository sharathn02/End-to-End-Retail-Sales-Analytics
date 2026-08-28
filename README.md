## NovaMart Sales Efficiency & Growth Analysis  

### **Problem**
NovaMart faces significant revenue inefficiencies, highlighted by a ₹30.5M gap against its sales target. This challenge is amplified by broad, un-targeted promotional spending, high inventory complexity from product/supplier fragmentation, and inconsistent operational performance across different regional markets.
### **Dataset**
A multi-format retail business dataset consisting of raw CSV, Excel, TSV, and JSONL files containing transaction logs, store characteristics, geographic regions, monthly sales/profit targets, customer demographics, and product details.
### **Approach**
Built an end-to-end data pipeline starting with Python (Pandas & SQLAlchemy) to ingest multi-format files into a PostgreSQL staging environment. Developed robust SQL transformation layers to clean, deduplicate (via window functions), and handle missing values. Engineered a structured star-schema analytical warehouse consisting of five dimension tables (dim_customers, dim_stores, dim_products, dim_date) and two fact tables (fact_sales, fact_targets) to conduct diagnostic commercial analysis.
### **Dashboard**
An analytical warehouse environment and business reporting framework mapped to evaluate store-level monthly targets, track customer value metrics, assess SKU density, and compare regional performance matrices. (Note: Paste your Power BI/dashboard screenshot or embed link here to complete this section).
### **Key Findings**
  * **Target Achievement:** Diagnosed a stark ₹30.5M deficit between actual performance and sales targets.
  * **Customer Value:** Established critical baseline metrics showing an Average Order Value (AOV) of ~₹3K and an overall annual value of ₹42.79K per customer.
  * **Assortment Fragmentation:** Identified extreme catalog fragmentation with 150 unique products spread across 147 different brands, leading to unnecessary inventory complexity.
   * **Regional Variation:** Uncovered pockets of highly successful, top-performing stores concentrated in specific cities, contrasting sharply with underperforming markets.
### **Recommendations**
  * **Precision Targeting:** Pivot away from blanket promotions and redirect capital and marketing resources specifically toward underperforming regions and high-margin product categories.
   * **Basket-Size Expansion:** Deploy product bundling, cross-selling strategies, and personalized recommendations to increase the current ~₹3K Average Order Value.
   * **SKU Rationalization:** Aggressively eliminate underperforming items and consolidate suppliers to decrease product fragmentation and lower backend inventory costs.
   * **Operational Playbooks:** Standardize the merchandising and operational practices of top-performing stores into repeatable playbooks to scale up weaker regional markets.
 ### **Tools**
Python, Pandas, SQLAlchemy, PostgreSQL, SQL (PostgreSQL dialect), Jupyter Notebook, MS Excel / CSV / JSONL.

### **Screenshots:**  
**Executive Overview**  
<img width="1290" height="726" alt="Executive Overview BI" src="https://github.com/user-attachments/assets/c3c06981-5c26-481d-9302-9a95d0786ef9" />
**Store Analysis**  
<img width="1293" height="731" alt="Store Analysis BI" src="https://github.com/user-attachments/assets/1919c82d-50b3-466c-85b8-8992edca87ed" />
**Product Analysis**  
<img width="1291" height="736" alt="Product Analysis BI" src="https://github.com/user-attachments/assets/9a9da500-d930-4ca1-a02c-59e6ad3be8e1" />
**Customer Analysis**  
<img width="1290" height="732" alt="Customer Analysis BI" src="https://github.com/user-attachments/assets/af374cbb-0dd9-4829-aa5c-194157b1fc2b" />



