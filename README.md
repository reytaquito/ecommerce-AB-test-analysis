# E‑commerce A/B Test Hypotheses Prioritization & Analysis
This repository contains the end‑to‑end workflow for prioritizing marketing hypotheses, running an A/B test, and analyzing its results for a large online retailer.  

Key objectives:

1. **Hypotheses prioritization** based on expected impact and effort.  
2. **A/B test execution** to validate the top hypothesis.  
3. **Visualization** of cumulative revenue, average order size, and conversion rates per group.  
4. **Anomaly detection** in user order counts and order prices.  
5. **Statistical inference** on differences in conversion and order size, both on raw and filtered datasets.  
6. **Decision recommendation**: choose a winner group, stop test for no difference, or continue testing.

## 📈 Analyses & Visualizations

1. **Cumulative Revenue by Group**  
   - Plot of accumulated revenue over time for control (A) vs. variant (B).  
   - Conclusions & hypotheses on revenue trends.

2. **Cumulative Average Order Size by Group**  
   - Plot of average order value accumulation.  
   - Interpret differences and possible causes.

3. **Relative Difference in Cumulative Average Order Size (B vs. A)**  
   - Percentage gap chart.  
   - Insights on magnitude and stability of effect.

4. **Daily Conversion Rate per Group**  
   - Conversion = orders ÷ visits per day.  
   - Line chart comparison and descriptive conclusions.

5. **Scatter Plot: Number of Orders per User**  
   - Identify heavy purchasers vs. occasional buyers.  
   - Conclusions & detection of outliers.

6. **Order Count Anomaly Detection**  
   - 95th and 99th percentiles of orders per user.  
   - Thresholds beyond which an order count is considered anomalous.

7. **Scatter Plot: Order Prices**  
   - Distribution of individual order values.  
   - Conclusions on pricing behavior.

8. **Order Price Anomaly Detection**  
   - 95th and 99th percentiles of order price.  
   - Definition of anomalous order values.

9. **Statistical Significance Tests (Raw Data)**  
   - Conversion difference (two‑sample z‑test).  
   - Average order size difference (t‑test).

10. **Statistical Significance Tests (Filtered Data)**  
   - Repeat conversion and order size tests after excluding anomalies.

11. **Decision Making**  
   - Recommendation to:  
     1. Stop test and choose a leader.  
     2. Stop test—no significant difference.  
     3. Continue test for more data.
