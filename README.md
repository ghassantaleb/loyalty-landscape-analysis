# loyalty-landscape-analysis

# Overall Description of the Analysis

This analysis aimed to understand customer behavior and segment the customer base for targeted marketing using the marketing campaign dataset. The analysis involved the following key steps:

## Data Preparation:
 The initial dataset was loaded, cleaned, and preprocessed. Missing values were handled, and the 'Dt_Customer' column was converted to datetime format. Feature engineering was performed to calculate customer tenure.

## RFM Segmentation: 
Rency, Frequency, and Monetary (RFM) analysis was conducted to segment customers into distinct groups based on their purchase behavior. Customers were categorized into Champions, Loyal Customers, Potential Loyalists, At Risk, and Lost Customers based on their RFM scores. **This segmentation approach was ultimately favored due to its interpretability and relevance to the business context.**

## K-means Clustering: 
K-means clustering was also explored as an alternative segmentation method. **Parameters were fine-tuned to optimize cluster formation and achieve better results.** However, RFM segmentation proved to be more suitable for this specific dataset and analysis goals.

## Customer Profiling: 
Detailed customer profiling was performed for each RFM segment to understand their characteristics, including age, marital status, number of kids, and income. Descriptive statistics and visualizations were used to analyze the distributions of these features within each segment.

## Income Standardization: 
Income data was standardized to ensure comparability between segments and refine the analysis of income distributions. The standardized income analysis revealed more pronounced differences between segments and provided a more accurate basis for targeted marketing.

## Insights and Implications: 
The analysis yielded valuable insights into the characteristics and behavior of different customer segments. These insights can be leveraged to develop targeted marketing strategies, personalize communication, and improve customer relationships.

# Key Findings:

**RFM segmentation effectively categorized customers into meaningful groups based on their purchase behavior.**

**K-means clustering was explored but ultimately deemed less suitable for this particular dataset and analysis goals.**

**Champions, Loyal Customers, Potential Loyalists, At Risk, and Lost Customers exhibited distinct characteristics and income profiles.**

### Champions: 
This segment represents the most valuable customers, characterized by high recency, frequency, and monetary value, as well as higher income levels.
### Loyal Customers: 
This segment exhibits consistent purchase behavior and moderate income levels.
### Potential Loyalists: 
This segment shows potential for increased engagement and has slightly lower income levels.
### At Risk: 
This segment has decreased engagement and requires targeted re-engagement strategies.
### Lost Customers: 
This segment has churned and had significantly lower income levels after standardization.
