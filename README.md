# E-Commerce Product Quantity Sold Prediction

In e-commerce, understanding seasonal sales trends and best-selling products is critical to business strategy. However, companies often struggle with predicting sales, determining factors that influence sales (discounts, product categories, locations), and optimizing stock and marketing. Complex sales data requires in-depth analysis to identify buying patterns, determine high-demand products, and devise more effective pricing strategies.


Goals:  
- This project aims to analyze sales trends
- Identify best-selling products
- Build an accurate prediction model.


Insights:  
- Lowest Sales: February (~59,751) → Possible post-holiday effect.
- Highest Sales: November (~307,649) → Maybe affected by major shopping events (Year End Sales).
- Significant spike in March, then stable trend until August.
- Increased from September, peaked in November, then dropped slightly in December.
- Highest Sales: Canon imageCLASS 2200 Advanced Copier (~61,599)
- Lowest Sales: High Speed Automatic Electric Letter Opener (~17,030).
- Copiers and binding systems dominated the sales which is a high demand for office equipment.
- Highest Quantity Sold: Staples (215 units)
- Lowest Quantity Sold: Staple-based wall hangings (62 units)
- Products with high quantity sold are generally basic office supplies (staples, paper, envelopes).
- Random Forest and XGBoost have the best performance, with low MAE & RMSE and R² close to 1.
- Linear Regression is less suitable, as the R² is only 0.13, indicating this model cannot capture data patterns well.
- Gradient Boosting is quite good, but still inferior to Random Forest and XGBoost in terms of error and accuracy.


Conclusion:  
- XGBoost and Random Forest are the best models for predicting the product quantity sold because they give very accurate results with a small error!

If you have any suggestions or feedback, please don't hesitate to contact to me in direct message on LinkedIn and Email : mfkriazh57@gmail.com and http://www.linkedin.com/in/muhammad-fakhri-azhar

#Python #EDA #MachineLearning #SupervisedLearning #data-science
