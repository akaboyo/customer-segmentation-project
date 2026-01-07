# Quantium Customer Segmentation & Store Trial Analysis with R

## Project Overview  
This project analyzes customer purchasing behavior to identify key customer segments and evaluate the performance of a new store layout trial.  
As part of Quantium’s Data Analytics program, the goal is to provide **data-driven commercial insights** and a **strategic recommendation** for the Category Manager to optimize sales performance in the chips category.

## Business Objective  
To understand customer purchasing behavior and determine which segments drive the highest sales, while also assessing the effectiveness of a new trial layout in selected stores (77, 86, and 88).  
The insights will support strategic decisions on marketing, product placement, and store expansion.

---

## Project Workflow  
I carried out the following tasks for this project-

### 1. Business Understanding  
- Defined the business problem and key questions: who are our best customers, what drives their spending, and did the layout trial work?  
- Set measurable objectives aligned to commercial outcomes.

### 2. Data Understanding  
- Imported purchase behaviour and transaction datasets.
- Installed the necessary libraries and loaded the datasets. Used readxl to load the Excel file while the read.csv function was used to load the CSV file.  
- Established a data dictionary and profile of variables (Lifestage, Premium Customer, brand, pack size, etc.).
- checked the structure and summary of the datasets.

### 3. Data Preparation  
- Cleaned and merged datasets into `merged_data.csv`.
- Visualized the cleaned TOT_SALES data. 
- Created derived fields (e.g., pack size and brand name).  
- Structured customer-level and store-level metrics.

### 4. Exploratory Data Analysis (EDA)  
- Analysed key trends by Lifestage, Premium_Customer, and purchasing behaviour segments.  
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

