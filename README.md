# E-Commerce Sales & Operations Analysis 

---

### **Overview**
This project presents an end-to-end data analysis of an e-commerce retail business. The primary objective was to evaluate overall sales performance, analyze logistics and delivery efficiency, and understand customer purchasing behavior. The data originally consisted of three separate datasets (Orders, Customers, and Products). Through advanced data transformation, these datasets were consolidated to build a comprehensive interactive reporting tool that provides actionable business insights.

---

### **Business Questions Answered**
* What is the total sales amount generated in each country?
* What is the total quantity of items sold for each product across different countries?
* What is the average delivery time for each product?
* Are there specific products that consistently take longer to deliver than others?
* Which specific countries or provinces experience consistently long delivery times, and which enjoy fast deliveries?
* What is the average customer rating for each product?
* Who are the Top 10 customers in terms of total sales, what products did they purchase, and what is their exact percentage contribution to the overall total sales?
* What are the data-driven recommendations to optimize the business, prevent losses, and resolve current operational bottlenecks?

---

### **Tools Used**
* **Data Extraction & Transformation (ETL):** Used **Excel Power Query** to individually clean, transform, and format three raw tables, then combined them using the *Merge Queries* feature into a single consolidated master dataset.
* **Data Analysis & Aggregation:** Used **Excel Pivot Tables** directly on the consolidated dataset to aggregate metrics, calculate averages (like delivery days), and summarize total revenue and volume.
* **Data Visualization:** Designed an interactive 3-page dashboard utilizing advanced Excel charting features to present the findings clearly to stakeholders.

---

### **Process / Workflow**

**1. Data Cleaning & Pre-processing (Power Query):**
* Imported three raw tables: `Orders`, `Customers`, and `Products`.
* Processed each table individually (removing duplicates, handling missing values, standardizing text, and correcting data types).
* Used the **Merge Queries** function in Power Query to join the tables based on primary/foreign keys (e.g., Customer ID, Product ID), outputting a single unified `All Data` master sheet.

**2. Data Analysis & Aggregation (Pivot Tables):**
* Built a comprehensive network of standard Excel **Pivot Tables** sourced directly from the unified `All Data` sheet.
* Systematically answered the core business questions by aggregating critical metrics such as total sales, average delivery times, and the percentage contribution of the top 10 customers.

**3. Dashboard Design (3 Pages):**
* **Page 1 (Sales Overview):** A high-level dashboard focusing on total revenue, sales by country, and the performance of the Top 10 customers.
* **Page 2 (Operations & Logistics):** A detailed view tracking delivery times by product and geographic location, alongside average product ratings.
* **Page 3 (Key Insights & Recommendations):** A dedicated section summarizing the analytical findings and proposing strategic actions.
  
<img width="1520" height="892" alt="Sales" src="https://github.com/user-attachments/assets/19b4a9d8-30c4-4fa2-8214-af7fc18e3234" />
<img width="1681" height="887" alt="image_2026-08-16_01-39-50" src="https://github.com/user-attachments/assets/e2eb8564-92ad-4f83-9018-7709f717bc07" />
<img width="1522" height="892" alt="image" src="https://github.com/user-attachments/assets/136fb558-bbf4-41ce-b8b8-a7ed8ba6e147" />



---

### **Key KPIs**
* **Total Global Sales:** $14,461,529
* **Total Items Sold:** 7,899
* **Total Orders:** 3,472
* **Average Delivery Time:** 8 Days

---

### **Key Insights**

* **Geographic Sales:** KSA (Saudi Arabia) generated the highest total sales at **$4,999,926**, representing the largest market share, followed by Iraq ($3,468,905).
* **Product Performance:** **Jeans** is the absolute volume champion with 1,207 units sold, closely followed by Ties (1,173 units) and Bags (1,002 units).
* **Payment Preferences:** The "Hawala" payment method dominates the transactions, accounting for **42%** of the total revenue, while Direct Debit (DC) and Master Card (MC) account for 20% each.
* **Customer Concentration:** The Top 10 clients (led by Catherine Terrell and Zahir Spears) contribute a combined **~3.6%** of total revenue.
* **Logistics (Locations):** Delivery efficiency is remarkably standardized and consistent across all operating countries (EGY, Iraq, SYR, UAE, KSA), with every region averaging exactly **8 days** for delivery.
* **Logistics (Products):** The product **"Hat"** takes the longest to deliver (averaging 9 days), whereas **"Wallet"** and **"Glasses"** enjoy the fastest delivery times (7 days).

---

### **Final Recommendations**

* **Market Expansion:** Since KSA and Iraq are driving the majority of the revenue (~$8.4M combined), allocate a higher marketing budget to these regions to maximize ROI, while running targeted promotions in EGY ($1.4M) to boost its market share.
* **Payment Infrastructure:** Given that 42% of revenue flows through "Hawala", ensure that the operational logistics and accounting systems for this payment method are highly secure and streamlined to avoid any cash flow bottlenecks.
* **Logistics Optimization:** Investigate the supply chain for "Hats" to understand why it takes an extra day (9 days) compared to the 8-day average. Reducing this delay will align it with the company's standardized delivery SLA.
* **Inventory Focus:** Ensure that high-volume products (Jeans, Ties, and Bags) and top-selling sizes (XL and M, which generate over $3.6M each) are always fully stocked to prevent stockouts and missed revenue opportunities.
