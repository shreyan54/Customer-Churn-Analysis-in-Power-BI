# Call Centre -Analysis-in-Power-BI
Creating a dashboard in Power BI that reflects all relevant Key Performance Indicators (KPIs) and metrics for the buisness insights of Phone Now services


## **Project Overview**  

### **Key Features**  
- Integration of diverse data sources ( MySQL, Excel, CSV, and PDF).  
- Customer segmentation and retention analysis.  
- Defining kPis to reflect customer demographics and insights. 
- Interactive dashboards with slicers, custom panes, and drillthrough buttons for detailed analysis.  
- Advanced DAX calculations for KPIs like retention rate, churn rate and  employee hiring
- Implementation of Row-Level Security (RLS) to secure sensitive data.  

### **Technology Stack**  
- **Data Sources:** MySQL, Excel, CSV, PDF.  
- **Tools:** Power BI, Power Query, DAX.

## Overall Tasks ##

**1.  Creating a dashboard reflecting following KPI'S.**
-	Overall customer satisfaction
-	Overall calls answered/abandoned
-	Calls by time
-	Average speed of answer
-	Agent’s performance quadrant -> average handle time (talk duration) vs calls answered

**2.  Creating a dashboard using the defined KPIs to reflect customer demographics and insights.**
 The Key Indicators can be selected based on the following observations
 - Customers who left within the last month 
 - Services each customer has signed up for: phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies 
 - Customer account information: how long as a customer, contract, payment method, paperless billing, monthly charges, total charges and number of tickets opened in the categories administrative and technical 
 - Demographic info about customers – gender, age range, and if they have partners and dependents

**3. 	Creating a visualizations to represent HR data, particularly focusing on gender-related KPIs.**
-	Identify and discuss potential root causes for the slow progress in achieving gender balance at the executive management level.
-	Measures such as # of men,# of women,% hire of men and women, % employees promoted can be defined as KPIs


## **Step-by-Step Execution**  

### **1. Data Integration**   
- Connected to multiple data sources:    
  - MySQL (local warehouse data).  
  - Excel, CSV, and PDF files for supplementary data 
- Used **Power Query** for data cleaning, transformation, and merging.  

### **2. Data Standardization**  
- Ensured consistent units for analysis by normalizing data metrics.  

### **3. Data Modeling**  
- Established relationships between tables for unified modeling (star schema).

### **4. Dashboard Design**  
- Created an interactive dashboard with:   
  - Multi-page navigation for **Customer Satisfaction analysis**, **Churn analysis**, and **HR insights**.  
  - Visuals: Donut charts, bar charts, map visuals, radar charts, slicers, and matrix tables.  
  - Drillthrough buttons for deep-dives Customer demographics and service analysis.  
- Added slicer custom panes for better interactivity and filtering.  

### **5. Advanced Calculations**  
- Developed multiple DAX measures:  
  - churn rate, total charges , Employee performace.
  - Trend in hiring , customer satisfaction rate.


## **Final Output**  

### **Screenshots**  

### **Call Data Overview Dashboard**  
![Call Data Overview](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20dashboard.png)  

### **Churn Analysis Dashboard**  
![ChurnAnalysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/product.png)  

### **Customer Risk Analysis Dashboard**  
![Risk Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/product.png)  


### **HR Insights Dashboard**  
![HR1 Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20map.png)  

![HR2 Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/light%20dashboard.png)  

## **Key Findings** 

1.	Churned Customers: Customers with higher monthly charges and lower service utilization, especially in critical areas like tech support and online security, displayed a higher tendency to leave.
2.	Demographic Trends: Churn rates appear higher among younger customers without partners or dependents, suggesting lower perceived commitment.
3.	Service Utilization: Customers subscribed to multiple services (e.g., phone + streaming or internet) tend to stay longer, highlighting the value of bundling services.

## **KPIs Defined To better monitor and reduce churn, I recommend the following KPIs**

-	Churn Rate: Percentage of customers lost in the last month.
-	Average Monthly Revenue Per User (ARPU): Monthly charges from churned customers.
-	Service Penetration: Services adopted by retained vs. churned customers.
-	Tenure Analysis: Average customer lifespan before churn.
-	Support Engagement: Number of tickets (administrative/technical) raised vs. resolved for churned customers.

## **Key Learnings**  
  
-	Demonstrated expertise in data visualization through the creation of Power BI dashboards that effectively conveyed KPIs, showcasing the ability to respond to client requests with well-designed solutions.
-	Strong communication skills reflected in the concise and informative communication with engagement partners, delivering valuable insights and actionable suggestions based on data analysis.
-	Leveraged analytical problem-solving skills to examine HR data, particularly focusing on gender-related KPIs, and identified root causes for gender balance issues at the executive management level, highlighting a commitment to data-driven decision-making.
 

