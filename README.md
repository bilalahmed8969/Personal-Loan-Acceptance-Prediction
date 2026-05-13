# Personal-Loan-Acceptance-Prediction
Banks use direct marketing campaigns to promote products like personal loans, but contacting every customer is costly and inefficient. In this dataset, only 11.7% of customers accepted the loan offer, meaning nearly 9 out of 10 calls produced no result.
The objective of this project is to predict whether a customer will accept a personal loan offer using their demographic, financial, and campaign-related information. This allows the bank to focus resources on high-probability customers, reduce wasted outreach, and improve overall campaign performance.

The Logistic Regression model achieved a ROC-AUC of 0.91, successfully identifying 81% of actual loan acceptors. Below are the key takeaways from the analysis.
Call duration matters most. Customers who accepted the offer had calls lasting more than twice as long as those who declined. Longer conversations reflect genuine interest and are the strongest single predictor of acceptance.
Students and retired customers are the best targets. These two groups converted at 28.7% and 22.8% respectively — significantly above the 11.7% average. Campaigns directed at these segments will yield the highest return.
Single and tertiary-educated customers are more receptive. Single customers convert at a 48% higher relative rate than married customers. Tertiary-educated customers convert at nearly twice the rate of those with primary education.
Prior campaign success is the most reliable lead qualifier. Customers who had a positive outcome in a previous campaign converted at around 65% in the current one. Re-engaging this group should be the first priority of any campaign.
Fewer contacts are better. Customers who accepted were contacted an average of 2.14 times, while those who declined were contacted 2.85 times. Repeated follow-ups beyond 3 attempts are unlikely to add value.
Higher balance customers are more likely to accept. Accepted customers had an average balance of €1,804 compared to €1,303 for non-acceptors. Pre-filtering leads by account balance above the median can enrich the quality of the outreach list.
In summary, the model provides a practical and interpretable tool for targeting the right customers. Combined with the segment insights above, the bank can significantly improve campaign efficiency without increasing budget.
