# Quantium Data Analytics: Category Review (Chips) & Store Trial Evaluation

## Objective
To analyze customer purchasing behaviors and evaluate the commerical impact of new trial store layouts using transaction datasets. This porject involved extensive data wrangling, feature engineering, and statistical A/B testing to provide actionable reccomendations for catageory management.

## Tools & Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, SciPy
* **Techniques:** Data Wrangling, Text Analysis, Feature Engineering, A/B Testing, Hypothesis Testing, Pearson Correlation.

## Methodology & Key Findings

### 1. Data Preprocessing & Feature Engineering (Process_Merge.ipynb + QVI_Analysis.ipynb)
* **Data Cleansing:** Standardized temporal offsets, resolved missing time-series data, and performed text analysis on product nomenclature to isolate target product categories (potato chips).
* **Anomaly Detections:** Identified and removed commercial outliers skewing aggregate sales metrics.
* **Feature Extractions:** Engineered new categorical and numerical features from raw text strings, including 'PACK_SIZE' and consolidated 'BRAND' hierarchies.
* **Data Integrations:** Executed relational joins to merge transaction logs with customer loyalty datasets for a holistic view of purchasing behavior.

### 2. Store Trial Evaluation (A/B Testing, Store_xx_Analysis.ipynb)
* **Benchmark Establishment:** Designed a programmatic approach to endentify optimal control stores for three tral locations (Stores 77, 86, and 88) using Pearson correlations based on historical monthly sales and customer foot traffic.
* **Performance Measurement:** Evaluated the trial period against the control group, utilizing statistical hypothesis testing to determine the significance of changes in total sales revenue and average transactions per customer.
* **Commerical Insight:**
* **Expanding the Layout:** Based on the significant lift in Store 77’s performance, we recommend rolling out the new ‘Chips’ category layout to all stores in the region to maximize revenue and foot traffic, expecting that close to 2 out of 3 stores will experience a similar increase in revenue and foot traffic
<img width="959" height="569" alt="image" src="https://github.com/user-attachments/assets/f8bf41f7-bc48-4ab4-a748-ddad729042ac" />
<img width="959" height="569" alt="image" src="https://github.com/user-attachments/assets/d5447da9-6356-46da-bda6-bf09c1af42a4" />

* **Targeted Marketing:**Focus promotional activity on Mainstream Young/Mid-age Singles and Couples, as they represent the highest value makeup of the Mainstream tier.
<img width="984" height="647" alt="image" src="https://github.com/user-attachments/assets/611d8dce-1bbc-4059-a2a8-56015bdf9e88" />

* **Maintain Product Variety:** Continue prioritizing the 'volume' segments (families) through multi-buy offers to maintain category loyalty.
<img width="984" height="647" alt="image" src="https://github.com/user-attachments/assets/4467d054-888a-470b-bfcc-b0d272a47da6" />


