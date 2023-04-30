## Context gathering

Questions (for stakeholders):
- What stakeholders need: stakeholders ask to analyze the data to be used to make special offers for customers, and they also need presentations, and dashboard of the analysis results .

- Why stakeholders need the analysis: qualitative research is not enough to make decisions, they need arguments based on data.

- What research has been done before, and how can these findings inform current research: No, this is new research. Be as detailed as possible when describing how your solution might work.

- What time frame should be considered in the analysis: all periods covered in the data source.

Question (for myself):
- Who are the stakeholders, who needs the information, who will use the end result: Product Manager - responsible for the user experience.

- What kind of dataset do I need: data that includes customer transactions.

- Where and how do I get the dataset: data engineer.

- When the results of this analysis are needed: deadline 26/4/2023

## Summary

**Stakeholders**: Product Manager

**Define the problem**:
   - Analyze data to be used to create special offers for customers,
   - The entire period covered by the data source,
   - Presentation
   - Dashboards

**How do I solve the problem**:

   - Objective: Segmentation of users based on their consumer profile
   
   - Question:
       - What segments are likely to make seasonal purchases? Are these users likely to make repeat purchases?
       - What segments are likely to make multiple orders over a long period of time?
       - What segments make a lot of purchases in a short period of time?
       - What kind of segments create large orders? What do you get about their consumption patterns?
       - What kind of segments make the few orders? What do you get about their consumption patterns?
       - What are the differences in product preferences among consumer segments?
       
   - Analyzing datasets:
       - Data Overview;
           - Loads all libraries
           - Load datasets
           - View general dataset information
           - Check data quality:
               - Check for missing values,
               - Duplicate values,
               - Data types,
               - Column name,
               - Value of each column,
               - Possibility of outliers
        - Data Pre-processing;
            - Improve data quality (if any):
               - Fixed column naming,
               - Fixed duplicate values,
               - Fixed missing values,
               - Adding columns (such as columns that contain the value of the date, day, month, year of the transaction),
               - Fixed outliers
         - EDA;
           - Store metrics:
               - Revenue trends,
               - Average purchase size and its trend,
               - trend from month to month on average revenue per user
           - Find out the answers to the questions in the "Questions" section
           - Writing findings, insights, and recommendations.
           
       - Hypothesis testing
           - Using the independent t-test method, or Mann-Whitney (if the data is not normally distributed) to test hypotheses about differences in the frequency and average order size for different user segments.
           - Knowing whether or not there is a difference from the statistical test results:
               - p-value (probability value) > alpha (error rate) there is no significant difference, or
               - p-value (probability value) < alpha (error rate) there is a significant difference.
           
       - Machine Learning (if needed)
           - Using clustering methods (unsupervised machine learning) to study and visualize each customer segments
           
       - General Conclusion
       
       - Presentation
           - Insight from analysis results
           - Explain more about the insight based on the data
           - Recommendations based on that insight
        - Dashboards
           - Data content:
               - User categories
           - Parameters used to group data:
               - Date and time of customer transaction,
               - Customer segments
           - Graph, dashboard control, and their arrangement:
             [Dashboard](https://docs.google.com/document/d/1sh54NApUU_fGCVZsVX1G7ah6AOV34smWUrlLT-hRDwA/edit?usp=sharing)
