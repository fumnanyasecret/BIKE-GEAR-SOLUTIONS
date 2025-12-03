# BIKE-GEAR-SOLUTIONS
Bike Gear Solutions (Retailer specializing in bike racks and cycling accessories across various Countries)  

<img width="238" height="129" alt="image" src="https://github.com/user-attachments/assets/e89cf630-cc95-4dd5-9cd2-2a45005371b9" />
<img width="140" height="124" alt="image" src="https://github.com/user-attachments/assets/8b9261e2-2ef4-43b3-acb6-288a2dbffb4d" />
<img width="101" height="116" alt="image" src="https://github.com/user-attachments/assets/5afd60c8-3b1a-454c-945e-82be15c99f37" />
<img width="101" height="115" alt="image" src="https://github.com/user-attachments/assets/9ab7c079-498f-4df3-8811-4c61ef5639a2" />
<img width="109" height="89" alt="image" src="https://github.com/user-attachments/assets/09974c21-8b2b-42d5-bd11-6d2a63a64a93" />
<img width="119" height="152" alt="image" src="https://github.com/user-attachments/assets/b09b09d8-90ab-4948-8700-1ea2a0de5bac" />

BIKE GEAR SOLUTION PROJECT
A data-driven analysis project using Microsoft Excel to drive sales Optimization, through Data-Driven Analysis
# 🚲 Bike Gear Solution: Sales Optimisation  
### *Exploratory Data Analysis using Microsoft Excel*

---

## 📃 Problem Statement 
Bike Gear Solution is a **multinational retailer in the cycling accessories market** facing strategic blind spots in understanding its regional revenue performance, demographic appeal, product demand, and seasonal trends.  
Without a clear view of its highest-performing regions and products segments, the company risks misallocating resources and missing growth opportunities.  
This project applies **Exploratory Data Analysis** and **visualisation** to reveal:  
 🔺Revenue distribution by Region 🗾  
 🔺Which age group does our product mostly appeal to 👥  
 🔺Product popularity 👑  
🔺Sales Seasonality 📉 
 
By merging data cleaning, Data analysis, pivot table and dashboard storytelling, this project transforms raw data into a roadmap for smarter growth and retention.  

---

##  Requirements to be uncovered
1. Analyse which countries or states generate the most revenue 
2. Group the customers into age agroups 'young adult' and 'Adult' 
3. Assess how different subcatergories perfom in terms of sales volume 
4. Identify trends in sales across different times of the year and correlate them with holidays and cyling season

---

## 🗂️ Data Description  

