
Brazilian E-Commerce Data Analysis (Olist)
Problem Statement
This project explores the Brazilian E-Commerce Public Dataset by Olist, with the goal of uncovering actionable insights into customer behavior, product trends, geographic patterns, seller performance, and payment methods. These insights can help improve marketing strategies, logistics, and overall customer experience.

Dataset
The dataset is available on Kaggle - Brazilian E-Commerce Public Dataset by Olist. It contains data across multiple dimensions:

Orders: Timestamps, status, delivery dates, etc.

Customers: Demographic data (state, city, zip code).

Products: Category, dimensions, weight, and pricing.

Sellers: Seller location and performance metrics.

Payments: Payment types, installment plans, and values.

Reviews: Review scores, comments, and timestamps.

Tasks Performed
1. Data Exploration and Cleaning
Loaded and merged relevant datasets.

Handled missing values using backfilling and forward filling.

Ensured correct data types and cleaned inconsistencies.

2. Time-Series Analysis
Analyzed order volumes over time.

Performed seasonal decomposition to identify trends and seasonality in monthly orders.

3. Geographic Analysis
Visualized customer and seller locations by state and city.

Identified regional patterns and high-activity zones.

4. Product Analysis
Analyzed the popularity of product categories.

Explored the relationship between price, weight, dimensions, and sales.

Identified top-selling product types.

5. Customer Behavior Analysis
Calculated metrics like total revenue per customer, order frequency, and average order value (AOV).

Applied KMeans clustering to group customers by behavior.

6. Seller Performance Analysis
Evaluated sellers based on order volume, delivery times, and customer reviews.

7. Payment Analysis
Analyzed usage of different payment types and installment options.

Explored how payment methods affect purchasing behavior.

8. Data Visualization
Created a wide range of visualizations using Matplotlib and Seaborn:

Bar charts

Line plots

Scatter plots

Histograms

Time series visualizations

Cluster plots

Tools and Libraries
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Statsmodels

How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/olist-ecommerce-eda.git
cd olist-ecommerce-eda
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Olist_EDA.ipynb
Key Insights
Monthly orders show trends and seasonality aligned with promotions and holidays.

Urban areas, particularly in the Southeast region of Brazil, show higher purchasing activity.

A few product categories dominate the sales volume.

Installment-based payments are common and correlate with higher-value purchases.

Customer segmentation reveals valuable behavioral clusters for personalized marketing.

Outcome
This analysis provides the business with:

A clearer picture of who the customers are and how they shop.

Recommendations for inventory, promotions, and targeted advertising.

Insights into seller operations and potential areas for service improvement.

An understanding of how different payment methods impact customer spending.

License
This project is released under the MIT License.

Acknowledgements
Dataset: Olist - Kaggle
