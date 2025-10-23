# Quantium Customer Segmentation & Store Trial Analysis with R

## Project Overview  
This project, completed as part of the Quantium Data Analytics Virtual Experience Program via Forage, uses transactional data to:  
- Understand chip-category purchasing behaviour across customer segments.  
- Identify high-value customer segments (by Lifestage and Affluence).  
- Evaluate the impact of a new store layout trial (stores 77, 86, 88) via uplift testing.  
- Deliver strategic, data-driven recommendations to the Category Manager.

---

## Business Objective  
To provide the Category Manager with actionable insights into who spends on chips, why they spend, and whether a store layout trial should be scaled—all grounded in the metrics of total sales revenue, number of customers, and average transactions per customer.

---

## Project Workflow  
I carried out the following tasks for this project-

### 1. Business Understanding  
- Defined the business problem and key questions: who are our best customers, what drives their spending, and did the layout trial work?  
- Set measurable objectives aligned to commercial outcomes.

### 2. Data Understanding  
- Imported purchase behaviour and transaction datasets.  
- Established a data dictionary and profile of variables (Lifestage, Premium Customer, brand, pack size, etc.).  

### 3. Data Preparation  
- Cleaned and merged datasets into `merged_data.csv`.  
- Created derived fields (e.g., pack size and brand name).  
- Structured customer-level and store-level metrics.

### 4. Exploratory Data Analysis (EDA)  
- Analysed key trends by Lifestage and affluence segments.  
- Visualised distribution of spend, transaction size and pack size preferences.

### 5. Customer Segmentation  
- Derived customer segments using spend, frequency and size metrics.  
- Profiled segments and identified high-value groups (Older Families, Young Professionals, Premium & Budget Affluent).

### 6. Store Trial Performance Analysis  
- Matched trial stores (77, 86, 88) with control stores using correlation/magnitude distance.  
- Tested store performance during the trial period (Feb – Apr 2089) on total sales, customers and transactions per customer.  
- Visualised and interpreted results to assess uplift.

### 7. Insights & Strategic Recommendations  
- High-value segments drive chip sales—target marketing and shelf strategies accordingly.  
- Trial stores 86 and 88 show strong uplift; store 77 underperformed.  
- Recommend selective rollout, segmentation strategy and layout refinement.

### 8. Reporting & Documentation  
- Created visual deliverables (charts, tables) and a PowerPoint presentation following the Pyramid Principle.  
- Documented full analysis in RMarkdown and exported results for stakeholder review.

You can view the full notebook on Kaggle: [CUSTOMER SEGMENTATION PROJECT Notebook on Kaggle](https://www.kaggle.com/code/adebayoadebanjo/customer-segmentation-analysis-with-r)
---