| ORDER Table | Description |
|--------|--------------|
| `Date` | Full date of transaction |
| `Day` | Numeric day value of the transaction|
| `Month` | Name of month when the order was placed|
| `Year` | Four-dight year of transaction |
| `Customer_Age` | Age of the customer at the time of purchase |
| `Age Group` | Customer age group 'young adult' or 'Adult' |
| `Customer_Gender` | Gender of the customer (e.g., M for Male, F for Female |
| `Country` | Country where the customer is located|
| `State` | State or province within the country |
| `Product category` | High-level grouping of the products (e.g., Accessories|
| `Sub_Category` | More specific classification of the product (e.g., Bike racks, helmet) |
| `Product` | Name or model of the product purchased (e.g., Hitch Rack-4-Bike) |
| `Order_Quantity` | Number of units ordered |
| `Unit_Cost` | Cost of the business for one unit of the product|
| `Unit_Price` | Selling price of one unit |
| `Profit` | Earnings from the sale after subtracting cost |
| `Cost` |Total cost of the transaction |
| `Revenue` | Total income from the transaction |

📄 *Raw data sourced from Excel files was well imported and cleaned for analysis.*

---

## ⚙️ Project Workflow  

1. **Data Collection & Preparation** – Imported and Cleaned sales transaction data, imcluding region,product,subcategories,dates,customer demographics, and profit figures. 
2. **Exploratory Data Analysis (EDA)** – Analysed trends in revenue, unit sold, profit by geograpical location,age group and time using Excel formulars, pivot tables and charts.
3. **Insight Generaion** – Segemented customers into age groups, compared regional performance and assessed subcategory sales volume to identify top-performing segments.  
5. **Reporting & Visualization** – Created a dynamic Excel dashboard using pivot charts and slicers to visualise KPIs, sales trends and category-level inights
6. **Recommedations** - Delivered clear, data-driven recommendations on which regions to prioritize, which demographics to targert and how to plan for seasonal peaks.

---
**Imported clean Data**
<img width="933" height="367" alt="image" src="https://github.com/user-attachments/assets/29215fb5-9f52-4974-a477-76bf0e76d97c" />

---
**Pivot Tables**  
*Sum of VALUES*  
 <img width="182" height="117" alt="image" src="https://github.com/user-attachments/assets/b65a6df9-7945-4697-bf55-350c32de1514" />
 

A. Analyse which countries or states generate the most revenue  
 <img width="184" height="131" alt="image" src="https://github.com/user-attachments/assets/4696fb93-db02-4c2c-ae50-557e590a80fc" />

B.Assess how different subcatergories perfom in terms of sales volume  
 <img width="346" height="302" alt="image" src="https://github.com/user-attachments/assets/570cc233-8b75-40ce-97b0-71050ee34321" />

 ---
 **DashBoard**  
 <img width="863" height="308" alt="image" src="https://github.com/user-attachments/assets/7930d6b3-590d-4c34-ab60-d7151e417246" />

---
**Filtered dashboard by age_group 'young adult' ('=IF([@[Customer_Age]]<18,"young adult", "Adult")  
<img width="868" height="307" alt="image" src="https://github.com/user-attachments/assets/d6c92073-7c30-41e5-b1f9-29a7d7717e13" />

**Filtered dashboard by age_group 'Adult' ('=IF([@[Customer_Age]]<18,"young adult", "Adult")  
<img width="875" height="310" alt="image" src="https://github.com/user-attachments/assets/926e8ab3-1ad4-4fdf-97b8-78af6032ecdd" />  

### Dashboard KPIs
Total Transaction: 113,058k  
Total Quantity: ~1,346,911  
Total Cost: 52,950,696M  
Total Revenue: 95,021,171M   
Total Profit: 42,070,475M    

### Trends & Insights
1️⃣ Profit peaked in December, 2015 (1.8M) Seasonal times are December and June  
2️⃣ Top Sub_Categories: Road bikes, mountain bikes and helmet  
3️⃣ Country Leaders: United States, Australia and United Kingdom has the most customers  
4️⃣ Young Adult vs Adult Revenue: 819,240k vs 94.2M  
5️⃣ Revenue peaked in December,2015 (4.2M)  

### Focus Areas and Key Insights
1️⃣ Revenue Drivers - 70% of revenue from Bikes, 20% of revenue from accessories only 10% from clothing  
2️⃣ Geographical location - United States of America lead revenue generated  
3️⃣ Sales Performance - 'Young Adult'do purchase much products(Sales should be focused on 'Adult' <18years)  
4️⃣ Seasonality- More sales in December and June — requires strengthened customers retention   
5️⃣ Feedback Focus -Review marketing strategy during holidays, summer and spring  
6️⃣ Product category Growth - Improve clothing and accessories offers, check pricing and fix operational barriers    

### 📈 Recommendations
1️⃣ Double down with more commitment on Top Category by investing in Bike product innovation  
2️⃣ Optimise discount strategy by capping at ≤15% for sustainable margins  
3️⃣ Run bundle offers and promotion advert for Accessories and clothing.  
4️⃣ Enhance product quality by strengthening supplier and quality control processes.  
5️⃣ Reward loyal regional customers through personalised offers for USA and Australia.  
6️⃣ Scale regional campaigns by prioritising Canada, France and Germany.   
7️⃣ Target 'Young Adult' customers by market survey to know their interest of product purchase.  


### 🧰 Tool  
Tool used  
 1️⃣Excel - To effectively format the dataset before converting to CSV and subsequently importing it into PostgreSQL for analysis  

⚠️ Disclaimer  
This project is for educational and portfolio demonstration only. Data is simulated and does not represent any real organisation.  

### 🔗 Connect With Me  
Ifunanya R. Uzokwe  
📩 Uzokweifunanya10@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/Ifunanya-uzokwe/)    
💻 [GitHub](https://github.com/fumnanyasecret)    

















